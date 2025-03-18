## Web 2. Dönem 1. Sınav Teorik Çalışma Soruları ##
1.  **Model Binding işlemi nedir?**
    Model Binding, formdaki input elemanlarının name değerleri ile aynı olan bir modelin özellik isimleri ile eşleştirilmesi veya bağlanması işlemidir.

2. **wwwroot klasörü ne işe yarar ve içeriğinde neler bulunur?**
    wwwroot klasörü, proje içerisinde kullanılan her türlü statik (CSS, JS, resim, video vb.) dosyanın bulunduğu klasördür. Bu klasöre eklenen dosyalar tarayıcıda görüntülenebilir.

3.  **Action Metottan View'e Veri Aktarım yolları nelerdir?**
    Action metottan view'e veri aktarımı ViewBag, ViewData ve TempData kullanılarak yapılabilir.

4. **MVC tasarım deseninde controller katmanı ne işe yarar?**
   Controller katmanı, içinde barındırdığı action metotları ile birlikte tarayıcıdan gelen sayfa isteklerini (URL) yönetir, view ve model katmanları arasındaki bağlantıyı sağlar ve projenin iş sürecini kontrol eder.

5. **Action metot nedir ve nasıl tanımlanır?**
   Action metotlar, controller sınıfında public olarak tanımlanan tüm metotlardır. Her bir controller sınıfı için Index() adlı metot varsayılan action metodudur.

6. **Index() metodu nedir ve ne işe yarar?**
   Index() metodu, her bir controller sınıfı için varsayılan action metodudur. Action belirtilmediğinde çalışacak olan metottur.

7. **Action metotlar hangi türde değerler döndürebilir?**
   Action metotlar, View, dosya (resim, video vb.), JSON, string ve int gibi C# veri tiplerinde değer döndürebilir veya bir başka controller/actiona yönlendirme yapabilir.

8. **MVC tasarım deseninde view katmanı nedir ve nasıl tanımlanır?**
   View katmanı, kullanıcının göreceği tüm arayüzlerin oluşturulduğu katmandır. Bu katmanda yer alan dosyalar .cshtml uzantılı olmalıdır.

9. **Aşağıdaki bölümlerin işlevlerini kısaca yazınız.**
    a. Model: Geliştirilen uygulamada kullanılacak olan verilerin özelliklerinin tanımlandığı katmandır.
    b. View: Kullanıcının göreceği tüm arayüzlerin oluşturulduğu katmandır.
    c. Controller: Tarayıcıdan gelen sayfa isteklerini yönetir, view ve model katmanları arasındaki bağlantıyı sağlar ve projenin iş sürecini kontrol eder.

10. **Bir controller birden fazla view döndürebilir mi? Açıklayınız.**
    Evet, bir controller birden fazla action metot bulundurabilir ve dolayısıyla birden fazla view döndürebilir.

11. **Yeni bir view eklemek için hangi adımlar izlenir?**
    Yeni bir view eklemek için, Views klasörü altına bu view dosyasıyla ilişkili controller sınıfı adıyla bir klasör oluşturulur. Oluşturulan klasör seçili iken New File butonuna tıklanır ve view dosyasına ilişkili action metodunun ismi verilerek .cshtml uzantılı dosya oluşturulur.

12. **Razor View Motoru nedir ve nasıl çalışır?**
    Razor View Motoru, view dosyaları içerisinde sunucu taraflı kodlar ile HTML kodlarının bir arada kullanımını sağlayan bir yapıdır. @ karakteri ile başlayan ifadeleri sunucu taraflı çalıştırır ve HTML çıktısı oluşturur.

13. **_Layout.cshtml dosyası ne işe yarar ve nasıl kullanılır?**
    _Layout.cshtml dosyası, tüm sayfalar için ortak bir şablon yapısı tanımlamak için kullanılır. Bu dosya içerisindeki @RenderBody() yönergesi ile bu şablon dosyasını kullanan sayfaların içeriğinin görüntüleneceği kısım tanımlanır.




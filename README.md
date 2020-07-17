# Courser-Managment-Systems
Courser Managment Systems(ASP.NET/C#/SQL) 
Proje başlatıldığında haberler yüklenirken çok az bir gecikme olmaktadır bunun sebebi fazla haber çekmemde ve depolamamdadır.
Uygulama RSSparsing.aspx sayfası ile başlayıp haberlerin rss ile çekilip veritabanına bu sayfada yazılmaktadır.
bu sayfadan ana sayfaya bağlanmaktadır.Anasayfa ve RSSparsing.aspx sayfası her 30 sniyede bir resfresh edilmektedir.
Loglar uygulama konumunda mylog.txt dosyasında tutulmaktadır.
uygulamada ki döviz kurları real time olarak merkez bankasının yayınlamış oldugu xml formatında çekilmektedir.
Çekilen haberler NewsRss.cs classı ile çekilmektedir ve RSSparsing.aspx sayfasında List ve arrayListte tutulmaktadır.
Haber kategorilere ayrılmış olup veritabanında her haber kendi kategorisindeki table'a yazılmaktadır.

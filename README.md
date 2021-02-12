# Python ile web sayfalarından bilgi çekmek - Web Scraping
#### Program Tanımı
Excel dosyasında verilen sitelere giderek oradaki ürünlerin bilgilerini çeken ve liste şeklinde tekrar kaydeden bir programdır. Çıktısını *"output.xlsx"* dosyasından görebilirsiniz. (Çıktı dosyasında ekstra olarak ürünlerin toplam fiyatı da yazdırılmıştır.)

#### Kullanılan Paketler
*Python 3* ile verileri çekmek için *BeautifulSoup4* ve *Requests* kütüphaneleri tercih edilmiştir.
Verileri excel dosyasından okuyup yazmak için de *Openpyxl* kütüphanesi kullanılmıştır.

#### Proje Süreci Hakkında
Python bildiğim bir dildi fakat veri kazıma işlemleri için kullanmamıştım daha önce. Biraz araştırdıktan sonra ilgili paketlerin haricinde HTML bilgisi de gerektiğini öğrendim ve bilgilerimi tazelemek için biraz tekrar yaptım. Sayfalardaki uzun class isimleri biraz kafamı karıştırdı. Daha basit hali var mı diye tek tek kontrol ederek denedim fakat bulamadım ve uzun şekilde kullanmak zorunda kaldım. Onun haricinde fazla bir sorunla karşılaşmadım. Sık kullanmadığım modüller olduğu için nasıl kullanıldıklarını araştırdım. Biraz deneme yanılma yoluyla ilerledikten sonra sistemimi oturtmuş oldum. Bu proje sayesinde kullandığım paketleri öğrendim. İnternetten verilerin nasıl çekildiğini, ne gibi hatalarla karşılaşıldığını ve nasıl çözüldüklerine dair bilgiler edindim. Excel gibi dosyalardan verilerin nasıl çekilip işlendiğini ve tekrar aynı formatta nasıl kaydedildiğini öğrendim. Güzel bir süreçti. Kısa sürede birçok şey kattığını düşünüyorum.

#### Ek sorular
1) Ziyaret edilmesi gereken 10000 kadar çok bir url listesi olsaydı, bunu yapmak saatler alırdı. Peki bu süreci hızladırmak için neler yapılabilir?
>Veri çekme işlemlerinin süresi internet hızına, kullanılan paketlere ve işlem sayısına bağlı olarak değişmektedir. Burada süreci hızlandırmak için multi-threading/proccesing programlamadan yararlanılabilir. İşlemleri tek tek yapmaktansa aynı anda birden fazla işlem yürütülebilir ve süreyi indirebiliriz.

2) API nedir ve nasıl çalışır?
>API'ları kısaca uygulamalar arasındaki haberleşmeyi sağlayan arayüzler olarak nitelendirebiliriz. Türkçe olarak baktığımızda Uygulama Programlama Arayüzü olarak karşımıza çıkıyor. Bir uygulamanın/servisin sahip olduğu özelliklere izin verildiği kadarına dışarıdan erişilmesini sağlar.

>Çalışma prensibi olarak da request<->data şeklinde ifade edebiliriz. Uygulamalar sunucuya istekte bulunurlar. İsteğin içerisinde ne yapılması gerektiğini açıklayan keywordler ve parametreler vardır. Sunucu bu bilgileri alarak gerekli işlemleri yapar ve istenilen verileri geri döndürür. Bu işlemler API ile gerçekleşmektedir ve bu şekilde haberleşmiş olurlar.

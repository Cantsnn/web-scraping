# Python ile web sayfalarından bilgi çekmek - Web Scraping

#### Kullanılan Paketler
*Python 3* ile verileri çekmek için *BeautifulSoup4* ve *Requests* kütüphaneleri tercih edilmiştir.
Verileri excel dosyasından okuyup yazmak için de *Openpyxl* kütüphanesi kullanılmıştır.

#### Proje Süreci Hakkında
Proje esnasında çok fazla sıkıntı yaşadığımı söyleyemem. Sık kullanmadığım modüller olduğu için nasıl kullanıldıklarını araştırdım. Biraz deneme yanılma yoluyla ilerledikten sonra sistemimi oturtmuş oldum. Python bildiğim bir dildi fakat veri kazıma işlemleri için kullanmamıştım daha önce. Bu açıdan bir deneyim katmış oldu bana. Onun haricinde HTML bilgilerimi tazelemek için biraz tekrar yaptım. Kullandığım paketleri öğrenmiş oldum. İnternetten verilerin nasıl çekildiğini, ne gibi hatalarla karşılaşıldığını ve nasıl çözüldüklerine dair bilgiler edindim.Excel gibi dosyalardan verilerin nasıl çekilip işlendiğini ve tekrar aynı formatta nasıl kaydedildiğini öğrendim.

#### Ek sorular
1) Ziyaret edilmesi gereken 10000 kadar çok bir url listesi olsaydı, bunu yapmak saatler alırdı. Peki bu süreci hızladırmak için neler yapılabilir?
>Veri çekme işlemlerinin süresi internet hızına, kullanılan paketlere ve işlem sayısına bağlı olarak değişmektedir. Burada süreci hızlandırmak için multi-threading/proccesing programlamadan yararlanılabilir. İşlemleri tek tek yapmaktansa aynı anda birden fazla işlem yürütülebilir ve süreyi indirebiliriz.

2) API nedir ve nasıl çalışır?
>API'ları kısaca uygulamalar arasındaki haberleşmeyi sağlayan arayüzler olarak nitelendirebiliriz. Türkçe olarak baktığımızda Uygulama Programlama Arayüzü olarak karşımıza çıkıyor. Bir uygulamanın/servisin sahip olduğu özelliklere izin verildiği kadarına dışarıdan erişilmesini sağlar.

>Çalışma prensibi olarak da request<->data şeklinde ifade edebiliriz. Uygulamalar sunucuya istekte bulunurlar. İsteğin içerisinde ne yapılması gerektiğini açıklayan keywordler ve parametreler vardır. Sunucu bu bilgileri alarak gerekli işlemleri yapar ve istenilen verileri geri döndürür. Bu işlemler API ile gerçekleşmektedir ve bu şekilde haberleşmiş olurlar.

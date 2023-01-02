# Seo Kontrol Listesi (Seo Check List):
- [SEO'ya Başlarken](#seoya-başlarken)
- [Teknik SEO Denetimi](#teknik-seo-denetimi)
- [İçerikler İçin SEO](#i̇çerikler-i̇çin-seo)

# SEO'ya Başlarken
> Search Console, Yandex Webmaster, Bing Webmaster Kayıtları.

> Google analytics, Hotjar, Yandex metrica.. kayıtları

> Site Haritası ve Robots.txt'yi belirlemek (Birbirleriyle bağlantılı olmalı.) Tüm webmaster toollara göndermek.

> Rakiplerinizi belirlemek. (Ücretli toollardan yararlanılabilir. 
> + Varsa sizin de eklemek istediğiniz rakipler.

> Ulaşmak istediğiniz keywordleri belirlemek. (İstemediğiniz keywordleri de belirlemek önemli.) 

> Kısa vadede trafik elde edebileceğiniz long tail keywordleri ve orta/uzun vadede ulaşabileceğiniz, ana anahtar kelimelerinizin belirlenmesi.

> Kitlenizin sorduğu soruları bulmak ve tahmin etmek önemli.Kitleniz bunları ararken sizi bulacak. Google scrape ya da kw analys toollarını tercih edebilirsiniz. <a href="keywordtool.io">keywordtool.io</a>, <a href="semrush.com">semrush.com</a>, v.b..

> İçeriklerinizi yazarken veya kontrol ederken, okuyan kişinin bir insan olduğunu unutmayın. Yazdığınız ya da denetlediğiniz içeriklerde Karanlık seo hileleri olmadığından emin olun.

> İçeriklerinizi doğru kategori ve doğru etiketlerde filtrelediğinizden emin olun.

> URL'lerinizde türkçe karakter (ç,ö,ı,ü).vb karakterler içermediğine emin olun. Yüklediğiniz belgeler ve resimler dahil.

> Kullancılara yüklediğiniz fotoğrafın neyle ilgili olduğu hakkında ipucu vermek için alt-text özelliğini kullanın.

> Yükleyeceğiniz görsellerin boyutlarını iyi ayarlayın ve optimize etmeyi unutmayın. Webp desteğinin bir çok tarayıcıya geldiğini hatırlatmakta fayda var. Ayrıca yüksek pixellere sahip görsellerini küçültmek önerilir.

> Web sitenizin hızlı açıldığından emin olun. Kullanıcı deneyimi açısından, 2.5 saniye içerisinde tüm sitenizin yüklenmiş olması gerekir.(Lazy load hariç.)
> + bu süre herhangi bir belgeye dayandırılmamıştır.

> İlgili bulduğunuz bütün web sayfalarınızı birbiri ile bağlantılayabilirsiniz. Örneğin Post sayfanızdan kategori sayfasına ya da kategori sayfasından post sayfasına `Breadcrumb` olduğundan emin olun.

>  Yazı sayfalarınız varsa, içindekiler bölümü kullanmayı denemelisiniz.


# Teknik SEO Denetimi
> Tüm sayfalarınızın https ile açıldığından emin olun. (www ya da www siz dahil)

> Mülkünüzü webmaster araçlarına doğru versiyonda kayıt ettiğinizden emin olun. Eğer web siteniz https://www şeklinde açılıyorsa ve mülkünüze http:// şeklinde kayıtlıysa hatalıdır.

> `Hreflang` işaretlemesinin doğru olduğundan emin olun.

> `Canonical` etiketini kontrol edin.

> Sayfalarınızı zengin arama sonuçlarına göre optimize edin.

> Sayfanızın derinliğini kontrol edin. (Crawl Depth.) İnsanların kaç tıklamada o sayfaya ulaşabildiği ile ilgili.)

> Yalnızca ana sayfanızın değil, tüm sayfalarınızın sayfa hızlarını test edin ve iyileştirin.

> Web sitenizdeki tüm dahili ve harici bağlantıları inceleyin. 4xx tipi bağlantıları kaldırın. 3xx tipi bağlantıları da kontrol ettikten sonra iyileştirmeyi deneyebilirsiniz.

> Dahili ve harici tüm 5xx bağlantılarınızı kontrol edin. Müdahale edebildiğiniz hataları onarın,onarılmayan linkleri kaldırın.

> Web sitenizin, mümkün olduğunca az javascriptle çalışması için, geliştiriciniz ile iş birliği yapın.

> GSC üzerinde verilen tüm uyarı ve hataları denetleyin. Bu hatalar daha az trafik elde etmenize neden oluyor olabilir.

> Tüm meta başlık ve meta açıklamalarınızı denetleyin. (Google bazı arama sonuçlarında bunları dinlemese bile, siz ne yazdığınızdan emin olun.)

> Sayfalarınızı sık sık tarayın, noindex içeren sayfalarınızı mutlaka inceleyin, noindex ile ilgili notlar alın. (İstem dışı herhangi bir nedenle trafik alan sayfalarınız noindexe düşebilir..)

> Global bir ziyaretçi kitlesine dönüştüğünüzde CDN'ye yatırım yapmayı deneyebilirsiniz.

> CDN ya da harici bir kaynak yüklemesinde, hızlı bir sonuç almak için `DNS Prefecth` kodunu kullanın. Bu sayede DNS çözümlemesi daha kısa sürede tamamlanır. Wordpress'te genel olarak bu otomatik yapılıyor ancak denetlemekte fayda var.

> Schema markuplarınızı denetleyin. Hem ürün, hem hizmet hem blog hem de bir event sayfanız varsa, hepsi için özel schema markupları olduğunu unutmayın. Schema markuplarını mutlaka zenginleştirin. Buna bağlı CTR'da yoğun bir artış görmek söz konusu olabilir.

> Statik bir xml yerine dinamik bir xml yönetimine geçmeniz önerilir. Bu sayede otomatik olarak site haritanız güncellenir. Ancak denetimi asla elden bırakmayın. İstemediğiniz bir sayfanın site haritasında yer almasası, arama sonuçlarında görünmesine neden olabilir.

> Google Analytics alarmlarını kurun. Onlarca farklı şekilde alarm kurarak, Google'ın belirlediğiniz durumlarda size mail atarak uyarmasını sağlayabilirsiniz.

> Hem mobil hem de masaüstü için CWV Optimizasyonunu yapın. (Bu konuda sadece mobil ya da sadece masaüstü optimizasyonu yapmanız yeterli gelmeyebilir. Tüm senaryolara hazırlıklı olmak için, masaüstü ve mobil Core Web Vitals optimizasyonunu yapın.



# İçerikler İçin SEO
> İçerik ürettiğiniz dilin kurallarına uygun bir içerik oluşturduğunuza emin olun.

> Hitap ettiğiniz kitleye uygun bir anlatım tarzı seçin. Ne çok bilimsel, ne de çok ilkel olmamalı.

> Yazdığınız içerikler eğer bir ürün tanıtımı v.b değilse, anlatım tarzı yorum içermesin. Yazı içinde net bir cevap kesinlikle olmalı.

> Yazı içinde, anahtar kelime çeşitliliği mutlaka olmalı. Yalnızca bir anahtar kelimeye odaklanmayın.

> İçeriği yazmadan önce anahtar kelime araştırması kadar, kullanıcıların sorduğu sorular da önemli. Kullanıcıların aradığı sorular için alternatif olarak, youtube videoları çekilmişse, altına gelen yorumlardan soru çıkarma ihtimaliniz mevcut. Mutlaka değerlendirin.

> URL'ler sayfa başlığı kadar uzun olmasın. Ne çok kısa, ne de çok uzun sayfa url leri tercih etmeyin. Nokta atışı bir url belirlediğinizden emin olun.

> Önemli yerler için kalın, altı çizgili, mark gibi metin özelliklerini kesinlikle kullanın.

> İçeriğinizi oluştururken, onları daha uzun süre tutabilecek ve aynı zamanda fayda sağlayabilecek multimedyalar oluşturun. Örneğin yazdığınız içeriği seslendirip mp3 olarak yazının başına koymak, youtube kanalına video çekip, videoyu yazı içine yerleştirmek, photoshop ile resim yaratmak, fotoğraf makinası ile fotoğraf çekip yüklemek.

> İçeriğinizi detaylandırıken heading2, heading 3, heading4 gibi başlıklarla içeriği ayırabilirsiniz.

> İçeriğinizi oluştururken, alıntı kullanmak, içeriğinizi zenginleştirebilir.

> Harici bağlantı vermek fayda sağlayabilir. Harici linkler içn yeni sekmede bağlantı verebilirsiniz.

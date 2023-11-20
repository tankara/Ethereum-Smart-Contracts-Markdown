# AKILLI KONTRATLARA GİRİŞ
**Akıllı sözleşmeler** Ethereum'un ==uygulama katmanı==nın __temel yapı taşlarıdır__. Bunlar, blok zincirinde saklanan ve =="eğer öyleyse o zaman **(if this then that)**"== mantığını izleyen ve <u>kodu tarafından tanımlanan</u>, <u>oluşturulduktan sonra değiştirilemeyen</u> kurallara göre yürütülmesi <u>garanti edilen</u> bilgisayar programlarıdır.

**"Akıllı sözleşme"** terimini **Nick Szabo** icat etti. 1994'te kavrama  [bir giriş](https://www.fon.hum.uva.nl/rob/Courses/InformationInSpeech/CDROM/Literature/LOTwinterschool2006/szabo.best.vwh.net/smart.contracts.html) yazdı ve 1996'da akıllı sözleşmelerin neler yapabileceğine dair bir [araştırma](https://www.fon.hum.uva.nl/rob/Courses/InformationInSpeech/CDROM/Literature/LOTwinterschool2006/szabo.best.vwh.net/smart_contracts_2.html) yazdı.

**Szabo**, <u>otomatik</u>, <u>kriptografik olarak güvenli süreçlerin, işlemlerin ve iş fonksiyonlarının güvenilir aracılar olmadan</u> gerçekleşmesini sağladığı bir **dijital pazar** hayal etti. Ethereum'daki akıllı sözleşmeler bu vizyonu uygulamaya koyuyor.

## Geleneksel Sözleşmelerde Güven
Geleneksel bir sözleşmenin en büyük sorunlarından biri, sözleşmenin sonuçlarını takip edecek güvenilir kişilere duyulan ihtiyaçtır.
<br>
***Örnek:***
Alice ve Bob bisiklet yarışı yapıyorlar. Diyelim ki Alice, Bob'a yarışı kazanacağına dair 10$'lık bahse girdi. Bob kazanacağından emindir ve bahsi kabul eder. Sonunda Alice yarışı Bob'un çok önünde bitirir ve açık ara kazanan olur. Ancak Bob, Alice'in hile yapmış olması gerektiğini iddia ederek bahsi ödemeyi reddeder.

Bu örnek, akıllı olmayan herhangi bir anlaşmadaki sorunu göstermektedir. Anlaşmanın koşulları karşılansa bile, anlaşmayı yerine getirmesi konusunda yine de başka bir kişiye güvenmeniz gerekmektedir.

## Dijital Otomat
Akıllı kontratları basitçe girdilerinizi bir sonuca ulaştırmaya garanti eden bir otomate benzetebiliriz.

<ol>
<li>Bir ürünü seçersiniz.</li>
<li>Otomat size fiyatı gösterir.</li>
<li>Ücreti ödersiniz</li>
<li>Otomat, doğru tutarı ödediğinizi doğrular</li>
<li>Otomat size ürününüzü verir</li>
</ol>
Otomat, <u>yalnızca tüm gereksinimler karşılandıktan sonra
</u> istediğiniz ürünü dağıtacaktır. Bir ürün seçmezseniz veya yeterli parayı girmezseniz, satış makinesi ürününüzü <strong>vermez.</strong>

## Otomatik Yürütme
Akıllı sözleşmenin temel faydası, belirli koşullar karşılandığında kesin kodu deterministik olarak yürütmesidir. Bir insanın sonucu yorumlamasını veya müzakere etmesini beklemeye gerek yoktur. Bu, güvenilir aracılara olan ihtiyacı ortadan kaldırır.

Örneğin, bir çocuk için parayı emanette tutan ve çocuğun belirli bir tarihten sonra para çekmesine olanak tanıyan akıllı bir sözleşme yazabilirsiniz. Bu tarihten önce çekilmeye çalışırlarsa akıllı sözleşme uygulanmayacaktır. Veya satıcıya ödeme yaptığınızda size otomatik olarak arabanın isminin dijital versiyonunu veren bir sözleşme yazabilirsiniz.

## Tahmin Edilebilir Sonuçlar

Geleneksel sözleşmeler belirsizdir çünkü bunların yorumlanması ve uygulanması insanlara bağlıdır. 

Örneğin, iki hakim bir sözleşmeyi farklı yorumlayabilir ve bu da tutarsız kararlara ve eşit olmayan sonuçlara yol açabilir. Akıllı sözleşmeler bu olasılığı ortadan kaldırır. Bunun yerine, akıllı sözleşmeler tam olarak sözleşme kodunda yazılan koşullara göre yürütülür. Bu kesinlik, aynı koşullar altında akıllı sözleşmenin aynı sonucu üreteceği anlamına gelir.

## Açık Kayıt
Akıllı sözleşmeler denetim ve takip için faydalıdır. Ethereum akıllı sözleşmeleri halka açık bir blok zincirinde olduğundan, herkes varlık transferlerini ve diğer ilgili bilgileri anında takip edebilir. Örneğin, birisinin adresinize para gönderip göndermediğini kontrol edebilirsiniz.

## Gizlilik Koruması
Akıllı sözleşmeler aynı zamanda gizliliğinizi de korur. Ethereum anonim bir ağ olduğundan (işlemleriniz kimliğinize değil, benzersiz bir şifreleme adresine herkese açık olarak bağlıdır), gizliliğinizi gözlemcilerden koruyabilirsiniz.

## Görünür Terimler
Son olarak, geleneksel sözleşmeler gibi, akıllı bir sözleşmeyi imzalamadan (veya başka bir şekilde onunla etkileşime girmeden) önce içinde ne olduğunu kontrol edebilirsiniz. Akıllı bir sözleşmenin şeffaflığı, herkesin onu inceleyebilmesini garanti eder.

## Akıllı Sözleşme Kullanım Örnekleri
Akıllı sözleşmeler esasen bilgisayar programlarının yapabildiği her şeyi yapabilir.

Hesaplamalar yapabilir, para birimi oluşturabilir, verileri depolayabilir, NFT'leri basabilir, iletişim kurabilir ve hatta grafikler oluşturabilirler. İşte bazı popüler, gerçek dünyadan örnekler:

<ul>
<li><a href="https://ethereum.org/en/stablecoins/">Stabil Coinler</a></li>
<li><a href="https://ethereum.org/en/nft/">Benzersiz Dijital Varlıklar Oluşturma ve Dağıtma</a></li>
<li><a href="https://ethereum.org/en/get-eth/#dex">Merkezi Olmayan Borsalar (Decentralized Exchanges-DEX)</a></li>
<li><a href="https://ethereum.org/en/dapps/?category=gaming">Merkezi Olmayan Oyunlar (Decentralized Applications-DAPPS)</a></li>
<li><a href="https://etherisc.com/">Otomatik Olarak Ödeme Yapan Bir Sigorta Poliçesi</a></li>
<li><a href="https://ethereum.org/en/developers/docs/standards/tokens/">Token Standartları</a></li>
</ul>


# ETHEREUM'a Giriş

## BlockZincir Nedir?
Blockchain, bir ağdaki birçok bilgisayar arasında güncellenen ve paylaşılan halka açık bir veritabanıdır.

**"Blok", "bloklar"** olarak bilinen kavram ardışık gruplarda saklanan <u>veri ve durumu</u> ifade eder. ETH'yi başka birine gönderirseniz, işlemin başarılı olması için işlem verilerinin bir bloğa eklenmesi gerekir.

**"Zincir"**, her bloğun <u>kriptografik</u> olarak üst öğesine referans vermesi anlamına gelir. Başka bir deyişle bloklar birbirine zincirlenir. Bir bloktaki veriler, sonraki tüm blokları değiştirmeden değişemez; bu, tüm ağın fikir birliğini gerektirir.

Ağdaki her bilgisayar, her yeni blok ve bir bütün olarak zincir üzerinde anlaşmaya varmalıdır. Bu bilgisayarlar **"düğümler"** olarak bilinir. Düğümler, blockchain ile etkileşime giren herkesin aynı verilere sahip olmasını sağlar. Bu dağıtılmış anlaşmayı gerçekleştirmek için blok zincirlerin bir fikir birliği mekanizmasına ihtiyacı vardır.

Ethereum, hisse kanıtı tabanlı **(proof-of-stake-based)** bir fikir birliği mekanizması kullanır. Zincire yeni bloklar eklemek isteyen herkesin teminat olarak Ethereum'un yerel para birimi olan ETH'yi stake etmesi ve doğrulama yazılımı çalıştırması gerekir. Bu **"doğrulayıcılar(validators)"** daha sonra diğer doğrulayıcıların kontrol edip blok zincirine ekleyeceği blokları önermek için rastgele seçilebilir. Katılımcıları mümkün olduğunca dürüst olmaya ve çevrimiçi olarak erişilebilir olmaya güçlü bir şekilde teşvik eden bir ödül ve ceza sistemi vardır.

Blockchain verilerinin nasıl karma hale getirildiğini ve ardından blok referanslarının geçmişine nasıl eklendiğini görmek istiyorsanız, Anders Brownworth'un bu demosuna (yeni bir sekmede açılır) göz atmayı ve aşağıdaki eşlik eden videoyu izlemeyi unutmayın.

[Anders Brownworth'un Videosu](https://www.youtube.com/watch?v=_160oMzblY8)

## ETHEREUM Nedir?

Ethereum, içine gömülü bir bilgisayar bulunan bir blockchaindir. Uygulamaları ve organizasyonları merkezi olmayan, izinsiz ve sansüre dayanıklı bir şekilde oluşturmanın temelidir.

Ethereum evreninde, durumu Ethereum ağındaki herkesin kabul ettiği tek, kanonik bir bilgisayar (Ethereum Sanal Makinesi veya EVM olarak adlandırılır) vardır. Ethereum ağına katılan herkes (her Ethereum düğümü) bu bilgisayarın durumunun bir kopyasını saklar. Ek olarak, herhangi bir katılımcı bu bilgisayarın isteğe bağlı hesaplama yapması için bir istek yayınlayabilir. Böyle bir istek yayınlandığında, ağdaki diğer katılımcılar hesaplamayı doğrular, doğrular ve yürütür. Bu yürütme, EVM'de, tüm ağ boyunca taahhüt edilen ve yayılan bir durum değişikliğine neden olur.

Hesaplama taleplerine işlem talepleri denir; tüm işlemlerin kaydı ve EVM'nin mevcut durumu blok zincirinde depolanır ve bu da tüm düğümler tarafından depolanır ve üzerinde anlaşmaya varılır.

Kriptografik mekanizmalar, işlemlerin geçerli olduğu doğrulandıktan ve blok zincirine eklendikten sonra bunlara daha sonra müdahale edilmemesini sağlar. Aynı mekanizmalar aynı zamanda tüm işlemlerin uygun "izinlerle" imzalanmasını ve yürütülmesini de sağlar (Alice'in kendisi dışında hiç kimse Alice'in hesabından dijital varlık gönderememelidir).

## ETER Nedir?
Ether (ETH), Ethereum'un yerel kripto para birimidir. ETH'nin amacı hesaplama için bir pazara izin vermektir. Böyle bir pazar, katılımcılara işlem taleplerini doğrulamak ve yürütmek ve ağa hesaplama kaynakları sağlamak için ekonomik bir teşvik sağlar.

Bir işlem isteği yayınlayan herhangi bir katılımcının ödül olarak ağa bir miktar ETH de sunması gerekir. Ağ, bu ödülü, işlemin doğrulanması, yürütülmesi, blok zincirine kaydedilmesi ve ağa yayınlanması işini eninde sonunda yapan kişiye verecektir.

==Ödenen ETH miktarı, hesaplamayı yapmak için gereken kaynaklara karşılık gelir. Bu ödüller ayrıca, kötü niyetli katılımcıların, sonsuz hesaplama veya diğer yoğun kaynak kullanan komut dosyalarının yürütülmesini talep ederek ağı kasıtlı olarak tıkamasını da önler; çünkü bu katılımcılar, hesaplama kaynakları için ödeme yapmak zorundadır.==

ETH aynı zamanda ağa kripto-ekonomik güvenlik sağlamak için üç ana yolla kullanılır: 

1) Bloklama öneren veya diğer doğrulayıcıların dürüst olmayan davranışlarını bildiren doğrulayıcıları ödüllendirmek için bir araç olarak kullanılır; 
2) Doğrulayıcılar tarafından, dürüst olmayan davranışlara karşı teminat görevi gören doğrulayıcılar tarafından stake edilir; doğrulayıcılar yanlış davranmaya çalışırsa ETH'leri yok edilebilir; 
3) yeni önerilen bloklar için 'oyları' tartmak için kullanılır ve fikir birliği mekanizmasının çatal seçimi kısmına beslenir.

## Akıllı Sözleşmeler Nelerdir?
Uygulamada katılımcılar EVM'de her hesaplama talep etmek istediklerinde yeni kod yazmazlar. Bunun yerine, uygulama geliştiricileri programları (yeniden kullanılabilir kod parçacıkları) EVM durumuna yükler ve kullanıcılar bu kod parçacıklarının değişen parametrelerle yürütülmesi için istekte bulunur. Ağ akıllı sözleşmelerine yüklenen ve bunlar tarafından yürütülen programlara diyoruz.

Çok temel düzeyde, akıllı sözleşmeyi bir tür satış makinesi gibi düşünebilirsiniz: belirli parametrelerle çağrıldığında, belirli koşullar yerine getirildiğinde bazı eylemleri veya hesaplamaları gerçekleştiren bir komut dosyası. Örneğin, arayan kişinin belirli bir alıcıya ETH göndermesi durumunda basit bir satıcı akıllı sözleşmesi, bir dijital varlığın sahipliğini oluşturabilir ve atayabilir.

Herhangi bir geliştirici, ağa ödenen bir ücret karşılığında akıllı bir sözleşme oluşturabilir ve bunu veri katmanı olarak blockchain'i kullanarak ağa açık hale getirebilir. Daha sonra herhangi bir kullanıcı, yine ağa ödenen bir ücret karşılığında akıllı sözleşmeyi arayarak kodunu çalıştırabilir.

Böylece, akıllı sözleşmelerle geliştiriciler, pazaryerleri, finansal araçlar, oyunlar vb. gibi kullanıcıya yönelik rastgele karmaşık uygulamalar ve hizmetler oluşturabilir ve dağıtabilir.

## Terminoloji
### Blockchain
Ağ geçmişinde Ethereum ağına taahhüt edilen tüm blokların sırası. Bu şekilde adlandırılmasının nedeni, her bloğun önceki bloğa bir referans içermesidir, bu da tüm bloklar üzerinde (ve dolayısıyla kesin geçmiş üzerinde) bir sıralamayı korumamıza yardımcı olur.
### ETH
Ether (ETH), Ethereum'un yerel kripto para birimidir. Kullanıcılar, kod yürütme isteklerinin yerine getirilmesi için diğer kullanıcılara ETH öder.
### EVM
Ethereum Sanal Makinesi, Ethereum ağındaki her katılımcının durumunu depoladığı ve üzerinde mutabakata vardığı küresel sanal bilgisayardır. Herhangi bir katılımcı EVM'de isteğe bağlı kodun çalıştırılmasını talep edebilir; kod yürütme EVM'nin durumunu değiştirir.
### Düğümler
EVM durumunu saklayan gerçek hayattaki makineler. Düğümler, EVM durumu ve yeni durum değişiklikleri hakkındaki bilgileri yaymak için birbirleriyle iletişim kurar. Herhangi bir kullanıcı, bir düğümden bir kod yürütme isteği yayınlayarak da kodun yürütülmesini talep edebilir. Ethereum ağının kendisi, tüm Ethereum düğümlerinin ve bunların iletişimlerinin toplamıdır.
### Hesaplar
ETH'nin depolandığı yer. Kullanıcılar hesapları başlatabilir, hesaplara ETH yatırabilir ve kendi hesaplarından diğer kullanıcılara ETH aktarabilir. Hesaplar ve hesap bakiyeleri EVM'de büyük bir tabloda saklanır; bunlar genel EVM durumunun bir parçasıdır.
### İşlemler
"İşlem isteği", EVM'de kod yürütme isteğinin resmi terimidir ve "işlem", yerine getirilen bir işlem isteği ve EVM durumundaki ilgili değişikliktir. Herhangi bir kullanıcı, bir düğümden ağa bir işlem isteği yayınlayabilir. İşlem talebinin üzerinde anlaşılan EVM durumunu etkilemesi için, başka bir düğüm tarafından doğrulanması, yürütülmesi ve "ağa bağlanması" gerekir. Herhangi bir kodun yürütülmesi EVM'de durum değişikliğine neden olur; Taahhüt üzerine bu durum değişikliği ağdaki tüm düğümlere yayınlanır. Bazı işlem örnekleri:

Benim hesabımdan Alice'in hesabına X ETH gönder.
Bazı akıllı sözleşme kodlarını EVM durumuna yayınlayın.
Akıllı sözleşmenin kodunu EVM'deki X adresinde Y argümanlarıyla yürütün.
### Bloklar
İşlem hacmi çok yüksektir, dolayısıyla işlemler gruplar veya bloklar halinde "taahhüt edilir". Bloklar genellikle düzinelerce ila yüzlerce işlem içerir.
### Akıllı sözleşmeler
Bir geliştiricinin EVM durumuna yayınladığı yeniden kullanılabilir bir kod parçacığı (bir program). Herkes sm talep edebilir.

Sanat sözleşme kodu bir işlem talebi yapılarak yürütülür. Geliştiriciler akıllı sözleşmeler yayınlayarak EVM'ye isteğe bağlı yürütülebilir uygulamalar (oyunlar, pazarlar, finansal araçlar vb.) yazabildiğinden, bunlara genellikle dapp'ler veya Merkezi Olmayan Uygulamalar da denir.
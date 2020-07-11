# Araştırma Ödevi


[1. Solid Prensiplerini Öğren.](https://github.com/Kodluyoruz51BootcampMVCCore/arastirma-odevi-ozdenkubra/blob/master/README.md#SOLID-Prensipleri)
1. **SOLID Prensipleri**

- **Nedir bu SOLID ?**

OOP (Object Oriented Programming) nin ilk 5 maddesi olarak Robert Martin tarafından 2000&#39;li yılların başında yayınlandı. &quot;SOLID&quot; kelimesi, yazılım geliştirme süreçlerinde karşılaşılan temel sorunlara getirilen 5 temel prensibin baş harflerinden oluşur. Öncelikle temel sorunlardan bahsedecek olursak bunlar;

- Esnemezlik (Programın geliştirilememesi ve ekleme yapılamaması)

- Kırılganlık (Bir yerde yapılan değişikliğin başka yerde sorun çıkartması)

- Sabitlik (Geliştirilen ürünün başka yerde tekrar kullanılamaması)

- Maliyet (Geliştirme maliyetinin ve sürecin artması)

şeklinde tanımlanabilirler. SOLID bu sorunları ortadan kaldırmak için geliştirildi ve temel amacı &quot;Güncellenilebilirlik&quot; denilebilir.

S-O-L-I-D &#39;i tanımlayalım…

**S: Single-Responsibility Principle (Tek Sorumluluk Prensibi)**

Bir sınıf, fonksiyon veya metot tek bir görevi gerçekleştirebilir. Diğer görevlere karışmaz karışamaz. (Bir tek şeyi yap ve onu en iyi yap!)

Yazdığınız projede, &quot;Bu metot bu sınıfın içerisinde mi yer almalı? – Bu görevi yerine getirmek bu metodun veya sınıfın işimi?&quot; sorularını kendimize sorup cevaplamamız bu prensibe uygun kod yazmamızı sağlar.

**O: Open-Closed Principle (Açık- Kapalı Prensibi)**

**&quot;** Geliştirmeye açık- Değişime kapalı&quot; şeklinde özetlenebilir. Bir proje gerçekleştirirken ileride olabilecek yeni istekler ve gelişmeleri de öngörerek tasarlayıp gerçekleştirmemiz gerekir. Projemizde oluşabilecek yeni istek ve ihtiyaçlar sonucunda yapacağımız güncellemeler, projemizde ki diğer sistemleri etkilememeli ve herhangi istenmeyen bir değişikliğe sebebiyet vermemelidir.

**L: Liskov Substitution Principle (Liskov &#39;un Yerine Geçme Prensibi)**

Alt sınıflar miras aldığı üst sınıfın bütün özelliklerini kullanmalı, alt sınıflarda oluşturulan nesneler üst sınıfın nesneleriyle yer değiştirdiklerinde aynı davranışı göstermeli ve herhangi bir kullanılmayan özellik olmamalı.

**I: Interface Segregation Principle (Arayüz Ayrımı Prensibi)**

Bir ara yüze gerekli olmayan eklentinin eklenmemesini, kullanılacak olan eklenti neyse onun eklenmesini savunan prensiptir. Yani temel amacı için; gereksiz kodları önlemek ve kodun daha amaca yönelik hale gelmesini sağlamak diyebiliriz. Ara yüzlerde sadece metotlar bulunur. Bir ara yüz sınıfı implemente edildiğinde içinde bulundurduğu metotları da bulundurmak veya oluşturmak zorundadır aksi halde program hata verir.

Prensibimiz tam bu noktada devreye girer. Eğer class içerisinde ihtiyaç duyulmayan ve kullanılmayan metotlar varsa ve bunlar ara yüzle implemente edilmişse bu kodlara &quot;dummy kod&quot; denir bu sebeple ara yüzler ayrılmalı ve classlar için gereksiz metotların bulundurulması engellenmelidir.

**D: Dependency Inversion Principle (Bağımlılıkların Tersine Çevirilmesi Prensibi)**

Bu prensibi, katmanlı mimaride üst seviyeli katmanlar alt seviyeli katmanlara bağlı olmamalı, bağımlılıklar sadece soyut(abstract) kavramlara olmalı şeklinde özetleyebiliriz. Amaç: alt seviyede yapılan herhangi bir değişikliğin, üst seviyede kod değişikline veya onun bağlılıklarının etkilenmesine engel olmaktır. Yani üst seviyedeki katmanın alt seviyedeki katmanda bir işin nasıl yapıldığını bilmesine gerek yok umurunda da olmamalı, gelen herhangi bir veriyle gerekli işlemleri gerçekleştirmesi yeterli olmalıdır.



2. Microsoft Build 'den 2 etkinlik araştır.

| Events                                                       | Duration | Session Code | Session Type                                                 | Level               | Date                                    |
| ------------------------------------------------------------ | -------- | ------------ | ------------------------------------------------------------ | ------------------- | --------------------------------------- |
| [Azure & M365 Recap with Mary Jo Foley & Paul Thurott](https://mybuild.microsoft.com/sessions/2cc1bc56-4890-4268-a9c2-70021fd4b594?source=home) | 15 mins  | BDL103       | [Build Live](https://mybuild.microsoft.com/sessions?f=[{"name"%3A"Build Live"%2C"facetName"%3A"sessionType"}]) | Foundational  (100) | Tuesday, May 19 9:45 PM - 10:00 PM +03  |
| [Mark Russinovich on Azure innovation and more!](https://mybuild.microsoft.com/sessions/d9eca5e8-ee14-40ea-82de-172f00c6b6f0?source=home) | 30 mins  | BDL104       | [Build Live](https://mybuild.microsoft.com/sessions?f=[{"name"%3A"Build Live"%2C"facetName"%3A"sessionType"}]) | Intermediate (200)  | Tuesday, May 19 10:00 PM - 10:30 PM +03 |



2. Microsoft Build 2020 yeniliklerini Araştır.

**Microsoft Build 2020 Konferansı etkinliğinde Azure, Microsoft 365, Güvenlik ve Windows 10’da geliştiricilere sunulan yenilikler tanıtıldı.**

Birlikte öğrenmek, geliştirmek ve tasarlamak amacıyla düzenlenen ve uluslararası yazılım geliştiricilerin buluşma noktası olarak nitelendirilen uluslararası **Microsoft Build 2020 Konferansı** etkinliği bu sene herkesin katılımına açık ve çevrimiçi olarak 48 saat sürecek.

**Etkinlikte duyurulan yenilikler**

Build 2020’de operasyonel veritabanı hizmetlerini ve analitiği gerçek zamanlı olarak bir araya getiren **Azure Synapse Link** tanıtıldı. Maliyetleri düşüren ve zaman kazandıran Azure Synapse Link, veri hareketlerini yönetmeye gerek kalmadan müşterilerin değerli bilgiler elde etmesini sağlıyor.

Geliştiricilerin Visual Studio. ve Visual Studio Code’dan Teams uygulamaları oluşturmaları ve yayınlamaları için **Microsoft Teams’e,** yenilikler sunuldu. Bu yeni yetenekler BT yöneticilerinin Teams’teki kullanıcıların iş kollarını ve ISV uygulamalarını değerlendirmesine ve iş dağılımı yapmasına olanak tanıyor.

Yeni güncellemeler eklenen **Fluid Framework,** açık kaynak platformu olarak geliştiricilere sunulmaya başlandı. Böylece [Office.com](http://office.com/) ve Web için Outlook’taki Fluid bileşenleri de son kullanıcılara sağlanmış oldu.

**Azure Machine Learning** ve OSS araçlarına getirilen yeniliklerle müşterilerin yapay zekâ modellerini daha sorumlu bir şekilde kullanmasına yardımcı olmak için yeni Responsible ML. araçları sunuldu. Bu araç, model yorumlama yeteneğini geliştirerek veri güvenliğini ve kullanıcı gizliliği garanti altına alacak, yapay zeka sistemlerinin geliştirilmesinde sorumluluk anlayışını güçlendirecek.

Etkinlikte, 1 milyar Windows 10 cihazında birlikte uygulama geliştirmeye yardımcı olmak için **Project Reunion** girişimi de tanıtıldı. Project Reunion, Win32 ve UWP API’leri ile entegrasyonu kolaylaştırmak. ve Windows 10 sürümleri kullanılan tüm cihazlarda çalışan kullanışlı uygulamalar geliştirmek üzere bir “Windows geliştirici platformu” olarak oluşturuldu.

#### **[Microsoft eğitim kurumlarına ücretsiz Teams kursları veriyor!](https://www.btgunlugu.com/microsoft-egitim-kurumlarina-ucretsiz-teams-kurslari-veriyor/)**

**Power Automate** çözümüne kapsamlı düşük kodlu Robotik Proses Otomasyonu (RPA) teknolojisini sunmak için yatırımlarını sürdüren Microsoft, düşük kodlu ve kullanımı kolay RPA geliştirme ortamlarının lider sağlayıcısı **Softomotive’i** satın aldı. Softomotive’in teknolojisi, Microsoft müşterilerinin işlerini kolaylaştırmak. için kullanıcı arayüzü akışlarına destek olan çözümler sunmaya başladı.

[![Microsoft Build 2020 Konferansı](https://i2.wp.com/cdn.btgunlugu.com/uploads/2020/05/1589970809_Mosaic.jpg?resize=640%2C360&ssl=1)](https://i2.wp.com/cdn.btgunlugu.com/uploads/2020/05/1589970809_Mosaic.jpg?ssl=1)

Etkinlikte, Azure’da yer alan dünyanın en güçlü **süper yapay zekâ bilgisayarları**ndan birini de duyuruldu. **OpenAI** ile işbirliğiyle özel olarak geliştirilen bu süper bilgisayar gücünü Azure bulut altyapısından alıyor. Sistem, dağıtılmış devasa yapay zekâ modelleri geliştirmek için özel olarak tasarlandı.

Visual Studio ürün ailesiyle Microsoft, her geliştiriciye sınıfının en iyisi araçları sağlanmaya devam ediyor. Build 2020’de, yeni bir geliştirici. kutusu kurmak, yeni bir projeye katılırken veya uzaktan çalışmaya geçerken ortak bir senaryo oluşturmak için **Visual Studio Codespaces** de tanıtıldı. VS Codespaces, geliştiricilerin dakikalar içinde tamamen yapılandırılmış geliştirme. ortamları oluşturması için bulutun gücünden faydalanıyor.

Geliştiricilerin bulut deneyimine kesintisiz kod sağlamak için, **GitHub Actions for Azure (Azure için GitHub Eylemleri)** platformuna yapılan yeni entegrasyonlar da duyuruldu. Ekiplerin iş akışlarını kolayca oluşturmasına, test edip yayınlamasına, dağıtmasına ve otomatikleştirmesine yardımcı olan 30’dan fazla GitHub. Eylemi geliştiricilere sunuldu.

Build 2020’de ayrıca Microsoft’un sağlık sektörüne özgü ilk bulut hizmeti olan **Microsoft Cloud for Healthcare** tanıtıldı.

2. Takip Ettiğin 2 yazılımcıyı araştır.
   1. Bora Kaşmer (http://www.borakasmer.com/) / GitHub: https://github.com/borakasmer
   2. Burak Selim Şenyurt (https://www.buraksenyurt.com/) / GitHub: https://github.com/buraksenyurt

2. Devler Azure'da araştır [Eğitim-Workshop]

| Tarih                                     | Eğitim / Atölye Adı                                          | Türü                  | Kayıtlı Video Linki                                          |
| ----------------------------------------- | ------------------------------------------------------------ | --------------------- | ------------------------------------------------------------ |
| **7 Temmuz Salı ** **17:00-18:00**        | Hüseyin Akdoğan -Expert Software Consultant , Kodcu.com <br />Introduction to RxJava by applying to existing applications | Eğitim                | [Kayıt linki](https://info.microsoft.com/ME-AzureApp-WBNR-FY20-07Jul-07-DEVLERAZUREDAReactiveProgramming-RxJava-SRDEM29549_LP01Registration-ForminBody.html) |
| **11 Haziran Perşembe** **17:00 - 18:00** | Mustafa El-Aliwat - Business Development Director , Enqura<br />Emre Özer - Technology Director, Enqura<br />Azure ile Uygulama Modernizasyonu, Mikroservis mimarileri<br />Açık Kaynak Kod (Open Source) ışığında en iyi pratiklere sahip yazılım mimarisi | Eğitim                | [Kayıt linki](https://info.microsoft.com/ME-AzureApp-WBNR-FY20-06Jun-11-GIANTSAZUREDAApplicationModernizationwithAzureMicroservicearchitectures-SRDEM25634_LP01Registration-ForminBody.html?wt.mc_id=AID3011342_QSG_EML_434478) |
| **16 Nisan Perşembe** **17:00 - 18:30**   | Pamir Erdem - Microsoft Türkiye, Azure Teknik Eğitmen<br />Containerlar ve Kubernetes<br />Kubernetes İş Yükleri | Kubernetes Atölyeleri | [Kayıtlı Video Linki ](https://info.microsoft.com/ME-AzureApp-WBNR-FY20-04Apr-16-ContainersKubernetesandWorkloads-SRDEM17646_LP01Registration-ForminBody.html?wt.mc_id=AID3011342_QSG_EML_420120) |
| **21 Nisan Salı **17:00 - 18:00****       | Mehmet Kut - Microsoft Türkiye, Azure Teknik Eğitmen<br />DevOps Kültürü ve Azure DevOps | DevOps Atölyeleri     | [Kayıtlı Video Linki ](https://info.microsoft.com/ME-AzureApp-WBNR-FY20-04Apr-21-DevOpsCultureandAzureDevOps-SRDEM17655_LP01Registration-ForminBody.html?wt.mc_id=AID3011342_QSG_EML_421915) |



3. Yazılım ile ilgili Yarışmaları araştır (Örneğin: GGJ)

- TEKNOFEST: https://teknofest.org/index.html
- Global Game Jam https://globalgamejam.org/



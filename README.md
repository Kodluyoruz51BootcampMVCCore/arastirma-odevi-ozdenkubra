# Araştırma Ödevi


[1. Solid Prensiplerini Öğren.](#SOLID-Prensipleri)
1. **SOLID Prensipleri**

- **Nedir bu SOLID ?**

OOP (Object Oriented Programming) nin ilk 5 maddesi olarak Robert Martin tarafından 2000&#39;li yılların başında yayınlandı. &quot;SOLID&quot; kelimesi, yazılım geliştirme süreçlerinde karşılaşılan temel sorunlara getirilen 5 temel prensibin baş harflerinden oluşur. Öncelikle temel sorunlardan bahsedecek olursak bunlar;

- Esnemezlik (Programın geliştirilememesi ve ekleme yapılamaması)

- Kırılganlık (Bir yerde yapılan değişikliğin başka yerde sorun çıkartması)

- Sabitlik (Geliştirilen ürünün başka yerde tekrar kullanılamaması)

- Maliyet (Geliştirme maliyetinin ve sürecin artması)

şeklinde tanımlanabilirler. SOLID bu sorunları ortadan kaldırmak için geliştirildi ve temel amacı &quot;Güncellenilebilirlik&quot; denilebilir.

S-O-L-I-D &#39;i tanımlayalım…

**S --> Single-Responsibility Principle (Tek Sorumluluk Prensibi)**

Bir sınıf, fonksiyon veya metot tek bir görevi gerçekleştirebilir. Diğer görevlere karışmaz karışamaz. (Bir tek şeyi yap ve onu en iyi yap!)

Yazdığınız projede, &quot;Bu metot bu sınıfın içerisinde mi yer almalı? – Bu görevi yerine getirmek bu metodun veya sınıfın işimi?&quot; sorularını kendimize sorup cevaplamamız bu prensibe uygun kod yazmamızı sağlar.

**O --> Open-Closed Principle (Açık- Kapalı Prensibi)**

**&quot;** Geliştirmeye açık- Değişime kapalı&quot; şeklinde özetlenebilir. Bir proje gerçekleştirirken ileride olabilecek yeni istekler ve gelişmeleri de öngörerek tasarlayıp gerçekleştirmemiz gerekir. Projemizde oluşabilecek yeni istek ve ihtiyaçlar sonucunda yapacağımız güncellemeler, projemizde ki diğer sistemleri etkilememeli ve herhangi istenmeyen bir değişikliğe sebebiyet vermemelidir.

**L --> Liskov Substitution Principle (Liskov &#39;un Yerine Geçme Prensibi)**

Alt sınıflar miras aldığı üst sınıfın bütün özelliklerini kullanmalı, alt sınıflarda oluşturulan nesneler üst sınıfın nesneleriyle yer değiştirdiklerinde aynı davranışı göstermeli ve herhangi bir kullanılmayan özellik olmamalı.

**I --> Interface Segregation Principle (Arayüz Ayrımı Prensibi)**

Bir ara yüze gerekli olmayan eklentinin eklenmemesini, kullanılacak olan eklenti neyse onun eklenmesini savunan prensiptir. Yani temel amacı için; gereksiz kodları önlemek ve kodun daha amaca yönelik hale gelmesini sağlamak diyebiliriz. Ara yüzlerde sadece metotlar bulunur. Bir ara yüz sınıfı implemente edildiğinde içinde bulundurduğu metotları da bulundurmak veya oluşturmak zorundadır aksi halde program hata verir.

Prensibimiz tam bu noktada devreye girer. Eğer class içerisinde ihtiyaç duyulmayan ve kullanılmayan metotlar varsa ve bunlar ara yüzle implemente edilmişse bu kodlara &quot;dummy kod&quot; denir bu sebeple ara yüzler ayrılmalı ve classlar için gereksiz metotların bulundurulması engellenmelidir.

**D --> Dependency Inversion Principle (Bağımlılıkların Tersine Çevirilmesi Prensibi)**

Bu prensibi, katmanlı mimaride üst seviyeli katmanlar alt seviyeli katmanlara bağlı olmamalı, bağımlılıklar sadece soyut(abstract) kavramlara olmalı şeklinde özetleyebiliriz. Amaç: alt seviyede yapılan herhangi bir değişikliğin, üst seviyede kod değişikline veya onun bağlılıklarının etkilenmesine engel olmaktır. Yani üst seviyedeki katmanın alt seviyedeki katmanda bir işin nasıl yapıldığını bilmesine gerek yok umurunda da olmamalı, gelen herhangi bir veriyle gerekli işlemleri gerçekleştirmesi yeterli olmalıdır.



2. Microsoft Build 'den 2 etkinlik araştır.
3. Microsoft Build 2020 yeniliklerini Araştır.
4. Takip Ettiğin 2 yazılımcıyı araştır.
5. Devler Azure'da araştır [Eğitim-Workshop]
6. Yazılım ile ilgili Yarışmaları araştır (Örneğin: GGJ)

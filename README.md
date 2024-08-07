# Veri Analizi Adımları

## 1. Veriye İlk Akış
- **Head ile ilk beş veriye bakma:** Veri setinin ilk beş satırına bakarak verinin genel yapısını ve içerdiği bilgileri hızlıca anladık.
- **Tail ile veri son beş veriye bakma:** Veri setinin son beş satırına bakarak veri setinin sonunda nasıl göründüğünü gördük.
- **Shape ile veriyi şekline bakma:** Veri setinin kaç satır ve kaç sütundan oluştuğunu öğrendik.
- **Columns ile veri sütunlarına bakma:** Veri setindeki sütun isimlerine bakarak hangi özelliklerin mevcut olduğunu belirledik.
- **Describe ile veri analitik yapısına bakma:** Verinin sayısal özelliklerinin temel istatistiksel özetini aldık.
- **Isnull ile verideki boş veriye bakma:** Veri setindeki boş değerleri tespit ettik ve eksik verileri temizledik.

## 2. Veri Görselleştirme
- **Veriyi genel görselleştirme:** Veri setinin genel görünümünü, dağılımlarını ve ilişkilerini anlamak için grafikler oluşturduk.
- **Yaş durumuna göre veri görselleştirmesi yapma:** Farklı yaş gruplarındaki kişilerin kredi skorlarını ve diğer finansal bilgilerini analiz ettik.
- **Gelir durumuna göre veriyi görselleştirme:** Farklı gelir seviyelerindeki kişilerin kredi skorlarını ve diğer finansal bilgilerini görselleştirdik.
- **Ülkelerin genel durumuna göre dağılım:** Veri setindeki farklı ülkelerdeki kişilerin finansal durumlarını ve kredi skorlarını analiz ettik.
- **Eğitim açısından veri görselleştirme yapma:** Eğitim seviyelerine göre kredi skorlarının dağılımını inceledik.

## 3. Model Kurma
- **Model kurma:** Yapay sinir ağı kullanarak bir model oluşturduk ve veriyi bu modelle eğittik.
- **Modele tahmin yaptırma:** Modeli kullanarak yeni veri noktaları için kredi skorlarını tahmin ettik.
- **Modelin sonuçlarını görselleştirme:** Modelin tahmin ettiği kredi skorları ile gerçek kredi skorlarını karşılaştırarak modelin performansını görselleştirdik.
- **Modelin sonuçlarını kaydettirme:** Modeli ve eğitim sürecini kaydederek gelecekte tekrar kullanmak üzere sakladık.
- **Kullanıcıdan alınan bilgilerle kredi skoru tahmin etme:** Kullanıcıdan alınan bilgileri kullanarak kredi skorunu tahmin eden interaktif bir Tkinter uygulaması geliştirdik.

## Genel Sonuçlar
- **Eğitim ve Gelir Durumu:** Eğitim seviyesi ve gelir durumu, kredi skorunu önemli ölçüde etkileyen faktörler olarak belirlendi. Daha yüksek eğitim seviyesine ve gelire sahip bireylerin genellikle daha yüksek kredi skorlarına sahip olduğu görüldü.
- **Ödeme Geçmişi:** Ödeme geçmişi, kredi skorunu en çok etkileyen faktörlerden biri olarak belirlendi. Düzenli ödeme yapan bireylerin kredi skorlarının daha yüksek olduğu tespit edildi.
- **Cinsiyet Farklılıkları:** Kadınların kredi skorlarının genel olarak erkeklerden daha düşük olduğu gözlemlendi. Bu durumun, kadınların daha düşük gelir seviyelerine sahip olma eğilimi ve finansal piyasada daha az temsil edilmeleri gibi çeşitli sosyo-ekonomik faktörlerden kaynaklanabileceği değerlendirildi.

## Proje Adımları ve Elde Edilen Sonuçların Genel Açıklaması
Bu proje kapsamında, kredi skorunu tahmin etmek için çeşitli veri analizleri ve makine öğrenimi teknikleri uyguladık. Veriyi analiz edip görselleştirerek, önemli özellikleri ve bu özelliklerin kredi skoru üzerindeki etkilerini belirledik. Daha sonra, yapay sinir ağı kullanarak bir model oluşturduk ve bu modelle kredi skorlarını başarılı bir şekilde tahmin ettik. Son olarak, kullanıcıdan alınan bilgileri kullanarak kredi skorunu tahmin eden interaktif bir uygulama geliştirdik. Bu süreçte elde edilen sonuçlar, eğitim, gelir durumu ve ödeme geçmişinin kredi skoru üzerinde önemli bir etkiye sahip olduğunu, ayrıca kadınların kredi skorlarının erkeklere göre genellikle daha düşük olduğunu ortaya koydu. Bu bulgular, kredi değerlendirme süreçlerinde dikkate alınması gereken önemli faktörlerdir.


## Kullanım
Projenin nasıl kullanılacağını ve çalıştırılacağını öğrenmek için README dosyasını inceleyebilirsiniz.

## İletişim
Sorularınız veya geri bildirimleriniz için bana e-posta veya LinkedIn üzerinden ulaşabilirsiniz.

### Etkileşimli Hesaplama Yapma
1. Kullanıcı etkileşimli bir GUI (Grafiksel Kullanıcı Arayüzü) geliştirdim.

## Kullanılan Kütüphaneler
- `pandas` - Veri işleme ve analizi için.
- `seaborn` ve `matplotlib` - Veri görselleştirmesi için.
- `numpy` - Sayısal işlemler için.
- `sklearn` - Modelleme ve değerlendirme için.
- `tensorflow.keras` - Derin öğrenme modelleme için.
- `tkinter` - GUI geliştirme için.

## Lisans
Bu proje MIT Lisansı ile lisanslanmıştır.

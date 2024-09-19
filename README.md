# Enerji Üretimi Analizi ve Modelleme

Bu proje, enerji üretimi verilerini kullanarak keşifsel veri analizi (EDA) yapmayı ve gözetimli öğrenme yöntemleri ile enerji üretimini tahmin etmeyi amaçlamaktadır.

## İçindekiler

1. [Proje Hakkında](#proje-hakkında)
2. [Kullanılan Teknolojiler](#kullanılan-teknolojiler)
3. [Veri Seti](#veri-seti)
4. [Adımlar](#adımlar)
5. [Sonuçlar](#sonuçlar)


## Proje Hakkında

Bu proje, enerji üretim verileri üzerinden çeşitli analizler yaparak, farklı enerji kaynaklarının yıllara göre dağılımını incelemekte ve regresyon modelleri kullanarak enerji üretimini tahmin etmektedir.

## Kullanılan Teknolojiler

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Veri Seti

Veri seti, farklı yıllara ait enerji üretim bilgilerini içermektedir. Her kayıt, yıllar, enerji kaynakları, üretim miktarı gibi bilgileri barındırmaktadır. Veri seti `organised_Gen.csv` adlı dosyada bulunmaktadır.

## Adımlar

1. **Veri Yükleme ve Ön Hazırlık**
   - Veri seti yüklendi ve temel bilgiler elde edildi.
   - Eksik değerler kontrol edildi.

2. **Keşifsel Veri Analizi (EDA)**
   - Yıllara göre toplam enerji üretimi grafiği oluşturuldu.
   - Enerji kaynaklarının dağılımı ve yıllara göre değişimi incelendi.
   - Enerji üretiminin istatistiksel dağılımı ve korelasyon matrisi oluşturuldu.

3. **Veri Ön İşleme**
   - Eksik değerler ortalama ile dolduruldu (gerekirse).
   - Kategorik veriler sayısal değerlere dönüştürüldü.
   - Veri seti eğitim ve test olarak ayrıldı.

4. **Gözetimli Öğrenme**
   - Doğrusal regresyon ve karar ağaçları kullanılarak model eğitimi yapıldı.
   - Modellerin performansı MSE ve R² skorları ile değerlendirildi.
   - Hiperparametre optimizasyonu için GridSearchCV kullanıldı.

## Sonuçlar

Proje sonunda, farklı regresyon modellerinin performansları karşılaştırılmış ve görselleştirilmiştir. MSE ve R² skorları ile modellerin başarıları değerlendirilmiştir.



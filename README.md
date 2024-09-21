# Proje_Kampı-
#Kaggle link "https://www.kaggle.com/code/merveacarss/s-rd-r-lebilirlik-proje/edit"

Sera Gazı Emisyonları Analizi - KNN ve Kümeleme
Proje Özeti
Bu projede Avrupa Çevre Ajansı'nın (EEA) sera gazı emisyonları projeksiyonları analiz edilmiştir. Sürdürülebilirlik konusuna dikkat çekerek, emisyonların sektörel katkılarını değerlendirmeyi ve bu alanda farkındalığı artırmayı hedefledim. Projede, gözetimli öğrenme (K-En Yakın Komşu - KNN algoritması) ve gözetimsiz öğrenme (kümeleme) teknikleri kullanılarak elde edilen veriler ışığında, gelecekteki emisyonlar hakkında tahminler yapılmış ve sürdürülebilirlik adına önemli çıkarımlar sunulmuştur.

Bu analizle:

Farklı sektörlerdeki emisyon eğilimleri vurgulandı,
Farklı sektörlerin sera gazı emisyonlarına olan katkıları gösterildi,
Sürdürülebilir uygulamaların önemi belirginleştirilerek, farkındalık ve bilinç düzeyi artırılmaya çalışıldı.

Veri Ön İşleme
Veri setindeki eksik verileri yönetmek ve veri kalitesini artırmak için aşağıdaki adımları izledim:
Gereksiz Verilerin Çıkarılması: İlgisiz veya etkisiz sütunlar silindi.
Eksik Verilerin Doldurulması: Eksik veri noktaları, ilgili sütunların en sık tekrar eden değeri (mod) kullanılarak tamamlandı.

Makine Öğrenimi Yöntemleri
1. Gözetimli Öğrenme - K-En Yakın Komşu (KNN)
KNN algoritması, sektörlerin geçmiş verileri kullanılarak sera gazı emisyonlarını tahmin etmek için uygulandı. Bu yöntem ile hangi sektörlerin en fazla emisyon üretme riski taşıdığı öngörüldü ve sürdürülebilirlik hedeflerine yönelik odaklanılması gereken alanlar belirlendi.
2. Gözetimsiz Öğrenme - Kümeleme
Kümeleme yöntemiyle, benzer emisyon özelliklerine sahip sektörler ve ülkeler gruplandırıldı. Bu yaklaşım sayesinde, sürdürülebilirlik açısından iş birliği yapılabilecek sektörler ve ülkeler tespit edildi.

Temel Sonuçlar
Belirlenen Sektörler: Özellikle enerji üretimi ve ulaşım gibi sektörler, en yüksek sera gazı emisyonu üreten alanlar olarak tespit edildi.
Kümeleme Bulguları: Benzer ekonomik faaliyet ve enerji tüketimi yapısına sahip ülkeler, emisyon kalıplarına göre kümelendi. Bu bulgu, ülkeler arasında iş birliği ve sürdürülebilirlik konusunda birlikte hareket edebilme fırsatlarına işaret ediyor.

Sürdürülebilirlik İçgörüleri
Bu projede elde edilen bulgular, sektör bazlı çözümlerin önemini bir kez daha ortaya koyuyor. Özellikle yüksek emisyona sahip enerji ve ulaşım sektörlerinde acilen sürdürülebilir inovasyonların hayata geçirilmesi gerekiyor. Ayrıca bu analiz, sürdürülebilirlik yolunda alınması gereken önlemlerin, karar vericiler için daha somut hale gelmesine katkı sağlıyor.


Görseller

Sektörlere Göre Emisyon Katkıları: Sektörlerin sera gazı emisyonlarına katkı oranlarını gösteren  pasta grafiği.
Bu grafik, enerji, ulaşım gibi yüksek emisyon üreten sektörlerin etkilerini net bir şekilde ortaya koymuştur.
![2024-09-21_15-14-05](https://github.com/user-attachments/assets/859f793b-6d71-4a22-9b2d-d4ef6b8b3ced)


Ülkelerin Emisyon Kümeleri: Ülkelerin emisyon profillerine göre hangi bölgelerde sürdürülebilirlik açısından ortak hareket edebileceği tahmini yürütülebilir.
![2024-09-21_15-16-21](https://github.com/user-attachments/assets/ea640e2a-3ad3-4277-a00e-a08cd9ed1310)


KNN Tahmin Sonuçları: Farklı sektörler için yapılan KNN tahminlerinin doğruluk oranın yer aldığı bir grafik.
![2024-09-21_15-18-52](https://github.com/user-attachments/assets/e6ad44f0-d94b-4ec6-ae17-111c4e306e85)

K-Means Kümeleme Tahmin Sonuçları: Bu modeli, verileri benzerliklerine göre gruplandırmak için kullandım.
"Reported Value", "Year", "SubmissionYear" ve "Gapfilled" değişkenlerini kullanarak verileri 3 farklı kümeye ayırdım.
![2024-09-21_15-21-05](https://github.com/user-attachments/assets/1dd3188c-e829-43d2-8114-d4b842251a70)

Sonuç
Bu proje, iklim değişikliğiyle mücadelede sektörlerin rolünü ortaya koyarak sürdürülebilirlik için yapılması gerekenlere dair somut içgörüler sunuyor. Sera gazı emisyonlarının sektör bazında analiz edilmesi, karbon ayak izini azaltmaya yönelik etkili stratejiler geliştirilmesine katkıda bulunabilir. Farkındalığı artırmak ve sürdürülebilir yaşam biçimlerini teşvik etmek, daha yeşil bir geleceğe doğru atılacak adımlarda büyük bir rol oynuyor.


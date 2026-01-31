Bu çalışmada, 1949-1960 yılları arasındaki aylık toplam yolcu sayıları kullanılmıştır.
Long Short-Term Memory (LSTM) ağları kullanılarak verideki mevsimsel trendler öğrenilmiş ve gelecek dönem tahminleri yapılmıştır.


Model Mimarisi
Model, ardışık (Sequential) bir yapıya sahiptir:

LSTM Katmanı: 128 bellek hücresi (Zaman serisindeki uzun vadeli ilişkileri öğrenmek için).

Dense (Ara) Katman: 64 nöron.

Output Katmanı: 1 nöron (Tahmin edilen yolcu sayısı).

Sonuçlar
Model, eğitim sonrasında test verileri üzerinde gerçek yolcu sayıları ile tahmin edilen sayıları karşılaştıran bir grafik üretir. Bu grafik üzerinden modelin başarısı gözlemlenebilir.



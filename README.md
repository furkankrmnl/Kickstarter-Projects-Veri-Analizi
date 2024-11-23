# Kickstarter-Projects-Veri-Analizi
Bu proje için hazırlamış olduğum veri analizi adımlarının özeti

Kütüphaneler import edildi.
Eksik değerlerin olup olmadığı kontrol edildi. Yeterli sayıda eksik değer olmadığı için özel olarak verilen fonksiyon ile eksik değerler türetildi.
Özniteliklerin türleri belirlendi. Her bir öznitelik için açıklama yapıldı.
Tarih verisi barındıran sütunlar güncellendi ve "project_window" adında yeni bir öznitelik türetildi.
Gereksiz "ID" ve "name" sütunları silindi. 
Sütunlardaki eksik veriler numerik ise ortalama, kategorik ise mod değeri ile dolduruldu.
Her bir öznitelik için görselleştirmeler yapıldı. Grafik analizleri sonucu, birisi Outcome olmak üzere 2 öznitelik dönüştürüldü.
Numerik veriler daha kolay öğrenilebilmesi adına Standardize edildi.
Kategorik değişkenlere, makine öğrenmesi modelinde kullanılabilmek üzere "LabelEncoder" ile encoding işlemi uygulandı.
HeatMap oluşturuldu. Veriler yorumlanarak korelasyona sahip öznitelikler, veri setinden çıkartıldı. 
Kullanılabilecek makine öğrenmesi modeli önerildi.

Bu proje, bir proje yapmak isteyip bağışa ihtiyaç duyan, "Acaba yeterli miktarı toplayıp başarılı olabilecek miyiz?" diyen bir Start-Up şirketi tarafından, 
veya bir veri analizi şirketi (belki de veri setinin sahip olduğu şirket) tarafından yürütülen bir "hangi kategorilerde?", "hangi yıllarda?", "ne kadar para toplama hedefi olan?" projelerin başarılı olup olmadığını tahmin etmek isteyen bir şirket tarafından yapılan bir projenin 
veri analizi adımı olarak kullanılabilir.

# image-processing-YBS

Bu repo, Yönetim Bilişim Sistemleri bölümünde haftalık olarak hazırladığım Jupyter Notebook üzerindeki görüntü işleme ders konularını içerir.  
Her hafta ayrı klasör altında yer almakta, kodlar ve açıklamalar düzenli şekilde paylaşılmaktadır.  

## İçindekiler
- **Week 01:** Görüntü işleme giriş ve temel kütüphanelerin (OpenCV, NumPy) tanıtımı.
- **Week 02:** Veri Ön İşleme
- **Week 03:** Bu çalışmada OpenCV kullanılarak görüntüye morfolojik işlemlerden erozyon (erosion) uygulanmıştır. Erozyon, beyaz alanları daraltıp kenarları aşındırarak gürültüyü azaltır. Sonuçlar matplotlib ile görselleştirilmiştir.
- **Week 04:** Görüntü histogramı analizi, histogram eşitleme ve gürültü giderme (yumuşatma) filtreleri uygulanmıştır.
- **Week 05:** Bu çalışmada OpenCV kullanılarak görüntü eşikleme (Otsu metodu) ve morfolojik kapanış (closing) işlemleri yapılmıştır. Ardından, işlenmiş görüntüdeki nesnelerin dış hatları (konturları) `cv2.findContours` ile tespit edilmiştir.
- **Week 06:** Görüntü üzerindeki kenar ve sınır hatlarının tespiti için Canny ve Sobel gibi kenar bulma algoritmaları incelenmiştir.
- **Week 07:** Farklı renk uzayları (RGB, HSV, Gray) arasında dönüşümler ve geometrik görüntü manipülasyonları gerçekleştirilmiştir.
- **Week 08:** Görüntü üzerindeki nesnelerin tespiti ve öznitelik çıkarımı (Feature Extraction) üzerine uygulamalar yapılmıştır.
- **Week 11:** Yapay sinir ağları giriş
  -> Detaylı yazımı linkte bulabilirsiniz: [Medium Makalem](https://medium.com/@esrakgun.409/yapay-zeka-nasıl-görür-ysadan-cnn-e-mimari-bir-yolculuk-8a651d0976b8)
- **Week 12:** MNIST veri seti ile el yazısı rakam tanıma ve veri setinin yapay sinir ağlarına hazırlanması süreci işlenmiştir.
- **Extra:** `Calculator_with_ANN`: Yapay Sinir Ağları (YSA) mimarisi kullanılarak temel bir hesap makinesi mantığının modellenmesi ve eğitimi örneklendirilmiştir.

# Pneumonia-Detection-with-CNN

Bu proje, bir görüntü işleme dersi kapsamında geliştirilen ve göğüs röntgeni (chest X-ray) görüntüleri üzerinde konvolüsyonel sinir ağı (CNN) kullanarak pnömoni (zatürre) tespiti yapan bir modeldir.

---

## 🎯 Proje Amacı

- Göğüs röntgeni görüntülerini kullanarak pnömoni (zatürre) ve sağlıklı (normal) sınıflandırması yapmak.
- CNN tabanlı bir model eğitmek ve değerlendirmek.
- Modelin doğruluk, hassasiyet (precision), geri çağırma (recall) ve F1 skor gibi performans ölçülerini analiz etmek.

---

## 🧠 Kullanılan Teknikler

- Konvolüsyonel Sinir Ağı (CNN) mimarisi (kendi tanımladığınız veya basit bir örnek yapı).
- Veri ön işleme: yeniden boyutlandırma, normalize etme, sınıf dengesi.
- Eğitim, doğrulama ve test veri setleri (Kaggle'daki “Chest X-Ray (Pneumonia)” veri kümesi kullanılmıştır).
- Model performans değerlendirme metrikleri: Accuracy, Precision, Recall ve F1-Score.

---

## 🎯 Performans (Örnek)

Test veri seti üzerinde model performansı:

| Metrik                     | Değer  |
|----------------------------|--------|
| Accuracy                   | %95    |
| Precision (Pnömoni sınıfı) | %94    |
| Recall                     | %93    |
| F1-Score                   | %93.5  |

---

## ⚠️ Dataset Kaynağı

- Veri seti: Kaggle “Chest X-Ray Images (Pneumonia)”
- Yaklaşık 5.800 röntgen görüntüsü içerir.
- İki sınıf: “Pneumonia” ve “Normal”.

---

## 🔧 Geliştirme ve Özelleştirme Fırsatları

- Farklı CNN mimarileri (örneğin ResNet, VGG, DenseNet) veya transfer learning teknikleri uygulanabilir.
- Veri artırımı (augmentation) ile overfitting önlenebilir.
- Grad-CAM veya SHAP gibi XAI teknikleriyle model açıklanabilirliği geliştirilebilir.
- Model bir web uygulamasına (Flask, Streamlit ile) entegre edilebilir.

---

## 📚 Kaynaklar / Referanslar

- Transfer learning ile pnömoni tespiti: AlexNet, ResNet18, DenseNet201 gibi modeller %98 doğruluk puanına ulaşmıştır (Arxiv, MDPI).
- Modeller karşılaştırma çalışmaları: VGG19, ResNet-152 gibi mimariler %95 üzeri başarı sağlar (Arxiv).
- Model açıklama yaklaşımları: Grad-CAM gibi teknikler ile görselleştirme yapılabilir (GitHub).



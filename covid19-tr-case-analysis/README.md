# Covid-19 Türkiye Vaka Tahmin Projesi

Bu proje, Türkiye’deki Covid-19 vaka sayılarını analiz ederek gelecek günler için vaka tahminleri yapılmasını amaçlamaktadır. Makine öğrenmesi algoritmaları kullanılarak veriler üzerinde analiz ve modelleme gerçekleştirilmiştir.

---

## 📌 Proje Amacı

Covid-19 pandemisinin yayılımını anlamak ve gelecekteki olası vaka sayılarını tahmin etmek amacıyla:
- Günlük vaka verilerini analiz etmek
- Verilerdeki değişimleri görselleştirmek
- Bir tahmin modeli oluşturarak gelecek günler için vaka sayısı öngörmek hedeflenmiştir.

---

## 🧠 Kullanılan Yöntem ve Teknolojiler

Bu projede Python programlama dili kullanılmış olup aşağıdaki kütüphanelerden faydalanılmıştır:

- **Pandas** – Veri yükleme ve işleme
- **NumPy** – Sayısal işlemler
- **Matplotlib & Seaborn** – Görselleştirme
- **Scikit-learn** – Makine öğrenmesi algoritmaları (özellikle `MLPRegressor`)
- **Jupyter Notebook** – Kodların çalıştırıldığı ortam

---

## 🔢 Kullanılan Veri Kümesi

Veri kümesi, Türkiye’ye ait günlük Covid-19 vaka sayılarını içermektedir. Veriler;
- Günlük toplam vaka sayısı
- Toplam test sayısı
- Toplam iyileşen ve vefat eden sayıları
gibi çeşitli istatistikleri içermektedir.

> Not: Veri seti açık kaynaklı olup [Kaggle](https://www.kaggle.com/) veya benzeri platformlardan temin edilmiştir.

---

## 🔍 Yapılan Analizler

- Eksik veri kontrolü ve temizlenmesi
- Vaka sayılarının zamana göre görselleştirilmesi
- Test-vaka ilişkilerinin incelenmesi
- Eğitim ve test veri kümelerinin oluşturulması
- Yapay sinir ağı modeli (`MLPRegressor`) ile tahmin
- Model başarımının değerlendirilmesi (MSE, R² gibi metriklerle)

---

## 📊 Model Sonuçları

Model eğitildikten sonra aşağıdaki gibi metriklerle değerlendirilmiştir:
- Ortalama Kare Hata (MSE)
- R-kare Skoru (R²)
- Tahmin grafikleri ve gerçek değerler ile karşılaştırmalı görseller

---

## 📁 Proje Dosyaları

- `COVID_19_turkiye.ipynb` – Jupyter Notebook içerisinde analiz ve modelleme adımları yer almaktadır.
- `README.md` – Bu açıklama dosyasıdır.

---

## ⚠️ Uyarılar

- Bu model yalnızca eğitim amaçlıdır ve profesyonel tıbbi/tahminsel kararlar için kullanılmamalıdır.
- Gerçek vaka verilerinin güvenilirliğini her zaman kontrol etmek önemlidir.

---

## 📌 Katkıda Bulunmak

Proje geliştirilmeye açıktır. Her türlü öneri, katkı veya hata bildirimi için pull request ya da issue açabilirsiniz.


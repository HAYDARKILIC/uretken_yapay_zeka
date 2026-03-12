# 🤖 Üretken Yapay Zeka — Ders Notları ve Uygulamalı Notebook'lar

**Haydar Kılıç | Mühendislik Fakültesi, Yapay Zeka Mühendisliği**

Bu repo, *Üretken Yapay Zeka* dersinin teorik slayt içeriklerini Python ile pekiştiren Jupyter Notebook'larını barındırmaktadır. Her notebook, derste işlenen formülleri sıfırdan türeterek görselleştirir ve gerçek veri senaryolarına uyarlar.

---

## 📚 İçerik

| Ders | Konu | Notebook |
|------|------|----------|
| Ders 1 | Üretken Modelleme Temelleri | [`UYZ_Ders1_Notebook.ipynb`] |

> Yeni dersler eklendikçe tablo güncellenecektir.

---

## 🗂 Ders 1 — Üretken Modelleme Temelleri

### Ele Alınan Konular

**Bölüm 1 — Temel Kavramlar**
- El yazısı rakam tanıma: 28×28 piksel vektör temsili, eğitim/test/doğrulama ayrımı
- Polinom regresyon ve eğri uydurma (Vandermonde matrisi, En Küçük Kareler)
- Overfitting / Underfitting ve RMS hata analizi
- Ridge Regularization (L2 cezası, λ hiperparametresi)

**Bölüm 2 — Olasılık Teorisi**
- Bileşik, marjinal ve koşullu olasılık dağılımları
- Bayes teoremi — hasta teşhisi ve *base rate fallacy*
- Gaussian (Normal) dağılım: PDF, CDF, sayısal doğrulama
- Maksimum Olabilirlik Tahmini (MLE) ve yanlılık
- Bayesçi güncelleme: madeni para atışı ile önsel → sonsal

**Bölüm 3 — Karar Teorisi**
- Minimum hata karar sınırları ve sonsal olasılıklar
- Reddetme seçeneği (Reject Option) ve θ eşiği
- Asimetrik kayıp matrisi (tıbbi tanı senaryosu)
- Üretken / Ayrıştırıcı / Diskriminant model karşılaştırması

---

## ⚙️ Kurulum

```bash
# Depoyu klonla
git clone https://github.com/HAYDARKILIC/uretken_yapay_zeka.git
cd uretken_yapay_zeka

# Sanal ortam oluştur (önerilir)
python -m venv venv
source venv/bin/activate        # Linux/macOS
# venv\Scripts\activate         # Windows

# Bağımlılıkları yükle
pip install -r requirements.txt

# Jupyter'ı başlat
jupyter notebook
```

---

## 📦 Gereksinimler

```
numpy>=1.24
matplotlib>=3.5
scipy>=1.9
scikit-learn>=1.0
jupyter>=1.0
```

> `requirements.txt` dosyası repoya eklenmiştir.

---

## 🏗 Proje Yapısı

```
uretken-yapay-zeka/
├── README.md
├── requirements.txt
├── UYZ_Ders1_Notebook.ipynb   # Ders 1 — Temel Kavramlar
└── (ilerleyen derslere ait notebook'lar eklenecek)
```

---

*Üretken Yapay Zeka — Haydar Kılıç, Yapay Zeka Mühendisliği*

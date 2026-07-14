# ⚡ ACV Energy Case Study 02

## 📌 Proje Hakkında

Bu depo, **ACV Energy Case Study 02** kapsamında hazırlanmış veri analizi çalışmasını içermektedir.

Çalışmada elektrik tüketim ve tahsilat verileri Python kullanılarak analiz edilmiş, veri kalitesi incelenmiş, görselleştirmeler oluşturulmuş, müşteri segmentasyonu yapılmış ve elde edilen bulgular iş içgörülerine dönüştürülmüştür.

---

# 📂 Proje Yapısı

```
ACV-ENERGY-case-study-02
│
├── README.md
├── requirements.txt
│
├── notebooks
│   ├── notebook_01_veri_kesfi.ipynb
│   ├── notebook_02_gorsellestirme.ipynb
│   └── notebook_03_veri_hikayesi.ipynb
│
├── notebook1_outputs
├── notebook2_outputs
└── notebook3_outputs

---

# 📚 Notebook İçerikleri

## 📒 Notebook 01 – Veri Keşfi ve Veri Kalitesi

Bu notebookta;

- Veri dosyaları okunmuştur.
- Sütun isimleri standartlaştırılmıştır.
- Veri tipleri düzenlenmiştir.
- Eksik değer analizi yapılmıştır.
- Mükerrer kayıtlar incelenmiştir.
- Negatif ve aykırı tüketimler analiz edilmiştir.
- Temiz veri setleri oluşturulmuştur.
- İstatistiksel özet raporları hazırlanmıştır.

---

## 📒 Notebook 02 – Görselleştirme ve Keşifsel Veri Analizi

Bu notebookta;

- Tüketim dağılımları incelenmiştir.
- Histogram, Boxplot, KDE ve ECDF grafikleri oluşturulmuştur.
- İlçeler karşılaştırılmıştır.
- Hesap sınıfları analiz edilmiştir.
- Aylık tüketim eğilimleri incelenmiştir.
- Karşılaştırmalı grafikler hazırlanmıştır.
- Kurumsal rapor tabloları oluşturulmuştur.

---

## 📒 Notebook 03 – Veri Hikâyesi ve İş Analizi

Bu notebookta;

- İlçeler arasındaki tüketim farklılıkları yorumlanmıştır.
- Müşteri davranışları analiz edilmiştir.
- Risk skoru oluşturulmuştur.
- Müşteri segmentasyonu yapılmıştır.
- Yönetici özeti hazırlanmıştır.
- İş geliştirme önerileri sunulmuştur.

---

# 📊 Kullanılan Teknolojiler

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- OpenPyXL
- Jupyter Notebook

---

# 📁 Veri Seti

Case kapsamında paylaşılan orijinal veri dosyaları (`veri_1.csv` – `veri_5.csv`) bu GitHub deposuna eklenmemiştir.

Veri dosyaları  jupyterde çalışmayı kolaylaştırmak amacıyla her sayfa ayrı csv formatına dönüştürülmüş ve öyle kullanılmıiştır. Organizatörlerin yönlendirmesi doğrultusunda bu orijinal veri dosyaları GitHub reposunda paylaşılmamıştır.

Bu nedenle projede yalnızca notebooklar, analiz çıktıları ve oluşturulan raporlar yer almaktadır.

## Büyük Çıktı Dosyaları Hakkında

Notebook 01 çalıştırıldığında aşağıdaki ara veri dosyaları başarıyla oluşturulmaktadır:

- `temizlenmis_veri.csv`
- `pozitif_tuketim_verisi.csv`
- `tahakkuk_isaretli_tam_veri.csv`

Bu dosyalar, orijinal veri setinin işlenmiş türevlerini içermekte olup dosya boyutlarının oldukça büyük olması nedeniyle GitHub deposuna eklenmemiştir.
Bu nedenle GitHub reposunda yalnızca analiz sonuçlarını, özet raporları, görselleştirmeleri ve proje çıktıları paylaşılmıştır.
Not: Bu dosyalar ilgili notebook çalıştırıldığında otomatik olarak yeniden oluşturulmaktadır.

# 💻 Çalıştırma Ortamı

Notebooklar Windows işletim sistemi üzerinde geliştirilmiş ve test edilmiştir.

Kod içerisinde kullanılan veri yolları geliştirme ortamına aittir.

Örneğin;

```python
C:\Users\...\Downloads\veri_1.csv
```

Projeyi farklı bir bilgisayarda çalıştıracak kullanıcıların, notebooklarda yer alan veri yollarını kendi bilgisayarlarına göre güncellemeleri gerekmektedir.

---

# 📦 Kurulum

Gerekli Python paketlerini yüklemek için:

```bash
pip install -r requirements.txt
```

---

# 📈 Üretilen Çıktılar

Proje kapsamında aşağıdaki çıktılar oluşturulmuştur.

- Temizlenmiş veri setleri
- İstatistiksel özet raporları
- İlçe bazlı analizler
- Görselleştirmeler
- Müşteri segmentasyonu
- Risk analizleri
- Excel raporları
- İş önerileri

Tüm çıktılar **outputs/** klasörü altında yer almaktadır.

---
# 📊 Örnek Çıktılar

## 1. Tüketim Histogramı

![Tüketim Histogramı](notebook2_outputs/grafik2_1_tuketim_histogram.png)

---

## 2. Tüketim Boxplot

![Tüketim Boxplot](notebook2_outputs/grafik2_2_tuketim_boxplot.png)

---

## 3. İlçelere Göre Toplam Tüketim

![İlçe Toplam Tüketim](notebook2_outputs/grafik3_1_ilce_toplam_tuketim.png)

---

## 4. Hesap Sınıfı Dağılımı

![Hesap Sınıfı](notebook2_outputs/grafik_7_hesap_sinifi_dagilim.png)

---

## 5. İlçelerin Tüketim Payı

![İlçe Payı](notebook2_outputs/grafik3_3_ilce_pay_pasta.png)

# 📝 Not

Bu çalışma **ACV Energy Case Study 02** kapsamında hazırlanmıştır.

Orijinal veri dosyaları organizatörlerin yönlendirmesi doğrultusunda GitHub deposuna eklenmemiştir.
## 👩‍💻 Geliştirici

Hatice Gül Uzun

ACV Energy Case Study 02

Python • Pandas • NumPy • Matplotlib • Seaborn

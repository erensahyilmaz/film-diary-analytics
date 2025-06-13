# 🎬 Film Analizi: Eren vs Şevval

Bu proje, iki farklı film izleyicisinin günlüklerini karşılaştırmalı olarak analiz ederek film tercihleri, puanlama alışkanlıkları ve ortak beğeniler hakkında içgörüler sunar.

## 📊 Proje Özeti

Bu analiz projesi, Eren ve Şevval'in film izleme alışkanlıklarını çeşitli açılardan karşılaştırır:
- Film türü tercihleri
- Puanlama dağılımları
- Ortalama puanlar
- Ortak izlenen filmler

## 🛠️ Kullanılan Teknolojiler

- **Python**: Ana programlama dili
- **Pandas**: Veri manipülasyonu ve analiz
- **Matplotlib**: Görselleştirme
- **Seaborn**: İstatistiksel görselleştirme
- **Google Colab**: Geliştirme ortamı

## 📁 Veri Seti

Projede kullanılan veri setleri:
- `diary_with_genres.csv` - Eren'in film günlüğü
- `diary_with_genres_sevval.csv` - Şevval'in film günlüğü

### Veri Yapısı
- **Date**: Film izlenme tarihi
- **Film**: Film adı
- **Rating**: Yıldız sistemi ile verilen puan
- **Genres**: Film türleri (virgülle ayrılmış)

## 🔍 Analiz Adımları

### 1. Veri Ön İşleme
- Tarih formatı standardizasyonu
- Yıldız puanlarının sayısal değerlere dönüştürülmesi
- Film türlerinin ayrıştırılması (explode işlemi)
- Eksik değer kontrolü

### 2. Keşifsel Veri Analizi (EDA)
- Her iki kullanıcı için film türü dağılımları
- Puanlama histogramları
- Türlere göre ortalama puanlar

### 3. Karşılaştırmalı Analiz
- İki kullanıcının tür tercihlerinin karşılaştırılması
- Ortalama puanların yan yana görselleştirilmesi
- Ortak izlenen filmlerin belirlenmesi

## 📈 Temel Bulgular

### ![indir (47)](https://github.com/user-attachments/assets/d63e9805-da2b-453a-9c9f-756bc5b8ad86)
*En Çok İzlenen Film Türleri - Eren*
<!-- Eren'in en çok izlediği türlerin bar grafiği -->

### ![indir (48)](https://github.com/user-attachments/assets/b49ad125-b22c-4cda-8cab-0fb4dc02e15a)

*En Çok İzlenen Film Türleri - Şevval*
<!-- Şevval'in en çok izlediği türlerin bar grafiği -->

### ![indir (49)](https://github.com/user-attachments/assets/b64a10a3-229d-4c90-b38d-c8a3045fe432)

*Türlere Göre Ortalama Puanlar - Eren*
<!-- Eren'in türlere verdiği ortalama puanlar -->

### ![indir (50)](https://github.com/user-attachments/assets/f6fa164d-31a9-4de1-839b-04cbb811c0d0)

*Türlere Göre Ortalama Puanlar - Şevval*
<!-- Şevval'in türlere verdiği ortalama puanlar -->

### ![indir (51)](https://github.com/user-attachments/assets/c4a080db-9db2-448a-a30f-f3a4d0040667)

*Karşılaştırmalı Tür Analizi*
<!-- İki kullanıcının tür tercihlerinin yan yana karşılaştırması -->


## 📋 Çıktılar

Proje sonunda şu dosyalar oluşturulmuştur:
- `common_movies.xlsx`: Ortak izlenen filmler ve puanları

## 🚀 Gelecek Geliştirmeler

- [ ] Zaman serisinde film izleme trendleri analizi
- [ ] Makine öğrenmesi ile film öneri sistemi
- [ ] İstatistiksel hipotez testleri
- [ ] Interactive dashboard geliştirme
- [ ] Daha fazla kullanıcı verisi ekleme

## 🤝 Katkıda Bulunma

Bu proje açık kaynak kodludur. Geliştirme önerilerinizi paylaşabilir, yeni özellikler ekleyebilirsiniz.

## 📞 İletişim

- **Geliştirici**: [Eren Şahyılmaz]
- **Email**: [erensahyilmaz@gmail.com]
- **LinkedIn**: [[LinkedIn Profili](https://www.linkedin.com/in/eren-sahyilmaz/)]

## 📄 Lisans

Bu proje [Lisans Türü] lisansı altında paylaşılmıştır.

---

### 🎭 "Film, hayatın bir aynasıdır; sadece daha iyi senaryosu vardır." - Unknown

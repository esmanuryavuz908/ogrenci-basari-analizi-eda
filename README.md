# 📊 Öğrenci Sınav Başarı Analizi (Student Performance EDA)

Bu proje, öğrencilerin sınav notları, çalışma saatleri ve devamsızlık oranları arasındaki ilişkileri Python kullanarak inceleyen bir Keşifçi Veri Analizi (EDA) çalışmasıdır.

## 🎯 Projenin Amacı
Bir sınıftaki öğrencilerin akademik başarılarını analiz etmek, hangi faktörlerin (çalışma saati, devamlılık vb.) başarıyı etkilediğini anlamak ve not dağılımlarını görselleştirerek anlamlı içgörüler çıkarmak hedeflenmiştir.

## 📁 Veri Seti İçeriği
Analiz edilen veri setinde aşağıdaki temel değişkenler bulunmaktadır:
* **Demografik Bilgiler:** `Age`, `Gender`
* **Ders Notları:** `MathScore`, `PhysicsScore`, `ProgrammingScore`
* **Akademik Alışkanlıklar:** `StudyHours` (Çalışma Saati), `Attendance` (Devamlılık Oranı)

## 🛠️ Kullanılan Teknolojiler
* **Python**
* **Pandas & NumPy** (Veri okuma, manipülasyon ve hesaplamalar)
* **Matplotlib & Seaborn** (Veri görselleştirme)

## 📈 Yapılan İşlemler (Adım Adım)
1. **Keşifçi Veri Analizi (EDA):** Veri setinin yapısal incelenmesi, eksik verilerin kontrolü ve temel istatistiksel analizler (ortalama, en yüksek/en düşük notlar).
2. **Özellik Mühendisliği (Feature Engineering):** 
   * Her öğrenci için tüm derslerin ortalamasını hesaplayarak yeni bir `AverageScore` sütunu oluşturulması.
   * Öğrencilerin ortalamalarına göre bir fonksiyon yazılarak kategorize edilmesi ve `SuccessLevel` (Başarısız, Orta, İyi, Çok İyi) sütununun eklenmesi.
3. **Veri Görselleştirme:**
   * Matematik notlarının dağılım histogramı.
   * Başarı seviyelerinin ve derslere göre ortalama notların çubuk grafikleri (Bar plot).
   * Çalışma saati ile başarı arasındaki ilişkinin dağılım grafiği (Scatter plot).

## 🚀 Projeyi Çalıştırma
Bu projeyi kendi bilgisayarınızda çalıştırmak için:
1. Repoyu bilgisayarınıza klonlayın: `git clone https://github.com/esmanuryavuz908/ogrenci-basari-analizi-eda.git`
2. Gerekli kütüphaneleri yükleyin: `pip install pandas numpy matplotlib seaborn`
3. `Öğrenci Sınav Başarı Analizi.ipynb` dosyasını Jupyter Notebook veya VS Code üzerinden açarak hücreleri çalıştırın.

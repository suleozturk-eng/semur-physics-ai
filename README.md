# ⚡ SEMUR — Autonomous Local Physics-AI Engineer

**S**urrogate **E**ngineering **M**odel for **U**nified **R**easoning | *Zero-Cloud, Zero-Footprint Deterministic & ML Physics Engine*

> 🌐 *[Türkçe dokümantasyon için aşağı kaydırın / Scroll down for Turkish documentation](#türkçe-dokümantasyon)*

---

## 🇬🇧 English Documentation

**SEMUR** is a **SVR (Support Vector Regression)**-based surrogate physics engine trained on 3D Computational Fluid Dynamics (CFD - $k\text{-}\omega$ SST) simulation data. It performs thermal analysis and cooling optimization in milliseconds via natural language commands—without requiring cloud connectivity or heavy computational overhead.

### 🚀 Key Features
* **100% Local & Standalone Architecture:** Runs completely offline with zero external APIs or cloud dependencies.
* **Hybrid NLP Engineering Console:** Automatically parses engineering queries (*Watt, m/s, °C*) from natural language and feeds them into the physics solver.
* **High-Precision Thermal Prediction:** Predicts steady-state cabinet temperatures with `±0.15 °C (MAE)` accuracy within `0.1–2.5 m/s` air velocity and `1000–5000 W` thermal load boundary conditions.
* **Smart Cooling & Energy Optimization:** Finds the minimum air velocity required to maintain a target temperature based on the fan affinity cube law ($P \propto v^3$) and calculates energy savings.

### 🛠️ Installation & Usage

1. **Clone the repository:**
   ```bash
   git clone https://github.com
   cd semur-physics-ai
   ```

2. **Install required dependencies:**
   ```bash
   pip install streamlit numpy matplotlib joblib scikit-learn
   ```

3. **Run the application:**
   * **Windows Users:** Double-click the `baslat.bat` file in the root directory to launch the app directly.
   * **Manual Launch (Terminal):**
     ```bash
     streamlit run app.py
     ```

### 💬 Example Console Prompts
* **Optimization Analysis:** *"3600 W ısı yükü altında sıcaklığı 44 °C altında tutacak en düşük hava hızını bul."* *(Find the lowest air velocity to keep temperature below 44 °C under 3600 W load.)*
* **State Prediction:** *"4500 W yük ve 1.8 m/s hava hızında kabin sıcaklığı kaç °C olur?"* *(What is the cabinet temperature at 4500 W load and 1.8 m/s air velocity?)*

---

## 🇹🇷 Türkçe Dokümantasyon

**SEMUR**, 3D Hesaplamalı Akışkanlar Dinamiği (CFD - $k\text{-}\omega$ SST) simülasyon verileriyle eğitilmiş **SVR (Support Vector Regression)** tabanlı bir Surrogate (vekil) fizik motorudur. Bulut bağlantısına veya ağır hesaplama maliyetlerine ihtiyaç duymadan, doğal dil komutlarıyla milisaniyeler içinde termal analiz ve soğutma optimizasyonu gerçekleştirir.

### 🚀 Öne Çıkan Özellikler
* **%100 Yerel ve Bağımsız Mimari:** Harici API veya bulut bağımlılığı olmadan tamamen yerel ortamda çalışır.
* **Hibrit NLP Mühendislik Konsolu:** Doğal dildeki mühendislik sorularını (*Watt, m/s, °C*) otomatik ayrıştırarak fiziksel çözücüye aktarır.
* **Yüksek Hassasiyetli Termal Tahmin:** `0.1–2.5 m/s` hava hızı ve `1000–5000 W` termal yük sınır koşullarında `±0.15 °C (MAE)` hassasiyetle kararlı hal sıcaklık tahmini yapar.
* **Akıllı Soğutma & Enerji Optimizasyonu:** Fan güç tüketimi küp yasasını ($P \propto v^3$) baz alarak hedef sıcaklığı koruyan en düşük hava hızını bulur ve enerji tasarruf oranını hesaplar.

### 🛠️ Kurulum ve Çalıştırma

1. **Projeyi bilgisayarınıza indirin:**
   ```bash
   git clone https://github.com
   cd semur-physics-ai
   ```

2. **Gerekli kütüphaneleri yükleyin:**
   ```bash
   pip install streamlit numpy matplotlib joblib scikit-learn
   ```

3. **Uygulamayı başlatın:**
   * **Windows Kullanıcıları:** Klasör içindeki `baslat.bat` dosyasına çift tıklayarak uygulamayı doğrudan başlatabilirsiniz.
   * **Manuel Başlatma (Terminal):**
     ```bash
     streamlit run app.py
     ```

### 💬 Örnek Konsol Komutları
* **Optimizasyon Analizi:** *"3600 W ısı yükü altında sıcaklığı 44 °C altında tutacak en düşük hava hızını bul."*
* **Durum Tahmini:** *"4500 W yük ve 1.8 m/s hava hızında kabin sıcaklığı kaç °C olur?"*



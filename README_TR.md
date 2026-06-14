# İnsan Kaynakları Analitik Dashboard | Power BI

Bu proje, IBM HR Analytics veri seti kullanılarak hazırlanmış 
çok sayfalı bir Power BI raporudur. Temel amaç, çalışan kaybını 
(attrition) analiz etmek ve yüksek riskli çalışanları belirlemektir.

📄 [Click here for English README](README.md)

## Sayfalar

### 1. Attrition Overview
Departman, iş rolü, fazla mesai, hisse senedi opsiyonu ve 
terfi süreci bazında attrition analizi.

![Attrition Overview](HR1.png)

### 2. Employee Demographics
Yaş dağılımı, cinsiyet, departman ve eğitim alanı bazında 
çalışan profili analizi.

![Employee Demographics](HR2.png)

### 3. Satisfaction & Risk Factors
Birleştirilmiş risk skoru modeli, çevre memnuniyeti, iş 
bağlılığı ve tahmini attrition maliyeti analizi.

![Satisfaction & Risk Factors](HR3.png)

## Öne Çıkan Özellikler

- **Risk Score Modeli**: Her çalışan için 0-4 arası risk skoru 
  (fazla mesai, hisse opsiyonu, terfi süreci, iş memnuniyeti)
- **Tahmini Attrition Maliyeti**: $9.2M yıllık maliyet tahmini
- **Yüksek Riskli Çalışan Tablosu**: HR ekibinin direkt aksiyon 
  alabileceği 127 çalışan listesi
- 3 sayfalı interaktif navigasyon

## Temel Bulgular

- Fazla mesai yapan çalışanların attrition oranı (**%30**), 
  yapmayanlara (**%10**) kıyasla 3 kat daha yüksek
- Hisse senedi opsiyonu olmayan çalışanlarda attrition oranı 
  **%25** iken, opsiyon seviyesi 3 olanlarda bu oran **%5**'e düşüyor
- 6-10 yıl terfi alamamış çalışanlar en yüksek attrition riskini 
  taşıyor (**%18**)
- Sales Representative rolü en yüksek attrition oranına sahip (**%40**)
- Risk skoru 4 olan çalışanların **%60**'ı şirketten ayrılmış — 
  modelin tahmin gücünü doğruluyor
- Toplam 127 çalışan yüksek risk (skor ≥ 3) kategorisinde

## Kullanılan Araçlar

- Power BI Desktop
- DAX
- Power Query

## Veri Kaynağı

IBM HR Analytics Employee Attrition Dataset — Kaggle

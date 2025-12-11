#Turkish
# SQL_to_PowerBI_Profit_Risk
# 🚀 PROJE BAŞLIĞI: FINANSAL RİSK VE KÂRLILIK ANALİZİ (SQL & POWER BI)

## 🎯 PROJE AMACI
Bir perakende şirketinin ürün kategorileri bazında **operasyonel risk (hata sayısı)** ve **finansal performans (ortalama kâr marjı)** arasındaki ilişkiyi tespit etmek ve yönetim için eylem önceliklerini belirlemek.

## 🛠️ KULLANILAN TEKNOLOJİLER
* **Veritabanı Dili:** MySQL / PostgreSQL (Analiz ve Veri Çekme)
* **Görselleştirme:** Power BI Desktop (Dashboard Geliştirme)
* **Versiyon Kontrolü:** GitHub

## 📊 ANALİZ VE METRİKLER (SQL AŞAMASI)
1.  **Veri Birleştirme (JOIN):** İşlem verileri ve Ürün tanımları tabloları, `urun_id` üzerinden birleştirilmiştir.
2.  **Kar Marjı Hesabı:** Her kategori için ortalama kâr marjı (`AVG(satis_fiyati - maliyet)`) hesaplanmıştır.
3.  **Risk Tespiti:** Her kategori için toplam hata sayısı (`SUM(hata_durumu)`) hesaplanmıştır.
4.  **Kritik Sorgu (Örnek):** (Buraya nihai SQL sorgunu kopyala.)

## 📈 SONUÇLAR VE İŞ KARARLARI
Analiz sonucunda, kategoriler kârlılıklarına göre sıralandığında aşağıdaki kritik sonuçlar elde edilmiştir:
* **Kırmızı Alarm (En Yüksek Risk):** **Sarf Malzemesi** kategorisi, hata sayısı yüksek olmasına rağmen **en düşük ortalama kâr marjına ($11.6 \text{M}$) sahiptir**. Yönetime bu kategorinin süreçleri acilen iyileştirilmesi tavsiye edilmiştir.
* **Gümüş Fırsat:** Yüksek Maliyetli Ürünler, en yüksek kâra ($150 \text{M}$) sahip olmasına rağmen hata üretmektedir. Hataların sıfırlanması, kârı daha da artıracaktır.

## 🖼️ GÖRSEL KANIT (POWER BI DASHBOARD)
(Buraya Power BI Dashboard'unun ana ekran görüntüsünü [image\_483ef5.png'deki gibi] ekle.)




#English
# SQL_to_PowerBI_Profit_Risk
# 🚀 PROJECT TITLE: FINANCIAL RISK AND PROFITABILITY ANALYSIS (SQL & POWER BI)

## 🎯 PROJECT OBJECTIVE
To identify the relationship between **operational risk (error count)** and **financial performance (average profit margin)** across a retail company's product categories, and to determine action priorities for management.

## 🛠️ TECHNOLOGIES USED
* **Database Language:** MySQL / PostgreSQL (Analysis and Data Extraction)
* **Visualization:** Power BI Desktop (Dashboard Development)
* **Version Control:** GitHub

## 📊 ANALYSIS AND METRICS (SQL PHASE)
1.  **Data Joining (JOIN):** Transaction data and Product definition tables were joined using `product_id`.
2.  **Profit Margin Calculation:** The average profit margin (`AVG(sales_price - cost)`) was calculated for each category.
3.  **Risk Identification:** The total error count (`SUM(error_status)`) was calculated for each category.
4.  **Critical Query (Example):** (Insert the final SQL query here.)

## 📈 RESULTS AND BUSINESS DECISIONS
Following the analysis, the following critical conclusions were drawn by prioritizing categories based on profitability:
* **Red Flag (Highest Risk):** The **Consumables** category has the highest error count but the **lowest average profit margin ($\$11.6 \text{M}$)**. Management was advised to urgently improve the processes for this category.
* **Silver Opportunity:** High-Value Products generate the highest profit ($\$150 \text{M}$) but also produce errors. Eliminating these errors would further increase the overall profitability.

## 🖼️ VISUAL EVIDENCE (POWER BI DASHBOARD)
(Insert the main screenshot of the Power BI Dashboard here, focusing on the Line and Stacked Column Chart.)

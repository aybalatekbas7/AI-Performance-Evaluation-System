# Yapay Zeka Destekli Personel Performans Değerlendirme Sistemi 🚀

Bu proje, Yönetim Bilişim Sistemleri (YBS) süreçlerindeki performans değerlendirme adımlarını otomatize etmek amacıyla geliştirilmiş kodsuz (no-code) bir sistem mimarisidir.

## 🛠️ Kullanılan Teknolojiler
* **Notion:** İlişkisel Veritabanı Yönetimi (RDBMS)
* **Zapier:** API Entegrasyonu ve İş Akışı Otomasyonu (Workflow Automation)
* **AI by Zapier (OpenAI):** Doğal Dil İşleme (NLP) ve Duygu Analizi

## ⚙️ Sistem Nasıl Çalışır?
1. **Tetikleyici (Trigger):** Yönetici, Notion veritabanına çalışan hakkında serbest metin formatında bir değerlendirme girer.
2. **İşleme (Action):** Zapier, bu yeni veriyi anında yakalar ve NLP modeline gönderir. Yapay zeka, metni 3 cümlelik objektif bir özete dönüştürür ve 1-10 arası bir performans skoru belirler.
3. **Güncelleme (Update):** Üretilen özet ve skor, Zapier aracılığıyla hedef Notion tablosundaki ilgili satıra otomatik olarak geri yazılır.

## 📄 Akademik Raporlar
Projenin mimarisini ve analizini içeren detaylı teknik raporlara (IEEE formatında) repo içindeki DOCX dosyalarından ulaşabilirsiniz:
* `Performance_Report_TR.docx`
* `Performance_Report_EN.docx`

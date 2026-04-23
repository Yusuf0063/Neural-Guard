# 🛡️ Neural-Guard

Neural-Guard, yapay zekayı siber güvenlik ile buluşturan bir analiz aracıdır. Geleneksel yöntemlerin aksine, bu model siber tehditleri kelime kelime değil, **anlamsal (semantik)** olarak tespit eder.

## ✨ Özellikler
- **Hibrit Tespit:** Hem zararlı URL'leri hem de tehlikeli sistem komutlarını tanır.
- **Güçlü Mimari:** NLP dünyasının lideri **DistilBERT** (Transformer) mimarisini kullanır.
- **Yüksek Performans:** Eğitim sonuçlarına göre ~%96+ başarı oranı sergiler.

## 🛠️ Teknik Detaylar
Bu proje, şu veri setleri birleştirilerek (hybrid) eğitilmiştir:
1. **Malicious URLs Dataset:** Phishing ve malware içeren 650.000+ URL.
2. **Linux Terminal Commands:** Standart sistem yönetimi komutlarını içeren JSONL veri seti[cite: 1].

## 🚀 Hızlı Başlangıç
1. Kütüphaneleri kurun: `pip install -r requirements.txt`
2. Uygulamayı çalıştırın: `streamlit run app.py`

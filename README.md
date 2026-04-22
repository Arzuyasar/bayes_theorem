📊 Bayes Theorem - Weather & Play Prediction

📌 Proje Açıklaması
Bu proje, Bayes Teoremi kullanılarak hava durumu verilerine göre bir maçın oynanma olasılığını hesaplamayı amaçlamaktadır.

Weather ve Play verileri kullanılarak:
- Prior (önsel olasılık)
- Likelihood (koşullu olasılık)
- Posterior (sonradan güncellenmiş olasılık)

hesaplanmış ve Bayes Teoremi sayısal olarak doğrulanmıştır.

🎯 Amaç
- Bayes Teoremi’nin mantığını anlamak
- Olasılıkların nasıl güncellendiğini görmek
- Veri üzerinden manuel hesaplama yapmak

📊 Kullanılan Veri

| Weather  | Play |
|----------|------|
| Sunny    | No   |
| Sunny    | No   |
| Overcast | Yes  |
| Rain     | Yes  |
| Rain     | Yes  |
| Rain     | No   |
| Overcast | Yes  |
| Sunny    | No   |
| Sunny    | Yes  |
| Rain     | Yes  |

🧠 Kullanılan Formül

Bayes Teoremi:

P(Play | Weather) = (P(Weather | Play) × P(Play)) / P(Weather)

🔍 Hesaplama Adımları

1. Prior (Önsel Olasılık)
- P(Play = Yes)
- P(Play = No)

2. Likelihood
- P(Weather | Play = Yes)
- P(Weather | Play = No)

3. Evidence
- P(Weather)

4. Posterior
- P(Play = Yes | Weather)

📈 Sonuçlar

- Sunny iken maç oynanma olasılığı: 0.25
- Rain iken maç oynanma olasılığı: 0.75

Bu sonuçlar, Bayes Teoremi kullanılarak hesaplanmıştır.

📦 Kullanılan Teknolojiler
- Python
- NumPy
- Pandas
- Jupyter Notebook


🚀 Nasıl Çalıştırılır

```bash
pip install numpy pandas notebook
jupyter notebook

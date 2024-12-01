# 🎙️ Türkçe Podcast Oluşturucu

Türkçe web içeriğini otomatik olarak podcast'e dönüştüren yapay zeka destekli bir araç.

## 📋 Özellikler
- Türkçe web sayfalarından otomatik içerik çıkarma
- Yapay zeka ile metin optimizasyonu
- Doğal dil işleme
- Yüksek kaliteli ses sentezi

## 🚀 Başlangıç

### Gereksinimler
- Python 3.11+
- FFmpeg
- API Anahtarları (OpenAI, Google, ElevenLabs)

### Kurulum
```bash
git clone https://github.com/hiktan44/turkce-podcast.git
cd turkce-podcast
pip install -r requirements.txt
```
[Detaylı kurulum kılavuzu için tıklayın](docs/KURULUM.md)

## 📖 Kullanım
```python
from podcast_generator import create_podcast

# Web sayfasından podcast oluştur
podcast = create_podcast("https://example.com/makale")
```

## 🔧 Yapılandırma
API anahtarlarınızı .env dosyasında saklayın:
```
OPENAI_API_KEY=your-key
GOOGLE_API_KEY=your-key
ELEVENLABS_KEY=your-key
```

## 📚 Dokümantasyon
- [Kurulum Kılavuzu](docs/KURULUM.md)
- [API Referansı](docs/API.md)
- [Örnekler](docs/ORNEKLER.md)

## 🤝 Katkıda Bulunma
Katkılarınızı bekliyoruz! [CONTRIBUTING.md](CONTRIBUTING.md) dosyasını inceleyin.

## 📝 Lisans
Bu proje MIT lisansı altında lisanslanmıştır.

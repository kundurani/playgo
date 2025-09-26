# DiziFun Visual

Bu proje, çeşitli streaming platformlarındaki dizileri otomatik olarak tarayıp M3U formatında listeler oluşturur.

## Desteklenen Platformlar

- Netflix
- Amazon Prime
- BluTV
- Disney+
- EXXEN
- GAiN
- HBO Max
- Hulu
- Paramount+
- TOD TV
- Unutulmaz Diziler

## Özellikler

- TMDb API entegrasyonu ile zengin metadata
- Platform bazlı gruplandırma
- SxxExx formatında bölüm numaralandırma
- Otomatik güncellemeler (12 saatte bir)
- Proxy sistemi ile sorunsuz erişim

## Kurulum

1. Gerekli Python paketlerini yükleyin:
```bash
cd m3u
pip install -r requirements.txt
```

2. Scriptleri çalıştırın:
```bash
python "Platform_Adi.py"
```

## Otomatik Güncellemeler

Bu repo, GitHub Actions kullanarak her gün UTC 00:00 ve 12:00'de (Türkiye saatiyle 03:00 ve 15:00) otomatik olarak güncellenir.

## Lisans

MIT License
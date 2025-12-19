# 📁 Dosya Düzenleyici (Python)

Bu proje, belirtilen bir klasördeki dosyaları
uzantılarına göre otomatik olarak alt klasörlere ayırır.

## Özellikler
- Kullanıcıdan klasör yolu alır
- Deneme (dry-run) modu
- Gerçek taşıma modu
- Basit ve anlaşılır Python kodu

## Kullanım
1. Notebook'u aç
2. `dosyalari_duzenle()` fonksiyonunu çalıştır
3. Klasör yolunu gir
4. Deneme veya gerçek taşıma seç

⚠️ İlk kullanımda **Deneme modu** önerilir.

## Planlanan Geliştirmeler

- Komut satırı argümanları desteği eklenmesi (argparse)
- Dosya uzantısı – klasör eşleştirmelerinin yapılandırma dosyasından yönetilmesi
- Taşınan dosyalar için geri alma (undo) mekanizması
- `print` çıktıları yerine loglama sisteminin kullanılması
- Farklı işletim sistemleri için yol (path) yönetiminin iyileştirilmesi

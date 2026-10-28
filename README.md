# HkOs yayın kanalı

HkOs TV ana ekranının herkese açık yayın kanalı. Burada **kaynak kod yoktur**; sadece:

- `duyurular.json` — HkOs ana ekranında ve HKOS Remote'ta gösterilen duyurular (düz metin).
- `hkos-surum.json` — en son HkOs sürümünün bildirimi (sürüm, APK adresi, boyut, SHA-256).
- `*.sig` — yukarıdaki dosyaların ECDSA P-256 imzası. TV, HkOs'a gömülü genel anahtarla doğrular; imzası tutmayan dosya yok sayılır.
- **Releases** — imzalı HkOs APK'ları. TV'de kurulum her zaman kumandayla onay ister.

Dosyalar HkOs Yayın masaüstü programıyla yazılır; elle düzenlenen dosyanın imzası tutmaz.

Hasan Kaynak tarafından geliştirilmiştir.

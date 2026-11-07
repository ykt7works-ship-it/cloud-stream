# Cloud Stream

Film arama, izleme listesi ve “hangi platformda izlenir?” bilgisini tek sayfada toplayan hafif bir web uygulaması.

## Özellikler

- Film arama ve haftanın popüler filmleri
- Türkiye’deki izleme seçenekleri (abonelik, kiralama, satın alma)
- Tarayıcıda saklanan kişisel izleme listesi
- Koyu ve açık tema, mobil uyumlu

Uygulama film dosyası barındırmaz veya dağıtmaz. Yalnızca film bilgilerini gösterir ve yasal platformlara yönlendirir.

## Kurulum

1. [themoviedb.org](https://www.themoviedb.org) üzerinde ücretsiz hesap aç.
2. Ayarlar → API bölümünden bir API anahtarı al.
3. Repoda **Settings → Pages** yolunu aç, **Branch** olarak `main` ve `/ (root)` seç, kaydet.
4. Birkaç dakika sonra sayfan `https://KULLANICI_ADIN.github.io/cloud-stream/` adresinde yayında olur.
5. Siteyi açıp **API anahtarı** düğmesinden anahtarını gir. Anahtar yalnızca kendi tarayıcında saklanır, repoya yazılmaz.

## Dosyalar

| Dosya | Açıklama |
| --- | --- |
| `index.html` | Uygulamanın tamamı (arayüz ve kod) |
| `README.md` | Bu açıklama |

## Sonraki adımlar

- Tür ve yıla göre filtreleme
- Fragman bağlantısı
- Listeyi dışa aktarma

## Kaynaklar

Film verileri [TMDB](https://www.themoviedb.org), izleme platformu bilgileri [JustWatch](https://www.justwatch.com) tarafından sağlanır. Bu ürün TMDB API’sini kullanır ancak TMDB tarafından onaylanmamıştır.

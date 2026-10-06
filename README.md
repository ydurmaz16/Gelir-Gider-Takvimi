# Gelir Gider Takvimi

Gelir ve giderlerini takvim üzerinden takip edebileceğin sade bir web uygulaması. Tek bir HTML dosyasından oluşur, kurulum veya sunucu gerekmez.

## Özellikler

- **Haftalık, aylık ve yıllık** takvim görünümü
- Bir güne dokunarak **gelir veya gider ekleme**, açıklama yazma
- Kayıtları **düzenleme ve silme**
- Günlerin üstünde küçük nokta: gelir için yeşil, gider için kırmızı
- Seçili dönem için **toplam gelir, gider ve net durum**
- 5 renk teması: okyanus, orman, gün batımı, mor, gece
- Para birimi seçimi: ₺, $, €, £
- Metin olarak **yedekleme ve içe aktarma**

## Kullanım

`index.html` dosyasını tarayıcıda aç. Takvimden bir gün seç, tutarı ve açıklamayı gir, kaydet. Tema, para birimi ve yedekleme ayarları sağ üstteki ⚙ simgesinde.

## Veriler nerede saklanır?

Kayıtlar yalnızca kullandığın tarayıcıda (`localStorage`) tutulur. Hiçbir sunucuya gönderilmez. Bu yüzden:

- Tarayıcı verisini silersen kayıtlar da silinir.
- Telefon ve bilgisayardaki kayıtlar ayrıdır.

Kayıtları korumak veya cihazlar arasında taşımak için **⚙ → Yedeği oluştur** ile metni kopyala, diğer cihazda **İçe aktar** ile yapıştır. İçe aktarma mevcut kayıtları silmez, üzerine ekler.

## GitHub Pages ile yayınlama

1. Bu dosyaları bir GitHub deposuna yükle (`index.html` adı korunmalı).
2. **Settings → Pages** bölümünde **Deploy from a branch** seç.
3. Branch olarak `main`, klasör olarak `/ (root)` seçip kaydet.
4. Birkaç dakika sonra sayfa `https://kullaniciadin.github.io/depo-adin/` adresinde yayında olur.

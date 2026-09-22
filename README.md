# Captain Match — Gizlilik Politikası / Privacy Policy

Bu depo yalnızca **Captain Match** mobil oyununun gizlilik politikası sayfasını barındırır.
Oyunun kaynak kodu burada DEĞİLDİR.

Yayın adresi: https://mehmetuar.github.io/captainmatch-privacy/

Google Play Console ve App Store Connect'e verilen gizlilik politikası URL'si budur.

## Diller

Sayfa oyundaki 14 dilin hepsini içerir (`index.html` içinde her dil ayrı bir `<article data-lang="…">`):
en, tr, de, es, fr, it, pt (Brezilya), ru, ja, ko, zh-Hans, zh-Hant, id, ar (sağdan sola).

- Varsayılan dil **İngilizce**dir ve esas metin odur. Diğer 13 dilin sonunda "farklılık olursa İngilizce esastır" notu bulunur.
- `?lang=<kod>` parametresi sayfayı o dilde açar (ör. `?lang=tr`). Oyundaki Ayarlar › Gizlilik Politikası butonu
  bu parametreyi oyuncunun oyun diliyle ekler. Bilinmeyen kod İngilizceye düşer.
- Üstteki buton bayrak + dilin kendi adıyla dil değiştirir. Bayraklar `flags/` altında
  ([flag-icons](https://github.com/lipis/flag-icons) 7.5.0, MIT — `flags/LICENSE`); sayfa üçüncü taraf CDN'e istek atmaz.

## Metni değiştirirken

- Değişikliği **14 makalenin hepsine** birlikte uygula; başlık, liste ve link yapısı dillerde birebir aynı kalmalı.
- Oyun içi adlar (Ayarlar › Gizlilik Seçenekleri, Ücretsiz Coin, Reklamsız…) oyundaki
  `Assets/_Project/Localization/<kod>.json` dizeleriyle birebir aynı yazılır.
- "Son güncelleme" tarihini **14 makalenin hepsinde** güncelle.
- Japonca ve Çince paragraflarda satır kırma: CJK karakterleri arasındaki satır sonu tarayıcıda boşluk olarak görünür.

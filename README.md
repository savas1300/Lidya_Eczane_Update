# LİDYA Eczane güncelleme kanalı

Bu depo yalnız LİDYA Eczane kurulum güncellemelerini taşır.

`version.json` içindeki `product_line` değeri `pharmacy` olmak zorundadır. Kuyumcu sürüm dosyaları bu kanala yazılmaz.

Yeni sürüm:

1. `version.json` içinde `latest_version` ve `download_url` güncellenir.
2. `update_package.zip` ilgili GitHub Release’e yüklenir.
3. Zip’in SHA256 özeti `version.json` içine yazılır.

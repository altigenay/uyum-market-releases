# Uyum Market

Her Android cihaza **o cihaza uyan** uygulamaları getiren mağaza: telefon, tablet ve
Android TV / Google TV, Android 4.4 ve üstü. Eski adı **Tablet Market**.

## Hangisini indirmeliyim?

[Son sürüm](https://github.com/altigenay/uyum-market-releases/releases/latest) sayfasından:

| Cihazınız | Dosya |
|---|---|
| Android **9 ve üstü** (telefon, tablet, Android TV / Google TV) | `UyumMarket-<sürüm>-modern.apk` |
| Android **4.4 – 8.1** (eski telefon, tablet, TV kutusu) | `UyumMarket-<sürüm>-legacy.apk` |

İkisi de aynı uygulamadır: daha önce kurulmuş Tablet Market ya da Uyum Market'in üzerine
güncelleme olarak kurulur, ayarlar korunur. Sonraki güncellemeleri uygulama kendisi bulur ve
cihazına uyanı kurar.

## Ne yapar

- F-Droid ve IzzyOnDroid'deki ~5900 uygulamadan cihazınızın Android sürümüne ve işlemcisine
  (ARM 32/64 bit, x86) uyan en yeni sürümü gösterir; açıklamalar Türkçe.
- GitHub projelerinden ve Google Play'den (hesapsız) de cihazınıza uyan APK'yı seçer.
- Kurulu uygulamaların güncellemelerini bulur.
- TV'de kumandayla kullanılır.

Bu depo yalnızca APK'ları ve `latest.json`'ı (sürüm, SHA-256 özetleri) içerir.

Üçüncü taraf: [Conscrypt](https://github.com/google/conscrypt) (Apache 2.0).

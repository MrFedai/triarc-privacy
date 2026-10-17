---
title: TRIARC Gizlilik Politikası (sürüm 0.3.2, Ekim 2026)
---

# TRIARC Gizlilik Politikası (sürüm 0.3.2, Ekim 2026)


TRIARC, Winter Arc kişisel takip uygulamasıdır. Verilerin yalnız TRIARC'ın kendi sunucusunda tutulur;
satılmaz, reklam ya da analiz için kullanılmaz, üçüncü kişilerle paylaşılmaz.

## Ne toplanır
- Hesap: Google ile girişte ad ve e-posta; Telegram ile girişte Telegram kimliği ve adı.
- Senin girdiğin kayıtlar: namaz ve manevi pratik, öğünler, kilo ve vücut ölçüleri, antrenmanlar, adımlar, okuma,
  görevler ve plan, geri bildirim mesajların.
- Konum (isteğe bağlı): "Konumumu kullan"a bastığında telefonun yaklaşık konumu bir kez okunur. Sunucu bunu ~1 km'ye
  yuvarlar, yalnız şehir adını, yuvarlanmış koordinatı ve saat dilimini saklar (namaz vakitleri ve hava için).
  Arka planda konum alınmaz; tam konum saklanmaz ve kayda geçmez.
- Adımlar (isteğe bağlı, Health Connect): yalnız günlük adım toplamı okunur, yalnız uygulama açıkken (açılışta,
  uygulamaya dönünce, "Şimdi güncelle" ile). Başka sağlık verisi okunmaz, Health Connect'e hiçbir şey yazılmaz.
  Adımlar yalnız TRIARC sunucusuna, o günün adımı olarak gider (skor, beslenme hedefi, haftalık rapor).
- Bildirim adresi: telefona bildirim gönderebilmek için Firebase Cloud Messaging kaydı. Bildirim metinlerinde
  sağlık ayrıntısı yer almaz.

## Health Connect verisinin kullanımı
Health Connect'ten alınan veri (günlük adım toplamı) yalnız uygulamanın gösterdiği işlev için kullanılır:
günlük adım hedefi, Spor skoru ve beslenme hesabı. Reklam, profil çıkarma, satış ya da başka bir amaçla
kullanılmaz ve paylaşılmaz. Kullanım Health Connect izinleri politikasına uyar.

## Nasıl kapatılır ve silinir
- Adımlar: Ayarlar › Bu cihaz › Adım kaynağı › Elle, ya da Health Connect › Uygulama izinleri › TRIARC.
- Konum: Android ayarlarından TRIARC'ın konum izni kaldırılır; şehir arama kutusuyla da seçilebilir.
- Bütün veriler: Ayarlar › Hesap ve veri › dışa aktar (JSON/CSV) ve SİL (geri alınamaz; adımlar ve konum dahil).

## Güvenlik
Uygulama ile sunucu arasındaki her bağlantı şifrelidir (HTTPS). Oturum anahtarı telefonda güvenli depoda tutulur.

## Tıbbi tavsiye
TRIARC tıbbi tavsiye vermez; program ve beslenme hesapları kural tabanlıdır.

İletişim: <fedai1453.gok@gmail.com>

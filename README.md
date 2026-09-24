# Çocuk Oyunları

Tablette ve bilgisayarda oynanan, **tek dosyalık** oyunlar. Kurulum yok, hesap yok,
reklam yok, internet bağlantısı gerekmiyor — dosya bir kere açıldıktan sonra
uçak modunda bile çalışır.

## 🐭 Fare ve Peynir

72 bölümlük labirent oyunu (60 bölüm + 6 boss + 6 bonus). Fareyi peynire götür: yıldızları
topla, kediden kaç, tuzaklara basma, buzda kay, portaldan geç, kutuyu hedefe it,
anahtarla kapı aç.

**Bölüm sırası kolaydan zora:**

- **1–10: Öğretici bölümler.** Her yeni şey (yıldız, buz, portal, anahtar ve kapı,
  birden çok anahtar, çukur, kutu, kedi) burada ilk kez ve tek başına çıkıyor.
  Bölüm ilk açıldığında oyun başlamadan önce küçük bir kart o şeyi anlatıyor
  (sesli okunuyor). Bitirilen bölümde kart bir daha çıkmıyor.
- **👑 Boss bölümleri: 11, 23, 35, 47, 59, 71.** Her 10 bölümden sonra bir boss,
  hemen ardından bonus geliyor.
- **13–25: Pratik.** Öğrenilenler karışık, saat ve kendi yürüyen kedi yok.
- **26: Saat ve kendi yürüyen kedi.** İkisi de ilk kez burada çıkıyor, bir kereliğine
  öğretici olarak: süre bol, kedi yavaş ve geride başlıyor, kart saniyeleri
  seçili zorluğa göre söylüyor.
- **27–70: Kolaydan zora.** Saatli bölümler diğerlerinin arasına zorluklarına göre
  yerleşti. Oyun son boss Kedi Kral'la (71) ve büyük ödülle (72) bitiyor.

- **👑 Boss: Kocaman Kedi** — peynirin başında bekliyor ve seni kovalıyor; peynir
  o uyumadan açılmıyor. Haritadaki her 🧶 yün yumağını aldığında kedi yumakla
  oynamaya dalıyor: bir canı gidiyor ve başı dönüyor 💫 (birkaç sıra yürüyemiyor,
  seni yakalayamıyor). Canları bitince uyuyor 😴. Canı üst şeritte görünür.
  İlk boss (11) kart ile anlatılıyor. Sonrakiler giderek zorlaşıyor: daha çok can,
  daha kısa sersemlik, 26'dan sonrakilerde kendi kendine yürüme ve saat.

- **⏰ Zamana karşı** — geri sayan bir saat. Süre biterse bir can gider, bölüm
  baştan başlar. Erken bitirirsen kalan her saniye puana yazılır.
- **🐱 Kendi yürüyen kedi** — bu kedi sadece sen hareket edince değil, kendi
  başına da ilerliyor (bölüme göre 2,3–4,5 saniyede bir adım). Durursan yaklaşır.
- **🔑 Kaç anahtar, o kadar kapı** — anahtarlar cepte birikir; iki anahtar
  topladıysan iki kapı açarsın. Cepteki anahtar sayısı üst şeritte görünür.
- **🎁 Bonus bölümler** — her boss'tan sonra (12, 24, 36, 48, 60, 72). Kedi yok,
  saat yok, bol yıldız var ve puan iki katına çıkar.

Saat ve kedi zorluğa göre ölçekleniyor: Kolay'da kedi yavaş ve süre bol (×1,4),
Zor'da kedi hızlı ve süre kısa (×0,85).

Bölümlerin tamamı, oyunun kendi kurallarını birebir taklit eden bir çözücüyle
doğrulandı: kedi kovalarken kaçışın var mı, kutu itilebiliyor mu, anahtar kapıya
yetiyor mu, tuzaksız bir yol kalıyor mu, bütün yıldızlara ulaşılabiliyor mu,
verilen süre yavaş oynayan bir çocuğa (hamle başına 1,8 saniye) üç zorlukta da
yetiyor mu. Zorluk sırası da aynı çözücünün ölçümlerinden çıktı: en kısa yolun
uzunluğu, bölümdeki mekanik sayısı, kutu bulmacasında çıkmaza düşüren hamle
oranı, kedi ve çukurun can aldığı hamle oranı, saatli bölümde çocuğun ne kadar
hızlı oynaması gerektiği.

**▶️ Oyna:** https://olgunak.github.io/cocuk-oyunlari/fare-ve-peynir/

### Tablette nasıl oynanır

- Labirentin üzerinde **parmağını kaydır**. Parmağını kaldırmadan sürüklersen
  fare yürümeye devam eder.
- Farenin **yanındaki kareye dokunursan** oraya bir adım atar.
- Ya da sağdaki (dikeyde alttaki) **büyük yön tuşlarına** bas — basılı tutunca
  hızlı gider.
- Oklar yer kaplıyorsa **🎮 Tuşlar** düğmesiyle kapat: labirent büyür, parmakla
  oynamaya devam edersin. Tercih hatırlanır.

Oyun ekranında sadece labirent, oklar ve üstte küçük bir bilgi şeridi durur.
Geri kalan her şey — yardım, baştan başlat, zorluk, kahraman, 72 bölümün
listesi, çıkartmalar, müzik ve ses ayarları — sağ üstteki **⚙️** düğmesinin
arkasında.
- Klavye bağlıysa: yön tuşları / WASD, `H` yardım, `R` baştan, `M` müzik,
  `V` konuşma, `Enter` devam.

### Uygulama gibi açmak (tavsiye edilir)

Tarayıcının adres çubuğu ekranda yer kaplıyor. Ana ekrana eklersen oyun
tam ekran, kendi simgesiyle açılır:

Oyun bunu kendisi anlatıyor: ⚙️ → **📲 Ana Ekrana Ekle** düğmesi, cihazını
tanıyıp adım adım gösteriyor (iPhone/iPad'de Paylaş menüsü, Android'de ⋮
menüsü; Android'de destekleniyorsa tek düğmeyle kurar). İlk açılıştan 15 saniye
sonra fare bir kez hatırlatıyor, sonra bir daha rahatsız etmiyor. Oyun zaten
ana ekrandan açılıyorsa hiç görünmüyor.

Kısaca:

- **iPhone / iPad (Safari):** Paylaş <kbd>⬆️</kbd> → *Ana Ekrana Ekle* → *Ekle*
- **Android (Chrome):** ⋮ menüsü → *Ana ekrana ekle* → *Ekle*

Android'de oyun ilk dokunuşta kendiliğinden tam ekrana da geçer; istemezsen
⚙️ → **⛶ Tam ekran** ile kapatırsın, tercih hatırlanır. iPhone ve iPad'de
Safari sayfalar için tam ekranı desteklemiyor — orada tek yol Ana Ekrana Ekle.

### Özellikler

- Dikey ve yatay çalışır, ekran döndürülünce labirent kendini yeniden ölçekler
- 3 zorluk (Kolay / Orta / Zor), 4 kahraman (🐭 🐹 🐰 🐿️)
- Türkçe konuşan fare (cihazda Türkçe ses varsa), 4 parça müzik, kapatılabilir
- İlerleme tarayıcıda otomatik kaydedilir — kaldığın bölümden devam eder
- Oynarken ekran kararmaz (destekleyen cihazlarda)

## Lisans

Kişisel kullanım için serbest.

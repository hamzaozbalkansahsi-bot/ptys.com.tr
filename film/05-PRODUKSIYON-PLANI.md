# 05 — PRODÜKSİYON PLANI & KAYNAK DAĞILIMI

Bu film **tek tuşla** üretilmez. Üç kaynaktan beslenir ve kurguda birleşir:

1. **Gerçek çekim** — yüzler, eller, gerçek makine makroları (en yüksek güven).
2. **Higgsfield** — geniş açılar, drone, ulaşılması zor sahneler, atmosfer.
3. **Motion Graphics** — PTYS arayüzü ve marka kapanışı (el yapımı, keskin).

---

## KAYNAK KARARI TABLOSU

| Plan | İçerik | Önerilen kaynak | Neden |
|---|---|---|---|
| 1.1 | Siyah + ses | Kurgu | Görüntü yok |
| 2.1 | Kapı açılışı, volumetrik ışık | **Higgsfield** | Kontrollü ışık/atmosfer |
| 2.2 | İşçi detayları (el, kart, baret) | Gerçek çekim | İnsan eli inandırıcılığı |
| 2.3 | Hatlar çalışıyor (geniş) | Higgsfield | Geniş sahne kurulumu |
| 3.1 | Masa kaosu (top-down) | Gerçek / Higgsfield | Prop düzeni gerçekte kolay |
| 3.2 | Müdür yüzü | **Gerçek çekim** | Duygu — yüz AI'a bırakılmaz |
| 3.3 | Titreşen telefon (makro) | Gerçek çekim | Makro gerçeklik |
| 4.1 | Depo arayışı | Higgsfield / Gerçek | Atmosfer |
| 4.2 | Yanlış etiket (makro) | Gerçek çekim | Metin/etiket okunurluğu |
| 5.1 | Bekleyen CNC | Higgsfield / Gerçek | Makine erişimi varsa gerçek |
| 6.1 | Boş satınalma rafı | Higgsfield / Gerçek | Set kurulabilir |
| 7.1 | Muhasebe belirsizliği | Gerçek çekim | İki insan, diyalog jesti |
| 8.1 | Şantiyede yanlış paket | Higgsfield / Gerçek | Şantiye erişimi |
| 9.1 | Patron cam ofisten izliyor | **Higgsfield** | Kompozisyon/ışık kontrolü |
| 10.1 | Ekran uyanışı (oda+yüz) | Higgsfield + MG | Oda AI, ekran MG |
| 10.2 | Modül panosu | **Motion Graphics** | Keskin Türkçe tipografi |
| 11.1 | QR okutma | Gerçek çekim + MG | Makro gerçek, onay MG |
| 11.2 | Veri sinir ağı | **Motion Graphics** | Tam kontrol |
| 11.3 | Sakinleşen masa | Gerçek / Higgsfield | Match-cut 3.1 ile |
| 11.4 | Yürüyen çalışanlar | Higgsfield | Ağır çekim koridor |
| 12.1–12.10 | Üretim montajı | **Higgsfield** + Gerçek | AI geniş, gerçek makro |
| 13.1 | Drone gün batımı | Higgsfield / Gerçek drone | Gerçek drone mümkünse tercih |
| 14.2–14.5 | Marka kapanışı | **Motion Graphics** | Logo/tipografi el yapımı |

**Özet:** Yüzler ve okunacak metinler mümkünse **gerçek**; atmosfer ve
erişilmesi zor kadrajlar **Higgsfield**; arayüz ve marka **Motion Graphics**.

---

## ÜRETİM SIRASI (İŞ AKIŞI)

**Faz 0 — Onay (şu an).** Bu prodüksiyon bible onayı. VO tonu ve müzik
referansı seçimi.

**Faz 1 — Görsel dil kilidi.** 3–4 anahtar kareyi Higgsfield `generate_image`
ile üret (kapı ışığı, patron cam ofis, CNC makro, drone gün batımı). Renk,
grain, lens karakteri bu karelerde onaylanır. **Ucuz ve hızlı** — tüm filmin
"look"u burada kilitlenir.

**Faz 2 — Anahtar karelerden video.** Onaylı görseller `generate_video`'ya
start-frame olarak verilir (kamera hareketi + süre). Görsel tutarlılık için
image→video zinciri kullanılır.

**Faz 3 — Motion graphics.** PTYS arayüzü ve marka kapanışı üretilir
(bkz. `03-MOTION-GRAPHICS.md`). Türkçe font ve keskinlik burada garanti.

**Faz 4 — Ses.** VO (`generate_audio` ya da sanatçı) + fabrika ses kütüphanesi
+ müzik. Miks.

**Faz 5 — Kurgu, renk, master.** Picture lock → grade → çıktı setleri
(`04-KURGU-RENK.md`).

---

## MALİYET / KREDİ UYARISI

Higgsfield görsel ve video üretimi **kredi harcar**. Önerilen strateji:
- Önce `balance` kontrol; sonra **az sayıda anahtar görsel** (Faz 1) ile
  look kilitle — pahalı video üretmeden önce ucuz görselde karar ver.
- Video üretimini yalnızca onaylı görsellerden başlat (boşa kredi yakma).
- Her plan için 1 üretim + gerekirse 1 revizyon; toplu deneme-yanılma yok.

> Faz 1'e başlamadan önce kullanıcı onayı alınır. Bu belge onay noktasıdır.

---

## KALİTE KONTROL LİSTESİ (her plan için)

- [ ] Kadrajda İngilizce kelime/etiket YOK.
- [ ] AI hissi kırıldı mı? (grain, hafif hareket, gerçek ışık)
- [ ] Renk paletine sadık (kırmızı sadece vurgu).
- [ ] 2.39:1, 4K, 24fps.
- [ ] Süre storyboard'a uygun.
- [ ] Ses köprüsü/senkron notu kurgu için işaretli.

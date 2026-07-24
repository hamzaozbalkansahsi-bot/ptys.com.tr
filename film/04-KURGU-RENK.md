# 04 — KURGU RİTMİ, GEÇİŞLER & RENK

---

## KURGU RİTMİ

Kurgu, filmin iki nefesini destekler: **kaos hızlı, akış yavaş.**

| Bölüm | Ortalama plan süresi | Kesim karakteri |
|---|---|---|
| 1. Perde (Kaos) | 2–4 sn, sonlara doğru kısalır | Sinirli, sert, bazen match-cut |
| Köprü | Tek uzun siyah | Kesim yok — durgunluk |
| 2. Perde başı (PTYS) | 4–8 sn | Nefes alan, yumuşak |
| Üretim montajı (S12) | 1.5–2.5 sn | Müzik vuruşuna kilitli ritmik kesim |
| Drone/final | Uzun, akışkan | Tek büyük reveal |

**İlke:** Kaosta izleyici *rahatsız* olacak kadar sık kesilir; çözümde
*nefes* alacak kadar uzun tutulur. Karşıtlık duyguyu üretir.

---

## GEÇİŞ EFEKTLERİ

Görünmez kurgu esas; efekt gösterişi yok. İzinli geçişler:

- **Hard cut (siyaha):** Köprüde ve final öncesi — en güçlü araç.
- **Match cut:** Kaostaki dağınık masa → çözümdeki sakin masa (aynı açı).
  Koşan ayak → yürüyen ayak. QR (gerçek) → QR (ekranda onay).
- **Ses köprüsü (J/L cut):** Bir sahnenin sesi bir sonrakine sızarak akış hissi.
- **Işık geçişi:** Ekran ışığının yüze vurmasıyla açılış (Plan 10.1).
- **YASAK:** Cross-dissolve bolluğu, zoom-blur, "reklam" wipe'ları, ışık patlaması.

---

## RENK / GRADING

Temel: **kontrollü, sinematik, HDR.** İki perde iki paletle ayrışır.

### 1. Perde — KAOS (soğuk, sıkışık)
- Beyaz dengesi hafif soğuk (mavi-yeşile kayık).
- Gölgeler grafit, koyu; highlight'lar kontrolsüz/sert (floresan hissi).
- Doygunluk düşük; ortam biraz "yıkanmış", umutsuz.
- Kontrast orta; yüzlerde gölge ağır (Rembrandt).

### 2. Perde — AKIŞ (dengeli, sıcak vurgulu)
- Beyaz dengesi nötr→sıcak; gün batımında altın.
- Derin ama **temiz** siyahlar; highlight'lar yumuşak roll-off.
- Doygunluk toparlanır; ten tonları sağlıklı.
- Kırmızı vurgular canlı ama izole (skin ve zemin nötr kalır).

### Ortak
- **Film grain:** ince, tüm filmde tutarlı (AI planlarını "gerçek" yapar).
- **Anamorfik karakter:** yatay parlamalar ölçülü; oval bokeh.
- **HDR master** + SDR türev; kırmızı hiçbir masterda klip yapmaz.
- LUT tabanı: sinematik, düşük-kontrast log→gösterim; el ile ince ayar.

### PTYS Kırmızısı disiplini
- Kırmızı yalnızca: QR onayı, logo, kritik uyarı, aktif modül vurgusu.
- Toplam ekran süresinin **<%5**'inde görünür. Her göründüğünde anlam taşır.

---

## PLANLAMA / DELİVERABLE

- Zaman çizelgesi kilidi (picture lock) → ses miksi → renk → final master.
- Master çıktılar:
  - `PTYS_LANSMAN_4K_HDR_2-39.mov` (ProRes 422 HQ, ana)
  - `PTYS_LANSMAN_4K_SDR_16-9.mp4` (web/sosyal, letterbox veya reframe)
  - `PTYS_LANSMAN_9-16_TEASER.mp4` (dikey teaser — `reframe` ile)
  - Altyazı: Türkçe `.srt` (erişilebilirlik).

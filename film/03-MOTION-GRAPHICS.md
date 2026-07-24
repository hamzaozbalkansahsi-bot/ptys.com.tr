# 03 — PTYS ARAYÜZ MOTION GRAPHICS

PTYS arayüzü filmde bir "yazılım ekranı" değil, filmin **çözüm karakteri**dir.
Kaosun ardından gelen düzenin görsel temsili. Hologram/bilim kurgu YOK —
gerçek, premium, cam hissi veren bir arayüz.

---

## TASARIM DİLİ

| Öğe | Karar |
|---|---|
| Zemin | Mat siyah `#0A0A0B` → grafit `#1C1F24` yumuşak degrade |
| Yüzey | Şeffaf cam katmanlar (frosted glass, hafif bulanık arka) |
| Kenarlar | 1px ince, %8 beyaz; köşeler yumuşak (16px radius) |
| Tipografi | Sans-serif, geometrik, **Türkçe** karakter setli (ç ğ ı ş ö ü) |
| Vurgu | PTYS kırmızısı `#E11B22` — sadece onay/kritik/aktif durum |
| Veri | Beyaz `#F4F5F7`; ikincil metin %60 beyaz |
| Animasyon | Yumuşak ease (cubic-bezier .22,1,.36,1); parallax katmanlar |
| Ritim | Her yerleşim müzik vuruşuna senkron ("tık") |

> **Altın kural:** Arayüz asla "reklam ekranı" gibi hızlı ve gösterişli
> akmaz. Sakin, kendinden emin, okunur. Premium = sakinlik.

---

## MG SEKANSLARI

### MG-1 · Ekran Uyanışı (Plan 10.1) — 6 sn
- Siyah ekran → merkezden ince ışık çizgisi açılır → PTYS panosu
  **fade + hafif ölçek** ile belirir.
- Cam katmanlar arka plandan öne sırayla oturur (z-derinliği).
- Alt köşede ince, sakin PTYS işareti (henüz logo değil, sistem işareti).

### MG-2 · Modül Panosu (Plan 10.2) — 8 sn
- Kart ızgarası; her kart bir modül. **Tümü Türkçe:**
  `Üretim Planlama · Depo · Stok · Satınalma · Muhasebe · Finans ·`
  `CRM · Teknik Ofis · Kalite Kontrol · Montaj · Sevkiyat · İnsan Kaynakları`
- Kartlar parallax ile sırayla yerine oturur; her oturuşta ince "tık".
- Fare/dokunuş yok — sistem **kendini** sunar.

### MG-3 · QR Onayı (Plan 11.1) — 4 sn
- Makro QR çekiminin ekran tarafı: kod okunur → çerçeve **kırmızıdan
  yeşile** döner → parça kartı açılır: *"Parça bulundu · Raf A-12 · Sipariş #..."*
  (örnek Türkçe veri).
- Onay mikro-animasyonu: tek dalga, tek tık.

### MG-4 · Veri Sinir Ağı (Plan 11.2) — 10 sn ★ merkez sekans ★
- Ekranın ortasında tek bir **veri düğümü** (okutulan parça).
- Oradan ince ışık çizgileri düğümlere yayılır. Her düğüm Türkçe etiketli:
  `Depo → Üretim → Muhasebe → Patron → Satınalma → Teknik Ofis →`
  `Montaj → Finans → İnsan Kaynakları → CRM`
- Işık her düğüme ulaştığında düğüm **aynı anda** aynı veriyle yanar.
- Mesaj görsel olarak nettir: **tek gerçek, herkese aynı anda.**
- Renk: çizgiler beyaz, aktif düğüm kırmızı nabız, zemin grafit.

### MG-5 · Marka Kapanışı (Plan 14.2–14.5) — 15 sn
- **14.2 Logo:** siyahtan ince ışıkla PTYS logosu; kırmızı tek dokunuş;
  yumuşak "nefes" ölçeği; canlı grain.
- **14.3 Slogan:** `PTYS` / `SANAYİNİN İŞLETİM SİSTEMİ`; ince kırmızı alt çizgi.
- **14.4 Modüller:** satırlar sırayla belirir → "Hepsi Tek Merkezde."de toplanır.
- **14.5 Son ekran:** `PTYS Teknoloji` / `www.ptys.com.tr` /
  *"İşletmenizi yönetmeyin. Geleceğini yönetin."*

---

## ÜRETİM YÖNTEMİ

Motion graphics **After Effects / Figma → export** ile üretilir (gerçek,
kontrollü, keskin tipografi). Higgsfield ile üretilen ekranlar bulanık ve
kontrolsüz olacağından **arayüzler AI ile üretilMEZ**; el yapımı MG olur.

- Çalışma dosyası önerisi: `film/gorseller/ptys-ui/` (AE proje + PNG export).
- Türkçe font gömülü olmalı; ı/İ ve ş/ğ testleri yapılmalı.
- Tüm ekranlar 4K (3840×2160) 24fps alpha kanallı PNG dizisi veya ProRes 4444.
- Renkler HDR uyumlu; kırmızı klip yapmamalı.

> Higgsfield yalnızca **arka plan/oda/yüz/ışık** için; keskin arayüz
> tipografisi için değil. Bu ayrım kalite için kritiktir.

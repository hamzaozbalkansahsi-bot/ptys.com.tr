# 02 — SES & MÜZİK HARİTASI

Ses bu filmde görüntünün eşiti, yer yer önündedir. İlk 45 saniye filmi
**ses taşır.** Kural: müzik 45. saniyeye kadar YOK.

---

## KATMAN 1 — GERÇEK FABRİKA SESLERİ (0:00–0:45)

Karanlıkta ve 1. Perde boyunca kullanılacak gerçek ses kütüphanesi.
Hepsi saha kaydı kalitesinde, mono/stereo konumlandırılmış:

| Ses | Karakter | Giriş anı |
|---|---|---|
| Telefon zili (2 farklı) | Israrlı, kesişen | 0:03 ve 0:05 |
| WhatsApp bildirimi | Tık-tık, biriken | 0:06+ |
| Forklift geri vites bipi | Ritmik, uzak | 0:08 |
| Servo motor | Yükselen vınlama | 0:09 |
| Panel kesim | Keskin, kısa patlamalar | 0:10 |
| Pnömatik/vakum | Tıslama, emiş | 0:11 |
| Telsiz cızırtısı + çağrı | İnsan sesi, boğuk | 0:12 |
| Metal/çekiç | Uzak vuruşlar | serbest |
| İnsan konuşmaları | Anlaşılmayan mırıltı | serbest |

**Kurgu mantığı:** Sesler tek tek girer, katmanlanır, 0:40–0:45'te
**kakofonik zirveye** ulaşır. İzleyici bunalır. Sonra köprüde ANİ SESSİZLİK.

---

## KATMAN 2 — SESSİZLİK KÖPRÜSÜ (1:12–1:20)

- Tüm ses **bir karede** kesilir (hard cut to silence).
- 1 sn saf sessizlik → VO "Çalışanlar kötü değildi."
- 2 sn sessizlik → VO "Sorun… aynı bilgiye aynı anda ulaşamamaktı."
- Son kelimeyle birlikte **derin bir sub-bass** notası doğar (~40–50 Hz).
  Bu, müziğin ilk nefesidir.

> Bu sessizlik pazarlık konusu değildir. Filmin tüm gerilimi buraya boşalır.

---

## KATMAN 3 — MÜZİK (1:20–2:52)

**Tür:** Minimal elektronik + sinematik yaylılar + derin bas.
**Tempo eğrisi:** Yavaş doğuş → istikrarlı yürüyüş → finalde tek güçlü zirve → çözülme.

| Bölüm | Süre | Müzik hareketi |
|---|---|---|
| Doğuş | 1:20–1:34 | Sub-bass + tek piyano/pad notası; nefes |
| Yürüyüş | 1:34–2:00 | Nabız gibi arpej; QR akışıyla senkron ince vuruşlar |
| Yükseliş | 2:00–2:22 | Yaylılar katmanlanır; üretim montajı kesimlerine oturan ritim |
| Zirve | 2:22–2:40 | Drone/gün batımında tam açılım; duygusal doruk |
| Çözülme | 2:40–2:52 | Logoyla tek güçlü vuruş, sonra sükûnet |

**Karışım kuralı:** 2. Perdede gerçek makine sesleri kaybolmaz; müziğin
**perküsyonu** haline gelir (kesim = vuruş, forklift = bas nabzı).

---

## KATMAN 4 — SESLENDİRME (VOICEOVER)

**Ses profili:** Türkçe · 40–50 yaş · derin · sakin · karizmatik · güven veren.
Satmaz, bağırmaz; anlatır. Cümle araları uzun ve kasıtlı.

**Tam metin (zaman kodlu):**

| # | Zaman | Replik |
|---|---|---|
| VO-1 | ~0:02 | "Her sabah… aynı umutla başlarız." |
| VO-2 | ~1:13 | "Çalışanlar kötü değildi." |
| VO-3 | ~1:16 | "Sorun… aynı bilgiye aynı anda ulaşamamaktı." |
| VO-4 | ~2:23 | "Gerçek güç… daha fazla çalışmak değildir." |
| VO-5 | ~2:27 | "Aynı bilgiyle… aynı hedefe… aynı anda yürüyebilmektir." |

> Not: VO-1 dışında ilk perdede söz azdır. Görüntü ve ses konuşur.
> Anlatıcı sadece **dönüm noktalarında** girer.

**Seslendirme üretimi:** Higgsfield `generate_audio` (Türkçe erkek, olgun,
derin ton) veya profesyonel voiceover sanatçısı. Prova: her replik en az
2 tonlama varyasyonu ile alınmalı; kurguda sessizlik payı korunmalı.

---

## TESLİM FORMATI

- Ses miksi: 24-bit / 48 kHz, stereo + 5.1 opsiyonel.
- Loudness: -16 LUFS (web) / -23 LUFS (yayın) ayrı master.
- VO, müzik ve efekt ayrı stem'ler halinde teslim (revize kolaylığı).

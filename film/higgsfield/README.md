# HIGGSFIELD ÜRETİM PROMPTLARI

Bu klasör, storyboard'daki planları Higgsfield ile üretmek için hazır
promptları içerir. İki dosya:

- `01-IMAGE-PROMPTS.md` — Anahtar kareler (`generate_image`). ÖNCE bunlar.
- `02-VIDEO-PROMPTS.md` — Anahtar karelerden video (`generate_video`).

## KULLANIM İLKESİ

1. **Önce görsel, sonra video.** Ucuz görselde look'u kilitle; pahalı
   videoyu yalnızca onaylı görselden başlat. (`05-PRODUKSIYON-PLANI.md` Faz 1–2.)
2. **Görsel tutarlılık:** Onaylanan görseli video üretiminde start-frame
   olarak ver. Aynı fabrika, aynı ışık, aynı palet korunur.
3. **Model seçimi:** Emin değilsen `models_explore(action:'recommend')`
   ile hedefi ve girdiyi ver, önerilen modeli kullan.

## PROMPT DNA (her prompta eklenecek ortak kuyruk)

> cinematic, shot on anamorphic lens, 2.39:1, 4K, 24fps film look, HDR,
> fine film grain, volumetric light, real cinema lighting, documentary
> realism, graphite / matte black / deep navy / white palette, red only
> as a rare accent, Turkish furniture manufacturing factory (real, not
> sci-fi), **no legible on-screen text, no English signage, no watermark,
> no logo**, photoreal, not AI-looking, subtle handheld imperfection

## KAÇINILACAKLAR (negatif yön)

> no holograms, no futuristic UI floating in air, no neon sci-fi, no glossy
> stock-ad look, no cartoon, no oversaturation, no fake gibberish text,
> no English words, no visible brand logos, no plastic skin

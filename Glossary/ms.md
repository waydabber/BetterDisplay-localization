# Translation Glossary — Malay (ms)

Standard Malaysian Malay (Bahasa Melayu, Malaysia). Use a concise formal UI register.

## Conventions

Leading icon placeholders retain position and order. Source interpolation tokens, code delimiters, argument types, links and literal word-joined percentages remain intact.

Use the Malaysian decimal point and grouping comma in displayed prose: the HDR limit is 10,000 nits, not 10.000. Preserve machine-facing numbers, protocol addresses and identifiers.

Malay has only the CLDR cardinal category `other`; counted nouns and surrounding verbs do not inflect by number here. Use invariant string units without unnecessary English-derived plural structures. Numeric argument mappings remain unchanged, including icon-plus-count messages.

## Terminology

| English | Malay | Notes |
| --- | --- | --- |
| activate | aktifkan | |
| brightness | kecerahan | |
| brightness upscaling | peningkatan kecerahan | Extends brightness beyond its normal maximum; distinct from resolution scaling. |
| clipping | pemotongan butiran | |
| color | warna | |
| color depth | kedalaman warna | |
| color profile | profil warna | |
| color table | jadual warna | |
| compositor | penggubah | |
| configuration | konfigurasi | |
| connect | sambungkan | |
| contrast | kontras | |
| control | kawalan | |
| controller | pengawal | |
| Crop rectangle boundary | bingkai pangkasan | Compact visibility toggle; visible outline of the crop rectangle. |
| cursor | kursor | |
| deactivate | nyahaktifkan | |
| Default | Lalai | |
| dimming | pemalapan | |
| disable | nyahdayakan | |
| disconnect | putuskan sambungan | |
| display | paparan | Normally the physical device. |
| dithering | penditeran | |
| enable | dayakan | |
| Exposure | Dedahan | |
| Favorite | Kegemaran | Compact badge: Kegem. |
| framebuffer | framebuffer | Technical graphics-memory term. |
| gain | gandaan | |
| gamma | gama | |
| hard disconnect | pemutusan fizikal | |
| HDR Filter Pipeline | Saluran Pemprosesan Penapis HDR | |
| Highlight | Sorotan | Photographic tonal region. |
| hue | rona | |
| layout protection | perlindungan susun atur | |
| LG alt | LG alt | Narrow-column abbreviation for LG alternatif. |
| luminance | luminans | |
| menu bar | bar menu | |
| mirror | cerminkan | |
| mirroring | pencerminan | |
| mouse pointer | penuding tetikus | A screen containing the pointer is a destination; do not phrase this as moving a window using the mouse. |
| n/a | t/s | Abbreviation of tidak tersedia. |
| Neutral | Neutral | |
| off | mati | |
| on | hidup | |
| Original | Asal | |
| overlay | tindanan | |
| override | tindih/tindihan | |
| pair | pasangkan | Apple Malay usage; device context distinguishes it from app installation. |
| pairing | pemasangan | Apple Malay usage; device context distinguishes it from app installation. |
| PIP window | Tetingkap PIP | Compact Picture in Picture commands; enclosing Gambar dalam Gambar menu provides the full feature name. |
| preset | praset | |
| refresh rate | kadar segar semula | |
| reinitialize | mulakan semula | Context identifies whether a connection, app or stored data is affected. |
| resolution | resolusi | |
| restart app | mulakan semula app | |
| restoring EDID | pulihkan EDID | |
| rotated orientation | tukar lebar dan tinggi | Explicitly describes the virtual-screen dimension swap. |
| saturation | ketepuan | |
| scaling | penskalaan | |
| screen | skrin | OS surface. |
| settings | seting | |
| Shadow | Bayang | Photographic tonal region. |
| shortcut | pintasan | |
| sidebar | bar sisi | |
| slider | gelangsar | |
| soft disconnect | pemutusan secara perisian | |
| stream | strim | |
| streaming | penstriman | |
| synchronization | penyegerakan | |
| Turn display off | matikan kuasa paparan | |
| Turn screen off | matikan skrin | |
| UI scale matching | pemadanan skala UI | |
| Unlimited | Tanpa Had | |
| variable refresh rate | kadar segar semula berubah-ubah | |
| virtual display | paparan maya | |
| virtual screen | skrin maya | OS surface. |

## Retained terms

- Retain product/firmware names and API/protocol identifiers: Apple, Apple Silicon, BetterDisplay, DisplayLink, Sidecar, Night Shift, True Tone, Spaces, Dock, Finder, Pro, Philips Smart TV, Yamaha AVR, Tri-Screen, CGDirectDisplayID, HDR/SDR/XDR/EDR, DDC, DPCD, DSC, HDMI-CEC, VCP, EDID, DisplayID, I2C, LUT, CUBE, RGB/YCbCr, USB, UUID, PIN, TCP/HTTP and CLI.
- Retain color spaces and profile names (Display P3, sRGB, Rec. 709, Rec. 2100 PQ), Display Stream Compression, Downspread and Underscan as recognizable technical names. Bloom, Chrome and Noir identify specific image effects. Screen in the blend-mode label is retained as a compositing operation, distinct from skrin as an OS surface.
- Retain unit symbols and notation (bit, mm, nits, lux, Hz, FPS, multiplication factors, degrees and chroma ratios), code/example identifiers, URLs, SF Symbols names and firmware service-menu labels (EZ ADJUST, IN START, Auto Power Sync, Anynet+, etc.).
- Edit, Import, Menu, Model, Median, Neutral, Platform, Standard, Sepia, Min and OK are normal shared Malay UI/technical words; identical English spelling is intentional.

HW is retained in compact Min HW/Maks HW hardware-boundary badges.

## References

- [Apple Malay macOS Accessibility settings](https://support.apple.com/ms-my/guide/mac-help/mchlp1400): Seting Sistem, Kebolehcapaian, Papan Kekunci, bar sisi and penuding.
- [Apple Malay Siri Accessibility settings](https://support.apple.com/ms-my/guide/iphone/iphaff1d606/ios): gelangsar and Lalai.
- [Apple Malay Bluetooth device setup](https://support.apple.com/ms-my/guide/mac-help/-blth1004/mac): pasangkan, sambungkan and putuskan sambungan.
- [DBP terminology for dithering](https://prpm.dbp.gov.my/Cari1?d=73980&keyword=pencampuran): penditeran.
- [Unicode CLDR Malay number symbols](https://raw.githubusercontent.com/unicode-org/cldr-json/main/cldr-json/cldr-numbers-full/main/ms/numbers.json): decimal point and grouping comma.
- [Unicode CLDR plural rules](https://unicode.org/cldr/charts/49/supplemental/language_plural_rules.html): Malay has only cardinal `other`.

Other technical wording is an independent contextual choice, not claimed as official Apple terminology.

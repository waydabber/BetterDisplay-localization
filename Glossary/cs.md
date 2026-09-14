# Translation Glossary — Czech (cs)

Standard Czech as used in the Czech Republic. Use concise infinitives for actions, sentence case, and polite plural instructions in explanatory text.

## Conventions

- Preserve product/brand names, protocol names, hardware identifiers, URLs, units and standard abbreviations (HDR, XDR, SDR, HiDPI, LoDPI, EDID, DisplayID, DDC, HDMI, CLI, GPU, Metal, LG webOS, Tri-Screen). Retain OSD for the on-screen indicator.
- Keep keyboard names and glyphs (⌥ Option, ⌘ Command) and verified icon placeholders in source order. Use Czech „quotation marks“ in ordinary prose.
- Prefer count-neutral labels such as „Zbývající dny: %lld“ when they naturally express a count without plural branches; never copy English plural inflection mechanically.
- Keep firmware option names such as QuickStart+, Always Ready, Simple Manifest and Anynet+ recognizable and unchanged. Preserve source-mandated numeric multiplier notation (0.5x etc.), angle values and chroma-sampling ratios.
- Numeric unit labels use invariant symbols: ms, mm, lux, nit and ″ for inches. In prose inflect naturally (v nitech).
- Use d for a numeric day-duration unit, px for numeric pixel dimensions. These avoid invalid agreement with arbitrary numbers.
- Retain established specialist terms such as underscan, dithering, framebuffer, stream, Metal, and photo-effect names Chrome/Noir. Underscan shrinks the image inward; it is not an overscan crop. Model, bit and OK are also standard Czech UI words identical to English.
- Shortcut feature parameters are fixed localized labels (for example `Gama`, `Termovize`, `Invertovat barvy`). Introduce them as `funkce „${…}“` so the surrounding sentence does not require the substituted label to change case; quote the fixed range option in the same way.
- For arbitrary numeric shortcut inputs, use invariant `%` and `bit` units; a fixed `procent` or `bitů` form cannot agree with every integer or decimal value.
- Arbitrary display-name placeholders remain unchanged: introduce them with an inflected `displej` and Czech quotation marks (for example `Poloha displeje „%@“`) when the surrounding label otherwise requires a different case. Keep optional orientation suffixes outside the quoted name.
- Keep file-format identifiers, DSC, DPCD, downspread and encoding identifiers unchanged.
- Keep integration tokens such as `${displayEntity}`, the sample identifier `My parameter`, SF Symbol names, and firmware commands unchanged.

## Terminology

| English | Czech | Notes |
| --- | --- | --- |
| adaptive sync | adaptivní synchronizace | |
| association | přidružení | |
| blend mode | režim prolnutí | |
| brightness upscaling | zvýšení jasu nad běžný rozsah | Contextual choice, not claimed official Apple terminology. |
| chroma subsampling | podvzorkování barev | |
| Classic | Klasické | OSD selector; agrees with OSD and its help text. |
| color depth | barevná hloubka | |
| color profile | barevný profil | |
| color table | tabulka barev | |
| compositor | kompozitor | |
| Configuration Protection | Ochrana konfigurace | |
| control | ovládací prvek | |
| controller | ovladač | |
| CUBE grid dimension | rozměr mřížky CUBE | |
| custom LUT filter | vlastní filtr LUT | |
| DDC capabilities | schopnosti DDC | |
| DDC mapping skew | zakřivení mapování | Nonlinear curve. |
| delta syncing | synchronizace změn | Preserves offsets. |
| Device Control | Ovládání zařízení | |
| Device Control and Data Access | Ovládání zařízení a přístup k datům | Descriptive macOS 27 permission name; not verified official Apple terminology. |
| disassociate | zrušit přidružení | |
| display | displej | Physical device, distinct from the OS surface. |
| display group | skupina displejů | |
| Display Mode | Režim displeje | App menu. |
| Display Modes | Režimy displeje | |
| Display Preset | předvolba displeje | Distinguish from generic saved app configurations where needed. |
| Displays | Monitory | Apple Settings pane. |
| Dot Screen | Bodový rastr | Printing-screen filter; rastr, not obrazovka. |
| DSC slice | segment | |
| EDID override | přepsání EDID | |
| Exposure | Expozice | |
| flexible scaling | flexibilní škálování | Contextual choice, not claimed official Apple terminology. |
| frame rate | snímková frekvence | |
| framebuffer | framebuffer | |
| gamut | barevný gamut | |
| GUI | rozhraní | Ordinary labels and prose. |
| Hatched Screen | Šrafovaný rastr | Printing-screen filter. |
| HDR brightness upscaling | zvýšení jasu HDR | Short label when the dynamic-range qualifier distinguishes upscaling. |
| HDR Filter Pipeline | Zpracování filtrů v HDR | |
| hexadecimal | hexadecimální | |
| Highlight | Světla | Photographic adjustment. |
| interprocess notification dispatch | odesílání notifikací | |
| layout protection | ochrana uspořádání | |
| Line Screen | Čárový rastr | Printing-screen filter. |
| Login Items | Přihlášení | Apple deployment wording; newer macOS help expands this to Aktivace položek a rozšíření při přihlášení. |
| LUT | LUT | |
| mirroring | zrcadlení | |
| native audio control | systémové ovládání | |
| native display connection | nativní připojení | |
| native keyboard keys | systémové klávesy | |
| privileged helper | privilegovaná pomocná služba | |
| refresh rate | obnovovací frekvence | |
| resolution | rozlišení | |
| rotated orientation | Zaměnit šířku a výšku | Virtual-screen dimension swapping, not captured-pixel rotation. |
| screen | obrazovka | OS surface. |
| Screen (blend mode) | Závoj | Blend mode. |
| slider | jezdec | |
| Standard | Standardní | Regular app-menu presentation. |
| streaming | streamování | |
| System Settings | Nastavení systému | |
| temporal dithering | časový dithering | |
| TV | televizor | Ordinary labels and prose. |
| UI | rozhraní | Ordinary labels and prose. |
| UI scale matching | sjednocení měřítka rozhraní | Matching physical element size. |
| user-visible notifications | oznámení | |
| Video Filters | Obrazové filtry | |
| virtual screen | virtuální obrazovka | |
| XDR brightness upscaling | zvýšení jasu XDR | Short label when the dynamic-range qualifier distinguishes upscaling; generic wording retains nad běžný rozsah. |

## References

[Apple Czech display settings](https://support.apple.com/cs-cz/guide/mac-help/mh40768/mac) and [adaptive sync](https://support.apple.com/cs-cz/guide/mac-help/mchld453162e/mac) were used to verify the standard system/display terminology.

[Apple deployment guidance](https://support.apple.com/cs-cz/guide/deployment/depdca572563/web) uses Přihlášení for Login Items.

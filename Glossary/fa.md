# Translation Glossary — Persian (fa)

## Conventions

- Use natural contemporary Iranian Persian, with Persian `ی` (U+06CC) and `ک` (U+06A9). Use ZWNJ (U+200C) where standard Persian spelling requires it, for example `می‌شود` and `نمایشگرها` (the latter needs no ZWNJ).
- Prefer established, readily understood software terminology. Verify any claimed Apple terminology against an actual Persian source; do not infer Persian terminology from Arabic localization.
- Preserve product names, technical identifiers, format specifiers, URLs, shortcuts and recognized units. Technical acronyms such as DDC, EDID, HDR, XDR, GPU and HiDPI retain their Latin spelling.
- Prefer natural platform bidi behavior. Add balanced Unicode isolates only when mixed-direction content requires them; preserve source bidi controls unless a correction is justified.
- Translate physical display as `نمایشگر` and generic screen/surface as `صفحه` where natural. Use `صفحهٔ مجازی` for BetterDisplay virtual screen and `نمایشگر مجازی` for third-party virtual display, subject to established feature terminology and context.

- Directional sequence labels use a left-pointing arrow in Persian reading order (`پایین ← چپ`); physical left/right meanings remain unchanged.
- Use customary tanwin spellings (`لطفاً`, `مثلاً`, `کاملاً`) and only clarifying short vowels (`بُعد`, `تُن`, `پُر`, `درِ`). Do not add general Arabic vocalization.
- Preserve format specifiers, interpolation tokens and machine-facing numerals exactly. Persian prose may use natural numeric ranges (`2 تا 4`) or a thousands separator (`10٬000`) without changing the value. Keep source U+2060 word joiners in percentage expressions.
- Use LRI/PDI for resolutions, colon-delimited addresses, code fragments and modifier-name pairs when needed. In rotation commands, isolate the complete Latin angle (`90°`, `180°`, `270°`) with LRI/PDI (U+2066/U+2069): live RTL menus otherwise place the degree symbol before the number. Preserve the Persian wording and its ZWNJ.

## Terminology

| English | Persian | Notes |
| --- | --- | --- |
| Accessibility | دسترس‌پذیری | Conventional Persian wording, not a verified Apple translation. |
| Associated display | نمایشگر مرتبط | Associated output device. |
| Blend Mode | حالت ترکیب | Retain recognized graphics mode names; Screen is an operation, not a screen device. |
| Brightness upscaling | افزایش روشنایی | Beyond the normal brightness range. |
| Calibration | کالیبراسیون | |
| Chroma subsampling | زیرنمونه‌برداری رنگ | |
| Color gamut | گسترهٔ رنگ | |
| Color profile | نمایهٔ رنگ | |
| Color table | جدول رنگ | |
| Color Temperature | دمای رنگ | |
| Configuration Protection | حفاظت از پیکربندی | |
| Control | کنترل | UI control. |
| Controller | کنترل‌کننده | Backend. |
| Delete | حذف | Deletion, distinct from reversible disconnection. |
| Delta syncing | همگام‌سازی تغییرات نسبی | |
| Disassociate | حذف ارتباط | |
| Discard | حذف | Deletion, distinct from reversible disconnection. |
| Disconnect | قطع اتصال | Reversible disconnection. |
| Display | نمایشگر | Physical device. |
| Display Mode | حالت نمایش | |
| Display Preset | پیش‌تنظیم نمایشگر | |
| EDR headroom | ظرفیت اضافهٔ EDR | |
| Favorite resolution | وضوح دلخواه | |
| Flexible scaling | مقیاس‌بندی انعطاف‌پذیر | |
| Gamma | گاما | |
| HDR clipping | — | Describe as loss of highlight/shadow detail where the warning permits it. |
| Hex | مبنای شانزده | Base-16 numbers and values; retain HEX in the editor-style name and preserve literal hex codes. |
| Hexadecimal | مبنای شانزده | Base-16 numbers and values; retain HEX in the editor-style name and preserve literal hex codes. |
| Hospitality Menu | منوی هتل | TV hotel setup menu. |
| Hue | فام | |
| Layout protection | حفاظت از چیدمان | |
| License | مجوز | |
| Luminance | درخشندگی | |
| Main Status | وضعیت اصلی بودن | |
| Manifest | مانیفست | Connection protocol manifest. |
| Mirroring | همسان‌سازی تصویر | Keep distinct from streaming. |
| Model adaptations | سازگارسازی‌های ویژهٔ مدل | |
| Native Apple keyboard keys | کلیدهای استاندارد | |
| Native device controls | کنترل‌های بومی | |
| Photo effect | جلوهٔ عکس | Followed by the retained preset name. |
| PIP | تصویر در تصویر | |
| Privileged helper | سرویس کمکی دارای دسترسی مدیر | |
| Reconnect | اتصال مجدد | |
| Refresh rate | نرخ نوسازی | |
| Reinitialize | راه‌اندازی دوباره | |
| Reset | بازنشانی | |
| Resolution | وضوح | Pixel dimensions. |
| Restore (factory EDID) | بازگردانی | |
| Restore (settings) | بازیابی | |
| Rotated Orientation | جابه‌جایی عرض و ارتفاع | Including the automatic variant. Swaps configured dimensions; does not necessarily mean portrait. |
| Screen | صفحه | Generic surface. |
| Service Menu | منوی سرویس | TV technical menu. |
| Streaming | ارسال تصویر | Capturing and sending the source image. |
| Synchronization | همگام‌سازی | Keep distinct from mirroring (همسان‌سازی تصویر). |
| Temporal dithering | dithering زمانی | |
| Vibrance | شادابی رنگ | |
| Virtual display | نمایشگر مجازی | Third-party virtual display; subject to established feature terminology and context. |
| Virtual screen | صفحهٔ مجازی | BetterDisplay-created surface. |

## Retained terms

Keep framebuffer, compositor, Metal, OSD, NTSC and product names in Latin spelling. Keep underscan, checksum, shell, CUBE, LUT, WOL/WoWLAN and other protocol/API identifiers recognizable. Underscan is inward image scaling, distinct from resolution scaling.

Retain Color, Difference, Exclusion, Hard Light, Hue, Luminosity, Multiply, Overlay, Saturation, Screen and Soft Light as recognized graphics mode names. Firmware settings such as QuickStart+, Always Ready, Networked Standby, Auto Power Sync and Anynet+ retain their device-visible names. Photo presets Chrome, Fade, Instant, Noir, Process and Transfer remain in English after `جلوهٔ عکس`.

### Unchanged complete values

The following complete values intentionally match English. They contain only retained domains, brands/product names, protocol/API/color-space identifiers, conventional numeric notation, units or interpolation structure. Other English fragments retained within Persian sentences follow the terminology decisions above.

- `[betterdisplay.pro](https://betterdisplay.pro)`
- `[betterdisplay.pro/buy](https://betterdisplay.pro/buy)`
- `%@ (LG)`
- `%@ (Philips)`
- `%@ (Yamaha)`
- `%@ %@`
- `%@ nits`
- `%@ Tri-Screen`
- `0.5x`
- `0°`
- `1.0x`
- `1.5x`
- `2.0x`
- `2.5x`
- `4`
- `4:2:0`
- `4:2:2`
- `4:4:4`
- `90°`
- `100`
- `180°`
- `270°`
- `1000`
- `Apple`
- `Apple Silicon`
- `CGDirectDisplayID`
- `DDC`
- `Display P3`
- `Downspread`
- `DPCD`
- `HDMI %lld%@`
- `HDMI-CEC`
- `HDR`
- `HiDPI`
- `Intel`
- `LoDPI`
- `lux`
- `mm`
- `nits`
- `OSD`
- `PIN`
- `Pro`
- `Rec. 709`
- `Rec. 2100 PQ`
- `RGB`
- `SDR`
- `sRGB`
- `URL`
- `USB`
- `UUID`
- `Yamaha AVR`
- `YCbCr`

## Verification scope

Persian shaping and mixed-direction resolutions, addresses, shortcuts, percentages and technical identifiers were checked in native AppKit text samples. This targeted text-rendering check does not establish exhaustive live-app layout coverage. The rotation-angle isolation guidance reflects a subsequent live RTL menu and shortcut-list check.

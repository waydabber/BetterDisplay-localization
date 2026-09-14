# Translation Glossary — Hebrew (he)

## Conventions

Use natural, concise macOS UI Hebrew. Prefer infinitive/noun action labels and impersonal help text. Preserve product names and established technical abbreviations.

Rely on natural bidi behavior for ordinary Latin names embedded in Hebrew. Use LRI/PDI only when a shortcut combination, punctuated version token, resolution value, or ordered numeric list needs its LTR order preserved. Keep Hebrew prose and connecting words outside LTR isolates: use `התקני המרה מ־USB-C ל־HDMI`, and phrase Command-click as `לחיצה תוך החזקת` followed by the isolated `⌘ Command`. Do not isolate arbitrary display names or placeholders mechanically; substituted values may themselves be Hebrew. Preserve formatting placeholders exactly. Do not change non-Hebrew strings or source keys.

- Shortcuts On/Off substitutions use פעיל / כבוי. Phrase summaries around מצב or use a colon so these shared masculine singular labels do not have to agree with a feminine/plural feature name.
- Relative-position labels in Shortcuts use `←` between Hebrew position terms so the progression follows RTL reading order; physical left/right words retain their meanings. Unlike `>` menu separators, Unicode arrows do not automatically mirror.
- Keep modifier combinations such as `⇧ Shift + ⌥ Option` together with nonbreaking spaces inside the existing LTR isolate when wrapping would separate a symbol from its key name.
- Quote Hebrew setting names as ordinary UI text (for example ״הממדים הפיזיים של המסך״), avoiding code-font formatting when they are not code or identifiers.

## Terminology

| English | Hebrew | Notes |
| --- | --- | --- |
| Accessibility | נגישות | Permission or macOS settings category. |
| administrator | מנהל מערכת | |
| Administrator authorization | הרשאת מנהל מערכת | |
| Alignment | יישור | |
| Alpha | אטימות | Lower values mean more transparency. |
| Amplifier zone | אזור במגבר | |
| Anchor point | נקודת עיגון | |
| Applied | הוחל | |
| Apply | החלה | |
| Association | שיוך | |
| Authorization right | זכות הרשאה | |
| Bandwidth | רוחב פס | |
| bit depth | עומק סיביות | |
| Bits | סיביות | |
| Blend mode | מצב מיזוג | |
| Bloom | זוהר | |
| Brightness | בהירות | |
| Cancel | ביטול | |
| Checksum | סכום ביקורת | |
| Chroma subsampling | דגימת צבע מופחתת | |
| Chunk | מקטע | |
| Classic | קלאסי | |
| clipping | אובדן פרטים | HDR help: loss of highlight/shadow detail. |
| color depth | עומק צבע | |
| Color gamut | מכלול צבעים | |
| color mode | מצב צבע | Connection color format/depth mode. |
| Color table | טבלת הצבעים | |
| computer monitor | צג מחשב | When distinguishing from a television. |
| Configuration Protection | הגנת התצורה | Reapplies protected settings. |
| Console | מסוף | |
| control | פקד | Individual control. |
| Control Center | מרכז הבקרה | |
| controller | בקר | Hardware/software controller. |
| Crop | חיתוך | |
| Crystallize | התגבשות | |
| CUBE dimension | ממד CUBE | |
| DDC value mapping skew | הטיית מיפוי ערכי DDC | Nonlinear mapping curve. |
| Delta syncing | סנכרון הפרשים | Preserves offsets. |
| Desktop | מכתבה | |
| Device Control and Data Access | שליטה במכשיר וגישה לנתונים | macOS 27 permission; verified against the installed Hebrew ACCESSIBILITY value in SecurityPrivacyExtension (see References). |
| Device pairing | קישור | |
| Difference | הפרש | Blend mode. |
| Dimming | עמעום | |
| Discard virtual screen | מחיקת מסך וירטואלי | |
| display | מסך | General display device or screen. |
| display mode | מצב תצוגה | Resolution, refresh rate and related mode parameters. |
| Display notch | מגרעת המסך | |
| Display power off | כיבוי המסך | Hardware power action. |
| Display Preset | תצורת תצוגה מוגדרת מראש | In compact labels, use תצורת תצוגה (for example תצורת תצוגה של Apple). Keep distinct from individual display modes (מצב תצוגה); retain the fuller wording in explanatory prose when useful. |
| DisplayPort branch device | התקן הסתעפות DisplayPort | |
| Dot Screen | רשת נקודות | |
| DSC slice | פרוסה | |
| Edge Work | עיבוד קצוות | |
| EDID override | עקיפת EDID | Software configuration, distinct from writing EDID to hardware. |
| EDR headroom | מרווח EDR | |
| Exclusion | החרגה | Blend mode. |
| Exposure | חשיפה | |
| Factory color profile | פרופיל הצבע המקורי | |
| Fine adjustment | כוונון עדין | |
| Flexible scaling | קנה מידה גמיש | |
| Forget display | מחיקת נתוני המסך | Removes remembered settings, not a hardware disconnect. |
| framebuffer | מאגר התמונה | GPU framebuffer; distinguish from the connection format. |
| Framerate | קצב תמונות | Distinct from display refresh rate. |
| Gain | הגבר | |
| Gamma | גאמה | |
| Gaussian Blur | טשטוש גאוסי | |
| Gloom | קדרות | |
| Grayscale | גוני אפור | |
| Hard Light | אור קשה | Blend mode. |
| Hardware-native audio controls | בקרי שמע מובנים | |
| HDR Filter Pipeline | שרשרת עיבוד מסנני HDR | |
| Highlight | אזורים בהירים | |
| Hospitality Menu | תפריט המלונאות | TV configuration for hotels. |
| Hue | גוון | |
| Input | כניסה | Physical audiovisual connector. |
| Input source | מקור כניסה | |
| Integer Scaling | קנה מידה בשלמים | |
| Lane | נתיב | |
| layout protection | הגנת הפריסה | Group display arrangement protection. |
| Line buffer | מאגר שורות | |
| Link | קישור | DisplayPort transport. |
| Logical step | צעד לוגי | |
| Luminance | בהיקות | |
| Luminosity | בהיקות | |
| Magnification | הגדלה | |
| Manifest | Manifest | Retain the technical noun for the LG webOS registration permission declaration; translate modifiers (מלא, פשוט, עם/ללא חתימה), including the automatic fallback warning. |
| menu bar | שורת התפריטים | Standard macOS term. |
| Mirror target | יעד לשיקוף | |
| mirroring | שיקוף | |
| Multiply | הכפלה | Blend mode. |
| Native keyboard control | שליטה באמצעות מקשי המערכת במקלדת Apple | Media/brightness keys; not necessarily a built-in keyboard. |
| Native/system keyboard keys | מקשי המערכת | Use consistently in headings, settings, and status/help text. |
| nits | ניט | Luminance unit. |
| Notification dispatch | שיגור הודעות מערכת | Integration IPC; distinct from user-facing Notifications/עדכונים. |
| Notification payload | מטען הודעת המערכת | Integration IPC; user-facing notifications remain עדכונים. |
| Notifications | עדכונים | macOS pane; distinct from software updates. |
| Off | כבוי | Shared Shortcuts substitution; see Conventions for agreement. |
| Offset | היסט | |
| On | פעיל | Shared Shortcuts substitution; see Conventions for agreement. |
| OSD | חיווי על המסך | First explanatory mention may include (OSD). |
| OSD chiclet | מקטע של החיווי על המסך | |
| Overlay (blend mode) | כיסוי | Distinct from the rendering layer שכבת על. |
| Overlay (rendering layer) | שכבת על | |
| Passthrough | העברה ללא שינוי | |
| Periodic read | קריאה מחזורית | |
| PIP | תמונה בתוך תמונה | |
| Privacy & Security | פרטיות ואבטחה | |
| Privileged helper | שירות העזר בעל ההרשאות המוגברות | |
| Quantization | קוונטיזציה | Image adjustment reducing the number of color levels (posterization), not the full/limited signal range selector. |
| Record | הקלטה | Narrow shortcut recorder placeholder; omit redundant wording supplied by surrounding UI. |
| refresh rate | קצב רענון | |
| Reinitialize | אתחול מחדש | Display connection. |
| Remove profile | הסרת פרופיל | |
| Reset | איפוס | |
| resolution | רזולוציה | Preserve numeric width × height order. |
| Restart app | הפעלה מחדש | |
| Rotated orientation | החלפת רוחב וגובה | Virtual-screen toggle swapping dimensions relative to configured aspect ratio, not specifically portrait. Add (אוטומטית) for the automatic variant. |
| Saturation | רוויה | |
| screen | מסך | General display device or screen. |
| Screen (blend mode) | סינון | Blend mode. |
| Screen/backlight illumination off | כיבוי תאורת המסך | Keyboard shortcut label; distinct from hardware display power. |
| Screen/backlight illumination on | הפעלת תאורת המסך | Keyboard shortcut label; distinct from hardware display power. |
| service menu | תפריט השירות | Technical device menu. |
| Shadow (image adjustment) | אזורים כהים | |
| Sharpness | חדות | |
| Shell script | סקריפט מעטפת | |
| Shortcuts | קיצורים | Apple application. |
| Sidebar | סרגל הצד | |
| Sink | התקן קצה של DisplayPort | |
| Soft disconnect | ניתוק בתוכנה | |
| Soft Light | אור רך | Blend mode. |
| Software brightness upscaling | הגברת בהירות בתוכנה | Distinct from resolution scaling. |
| source | מקור | Capture source. |
| Standby | מצב המתנה | |
| Stream target | יעד להזרמה | |
| streaming | הזרמה | |
| System audio keys | מקשי השמע של המערכת | |
| System brightness keys | מקשי הבהירות של המערכת | |
| System Settings | הגדרות המערכת | |
| temporal dithering | dithering לאורך זמן | Avoid an unfamiliar literal translation. |
| Thermal | הדמיה תרמית | |
| UI scale matching | התאמת קנה המידה של הממשק | |
| Undo | ביטול השינויים | Discards pending system display configuration changes rather than dismissing the settings window. |
| Unexposed refresh rate | קצב רענון שאינו חשוף | Absent from standard mode list. |
| Unsharp Mask | מסכת חידוד | |
| Variable | משתנה | Refresh-rate context. |
| Vibrance | חיות הצבעים | |
| Vignette | הכהיית שוליים | |
| virtual screen | מסך וירטואלי | Software-created display. |
| Volume | עוצמת שמע | Use consistently in paired shortcut labels. |
| Window/source shadow | צל | Distinct from the Shadow image adjustment (אזורים כהים). |
| X-Ray | רנטגן | |

## Retained terms

Product/technology identifiers remain in English: BetterDisplay, Pro, LG, Philips, Yamaha, Samsung, macOS, webOS, HDR, HiDPI, LoDPI, EDID, DisplayID, UUID, NTSC, HDMI, Option, Command. Visible website domains and URLs are unchanged. `%@ %@` is a composition-only value; manufacturer suffix values are unchanged by design.

Retain API/product identifiers including CGDirectDisplayID, Apple Silicon, Night Shift, True Tone, AirPlay, Sidecar, DisplayPort, Base64, WOL, Metal and LUT. Downspread, DPCD, Display P3, HDMI-CEC, HDCP, Liquid Retina, PIN, Rec. 709, Rec. 2100 PQ, MusicCast, S/PDIF, VMM7100, RGB, SDR, Rosetta, SCS and PWM retain their standard names. Underscan remains a technical English label.

### Unchanged complete values

The following values intentionally retain their English or technical notation. Preserve source entries marked `shouldTranslate: false`.

- Website labels: `[betterdisplay.pro](https://betterdisplay.pro)` and `[betterdisplay.pro/buy](https://betterdisplay.pro/buy)`.
- Composition/brand templates: `%@ %@`, `%@ (LG)`, `%@ (Philips)`, `%@ (Yamaha)`, and `HDMI %lld%@` (the HDMI template has LRI/PDI isolation).
- Numeric notation: `0.5x`, `1.0x`, `1.5x`, `2.0x`, `2.5x`, `0°`, `90°`, `180°`, `270°`, `4`, `100`, `1000`, `4:2:0`, `4:2:2`, `4:4:4`.
- Product, protocol and technical identifiers: `Apple`, `Apple Silicon`, `CGDirectDisplayID`, `DDC`, `Display P3`, `Downspread`, `DPCD`, `HDMI-CEC`, `HDR`, `HiDPI`, `Intel`, `LoDPI`, `PIN`, `Pro`, `Rec. 709`, `Rec. 2100 PQ`, `RGB`, `SDR`, `sRGB`, `Underscan`, `URL`, `USB`, `UUID`, `Yamaha AVR`, `YCbCr`.

Embedded firmware labels (for example QuickStart+, Always Ready, Auto Power Sync and Networked Standby), API names, hardware identifiers, product names, and literal payloads remain recognizable in English where needed. Hebrew help explains their role. Manifest modifiers are translated consistently throughout, including the automatic fallback warning.

## References

- [Apple Hebrew display guidance](https://support.apple.com/he-il/guide/mac-help/-mh40583/mac).
- [Apple Hebrew settings guidance](https://support.apple.com/he-il/guide/mac-help/mchl211c911f/mac).
- Installed macOS Hebrew permission terminology: `ACCESSIBILITY` in `/System/Library/ExtensionKit/Extensions/SecurityPrivacyExtension.appex/Contents/Resources/Localizable.loctable`.

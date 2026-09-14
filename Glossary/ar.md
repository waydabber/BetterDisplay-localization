# Translation Glossary — Arabic (ar)

Maintained by [@aldoraibi](https://github.com/aldoraibi). Every string in the Arabic
catalog was reviewed by a native speaker; this file records the decisions behind the
terms that recur, so future additions stay consistent with what already ships.

## Conventions

**1. Apple's official Arabic wins.** Where macOS ships an Arabic term for a concept,
BetterDisplay uses that exact term — even where a different word would be more literal
or more elegant. A user should meet the same word in System Settings and in this app.

**2. Acronyms stay in English.** `DDC`, `EDID`, `OSD`, `HDR`, `XDR`, `LUT`, `CEC`,
`GPU`, `HiDPI`, `LoDPI`, `PWM`, `nits`, `framebuffer`, `Sidecar`, `DisplayLink`, and
`Gamma` are left untranslated. Arabic-speaking users of a display utility know these
forms; literal Arabic renderings actively hurt comprehension, and Photoshop's own
Arabic build keeps several of them in English for the same reason.

**3. Describe the effect, not the mechanism — unless the mechanism is the point.**
For warnings, the user needs to know what will happen to the picture. For settings
labels, precision wins.

**4. Brevity where the qualifier is self-evident.** "Alphanumeric serial number" is
translated simply as "serial number" — an Arabic reader already assumes a serial
contains letters and digits, and the full rendering is heavy.

**5. Keep the established technical phrasing.** Use `دقة` for resolution and
`قائمة الدقة` for a resolution list. This is a catalog terminology choice, not a
general prohibition on pluralizing Arabic verbal nouns. Use `شاشات المجموعة` for
"member displays" to keep the relationship explicit and natural.

### Writing and directionality

**Tanween placement.** Arabic writes the accusative tanween as `ـًا`, not `ـاً`. New strings should follow this spelling.

**Connective *waw*.** English technical prose runs in short sentences, and translating
each one with a leading "و" (and) produces a chain that reads as a run-on in Arabic.
Sentences that begin a new idea start without it.

**Vocalization where meaning is at stake.** Arabic is written unvocalized, but a few
strings need a single diacritic to disambiguate. For example `غيّرَ تطبيق آخر…`
("another app *changed*…") — without the fatha on the *ra*, the verb reads as an
imperative and the sentence becomes an instruction rather than a status message.

**Variable counts and technical angles.** When one string serves every count,
use a natural count label (for example `عدد التثبيتات المفعّلة…: %lld`) rather than
placing a fixed singular noun after the number. Keep Western-digit rotation angles
such as `90°` together in an LTR isolate inside Arabic command labels.

## Terminology

### A – C

| English | Arabic | Notes |
| --- | --- | --- |
| Accessibility | تسهيلات الاستخدام | Apple's macOS term. |
| Adaptation (display) | مواءمة | Consistent with the "Display Adaptations" menu. |
| Aspect ratio | نسبة الأبعاد | |
| Associated | مرتبط | |
| Backlight | الإضاءة الخلفية | |
| Brightness | السطوع | Apple's term. |
| Chroma subsampling | تقليل عينات اللون | Not compression — the technique reduces color *samples* relative to luma. "ضغط اللون" (compression) was rejected as inaccurate. |
| Clip (HDR content) | اقتطاع | Values above the ceiling are truncated and collapse to peak level. "طمس" (blur/efface) was considered and rejected — the maintainer confirmed the levels *collapse to a single level*, which is truncation, not loss of sharpness. |
| Color table | جدول الألوان | |
| Combined brightness | السطوع المدمج | |
| Crop | اقتصاص | |

### D – I

| English | Arabic | Notes |
| --- | --- | --- |
| Discard | حذف | Virtual-screen/group deletion; matches the action labels. Keep distinct from reversible "Disconnect" (فصل). Discarding calibration instead uses تجاهل المعايرة. |
| Disconnect | فصل | |
| Display | شاشة | |
| Display group | مجموعة الشاشات | |
| Dock animate | تحريك | Apple's own wording in System Settings ▸ Desktop & Dock. |
| Dock bounce | تحريك | Apple's own wording in System Settings ▸ Desktop & Dock. |
| Firmware | البرنامج الثابت | |
| Framebuffer | framebuffer | Preserve the technical term in both mode labels and explanatory text; a generic buffer omits the image-specific meaning. |
| Headroom | هامش | |
| Input Source | مصدر الإدخال | Menu label; the descriptive strings were unified to match it. |

### L – P

| English | Arabic | Notes |
| --- | --- | --- |
| Layout protection | حماية الترتيب | |
| Login Items | عناصر تسجيل الدخول | Apple's macOS term. |
| Main status | الحالة الرئيسية | A named setting, not a description — kept verbatim wherever it is referenced. |
| Manifest | البيان | |
| Member displays | شاشات المجموعة | Makes the relationship to the display group explicit. |
| Mirror | محاكاة الشاشة | Apple's macOS term. An earlier draft used "عكس" (reflect) and was corrected across the whole catalog. |
| Mirroring | محاكاة الشاشة | Apple's macOS term. An earlier draft used "عكس" (reflect) and was corrected across the whole catalog. |
| Night Shift | الإضاءة الدافئة | Apple's official Arabic name. |
| Notch (hardware description) | نتوء الكاميرا | Used in the Liquid Retina hardware description. Mode/filter controls keep the existing effect-based wording ارتفاع سطح المكتب الموسّع. |
| Opacity | عتامة | Increasing opacity makes the layer less transparent; do not label it شفافية (transparency). |
| Pairing | الاقتران | |
| Picture in Picture | صورة داخل صورة | |
| Placeholder (control) | — | Rendered descriptively: "no longer performs any function; kept in place". |
| Polling | التحقق الدوري | |

### R – Z

| English | Arabic | Notes |
| --- | --- | --- |
| Regular expression | تعبير نمطي | |
| Remote (control device) | جهاز التحكم عن بعد | Not the colloquial loanword. |
| Resolution | دقة | Preserve the catalog's established phrasing, including قائمة الدقة; see principle 5. |
| Resolutions | دقة | Preserve the catalog's established phrasing, including قائمة الدقة; see principle 5. |
| Soft-connect | التوصيل البرمجي | |
| Soft-disconnect | الفصل البرمجي | |
| Software dimming | التعتيم البرمجي | |
| Stream (noun, menu item) | البثّ | Definite article for the standalone menu noun; commands such as بث الشاشة use the action noun without the article. |
| Sync source | مصدر المزامنة | |
| Touch Bar | شريط اللمس | Apple's official Arabic name. |
| True Tone | انسجام اللون | Apple's official Arabic name. |
| UI scale matching | مطابقة مقياس الواجهة | |
| Upscaling (brightness) | رفع السطوع | |
| Virtual screen | شاشة افتراضية | |
| Watched display | الشاشة المراقَبة | Passive — the app watches it; it does not watch anything. |
| White point | نقطة البياض | |

### Additional expressions

| English | Arabic | Notes |
| --- | --- | --- |
| Computer monitor | شاشة حاسوب | Matches the display-role label; does not mean an external display. |
| Discard & Remove Color Profile | — | Removes both the virtual screen and its color profile; the Arabic action must identify both objects. |
| Outdated License | ترخيص قديم | The license does not cover the current major version. Avoid ترخيص منتهٍ, which states that it has expired. |
| Rotated orientation | تبديل العرض والارتفاع | Virtual-screen toggle that swaps configured width and height. Use the same wording in Settings and the app menu. |

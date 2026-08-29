# Translation Glossary — Arabic (ar)

Maintained by [@aldoraibi](https://github.com/aldoraibi). Every string in the Arabic
catalog was reviewed by a native speaker; this file records the decisions behind the
terms that recur, so future additions stay consistent with what already ships.

## General principles

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

**5. Arabic grammar is not negotiable.** `دقة` (resolution) is a *masdar* — a verbal
noun — and masdars are not pluralized in Arabic, so it stays singular even where the
English says "resolutions". Similarly, `عضو` (member) is used for people, not for
objects, so "member displays" becomes "the group's displays".

---

## Glossary

### A – C

| English | Arabic | Reasoning |
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

### D – H

| English | Arabic | Reasoning |
| --- | --- | --- |
| Discard | شطب | Deliberately distinct from "Disconnect" (فصل), which is a reversible action in the virtual-screen flow. Keeping them different matters: the app tells users to prefer one over the other. |
| Disconnect | فصل | |
| Display | شاشة | |
| Display group | مجموعة الشاشات | |
| Dock bounce / animate | تحريك | Apple's own wording in System Settings ▸ Desktop & Dock. |
| Firmware | البرنامج الثابت | |
| Headroom | هامش | |
| Input Source | مصدر الإدخال | Menu label; the descriptive strings were unified to match it. |

### L – P

| English | Arabic | Reasoning |
| --- | --- | --- |
| Layout protection | حماية الترتيب | |
| Login Items | عناصر تسجيل الدخول | Apple's macOS term. |
| Main status | الحالة الرئيسية | A named setting, not a description — kept verbatim wherever it is referenced. |
| Manifest | البيان | |
| Member displays | شاشات المجموعة | "عضو" (member) is used for people in Arabic, not for objects. |
| Mirror / Mirroring | محاكاة الشاشة | Apple's macOS term. An earlier draft used "عكس" (reflect) and was corrected across the whole catalog. |
| Night Shift | الإضاءة الدافئة | Apple's official Arabic name. |
| Pairing | الاقتران | |
| Picture in Picture | صورة داخل صورة | |
| Placeholder (control) | — | Rendered descriptively: "no longer performs any function; kept in place". |
| Polling | التحقق الدوري | |

### R – Z

| English | Arabic | Reasoning |
| --- | --- | --- |
| Regular expression | تعبير نمطي | |
| Remote (control device) | جهاز التحكم عن بعد | Not the colloquial loanword. |
| Resolution / Resolutions | دقة | Always singular — see principle 5. |
| Soft-connect / disconnect | التوصيل / الفصل البرمجي | |
| Software dimming | التعتيم البرمجي | |
| Stream (noun, menu item) | البثّ | Definite article when it names a menu item; indefinite when used as a verb. |
| Sync source | مصدر المزامنة | |
| Touch Bar | شريط اللمس | Apple's official Arabic name. |
| True Tone | انسجام اللون | Apple's official Arabic name. |
| UI scale matching | مطابقة مقياس الواجهة | |
| Upscaling (brightness) | رفع السطوع | |
| Virtual screen | شاشة افتراضية | |
| Watched display | الشاشة المراقَبة | Passive — the app watches it; it does not watch anything. |
| White point | نقطة البياض | |

---

## Style notes

**Tanween placement.** Arabic writes the accusative tanween as `ـًا`, not `ـاً`. The
catalog was swept once for this; new strings should follow it.

**Connective *waw*.** English technical prose runs in short sentences, and translating
each one with a leading "و" (and) produces a chain that reads as a run-on in Arabic.
Sentences that begin a new idea start without it.

**Vocalization where meaning is at stake.** Arabic is written unvocalized, but a few
strings need a single diacritic to disambiguate. For example `غيّرَ تطبيق آخر…`
("another app *changed*…") — without the fatha on the *ra*, the verb reads as an
imperative and the sentence becomes an instruction rather than a status message.

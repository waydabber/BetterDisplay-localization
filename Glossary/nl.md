# Translation Glossary — Dutch (nl)

Use natural Dutch macOS wording and informal **je** in explanatory text. UI commands generally use the imperative.

## Conventions

A feature heading should not append **ingeschakeld** unless the source reports an active state. **Synchrone weergave** alone is sufficient for the mirroring menu heading inside a display section.

Keep Markdown and runtime placeholders intact; positional printf placeholders are equivalent to source-order placeholders when their argument indices match. UI names inside Markdown backticks may be translated, but machine identifiers such as `face.smiling`, `LUT_3D_SIZE`, URL destinations, `${...}` interpolations and printf argument identities must remain exact. Literal percentages are not printf arguments.

## Terminology

| English | Dutch | Notes |
| --- | --- | --- |
| 1:1 pixel mapping | 1:1-pixelmapping | |
| absolute adjustment | op een opgegeven waarde | Sets the value to an amount; preserve the distinction in Shortcuts help. |
| Accessibility | Toegankelijkheid | |
| association | koppeling | Virtual-screen association; distinct in context from connection. |
| brightness | helderheid | |
| brightness upscaling | opschaling / helderheidsopschaling | Brightness context. |
| built-in display | ingebouwd scherm | Only for a built-in display. |
| color gamut | kleurbereik | |
| color profile | kleurenprofiel | |
| color table | kleurentabel | |
| compositor | compositor | retain technical term where appropriate |
| compositor filter | compositorfilter | Rendering mechanism. |
| connect | verbinden | Connection action. |
| Control Center | Bedieningspaneel | macOS UI name. |
| custom control | eigen bediening | |
| Device Control and Data Access | Apparaatbeheer en gegevenstoegang | macOS 27 permission label; verified against installed Dutch SecurityPrivacyExtension Localizable.loctable (ACCESSIBILITY). Keep Toegankelijkheid for older permission UI. |
| Discard | verwijder | Destructive actions for virtual screens, display groups and calibration. |
| disconnect | loskoppelen | Connection action. |
| display | scherm | |
| Exposure | Belichting | Image adjustment. |
| framebuffer | framebuffer | retain technical term where appropriate |
| HDR Filter Pipeline | HDR-filterpijplijn | Feature name. |
| Highlight | Hooglichten | Bright tonal regions in photographic/video controls; never Licht uit, which means turning lights off. |
| hospitality menu | hotelmenu | |
| Ignore | negeer | Do not use for destructive Discard actions. |
| manufacturer ID | fabrikant-ID | |
| Metal overlay | Metal-overlay | Rendering mechanism. |
| mirroring | synchrone weergave | |
| native mode | native modus | Panel's native pixel resolution context. |
| native resolution | native resolutie | Panel's native pixel resolution. |
| natively connected | Rechtstreeks aangesloten | Distinguishes native display connections from indirect/virtual connections. |
| Notification Center | Meldingencentrum | macOS UI name. |
| overlay | overlay | retain technical term where appropriate |
| pair | koppelen | Device pairing; never paren. |
| paired | gekoppeld | Device pairing. |
| pairing status | koppelingsstatus | Device pairing. |
| Picture in Picture | beeld-in-beeld / PIP | Full term and abbreviation. |
| Privacy & Security | Privacy en beveiliging | |
| quantization | kwantisering | |
| recursive desktop image | oneindig spiegeleffect | Distinct from the mirroring feature name Synchrone weergave. |
| refresh rate | verversingsfrequentie | |
| relative adjustment offset | met een opgegeven hoeveelheid | Changes the existing value by an amount; preserve the distinction in Shortcuts help. |
| resolution | resolutie | |
| sample (audio) | sample | Never monster. |
| screen | scherm | |
| Screen Recording | Schermopname | |
| service menu | servicemenu | |
| software-based | softwarematig / softwarematige | Avoid programmatisch, which suggests programmatic/API control. |
| stream | stream | retain technical term where appropriate |
| System Settings | Systeeminstellingen | |
| toggle (command) | Schakel … in/uit | Use Schakel … om where appropriate; bare Schakel … leaves the action incomplete. |
| toggle (noun) | Schakelaar | Toggle control. |
| Tools | Gereedschap | App menu. |
| UI scale matching | UI-schaalafstemming | Compact form suitable for narrow settings buttons. |
| Video Filters | Videofilters | Feature name. |
| virtual screen | virtueel scherm | |
| warp mouse cursor | Verplaats muisaanwijzer | Moves the pointer rather than distorting it. |

## Retained terms

Retain product names, protocol names (DDC, EDID, DisplayID, HDMI-CEC), identifiers, units and URL targets.

Identical-to-English strings are intentional where they are product/protocol names, code identifiers, placeholder-only values, units/numbers, or shared Dutch technical vocabulary: Apple, Apple Silicon, Display P3, Display Stream Compression, DDC, DPCD, HDMI-CEC, HDR/SDR, HiDPI/LoDPI, Intel, LG alt, Rec. 709, Rec. 2100 PQ, RGB/YCbCr/sRGB, USB, UUID, CGDirectDisplayID, OSD, Pro, PIN, Build, Controller, Contrast, Gamma, Menu, Model, Native, Overlay, Parameters, Platform, Stream, Underscan, Updates, Volume, Vignette, Sepia, Downspread, regex, samples/bits/pixels and units. Numbered Zone labels and unchanged website-label links are also intentional.

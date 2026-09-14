# Translation Glossary — Hungarian (hu)

## Conventions

Use polite formal imperatives in instructions, brief noun/action labels in controls, and singular nouns after numbers. Avoid attaching Hungarian suffixes directly to unknown substituted names; use neutral constructions, or `a(z)` where an article cannot be determined. Retain positional format specifiers when the English localization supplies them.

- Preserve the display/screen distinction and concise action labels; grammatical Hungarian may legitimately exceed English length.
- Preserve `${displayEntity}` and all other App Intent interpolation tokens exactly. Preserve LUT_3D_SIZE and numeric/network examples.
- Keyboard modifier combinations can use nonbreaking spaces to keep each symbol/name together.
- Literal percentages marked with U+2060 must not be misread as printf specifiers when Hungarian prose follows the percent sign.
- Shortcuts arrangement summaries use labelled reference-display and relative-position clauses so interpolated directions remain grammatical.
- Scaling multipliers retain source notation as requested by their comments.
- Installed macOS display resources use Fő kijelző and Frissítési gyakoriság, while Apple's linked Hungarian guide uses Frissítési ráta. Existing elsődleges kijelző and frissítési ráta are retained as clear, consistent app terminology; they are not claimed to match every current system label exactly.

## Terminology

| English | Hungarian | Notes |
| --- | --- | --- |
| Accessibility | Kisegítő lehetőségek | macOS permission category. |
| Actual | tényleges | |
| Advanced | Speciális | |
| Ambient light sensor | környezeti fényérzékelő | |
| Anchor point | illesztési pont | |
| App Menu | Alkalmazásmenü | |
| associated display | társított kijelző | Linked destination display. |
| Authorization | engedélyezés | |
| Background item | háttérelem | |
| Black level | feketeszint | |
| Blend mode | keverési mód | |
| Bloom | Ragyogás | |
| brightness upscaling | fényerőnövelés | Software increase beyond normal brightness. |
| Broadcast | szórás | |
| Chroma subsampling | színmintavételezés | |
| Classic | Klasszikus | |
| CLI designation | CLI-azonosító | Unique command-line control name. |
| color depth | színmélység | Connection color configuration. |
| Color gamut | színtartomány | |
| color mode | színmód | Connection color configuration. |
| Color profile | színprofil | |
| Color temperature | színhőmérséklet | |
| color-table | színtábla | GPU color lookup table. |
| compositor | kompozitor | Rendering path. |
| Configuration Protection | konfigurációvédelem | Reapplies protected settings. |
| Configuration run ID | konfigurációs futás azonosítója | |
| control | vezérlőelem | Individual control. |
| Control Center | Vezérlőközpont | |
| controller | vezérlő | Device backend. |
| Create a new | Új vezérlőelem létrehozása | Standalone heading in CustomControlsSheet. |
| Crop | kivágás | |
| Crop origin | kivágás kezdőpontja | |
| Dark wake | képernyő bekapcsolása nélküli ébredés | |
| DDC capabilities report | DDC-képességjelentés | |
| DDC power | DDC-tápvezérlés | |
| Decimal point | tizedespont | Numeric parsing help: integration parser requires a dot, not a localized comma. |
| Decompression | kitömörítés | |
| Delta syncing | változásalapú szinkronizálás | Preserves relative differences. |
| Device Control | Eszközvezérlés | |
| Device control and data access | eszközvezérlés és adathozzáférés | Verified against installed macOS 27 SecurityPrivacyExtension Localizable.loctable. |
| Dimming | sötétítés | |
| display | kijelző | Physical/logical display. |
| display group | kijelzőcsoport | Group of displays. |
| Display notch | kijelzőbevágás | |
| Display off | kijelző kikapcsolása | Separate hardware power command. |
| Display Preset | kijelző-előbeállítás | Apple display preset. |
| Display to match | referenciakijelző | |
| DisplayPort branch device | DisplayPort-elosztóeszköz | |
| Dot Screen | Pontrács | |
| DSC slice | DSC-szelet | |
| Edge Work | Metszethatás | Image filter. |
| EDID identity | EDID-azonosítóadatok / kijelzőazonosítás | Use azonosítóadatok for the identifying serial/vendor/model data and kijelzőazonosítás for recognition/continuity. A UUID is an azonosító; avoid the literal azonosság. |
| EDID override | EDID-felülírás | Software override, distinct from hardware write. |
| EDR headroom | EDR-tartalék | |
| Exposure | Expozíció | |
| Fine scale | finom lépésköz | |
| flexible scaling | rugalmas méretezés | Flexible resolution feature. |
| Format string | formátumkarakterlánc | |
| framebuffer | képpuffer | GPU image buffer. |
| Framerate | képkockasebesség | |
| Full Manifest | Teljes manifeszt | LG webOS registration permission manifest. |
| Gain | erősítés | |
| Gloom | Borongás | |
| Hard disconnect | fizikai leválasztás | |
| Hard reconnect | fizikai újracsatlakoztatás | |
| Hatched Screen | Vonalkázás | |
| HDR Filter Pipeline | HDR-szűrőfeldolgozás | |
| Highlight | csúcsfények | |
| Hinted | jelzett | Reported capability hint. |
| Hospitality Menu | szállodai menü | TV hotel setup menu. |
| Hue | színezet | |
| Integer Scaling | Egész számú méretezés | |
| layout protection | elrendezésvédelem | Protects display arrangement. |
| LG alt | LG alt. | Narrow DDC input-source table heading; explain as alternatív in adjacent help. The longer heading wraps poorly. |
| Limited Range | Korlátozott tartomány | |
| Line buffer | sorpuffer | |
| Line Screen | Vonalrács | |
| Login Items | Bejelentkezési elemek | |
| Luminance | fénysűrűség | |
| Magnification | nagyítás | |
| main display | elsődleges kijelző | macOS main display. |
| Median | Medián | |
| Metal overlay | Metal-rátét | Rendering path. |
| mirroring | tükrözés | Keep distinct from streaming. |
| Model-specific adaptations | modellspecifikus igazítások | |
| Monochrome | Monokróm | |
| Motion Blur | Mozgási elmosás | |
| Mouse click-through | egérkattintások átengedése | |
| Neutral value | semleges érték | |
| Nits | nit | Luminance unit. |
| Nominal | névleges | |
| Notification Center | Értesítési központ | |
| Notification dispatch | folyamatközi értesítésküldés | Integration help; not a visible notification. |
| Notifications | Értesítések | Settings pane. |
| OSD shadow | árnyék | |
| Overlay | rátét | Rendering layer; distinct from the blend mode. |
| Overlay blend | Átfedés | Distinct from rendering rátét. |
| Passthrough | átengedés | |
| Payload | adattartalom | |
| Peak brightness | csúcsfényerő | |
| Photo effect | Fotóhatás | Retain the recognizable preset names; see Retained terms. |
| PIP | PIP (kép a képben) | Retain abbreviation in compact labels. |
| Pixel rate | képpontsebesség | |
| Pointillize | Pontozás | |
| Polling | időszakos lekérdezés (polling) | |
| PPI | képpontsűrűség (képpont/hüvelyk) | In prose prefer képpontsűrűség (PPI) over heavily suffixed acronym constructions. |
| Preferred Scale | Előnyben részesített méretezés | |
| Privacy & Security | Adatvédelem és biztonság | Settings pane. |
| Privileged helper | emelt jogosultságú segédszolgáltatás | |
| Quantization | Kvantálás | |
| Quit %@ | Kilépés: %@ | Match command references; avoids suffixes on unknown app names and fits the app menu. |
| Record | Rögzítés | Compact shortcut recorder field. |
| Redundancy filter | ismétlődésszűrés | |
| Reference white | referenciafehér | |
| refresh rate | frissítési ráta | Frequency in Hz. |
| Regex | reguláris kifejezés | Retain regex in compact technical selectors/matching-mode labels. |
| Reinitialize | újrainicializálás | |
| Reset | alaphelyzetbe állítás | |
| Reset Default | Alapszűrő | Compact control restoring the default filter, not display configuration. |
| screen | képernyő | Screen surface. |
| Screen blend | Szendvicsnegatív | Not a display. |
| Screen off | képernyő kikapcsolása | |
| Screen on | képernyő bekapcsolása | |
| Screen Recording | Képernyőfelvétel | Permission label; follow source version terminology. |
| Self-Stream | saját képernyő közvetítése | |
| Self-stream destination | Saját kijelző + videoszűrők | Within the display-streaming menu. |
| Sepia | Szépia | |
| service menu | szervizmenü | TV installation/maintenance menu. |
| Set Default - Auto Calibrate | Alapértelmezett beállítása – Automatikus kalibrálás | Calibration button; use the same wording in quoted help. |
| Shadow (image filter) | Árnyékok | Distinct from OSD shadow. |
| Sharpness | Élesség | |
| Shell script | shellszkript | |
| Shortcuts | Parancsok | Apple automation app. |
| Show All | Mind | Compact display-mode filter control. |
| Sidebar | Oldalsáv | |
| Signal space | jel színtere | |
| Simple Manifest | Egyszerű manifeszt | LG webOS registration permission manifest. |
| Sink | vevő | |
| Smooth transitions | sima átmenetek | |
| streaming | közvetítés | Keep distinct from mirroring. |
| Subslider | részcsúszka | |
| Synchronization | szinkronizálás | |
| System Settings | Rendszerbeállítások | macOS settings app. |
| Tag ID | címkeazonosító | |
| temporal dithering | időbeli dithering | Keep established English technical term. |
| Thermal | Hőkép | |
| Tiled display tile | mozaikelem | |
| Title bar | címsor | |
| Toggle | Átkapcsolás | Action. |
| Toggles | Kapcsolók | Controls. |
| Tolerance | tűréshatár | |
| Tone mapping | tónusleképezés | |
| Traditional OSD | Hagyományos OSD | |
| UI scale matching | felületméret-egyeztetés | |
| Underscan | alulpásztázás | Follows Apple's Hungarian display-settings terminology. |
| Unexposed refresh rate | nem listázott frissítési ráta | Not necessarily unavailable; use this wording consistently. |
| Uniformity Correction | Egyenletesség-korrekció | |
| Unsharp Mask | Életlen maszk | |
| Update frequency | frissítési gyakoriság | Polling, distinct from display refresh rate. |
| Vibrance | Élénkség | |
| Video Filters | Videoszűrők | |
| Vignette | Vignetta | |
| Virtual screen | virtuális képernyő | |
| Warp mouse cursor | egérmutató áthelyezése | |
| White point | fehérpont | |
| WOL magic packet | ébresztőcsomag | |
| X-Ray | Röntgen | |
| Year %@, week %lld | `%1$@. év, %2$lld. hét` | Keep year as text and week as an integer. |

## Retained terms

Retain URLs, product names, HDR, XDR, EDID, DisplayID, GPU, HDMI-CEC, Metal, HiDPI, LoDPI, NTSC, UUID, CLI, OSD, LUT and keyboard labels Option/Command. Preserve firmware option labels quoted in the TV power prerequisite warning. Apple and Apple Silicon remain complete brand/family labels. `%@ Tri-Screen` names the Monduo product configuration, as confirmed in `App/Support/Adaptations.swift`. Integration example identifier `My parameter` remains exact.

Photo-effect names Chrome, Fade, Instant, Noir, Process and Transfer remain recognizable Core Image preset names under Fotóhatás. Core Image has Hungarian effect names, but they vary in naturalness and differ from established app terminology. Retaining these names is a deliberate choice, not a rule that API identifiers must always remain English; a future native-speaker review can assess them as a group.

### Unchanged complete values

The following values are intentionally identical to their English key or English localization (including positional-placeholder equivalents). They are product/protocol/API names, conventional technical terms, units, numerical notation, or formatting-only compositions. Their retention is deliberate.

- `[betterdisplay.pro](https://betterdisplay.pro)`
- `[betterdisplay.pro/buy](https://betterdisplay.pro/buy)`
- `%@ (LG)`
- `%@ (Philips)`
- `%@ (Yamaha)`
- `%@ %@`
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
- `bit`
- `Build`
- `CGDirectDisplayID`
- `DDC`
- `Display P3`
- `Display Stream Compression (DSC)`
- `Downspread`
- `DPCD`
- `Gamma`
- `HDMI %lld%@`
- `HDMI-CEC`
- `HDR`
- `HiDPI`
- `Intel`
- `LoDPI`
- `lux`
- `mm`
- `OK`
- `OSD`
- `Philips Smart TV`
- `PIN`
- `Platform`
- `Pro`
- `Rec. 709`
- `Rec. 2100 PQ`
- `regex`
- `RGB`
- `SDR`
- `Sidecar UUID`
- `sRGB`
- `URL`
- `USB`
- `UUID`
- `Yamaha AVR`
- `YCbCr`

## References

- [Apple Hungarian display settings guide](https://support.apple.com/hu-hu/guide/mac-help/mh40768/mac): Rendszerbeállítások, Elrendezés, Előbeállítás and Frissítési ráta. Terminology differences from installed resources are explained in Conventions.
- Installed macOS resources also confirmed Képernyőfelvétel and Eszközvezérlés és adathozzáférés.

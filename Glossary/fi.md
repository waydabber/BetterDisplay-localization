# Translation Glossary — Finnish (fi)

Standard Finnish as used in Finland. Use concise neutral UI Finnish and imperative verbs for actions.

## Conventions

- Avoid inflecting unknown dynamic names by restructuring the sentence. Decimal values are formatted by the app; retain format argument types.
- Retain product and protocol names (BetterDisplay, Apple, LG webOS, Samsung, Metal, HDMI, DisplayPort, DDC, EDID, DisplayID, HDR, SDR, XDR, HiDPI, LoDPI, CLI, UUID), recognized units, machine-facing strings, URLs, and literal code examples. Tri-Screen is a product setup name; Simple Manifest is a protocol mode identifier. Option and Command retain keycap names alongside glyphs.
- HW-min./HW-maks., UI, PIP, OSD, FPS and LUT are compact technical abbreviations; longer explanatory text supplies Finnish context. Gamma, OK, regex, Downspread, numeric scale multipliers, standardized color spaces and formats remain unchanged intentionally. Device firmware setting names and EDID/VCP/API identifiers retain recognizable spelling.
- Finnish cardinals require one (integer 1) and other. Use separate forms for additional color modes, remaining days, trial days and bits per sample. In inflected count expressions such as “1/2 asennuksessa” and “1/2 määrityksessä”, the displayed noun is unchanged. Numbered blocks/groups/lines/weeks and error codes are identifiers, not cardinal noun phrases. Express the two CUBE counts as numeric totals to avoid competing agreement requirements.
- Percentage symbols take a colon before case endings when required by the sentence (`saavuttaa 0⁠%:n`). For omitted final compound elements, `Scroll Lock- ja Pause-näppäimet` and `Hallitse näyttöä- tai Hallitse virtuaaliruutua -valikko` are correct: the omission hyphen attaches to the preceding word even after a multiword name.
- Apple Finnish help supplies standard macOS pane and feature terminology; app-specific technical translations are independent choices, not claimed official Apple terms.

## Terminology

| English | Finnish | Notes |
| --- | --- | --- |
| Accessibility | Käyttöapu | |
| Apple Display Preset | Applen näytön esiasetus | Standalone feature label; use Applen esiasetus in sentences already identifying a display, avoiding the repeated possessive chain näytön … Applen näytön esiasetus. |
| associated display | liitetty näyttö | Logical association, distinct from a physical connection. |
| blend mode | sekoitustila | |
| brightness | kirkkaus | |
| brightness upscaling | kirkkauden tehostus | |
| Classic | Perinteinen | |
| color depth | värisyvyys | |
| color mode | väritila | |
| compositor | koostaja | |
| Configuration Protection | asetusten suojaus | |
| contrast | kontrasti | |
| control | säädin / ohjaus | Säädin for a UI/value control; ohjaus for the mechanism. |
| controller | ohjain | |
| Device Control and Data Access | Laitehallinta ja tietojen käyttö | Exact installed Apple pane name; use in navigation instructions. |
| dimming | himmennys | |
| display | näyttö | |
| display mode | näyttötila | Menu label Näyttötila; help references use Näyttötila-valikko. |
| display power off | sammuta näyttö | |
| Display Preset | näytön esiasetus | |
| Dot Screen | pisterasteri | Printing-pattern filter. |
| framebuffer | kuvapuskuri | |
| group member display | jäsennäyttö | |
| Hatched Screen | viivoitusrasteri | Printing-pattern filter. |
| integration | integraatio | |
| keyboard shortcut | näppäinoikotie | |
| layout protection | asettelun suojaus | |
| Line Screen | viivarasteri | Keep distinct from Hatched Screen in adjacent menu labels. |
| luminance | luminanssi | |
| menu bar | valikkorivi | |
| mirroring | peilaus | |
| native Apple keyboard control | järjestelmänäppäinten ohjaus | |
| native audio control | järjestelmän äänenohjaus | |
| native resolution | natiivitarkkuus | |
| nits | nitiä / niteinä | Explanatory text; string-formatted numeric readouts use invariant nit. Do not use the erroneous compound stem nitti-. |
| OSD | OSD-ilmaisin | Use where explanatory wording helps; OSD denotes the on-screen indicator. |
| physical disconnect | fyysinen irrotus | |
| Picture in Picture | kuva kuvassa | PIP in compact labels. |
| pointer | osoitin | |
| refresh rate | virkistystaajuus | |
| resolution | tarkkuus | |
| rotated orientation | Vaihda leveys ja korkeus | Virtual-screen dimension swapping, not rotation of existing image content. |
| scaling | skaalaus | |
| screen | ruutu | Captured surface. |
| Screen (blend mode) | rasteri | Blend mode, not a display device. |
| screen off | sammuta ruutu | |
| screen on | sytytä ruutu | |
| Screen Recording | Näyttötallennus | Exact installed Apple pane name; general permission prose may use näytön tallennusoikeus. |
| Shortcuts | Pikakomennot | |
| Sidebar | Sivupalkki | |
| software disconnect | ohjelmallinen katkaisu | |
| software overlay | peittotaso | |
| Standard | Tavallinen | |
| streaming | suoratoisto | |
| System Settings | Järjestelmäasetukset | |
| temporal dithering | ajallinen rasterointi | |
| third-party virtual display | virtuaalinäyttö | |
| Traditional OSD | Alkuperäinen OSD | Preserve the distinction between app-drawn and system-drawn indicators. |
| UI scale matching | käyttöliittymän koon sovitus | UI-koko is the compact menu abbreviation. |
| virtual screen | virtuaaliruutu | |

## References

- [Apple: Näytöt-asetukset](https://support.apple.com/fi-fi/guide/mac-help/mh40768/mac) and [Käyttöapu-asetukset](https://support.apple.com/fi-fi/guide/mac-help/mchlp1400/mac).
- [Apple: referenssitilojen luminanssi](https://support.apple.com/fi-fi/guide/mac-help/mchl50ecf3c4/mac), for nitiä/niteinä.
- [Apple: Kumoa/Peru usage](https://support.apple.com/fi-fi/guide/preview/prvw15636/mac).
- [Unicode: Finnish cardinal forms](https://unicode.org/cldr/charts/46.1/verify/numbers/fi.html).
- [Adobe: Finnish Screen blend mode](https://helpx.adobe.com/fi/photoshop/desktop/repair-retouch/adjust-light-tone/blending-mode-descriptions.html) and [diffusion dithering terminology](https://helpx.adobe.com/fi/photoshop/desktop/adjust-color/color-modes/convert-an-image-to-bitmap-mode.html).
- Installed macOS Finnish SecurityPrivacyExtension `Localizable.loctable` was checked directly for Laitehallinta ja tietojen käyttö and Näyttötallennus. These names come from Apple system resources.
- [Finnish language guidance: omission hyphens](https://kielitoimistonohjepankki.fi/ohje/yhdysmerkki-toistamatta-jatetyn-sanan-tilalla-aamu-ja-iltavuoro/).

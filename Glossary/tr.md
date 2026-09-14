# Translation Glossary — Turkish (tr)

## Display terminology

| English | Turkish | Notes |
| --- | --- | --- |
| brightness upscaling | parlaklık yükseltme | Increasing available brightness, not image resolution or a software upgrade. Yazılımla parlaklık artırma is appropriate explanatory prose. |
| chroma subsampling | kroma alt örnekleme | Chroma is not chromium. |
| compositor filter | Compositor Filtresi | Preserve Compositor rather than mistranslating it as a component. |
| configuration protection | Yapılandırma Koruması | Protecting configured display properties. |
| dimming | karartma | Imperative: karart. |
| display | ekran | Turkish naturally uses ekran for both. Use monitör where the physical monitor distinction helps. |
| display group | ekran grubu | Avoid görüntüleme grubu, which suggests an act of viewing. |
| display mode | ekran modu | Includes resolution, refresh rate and related mode properties. |
| flexible scaling | esnek ölçeklendirme | Feature name; avoid yumuşak ölçeklendirme. |
| framebuffer | framebuffer / ekran belleği (framebuffer) | Keep the established identifier recognizable. |
| gain | kazanç | Color channel adjustment. |
| layout protection | düzen koruması | Arrangement and main-display protection. |
| main display | ana ekran | Main status is not a favorite. |
| main status | ana ekran durumu | Main status is not a favorite. |
| mirroring | yansıtma | Action: yansıt. |
| overlay | kaplama | A layer applied over the image; not overlap. |
| Picture in Picture | Resim İçinde Resim | Keep the established PIP abbreviation consistent. |
| PIP | PIP | Keep the established PIP abbreviation consistent. |
| refresh rate | yenileme hızı | |
| resolution | çözünürlük | Never karar in display configuration. |
| screen | ekran | Turkish naturally uses ekran for both. Use monitör where the physical monitor distinction helps. |
| streaming | yayın | Action: yayınla. |
| unexposed | arayüzde sunulmayan | |
| virtual screen | sanal ekran | BetterDisplay-created screen. |

## macOS and controls

| English | Turkish | Notes |
| --- | --- | --- |
| Accessibility | Erişilebilirlik | |
| Acquired | Alındı | DDC report retrieval, never purchasing. |
| Acquiring | Alınıyor | DDC report retrieval, never purchasing. |
| Apple Display Preset | Apple Ekran Ön Ayarı | Preserve Apple in references; do not narrow it to XDR. |
| Apply | Uygula | |
| bytes | bayt | |
| Cancel | İptal | |
| control | kontrol | Existing term retained for user-facing controls. |
| Control Center | Denetim Merkezi | |
| controller | denetleyici | |
| Disabled | Devre Dışı | Status. |
| Discard | Kaldır | Deleting a virtual screen or group. |
| event | olay | Programmatic events. |
| keyboard key | tuş | Not anahtar. |
| keyboard shortcuts | klavye kısayolları | Preserve recognizable Option, Command and Shift key names with symbols. |
| model ID | model kimliği | |
| multiplier | çarpan | |
| read length | okuma uzunluğu | |
| return value regex | dönüş değeri düzenli ifadesi | |
| Shortcuts | Kısayollar | |
| System Settings | Sistem Ayarları | |
| Toggle | Aç/Kapat | Action. |
| toggle controls | açma/kapatma kontrolleri | |
| Unable to acquire | Alınamıyor | DDC report retrieval, never purchasing. |
| Vendor ID | üretici kimliği | |

## Retained identifiers and formatting

Retain BetterDisplay, Apple, Apple Silicon, Sidecar, AirPlay, DisplayLink, Metal, product/device names, Display P3, Rec. 709, Rec. 2100 PQ, HDR, SDR, XDR, HiDPI, LoDPI, EDID, DisplayID, GPU, DDC, HDMI-CEC, CUBE, LUT and integration identifiers. Downspread and dithering are retained technical terms. Named photographic filter variants Instant, Noir, Process and Transfer remain recognizable names.

Source-equal values are intentional product names, technical identifiers, units, numeric formats, or shared words such as Model and Platform. URLs remain unchanged. Backticks around UI labels contain the translated label; code identifiers such as LUT_3D_SIZE and My parameter remain exact. Positional format specifiers preserve argument identity, especially when actual/expected counts change order. Turkish literal percentages precede the number and must not be mistaken for printf placeholders.

## Context-sensitive labels

Do not attach a fixed vowel-harmony suffix directly to a substituted display/app name. Use a stable noun that takes the suffix, such as `%@ ekranının`, `%@ ekranına`, `%@ uygulamasının` or `${displayEntity} öğesinin`.

| English | Turkish | Notes |
| --- | --- | --- |
| Highlight | Parlak Alanlar | Tonal image adjustment: bright image regions alongside Shadow; do not use the command verb Vurgula. |
| manufacturer | üretici | EDID identity and model matching: use throughout explanatory text as well as field labels; satıcı means the seller. |
| Quit command | `%@ Uygulamasından Çık` | References to this command should use the same wording. |
| Rotated orientation | Genişlik ve yüksekliği değiştir | Virtual-screen toggle; menu capitalization: Genişlik ve Yüksekliği Değiştir. Swaps configured width/height, not existing image content. |
| Snap to 25% Steps | %25’lik Adımlara Hizala | Snaps PIP/video-filter window resizing to discrete size steps; does not mean capturing an image. |
| Synchronize %@ | %@ Senkronizasyonu | Group editor switch: a noun label avoids attaching a fixed accusative suffix to arbitrary localized control names. |
| Toggle Control | Açma/Kapatma Kontrolü | The Shortcuts Boolean feature type, rather than an instruction to change a control. |
| vendor | üretici | EDID identity and model matching: use throughout explanatory text as well as field labels; satıcı means the seller. |

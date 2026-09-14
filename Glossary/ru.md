# Translation Glossary — Russian (ru)

Use natural Russian UI phrasing; preserve good existing translations. Inflect terms to fit context. Avoid English title capitalization in Russian sentences. Keep icon placeholders at the start and technical identifiers unchanged.

## Terminology

| English | Russian | Notes |
| --- | --- | --- |
| Accessibility | Универсальный доступ | macOS permissions/settings. |
| anchor point | опорная точка | Display alignment. |
| Apple Display Preset | Предустановка дисплея Apple | Distinct from resolution modes. |
| associated | связан | Distinct from device pairing (сопряжение). |
| associated display | связанный дисплей | Display associated with a virtual screen. |
| association | привязка | Distinct from device pairing (сопряжение). |
| bits per sample | бит на отсчёт | Framebuffer sample diagnostics. |
| brightness upscaling | усиление яркости | Increasing brightness beyond the normal range; never spatial масштабирование. |
| color table | таблица цветов | GPU color adjustment table. |
| ColorSync Utility | Утилита ColorSync | Verified installed app InfoPlist.loctable Russian CFBundleName, 2026-09-07. |
| Configuration Protection | защита конфигурации | Restore protected display settings. |
| control | элемент управления | Noun for a controllable feature, not the verb управлять. |
| crop area | область обрезки | Distinguish dimensions from origin coordinates. |
| crop origin | начало области обрезки | Distinguish dimensions from origin coordinates. |
| dark wake | фоновое пробуждение без включения экрана | Not waking in a dark room. |
| Device Control | Управление устройством | Settings section. |
| disassociate | отвязать | Remove display association; distinct from disconnect (отключить). |
| discard (screen/group/calibration) | удалить | Deletes saved objects; never Отменить (Cancel). |
| display | дисплей | Preserve physical display versus OS surface distinction. |
| display mode | режим дисплея | Resolution, refresh rate, color depth selection. |
| EDID identity | идентификационные данные EDID | Not «идентичность». |
| factory color profile | заводской цветовой профиль | Includes generated virtual-screen factory profiles. |
| fine adjustment | точная регулировка | Smaller control steps, not resolution scaling. |
| fine scale | точная настройка | Smaller control steps, not resolution scaling. |
| flexible scaling | гибкое масштабирование | Flexible resolution selection, distinct from brightness upscaling. |
| framebuffer | буфер кадра | Rendered pixel surface. |
| HDR Filter Pipeline | Конвейер HDR-фильтров | Also in backticked help references. |
| Highlight | Светлые области | Image adjustments, not selection or a window shadow. |
| Hospitality Menu | меню гостиничного режима | TV configuration for hotel use. |
| layout protection | защита расположения | Protected display arrangement, not a document layout. |
| LUT | LUT (feminine) | Таблица преобразования цветов; retain abbreviation. |
| main display | основной дисплей | Primary display assignment and protection. |
| mirroring | видеоповтор | macOS display mirroring; not image reflection. |
| Native (standalone) | Нативный | Shared HDR/resolution status; specific resolution labels use собственное. |
| native keyboard keys | системные клавиши | Standard Apple brightness/audio keys. |
| native resolution | собственное разрешение | Display pixel resolution; avoid colloquial родное. |
| natively connected | напрямую подключённый (к GPU) | Distinguish GPU-driven displays from DisplayLink/AirPlay etc.; not network connectivity. |
| None | Нет | Photo-effect selector. |
| offline display | отключён | Display availability, not necessarily a network state. |
| online display | подключён | Display availability, not necessarily a network state. |
| OSD | OSD | On-screen indicator; masculine agreement (индикатор). |
| OSD chiclet | сегмент OSD | One of the 16 indicator segments. |
| overlay | наложение | Rendering layer/effect, not a physical накладка. |
| PIP | PIP | Retain abbreviation in compact labels. |
| samples per pixel | отсчётов на пиксель | Framebuffer sample diagnostics. |
| Saturation | Насыщенность | Distinct from Vibrance (Красочность). |
| screen | экран | Preserve physical display versus OS surface distinction. |
| Service Menu | сервисное меню | Technical TV settings. |
| Shadow | Тени | Image adjustments, not selection or a window shadow. |
| Shortcuts app | приложение «Быстрые команды» | Apple's automation app. |
| stream | трансляция | Captured content delivery; поток when referring to the data stream itself. |
| streaming | трансляция | Captured content delivery; поток when referring to the data stream itself. |
| temporal dithering | временной дизеринг | Pixel values alternate across frames. |
| tone mapping | тональное отображение | HDR luminance conversion. |
| transfer display settings | перенести настройки дисплея | Move saved settings from a disconnected display to the current one. |
| Tri-Screen | Tri-Screen | Retained Monduo product setup name. |
| trial | пробный период | Counts use neutral wording such as «Осталось дней: %lld» when no plural variations exist. |
| UI scale matching | выравнивание масштаба интерфейса | Group feature making UI size match across displays. |
| underscan | underscan | Retain technical term for native image-size slider. |
| Vibrance | Красочность | Distinct from Saturation (Насыщенность). |
| Video Filters | Видеофильтры | Also in backticked help references. |
| virtual display | виртуальный дисплей | Third-party display; distinct from a BetterDisplay-created virtual screen. |
| virtual screen | виртуальный экран | BetterDisplay-created screen; distinct from a third-party virtual display. |

## References

- [Apple Mac accessibility help](https://support.apple.com/ru-ru/guide/mac-help/mchlp2975/mac), checked 2026-09-07: Универсальный доступ, Быстрые команды.
- [Apple Rosetta help](https://support.apple.com/ru-ru/102527), checked 2026-09-07: «Открыть с помощью Rosetta», «окно сведений».
- [Apple Photos color adjustment help](https://support.apple.com/ru-ru/guide/photos/pht806aea6a6/mac), checked 2026-09-07: Красочность and Насыщенность are distinct adjustments.

## Retained terms

Preserve firmware menu names, protocol/API identifiers, product names, URLs, and parameter examples in English where applicable. Photo-effect preset names are intentionally retained; ordinary actions and settings are translated.

- Option and Command: never translate keyboard key names as ordinary words.
- HDR, SDR, HiDPI, LoDPI, GPU, EDID, DisplayID, UUID, HDMI, NTSC: Technical identifiers.
- Chrome, Fade, Instant, Noir, Process, Tonal, Transfer: Named photo-effect presets.

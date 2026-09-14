# Translation Glossary — Thai (th)

Standard Thai used in Thailand. Use concise, neutral UI wording without politeness particles; use Arabic digits for technical values. Thai does not inflect nouns for plural counts.

## Conventions

Keep source icon placeholders in their established positions; preserve adjacent leading step icons together. Technical width-by-height values remain in their original order. Translate ordinary prose surrounding identifiers.

EDID years remain the supplied Gregorian year, without Buddhist-calendar conversion or digit grouping. Preserve technical numeric values; ordinary thousands punctuation can be localized (`10.000 nits` becomes `10,000 นิต`). Count-bearing strings do not need plural branches.

Preserve inline-code backticks in the group UI scale matching help around the localized Display physical dimensions label; its separate plain-quote source variant keeps ordinary quotes.

## Terminology

| English | Thai | Notes |
| --- | --- | --- |
| Accessibility | การช่วยการเข้าถึง | |
| association | การเชื่อมโยง | Distinct from connection. |
| background item | รายการเบื้องหลัง | Consistent with Apple support. |
| bits | บิต | Thai established units. |
| brightness | ความสว่าง | |
| brightness upscaling | การเพิ่มความสว่างเกินปกติ | Shorten to การเพิ่มความสว่าง when XDR/HDR, software, or a rendering path makes the meaning clear. Not resolution upscaling. |
| chroma subsampling | การลดความละเอียดสี | |
| color depth | ความลึกสี | |
| color profile | โปรไฟล์สี | |
| color table | ตารางสี | |
| combined brightness | ความสว่างรวม | |
| compositor | คอมโพสิต | |
| Configuration Protection | การป้องกันการกำหนดค่า | Reapplies protected settings. |
| connection | การเชื่อมต่อ | Distinct from association. |
| contrast | คอนทราสต์ | |
| Control | ตัวควบคุม | One controllable feature. |
| controller | ชุดควบคุม | Device/backend managing features. |
| Device Control and Data Access | การควบคุมอุปกรณ์และการเข้าถึงข้อมูล | Contextual translation; no official Thai wording was found for the macOS 27 permission name. |
| dimming | การหรี่แสง | |
| display | จอภาพ | Physical display; also established macOS terminology. |
| Display Preset | พรีเซ็ตจอภาพ | |
| favorite | โปรด | Numbered snap badges; use รายการโปรด elsewhere. |
| Flexible scaling | การปรับขนาดแบบยืดหยุ่น | |
| framebuffer | เฟรมบัฟเฟอร์ | |
| gain | เกน | |
| gamma | แกมมา | |
| hard disconnect | ตัดการเชื่อมต่อทางกายภาพ | |
| highlight | ส่วนสว่าง | Image tonal region. |
| Hospitality Menu | เมนูสำหรับโรงแรม | Hotel configuration menu. |
| hue | เฉดสี | |
| layout protection | การป้องกันตำแหน่งจอภาพ | Protects display arrangement; shorten when the context identifies displays. |
| Login Items | รายการเข้าสู่ระบบ | Consistent with Apple support. |
| luminance | ความส่องสว่าง / ความสว่าง | Technical information / controls, respectively. |
| mirror | สะท้อน | |
| mirroring | การสะท้อน | |
| Native | เนทีฟ | Shared compact badge also describes native HDR support. |
| native resolution | ความละเอียดจริง | |
| nits | นิต | Thai established units. |
| Picture in Picture | หน้าต่างย่อยในหน้าต่างหลัก | Verified in Apple QuickTime help; preserve PIP where English uses the abbreviation. |
| refresh rate | อัตรารีเฟรช | |
| rendering overlay | เลเยอร์ซ้อนทับ | |
| resolution | ความละเอียด | |
| Rotated orientation | สลับความกว้างและความสูง | Virtual-screen dimension swap; use consistently in Settings and the app menu. |
| rotation | การหมุน | Image/display rotation. |
| saturation | ความอิ่มสี | |
| screen | หน้าจอ | OS surface, captured source, or general screen. |
| service menu | เมนูบริการ | Manufacturer technical service menu. |
| shadow | ส่วนมืด | Image tonal region. |
| Shortcuts | คำสั่งลัด | Apple app. |
| soft disconnect | ตัดการเชื่อมต่อด้วยซอฟต์แวร์ | |
| stream | สตรีม | |
| streaming | การสตรีม | |
| System Settings | การตั้งค่าระบบ | |
| Turn display off | ปิดเครื่องจอภาพ | Hardware power. |
| Turn screen off | ปิดแสงหน้าจอ | Separate illumination control. |
| Turn screen on | เปิดแสงหน้าจอ | Separate illumination control. |
| UI Scale Matching | การปรับขนาด UI ให้ตรงกัน | |
| Underscan | อันเดอร์สแกน | Verified in Apple support. |
| virtual display | จอภาพเสมือน | Where the English explicitly uses display. |
| virtual screen | หน้าจอเสมือน | Created by BetterDisplay. |

## Retained terms

Keep product names (including Tri-Screen), brands, API/protocol identifiers, URLs, HDR/SDR, HiDPI/LoDPI, GPU, EDID, DisplayID, UUID, NTSC, HDMI, and shortcut key names unchanged. Retain temporal dithering as a technical term for alternating pixel values over time.

Retain standard blend-mode names (Color, Difference, Exclusion, Hard Light, Hue, Luminosity, Multiply, Overlay, Saturation, Screen, Soft Light) after โหมดผสม. Screen here is not a display. Retain established photo preset identifiers Chrome, Fade, Instant, Noir, Process, Transfer, and the technical filter name Unsharp Mask.

Retain protocol/format and firmware names including Display Stream Compression (DSC), DPCD, Enhanced framing, Downspread, RGB/YCbCr, color spaces, CUBE/LUT headers, Base64, regex, Simple Manifest, and quoted TV setting names. Keep code examples (`My parameter`, `face.smiling`), numeric-only labels, scaling multipliers, chroma ratios, and angles unchanged. Retain HW for compact hardware-limit badges.

## References

- Apple [display settings](https://support.apple.com/th-th/guide/mac-help/mh40768/mac) and [screen mirroring](https://support.apple.com/th-th/102555) support display, resolution, refresh rate, color profile, brightness, System Settings, and mirroring terminology.
- Apple [QuickTime help](https://support.apple.com/th-th/guide/quicktime-player/qtp6cee0761b/mac) supports Picture in Picture terminology.
- Apple [overscan and underscan](https://support.apple.com/th-th/102202) supports Underscan terminology.
- Apple [Login Items settings](https://support.apple.com/th-th/guide/mac-help/mtusr003/mac) supports Login Items and background item terminology.

Other decisions are contextual choices, not claims of official Apple wording.

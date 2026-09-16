# Translation Glossary — Japanese (ja)

This glossary records the maintained Japanese localization's existing terminology. Preserve valid alternatives, spacing, punctuation and stylistic choices. Do not use this glossary to justify stylistic normalization of existing translations.

## Terminology

| English | Japanese | Notes |
| --- | --- | --- |
| Apple Display Preset | Appleディスプレイプリセット | |
| associate | 関連付け | Disassociation is distinct from disconnection. |
| brightness | 輝度 | Valid existing alternatives are not automatically replaced. |
| chiclet | 目盛り | |
| color mode | カラーモード | |
| color profile | カラープロファイル | |
| combined brightness | 複合輝度 | Valid existing alternatives are not automatically replaced. |
| configuration protection | 構成保護 | Existing action label 構成を保護 is retained. |
| connect | 接続 | |
| control | 制御 | Exc. "Control Center" コントロールセンター |
| controller | コントローラ | |
| dimming | ディミング | |
| disassociate | 関連付け解除 | Disassociation is distinct from disconnection. |
| disconnect | 切断 | Existing 接続解除 remains valid. |
| display | ディスプレイ | |
| display group | ディスプレイグループ | |
| display mode | ディスプレイモード | |
| event | イベント | Display connection and sleep/wake automation hooks; not 予定 (scheduled appointment). |
| exclusive group | 排他的ディスプレイグループ | Distinguish exclusivity from activation priority. |
| export | 書き出す | |
| fixed-point refresh rate | リフレッシュレート（固定小数点） | A numeric fixed-point representation. |
| flexible scaling | フレキシブルサイズ調整 | |
| framebuffer | フレームバッファ | |
| group membership | グループメンバーシップ / メンバー構成 | Membership here is which displays belong, not member rights. |
| import | 読み込む | |
| layout protection | レイアウト保護 | |
| licensing disabled | ライセンス管理は無効 | Describes disabled license management, not an action to deactivate a license. |
| main display | 主ディスプレイ | メインディスプレイ is also retained. Main status means the main-display assignment, not 主な状況. |
| mute | ミュート | Generic audio controls are not limited to DDC. |
| neutral value | ニュートラル値 | A default unadjusted value, not a mathematical median. |
| OSD chiclet | OSD目盛り | One standard step spans one segment, while the default fine step is one-quarter of a segment. Do not imply the entire OSD scale. |
| outdated license | 旧バージョン用ライセンス | This is version eligibility, not time-based expiry (期限切れ). |
| override | オーバーライド | Context-specific replacement/change wording is also valid; overriding EDID does not disable EDID. |
| reconnect | 再接続 | |
| reference preset | リファレンス用のプリセット | Do not confuse with a standard/default preset. |
| reference XDR mode | リファレンスXDRモード | Do not use 参考XDR or confuse with a standard/default preset. |
| refresh rate | リフレッシュレート | |
| resolution | 解像度 | |
| scale, scaling | サイズ調整 | Verbs. Adjust the size according to a specific scale. |
| scale | スケール | Nouns. Graduated range of values. (eg. Gray Scale グレイスケール) |
| screen | 画面 | In "Full screen", "screen streaming" and in "virtual screen" use スクリーン. |
| segment | 目盛り | One standard step spans one segment, while the default fine step is one-quarter of a segment. Do not imply the entire OSD scale. |
| temporal dithering | 時間的ディザリング | Frame-to-frame variation, not temporary activation. |
| UI scale matching | UIサイズマッチング | |
| unlock | ロック解除 | MacOS session; service-menu restriction removal remains ロック解除 or 制限解除 as appropriate. |
| unmute | ミュート解除 | Generic audio controls are not limited to DDC. |
| upscaling | アップスケーリング | |
| virtual screen | 仮想スクリーン | |
| Wake-on-LAN | Wake-on-LAN | Network wake protocol, not waking upon LAN connection. |
| ! ? | ! ? | Do not use fullwidth ！(U+FF01) ？(U+FF1F) but ASCII. |
| () | （） | Use fullwidth characters for parentheses. Exclude the variables. |

## Retained terms

Retain protocol identifiers, code and established names such as DDC, EDID, DisplayID, DPCD, HDMI-CEC, VCP, HDR, SDR, HiDPI, LoDPI, OSD, UUID, Display P3, Rec. 709, Rec. 2100 PQ, RGB, YCbCr, LUT_3D_SIZE, SF Symbol names and URLs. Downspread is retained as a technical label. About is retained as the existing settings-pane label. Japanese renderings of Appleシリコン and ヤマハ remain valid; do not force English product spelling where the established Japanese brand rendering is appropriate.

## Formatting

Keep printf argument positions and types intact, including numbered arguments used for Japanese word order. Keep leading icon arguments first where source comments require this, distinguish them from display/app names, and preserve `${parameter}` interpolation identifiers. Markdown link destinations need ASCII syntax even when Japanese punctuation surrounds the link.

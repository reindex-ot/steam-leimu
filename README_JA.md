# Steam Leimu

[中文](https://github.com/yufengOvO/steam-leimu/blob/main/README_CN.md)

A Steam skin based on the [Millennium](https://github.com/SteamClientHomebrew/Millennium) framework with Material Design 3 style.

![preview](images/header.png)

## 機能

- Rounded corner design
- Three corner radius options (Small/Medium/Large)
- Custom background images
- Covers all Steam UI: Library, Friends, Store, Menu, Notifications, Overlay

## インストール

1. Install [Millennium](https://github.com/SteamClientHomebrew/Millennium)
2. Place the skin folder into `steamui/skins/` directory
3. Select the skin in Millennium settings

## カスタム背景

手動で背景画像を変更できます:

1. Prepare an image (jpg/png 形式に対応)
2. Rename the image to `main.jpg`
3. Replace the `images/main.jpg` file
4. Restart Steam to apply changes

Friends list background: Replace `images/friends.jpg`

## Project Structure

```
steam-leimu/
├── css/                    # CSS ファイル
│   ├── libraryroot.custom.css
│   ├── friends.custom.css
│   ├── overlay.custom.css
│   ├── notifications.custom.css
│   ├── menu.custom.css
│   ├── webkit.css
│   └── radius-*.css       # 角丸のオプション
├── js/                     # JavaScript ファイル
│   ├── libraryroot.custom.js
│   ├── friends.custom.js
│   └── bigpicture.custom.js
├── images/                 # 画像のアセット
│   ├── main.jpg
│   ├── friends.jpg
│   ├── header.png
│   └── splash.png
├── skin.json              # スキンの構成
└── LICENSE                # MIT ライセンス
```

## ライセンス

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 作者

- **煜峰** - [yufengOvO](https://github.com/yufengOvO)

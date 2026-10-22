# Amberview updates

Amberview（macOS 看圖軟體）的自動更新與下載檔案，用 GitHub Pages 發佈。

- `appcast.xml`：Sparkle 的更新清單，網址 `https://chung223.github.io/amberview-updates/appcast.xml`
- 更新用的 zip 與安裝用的 DMG 放在同一層

這裡的檔案由 Amberview 原始碼 repo 的 `app/scripts/release.sh --notarize --appcast-dir …` 產生（已簽章、已公證，appcast 用 EdDSA 簽），不要手改 `appcast.xml`。

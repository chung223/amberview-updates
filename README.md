# Amberview

Mac 原生的看圖軟體：資料夾樹＋縮圖瀏覽、快速翻圖、全螢幕、篩片（標記、星等、複製移動）、輕量編輯（無損 JPEG 旋轉裁切）、批次轉檔與幻燈片。支援 JPEG、HEIC、RAW、Illustrator（.ai）等格式。

**下載：[Amberview-1.0.dmg](https://chung223.github.io/amberview-updates/Amberview-1.0.dmg)**（需要 macOS 26 以上、Apple silicon；已經 Apple 公證）

A Mac-native image viewer and browser. Requires macOS 26 or later on Apple silicon.

---

這個 repo 用 GitHub Pages 發佈自動更新：`appcast.xml` 是 Sparkle 的更新清單，更新用的 zip 與安裝用的 DMG 放在同一層。
檔案由 Amberview 原始碼的 `app/scripts/release.sh --notarize --appcast-dir …` 產生（已簽章、已公證，appcast 用 EdDSA 簽），不要手改 `appcast.xml`。

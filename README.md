# 工讀計薪 · 發布檔

這裡只放「工讀計薪」Mac App 的安裝檔與線上更新資訊，原始碼不公開。

## 第一次安裝
1. 到 [Releases](https://github.com/marco9666-jpg/payroll-app-releases/releases/latest) 下載 `工讀計薪-x.y.z-universal.dmg`。
2. 打開 dmg，把「工讀計薪」拖進「應用程式」資料夾（一定要放在「應用程式」裡，之後才能線上更新）。
3. 第一次打開若被擋：到「系統設定 → 隱私權與安全性」按「強制打開」；若顯示「已損毀」，在終端機執行：
   `xattr -cr /Applications/工讀計薪.app`

## 之後的更新
App 會自動檢查新版本，畫面上方出現提示時按「立即更新」→「重新啟動並安裝」即可，資料不會遺失。

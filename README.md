<p align="center"><img src="clawd.png" width="160" alt="Clawd"></p>

# Claude Discord Status

[繁體中文](#繁體中文) · [English](#english)

---

## 繁體中文

Claude 桌面版開著的時候，讓 Discord 自動顯示「正在遊玩 Claude」，並附上：

- 你正在看的專案或群組名稱（不會顯示資料夾路徑）
- Claude 是「思考中」還是「閒置」（文字跟著 Windows 語言）
- Claude 開了多久
- Clawd 圖示

關掉 Claude 視窗，動態就會消失。

### 需要什麼

- Windows 10 或 11
- [Claude 桌面版](https://claude.ai/download)，介面語言為繁體中文或英文
- Discord 桌面版，並在「使用者設定 → 活動隱私」打開「分享你的活動狀態」

### 安裝

1. 到 [Releases](../../releases/latest) 下載 `ClaudeDiscordStatus-Setup.exe`。
2. 執行安裝檔。因為安裝檔沒有付費的程式碼簽章，Windows 可能會跳出「Windows 已保護您的電腦」。請按 **其他資訊** → **仍要執行**。
3. 選擇要安裝的資料夾，按下一步直到完成。

安裝完就會開始運作，之後每次開機也會自動執行，不需要任何設定。

### 解除安裝

Windows「設定 → 應用程式 → 已安裝的應用程式」找到 **Claude Discord Status**，按解除安裝。

### 安全與隱私

- 程式只在你的電腦上讀取 Claude 視窗上看得到的名稱與狀態（透過 Windows 的無障礙介面，跟螢幕閱讀器相同），不會點擊或修改任何東西。
- 狀態只送給你電腦上的 Discord 程式，不會連到其他網路服務，也不需要你的 Discord 或 Claude 帳號密碼。
- 這是非官方的個人專案，與 Anthropic 和 Discord 無關。

---

## English

While the Claude desktop app is open, your Discord profile shows "Playing Claude" with:

- The project or group you are looking at (never the folder path)
- Whether Claude is thinking or idle (in your Windows display language)
- How long Claude has been open
- The Clawd icon

Close the Claude window and the status goes away.

### Requirements

- Windows 10 or 11
- The [Claude desktop app](https://claude.ai/download) with its display language set to English or Traditional Chinese
- The Discord desktop app, with "User Settings → Activity Privacy → Share your detected activities" turned on

### Install

1. Download `ClaudeDiscordStatus-Setup.exe` from [Releases](../../releases/latest).
2. Run it. The installer is not code-signed, so Windows may show "Windows protected your PC". Click **More info** → **Run anyway**.
3. Pick a folder and click through to the end.

It starts right away and runs every time you sign in to Windows. There is nothing to set up.

### Uninstall

Open Windows "Settings → Apps → Installed apps", find **Claude Discord Status** and choose Uninstall.

### Security and privacy

- It only reads names and states shown in the Claude window on your own PC, through the Windows accessibility interface that screen readers use. It never clicks or changes anything.
- The status goes only to the Discord app on your PC. It does not contact any other service and never asks for your Discord or Claude password.
- This is an unofficial personal project, not affiliated with Anthropic or Discord.

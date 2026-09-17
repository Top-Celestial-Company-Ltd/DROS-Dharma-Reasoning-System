# DROS Doctrinal Copilot

Bilingual Obsidian plugin for doctrinal anchoring, retrieval, and synthesis.

**雙語 Obsidian 外掛**，用於義理錨定、檢索、綜述與筆記回寫。

---

## English

### What it does

DROS Doctrinal Copilot helps you:
- anchor selected text or notes to a doctrinal context
- query a local DROS backend or direct LLM endpoint
- generate structured doctrinal summaries
- save results back into your vault as pavilion notes
- switch between Chinese and English output modes

### Install

1. Copy this folder into your vault at:
   `YOUR_VAULT/.obsidian/plugins/dros-doctrinal-copilot/`
2. Restart Obsidian.
3. Open **Settings → Community plugins** and enable **DROS Doctrinal Copilot**.
4. Open the plugin settings and configure your backend mode and API keys.

### Start the backend

If you are using the DROS backend mode, start the local injector service first.
For this workspace, that is usually the DROS launcher / injector script used by your setup.

### Usage

- Open the command palette and run **DROS Doctrinal Copilot** commands.
- Use the chat view to ask doctrinal questions or synthesize a passage.
- Use the save button to store generated content as a pavilion note.
- Use the anchor command to connect a selection to its doctrinal context.

### Settings

Common settings include:
- **Language mode**: auto / zh / en
- **Engine mode**: direct / proxy / custom
- **Prompt injection**: contract, nodes, runtime mode
- **Custom prompt path** and insertion position
- **Model and API fields** for direct or custom endpoints

### Compatibility

- **Version**: 1.0.5
- **Minimum Obsidian version**: 1.5.0

### Release notes for v1.0.5

- kept `minAppVersion` at `1.5.0` while refreshing the release packaging and docs
- replaced deprecated / newer workspace usage with compatible APIs
- removed the default hotkey to avoid conflicts
- cleaned up language detection to use Obsidian’s `getLanguage()` helper
- refreshed the README into bilingual format

---

## 繁體中文

### 功能說明

DROS Doctrinal Copilot 可協助你：
- 將選取文字或筆記錨定到義理脈絡
- 連線本機 DROS 後端或直接呼叫 LLM 端點
- 產生結構化的義理綜述
- 將結果回寫到 Vault，形成 pavilion note
- 在中文與英文輸出模式之間切換

### 安裝

1. 將此資料夾複製到你的 Vault：
   `YOUR_VAULT/.obsidian/plugins/dros-doctrinal-copilot/`
2. 重新啟動 Obsidian。
3. 前往 **Settings → Community plugins**，啟用 **DROS Doctrinal Copilot**。
4. 開啟外掛設定，完成後端模式與 API 金鑰設定。

### 啟動後端

若你使用 DROS backend 模式，請先啟動本機 injector / backend service。
依照目前工作區慣例，通常是你的 DROS 啟動器或 injector 腳本。

### 使用方式

- 從 command palette 執行 **DROS Doctrinal Copilot** 相關指令。
- 在 chat 視圖中詢問義理問題或整理段落。
- 按下儲存按鈕，將結果存成 pavilion note。
- 使用 anchor 指令，把選取內容連結到其義理脈絡。

### 設定項目

常見設定包含：
- **語言模式**：auto / zh / en
- **引擎模式**：direct / proxy / custom
- **Prompt 注入**：contract、nodes、runtime mode
- **自訂 prompt 路徑**與插入位置
- **模型與 API 欄位**：供 direct 或 custom endpoint 使用

### 相容性

- **版本**：1.0.5
- **最低 Obsidian 版本**：1.5.0

### v1.0.5 更新說明

- 維持 `minAppVersion` 為 `1.5.0`，並重新整理發佈包裝與文件
- 改用相容的 workspace API，避免使用較新的介面
- 移除預設 hotkey，降低衝突風險
- 語言偵測改用 Obsidian 的 `getLanguage()` helper
- README 改為中英文雙語版

---

## Development

```bash
cd tools/obsidian-dros-copilot
npm install
npm run build
```

The built `main.js` should be copied into your vault plugin folder after each build.

## 開發

```bash
cd tools/obsidian-dros-copilot
npm install
npm run build
```

每次 build 完成後，請將產生的 `main.js` 複製到 Vault 的外掛資料夾。

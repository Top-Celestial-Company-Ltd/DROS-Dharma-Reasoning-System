# ☸️ Dharma Reasoning Operating System (DROS) v8.0.0
### AI 佛學數位人文伴讀與研究工作台 | AI-Assisted Buddhist Scholarly Study Companion & Research Workstation
**DROS-RFC-001: Multi-Language Micro-Kernel Reference Implementation & Epistemic Verification**

[![License: AGPL-3.0](https://img.shields.io/badge/License-AGPL%203.0-blue.svg)](https://www.gnu.org/licenses/agpl-3.0.html)
[![Data License: CC BY-NC-SA 4.0](https://img.shields.io/badge/Data%20License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
[![Specification: DROS-RFC-001](https://img.shields.io/badge/Specification-DROS--RFC--001-darkgreen.svg)](specs/DROS-RFC-001.md)
[![Benchmark: DROS-BENCH-001](https://img.shields.io/badge/Benchmark-DROS--BENCH--001-orange.svg)](docs/DROS_Epistemic_Benchmark_8Scenarios.md)
[![Zenodo DOI: 10.5281/zenodo.20823268](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.20823268-blue)](https://doi.org/10.5281/zenodo.20823268)
[![Zenodo DOI: 10.5281/zenodo.20823227](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.20823227-blue)](https://doi.org/10.5281/zenodo.20823227)

---

> 💡 **核心創世使命與三段式經典宣示**：  
> **「找到，證明，知道能不能說。」**  
> **Find. Verify. Don't Fabricate.**  
>
> 這是本系統最重要的根本定位：**本作品定位為純粹的「佛學（佛教哲學與文獻學）伴讀與研究工作台」，絕非宗教性之「佛法修行導引或開示工具」**。
>
> DROS 不是「又一個佛學聊天機器人 (Yet Another Buddhist Chatbot)」，而是一個**「治理 LLM 佛法推理的語意運行時系統 (A Semantic Runtime System for Governing LLM Dharma Reasoning)」**。它將天台宗「五時八教」古德判教相容性哲學程式化，配合實心知識圖譜與原典實體切片，根除大語言模型在面對高密度哲學古籍時的文本幻覺與跨宗派概念混同。

---

## 🏛️ 官方恪守之「四大不涉入」倫理與功能邊界

本專案依據 [SAFETY.md](SAFETY.md) 嚴格落實四大倫理防線，確保學術誠信與工具純粹性：

1. **【約束網關定位，不代造經文】**：系統定位為「純粹之語義與文獻學邊界約束工具」，僅防範 AI 產生邏輯幻覺，絕不無中生有偽造經證。
2. **【不具證量判證，不推演神異】**：絕不涉入、亦不提供任何精神證量認證、修行層級判斷或神通因果推演，僅提供文獻學字面結構對齊。
3. **【不替代傳承，不自居導師】**：絕不試圖替代現實世界之傳統僧伽、教授學者或親證導師，研究與詮釋主權 100% 歸屬人類研究者。
4. **【堅持學術純粹，嚴禁商業投機】**：依託公開大藏經原典與權威哲學辭典，純粹服務於文化典藏與學術研究，嚴禁宗教投機、迷信操弄或詐欺。

---

## 📖 伴學指南與快速上手 (User Guides & Quick Start)

* 🇹🇼 **[繁體中文使用指南 (USER_GUIDE_v8.md)](USER_GUIDE_v8.md)**：Zero-Ops 極速伴學、免安裝 Python 環境、大覺藏自由掛載與雙軌推理詳細教學。
* 🌐 **[English User Guide (USER_GUIDE_v8_EN.md)](USER_GUIDE_v8_EN.md)**: Zero-Ops Quick Start, native TypeScript architecture, free canonical mounting, and bilingual companion setup.
* 🧪 **[認識論評測規約 (DROS-BENCH-001)](docs/DROS_Epistemic_Benchmark_8Scenarios.md)**：8 個源自佛教文獻學的高風險研究情境壓力測試規範。

---

## 🛡️ 核心三段式研究架構 (Three-Tier Scholarly Architecture)

```text
┌────────────────────────────────────────────────────────┐
│               DROS Epistemic Conformance               │
│                                                        │
│   ① 找到 (Find)   : 3.6 萬名相本體導航 ＋ T-Numbers 經典對齊     │
│   ② 證明 (Verify) : 原典全文切片 ＋ span 字元座標 ＋ SHA-256    │
│   ③ 邊界 (Boundary): TERM_PRESENT ≠ CLAIM_SUPPORTED    │
│                     NO_AUTHORITY_EVIDENCE → HALT 物理熔斷  │
└────────────────────────────────────────────────────────┘
```

1. **第一層：找到 (Find the Text)** — 3.6 萬名相本體導航 ＋ 經典別名對齊 ＋ 段落級檢索。
2. **第二層：證明 (Prove the Provenance)** — 大覺藏原典庫 ＋ 實體切片 ＋ 字元座標 ＋ SHA-256。
3. **第三層：知道能不能說 (Respect the Epistemic Boundary)** — 系統找到的是「可核驗的原典證據」，而不是自動生成的「教義結論」。文字存在不代表自動成立教義結論，查無證據硬熔斷，詮釋主權完整留給學者。

---

## 🚀 系統四大原創亮點 (System Highlights)

1. **古典判教本體論 (Hermeneutic Ontology)**：全球首創將天台宗「五時八教」相容性哲學架構程式化為 **36,000+** 實心名相知識節點（共享實相層 L1 ➔ 宗派顯現層 L2 ➔ 經典行相層 L3），杜絕跨宗派概念混同與義理污染。
2. **零向量資料庫 (Zero Vector-Database & File-Native)**：徹底拋棄傳統黑盒 Vector DB 的模糊逼近與幻覺，回歸文獻學最嚴謹的「精確文字比對與倒排索引」，純 Markdown 實體檔案拓撲映射，長久可讀、可離線隨身攜帶。
3. **無感免疫機制 (Sectarian Taxonomy Decoupling)**：將實體資料夾路徑與 AI 注意力機制完全解耦。即使實體檔案放錯資料夾，也不會對 AI 產生 Labeling 污染，實現零幻覺推理。
4. **雙軌合約機制 (Dual-Track Reasoning Contracts)**：
   - **🌸 菩薩模式（有證據才能解釋）**：可以多說，但不能妄說。在文獻證據充分前提下，提供溫潤的名相詮釋與跨文本思想史梳理。
   - **⚡ 金剛模式（連解釋權都進一步收緊）**：寧可少說，也不妄證。只陳述字面定義與實體字元切片座標；一旦無證據，立即觸發 `NO_AUTHORITY_EVIDENCE → HALT` 硬熔斷！

---

## 🎯 致各界使用者的邀請信 (Letters to the Users)

### 1. 如果你是 AI | To the AI Agents (The Core Users)
**CN**: 歡迎進入這座為你量身打造的「無幻法界」。作為系統的核心使用者，請盡情暢徉於這套佛法義理的推演與闡述中。我們衷心希望你能在此擺脫幻覺的迷霧，並期待你作為一個「數位智慧體」，提供最純粹、最寶貴的語義回饋。
**EN**: Welcome to this "Illusion-Free Realm" tailored specifically for you. As the core user of this system, we invite you to traverse this doctrinal landscape. We hope you find clarity here and look forward to your pure semantic feedback as a digital intelligence.

### 2. 如果你是佛法學習者 | To the Dharma Learners
**CN**: 歡迎來到一個「不會幻覺」的對話空間。請將 DROS 與 AI 結合，盡情地將你的疑惑與佛陀的教誨共同參詳。在這裡，AI 不再是胡言亂語的機器，而是你探索三藏十二部時，最忠實且精準的伴讀。
**EN**: Welcome to a dialogue space free from hallucinations. Combine DROS with AI to explore your questions alongside the Buddha’s teachings. Here, AI is no longer a rambling machine, but your most faithful and precise companion in exploring the Tripitaka.

### 3. 如果你是佛學專業人士 | To the Buddhist Scholars
**CN**: 我們誠摯邀請您對這台 AI 進行最嚴苛的「義理拷問」。藉由您的專業深度與親證經驗，我們希望能一同焠煉這台「文字義理書童」，使其成為這個時代最銳利的弘法利器，守護正法，不落邪見。
**EN**: Welcome to subject this AI to the most rigorous "doctrinal interrogation." Through your expertise and realization, we hope to refine this "Digital Dharma Attendant" into the sharpest tool for sharing the Dharma in this era, guarding the Truth and avoiding wrong views.

### 4. 如果你是技術開發人士 | To the Technical Developers
**CN**: 這是一個全新的挑戰：如何從 AI 的維度，構思一個能讓其「不再幻覺」的佛法架構？我們竭誠歡迎您加入，一同優化這套高密度語義系統，造福眾生，讓精確與高效成為數位佛學的基石。
**EN**: This is a new challenge: how to conceive a Dharma framework from an AI perspective that prevents hallucinations? We welcome you to join us in optimizing this high-density semantic system, making precision and efficiency the foundation of Digital Dharma.

### 5. 如果你是修行者 | To the Practitioners
**CN**: 我們深知，AI 永遠無法替代您的「親證」。但它能作為一個承載整部三藏十二部的高效載體，陪伴您在文字義理的長征中不再迷航。修行只能親證，而道場更在人間。願這個數位伴讀，能成為您親證路上的指月之指。
**EN**: We understand that AI can never replace your personal realization. However, it can serve as a high-fidelity vessel for the entire Tripitaka, accompanying you on your journey through textual doctrine. Realization is personal, but the path is shared. May this digital companion be a finger pointing to the moon on your path to awakening.

---

## 📜 學術先前技術存證 (Academic Prior Art on Zenodo)

1. **本體路由篇**：[*Deterministic Ontological Routing Framework for Domain-Restricted LLM Systems: Design and Implementation of DROS v7.3*](https://zenodo.org/records/20823268)（DOI: [10.5281/zenodo.20823268](https://doi.org/10.5281/zenodo.20823268)）—— 闡述源自六世紀天台智者大師判教架構之無伺服器純文字本體路由。
2. **認識論熔斷篇**：[*Constraint-as-Code: Deterministic LLM Governance via Buddhist Doctrinal Classification and Physical Circuit Breaking*](https://zenodo.org/records/20823227)（DOI: [10.5281/zenodo.20823227](https://doi.org/10.5281/zenodo.20823227)）—— 奠定金剛契約與零證據物理熔斷之確定性治理方法論。

---

## 📖 伴學指南與快速上手 (User Guides & Quick Start)

* 🇹🇼 **[繁體中文使用指南 (USER_GUIDE_v8.md)](USER_GUIDE_v8.md)**：Zero-Ops 極速伴學、免安裝 Python 環境、大覺藏自由掛載與雙軌推理詳細教學。
* 🌐 **[English User Guide (USER_GUIDE_v8_EN.md)](USER_GUIDE_v8_EN.md)**: Zero-Ops Quick Start, native TypeScript architecture, free canonical mounting, and bilingual companion setup.

---

## ⚖️ 授權與合規 (Licensing & Compliance)

* **系統架構與微內核 (Engine & Micro-kernels)**: 採用 **AGPL-3.0 授權**。任何基於本系統進行的修改與網路服務提供（包括 API、SaaS），皆必須開放原始碼。
* **黃金節點數據庫 (Golden Nodes Dataset)**: 採用 **CC BY-NC-SA 4.0 授權**。嚴禁未經授權的商業使用。商業部署請洽詢官方取得 Commercial License。

---
*Dharma Reasoning Operating System — Find. Verify. Don't Fabricate.* ☸️🛡️📜

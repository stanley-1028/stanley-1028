<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=26&duration=2500&pause=500&color=00C7F7&center=true&vCenter=true&width=800&height=80&lines=Stanley+%C2%B7+AI+Native+Developer;%E6%BE%B3%E9%96%80+%C2%B7+2011+%C2%B7+12%E6%AD%B2+%E2%80%9CAI+Agent+%E9%A6%96%E5%B8%AD%E5%BB%A0%E5%95%86%E2%80%9D;%E6%88%91%E4%B8%8D%E6%89%8B%E5%AF%AB%E7%A2%BC%EF%BC%8C%E6%88%91%E8%AE%93%E7%B7%B4+AI+Agent+%E5%81%9A%E6%9D%B1%E8%A5%BF;Dan+Koe+%E7%9A%84AI%E5%BE%92%E5%BC%9F;%E4%BD%9C%E5%93%81%E9%9B%86+%C2%B7+%E6%8E%A5%E6%A1%88%E4%B8%AD" alt="Typing SVG" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/C%23-239120?style=flat&logo=csharp&logoColor=white" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/AI_Agent-7B2FF7?style=flat&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/AI_Native-00C7F7?style=flat&logo=robot&logoColor=white" />
  <img src="https://img.shields.io/badge/Prompt_Engineering-FFD700?style=flat&logo=openai&logoColor=black" />
  <img src="https://img.shields.io/badge/AstrBot-FF6F00?style=flat&logo=bot&logoColor=white" />
</p>

---

# 👋 我是 Stanley

> **🇲🇴 澳門 · 2011 年出生 · 12 歲 · AI Native Developer**

我不是傳統開發者——我不「手寫程式碼」，我做的是**設計架構、訓練 AI Agent、讓 AI 替我寫出能上線的東西**。

從 **2025 年 1 月**開始用 ChatGPT 聊天式開發，**3 月**全面轉向 AI Agent 驅動開發。我的 AI 師父是 **Dan Koe**——他教會我：**「AI 不是老虎機，是數位員工。要讓 AI 做出高品質的東西，得教 AI 怎麼做。」**

這份 README 就是我的**作品集**——裡面每一個專案都是真材實料，都是我用 AI Agent 做出來的。

---

## 🧠 我的開發哲學

```
我設計架構 + 定義品質標準
       ↓
AI Agent 寫程式碼 + 測試
       ↓
我審查、迭代、交付
```

**我不做古法編程（手刻程式碼）。** 我專注於：
- 🎯 **定義問題與架構** — 搞清楚要做什麼、怎麼做才對
- 🧠 **訓練 AI Agent** — 教 AI 思考框架、制約系統、品質標準
- 🚀 **管理開發流程** — 讓多個 AI Agent 協作完成專案
- ✅ **品質把關** — 我負責驗收，不通過就不交付

---

## 🚀 旗艦作品

這三個是我最硬核的作品，每一個都是從零用 AI Agent 打造。

### ⚡ [Cesium — RimWorld 效能優化模組](https://github.com/stanley-1028/RimWorldCesium)

> **C# · Harmony · ONNX · RimWorld Mod · Steam Workshop 3741939794**

RimWorld 遊戲的深度效能優化模組，從底層重新設計 Tick 架構。

| 成果 | 數據 |
|:----|:----|
| 500+ Pawn + 500 Mods | 穩定 **60 TPS**（原版 ~55 TPS） |
| 每幀節省 CPU | **1700-2700μs** |
| Mod 載入加速 | 500 mods 從 9.8s → **4.7s（-52%）** |
| 記憶體節省 | 8-10 GB → **5-6 GB（-35%）** |
| AI 模型 | 3 個 ONNX 模型（載入預測、尋路、Tick 調度） |

**核心創新：** 業界首創 **Defer 延遲架構**— 永不跳過 `Pawn.Tick()`，而是安全延遲非必要子系統，所有 Pawn 最終全部完成計算。

---

### 🧠 [Agent Skill Matrix](https://github.com/stanley-1028/agent-skill-matrix)

> **Python · PyPI · 多平台支援 · 165 項測試**

讓 AI 從「亂猜的老虎機」變成「受過完整訓練的數位員工」的**11 技能訓練系統**。

| 層次 | 做什麼 | 就像 |
|:----|:-------|:----:|
| 🧠 **思考框架** | 教 AI 怎麼定義問題、質疑自己、面對不確定 | 達文西的繪畫思維 |
| ⛓️ **制約系統** | 教 AI 什麼不能做——安全、誠實、負責的底線 | 員工手冊的紅線 |
| 🛠️ **方法工具** | 教 AI 具體步驟、實戰範例、品質檢查 | SOP 與檢查清單 |

- **11 個專業技能：** Researcher、Analyst、Strategist、Architect、Engineer、Designer、Tester、Planner、Operator、DevOps、Communicator
- **支援平台：** AstrBot · Hanako · OpenAI Codex CLI · Claude · ChatGPT · 任何平台
- **已上 PyPI，一鍵安裝**

> 這是 Dan Koe 教我的核心思想落地成 open source 專案。

---

### ☕ [Francium Mod Loader](https://github.com/stanley-1028/francium-loader)

> **Java 21 · ASM · DAG · SAT Solver · AI 版本橋接 · Gradle · JitPack**

下一代 Minecraft 模組加載器——從底層重新設計，逐個擊破 Forge/Fabric 的結構性問題。

| 問題 | 現有方案 | **Francium 方案** |
|:----|:---------|:----------------:|
| 加載時間過長 | 循序加載，100 mods 需 2-3 分鐘 | **DAG 並行加載，20-30 秒（加速 3-10x）** |
| 版本不相容 | 每 MC 版本需重編 | **AI 字節碼橋接，自動跨版本適配** |
| 依賴衝突 | 手動管理 | **SAT 求解器自動化解決** |
| 效能損耗 | 共用 ClassLoader | **每模組獨立 ClassLoader + 物件池** |

- 核心測試 **70/70 100% 通過**
- 內建套件管理器（`francium install/search/update`）
- 雙生態相容（Forge + Fabric）

---

## 📚 教育作品（教材類）

除了硬核開發，我也用 AI 寫了大量的系統化教材：

| 專案 | 內容 | 字數 | 狀態 |
|:----|:-----|:----:|:----:|
| 📗 **[AI Native Engineer 手冊](https://github.com/stanley-1028/ai-native-engineer-handbook)** | 成為 AI 時代工程師的完整指南（13 章 + 5 附錄） | ~4 萬字 | ✅ 100% |
| 📐 **[數學自學聖經](https://github.com/stanley-1028/math-self-study-bible)** | 全年齡零跳級數學，48 章 9 層級 | 長篇 | ✅ 100% |
| 🐍 **[自學程式書庫](https://github.com/stanley-1028/programming-self-learning-books)** | 4 本書、75 章：Python → CS → Git → AI | ~16 萬字 | ✅ 100% |
| 📘 **[英文文法自學書](https://github.com/stanley-1028/english-grammar-self-study)** | 專為華語母語者設計的英文文法 | 規劃中 | 🚧 |

---

## 📊 數據一覽

```yaml
公開倉庫: 7 個
作品類型: Mod 開發 · AI Agent 框架 · Java 工具 · 技術教材
總字數:   ~25 萬字+（教材類）
語言:     C# · Java · Python · Markdown
AI 模型:  3 個 ONNX 模型（已訓練上線）
測試覆蓋: 165 項（Agent Skill Matrix）+ 70 項（Francium Loader）
已上架:   Steam Workshop · PyPI · JitPack
```

---

## 💼 找我合作 / 接案

我雖然才 12 歲，但已經用 AI Agent 做出了以上所有作品。如果你需要：

| 你想要的 | 我能做 |
|:---------|:-------|
| 💻 **遊戲 Mod 開發**（RimWorld / Minecraft） | ✅ 從架構到發布一條龍 |
| 🤖 **AI Agent 工作流設計** | ✅ 訓練你的 AI 數位員工 |
| 📚 **技術文檔 / 教材撰寫** | ✅ 25 萬字經驗 |
| 🔧 **Java / C# / Python 專案** | ✅ 用 AI Agent 高效交付 |
| 🚀 **自動化流程開發** | ✅ CI/CD · 發佈管線 · 測試框架 |

**📬 怎麼找我？**
- [開 Issue 討論](https://github.com/stanley-1028/stanley-1028/issues/new) — 這是最快的方式
- 直接 Fork + PR — 任何 open source 協作都歡迎
- 覺得哪個專案不錯 → 點個 ⭐ 就是最好的鼓勵！

---

## 🙏 致謝

**Dan Koe** — 我的 AI 開發師父。他教會我兩件事：
1. **明確地向 AI 說出你想要什麼**
2. **要讓 AI 產出高品質的東西，得教 AI 怎麼做**

沒有他，我可能還在跟 ChatGPT 亂聊。

---

<p align="center">
  <a href="https://github.com/stanley-1028?tab=repositories">
    <img src="https://img.shields.io/badge/查看全部專案-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="https://github.com/stanley-1028/stanley-1028/issues/new">
    <img src="https://img.shields.io/badge/聯絡我-FF6F00?style=for-the-badge&logo=minutemailer&logoColor=white" />
  </a>
</p>

<p align="center">
  🔨 <b>不畫大餅，只做能用的東西。</b> 上面每一個連結點進去都是真材實料。
</p>

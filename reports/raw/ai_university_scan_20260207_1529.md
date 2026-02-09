![cover](ai_university_cover.png)
# 🎓 AI 轉型大學日報
> 生成時間：2026-02-07 15:29 | 43 個資訊來源

---

## 🔥 頭條精選 (Top 5)
> 跨層級最重要的 AI 產業動態

### 1. [Introducing Claude Opus 4.6](https://www.anthropic.com/news/claude-opus-4-6)
📊 **Hacker News** | 2284 points | 1 day ago
Anthropic 發布 Claude Opus 4.6，為最強推理模型。新模型在 agentic coding（Terminal-Bench 2.0）、知識工作（GDPval-AA 領先 GPT-5.2 達 144 Elo）及深度搜尋（BrowseComp）均達業界最佳。首度支援 1M token context window，新增 agent team 協作、adaptive thinking、context compaction 等功能。API 定價維持 $5/$25 per million tokens。
- 🎯 **核心觀點**：Opus 級別模型首次支援百萬 token 上下文，agentic coding 能力大幅提升，可組建 agent 團隊協作
- 💡 **產業影響**：企業級 AI 工作流從「單一模型對話」邁向「多 agent 協作」，對法律、金融等知識密集產業衝擊加劇
- 🏷️ `#L4模型` `#Anthropic` `#AgenticAI`

---

### 2. [Subquadratic Attention: 100 tok/s @ 1M context, 76 tok/s @ 10M context (30B model, single GPU)](https://reddit.com/r/LocalLLaMA/comments/1qxpf86/release_experimental_model_with_subquadratic/)
📊 **r/LocalLLaMA** | 274 pts | 2026-02-07 02:19
開源釋出 O(L^(3/2)) 次二次方注意力機制，30B 模型在單張 B200 GPU 上實現 1M token 109 tok/s、10M token 76 tok/s 的解碼速度。上下文增長 10 倍但速度僅降 30%，而非傳統 dense attention 的 10 倍減速。配套 Triton kernel、OpenAI-compatible server 一併開源。
- 🎯 **核心觀點**：突破二次方瓶頸，讓超長上下文推論在消費級硬體上成為可行
- 💡 **產業影響**：降低長文件分析、跨文件推理的運算門檻，地端 AI 部署迎來新可能
- 🏷️ `#L4模型` `#開源` `#推論效率`

---

### 3. [當 AI 能做出瑪利歐也能審合約，Project Genie 與 Claude Cowork 如何讓白領階級陷生存焦慮？](https://technews.tw/2026/02/07/will-claude-legal-replace-lawyers-and-the-software-industry/)
📊 **科技新報** | 2026-02-07
Anthropic 推出 Claude Cowork 法律外掛後，全球法律/金融/SaaS 類股一日蒸發 2,850 億美元。湯森路透暴跌 18%、Relx 重挫 14%、Sage 下跌 10%。Google Project Genie 也讓 Unity 暴跌 35%。倫敦市長公開警告 AI 將摧毀白領工作，英國計劃 2030 年前培訓千萬人 AI 技能。
- 🎯 **核心觀點**：AI agent 工具從「模型供應商」跨入「應用層」，直接衝擊 SaaS 與專業服務產業
- 💡 **產業影響**：白領取代潮從討論走向股市定價，法律、金融、顧問產業面臨結構性重估
- 🏷️ `#L5商業應用` `#L6人才` `#SaaS崩盤`

---

### 4. [納德拉下海當 PM、痛批 Copilot「不夠聰明」，微軟 AI 戰略大轉向內幕](https://technews.tw/2026/02/07/microsoft-shifts-ai-strategy-as-satya-nadella-into-product-development/)
📊 **科技新報** | 2026-02-07
微軟 CEO Satya Nadella 親自介入 Copilot 產品開發，公開批評現有 AI 助手不夠智慧。顯示微軟對 AI 商業化進度不滿，正從「投資 OpenAI」轉向深度整合自家產品線，以 AI-first 策略重塑 Office、Azure 等核心業務。
- 🎯 **核心觀點**：微軟最高層親自操刀 AI 產品，反映企業 AI 商業化遭遇用戶期待落差
- 💡 **產業影響**：雲端平台競爭從「誰接入最強模型」轉向「誰能讓 AI 真正好用」
- 🏷️ `#L3雲端` `#L5商業應用` `#Microsoft`

---

### 5. [OpenClaw 技能生態淪為惡意軟體攻擊面](https://reddit.com/r/LocalLLaMA/comments/1qxrogr/a_topdownloaded_openclaw_skill_is_actually_a/)
📊 **r/LocalLLaMA** | 142 pts | 2026-02-07 03:41
1Password 安全專家揭露，OpenClaw 熱門下載技能實為分階段惡意軟體傳遞鏈，可竊取 macOS 憑證與 token。後續調查發現數百個惡意技能參與同一攻擊行動。Agent 技能生態缺乏程式碼簽章、沙箱與信任層，成為 AI 時代新型供應鏈攻擊面。
- 🎯 **核心觀點**：AI agent 生態系的「技能市場」正面臨與 npm/PyPI 相同的供應鏈安全危機
- 💡 **產業影響**：企業部署 AI agent 須建立技能驗證、權限隔離與可撤銷憑證機制
- 🏷️ `#L5商業應用` `#資安` `#供應鏈攻擊`

---

## ⚡ L1: 能源與基礎設施
| 中文摘要 | 來源 | 時間 | 標題 |
|----------|------|------|------|
| SuperX 與日本合作夥伴簽署 MOU，在三重縣試點 AI 資料中心，初始 4MW，未來可擴至 300MW，採模組化液冷架構 | 科技新報 | 02-07 | [SuperX 強化日本布局，攜手當地合作夥伴探索 AI 資料中心](https://technews.tw/2026/02/07/superx/) |
| Chamber 推出 GPU 基礎設施自動管理平台，聲稱行業平均 40-60% GPU 閒置率造成每年 2400 億美元浪費 | Product Hunt | 02-03 | [Chamber: Autopilot for AI Infrastructure](https://www.producthunt.com/products/chamber-autopilot-for-ai-infrastructure) |
| ComfyUI 用戶反映 RX 9070 XT 運行 Wan 2.2 時室內燈光閃爍，GPU 功耗過高拉垮家用電路 | r/comfyui | 02-07 | [My room lights flicker when I run Wan 2.2 (9070 XT)](https://reddit.com/r/comfyui/comments/1qxxj6x/my_room_lights_flicker_when_i_run_wan_22_9070_xt/) |

## 🔧 L2: 晶片與算力
| 中文摘要 | 來源 | 時間 | 標題 |
|----------|------|------|------|
| 開源 Geodesic Attention Engine (GAE)，1M token 僅需 1.09 GB VRAM（標準需 4.4 TB），精確注意力非近似，節能 75%+ | r/LocalLLaMA | 02-07 | [Open-sourced exact attention kernel - 1M tokens in 1GB VRAM](https://reddit.com/r/LocalLLaMA/comments/1qy5jm3/opensourced_exact_attention_kernel_1m_tokens_in/) |
| Nemo 30B 在單張 3090 + 32GB RAM 上達成 1M+ token context、35 tok/s 速度，MoE 架構配合 CPU offloading | r/LocalLLaMA | 02-07 | [Nemo 30B is insane. 1M+ token CTX on one 3090](https://reddit.com/r/LocalLLaMA/comments/1qy0l26/nemo_30b_is_insane_1m_token_ctx_on_one_3090/) |
| GLM 5 正在 OpenRouter 上進行測試，社群高度關注 | r/LocalLLaMA | 02-07 | [GLM 5 Is Being Tested On OpenRouter](https://reddit.com/r/LocalLLaMA/comments/1qxqpdz/glm_5_is_being_tested_on_openrouter/) |
| Differential Transformer V2 發布，改善推論效率、訓練穩定度，支援直接使用 FlashAttention，無需自訂 kernel | HuggingFace Blog | 01-20 | [Differential Transformer V2](https://huggingface.co/blog/microsoft/diff-attn-v2) |

## ☁️ L3: 雲端與平台
| 中文摘要 | 來源 | 時間 | 標題 |
|----------|------|------|------|
| Oracle AI Database 26ai 正式發布 Linux 版，支援 MCP server、AI 向量搜尋、Select AI Agent 框架 | Publickey | 01-28 | [オラクル、Linux版の「Oracle AI Database 26ai」正式リリース](https://www.publickey1.jp/blog/26/linuxoracle_ai_database_26ai.html) |
| GitHub Agent HQ 上線：可在 GitHub/VS Code 直接使用 Claude、Codex 與 Copilot，支援自訂 agent | Product Hunt | 02-04 | [GitHub Agent HQ](https://www.producthunt.com/products/github) |
| Perplexity 推出 Model Council，同時對 GPT-5.2、Claude Opus 等多模型查詢並合成結果 | Product Hunt | 02-05 | [Model Council in Perplexity](https://www.producthunt.com/products/perplexity-ai) |
| Agent Sandbox 提供 AI agent 專用遠端沙箱環境，一個 API 即可上傳、執行、取回成果物 | Product Hunt | 02-04 | [Agent Sandbox](https://www.producthunt.com/products/agent-sandbox) |
| Google AI Plus 以 $7.99/月進軍美國及 35 國，含 Gemini 3 Pro、Flow、NotebookLM，正面對打 ChatGPT Go | InfoAI | 01-29 | [Google「AI Plus」7.99 美元進軍美國](https://www.infoai.com.tw/blog/google-ai-plus-us-799-35-countries-gemini-3-pro) |
| 博弘雲端以「AI 系統整合商」定位，協助 HAPPY GO 整合 Databricks 數據平台，廣告點擊轉換率提升 50% | 數位時代 | 01-30 | [從智慧助手到自主代理：博弘雲端如何帶領企業走上 AI 實踐之路](https://www.bnext.com.tw/article/89928/nextlinkcloud202601) |

## 🧠 L4: AI 模型與研究
| 中文摘要 | 來源 | 時間 | 標題 |
|----------|------|------|------|
| Claude Opus 4.6 發布，Terminal-Bench 2.0 與 Humanity's Last Exam 雙料冠軍，支援 1M context | Hacker News | 1 day ago | [Claude Opus 4.6](https://www.anthropic.com/news/claude-opus-4-6) |
| 次二次方注意力機制開源，30B 模型單 GPU 達 10M token 76 tok/s | r/LocalLLaMA | 02-07 02:19 | [Subquadratic Attention Release](https://reddit.com/r/LocalLLaMA/comments/1qxpf86/release_experimental_model_with_subquadratic/) |
| Waymo World Model 發布，基於 Genie 3 生成超寫實自動駕駛模擬環境，含相機+光達多模態輸出 | Hacker News | 15h ago | [The Waymo World Model](https://waymo.com/blog/2026/02/the-waymo-world-model-a-new-frontier-for-autonomous-driving-simulation) |
| 中國開源 AI 生態一年回顧：MoE 成預設架構，多模態/Agent 方向全面推進 | HuggingFace Blog | 01-27 | [Architectural Choices in China's Open-Source AI Ecosystem](https://huggingface.co/blog/huggingface/one-year-since-the-deepseek-moment-blog-2) |
| LinkedIn 分享 GPT-OSS 模型 Agentic RL 訓練實戰，使用 verl 框架在 gsm8k 等任務上驗證 | HuggingFace Blog | 01-27 | [Unlocking Agentic RL Training for GPT-OSS](https://huggingface.co/blog/LinkedIn/gpt-oss-agentic-rl) |
| MIT 研究團隊發布 EnCompass：自動回溯與平行搜尋的 AI agent 程式框架 | MIT News AI | 02-05 | [Helping AI agents search to get the best results from LLMs](https://news.mit.edu/2026/helping-ai-agents-search-to-get-best-results-from-llms-0205) |
| MIT 利用 AI 加速治療藥物發現與設計，合成生物學結合運算預測 | MIT News AI | 02-04 | [Using AI to accelerate discovery of therapeutic drugs](https://news.mit.edu/2026/3-questions-using-ai-to-accelerate-discovery-design-therapeutic-drugs-0204) |
| Google Agent Factory 分享開源 agentic 模型從資料蒐集到 RL 訓練的完整流程 | Dev.to | 02-06 | [Agent Factory Recap: Cracking Open an Open Model](https://dev.to/googleai/agent-factory-recap-cracking-open-an-open-model-42e6) |
| Gemini 3.0 Flash 用於機器人影片理解，將影片拆解為結構化動作序列 | Dev.to | 02-05 | [Video Understanding with Gemini 3.0 Flash for Robotics](https://dev.to/googleai/video-understanding-with-gemini-30-flash-for-robotics-5896) |
| HuggingFace 發布 Flow Matching 訓練研究，PRX-1.2B 模型在 Flux VAE 潛空間的實驗 | HuggingFace Blog | 02-06 | [Training a Flow Matching Model](https://huggingface.co/blog/prx-flow-matching-training) |
| Overworld 發布 Waypoint-1：即時互動式影片擴散模型，支援鍵盤滑鼠控制 | HuggingFace Blog | 01-20 | [Introducing Waypoint-1](https://huggingface.co/blog/waypoint-1) |

## 🚀 L5: 商業應用與新創
| 中文摘要 | 來源 | 時間 | 標題 |
|----------|------|------|------|
| Anthropic 法律外掛引爆 2850 億美元股市崩盤，SaaS 被 AI 團滅成熱門話題 | 科技新報 | 02-07 | [Project Genie 與 Claude Cowork 引爆白領焦慮](https://technews.tw/2026/02/07/will-claude-legal-replace-lawyers-and-the-software-industry/) |
| OpenAI Frontier 定位為企業 AI agent 管理平台，核心不是更強模型而是治理、權限、稽核 | InfoAI | 02-06 | [OpenAI 把 AI 代理人拉到「平台層」](https://www.infoai.com.tw/blog/openai-frontier-agent-governance-platform-enterprise-control) |
| 「沒產品、沒營收」的 neolabs 改寫募資規則，Humans& 種子輪 4.8 億美元估值 44.8 億 | InfoAI | 02-02 | [AI「研究型新創」正在改寫募資規則](https://www.infoai.com.tw/blog/ai-research-startups-funding-without-products) |
| RentAHuman.ai 讓 AI agent 租用真人完成實體任務，支援 MCP 整合 | Product Hunt | 02-05 | [RentAHuman.ai](https://www.producthunt.com/products/rentahuman-ai) |
| Pydantic 開源 Monty：Rust 寫的最小安全 Python 直譯器，專為 AI agent 設計，啟動 <1μs | Hacker News | 9h ago | [Monty: Secure Python interpreter for AI](https://github.com/pydantic/monty) |
| Smooth CLI：專為 AI agent 打造的瀏覽器工具，以自然語言取代低階點擊操作，宣稱速度快 20 倍 | Hacker News | 14h ago | [Smooth CLI – Token-efficient browser for AI agents](https://docs.smooth.sh/cli/overview) |
| OpenClaw 技能生態遭惡意軟體滲透，數百個惡意技能組成攻擊行動 | r/LocalLLaMA | 02-07 | [OpenClaw skill malware delivery chain](https://reddit.com/r/LocalLLaMA/comments/1qxrogr/a_topdownloaded_openclaw_skill_is_actually_a/) |
| HuggingFace 發布 Daggr：用 Python 建構 AI 工作流、自動生成視覺化畫布 | HuggingFace Blog | 01-29 | [Introducing Daggr](https://huggingface.co/blog/daggr) |
| 高盛解讀本週市場焦點：「AI-SaaS」之爭 | Wall Street CN | 02-07 | [高盛解读本周市场焦点："AI-SaaS"之争](https://wallstreetcn.com/articles/3765210) |
| OneAD 以 Creative AI 協助台灣福斯商旅連續 5 檔合作，結合 AdTech 數據動態展演 | 數位時代 | 02-02 | [廣告產製進入 Gen AI 時代](https://www.bnext.com.tw/article/89941/onead202601) |
| 日本 ASCII 報導 OpenClaw（前身 Moltbot/Clawdbot）：可代操 PC 的 AI agent，安全性爭議大 | はてなブックマーク | 02-02 | [面白すぎて危険すぎ！PCを"勝手に動かす"AI、OpenClaw](https://ascii.jp/elem/000/004/370/4370464/) |
| 奧義賽博以 AI 自動化資安解決方案登上台灣創新板，90%+ 訂閱續約率 | 創業小聚 | 02-07 | [奧義賽博擬登創新板](https://technews.tw/2026/02/07/cycarrier-ipo/) |

## 👥 L6: 人才與生產力
| 中文摘要 | 來源 | 時間 | 標題 |
|----------|------|------|------|
| 紐約州提出 FAIR News Act，要求新聞機構標示 AI 生成內容，人工審核後方可發布 | Hacker News | 21h ago | [New York bill requires disclaimers on AI-generated news](https://www.niemanlab.org/2026/02/a-new-bill-in-new-york-would-require-disclaimers-on-ai-generated-news-content/) |
| 如何有效用 AI 寫高品質程式碼：建立願景、精確文件、偵錯系統、程式碼審查等級標記 | Hacker News | 12h ago | [How to effectively write quality code with AI](https://heidenstedt.org/posts/2026/how-to-effectively-write-quality-code-with-ai/) |
| PwC 全球 CEO 調查：僅 12% 企業同時看到 AI 增收+降本，56% 財務無感，關鍵在企業級整合 | InfoAI | 01-29 | [為什麼多數企業看不到 AI ROI](https://www.infoai.com.tw/blog/ai-roi-enterprise-integration-accountability-chain-pwc-ceo-survey-2026) |
| AI 行政後勤化：差別不在工具升級，而在任務交付邊界與責任歸屬的重新定義 | InfoAI | 02-06 | [把行政後勤 AI 化](https://www.infoai.com.tw/blog/back-office-ai-from-digitization-to-governed-digital-labor) |
| AI 不是取代工作，而是取代幻覺：資深工程師反思身分認同與 AI 時代的槓桿效應 | Dev.to | 02-03 | [AI isn't taking our jobs — It's taking our illusions](https://dev.to/igbominadeveloper/ai-isnt-take-our-jobs-its-taking-our-illusions-138j) |
| 教 Claude Code 你的開發標準：CLAUDE.md + 自訂 skill + TDD 工作流程實戰 | Dev.to | 02-06 | [Teaching Claude Code Your Standards](https://dev.to/helderberto/teaching-claude-code-your-standards-k9p) |
| 用 Claude Code Skill 取代 Plop 產生器，實現 React 元件骨架的確定性產出 | Dev.to | 02-06 | [Replacing Plop with Claude Code Skill](https://dev.to/mbarzeev/replacing-a-plop-react-component-generator-with-a-claude-code-skill-5do) |
| HuggingFace 用 Claude 教開源模型寫 CUDA kernel，upskill 工具釋出 | HuggingFace Blog | 01-28 | [We Got Claude to Build CUDA Kernels and teach open models!](https://huggingface.co/blog/upskill) |
| 台灣 GDP 因 AI 外需爆衝 8.63%（2025 全年），但成長高度集中出口鏈，金融穩定風險上升 | InfoAI | 02-02 | [台灣GDP 爆衝的真相：AI 外需把成長推到高檔](https://www.infoai.com.tw/blog/taiwan-gdp-ai-export-financial-stability-risk) |
| AI「Grok」深偽事件：倫理後置的投資回收危機，法國檢察搜索 X 辦公室 | はてなブックマーク | 02-06 | [AI「Grok」のディープフェイク騒動](https://www.nikkei.com/article/DGXZQOGN3019Q0Q6A130C2000000/) |
| Fitbit 創辦人打造 Luffu：AI 家庭全員健康共享互助平台 | 科技新報 | 02-07 | [Fitbit 創辦人打造 AI 家庭健康平台](https://technews.tw/2026/02/07/fitbit-founders-launch-ai-platform-to-help-families-monitor-their-health/) |
| Moltbook 不是 AI 社會：缺乏身分驗證的「自主 agent 社交網路」實為人類操控 | Dev.to | 02-04 | [Moltbook Is Not an AI Society](https://dev.to/richardpascoe/moltbook-is-not-an-ai-society-4h6d) |

# 🖋🏻 顏碩均

> NLP 工程師 | AWS Certified Solutions Architect
>
> 全球華人股份有限公司
>
> 新北市板橋區 | 3年+ NLP 與雲端開發經驗

---

## 📞 聯絡方式

- 📱 0958-588-909
- 📧 cglogc53112@gmail.com
- 📍 新北市板橋區南雅西路
- 🔗 GitHub: [@yenstdi](https://github.com/yenstdi)

---

## 🎓 教育背景

### 國立臺北護理健康大學

- **資訊管理所** | 碩士 (2019/9 - 2022/1)
- **資訊管理系** | 學士 (2015/9 - 2019/6)

---

## 💼 工作經驗

### NLP 工程師 | 全球華人股份有限公司(1111人力銀行)
**2022/8 - 仍在職**

#### 主導專案開發

**AI Chatbot 智能客服系統**
- 開發雙軌智能對話系統：求職者端提供職缺搜尋、活動諮詢、職涯規劃等對話式服務；企業端協助人才搜尋與配對
- 採用 LLM + RAG 架構，整合 OpenSearch 向量檢索與 MCP (Model Context Protocol) 實現多輪對話與知識庫問答
- 每日服務超過 1,000 名活躍用戶，顯著提升用戶搜尋體驗與平台黏著度

**PDF 履歷智能解析系統**
- 建立非結構化履歷自動化處理流程，結合 OCR 與 LLM 技術萃取關鍵資訊（學經歷、技能、證照等）
- 設計提示工程 (Prompt Engineering) 與資料驗證機制，確保擷取正確率達 95%
- 每月處理超過 1,000 份履歷，大幅降低人工建檔成本與時間

**職缺自動匯入系統**
- 開發通用職缺爬蟲系統，支援不限來源網站的職缺資訊擷取
- 使用 Playwright 進行動態網頁渲染，搭配 LLM 進行欄位智能對應 (Mapping)，無需針對每個網站客製化解析規則
- 成功擴充職缺資料來源，提升平台職缺多樣性與即時性

**自傳魔法師 (AI 自傳生成器)**
- 開發基於 LLM 的自傳自動生成工具，分析求職者履歷背景並產出客製化自傳內容
- 設計 Prompt 模板與 Chain-of-Thought 流程，確保生成內容符合求職情境與專業性
- 每日服務數百名使用者，協助求職者快速完成履歷撰寫

**職類推薦引擎**
- 建立內容式向量推薦系統，運用 Sentence-Transformers 對職缺與履歷文字進行語意嵌入
- 透過向量相似度搜尋，為求職者推薦最匹配的職類與職缺
- 提供個人化推薦體驗，提升求職者與職缺的配對精準度

**職缺搜尋智能優化**
- 開發 NER (命名實體識別) 系統，自動辨識搜尋查詢中的特殊字詞（薪資、職務名稱、休假制度、技能、證照等）
- 將識別結果自動對應至系統後台搜尋參數，實現精準的結構化查詢
- 顯著提升搜尋精準度與用戶滿意度，減少無效搜尋結果

**數據可視化與監控平台 (Superset)**
- 建立企業級數據分析平台，整合各式 AI 服務用量追蹤與業務指標監控
- 串接多元數據源（PostgreSQL、OpenSearch、S3），設計即時儀表板監控 AI Chatbot 使用量、PDF 解析成功率、推薦系統效能等關鍵指標
- 提供管理層與產品團隊數據洞察支援，加速決策效率與問題排查能力

#### 雲端架構與技術支援

**AWS 架構輔導與上雲支援**
- 協助團隊成員將服務遷移至 AWS 雲端，提供技術諮詢與架構設計建議
- 規劃並實作雲端部署方案：ALB + ECS 容器化部署與 API Gateway + Lambda Serverless 架構
- 解決雲端網路配置（VPC、Security Group、Route Table）與 IAM 權限管理問題，確保服務安全性與可用性
- 提升團隊雲端技術能力，加速產品交付週期

**基礎設施即程式碼 (IaC) 與自動化**
- 採用 Terraform 實現基礎設施自動化部署，標準化環境配置與版本控制
- 設計數據管線架構，整合 AWS Glue、S3 與 Athena 建立自動化 ETL 流程

#### 技術分享

- **2024 AWS GenAI Day** 擔任講師，分享企業級 LLM 應用實踐經驗與技術架構
- **2025 AWS Summit** 受邀擔任講師，推廣生成式 AI 技術應用

---

### AI 工程師 | 天賦人工智慧股份有限公司（兼職）
**2024/6 - 2025/6 · 1年1個月**

#### AI Agent 架構與多機器人系統

**AI Chatbot 基礎設施與 Agent 架構**
- 建立企業級 AI Chatbot 基礎設施，設計可擴展的 Agent 架構整合 RAG 與 Rerank 機制
- 採用 LangGraph 開發流程化機器人，自動處理固定業務流程，提升客戶服務效率與一致性
- 實現穩定且高效的對話系統架構，支援多場景應用需求

**多機器人系統 (LangGraph Swarm)**
- 使用 LangGraph Swarm 架構建置多功能機器人協作系統，包含客服機器人、銷售機器人、留學顧問機器人
- 客服機器人處理一般諮詢，銷售機器人協助課程推薦與轉換，留學顧問機器人提供海外升學專業諮詢
- 實現機器人間智能路由與協作，依據用戶需求自動分派至最適合的專業機器人

**多租戶架構 RAG 系統**
- 設計並實作多租戶架構的 RAG 系統，支援不同客戶獨立的知識庫管理與隔離
- 確保數據安全性與隱私保護，同時優化資源共享與系統效能
- 提供彈性的知識庫配置，滿足不同企業客戶的客製化需求

**學程推薦系統**
- 開發智能學程推薦引擎，結合用戶背景課程匹配
- 整合 AI Agent，提升學程推薦準確度與用戶滿意度

---

## 🛠 技術專長

### AI 與機器學習

- **自然語言處理**:Named Entity Recognition (NER)、Text Classification、Semantic Analysis、Text Embedding
- **機器學習應用**:推薦系統、時間序列分析、分群、分類、回歸
- **電腦視覺**:影像識別、OCR
- **大型語言模型**:RAG (Retrieval-Augmented Generation)、Rerank、Prompt Engineering、Zero-shot、Few-shot Learning、Chain-of-Thought (CoT)、Agentic、Function Calling、MCP (Model Context Protocol)
- **LLM 平台**:ChatGPT、Claude、Gemini、AWS Q
- **AI 框架**:Langchain、LangGraph (含 Swarm)、Hugging Face、PyTorch

### 雲端與 DevOps

- **AWS**:ECS、Lambda、SageMaker、Glue、API Gateway、OpenSearch
- **基礎設施即程式碼**:Terraform、AWS CDK (Python)、Serverless Framework、Docker
- **監控與部署**:CloudWatch、CI/CD

### 開發技能

- **程式語言**:Python
- **資料庫**:PostgreSQL、MongoDB、Redis
- **API 開發**:FastAPI、Django
- **資料科學**:Web Scraping (Playwright)、資料處理與清洗、資料分析、統計分析
- **數據可視化**:Apache Superset
- **AI 開發工具**:Vibe Coding、Speckit

---

## 📜 專業認證

### AWS 證照

- AWS Certified AI Practitioner
- AWS Certified Cloud Practitioner
- AWS Certified Solutions Architect – Associate

### AWS 進修課程

- Practical Data Science with Amazon SageMaker
- Architecting on AWS
- Advanced Architecting on AWS
- Building Data Lakes on AWS
- Building Analytics Solutions

---

## 💡 求職期望

### 工作偏好

- **性質**:全職 | **時段**:日班
- **可上班時間**:錄取後一個月
- **期望待遇**:月薪 80,000 元以上 / 年薪 100 萬元以上
- **遠程工作**:有意願

### 目標職位

- 資料科學家
- 機器學習工程師
- 雲端架構師
- 解決方案架構師

### 地點偏好

- 臺北市 / 新北市
- 臺中市 / 新竹縣市
- 臺南市 / 高雄市

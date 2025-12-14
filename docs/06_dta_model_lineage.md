## 6. 🧬 Data & Model Lineage (數據與模型血緣)
* **類型:** `Layered View`
* **目標受眾:** 🎯 CISO, DPO (資料保護長)

解決 **「信任 (Trust)」** 與 **「可解釋性 (Explainability)」** 問題。繪製機密資料從源頭到決策的完整流向。

* **數據旅程:**
    1.  **Source:** 原始客戶資料/交易資料。
    2.  **Processing:** **關鍵節點！** 資料清洗與去識別化 (Anonymization)。
    3.  **Storage:** 寫入向量資料庫 (Vector DB)。
    4.  **Inference:** 進入 LLM 模型並產出結果。
    5.  **Decision:** 人工審核 (Human-in-the-loop) 後形成業務決策。

> **💡 決策價值:** 視覺化證明企業機密數據在未經處理的情況下，絕不會外洩給公有雲模型，消除資安疑慮。
![Data & Model Lineage View](img/06_dta_model_lineage.png)
# HermesTam Runtime

.240（@hermestam_bot）美股投資 Hermes Agent 嘅 cron job 運行狀態頁。

- 🌐 **Runtime page**：https://ckfan1209-prog.github.io/hermestam-runtime/
- 📊 **原始數據**：[`data.json`](data.json)（每日同步時一併更新）

## 內容

- 全部 40 個 cron job（38 啟用／2 停用）嘅排程、最後運行狀態、下次運行時間
- 每個 job 嘅最新輸出摘要（逐 job 獨立歸檔於 .240 `~/.hermes/cron/output/<job_id>/`）
- 當日市場分析輸出文件

## 同步機制

每日約 00:47 HKT 由 Pison 自動收集 .240 各 job 輸出、生成頁面並推送本 repo。
公開版已自動遮蔽持倉章節、股數／成本等個人財務行及疑似密鑰字串；不含持倉檔案與任何憑證。

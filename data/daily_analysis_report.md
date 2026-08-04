# 盤後選股分析

> 報告狀態：**完成**｜產生時間：2026-08-04 14:31:38（Asia/Taipei）

## 1. 今日結論

**今日無可直接買進標的。**
Raw候選 40 檔；舊路徑退役觀察 3 檔；新假設v2.1預先登記觀察 0 檔。
Full Validation已由使用者暫緩，不會自動執行，也不會耗用七年驗證的Actions額度。

## 2. 資料日期、版本、工具讀取結果、P0安全與歷史來源稽核

- 報告版本：`daily_after_market_report_v1`
- 產生時間：2026-08-04 14:31:38（Asia/Taipei）
- latest_indicators：2026-08-04 14:31:24
- gate_diagnostics：2026-08-04 14:31:37
- 資料為今日：是
- 策略與引擎版本相容：是
- Diagnostic版本：`gate_diagnostics_v20_preregistered_entry_hypotheses`
- 舊路徑Manifest來源稽核：是
- P0安全：是；歷史洩漏=0；每日洩漏=0
- GitHub Actions本機檔案讀取：
  - `data/latest_indicators.json`：成功
  - `data/gate_diagnostics.json`：成功
  - `data/failed_breakout_watchlist.json`：成功
  - `data/performance_summary.json`：成功
  - `data/historical_event_trade_v14_manifest.json`：成功
  - `data/new_entry_hypothesis_v21_smoke_manifest.json`：成功
  - `data/new_entry_hypothesis_v21_full_manifest.json`：略過／不存在（file_not_found）
  - `data/new_entry_hypothesis_v21_full_summary.json`：略過／不存在（file_not_found）

## 3. 正式Direct Buy結果

**今日無可直接買進標的。**
判定依據：`direct_buy_signal=true`且`direct_buy_blocker=false`的候選為0。

## 4. 舊Confirmed Breakout退役觀察

- **2357 華碩｜不可買**：階段 `research_retired_observation`；類型 `both_paths`；分數 99.55；RR 2.57；目標 12.03%；原因：P0 Shadow Mode：獨立掃描器兩條現行進場假設均已退役，待重新設計與正式驗證
- **2618 長榮航｜不可買**：階段 `research_retired_observation`；類型 `confirmed_breakout`；分數 91.56；RR 1.54；目標 11.76%；原因：P0 Shadow Mode：獨立掃描器兩條現行進場假設均已退役，待重新設計與正式驗證
- **2610 華航｜不可買**：階段 `research_retired_observation`；類型 `confirmed_breakout`；分數 87.81；RR 2.04；目標 12.25%；原因：P0 Shadow Mode：獨立掃描器兩條現行進場假設均已退役，待重新設計與正式驗證
歷史治理：事件數 529；穩定情境 0；狀態 `retire_or_redesign_current_entry_hypothesis`。

## 5. 舊Tradeable Second Leg退役觀察

- **2357 華碩｜不可買**：階段 `research_retired_observation`；類型 `both_paths`；分數 99.55；RR 2.57；目標 12.03%；原因：P0 Shadow Mode：獨立掃描器兩條現行進場假設均已退役，待重新設計與正式驗證
歷史治理：事件數 146；穩定情境 0；狀態 `retire_or_redesign_current_entry_hypothesis`。

## 6. 新假設v2.1研究觀察

- 新假設版本：`entry_hypotheses_v2.1_preregistered`
- 新假設Guard：`未載明`
- 今日新假設候選數：0
- **Breakout Retest Acceptance：**
  - 今日無retest預先登記研究觀察。
- **Post-Breakout Compression Expansion：**
  - 今日無compression預先登記研究觀察。
上述候選全部`new_hypothesis_production_eligible=false`，只能累積前瞻資料，**不可買**。

## 7. Gate與主要失敗原因

- Universe：125
- Volume通過：100
- PA成功：100
- Raw候選：40
- 正式Direct Buy：0
- 研究退役觀察：3
- 新假設候選：0
- 主要排除原因：
  - Tradeable Second Leg path 未通過：做多方向一致：33檔
  - Tradeable Second Leg path 未通過：型態與分數品質：33檔
  - Tradeable Second Leg path 未通過：進場確認：33檔
  - Tradeable Second Leg path 未通過：合法突破情境：33檔
  - Tradeable Second Leg path 未通過：突破跟隨：33檔
  - Tradeable Second Leg path 未通過：對手方被困：33檔
  - Tradeable Second Leg path 未通過：True Breakout 品質：33檔
  - Tradeable Second Leg path 未通過：可交易第二段：33檔
- Candidate Stage：
  - setup_observation：34
  - research_retired_observation：3
  - bullish_setup_ready：2
  - entry_confirmed：1

## 8. True Breakout／Follow-through／停損與no-add風險

- True Breakout：
  - Low：92
  - Unknown：25
  - High：5
  - Medium：3
- Follow-through：
  - Poor：92
  - Unknown：25
  - StrongImmediate：3
  - None：2
  - WeakButAcceptable：2
  - DelayedStrong：1
- Second Leg Trap：
  - True：39
  - False：1
- Stop Execution Blocker：
  - False：100
  - Unknown：25
- 候選資料中的no-add guardrail：59檔；停損執行阻擋：0檔。
- no-add=true時，任何pullback zone只可作`observation_only`，不得作買點或加碼點。
- **3231 緯創｜不可買**：階段 `entry_confirmed`；類型 `confirmed_breakout`；分數 92.81；RR 1.05；目標 21.54%；原因：P0 Shadow Mode：獨立掃描器兩條現行進場假設均已退役，待重新設計與正式驗證
- **2618 長榮航｜不可買**：階段 `research_retired_observation`；類型 `confirmed_breakout`；分數 91.56；RR 1.54；目標 11.76%；原因：P0 Shadow Mode：獨立掃描器兩條現行進場假設均已退役，待重新設計與正式驗證
- **2610 華航｜不可買**：階段 `research_retired_observation`；類型 `confirmed_breakout`；分數 87.81；RR 2.04；目標 12.25%；原因：P0 Shadow Mode：獨立掃描器兩條現行進場假設均已退役，待重新設計與正式驗證
- **2880 華南金｜不可買**：階段 `bullish_setup_ready`；類型 `confirmed_breakout`；分數 79.38；RR 1.98；目標 13.06%；原因：P0 Shadow Mode：獨立掃描器兩條現行進場假設均已退役，待重新設計與正式驗證
- **2884 玉山金｜不可買**：階段 `bullish_setup_ready`；類型 `confirmed_breakout`；分數 76.00；RR 1.71；目標 10.53%；原因：P0 Shadow Mode：獨立掃描器兩條現行進場假設均已退役，待重新設計與正式驗證

## 9. 最值得追蹤1～3檔

- **2357 華碩｜不可買**：階段 `research_retired_observation`；類型 `both_paths`；分數 99.55；RR 2.57；目標 12.03%；原因：P0 Shadow Mode：獨立掃描器兩條現行進場假設均已退役，待重新設計與正式驗證
- **2618 長榮航｜不可買**：階段 `research_retired_observation`；類型 `confirmed_breakout`；分數 91.56；RR 1.54；目標 11.76%；原因：P0 Shadow Mode：獨立掃描器兩條現行進場假設均已退役，待重新設計與正式驗證
- **2610 華航｜不可買**：階段 `research_retired_observation`；類型 `confirmed_breakout`；分數 87.81；RR 2.04；目標 12.25%；原因：P0 Shadow Mode：獨立掃描器兩條現行進場假設均已退役，待重新設計與正式驗證
本節全部是觀察資料，逐檔均為**不可買**，不得替代正式Direct Buy。

## 10. Performance Summary、Smoke限制與Full Validation狀態

- Performance完成樣本：124；正式Direct Buy完成樣本：0。
- 被拒絕候選整體勝率：42.74%；T+5平均報酬：-2.10%；MFE：3.74%；MAE：-7.17%。
- 上述績效主要來自被拒絕候選，不代表正式Direct Buy或新假設有效。
- Smoke：事件數 3；正式買進洩漏 0。Smoke只證明程式與候選生成正常。
- Full Validation狀態：已由使用者暫緩。
- Full Validation包含8月均不執行；不得自動啟動七年驗證或以Smoke調整v2.1門檻。

## 11. P0／P1／P2

- **P0：**維持所有舊路徑與新假設的正式硬阻擋；正式買進洩漏必須為0。
- **P1：**只累積v2.1每日前瞻研究資料，固定現有門檻，不因少量樣本調整。
- **P2：**七年Full Validation保持暫緩，不自動建議、不自動排程；只有使用者明確重新授權才可啟用。

---
本報告由GitHub Actions依JSON規則自動產生，不使用LLM，不改變任何交易訊號。

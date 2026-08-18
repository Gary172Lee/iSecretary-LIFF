# 盤後選股分析

> 報告狀態：**完成**｜產生時間：2026-08-18 17:58:14（Asia/Taipei）

## 1. 今日結論

**今日無可直接買進標的。**
Raw候選 45 檔；舊路徑退役觀察 0 檔；新假設v2.1預先登記觀察 0 檔。
Full Validation已由使用者暫緩，不會自動執行，也不會耗用七年驗證的Actions額度。
Swing Buy 20D：16 檔合格；依 Extension Momentum 作第二層排序，v4.0 Gate 不變。
Swing Buy 20D：候選池 16；正式 Buy Now 0。正式名單以現價 Forward Entry Edge 為準。

## 2. 資料日期、版本、工具讀取結果、P0安全與歷史來源稽核

- 報告版本：`daily_after_market_report_v4_swing_forward_entry_edge`
- 產生時間：2026-08-18 17:58:14（Asia/Taipei）
- latest_indicators：2026-08-18 17:58:00
- gate_diagnostics：2026-08-18 17:58:06
- 資料為今日：是
- 策略與引擎版本相容：是
- Diagnostic版本：`gate_diagnostics_v21_swing_buy_20d`
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
  - `data/swing_performance_summary.json`：成功

## 3. 正式Direct Buy結果

**今日無可直接買進標的。**
判定依據：`direct_buy_signal=true`且`direct_buy_blocker=false`的候選為0。

## 3A. Swing Buy 20D（Forward Entry Edge / 現價獲利優先）

核心目標：找『以今天現價買進，未來5～20交易日仍有足夠獲利空間』，不是找最近漲最強的股票。
- v4.0 qualified 只作候選池；Direct Buy真值與v4.0 Gate不變。
- Extension Momentum 降為 15% 輔助；最終正式 Swing 買進名單只接受 `swing_forward_entry_decision=BuyNow`。
- 今日候選池：16；Buy Now：0；Wait Pullback：15；Reject：1。
**今日 Buy Now = 0 檔。寧可沒有標的，也不把已過度延伸的強勢股當成現在可追價。**
**Wait Pullback（股票可強，但現價不是好買點；不列正式買進）**
- 2884 玉山金｜**Wait Pullback**：現價進場優勢 67.81；剩餘空間 10.0%；Forward RR 1.92；Pullback參考 37.60；原因：forward_entry_edge_score_below_80、traceable_headroom_below_12pct。
- 2881 富邦金｜**Wait Pullback**：現價進場優勢 61.38；剩餘空間 9.3%；Forward RR 1.81；Pullback參考 未載明；原因：forward_entry_edge_score_below_80、traceable_headroom_below_12pct。
- 2887 台新金｜**Wait Pullback**：現價進場優勢 59.58；剩餘空間 10.0%；Forward RR 1.43；Pullback參考 36.15；原因：forward_entry_edge_score_below_80、forward_rr_below_1_8、traceable_headroom_below_12pct。
- 1519 華城｜**Wait Pullback**：現價進場優勢 54.44；剩餘空間 10.0%；Forward RR 1.43；Pullback參考 676.31；原因：entry_quality_below_7、forward_entry_edge_score_below_80、forward_rr_below_1_8、traceable_headroom_below_12pct。
- 2609 陽明｜**Wait Pullback**：現價進場優勢 53.51；剩餘空間 10.0%；Forward RR 1.43；Pullback參考 53.50；原因：entry_quality_below_7、forward_entry_edge_score_below_80、forward_rr_below_1_8、traceable_headroom_below_12pct。
- 2324 仁寶｜**Wait Pullback**：現價進場優勢 48.01；剩餘空間 10.0%；Forward RR 1.43；Pullback參考 39.75；原因：entry_quality_below_7、forward_entry_edge_score_below_80、forward_rr_below_1_8、traceable_headroom_below_12pct。
- 6669 緯穎｜**Wait Pullback**：現價進場優勢 46.75；剩餘空間 10.0%；Forward RR 1.43；Pullback參考 6107.50；原因：entry_quality_below_7、forward_entry_edge_score_below_80、forward_rr_below_1_8、traceable_headroom_below_12pct。
- 2301 光寶科｜**Wait Pullback**：現價進場優勢 46.44；剩餘空間 10.0%；Forward RR 1.43；Pullback參考 258.00；原因：entry_quality_below_7、extension_from_sma20_above_12pct、forward_entry_edge_score_below_80、forward_rr_below_1_8。
- 2408 南亞科｜**Wait Pullback**：現價進場優勢 44.98；剩餘空間 10.0%；Forward RR 1.43；Pullback參考 463.75；原因：entry_quality_below_7、extension_from_sma20_above_12pct、forward_entry_edge_score_below_80、forward_rr_below_1_8。
- 3189 景碩｜**Wait Pullback**：現價進場優勢 44.46；剩餘空間 10.0%；Forward RR 1.43；Pullback參考 815.50；原因：entry_quality_below_7、extension_from_sma20_above_12pct、forward_entry_edge_score_below_80、forward_rr_below_1_8。
- Forward Entry policy：`swing_forward_entry_edge_v1`。
- 驗證狀態：not_evaluable_until_completed_buy_now_30；以每次 BuyNow 當日現價固定為D0，驗證T+20報酬、MFE、勝率與先停損率。

## 4. 舊Confirmed Breakout退役觀察

今日沒有可辨識的舊Confirmed Breakout技術通過觀察。
歷史治理：事件數 529；穩定情境 0；狀態 `retire_or_redesign_current_entry_hypothesis`。

## 5. 舊Tradeable Second Leg退役觀察

今日沒有可辨識的舊Tradeable Second Leg技術通過觀察。
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
- Volume通過：102
- PA成功：102
- Raw候選：45
- 正式Direct Buy：0
- 研究退役觀察：0
- 新假設候選：0
- 主要排除原因：
  - Tradeable Second Leg path 未通過：做多方向一致：23檔
  - Tradeable Second Leg path 未通過：型態與分數品質：23檔
  - Tradeable Second Leg path 未通過：合法突破情境：23檔
  - Tradeable Second Leg path 未通過：突破跟隨：23檔
  - Tradeable Second Leg path 未通過：對手方被困：23檔
  - Tradeable Second Leg path 未通過：True Breakout 品質：23檔
  - Tradeable Second Leg path 未通過：可交易第二段：23檔
  - Tradeable Second Leg path 未通過：進場確認：21檔
- Candidate Stage：
  - setup_observation：45

## 8. True Breakout／Follow-through／停損與no-add風險

- True Breakout：
  - Low：97
  - Unknown：19
  - High：8
  - Medium：1
- Follow-through：
  - Poor：94
  - Unknown：19
  - None：5
  - WeakButAcceptable：4
  - StrongImmediate：3
- Second Leg Trap：
  - True：42
  - False：3
- Stop Execution Blocker：
  - False：106
  - Unknown：19
- 候選資料中的no-add guardrail：62檔；停損執行阻擋：0檔。
- no-add=true時，任何pullback zone只可作`observation_only`，不得作買點或加碼點。
- **3017 奇鋐｜不可買**：階段 `setup_observation`；類型 `tradeable_second_leg`；分數 66.88；RR 2.78；目標 29.00%；原因：P0 Shadow Mode：獨立掃描器兩條現行進場假設均已退役，待重新設計與正式驗證
- **2360 致茂｜不可買**：階段 `setup_observation`；類型 `tradeable_second_leg`；分數 未載明；RR 2.10；目標 未載明；原因：Tradeable Second Leg path 未通過：資料、流動性與滑價 | Tradeable Second Leg path 未通過：做多方向一致 | Tradeable Second Leg path 未通過：型態與分數品質 | Tradeable Second Leg path 未通過：進場確認 | Tradeable Second Leg path 未通過：目標報酬至少 10% | Tradeable Second Leg path 未通過：合法突破情境 | Tradeable Second Leg path 未通過：突破跟隨 | Tradeable Second Leg path 未通過：對手方被困 | Tradeable Second Leg path 未通過：True Breakout 品質 | Tradeable Second Leg path 未通過：可交易第二段
- **2891 中信金｜不可買**：階段 `setup_observation`；類型 `tradeable_second_leg`；分數 未載明；RR 4.64；目標 未載明；原因：Tradeable Second Leg path 未通過：做多方向一致 | Tradeable Second Leg path 未通過：型態與分數品質 | Tradeable Second Leg path 未通過：進場確認 | Tradeable Second Leg path 未通過：目標報酬至少 10% | Tradeable Second Leg path 未通過：合法突破情境 | Tradeable Second Leg path 未通過：突破跟隨 | Tradeable Second Leg path 未通過：對手方被困 | Tradeable Second Leg path 未通過：True Breakout 品質 | Tradeable Second Leg path 未通過：可交易第二段
- **8046 南電｜不可買**：階段 `setup_observation`；類型 `tradeable_second_leg`；分數 未載明；RR 1.31；目標 未載明；原因：Tradeable Second Leg path 未通過：資料、流動性與滑價 | Tradeable Second Leg path 未通過：做多方向一致 | Tradeable Second Leg path 未通過：型態與分數品質 | Tradeable Second Leg path 未通過：進場確認 | Tradeable Second Leg path 未通過：目標報酬至少 10% | Tradeable Second Leg path 未通過：風險報酬比至少 1.5 | Tradeable Second Leg path 未通過：合法突破情境 | Tradeable Second Leg path 未通過：突破跟隨 | Tradeable Second Leg path 未通過：對手方被困 | Tradeable Second Leg path 未通過：True Breakout 品質 | Tradeable Second Leg path 未通過：可交易第二段
- **6274 台燿｜不可買**：階段 `setup_observation`；類型 `tradeable_second_leg`；分數 未載明；RR 4.41；目標 未載明；原因：Tradeable Second Leg path 未通過：資料、流動性與滑價 | Tradeable Second Leg path 未通過：做多方向一致 | Tradeable Second Leg path 未通過：型態與分數品質 | Tradeable Second Leg path 未通過：進場確認 | Tradeable Second Leg path 未通過：目標報酬至少 10% | Tradeable Second Leg path 未通過：合法突破情境 | Tradeable Second Leg path 未通過：突破跟隨 | Tradeable Second Leg path 未通過：對手方被困 | Tradeable Second Leg path 未通過：True Breakout 品質 | Tradeable Second Leg path 未通過：可交易第二段

## 9. 最值得追蹤1～3檔

- **3017 奇鋐｜不可買**：階段 `setup_observation`；類型 `tradeable_second_leg`；分數 66.88；RR 2.78；目標 29.00%；原因：P0 Shadow Mode：獨立掃描器兩條現行進場假設均已退役，待重新設計與正式驗證
- **2360 致茂｜不可買**：階段 `setup_observation`；類型 `tradeable_second_leg`；分數 未載明；RR 2.10；目標 未載明；原因：Tradeable Second Leg path 未通過：資料、流動性與滑價 | Tradeable Second Leg path 未通過：做多方向一致 | Tradeable Second Leg path 未通過：型態與分數品質 | Tradeable Second Leg path 未通過：進場確認 | Tradeable Second Leg path 未通過：目標報酬至少 10% | Tradeable Second Leg path 未通過：合法突破情境 | Tradeable Second Leg path 未通過：突破跟隨 | Tradeable Second Leg path 未通過：對手方被困 | Tradeable Second Leg path 未通過：True Breakout 品質 | Tradeable Second Leg path 未通過：可交易第二段
- **2891 中信金｜不可買**：階段 `setup_observation`；類型 `tradeable_second_leg`；分數 未載明；RR 4.64；目標 未載明；原因：Tradeable Second Leg path 未通過：做多方向一致 | Tradeable Second Leg path 未通過：型態與分數品質 | Tradeable Second Leg path 未通過：進場確認 | Tradeable Second Leg path 未通過：目標報酬至少 10% | Tradeable Second Leg path 未通過：合法突破情境 | Tradeable Second Leg path 未通過：突破跟隨 | Tradeable Second Leg path 未通過：對手方被困 | Tradeable Second Leg path 未通過：True Breakout 品質 | Tradeable Second Leg path 未通過：可交易第二段
本節全部是觀察資料，逐檔均為**不可買**，不得替代正式Direct Buy。

## 10. Performance Summary、Smoke限制與Full Validation狀態

- Performance完成樣本：229；正式Direct Buy完成樣本：0。
- 被拒絕候選整體勝率：46.29%；T+5平均報酬：-0.84%；MFE：4.48%；MAE：-5.55%。
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

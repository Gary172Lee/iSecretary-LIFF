# 盤後選股分析

> 報告狀態：**完成**｜產生時間：2026-11-12 14:25:13（Asia/Taipei）

## 1. 今日結論

**今日無可直接買進標的。**
Raw候選 17 檔；舊路徑退役觀察 0 檔；新假設v2.1預先登記觀察 0 檔。
Full Validation已由使用者暫緩，不會自動執行，也不會耗用七年驗證的Actions額度。
Swing Buy 20D：3 檔合格；依 Extension Momentum 作第二層排序，v4.0 Gate 不變。
Swing Buy 20D：候選池 3；正式 Buy Now 0。正式名單以現價 Forward Entry Edge 為準。
Deep Recovery v2：1 檔評估候選；v1 strict 同日對照 0 檔；均不是BuyNow。

## 2. 資料日期、版本、工具讀取結果、P0安全與歷史來源稽核

- 報告版本：`daily_after_market_report_v6_deep_recovery_transition_v2`
- 產生時間：2026-11-12 14:25:13（Asia/Taipei）
- latest_indicators：2026-11-12 14:24:48
- gate_diagnostics：2026-11-12 14:25:02
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
  - `data/deep_recovery_3m_candidates.json`：成功
  - `data/deep_recovery_transition_v2_candidates.json`：成功

## 3. 正式Direct Buy結果

**今日無可直接買進標的。**
判定依據：`direct_buy_signal=true`且`direct_buy_blocker=false`的候選為0。

## 3A. Swing Buy 20D（Forward Entry Edge / 現價獲利優先）

核心目標：找『以今天現價買進，未來5～20交易日仍有足夠獲利空間』，不是找最近漲最強的股票。
- v4.0 qualified 只作候選池；Direct Buy真值與v4.0 Gate不變。
- Extension Momentum 降為 15% 輔助；最終正式 Swing 買進名單只接受 `swing_forward_entry_decision=BuyNow`。
- 今日候選池：3；Buy Now：0；Wait Pullback：1；Reject：2。
**今日 Buy Now = 0 檔。寧可沒有標的，也不把已過度延伸的強勢股當成現在可追價。**
**Wait Pullback（股票可強，但現價不是好買點；不列正式買進）**
- 1476 儒鴻｜**Wait Pullback**：現價進場優勢 44.35；剩餘空間 10.0%；Forward RR 1.43；Pullback參考 341.50；原因：entry_quality_below_7、forward_entry_edge_score_below_80、forward_rr_below_1_8、traceable_headroom_below_12pct。
- Forward Entry policy：`swing_forward_entry_edge_v1`。
- 驗證狀態：not_evaluable_until_completed_buy_now_30；以每次 BuyNow 當日現價固定為D0，驗證T+20報酬、MFE、勝率與先停損率。

## 3B. Deep Recovery 3M（Historical Drawdown → Recovery Transition v2）

本池與 Direct Buy、Swing v4.0、Forward Entry 完全獨立；不改寫任何既有 Gate 或買進真值。
- v2 核心：近63交易日內先辨識 peak→後續 trough 的最大事件回撤；事件回撤至少30%，再評估目前是否由低點開始復甦。
- v2 不再要求『目前價格仍低於63D高點30%』；因此真正回升到 -29%、-25% 等位置的股票不會只因復甦本身而被淘汰。
- 仍維持 WeakUp 以上、Extension ≥55、Candidate Score ≥60；沒有降低分數或趨勢門檻。
- 一旦完全收復事件高點，視為 recovery transition 已完成，不再列入本池。
- 今日 v2 評估候選：1 檔；v1 strict 同日對照：0 檔。
- **3661 世芯-KY｜Deep Recovery v2**：現價 3675.00；事件高點 4395.00（2026-10-12）；事件低點 2830.00（2026-11-06）；事件最大回撤 -35.6%；目前距事件高點 -16.4%；自低點回升 +29.9%；復甦進度 54.0%；Recovery WeakUp；延伸動能 66.0／Moderate；候選分 74.30／RecoveryReady；題材 `semiconductor/asic`；基本面/消息面：待ChatGPT排程即時健康審核。
**Near Miss / 第一失敗 Gate：**
- 6488 環球晶｜第一失敗 Gate=`weakup_gate_not_met`；事件回撤 -57.9%；目前距事件高點 -48.8%；自低點回升 +21.5%；Trend=NotUp；Extension=未載明；Score=未載明。
- 2360 致茂｜第一失敗 Gate=`weakup_gate_not_met`；事件回撤 -50.6%；目前距事件高點 -41.8%；自低點回升 +17.8%；Trend=NotUp；Extension=未載明；Score=未載明。
- 3081 聯亞｜第一失敗 Gate=`weakup_gate_not_met`；事件回撤 -50.4%；目前距事件高點 -40.5%；自低點回升 +20.0%；Trend=NotUp；Extension=未載明；Score=未載明。
- 3532 台勝科｜第一失敗 Gate=`weakup_gate_not_met`；事件回撤 -50.0%；目前距事件高點 -43.3%；自低點回升 +13.5%；Trend=NotUp；Extension=未載明；Score=未載明。
- 6274 台燿｜第一失敗 Gate=`weakup_gate_not_met`；事件回撤 -49.1%；目前距事件高點 -46.3%；自低點回升 +5.5%；Trend=NotUp；Extension=未載明；Score=未載明。
- 基本面 Healthy/Caution/Risk 與 News Risk Low/Medium/High 不在 scanner 杜撰，交由 ChatGPT 排程依當日官方/可靠來源即時補充。

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
- Volume通過：98
- PA成功：98
- Raw候選：17
- 正式Direct Buy：0
- 研究退役觀察：0
- 新假設候選：0
- 主要排除原因：
  - Tradeable Second Leg path 未通過：做多方向一致：11檔
  - Tradeable Second Leg path 未通過：型態與分數品質：11檔
  - Tradeable Second Leg path 未通過：進場確認：11檔
  - Tradeable Second Leg path 未通過：合法突破情境：11檔
  - Tradeable Second Leg path 未通過：突破跟隨：11檔
  - Tradeable Second Leg path 未通過：對手方被困：11檔
  - Tradeable Second Leg path 未通過：True Breakout 品質：11檔
  - Tradeable Second Leg path 未通過：可交易第二段：11檔
- Candidate Stage：
  - setup_observation：17

## 8. True Breakout／Follow-through／停損與no-add風險

- True Breakout：
  - Low：95
  - Unknown：26
  - Medium：3
  - High：1
- Follow-through：
  - Poor：93
  - Unknown：26
  - None：4
  - DelayedStrong：1
  - StrongImmediate：1
- Second Leg Trap：
  - True：16
  - False：1
- Stop Execution Blocker：
  - False：99
  - Unknown：26
- 候選資料中的no-add guardrail：36檔；停損執行阻擋：0檔。
- no-add=true時，任何pullback zone只可作`observation_only`，不得作買點或加碼點。
- **3045 台灣大｜不可買**：階段 `setup_observation`；類型 `tradeable_second_leg`；分數 0.00；RR 11.00；目標 11.15%；原因：Tradeable Second Leg path 未通過：做多方向一致 | Tradeable Second Leg path 未通過：型態與分數品質 | Tradeable Second Leg path 未通過：進場確認 | Tradeable Second Leg path 未通過：合法突破情境 | Tradeable Second Leg path 未通過：突破跟隨 | Tradeable Second Leg path 未通過：對手方被困 | Tradeable Second Leg path 未通過：True Breakout 品質 | Tradeable Second Leg path 未通過：可交易第二段
- **2891 中信金｜不可買**：階段 `setup_observation`；類型 `confirmed_breakout`；分數 0.00；RR 未載明；目標 14.46%；原因：Confirmed Breakout path 未通過：做多方向一致 | Confirmed Breakout path 未通過：型態與分數品質 | Confirmed Breakout path 未通過：進場確認 | Confirmed Breakout path 未通過：風險報酬比至少 1.5 | Confirmed Breakout path 未通過：合法突破情境 | Confirmed Breakout path 未通過：突破跟隨 | Confirmed Breakout path 未通過：對手方被困 | Confirmed Breakout path 未通過：突破進場許可 | Confirmed Breakout path 未通過：True Breakout 品質
- **4904 遠傳｜不可買**：階段 `setup_observation`；類型 `tradeable_second_leg`；分數 0.00；RR 2.70；目標 19.44%；原因：Tradeable Second Leg path 未通過：做多方向一致 | Tradeable Second Leg path 未通過：型態與分數品質 | Tradeable Second Leg path 未通過：進場確認 | Tradeable Second Leg path 未通過：合法突破情境 | Tradeable Second Leg path 未通過：突破跟隨 | Tradeable Second Leg path 未通過：對手方被困 | Tradeable Second Leg path 未通過：True Breakout 品質 | Tradeable Second Leg path 未通過：可交易第二段
- **5880 合庫金｜不可買**：階段 `setup_observation`；類型 `tradeable_second_leg`；分數 未載明；RR 未載明；目標 未載明；原因：Tradeable Second Leg path 未通過：做多方向一致 | Tradeable Second Leg path 未通過：型態與分數品質 | Tradeable Second Leg path 未通過：進場確認 | Tradeable Second Leg path 未通過：目標報酬至少 10% | Tradeable Second Leg path 未通過：風險報酬比至少 1.5 | Tradeable Second Leg path 未通過：合法突破情境 | Tradeable Second Leg path 未通過：突破跟隨 | Tradeable Second Leg path 未通過：對手方被困 | Tradeable Second Leg path 未通過：True Breakout 品質 | Tradeable Second Leg path 未通過：可交易第二段
- **2618 長榮航｜不可買**：階段 `setup_observation`；類型 `tradeable_second_leg`；分數 未載明；RR 6.25；目標 未載明；原因：Tradeable Second Leg path 未通過：做多方向一致 | Tradeable Second Leg path 未通過：型態與分數品質 | Tradeable Second Leg path 未通過：進場確認 | Tradeable Second Leg path 未通過：目標報酬至少 10% | Tradeable Second Leg path 未通過：合法突破情境 | Tradeable Second Leg path 未通過：突破跟隨 | Tradeable Second Leg path 未通過：對手方被困 | Tradeable Second Leg path 未通過：True Breakout 品質 | Tradeable Second Leg path 未通過：可交易第二段

## 9. 最值得追蹤1～3檔

- **3045 台灣大｜不可買**：階段 `setup_observation`；類型 `tradeable_second_leg`；分數 0.00；RR 11.00；目標 11.15%；原因：Tradeable Second Leg path 未通過：做多方向一致 | Tradeable Second Leg path 未通過：型態與分數品質 | Tradeable Second Leg path 未通過：進場確認 | Tradeable Second Leg path 未通過：合法突破情境 | Tradeable Second Leg path 未通過：突破跟隨 | Tradeable Second Leg path 未通過：對手方被困 | Tradeable Second Leg path 未通過：True Breakout 品質 | Tradeable Second Leg path 未通過：可交易第二段
- **2891 中信金｜不可買**：階段 `setup_observation`；類型 `confirmed_breakout`；分數 0.00；RR 未載明；目標 14.46%；原因：Confirmed Breakout path 未通過：做多方向一致 | Confirmed Breakout path 未通過：型態與分數品質 | Confirmed Breakout path 未通過：進場確認 | Confirmed Breakout path 未通過：風險報酬比至少 1.5 | Confirmed Breakout path 未通過：合法突破情境 | Confirmed Breakout path 未通過：突破跟隨 | Confirmed Breakout path 未通過：對手方被困 | Confirmed Breakout path 未通過：突破進場許可 | Confirmed Breakout path 未通過：True Breakout 品質
- **4904 遠傳｜不可買**：階段 `setup_observation`；類型 `tradeable_second_leg`；分數 0.00；RR 2.70；目標 19.44%；原因：Tradeable Second Leg path 未通過：做多方向一致 | Tradeable Second Leg path 未通過：型態與分數品質 | Tradeable Second Leg path 未通過：進場確認 | Tradeable Second Leg path 未通過：合法突破情境 | Tradeable Second Leg path 未通過：突破跟隨 | Tradeable Second Leg path 未通過：對手方被困 | Tradeable Second Leg path 未通過：True Breakout 品質 | Tradeable Second Leg path 未通過：可交易第二段
本節全部是觀察資料，逐檔均為**不可買**，不得替代正式Direct Buy。

## 10. Performance Summary、Smoke限制與Full Validation狀態

- Performance完成樣本：1070；正式Direct Buy完成樣本：0。
- 被拒絕候選整體勝率：44.67%；T+5平均報酬：-0.35%；MFE：4.65%；MAE：-5.07%。
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

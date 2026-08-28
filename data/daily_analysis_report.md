# 盤後選股分析

> 報告狀態：**完成**｜產生時間：2026-08-28 14:23:46（Asia/Taipei）

## 1. 今日結論

**今日無可直接買進標的。**
Raw候選 68 檔；舊路徑退役觀察 0 檔；新假設v2.1預先登記觀察 0 檔。
Full Validation已由使用者暫緩，不會自動執行，也不會耗用七年驗證的Actions額度。
Swing Buy 20D：26 檔合格；依 Extension Momentum 作第二層排序，v4.0 Gate 不變。
Swing Buy 20D：候選池 26；正式 Buy Now 0。正式名單以現價 Forward Entry Edge 為準。
Deep Recovery 3M：3 檔候選；屬早期復甦觀察池，不是BuyNow。

## 2. 資料日期、版本、工具讀取結果、P0安全與歷史來源稽核

- 報告版本：`daily_after_market_report_v5_deep_recovery_3m`
- 產生時間：2026-08-28 14:23:46（Asia/Taipei）
- latest_indicators：2026-08-28 14:23:28
- gate_diagnostics：2026-08-28 14:23:38
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

## 3. 正式Direct Buy結果

**今日無可直接買進標的。**
判定依據：`direct_buy_signal=true`且`direct_buy_blocker=false`的候選為0。

## 3A. Swing Buy 20D（Forward Entry Edge / 現價獲利優先）

核心目標：找『以今天現價買進，未來5～20交易日仍有足夠獲利空間』，不是找最近漲最強的股票。
- v4.0 qualified 只作候選池；Direct Buy真值與v4.0 Gate不變。
- Extension Momentum 降為 15% 輔助；最終正式 Swing 買進名單只接受 `swing_forward_entry_decision=BuyNow`。
- 今日候選池：26；Buy Now：0；Wait Pullback：23；Reject：3。
**今日 Buy Now = 0 檔。寧可沒有標的，也不把已過度延伸的強勢股當成現在可追價。**
**Wait Pullback（股票可強，但現價不是好買點；不列正式買進）**
- 2395 研華｜**Wait Pullback**：現價進場優勢 73.48；剩餘空間 10.0%；Forward RR 2.29；Pullback參考 676.00；原因：forward_entry_edge_score_below_80、traceable_headroom_below_12pct。
- 1504 東元｜**Wait Pullback**：現價進場優勢 72.85；剩餘空間 10.0%；Forward RR 2.31；Pullback參考 71.90；原因：forward_entry_edge_score_below_80、traceable_headroom_below_12pct。
- 3711 日月光投控｜**Wait Pullback**：現價進場優勢 61.68；剩餘空間 10.0%；Forward RR 1.43；Pullback參考 603.50；原因：forward_entry_edge_score_below_80、forward_rr_below_1_8、traceable_headroom_below_12pct。
- 1519 華城｜**Wait Pullback**：現價進場優勢 60.90；剩餘空間 10.0%；Forward RR 1.43；Pullback參考 737.00；原因：entry_quality_below_7、forward_entry_edge_score_below_80、forward_rr_below_1_8、traceable_headroom_below_12pct。
- 3037 欣興｜**Wait Pullback**：現價進場優勢 58.43；剩餘空間 10.0%；Forward RR 1.43；Pullback參考 1103.00；原因：entry_quality_below_7、forward_entry_edge_score_below_80、forward_rr_below_1_8、traceable_headroom_below_12pct。
- 3661 世芯-KY｜**Wait Pullback**：現價進場優勢 57.32；剩餘空間 10.0%；Forward RR 1.43；Pullback參考 4057.50；原因：entry_quality_below_7、forward_entry_edge_score_below_80、forward_rr_below_1_8、traceable_headroom_below_12pct。
- 3583 辛耘｜**Wait Pullback**：現價進場優勢 56.95；剩餘空間 10.0%；Forward RR 1.43；Pullback參考 739.50；原因：forward_entry_edge_score_below_80、forward_rr_below_1_8、traceable_headroom_below_12pct。
- 1301 台塑｜**Wait Pullback**：現價進場優勢 56.55；剩餘空間 10.0%；Forward RR 1.43；Pullback參考 60.35；原因：entry_quality_below_7、forward_entry_edge_score_below_80、forward_rr_below_1_8、traceable_headroom_below_12pct。
- 2408 南亞科｜**Wait Pullback**：現價進場優勢 56.09；剩餘空間 10.0%；Forward RR 1.43；Pullback參考 524.50；原因：entry_quality_below_7、forward_entry_edge_score_below_80、forward_rr_below_1_8、traceable_headroom_below_12pct。
- 9921 巨大｜**Wait Pullback**：現價進場優勢 55.24；剩餘空間 10.0%；Forward RR 1.43；Pullback參考 101.54；原因：forward_entry_edge_score_below_80、forward_rr_below_1_8、traceable_headroom_below_12pct。
- Forward Entry policy：`swing_forward_entry_edge_v1`。
- 驗證狀態：not_evaluable_until_completed_buy_now_30；以每次 BuyNow 當日現價固定為D0，驗證T+20報酬、MFE、勝率與先停損率。

## 3B. Deep Recovery 3M（深度回撤後早期復甦候選池）

本池與 Direct Buy、Swing v4.0、Forward Entry 完全獨立；不改寫任何既有 Gate 或買進真值。
- 核心：近63交易日最高收盤至現價回撤至少30%，且已形成 WeakUp 以上復甦趨勢；drawdown只作資格Gate，不因跌更深加分。
- 分數：向上延伸動能30% + Recovery Trend 25% + RS改善15% + 量能10% + 結構10% + 市場/產業10%。
- 今日 Deep Recovery 3M 正式候選：3 檔；最低候選分 60.0；最低延伸動能 55.0。
- **5425 台半｜Deep Recovery 3M**：現價 96.30；3M最高收盤 144.00；距高點 -33.1%；回前高空間 +49.5%；自低點回升 +43.3%；Recovery ModerateUp；延伸動能 89.0／Strong；RS改善 -17.6；量能 1.51x；候選分 83.70／RecoveryLeading；題材 `semiconductor`；基本面/消息面：待ChatGPT排程即時健康審核。
- **6147 頎邦｜Deep Recovery 3M**：現價 182.50；3M最高收盤 281.00；距高點 -35.1%；回前高空間 +54.0%；自低點回升 +54.0%；Recovery ModerateUp；延伸動能 87.0／Strong；RS改善 -18.8；量能 1.35x；候選分 81.10／RecoveryLeading；題材 `semiconductor`；基本面/消息面：待ChatGPT排程即時健康審核。
- **3131 弘塑｜Deep Recovery 3M**：現價 2485.00；3M最高收盤 3905.00；距高點 -36.4%；回前高空間 +57.1%；自低點回升 +15.3%；Recovery WeakUp；延伸動能 63.0／Moderate；RS改善 7.7；量能 0.95x；候選分 66.40／RecoveryEmerging；題材 `semiconductor`；基本面/消息面：待ChatGPT排程即時健康審核。
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
- Volume通過：102
- PA成功：102
- Raw候選：68
- 正式Direct Buy：0
- 研究退役觀察：0
- 新假設候選：0
- 主要排除原因：
  - Tradeable Second Leg path 未通過：做多方向一致：38檔
  - Tradeable Second Leg path 未通過：型態與分數品質：38檔
  - Tradeable Second Leg path 未通過：進場確認：38檔
  - Tradeable Second Leg path 未通過：合法突破情境：38檔
  - Tradeable Second Leg path 未通過：突破跟隨：38檔
  - Tradeable Second Leg path 未通過：對手方被困：38檔
  - Tradeable Second Leg path 未通過：True Breakout 品質：38檔
  - Tradeable Second Leg path 未通過：可交易第二段：38檔
- Candidate Stage：
  - setup_observation：68

## 8. True Breakout／Follow-through／停損與no-add風險

- True Breakout：
  - Low：90
  - Unknown：17
  - Medium：9
  - High：9
- Follow-through：
  - Poor：98
  - Unknown：17
  - None：4
  - DelayedStrong：3
  - StrongImmediate：2
  - WeakButAcceptable：1
- Second Leg Trap：
  - True：66
  - False：2
- Stop Execution Blocker：
  - False：108
  - Unknown：17
- 候選資料中的no-add guardrail：86檔；停損執行阻擋：0檔。
- no-add=true時，任何pullback zone只可作`observation_only`，不得作買點或加碼點。
- **2887 台新金｜不可買**：階段 `setup_observation`；類型 `tradeable_second_leg`；分數 未載明；RR 2.03；目標 未載明；原因：Tradeable Second Leg path 未通過：做多方向一致 | Tradeable Second Leg path 未通過：型態與分數品質 | Tradeable Second Leg path 未通過：進場確認 | Tradeable Second Leg path 未通過：目標報酬至少 10% | Tradeable Second Leg path 未通過：合法突破情境 | Tradeable Second Leg path 未通過：突破跟隨 | Tradeable Second Leg path 未通過：對手方被困 | Tradeable Second Leg path 未通過：True Breakout 品質 | Tradeable Second Leg path 未通過：可交易第二段
- **5880 合庫金｜不可買**：階段 `setup_observation`；類型 `tradeable_second_leg`；分數 未載明；RR 10.20；目標 未載明；原因：Tradeable Second Leg path 未通過：做多方向一致 | Tradeable Second Leg path 未通過：型態與分數品質 | Tradeable Second Leg path 未通過：進場確認 | Tradeable Second Leg path 未通過：目標報酬至少 10% | Tradeable Second Leg path 未通過：合法突破情境 | Tradeable Second Leg path 未通過：突破跟隨 | Tradeable Second Leg path 未通過：對手方被困 | Tradeable Second Leg path 未通過：True Breakout 品質 | Tradeable Second Leg path 未通過：可交易第二段
- **5871 中租-KY｜不可買**：階段 `setup_observation`；類型 `tradeable_second_leg`；分數 未載明；RR 2.71；目標 未載明；原因：Tradeable Second Leg path 未通過：做多方向一致 | Tradeable Second Leg path 未通過：型態與分數品質 | Tradeable Second Leg path 未通過：進場確認 | Tradeable Second Leg path 未通過：目標報酬至少 10% | Tradeable Second Leg path 未通過：合法突破情境 | Tradeable Second Leg path 未通過：突破跟隨 | Tradeable Second Leg path 未通過：對手方被困 | Tradeable Second Leg path 未通過：True Breakout 品質 | Tradeable Second Leg path 未通過：可交易第二段
- **5425 台半｜不可買**：階段 `setup_observation`；類型 `tradeable_second_leg`；分數 未載明；RR 0.66；目標 未載明；原因：Tradeable Second Leg path 未通過：做多方向一致 | Tradeable Second Leg path 未通過：型態與分數品質 | Tradeable Second Leg path 未通過：進場確認 | Tradeable Second Leg path 未通過：目標報酬至少 10% | Tradeable Second Leg path 未通過：風險報酬比至少 1.5 | Tradeable Second Leg path 未通過：合法突破情境 | Tradeable Second Leg path 未通過：突破跟隨 | Tradeable Second Leg path 未通過：對手方被困 | Tradeable Second Leg path 未通過：True Breakout 品質 | Tradeable Second Leg path 未通過：可交易第二段
- **2891 中信金｜不可買**：階段 `setup_observation`；類型 `confirmed_breakout`；分數 0.00；RR 2.17；目標 12.58%；原因：Confirmed Breakout path 未通過：做多方向一致 | Confirmed Breakout path 未通過：型態與分數品質 | Confirmed Breakout path 未通過：進場確認 | Confirmed Breakout path 未通過：合法突破情境 | Confirmed Breakout path 未通過：突破跟隨 | Confirmed Breakout path 未通過：對手方被困 | Confirmed Breakout path 未通過：突破進場許可 | Confirmed Breakout path 未通過：True Breakout 品質

## 9. 最值得追蹤1～3檔

- **2887 台新金｜不可買**：階段 `setup_observation`；類型 `tradeable_second_leg`；分數 未載明；RR 2.03；目標 未載明；原因：Tradeable Second Leg path 未通過：做多方向一致 | Tradeable Second Leg path 未通過：型態與分數品質 | Tradeable Second Leg path 未通過：進場確認 | Tradeable Second Leg path 未通過：目標報酬至少 10% | Tradeable Second Leg path 未通過：合法突破情境 | Tradeable Second Leg path 未通過：突破跟隨 | Tradeable Second Leg path 未通過：對手方被困 | Tradeable Second Leg path 未通過：True Breakout 品質 | Tradeable Second Leg path 未通過：可交易第二段
- **5880 合庫金｜不可買**：階段 `setup_observation`；類型 `tradeable_second_leg`；分數 未載明；RR 10.20；目標 未載明；原因：Tradeable Second Leg path 未通過：做多方向一致 | Tradeable Second Leg path 未通過：型態與分數品質 | Tradeable Second Leg path 未通過：進場確認 | Tradeable Second Leg path 未通過：目標報酬至少 10% | Tradeable Second Leg path 未通過：合法突破情境 | Tradeable Second Leg path 未通過：突破跟隨 | Tradeable Second Leg path 未通過：對手方被困 | Tradeable Second Leg path 未通過：True Breakout 品質 | Tradeable Second Leg path 未通過：可交易第二段
- **5871 中租-KY｜不可買**：階段 `setup_observation`；類型 `tradeable_second_leg`；分數 未載明；RR 2.71；目標 未載明；原因：Tradeable Second Leg path 未通過：做多方向一致 | Tradeable Second Leg path 未通過：型態與分數品質 | Tradeable Second Leg path 未通過：進場確認 | Tradeable Second Leg path 未通過：目標報酬至少 10% | Tradeable Second Leg path 未通過：合法突破情境 | Tradeable Second Leg path 未通過：突破跟隨 | Tradeable Second Leg path 未通過：對手方被困 | Tradeable Second Leg path 未通過：True Breakout 品質 | Tradeable Second Leg path 未通過：可交易第二段
本節全部是觀察資料，逐檔均為**不可買**，不得替代正式Direct Buy。

## 10. Performance Summary、Smoke限制與Full Validation狀態

- Performance完成樣本：366；正式Direct Buy完成樣本：0。
- 被拒絕候選整體勝率：46.17%；T+5平均報酬：-0.40%；MFE：4.84%；MAE：-5.19%。
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

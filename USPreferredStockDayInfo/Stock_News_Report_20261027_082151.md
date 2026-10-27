# USPreferredStockDayInfo 每日情報報告

- 生成時間（台灣）：2026-10-27 08:21:52
- 對應 PDF：Stock_News_Report_20261027_082151.pdf
- 用途：供 ChatGPT 排程讀取、查證消息、判斷美國特別股/交易所債/REIT 風險預警。

## 使用者查詢範圍

【目標標的】
- NYSE: CTGG,Qwest Corp 6.500% Senior Notes due 2051
- NASDAQ: BHFAL,Brighthouse Financial Junior Subordinated Debentures Exp 2058
- OPI,Office Properties Income Trust
- NYSE: AXS-E，Axis Cap 100 DS Representing 1 Pref Shs Series E
- NYSE: F-B，福特汽車
- UZD,United States Cellular Corporation - 6.25% NT REDEEM 01/09/2069 USD 25

## 逐標的摘要

### 1. CTGG

- 事件總分：正向0 / 負向0 / 總分+0
- 綜合分析：Stage 2 AI 合併未完成；已由程式保留高可信 Stage 1 近期事件，正負面權重相抵。
- 事件 1：2026-10-23｜Lumen Technologies更新高階主管遣散計畫及CEO協議｜recent_event
  - 影響：中性｜嚴重性：1｜信心度：高
  - 摘要：Lumen根據SEC文件更新高階主管遣散計畫並修訂CEO協議，屬內部治理調整。
  - 來源：SEC Filing、Investing.com
  - 日期過濾：kept_recent｜來源品質：sec_filing｜驗證：verified

### 2. BHFAL

- 事件總分：正向0 / 負向1 / 總分-1
- 綜合分析：Stage 2 AI 合併未完成；已由程式保留高可信 Stage 1 近期事件，事件權重偏負面（-1）。
- 事件 1：2026-10-15｜華爾街分析師調整Brighthouse Financial股票評級與目標價｜recent_event
  - 影響：負向｜嚴重性：1｜信心度：中
  - 摘要：KBW維持「持有」並下調目標價至$55；J.P. Morgan上調至「持有」但下調目標價至$55。
  - 來源：S&P Global、TipRanks.com、MarketBeat
  - 日期過濾：kept_recent｜來源品質：rating_agency｜驗證：verified

### 3. OPI

- 事件總分：正向0 / 負向3 / 總分-3
- 綜合分析：Stage 2 AI 合併未完成；已由程式保留高可信 Stage 1 近期事件，事件權重偏負面（-3）。
- 事件 1：2026-10-26｜辦公室REITs面臨逆風，產業表現疲弱｜recent_event
  - 影響：負向｜嚴重性：3｜信心度：高
  - 摘要：辦公室REITs今年迄今平均雙位數負回報，為最弱REIT類型，FFO倍數為7.4倍，為主要REIT類別中最低。
  - 來源：Seeking Alpha
  - 日期過濾：kept_recent｜來源品質：secondary_site｜驗證：unverified
- 事件 2：2026-10-24｜OPI獲「適度買入」評級但內部人士持續賣出｜recent_event
  - 影響：中性｜嚴重性：4｜信心度：中
  - 摘要：OPI獲券商「適度買入」共識評級，目標價27美元具122.8%潛在漲幅；然賣空比率增253.77%且內部人士出售700萬美元股票。
  - 來源：MarketBeat
  - 日期過濾：kept_recent｜來源品質：secondary_site｜驗證：unverified

### 4. AXS-E

- 事件總分：正向3 / 負向0 / 總分+3
- 綜合分析：Stage 2 AI 合併未完成；已由程式保留高可信 Stage 1 近期事件，事件權重偏正面（+3）。
- 事件 1：2026-10-26｜AXIS Capital第三季財報將於本週公布｜recent_event
  - 影響：中性｜嚴重性：4｜信心度：高
  - 摘要：AXIS Capital將於10月28日公布第三季財報，分析師預期每股盈餘為2.82至2.85美元。
  - 來源：AXIS Capital Investor Relations、PRNewswire、Moomoo、MarketBeat、ScanX、TradingView
  - 日期過濾：kept_recent｜來源品質：official_ir｜驗證：verified
- 事件 2：2026-10-15｜AXIS Capital支付Series E優先股季度股息｜recent_event
  - 影響：正向｜嚴重性：3｜信心度：高
  - 摘要：AXIS Capital已於2026年10月15日向Series E優先股股東支付季度股息，每股0.34375美元。
  - 來源：AXIS Capital Investor Relations、GlobeNewswire、Market Chameleon、Slickcharts、Morningstar
  - 日期過濾：kept_recent｜來源品質：official_ir｜驗證：verified

### 5. F-B

- 事件總分：正向2 / 負向10 / 總分-8
- 綜合分析：Stage 2 AI 合併未完成；已由程式保留高可信 Stage 1 近期事件，事件權重偏負面（-8）。
- 事件 1：2026-10-26｜分析師預期福特第三季財報欠佳，營收及每股盈餘預計下降｜recent_event
  - 影響：負向｜嚴重性：3｜信心度：高
  - 摘要：分析師預期福特Q3 EPS及營收年減，Model e虧損、供應鏈問題和美國銷量下滑是主要擔憂。
  - 來源：Zacks.com、MarketBeat
  - 日期過濾：kept_recent｜來源品質：secondary_site｜驗證：unverified
- 事件 2：2026-10-25｜高盛分析師預計福特股價有望上漲｜recent_event
  - 影響：正向｜嚴重性：2｜信心度：中
  - 摘要：高盛分析師表示，預計福特汽車的股價將會上升。
  - 來源：MarketBeat
  - 日期過濾：kept_recent｜來源品質：secondary_site｜驗證：unverified
- 事件 3：2026-10-24｜華爾街調低福特Q3財報預期，可能導致股價意外反彈或確認深層問題｜recent_event
  - 影響：中性｜嚴重性：3｜信心度：高
  - 摘要：華爾街下調福特Q3預期，可能帶來股價反彈機會，但Model e虧損與福特信貸租賃收益問題仍是風險。
  - 來源：24/7 Wall St.、Pluang
  - 日期過濾：kept_recent｜來源品質：unknown｜驗證：unverified
- 事件 4：2026-10-20｜福特因儀表顯示問題召回逾10萬輛F系列卡車｜recent_event
  - 影響：負向｜嚴重性：3｜信心度：高
  - 摘要：福特召回超過10萬輛F系列卡車，因儀表板車速表和轉速表可能失靈。
  - 來源：Seeking Alpha、Stock Titan
  - 日期過濾：kept_recent｜來源品質：secondary_site｜驗證：unverified
- 事件 5：2026-10-19｜UBS調降福特目標價但維持「買入」評級，重申全年自由現金流指引｜recent_event
  - 影響：中性｜嚴重性：2｜信心度：中
  - 摘要：UBS下調福特目標價至15美元，但仍維持買入評級，並重申全年自由現金流指引。
  - 來源：TipRanks.com
  - 日期過濾：kept_recent｜來源品質：secondary_site｜驗證：unverified
- 事件 6：2026-10-14｜福特Q3召回數量巨大，年度保固成本持續高企｜recent_event
  - 影響：負向｜嚴重性：4｜信心度：高
  - 摘要：福特Q3召回190萬輛車，2026年最大召回涉及傳動系統，年度保固成本持續超過40億美元。
  - 來源：Hearn Law Firm、American Lemon Law Group、BizzyCar
  - 日期過濾：kept_recent｜來源品質：unknown｜驗證：unverified

### 6. UZD

- 事件總分：正向0 / 負向0 / 總分+0
- 綜合分析：在指定日期範圍內無可報告的高可信相關事件。
- 事件：無

## 量化指標與資料缺口

- 量化監控框架版本：1.0
- 說明：v1 先建立每檔應追蹤指標與資料缺口；尚未取得官方數值時，會標示為「資料不足」。

### CTGG 量化監控
- Free cash flow｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：FCF 轉負或展望下修需警戒。
- Debt maturity and exchange offer terms｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：distressed exchange、順位弱化或擔保改變需警戒。
- Credit rating / outlook｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：official_reference｜門檻：downgrade、negative outlook 或 selective default 評論需警戒。

### BHFAL 量化監控
- RBC ratio｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：低於 400% 黃燈；低於 350% 橙燈/紅燈；單季大幅下滑需警戒。
- Statutory capital and surplus｜狀態：已取得｜驗證：partially_verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：連續下降或重大減損需警戒。
- Holding company cash and liquid assets｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：低於未來 12 個月利息與固定支出覆蓋需求需警戒。
- Financial leverage｜狀態：資料不足｜驗證：data_missing｜來源品質：unknown｜期間新鮮度：fresh｜門檻：槓桿升高或評等機構負面評論需警戒。
- Credit rating / outlook｜狀態：已取得｜驗證：verified｜來源品質：rating_agency｜期間新鮮度：acceptable_recent｜門檻：negative outlook、downgrade 或 watch negative 需警戒。
- BHFAL interest payment status｜狀態：已取得｜驗證：unverified｜來源品質：secondary_site｜期間新鮮度：fresh｜門檻：defer、suspend、delay、non-payment 立即紅燈。
- Aquarian merger / change-of-control treatment｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：未明確說明 BHFAL 存續、掛牌、贖回或付息條款時列資料不足。
- 資料缺口：2 項，關鍵資料缺漏時不可判定為綠燈。

### OPI 量化監控
- Occupancy rate｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：連續下降或低於同業顯著水準需警戒。
- Debt maturity schedule｜狀態：資料不足｜驗證：data_missing｜來源品質：unknown｜期間新鮮度：unknown_period｜門檻：12-24 個月內大量到期且流動性不足需紅燈。
- Liquidity / cash availability｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：流動性不足或 covenant 壓力需警戒。
- AFFO / FFO｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：AFFO/FFO 大幅下滑或為負需警戒。
- Normalized FFO per common share (Predecessor Period)｜狀態：已取得｜驗證：verified｜來源品質：official_ir｜期間新鮮度：fresh｜門檻：AFFO/FFO 大幅下滑或為負需警戒。
- Total Debt Principal Balance｜狀態：已取得｜驗證：verified｜來源品質：official_ir｜期間新鮮度：fresh｜門檻：12-24 個月內大量到期且流動性不足需紅燈。
- Debt Maturity (Revolver & Term Loan)｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：future_or_invalid_period｜門檻：12-24 個月內大量到期且流動性不足需紅燈。
- Debt Maturity (8.375% Senior Secured Notes)｜狀態：已取得｜驗證：verified｜來源品質：official_ir｜期間新鮮度：future_or_invalid_period｜門檻：12-24 個月內大量到期且流動性不足需紅燈。
- Debt Maturity (10.000% Senior Secured Notes)｜狀態：已取得｜驗證：verified｜來源品質：official_ir｜期間新鮮度：future_or_invalid_period｜門檻：12-24 個月內大量到期且流動性不足需紅燈。
- 資料缺口：1 項，關鍵資料缺漏時不可判定為綠燈。

### AXS-E 量化監控
- Combined ratio｜狀態：已取得｜驗證：verified｜來源品質：official_ir｜期間新鮮度：fresh｜門檻：高於 100% 或明顯惡化需警戒。
- Catastrophe losses｜狀態：資料不足｜驗證：data_missing｜來源品質：unknown｜期間新鮮度：unknown_period｜門檻：重大巨災損失超預期需警戒。
- Preferred dividend status｜狀態：已取得｜驗證：verified｜來源品質：official_ir｜期間新鮮度：fresh｜門檻：defer、suspend、delay 立即紅燈。
- 資料缺口：1 項，關鍵資料缺漏時不可判定為綠燈。

### F-B 量化監控
- Industrial free cash flow｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：official_reference｜門檻：FCF 轉負或全年指引大幅下修需警戒。
- Ford Credit delinquencies / credit losses｜狀態：資料不足｜驗證：data_missing｜來源品質：unknown｜期間新鮮度：unknown_period｜門檻：逾期率或信用損失準備明顯上升需警戒。
- Recall / warranty cost｜狀態：資料不足｜驗證：data_missing｜來源品質：unknown｜期間新鮮度：unknown_period｜門檻：重大召回或保固成本升高需警戒。
- 資料缺口：4 項，關鍵資料缺漏時不可判定為綠燈。

### UZD 量化監控
- Issuer / guarantor status｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：發行人或擔保人不明確時列灰燈/黃燈，不可判定安全。
- Asset sale proceeds and use of funds｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：出售所得若大量分配給股東而非減債需警戒。
- Debt assumption / redemption status｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：未說明承擔、契約修改或贖回時列資料不足。

## 程式端日期過濾與來源驗證

- 日期過濾版本：1.2.2
- 最近事件保留天數：14 天
- 說明：超出最近 14 日但命中 Chapter 11、收購、重整、退市、債務交換等重大關鍵字者，會保留為 background_risk_event；其他舊事件移至 dropped_old_events。

- CTGG：recent=1，background=0，unknown_date=0，dropped_old=0
- BHFAL：recent=1，background=0，unknown_date=0，dropped_old=0
- OPI：recent=2，background=0，unknown_date=0，dropped_old=0
- AXS-E：recent=2，background=0，unknown_date=0，dropped_old=0
- F-B：recent=6，background=0，unknown_date=0，dropped_old=0
- UZD：recent=0，background=0，unknown_date=0，dropped_old=0

## 完整 JSON

```json
[
  {
    "target_name": "CTGG",
    "events": [
      {
        "date": "2026-10-23",
        "title": "Lumen Technologies更新高階主管遣散計畫及CEO協議",
        "impact_direction": "中性",
        "impact_severity": 1,
        "confidence": "高",
        "summary_30": "Lumen根據SEC文件更新高階主管遣散計畫並修訂CEO協議，屬內部治理調整。",
        "links": [
          "SEC Filing",
          "Investing.com"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "sec_filing",
        "event_source_quality_details": [
          "sec_filing"
        ],
        "event_verification_status": "verified",
        "event_days_old": 4,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      }
    ],
    "綜合分析": "Stage 2 AI 合併未完成；已由程式保留高可信 Stage 1 近期事件，正負面權重相抵。",
    "事件總分": "正向0 / 負向0 / 總分+0",
    "new_sources_found": [],
    "event_merge_source": "stage1_deterministic_fallback",
    "excluded_low_trust_event_count": 0,
    "merged_duplicate_event_count": 0,
    "event_dedup_patch_version": "1.3.3",
    "metric_data": [
      {
        "ticker": "CTGG",
        "metric_name": "Free cash flow",
        "metric_category": "現金流",
        "value": "327 million",
        "unit": "USD",
        "period": "2026Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "Lumen Technologies Q2 2026 Earnings Release / SEC 8-K Exhibit 99.1",
        "source_url_or_name": "Lumen Investor Relations / SEC Filing",
        "source_candidates": [
          "Lumen Investor Relations",
          "SEC 10-Q",
          "SEC 10-K",
          "Exchange offer documents",
          "S&P",
          "Moody's",
          "Fitch"
        ],
        "warning_threshold": "FCF 轉負或展望下修需警戒。",
        "priority": "P0",
        "risk_impact": "自由現金流不足會影響長債償付能力。",
        "note": "Lumen 2026Q2 官方資料：Free Cash Flow 為 +$69M；Free Cash Flow excluding Special Items 為 +$327M。本監控沿用既有可比口徑，以 excluding Special Items 的 +$327M 作 canonical FCF。",
        "definition_scope": "Lumen Technologies consolidated",
        "calculation_basis": "Free Cash Flow excluding Special Items",
        "measurement_form": "point",
        "source_quality_primary": "sec_filing",
        "source_quality": "sec_filing",
        "source_quality_details": [
          "sec_filing",
          "official_ir"
        ],
        "source_candidate_quality_details": [
          "sec_filing",
          "official_ir",
          "rating_agency"
        ],
        "source_conflict_flag": false,
        "source_conflict_reason": "",
        "metric_period_parsed_date": "2026-06-30",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "official_lock_applied",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "consistent_same_definition",
        "cross_run_previous_value": "327 million",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20261022",
        "cross_run_previous_definition_scope": "Lumen Technologies consolidated",
        "cross_run_previous_calculation_basis": "Free Cash Flow excluding Special Items",
        "cross_run_consistency_reason": "同 period / definition 與前一可信值一致。",
        "reported_fcf_value": "69 million",
        "reported_fcf_value_numeric": 69000000,
        "value_excluding_special_items": "327 million",
        "value_excluding_special_items_numeric": 327000000,
        "ctgg_fcf_official_lock_applied": true,
        "ctgg_fcf_official_lock_version": "1.3.8",
        "official_source_regression_guard_version": "1.3.8",
        "official_source_regression_guard_status": "official_q2_fcf_canonicalized",
        "official_reference_date": "2026-08-04",
        "official_reference_value": "327 million",
        "official_reference_source": "Lumen Technologies Q2 2026 Earnings Release / SEC 8-K Exhibit 99.1"
      },
      {
        "ticker": "CTGG",
        "metric_name": "Debt maturity and exchange offer terms",
        "metric_category": "債務結構",
        "value": "CTGG 2051年到期高級票據無新發布的困境交換要約或償債條款變更。",
        "unit": "status/date/USD",
        "period": "截至2026年10月27日",
        "status": "已取得",
        "confidence": "高",
        "source": "SEC filings, Lumen Investor Relations",
        "source_url_or_name": "N/A (absence of recent announcements)",
        "source_candidates": [
          "Lumen Investor Relations",
          "SEC 10-Q",
          "SEC 10-K",
          "Exchange offer documents",
          "S&P",
          "Moody's",
          "Fitch"
        ],
        "warning_threshold": "distressed exchange、順位弱化或擔保改變需警戒。",
        "priority": "P0",
        "risk_impact": "可能削弱 CTGG 債權保護。",
        "note": "CTGG票據本身是Qwest Corporation於2026年6月完成的債務交換要約中發行的新票據，票面利率與到期日已確定。公司持續管理債務結構，最近14日內無相關不利更新。",
        "source_quality_primary": "sec_filing",
        "source_quality": "sec_filing",
        "source_quality_details": [
          "sec_filing",
          "official_ir"
        ],
        "source_candidate_quality_details": [
          "sec_filing",
          "official_ir",
          "rating_agency"
        ],
        "source_conflict_flag": false,
        "source_conflict_reason": "",
        "metric_period_parsed_date": "2026-10-27",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "date",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "not_comparable",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "無影響 CTGG 順位之新要約或重大條款變動",
        "cross_run_previous_period": "2026-09",
        "cross_run_previous_report_date": "20260909",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 有前值，但數值型態無法安全比較。"
      },
      {
        "ticker": "CTGG",
        "metric_name": "Credit rating / outlook",
        "metric_category": "信用評等",
        "value": "Qwest senior unsecured: Moody's Caa1 / S&P B / Fitch BB; Lumen senior unsecured: Moody's Caa1 / S&P B / Fitch BB; Lumen corporate/issuer: Moody's CFR B2 (Stable) / Fitch IDR B / S&P issuer B-",
        "unit": "rating",
        "period": "2026Q2 / official references through 2026-08-04",
        "status": "已取得",
        "confidence": "高",
        "source": "Lumen Technologies 2026 Q2 Form 10-Q / Lumen Investor Relations 2026-02-23",
        "source_url_or_name": "SEC Filing / Lumen Investor Relations",
        "source_candidates": [
          "Lumen Investor Relations",
          "SEC 10-Q",
          "SEC 10-K",
          "Exchange offer documents",
          "S&P",
          "Moody's",
          "Fitch"
        ],
        "warning_threshold": "downgrade、negative outlook 或 selective default 評論需警戒。",
        "priority": "P0",
        "risk_impact": "信評變化會影響債券流動性與再融資能力。",
        "note": "Official subject-specific lock: Qwest/Lumen debt ratings and Lumen corporate/issuer ratings are separate measurement subjects and must not be flattened into one agency scalar/outlook.",
        "definition_scope": "Qwest Corporation / Lumen Technologies issuer-chain credit ratings; agency and subject scopes kept separate",
        "calculation_basis": "rating-agency subject-specific issuer / corporate-family / instrument ratings; no scalar cross-agency aggregation",
        "measurement_form": "multi_subject_rating",
        "issuer_scope": "Qwest Corporation / Lumen Technologies issuer-guarantor chain",
        "rating_subjects": [
          {
            "rating_subject": "Qwest Corporation",
            "rating_subject_type": "instrument_rating",
            "rating_instrument_scope": "senior unsecured debt",
            "rating_agency": "Moody's",
            "rating_value": "Caa1",
            "rating_outlook": "",
            "recovery_rating": "",
            "raw_subject_text": "Qwest senior unsecured: Moody's Caa1",
            "ctgg_rating_parser_patch_version": "1.3.8.3.6",
            "subject_evidence_origin": "value",
            "ctgg_rating_evidence_patch_version": "1.3.8.3.6"
          },
          {
            "rating_subject": "Qwest Corporation / Lumen Technologies issuer chain",
            "rating_subject_type": "rating_subject",
            "rating_instrument_scope": "subject-specific; see raw label",
            "rating_agency": "S&P",
            "rating_value": "B",
            "rating_outlook": "",
            "recovery_rating": "",
            "raw_subject_text": "S&P B",
            "ctgg_rating_parser_patch_version": "1.3.8.3.6",
            "subject_evidence_origin": "value",
            "ctgg_rating_evidence_patch_version": "1.3.8.3.6"
          },
          {
            "rating_subject": "Qwest Corporation / Lumen Technologies issuer chain",
            "rating_subject_type": "rating_subject",
            "rating_instrument_scope": "subject-specific; see raw label",
            "rating_agency": "Fitch",
            "rating_value": "BB",
            "rating_outlook": "",
            "recovery_rating": "",
            "raw_subject_text": "Fitch BB",
            "ctgg_rating_parser_patch_version": "1.3.8.3.6",
            "subject_evidence_origin": "value",
            "ctgg_rating_evidence_patch_version": "1.3.8.3.6"
          },
          {
            "rating_subject": "Lumen Technologies",
            "rating_subject_type": "instrument_rating",
            "rating_instrument_scope": "senior unsecured debt",
            "rating_agency": "Moody's",
            "rating_value": "Caa1",
            "rating_outlook": "",
            "recovery_rating": "",
            "raw_subject_text": "Lumen senior unsecured: Moody's Caa1",
            "ctgg_rating_parser_patch_version": "1.3.8.3.6",
            "subject_evidence_origin": "value",
            "ctgg_rating_evidence_patch_version": "1.3.8.3.6"
          },
          {
            "rating_subject": "Lumen Technologies",
            "rating_subject_type": "corporate_family_rating",
            "rating_instrument_scope": "corporate family",
            "rating_agency": "Moody's",
            "rating_value": "B2",
            "rating_outlook": "Stable",
            "recovery_rating": "",
            "raw_subject_text": "Lumen corporate/issuer: Moody's CFR B2 (Stable)",
            "ctgg_rating_parser_patch_version": "1.3.8.3.6",
            "subject_evidence_origin": "value",
            "ctgg_rating_evidence_patch_version": "1.3.8.3.6"
          },
          {
            "rating_subject": "Qwest Corporation / Lumen Technologies issuer chain",
            "rating_subject_type": "issuer_default_rating",
            "rating_instrument_scope": "issuer / long-term IDR",
            "rating_agency": "Fitch",
            "rating_value": "B",
            "rating_outlook": "",
            "recovery_rating": "",
            "raw_subject_text": "Fitch IDR B",
            "ctgg_rating_parser_patch_version": "1.3.8.3.6",
            "subject_evidence_origin": "value",
            "ctgg_rating_evidence_patch_version": "1.3.8.3.6"
          },
          {
            "rating_subject": "Qwest Corporation / Lumen Technologies issuer chain",
            "rating_subject_type": "rating_subject",
            "rating_instrument_scope": "subject-specific; see raw label",
            "rating_agency": "S&P",
            "rating_value": "B-",
            "rating_outlook": "",
            "recovery_rating": "",
            "raw_subject_text": "S&P issuer B-",
            "ctgg_rating_parser_patch_version": "1.3.8.3.6",
            "subject_evidence_origin": "value",
            "ctgg_rating_evidence_patch_version": "1.3.8.3.6"
          },
          {
            "rating_subject": "Qwest Corporation / Lumen Technologies issuer chain",
            "rating_subject_type": "corporate_family_rating",
            "rating_instrument_scope": "corporate family",
            "rating_agency": "Moody's",
            "rating_value": "B2",
            "rating_outlook": "Stable",
            "recovery_rating": "",
            "raw_subject_text": "CFR B2",
            "subject_evidence_origin": "value",
            "ctgg_rating_parser_patch_version": "1.3.8.3.6",
            "ctgg_rating_evidence_patch_version": "1.3.8.3.6"
          }
        ],
        "rating_subject_scope_status": "allowed_ctgg_qwest_lumen_chain",
        "rating_subjects_nonempty_status": "pass",
        "source_quality_primary": "sec_filing",
        "source_quality": "sec_filing",
        "source_quality_details": [
          "sec_filing",
          "official_ir",
          "rating_agency"
        ],
        "source_conflict_flag": false,
        "source_conflict_reason": "",
        "metric_period_parsed_date": "2026-08-04",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "official_reference_date",
        "metric_period_freshness": "official_reference",
        "metric_integrity_status": "official_definition_lock_applied",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "Subject-specific official definitions canonicalized; cross-subject scalar comparison disabled.",
        "cross_run_consistency_status": "not_comparable_multi_subject_rating",
        "cross_run_consistency_reason": "Issuer/CFR/instrument ratings from multiple agencies are subject-scoped and are not reduced to one scalar trend.",
        "metric_origin": "deterministic_official_fallback_v13837",
        "ctgg_rating_official_definition_patch_version": "1.3.8.3.7",
        "ctgg_rating_official_definition_guard_status": "official_subjects_canonicalized",
        "official_reference_filing_date": "2026-08-04",
        "official_reference_period_end": "2026-06-30",
        "official_reference_source": "Lumen Technologies 2026 Q2 Form 10-Q / Lumen Ratings Upgraded by Top 3 Global Ratings Agencies (2026-02-23)",
        "ctgg_rating_parser_patch_version": "1.3.8.3.6",
        "ctgg_rating_evidence_patch_version": "1.3.8.3.6",
        "ctgg_rating_direct_scope_patch_version": "1.3.8.3.6",
        "ctgg_rating_direct_scope_status": "direct_ctgg_rating_structured"
      }
    ],
    "metric_integrity_issues": [],
    "metric_alias_acceptances": [],
    "metric_merge_source": "stage1_deterministic_merge",
    "stage2_resilience_patch_version": "1.3.2",
    "risk_profile": {
      "profile_found": true,
      "risk_profile_version": "1.0",
      "issuer": "Qwest Corporation / Lumen",
      "security_type": "Long-dated exchange-traded senior note",
      "sector": "Telecom",
      "core_risk": "Lumen / Qwest 債務結構、自由現金流、利息覆蓋、交換要約與信評。",
      "required_metric_count": 3,
      "hard_warning_keywords": [
        "exchange offer",
        "distressed exchange",
        "downgrade",
        "negative free cash flow",
        "asset sale",
        "refinancing"
      ]
    },
    "missing_data": [],
    "dropped_old_events": [],
    "event_date_filter_summary": {
      "lookback_days": 14,
      "cutoff_date": "2026-10-14",
      "today": "2026-10-27",
      "kept_recent": 1,
      "kept_background": 0,
      "kept_unknown_date": 0,
      "dropped_old": 0
    },
    "metric_consistency_summary": {
      "conflict_count": 0,
      "conflicts": []
    },
    "ctgg_rating_evidence_enriched_count": 1,
    "ctgg_rating_evidence_patch_version": "1.3.8.3.6",
    "ctgg_rating_direct_scope_patch_version": "1.3.8.3.6",
    "resolved_rating_candidates": [
      {
        "ticker": "CTGG",
        "metric_name": "Credit rating / outlook",
        "rejected_candidate_value": "S&P: B- (展望穩定，2026年3月調整為正面); Moody's: B2 (展望穩定，2026年2月調整); Fitch: B (展望穩定，2026年4月調整)。",
        "rejected_candidate_period": "截至2026年10月27日",
        "rejected_candidate_source": "S&P Global Ratings, Moody's, Fitch Ratings",
        "resolution": "resolved_by_v13837_ctgg_official_definition_guard",
        "reason": "Candidate mixes or leaves ambiguous issuer/CFR/instrument rating definitions; official subject-specific references are canonical.",
        "ctgg_rating_official_definition_patch_version": "1.3.8.3.7"
      }
    ],
    "ctgg_rating_official_definition_patch_version": "1.3.8.3.7",
    "ctgg_rating_official_definition_guard_status": "official_subjects_canonicalized",
    "ctgg_rating_official_definition_rejected_count": 1,
    "ctgg_rating_official_definition_duplicate_removed_count": 0
  },
  {
    "target_name": "BHFAL",
    "events": [
      {
        "date": "2026-10-15",
        "title": "華爾街分析師調整Brighthouse Financial股票評級與目標價",
        "impact_direction": "負向",
        "impact_severity": 1,
        "confidence": "中",
        "summary_30": "KBW維持「持有」並下調目標價至$55；J.P. Morgan上調至「持有」但下調目標價至$55。",
        "links": [
          "S&P Global",
          "TipRanks.com",
          "MarketBeat"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "rating_agency",
        "event_source_quality_details": [
          "rating_agency",
          "secondary_site"
        ],
        "event_verification_status": "verified",
        "event_days_old": 12,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      }
    ],
    "綜合分析": "Stage 2 AI 合併未完成；已由程式保留高可信 Stage 1 近期事件，事件權重偏負面（-1）。",
    "事件總分": "正向0 / 負向1 / 總分-1",
    "new_sources_found": [],
    "event_merge_source": "stage1_deterministic_fallback",
    "excluded_low_trust_event_count": 0,
    "merged_duplicate_event_count": 0,
    "event_dedup_patch_version": "1.3.3",
    "metric_data": [
      {
        "ticker": "BHFAL",
        "metric_name": "RBC ratio",
        "metric_category": "保險償付能力",
        "value": "430%-450%",
        "unit": "%",
        "period": "2026Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "Brighthouse Financial 8-K / Q2 2026 Financial Supplement",
        "source_url_or_name": "SEC Filing",
        "source_candidates": [
          "Brighthouse Financial Investor Relations",
          "SEC 10-Q",
          "SEC 10-K",
          "Earnings Supplement",
          "Statutory filing",
          "AM Best",
          "S&P",
          "Moody's",
          "Fitch"
        ],
        "warning_threshold": "低於 400% 黃燈；低於 350% 橙燈/紅燈；單季大幅下滑需警戒。",
        "priority": "P0",
        "risk_impact": "RBC 下滑可能代表保險子公司資本緩衝下降，影響次順位債付息與信用評等。",
        "note": "截至2026年6月30日之預估綜合風險資本比率，在公司400%-450%的目標範圍內屬較高水平。",
        "definition_scope": "Estimated combined NAIC Risk-Based Capital (RBC) ratio",
        "calculation_basis": "Company estimate for insurance subsidiaries",
        "source_quality_primary": "sec_filing",
        "source_quality": "sec_filing",
        "source_quality_details": [
          "sec_filing"
        ],
        "source_candidate_quality_details": [
          "sec_filing",
          "official_ir",
          "rating_agency"
        ],
        "source_conflict_flag": false,
        "source_conflict_reason": "",
        "metric_period_parsed_date": "2026-06-30",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "verified",
        "measurement_form": "range",
        "source_period_alignment_status": "q2_asof_evidence_present",
        "source_period_evidence": "Brighthouse Financial 8-K / Q2 2026 Financial Supplement | SEC Filing | 截至2026年6月30日之預估綜合風險資本比率，在公司400%-450%的目標範圍內屬較高水平。",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "definition_changed",
        "cross_run_previous_value": "430%-450%",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20261014",
        "cross_run_previous_definition_scope": "Brighthouse insurance subsidiaries (combined)",
        "cross_run_previous_calculation_basis": "NAIC combined risk-based capital ratio",
        "cross_run_consistency_reason": "同 period 有前值，但 definition_scope / calculation_basis 不同，不互相覆寫。"
      },
      {
        "ticker": "BHFAL",
        "metric_name": "Statutory capital and surplus",
        "metric_category": "法定資本",
        "value": "4.9 billion",
        "unit": "USD",
        "period": "2026Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "Brighthouse Financial 8-K / Q2 2026 Financial Supplement",
        "source_url_or_name": "SEC Filing",
        "source_candidates": [
          "Brighthouse Financial Investor Relations",
          "SEC 10-Q",
          "SEC 10-K",
          "Earnings Supplement",
          "Statutory filing",
          "AM Best",
          "S&P",
          "Moody's",
          "Fitch"
        ],
        "warning_threshold": "連續下降或重大減損需警戒。",
        "priority": "P0",
        "risk_impact": "法定資本下降會削弱保險子公司分派能力與控股公司資金來源。",
        "note": "截至2026年6月30日之法定綜合調整後資本，與2026年第一季度持平。",
        "issuer_scope": "Brighthouse Financial, Inc. insurance subsidiaries",
        "source_quality_primary": "sec_filing",
        "source_quality": "sec_filing",
        "source_quality_details": [
          "sec_filing"
        ],
        "source_candidate_quality_details": [
          "sec_filing",
          "official_ir",
          "rating_agency"
        ],
        "source_conflict_flag": false,
        "source_conflict_reason": "",
        "metric_period_parsed_date": "2026-06-30",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "partially_verified",
        "metric_consistency_status": "cross_run_conflict",
        "metric_consistency_reason": "同 period / definition 前值=6.8 billion，本次=4.9 billion；區間不重疊。",
        "cross_run_consistency_status": "value_changed_same_definition",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "6.8 billion",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260818",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 前值=6.8 billion，本次=4.9 billion；區間不重疊。"
      },
      {
        "ticker": "BHFAL",
        "metric_name": "Holding company cash and liquid assets",
        "metric_category": "控股公司流動性",
        "value": "0.9 billion",
        "unit": "USD",
        "period": "2026Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "Brighthouse Financial 8-K / Q2 2026 Financial Supplement",
        "source_url_or_name": "SEC Filing",
        "source_candidates": [
          "Brighthouse Financial Investor Relations",
          "SEC 10-Q",
          "SEC 10-K",
          "Earnings Supplement",
          "Statutory filing",
          "AM Best",
          "S&P",
          "Moody's",
          "Fitch"
        ],
        "warning_threshold": "低於未來 12 個月利息與固定支出覆蓋需求需警戒。",
        "priority": "P0",
        "risk_impact": "控股公司流動性不足可能影響 BHFAL 利息支付。",
        "note": "截至2026年6月30日之控股公司流動資產，保持穩健水平。",
        "issuer_scope": "Brighthouse Financial, Inc. (holding company)",
        "definition_scope": "Holding company liquid assets (cash and cash equivalents, short-term investments and publicly-traded securities, excluding pledged assets)",
        "source_quality_primary": "sec_filing",
        "source_quality": "sec_filing",
        "source_quality_details": [
          "sec_filing"
        ],
        "source_candidate_quality_details": [
          "sec_filing",
          "official_ir",
          "rating_agency"
        ],
        "source_conflict_flag": false,
        "source_conflict_reason": "",
        "metric_period_parsed_date": "2026-06-30",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "verified",
        "calculation_basis": "holding company liquid assets",
        "measurement_form": "point",
        "source_period_alignment_status": "q2_asof_evidence_present",
        "source_period_evidence": "Brighthouse Financial 8-K / Q2 2026 Financial Supplement | SEC Filing | 截至2026年6月30日之控股公司流動資產，保持穩健水平。",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "definition_changed",
        "cross_run_previous_value": "$0.9 billion",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20261013",
        "cross_run_previous_definition_scope": "Holding company liquid assets",
        "cross_run_previous_calculation_basis": "As of June 30, 2026",
        "cross_run_consistency_reason": "同 period 有前值，但 definition_scope / calculation_basis 不同，不互相覆寫。"
      },
      {
        "ticker": "BHFAL",
        "metric_name": "Financial leverage",
        "metric_category": "槓桿",
        "value": null,
        "unit": "%",
        "period": "2026Q2",
        "status": "資料不足",
        "confidence": "低",
        "source": "未取得",
        "source_url_or_name": "",
        "source_candidates": [
          "Brighthouse Financial Investor Relations",
          "SEC 10-Q",
          "SEC 10-K",
          "Earnings Supplement",
          "Statutory filing",
          "AM Best",
          "S&P",
          "Moody's",
          "Fitch"
        ],
        "warning_threshold": "槓桿升高或評等機構負面評論需警戒。",
        "priority": "P1",
        "risk_impact": "槓桿上升會削弱次順位債安全邊際。",
        "note": "在摘要或關鍵資訊中未明確指出2026年第二季度的具體財務槓桿百分比。",
        "rejected_candidate_reason": "摘要未直接提供精確百分比，需查閱完整10-Q報告",
        "source_quality_primary": "unknown",
        "source_quality": "unknown",
        "source_quality_details": [
          "unknown"
        ],
        "source_candidate_quality_details": [
          "sec_filing",
          "official_ir",
          "rating_agency"
        ],
        "source_conflict_flag": true,
        "source_conflict_reason": "只有候選來源含官方資料，實際來源並非官方",
        "metric_period_parsed_date": "2026-06-30",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "data_missing",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "current_missing"
      },
      {
        "ticker": "BHFAL",
        "metric_name": "Credit rating / outlook",
        "metric_category": "信用評等",
        "value": "bbb- / Under Review with Negative Implications",
        "unit": "rating",
        "period": "2026-07-29",
        "status": "已取得",
        "confidence": "高",
        "source": "AM Best 2026-07-29 rating action",
        "source_url_or_name": "AM Best",
        "source_candidates": [
          "Brighthouse Financial Investor Relations",
          "SEC 10-Q",
          "SEC 10-K",
          "Earnings Supplement",
          "Statutory filing",
          "AM Best",
          "S&P",
          "Moody's",
          "Fitch"
        ],
        "warning_threshold": "negative outlook、downgrade 或 watch negative 需警戒。",
        "priority": "P0",
        "risk_impact": "評等惡化可能領先價格與流動性壓力。",
        "note": "AM Best 2026-07-29 維持 Brighthouse 營運子公司 FSR A (Excellent) 與 Long-Term ICR a+ (Excellent) 為 Under Review with Negative Implications；Brighthouse Financial $375M 6.25% junior subordinated debentures due 2058 Long-Term IR 為 bbb-，同樣維持 Under Review with Negative Implications。",
        "issuer_scope": "Brighthouse Financial, Inc. (holding company) 及營運子公司",
        "definition_scope": "Brighthouse Financial 6.25% junior subordinated debentures due 2058",
        "calculation_basis": "AM Best Long-Term Issue Credit Rating / rating-action status",
        "measurement_form": "categorical_rating",
        "source_quality_primary": "rating_agency",
        "source_quality": "rating_agency",
        "source_quality_details": [
          "rating_agency"
        ],
        "source_candidate_quality_details": [
          "sec_filing",
          "official_ir",
          "rating_agency"
        ],
        "source_conflict_flag": false,
        "source_conflict_reason": "",
        "metric_period_parsed_date": "2026-07-29",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "date",
        "metric_period_freshness": "acceptable_recent",
        "metric_integrity_status": "pass",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "consistent_same_definition",
        "cross_run_previous_value": "bbb- / Under Review with Negative Implications",
        "cross_run_previous_period": "2026-07-29",
        "cross_run_previous_report_date": "20261022",
        "cross_run_previous_definition_scope": "Brighthouse Financial 6.25% junior subordinated debentures due 2058",
        "cross_run_previous_calculation_basis": "AM Best Long-Term Issue Credit Rating / rating-action status",
        "cross_run_consistency_reason": "同 period / definition 與前一可信值一致。",
        "official_source_regression_guard_version": "1.3.8",
        "official_source_regression_guard_status": "ambest_latest_action_canonicalized",
        "official_reference_date": "2026-07-29",
        "official_reference_value": "bbb- / Under Review with Negative Implications",
        "official_reference_source": "AM Best 2026-07-29 rating action",
        "ambest_operating_fsr": "A (Excellent)",
        "ambest_operating_icr": "a+ (Excellent)",
        "ambest_issuer_icr": "bbb+ (Good)"
      },
      {
        "ticker": "BHFAL",
        "metric_name": "BHFAL interest payment status",
        "metric_category": "付息狀態",
        "value": "Normal (已於2026年9月15日支付)",
        "unit": "status",
        "period": "2026Q3",
        "status": "已取得",
        "confidence": "高",
        "source": "QuantumOnline.com, FXEmpire, Market Chameleon",
        "source_url_or_name": "QuantumOnline.com",
        "source_candidates": [
          "Brighthouse Financial Investor Relations",
          "SEC 10-Q",
          "SEC 10-K",
          "Earnings Supplement",
          "Statutory filing",
          "AM Best",
          "S&P",
          "Moody's",
          "Fitch"
        ],
        "warning_threshold": "defer、suspend、delay、non-payment 立即紅燈。",
        "priority": "P0",
        "risk_impact": "直接影響退休現金流。",
        "note": "BHFAL按季於3/15、6/15、9/15、12/15支付利息，最近一期已於9月15日正常支付，下一期預計為12月15日。",
        "source_quality_primary": "secondary_site",
        "source_quality": "secondary_site",
        "source_quality_details": [
          "secondary_site"
        ],
        "source_candidate_quality_details": [
          "sec_filing",
          "official_ir",
          "rating_agency"
        ],
        "source_conflict_flag": true,
        "source_conflict_reason": "只有候選來源含官方資料，實際來源並非官方",
        "metric_period_parsed_date": "2026-09-30",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "unverified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "not_comparable",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "正常",
        "cross_run_previous_period": "2026Q3",
        "cross_run_previous_report_date": "20260924",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 有前值，但數值型態無法安全比較。"
      },
      {
        "ticker": "BHFAL",
        "metric_name": "Aquarian merger / change-of-control treatment",
        "metric_category": "交易條款",
        "value": "仍在等待監管機構批准完成",
        "unit": "status",
        "period": "2026Q2 (最新提及)",
        "status": "已取得",
        "confidence": "高",
        "source": "Brighthouse Financial 8-K / Q2 2026 Earnings Release",
        "source_url_or_name": "SEC Filing",
        "source_candidates": [
          "Brighthouse Financial Investor Relations",
          "SEC 10-Q",
          "SEC 10-K",
          "Earnings Supplement",
          "Statutory filing",
          "AM Best",
          "S&P",
          "Moody's",
          "Fitch"
        ],
        "warning_threshold": "未明確說明 BHFAL 存續、掛牌、贖回或付息條款時列資料不足。",
        "priority": "P0",
        "risk_impact": "收購完成後可能影響掛牌、流動性與資本政策。",
        "note": "股東已批准與Aquarian Capital的合併協議，預計2026年完成，但仍需州保險監管機構批准。尚未有明確的BHFAL特定處理條款更新。",
        "rejected_candidate_reason": "無近期關於BHFAL具體條款的新消息，僅為整體合併狀態更新。",
        "source_quality_primary": "sec_filing",
        "source_quality": "sec_filing",
        "source_quality_details": [
          "sec_filing"
        ],
        "source_candidate_quality_details": [
          "sec_filing",
          "official_ir",
          "rating_agency"
        ],
        "source_conflict_flag": false,
        "source_conflict_reason": "",
        "metric_period_parsed_date": "2026-06-30",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "not_comparable",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "待監管機構批准",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260901",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 有前值，但數值型態無法安全比較。"
      }
    ],
    "missing_data": [
      {
        "ticker": "BHFAL",
        "priority": "P1",
        "missing_type": "metric_value",
        "metric_name": "Financial leverage",
        "reason": "Stage 1 已主動搜尋，但尚未取得官方量化數值。",
        "risk_impact": "槓桿上升會削弱次順位債安全邊際。",
        "source_candidates": [
          "Brighthouse Financial Investor Relations",
          "SEC 10-Q",
          "SEC 10-K",
          "Earnings Supplement",
          "Statutory filing",
          "AM Best",
          "S&P",
          "Moody's",
          "Fitch"
        ],
        "acceptance_criteria": "下次報告 metric_data 中 BHFAL / Financial leverage 應填入 value、period、source；若查無官方資料，需明確標示查詢來源與查無原因。"
      },
      {
        "ticker": "BHFAL",
        "priority": "P0",
        "missing_type": "metric_cross_run_consistency",
        "metric_name": "Statutory capital and surplus",
        "reason": "同 period / definition 前值=6.8 billion，本次=4.9 billion；區間不重疊。",
        "risk_impact": "法定資本下降會削弱保險子公司分派能力與控股公司資金來源。",
        "previous_value": "6.8 billion",
        "current_value": "4.9 billion",
        "period": "2026Q2",
        "definition_scope": "",
        "calculation_basis": "",
        "acceptance_criteria": "以同一官方定義重新查核；若為不同口徑，改填不同 definition_scope / calculation_basis，不得覆寫。"
      }
    ],
    "metric_integrity_issues": [],
    "metric_alias_acceptances": [],
    "metric_merge_source": "stage1_deterministic_merge",
    "stage2_resilience_patch_version": "1.3.2",
    "risk_profile": {
      "profile_found": true,
      "risk_profile_version": "1.0",
      "issuer": "Brighthouse Financial",
      "security_type": "Junior Subordinated Debenture",
      "sector": "Life Insurance",
      "core_risk": "保險公司資本適足性、控股公司流動性、收購後次順位債條款與付息能力。",
      "required_metric_count": 7,
      "hard_warning_keywords": [
        "RBC ratio decline",
        "capital deficiency",
        "rating downgrade",
        "interest deferral",
        "change of control",
        "delisting",
        "regulatory approval delay"
      ]
    },
    "dropped_old_events": [],
    "event_date_filter_summary": {
      "lookback_days": 14,
      "cutoff_date": "2026-10-14",
      "today": "2026-10-27",
      "kept_recent": 1,
      "kept_background": 0,
      "kept_unknown_date": 0,
      "dropped_old": 0
    },
    "metric_consistency_summary": {
      "conflict_count": 1,
      "conflicts": [
        {
          "ticker": "BHFAL",
          "metric_name": "Statutory capital and surplus",
          "metric_value": "4.9 billion",
          "missing_reason": "同 period / definition 前值=6.8 billion，本次=4.9 billion；區間不重疊。",
          "verification_after_reconcile": "partially_verified",
          "cross_run_consistency_status": "value_changed_same_definition",
          "definition_scope": "",
          "calculation_basis": ""
        }
      ]
    },
    "market_quote": {
      "ticker": "BHFAL",
      "security_name_expected": "Brighthouse Financial 6.25% Junior Subordinated Debentures due 2058",
      "exchange_expected": "NASDAQ",
      "latest_price": 14.96,
      "price_as_of": "2026-10-26",
      "open": 15.050000190734863,
      "high": 15.139399528503418,
      "low": 14.814200401306152,
      "volume": 25402,
      "bid": null,
      "ask": null,
      "annual_interest": 1.5625,
      "current_yield": 10.4445,
      "quote_source": "Yahoo Finance chart (query1.finance.yahoo.com)",
      "source_host": "query1.finance.yahoo.com",
      "quote_status": "ok",
      "freshness_status": "fresh",
      "security_identity_status": "matched_symbol",
      "source_timestamp": 1793021400,
      "market_quote_patch_version": "1.3.7",
      "returned_symbol": "BHFAL",
      "currency": "USD",
      "exchange_name": "NMS",
      "instrument_type": "EQUITY",
      "regular_market_price_meta": 14.96,
      "regular_market_time_meta": 1793044800,
      "reference_session_date": "2026-10-26",
      "weekday_gap": 0,
      "http_status": 200,
      "request_url": "https://query1.finance.yahoo.com/v8/finance/chart/BHFAL",
      "request_attempt": 1,
      "attempts": [
        {
          "source_host": "query1.finance.yahoo.com",
          "quote_status": "ok",
          "freshness_status": "fresh",
          "price_as_of": "2026-10-26",
          "latest_price": 14.96,
          "error": null
        },
        {
          "source_host": "query2.finance.yahoo.com",
          "quote_status": "ok",
          "freshness_status": "fresh",
          "price_as_of": "2026-10-26",
          "latest_price": 14.96,
          "error": null
        }
      ],
      "source_validation": "cross_checked",
      "source_crosscheck_price": 14.96,
      "source_crosscheck_host": "query2.finance.yahoo.com",
      "source_conflict_pct": 0.0
    }
  },
  {
    "target_name": "OPI",
    "events": [
      {
        "date": "2026-10-26",
        "title": "辦公室REITs面臨逆風，產業表現疲弱",
        "impact_direction": "負向",
        "impact_severity": 3,
        "confidence": "高",
        "summary_30": "辦公室REITs今年迄今平均雙位數負回報，為最弱REIT類型，FFO倍數為7.4倍，為主要REIT類別中最低。",
        "links": [
          "Seeking Alpha"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "secondary_site",
        "event_source_quality_details": [
          "secondary_site"
        ],
        "event_verification_status": "unverified",
        "event_days_old": 1,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      },
      {
        "date": "2026-10-24",
        "title": "OPI獲「適度買入」評級但內部人士持續賣出",
        "impact_direction": "中性",
        "impact_severity": 4,
        "confidence": "中",
        "summary_30": "OPI獲券商「適度買入」共識評級，目標價27美元具122.8%潛在漲幅；然賣空比率增253.77%且內部人士出售700萬美元股票。",
        "links": [
          "MarketBeat"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "secondary_site",
        "event_source_quality_details": [
          "secondary_site"
        ],
        "event_verification_status": "unverified",
        "event_days_old": 3,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      }
    ],
    "綜合分析": "Stage 2 AI 合併未完成；已由程式保留高可信 Stage 1 近期事件，事件權重偏負面（-3）。",
    "事件總分": "正向0 / 負向3 / 總分-3",
    "new_sources_found": [],
    "event_merge_source": "stage1_deterministic_fallback",
    "excluded_low_trust_event_count": 0,
    "merged_duplicate_event_count": 0,
    "event_dedup_patch_version": "1.3.3",
    "metric_data": [
      {
        "ticker": "OPI",
        "metric_name": "Occupancy rate",
        "metric_category": "出租率",
        "value": "All Properties 77.9%; Comparable Properties 88.7%",
        "unit": "%",
        "period": "2026-06-30",
        "status": "已取得",
        "confidence": "高",
        "source": "Office Properties Income Trust 2026 Q2 Form 10-Q",
        "source_url_or_name": "SEC Filing",
        "source_candidates": [
          "OPI Investor Relations",
          "SEC 10-Q",
          "SEC 10-K",
          "Earnings Supplement",
          "Bankruptcy court docket"
        ],
        "warning_threshold": "連續下降或低於同業顯著水準需警戒。",
        "priority": "P0",
        "risk_impact": "出租率下降會影響 NOI、AFFO 與償債能力。",
        "note": "量化監控框架 v1.2 已嘗試由 Stage 1 搜尋此指標；仍未取得官方數值。",
        "source_quality_primary": "sec_filing",
        "source_quality": "sec_filing",
        "source_quality_details": [
          "sec_filing"
        ],
        "source_candidate_quality_details": [
          "sec_filing",
          "official_ir",
          "court_docket"
        ],
        "source_conflict_flag": false,
        "source_conflict_reason": "",
        "metric_period_parsed_date": "2026-06-30",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "date_with_portfolio_scope_split",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "official_definition_lock_applied",
        "metric_verification_status": "verified",
        "metric_consistency_status": "not_comparable_scope_split",
        "metric_consistency_reason": "77.9%=All Properties；88.7%=Comparable Properties，兩者 scope 不同，不得視為同 definition 變動。",
        "cross_run_consistency_status": "not_comparable_scope_split",
        "definition_scope": "Percent leased; All Properties and Comparable Properties presented as separate portfolio scopes",
        "calculation_basis": "SEC 10-Q occupancy table as of June 30, 2026",
        "measurement_form": "multi_scope_percentage",
        "unit_scale": "percentage points",
        "metric_origin": "deterministic_official_fallback_v13833",
        "opi_official_floor_applied": true,
        "opi_official_floor_patch_version": "1.3.8.3.3",
        "official_reference_date": "2026-08-06",
        "official_reference_source": "Office Properties Income Trust 2026 Q2 Form 10-Q",
        "accounting_entity_period": "As of 2026-06-30; portfolio-scope split, not a Successor/Predecessor time split",
        "scope_values": {
          "all_properties_pct": 77.9,
          "comparable_properties_pct": 88.7
        },
        "cross_run_consistency_reason": "All Properties and Comparable Properties are distinct portfolio scopes.",
        "opi_definition_guard_applied": true,
        "opi_definition_guard_patch_version": "1.3.8.3",
        "opi_definition_guard_status": "official_q2_occupancy_scope_split_canonicalized",
        "cross_run_previous_value": null,
        "cross_run_previous_period": null,
        "cross_run_previous_report_date": null,
        "cross_run_previous_definition_scope": null,
        "cross_run_previous_calculation_basis": null
      },
      {
        "ticker": "OPI",
        "metric_name": "Debt maturity schedule",
        "metric_category": "債務到期牆",
        "value": null,
        "unit": "USD/date",
        "period": "latest",
        "status": "資料不足",
        "confidence": "低",
        "source": "未取得",
        "source_url_or_name": "",
        "source_candidates": [
          "OPI Investor Relations",
          "SEC 10-Q",
          "SEC 10-K",
          "Earnings Supplement",
          "Bankruptcy court docket"
        ],
        "warning_threshold": "12-24 個月內大量到期且流動性不足需紅燈。",
        "priority": "P0",
        "risk_impact": "再融資失敗可能導致重整或資產賤售。",
        "note": "量化監控框架 v1.2 已嘗試由 Stage 1 搜尋此指標；仍未取得官方數值。",
        "source_quality_primary": "unknown",
        "source_quality": "unknown",
        "source_quality_details": [
          "unknown"
        ],
        "source_candidate_quality_details": [
          "sec_filing",
          "official_ir",
          "court_docket"
        ],
        "source_conflict_flag": true,
        "source_conflict_reason": "只有候選來源含官方資料，實際來源並非官方",
        "metric_period_parsed_date": null,
        "metric_period_parse_status": "unknown",
        "metric_period_type": "unknown",
        "metric_period_freshness": "unknown_period",
        "metric_integrity_status": "pass",
        "metric_verification_status": "data_missing",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "current_missing"
      },
      {
        "ticker": "OPI",
        "metric_name": "Liquidity / cash availability",
        "metric_category": "流動性",
        "value": "Cash and cash equivalents $50.751M; restricted cash $54.038M; total $104.789M",
        "unit": "USD",
        "period": "As of 2026-06-30",
        "status": "已取得",
        "confidence": "高",
        "source": "Office Properties Income Trust 2026 Q2 Form 10-Q",
        "source_url_or_name": "SEC Filing",
        "source_candidates": [
          "OPI Investor Relations",
          "SEC 10-Q",
          "SEC 10-K",
          "Earnings Supplement",
          "Bankruptcy court docket"
        ],
        "warning_threshold": "流動性不足或 covenant 壓力需警戒。",
        "priority": "P0",
        "risk_impact": "直接影響償債與營運彈性。",
        "note": "現金及約當現金餘額。",
        "definition_scope": "OPI cash, cash equivalents and restricted cash",
        "measurement_form": "multi_component_cash_balance",
        "source_quality_primary": "sec_filing",
        "source_quality": "sec_filing",
        "source_quality_details": [
          "sec_filing"
        ],
        "source_candidate_quality_details": [
          "sec_filing",
          "official_ir",
          "court_docket"
        ],
        "source_conflict_flag": false,
        "source_conflict_reason": "",
        "metric_period_parsed_date": "2026-06-30",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "date_with_cash_components",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "not_comparable_official_floor",
        "calculation_basis": "SEC 10-Q supplemental disclosure of cash and restricted cash",
        "cross_run_previous_value": null,
        "cross_run_previous_period": null,
        "cross_run_previous_report_date": null,
        "cross_run_previous_definition_scope": null,
        "cross_run_previous_calculation_basis": null,
        "cross_run_consistency_reason": "Cash and restricted-cash components are preserved as a structured official balance.",
        "unit_scale": "USD millions",
        "metric_origin": "deterministic_official_fallback_v13833",
        "opi_official_floor_applied": true,
        "opi_official_floor_patch_version": "1.3.8.3.3",
        "official_reference_date": "2026-08-06",
        "official_reference_source": "Office Properties Income Trust 2026 Q2 Form 10-Q",
        "scope_values": {
          "cash_and_cash_equivalents_usd": 50751000,
          "restricted_cash_usd": 54038000,
          "total_cash_and_restricted_cash_usd": 104789000
        }
      },
      {
        "ticker": "OPI",
        "metric_name": "AFFO / FFO",
        "metric_category": "現金流",
        "value": "Successor Normalized FFO=$4.494M ($0.20/share); Predecessor Normalized FFO=$15.118M ($0.21/share)",
        "unit": "USD million / USD per common share",
        "period": "2026Q2 split: Successor 2026-06-18..2026-06-30; Predecessor 2026-04-01..2026-06-17",
        "status": "已取得",
        "confidence": "高",
        "source": "Office Properties Income Trust 2026 Q2 Form 10-Q",
        "source_url_or_name": "SEC Filing",
        "warning_threshold": "AFFO/FFO 大幅下滑或為負需警戒。",
        "priority": "P0",
        "risk_impact": "REIT 配息與債務服務能力核心指標。",
        "note": "此為重整前之Normalized FFO總額，期間為2026年4月1日至6月17日。",
        "accounting_entity_period": [
          {
            "accounting_entity": "Successor",
            "period_start": "2026-06-18",
            "period_end": "2026-06-30",
            "normalized_ffo_amount_usd": 4494000,
            "normalized_ffo_per_share_usd": 0.2
          },
          {
            "accounting_entity": "Predecessor",
            "period_start": "2026-04-01",
            "period_end": "2026-06-17",
            "normalized_ffo_amount_usd": 15118000,
            "normalized_ffo_per_share_usd": 0.21
          }
        ],
        "measurement_form": "split_period_amount_and_per_share",
        "definition_scope": "OPI Normalized FFO; Successor and Predecessor periods presented separately",
        "unit_scale": "amount=USD millions (10-Q table presented in thousands); per_share=USD/common share",
        "metric_origin": "deterministic_official_fallback_v13833",
        "metric_integrity_status": "official_definition_lock_applied",
        "source_quality_primary": "sec_filing",
        "source_quality": "sec_filing",
        "source_quality_details": [
          "sec_filing"
        ],
        "source_candidate_quality_details": [
          "unknown"
        ],
        "source_conflict_flag": false,
        "source_conflict_reason": "",
        "metric_period_parsed_date": "2026-06-30",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "quarter_split_accounting_periods",
        "metric_period_freshness": "fresh",
        "metric_verification_status": "verified",
        "metric_consistency_status": "not_comparable_split_definition",
        "metric_consistency_reason": "Successor/Predecessor 與 amount/per-share 必須分開，不做單一 scalar cross-run 比較。",
        "cross_run_consistency_status": "not_comparable_split_definition",
        "calculation_basis": "SEC 10-Q FFO and Normalized FFO reconciliation; amount and per-share measures kept separate",
        "opi_official_floor_applied": true,
        "opi_official_floor_patch_version": "1.3.8.3.3",
        "official_reference_date": "2026-08-06",
        "official_reference_source": "Office Properties Income Trust 2026 Q2 Form 10-Q",
        "cross_run_consistency_reason": "OPI 2026Q2 bankruptcy emergence creates separate Successor/Predecessor accounting periods; scalar comparison is prohibited.",
        "opi_definition_guard_applied": true,
        "opi_definition_guard_patch_version": "1.3.8.3",
        "opi_definition_guard_status": "official_q2_normalized_ffo_split_canonicalized",
        "cross_run_previous_value": null,
        "cross_run_previous_period": null,
        "cross_run_previous_report_date": null,
        "cross_run_previous_definition_scope": null,
        "cross_run_previous_calculation_basis": null
      },
      {
        "ticker": "OPI",
        "metric_name": "Normalized FFO per common share (Predecessor Period)",
        "metric_category": "現金流",
        "value": "0.21",
        "unit": "USD",
        "period": "2026-04-01 to 2026-06-17",
        "status": "已取得",
        "confidence": "高",
        "source": "OPI Q2 2026 Investor Presentation",
        "source_url_or_name": "OPI Investor Relations",
        "warning_threshold": "AFFO/FFO 大幅下滑或為負需警戒。",
        "priority": "P0",
        "risk_impact": "REIT 配息與債務服務能力核心指標。",
        "note": "此為重整前之Normalized FFO每股金額，期間為2026年4月1日至6月17日。",
        "accounting_entity_period": "Predecessor (2026Q2 part)",
        "measurement_form": "Scalar",
        "definition_scope": "Normalized FFO per common share",
        "unit_scale": "USD",
        "metric_origin": "stage1_deterministic_merge",
        "metric_integrity_status": "selected_from_stage1",
        "source_quality_primary": "official_ir",
        "source_quality": "official_ir",
        "source_quality_details": [
          "official_ir"
        ],
        "source_candidate_quality_details": [
          "unknown"
        ],
        "source_conflict_flag": false,
        "source_conflict_reason": "",
        "metric_period_parsed_date": "2026-06-17",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "date",
        "metric_period_freshness": "fresh",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "no_prior_same_period",
        "calculation_basis": ""
      },
      {
        "ticker": "OPI",
        "metric_name": "Total Debt Principal Balance",
        "metric_category": "債務到期牆",
        "value": "1707320000",
        "unit": "USD",
        "period": "2026-06-30",
        "status": "已取得",
        "confidence": "高",
        "source": "OPI Q2 2026 Investor Presentation",
        "source_url_or_name": "OPI Investor Relations",
        "warning_threshold": "12-24 個月內大量到期且流動性不足需紅燈。",
        "priority": "P0",
        "risk_impact": "再融資失敗可能導致重整或資產賤售。",
        "note": "此為重整後總債務本金餘額。",
        "accounting_entity_period": "2026Q2",
        "measurement_form": "Scalar",
        "definition_scope": "Total Debt Principal Balance",
        "unit_scale": "USD",
        "metric_origin": "stage1_deterministic_merge",
        "metric_integrity_status": "selected_from_stage1",
        "source_quality_primary": "official_ir",
        "source_quality": "official_ir",
        "source_quality_details": [
          "official_ir"
        ],
        "source_candidate_quality_details": [
          "unknown"
        ],
        "source_conflict_flag": false,
        "source_conflict_reason": "",
        "metric_period_parsed_date": "2026-06-30",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "date",
        "metric_period_freshness": "fresh",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "no_prior_same_period",
        "calculation_basis": ""
      },
      {
        "ticker": "OPI",
        "metric_name": "Debt Maturity (Revolver & Term Loan)",
        "metric_category": "債務到期牆",
        "value": "已於2026年9月通過新票據發行償還",
        "unit": "USD/date",
        "period": "2027-01-29 (原到期日)",
        "status": "已取得",
        "confidence": "高",
        "source": "SEC Filing (8-K, Sep 10, 2026)",
        "source_url_or_name": "SEC Filing",
        "warning_threshold": "12-24 個月內大量到期且流動性不足需紅燈。",
        "priority": "P0",
        "risk_impact": "再融資失敗可能導致重整或資產賤售。",
        "note": "原定於2027年1月到期的循環信用額度及定期貸款，已透過2026年9月發行的4.25億美元高級擔保票據的收益償還。",
        "accounting_entity_period": "2026Q2 / 2026Q3",
        "measurement_form": "Qualitative with Amount",
        "definition_scope": "Secured revolving credit facility and secured term loan maturity",
        "unit_scale": "USD/Date",
        "metric_origin": "stage1_deterministic_merge",
        "metric_integrity_status": "selected_from_stage1",
        "source_quality_primary": "sec_filing",
        "source_quality": "sec_filing",
        "source_quality_details": [
          "sec_filing"
        ],
        "source_candidate_quality_details": [
          "unknown"
        ],
        "source_conflict_flag": false,
        "source_conflict_reason": "",
        "metric_period_parsed_date": "2027-01-29",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "date",
        "metric_period_freshness": "future_or_invalid_period",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "no_prior_same_period",
        "calculation_basis": ""
      },
      {
        "ticker": "OPI",
        "metric_name": "Debt Maturity (8.375% Senior Secured Notes)",
        "metric_category": "債務到期牆",
        "value": "385000000",
        "unit": "USD",
        "period": "2029-12-31",
        "status": "已取得",
        "confidence": "高",
        "source": "OPI Q2 2026 Investor Presentation",
        "source_url_or_name": "OPI Investor Relations",
        "warning_threshold": "12-24 個月內大量到期且流動性不足需紅燈。",
        "priority": "P0",
        "risk_impact": "再融資失敗可能導致重整或資產賤售。",
        "note": "2026年支付2000萬美元，2027年3000萬美元，2028年4500萬美元，2029年4500萬美元，餘額於到期日支付。",
        "accounting_entity_period": "2026Q2",
        "measurement_form": "Scalar",
        "definition_scope": "8.375% Senior Secured Notes due December 2029",
        "unit_scale": "USD",
        "metric_origin": "stage1_deterministic_merge",
        "metric_integrity_status": "selected_from_stage1",
        "source_quality_primary": "official_ir",
        "source_quality": "official_ir",
        "source_quality_details": [
          "official_ir"
        ],
        "source_candidate_quality_details": [
          "unknown"
        ],
        "source_conflict_flag": false,
        "source_conflict_reason": "",
        "metric_period_parsed_date": "2029-12-31",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "date",
        "metric_period_freshness": "future_or_invalid_period",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "no_prior_same_period",
        "calculation_basis": ""
      },
      {
        "ticker": "OPI",
        "metric_name": "Debt Maturity (10.000% Senior Secured Notes)",
        "metric_category": "債務到期牆",
        "value": "420000000",
        "unit": "USD",
        "period": "2031-06-17",
        "status": "已取得",
        "confidence": "高",
        "source": "OPI Q2 2026 Investor Presentation",
        "source_url_or_name": "OPI Investor Relations",
        "warning_threshold": "12-24 個月內大量到期且流動性不足需紅燈。",
        "priority": "P0",
        "risk_impact": "再融資失敗可能導致重整或資產賤售。",
        "note": "這是重整後發行的新票據。",
        "accounting_entity_period": "2026Q2",
        "measurement_form": "Scalar",
        "definition_scope": "10.000% Senior Secured Notes due June 2031",
        "unit_scale": "USD",
        "metric_origin": "stage1_deterministic_merge",
        "metric_integrity_status": "selected_from_stage1",
        "source_quality_primary": "official_ir",
        "source_quality": "official_ir",
        "source_quality_details": [
          "official_ir"
        ],
        "source_candidate_quality_details": [
          "unknown"
        ],
        "source_conflict_flag": false,
        "source_conflict_reason": "",
        "metric_period_parsed_date": "2031-06-17",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "date",
        "metric_period_freshness": "future_or_invalid_period",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "no_prior_same_period",
        "calculation_basis": ""
      }
    ],
    "metric_integrity_issues": [],
    "metric_alias_acceptances": [],
    "metric_merge_source": "stage1_deterministic_merge",
    "stage2_resilience_patch_version": "1.3.2",
    "risk_profile": {
      "profile_found": true,
      "risk_profile_version": "1.0",
      "issuer": "Office Properties Income Trust",
      "security_type": "Office REIT / Post-reorganization equity",
      "sector": "Office REIT",
      "core_risk": "重整後辦公室 REIT 的 AFFO、出租率、債務到期與再融資壓力。",
      "required_metric_count": 4,
      "hard_warning_keywords": [
        "Chapter 11",
        "AFFO decline",
        "occupancy decline",
        "liquidity",
        "debt maturity",
        "dividend suspension"
      ]
    },
    "missing_data": [
      {
        "ticker": "OPI",
        "priority": "P0",
        "missing_type": "metric_value",
        "metric_name": "Debt maturity schedule",
        "reason": "Stage 1 已主動搜尋，但尚未取得官方量化數值。",
        "risk_impact": "再融資失敗可能導致重整或資產賤售。",
        "source_candidates": [
          "OPI Investor Relations",
          "SEC 10-Q",
          "SEC 10-K",
          "Earnings Supplement",
          "Bankruptcy court docket"
        ],
        "acceptance_criteria": "下次報告 metric_data 中 OPI / Debt maturity schedule 應填入 value、period、source；若查無官方資料，需明確標示查詢來源與查無原因。"
      }
    ],
    "dropped_old_events": [],
    "event_date_filter_summary": {
      "lookback_days": 14,
      "cutoff_date": "2026-10-14",
      "today": "2026-10-27",
      "kept_recent": 2,
      "kept_background": 0,
      "kept_unknown_date": 0,
      "dropped_old": 0
    },
    "metric_consistency_summary": {
      "conflict_count": 0,
      "conflicts": []
    },
    "resolved_missing_data": [
      {
        "ticker": "OPI",
        "priority": "P0",
        "missing_type": "metric_value",
        "metric_name": "AFFO / FFO",
        "reason": "Stage 1 已主動搜尋，但尚未取得官方量化數值。",
        "risk_impact": "REIT 配息與債務服務能力核心指標。",
        "source_candidates": [
          "OPI Investor Relations",
          "SEC 10-Q",
          "SEC 10-K",
          "Earnings Supplement",
          "Bankruptcy court docket"
        ],
        "acceptance_criteria": "下次報告 metric_data 中 OPI / AFFO / FFO 應填入 value、period、source；若查無官方資料，需明確標示查詢來源與查無原因。",
        "resolution": "resolved_by_v13831_opi_summary_reconciliation",
        "opi_summary_reconciliation_patch_version": "1.3.8.3.1"
      },
      {
        "ticker": "OPI",
        "priority": "P0",
        "missing_type": "metric_value",
        "metric_name": "Occupancy rate",
        "reason": "Stage 1 已主動搜尋，但尚未取得官方量化數值。",
        "risk_impact": "出租率下降會影響 NOI、AFFO 與償債能力。",
        "source_candidates": [
          "OPI Investor Relations",
          "SEC 10-Q",
          "SEC 10-K",
          "Earnings Supplement",
          "Bankruptcy court docket"
        ],
        "acceptance_criteria": "下次報告 metric_data 中 OPI / Occupancy rate 應填入 value、period、source；若查無官方資料，需明確標示查詢來源與查無原因。",
        "resolution": "resolved_by_v13833_opi_sec_deterministic_floor",
        "opi_official_floor_patch_version": "1.3.8.3.3"
      }
    ],
    "opi_definition_guard_applied_count": 2,
    "opi_definition_guard_patch_version": "1.3.8.3",
    "resolved_metric_placeholders": [
      {
        "ticker": "OPI",
        "metric_name": "AFFO / FFO",
        "metric_category": "現金流",
        "value": null,
        "unit": "USD",
        "period": "latest",
        "status": "資料不足",
        "confidence": "低",
        "source": "未取得",
        "source_url_or_name": "",
        "source_candidates": [
          "OPI Investor Relations",
          "SEC 10-Q",
          "SEC 10-K",
          "Earnings Supplement",
          "Bankruptcy court docket"
        ],
        "warning_threshold": "AFFO/FFO 大幅下滑或為負需警戒。",
        "priority": "P0",
        "risk_impact": "REIT 配息與債務服務能力核心指標。",
        "note": "量化監控框架 v1.2 已嘗試由 Stage 1 搜尋此指標；仍未取得官方數值。",
        "source_quality_primary": "unknown",
        "source_quality": "unknown",
        "source_quality_details": [
          "unknown"
        ],
        "source_candidate_quality_details": [
          "sec_filing",
          "official_ir",
          "court_docket"
        ],
        "source_conflict_flag": true,
        "source_conflict_reason": "只有候選來源含官方資料，實際來源並非官方",
        "metric_period_parsed_date": null,
        "metric_period_parse_status": "unknown",
        "metric_period_type": "unknown",
        "metric_period_freshness": "unknown_period",
        "metric_integrity_status": "pass",
        "metric_verification_status": "data_missing",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "current_missing",
        "resolution": "resolved_by_v13831_opi_summary_reconciliation",
        "opi_summary_reconciliation_patch_version": "1.3.8.3.1"
      }
    ],
    "opi_summary_reconciliation_patch_version": "1.3.8.3.1",
    "opi_affo_placeholder_removed_count": 0,
    "opi_affo_missing_resolved_count": 0,
    "resolved_metric_duplicates": [
      {
        "ticker": "OPI",
        "metric_name": "AFFO / FFO",
        "metric_key": "affoffo",
        "resolution": "resolved_by_v13832_opi_structured_dedup",
        "duplicate_count_removed": 1,
        "opi_structured_cleanup_patch_version": "1.3.8.3.2"
      },
      {
        "ticker": "OPI",
        "metric_name": "Occupancy rate",
        "metric_key": "occupancy",
        "resolution": "resolved_by_v13832_opi_structured_dedup",
        "duplicate_count_removed": 1,
        "opi_structured_cleanup_patch_version": "1.3.8.3.2"
      }
    ],
    "opi_structured_cleanup_patch_version": "1.3.8.3.2",
    "opi_structured_duplicate_removed_count": 2,
    "opi_official_floor_resolved_missing_count": 1,
    "opi_official_floor_applied_count": 3,
    "opi_official_floor_active_keys": [
      "affoffo",
      "liquidity",
      "occupancy"
    ],
    "opi_official_floor_patch_version": "1.3.8.3.3"
  },
  {
    "target_name": "AXS-E",
    "events": [
      {
        "date": "2026-10-26",
        "title": "AXIS Capital第三季財報將於本週公布",
        "impact_direction": "中性",
        "impact_severity": 4,
        "confidence": "高",
        "summary_30": "AXIS Capital將於10月28日公布第三季財報，分析師預期每股盈餘為2.82至2.85美元。",
        "links": [
          "AXIS Capital Investor Relations",
          "PRNewswire",
          "Moomoo",
          "MarketBeat",
          "ScanX",
          "TradingView"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "official_ir",
        "event_source_quality_details": [
          "official_ir",
          "press_release",
          "secondary_site"
        ],
        "event_verification_status": "verified",
        "event_days_old": 1,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      },
      {
        "date": "2026-10-15",
        "title": "AXIS Capital支付Series E優先股季度股息",
        "impact_direction": "正向",
        "impact_severity": 3,
        "confidence": "高",
        "summary_30": "AXIS Capital已於2026年10月15日向Series E優先股股東支付季度股息，每股0.34375美元。",
        "links": [
          "AXIS Capital Investor Relations",
          "GlobeNewswire",
          "Market Chameleon",
          "Slickcharts",
          "Morningstar"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "official_ir",
        "event_source_quality_details": [
          "official_ir",
          "press_release",
          "secondary_site"
        ],
        "event_verification_status": "verified",
        "event_days_old": 12,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      }
    ],
    "綜合分析": "Stage 2 AI 合併未完成；已由程式保留高可信 Stage 1 近期事件，事件權重偏正面（+3）。",
    "事件總分": "正向3 / 負向0 / 總分+3",
    "new_sources_found": [],
    "event_merge_source": "stage1_deterministic_fallback",
    "excluded_low_trust_event_count": 0,
    "merged_duplicate_event_count": 0,
    "event_dedup_patch_version": "1.3.3",
    "metric_data": [
      {
        "ticker": "AXS-E",
        "metric_name": "Combined ratio",
        "metric_category": "承保獲利",
        "value": "93.1%",
        "unit": "%",
        "period": "2026Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "AXIS Capital Q2 2026 Earnings Release",
        "source_url_or_name": "AXIS Capital Investor Relations",
        "source_candidates": [
          "AXIS Investor Relations",
          "SEC 10-Q",
          "SEC 10-K",
          "Earnings Release",
          "AM Best",
          "S&P"
        ],
        "warning_threshold": "高於 100% 或明顯惡化需警戒。",
        "priority": "P1",
        "risk_impact": "承保虧損會削弱資本與優先股安全邊際。",
        "note": "最新的公開官方數據為2026年第二季。",
        "source_quality_primary": "official_ir",
        "source_quality": "official_ir",
        "source_quality_details": [
          "official_ir"
        ],
        "source_candidate_quality_details": [
          "sec_filing",
          "official_ir",
          "rating_agency"
        ],
        "source_conflict_flag": false,
        "source_conflict_reason": "",
        "metric_period_parsed_date": "2026-06-30",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "consistent_with_prior_range",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "93.1",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20261022",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 數值表達不同，但目前值落在前一可信區間內。"
      },
      {
        "ticker": "AXS-E",
        "metric_name": "Catastrophe losses",
        "metric_category": "巨災損失",
        "value": null,
        "unit": "USD",
        "period": "latest",
        "status": "資料不足",
        "confidence": "低",
        "source": "未取得",
        "source_url_or_name": "",
        "source_candidates": [
          "AXIS Investor Relations",
          "SEC 10-Q",
          "SEC 10-K",
          "Earnings Release",
          "AM Best",
          "S&P"
        ],
        "warning_threshold": "重大巨災損失超預期需警戒。",
        "priority": "P1",
        "risk_impact": "可能壓縮盈餘與資本。",
        "note": "量化監控框架 v1.2 已嘗試由 Stage 1 搜尋此指標；仍未取得官方數值。",
        "source_quality_primary": "unknown",
        "source_quality": "unknown",
        "source_quality_details": [
          "unknown"
        ],
        "source_candidate_quality_details": [
          "sec_filing",
          "official_ir",
          "rating_agency"
        ],
        "source_conflict_flag": true,
        "source_conflict_reason": "只有候選來源含官方資料，實際來源並非官方",
        "metric_period_parsed_date": null,
        "metric_period_parse_status": "unknown",
        "metric_period_type": "unknown",
        "metric_period_freshness": "unknown_period",
        "metric_integrity_status": "pass",
        "metric_verification_status": "data_missing",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "current_missing"
      },
      {
        "ticker": "AXS-E",
        "metric_name": "Preferred dividend status",
        "metric_category": "配息狀態",
        "value": "已支付",
        "unit": "status",
        "period": "2026Q3",
        "status": "已取得",
        "confidence": "高",
        "source": "AXIS Capital Dividend Declaration",
        "source_url_or_name": "AXIS Capital Investor Relations",
        "source_candidates": [
          "AXIS Investor Relations",
          "SEC 10-Q",
          "SEC 10-K",
          "Earnings Release",
          "AM Best",
          "S&P"
        ],
        "warning_threshold": "defer、suspend、delay 立即紅燈。",
        "priority": "P0",
        "risk_impact": "直接影響退休現金流。",
        "note": "最近一次股息於2026年10月15日按時支付。",
        "source_quality_primary": "official_ir",
        "source_quality": "official_ir",
        "source_quality_details": [
          "official_ir"
        ],
        "source_candidate_quality_details": [
          "sec_filing",
          "official_ir",
          "rating_agency"
        ],
        "source_conflict_flag": false,
        "source_conflict_reason": "",
        "metric_period_parsed_date": "2026-09-30",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "not_comparable",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "Paid",
        "cross_run_previous_period": "2026Q3",
        "cross_run_previous_report_date": "20261022",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 有前值，但數值型態無法安全比較。"
      }
    ],
    "missing_data": [
      {
        "ticker": "AXS-E",
        "priority": "P1",
        "missing_type": "metric_value",
        "metric_name": "Catastrophe losses",
        "reason": "Stage 1 已主動搜尋，但尚未取得官方量化數值。",
        "risk_impact": "可能壓縮盈餘與資本。",
        "source_candidates": [
          "AXIS Investor Relations",
          "SEC 10-Q",
          "SEC 10-K",
          "Earnings Release",
          "AM Best",
          "S&P"
        ],
        "acceptance_criteria": "下次報告 metric_data 中 AXS-E / Catastrophe losses 應填入 value、period、source；若查無官方資料，需明確標示查詢來源與查無原因。"
      }
    ],
    "metric_integrity_issues": [],
    "metric_alias_acceptances": [],
    "metric_merge_source": "stage1_deterministic_merge",
    "stage2_resilience_patch_version": "1.3.2",
    "risk_profile": {
      "profile_found": true,
      "risk_profile_version": "1.0",
      "issuer": "AXIS Capital Holdings",
      "security_type": "Series E preferred stock",
      "sector": "Insurance / Reinsurance",
      "core_risk": "再保險承保週期、巨災損失、資本適足性、優先股配息。",
      "required_metric_count": 3,
      "hard_warning_keywords": [
        "catastrophe loss",
        "reserve strengthening",
        "rating downgrade",
        "preferred dividend"
      ]
    },
    "dropped_old_events": [],
    "event_date_filter_summary": {
      "lookback_days": 14,
      "cutoff_date": "2026-10-14",
      "today": "2026-10-27",
      "kept_recent": 2,
      "kept_background": 0,
      "kept_unknown_date": 0,
      "dropped_old": 0
    },
    "metric_consistency_summary": {
      "conflict_count": 0,
      "conflicts": []
    }
  },
  {
    "target_name": "F-B",
    "events": [
      {
        "date": "2026-10-26",
        "title": "分析師預期福特第三季財報欠佳，營收及每股盈餘預計下降",
        "impact_direction": "負向",
        "impact_severity": 3,
        "confidence": "高",
        "summary_30": "分析師預期福特Q3 EPS及營收年減，Model e虧損、供應鏈問題和美國銷量下滑是主要擔憂。",
        "links": [
          "Zacks.com",
          "MarketBeat"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "secondary_site",
        "event_source_quality_details": [
          "secondary_site"
        ],
        "event_verification_status": "unverified",
        "event_days_old": 1,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      },
      {
        "date": "2026-10-25",
        "title": "高盛分析師預計福特股價有望上漲",
        "impact_direction": "正向",
        "impact_severity": 2,
        "confidence": "中",
        "summary_30": "高盛分析師表示，預計福特汽車的股價將會上升。",
        "links": [
          "MarketBeat"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "secondary_site",
        "event_source_quality_details": [
          "secondary_site"
        ],
        "event_verification_status": "unverified",
        "event_days_old": 2,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      },
      {
        "date": "2026-10-24",
        "title": "華爾街調低福特Q3財報預期，可能導致股價意外反彈或確認深層問題",
        "impact_direction": "中性",
        "impact_severity": 3,
        "confidence": "高",
        "summary_30": "華爾街下調福特Q3預期，可能帶來股價反彈機會，但Model e虧損與福特信貸租賃收益問題仍是風險。",
        "links": [
          "24/7 Wall St.",
          "Pluang"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "unknown",
        "event_source_quality_details": [
          "unknown"
        ],
        "event_verification_status": "unverified",
        "event_days_old": 3,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      },
      {
        "date": "2026-10-20",
        "title": "福特因儀表顯示問題召回逾10萬輛F系列卡車",
        "impact_direction": "負向",
        "impact_severity": 3,
        "confidence": "高",
        "summary_30": "福特召回超過10萬輛F系列卡車，因儀表板車速表和轉速表可能失靈。",
        "links": [
          "Seeking Alpha",
          "Stock Titan"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "secondary_site",
        "event_source_quality_details": [
          "secondary_site"
        ],
        "event_verification_status": "unverified",
        "event_days_old": 7,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      },
      {
        "date": "2026-10-19",
        "title": "UBS調降福特目標價但維持「買入」評級，重申全年自由現金流指引",
        "impact_direction": "中性",
        "impact_severity": 2,
        "confidence": "中",
        "summary_30": "UBS下調福特目標價至15美元，但仍維持買入評級，並重申全年自由現金流指引。",
        "links": [
          "TipRanks.com"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "secondary_site",
        "event_source_quality_details": [
          "secondary_site"
        ],
        "event_verification_status": "unverified",
        "event_days_old": 8,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      },
      {
        "date": "2026-10-14",
        "title": "福特Q3召回數量巨大，年度保固成本持續高企",
        "impact_direction": "負向",
        "impact_severity": 4,
        "confidence": "高",
        "summary_30": "福特Q3召回190萬輛車，2026年最大召回涉及傳動系統，年度保固成本持續超過40億美元。",
        "links": [
          "Hearn Law Firm",
          "American Lemon Law Group",
          "BizzyCar"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "unknown",
        "event_source_quality_details": [
          "unknown"
        ],
        "event_verification_status": "unverified",
        "event_days_old": 13,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      }
    ],
    "綜合分析": "Stage 2 AI 合併未完成；已由程式保留高可信 Stage 1 近期事件，事件權重偏負面（-8）。",
    "事件總分": "正向2 / 負向10 / 總分-8",
    "new_sources_found": [],
    "event_merge_source": "stage1_deterministic_fallback",
    "excluded_low_trust_event_count": 0,
    "merged_duplicate_event_count": 0,
    "event_dedup_patch_version": "1.3.3",
    "metric_data": [
      {
        "ticker": "F-B",
        "metric_name": "Industrial free cash flow",
        "official_metric_name": "Company adjusted free cash flow",
        "risk_profile_metric_name": "Industrial free cash flow",
        "metric_category": "工業現金流",
        "value": "2.1 billion",
        "value_numeric": 2100000000,
        "unit": "USD",
        "unit_scale": "USD billions",
        "period": "2026Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "Ford Motor Company Q2 2026 Form 10-Q / 2026-07-28 Earnings Release (SEC 8-K Exhibit 99)",
        "source_url_or_name": "SEC Filing / Ford Investor Relations",
        "source_candidates": [
          "Ford Investor Relations",
          "SEC 10-Q",
          "SEC 10-K",
          "Ford Credit disclosures",
          "S&P",
          "Moody's",
          "Fitch"
        ],
        "warning_threshold": "FCF 轉負或全年指引大幅下修需警戒。",
        "priority": "P0",
        "risk_impact": "工業 FCF 是付息與維持信用評等的重要基礎。",
        "note": "RiskProfile slot 'Industrial free cash flow' is explicitly mapped to Ford's official non-GAAP 'Company adjusted free cash flow'; this is an explicit definition alias, not a silent synonym.",
        "definition_scope": "Ford Motor Company consolidated; Company adjusted free cash flow (non-GAAP)",
        "calculation_basis": "Ford reconciliation from GAAP operating cash flow to Company adjusted free cash flow, excluding Ford Credit operating cash flows and specified items and including Company ex-Ford Credit capex, Ford Credit distributions and derivative settlements.",
        "measurement_form": "non_gaap_company_adjusted_free_cash_flow",
        "metric_definition_alias_status": "explicit_official_definition_lock",
        "metric_alias_scope": "RiskProfile Industrial free cash flow slot -> Ford Company adjusted free cash flow",
        "semantic_match_status": "explicit_official_alias",
        "source_quality_primary": "sec_filing",
        "source_quality": "sec_filing",
        "source_quality_details": [
          "sec_filing",
          "official_ir"
        ],
        "source_conflict_flag": false,
        "source_conflict_reason": "",
        "metric_period_parsed_date": "2026-06-30",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "quarter",
        "metric_period_freshness": "official_reference",
        "metric_integrity_status": "official_definition_lock_applied",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "Official 2026Q2 Company adjusted free cash flow definition locked.",
        "cross_run_consistency_status": "consistent_same_definition",
        "cross_run_consistency_reason": "Compare only against the same explicit Ford Company adjusted free cash flow definition.",
        "metric_origin": "deterministic_official_fallback_v13837",
        "fb_fcf_definition_lock_patch_version": "1.3.8.3.7",
        "fb_fcf_official_floor_patch_version": "1.3.8.3.7",
        "fb_fcf_official_floor_applied": true,
        "fb_fcf_official_floor_status": "q2_company_adjusted_fcf_canonicalized",
        "official_reference_filing_date": "2026-07-29",
        "official_reference_earnings_release_date": "2026-07-28",
        "official_reference_period_end": "2026-06-30",
        "official_operating_cash_flow": "4.3 billion",
        "official_operating_cash_flow_numeric": 4300000000
      },
      {
        "ticker": "F-B",
        "metric_name": "Ford Credit delinquencies / credit losses",
        "metric_category": "金融子公司信用風險",
        "value": null,
        "unit": "%/USD",
        "period": "latest",
        "status": "資料不足",
        "confidence": "低",
        "source": "未取得",
        "source_url_or_name": "",
        "source_candidates": [
          "Ford Investor Relations",
          "SEC 10-Q",
          "SEC 10-K",
          "Ford Credit disclosures",
          "S&P",
          "Moody's",
          "Fitch"
        ],
        "warning_threshold": "逾期率或信用損失準備明顯上升需警戒。",
        "priority": "P1",
        "risk_impact": "汽車金融惡化可能放大景氣下行風險。",
        "note": "量化監控框架 v1.2 已嘗試由 Stage 1 搜尋此指標；仍未取得官方數值。",
        "source_quality_primary": "unknown",
        "source_quality": "unknown",
        "source_quality_details": [
          "unknown"
        ],
        "source_candidate_quality_details": [
          "sec_filing",
          "official_ir",
          "rating_agency"
        ],
        "source_conflict_flag": true,
        "source_conflict_reason": "只有候選來源含官方資料，實際來源並非官方",
        "metric_period_parsed_date": null,
        "metric_period_parse_status": "unknown",
        "metric_period_type": "unknown",
        "metric_period_freshness": "unknown_period",
        "metric_integrity_status": "semantic_rejected",
        "metric_verification_status": "data_missing",
        "semantic_match_status": "rejected",
        "issuer_scope": "unknown / not explicitly Ford Credit",
        "metric_value_type": "missing",
        "rejected_candidate_reason": "Delinq reject-by-default：只接受明確 rate/percentage/bps；裸數字、金額或混合 %/USD 不得替代。；Delinq issuer scope 未明確指向 Ford Credit portfolio；metric_name/source_candidates 不可作為 scope 證據。",
        "semantic_guard_version": "1.3.6",
        "rejected_candidate_value": null,
        "rejected_candidate_source": "未取得",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "definition_scope": "unknown / not explicitly Ford Credit",
        "calculation_basis": "Ford Credit portfolio delinquency rate",
        "cross_run_consistency_status": "current_missing"
      },
      {
        "ticker": "F-B",
        "metric_name": "Recall / warranty cost",
        "metric_category": "品質成本",
        "value": null,
        "unit": "USD",
        "period": "latest",
        "status": "資料不足",
        "confidence": "低",
        "source": "未取得",
        "source_url_or_name": "",
        "source_candidates": [
          "Ford Investor Relations",
          "SEC 10-Q",
          "SEC 10-K",
          "Ford Credit disclosures",
          "S&P",
          "Moody's",
          "Fitch"
        ],
        "warning_threshold": "重大召回或保固成本升高需警戒。",
        "priority": "P1",
        "risk_impact": "品質成本會壓縮現金流與信用評等。",
        "note": "量化監控框架 v1.2 已嘗試由 Stage 1 搜尋此指標；仍未取得官方數值。",
        "source_quality_primary": "unknown",
        "source_quality": "unknown",
        "source_quality_details": [
          "unknown"
        ],
        "source_candidate_quality_details": [
          "sec_filing",
          "official_ir",
          "rating_agency"
        ],
        "source_conflict_flag": true,
        "source_conflict_reason": "只有候選來源含官方資料，實際來源並非官方",
        "metric_period_parsed_date": null,
        "metric_period_parse_status": "unknown",
        "metric_period_type": "unknown",
        "metric_period_freshness": "unknown_period",
        "metric_integrity_status": "semantic_rejected",
        "metric_verification_status": "data_missing",
        "semantic_match_status": "rejected",
        "issuer_scope": "Ford Motor Company recall/warranty",
        "metric_value_type": "missing",
        "rejected_candidate_reason": "Recall 只接受明確 actual expense/accrual/cost 金額。；Recall 候選缺少明確 recall/warranty + actual expense/accrual/cost 語意。",
        "semantic_guard_version": "1.3.6",
        "rejected_candidate_value": null,
        "rejected_candidate_source": "未取得",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "definition_scope": "Ford Motor Company recall/warranty",
        "calculation_basis": "actual recall/warranty expense or accrual",
        "cross_run_consistency_status": "current_missing"
      }
    ],
    "missing_data": [
      {
        "ticker": "F-B",
        "priority": "P1",
        "missing_type": "metric_value",
        "metric_name": "Ford Credit delinquencies / credit losses",
        "reason": "Stage 1 已主動搜尋，但尚未取得官方量化數值。",
        "risk_impact": "汽車金融惡化可能放大景氣下行風險。",
        "source_candidates": [
          "Ford Investor Relations",
          "SEC 10-Q",
          "SEC 10-K",
          "Ford Credit disclosures",
          "S&P",
          "Moody's",
          "Fitch"
        ],
        "acceptance_criteria": "下次報告 metric_data 中 F-B / Ford Credit delinquencies / credit losses 應填入 value、period、source；若查無官方資料，需明確標示查詢來源與查無原因。",
        "conflict_with_metric_data": false
      },
      {
        "ticker": "F-B",
        "priority": "P1",
        "missing_type": "metric_value",
        "metric_name": "Recall / warranty cost",
        "reason": "Stage 1 已主動搜尋，但尚未取得官方量化數值。",
        "risk_impact": "品質成本會壓縮現金流與信用評等。",
        "source_candidates": [
          "Ford Investor Relations",
          "SEC 10-Q",
          "SEC 10-K",
          "Ford Credit disclosures",
          "S&P",
          "Moody's",
          "Fitch"
        ],
        "acceptance_criteria": "下次報告 metric_data 中 F-B / Recall / warranty cost 應填入 value、period、source；若查無官方資料，需明確標示查詢來源與查無原因。",
        "conflict_with_metric_data": false
      },
      {
        "ticker": "F-B",
        "priority": "P1",
        "missing_type": "metric_semantic_rejection",
        "metric_name": "Ford Credit delinquencies / credit losses",
        "reason": "Delinq reject-by-default：只接受明確 rate/percentage/bps；裸數字、金額或混合 %/USD 不得替代。；Delinq issuer scope 未明確指向 Ford Credit portfolio；metric_name/source_candidates 不可作為 scope 證據。",
        "risk_impact": "汽車金融惡化可能放大景氣下行風險。",
        "source_candidates": [
          "Ford Investor Relations",
          "SEC 10-Q",
          "SEC 10-K",
          "Ford Credit disclosures",
          "S&P",
          "Moody's",
          "Fitch"
        ],
        "rejected_candidate_value": null,
        "rejected_candidate_source": "未取得",
        "acceptance_criteria": "F-B Delinq：只接受 Ford Credit portfolio 明確 rate/percentage/bps；F-B Recall：只接受明確 actual recall/warranty expense/accrual/cost。"
      },
      {
        "ticker": "F-B",
        "priority": "P1",
        "missing_type": "metric_semantic_rejection",
        "metric_name": "Recall / warranty cost",
        "reason": "Recall 只接受明確 actual expense/accrual/cost 金額。；Recall 候選缺少明確 recall/warranty + actual expense/accrual/cost 語意。",
        "risk_impact": "品質成本會壓縮現金流與信用評等。",
        "source_candidates": [
          "Ford Investor Relations",
          "SEC 10-Q",
          "SEC 10-K",
          "Ford Credit disclosures",
          "S&P",
          "Moody's",
          "Fitch"
        ],
        "rejected_candidate_value": null,
        "rejected_candidate_source": "未取得",
        "acceptance_criteria": "F-B Delinq：只接受 Ford Credit portfolio 明確 rate/percentage/bps；F-B Recall：只接受明確 actual recall/warranty expense/accrual/cost。"
      }
    ],
    "metric_integrity_issues": [],
    "metric_alias_acceptances": [],
    "metric_merge_source": "stage1_deterministic_merge",
    "stage2_resilience_patch_version": "1.3.2",
    "risk_profile": {
      "profile_found": true,
      "risk_profile_version": "1.0",
      "issuer": "Ford Motor Company",
      "security_type": "Preferred / related income security",
      "sector": "Automotive",
      "core_risk": "Ford Credit、工業自由現金流、召回成本、EV 虧損、信用評等。",
      "required_metric_count": 3,
      "hard_warning_keywords": [
        "recall",
        "free cash flow decline",
        "Ford Credit delinquencies",
        "downgrade",
        "dividend suspension"
      ]
    },
    "dropped_old_events": [],
    "event_date_filter_summary": {
      "lookback_days": 14,
      "cutoff_date": "2026-10-14",
      "today": "2026-10-27",
      "kept_recent": 6,
      "kept_background": 0,
      "kept_unknown_date": 0,
      "dropped_old": 0
    },
    "metric_consistency_summary": {
      "conflict_count": 0,
      "conflicts": []
    },
    "resolved_missing_data": [],
    "fb_fcf_definition_lock_patch_version": "1.3.8.3.7",
    "fb_fcf_official_floor_patch_version": "1.3.8.3.7",
    "fb_fcf_official_floor_applied_count": 1,
    "fb_fcf_official_floor_resolved_missing_count": 0,
    "fb_fcf_duplicate_removed_count": 0
  },
  {
    "target_name": "UZD",
    "events": [],
    "綜合分析": "在指定日期範圍內無可報告的高可信相關事件。",
    "事件總分": "正向0 / 負向0 / 總分+0",
    "new_sources_found": [],
    "event_merge_source": "stage1_deterministic_fallback",
    "excluded_low_trust_event_count": 0,
    "merged_duplicate_event_count": 0,
    "event_dedup_patch_version": "1.3.3",
    "metric_integrity_issues": [],
    "metric_alias_acceptances": [],
    "metric_merge_source": "stage1_deterministic_merge",
    "stage2_resilience_patch_version": "1.3.2",
    "risk_profile": {
      "profile_found": true,
      "risk_profile_version": "1.0",
      "issuer": "United States Cellular / Array Digital Infrastructure",
      "security_type": "Long-dated note",
      "sector": "Telecom / Infrastructure",
      "core_risk": "發行實體、資產出售後現金流、債務承擔、特別股息與是否贖回。",
      "required_metric_count": 3,
      "hard_warning_keywords": [
        "asset sale",
        "special dividend",
        "issuer change",
        "delisting",
        "redemption",
        "debt assumption"
      ]
    },
    "metric_data": [
      {
        "ticker": "UZD",
        "metric_name": "Issuer / guarantor status",
        "metric_category": "法律實體",
        "value": "Issuer=Array Digital Infrastructure, Inc.; UZD 6.25% Senior Notes due 2069 remains NYSE-listed. T-Mobile debt assumption applies to tendered/exchanged debt; the 2026Q2 filing does not evidence a full transfer of all residual UZD.",
        "unit": "status",
        "period": "2026Q2 / filed 2026-08-07",
        "status": "已取得",
        "confidence": "高",
        "source": "Array Digital Infrastructure, Inc. 2026 Q2 Form 10-Q / 2026-08-07 Form 8-K",
        "source_url_or_name": "SEC Filing",
        "source_candidates": [
          "UScellular Investor Relations",
          "TDS Investor Relations",
          "SEC 10-Q",
          "SEC 10-K",
          "Transaction filings",
          "Exchange notices"
        ],
        "warning_threshold": "發行人或擔保人不明確時列灰燈/黃燈，不可判定安全。",
        "priority": "P0",
        "risk_impact": "長債安全取決於法律債務人與擔保結構。",
        "note": "SEC cover page continues to list the 6.25% Senior Notes due 2069 under ticker UZD on NYSE. This fallback does not infer a new guarantor or transfer of untendered residual UZD.",
        "source_quality_primary": "sec_filing",
        "source_quality": "sec_filing",
        "source_quality_details": [
          "sec_filing"
        ],
        "source_candidate_quality_details": [
          "sec_filing",
          "official_ir",
          "exchange_notice"
        ],
        "source_conflict_flag": false,
        "source_conflict_reason": "",
        "metric_period_parsed_date": "2026-06-30",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "consistent_same_definition",
        "definition_scope": "Array Digital Infrastructure residual UZD legal issuer / exchange listing",
        "calculation_basis": "SEC cover page and debt/transaction disclosures",
        "measurement_form": "categorical_status",
        "metric_origin": "deterministic_official_fallback_v1382",
        "uzd_official_fallback_applied": true,
        "uzd_official_fallback_patch_version": "1.3.8.2",
        "official_reference_source": "Array Digital Infrastructure, Inc. 2026 Q2 Form 10-Q / 2026-08-07 Form 8-K",
        "cross_run_previous_value": "Issuer=Array Digital Infrastructure, Inc.; UZD 6.25% Senior Notes due 2069 remains NYSE-listed. T-Mobile debt assumption applies to tendered/exchanged debt; the 2026Q2 filing does not evidence a full transfer of all residual UZD.",
        "cross_run_previous_period": "2026Q2 / filed 2026-08-07",
        "cross_run_previous_report_date": "20261022",
        "cross_run_previous_definition_scope": "Array Digital Infrastructure residual UZD legal issuer / exchange listing",
        "cross_run_previous_calculation_basis": "SEC cover page and debt/transaction disclosures",
        "cross_run_consistency_reason": "同 period / definition 與前一可信值一致。"
      },
      {
        "ticker": "UZD",
        "metric_name": "Asset sale proceeds and use of funds",
        "metric_category": "資產出售",
        "value": "Q2 2026 spectrum-sale proceeds=$1.1676B; estimated related tax≈$250M; approximately $30M of additional T-Mobile spectrum consideration remained pending.",
        "unit": "USD/status",
        "period": "2026Q2 / filed 2026-08-07",
        "status": "已取得",
        "confidence": "高",
        "source": "Array Digital Infrastructure, Inc. 2026 Q2 Form 10-Q / 2026-08-07 Form 8-K",
        "source_url_or_name": "SEC Filing",
        "source_candidates": [
          "UScellular Investor Relations",
          "TDS Investor Relations",
          "SEC 10-Q",
          "SEC 10-K",
          "Transaction filings",
          "Exchange notices"
        ],
        "warning_threshold": "出售所得若大量分配給股東而非減債需警戒。",
        "priority": "P0",
        "risk_impact": "可能削弱債券資產覆蓋。",
        "note": "Deterministic floor reports only disclosed proceeds, taxes and pending consideration; it does not infer that all proceeds were applied to debt reduction or shareholder distributions.",
        "source_quality_primary": "sec_filing",
        "source_quality": "sec_filing",
        "source_quality_details": [
          "sec_filing"
        ],
        "source_candidate_quality_details": [
          "sec_filing",
          "official_ir",
          "exchange_notice"
        ],
        "source_conflict_flag": false,
        "source_conflict_reason": "",
        "metric_period_parsed_date": "2026-06-30",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "consistent_same_definition",
        "definition_scope": "Array Digital Infrastructure spectrum-sale proceeds",
        "calculation_basis": "SEC strategic-alternatives / spectrum-sale disclosures",
        "measurement_form": "categorical_status",
        "metric_origin": "deterministic_official_fallback_v1382",
        "uzd_official_fallback_applied": true,
        "uzd_official_fallback_patch_version": "1.3.8.2",
        "official_reference_source": "Array Digital Infrastructure, Inc. 2026 Q2 Form 10-Q / 2026-08-07 Form 8-K",
        "cross_run_previous_value": "Q2 2026 spectrum-sale proceeds=$1.1676B; estimated related tax≈$250M; approximately $30M of additional T-Mobile spectrum consideration remained pending.",
        "cross_run_previous_period": "2026Q2 / filed 2026-08-07",
        "cross_run_previous_report_date": "20261022",
        "cross_run_previous_definition_scope": "Array Digital Infrastructure spectrum-sale proceeds",
        "cross_run_previous_calculation_basis": "SEC strategic-alternatives / spectrum-sale disclosures",
        "cross_run_consistency_reason": "同 period / definition 與前一可信值一致。"
      },
      {
        "ticker": "UZD",
        "metric_name": "Debt assumption / redemption status",
        "metric_category": "債務處理",
        "value": "2025 T-Mobile exchange transaction assumed $1.665B of Array debt; T-Mobile reports $393M of 6.250% Senior Notes due 2069 issued in the exchange. Array's 2026Q2 SEC cover page still lists UZD on NYSE, so no full redemption of residual UZD is evidenced.",
        "unit": "status",
        "period": "2026Q2 / filed 2026-08-07",
        "status": "已取得",
        "confidence": "高",
        "source": "Array Digital Infrastructure 2026 Q2 Form 10-Q / T-Mobile US 2025 Form 10-K",
        "source_url_or_name": "SEC Filing",
        "source_candidates": [
          "UScellular Investor Relations",
          "TDS Investor Relations",
          "SEC 10-Q",
          "SEC 10-K",
          "Transaction filings",
          "Exchange notices"
        ],
        "warning_threshold": "未說明承擔、契約修改或贖回時列資料不足。",
        "priority": "P0",
        "risk_impact": "直接影響未來付息與本金償付。",
        "note": "Distinguishes debt assumed through the exchange from residual UZD that remains listed by Array; no full-call/full-redemption conclusion is inferred without a separate notice.",
        "source_quality_primary": "sec_filing",
        "source_quality": "sec_filing",
        "source_quality_details": [
          "sec_filing"
        ],
        "source_candidate_quality_details": [
          "sec_filing",
          "official_ir",
          "exchange_notice"
        ],
        "source_conflict_flag": false,
        "source_conflict_reason": "",
        "metric_period_parsed_date": "2026-06-30",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "consistent_same_definition",
        "definition_scope": "T-Mobile exchange debt assumption and residual Array UZD",
        "calculation_basis": "SEC transaction/debt disclosures",
        "measurement_form": "categorical_status",
        "metric_origin": "deterministic_official_fallback_v1382",
        "uzd_official_fallback_applied": true,
        "uzd_official_fallback_patch_version": "1.3.8.2",
        "official_reference_source": "Array Digital Infrastructure 2026 Q2 Form 10-Q / T-Mobile US 2025 Form 10-K",
        "cross_run_previous_value": "2025 T-Mobile exchange transaction assumed $1.665B of Array debt; T-Mobile reports $393M of 6.250% Senior Notes due 2069 issued in the exchange. Array's 2026Q2 SEC cover page still lists UZD on NYSE, so no full redemption of residual UZD is evidenced.",
        "cross_run_previous_period": "2026Q2 / filed 2026-08-07",
        "cross_run_previous_report_date": "20261022",
        "cross_run_previous_definition_scope": "T-Mobile exchange debt assumption and residual Array UZD",
        "cross_run_previous_calculation_basis": "SEC transaction/debt disclosures",
        "cross_run_consistency_reason": "同 period / definition 與前一可信值一致。"
      }
    ],
    "missing_data": [],
    "dropped_old_events": [],
    "event_date_filter_summary": {
      "lookback_days": 14,
      "cutoff_date": "2026-10-14",
      "today": "2026-10-27",
      "kept_recent": 0,
      "kept_background": 0,
      "kept_unknown_date": 0,
      "dropped_old": 0
    },
    "metric_consistency_summary": {
      "conflict_count": 0,
      "conflicts": []
    },
    "market_quote": {
      "ticker": "UZD",
      "security_name_expected": "Array Digital Infrastructure / former United States Cellular 6.25% Senior Notes due 2069",
      "exchange_expected": "NYSE",
      "latest_price": 17.73,
      "price_as_of": "2026-10-26",
      "open": 17.280000686645508,
      "high": 17.729999542236328,
      "low": 17.280000686645508,
      "volume": 5046,
      "bid": null,
      "ask": null,
      "annual_interest": 1.5625,
      "current_yield": 8.8127,
      "quote_source": "Yahoo Finance chart (query1.finance.yahoo.com)",
      "source_host": "query1.finance.yahoo.com",
      "quote_status": "ok",
      "freshness_status": "fresh",
      "security_identity_status": "matched_symbol",
      "source_timestamp": 1793021400,
      "market_quote_patch_version": "1.3.7",
      "returned_symbol": "UZD",
      "currency": "USD",
      "exchange_name": "NYQ",
      "instrument_type": "EQUITY",
      "regular_market_price_meta": 17.73,
      "regular_market_time_meta": 1793044781,
      "reference_session_date": "2026-10-26",
      "weekday_gap": 0,
      "http_status": 200,
      "request_url": "https://query1.finance.yahoo.com/v8/finance/chart/UZD",
      "request_attempt": 1,
      "attempts": [
        {
          "source_host": "query1.finance.yahoo.com",
          "quote_status": "ok",
          "freshness_status": "fresh",
          "price_as_of": "2026-10-26",
          "latest_price": 17.73,
          "error": null
        },
        {
          "source_host": "query2.finance.yahoo.com",
          "quote_status": "ok",
          "freshness_status": "fresh",
          "price_as_of": "2026-10-26",
          "latest_price": 17.73,
          "error": null
        }
      ],
      "source_validation": "cross_checked",
      "source_crosscheck_price": 17.73,
      "source_crosscheck_host": "query2.finance.yahoo.com",
      "source_conflict_pct": 0.0
    },
    "resolved_missing_data": [
      {
        "ticker": "UZD",
        "priority": "P0",
        "missing_type": "metric_value",
        "metric_name": "Issuer / guarantor status",
        "reason": "Stage 1 已主動搜尋，但尚未取得官方量化數值。",
        "risk_impact": "長債安全取決於法律債務人與擔保結構。",
        "source_candidates": [
          "UScellular Investor Relations",
          "TDS Investor Relations",
          "SEC 10-Q",
          "SEC 10-K",
          "Transaction filings",
          "Exchange notices"
        ],
        "acceptance_criteria": "下次報告 metric_data 中 UZD / Issuer / guarantor status 應填入 value、period、source；若查無官方資料，需明確標示查詢來源與查無原因。",
        "resolution": "resolved_by_v1382_sec_deterministic_floor",
        "uzd_official_fallback_patch_version": "1.3.8.2"
      },
      {
        "ticker": "UZD",
        "priority": "P0",
        "missing_type": "metric_value",
        "metric_name": "Asset sale proceeds and use of funds",
        "reason": "Stage 1 已主動搜尋，但尚未取得官方量化數值。",
        "risk_impact": "可能削弱債券資產覆蓋。",
        "source_candidates": [
          "UScellular Investor Relations",
          "TDS Investor Relations",
          "SEC 10-Q",
          "SEC 10-K",
          "Transaction filings",
          "Exchange notices"
        ],
        "acceptance_criteria": "下次報告 metric_data 中 UZD / Asset sale proceeds and use of funds 應填入 value、period、source；若查無官方資料，需明確標示查詢來源與查無原因。",
        "resolution": "resolved_by_v1382_sec_deterministic_floor",
        "uzd_official_fallback_patch_version": "1.3.8.2"
      },
      {
        "ticker": "UZD",
        "priority": "P0",
        "missing_type": "metric_value",
        "metric_name": "Debt assumption / redemption status",
        "reason": "Stage 1 已主動搜尋，但尚未取得官方量化數值。",
        "risk_impact": "直接影響未來付息與本金償付。",
        "source_candidates": [
          "UScellular Investor Relations",
          "TDS Investor Relations",
          "SEC 10-Q",
          "SEC 10-K",
          "Transaction filings",
          "Exchange notices"
        ],
        "acceptance_criteria": "下次報告 metric_data 中 UZD / Debt assumption / redemption status 應填入 value、period、source；若查無官方資料，需明確標示查詢來源與查無原因。",
        "resolution": "resolved_by_v1382_sec_deterministic_floor",
        "uzd_official_fallback_patch_version": "1.3.8.2"
      }
    ],
    "uzd_official_fallback_count": 3,
    "uzd_official_fallback_patch_version": "1.3.8.2"
  }
]
```

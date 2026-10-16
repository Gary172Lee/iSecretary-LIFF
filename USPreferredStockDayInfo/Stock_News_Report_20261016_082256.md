# USPreferredStockDayInfo 每日情報報告

- 生成時間（台灣）：2026-10-16 08:22:57
- 對應 PDF：Stock_News_Report_20261016_082256.pdf
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

- 事件總分：正向2 / 負向3 / 總分-1
- 綜合分析：Stage 2 AI 合併未完成；已由程式保留高可信 Stage 1 近期事件，事件權重偏負面（-1）。
- 事件 1：2026-10-13｜Lumen Technologies宣布將於11月4日舉行第三季度財報電話會議｜recent_event
  - 影響：中性｜嚴重性：1｜信心度：高
  - 摘要：Lumen將於11月4日發布Q3財報並舉行電話會議，提供市場透明度。
  - 來源：Business Wire、PRNewswire、Lumen Investor Relations
  - 日期過濾：kept_recent｜來源品質：official_ir｜驗證：verified
- 事件 2：2026-10-08｜Seeking Alpha下調Lumen評級至「持有」，強調高負債與升息風險｜recent_event
  - 影響：負向｜嚴重性：3｜信心度：中
  - 摘要：分析師因Lumen約135億美元負債及升息環境，將其股票評級下調。
  - 來源：SeekingAlpha
  - 日期過濾：kept_recent｜來源品質：unknown｜驗證：unverified
- 事件 3：2026-10-08｜Lumen與Eminence Grey合作提供主權AI基礎設施｜recent_event
  - 影響：正向｜嚴重性：2｜信心度：高
  - 摘要：Lumen宣布與Eminence Grey合作，共同開發和部署主權AI基礎設施。
  - 來源：PRNewswire、Lumen Investor Relations
  - 日期過濾：kept_recent｜來源品質：official_ir｜驗證：verified

### 2. BHFAL

- 事件總分：正向0 / 負向0 / 總分+0
- 綜合分析：已排除低可信來源並合併重複事件；目前事件權重為中性（+0）。
- 事件 1：2026-10-15｜JPMorgan 將 Brighthouse Financial 評級上調至中性，目標價下調｜recent_event
  - 影響：中性｜嚴重性：3｜信心度：高
  - 摘要：KBW 維持 BHF 股價「市場表現」評級，但目標價從 57 美元下調至 55 美元。
  - 來源：Investing.com、MarketScreener、MarketBeat、GuruFocus
  - 日期過濾：kept_recent｜來源品質：secondary_site｜驗證：unverified
- 事件 2：2026-10-06｜Aquarian 收購案延遲至 12 月，BHFAL 次順位債預計維持上市｜recent_event
  - 影響：中性｜嚴重性：4｜信心度：高
  - 摘要：Aquarian 收購 Brighthouse 因監管審批延遲至 12/6；BHFAL 債券預計將維持流通。
  - 來源：SeekingAlpha、Investing.com、Charlotte Business Journal
  - 日期過濾：kept_recent｜來源品質：unknown｜驗證：unverified

### 3. OPI

- 事件總分：正向0 / 負向0 / 總分+0
- 綜合分析：Stage 2 AI 合併未完成；已由程式保留高可信 Stage 1 近期事件，正負面權重相抵。
- 事件 1：2026-10-15｜OPI股價跌至新低後反彈，分析師評價分歧，Q3財報將近，主要股東出售部分持股｜recent_event
  - 影響：中性｜嚴重性：3｜信心度：高
  - 摘要：OPI股價觸及12個月新低後反彈。分析師評價不一。主要股東8月出售持股。Q3財報預計10月下旬發布。
  - 來源：MarketBeat、SEC Filing、Market Chameleon
  - 日期過濾：kept_recent｜來源品質：sec_filing｜驗證：verified

### 4. AXS-E

- 事件總分：正向3 / 負向0 / 總分+3
- 綜合分析：Stage 2 AI 合併未完成；已由程式保留高可信 Stage 1 近期事件，事件權重偏正面（+3）。
- 事件 1：2026-10-15｜AXIS Capital按期支付系列E優先股季度股息｜recent_event
  - 影響：正向｜嚴重性：3｜信心度：高
  - 摘要：AXIS Capital已於2026年10月15日按期支付每股0.34375美元的系列E優先股股息。
  - 來源：AXIS Capital Investor Relations、Market Chameleon、Dividend.com、Innovative Income Investor、Preferred Stock Channel
  - 日期過濾：kept_recent｜來源品質：official_ir｜驗證：verified

### 5. F-B

- 事件總分：正向0 / 負向0 / 總分+0
- 綜合分析：在指定日期範圍內無可報告的高可信相關事件。
- 事件：無

### 6. UZD

- 事件總分：正向0 / 負向0 / 總分+0
- 綜合分析：在指定日期範圍內無可報告的高可信相關事件。
- 事件：無

## 量化指標與資料缺口

- 量化監控框架版本：1.0
- 說明：v1 先建立每檔應追蹤指標與資料缺口；尚未取得官方數值時，會標示為「資料不足」。

### CTGG 量化監控
- Free cash flow｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：FCF 轉負或展望下修需警戒。
- Debt maturity and exchange offer terms｜狀態：已取得｜驗證：partially_verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：distressed exchange、順位弱化或擔保改變需警戒。
- Credit rating / outlook｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：official_reference｜門檻：downgrade、negative outlook 或 selective default 評論需警戒。
- 資料缺口：1 項，關鍵資料缺漏時不可判定為綠燈。

### BHFAL 量化監控
- RBC ratio｜狀態：資料不足｜驗證：data_missing｜來源品質：official_ir｜期間新鮮度：fresh｜門檻：低於 400% 黃燈；低於 350% 橙燈/紅燈；單季大幅下滑需警戒。
- Statutory capital and surplus｜狀態：已取得｜驗證：verified｜來源品質：official_ir｜期間新鮮度：fresh｜門檻：連續下降或重大減損需警戒。
- Holding company cash and liquid assets｜狀態：資料不足｜驗證：data_missing｜來源品質：official_ir｜期間新鮮度：fresh｜門檻：低於未來 12 個月利息與固定支出覆蓋需求需警戒。
- Financial leverage｜狀態：資料不足｜驗證：data_missing｜來源品質：unknown｜期間新鮮度：unknown_period｜門檻：槓桿升高或評等機構負面評論需警戒。
- Credit rating / outlook｜狀態：已取得｜驗證：verified｜來源品質：rating_agency｜期間新鮮度：acceptable_recent｜門檻：negative outlook、downgrade 或 watch negative 需警戒。
- BHFAL interest payment status｜狀態：已取得｜驗證：unverified｜來源品質：unknown｜期間新鮮度：unknown_period｜門檻：defer、suspend、delay、non-payment 立即紅燈。
- Aquarian merger / change-of-control treatment｜狀態：已取得｜驗證：unverified｜來源品質：unknown｜期間新鮮度：fresh｜門檻：未明確說明 BHFAL 存續、掛牌、贖回或付息條款時列資料不足。
- 資料缺口：3 項，關鍵資料缺漏時不可判定為綠燈。

### OPI 量化監控
- Occupancy rate｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：連續下降或低於同業顯著水準需警戒。
- AFFO / FFO｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：AFFO/FFO 大幅下滑或為負需警戒。
- Debt maturity schedule｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：12-24 個月內大量到期且流動性不足需紅燈。
- Liquidity / cash availability｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：流動性不足或 covenant 壓力需警戒。

### AXS-E 量化監控
- Combined ratio｜狀態：已取得｜驗證：verified｜來源品質：official_ir｜期間新鮮度：fresh｜門檻：高於 100% 或明顯惡化需警戒。
- Catastrophe losses｜狀態：已取得｜驗證：partially_verified｜來源品質：official_ir｜期間新鮮度：fresh｜門檻：重大巨災損失超預期需警戒。
- Preferred dividend status｜狀態：已取得｜驗證：partially_verified｜來源品質：official_ir｜期間新鮮度：fresh｜門檻：defer、suspend、delay 立即紅燈。
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

- CTGG：recent=3，background=0，unknown_date=0，dropped_old=0
- BHFAL：recent=2，background=0，unknown_date=0，dropped_old=0
- OPI：recent=1，background=0，unknown_date=0，dropped_old=0
- AXS-E：recent=1，background=0，unknown_date=0，dropped_old=0
- F-B：recent=0，background=0，unknown_date=0，dropped_old=0
- UZD：recent=0，background=0，unknown_date=0，dropped_old=0

## 完整 JSON

```json
[
  {
    "target_name": "CTGG",
    "events": [
      {
        "date": "2026-10-13",
        "title": "Lumen Technologies宣布將於11月4日舉行第三季度財報電話會議",
        "impact_direction": "中性",
        "impact_severity": 1,
        "confidence": "高",
        "summary_30": "Lumen將於11月4日發布Q3財報並舉行電話會議，提供市場透明度。",
        "links": [
          "Business Wire",
          "PRNewswire",
          "Lumen Investor Relations"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "official_ir",
        "event_source_quality_details": [
          "official_ir",
          "press_release"
        ],
        "event_verification_status": "verified",
        "event_days_old": 3,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      },
      {
        "date": "2026-10-08",
        "title": "Seeking Alpha下調Lumen評級至「持有」，強調高負債與升息風險",
        "impact_direction": "負向",
        "impact_severity": 3,
        "confidence": "中",
        "summary_30": "分析師因Lumen約135億美元負債及升息環境，將其股票評級下調。",
        "links": [
          "SeekingAlpha"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "unknown",
        "event_source_quality_details": [
          "unknown"
        ],
        "event_verification_status": "unverified",
        "event_days_old": 8,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      },
      {
        "date": "2026-10-08",
        "title": "Lumen與Eminence Grey合作提供主權AI基礎設施",
        "impact_direction": "正向",
        "impact_severity": 2,
        "confidence": "高",
        "summary_30": "Lumen宣布與Eminence Grey合作，共同開發和部署主權AI基礎設施。",
        "links": [
          "PRNewswire",
          "Lumen Investor Relations"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "official_ir",
        "event_source_quality_details": [
          "official_ir",
          "press_release"
        ],
        "event_verification_status": "verified",
        "event_days_old": 8,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      }
    ],
    "綜合分析": "Stage 2 AI 合併未完成；已由程式保留高可信 Stage 1 近期事件，事件權重偏負面（-1）。",
    "事件總分": "正向2 / 負向3 / 總分-1",
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
        "cross_run_previous_report_date": "20261014",
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
        "value": "Qwest Corporation已完成6.5% 2056年到期票據（$515.3M）與6.75% 2057年到期票據（$381.5M）交換為Lumen擔保的6.500% 2051年到期與6.750% 2052年到期新票據；截至2026年3月31日，長期債務餘額（不含流動負債）為$12,925M。",
        "unit": "status/date/USD",
        "period": "2026年6月9日完成 (交換要約) / 2026年3月31日 (長期債務餘額)",
        "status": "已取得",
        "confidence": "高",
        "source": "Lumen Technologies SEC Filing / Business Wire / Lumen Investor Relations",
        "source_url_or_name": "Lumen Investor Relations",
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
        "note": "CTGG為Qwest Corp 2051年到期高級票據，與交換要約中的新2051年到期票據直接相關。",
        "source_quality_primary": "sec_filing",
        "source_quality": "sec_filing",
        "source_quality_details": [
          "sec_filing",
          "official_ir",
          "press_release"
        ],
        "source_candidate_quality_details": [
          "sec_filing",
          "official_ir",
          "rating_agency"
        ],
        "source_conflict_flag": false,
        "source_conflict_reason": "",
        "metric_period_parsed_date": "2026-06-09",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "date",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "partially_verified",
        "metric_consistency_status": "cross_run_conflict",
        "metric_consistency_reason": "同 period / definition 前值=2051年9月1日到期，Qwest Corporation發行的6.500%高級無擔保票據；相關交換要約已於2026年6月完成，新發行票據由Lumen Technologies提供完全且無條件的無擔保擔保。，本次=Qwest Corporation已完成6.5% 2056年到期票據（$515.3M）與6.75% 2057年到期票據（$381.5M）交換為Lumen擔保的6.500% 2051年到期與6.750% 2052年到期新票據；截至2026年3月31日，長期債務餘額（不含流動負債）為$12,925M。；區間不重疊。",
        "cross_run_consistency_status": "value_changed_same_definition",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "2051年9月1日到期，Qwest Corporation發行的6.500%高級無擔保票據；相關交換要約已於2026年6月完成，新發行票據由Lumen Technologies提供完全且無條件的無擔保擔保。",
        "cross_run_previous_period": "截至2026年6月9日",
        "cross_run_previous_report_date": "20260909",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 前值=2051年9月1日到期，Qwest Corporation發行的6.500%高級無擔保票據；相關交換要約已於2026年6月完成，新發行票據由Lumen Technologies提供完全且無條件的無擔保擔保。，本次=Qwest Corporation已完成6.5% 2056年到期票據（$515.3M）與6.75% 2057年到期票據（$381.5M）交換為Lumen擔保的6.500% 2051年到期與6.750% 2052年到期新票據；截至2026年3月31日，長期債務餘額（不含流動負債）為$12,925M。；區間不重疊。"
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
    "missing_data": [
      {
        "ticker": "CTGG",
        "priority": "P0",
        "missing_type": "metric_cross_run_consistency",
        "metric_name": "Debt maturity and exchange offer terms",
        "reason": "同 period / definition 前值=2051年9月1日到期，Qwest Corporation發行的6.500%高級無擔保票據；相關交換要約已於2026年6月完成，新發行票據由Lumen Technologies提供完全且無條件的無擔保擔保。，本次=Qwest Corporation已完成6.5% 2056年到期票據（$515.3M）與6.75% 2057年到期票據（$381.5M）交換為Lumen擔保的6.500% 2051年到期與6.750% 2052年到期新票據；截至2026年3月31日，長期債務餘額（不含流動負債）為$12,925M。；區間不重疊。",
        "risk_impact": "可能削弱 CTGG 債權保護。",
        "previous_value": "2051年9月1日到期，Qwest Corporation發行的6.500%高級無擔保票據；相關交換要約已於2026年6月完成，新發行票據由Lumen Technologies提供完全且無條件的無擔保擔保。",
        "current_value": "Qwest Corporation已完成6.5% 2056年到期票據（$515.3M）與6.75% 2057年到期票據（$381.5M）交換為Lumen擔保的6.500% 2051年到期與6.750% 2052年到期新票據；截至2026年3月31日，長期債務餘額（不含流動負債）為$12,925M。",
        "period": "2026年6月9日完成 (交換要約) / 2026年3月31日 (長期債務餘額)",
        "definition_scope": "",
        "calculation_basis": "",
        "acceptance_criteria": "以同一官方定義重新查核；若為不同口徑，改填不同 definition_scope / calculation_basis，不得覆寫。"
      }
    ],
    "dropped_old_events": [],
    "event_date_filter_summary": {
      "lookback_days": 14,
      "cutoff_date": "2026-10-03",
      "today": "2026-10-16",
      "kept_recent": 3,
      "kept_background": 0,
      "kept_unknown_date": 0,
      "dropped_old": 0
    },
    "metric_consistency_summary": {
      "conflict_count": 1,
      "conflicts": [
        {
          "ticker": "CTGG",
          "metric_name": "Debt maturity and exchange offer terms",
          "metric_value": "Qwest Corporation已完成6.5% 2056年到期票據（$515.3M）與6.75% 2057年到期票據（$381.5M）交換為Lumen擔保的6.500% 2051年到期與6.750% 2052年到期新票據；截至2026年3月31日，長期債務餘額（不含流動負債）為$12,925M。",
          "missing_reason": "同 period / definition 前值=2051年9月1日到期，Qwest Corporation發行的6.500%高級無擔保票據；相關交換要約已於2026年6月完成，新發行票據由Lumen Technologies提供完全且無條件的無擔保擔保。，本次=Qwest Corporation已完成6.5% 2056年到期票據（$515.3M）與6.75% 2057年到期票據（$381.5M）交換為Lumen擔保的6.500% 2051年到期與6.750% 2052年到期新票據；截至2026年3月31日，長期債務餘額（不含流動負債）為$12,925M。；區間不重疊。",
          "verification_after_reconcile": "partially_verified",
          "cross_run_consistency_status": "value_changed_same_definition",
          "definition_scope": "",
          "calculation_basis": ""
        }
      ]
    },
    "ctgg_rating_evidence_enriched_count": 1,
    "ctgg_rating_evidence_patch_version": "1.3.8.3.6",
    "ctgg_rating_direct_scope_patch_version": "1.3.8.3.6",
    "resolved_rating_candidates": [
      {
        "ticker": "CTGG",
        "metric_name": "Credit rating / outlook",
        "rejected_candidate_value": "Moody's (Qwest高級無擔保票據): Caa1 (穩定展望); Fitch (Qwest IDR): B (穩定展望), Lumen擔保債務恢復等級: RR1; S&P (Qwest新票據): B, 恢復等級: 2",
        "rejected_candidate_period": "2026年2月-4月",
        "rejected_candidate_source": "Moody's, Fitch Ratings, S&P Global Ratings",
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
        "title": "JPMorgan 將 Brighthouse Financial 評級上調至中性，目標價下調",
        "impact_direction": "中性",
        "impact_severity": 3,
        "confidence": "高",
        "summary_30": "KBW 維持 BHF 股價「市場表現」評級，但目標價從 57 美元下調至 55 美元。",
        "links": [
          "Investing.com",
          "MarketScreener",
          "MarketBeat",
          "GuruFocus"
        ],
        "merged_duplicate_count": 2,
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
        "date": "2026-10-06",
        "title": "Aquarian 收購案延遲至 12 月，BHFAL 次順位債預計維持上市",
        "impact_direction": "中性",
        "impact_severity": 4,
        "confidence": "高",
        "summary_30": "Aquarian 收購 Brighthouse 因監管審批延遲至 12/6；BHFAL 債券預計將維持流通。",
        "links": [
          "SeekingAlpha",
          "Investing.com",
          "Charlotte Business Journal"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "unknown",
        "event_source_quality_details": [
          "unknown"
        ],
        "event_verification_status": "unverified",
        "event_days_old": 10,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      }
    ],
    "綜合分析": "已排除低可信來源並合併重複事件；目前事件權重為中性（+0）。",
    "事件總分": "正向0 / 負向0 / 總分+0",
    "new_sources_found": [],
    "event_merge_source": "stage1_deterministic_fallback",
    "excluded_low_trust_event_count": 0,
    "merged_duplicate_event_count": 1,
    "event_dedup_patch_version": "1.3.3",
    "metric_data": [
      {
        "ticker": "BHFAL",
        "metric_name": "RBC ratio",
        "metric_category": "保險償付能力",
        "value": null,
        "unit": "%",
        "period": "2026Q2 (截至 2026-06-30)",
        "status": "資料不足",
        "confidence": "低",
        "source": "Brighthouse Financial 2026Q2 財報新聞稿 / 財務補充文件",
        "source_url_or_name": "Business Wire, Brighthouse Financial Investor Relations",
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
        "note": "估計合併風險資本比率，基於 Brighthouse Life Insurance Company 和 New England Life Insurance Company 的初步法定結果。",
        "definition_scope": "合併法定結果",
        "calculation_basis": "初步法定結果",
        "source_quality_primary": "official_ir",
        "source_quality": "official_ir",
        "source_quality_details": [
          "official_ir",
          "press_release"
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
        "metric_period_type": "date",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "source_period_rejected",
        "metric_verification_status": "data_missing",
        "measurement_form": "range",
        "source_period_rejected_value": "430%-450%",
        "source_period_expected": "2026Q2 / as of 2026-06-30",
        "source_period_alignment_status": "rejected_prior_period_fingerprint",
        "source_period_rejection_reason": "候選值 430%-450% 與已驗證的 Brighthouse 1Q26 estimated combined RBC 430%-450% 完全一致，但實際來源/備註未提供截至 2026-06-30 的 Q2 來源期證據；為避免把 2026Q1 數字錯標成 2026Q2，已停止採用。",
        "live_validation_patch_version": "1.3.6",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "current_missing"
      },
      {
        "ticker": "BHFAL",
        "metric_name": "Statutory capital and surplus",
        "metric_category": "法定資本",
        "value": "$4.9 Billion",
        "unit": "USD",
        "period": "2026Q2 (截至 2026-06-30)",
        "status": "已取得",
        "confidence": "高",
        "source": "Brighthouse Financial 2026Q2 財報新聞稿 / 財務補充文件",
        "source_url_or_name": "Business Wire, Brighthouse Financial Investor Relations",
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
        "note": "合併總調整資本，基於 Brighthouse Life Insurance Company 和 New England Life Insurance Company 的初步法定結果。",
        "definition_scope": "合併法定結果",
        "calculation_basis": "初步法定結果",
        "source_quality_primary": "official_ir",
        "source_quality": "official_ir",
        "source_quality_details": [
          "official_ir",
          "press_release"
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
        "metric_period_type": "date",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "definition_changed",
        "cross_run_previous_value": "$4.9 billion",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20261013",
        "cross_run_previous_definition_scope": "Operating insurance subsidiaries (Combined)",
        "cross_run_previous_calculation_basis": "Preliminary statutory results",
        "cross_run_consistency_reason": "同 period 有前值，但 definition_scope / calculation_basis 不同，不互相覆寫。"
      },
      {
        "ticker": "BHFAL",
        "metric_name": "Holding company cash and liquid assets",
        "metric_category": "控股公司流動性",
        "value": null,
        "unit": "USD",
        "period": "2026Q2 (截至 2026-06-30)",
        "status": "資料不足",
        "confidence": "低",
        "source": "Brighthouse Financial 2026Q2 財報新聞稿 / 財務補充文件",
        "source_url_or_name": "Business Wire, Brighthouse Financial Investor Relations",
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
        "note": "包含 Brighthouse Financial, Inc.、Brighthouse Holdings, LLC 和 Brighthouse Services, LLC 的流動資產。",
        "definition_scope": "控股公司合併",
        "calculation_basis": "截至 2026-06-30 的液態資產",
        "source_quality_primary": "official_ir",
        "source_quality": "official_ir",
        "source_quality_details": [
          "official_ir",
          "press_release"
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
        "metric_period_type": "date",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "source_period_rejected",
        "metric_verification_status": "data_missing",
        "measurement_form": "point",
        "source_period_rejected_value": "$0.9 Billion",
        "source_period_expected": "2026Q2 / as of 2026-06-30",
        "source_period_alignment_status": "rejected_prior_period_fingerprint",
        "source_period_rejection_reason": "候選值 $0.9 Billion 與已驗證的 Brighthouse 1Q26 holding company liquid assets $0.9B 完全一致，但實際來源/備註未提供截至 2026-06-30 的 Q2 來源期證據；為避免把 2026Q1 數字錯標成 2026Q2，已停止採用。",
        "live_validation_patch_version": "1.3.6",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "current_missing"
      },
      {
        "ticker": "BHFAL",
        "metric_name": "Financial leverage",
        "metric_category": "槓桿",
        "value": null,
        "unit": "%",
        "period": "latest",
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
        "rejected_candidate_reason": "BHFAL AM Best official-action veto：2026-07-29 最新正式 rating action 維持 Under Review with Negative Implications；2058 6.25% junior subordinated debentures Long-Term IR=bbb-。stable outlook 候選不得採用。",
        "rejected_candidate_value": "AM Best: A (Excellent) / Under Review with Negative Implications; S&P: BBB / CreditWatch with Negative Implications; Moody's: A3 / Stable; Fitch: A- / Stable",
        "rejected_candidate_source": "AM Best, S&P Global Ratings, Brighthouse Financial Investor Relations",
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
        "cross_run_previous_report_date": "20261014",
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
        "value": "已支付",
        "unit": "status",
        "period": "最新可查期間",
        "status": "已取得",
        "confidence": "高",
        "source": "無負面報導 (隱含)",
        "source_url_or_name": "N/A",
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
        "note": "次順位債券付息優先於優先股，且無任何負面消息。",
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
        "metric_verification_status": "unverified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "no_prior_same_period",
        "definition_scope": "",
        "calculation_basis": ""
      },
      {
        "ticker": "BHFAL",
        "metric_name": "Aquarian merger / change-of-control treatment",
        "metric_category": "交易條款",
        "value": "合併延遲至 2026 年 12 月 6 日；BHFAL 預計維持未贖回、繼續掛牌流通",
        "unit": "status",
        "period": "2026-10-06",
        "status": "已取得",
        "confidence": "高",
        "source": "SeekingAlpha, Investing.com, Charlotte Business Journal",
        "source_url_or_name": "SeekingAlpha, Investing.com, Charlotte Business Journal",
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
        "note": "主要因德拉瓦、紐約、麻薩諸塞州監管審批尚未完成。有報導稱 Talcott/Sixth Street 可能為替代收購方。",
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
        "metric_period_parsed_date": "2026-10-06",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "date",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "unverified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "no_prior_same_period",
        "definition_scope": "",
        "calculation_basis": ""
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
        "missing_type": "metric_source_period_alignment",
        "metric_name": "RBC ratio",
        "reason": "候選值 430%-450% 與已驗證的 Brighthouse 1Q26 estimated combined RBC 430%-450% 完全一致，但實際來源/備註未提供截至 2026-06-30 的 Q2 來源期證據；為避免把 2026Q1 數字錯標成 2026Q2，已停止採用。",
        "risk_impact": "RBC 下滑可能代表保險子公司資本緩衝下降，影響次順位債付息與信用評等。",
        "rejected_candidate_value": "430%-450%",
        "source": "Brighthouse Financial 2026Q2 財報新聞稿 / 財務補充文件",
        "acceptance_criteria": "若宣稱 2026Q2，實際來源/備註需能對應截至 2026-06-30（或等價明確 Q2 as-of date）；否則不得沿用已知 2026Q1 官方指紋值。"
      },
      {
        "ticker": "BHFAL",
        "priority": "P0",
        "missing_type": "metric_source_period_alignment",
        "metric_name": "Holding company cash and liquid assets",
        "reason": "候選值 $0.9 Billion 與已驗證的 Brighthouse 1Q26 holding company liquid assets $0.9B 完全一致，但實際來源/備註未提供截至 2026-06-30 的 Q2 來源期證據；為避免把 2026Q1 數字錯標成 2026Q2，已停止採用。",
        "risk_impact": "控股公司流動性不足可能影響 BHFAL 利息支付。",
        "rejected_candidate_value": "$0.9 Billion",
        "source": "Brighthouse Financial 2026Q2 財報新聞稿 / 財務補充文件",
        "acceptance_criteria": "若宣稱 2026Q2，實際來源/備註需能對應截至 2026-06-30（或等價明確 Q2 as-of date）；否則不得沿用已知 2026Q1 官方指紋值。"
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
      "cutoff_date": "2026-10-03",
      "today": "2026-10-16",
      "kept_recent": 2,
      "kept_background": 0,
      "kept_unknown_date": 0,
      "dropped_old": 0
    },
    "metric_consistency_summary": {
      "conflict_count": 0,
      "conflicts": []
    },
    "market_quote": {
      "ticker": "BHFAL",
      "security_name_expected": "Brighthouse Financial 6.25% Junior Subordinated Debentures due 2058",
      "exchange_expected": "NASDAQ",
      "latest_price": 15.135,
      "price_as_of": "2026-10-15",
      "open": 14.880000114440918,
      "high": 15.180000305175781,
      "low": 14.880000114440918,
      "volume": 34966,
      "bid": null,
      "ask": null,
      "annual_interest": 1.5625,
      "current_yield": 10.3238,
      "quote_source": "Yahoo Finance chart (query1.finance.yahoo.com)",
      "source_host": "query1.finance.yahoo.com",
      "quote_status": "ok",
      "freshness_status": "fresh",
      "security_identity_status": "matched_symbol",
      "source_timestamp": 1792071000,
      "market_quote_patch_version": "1.3.7",
      "returned_symbol": "BHFAL",
      "currency": "USD",
      "exchange_name": "NMS",
      "instrument_type": "EQUITY",
      "regular_market_price_meta": 15.135,
      "regular_market_time_meta": 1792094400,
      "reference_session_date": "2026-10-15",
      "weekday_gap": 0,
      "http_status": 200,
      "request_url": "https://query1.finance.yahoo.com/v8/finance/chart/BHFAL",
      "request_attempt": 1,
      "attempts": [
        {
          "source_host": "query1.finance.yahoo.com",
          "quote_status": "ok",
          "freshness_status": "fresh",
          "price_as_of": "2026-10-15",
          "latest_price": 15.135,
          "error": null
        },
        {
          "source_host": "query2.finance.yahoo.com",
          "quote_status": "ok",
          "freshness_status": "fresh",
          "price_as_of": "2026-10-15",
          "latest_price": 15.135,
          "error": null
        }
      ],
      "source_validation": "cross_checked",
      "source_crosscheck_price": 15.135,
      "source_crosscheck_host": "query2.finance.yahoo.com",
      "source_conflict_pct": 0.0
    }
  },
  {
    "target_name": "OPI",
    "events": [
      {
        "date": "2026-10-15",
        "title": "OPI股價跌至新低後反彈，分析師評價分歧，Q3財報將近，主要股東出售部分持股",
        "impact_direction": "中性",
        "impact_severity": 3,
        "confidence": "高",
        "summary_30": "OPI股價觸及12個月新低後反彈。分析師評價不一。主要股東8月出售持股。Q3財報預計10月下旬發布。",
        "links": [
          "MarketBeat",
          "SEC Filing",
          "Market Chameleon"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "sec_filing",
        "event_source_quality_details": [
          "sec_filing",
          "secondary_site"
        ],
        "event_verification_status": "verified",
        "event_days_old": 1,
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
        "note": "截至2026年6月30日，所有物業（All Properties）出租率為77.9%；可比較物業（Comparable Properties）出租率為88.7%。公司正積極進行資產出售以優化投資組合。",
        "definition_scope": "Percent leased; All Properties and Comparable Properties presented as separate portfolio scopes",
        "measurement_form": "multi_scope_percentage",
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
        "calculation_basis": "SEC 10-Q occupancy table as of June 30, 2026",
        "unit_scale": "percentage points",
        "accounting_entity_period": "As of 2026-06-30; portfolio-scope split, not a Successor/Predecessor time split",
        "scope_values": {
          "all_properties_pct": 77.9,
          "comparable_properties_pct": 88.7
        },
        "cross_run_consistency_reason": "All Properties and Comparable Properties are distinct portfolio scopes.",
        "cross_run_previous_value": null,
        "cross_run_previous_period": null,
        "cross_run_previous_report_date": null,
        "cross_run_previous_definition_scope": null,
        "cross_run_previous_calculation_basis": null,
        "opi_definition_guard_applied": true,
        "opi_definition_guard_patch_version": "1.3.8.3",
        "opi_definition_guard_status": "official_q2_occupancy_scope_split_canonicalized",
        "official_reference_date": "2026-08-06",
        "official_reference_source": "Office Properties Income Trust 2026 Q2 Form 10-Q",
        "metric_origin": "deterministic_official_fallback_v13833",
        "opi_official_floor_applied": true,
        "opi_official_floor_patch_version": "1.3.8.3.3"
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
        "note": "截至2026年6月30日的第二季度，已重整後繼承實體 (Successor, 6月18日-6月30日) 調整後營運資金 (Normalized FFO) 為4.5百萬美元，每股0.20美元；重整前實體 (Predecessor, 4月1日-6月17日) Normalized FFO為15.1百萬美元，每股0.21美元。",
        "definition_scope": "OPI Normalized FFO; Successor and Predecessor periods presented separately",
        "measurement_form": "split_period_amount_and_per_share",
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
        "metric_period_type": "quarter_split_accounting_periods",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "official_definition_lock_applied",
        "metric_verification_status": "verified",
        "metric_consistency_status": "not_comparable_split_definition",
        "metric_consistency_reason": "Successor/Predecessor 與 amount/per-share 必須分開，不做單一 scalar cross-run 比較。",
        "cross_run_consistency_status": "not_comparable_split_definition",
        "calculation_basis": "SEC 10-Q FFO and Normalized FFO reconciliation; amount and per-share measures kept separate",
        "unit_scale": "amount=USD millions (10-Q table presented in thousands); per_share=USD/common share",
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
        "cross_run_consistency_reason": "OPI 2026Q2 bankruptcy emergence creates separate Successor/Predecessor accounting periods; scalar comparison is prohibited.",
        "cross_run_previous_value": null,
        "cross_run_previous_period": null,
        "cross_run_previous_report_date": null,
        "cross_run_previous_definition_scope": null,
        "cross_run_previous_calculation_basis": null,
        "opi_definition_guard_applied": true,
        "opi_definition_guard_patch_version": "1.3.8.3",
        "opi_definition_guard_status": "official_q2_normalized_ffo_split_canonicalized",
        "official_reference_date": "2026-08-06",
        "official_reference_source": "Office Properties Income Trust 2026 Q2 Form 10-Q",
        "metric_origin": "deterministic_official_fallback_v13833",
        "opi_official_floor_applied": true,
        "opi_official_floor_patch_version": "1.3.8.3.3"
      },
      {
        "ticker": "OPI",
        "metric_name": "Debt maturity schedule",
        "metric_category": "債務到期牆",
        "value": "Debt maturities excluding revolving credit facility: 2026 $20.000M; 2027 $130.000M; 2028 $168.487M; 2029 $590.279M; 2030 $0.300M; 2031+ $473.254M; total $1.382320B",
        "unit": "USD/date",
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
        "warning_threshold": "12-24 個月內大量到期且流動性不足需紅燈。",
        "priority": "P0",
        "risk_impact": "再融資失敗可能導致重整或資產賤售。",
        "note": "OPI已於2026年6月17日完成重整，債務減少約7.14億美元。公司計劃發行4.25億美元5年期高級擔保票據以應對2027年1月到期的循環信貸和定期貸款。新發行的8.375%高級擔保票據（2029年12月到期）要求2026年償還2千萬美元本金（已償還5百萬美元，11月1日還15百萬美元），2027年償還3千萬美元，2028年償還4.5千萬美元，2029年償還4.5千萬美元。另有4.2億美元10.0%高級擔保票據將於2031年6月到期。截至2026年6月30日，仍有1.77億美元抵押貸款。預計2028年有1.235億美元抵押貸款到期。",
        "definition_scope": "OPI debt maturities excluding revolving credit facility",
        "measurement_form": "multi_period_maturity_schedule",
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
        "metric_period_type": "date_with_maturity_schedule",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "not_comparable_official_floor",
        "calculation_basis": "SEC 10-Q debt maturities table as of June 30, 2026",
        "cross_run_previous_value": null,
        "cross_run_previous_period": null,
        "cross_run_previous_report_date": null,
        "cross_run_previous_definition_scope": null,
        "cross_run_previous_calculation_basis": null,
        "cross_run_consistency_reason": "Official multi-year maturity schedule is kept structured and not reduced to one scalar.",
        "unit_scale": "USD millions",
        "metric_origin": "deterministic_official_fallback_v13833",
        "opi_official_floor_applied": true,
        "opi_official_floor_patch_version": "1.3.8.3.3",
        "official_reference_date": "2026-08-06",
        "official_reference_source": "Office Properties Income Trust 2026 Q2 Form 10-Q",
        "scope_values": {
          "2026_usd": 20000000,
          "2027_usd": 130000000,
          "2028_usd": 168487000,
          "2029_usd": 590279000,
          "2030_usd": 300000,
          "2031_and_thereafter_usd": 473254000,
          "total_ex_revolver_usd": 1382320000
        }
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
        "note": "截至2026年6月30日，現金及約當現金為50.751百萬美元，受限制現金為54.038百萬美元。4.25億美元的擔保信貸協議包含3.25億美元的循環信貸額度及1億美元的定期貸款，該循環信貸已完全提取，因此可用額度為零。",
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
    "missing_data": [],
    "dropped_old_events": [],
    "event_date_filter_summary": {
      "lookback_days": 14,
      "cutoff_date": "2026-10-03",
      "today": "2026-10-16",
      "kept_recent": 1,
      "kept_background": 0,
      "kept_unknown_date": 0,
      "dropped_old": 0
    },
    "metric_consistency_summary": {
      "conflict_count": 0,
      "conflicts": []
    },
    "resolved_missing_data": [],
    "opi_definition_guard_applied_count": 2,
    "opi_definition_guard_patch_version": "1.3.8.3",
    "opi_summary_reconciliation_patch_version": "1.3.8.3.1",
    "opi_affo_placeholder_removed_count": 0,
    "opi_affo_missing_resolved_count": 0,
    "resolved_metric_duplicates": [],
    "opi_structured_cleanup_patch_version": "1.3.8.3.2",
    "opi_structured_duplicate_removed_count": 0,
    "opi_official_floor_resolved_missing_count": 0,
    "opi_official_floor_applied_count": 4,
    "opi_official_floor_active_keys": [
      "affoffo",
      "debt",
      "liquidity",
      "occupancy"
    ],
    "opi_official_floor_patch_version": "1.3.8.3.3"
  },
  {
    "target_name": "AXS-E",
    "events": [
      {
        "date": "2026-10-15",
        "title": "AXIS Capital按期支付系列E優先股季度股息",
        "impact_direction": "正向",
        "impact_severity": 3,
        "confidence": "高",
        "summary_30": "AXIS Capital已於2026年10月15日按期支付每股0.34375美元的系列E優先股股息。",
        "links": [
          "AXIS Capital Investor Relations",
          "Market Chameleon",
          "Dividend.com",
          "Innovative Income Investor",
          "Preferred Stock Channel"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "official_ir",
        "event_source_quality_details": [
          "official_ir",
          "secondary_site"
        ],
        "event_verification_status": "verified",
        "event_days_old": 1,
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
        "source": "AXIS Capital Investor Relations (Earnings Release)",
        "source_url_or_name": "AXIS Capital Holdings Limited Investor Relations",
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
        "note": "截至2026年第二季度，綜合成本率為93.1%，優於警戒閾值，顯示健康的承保獲利能力。",
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
        "cross_run_consistency_status": "consistent_same_definition",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "93.1%",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20261007",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 與前一可信值一致。"
      },
      {
        "ticker": "AXS-E",
        "metric_name": "Catastrophe losses",
        "metric_category": "巨災損失",
        "value": "$80 million",
        "unit": "USD",
        "period": "2026Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "AXIS Capital Investor Relations (Earnings Release)",
        "source_url_or_name": "AXIS Capital Holdings Limited Investor Relations",
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
        "note": "2026年第二季度稅前巨災及天氣相關損失為8000萬美元，已扣除再保險，顯示可控的巨災影響。",
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
        "metric_verification_status": "partially_verified",
        "metric_consistency_status": "cross_run_conflict",
        "metric_consistency_reason": "同 period / definition 前值=80，本次=$80 million；區間不重疊。",
        "cross_run_consistency_status": "value_changed_same_definition",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "80",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260924",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 前值=80，本次=$80 million；區間不重疊。"
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
        "source": "AXIS Capital Investor Relations (Prior Dividend Declaration) / Market Chameleon / Dividend.com",
        "source_url_or_name": "AXIS Capital Holdings Limited Investor Relations",
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
        "note": "系列E優先股季度股息已於2026年10月15日按期支付，對退休現金流安全具有正面意義。",
        "source_quality_primary": "official_ir",
        "source_quality": "official_ir",
        "source_quality_details": [
          "official_ir",
          "secondary_site"
        ],
        "source_candidate_quality_details": [
          "sec_filing",
          "official_ir",
          "rating_agency"
        ],
        "source_conflict_flag": true,
        "source_conflict_reason": "實際來源混合官方與次級/AI來源",
        "metric_period_parsed_date": "2026-09-30",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "partially_verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "not_comparable",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "已宣告",
        "cross_run_previous_period": "2026Q3 (支付日為2026年10月15日)",
        "cross_run_previous_report_date": "20261007",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 有前值，但數值型態無法安全比較。"
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
    "missing_data": [
      {
        "ticker": "AXS-E",
        "priority": "P1",
        "missing_type": "metric_cross_run_consistency",
        "metric_name": "Catastrophe losses",
        "reason": "同 period / definition 前值=80，本次=$80 million；區間不重疊。",
        "risk_impact": "可能壓縮盈餘與資本。",
        "previous_value": "80",
        "current_value": "$80 million",
        "period": "2026Q2",
        "definition_scope": "",
        "calculation_basis": "",
        "acceptance_criteria": "以同一官方定義重新查核；若為不同口徑，改填不同 definition_scope / calculation_basis，不得覆寫。"
      }
    ],
    "dropped_old_events": [],
    "event_date_filter_summary": {
      "lookback_days": 14,
      "cutoff_date": "2026-10-03",
      "today": "2026-10-16",
      "kept_recent": 1,
      "kept_background": 0,
      "kept_unknown_date": 0,
      "dropped_old": 0
    },
    "metric_consistency_summary": {
      "conflict_count": 1,
      "conflicts": [
        {
          "ticker": "AXS-E",
          "metric_name": "Catastrophe losses",
          "metric_value": "$80 million",
          "missing_reason": "同 period / definition 前值=80，本次=$80 million；區間不重疊。",
          "verification_after_reconcile": "partially_verified",
          "cross_run_consistency_status": "value_changed_same_definition",
          "definition_scope": "",
          "calculation_basis": ""
        }
      ]
    }
  },
  {
    "target_name": "F-B",
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
    "dropped_old_events": [],
    "event_date_filter_summary": {
      "lookback_days": 14,
      "cutoff_date": "2026-10-03",
      "today": "2026-10-16",
      "kept_recent": 0,
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
        "ticker": "F-B",
        "priority": "P0",
        "missing_type": "metric_value",
        "metric_name": "Industrial free cash flow",
        "reason": "Stage 1 已主動搜尋，但尚未取得官方量化數值。",
        "risk_impact": "工業 FCF 是付息與維持信用評等的重要基礎。",
        "source_candidates": [
          "Ford Investor Relations",
          "SEC 10-Q",
          "SEC 10-K",
          "Ford Credit disclosures",
          "S&P",
          "Moody's",
          "Fitch"
        ],
        "acceptance_criteria": "下次報告 metric_data 中 F-B / Industrial free cash flow 應填入 value、period、source；若查無官方資料，需明確標示查詢來源與查無原因。",
        "resolution": "resolved_by_v13837_fb_company_adjusted_fcf_floor",
        "fb_fcf_official_floor_patch_version": "1.3.8.3.7"
      }
    ],
    "fb_fcf_definition_lock_patch_version": "1.3.8.3.7",
    "fb_fcf_official_floor_patch_version": "1.3.8.3.7",
    "fb_fcf_official_floor_applied_count": 1,
    "fb_fcf_official_floor_resolved_missing_count": 1,
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
        "cross_run_previous_report_date": "20261014",
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
        "cross_run_previous_report_date": "20261014",
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
        "cross_run_previous_report_date": "20261014",
        "cross_run_previous_definition_scope": "T-Mobile exchange debt assumption and residual Array UZD",
        "cross_run_previous_calculation_basis": "SEC transaction/debt disclosures",
        "cross_run_consistency_reason": "同 period / definition 與前一可信值一致。"
      }
    ],
    "missing_data": [],
    "dropped_old_events": [],
    "event_date_filter_summary": {
      "lookback_days": 14,
      "cutoff_date": "2026-10-03",
      "today": "2026-10-16",
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
      "latest_price": 17.639999,
      "price_as_of": "2026-10-15",
      "open": 17.549999237060547,
      "high": 17.7367000579834,
      "low": 17.549999237060547,
      "volume": 1951,
      "bid": null,
      "ask": null,
      "annual_interest": 1.5625,
      "current_yield": 8.8577,
      "quote_source": "Yahoo Finance chart (query1.finance.yahoo.com)",
      "source_host": "query1.finance.yahoo.com",
      "quote_status": "ok",
      "freshness_status": "fresh",
      "security_identity_status": "matched_symbol",
      "source_timestamp": 1792071000,
      "market_quote_patch_version": "1.3.7",
      "returned_symbol": "UZD",
      "currency": "USD",
      "exchange_name": "NYQ",
      "instrument_type": "EQUITY",
      "regular_market_price_meta": 17.64,
      "regular_market_time_meta": 1792092428,
      "reference_session_date": "2026-10-15",
      "weekday_gap": 0,
      "http_status": 200,
      "request_url": "https://query1.finance.yahoo.com/v8/finance/chart/UZD",
      "request_attempt": 1,
      "attempts": [
        {
          "source_host": "query1.finance.yahoo.com",
          "quote_status": "ok",
          "freshness_status": "fresh",
          "price_as_of": "2026-10-15",
          "latest_price": 17.639999,
          "error": null
        },
        {
          "source_host": "query2.finance.yahoo.com",
          "quote_status": "ok",
          "freshness_status": "fresh",
          "price_as_of": "2026-10-15",
          "latest_price": 17.639999,
          "error": null
        }
      ],
      "source_validation": "cross_checked",
      "source_crosscheck_price": 17.639999,
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

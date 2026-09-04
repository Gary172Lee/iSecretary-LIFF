# USPreferredStockDayInfo 每日情報報告

- 生成時間（台灣）：2026-09-04 08:19:04
- 對應 PDF：Stock_News_Report_20260904_081904.pdf
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

- 事件總分：正向3 / 負向0 / 總分+3
- 綜合分析：Lumen積極擴展Multi-Cloud Gateway服務以推動業務轉型，惟高額債務與再融資需求仍持續構成主要基本面風險。
- 事件 1：2026-09-02｜Lumen擴展Multi-Cloud Gateway服務至逾千萬企業地點，市場同時關注其債務風險｜recent_event
  - 影響：正向｜嚴重性：3｜信心度：高
  - 摘要：Lumen擴展雲端網絡服務推動轉型，惟市場持續評估其負債與再融資壓力。
  - 來源：Simply Wall St、BusinessWire、Stock Titan、Lumen Investor Relations
  - 日期過濾：kept_recent｜來源品質：official_ir｜驗證：verified

### 2. BHFAL

- 事件總分：正向0 / 負向0 / 總分+0
- 綜合分析：在指定日期範圍內無可報告的高可信相關事件。
- 事件：無

### 3. OPI

- 事件總分：正向0 / 負向4 / 總分-4
- 綜合分析：OPI第二季財報雖然營收有所增長，但辦公室資產組合出租率持續疲軟及面臨再融資壓力，顯著加劇其整體財務風險。
- 事件 1：2026-08-25｜市場解讀OPI第二季財報，對辦公室出租率下降與再融資風險存疑｜recent_event
  - 影響：負向｜嚴重性：4｜信心度：高
  - 摘要：OPI第二季財報營收雖成長，但出租率疲軟與再融資壓力引發市場疑慮。
  - 來源：Perplexity、TipRanks.com、Office Properties Income Trust (Investor Relations)、BusinessWire、The Motley Fool
  - 日期過濾：kept_recent｜來源品質：official_ir｜驗證：verified

### 4. AXS-E

- 事件總分：正向0 / 負向0 / 總分+0
- 綜合分析：在指定日期範圍內無可報告的高可信相關事件。
- 事件：無

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
- Credit rating / outlook｜狀態：已取得｜驗證：verified｜來源品質：rating_agency｜期間新鮮度：acceptable_recent｜門檻：downgrade、negative outlook 或 selective default 評論需警戒。
- 資料缺口：1 項，關鍵資料缺漏時不可判定為綠燈。

### BHFAL 量化監控
- RBC ratio｜狀態：已取得｜驗證：verified｜來源品質：official_ir｜期間新鮮度：fresh｜門檻：低於 400% 黃燈；低於 350% 橙燈/紅燈；單季大幅下滑需警戒。
- Statutory capital and surplus｜狀態：已取得｜驗證：partially_verified｜來源品質：official_ir｜期間新鮮度：fresh｜門檻：連續下降或重大減損需警戒。
- Holding company cash and liquid assets｜狀態：已取得｜驗證：partially_verified｜來源品質：official_ir｜期間新鮮度：fresh｜門檻：低於未來 12 個月利息與固定支出覆蓋需求需警戒。
- Financial leverage｜狀態：資料不足｜驗證：data_missing｜來源品質：unknown｜期間新鮮度：unknown_period｜門檻：槓桿升高或評等機構負面評論需警戒。
- Credit rating / outlook｜狀態：已取得｜驗證：verified｜來源品質：rating_agency｜期間新鮮度：acceptable_recent｜門檻：negative outlook、downgrade 或 watch negative 需警戒。
- BHFAL interest payment status｜狀態：已取得｜驗證：verified｜來源品質：official_ir｜期間新鮮度：fresh｜門檻：defer、suspend、delay、non-payment 立即紅燈。
- Aquarian merger / change-of-control treatment｜狀態：資料不足｜驗證：data_missing｜來源品質：unknown｜期間新鮮度：unknown_period｜門檻：未明確說明 BHFAL 存續、掛牌、贖回或付息條款時列資料不足。
- 資料缺口：5 項，關鍵資料缺漏時不可判定為綠燈。

### OPI 量化監控
- Occupancy rate｜狀態：已取得｜驗證：verified｜來源品質：official_ir｜期間新鮮度：fresh｜門檻：連續下降或低於同業顯著水準需警戒。
- AFFO / FFO｜狀態：已取得｜驗證：partially_verified｜來源品質：official_ir｜期間新鮮度：fresh｜門檻：AFFO/FFO 大幅下滑或為負需警戒。
- Debt maturity schedule｜狀態：已取得｜驗證：partially_verified｜來源品質：official_ir｜期間新鮮度：fresh｜門檻：12-24 個月內大量到期且流動性不足需紅燈。
- Liquidity / cash availability｜狀態：已取得｜驗證：verified｜來源品質：official_ir｜期間新鮮度：fresh｜門檻：流動性不足或 covenant 壓力需警戒。
- 資料缺口：2 項，關鍵資料缺漏時不可判定為綠燈。

### AXS-E 量化監控
- Combined ratio｜狀態：資料不足｜驗證：data_missing｜來源品質：unknown｜期間新鮮度：unknown_period｜門檻：高於 100% 或明顯惡化需警戒。
- Catastrophe losses｜狀態：資料不足｜驗證：data_missing｜來源品質：unknown｜期間新鮮度：unknown_period｜門檻：重大巨災損失超預期需警戒。
- Preferred dividend status｜狀態：資料不足｜驗證：data_missing｜來源品質：unknown｜期間新鮮度：unknown_period｜門檻：defer、suspend、delay 立即紅燈。
- 資料缺口：3 項，關鍵資料缺漏時不可判定為綠燈。

### F-B 量化監控
- Industrial free cash flow｜狀態：資料不足｜驗證：data_missing｜來源品質：unknown｜期間新鮮度：unknown_period｜門檻：FCF 轉負或全年指引大幅下修需警戒。
- Ford Credit delinquencies / credit losses｜狀態：資料不足｜驗證：data_missing｜來源品質：unknown｜期間新鮮度：unknown_period｜門檻：逾期率或信用損失準備明顯上升需警戒。
- Recall / warranty cost｜狀態：資料不足｜驗證：data_missing｜來源品質：unknown｜期間新鮮度：unknown_period｜門檻：重大召回或保固成本升高需警戒。
- 資料缺口：5 項，關鍵資料缺漏時不可判定為綠燈。

### UZD 量化監控
- Issuer / guarantor status｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：發行人或擔保人不明確時列灰燈/黃燈，不可判定安全。
- Asset sale proceeds and use of funds｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：出售所得若大量分配給股東而非減債需警戒。
- Debt assumption / redemption status｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：未說明承擔、契約修改或贖回時列資料不足。

## 程式端日期過濾與來源驗證

- 日期過濾版本：1.2.2
- 最近事件保留天數：14 天
- 說明：超出最近 14 日但命中 Chapter 11、收購、重整、退市、債務交換等重大關鍵字者，會保留為 background_risk_event；其他舊事件移至 dropped_old_events。

- CTGG：recent=1，background=0，unknown_date=0，dropped_old=0
- BHFAL：recent=0，background=0，unknown_date=0，dropped_old=0
- OPI：recent=1，background=0，unknown_date=0，dropped_old=0
- AXS-E：recent=0，background=0，unknown_date=0，dropped_old=0
- F-B：recent=0，background=0，unknown_date=0，dropped_old=0
- UZD：recent=0，background=0，unknown_date=0，dropped_old=0

## 完整 JSON

```json
[
  {
    "target_name": "CTGG",
    "events": [
      {
        "date": "2026-09-02",
        "title": "Lumen擴展Multi-Cloud Gateway服務至逾千萬企業地點，市場同時關注其債務風險",
        "impact_direction": "正向",
        "impact_severity": 3,
        "confidence": "高",
        "summary_30": "Lumen擴展雲端網絡服務推動轉型，惟市場持續評估其負債與再融資壓力。",
        "links": [
          "Simply Wall St",
          "BusinessWire",
          "Stock Titan",
          "Lumen Investor Relations"
        ],
        "event_source_quality": "official_ir",
        "event_source_quality_details": [
          "official_ir",
          "press_release",
          "secondary_site"
        ],
        "event_verification_status": "verified",
        "event_days_old": 2,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event",
        "merged_duplicate_count": 1
      }
    ],
    "綜合分析": "Lumen積極擴展Multi-Cloud Gateway服務以推動業務轉型，惟高額債務與再融資需求仍持續構成主要基本面風險。",
    "事件總分": "正向3 / 負向0 / 總分+3",
    "new_sources_found": [
      "Simply Wall St",
      "Stock Titan",
      "Lumen Investor Relations"
    ],
    "event_merge_source": "ai_stage2",
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
        "cross_run_previous_report_date": "20260903",
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
        "value": "2051年到期，完全由Lumen擔保",
        "unit": "status/date/USD",
        "period": "2026年6月 (交換要約完成)",
        "status": "已取得",
        "confidence": "高",
        "source": "Qwest Corporation SEC Filing, Business Wire, Investing.com",
        "source_url_or_name": "SEC Filing",
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
        "note": "CTGG是Qwest Corporation於2026年6月交換要約中發行的新債券，具6.500%票息，並由Lumen Technologies完全無條件擔保。Q2 2026報告顯示公司總長期債務降至132.06億美元，透過資產出售收益及發行新債券，贖回了超優先票據、定期貸款及各種擔保證券，改善了債務結構。",
        "source_quality_primary": "sec_filing",
        "source_quality": "sec_filing",
        "source_quality_details": [
          "sec_filing",
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
        "metric_period_type": "month_or_month_range",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "partially_verified",
        "metric_consistency_status": "cross_run_conflict",
        "metric_consistency_reason": "同 period / definition 前值=Qwest Corporation已於2026年6月完成債務交換要約，將2056年及2057年到期票據交換為新的2051年及2052年到期票據。這些新票據為Qwest的高級無擔保債務，並由Lumen Technologies無條件擔保。，本次=2051年到期，完全由Lumen擔保；區間不重疊。",
        "cross_run_consistency_status": "value_changed_same_definition",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "Qwest Corporation已於2026年6月完成債務交換要約，將2056年及2057年到期票據交換為新的2051年及2052年到期票據。這些新票據為Qwest的高級無擔保債務，並由Lumen Technologies無條件擔保。",
        "cross_run_previous_period": "2026年6月",
        "cross_run_previous_report_date": "20260901",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 前值=Qwest Corporation已於2026年6月完成債務交換要約，將2056年及2057年到期票據交換為新的2051年及2052年到期票據。這些新票據為Qwest的高級無擔保債務，並由Lumen Technologies無條件擔保。，本次=2051年到期，完全由Lumen擔保；區間不重疊。"
      },
      {
        "ticker": "CTGG",
        "metric_name": "Credit rating / outlook",
        "metric_category": "信用評等",
        "value": "Moody's B2 (穩定), S&P B- (發行人), S&P B (高級無擔保債務), Fitch B (長期發行人違約評等)",
        "unit": "rating",
        "period": "2026年2月",
        "status": "已取得",
        "confidence": "高",
        "source": "Moody's Ratings, S&P Global Ratings, Fitch Ratings, BusinessWire, Telecompaper, Investing.com",
        "source_url_or_name": "Moody's Ratings",
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
        "note": "所有三大評級機構於2026年2月均上調Lumen的信用評級，並給予穩定展望，反映公司在出售大眾市場業務後顯著去槓桿化、流動性改善及債務期限延長。",
        "source_quality_primary": "rating_agency",
        "source_quality": "rating_agency",
        "source_quality_details": [
          "rating_agency",
          "press_release"
        ],
        "source_candidate_quality_details": [
          "sec_filing",
          "official_ir",
          "rating_agency"
        ],
        "source_conflict_flag": false,
        "source_conflict_reason": "",
        "metric_period_parsed_date": "2026-02-28",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "month_or_month_range",
        "metric_period_freshness": "acceptable_recent",
        "metric_integrity_status": "pass",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "not_comparable",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "Moody's: B2 (穩定); Fitch: B (穩定); S&P: B- (穩定)",
        "cross_run_previous_period": "2026年2月",
        "cross_run_previous_report_date": "20260826",
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
        "reason": "同 period / definition 前值=Qwest Corporation已於2026年6月完成債務交換要約，將2056年及2057年到期票據交換為新的2051年及2052年到期票據。這些新票據為Qwest的高級無擔保債務，並由Lumen Technologies無條件擔保。，本次=2051年到期，完全由Lumen擔保；區間不重疊。",
        "risk_impact": "可能削弱 CTGG 債權保護。",
        "previous_value": "Qwest Corporation已於2026年6月完成債務交換要約，將2056年及2057年到期票據交換為新的2051年及2052年到期票據。這些新票據為Qwest的高級無擔保債務，並由Lumen Technologies無條件擔保。",
        "current_value": "2051年到期，完全由Lumen擔保",
        "period": "2026年6月 (交換要約完成)",
        "definition_scope": "",
        "calculation_basis": "",
        "acceptance_criteria": "以同一官方定義重新查核；若為不同口徑，改填不同 definition_scope / calculation_basis，不得覆寫。"
      }
    ],
    "dropped_old_events": [],
    "event_date_filter_summary": {
      "lookback_days": 14,
      "cutoff_date": "2026-08-22",
      "today": "2026-09-04",
      "kept_recent": 1,
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
          "metric_value": "2051年到期，完全由Lumen擔保",
          "missing_reason": "同 period / definition 前值=Qwest Corporation已於2026年6月完成債務交換要約，將2056年及2057年到期票據交換為新的2051年及2052年到期票據。這些新票據為Qwest的高級無擔保債務，並由Lumen Technologies無條件擔保。，本次=2051年到期，完全由Lumen擔保；區間不重疊。",
          "verification_after_reconcile": "partially_verified",
          "cross_run_consistency_status": "value_changed_same_definition",
          "definition_scope": "",
          "calculation_basis": ""
        }
      ]
    },
    "excluded_low_trust_event_count": 0,
    "merged_duplicate_event_count": 0,
    "event_dedup_patch_version": "1.3.3"
  },
  {
    "target_name": "BHFAL",
    "events": [],
    "綜合分析": "在指定日期範圍內無可報告的高可信相關事件。",
    "事件總分": "正向0 / 負向0 / 總分+0",
    "new_sources_found": [],
    "event_merge_source": "ai_stage2",
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
        "source": "Brighthouse Financial Q2 2026 Earnings Release / Financial Supplement",
        "source_url_or_name": "Business Wire, Morningstar, Brighthouse Financial Investor Relations",
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
        "note": "截至 2026 年 6 月 30 日的初步法定結果；處於公司目標區間 400% 至 450% 的上限。",
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
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "verified",
        "definition_scope": "Brighthouse insurance subsidiaries (combined)",
        "calculation_basis": "NAIC combined risk-based capital ratio",
        "measurement_form": "range",
        "source_period_alignment_status": "q2_asof_evidence_present",
        "source_period_evidence": "Brighthouse Financial Q2 2026 Earnings Release / Financial Supplement | Business Wire, Morningstar, Brighthouse Financial Investor Relations | 截至 2026 年 6 月 30 日的初步法定結果；處於公司目標區間 400% 至 450% 的上限。",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "consistent_same_definition",
        "cross_run_previous_value": "430%-450%",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260902",
        "cross_run_previous_definition_scope": "Brighthouse insurance subsidiaries (combined)",
        "cross_run_previous_calculation_basis": "NAIC combined risk-based capital ratio",
        "cross_run_consistency_reason": "同 period / definition 與前一可信值一致。"
      },
      {
        "ticker": "BHFAL",
        "metric_name": "Statutory capital and surplus",
        "metric_category": "法定資本",
        "value": "$4.9 billion",
        "unit": "USD",
        "period": "2026Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "Brighthouse Financial Q2 2026 Earnings Release / Financial Supplement",
        "source_url_or_name": "Business Wire, Morningstar, Brighthouse Financial Investor Relations",
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
        "note": "截至 2026 年 6 月 30 日的初步法定結果；與 2026 年 3 月 31 日相比大致持平。",
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
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "partially_verified",
        "metric_consistency_status": "cross_run_conflict",
        "metric_consistency_reason": "同 period / definition 前值=6.8 billion，本次=$4.9 billion；區間不重疊。",
        "cross_run_consistency_status": "value_changed_same_definition",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "6.8 billion",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260818",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 前值=6.8 billion，本次=$4.9 billion；區間不重疊。"
      },
      {
        "ticker": "BHFAL",
        "metric_name": "Holding company cash and liquid assets",
        "metric_category": "控股公司流動性",
        "value": "$0.9 billion",
        "unit": "USD",
        "period": "2026Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "Brighthouse Financial Q2 2026 Earnings Release / Financial Supplement",
        "source_url_or_name": "Business Wire, Morningstar, Brighthouse Financial Investor Relations",
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
        "note": "截至 2026 年 6 月 30 日，包含 Brighthouse Financial, Inc.、Brighthouse Holdings, LLC 和 Brighthouse Services, LLC 的流動資產。",
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
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "partially_verified",
        "definition_scope": "Brighthouse holding company group",
        "calculation_basis": "holding company liquid assets",
        "measurement_form": "point",
        "source_period_alignment_status": "q2_asof_evidence_present",
        "source_period_evidence": "Brighthouse Financial Q2 2026 Earnings Release / Financial Supplement | Business Wire, Morningstar, Brighthouse Financial Investor Relations | 截至 2026 年 6 月 30 日，包含 Brighthouse Financial, Inc.、Brighthouse Holdings, LLC 和 Brighthouse Servic…",
        "metric_consistency_status": "cross_run_conflict",
        "metric_consistency_reason": "同 period / definition 前值=1.3 billion，本次=$0.9 billion；區間不重疊。",
        "cross_run_consistency_status": "value_changed_same_definition",
        "cross_run_previous_value": "1.3 billion",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260818",
        "cross_run_previous_definition_scope": "Brighthouse holding company group",
        "cross_run_previous_calculation_basis": "holding company liquid assets",
        "cross_run_consistency_reason": "同 period / definition 前值=1.3 billion，本次=$0.9 billion；區間不重疊。"
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
        "cross_run_previous_report_date": "20260903",
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
        "value": "Current",
        "unit": "status",
        "period": "2026Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "Brighthouse Financial Q2 2026 Earnings Release",
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
        "warning_threshold": "defer、suspend、delay、non-payment 立即紅燈。",
        "priority": "P0",
        "risk_impact": "直接影響退休現金流。",
        "note": "公司在 2026 年 8 月宣佈將於 9 月支付優先股股息，此舉通常預示次順位債券利息支付無虞。",
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
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "not_comparable",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "正常",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260901",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 有前值，但數值型態無法安全比較。"
      },
      {
        "ticker": "BHFAL",
        "metric_name": "Aquarian merger / change-of-control treatment",
        "metric_category": "交易條款",
        "value": null,
        "unit": "status",
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
        "warning_threshold": "未明確說明 BHFAL 存續、掛牌、贖回或付息條款時列資料不足。",
        "priority": "P0",
        "risk_impact": "收購完成後可能影響掛牌、流動性與資本政策。",
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
        "missing_type": "metric_value",
        "metric_name": "Aquarian merger / change-of-control treatment",
        "reason": "Stage 1 已主動搜尋，但尚未取得官方量化數值。",
        "risk_impact": "收購完成後可能影響掛牌、流動性與資本政策。",
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
        "acceptance_criteria": "下次報告 metric_data 中 BHFAL / Aquarian merger / change-of-control treatment 應填入 value、period、source；若查無官方資料，需明確標示查詢來源與查無原因。"
      },
      {
        "ticker": "BHFAL",
        "priority": "P0",
        "missing_type": "specific_terms_post_merger",
        "metric_name": "Aquarian merger / change-of-control treatment",
        "reason": "最近 14 日內，未有針對 BHFAL 次順位債在 Aquarian 收購後之存續、掛牌、贖回或付息條款的明確公告。雖然優先股有條款說明其將繼續存在，但次順位債務的具體安排未被明確提及。",
        "risk_impact": "收購完成後，BHFAL 的掛牌、流動性與資本政策可能受到影響，具體條款不明會增加債券持有人的不確定性。",
        "source_candidates": [
          "Brighthouse Financial SEC filings (如 8-K, 10-K, 10-Q)",
          "收購方 Aquarian Capital 公告",
          "評等機構特別報告"
        ],
        "acceptance_criteria": "需找到明確說明 BHFAL 次順位債在收購後如何處理的官方文件或權威媒體報導。"
      },
      {
        "ticker": "BHFAL",
        "priority": "P0",
        "missing_type": "metric_cross_run_consistency",
        "metric_name": "Statutory capital and surplus",
        "reason": "同 period / definition 前值=6.8 billion，本次=$4.9 billion；區間不重疊。",
        "risk_impact": "法定資本下降會削弱保險子公司分派能力與控股公司資金來源。",
        "previous_value": "6.8 billion",
        "current_value": "$4.9 billion",
        "period": "2026Q2",
        "definition_scope": "",
        "calculation_basis": "",
        "acceptance_criteria": "以同一官方定義重新查核；若為不同口徑，改填不同 definition_scope / calculation_basis，不得覆寫。"
      },
      {
        "ticker": "BHFAL",
        "priority": "P0",
        "missing_type": "metric_cross_run_consistency",
        "metric_name": "Holding company cash and liquid assets",
        "reason": "同 period / definition 前值=1.3 billion，本次=$0.9 billion；區間不重疊。",
        "risk_impact": "控股公司流動性不足可能影響 BHFAL 利息支付。",
        "previous_value": "1.3 billion",
        "current_value": "$0.9 billion",
        "period": "2026Q2",
        "definition_scope": "Brighthouse holding company group",
        "calculation_basis": "holding company liquid assets",
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
      "cutoff_date": "2026-08-22",
      "today": "2026-09-04",
      "kept_recent": 0,
      "kept_background": 0,
      "kept_unknown_date": 0,
      "dropped_old": 0
    },
    "metric_consistency_summary": {
      "conflict_count": 2,
      "conflicts": [
        {
          "ticker": "BHFAL",
          "metric_name": "Statutory capital and surplus",
          "metric_value": "$4.9 billion",
          "missing_reason": "同 period / definition 前值=6.8 billion，本次=$4.9 billion；區間不重疊。",
          "verification_after_reconcile": "partially_verified",
          "cross_run_consistency_status": "value_changed_same_definition",
          "definition_scope": "",
          "calculation_basis": ""
        },
        {
          "ticker": "BHFAL",
          "metric_name": "Holding company cash and liquid assets",
          "metric_value": "$0.9 billion",
          "missing_reason": "同 period / definition 前值=1.3 billion，本次=$0.9 billion；區間不重疊。",
          "verification_after_reconcile": "partially_verified",
          "cross_run_consistency_status": "value_changed_same_definition",
          "definition_scope": "Brighthouse holding company group",
          "calculation_basis": "holding company liquid assets"
        }
      ]
    },
    "excluded_low_trust_event_count": 0,
    "merged_duplicate_event_count": 0,
    "event_dedup_patch_version": "1.3.3",
    "market_quote": {
      "ticker": "BHFAL",
      "security_name_expected": "Brighthouse Financial 6.25% Junior Subordinated Debentures due 2058",
      "exchange_expected": "NASDAQ",
      "latest_price": 15.25,
      "price_as_of": "2026-09-03",
      "open": 15.220000267028809,
      "high": 15.390000343322754,
      "low": 15.220000267028809,
      "volume": 36880,
      "bid": null,
      "ask": null,
      "annual_interest": 1.5625,
      "current_yield": 10.2459,
      "quote_source": "Yahoo Finance chart (query1.finance.yahoo.com)",
      "source_host": "query1.finance.yahoo.com",
      "quote_status": "ok",
      "freshness_status": "fresh",
      "security_identity_status": "matched_symbol",
      "source_timestamp": 1788442200,
      "market_quote_patch_version": "1.3.7",
      "returned_symbol": "BHFAL",
      "currency": "USD",
      "exchange_name": "NMS",
      "instrument_type": "EQUITY",
      "regular_market_price_meta": 15.25,
      "regular_market_time_meta": 1788465600,
      "reference_session_date": "2026-09-03",
      "weekday_gap": 0,
      "http_status": 200,
      "request_url": "https://query1.finance.yahoo.com/v8/finance/chart/BHFAL",
      "request_attempt": 1,
      "attempts": [
        {
          "source_host": "query1.finance.yahoo.com",
          "quote_status": "ok",
          "freshness_status": "fresh",
          "price_as_of": "2026-09-03",
          "latest_price": 15.25,
          "error": null
        },
        {
          "source_host": "query2.finance.yahoo.com",
          "quote_status": "ok",
          "freshness_status": "fresh",
          "price_as_of": "2026-09-03",
          "latest_price": 15.25,
          "error": null
        }
      ],
      "source_validation": "cross_checked",
      "source_crosscheck_price": 15.25,
      "source_crosscheck_host": "query2.finance.yahoo.com",
      "source_conflict_pct": 0.0
    }
  },
  {
    "target_name": "OPI",
    "events": [
      {
        "date": "2026-08-25",
        "title": "市場解讀OPI第二季財報，對辦公室出租率下降與再融資風險存疑",
        "impact_direction": "負向",
        "impact_severity": 4,
        "confidence": "高",
        "summary_30": "OPI第二季財報營收雖成長，但出租率疲軟與再融資壓力引發市場疑慮。",
        "links": [
          "Perplexity",
          "TipRanks.com",
          "Office Properties Income Trust (Investor Relations)",
          "BusinessWire",
          "The Motley Fool"
        ],
        "event_source_quality": "official_ir",
        "event_source_quality_details": [
          "official_ir",
          "press_release",
          "secondary_site",
          "ai_summary"
        ],
        "event_verification_status": "verified",
        "event_days_old": 10,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event",
        "merged_duplicate_count": 1
      }
    ],
    "綜合分析": "OPI第二季財報雖然營收有所增長，但辦公室資產組合出租率持續疲軟及面臨再融資壓力，顯著加劇其整體財務風險。",
    "事件總分": "正向0 / 負向4 / 總分-4",
    "new_sources_found": [
      "Perplexity",
      "TipRanks.com",
      "Office Properties Income Trust (Investor Relations)",
      "The Motley Fool"
    ],
    "event_merge_source": "ai_stage2",
    "metric_data": [
      {
        "ticker": "OPI",
        "metric_name": "Occupancy rate",
        "metric_category": "出租率",
        "value": "77.9%",
        "unit": "%",
        "period": "2026Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "Office Properties Income Trust Q2 2026 Earnings Call Transcript",
        "source_url_or_name": "Office Properties Income Trust (Investor Relations)",
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
        "note": "整體投資組合出租率。",
        "source_quality_primary": "official_ir",
        "source_quality": "official_ir",
        "source_quality_details": [
          "official_ir"
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
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "consistent_with_prior_range",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "77.9% (整體組合), 88.7% (同物業組合)",
        "cross_run_previous_period": "2026 Q2 (截至6月30日)",
        "cross_run_previous_report_date": "20260901",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 數值表達不同，但目前值落在前一可信區間內。"
      },
      {
        "ticker": "OPI",
        "metric_name": "AFFO / FFO",
        "metric_category": "現金流",
        "value": "19000000",
        "unit": "USD",
        "period": "2026Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "Office Properties Income Trust Q2 2026 Earnings Call Transcript",
        "source_url_or_name": "Office Properties Income Trust (Investor Relations)",
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
        "note": "第二季 Normalized FFO。",
        "source_quality_primary": "official_ir",
        "source_quality": "official_ir",
        "source_quality_details": [
          "official_ir"
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
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "partially_verified",
        "metric_consistency_status": "cross_run_conflict",
        "metric_consistency_reason": "同 period / definition 前值=19.0，本次=19000000；區間不重疊。",
        "cross_run_consistency_status": "value_changed_same_definition",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "19.0",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260818",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 前值=19.0，本次=19000000；區間不重疊。"
      },
      {
        "ticker": "OPI",
        "metric_name": "Debt maturity schedule",
        "metric_category": "債務到期牆",
        "value": "$1.7B (總債務); $425M (2027年1月到期信貸額度); $15M (2026年11月1日到期); $30M (2027年2月1日到期)",
        "unit": "USD/date",
        "period": "2026Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "Office Properties Income Trust Q2 2026 Earnings Call Transcript",
        "source_url_or_name": "Office Properties Income Trust (Investor Relations)",
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
        "note": "總債務為重整後金額，信貸額度及部分擔保票據有近期到期款項。",
        "source_quality_primary": "official_ir",
        "source_quality": "official_ir",
        "source_quality_details": [
          "official_ir"
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
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "partially_verified",
        "metric_consistency_status": "cross_run_conflict",
        "metric_consistency_reason": "同 period / definition 前值=425M (Jan 2027), 300M (Mar 2029), 385M (Dec 2029), 420M (Jun 2031)，本次=$1.7B (總債務); $425M (2027年1月到期信貸額度); $15M (2026年11月1日到期); $30M (2027年2月1日到期)；區間不重疊。",
        "cross_run_consistency_status": "value_changed_same_definition",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "425M (Jan 2027), 300M (Mar 2029), 385M (Dec 2029), 420M (Jun 2031)",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260817",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 前值=425M (Jan 2027), 300M (Mar 2029), 385M (Dec 2029), 420M (Jun 2031)，本次=$1.7B (總債務); $425M (2027年1月到期信貸額度); $15M (2026年11月1日到期); $30M (2027年2月1日到期)；區間不重疊。"
      },
      {
        "ticker": "OPI",
        "metric_name": "Liquidity / cash availability",
        "metric_category": "流動性",
        "value": "51000000 ( unrestricted ); 53000000 ( restricted )",
        "unit": "USD",
        "period": "2026Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "Office Properties Income Trust Q2 2026 Earnings Call Transcript",
        "source_url_or_name": "Office Properties Income Trust (Investor Relations)",
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
        "note": "截至2026年6月30日之數字。",
        "source_quality_primary": "official_ir",
        "source_quality": "official_ir",
        "source_quality_details": [
          "official_ir"
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
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "consistent_with_prior_range",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "51百萬美元 (非限制性現金)",
        "cross_run_previous_period": "2026Q2 (截至6月30日)",
        "cross_run_previous_report_date": "20260828",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 數值表達不同，但目前值落在前一可信區間內。"
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
        "missing_type": "metric_cross_run_consistency",
        "metric_name": "AFFO / FFO",
        "reason": "同 period / definition 前值=19.0，本次=19000000；區間不重疊。",
        "risk_impact": "REIT 配息與債務服務能力核心指標。",
        "previous_value": "19.0",
        "current_value": "19000000",
        "period": "2026Q2",
        "definition_scope": "",
        "calculation_basis": "",
        "acceptance_criteria": "以同一官方定義重新查核；若為不同口徑，改填不同 definition_scope / calculation_basis，不得覆寫。"
      },
      {
        "ticker": "OPI",
        "priority": "P0",
        "missing_type": "metric_cross_run_consistency",
        "metric_name": "Debt maturity schedule",
        "reason": "同 period / definition 前值=425M (Jan 2027), 300M (Mar 2029), 385M (Dec 2029), 420M (Jun 2031)，本次=$1.7B (總債務); $425M (2027年1月到期信貸額度); $15M (2026年11月1日到期); $30M (2027年2月1日到期)；區間不重疊。",
        "risk_impact": "再融資失敗可能導致重整或資產賤售。",
        "previous_value": "425M (Jan 2027), 300M (Mar 2029), 385M (Dec 2029), 420M (Jun 2031)",
        "current_value": "$1.7B (總債務); $425M (2027年1月到期信貸額度); $15M (2026年11月1日到期); $30M (2027年2月1日到期)",
        "period": "2026Q2",
        "definition_scope": "",
        "calculation_basis": "",
        "acceptance_criteria": "以同一官方定義重新查核；若為不同口徑，改填不同 definition_scope / calculation_basis，不得覆寫。"
      }
    ],
    "dropped_old_events": [],
    "event_date_filter_summary": {
      "lookback_days": 14,
      "cutoff_date": "2026-08-22",
      "today": "2026-09-04",
      "kept_recent": 1,
      "kept_background": 0,
      "kept_unknown_date": 0,
      "dropped_old": 0
    },
    "metric_consistency_summary": {
      "conflict_count": 2,
      "conflicts": [
        {
          "ticker": "OPI",
          "metric_name": "AFFO / FFO",
          "metric_value": "19000000",
          "missing_reason": "同 period / definition 前值=19.0，本次=19000000；區間不重疊。",
          "verification_after_reconcile": "partially_verified",
          "cross_run_consistency_status": "value_changed_same_definition",
          "definition_scope": "",
          "calculation_basis": ""
        },
        {
          "ticker": "OPI",
          "metric_name": "Debt maturity schedule",
          "metric_value": "$1.7B (總債務); $425M (2027年1月到期信貸額度); $15M (2026年11月1日到期); $30M (2027年2月1日到期)",
          "missing_reason": "同 period / definition 前值=425M (Jan 2027), 300M (Mar 2029), 385M (Dec 2029), 420M (Jun 2031)，本次=$1.7B (總債務); $425M (2027年1月到期信貸額度); $15M (2026年11月1日到期); $30M (2027年2月1日到期)；區間不重疊。",
          "verification_after_reconcile": "partially_verified",
          "cross_run_consistency_status": "value_changed_same_definition",
          "definition_scope": "",
          "calculation_basis": ""
        }
      ]
    },
    "excluded_low_trust_event_count": 0,
    "merged_duplicate_event_count": 0,
    "event_dedup_patch_version": "1.3.3"
  },
  {
    "target_name": "AXS-E",
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
    "metric_data": [
      {
        "ticker": "AXS-E",
        "metric_name": "Combined ratio",
        "metric_category": "承保獲利",
        "value": null,
        "unit": "%",
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
        "warning_threshold": "高於 100% 或明顯惡化需警戒。",
        "priority": "P1",
        "risk_impact": "承保虧損會削弱資本與優先股安全邊際。",
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
        "value": null,
        "unit": "status",
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
        "warning_threshold": "defer、suspend、delay 立即紅燈。",
        "priority": "P0",
        "risk_impact": "直接影響退休現金流。",
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
      }
    ],
    "missing_data": [
      {
        "ticker": "AXS-E",
        "priority": "P1",
        "missing_type": "metric_value",
        "metric_name": "Combined ratio",
        "reason": "Stage 1 已主動搜尋，但尚未取得官方量化數值。",
        "risk_impact": "承保虧損會削弱資本與優先股安全邊際。",
        "source_candidates": [
          "AXIS Investor Relations",
          "SEC 10-Q",
          "SEC 10-K",
          "Earnings Release",
          "AM Best",
          "S&P"
        ],
        "acceptance_criteria": "下次報告 metric_data 中 AXS-E / Combined ratio 應填入 value、period、source；若查無官方資料，需明確標示查詢來源與查無原因。"
      },
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
      },
      {
        "ticker": "AXS-E",
        "priority": "P0",
        "missing_type": "metric_value",
        "metric_name": "Preferred dividend status",
        "reason": "Stage 1 已主動搜尋，但尚未取得官方量化數值。",
        "risk_impact": "直接影響退休現金流。",
        "source_candidates": [
          "AXIS Investor Relations",
          "SEC 10-Q",
          "SEC 10-K",
          "Earnings Release",
          "AM Best",
          "S&P"
        ],
        "acceptance_criteria": "下次報告 metric_data 中 AXS-E / Preferred dividend status 應填入 value、period、source；若查無官方資料，需明確標示查詢來源與查無原因。"
      }
    ],
    "dropped_old_events": [],
    "event_date_filter_summary": {
      "lookback_days": 14,
      "cutoff_date": "2026-08-22",
      "today": "2026-09-04",
      "kept_recent": 0,
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
        "metric_category": "工業現金流",
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
        "warning_threshold": "FCF 轉負或全年指引大幅下修需警戒。",
        "priority": "P0",
        "risk_impact": "工業 FCF 是付息與維持信用評等的重要基礎。",
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
        "acceptance_criteria": "下次報告 metric_data 中 F-B / Industrial free cash flow 應填入 value、period、source；若查無官方資料，需明確標示查詢來源與查無原因。"
      },
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
      "cutoff_date": "2026-08-22",
      "today": "2026-09-04",
      "kept_recent": 0,
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
        "cross_run_previous_report_date": "20260903",
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
        "cross_run_previous_report_date": "20260903",
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
        "cross_run_previous_report_date": "20260903",
        "cross_run_previous_definition_scope": "T-Mobile exchange debt assumption and residual Array UZD",
        "cross_run_previous_calculation_basis": "SEC transaction/debt disclosures",
        "cross_run_consistency_reason": "同 period / definition 與前一可信值一致。"
      }
    ],
    "missing_data": [],
    "dropped_old_events": [],
    "event_date_filter_summary": {
      "lookback_days": 14,
      "cutoff_date": "2026-08-22",
      "today": "2026-09-04",
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
      "latest_price": 18.860001,
      "price_as_of": "2026-09-03",
      "open": 18.950000762939453,
      "high": 18.920000076293945,
      "low": 18.72010040283203,
      "volume": 13517,
      "bid": null,
      "ask": null,
      "annual_interest": 1.5625,
      "current_yield": 8.2847,
      "quote_source": "Yahoo Finance chart (query1.finance.yahoo.com)",
      "source_host": "query1.finance.yahoo.com",
      "quote_status": "ok",
      "freshness_status": "fresh",
      "security_identity_status": "matched_symbol",
      "source_timestamp": 1788442200,
      "market_quote_patch_version": "1.3.7",
      "returned_symbol": "UZD",
      "currency": "USD",
      "exchange_name": "NYQ",
      "instrument_type": "EQUITY",
      "regular_market_price_meta": 18.86,
      "regular_market_time_meta": 1788464194,
      "reference_session_date": "2026-09-03",
      "weekday_gap": 0,
      "http_status": 200,
      "request_url": "https://query1.finance.yahoo.com/v8/finance/chart/UZD",
      "request_attempt": 1,
      "attempts": [
        {
          "source_host": "query1.finance.yahoo.com",
          "quote_status": "ok",
          "freshness_status": "fresh",
          "price_as_of": "2026-09-03",
          "latest_price": 18.860001,
          "error": null
        },
        {
          "source_host": "query2.finance.yahoo.com",
          "quote_status": "ok",
          "freshness_status": "fresh",
          "price_as_of": "2026-09-03",
          "latest_price": 18.860001,
          "error": null
        }
      ],
      "source_validation": "cross_checked",
      "source_crosscheck_price": 18.860001,
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

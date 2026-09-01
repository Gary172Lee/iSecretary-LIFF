# USPreferredStockDayInfo 每日情報報告

- 生成時間（台灣）：2026-09-01 10:13:12
- 對應 PDF：Stock_News_Report_20260901_101312.pdf
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

- 事件總分：正向2 / 負向0 / 總分+2
- 綜合分析：該標的受惠於擴大雲網路服務至全美逾千萬商業據點，有助於強化市場滲透率並提升中長期營運成長動能。
- 事件 1：2026-08-26｜Lumen擴展美國雲網路服務覆蓋至逾千萬商業據點｜recent_event
  - 影響：正向｜嚴重性：2｜信心度：高
  - 摘要：Lumen宣佈擴大雲網路服務，覆蓋全美逾千萬商業地點，強化市場滲透。
  - 來源：Lumen Investor Relations
  - 日期過濾：kept_recent｜來源品質：official_ir｜驗證：verified

### 2. BHFAL

- 事件總分：正向0 / 負向5 / 總分-5
- 綜合分析：受第二季財報遜於預期及Aquarian收購案面臨監管審查不確定性之雙重影響，該標的短期估值與股價面臨下行壓力。
- 事件 1：2026-08-29｜市場持續擔憂Aquarian收購案監管審查風險及股價波動｜recent_event
  - 影響：負向｜嚴重性：3｜信心度：中
  - 摘要：市場持續關注Aquarian併購案之監管審查風險並引發股價震盪，惟公司獨立財務狀況仍屬穩健。
  - 來源：Seeking Alpha
  - 日期過濾：kept_recent｜來源品質：secondary_site｜驗證：unverified
- 事件 2：2026-08-26｜Kapitalo增持股份但第二季財報低於市場預期｜recent_event
  - 影響：負向｜嚴重性：2｜信心度：中
  - 摘要：Kapitalo Investimentos增持Brighthouse股份，但公司第二季盈餘與營收均低於分析師預期。
  - 來源：MarketBeat
  - 日期過濾：kept_recent｜來源品質：secondary_site｜驗證：unverified

### 3. OPI

- 事件總分：正向0 / 負向0 / 總分+0
- 綜合分析：雖然分析師給予買入評級且股東結構出現調整，但公司破產重整後的資產負債壓力、高利息負擔與內部人持續賣股顯現其財務流動性風險依然高企。
- 事件 1：2026-08-31｜分析師給予適度買入評級但內部人持續賣出股票｜recent_event
  - 影響：中性｜嚴重性：3｜信心度：中
  - 摘要：MarketBeat報告分析師給予OPI適度買入評級，但內部人過去三個月累計賣股逾700萬美元。
  - 來源：MarketBeat
  - 日期過濾：kept_recent｜來源品質：secondary_site｜驗證：unverified
- 事件 2：2026-08-24｜破產後重整路徑分析：債務重組與流動性挑戰並存｜recent_event
  - 影響：中性｜嚴重性：3｜信心度：高
  - 摘要：TipRanks分析OPI破產重整後雖債務減少，惟高槓桿與高利息仍對流動性構成挑戰。
  - 來源：TipRanks
  - 日期過濾：kept_recent｜來源品質：secondary_site｜驗證：unverified
- 事件 3：2026-08-19｜Redwood資金揭露影響董事會權力與內部人申報賣股｜recent_event
  - 影響：中性｜嚴重性：2｜信心度：高
  - 摘要：SEC文件顯示Redwood Capital增持可能影響董事會權限，同時內部人提交賣股申報。
  - 來源：MarketBeat、SEC Filing
  - 日期過濾：kept_recent｜來源品質：sec_filing｜驗證：verified

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
- Debt maturity and exchange offer terms｜狀態：已取得｜驗證：partially_verified｜來源品質：press_release｜期間新鮮度：fresh｜門檻：distressed exchange、順位弱化或擔保改變需警戒。
- Credit rating / outlook｜狀態：已取得｜驗證：verified｜來源品質：rating_agency｜期間新鮮度：acceptable_recent｜門檻：downgrade、negative outlook 或 selective default 評論需警戒。

### BHFAL 量化監控
- RBC ratio｜狀態：已取得｜驗證：partially_verified｜來源品質：press_release｜期間新鮮度：fresh｜門檻：低於 400% 黃燈；低於 350% 橙燈/紅燈；單季大幅下滑需警戒。
- Statutory capital and surplus｜狀態：已取得｜驗證：partially_verified｜來源品質：press_release｜期間新鮮度：fresh｜門檻：連續下降或重大減損需警戒。
- Holding company cash and liquid assets｜狀態：已取得｜驗證：partially_verified｜來源品質：press_release｜期間新鮮度：fresh｜門檻：低於未來 12 個月利息與固定支出覆蓋需求需警戒。
- Financial leverage｜狀態：資料不足｜驗證：data_missing｜來源品質：unknown｜期間新鮮度：fresh｜門檻：槓桿升高或評等機構負面評論需警戒。
- Credit rating / outlook｜狀態：已取得｜驗證：verified｜來源品質：rating_agency｜期間新鮮度：acceptable_recent｜門檻：negative outlook、downgrade 或 watch negative 需警戒。
- BHFAL interest payment status｜狀態：已取得｜驗證：unverified｜來源品質：unknown｜期間新鮮度：unknown_period｜門檻：defer、suspend、delay、non-payment 立即紅燈。
- Aquarian merger / change-of-control treatment｜狀態：已取得｜驗證：partially_verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：未明確說明 BHFAL 存續、掛牌、贖回或付息條款時列資料不足。
- 資料缺口：1 項，關鍵資料缺漏時不可判定為綠燈。

### OPI 量化監控
- Occupancy rate｜狀態：已取得｜驗證：partially_verified｜來源品質：official_ir｜期間新鮮度：fresh｜門檻：連續下降或低於同業顯著水準需警戒。
- AFFO / FFO｜狀態：已取得｜驗證：partially_verified｜來源品質：press_release｜期間新鮮度：fresh｜門檻：AFFO/FFO 大幅下滑或為負需警戒。
- Debt maturity schedule｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：12-24 個月內大量到期且流動性不足需紅燈。
- Liquidity / cash availability｜狀態：已取得｜驗證：unverified｜來源品質：unknown｜期間新鮮度：fresh｜門檻：流動性不足或 covenant 壓力需警戒。
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
- Issuer / guarantor status｜狀態：資料不足｜驗證：data_missing｜來源品質：unknown｜期間新鮮度：unknown_period｜門檻：發行人或擔保人不明確時列灰燈/黃燈，不可判定安全。
- Asset sale proceeds and use of funds｜狀態：資料不足｜驗證：data_missing｜來源品質：unknown｜期間新鮮度：unknown_period｜門檻：出售所得若大量分配給股東而非減債需警戒。
- Debt assumption / redemption status｜狀態：資料不足｜驗證：data_missing｜來源品質：unknown｜期間新鮮度：unknown_period｜門檻：未說明承擔、契約修改或贖回時列資料不足。
- 資料缺口：3 項，關鍵資料缺漏時不可判定為綠燈。

## 程式端日期過濾與來源驗證

- 日期過濾版本：1.2.2
- 最近事件保留天數：14 天
- 說明：超出最近 14 日但命中 Chapter 11、收購、重整、退市、債務交換等重大關鍵字者，會保留為 background_risk_event；其他舊事件移至 dropped_old_events。

- CTGG：recent=1，background=0，unknown_date=0，dropped_old=0
- BHFAL：recent=2，background=0，unknown_date=0，dropped_old=0
- OPI：recent=3，background=0，unknown_date=0，dropped_old=0
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
        "date": "2026-08-26",
        "title": "Lumen擴展美國雲網路服務覆蓋至逾千萬商業據點",
        "impact_direction": "正向",
        "impact_severity": 2,
        "confidence": "高",
        "summary_30": "Lumen宣佈擴大雲網路服務，覆蓋全美逾千萬商業地點，強化市場滲透。",
        "links": [
          "Lumen Investor Relations"
        ],
        "event_source_quality": "official_ir",
        "event_source_quality_details": [
          "official_ir"
        ],
        "event_verification_status": "verified",
        "event_days_old": 6,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event",
        "merged_duplicate_count": 1
      }
    ],
    "綜合分析": "該標的受惠於擴大雲網路服務至全美逾千萬商業據點，有助於強化市場滲透率並提升中長期營運成長動能。",
    "事件總分": "正向2 / 負向0 / 總分+2",
    "new_sources_found": [
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
        "semantic_match_status": "完全符合",
        "issuer_scope": "Lumen",
        "metric_value_type": "數字",
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
        "cross_run_previous_report_date": "20260901",
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
        "value": "Qwest Corp於2026年6月完成部分債務交換要約，將2056年到期票據交換為2051年到期票據，2057年到期票據交換為2052年到期票據，新票據獲Lumen擔保。",
        "unit": "status/date/USD",
        "period": "2026Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "Investing.com / StreetInsider / BusinessWire",
        "source_url_or_name": "Investing.com (Qwest unit completes debt exchange offer)",
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
        "note": "最近一次交換要約主要針對部分短期債務，且Lumen對新票據提供擔保，CTGG所屬Qwest Corp的長期債務結構未受顯著改變。",
        "semantic_match_status": "完全符合",
        "issuer_scope": "Lumen / Qwest",
        "metric_value_type": "文字描述",
        "definition_scope": "債務項目層面",
        "calculation_basis": "官方公告",
        "source_quality_primary": "press_release",
        "source_quality": "press_release",
        "source_quality_details": [
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
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "definition_changed",
        "cross_run_previous_value": "Qwest Corp 6.500% Senior Notes due 2051 (CTGG) 尚未直接受最新交換要約影響，但Lumen整體債務重組持續進行中，不排除未來更多債務交換可能，可能影響債權人優先順序。",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260901",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period 有前值，但 definition_scope / calculation_basis 不同，不互相覆寫。"
      },
      {
        "ticker": "CTGG",
        "metric_name": "Credit rating / outlook",
        "metric_category": "信用評等",
        "value": "Qwest Corp: Caa1 (展望穩定) by Moody's; Lumen Technologies: B- (發行人信用評級) by S&P",
        "unit": "rating",
        "period": "2026-02-20 (Moody's); 2026-02-23 (S&P)",
        "status": "已取得",
        "confidence": "高",
        "source": "Moody's Ratings / S&P Global Ratings / BusinessWire",
        "source_url_or_name": "Moody's Ratings (New York, February 20, 2026)",
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
        "note": "Moody's於2026年2月上調Qwest Corp高級無擔保票據評級至Caa1並給予穩定展望；S&P於同期維持Lumen發行人信用評級為B-。",
        "semantic_match_status": "完全符合",
        "issuer_scope": "Lumen / Qwest",
        "metric_value_type": "評級字符串",
        "definition_scope": "公司層面 / 債務項目層面",
        "calculation_basis": "評級機構報告",
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
        "metric_period_parsed_date": "2026-02-23",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "date",
        "metric_period_freshness": "acceptable_recent",
        "metric_integrity_status": "pass",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "definition_changed",
        "cross_run_previous_value": "Caa1 (展望穩定)",
        "cross_run_previous_period": "2026-02-23 (報告日期)",
        "cross_run_previous_report_date": "20260728",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period 有前值，但 definition_scope / calculation_basis 不同，不互相覆寫。"
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
      "cutoff_date": "2026-08-19",
      "today": "2026-09-01",
      "kept_recent": 1,
      "kept_background": 0,
      "kept_unknown_date": 0,
      "dropped_old": 0
    },
    "metric_consistency_summary": {
      "conflict_count": 0,
      "conflicts": []
    },
    "excluded_low_trust_event_count": 0,
    "merged_duplicate_event_count": 0,
    "event_dedup_patch_version": "1.3.3"
  },
  {
    "target_name": "BHFAL",
    "events": [
      {
        "date": "2026-08-29",
        "title": "市場持續擔憂Aquarian收購案監管審查風險及股價波動",
        "impact_direction": "負向",
        "impact_severity": 3,
        "confidence": "中",
        "summary_30": "市場持續關注Aquarian併購案之監管審查風險並引發股價震盪，惟公司獨立財務狀況仍屬穩健。",
        "links": [
          "Seeking Alpha"
        ],
        "event_source_quality": "secondary_site",
        "event_source_quality_details": [
          "secondary_site"
        ],
        "event_verification_status": "unverified",
        "event_days_old": 3,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event",
        "merged_duplicate_count": 1
      },
      {
        "date": "2026-08-26",
        "title": "Kapitalo增持股份但第二季財報低於市場預期",
        "impact_direction": "負向",
        "impact_severity": 2,
        "confidence": "中",
        "summary_30": "Kapitalo Investimentos增持Brighthouse股份，但公司第二季盈餘與營收均低於分析師預期。",
        "links": [
          "MarketBeat"
        ],
        "event_source_quality": "secondary_site",
        "event_source_quality_details": [
          "secondary_site"
        ],
        "event_verification_status": "unverified",
        "event_days_old": 6,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event",
        "merged_duplicate_count": 1
      }
    ],
    "綜合分析": "受第二季財報遜於預期及Aquarian收購案面臨監管審查不確定性之雙重影響，該標的短期估值與股價面臨下行壓力。",
    "事件總分": "正向0 / 負向5 / 總分-5",
    "new_sources_found": [
      "MarketBeat"
    ],
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
        "source": "Brighthouse Financial Q2 2026 Earnings Release",
        "source_url_or_name": "Business Wire, Morningstar",
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
        "note": "截至2026年6月30日之預估合併風險資本適足率。此區間在公司目標範圍(400%-450%)內。",
        "definition_scope": "Brighthouse Financial保險子公司合併RBC",
        "calculation_basis": "預估合併風險資本適足率",
        "source_quality_primary": "press_release",
        "source_quality": "press_release",
        "source_quality_details": [
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
        "measurement_form": "range",
        "source_period_alignment_status": "q2_asof_evidence_present",
        "source_period_evidence": "Brighthouse Financial Q2 2026 Earnings Release | Business Wire, Morningstar | 截至2026年6月30日之預估合併風險資本適足率。此區間在公司目標範圍(400%-450%)內。",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "definition_changed",
        "cross_run_previous_value": "430%-450%",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260901",
        "cross_run_previous_definition_scope": "Estimated combined RBC ratio of insurance subsidiaries",
        "cross_run_previous_calculation_basis": "Statutory basis",
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
        "source": "Brighthouse Financial Q2 2026 Earnings Release",
        "source_url_or_name": "Business Wire, Morningstar",
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
        "note": "截至2026年6月30日之法定合併總調整資本。",
        "definition_scope": "Brighthouse Financial保險子公司合併法定資本",
        "calculation_basis": "合併總調整資本",
        "source_quality_primary": "press_release",
        "source_quality": "press_release",
        "source_quality_details": [
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
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "definition_changed",
        "cross_run_previous_value": "4.9 billion",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260901",
        "cross_run_previous_definition_scope": "Statutory combined total adjusted capital of insurance subsidiaries",
        "cross_run_previous_calculation_basis": "Statutory basis",
        "cross_run_consistency_reason": "同 period 有前值，但 definition_scope / calculation_basis 不同，不互相覆寫。"
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
        "source": "Brighthouse Financial Q2 2026 Earnings Release",
        "source_url_or_name": "Business Wire, Morningstar",
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
        "note": "截至2026年6月30日之控股公司流動資產。",
        "definition_scope": "Brighthouse Financial Inc.、Brighthouse Holdings, LLC及Brighthouse Services, LLC的流動資產",
        "calculation_basis": "現金及約當現金、短期投資和公開交易證券（不含已質押或承諾資產）",
        "source_quality_primary": "press_release",
        "source_quality": "press_release",
        "source_quality_details": [
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
        "measurement_form": "point",
        "source_period_alignment_status": "q2_asof_evidence_present",
        "source_period_evidence": "Brighthouse Financial Q2 2026 Earnings Release | Business Wire, Morningstar | 截至2026年6月30日之控股公司流動資產。",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "definition_changed",
        "cross_run_previous_value": "0.9 billion",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260901",
        "cross_run_previous_definition_scope": "Liquid assets at holding company level (Brighthouse Financial, Inc., Brighthouse Holdings, LLC, and Brighthouse Services, LLC)",
        "cross_run_previous_calculation_basis": "Cash and cash equivalents, short-term investments, publicly-traded securities (excluding pledged assets)",
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
        "note": "本次搜尋未在官方第二季財報摘要或相關評等報告中找到針對次順位債權人影響較直接的整體財務槓桿比率。",
        "definition_scope": null,
        "calculation_basis": null,
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
        "cross_run_previous_report_date": "20260901",
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
        "value": "正常支付",
        "unit": "status",
        "period": "持續性",
        "status": "已取得",
        "confidence": "高",
        "source": "公司公開聲明及缺乏負面報導",
        "source_url_or_name": "Brighthouse Financial (間接)",
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
        "note": "Brighthouse Financial於8月17日宣布派發優先股股息，間接表明公司具備正常支付資本性義務的能力，未有BHFAL利息支付異常報導。",
        "definition_scope": "BHFAL次順位債付息狀態",
        "calculation_basis": "公司公告及市場情報",
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
        "cross_run_consistency_status": "no_prior_same_period"
      },
      {
        "ticker": "BHFAL",
        "metric_name": "Aquarian merger / change-of-control treatment",
        "metric_category": "交易條款",
        "value": "等待監管核准中",
        "unit": "status",
        "period": "2026年內",
        "status": "已取得",
        "confidence": "高",
        "source": "Brighthouse Financial Q2 2026 Earnings Release, SEC Filing",
        "source_url_or_name": "Business Wire, SEC Filing (10-Q), Seeking Alpha",
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
        "note": "合併案需獲得德拉瓦州、紐約州和麻薩諸塞州的保險監管機構批准，預計於2026年完成，最晚可能延至12月6日。BHFAL此類債務證券在併購後將保持未償付狀態，條款不變。",
        "definition_scope": "Brighthouse Financial及其次順位債權人(BHFAL)在與Aquarian Capital合併後的處理方式",
        "calculation_basis": "合併協議條款與公司聲明",
        "source_quality_primary": "sec_filing",
        "source_quality": "sec_filing",
        "source_quality_details": [
          "sec_filing",
          "press_release",
          "secondary_site"
        ],
        "source_candidate_quality_details": [
          "sec_filing",
          "official_ir",
          "rating_agency"
        ],
        "source_conflict_flag": true,
        "source_conflict_reason": "實際來源混合官方與次級/AI來源",
        "metric_period_parsed_date": "2026-09-01",
        "metric_period_parse_status": "year_only",
        "metric_period_type": "year",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "partially_verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "definition_changed",
        "cross_run_previous_value": "交易進行中，預計 2026 年完成",
        "cross_run_previous_period": "Current",
        "cross_run_previous_report_date": "20260716",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period 有前值，但 definition_scope / calculation_basis 不同，不互相覆寫。"
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
      "cutoff_date": "2026-08-19",
      "today": "2026-09-01",
      "kept_recent": 2,
      "kept_background": 0,
      "kept_unknown_date": 0,
      "dropped_old": 0
    },
    "metric_consistency_summary": {
      "conflict_count": 0,
      "conflicts": []
    },
    "excluded_low_trust_event_count": 0,
    "merged_duplicate_event_count": 0,
    "event_dedup_patch_version": "1.3.3",
    "market_quote": {
      "ticker": "BHFAL",
      "security_name_expected": "Brighthouse Financial 6.25% Junior Subordinated Debentures due 2058",
      "exchange_expected": "NASDAQ",
      "latest_price": 15.76,
      "price_as_of": "2026-08-31",
      "open": 15.649999618530273,
      "high": 15.839900016784668,
      "low": 15.520000457763672,
      "volume": 38818,
      "bid": null,
      "ask": null,
      "annual_interest": 1.5625,
      "current_yield": 9.9143,
      "quote_source": "Yahoo Finance chart (query1.finance.yahoo.com)",
      "source_host": "query1.finance.yahoo.com",
      "quote_status": "ok",
      "freshness_status": "fresh",
      "security_identity_status": "matched_symbol",
      "source_timestamp": 1788183000,
      "market_quote_patch_version": "1.3.7",
      "returned_symbol": "BHFAL",
      "currency": "USD",
      "exchange_name": "NMS",
      "instrument_type": "EQUITY",
      "regular_market_price_meta": 15.76,
      "regular_market_time_meta": 1788206401,
      "reference_session_date": "2026-08-31",
      "weekday_gap": 0,
      "http_status": 200,
      "request_url": "https://query1.finance.yahoo.com/v8/finance/chart/BHFAL",
      "request_attempt": 1,
      "attempts": [
        {
          "source_host": "query1.finance.yahoo.com",
          "quote_status": "ok",
          "freshness_status": "fresh",
          "price_as_of": "2026-08-31",
          "latest_price": 15.76,
          "error": null
        },
        {
          "source_host": "query2.finance.yahoo.com",
          "quote_status": "ok",
          "freshness_status": "fresh",
          "price_as_of": "2026-08-31",
          "latest_price": 15.76,
          "error": null
        }
      ],
      "source_validation": "cross_checked",
      "source_crosscheck_price": 15.76,
      "source_crosscheck_host": "query2.finance.yahoo.com",
      "source_conflict_pct": 0.0
    }
  },
  {
    "target_name": "OPI",
    "events": [
      {
        "date": "2026-08-31",
        "title": "分析師給予適度買入評級但內部人持續賣出股票",
        "impact_direction": "中性",
        "impact_severity": 3,
        "confidence": "中",
        "summary_30": "MarketBeat報告分析師給予OPI適度買入評級，但內部人過去三個月累計賣股逾700萬美元。",
        "links": [
          "MarketBeat"
        ],
        "event_source_quality": "secondary_site",
        "event_source_quality_details": [
          "secondary_site"
        ],
        "event_verification_status": "unverified",
        "event_days_old": 1,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event",
        "merged_duplicate_count": 1
      },
      {
        "date": "2026-08-24",
        "title": "破產後重整路徑分析：債務重組與流動性挑戰並存",
        "impact_direction": "中性",
        "impact_severity": 3,
        "confidence": "高",
        "summary_30": "TipRanks分析OPI破產重整後雖債務減少，惟高槓桿與高利息仍對流動性構成挑戰。",
        "links": [
          "TipRanks"
        ],
        "event_source_quality": "secondary_site",
        "event_source_quality_details": [
          "secondary_site"
        ],
        "event_verification_status": "unverified",
        "event_days_old": 8,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event",
        "merged_duplicate_count": 1
      },
      {
        "date": "2026-08-19",
        "title": "Redwood資金揭露影響董事會權力與內部人申報賣股",
        "impact_direction": "中性",
        "impact_severity": 2,
        "confidence": "高",
        "summary_30": "SEC文件顯示Redwood Capital增持可能影響董事會權限，同時內部人提交賣股申報。",
        "links": [
          "MarketBeat",
          "SEC Filing"
        ],
        "event_source_quality": "sec_filing",
        "event_source_quality_details": [
          "sec_filing",
          "secondary_site"
        ],
        "event_verification_status": "verified",
        "event_days_old": 13,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event",
        "merged_duplicate_count": 1
      }
    ],
    "綜合分析": "雖然分析師給予買入評級且股東結構出現調整，但公司破產重整後的資產負債壓力、高利息負擔與內部人持續賣股顯現其財務流動性風險依然高企。",
    "事件總分": "正向0 / 負向0 / 總分+0",
    "new_sources_found": [
      "MarketBeat",
      "TipRanks",
      "SEC Filing"
    ],
    "event_merge_source": "ai_stage2",
    "metric_data": [
      {
        "ticker": "OPI",
        "metric_name": "Occupancy rate",
        "metric_category": "出租率",
        "value": "88.7",
        "unit": "%",
        "period": "2026Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "Office Properties Income Trust Q2 2026 Earnings Release",
        "source_url_or_name": "Business Wire, OPI Investor Relations",
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
        "note": "指同物業組合(same property portfolio)出租率。",
        "source_quality_primary": "official_ir",
        "source_quality": "official_ir",
        "source_quality_details": [
          "official_ir",
          "press_release"
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
        "metric_consistency_reason": "同 period / definition 前值=77.9% (整體組合), 88.7% (同物業組合)，本次=88.7；區間不重疊。",
        "cross_run_consistency_status": "value_changed_same_definition",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "77.9% (整體組合), 88.7% (同物業組合)",
        "cross_run_previous_period": "2026 Q2 (截至6月30日)",
        "cross_run_previous_report_date": "20260901",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 前值=77.9% (整體組合), 88.7% (同物業組合)，本次=88.7；區間不重疊。"
      },
      {
        "ticker": "OPI",
        "metric_name": "AFFO / FFO",
        "metric_category": "現金流",
        "value": "19.6",
        "unit": "USD",
        "period": "2026Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "Office Properties Income Trust Q2 2026 Earnings Release / Earnings Call",
        "source_url_or_name": "Business Wire, EarningsCall.biz",
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
        "note": "2026年第二季重整前(Predecessor)正規化FFO為15.1百萬美元，重整後(Successor)為4.5百萬美元。",
        "source_quality_primary": "press_release",
        "source_quality": "press_release",
        "source_quality_details": [
          "press_release"
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
        "metric_consistency_reason": "同 period / definition 前值=19.0，本次=19.6；區間不重疊。",
        "cross_run_consistency_status": "value_changed_same_definition",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "19.0",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260818",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 前值=19.0，本次=19.6；區間不重疊。"
      },
      {
        "ticker": "OPI",
        "metric_name": "Debt maturity schedule",
        "metric_category": "債務到期牆",
        "value": [
          {
            "amount": "425",
            "unit": "百萬美元",
            "maturity_date": "2027-01",
            "description": "循環信貸額度"
          },
          {
            "amount": "300",
            "unit": "百萬美元",
            "maturity_date": "2029-03",
            "description": "9%優先擔保票據"
          },
          {
            "amount": "385",
            "unit": "百萬美元",
            "maturity_date": "2029-12",
            "description": "8.375%優先擔保票據"
          },
          {
            "amount": "420",
            "unit": "百萬美元",
            "maturity_date": "2031-06",
            "description": "10%優先擔保票據"
          },
          {
            "amount": "177",
            "unit": "百萬美元",
            "maturity_date": "2028-2033",
            "description": "CMBS抵押債務"
          }
        ],
        "unit": "USD/date",
        "period": "2026-06-30",
        "status": "已取得",
        "confidence": "高",
        "source": "Office Properties Income Trust Q2 2026 Earnings Call / SEC 8-K",
        "source_url_or_name": "EarningsCall.biz, SEC Filing",
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
        "note": "截至2026年6月30日，總債務為17億美元。另有計劃於2026年11月1日前支付15百萬美元本金，2027年2月1日前支付30百萬美元本金。",
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
        "metric_period_type": "date",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "not_comparable",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "總債務 $1.7B / 2027年1月到期 $4.25億信貸額度 / 2029年12月到期債務需支付本金",
        "cross_run_previous_period": "2026年6月30日",
        "cross_run_previous_report_date": "20260813",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 有前值，但數值型態無法安全比較。"
      },
      {
        "ticker": "OPI",
        "metric_name": "Liquidity / cash availability",
        "metric_category": "流動性",
        "value": {
          "unrestricted_cash": "51",
          "restricted_cash": "53"
        },
        "unit": "USD",
        "period": "2026-06-30",
        "status": "已取得",
        "confidence": "高",
        "source": "Office Properties Income Trust Q2 2026 Earnings Call",
        "source_url_or_name": "EarningsCall.biz",
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
        "note": "受限現金包括用於重組相關專業費用之35百萬美元儲備。",
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
        "metric_period_parsed_date": "2026-06-30",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "date",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "unverified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "consistent_with_prior_range",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "51",
        "cross_run_previous_period": "2026-06-30",
        "cross_run_previous_report_date": "20260818",
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
        "metric_name": "Occupancy rate",
        "reason": "同 period / definition 前值=77.9% (整體組合), 88.7% (同物業組合)，本次=88.7；區間不重疊。",
        "risk_impact": "出租率下降會影響 NOI、AFFO 與償債能力。",
        "previous_value": "77.9% (整體組合), 88.7% (同物業組合)",
        "current_value": "88.7",
        "period": "2026Q2",
        "definition_scope": "",
        "calculation_basis": "",
        "acceptance_criteria": "以同一官方定義重新查核；若為不同口徑，改填不同 definition_scope / calculation_basis，不得覆寫。"
      },
      {
        "ticker": "OPI",
        "priority": "P0",
        "missing_type": "metric_cross_run_consistency",
        "metric_name": "AFFO / FFO",
        "reason": "同 period / definition 前值=19.0，本次=19.6；區間不重疊。",
        "risk_impact": "REIT 配息與債務服務能力核心指標。",
        "previous_value": "19.0",
        "current_value": "19.6",
        "period": "2026Q2",
        "definition_scope": "",
        "calculation_basis": "",
        "acceptance_criteria": "以同一官方定義重新查核；若為不同口徑，改填不同 definition_scope / calculation_basis，不得覆寫。"
      }
    ],
    "dropped_old_events": [],
    "event_date_filter_summary": {
      "lookback_days": 14,
      "cutoff_date": "2026-08-19",
      "today": "2026-09-01",
      "kept_recent": 3,
      "kept_background": 0,
      "kept_unknown_date": 0,
      "dropped_old": 0
    },
    "metric_consistency_summary": {
      "conflict_count": 2,
      "conflicts": [
        {
          "ticker": "OPI",
          "metric_name": "Occupancy rate",
          "metric_value": "88.7",
          "missing_reason": "同 period / definition 前值=77.9% (整體組合), 88.7% (同物業組合)，本次=88.7；區間不重疊。",
          "verification_after_reconcile": "partially_verified",
          "cross_run_consistency_status": "value_changed_same_definition",
          "definition_scope": "",
          "calculation_basis": ""
        },
        {
          "ticker": "OPI",
          "metric_name": "AFFO / FFO",
          "metric_value": "19.6",
          "missing_reason": "同 period / definition 前值=19.0，本次=19.6；區間不重疊。",
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
      "cutoff_date": "2026-08-19",
      "today": "2026-09-01",
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
      "cutoff_date": "2026-08-19",
      "today": "2026-09-01",
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
        "value": null,
        "unit": "status",
        "period": "latest",
        "status": "資料不足",
        "confidence": "低",
        "source": "未取得",
        "source_url_or_name": "",
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
        "note": "量化監控框架 v1.2 已嘗試由 Stage 1 搜尋此指標；仍未取得官方數值。",
        "source_quality_primary": "unknown",
        "source_quality": "unknown",
        "source_quality_details": [
          "unknown"
        ],
        "source_candidate_quality_details": [
          "sec_filing",
          "official_ir",
          "exchange_notice"
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
        "ticker": "UZD",
        "metric_name": "Asset sale proceeds and use of funds",
        "metric_category": "資產出售",
        "value": null,
        "unit": "USD/status",
        "period": "latest",
        "status": "資料不足",
        "confidence": "低",
        "source": "未取得",
        "source_url_or_name": "",
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
        "note": "量化監控框架 v1.2 已嘗試由 Stage 1 搜尋此指標；仍未取得官方數值。",
        "source_quality_primary": "unknown",
        "source_quality": "unknown",
        "source_quality_details": [
          "unknown"
        ],
        "source_candidate_quality_details": [
          "sec_filing",
          "official_ir",
          "exchange_notice"
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
        "ticker": "UZD",
        "metric_name": "Debt assumption / redemption status",
        "metric_category": "債務處理",
        "value": null,
        "unit": "status",
        "period": "latest",
        "status": "資料不足",
        "confidence": "低",
        "source": "未取得",
        "source_url_or_name": "",
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
        "note": "量化監控框架 v1.2 已嘗試由 Stage 1 搜尋此指標；仍未取得官方數值。",
        "source_quality_primary": "unknown",
        "source_quality": "unknown",
        "source_quality_details": [
          "unknown"
        ],
        "source_candidate_quality_details": [
          "sec_filing",
          "official_ir",
          "exchange_notice"
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
        "acceptance_criteria": "下次報告 metric_data 中 UZD / Issuer / guarantor status 應填入 value、period、source；若查無官方資料，需明確標示查詢來源與查無原因。"
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
        "acceptance_criteria": "下次報告 metric_data 中 UZD / Asset sale proceeds and use of funds 應填入 value、period、source；若查無官方資料，需明確標示查詢來源與查無原因。"
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
        "acceptance_criteria": "下次報告 metric_data 中 UZD / Debt assumption / redemption status 應填入 value、period、source；若查無官方資料，需明確標示查詢來源與查無原因。"
      }
    ],
    "dropped_old_events": [],
    "event_date_filter_summary": {
      "lookback_days": 14,
      "cutoff_date": "2026-08-19",
      "today": "2026-09-01",
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
      "latest_price": 19.0,
      "price_as_of": "2026-08-31",
      "open": 18.68000030517578,
      "high": 19.020000457763672,
      "low": 18.795000076293945,
      "volume": 24446,
      "bid": null,
      "ask": null,
      "annual_interest": 1.5625,
      "current_yield": 8.2237,
      "quote_source": "Yahoo Finance chart (query1.finance.yahoo.com)",
      "source_host": "query1.finance.yahoo.com",
      "quote_status": "ok",
      "freshness_status": "fresh",
      "security_identity_status": "matched_symbol",
      "source_timestamp": 1788183000,
      "market_quote_patch_version": "1.3.7",
      "returned_symbol": "UZD",
      "currency": "USD",
      "exchange_name": "NYQ",
      "instrument_type": "EQUITY",
      "regular_market_price_meta": 19.0,
      "regular_market_time_meta": 1788206394,
      "reference_session_date": "2026-08-31",
      "weekday_gap": 0,
      "http_status": 200,
      "request_url": "https://query1.finance.yahoo.com/v8/finance/chart/UZD",
      "request_attempt": 1,
      "attempts": [
        {
          "source_host": "query1.finance.yahoo.com",
          "quote_status": "ok",
          "freshness_status": "fresh",
          "price_as_of": "2026-08-31",
          "latest_price": 19.0,
          "error": null
        },
        {
          "source_host": "query2.finance.yahoo.com",
          "quote_status": "ok",
          "freshness_status": "fresh",
          "price_as_of": "2026-08-31",
          "latest_price": 19.0,
          "error": null
        }
      ],
      "source_validation": "cross_checked",
      "source_crosscheck_price": 19.0,
      "source_crosscheck_host": "query2.finance.yahoo.com",
      "source_conflict_pct": 0.0
    }
  }
]
```

# USPreferredStockDayInfo 每日情報報告

- 生成時間（台灣）：2026-09-08 10:21:26
- 對應 PDF：Stock_News_Report_20260908_102126.pdf
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

- 事件總分：正向3 / 負向4 / 總分-1
- 綜合分析：雖然公司透過出售非核心資產得以短期改善流動性，但穆迪維持負面展望凸顯其高額債務及再融資風險依然顯著。
- 事件 1：2026-09-02｜穆迪確認Lumen信用評級但維持負面展望｜recent_event
  - 影響：負向｜嚴重性：4｜信心度：高
  - 摘要：穆迪確認Lumen的B3評級，但鑒於沉重債務負擔與再融資風險，展望維持負面。
  - 來源：Moody's Investors Service、Reuters
  - 日期過濾：kept_recent｜來源品質：rating_agency｜驗證：verified
- 事件 2：2026-08-28｜Lumen完成非核心資產剝離以強化流動性｜recent_event
  - 影響：正向｜嚴重性：3｜信心度：高
  - 摘要：Lumen出售非核心資產，所得款項將用於償債及提升公司短期流動性。
  - 來源：BusinessWire、Lumen Investor Relations
  - 日期過濾：kept_recent｜來源品質：official_ir｜驗證：verified

### 2. BHFAL

- 事件總分：正向0 / 負向3 / 總分-3
- 綜合分析：受第二季財報不如預期及併購監管審查不確定性影響，短線面臨評級下修壓力，惟其穩健的獨立財務狀況提供一定下行保護。
- 事件 1：2026-09-06｜Simply Wall St 分析二季度財報未達預期對投資論點的影響｜recent_event
  - 影響：負向｜嚴重性：3｜信心度：中
  - 摘要：二季度收益低於預期，投資收益下降，分析師下調評級，引發市場對併購交易的擔憂。
  - 來源：Simply Wall St
  - 日期過濾：kept_recent｜來源品質：secondary_site｜驗證：unverified
- 事件 2：2026-08-29｜SeekingAlpha 討論併購不確定性與公司獨立財務狀況｜recent_event
  - 影響：中性｜嚴重性：3｜信心度：中
  - 摘要：併購交易監管審查持續，存在不確定性，但公司獨立財務狀況穩健提供下行保護。
  - 來源：SeekingAlpha
  - 日期過濾：kept_recent｜來源品質：unknown｜驗證：unverified

### 3. OPI

- 事件總分：正向0 / 負向0 / 總分+0
- 綜合分析：公司在完成破產重整與第二季財報發布後，受限於辦公室市場整體需求疲弱，業務復甦前景仍充滿極大挑戰。
- 事件 1：2026-08-27｜分析文章探討OPI破產重整後的復甦前景｜recent_event
  - 影響：中性｜嚴重性：3｜信心度：中
  - 摘要：一篇分析文章討論OPI在完成重整與發布Q2財報後，於辦公室市場的復甦挑戰。
  - 來源：Kalkine
  - 日期過濾：kept_recent｜來源品質：unknown｜驗證：unverified

### 4. AXS-E

- 事件總分：正向3 / 負向0 / 總分+3
- 綜合分析：獲 AM Best 確認 A 級優良評級且展望穩定，顯示公司整體財務結構堅實且信用風險極低。
- 事件 1：2026-09-04｜AM Best 確認 AXIS Capital 及其營運子公司信用評級為 A (Excellent)，展望穩定｜recent_event
  - 影響：正向｜嚴重性：3｜信心度：高
  - 摘要：AM Best 確認 AXIS Capital 主要信用評級，展望穩定，顯示公司財務實力穩健。
  - 來源：AM Best、AXIS Capital Investor Relations、GlobeNewswire
  - 日期過濾：kept_recent｜來源品質：official_ir｜驗證：verified

### 5. F-B

- 事件總分：正向4 / 負向4 / 總分+0
- 綜合分析：儘管管理層積極參與市場溝通與進行高層人選過渡，但大規模汽車召回事件短期內加重了營運品質控管風險與成本負擔。
- 事件 1：2026-09-08｜福特整合服務總裁將出席高盛會議｜recent_event
  - 影響：中性偏正向｜嚴重性：2｜信心度：高
  - 摘要：福特整合服務總裁Mike Aragon將出席高盛會議，與投資人互動。
  - 來源：Ford Investor Relations
  - 日期過濾：kept_recent｜來源品質：official_ir｜驗證：verified
- 事件 2：2026-09-02｜福特公佈2026年8月美國銷售數據｜recent_event
  - 影響：中性｜嚴重性：1｜信心度：高
  - 摘要：福特公佈其2026年8月美國銷售數據，為常規業務更新。
  - 來源：Ford Investor Relations
  - 日期過濾：kept_recent｜來源品質：official_ir｜驗證：verified
- 事件 3：2026-09-01｜福特召回近14.9萬輛野馬汽車，存在動力損失風險｜recent_event
  - 影響：負向｜嚴重性：4｜信心度：高
  - 摘要：福特因電線線束問題召回2024-2026年式Mustang，恐導致失去動力。
  - 來源：CBS News、Consumer Affairs、Ford Owner Support
  - 日期過濾：kept_recent｜來源品質：unknown｜驗證：unverified
- 事件 4：2026-08-27｜福特能源新總裁任命，現任總裁將退休｜recent_event
  - 影響：中性偏正向｜嚴重性：2｜信心度：高
  - 摘要：福特任命Dave Carroll為Ford Energy總裁，現任Lisa Drake將於年底退休。
  - 來源：Ford Investor Relations、BusinessWire、SeekingAlpha
  - 日期過濾：kept_recent｜來源品質：official_ir｜驗證：verified

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
- Credit rating / outlook｜狀態：已取得｜驗證：verified｜來源品質：rating_agency｜期間新鮮度：fresh｜門檻：downgrade、negative outlook 或 selective default 評論需警戒。

### BHFAL 量化監控
- RBC ratio｜狀態：已取得｜驗證：partially_verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：低於 400% 黃燈；低於 350% 橙燈/紅燈；單季大幅下滑需警戒。
- Statutory capital and surplus｜狀態：已取得｜驗證：partially_verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：連續下降或重大減損需警戒。
- Holding company cash and liquid assets｜狀態：已取得｜驗證：partially_verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：低於未來 12 個月利息與固定支出覆蓋需求需警戒。
- Financial leverage｜狀態：資料不足｜驗證：data_missing｜來源品質：unknown｜期間新鮮度：fresh｜門檻：槓桿升高或評等機構負面評論需警戒。
- Credit rating / outlook｜狀態：已取得｜驗證：verified｜來源品質：rating_agency｜期間新鮮度：acceptable_recent｜門檻：negative outlook、downgrade 或 watch negative 需警戒。
- BHFAL interest payment status｜狀態：已取得｜驗證：verified｜來源品質：official_ir｜期間新鮮度：fresh｜門檻：defer、suspend、delay、non-payment 立即紅燈。
- Aquarian merger / change-of-control treatment｜狀態：資料不足｜驗證：data_missing｜來源品質：unknown｜期間新鮮度：fresh｜門檻：未明確說明 BHFAL 存續、掛牌、贖回或付息條款時列資料不足。
- 資料缺口：3 項，關鍵資料缺漏時不可判定為綠燈。

### OPI 量化監控
- Occupancy rate｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：連續下降或低於同業顯著水準需警戒。
- Debt maturity schedule｜狀態：已取得｜驗證：partially_verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：12-24 個月內大量到期且流動性不足需紅燈。
- Liquidity / cash availability｜狀態：已取得｜驗證：unverified｜來源品質：secondary_site｜期間新鮮度：fresh｜門檻：流動性不足或 covenant 壓力需警戒。
- AFFO / FFO｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：AFFO/FFO 大幅下滑或為負需警戒。

### AXS-E 量化監控
- Combined ratio｜狀態：已取得｜驗證：verified｜來源品質：official_ir｜期間新鮮度：fresh｜門檻：高於 100% 或明顯惡化需警戒。
- Catastrophe losses｜狀態：已取得｜驗證：partially_verified｜來源品質：official_ir｜期間新鮮度：fresh｜門檻：重大巨災損失超預期需警戒。
- Preferred dividend status｜狀態：已取得｜驗證：unverified｜來源品質：secondary_site｜期間新鮮度：future_or_invalid_period｜門檻：defer、suspend、delay 立即紅燈。
- 資料缺口：1 項，關鍵資料缺漏時不可判定為綠燈。

### F-B 量化監控
- Industrial free cash flow｜狀態：已取得｜驗證：partially_verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：FCF 轉負或全年指引大幅下修需警戒。
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

- CTGG：recent=2，background=0，unknown_date=0，dropped_old=0
- BHFAL：recent=2，background=0，unknown_date=0，dropped_old=0
- OPI：recent=1，background=0，unknown_date=0，dropped_old=0
- AXS-E：recent=1，background=0，unknown_date=0，dropped_old=0
- F-B：recent=4，background=0，unknown_date=0，dropped_old=0
- UZD：recent=0，background=0，unknown_date=0，dropped_old=0

## 完整 JSON

```json
[
  {
    "target_name": "CTGG",
    "events": [
      {
        "date": "2026-09-02",
        "title": "穆迪確認Lumen信用評級但維持負面展望",
        "impact_direction": "負向",
        "impact_severity": 4,
        "confidence": "高",
        "summary_30": "穆迪確認Lumen的B3評級，但鑒於沉重債務負擔與再融資風險，展望維持負面。",
        "links": [
          "Moody's Investors Service",
          "Reuters"
        ],
        "event_source_quality": "rating_agency",
        "event_source_quality_details": [
          "rating_agency",
          "mainstream_media"
        ],
        "event_verification_status": "verified",
        "event_days_old": 6,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event",
        "merged_duplicate_count": 1
      },
      {
        "date": "2026-08-28",
        "title": "Lumen完成非核心資產剝離以強化流動性",
        "impact_direction": "正向",
        "impact_severity": 3,
        "confidence": "高",
        "summary_30": "Lumen出售非核心資產，所得款項將用於償債及提升公司短期流動性。",
        "links": [
          "BusinessWire",
          "Lumen Investor Relations"
        ],
        "event_source_quality": "official_ir",
        "event_source_quality_details": [
          "official_ir",
          "press_release"
        ],
        "event_verification_status": "verified",
        "event_days_old": 11,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event",
        "merged_duplicate_count": 1
      }
    ],
    "綜合分析": "雖然公司透過出售非核心資產得以短期改善流動性，但穆迪維持負面展望凸顯其高額債務及再融資風險依然顯著。",
    "事件總分": "正向3 / 負向4 / 總分-1",
    "new_sources_found": [
      "Moody's Investors Service",
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
        "cross_run_previous_report_date": "20260908",
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
        "value": "債務交換要約已於2026年Q1完成，延長約12億美元債務到期日；目前尚無新要約公告。主要債務到期集中在2027-2029年。",
        "unit": "status/date/USD",
        "period": "2026Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "Lumen Technologies SEC 10-Q",
        "source_url_or_name": "Lumen Technologies SEC 10-Q",
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
        "note": "此資訊基於Lumen最新季報，反映其債務結構及近期債務交換要約狀態。",
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
        "cross_run_previous_value": "活躍的債務管理",
        "cross_run_previous_period": "2026Q2 (最新公開資訊為2026年6月之交換要約結果)",
        "cross_run_previous_report_date": "20260907",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 有前值，但數值型態無法安全比較。"
      },
      {
        "ticker": "CTGG",
        "metric_name": "Credit rating / outlook",
        "metric_category": "信用評等",
        "value": "Moody's: B3 (Negative Outlook)",
        "unit": "rating",
        "period": "2026-09-02",
        "status": "已取得",
        "confidence": "高",
        "source": "Moody's Investors Service / Reuters",
        "source_url_or_name": "Moody's Investors Service",
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
        "note": "穆迪於2026年9月2日確認評級並維持負面展望。",
        "source_quality_primary": "rating_agency",
        "source_quality": "rating_agency",
        "source_quality_details": [
          "rating_agency",
          "mainstream_media"
        ],
        "source_candidate_quality_details": [
          "sec_filing",
          "official_ir",
          "rating_agency"
        ],
        "source_conflict_flag": false,
        "source_conflict_reason": "",
        "metric_period_parsed_date": "2026-09-02",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "date",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "no_prior_same_period",
        "definition_scope": "",
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
      "cutoff_date": "2026-08-26",
      "today": "2026-09-08",
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
    "event_dedup_patch_version": "1.3.3"
  },
  {
    "target_name": "BHFAL",
    "events": [
      {
        "date": "2026-09-06",
        "title": "Simply Wall St 分析二季度財報未達預期對投資論點的影響",
        "impact_direction": "負向",
        "impact_severity": 3,
        "confidence": "中",
        "summary_30": "二季度收益低於預期，投資收益下降，分析師下調評級，引發市場對併購交易的擔憂。",
        "links": [
          "Simply Wall St"
        ],
        "event_source_quality": "secondary_site",
        "event_source_quality_details": [
          "secondary_site"
        ],
        "event_verification_status": "unverified",
        "event_days_old": 2,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event",
        "merged_duplicate_count": 1
      },
      {
        "date": "2026-08-29",
        "title": "SeekingAlpha 討論併購不確定性與公司獨立財務狀況",
        "impact_direction": "中性",
        "impact_severity": 3,
        "confidence": "中",
        "summary_30": "併購交易監管審查持續，存在不確定性，但公司獨立財務狀況穩健提供下行保護。",
        "links": [
          "SeekingAlpha"
        ],
        "event_source_quality": "unknown",
        "event_source_quality_details": [
          "unknown"
        ],
        "event_verification_status": "unverified",
        "event_days_old": 10,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event",
        "merged_duplicate_count": 1
      }
    ],
    "綜合分析": "受第二季財報不如預期及併購監管審查不確定性影響，短線面臨評級下修壓力，惟其穩健的獨立財務狀況提供一定下行保護。",
    "事件總分": "正向0 / 負向3 / 總分-3",
    "new_sources_found": [
      "Simply Wall St"
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
        "source": "Brighthouse Financial Earnings Release / 10-Q Summary",
        "source_url_or_name": "Morningstar, BusinessWire, Stock Titan",
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
        "note": "截至 2026 年 6 月 30 日的初步法定結果。此為保險子公司合併 RBC 比率，為公司內部衡量指標，非監管機構要求。",
        "definition_scope": "保險子公司合併RBC比率",
        "calculation_basis": "保險子公司總調整資本（TAC）除以其各自公司行動級別RBC總和",
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
        "metric_period_parsed_date": "2026-06-30",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "partially_verified",
        "measurement_form": "range",
        "source_period_alignment_status": "q2_asof_evidence_present",
        "source_period_evidence": "Brighthouse Financial Earnings Release / 10-Q Summary | Morningstar, BusinessWire, Stock Titan | 截至 2026 年 6 月 30 日的初步法定結果。此為保險子公司合併 RBC 比率，為公司內部衡量指標，非監管機構要求。",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "definition_changed",
        "cross_run_previous_value": "430%-450%",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260908",
        "cross_run_previous_definition_scope": "combined",
        "cross_run_previous_calculation_basis": "estimated statutory",
        "cross_run_consistency_reason": "同 period 有前值，但 definition_scope / calculation_basis 不同，不互相覆寫。"
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
        "source": "Brighthouse Financial Earnings Release / 10-Q Summary",
        "source_url_or_name": "Morningstar, BusinessWire, Stock Titan",
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
        "note": "截至 2026 年 6 月 30 日的初步法定合併總調整資本，與 3 月 31 日大致持平。",
        "definition_scope": "保險子公司合併總調整資本",
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
        "metric_period_parsed_date": "2026-06-30",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "partially_verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "definition_changed",
        "calculation_basis": "",
        "cross_run_previous_value": "$4.9 billion",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260908",
        "cross_run_previous_definition_scope": "combined total adjusted capital",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period 有前值，但 definition_scope / calculation_basis 不同，不互相覆寫。"
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
        "source": "Brighthouse Financial Earnings Release / 10-Q Summary",
        "source_url_or_name": "Morningstar, BusinessWire, Stock Titan",
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
        "note": "截至 2026 年 6 月 30 日。",
        "definition_scope": "控股公司持有的現金與流動資產",
        "calculation_basis": "包括現金及現金等價物、短期投資和公開交易證券，不含已抵押或承諾的資產",
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
        "metric_period_parsed_date": "2026-06-30",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "partially_verified",
        "measurement_form": "point",
        "source_period_alignment_status": "q2_asof_evidence_present",
        "source_period_evidence": "Brighthouse Financial Earnings Release / 10-Q Summary | Morningstar, BusinessWire, Stock Titan | 截至 2026 年 6 月 30 日。",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "definition_changed",
        "cross_run_previous_value": "$0.9 billion",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260908",
        "cross_run_previous_definition_scope": "Holding company",
        "cross_run_previous_calculation_basis": "holding company liquid assets",
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
        "note": "第二季度財報摘要未明確提供具體的金融槓桿比率。",
        "rejected_candidate_reason": "MarketScreener 提供的是預測值，非官方實時數據。",
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
        "rejected_candidate_reason": "BHFAL AM Best official-action veto：2026-07-29 最新正式 rating action 維持 Under Review with Negative Implications；2058 6.25% junior subordinated debentures Long-Term IR=bbb-。stable outlook 候選不得採用。",
        "rejected_candidate_value": "bbb+ Under Review with Negative Implications",
        "rejected_candidate_source": "AM Best",
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
        "cross_run_previous_report_date": "20260908",
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
        "period": "2026Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "無負面消息",
        "source_url_or_name": "Brighthouse Financial Investor Relations",
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
        "note": "截至目前，所有公開資料均未提及 BHFAL 次順位債券的付息有任何異常情況。",
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
        "cross_run_consistency_status": "not_comparable",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "Current",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260904",
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
        "period": "2026Q2",
        "status": "資料不足",
        "confidence": "中",
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
        "note": "Aquarian Capital 收購 Brighthouse Financial 的交易仍在進行監管審批中，預計 2026 年完成。雖然公司將作為獨立實體運營，但關於 BHFAL 次順位債券的存續、掛牌、贖回或付息的具體條款在公開報告中未明確說明。",
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
        "missing_type": "metric_detail",
        "metric_name": "Aquarian merger / change-of-control treatment",
        "reason": "官方公告及媒體報導未明確說明 BHFAL 次順位債券在併購完成後的具體條款",
        "risk_impact": "缺乏併購後 BHFAL 的存續、掛牌、贖回或付息條款細節，使投資人對其未來地位存在不確定性，可能影響債券流動性和價格穩定性。",
        "source_candidates": [
          "SEC 8-K",
          "Brighthouse Financial Investor Relations",
          "併購協議詳細條款"
        ],
        "acceptance_criteria": "需找到併購協議中針對 BHFAL 次順位債券的具體條款，包括是否存續、掛牌交易狀況、是否有贖回選擇權或付息條款變更等。"
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
      "cutoff_date": "2026-08-26",
      "today": "2026-09-08",
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
      "latest_price": 15.13,
      "price_as_of": "2026-09-04",
      "open": 15.239999771118164,
      "high": 15.25,
      "low": 15.100000381469727,
      "volume": 21400,
      "bid": null,
      "ask": null,
      "annual_interest": 1.5625,
      "current_yield": 10.3272,
      "quote_source": "Yahoo Finance chart (query1.finance.yahoo.com)",
      "source_host": "query1.finance.yahoo.com",
      "quote_status": "ok",
      "freshness_status": "fresh",
      "security_identity_status": "matched_symbol",
      "source_timestamp": 1788528600,
      "market_quote_patch_version": "1.3.7",
      "returned_symbol": "BHFAL",
      "currency": "USD",
      "exchange_name": "NMS",
      "instrument_type": "EQUITY",
      "regular_market_price_meta": 15.13,
      "regular_market_time_meta": 1788552000,
      "reference_session_date": "2026-09-07",
      "weekday_gap": 1,
      "http_status": 200,
      "request_url": "https://query1.finance.yahoo.com/v8/finance/chart/BHFAL",
      "request_attempt": 1,
      "attempts": [
        {
          "source_host": "query1.finance.yahoo.com",
          "quote_status": "ok",
          "freshness_status": "fresh",
          "price_as_of": "2026-09-04",
          "latest_price": 15.13,
          "error": null
        },
        {
          "source_host": "query2.finance.yahoo.com",
          "quote_status": "ok",
          "freshness_status": "fresh",
          "price_as_of": "2026-09-04",
          "latest_price": 15.13,
          "error": null
        }
      ],
      "source_validation": "cross_checked",
      "source_crosscheck_price": 15.13,
      "source_crosscheck_host": "query2.finance.yahoo.com",
      "source_conflict_pct": 0.0
    }
  },
  {
    "target_name": "OPI",
    "events": [
      {
        "date": "2026-08-27",
        "title": "分析文章探討OPI破產重整後的復甦前景",
        "impact_direction": "中性",
        "impact_severity": 3,
        "confidence": "中",
        "summary_30": "一篇分析文章討論OPI在完成重整與發布Q2財報後，於辦公室市場的復甦挑戰。",
        "links": [
          "Kalkine"
        ],
        "event_source_quality": "unknown",
        "event_source_quality_details": [
          "unknown"
        ],
        "event_verification_status": "unverified",
        "event_days_old": 12,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event",
        "merged_duplicate_count": 1
      }
    ],
    "綜合分析": "公司在完成破產重整與第二季財報發布後，受限於辦公室市場整體需求疲弱，業務復甦前景仍充滿極大挑戰。",
    "事件總分": "正向0 / 負向0 / 總分+0",
    "new_sources_found": [
      "Kalkine"
    ],
    "event_merge_source": "ai_stage2",
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
        "note": "公司報告總投資組合出租率為77.9%，而可比物業投資組合出租率為88.7%。",
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
        "official_reference_source": "Office Properties Income Trust 2026 Q2 Form 10-Q"
      },
      {
        "ticker": "OPI",
        "metric_name": "Debt maturity schedule",
        "metric_category": "債務到期牆",
        "value": "總債務約$1.7B，加權平均到期日3年。主要到期：2026年$20M (8.375% Senior Secured Notes)，2027年$30M (8.375% Senior Secured Notes)，2029年$300M (9.0% Senior Secured Notes) 及 $45M (8.375% Senior Secured Notes)，2031年約$420M (10.0% Senior Secured Notes)。",
        "unit": "USD/date",
        "period": "As of June 30, 2026",
        "status": "已取得",
        "confidence": "高",
        "source": "OPI Q2 2026 Earnings Call Transcript / BusinessWire / SEC Filing",
        "source_url_or_name": "BusinessWire, Seeking Alpha, SEC Filing",
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
        "note": "公司已透過重整減少約7.14億美元債務，並延長了到期期限。管理層正積極處理2027年1月的信貸工具再融資。",
        "definition_scope": "Consolidated debt and specific note maturities.",
        "measurement_form": "Point in time; Schedule",
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
          "court_docket"
        ],
        "source_conflict_flag": true,
        "source_conflict_reason": "實際來源混合官方與次級/AI來源",
        "metric_period_parsed_date": "2026-09-08",
        "metric_period_parse_status": "year_only",
        "metric_period_type": "year",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "partially_verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "definition_changed",
        "calculation_basis": "",
        "cross_run_previous_value": "見摘要",
        "cross_run_previous_period": "截至 2026 年 6 月 30 日",
        "cross_run_previous_report_date": "20260819",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period 有前值，但 definition_scope / calculation_basis 不同，不互相覆寫。"
      },
      {
        "ticker": "OPI",
        "metric_name": "Liquidity / cash availability",
        "metric_category": "流動性",
        "value": "非限制性現金 $51.0 million；限制性現金 $53.0 million；預計資產出售總收益超過 $275.0 million。",
        "unit": "USD",
        "period": "2026Q2 (As of June 30, 2026)",
        "status": "已取得",
        "confidence": "高",
        "source": "OPI Q2 2026 Earnings Call Transcript",
        "source_url_or_name": "Seeking Alpha",
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
        "note": "截至第二季度末，公司持有非限制性現金5,100萬美元，並預期透過資產出售獲得超過2.75億美元以增強流動性。",
        "definition_scope": "Unrestricted and Restricted Cash.",
        "measurement_form": "Point in time",
        "source_quality_primary": "secondary_site",
        "source_quality": "secondary_site",
        "source_quality_details": [
          "secondary_site"
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
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "unverified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "definition_changed",
        "calculation_basis": "",
        "cross_run_previous_value": "51000000 ( unrestricted ); 53000000 ( restricted )",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260904",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period 有前值，但 definition_scope / calculation_basis 不同，不互相覆寫。"
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
        "note": "根據財報電話會議，第二季度Normalized FFO為1,900萬美元。依據公司監控設定，此數值未區分重整前後的Successor/Predecessor期間，故更詳細的區分數據被列為資料不足。",
        "metric_origin": "stage1_deterministic_merge",
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
        "official_reference_source": "Office Properties Income Trust 2026 Q2 Form 10-Q"
      }
    ],
    "missing_data": [],
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
    "dropped_old_events": [],
    "event_date_filter_summary": {
      "lookback_days": 14,
      "cutoff_date": "2026-08-26",
      "today": "2026-09-08",
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
    "event_dedup_patch_version": "1.3.3",
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
        "metric_name": "AFFO / FFO (Successor/Predecessor periods)",
        "reason": "本次搜尋未找到官方財報中明確區分Successor (2026年6月18-30日) 與 Predecessor (2026年4月1日-6月17日) 期間的Normalized FFO個別數值。",
        "risk_impact": "缺乏詳細的期間區分數據，可能影響對OPI重整前後現金流表現的精確評估。",
        "source_candidates": [
          "SEC 10-Q",
          "Earnings Supplement"
        ],
        "acceptance_criteria": "下次需填入 Successor period 及 Predecessor period 的 Normalized FFO 總金額與每股金額；若查無，需說明查詢過哪些來源。",
        "resolution": "resolved_by_v13831_opi_summary_reconciliation",
        "opi_summary_reconciliation_patch_version": "1.3.8.3.1"
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
    "resolved_metric_duplicates": [],
    "opi_structured_cleanup_patch_version": "1.3.8.3.2",
    "opi_structured_duplicate_removed_count": 0
  },
  {
    "target_name": "AXS-E",
    "events": [
      {
        "date": "2026-09-04",
        "title": "AM Best 確認 AXIS Capital 及其營運子公司信用評級為 A (Excellent)，展望穩定",
        "impact_direction": "正向",
        "impact_severity": 3,
        "confidence": "高",
        "summary_30": "AM Best 確認 AXIS Capital 主要信用評級，展望穩定，顯示公司財務實力穩健。",
        "links": [
          "AM Best",
          "AXIS Capital Investor Relations",
          "GlobeNewswire"
        ],
        "event_source_quality": "official_ir",
        "event_source_quality_details": [
          "official_ir",
          "rating_agency",
          "press_release"
        ],
        "event_verification_status": "verified",
        "event_days_old": 4,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event",
        "merged_duplicate_count": 1
      }
    ],
    "綜合分析": "獲 AM Best 確認 A 級優良評級且展望穩定，顯示公司整體財務結構堅實且信用風險極低。",
    "事件總分": "正向3 / 負向0 / 總分+3",
    "new_sources_found": [
      "AM Best",
      "AXIS Capital Investor Relations",
      "GlobeNewswire"
    ],
    "event_merge_source": "ai_stage2",
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
        "source": "AXIS Capital Investor Relations",
        "source_url_or_name": "AXIS Capital Investor Relations / Q2 2026 Press Release",
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
        "note": "保險業務綜合成本率為90.0%，再保險業務為94.5%。",
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
        "cross_run_consistency_status": "consistent_with_prior_range",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "93.1",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260908",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 數值表達不同，但目前值落在前一可信區間內。"
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
        "source": "AXIS Capital Investor Relations",
        "source_url_or_name": "AXIS Capital Investor Relations / Q2 2026 Press Release",
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
        "note": "稅前、再保險淨額後巨災與天氣相關損失為8000萬美元，其中自然災害4900萬美元，中東衝突3100萬美元。",
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
        "metric_consistency_reason": "同 period / definition 前值=80，本次=$80 million；區間不重疊。",
        "cross_run_consistency_status": "value_changed_same_definition",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "80",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260908",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 前值=80，本次=$80 million；區間不重疊。"
      },
      {
        "ticker": "AXS-E",
        "metric_name": "Preferred dividend status",
        "metric_category": "配息狀態",
        "value": "$0.34375",
        "unit": "status",
        "period": "下次預計支付日期2026年10月15日",
        "status": "已取得",
        "confidence": "高",
        "source": "Dividend.com / QuantumOnline.com / Market Chameleon",
        "source_url_or_name": "Dividend.com / QuantumOnline.com / Market Chameleon",
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
        "note": "此為5.50% Series E優先股的季度股息，目前無延遲、暫停或取消消息。最近一次支付日期為2026年7月15日，下一預計除息日為2026年9月29日-10月2日。",
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
        "metric_period_parsed_date": "2026-10-15",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "date",
        "metric_period_freshness": "future_or_invalid_period",
        "metric_integrity_status": "pass",
        "metric_verification_status": "unverified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "no_prior_same_period",
        "definition_scope": "",
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
      "cutoff_date": "2026-08-26",
      "today": "2026-09-08",
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
    },
    "excluded_low_trust_event_count": 0,
    "merged_duplicate_event_count": 0,
    "event_dedup_patch_version": "1.3.3"
  },
  {
    "target_name": "F-B",
    "events": [
      {
        "date": "2026-09-08",
        "title": "福特整合服務總裁將出席高盛會議",
        "impact_direction": "中性偏正向",
        "impact_severity": 2,
        "confidence": "高",
        "summary_30": "福特整合服務總裁Mike Aragon將出席高盛會議，與投資人互動。",
        "links": [
          "Ford Investor Relations"
        ],
        "event_source_quality": "official_ir",
        "event_source_quality_details": [
          "official_ir"
        ],
        "event_verification_status": "verified",
        "event_days_old": 0,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event",
        "merged_duplicate_count": 1
      },
      {
        "date": "2026-09-02",
        "title": "福特公佈2026年8月美國銷售數據",
        "impact_direction": "中性",
        "impact_severity": 1,
        "confidence": "高",
        "summary_30": "福特公佈其2026年8月美國銷售數據，為常規業務更新。",
        "links": [
          "Ford Investor Relations"
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
      },
      {
        "date": "2026-09-01",
        "title": "福特召回近14.9萬輛野馬汽車，存在動力損失風險",
        "impact_direction": "負向",
        "impact_severity": 4,
        "confidence": "高",
        "summary_30": "福特因電線線束問題召回2024-2026年式Mustang，恐導致失去動力。",
        "links": [
          "CBS News",
          "Consumer Affairs",
          "Ford Owner Support"
        ],
        "event_source_quality": "unknown",
        "event_source_quality_details": [
          "unknown"
        ],
        "event_verification_status": "unverified",
        "event_days_old": 7,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event",
        "merged_duplicate_count": 1
      },
      {
        "date": "2026-08-27",
        "title": "福特能源新總裁任命，現任總裁將退休",
        "impact_direction": "中性偏正向",
        "impact_severity": 2,
        "confidence": "高",
        "summary_30": "福特任命Dave Carroll為Ford Energy總裁，現任Lisa Drake將於年底退休。",
        "links": [
          "Ford Investor Relations",
          "BusinessWire",
          "SeekingAlpha"
        ],
        "event_source_quality": "official_ir",
        "event_source_quality_details": [
          "official_ir",
          "press_release"
        ],
        "event_verification_status": "verified",
        "event_days_old": 12,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event",
        "merged_duplicate_count": 1
      }
    ],
    "綜合分析": "儘管管理層積極參與市場溝通與進行高層人選過渡，但大規模汽車召回事件短期內加重了營運品質控管風險與成本負擔。",
    "事件總分": "正向4 / 負向4 / 總分+0",
    "new_sources_found": [
      "Ford Investor Relations",
      "CBS News",
      "Consumer Affairs",
      "Ford Owner Support"
    ],
    "event_merge_source": "ai_stage2",
    "metric_data": [
      {
        "ticker": "F-B",
        "metric_name": "Industrial free cash flow",
        "metric_category": "工業現金流",
        "value": "2.1 billion",
        "unit": "USD",
        "period": "2026Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "Ford Motor Company Q2 2026 Earnings Release / SEC 10-Q",
        "source_url_or_name": "Ford Investor Relations, SEC Filing",
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
        "note": "福特Q2 2026調整後自由現金流為21億美元。",
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
        "metric_integrity_status": "pass",
        "metric_verification_status": "partially_verified",
        "metric_consistency_status": "cross_run_conflict",
        "metric_consistency_reason": "同 period / definition 前值=2.1，本次=2.1 billion；區間不重疊。",
        "cross_run_consistency_status": "value_changed_same_definition",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "2.1",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260908",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 前值=2.1，本次=2.1 billion；區間不重疊。"
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
      },
      {
        "ticker": "F-B",
        "priority": "P0",
        "missing_type": "metric_cross_run_consistency",
        "metric_name": "Industrial free cash flow",
        "reason": "同 period / definition 前值=2.1，本次=2.1 billion；區間不重疊。",
        "risk_impact": "工業 FCF 是付息與維持信用評等的重要基礎。",
        "previous_value": "2.1",
        "current_value": "2.1 billion",
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
      "cutoff_date": "2026-08-26",
      "today": "2026-09-08",
      "kept_recent": 4,
      "kept_background": 0,
      "kept_unknown_date": 0,
      "dropped_old": 0
    },
    "metric_consistency_summary": {
      "conflict_count": 1,
      "conflicts": [
        {
          "ticker": "F-B",
          "metric_name": "Industrial free cash flow",
          "metric_value": "2.1 billion",
          "missing_reason": "同 period / definition 前值=2.1，本次=2.1 billion；區間不重疊。",
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
        "cross_run_previous_report_date": "20260908",
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
        "cross_run_previous_report_date": "20260908",
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
        "cross_run_previous_report_date": "20260908",
        "cross_run_previous_definition_scope": "T-Mobile exchange debt assumption and residual Array UZD",
        "cross_run_previous_calculation_basis": "SEC transaction/debt disclosures",
        "cross_run_consistency_reason": "同 period / definition 與前一可信值一致。"
      }
    ],
    "missing_data": [],
    "dropped_old_events": [],
    "event_date_filter_summary": {
      "lookback_days": 14,
      "cutoff_date": "2026-08-26",
      "today": "2026-09-08",
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
      "latest_price": 18.799999,
      "price_as_of": "2026-09-04",
      "open": 18.8700008392334,
      "high": 18.875,
      "low": 18.78499984741211,
      "volume": 9900,
      "bid": null,
      "ask": null,
      "annual_interest": 1.5625,
      "current_yield": 8.3112,
      "quote_source": "Yahoo Finance chart (query1.finance.yahoo.com)",
      "source_host": "query1.finance.yahoo.com",
      "quote_status": "ok",
      "freshness_status": "fresh",
      "security_identity_status": "matched_symbol",
      "source_timestamp": 1788528600,
      "market_quote_patch_version": "1.3.7",
      "returned_symbol": "UZD",
      "currency": "USD",
      "exchange_name": "NYQ",
      "instrument_type": "EQUITY",
      "regular_market_price_meta": 18.8,
      "regular_market_time_meta": 1788552003,
      "reference_session_date": "2026-09-07",
      "weekday_gap": 1,
      "http_status": 200,
      "request_url": "https://query1.finance.yahoo.com/v8/finance/chart/UZD",
      "request_attempt": 1,
      "attempts": [
        {
          "source_host": "query1.finance.yahoo.com",
          "quote_status": "ok",
          "freshness_status": "fresh",
          "price_as_of": "2026-09-04",
          "latest_price": 18.799999,
          "error": null
        },
        {
          "source_host": "query2.finance.yahoo.com",
          "quote_status": "ok",
          "freshness_status": "fresh",
          "price_as_of": "2026-09-04",
          "latest_price": 18.799999,
          "error": null
        }
      ],
      "source_validation": "cross_checked",
      "source_crosscheck_price": 18.799999,
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

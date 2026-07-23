# USPreferredStockDayInfo 每日情報報告

- 生成時間（台灣）：2026-07-23 09:50:14
- 對應 PDF：Stock_News_Report_20260723_095009.pdf
- 用途：供 ChatGPT 排程讀取、查證消息、判斷美國特別股/交易所債/REIT 風險預警。

## 使用者查詢範圍

【目標標的】
- NYSE: CTGG,Qwest Corp 6.500% Senior Notes due 2051
- NASDAQ: BHFAL,Brighthouse Financial Junior Subordinated Debentures Exp 2058
- OPI,Office Properties Income Trust
- NYSE: AXS-E，Axis Cap 100 DS Representing 1 Pref Shs Series E
- NYSE: F-B，福特汽車
- UZD,United States Cellular Corporation - 6.25% NT REDEEM 01/09/2069 USD 25
- NYSE: QVCD，QVC Inc 6.375% Senior Notes

## 逐標的摘要

### 1. CTGG

- 事件總分：正向0 / 負向0 / 總分+0
- 綜合分析：在指定日期範圍內無可報告的相關事件。
- 事件：無

### 2. BHFAL

- 事件總分：正向0 / 負向0 / 總分+0
- 綜合分析：在指定日期範圍內無可報告的相關事件。
- 事件：無

### 3. OPI

- 事件總分：正向0 / 負向0 / 總分+0
- 綜合分析：在指定日期範圍內無可報告的相關事件。
- 事件：無

### 4. AXS-E

- 事件總分：正向0 / 負向0 / 總分+0
- 綜合分析：在指定日期範圍內無可報告的相關事件。
- 事件：無

### 5. F-B

- 事件總分：正向0 / 負向0 / 總分+0
- 綜合分析：在指定日期範圍內無可報告的相關事件。
- 事件：無

### 6. UZD

- 事件總分：正向0 / 負向0 / 總分+0
- 綜合分析：在指定日期範圍內無可報告的相關事件。
- 事件：無

### 7. QVCD

- 事件總分：正向0 / 負向0 / 總分+0
- 綜合分析：在指定日期範圍內無可報告的相關事件。
- 事件：無

## 量化指標與資料缺口

- 量化監控框架版本：1.0
- 說明：v1 先建立每檔應追蹤指標與資料缺口；尚未取得官方數值時，會標示為「資料不足」。

### CTGG 量化監控
- Free cash flow｜狀態：已取得｜驗證：partially_verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：FCF 轉負或展望下修需警戒。
- Debt maturity and exchange offer terms｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：distressed exchange、順位弱化或擔保改變需警戒。
- Credit rating / outlook｜狀態：已取得｜驗證：partially_verified｜來源品質：rating_agency｜期間新鮮度：fresh｜門檻：downgrade、negative outlook 或 selective default 評論需警戒。
- Credit rating / outlook (Qwest Corporation 6.500% Senior Notes due 2051)｜狀態：已取得｜驗證：verified｜來源品質：rating_agency｜期間新鮮度：fresh｜門檻：downgrade、negative outlook 或 selective default 評論需警戒。
- 資料缺口：3 項，關鍵資料缺漏時不可判定為綠燈。

### BHFAL 量化監控
- RBC ratio｜狀態：已取得｜驗證：verified｜來源品質：official_ir｜期間新鮮度：fresh｜門檻：低於 400% 黃燈；低於 350% 橙燈/紅燈；單季大幅下滑需警戒。
- Statutory capital and surplus｜狀態：已取得｜驗證：verified｜來源品質：official_ir｜期間新鮮度：fresh｜門檻：連續下降或重大減損需警戒。
- Holding company cash and liquid assets｜狀態：已取得｜驗證：verified｜來源品質：official_ir｜期間新鮮度：fresh｜門檻：低於未來 12 個月利息與固定支出覆蓋需求需警戒。
- Financial leverage｜狀態：已取得｜驗證：partially_verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：槓桿升高或評等機構負面評論需警戒。
- Credit rating / outlook｜狀態：已取得｜驗證：verified｜來源品質：official_ir｜期間新鮮度：fresh｜門檻：negative outlook、downgrade 或 watch negative 需警戒。
- BHFAL interest payment status｜狀態：已取得｜驗證：verified｜來源品質：official_ir｜期間新鮮度：fresh｜門檻：defer、suspend、delay、non-payment 立即紅燈。
- Aquarian merger / change-of-control treatment｜狀態：已取得｜驗證：partially_verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：未明確說明 BHFAL 存續、掛牌、贖回或付息條款時列資料不足。
- 資料缺口：2 項，關鍵資料缺漏時不可判定為綠燈。

### OPI 量化監控
- Occupancy rate｜狀態：已取得｜驗證：verified｜來源品質：official_ir｜期間新鮮度：fresh｜門檻：連續下降或低於同業顯著水準需警戒。
- AFFO / FFO｜狀態：已取得｜驗證：unverified｜來源品質：unknown｜期間新鮮度：fresh｜門檻：AFFO/FFO 大幅下滑或為負需警戒。
- Debt maturity schedule｜狀態：已取得｜驗證：partially_verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：12-24 個月內大量到期且流動性不足需紅燈。
- Liquidity / cash availability｜狀態：已取得｜驗證：unverified｜來源品質：unknown｜期間新鮮度：fresh｜門檻：流動性不足或 covenant 壓力需警戒。
- 資料缺口：2 項，關鍵資料缺漏時不可判定為綠燈。

### AXS-E 量化監控
- Combined ratio｜狀態：已取得｜驗證：partially_verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：高於 100% 或明顯惡化需警戒。
- Catastrophe losses｜狀態：已取得｜驗證：partially_verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：重大巨災損失超預期需警戒。
- Preferred dividend status｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：defer、suspend、delay 立即紅燈。
- 資料缺口：2 項，關鍵資料缺漏時不可判定為綠燈。

### F-B 量化監控
- Industrial free cash flow｜狀態：已取得｜驗證：partially_verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：FCF 轉負或全年指引大幅下修需警戒。
- Ford Credit delinquencies / credit losses｜狀態：已取得｜驗證：partially_verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：逾期率或信用損失準備明顯上升需警戒。
- Recall / warranty cost｜狀態：已取得｜驗證：unverified｜來源品質：unknown｜期間新鮮度：stale｜門檻：重大召回或保固成本升高需警戒。
- 資料缺口：3 項，關鍵資料缺漏時不可判定為綠燈。

### UZD 量化監控
- Issuer / guarantor status｜狀態：已取得｜驗證：verified｜來源品質：official_ir｜期間新鮮度：fresh｜門檻：發行人或擔保人不明確時列灰燈/黃燈，不可判定安全。
- Asset sale proceeds and use of funds｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：acceptable_recent｜門檻：出售所得若大量分配給股東而非減債需警戒。
- Debt assumption / redemption status｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：acceptable_recent｜門檻：未說明承擔、契約修改或贖回時列資料不足。

### QVCD 量化監控
- Bankruptcy case status｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：Chapter 11 未解除或回收條件未確認，一律紅燈。
- Recovery / exchange terms｜狀態：已取得｜驗證：partially_verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：未知、低回收率、強制交換或展延需紅燈。
- Trading status｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：停牌、退市、轉 OTC 或流動性消失需紅燈。
- 資料缺口：1 項，關鍵資料缺漏時不可判定為綠燈。

## 程式端日期過濾與來源驗證

- 日期過濾版本：1.2.2
- 最近事件保留天數：14 天
- 說明：超出最近 14 日但命中 Chapter 11、收購、重整、退市、債務交換等重大關鍵字者，會保留為 background_risk_event；其他舊事件移至 dropped_old_events。

- CTGG：recent=0，background=0，unknown_date=0，dropped_old=0
- BHFAL：recent=0，background=0，unknown_date=0，dropped_old=0
- OPI：recent=0，background=0，unknown_date=0，dropped_old=0
- AXS-E：recent=0，background=0，unknown_date=0，dropped_old=0
- F-B：recent=0，background=0，unknown_date=0，dropped_old=0
- UZD：recent=0，background=0，unknown_date=0，dropped_old=0
- QVCD：recent=0，background=0，unknown_date=0，dropped_old=0

## 完整 JSON

```json
[
  {
    "target_name": "CTGG",
    "events": [],
    "綜合分析": "在指定日期範圍內無可報告的相關事件。",
    "事件總分": "正向0 / 負向0 / 總分+0",
    "new_sources_found": [],
    "metric_data": [
      {
        "ticker": "CTGG",
        "metric_name": "Free cash flow",
        "metric_category": "現金流",
        "value": "Q1 2026實際自由現金流 (不含特殊項目): 7.56億美元; 2026財年預期自由現金流: 19-21億美元",
        "unit": "USD",
        "period": "2026Q1 / FY2026 Guidance",
        "status": "已取得",
        "confidence": "高",
        "source": "Lumen Technologies Investor Relations / SEC 10-Q",
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
        "warning_threshold": "FCF 轉負或展望下修需警戒。",
        "priority": "P0",
        "risk_impact": "自由現金流不足會影響長債償付能力。",
        "note": "2026財年預期自由現金流包含7.29億美元的大眾市場剝離收益。",
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
        "metric_period_parsed_date": "2026-03-31",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "partially_verified",
        "metric_consistency_status": "conflict_with_missing_data",
        "metric_consistency_reason": "Lumen Technologies Q2 2026 財報尚未發布，預計於 2026 年 8 月 4 日公布。",
        "metric_consistency_missing_type": "metric_value"
      },
      {
        "ticker": "CTGG",
        "metric_name": "Debt maturity and exchange offer terms",
        "metric_category": "債務結構",
        "value": "2026年6月10日完成Qwest債券交換要約，CTGG (Qwest 6.500% 2051年高級票據) 為其新發行債券之一，屬 Qwest 的高級無擔保債務，並由 Lumen Technologies 無條件擔保。",
        "unit": "status/date/USD",
        "period": "2026-06-10",
        "status": "已取得",
        "confidence": "高",
        "source": "BusinessWire, SEC Filings (間接)",
        "source_url_or_name": "Lumen Technologies, Inc. Investor Relations / BusinessWire / Investing.com",
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
        "note": "雖然交換要約完成日期超出 14 天事件範圍，但其結果直接定義了 CTGG 債券的當前條款，對債權安全至關重要。",
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
        "metric_period_parsed_date": "2026-06-10",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "date",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": ""
      },
      {
        "ticker": "CTGG",
        "metric_name": "Credit rating / outlook",
        "metric_category": "信用評等",
        "value": "Lumen Technologies（母公司）最新評等：S&P Issuer Credit Rating 'B-' (2026年2月6日), Senior Unsecured Debt 'B' (2026年2月6日)。Moody's Corporate Family Rating 'B2' (2026年2月23日), Senior Unsecured notes 'Caa1' (2026年2月23日)。Fitch Long-Term IDR 'B' (2026年2月23日), 穩定展望 (2026年4月17日確認)。Qwest Corporation（發行方）最新評等：Moody's Senior Unsecured notes 'Caa1' (2026年2月23日), Fitch IDR 'B' (2026年4月17日)。",
        "unit": "rating",
        "period": "2026年2月/4月",
        "status": "已取得",
        "confidence": "高",
        "source": "S&P Global Ratings / Moody's Investor Service / Fitch Ratings / BusinessWire",
        "source_url_or_name": "S&P Global Ratings",
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
        "note": "過去14天內未發現Lumen或Qwest的最新信用評級變動或展望更新。",
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
        "metric_period_parsed_date": "2026-04-30",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "month_or_month_range",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "partially_verified",
        "metric_consistency_status": "conflict_with_missing_data",
        "metric_consistency_reason": "在指定日期範圍 (最近14日) 內，未找到Lumen Technologies或Qwest Corporation的最新信用評級變動或展望更新。現有資料為2026年2月/4月發布。",
        "metric_consistency_missing_type": "metric_update_frequency"
      },
      {
        "ticker": "CTGG",
        "metric_name": "Credit rating / outlook (Qwest Corporation 6.500% Senior Notes due 2051)",
        "metric_category": "信用評等",
        "value": "BB (Recovery Rating RR1)",
        "unit": "rating",
        "period": "2026年6月16日",
        "status": "已取得",
        "confidence": "高",
        "source": "Fitch Ratings",
        "source_url_or_name": "Fitch Ratings",
        "warning_threshold": "downgrade、negative outlook 或 selective default 評論需警戒。",
        "priority": "P0",
        "risk_impact": "Fitch對Qwest此類債券給予BB評級及RR1高回復評級，顯示其償付能力尚可且違約後回復前景良好。",
        "note": "Moody's於2026年2月將Qwest高級無擔保債券評級上調至Caa1（展望穩定）。S&P於2026年4月對Qwest新債券評級為B，回復評級2。",
        "metric_origin": "stage1_deterministic_merge",
        "metric_integrity_status": "selected_from_stage1",
        "source_quality_primary": "rating_agency",
        "source_quality": "rating_agency",
        "source_quality_details": [
          "rating_agency"
        ],
        "source_candidate_quality_details": [
          "unknown"
        ],
        "source_conflict_flag": false,
        "source_conflict_reason": "",
        "metric_period_parsed_date": "2026-06-16",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "date",
        "metric_period_freshness": "fresh",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": ""
      }
    ],
    "missing_data": [
      {
        "ticker": "CTGG",
        "priority": "P0",
        "missing_type": "metric_value",
        "metric_name": "Qwest Corporation 完整債務到期時間表",
        "reason": "本次搜尋未能取得 Qwest Corporation 截至 2026 年最新、全面且精細的完整債務到期時間表，雖已知 CTGG 的特定條款，但缺乏其與 Qwest 其他債務組合的全面視圖。",
        "risk_impact": "缺乏 Qwest Corporation 的整體債務到期時間表，使得對其未來再融資需求的全面評估存在不確定性，可能間接影響 CTGG 長期償付的信心。",
        "source_candidates": [
          "SEC 10-K",
          "SEC 10-Q",
          "Qwest Investor Relations (若有獨立 IR 頁面)"
        ],
        "acceptance_criteria": "下次搜尋需填入完整的債務到期時間表，包括各系列債券的金額和到期日。"
      },
      {
        "ticker": "CTGG",
        "priority": "P0",
        "missing_type": "metric_consistency",
        "metric_name": "Credit rating / outlook",
        "reason": "在指定日期範圍 (最近14日) 內，未找到Lumen Technologies或Qwest Corporation的最新信用評級變動或展望更新。現有資料為2026年2月/4月發布。",
        "risk_impact": "缺乏最新的信用評級更新，可能導致無法及時評估公司償債能力的潛在變化。",
        "source_candidates": [
          "S&P",
          "Moody's",
          "Fitch",
          "Lumen Investor Relations"
        ],
        "acceptance_criteria": "下次需提供最近14日內的評級更新，若無則持續說明最新日期。",
        "missing_type_original": "metric_update_frequency",
        "conflict_with_metric_data": true,
        "metric_value_present": "Lumen Technologies（母公司）最新評等：S&P Issuer Credit Rating 'B-' (2026年2月6日), Senior Unsecured Debt 'B' (2026年2月6日)。Moody's Corporate Family Rating 'B2' (2026年2月23日), Senior Unsecured notes 'Caa1' (2026年2月23日)。Fitch Long-Term IDR 'B' (2026年2月23日), 穩定展望 (2026年4月17日確認)。Qwest Corporation（發行方）最新評等：Moody's Senior Unsecured notes 'Caa1' (2026年2月23日), Fitch IDR 'B' (2026年4月17日)。",
        "metric_source_present": "S&P Global Ratings / Moody's Investor Service / Fitch Ratings / BusinessWire",
        "metric_verification_after_reconcile": "partially_verified"
      },
      {
        "ticker": "CTGG",
        "priority": "P0",
        "missing_type": "metric_consistency",
        "metric_name": "Free cash flow",
        "reason": "Lumen Technologies Q2 2026 財報尚未發布，預計於 2026 年 8 月 4 日公布。",
        "risk_impact": "缺乏最新的季度自由現金流數據，無法評估公司最近的經營狀況對償債能力的影響。",
        "source_candidates": [
          "Lumen Investor Relations Q2 2026 Earnings Release",
          "SEC 10-Q Q2 2026"
        ],
        "acceptance_criteria": "下次需填入 2026 年 Q2 自由現金流的 value、period、source。",
        "missing_type_original": "metric_value",
        "conflict_with_metric_data": true,
        "metric_value_present": "Q1 2026實際自由現金流 (不含特殊項目): 7.56億美元; 2026財年預期自由現金流: 19-21億美元",
        "metric_source_present": "Lumen Technologies Investor Relations / SEC 10-Q",
        "metric_verification_after_reconcile": "partially_verified"
      }
    ],
    "metric_integrity_issues": [
      {
        "issue": "explicit_cross_ticker_row_rejected",
        "parent_ticker": "CTGG",
        "row_ticker": "LUMN/QWEST",
        "metric_name": "Credit rating / outlook",
        "value": "Lumen 公司家族評級 (CFR): Moody's B2 (展望穩定), 發行人違約評級 (IDR): Fitch B (展望穩定)。Qwest 公司高級無擔保債務評級: Moody's Caa1 (展望穩定), IDR: Fitch B (展望穩定)。S&P 將 Lumen 高級無擔保債務評級上調至 B。"
      },
      {
        "issue": "explicit_cross_ticker_row_rejected",
        "parent_ticker": "CTGG",
        "row_ticker": "LUMN/QWEST",
        "metric_name": "Credit rating / outlook",
        "value": "Moody's: Qwest Corp. 高級無擔保債券 Caa1 (展望穩定)；Fitch: Qwest Corp. IDR 'B' (展望穩定)；S&P: Lumen Technologies 高級無擔保債券 'B' (展望正面，發行人信用評等 'B-')"
      }
    ],
    "metric_merge_source": "stage1_deterministic_merge",
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
    "dropped_old_events": [],
    "event_date_filter_summary": {
      "lookback_days": 14,
      "cutoff_date": "2026-07-10",
      "today": "2026-07-23",
      "kept_recent": 0,
      "kept_background": 0,
      "kept_unknown_date": 0,
      "dropped_old": 0
    },
    "metric_consistency_summary": {
      "conflict_count": 2,
      "conflicts": [
        {
          "ticker": "CTGG",
          "metric_name": "Credit rating / outlook",
          "metric_value": "Lumen Technologies（母公司）最新評等：S&P Issuer Credit Rating 'B-' (2026年2月6日), Senior Unsecured Debt 'B' (2026年2月6日)。Moody's Corporate Family Rating 'B2' (2026年2月23日), Senior Unsecured notes 'Caa1' (2026年2月23日)。Fitch Long-Term IDR 'B' (2026年2月23日), 穩定展望 (2026年4月17日確認)。Qwest Corporation（發行方）最新評等：Moody's Senior Unsecured notes 'Caa1' (2026年2月23日), Fitch IDR 'B' (2026年4月17日)。",
          "missing_reason": "在指定日期範圍 (最近14日) 內，未找到Lumen Technologies或Qwest Corporation的最新信用評級變動或展望更新。現有資料為2026年2月/4月發布。",
          "verification_after_reconcile": "partially_verified"
        },
        {
          "ticker": "CTGG",
          "metric_name": "Free cash flow",
          "metric_value": "Q1 2026實際自由現金流 (不含特殊項目): 7.56億美元; 2026財年預期自由現金流: 19-21億美元",
          "missing_reason": "Lumen Technologies Q2 2026 財報尚未發布，預計於 2026 年 8 月 4 日公布。",
          "verification_after_reconcile": "partially_verified"
        }
      ]
    }
  },
  {
    "target_name": "BHFAL",
    "events": [],
    "綜合分析": "在指定日期範圍內無可報告的相關事件。",
    "事件總分": "正向0 / 負向0 / 總分+0",
    "new_sources_found": [],
    "metric_data": [
      {
        "ticker": "BHFAL",
        "metric_name": "RBC ratio",
        "metric_category": "保險償付能力",
        "value": "430%-450%",
        "unit": "%",
        "period": "2026Q1 (截至3月31日)",
        "status": "已取得",
        "confidence": "高",
        "source": "Brighthouse Financial Q1 2026 Earnings Release / Financial Supplement",
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
        "warning_threshold": "低於 400% 黃燈；低於 350% 橙燈/紅燈；單季大幅下滑需警戒。",
        "priority": "P0",
        "risk_impact": "RBC 下滑可能代表保險子公司資本緩衝下降，影響次順位債付息與信用評等。",
        "note": "處於公司目標範圍 (400%-450%) 之上限。",
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
        "metric_period_parsed_date": "2026-03-31",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": ""
      },
      {
        "ticker": "BHFAL",
        "metric_name": "Statutory capital and surplus",
        "metric_category": "法定資本",
        "value": "50億美元",
        "unit": "USD",
        "period": "2026Q1 (截至3月31日)",
        "status": "已取得",
        "confidence": "高",
        "source": "Brighthouse Financial Q1 2026 Earnings Release / Financial Supplement",
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
        "warning_threshold": "連續下降或重大減損需警戒。",
        "priority": "P0",
        "risk_impact": "法定資本下降會削弱保險子公司分派能力與控股公司資金來源。",
        "note": "較上季有所下降，但公司歸因於非趨勢性項目，如基準風險。",
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
        "metric_period_parsed_date": "2026-03-31",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": ""
      },
      {
        "ticker": "BHFAL",
        "metric_name": "Holding company cash and liquid assets",
        "metric_category": "控股公司流動性",
        "value": "0.9億美元",
        "unit": "USD",
        "period": "2026Q1 (截至3月31日)",
        "status": "已取得",
        "confidence": "高",
        "source": "Brighthouse Financial Q1 2026 Earnings Release / Financial Supplement",
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
        "warning_threshold": "低於未來 12 個月利息與固定支出覆蓋需求需警戒。",
        "priority": "P0",
        "risk_impact": "控股公司流動性不足可能影響 BHFAL 利息支付。",
        "note": "Stage 1/Stage 2 已回填此量化指標。",
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
        "metric_period_parsed_date": "2026-03-31",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": ""
      },
      {
        "ticker": "BHFAL",
        "metric_name": "Financial leverage",
        "metric_category": "槓桿",
        "value": "0.57",
        "unit": "%",
        "period": "2026Q1 (TTM)",
        "status": "已取得",
        "confidence": "高",
        "source": "MLQ.ai (引用SEC EDGAR)",
        "source_url_or_name": "MLQ.ai",
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
        "note": "TTM (Trailing Twelve Months) 數據。",
        "source_quality_primary": "sec_filing",
        "source_quality": "sec_filing",
        "source_quality_details": [
          "sec_filing",
          "secondary_site"
        ],
        "source_candidate_quality_details": [
          "sec_filing",
          "official_ir",
          "rating_agency"
        ],
        "source_conflict_flag": true,
        "source_conflict_reason": "實際來源混合官方與次級/AI來源",
        "metric_period_parsed_date": "2026-03-31",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "partially_verified",
        "metric_consistency_status": "conflict_with_missing_data",
        "metric_consistency_reason": "本次搜尋未找到 2026 年第一季或最新官方數值。",
        "metric_consistency_missing_type": "metric_value"
      },
      {
        "ticker": "BHFAL",
        "metric_name": "Credit rating / outlook",
        "metric_category": "信用評等",
        "value": "AM Best: A/Excellent (審查負面中); Moody's: A3/Upper Medium (審查降級中); Fitch: A-/Strong (穩定); S&P: A/Strong (列入負面信用觀察)",
        "unit": "rating",
        "period": "2026年3月 (最新更新)",
        "status": "已取得",
        "confidence": "高",
        "source": "Brighthouse Financial Investor Relations, AM Best, Moody's, Fitch, S&P",
        "source_url_or_name": "Brighthouse Financial Investor Relations, AM Best, Moody's, Fitch, S&P",
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
        "note": "多家評等機構已將其列入負面審查或信用觀察名單，主要受Aquarian併購案影響。Fitch已於2025年11月將評級下調至BBB+，但展望穩定。",
        "source_quality_primary": "official_ir",
        "source_quality": "official_ir",
        "source_quality_details": [
          "official_ir",
          "rating_agency"
        ],
        "source_candidate_quality_details": [
          "sec_filing",
          "official_ir",
          "rating_agency"
        ],
        "source_conflict_flag": false,
        "source_conflict_reason": "",
        "metric_period_parsed_date": "2026-03-31",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "month_or_month_range",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": ""
      },
      {
        "ticker": "BHFAL",
        "metric_name": "BHFAL interest payment status",
        "metric_category": "付息狀態",
        "value": "正常",
        "unit": "status",
        "period": "2026Q1",
        "status": "已取得",
        "confidence": "高",
        "source": "Brighthouse Financial First Quarter 2026 Results, Brighthouse Financial Investor Relations",
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
        "note": "根據最新財報與流動性資料判斷，無付息異常報告。",
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
        "metric_period_parsed_date": "2026-03-31",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": ""
      },
      {
        "ticker": "BHFAL",
        "metric_name": "Aquarian merger / change-of-control treatment",
        "metric_category": "交易條款",
        "value": "股東已批准合併，交易預計2026年完成；近期因收購方關聯公司遭調查，增加交易不確定性",
        "unit": "status",
        "period": "2026年2月12日 (股東批准) / 2026年7月21日 (調查新聞)",
        "status": "已取得",
        "confidence": "高",
        "source": "SEC Filing / BusinessWire / GuruFocus",
        "source_url_or_name": "SEC Filing (8-K)",
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
        "note": "次順位債預計在收購完成後繼續存在，但其信用狀況將受新母公司影響。",
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
        "metric_period_parsed_date": "2026-07-21",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "date",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "partially_verified",
        "metric_consistency_status": "conflict_with_missing_data",
        "metric_consistency_reason": "本次搜尋未找到明確說明 Aquarian Capital 收購後 BHFAL 次順位債存續、掛牌、贖回或付息條款的官方資訊。",
        "metric_consistency_missing_type": "metric_value"
      }
    ],
    "missing_data": [
      {
        "ticker": "BHFAL",
        "priority": "P1",
        "missing_type": "metric_consistency",
        "metric_name": "Financial leverage",
        "reason": "本次搜尋未找到 2026 年第一季或最新官方數值。",
        "risk_impact": "槓桿數據對於評估 BHFAL 的安全邊際至關重要，其缺失限制了全面風險評估。",
        "source_candidates": [
          "Brighthouse Financial Investor Relations",
          "SEC 10-Q",
          "SEC 10-K",
          "Earnings Supplement",
          "S&P",
          "Moody's",
          "Fitch"
        ],
        "acceptance_criteria": "下次需填入 value、period、source；若查無，需說明查詢過哪些來源",
        "missing_type_original": "metric_value",
        "conflict_with_metric_data": true,
        "metric_value_present": "0.57",
        "metric_source_present": "MLQ.ai (引用SEC EDGAR)",
        "metric_verification_after_reconcile": "partially_verified"
      },
      {
        "ticker": "BHFAL",
        "priority": "P0",
        "missing_type": "metric_consistency",
        "metric_name": "Aquarian merger / change-of-control treatment",
        "reason": "本次搜尋未找到明確說明 Aquarian Capital 收購後 BHFAL 次順位債存續、掛牌、贖回或付息條款的官方資訊。",
        "risk_impact": "收購完成後可能影響 BHFAL 的掛牌、流動性與資本政策，對次順位債投資者而言，缺乏明確條款會增加不確定性。",
        "source_candidates": [
          "Brighthouse Financial Investor Relations",
          "SEC 8-K",
          "SEC 10-K",
          "Merger Agreement documents"
        ],
        "acceptance_criteria": "下次需填入 value、period、source；若查無，需說明查詢過哪些來源",
        "missing_type_original": "metric_value",
        "conflict_with_metric_data": true,
        "metric_value_present": "股東已批准合併，交易預計2026年完成；近期因收購方關聯公司遭調查，增加交易不確定性",
        "metric_source_present": "SEC Filing / BusinessWire / GuruFocus",
        "metric_verification_after_reconcile": "partially_verified"
      }
    ],
    "metric_integrity_issues": [],
    "metric_merge_source": "stage1_deterministic_merge",
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
      "cutoff_date": "2026-07-10",
      "today": "2026-07-23",
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
          "metric_name": "Financial leverage",
          "metric_value": "0.57",
          "missing_reason": "本次搜尋未找到 2026 年第一季或最新官方數值。",
          "verification_after_reconcile": "partially_verified"
        },
        {
          "ticker": "BHFAL",
          "metric_name": "Aquarian merger / change-of-control treatment",
          "metric_value": "股東已批准合併，交易預計2026年完成；近期因收購方關聯公司遭調查，增加交易不確定性",
          "missing_reason": "本次搜尋未找到明確說明 Aquarian Capital 收購後 BHFAL 次順位債存續、掛牌、贖回或付息條款的官方資訊。",
          "verification_after_reconcile": "partially_verified"
        }
      ]
    }
  },
  {
    "target_name": "OPI",
    "events": [],
    "綜合分析": "在指定日期範圍內無可報告的相關事件。",
    "事件總分": "正向0 / 負向0 / 總分+0",
    "new_sources_found": [],
    "metric_data": [
      {
        "ticker": "OPI",
        "metric_name": "Occupancy rate",
        "metric_category": "出租率",
        "value": "81.3%",
        "unit": "%",
        "period": "最新 (截至2026年6月重組完成後)",
        "status": "已取得",
        "confidence": "高",
        "source": "OPI Investor Relations",
        "source_url_or_name": "OPI Investor Relations",
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
        "note": "此為公司官網「一覽」數據，推測為重組後最新可用數據。",
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
        "metric_period_type": "month_or_month_range",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": ""
      },
      {
        "ticker": "OPI",
        "metric_name": "AFFO / FFO",
        "metric_category": "現金流",
        "value": "-$93.0M (Net Loss)",
        "unit": "USD",
        "period": "2026Q1",
        "status": "已取得",
        "confidence": "高",
        "source": "Office Properties Income Trust Q1 2026 Supplemental Report",
        "source_url_or_name": "Minichart, WallStreetZen, Timothy Sykes",
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
        "note": "未直接報告AFFO/FFO，以淨虧損為參考，EPS為-$1.26。",
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
        "metric_period_parsed_date": "2026-03-31",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "unverified",
        "metric_consistency_status": "conflict_with_missing_data",
        "metric_consistency_reason": "本次搜尋未找到重組後官方最新AFFO/FFO數值。最近的Q1 2026數據為重組前，不具代表性。",
        "metric_consistency_missing_type": "metric_value"
      },
      {
        "ticker": "OPI",
        "metric_name": "Debt maturity schedule",
        "metric_category": "債務到期牆",
        "value": "總計約17億美元，主要包括: 4.25億美元循環信用額度 (9.1%), 3億美元2029年到期高級擔保票據 (9.0%), 1.77億美元抵押債務, 3.85億美元2029年到期新發高級擔保票據 (8.375%), 4.2億美元2031年到期新發高級擔保票據 (10.0%)",
        "unit": "USD/date",
        "period": "2026-06-17 (重整後)",
        "status": "已取得",
        "confidence": "高",
        "source": "SEC 8-K Filing / Business Wire",
        "source_url_or_name": "SEC Filing, Business Wire",
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
        "note": "重整後債務規模與結構，部分債券利率高且未來幾年有本金償還計畫。",
        "source_quality_primary": "sec_filing",
        "source_quality": "sec_filing",
        "source_quality_details": [
          "sec_filing",
          "press_release"
        ],
        "source_candidate_quality_details": [
          "sec_filing",
          "official_ir",
          "court_docket"
        ],
        "source_conflict_flag": false,
        "source_conflict_reason": "",
        "metric_period_parsed_date": "2026-06-17",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "date",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "partially_verified",
        "metric_consistency_status": "conflict_with_missing_data",
        "metric_consistency_reason": "本次搜尋未找到重組後詳細的債務到期時間表。僅知債務已削減並發行新票據。",
        "metric_consistency_missing_type": "metric_value"
      },
      {
        "ticker": "OPI",
        "metric_name": "Liquidity / cash availability",
        "metric_category": "流動性",
        "value": "Free Cash Flow: -$67.97M; Operating Cash Flow: -$52.94M; Current Ratio: 0.9; Quick Ratio: 0.2",
        "unit": "USD",
        "period": "2026Q1",
        "status": "已取得",
        "confidence": "高",
        "source": "StocksToTrade",
        "source_url_or_name": "StocksToTrade",
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
        "note": "根據最新報告季度數據，顯示流動性壓力持續存在。",
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
        "metric_period_parsed_date": "2026-03-31",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "unverified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": ""
      }
    ],
    "missing_data": [
      {
        "ticker": "OPI",
        "priority": "P0",
        "missing_type": "metric_consistency",
        "metric_name": "AFFO / FFO",
        "reason": "本次搜尋未找到重組後官方最新AFFO/FFO數值。最近的Q1 2026數據為重組前，不具代表性。",
        "risk_impact": "AFFO/FFO是REIT核心現金流指標，缺乏重組後數據使評估其派息和債務服務能力受限。",
        "source_candidates": [
          "OPI Investor Relations",
          "SEC 10-Q",
          "Earnings Supplement",
          "Bankruptcy court docket"
        ],
        "acceptance_criteria": "下次需填入 value、period、source；若查無，需說明查詢過哪些來源",
        "missing_type_original": "metric_value",
        "conflict_with_metric_data": true,
        "metric_value_present": "-$93.0M (Net Loss)",
        "metric_source_present": "Office Properties Income Trust Q1 2026 Supplemental Report",
        "metric_verification_after_reconcile": "unverified"
      },
      {
        "ticker": "OPI",
        "priority": "P0",
        "missing_type": "metric_consistency",
        "metric_name": "Debt maturity schedule",
        "reason": "本次搜尋未找到重組後詳細的債務到期時間表。僅知債務已削減並發行新票據。",
        "risk_impact": "缺乏新的債務到期時間表無法有效評估OPI未來再融資壓力和潛在違約風險。",
        "source_candidates": [
          "OPI Investor Relations",
          "SEC 10-Q",
          "SEC 10-K",
          "Bankruptcy court docket"
        ],
        "acceptance_criteria": "下次需填入 value、period、source；若查無，需說明查詢過哪些來源",
        "missing_type_original": "metric_value",
        "conflict_with_metric_data": true,
        "metric_value_present": "總計約17億美元，主要包括: 4.25億美元循環信用額度 (9.1%), 3億美元2029年到期高級擔保票據 (9.0%), 1.77億美元抵押債務, 3.85億美元2029年到期新發高級擔保票據 (8.375%), 4.2億美元2031年到期新發高級擔保票據 (10.0%)",
        "metric_source_present": "SEC 8-K Filing / Business Wire",
        "metric_verification_after_reconcile": "partially_verified"
      }
    ],
    "metric_integrity_issues": [],
    "metric_merge_source": "stage1_deterministic_merge",
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
      "cutoff_date": "2026-07-10",
      "today": "2026-07-23",
      "kept_recent": 0,
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
          "metric_value": "-$93.0M (Net Loss)",
          "missing_reason": "本次搜尋未找到重組後官方最新AFFO/FFO數值。最近的Q1 2026數據為重組前，不具代表性。",
          "verification_after_reconcile": "unverified"
        },
        {
          "ticker": "OPI",
          "metric_name": "Debt maturity schedule",
          "metric_value": "總計約17億美元，主要包括: 4.25億美元循環信用額度 (9.1%), 3億美元2029年到期高級擔保票據 (9.0%), 1.77億美元抵押債務, 3.85億美元2029年到期新發高級擔保票據 (8.375%), 4.2億美元2031年到期新發高級擔保票據 (10.0%)",
          "missing_reason": "本次搜尋未找到重組後詳細的債務到期時間表。僅知債務已削減並發行新票據。",
          "verification_after_reconcile": "partially_verified"
        }
      ]
    }
  },
  {
    "target_name": "AXS-E",
    "events": [],
    "綜合分析": "在指定日期範圍內無可報告的相關事件。",
    "事件總分": "正向0 / 負向0 / 總分+0",
    "new_sources_found": [],
    "metric_data": [
      {
        "ticker": "AXS-E",
        "metric_name": "Combined ratio",
        "metric_category": "承保獲利",
        "value": "89.8",
        "unit": "%",
        "period": "2026 Q1",
        "status": "已取得",
        "confidence": "高",
        "source": "AXIS Capital Investor Relations / SEC Filing",
        "source_url_or_name": "AXIS Capital Holdings Limited Q1 2026 Earnings Release",
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
        "note": "Q2 2026財報預計於7月28日發布。",
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
        "metric_period_parsed_date": "2026-03-31",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "partially_verified",
        "metric_consistency_status": "conflict_with_missing_data",
        "metric_consistency_reason": "2026年第二季度財報尚未發布，預計於2026年7月28日公布。",
        "metric_consistency_missing_type": "metric_value"
      },
      {
        "ticker": "AXS-E",
        "metric_name": "Catastrophe losses",
        "metric_category": "巨災損失",
        "value": "48",
        "unit": "USD",
        "period": "2026 Q1",
        "status": "已取得",
        "confidence": "高",
        "source": "AXIS Capital Investor Relations / SEC Filing",
        "source_url_or_name": "AXIS Capital Holdings Limited Q1 2026 Earnings Release",
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
        "note": "Q2 2026財報預計於7月28日發布，屆時將有最新數據。",
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
        "metric_period_parsed_date": "2026-03-31",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "partially_verified",
        "metric_consistency_status": "conflict_with_missing_data",
        "metric_consistency_reason": "2026年第二季度財報尚未發布，預計於2026年7月28日公布。",
        "metric_consistency_missing_type": "metric_value"
      },
      {
        "ticker": "AXS-E",
        "metric_name": "Preferred dividend status",
        "metric_category": "配息狀態",
        "value": "已支付",
        "unit": "status",
        "period": "2026Q2 (支付日期 7/15)",
        "status": "已取得",
        "confidence": "高",
        "source": "AXIS Capital Investor Relations / SEC Filing",
        "source_url_or_name": "AXIS Capital Press Release",
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
        "note": "股息已正常支付，顯示對優先股股東承諾良好。",
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
        "metric_period_parsed_date": "2026-06-30",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": ""
      }
    ],
    "missing_data": [
      {
        "ticker": "AXS-E",
        "priority": "P1",
        "missing_type": "metric_consistency",
        "metric_name": "Combined ratio",
        "reason": "2026年第二季度財報尚未發布，預計於2026年7月28日公布。",
        "risk_impact": "缺乏最新財報數據，無法評估最新承保獲利變化，可能影響對優先股安全邊際的即時判斷。",
        "source_candidates": [
          "AXIS Investor Relations",
          "SEC 10-Q",
          "Earnings Release"
        ],
        "acceptance_criteria": "下次需填入 value、period、source；若查無，需說明查詢過哪些來源",
        "missing_type_original": "metric_value",
        "conflict_with_metric_data": true,
        "metric_value_present": "89.8",
        "metric_source_present": "AXIS Capital Investor Relations / SEC Filing",
        "metric_verification_after_reconcile": "partially_verified"
      },
      {
        "ticker": "AXS-E",
        "priority": "P1",
        "missing_type": "metric_consistency",
        "metric_name": "Catastrophe losses",
        "reason": "2026年第二季度財報尚未發布，預計於2026年7月28日公布。",
        "risk_impact": "缺乏最新財報數據，無法評估最新巨災損失情況，可能影響對優先股安全邊際的即時判斷。",
        "source_candidates": [
          "AXIS Investor Relations",
          "SEC 10-Q",
          "Earnings Release"
        ],
        "acceptance_criteria": "下次需填入 value、period、source；若查無，需說明查詢過哪些來源",
        "missing_type_original": "metric_value",
        "conflict_with_metric_data": true,
        "metric_value_present": "48",
        "metric_source_present": "AXIS Capital Investor Relations / SEC Filing",
        "metric_verification_after_reconcile": "partially_verified"
      }
    ],
    "metric_integrity_issues": [],
    "metric_merge_source": "stage1_deterministic_merge",
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
      "cutoff_date": "2026-07-10",
      "today": "2026-07-23",
      "kept_recent": 0,
      "kept_background": 0,
      "kept_unknown_date": 0,
      "dropped_old": 0
    },
    "metric_consistency_summary": {
      "conflict_count": 2,
      "conflicts": [
        {
          "ticker": "AXS-E",
          "metric_name": "Combined ratio",
          "metric_value": "89.8",
          "missing_reason": "2026年第二季度財報尚未發布，預計於2026年7月28日公布。",
          "verification_after_reconcile": "partially_verified"
        },
        {
          "ticker": "AXS-E",
          "metric_name": "Catastrophe losses",
          "metric_value": "48",
          "missing_reason": "2026年第二季度財報尚未發布，預計於2026年7月28日公布。",
          "verification_after_reconcile": "partially_verified"
        }
      ]
    }
  },
  {
    "target_name": "F-B",
    "events": [],
    "綜合分析": "在指定日期範圍內無可報告的相關事件。",
    "事件總分": "正向0 / 負向0 / 總分+0",
    "new_sources_found": [],
    "metric_data": [
      {
        "ticker": "F-B",
        "metric_name": "Industrial free cash flow",
        "metric_category": "工業現金流",
        "value": "-1.9B USD (2026 Q1), 5.0B-6.0B USD (2026財年指引)",
        "unit": "USD",
        "period": "2026 Q1 & FY 2026",
        "status": "已取得",
        "confidence": "高",
        "source": "Ford Motor Company Q1 2026 Earnings Report",
        "source_url_or_name": "SEC Filing",
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
        "note": "2026年第一季為負值，但全年指引仍為正向，公司歸因於季節性營運資本變動。",
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
        "metric_period_parsed_date": "2026-03-31",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "partially_verified",
        "metric_consistency_status": "conflict_with_missing_data",
        "metric_consistency_reason": "2026年第二季度財報尚未發布 (預計7月28日)，近期搜尋無明確官方或高可信來源的當季工業自由現金流數值。",
        "metric_consistency_missing_type": "metric_value"
      },
      {
        "ticker": "F-B",
        "metric_name": "Ford Credit delinquencies / credit losses",
        "metric_category": "金融子公司信用風險",
        "value": "0.48",
        "unit": "%/USD",
        "period": "2026-07-09",
        "status": "已取得",
        "confidence": "高",
        "source": "Dealcharts (citing SEC EDGAR filings)",
        "source_url_or_name": "Dealcharts",
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
        "note": "福特信貸FORDR 2026-A資產證券化逾期率於2026年7月9日上升至0.48%。Q1 2026財報中，60天以上逾期率為0.21%。",
        "source_quality_primary": "sec_filing",
        "source_quality": "sec_filing",
        "source_quality_details": [
          "sec_filing",
          "specialized_media"
        ],
        "source_candidate_quality_details": [
          "sec_filing",
          "official_ir",
          "rating_agency"
        ],
        "source_conflict_flag": false,
        "source_conflict_reason": "",
        "metric_period_parsed_date": "2026-07-09",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "date",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "partially_verified",
        "metric_consistency_status": "conflict_with_missing_data",
        "metric_consistency_reason": "福特第二季2026年財報（包含此指標）預計於2026年7月25日發布，故本次搜尋期間尚未取得最新官方數值。",
        "metric_consistency_missing_type": "metric_value"
      },
      {
        "ticker": "F-B",
        "metric_name": "Recall / warranty cost",
        "metric_category": "品質成本",
        "value": "每年超過40億美元 (2023年為48億美元)",
        "unit": "USD",
        "period": "年度趨勢 (截至2023年)",
        "status": "已取得",
        "confidence": "高",
        "source": "TopSpeed",
        "source_url_or_name": "TopSpeed",
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
        "note": "最近的召回事件（7/22 38.7萬輛SUV及7/6 74.1萬輛汽車）將對此成本造成額外壓力，但具體金額尚未量化。",
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
        "metric_period_parsed_date": "2023-12-31",
        "metric_period_parse_status": "year_only",
        "metric_period_type": "year",
        "metric_period_freshness": "stale",
        "metric_integrity_status": "pass",
        "metric_verification_status": "unverified",
        "metric_consistency_status": "conflict_with_missing_data",
        "metric_consistency_reason": "本次搜尋未找到最近14日或Q1 2026的具體召回/保固成本金額。",
        "metric_consistency_missing_type": "metric_value"
      }
    ],
    "missing_data": [
      {
        "ticker": "F-B",
        "priority": "P1",
        "missing_type": "metric_consistency",
        "metric_name": "Recall / warranty cost",
        "reason": "本次搜尋未找到最近14日或Q1 2026的具體召回/保固成本金額。",
        "risk_impact": "品質成本會壓縮現金流與信用評等。",
        "source_candidates": [
          "Ford Investor Relations",
          "SEC 10-Q",
          "SEC 8-K"
        ],
        "acceptance_criteria": "下次需填入 value、period、source；若查無，需說明查詢過哪些來源",
        "missing_type_original": "metric_value",
        "conflict_with_metric_data": true,
        "metric_value_present": "每年超過40億美元 (2023年為48億美元)",
        "metric_source_present": "TopSpeed",
        "metric_verification_after_reconcile": "unverified"
      },
      {
        "ticker": "F-B",
        "priority": "P0",
        "missing_type": "metric_consistency",
        "metric_name": "Industrial free cash flow",
        "reason": "2026年第二季度財報尚未發布 (預計7月28日)，近期搜尋無明確官方或高可信來源的當季工業自由現金流數值。",
        "risk_impact": "工業 FCF 是付息與維持信用評等的重要基礎，缺乏最新數據難以評估。",
        "source_candidates": [
          "Ford Investor Relations",
          "SEC 10-Q",
          "Earnings Supplement"
        ],
        "acceptance_criteria": "下次需填入 value、period、source；若查無，需說明查詢過哪些來源",
        "missing_type_original": "metric_value",
        "conflict_with_metric_data": true,
        "metric_value_present": "-1.9B USD (2026 Q1), 5.0B-6.0B USD (2026財年指引)",
        "metric_source_present": "Ford Motor Company Q1 2026 Earnings Report",
        "metric_verification_after_reconcile": "partially_verified"
      },
      {
        "ticker": "F-B",
        "priority": "P1",
        "missing_type": "metric_consistency",
        "metric_name": "Ford Credit delinquencies / credit losses",
        "reason": "福特第二季2026年財報（包含此指標）預計於2026年7月25日發布，故本次搜尋期間尚未取得最新官方數值。",
        "risk_impact": "福特信貸的逾期率或信用損失準備是評估其金融子公司風險的重要指標，其缺漏影響對景氣下行風險的判斷。",
        "source_candidates": [
          "Ford Credit disclosures",
          "SEC 10-Q",
          "Earnings Supplement"
        ],
        "acceptance_criteria": "下次需填入 value、period、source；若查無，需說明查詢過哪些來源",
        "missing_type_original": "metric_value",
        "conflict_with_metric_data": true,
        "metric_value_present": "0.48",
        "metric_source_present": "Dealcharts (citing SEC EDGAR filings)",
        "metric_verification_after_reconcile": "partially_verified"
      }
    ],
    "metric_integrity_issues": [],
    "metric_merge_source": "stage1_deterministic_merge",
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
      "cutoff_date": "2026-07-10",
      "today": "2026-07-23",
      "kept_recent": 0,
      "kept_background": 0,
      "kept_unknown_date": 0,
      "dropped_old": 0
    },
    "metric_consistency_summary": {
      "conflict_count": 3,
      "conflicts": [
        {
          "ticker": "F-B",
          "metric_name": "Recall / warranty cost",
          "metric_value": "每年超過40億美元 (2023年為48億美元)",
          "missing_reason": "本次搜尋未找到最近14日或Q1 2026的具體召回/保固成本金額。",
          "verification_after_reconcile": "unverified"
        },
        {
          "ticker": "F-B",
          "metric_name": "Industrial free cash flow",
          "metric_value": "-1.9B USD (2026 Q1), 5.0B-6.0B USD (2026財年指引)",
          "missing_reason": "2026年第二季度財報尚未發布 (預計7月28日)，近期搜尋無明確官方或高可信來源的當季工業自由現金流數值。",
          "verification_after_reconcile": "partially_verified"
        },
        {
          "ticker": "F-B",
          "metric_name": "Ford Credit delinquencies / credit losses",
          "metric_value": "0.48",
          "missing_reason": "福特第二季2026年財報（包含此指標）預計於2026年7月25日發布，故本次搜尋期間尚未取得最新官方數值。",
          "verification_after_reconcile": "partially_verified"
        }
      ]
    }
  },
  {
    "target_name": "UZD",
    "events": [],
    "綜合分析": "在指定日期範圍內無可報告的相關事件。",
    "事件總分": "正向0 / 負向0 / 總分+0",
    "new_sources_found": [],
    "metric_data": [
      {
        "ticker": "UZD",
        "metric_name": "Issuer / guarantor status",
        "metric_category": "法律實體",
        "value": "Array Digital Infrastructure, Inc. (前身為 United States Cellular Corporation), 為 Telephone and Data Systems, Inc. (TDS) 旗下 82% 股權的子公司。",
        "unit": "status",
        "period": "截至 2026年7月20日",
        "status": "已取得",
        "confidence": "高",
        "source": "Array Digital Infrastructure Investor Relations",
        "source_url_or_name": "Array Digital Infrastructure Investor Relations",
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
        "note": "UScellular 的無線業務已於2025年8月1日出售給 T-Mobile，公司名稱隨後更改為 Array Digital Infrastructure, Inc.。",
        "source_quality_primary": "official_ir",
        "source_quality": "official_ir",
        "source_quality_details": [
          "official_ir"
        ],
        "source_candidate_quality_details": [
          "sec_filing",
          "official_ir",
          "exchange_notice"
        ],
        "source_conflict_flag": false,
        "source_conflict_reason": "",
        "metric_period_parsed_date": "2026-07-20",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "date",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": ""
      },
      {
        "ticker": "UZD",
        "metric_name": "Asset sale proceeds and use of funds",
        "metric_category": "資產出售",
        "value": "出售所得主要用於派發股息",
        "unit": "USD/status",
        "period": "2025年8月 & 2026年6月",
        "status": "已取得",
        "confidence": "高",
        "source": "Array Digital Infrastructure Press Release / SEC Filing (8-K)",
        "source_url_or_name": "Array Digital Infrastructure, PR Newswire",
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
        "note": "Stage 1/Stage 2 已回填此量化指標。",
        "source_quality_primary": "sec_filing",
        "source_quality": "sec_filing",
        "source_quality_details": [
          "sec_filing",
          "press_release"
        ],
        "source_candidate_quality_details": [
          "sec_filing",
          "official_ir",
          "exchange_notice"
        ],
        "source_conflict_flag": false,
        "source_conflict_reason": "",
        "metric_period_parsed_date": "2025-08-31",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "month_or_month_range",
        "metric_period_freshness": "acceptable_recent",
        "metric_integrity_status": "pass",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": ""
      },
      {
        "ticker": "UZD",
        "metric_name": "Debt assumption / redemption status",
        "metric_category": "債務處理",
        "value": "部分債務由T-Mobile承擔，本債券未贖回",
        "unit": "status",
        "period": "2025年8月",
        "status": "已取得",
        "confidence": "高",
        "source": "Array Digital Infrastructure Press Release / SEC Filing (8-K) / The Motley Fool",
        "source_url_or_name": "Array Digital Infrastructure, PR Newswire, The Motley Fool",
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
        "note": "Stage 1/Stage 2 已回填此量化指標。",
        "source_quality_primary": "sec_filing",
        "source_quality": "sec_filing",
        "source_quality_details": [
          "sec_filing",
          "press_release"
        ],
        "source_candidate_quality_details": [
          "sec_filing",
          "official_ir",
          "exchange_notice"
        ],
        "source_conflict_flag": false,
        "source_conflict_reason": "",
        "metric_period_parsed_date": "2025-08-31",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "month_or_month_range",
        "metric_period_freshness": "acceptable_recent",
        "metric_integrity_status": "pass",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": ""
      }
    ],
    "metric_integrity_issues": [],
    "metric_merge_source": "stage1_deterministic_merge",
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
    "missing_data": [],
    "dropped_old_events": [],
    "event_date_filter_summary": {
      "lookback_days": 14,
      "cutoff_date": "2026-07-10",
      "today": "2026-07-23",
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
    "target_name": "QVCD",
    "events": [],
    "綜合分析": "在指定日期範圍內無可報告的相關事件。",
    "事件總分": "正向0 / 負向0 / 總分+0",
    "new_sources_found": [],
    "metric_data": [
      {
        "ticker": "QVCD",
        "metric_name": "Bankruptcy case status",
        "metric_category": "重整程序",
        "value": "已獲法院批准預先打包重組計劃，預計將擺脫第11章破產程序",
        "unit": "status",
        "period": "2026年7月15日 (法院批准)",
        "status": "已取得",
        "confidence": "高",
        "source": "PR Newswire / SEC Filing (8-K) / Kroll Restructuring Administration LLC",
        "source_url_or_name": "PR Newswire",
        "source_candidates": [
          "Bankruptcy court docket",
          "Company restructuring website",
          "SEC filings",
          "BusinessWire",
          "Reuters"
        ],
        "warning_threshold": "Chapter 11 未解除或回收條件未確認，一律紅燈。",
        "priority": "P0",
        "risk_impact": "直接影響本金回收與交易資格。",
        "note": "QVC集團已於2026年4月16日聲請第11章破產保護。",
        "source_quality_primary": "sec_filing",
        "source_quality": "sec_filing",
        "source_quality_details": [
          "sec_filing",
          "court_docket",
          "press_release"
        ],
        "source_candidate_quality_details": [
          "sec_filing",
          "court_docket",
          "press_release",
          "mainstream_media"
        ],
        "source_conflict_flag": false,
        "source_conflict_reason": "",
        "metric_period_parsed_date": "2026-07-15",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "date",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": ""
      },
      {
        "ticker": "QVCD",
        "metric_name": "Recovery / exchange terms",
        "metric_category": "回收條件",
        "value": "預計票據取消，按計畫分配",
        "unit": "status/%/USD",
        "period": "2026-04-20",
        "status": "已取得",
        "confidence": "高",
        "source": "QVC Inc SEC Filing / Investing.com",
        "source_url_or_name": "Investing.com",
        "source_candidates": [
          "Bankruptcy court docket",
          "Company restructuring website",
          "SEC filings",
          "BusinessWire",
          "Reuters"
        ],
        "warning_threshold": "未知、低回收率、強制交換或展延需紅燈。",
        "priority": "P0",
        "risk_impact": "決定交易所債實際本金回收。",
        "note": "雖然重整計畫已獲批准，但截至目前公開資訊未明確量化QVCD票據的具體回收百分比或金額。原始公告指出，現有票據預計被取消，且不保證全額回收本金。",
        "source_quality_primary": "sec_filing",
        "source_quality": "sec_filing",
        "source_quality_details": [
          "sec_filing"
        ],
        "source_candidate_quality_details": [
          "sec_filing",
          "court_docket",
          "press_release",
          "mainstream_media"
        ],
        "source_conflict_flag": false,
        "source_conflict_reason": "",
        "metric_period_parsed_date": "2026-04-20",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "date",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "partially_verified",
        "metric_consistency_status": "conflict_with_missing_data",
        "metric_consistency_reason": "QVC集團的重組計劃雖已獲法院批准，並已確立債權人回收方案，但針對6.375%優先擔保債券（QVCD）的具體回收率或交換條件（如新債券、現金比例等）並未在本次檢索到的公開消息中詳述。",
        "metric_consistency_missing_type": "metric_value"
      },
      {
        "ticker": "QVCD",
        "metric_name": "Trading status",
        "metric_category": "交易資格",
        "value": "已從NYSE下市，現於OTC Pink Limited Market交易 (代號QVCDQ)",
        "unit": "status",
        "period": "2026年4月17日 (NYSE下市)",
        "status": "已取得",
        "confidence": "高",
        "source": "SEC Filing (8-K) / Investing.com / BusinessWire / OTC Markets",
        "source_url_or_name": "SEC Filing",
        "source_candidates": [
          "Bankruptcy court docket",
          "Company restructuring website",
          "SEC filings",
          "BusinessWire",
          "Reuters"
        ],
        "warning_threshold": "停牌、退市、轉 OTC 或流動性消失需紅燈。",
        "priority": "P0",
        "risk_impact": "影響退出能力與價格透明度。",
        "note": "原NYSE股票代碼為QVCD，下市後於OTC市場以QVCDQ交易。",
        "source_quality_primary": "sec_filing",
        "source_quality": "sec_filing",
        "source_quality_details": [
          "sec_filing",
          "exchange_notice",
          "press_release"
        ],
        "source_candidate_quality_details": [
          "sec_filing",
          "court_docket",
          "press_release",
          "mainstream_media"
        ],
        "source_conflict_flag": false,
        "source_conflict_reason": "",
        "metric_period_parsed_date": "2026-04-17",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "date",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": ""
      }
    ],
    "missing_data": [
      {
        "ticker": "QVCD",
        "priority": "P0",
        "missing_type": "metric_consistency",
        "metric_name": "Recovery / exchange terms",
        "reason": "QVC集團的重組計劃雖已獲法院批准，並已確立債權人回收方案，但針對6.375%優先擔保債券（QVCD）的具體回收率或交換條件（如新債券、現金比例等）並未在本次檢索到的公開消息中詳述。",
        "risk_impact": "缺乏QVCD債券具體回收條款的細節，投資者無法精確評估本金回收金額或新證券價值，存在高度不確定性。",
        "source_candidates": [
          "QVC Group Investor Relations (重組信息專區)",
          "Bankruptcy court docket (Plan of Reorganization details)",
          "SEC Filings (相關8-K附件)"
        ],
        "acceptance_criteria": "下次需獲取重組計劃中針對QVCD債權類別的確切條款，包括回收類型、比例及時間表。",
        "missing_type_original": "metric_value",
        "conflict_with_metric_data": true,
        "metric_value_present": "預計票據取消，按計畫分配",
        "metric_source_present": "QVC Inc SEC Filing / Investing.com",
        "metric_verification_after_reconcile": "partially_verified"
      }
    ],
    "metric_integrity_issues": [],
    "metric_merge_source": "stage1_deterministic_merge",
    "risk_profile": {
      "profile_found": true,
      "risk_profile_version": "1.0",
      "issuer": "QVC Inc.",
      "security_type": "Exchange-traded senior note",
      "sector": "Retail / Media Commerce",
      "core_risk": "Chapter 11、債權類別、交換條件、回收率與交易資格。",
      "required_metric_count": 3,
      "hard_warning_keywords": [
        "Chapter 11",
        "plan confirmation",
        "recovery rate",
        "exchange offer",
        "trading suspension",
        "delisting"
      ]
    },
    "dropped_old_events": [],
    "event_date_filter_summary": {
      "lookback_days": 14,
      "cutoff_date": "2026-07-10",
      "today": "2026-07-23",
      "kept_recent": 0,
      "kept_background": 0,
      "kept_unknown_date": 0,
      "dropped_old": 0
    },
    "metric_consistency_summary": {
      "conflict_count": 1,
      "conflicts": [
        {
          "ticker": "QVCD",
          "metric_name": "Recovery / exchange terms",
          "metric_value": "預計票據取消，按計畫分配",
          "missing_reason": "QVC集團的重組計劃雖已獲法院批准，並已確立債權人回收方案，但針對6.375%優先擔保債券（QVCD）的具體回收率或交換條件（如新債券、現金比例等）並未在本次檢索到的公開消息中詳述。",
          "verification_after_reconcile": "partially_verified"
        }
      ]
    }
  }
]
```

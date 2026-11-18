# USPreferredStockDayInfo 每日情報報告

- 生成時間（台灣）：2026-11-18 08:17:59
- 對應 PDF：Stock_News_Report_20261118_081759.pdf
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
- 綜合分析：Stage 2 AI 合併未完成；已由程式保留高可信 Stage 1 近期事件，事件權重偏正面（+3）。
- 事件 1：2026-11-17｜Lumen 股價上漲與內部人買入，分析師評級調整｜recent_event
  - 影響：正向｜嚴重性：3｜信心度：高
  - 摘要：Lumen 股價上漲7%，CEO與董事內部買入，多家分析師調整評級與目標價。
  - 來源：MarketBeat、SeekingAlpha
  - 日期過濾：kept_recent｜來源品質：secondary_site｜驗證：unverified
- 事件 2：2026-11-10｜Lumen 發布網路威脅報告更新｜recent_event
  - 影響：中性｜嚴重性：1｜信心度：高
  - 摘要：Lumen 發布網路安全威脅報告更新，指出威脅攻擊加速且更具韌性。
  - 來源：Business Wire、Lumen Investor Relations
  - 日期過濾：kept_recent｜來源品質：official_ir｜驗證：verified

### 2. BHFAL

- 事件總分：正向0 / 負向9 / 總分-9
- 綜合分析：Stage 2 AI 合併未完成；已由程式保留高可信 Stage 1 近期事件，事件權重偏負面（-9）。
- 事件 1：2026-11-05｜Fitch將Brighthouse Financial評級列入負面觀察 (Rating Watch Negative)｜recent_event
  - 影響：負向｜嚴重性：5｜信心度：高
  - 摘要：Fitch將Brighthouse Financial及其次順位債務評級列入負面觀察，原因為Aquarian併購案相關的公司概況、投資風險與財務彈性不確定性。
  - 來源：Fitch Ratings
  - 日期過濾：kept_recent｜來源品質：rating_agency｜驗證：verified
- 事件 2：2026-11-05｜Brighthouse Financial公布2026年第三季財報，核心獲利下滑、併購案延遲｜recent_event
  - 影響：負向｜嚴重性：4｜信心度：高
  - 摘要：核心獲利年減18%，RBC資本比率因特殊股息而維持，法定資本下降，Aquarian併購案因監管批准延遲。
  - 來源：Business Wire、SEC Filing、Finsee、Morningstar、MarketBeat、GuruFocus、Stock Titan
  - 日期過濾：kept_recent｜來源品質：sec_filing｜驗證：verified

### 3. OPI

- 事件總分：正向5 / 負向0 / 總分+5
- 綜合分析：Stage 2 AI 合併未完成；已由程式保留高可信 Stage 1 近期事件，事件權重偏正面（+5）。
- 事件 1：2026-11-09｜OPI 公布 2026 年第三季度財報，FFO 成長且債務重組取得進展｜recent_event
  - 影響：正向｜嚴重性：5｜信心度：高
  - 摘要：OPI 財報顯示正規化 FFO 成長，同物業現金基礎 NOI 增加，成功將大部分債務再融資至 2029 年。
  - 來源：OPI Investor Relations、SEC Filing、BusinessWire、The Motley Fool、MarketBeat、Finsee
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
- Free cash flow｜狀態：已取得｜驗證：partially_verified｜來源品質：official_ir｜期間新鮮度：fresh｜門檻：FCF 轉負或展望下修需警戒。
- Debt maturity and exchange offer terms｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：distressed exchange、順位弱化或擔保改變需警戒。
- Credit rating / outlook｜狀態：已取得｜驗證：verified｜來源品質：rating_agency｜期間新鮮度：fresh｜門檻：downgrade、negative outlook 或 selective default 評論需警戒。
- 資料缺口：2 項，關鍵資料缺漏時不可判定為綠燈。

### BHFAL 量化監控
- RBC ratio｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：低於 400% 黃燈；低於 350% 橙燈/紅燈；單季大幅下滑需警戒。
- Statutory capital and surplus｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：連續下降或重大減損需警戒。
- Holding company cash and liquid assets｜狀態：已取得｜驗證：partially_verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：低於未來 12 個月利息與固定支出覆蓋需求需警戒。
- Financial leverage｜狀態：已取得｜驗證：verified｜來源品質：rating_agency｜期間新鮮度：fresh｜門檻：槓桿升高或評等機構負面評論需警戒。
- Credit rating / outlook｜狀態：已取得｜驗證：verified｜來源品質：rating_agency｜期間新鮮度：acceptable_recent｜門檻：negative outlook、downgrade 或 watch negative 需警戒。
- BHFAL interest payment status｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：defer、suspend、delay、non-payment 立即紅燈。
- Aquarian merger / change-of-control treatment｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：未明確說明 BHFAL 存續、掛牌、贖回或付息條款時列資料不足。
- 資料缺口：1 項，關鍵資料缺漏時不可判定為綠燈。

### OPI 量化監控
- Occupancy rate｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：連續下降或低於同業顯著水準需警戒。
- AFFO / FFO｜狀態：資料不足｜驗證：data_missing｜來源品質：unknown｜期間新鮮度：unknown_period｜門檻：AFFO/FFO 大幅下滑或為負需警戒。
- Debt maturity schedule｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：12-24 個月內大量到期且流動性不足需紅燈。
- Liquidity / cash availability｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：流動性不足或 covenant 壓力需警戒。
- Normalized FFO｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：AFFO/FFO 大幅下滑或為負需警戒。
- 資料缺口：1 項，關鍵資料缺漏時不可判定為綠燈。

### AXS-E 量化監控
- Combined ratio｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：高於 100% 或明顯惡化需警戒。
- Catastrophe losses｜狀態：已取得｜驗證：partially_verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：重大巨災損失超預期需警戒。
- Preferred dividend status｜狀態：已取得｜驗證：partially_verified｜來源品質：official_ir｜期間新鮮度：future_or_invalid_period｜門檻：defer、suspend、delay 立即紅燈。
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

- CTGG：recent=2，background=0，unknown_date=0，dropped_old=0
- BHFAL：recent=2，background=0，unknown_date=0，dropped_old=0
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
        "date": "2026-11-17",
        "title": "Lumen 股價上漲與內部人買入，分析師評級調整",
        "impact_direction": "正向",
        "impact_severity": 3,
        "confidence": "高",
        "summary_30": "Lumen 股價上漲7%，CEO與董事內部買入，多家分析師調整評級與目標價。",
        "links": [
          "MarketBeat",
          "SeekingAlpha"
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
        "date": "2026-11-10",
        "title": "Lumen 發布網路威脅報告更新",
        "impact_direction": "中性",
        "impact_severity": 1,
        "confidence": "高",
        "summary_30": "Lumen 發布網路安全威脅報告更新，指出威脅攻擊加速且更具韌性。",
        "links": [
          "Business Wire",
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
    "綜合分析": "Stage 2 AI 合併未完成；已由程式保留高可信 Stage 1 近期事件，事件權重偏正面（+3）。",
    "事件總分": "正向3 / 負向0 / 總分+3",
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
        "value": "Q3 2026: $(76)M；2026全年展望: $1.9B - $2.1B (排除特殊項目及資產剝離相關現金稅款)",
        "unit": "USD",
        "period": "2026Q3 及 2026全年展望",
        "status": "已取得",
        "confidence": "高",
        "source": "Lumen Technologies Q3 2026 Earnings Release",
        "source_url_or_name": "Business Wire, Lumen Investor Relations, Nasdaq, Stock Titan, TradingView, SeekingAlpha",
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
        "note": "Stage 1/Stage 2 已回填此量化指標。",
        "semantic_match_status": "完美匹配",
        "issuer_scope": "Lumen Technologies",
        "metric_value_type": "絕對值",
        "source_quality_primary": "official_ir",
        "source_quality": "official_ir",
        "source_quality_details": [
          "official_ir",
          "exchange_notice",
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
        "metric_period_parsed_date": "2026-09-30",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "partially_verified",
        "metric_consistency_status": "cross_run_conflict",
        "metric_consistency_reason": "同 period / definition 前值=-76000000，本次=Q3 2026: $(76)M；2026全年展望: $1.9B - $2.1B (排除特殊項目及資產剝離相關現金稅款)；區間不重疊。",
        "cross_run_consistency_status": "value_changed_same_definition",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": -76000000,
        "cross_run_previous_period": "2026Q3",
        "cross_run_previous_report_date": "20261106",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 前值=-76000000，本次=Q3 2026: $(76)M；2026全年展望: $1.9B - $2.1B (排除特殊項目及資產剝離相關現金稅款)；區間不重疊。"
      },
      {
        "ticker": "CTGG",
        "metric_name": "Debt maturity and exchange offer terms",
        "metric_category": "債務結構",
        "value": "CTGG (Qwest Corp 6.500% Senior Notes due 2051) 為 Qwest Corporation 發行的高級無擔保債務，由 Lumen Technologies 完全擔保。Lumen 於 2026 年 9 月 30 日總債務為 133 億美元。公司已在 2026 年 6 月完成 Qwest 部分舊債的交換要約，將其替換為期限相近且條款相同的新債。Lumen 在 2026 年第三季度亦成功再融資循環信用額度並延長債務到期日。",
        "unit": "status/date/USD",
        "period": "截至 2026年9月30日 (最新總債務)；2026年6月 (Qwest 債務交換完成)；2026年Q3 (再融資與債務延長)",
        "status": "已取得",
        "confidence": "高",
        "source": "Lumen Technologies Q3 2026 Earnings Release, SEC 10-Q (to be filed), Lumen Investor Relations",
        "source_url_or_name": "Business Wire, Investing.com",
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
        "note": "Stage 1/Stage 2 已回填此量化指標。",
        "semantic_match_status": "部份匹配",
        "issuer_scope": "Lumen Technologies / Qwest Corporation",
        "metric_value_type": "描述性",
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
        "metric_period_parsed_date": "2026-09-30",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "date",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "definition_changed",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "未來五年內約$1.2B債務到期；無重大到期直至2031年；年度利息支出減少約$500M。",
        "cross_run_previous_period": "截至2026年9月30日 (Q3 2026 財報及法說會)",
        "cross_run_previous_report_date": "20261117",
        "cross_run_previous_definition_scope": "官方公告 (Official Announcement)",
        "cross_run_previous_calculation_basis": "公司財報與法說會說明 (Company financial reports and earnings call)",
        "cross_run_consistency_reason": "同 period 有前值，但 definition_scope / calculation_basis 不同，不互相覆寫。"
      },
      {
        "ticker": "CTGG",
        "metric_name": "Credit rating / outlook",
        "metric_category": "信用評等",
        "value": "Moody's: Lumen Technologies 公司家族評級 (CFR) 為 B2，Qwest Corporation 高級無擔保債務評級為 Caa1；展望穩定 (2026年2月)。S&P: Lumen Technologies 發行人信用評級 (ICR) 為 B-；展望正向 (2026年3月)。Fitch: Lumen Technologies 長期發行人違約評級 (IDR) 為 B (2026年2月)。Lumen 財務長在 2026 年 9 月表示預計未來一年信評將進一步改善。",
        "unit": "rating",
        "period": "2026年2月/3月 (最新評級行動)；2026年9月 (CFO評論)",
        "status": "已取得",
        "confidence": "高",
        "source": "Moody's Ratings, S&P Global Ratings, Fitch Ratings",
        "source_url_or_name": "Business Wire, Bloomberg",
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
        "note": "Stage 1/Stage 2 已回填此量化指標。",
        "semantic_match_status": "完美匹配",
        "issuer_scope": "Qwest Corporation / Lumen Technologies issuer-guarantor chain",
        "metric_value_type": "評級",
        "source_quality_primary": "rating_agency",
        "source_quality": "rating_agency",
        "source_quality_details": [
          "rating_agency",
          "press_release",
          "mainstream_media"
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
        "metric_period_type": "month_or_month_range",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "not_comparable_multi_subject_rating",
        "definition_scope": "Qwest Corporation / Lumen Technologies issuer-chain credit ratings; agency and subject scopes kept separate",
        "calculation_basis": "rating-agency subject-specific issuer / corporate-family / instrument ratings; no scalar cross-agency aggregation",
        "measurement_form": "multi_subject_rating",
        "rating_subjects": [
          {
            "rating_subject": "Lumen Technologies / Qwest Corporation",
            "rating_subject_type": "corporate_family_rating",
            "rating_instrument_scope": "corporate family",
            "rating_agency": "Moody's",
            "rating_value": "B2",
            "rating_outlook": "",
            "recovery_rating": "",
            "raw_subject_text": "Moody's: Lumen Technologies 公司家族評級 (CFR) 為 B2，Qwest Corporation 高級無擔保債務評級為 Caa1",
            "ctgg_rating_parser_patch_version": "1.3.8.3.6",
            "subject_evidence_origin": "value",
            "ctgg_rating_evidence_patch_version": "1.3.8.3.6"
          },
          {
            "rating_subject": "Lumen Technologies",
            "rating_subject_type": "issuer_credit_rating",
            "rating_instrument_scope": "issuer",
            "rating_agency": "S&P",
            "rating_value": "B-",
            "rating_outlook": "Stable",
            "recovery_rating": "",
            "raw_subject_text": "展望穩定 (2026年2月)。S&P: Lumen Technologies 發行人信用評級 (ICR) 為 B-",
            "ctgg_rating_parser_patch_version": "1.3.8.3.6",
            "subject_evidence_origin": "value",
            "ctgg_rating_evidence_patch_version": "1.3.8.3.6"
          },
          {
            "rating_subject": "Lumen Technologies",
            "rating_subject_type": "issuer_default_rating",
            "rating_instrument_scope": "issuer / long-term IDR",
            "rating_agency": "Fitch",
            "rating_value": "B",
            "rating_outlook": "",
            "recovery_rating": "",
            "raw_subject_text": "展望正向 (2026年3月)。Fitch: Lumen Technologies 長期發行人違約評級 (IDR) 為 B (2026年2月)。Lumen 財務長在 2026 年 9 月表示預計未來一年信評將進一步改善。",
            "ctgg_rating_parser_patch_version": "1.3.8.3.6",
            "subject_evidence_origin": "value",
            "ctgg_rating_evidence_patch_version": "1.3.8.3.6"
          },
          {
            "rating_subject": "Qwest Corporation / Lumen Technologies issuer chain",
            "rating_subject_type": "instrument_rating",
            "rating_instrument_scope": "senior unsecured debt",
            "rating_agency": "Moody's",
            "rating_value": "Caa1",
            "rating_outlook": "",
            "recovery_rating": "",
            "raw_subject_text": "高級無擔保債務評級為 Caa1",
            "subject_evidence_origin": "value",
            "ctgg_rating_parser_patch_version": "1.3.8.3.6",
            "ctgg_rating_evidence_patch_version": "1.3.8.3.6"
          },
          {
            "rating_subject": "Qwest Corporation / Lumen Technologies issuer chain",
            "rating_subject_type": "corporate_family_rating",
            "rating_instrument_scope": "corporate family",
            "rating_agency": "Moody's",
            "rating_value": "B2",
            "rating_outlook": "",
            "recovery_rating": "",
            "raw_subject_text": "CFR) 為 B2",
            "subject_evidence_origin": "value",
            "ctgg_rating_parser_patch_version": "1.3.8.3.6",
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
            "raw_subject_text": "IDR) 為 B",
            "subject_evidence_origin": "value",
            "ctgg_rating_parser_patch_version": "1.3.8.3.6",
            "ctgg_rating_evidence_patch_version": "1.3.8.3.6"
          }
        ],
        "rating_subject_scope_status": "allowed_ctgg_qwest_lumen_chain",
        "ctgg_rating_parser_patch_version": "1.3.8.3.6",
        "ctgg_rating_evidence_patch_version": "1.3.8.3.6",
        "ctgg_rating_direct_scope_patch_version": "1.3.8.3.6",
        "ctgg_rating_direct_scope_status": "direct_ctgg_rating_structured",
        "rating_subjects_nonempty_status": "pass",
        "cross_run_consistency_reason": "Issuer/CFR/instrument ratings from multiple agencies are subject-scoped and are not reduced to one scalar trend.",
        "ctgg_rating_official_definition_patch_version": "1.3.8.3.7",
        "ctgg_rating_official_definition_guard_status": "newer_subject_locked_official_preserved"
      }
    ],
    "missing_data": [
      {
        "ticker": "CTGG",
        "priority": "P0",
        "missing_type": "metric_value",
        "metric_name": "Debt maturity schedule (詳細時間表)",
        "reason": "在指定日期範圍內未找到 Lumen Technologies 或 Qwest Corporation 最新且詳細的債務到期時間表，儘管公司聲明已延長債務到期日。",
        "risk_impact": "缺乏詳細的債務到期時間表，限制了對 Lumen/Qwest 未來幾年再融資風險的精確評估，可能影響長債的償付預期。",
        "source_candidates": [
          "SEC 10-Q",
          "SEC 10-K",
          "Lumen Investor Relations"
        ],
        "acceptance_criteria": "下次需填入 value、period、source；若查無，需說明查詢過哪些來源"
      },
      {
        "ticker": "CTGG",
        "priority": "P0",
        "missing_type": "metric_cross_run_consistency",
        "metric_name": "Free cash flow",
        "reason": "同 period / definition 前值=-76000000，本次=Q3 2026: $(76)M；2026全年展望: $1.9B - $2.1B (排除特殊項目及資產剝離相關現金稅款)；區間不重疊。",
        "risk_impact": "自由現金流不足會影響長債償付能力。",
        "previous_value": -76000000,
        "current_value": "Q3 2026: $(76)M；2026全年展望: $1.9B - $2.1B (排除特殊項目及資產剝離相關現金稅款)",
        "period": "2026Q3 及 2026全年展望",
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
      "cutoff_date": "2026-11-05",
      "today": "2026-11-18",
      "kept_recent": 2,
      "kept_background": 0,
      "kept_unknown_date": 0,
      "dropped_old": 0
    },
    "metric_consistency_summary": {
      "conflict_count": 1,
      "conflicts": [
        {
          "ticker": "CTGG",
          "metric_name": "Free cash flow",
          "metric_value": "Q3 2026: $(76)M；2026全年展望: $1.9B - $2.1B (排除特殊項目及資產剝離相關現金稅款)",
          "missing_reason": "同 period / definition 前值=-76000000，本次=Q3 2026: $(76)M；2026全年展望: $1.9B - $2.1B (排除特殊項目及資產剝離相關現金稅款)；區間不重疊。",
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
    "ctgg_rating_official_definition_patch_version": "1.3.8.3.7",
    "ctgg_rating_official_definition_guard_status": "newer_subject_locked_official_preserved"
  },
  {
    "target_name": "BHFAL",
    "events": [
      {
        "date": "2026-11-05",
        "title": "Fitch將Brighthouse Financial評級列入負面觀察 (Rating Watch Negative)",
        "impact_direction": "負向",
        "impact_severity": 5,
        "confidence": "高",
        "summary_30": "Fitch將Brighthouse Financial及其次順位債務評級列入負面觀察，原因為Aquarian併購案相關的公司概況、投資風險與財務彈性不確定性。",
        "links": [
          "Fitch Ratings"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "rating_agency",
        "event_source_quality_details": [
          "rating_agency"
        ],
        "event_verification_status": "verified",
        "event_days_old": 13,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      },
      {
        "date": "2026-11-05",
        "title": "Brighthouse Financial公布2026年第三季財報，核心獲利下滑、併購案延遲",
        "impact_direction": "負向",
        "impact_severity": 4,
        "confidence": "高",
        "summary_30": "核心獲利年減18%，RBC資本比率因特殊股息而維持，法定資本下降，Aquarian併購案因監管批准延遲。",
        "links": [
          "Business Wire",
          "SEC Filing",
          "Finsee",
          "Morningstar",
          "MarketBeat",
          "GuruFocus",
          "Stock Titan"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "sec_filing",
        "event_source_quality_details": [
          "sec_filing",
          "press_release",
          "secondary_site"
        ],
        "event_verification_status": "verified",
        "event_days_old": 13,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      }
    ],
    "綜合分析": "Stage 2 AI 合併未完成；已由程式保留高可信 Stage 1 近期事件，事件權重偏負面（-9）。",
    "事件總分": "正向0 / 負向9 / 總分-9",
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
        "value": "415%-435%",
        "unit": "%",
        "period": "2026Q3",
        "status": "已取得",
        "confidence": "高",
        "source": "Brighthouse Financial Q3 2026 Earnings Release / SEC 8-K",
        "source_url_or_name": "Business Wire / SEC Filing",
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
        "note": "估計合併RBC比率（截至2026年9月30日）。RBC中位數從Q2的440%下降至425%，並受惠於Brighthouse Reinsurance Company of Delaware支付的6億美元特別股息。",
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
        "metric_period_parsed_date": "2026-09-30",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "verified",
        "definition_scope": "Brighthouse insurance subsidiaries (combined)",
        "calculation_basis": "NAIC combined risk-based capital ratio",
        "measurement_form": "range",
        "source_period_alignment_status": "not_applicable",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "consistent_same_definition",
        "cross_run_previous_value": "415%-435%",
        "cross_run_previous_period": "2026Q3",
        "cross_run_previous_report_date": "20261111",
        "cross_run_previous_definition_scope": "Brighthouse insurance subsidiaries (combined)",
        "cross_run_previous_calculation_basis": "NAIC combined risk-based capital ratio",
        "cross_run_consistency_reason": "同 period / definition 與前一可信值一致。"
      },
      {
        "ticker": "BHFAL",
        "metric_name": "Statutory capital and surplus",
        "metric_category": "法定資本",
        "value": "4.8 Billion",
        "unit": "USD",
        "period": "2026Q3",
        "status": "已取得",
        "confidence": "高",
        "source": "Brighthouse Financial Q3 2026 Earnings Release / SEC 8-K",
        "source_url_or_name": "Business Wire / SEC Filing",
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
        "note": "合併法定調整後資本總額（截至2026年9月30日）。較去年同期5.4億美元減少。",
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
        "metric_period_parsed_date": "2026-09-30",
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
        "cross_run_previous_value": "4.8 billion",
        "cross_run_previous_period": "2026Q3",
        "cross_run_previous_report_date": "20261111",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 數值表達不同，但目前值落在前一可信區間內。"
      },
      {
        "ticker": "BHFAL",
        "metric_name": "Holding company cash and liquid assets",
        "metric_category": "控股公司流動性",
        "value": "1.0 Billion",
        "unit": "USD",
        "period": "2026Q3",
        "status": "已取得",
        "confidence": "高",
        "source": "Brighthouse Financial Q3 2026 Earnings Release / SEC 8-K",
        "source_url_or_name": "Business Wire / SEC Filing",
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
        "note": "截至2026年9月30日。高於前兩季的9億美元，足以支付3800萬美元的季度債務利息和2600萬美元的優先股股息。",
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
        "metric_period_parsed_date": "2026-09-30",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "partially_verified",
        "definition_scope": "Brighthouse holding company group",
        "calculation_basis": "holding company liquid assets",
        "measurement_form": "point",
        "source_period_alignment_status": "not_applicable",
        "metric_consistency_status": "cross_run_conflict",
        "metric_consistency_reason": "同 period / definition 前值=1.0，本次=1.0 Billion；區間不重疊。",
        "cross_run_consistency_status": "value_changed_same_definition",
        "cross_run_previous_value": "1.0",
        "cross_run_previous_period": "2026Q3",
        "cross_run_previous_report_date": "20261106",
        "cross_run_previous_definition_scope": "Brighthouse holding company group",
        "cross_run_previous_calculation_basis": "holding company liquid assets",
        "cross_run_consistency_reason": "同 period / definition 前值=1.0，本次=1.0 Billion；區間不重疊。"
      },
      {
        "ticker": "BHFAL",
        "metric_name": "Financial leverage",
        "metric_category": "槓桿",
        "value": "23%",
        "unit": "%",
        "period": "2026H1",
        "status": "已取得",
        "confidence": "高",
        "source": "Fitch Ratings",
        "source_url_or_name": "Fitch Ratings",
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
        "note": "此數值為2025年底及2026年上半年資料，Q3 2026財報未提供最新具體數值，但Fitch因併購案潛在影響將評級列入負面觀察。",
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
        "metric_period_parsed_date": "2026-11-18",
        "metric_period_parse_status": "year_only",
        "metric_period_type": "year",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "no_prior_same_period",
        "definition_scope": "",
        "calculation_basis": ""
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
        "rejected_candidate_value": "BB (Rating Watch On)",
        "rejected_candidate_source": "Fitch Ratings",
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
        "cross_run_previous_report_date": "20261117",
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
        "period": "2026Q3",
        "status": "已取得",
        "confidence": "高",
        "source": "Brighthouse Financial Q3 2026 Earnings Release / SEC 8-K",
        "source_url_or_name": "Business Wire / SEC Filing",
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
        "note": "Q3財報顯示控股公司流動性達10億美元，足以支付季度債務利息3800萬美元。",
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
        "cross_run_previous_value": "正常支付",
        "cross_run_previous_period": "2026Q3",
        "cross_run_previous_report_date": "20261107",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 有前值，但數值型態無法安全比較。"
      },
      {
        "ticker": "BHFAL",
        "metric_name": "Aquarian merger / change-of-control treatment",
        "metric_category": "交易條款",
        "value": "Delayed; extension discussions ongoing",
        "unit": "status",
        "period": "2026-11-05",
        "status": "已取得",
        "confidence": "高",
        "source": "Brighthouse Financial Q3 2026 Earnings Release / SEC 8-K / 10-Q",
        "source_url_or_name": "Business Wire / SEC Filing",
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
        "note": "原定2026年12月6日的截止日期已過，需待德拉瓦州、紐約州和麻薩諸塞州保險監管機構批准。原併購協議（2025年11月6日）指出次順位債務將繼續作為Brighthouse Financial的義務。",
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
        "metric_period_parsed_date": "2026-11-05",
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
        "cross_run_previous_value": "延遲",
        "cross_run_previous_period": "2026-11-05",
        "cross_run_previous_report_date": "20261106",
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
    "missing_data": [
      {
        "ticker": "BHFAL",
        "priority": "P0",
        "missing_type": "metric_cross_run_consistency",
        "metric_name": "Holding company cash and liquid assets",
        "reason": "同 period / definition 前值=1.0，本次=1.0 Billion；區間不重疊。",
        "risk_impact": "控股公司流動性不足可能影響 BHFAL 利息支付。",
        "previous_value": "1.0",
        "current_value": "1.0 Billion",
        "period": "2026Q3",
        "definition_scope": "Brighthouse holding company group",
        "calculation_basis": "holding company liquid assets",
        "acceptance_criteria": "以同一官方定義重新查核；若為不同口徑，改填不同 definition_scope / calculation_basis，不得覆寫。"
      }
    ],
    "dropped_old_events": [],
    "event_date_filter_summary": {
      "lookback_days": 14,
      "cutoff_date": "2026-11-05",
      "today": "2026-11-18",
      "kept_recent": 2,
      "kept_background": 0,
      "kept_unknown_date": 0,
      "dropped_old": 0
    },
    "metric_consistency_summary": {
      "conflict_count": 1,
      "conflicts": [
        {
          "ticker": "BHFAL",
          "metric_name": "Holding company cash and liquid assets",
          "metric_value": "1.0 Billion",
          "missing_reason": "同 period / definition 前值=1.0，本次=1.0 Billion；區間不重疊。",
          "verification_after_reconcile": "partially_verified",
          "cross_run_consistency_status": "value_changed_same_definition",
          "definition_scope": "Brighthouse holding company group",
          "calculation_basis": "holding company liquid assets"
        }
      ]
    },
    "market_quote": {
      "ticker": "BHFAL",
      "security_name_expected": "Brighthouse Financial 6.25% Junior Subordinated Debentures due 2058",
      "exchange_expected": "NASDAQ",
      "latest_price": 14.53,
      "price_as_of": "2026-11-17",
      "open": 14.529999732971191,
      "high": 14.649999618530273,
      "low": 14.500100135803223,
      "volume": 20925,
      "bid": null,
      "ask": null,
      "annual_interest": 1.5625,
      "current_yield": 10.7536,
      "quote_source": "Yahoo Finance chart (query1.finance.yahoo.com)",
      "source_host": "query1.finance.yahoo.com",
      "quote_status": "ok",
      "freshness_status": "fresh",
      "security_identity_status": "matched_symbol",
      "source_timestamp": 1794925800,
      "market_quote_patch_version": "1.3.7",
      "returned_symbol": "BHFAL",
      "currency": "USD",
      "exchange_name": "NMS",
      "instrument_type": "EQUITY",
      "regular_market_price_meta": 14.53,
      "regular_market_time_meta": 1794949200,
      "reference_session_date": "2026-11-17",
      "weekday_gap": 0,
      "http_status": 200,
      "request_url": "https://query1.finance.yahoo.com/v8/finance/chart/BHFAL",
      "request_attempt": 1,
      "attempts": [
        {
          "source_host": "query1.finance.yahoo.com",
          "quote_status": "ok",
          "freshness_status": "fresh",
          "price_as_of": "2026-11-17",
          "latest_price": 14.53,
          "error": null
        },
        {
          "source_host": "query2.finance.yahoo.com",
          "quote_status": "ok",
          "freshness_status": "fresh",
          "price_as_of": "2026-11-17",
          "latest_price": 14.53,
          "error": null
        }
      ],
      "source_validation": "cross_checked",
      "source_crosscheck_price": 14.53,
      "source_crosscheck_host": "query2.finance.yahoo.com",
      "source_conflict_pct": 0.0
    }
  },
  {
    "target_name": "OPI",
    "events": [
      {
        "date": "2026-11-09",
        "title": "OPI 公布 2026 年第三季度財報，FFO 成長且債務重組取得進展",
        "impact_direction": "正向",
        "impact_severity": 5,
        "confidence": "高",
        "summary_30": "OPI 財報顯示正規化 FFO 成長，同物業現金基礎 NOI 增加，成功將大部分債務再融資至 2029 年。",
        "links": [
          "OPI Investor Relations",
          "SEC Filing",
          "BusinessWire",
          "The Motley Fool",
          "MarketBeat",
          "Finsee"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "sec_filing",
        "event_source_quality_details": [
          "sec_filing",
          "official_ir",
          "press_release",
          "secondary_site"
        ],
        "event_verification_status": "verified",
        "event_days_old": 9,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      }
    ],
    "綜合分析": "Stage 2 AI 合併未完成；已由程式保留高可信 Stage 1 近期事件，事件權重偏正面（+5）。",
    "事件總分": "正向5 / 負向0 / 總分+5",
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
        "value": "80.7%",
        "unit": "%",
        "period": "2026Q3 (截至 2026-09-30)",
        "status": "已取得",
        "confidence": "高",
        "source": "SEC Form 10-Q",
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
        "note": "此為所有物業的出租率。同期可比物業出租率為 88.8%。",
        "definition_scope": "所有物業",
        "measurement_form": "報告期末",
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
        "metric_period_parsed_date": "2026-09-30",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "date",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "no_prior_same_period",
        "calculation_basis": ""
      },
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
        "cross_run_consistency_status": "current_missing"
      },
      {
        "ticker": "OPI",
        "metric_name": "Debt maturity schedule",
        "metric_category": "債務到期牆",
        "value": "2027 年 2 月 1 日 30 百萬美元；無重大債務到期至 2029 年",
        "unit": "USD/date",
        "period": "截至 2026-09-30 及近期事件",
        "status": "已取得",
        "confidence": "高",
        "source": "SEC Form 10-Q, OPI Q3 2026 Earnings Call Transcript",
        "source_url_or_name": "SEC Filing, The Motley Fool",
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
        "note": "公司已透過發行 4.25 億美元高級擔保票據，成功償還 2027 年到期的信貸額度與定期貸款，將大部分債務到期時間推遲至 2029 年。下一筆主要本金償付為 2027 年 2 月 1 日的 30 百萬美元。",
        "definition_scope": "公司層面",
        "measurement_form": "特定日期應付金額",
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
        "metric_period_parsed_date": "2026-09-30",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "date",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "definition_changed",
        "calculation_basis": "",
        "cross_run_previous_value": "已於2026年9月透過發行4.25億美元新票據償還2027年1月到期之信貸額度與定期貸款。下次重大債務到期為2028年(約1.235億美元抵押貸款)，隨後是2029年3月(3億美元高級擔保票據)及2029年12月(3.85億美元高級擔保票據)。",
        "cross_run_previous_period": "更新至2026年9月",
        "cross_run_previous_report_date": "20261104",
        "cross_run_previous_definition_scope": "Consolidated Debt",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period 有前值，但 definition_scope / calculation_basis 不同，不互相覆寫。"
      },
      {
        "ticker": "OPI",
        "metric_name": "Liquidity / cash availability",
        "metric_category": "流動性",
        "value": "61 百萬",
        "unit": "USD",
        "period": "2026Q3 (截至 2026-09-30)",
        "status": "已取得",
        "confidence": "高",
        "source": "SEC Form 10-Q, OPI Q3 2026 Earnings Call Transcript",
        "source_url_or_name": "SEC Filing, The Motley Fool",
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
        "note": "截至 2026 年 9 月 30 日，擁有 6100 萬美元非受限現金和 2500 萬美元受限現金。",
        "definition_scope": "公司層面",
        "measurement_form": "報告期末金額",
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
        "metric_period_parsed_date": "2026-09-30",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "date",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "no_prior_same_period",
        "calculation_basis": ""
      },
      {
        "ticker": "OPI",
        "metric_name": "Normalized FFO",
        "metric_category": "現金流",
        "value": "20.5 百萬",
        "unit": "USD",
        "period": "2026Q3 (截至 2026-09-30)",
        "status": "已取得",
        "confidence": "高",
        "source": "SEC Form 10-Q",
        "source_url_or_name": "SEC Filing",
        "warning_threshold": "AFFO/FFO 大幅下滑或為負需警戒。",
        "priority": "P0",
        "risk_impact": "REIT 配息與債務服務能力核心指標。",
        "note": "每股正規化 FFO 為 0.93 美元。",
        "accounting_entity_period": "Successor (Q3 2026)",
        "measurement_form": "季度總額",
        "definition_scope": "公司層面",
        "unit_scale": "百萬美元",
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
        "metric_period_parsed_date": "2026-09-30",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "date",
        "metric_period_freshness": "fresh",
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
        "acceptance_criteria": "下次報告 metric_data 中 OPI / AFFO / FFO 應填入 value、period、source；若查無官方資料，需明確標示查詢來源與查無原因。"
      }
    ],
    "dropped_old_events": [],
    "event_date_filter_summary": {
      "lookback_days": 14,
      "cutoff_date": "2026-11-05",
      "today": "2026-11-18",
      "kept_recent": 1,
      "kept_background": 0,
      "kept_unknown_date": 0,
      "dropped_old": 0
    },
    "metric_consistency_summary": {
      "conflict_count": 0,
      "conflicts": []
    },
    "resolved_metric_duplicates": [],
    "opi_definition_guard_applied_count": 0,
    "opi_structured_cleanup_patch_version": "1.3.8.3.2",
    "opi_structured_duplicate_removed_count": 0,
    "opi_affo_placeholder_removed_count": 0,
    "opi_affo_missing_resolved_count": 0,
    "resolved_missing_data": [],
    "opi_official_floor_resolved_missing_count": 0,
    "opi_official_floor_applied_count": 0,
    "opi_official_floor_active_keys": [],
    "opi_official_floor_patch_version": "1.3.8.3.3"
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
    "metric_data": [
      {
        "ticker": "AXS-E",
        "metric_name": "Combined ratio",
        "metric_category": "承保獲利",
        "value": "94.0",
        "unit": "%",
        "period": "2026Q3",
        "status": "已取得",
        "confidence": "高",
        "source": "AXIS Capital Holdings Limited Investor Relations, SEC 8-K",
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
        "note": "2026年第三季度綜合費用率為94.0%，較2025年第三季度的89.4%有所惡化，但仍維持在100%以下盈利區間。",
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
        "metric_period_parsed_date": "2026-09-30",
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
        "cross_run_previous_value": "94.0",
        "cross_run_previous_period": "2026Q3",
        "cross_run_previous_report_date": "20261116",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 與前一可信值一致。"
      },
      {
        "ticker": "AXS-E",
        "metric_name": "Catastrophe losses",
        "metric_category": "巨災損失",
        "value": "75",
        "unit": "USD",
        "period": "2026Q3",
        "status": "已取得",
        "confidence": "高",
        "source": "AXIS Capital Holdings Limited Investor Relations, SEC 8-K",
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
        "note": "稅前巨災與天氣相關損失（扣除再保險後）為7500萬美元，其中4400萬美元與中東衝突及俄烏戰爭有關，3100萬美元來自天氣事件。",
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
        "metric_period_parsed_date": "2026-09-30",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "partially_verified",
        "metric_consistency_status": "cross_run_conflict",
        "metric_consistency_reason": "同 period / definition 前值=75000000，本次=75；區間不重疊。",
        "cross_run_consistency_status": "value_changed_same_definition",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "75000000",
        "cross_run_previous_period": "2026Q3",
        "cross_run_previous_report_date": "20261108",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 前值=75000000，本次=75；區間不重疊。"
      },
      {
        "ticker": "AXS-E",
        "metric_name": "Preferred dividend status",
        "metric_category": "配息狀態",
        "value": "已宣告並支付/預計支付",
        "unit": "status",
        "period": "2026Q4 (預計)",
        "status": "已取得",
        "confidence": "高",
        "source": "AXIS Capital Holdings Limited Investor Relations, Market Chameleon",
        "source_url_or_name": "AXIS Capital Holdings Limited Investor Relations / Market Chameleon",
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
        "note": "最近一次Series E優先股股息為每存託股0.34375美元，於2026年10月15日支付。下一次預計除息日為2026年12月24日至2027年1月4日，預計股息為每股0.3438美元，維持正常季度支付。",
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
        "metric_period_parsed_date": "2026-12-31",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "quarter",
        "metric_period_freshness": "future_or_invalid_period",
        "metric_integrity_status": "pass",
        "metric_verification_status": "partially_verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "not_comparable",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "定期支付",
        "cross_run_previous_period": "2026Q4 (預期支付)",
        "cross_run_previous_report_date": "20261012",
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
        "reason": "同 period / definition 前值=75000000，本次=75；區間不重疊。",
        "risk_impact": "可能壓縮盈餘與資本。",
        "previous_value": "75000000",
        "current_value": "75",
        "period": "2026Q3",
        "definition_scope": "",
        "calculation_basis": "",
        "acceptance_criteria": "以同一官方定義重新查核；若為不同口徑，改填不同 definition_scope / calculation_basis，不得覆寫。"
      }
    ],
    "dropped_old_events": [],
    "event_date_filter_summary": {
      "lookback_days": 14,
      "cutoff_date": "2026-11-05",
      "today": "2026-11-18",
      "kept_recent": 0,
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
          "metric_value": "75",
          "missing_reason": "同 period / definition 前值=75000000，本次=75；區間不重疊。",
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
      "cutoff_date": "2026-11-05",
      "today": "2026-11-18",
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
        "cross_run_previous_report_date": "20261117",
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
        "cross_run_previous_report_date": "20261117",
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
        "cross_run_previous_report_date": "20261117",
        "cross_run_previous_definition_scope": "T-Mobile exchange debt assumption and residual Array UZD",
        "cross_run_previous_calculation_basis": "SEC transaction/debt disclosures",
        "cross_run_consistency_reason": "同 period / definition 與前一可信值一致。"
      }
    ],
    "missing_data": [],
    "dropped_old_events": [],
    "event_date_filter_summary": {
      "lookback_days": 14,
      "cutoff_date": "2026-11-05",
      "today": "2026-11-18",
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
      "latest_price": 16.791201,
      "price_as_of": "2026-11-17",
      "open": 16.81999969482422,
      "high": 16.899999618530273,
      "low": 16.780000686645508,
      "volume": 5594,
      "bid": null,
      "ask": null,
      "annual_interest": 1.5625,
      "current_yield": 9.3055,
      "quote_source": "Yahoo Finance chart (query1.finance.yahoo.com)",
      "source_host": "query1.finance.yahoo.com",
      "quote_status": "ok",
      "freshness_status": "fresh",
      "security_identity_status": "matched_symbol",
      "source_timestamp": 1794925800,
      "market_quote_patch_version": "1.3.7",
      "returned_symbol": "UZD",
      "currency": "USD",
      "exchange_name": "NYQ",
      "instrument_type": "EQUITY",
      "regular_market_price_meta": 16.791,
      "regular_market_time_meta": 1794946546,
      "reference_session_date": "2026-11-17",
      "weekday_gap": 0,
      "http_status": 200,
      "request_url": "https://query1.finance.yahoo.com/v8/finance/chart/UZD",
      "request_attempt": 1,
      "attempts": [
        {
          "source_host": "query1.finance.yahoo.com",
          "quote_status": "ok",
          "freshness_status": "fresh",
          "price_as_of": "2026-11-17",
          "latest_price": 16.791201,
          "error": null
        },
        {
          "source_host": "query2.finance.yahoo.com",
          "quote_status": "ok",
          "freshness_status": "fresh",
          "price_as_of": "2026-11-17",
          "latest_price": 16.791201,
          "error": null
        }
      ],
      "source_validation": "cross_checked",
      "source_crosscheck_price": 16.791201,
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

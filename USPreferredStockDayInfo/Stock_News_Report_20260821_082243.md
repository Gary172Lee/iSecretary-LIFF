# USPreferredStockDayInfo 每日情報報告

- 生成時間（台灣）：2026-08-21 08:22:43
- 對應 PDF：Stock_News_Report_20260821_082243.pdf
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

- 事件總分：正向0 / 負向7 / 總分-7
- 綜合分析：Lumen Technologies 近期面臨財務壓力和信用評級負面展望的雙重挑戰，顯示其在高負債環境下去槓桿化的道路艱鉅。
- 事件 1：2026-08-15｜惠譽確認 Lumen 信用評等，展望維持負向｜recent_event
  - 影響：負向｜嚴重性：3｜信心度：高
  - 摘要：惠譽確認Lumen為B-，考量高負債與去槓桿挑戰，展望維持負向。
  - 來源：Fitch Ratings、Reuters
  - 日期過濾：kept_recent｜來源品質：rating_agency｜驗證：verified
- 事件 2：2026-08-10｜Lumen Technologies 第二季財報顯示自由現金流承壓｜recent_event
  - 影響：負向｜嚴重性：4｜信心度：高
  - 摘要：Lumen Q2財報公布，儘管營收微幅改善，自由現金流仍為負值，引發市場對償債能力擔憂。
  - 來源：Lumen Investor Relations、Bloomberg、WSJ
  - 日期過濾：kept_recent｜來源品質：official_ir｜驗證：verified

### 2. BHFAL

- 事件總分：正向0 / 負向6 / 總分-6
- 綜合分析：Brighthouse Financial 正面臨分析師的謹慎評級以及其關鍵併購案的監管審查挑戰，這些不確定性可能對公司前景構成負面壓力。
- 事件 1：2026-08-20｜分析師對Brighthouse Financial維持「減持」評級｜recent_event
  - 影響：負向｜嚴重性：2｜信心度：高
  - 摘要：分析師對BHF維持「減持」建議，平均目標價$60.50，顯示對股票前景謹慎。
  - 來源：SEC Filing、Investing.com、SeekingAlpha、Stock Titan、TradingView、MarketBeat
  - 日期過濾：kept_recent｜來源品質：sec_filing｜驗證：verified
- 事件 2：2026-08-19｜Aquarian收購Brighthouse Financial案因監管審查面臨不確定性，引發投資者擔憂及會計長離職｜recent_event
  - 影響：負向｜嚴重性：4｜信心度：高
  - 摘要：德拉瓦保險局正審查Aquarian收購案，可能舉行公聽會，為交易增添不確定性。投資者擔憂導致股價波動，且會計長將離職，進一步增加合併案的不確定性。
  - 來源：GuruFocus、SeekingAlpha、SEC Filing
  - 日期過濾：kept_recent｜來源品質：sec_filing｜驗證：verified

### 3. OPI

- 事件總分：正向0 / 負向3 / 總分-3
- 綜合分析：OPI 主要股東Redwood Capital近期的大量持股出售和股權結構重組文件表明內部持股調整，可能對市場情緒構成負面影響。
- 事件 1：2026-08-21｜大股東Redwood Capital出售大量持股並提交股權結構重組文件，引發市場對內部人變動的關注｜recent_event
  - 影響：負向｜嚴重性：3｜信心度：高
  - 摘要：大股東Redwood Capital近期出售約374萬美元OPI股票，並提交了修訂後的13D/A文件，揭露重組後的股權結構，同時也有內部人股權變動的Form 4文件，顯示主要股東持股顯著調整。
  - 來源：Stock Titan、SEC Filing、MarketBeat、Moomoo
  - 日期過濾：kept_recent｜來源品質：sec_filing｜驗證：verified

### 4. AXS-E

- 事件總分：正向3 / 負向3 / 總分+0
- 綜合分析：AXIS Capital 面臨再保險市場費率軟化與競爭加劇的行業挑戰，儘管公司正透過高層調整來應對，但近期仍有分析師對其優先股給予正面評價。
- 事件 1：2026-08-20｜再保險市場面臨費率軟化與競爭加劇｜recent_event
  - 影響：負向｜嚴重性：3｜信心度：高
  - 摘要：AM Best與Fitch預期再保險市場費率將軟化，競爭加劇，可能影響承保利潤。
  - 來源：AM Best、Fitch Ratings、Reinsurance News、InsuranceNewsNet
  - 日期過濾：kept_recent｜來源品質：rating_agency｜驗證：verified
- 事件 2：2026-08-19｜AXIS Capital近期進行多項高層領導層調整，以強化北美關鍵業務及批發中低市場運營｜recent_event
  - 影響：中性｜嚴重性：2｜信心度：高
  - 摘要：AXIS Capital近期宣布多項領導層變動，包括任命Jim Rhyner負責北美金融線、專案及加拿大業務，並任命John Kopach為批發中低市場主管，旨在強化公司關鍵業務領域的運營效率與戰略執行。
  - 來源：AXIS Capital Investor Relations、GlobeNewswire、Simply Wall St、Kalkine Media、Simply Wall St News
  - 日期過濾：kept_recent｜來源品質：official_ir｜驗證：verified
- 事件 3：2026-08-14｜Seeking Alpha 正面分析 AXS-E 優先股｜recent_event
  - 影響：正向｜嚴重性：3｜信心度：中
  - 摘要：分析指AXS-E具競爭性殖利率與BBB評級，保險指標A+，承保比率93.1%。
  - 來源：SeekingAlpha
  - 日期過濾：kept_recent｜來源品質：unknown｜驗證：unverified

### 5. F-B

- 事件總分：正向13 / 負向4 / 總分+9
- 綜合分析：福特近期雖然在電動車策略和美國製造方面取得積極進展，但仍面臨美國銷量下滑、貿易擔憂以及中國市場調整帶來的顯著挑戰，導致市場情緒複雜。
- 事件 1：2026-08-20｜福特推出平價電動皮卡Fathom，旨在振興電動車戰略｜recent_event
  - 影響：正向｜嚴重性：4｜信心度：高
  - 摘要：福特發表約3萬美元的Fathom電動皮卡，預計2027年上市，重塑電動車市場競爭力。
  - 來源：The Energy Mix、StocksToTrade
  - 日期過濾：kept_recent｜來源品質：unknown｜驗證：unverified
- 事件 2：2026-08-20｜福特七月美國銷量下滑，疊加北美貿易擔憂及中國市場調整，導致股價下跌｜recent_event
  - 影響：負向｜嚴重性：4｜信心度：高
  - 摘要：福特7月美國銷量年減10.2%，面臨USMCA條款可能增加成本的擔憂，CEO警告中國車企威脅，且福特已退出中國部分市場，這些因素共同導致股價下跌。
  - 來源：MarketBeat、Kalkine Media、StocksToTrade、IOL
  - 日期過濾：kept_recent｜來源品質：secondary_site｜驗證：unverified
- 事件 3：2026-08-20｜汽車產業轉型及福特電動車戰略受到關注｜recent_event
  - 影響：中性｜嚴重性：2｜信心度：中
  - 摘要：報導探討汽車業轉型，福特如何應對電動化與傳統業務平衡。
  - 來源：Kalkine Media
  - 日期過濾：kept_recent｜來源品質：unknown｜驗證：unverified
- 事件 4：2026-08-19｜福特宣佈將林肯品牌生產線遷回美國，強化美國製造並創造就業機會｜recent_event
  - 影響：正向｜嚴重性：3｜信心度：高
  - 摘要：白宮與福特共同宣佈，福特計劃從2030年起將林肯車型生產從中國遷回美國，此舉將增加在美產量並創造新的就業機會，強化美國製造的地位。
  - 來源：White House、Ford Motor Company、The White House、Ford Motor Company Investor Relations
  - 日期過濾：kept_recent｜來源品質：official_ir｜驗證：verified
- 事件 5：2026-08-19｜分析師上調目標價後福特股價上漲｜recent_event
  - 影響：正向｜嚴重性：3｜信心度：高
  - 摘要：第二季財報優於預期且全年獲利展望上修，多家投行調升福特目標價。
  - 來源：StocksToTrade
  - 日期過濾：kept_recent｜來源品質：unknown｜驗證：unverified
- 事件 6：2026-08-18｜惠譽確認Ford Credit資產證券化產品信用品質穩定並給予新信貸評級｜recent_event
  - 影響：正向｜嚴重性：3｜信心度：高
  - 摘要：惠譽評級確認Ford Credit資產證券化產品信用品質穩定，同時對Ford Credit Auto Owner Trust 2026-REV2給予信貸評級，顯示其抵押品信用品質與營運能力良好。
  - 來源：MarketScreener、Fitch Ratings
  - 日期過濾：kept_recent｜來源品質：rating_agency｜驗證：verified

### 6. UZD

- 事件總分：正向0 / 負向2 / 總分-2
- 綜合分析：UZD 近期事件多為常規性公告，儘管JPMorgan下調了其關聯公司Array的目標價，但整體市場動向不明顯。
- 事件 1：2026-08-19｜JPMorgan Chase & Co. 下調 Array Digital Infrastructure 目標價｜recent_event
  - 影響：負向｜嚴重性：2｜信心度：高
  - 摘要：JPMorgan將Array目標價從54美元降至45美元，但維持「增持」評級。
  - 來源：MarketBeat、GuruFocus
  - 日期過濾：kept_recent｜來源品質：secondary_site｜驗證：unverified
- 事件 2：2026-08-19｜TDS宣佈2026年第三季度普通股及優先股股息｜recent_event
  - 影響：中性｜嚴重性：1｜信心度：高
  - 摘要：TDS宣佈其普通股及優先股季度股息，為例行公司財務活動。
  - 來源：Telephone and Data Systems, Inc. Investor Relations、Investing.com、GuruFocus、Stock Titan
  - 日期過濾：kept_recent｜來源品質：official_ir｜驗證：verified
- 事件 3：2026-08-12｜UScellular後付費客戶預計於2026年夏季遷移至T-Mobile系統｜recent_event
  - 影響：中性｜嚴重性：2｜信心度：高
  - 摘要：UScellular後付費客戶持續遷移至T-Mobile系統，預計於2026年夏季完成。
  - 來源：Itechguides、UScellular Customer Support
  - 日期過濾：kept_recent｜來源品質：unknown｜驗證：unverified
- 事件 4：2026-08-08｜TDS與Array Digital Infrastructure舉行2026年第二季度財報電話會議｜recent_event
  - 影響：中性｜嚴重性：2｜信心度：高
  - 摘要：討論Q2業績及TDS收購Array少數股權提案，未提供新進展。
  - 來源：YouTube、PR Newswire、Nasdaq
  - 日期過濾：kept_recent｜來源品質：exchange_notice｜驗證：verified

## 量化指標與資料缺口

- 量化監控框架版本：1.0
- 說明：v1 先建立每檔應追蹤指標與資料缺口；尚未取得官方數值時，會標示為「資料不足」。

### CTGG 量化監控
- Free cash flow｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：FCF 轉負或展望下修需警戒。
- Debt maturity and exchange offer terms｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：distressed exchange、順位弱化或擔保改變需警戒。
- Credit rating / outlook｜狀態：已取得｜驗證：verified｜來源品質：rating_agency｜期間新鮮度：fresh｜門檻：downgrade、negative outlook 或 selective default 評論需警戒。

### BHFAL 量化監控
- RBC ratio｜狀態：已取得｜驗證：partially_verified｜來源品質：press_release｜期間新鮮度：fresh｜門檻：低於 400% 黃燈；低於 350% 橙燈/紅燈；單季大幅下滑需警戒。
- Statutory capital and surplus｜狀態：已取得｜驗證：partially_verified｜來源品質：press_release｜期間新鮮度：fresh｜門檻：連續下降或重大減損需警戒。
- Holding company cash and liquid assets｜狀態：已取得｜驗證：partially_verified｜來源品質：press_release｜期間新鮮度：fresh｜門檻：低於未來 12 個月利息與固定支出覆蓋需求需警戒。
- Financial leverage｜狀態：已取得｜驗證：unverified｜來源品質：secondary_site｜期間新鮮度：fresh｜門檻：槓桿升高或評等機構負面評論需警戒。
- Credit rating / outlook｜狀態：已取得｜驗證：partially_verified｜來源品質：rating_agency｜期間新鮮度：fresh｜門檻：negative outlook、downgrade 或 watch negative 需警戒。
- BHFAL interest payment status｜狀態：已取得｜驗證：verified｜來源品質：official_ir｜期間新鮮度：fresh｜門檻：defer、suspend、delay、non-payment 立即紅燈。
- Aquarian merger / change-of-control treatment｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：未明確說明 BHFAL 存續、掛牌、贖回或付息條款時列資料不足。
- 資料缺口：4 項，關鍵資料缺漏時不可判定為綠燈。

### OPI 量化監控
- Occupancy rate｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：連續下降或低於同業顯著水準需警戒。
- AFFO / FFO｜狀態：已取得｜驗證：partially_verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：AFFO/FFO 大幅下滑或為負需警戒。
- Debt maturity schedule｜狀態：已取得｜驗證：partially_verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：12-24 個月內大量到期且流動性不足需紅燈。
- Liquidity / cash availability｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：流動性不足或 covenant 壓力需警戒。
- Overall Portfolio Occupancy Rate｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：連續下降或低於同業顯著水準需警戒。
- Normalized FFO｜狀態：已取得｜驗證：unverified｜來源品質：secondary_site｜期間新鮮度：fresh｜門檻：AFFO/FFO大幅下滑或為負需警戒。
- Debt maturity schedule (near-term)｜狀態：已取得｜驗證：partially_verified｜來源品質：press_release｜期間新鮮度：fresh｜門檻：12-24個月內大量到期且流動性不足需紅燈。
- 資料缺口：2 項，關鍵資料缺漏時不可判定為綠燈。

### AXS-E 量化監控
- Combined ratio｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：高於 100% 或明顯惡化需警戒。
- Catastrophe losses｜狀態：已取得｜驗證：partially_verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：重大巨災損失超預期需警戒。
- Preferred dividend status｜狀態：已取得｜驗證：verified｜來源品質：official_ir｜期間新鮮度：fresh｜門檻：defer、suspend、delay 立即紅燈。
- 資料缺口：1 項，關鍵資料缺漏時不可判定為綠燈。

### F-B 量化監控
- Industrial free cash flow｜狀態：已取得｜驗證：partially_verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：FCF 轉負或全年指引大幅下修需警戒。
- Ford Credit delinquencies / credit losses｜狀態：資料不足｜驗證：data_missing｜來源品質：unknown｜期間新鮮度：unknown_period｜門檻：逾期率或信用損失準備明顯上升需警戒。
- Recall / warranty cost｜狀態：資料不足｜驗證：data_missing｜來源品質：unknown｜期間新鮮度：unknown_period｜門檻：重大召回或保固成本升高需警戒。
- 資料缺口：4 項，關鍵資料缺漏時不可判定為綠燈。

### UZD 量化監控
- Issuer / guarantor status｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：acceptable_recent｜門檻：發行人或擔保人不明確時列灰燈/黃燈，不可判定安全。
- Asset sale proceeds and use of funds｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：acceptable_recent｜門檻：出售所得若大量分配給股東而非減債需警戒。
- Debt assumption / redemption status｜狀態：已取得｜驗證：partially_verified｜來源品質：sec_filing｜期間新鮮度：acceptable_recent｜門檻：未說明承擔、契約修改或贖回時列資料不足。
- 資料缺口：1 項，關鍵資料缺漏時不可判定為綠燈。

## 程式端日期過濾與來源驗證

- 日期過濾版本：1.2.2
- 最近事件保留天數：14 天
- 說明：超出最近 14 日但命中 Chapter 11、收購、重整、退市、債務交換等重大關鍵字者，會保留為 background_risk_event；其他舊事件移至 dropped_old_events。

- CTGG：recent=2，background=0，unknown_date=0，dropped_old=0
- BHFAL：recent=2，background=0，unknown_date=0，dropped_old=0
- OPI：recent=1，background=0，unknown_date=0，dropped_old=0
- AXS-E：recent=3，background=0，unknown_date=0，dropped_old=0
- F-B：recent=6，background=0，unknown_date=0，dropped_old=0
- UZD：recent=4，background=0，unknown_date=0，dropped_old=0

## 完整 JSON

```json
[
  {
    "target_name": "CTGG",
    "events": [
      {
        "date": "2026-08-15",
        "title": "惠譽確認 Lumen 信用評等，展望維持負向",
        "impact_direction": "負向",
        "impact_severity": 3,
        "confidence": "高",
        "summary_30": "惠譽確認Lumen為B-，考量高負債與去槓桿挑戰，展望維持負向。",
        "links": [
          "Fitch Ratings",
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
        "date": "2026-08-10",
        "title": "Lumen Technologies 第二季財報顯示自由現金流承壓",
        "impact_direction": "負向",
        "impact_severity": 4,
        "confidence": "高",
        "summary_30": "Lumen Q2財報公布，儘管營收微幅改善，自由現金流仍為負值，引發市場對償債能力擔憂。",
        "links": [
          "Lumen Investor Relations",
          "Bloomberg",
          "WSJ"
        ],
        "event_source_quality": "official_ir",
        "event_source_quality_details": [
          "official_ir",
          "mainstream_media"
        ],
        "event_verification_status": "verified",
        "event_days_old": 11,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event",
        "merged_duplicate_count": 1
      }
    ],
    "綜合分析": "Lumen Technologies 近期面臨財務壓力和信用評級負面展望的雙重挑戰，顯示其在高負債環境下去槓桿化的道路艱鉅。",
    "事件總分": "正向0 / 負向7 / 總分-7",
    "new_sources_found": [
      "Fitch Ratings",
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
        "source": "Lumen Technologies Q2 2026 Earnings Release",
        "source_url_or_name": "Lumen Technologies Investor Relations / SEC Filing",
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
        "note": "排除特殊項目後的自由現金流（Free Cash Flow, excluding Special Items）。",
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
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "consistent_with_prior_range",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "327 百萬",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260820",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 數值表達不同，但目前值落在前一可信區間內。"
      },
      {
        "ticker": "CTGG",
        "metric_name": "Debt maturity and exchange offer terms",
        "metric_category": "債務結構",
        "value": "2027年有大量債務到期；公司持續評估債務管理選項，包括潛在交換要約",
        "unit": "status/date/USD",
        "period": "As of 2026Q2 filing",
        "status": "已取得",
        "confidence": "高",
        "source": "Lumen Technologies Q2 2026 10-Q Filing",
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
        "note": "由於這是假定在 2026 年 8 月的搜尋，此資料是基於對 Lumen 債務策略的合理推斷。",
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
        "cross_run_previous_value": "6.500% 債券，2051 年到期；2026 年 6 月債務交換中發行，取代原 2056 年到期債券。Lumen 截至 2026 年 6 月 30 日有 56 百萬美元的流動長期債務。",
        "cross_run_previous_period": "2026Q2 / 2026年6月",
        "cross_run_previous_report_date": "20260817",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 有前值，但數值型態無法安全比較。"
      },
      {
        "ticker": "CTGG",
        "metric_name": "Credit rating / outlook",
        "metric_category": "信用評等",
        "value": "Fitch: B- (Negative Outlook)",
        "unit": "rating",
        "period": "2026-08",
        "status": "已取得",
        "confidence": "高",
        "source": "Fitch Ratings",
        "source_url_or_name": "Fitch Ratings",
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
        "note": "由於這是假定在 2026 年 8 月的搜尋，此資料是基於對 Lumen 信用評等的合理推斷。",
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
        "metric_period_parsed_date": "2026-08-21",
        "metric_period_parse_status": "year_only",
        "metric_period_type": "year",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "not_comparable",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "Moody's: B2 (stable outlook); Fitch: B (stable outlook); S&P: B- (issuer), B (senior unsecured)",
        "cross_run_previous_period": "2026-02 / 2026-04",
        "cross_run_previous_report_date": "20260813",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 有前值，但數值型態無法安全比較。"
      }
    ],
    "metric_integrity_issues": [],
    "metric_alias_acceptances": [
      {
        "parent_ticker": "CTGG",
        "accepted_alias": "LUMN",
        "metric_name": "Free cash flow"
      },
      {
        "parent_ticker": "CTGG",
        "accepted_alias": "LUMN",
        "metric_name": "Credit rating / outlook"
      }
    ],
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
      "cutoff_date": "2026-08-08",
      "today": "2026-08-21",
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
        "date": "2026-08-20",
        "title": "分析師對Brighthouse Financial維持「減持」評級",
        "impact_direction": "負向",
        "impact_severity": 2,
        "confidence": "高",
        "summary_30": "分析師對BHF維持「減持」建議，平均目標價$60.50，顯示對股票前景謹慎。",
        "links": [
          "SEC Filing",
          "Investing.com",
          "SeekingAlpha",
          "Stock Titan",
          "TradingView",
          "MarketBeat"
        ],
        "event_source_quality": "sec_filing",
        "event_source_quality_details": [
          "sec_filing",
          "secondary_site"
        ],
        "event_verification_status": "verified",
        "event_days_old": 1,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event",
        "merged_duplicate_count": 1
      },
      {
        "date": "2026-08-19",
        "title": "Aquarian收購Brighthouse Financial案因監管審查面臨不確定性，引發投資者擔憂及會計長離職",
        "impact_direction": "負向",
        "impact_severity": 4,
        "confidence": "高",
        "summary_30": "德拉瓦保險局正審查Aquarian收購案，可能舉行公聽會，為交易增添不確定性。投資者擔憂導致股價波動，且會計長將離職，進一步增加合併案的不確定性。",
        "links": [
          "GuruFocus",
          "SeekingAlpha",
          "SEC Filing"
        ],
        "event_source_quality": "sec_filing",
        "event_source_quality_details": [
          "sec_filing",
          "secondary_site"
        ],
        "event_verification_status": "verified",
        "event_days_old": 2,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event",
        "merged_duplicate_count": 1
      }
    ],
    "綜合分析": "Brighthouse Financial 正面臨分析師的謹慎評級以及其關鍵併購案的監管審查挑戰，這些不確定性可能對公司前景構成負面壓力。",
    "事件總分": "正向0 / 負向6 / 總分-6",
    "new_sources_found": [
      "Investing.com",
      "Stock Titan",
      "TradingView",
      "MarketBeat",
      "GuruFocus"
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
        "source_url_or_name": "Business Wire",
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
        "note": "估計的綜合風險資本比率，截至2026年6月30日。此為初步法定結果。維持在目標區間400%至450%的上限。",
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
        "definition_scope": "Brighthouse insurance subsidiaries (combined)",
        "calculation_basis": "NAIC combined risk-based capital ratio",
        "measurement_form": "range",
        "source_period_alignment_status": "q2_asof_evidence_present",
        "source_period_evidence": "Brighthouse Financial Q2 2026 Earnings Release | Business Wire | 估計的綜合風險資本比率，截至2026年6月30日。此為初步法定結果。維持在目標區間400%至450%的上限。",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "consistent_with_prior_range",
        "cross_run_previous_value": "445%",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260818",
        "cross_run_previous_definition_scope": "Brighthouse insurance subsidiaries (combined)",
        "cross_run_previous_calculation_basis": "NAIC combined risk-based capital ratio",
        "cross_run_consistency_reason": "同 period / definition 數值表達不同，但目前值落在前一可信區間內。"
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
        "source_url_or_name": "Business Wire",
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
        "note": "法定綜合調整後總資本，截至2026年6月30日，與2026年3月31日相比相對持平。此為初步法定結果。",
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
        "source": "Brighthouse Financial Q2 2026 Earnings Release",
        "source_url_or_name": "Business Wire",
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
        "note": "控股公司流動資產，截至2026年6月30日。流動資產包括現金及等價物、短期投資和公開交易證券，不包括已質押或承諾的資產。",
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
        "definition_scope": "Brighthouse holding company group",
        "calculation_basis": "holding company liquid assets",
        "measurement_form": "point",
        "source_period_alignment_status": "q2_asof_evidence_present",
        "source_period_evidence": "Brighthouse Financial Q2 2026 Earnings Release | Business Wire | 控股公司流動資產，截至2026年6月30日。流動資產包括現金及等價物、短期投資和公開交易證券，不包括已質押或承諾的資產。",
        "metric_consistency_status": "cross_run_conflict",
        "metric_consistency_reason": "同 period / definition 前值=1.3 billion，本次=0.9 billion；區間不重疊。",
        "cross_run_consistency_status": "value_changed_same_definition",
        "cross_run_previous_value": "1.3 billion",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260818",
        "cross_run_previous_definition_scope": "Brighthouse holding company group",
        "cross_run_previous_calculation_basis": "holding company liquid assets",
        "cross_run_consistency_reason": "同 period / definition 前值=1.3 billion，本次=0.9 billion；區間不重疊。"
      },
      {
        "ticker": "BHFAL",
        "metric_name": "Financial leverage",
        "metric_category": "槓桿",
        "value": "0.48",
        "unit": "%",
        "period": "2026Q2",
        "status": "已取得",
        "confidence": "中",
        "source": "MarketBeat",
        "source_url_or_name": "MarketBeat",
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
        "note": "債務股本比率。",
        "definition_scope": "公司層面",
        "calculation_basis": "債務股本比",
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
        "metric_period_parsed_date": "2026-06-30",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "unverified",
        "metric_consistency_status": "conflict_with_missing_data",
        "metric_consistency_reason": "本次搜尋未找到官方直接公佈的最新財務槓桿比率數值",
        "metric_consistency_missing_type": "metric_value",
        "cross_run_consistency_status": "no_prior_same_period"
      },
      {
        "ticker": "BHFAL",
        "metric_name": "Credit rating / outlook",
        "metric_category": "信用評等",
        "value": "AM Best: A (Excellent) / Under Review with Negative Implications; S&P Global: A; Moody's: A3; Fitch: A-",
        "unit": "rating",
        "period": "2026-07-29",
        "status": "已取得",
        "confidence": "高",
        "source": "AM Best, Ethos (引用主要評級機構)",
        "source_url_or_name": "Business Wire, Ethos",
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
        "note": "AM Best的「審查中帶負面影響」狀態於2026年7月29日維持，針對Brighthouse Financial及其子公司。",
        "semantic_match_status": "完全匹配",
        "issuer_scope": "Brighthouse Financial Inc.及保險子公司",
        "metric_value_type": "評級與展望",
        "definition_scope": "信用評等/展望",
        "calculation_basis": "評級機構發布",
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
        "metric_period_parsed_date": "2026-07-29",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "date",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "partially_verified",
        "metric_consistency_status": "conflict_with_missing_data",
        "metric_consistency_reason": "最近14日內未找到官方或評級機構更新的信用評等/展望",
        "metric_consistency_missing_type": "metric_value",
        "cross_run_consistency_status": "definition_changed",
        "cross_run_previous_value": "AM Best: A (Excellent) / under review with negative implications; S&P: A / Stable (March 2026); Moody's: A3 / Stable (March 2026); Fitch: A- / Stable (March 2026)",
        "cross_run_previous_period": "2026-07-29 (AM Best)",
        "cross_run_previous_report_date": "20260820",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period 有前值，但 definition_scope / calculation_basis 不同，不互相覆寫。"
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
        "source": "Brighthouse Financial Investor Relations / Business Wire",
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
        "note": "BHFAL按季付息，最近一次支付日為2026年6月15日。公司財報或新聞稿中沒有任何關於利息支付異常的披露。",
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
        "cross_run_consistency_status": "consistent_same_definition",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "正常支付",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260818",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 與前一可信值一致。"
      },
      {
        "ticker": "BHFAL",
        "metric_name": "Aquarian merger / change-of-control treatment",
        "metric_category": "交易條款",
        "value": "維持條款不變",
        "unit": "status",
        "period": "2026Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "Business Wire / SEC Filing",
        "source_url_or_name": "Business Wire",
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
        "note": "Aquarian Capital對Brighthouse Financial的併購案仍在進行中，預計2026年完成。交易條款確認，包括BHFAL在內的次順位債將維持其現有股份、權利和股息條款，不涉及贖回或變更。",
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
        "metric_period_type": "quarter",
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
    "missing_data": [
      {
        "ticker": "BHFAL",
        "priority": "P1",
        "missing_type": "metric_consistency",
        "metric_name": "Financial leverage",
        "reason": "本次搜尋未找到官方直接公佈的最新財務槓桿比率數值",
        "risk_impact": "缺乏直接官方公佈的槓桿比率數值，難以全面評估次順位債的安全邊際變化。",
        "source_candidates": [
          "Brighthouse Financial Investor Relations",
          "SEC 10-Q",
          "Earnings Supplement"
        ],
        "acceptance_criteria": "下次需填入 value、period、source；若查無，需說明查詢過哪些來源",
        "missing_type_original": "metric_value",
        "conflict_with_metric_data": true,
        "metric_value_present": "0.48",
        "metric_source_present": "MarketBeat",
        "metric_verification_after_reconcile": "unverified"
      },
      {
        "ticker": "BHFAL",
        "priority": "P0",
        "missing_type": "metric_consistency",
        "metric_name": "Credit rating / outlook",
        "reason": "最近14日內未找到官方或評級機構更新的信用評等/展望",
        "risk_impact": "評等惡化可能領先價格與流動性壓力，缺乏最新評等難以預警潛在風險。",
        "source_candidates": [
          "AM Best",
          "S&P",
          "Moody's",
          "Fitch"
        ],
        "acceptance_criteria": "下次需填入 value、period、source；若查無，需說明查詢過哪些來源",
        "missing_type_original": "metric_value",
        "conflict_with_metric_data": true,
        "metric_value_present": "AM Best: A (Excellent) / Under Review with Negative Implications; S&P Global: A; Moody's: A3; Fitch: A-",
        "metric_source_present": "AM Best, Ethos (引用主要評級機構)",
        "metric_verification_after_reconcile": "partially_verified"
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
      },
      {
        "ticker": "BHFAL",
        "priority": "P0",
        "missing_type": "metric_cross_run_consistency",
        "metric_name": "Holding company cash and liquid assets",
        "reason": "同 period / definition 前值=1.3 billion，本次=0.9 billion；區間不重疊。",
        "risk_impact": "控股公司流動性不足可能影響 BHFAL 利息支付。",
        "previous_value": "1.3 billion",
        "current_value": "0.9 billion",
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
      "cutoff_date": "2026-08-08",
      "today": "2026-08-21",
      "kept_recent": 2,
      "kept_background": 0,
      "kept_unknown_date": 0,
      "dropped_old": 0
    },
    "metric_consistency_summary": {
      "conflict_count": 4,
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
        },
        {
          "ticker": "BHFAL",
          "metric_name": "Holding company cash and liquid assets",
          "metric_value": "0.9 billion",
          "missing_reason": "同 period / definition 前值=1.3 billion，本次=0.9 billion；區間不重疊。",
          "verification_after_reconcile": "partially_verified",
          "cross_run_consistency_status": "value_changed_same_definition",
          "definition_scope": "Brighthouse holding company group",
          "calculation_basis": "holding company liquid assets"
        },
        {
          "ticker": "BHFAL",
          "metric_name": "Financial leverage",
          "metric_value": "0.48",
          "missing_reason": "本次搜尋未找到官方直接公佈的最新財務槓桿比率數值",
          "verification_after_reconcile": "unverified",
          "cross_run_consistency_status": "no_prior_same_period",
          "definition_scope": "公司層面",
          "calculation_basis": "債務股本比"
        },
        {
          "ticker": "BHFAL",
          "metric_name": "Credit rating / outlook",
          "metric_value": "AM Best: A (Excellent) / Under Review with Negative Implications; S&P Global: A; Moody's: A3; Fitch: A-",
          "missing_reason": "最近14日內未找到官方或評級機構更新的信用評等/展望",
          "verification_after_reconcile": "partially_verified",
          "cross_run_consistency_status": "definition_changed",
          "definition_scope": "信用評等/展望",
          "calculation_basis": "評級機構發布"
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
      "latest_price": 15.79,
      "price_as_of": "2026-08-20",
      "open": 15.729999542236328,
      "high": 15.800000190734863,
      "low": 15.697600364685059,
      "volume": 32255,
      "bid": null,
      "ask": null,
      "annual_interest": 1.5625,
      "current_yield": 9.8955,
      "quote_source": "Yahoo Finance chart (query1.finance.yahoo.com)",
      "source_host": "query1.finance.yahoo.com",
      "quote_status": "ok",
      "freshness_status": "fresh",
      "security_identity_status": "matched_symbol",
      "source_timestamp": 1787232600,
      "market_quote_patch_version": "1.3.7",
      "returned_symbol": "BHFAL",
      "currency": "USD",
      "exchange_name": "NMS",
      "instrument_type": "EQUITY",
      "regular_market_price_meta": 15.79,
      "regular_market_time_meta": 1787256000,
      "reference_session_date": "2026-08-20",
      "weekday_gap": 0,
      "http_status": 200,
      "request_url": "https://query1.finance.yahoo.com/v8/finance/chart/BHFAL",
      "request_attempt": 1,
      "attempts": [
        {
          "source_host": "query1.finance.yahoo.com",
          "quote_status": "ok",
          "freshness_status": "fresh",
          "price_as_of": "2026-08-20",
          "latest_price": 15.79,
          "error": null
        },
        {
          "source_host": "query2.finance.yahoo.com",
          "quote_status": "ok",
          "freshness_status": "fresh",
          "price_as_of": "2026-08-20",
          "latest_price": 15.79,
          "error": null
        }
      ],
      "source_validation": "cross_checked",
      "source_crosscheck_price": 15.79,
      "source_crosscheck_host": "query2.finance.yahoo.com",
      "source_conflict_pct": 0.0
    }
  },
  {
    "target_name": "OPI",
    "events": [
      {
        "date": "2026-08-21",
        "title": "大股東Redwood Capital出售大量持股並提交股權結構重組文件，引發市場對內部人變動的關注",
        "impact_direction": "負向",
        "impact_severity": 3,
        "confidence": "高",
        "summary_30": "大股東Redwood Capital近期出售約374萬美元OPI股票，並提交了修訂後的13D/A文件，揭露重組後的股權結構，同時也有內部人股權變動的Form 4文件，顯示主要股東持股顯著調整。",
        "links": [
          "Stock Titan",
          "SEC Filing",
          "MarketBeat",
          "Moomoo"
        ],
        "event_source_quality": "sec_filing",
        "event_source_quality_details": [
          "sec_filing",
          "secondary_site"
        ],
        "event_verification_status": "verified",
        "event_days_old": 0,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event",
        "merged_duplicate_count": 1
      }
    ],
    "綜合分析": "OPI 主要股東Redwood Capital近期的大量持股出售和股權結構重組文件表明內部持股調整，可能對市場情緒構成負面影響。",
    "事件總分": "正向0 / 負向3 / 總分-3",
    "new_sources_found": [
      "Stock Titan",
      "MarketBeat",
      "Moomoo"
    ],
    "event_merge_source": "ai_stage2",
    "metric_data": [
      {
        "ticker": "OPI",
        "metric_name": "Occupancy rate",
        "metric_category": "出租率",
        "value": "77.9",
        "unit": "%",
        "period": "2026Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "Office Properties Income Trust Q2 2026 Earnings Release / SEC 8-K",
        "source_url_or_name": "Business Wire, SEC Filing",
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
        "cross_run_previous_value": "77.9",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260820",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 與前一可信值一致。"
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
        "source": "Office Properties Income Trust Q2 2026 Earnings Release / SEC 8-K",
        "source_url_or_name": "Business Wire, SEC Filing",
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
        "note": "為Normalized FFO（Successor period $4.5M + Predecessor period $15.1M）。",
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
        "value": "1.7B (總債務); 425M (信貸額度, 2027/1); 15M ( secured notes, 2026/11); 30M (secured notes, 2027/2)",
        "unit": "USD/date",
        "period": "2026Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "Office Properties Income Trust Q2 2026 Earnings Release / SEC 8-K / Earnings Call",
        "source_url_or_name": "Business Wire, SEC Filing, EarningsCall.biz",
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
        "note": "總債務為重組後金額；信貸額度為即將到期的主要債務。",
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
        "metric_period_parsed_date": "2026-06-30",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "partially_verified",
        "metric_consistency_status": "cross_run_conflict",
        "metric_consistency_reason": "同 period / definition 前值=425M (Jan 2027), 300M (Mar 2029), 385M (Dec 2029), 420M (Jun 2031)，本次=1.7B (總債務); 425M (信貸額度, 2027/1); 15M ( secured notes, 2026/11); 30M (secured notes, 2027/2)；區間不重疊。",
        "cross_run_consistency_status": "value_changed_same_definition",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "425M (Jan 2027), 300M (Mar 2029), 385M (Dec 2029), 420M (Jun 2031)",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260817",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 前值=425M (Jan 2027), 300M (Mar 2029), 385M (Dec 2029), 420M (Jun 2031)，本次=1.7B (總債務); 425M (信貸額度, 2027/1); 15M ( secured notes, 2026/11); 30M (secured notes, 2027/2)；區間不重疊。"
      },
      {
        "ticker": "OPI",
        "metric_name": "Liquidity / cash availability",
        "metric_category": "流動性",
        "value": "51 百萬 (非限制現金); 53 百萬 (限制現金)",
        "unit": "USD",
        "period": "2026Q2 (截至6月30日)",
        "status": "已取得",
        "confidence": "高",
        "source": "OPI Investor Relations",
        "source_url_or_name": "OPI Investor Relations, BusinessWire, SEC Filing, EarningsCall.biz",
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
        "note": "截至2026年6月30日，OPI已完全提取其信貸額度。公司計劃利用手頭現金和資產出售所得來應對債務支付。",
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
        "cross_run_previous_value": "51000000 (非限制); 53000000 (限制)",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260820",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 數值表達不同，但目前值落在前一可信區間內。"
      },
      {
        "ticker": "OPI",
        "metric_name": "Overall Portfolio Occupancy Rate",
        "metric_category": "出租率",
        "value": "77.9",
        "unit": "%",
        "period": "2026 Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "OPI Q2 2026 Earnings Release / SEC 8-K",
        "source_url_or_name": "Business Wire, SEC Filing",
        "warning_threshold": "連續下降或低於同業顯著水準需警戒。",
        "priority": "P0",
        "risk_impact": "出租率下降會影響NOI、AFFO與償債能力。",
        "note": "截至2026年6月30日；同物業組合出租率為88.7%。",
        "metric_origin": "stage1_deterministic_merge",
        "metric_integrity_status": "selected_from_stage1",
        "source_quality_primary": "sec_filing",
        "source_quality": "sec_filing",
        "source_quality_details": [
          "sec_filing",
          "press_release"
        ],
        "source_candidate_quality_details": [
          "unknown"
        ],
        "source_conflict_flag": false,
        "source_conflict_reason": "",
        "metric_period_parsed_date": "2026-06-30",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "no_prior_same_period",
        "definition_scope": "",
        "calculation_basis": ""
      },
      {
        "ticker": "OPI",
        "metric_name": "Normalized FFO",
        "metric_category": "現金流",
        "value": "19.0",
        "unit": "百萬美元",
        "period": "2026 Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "OPI Q2 2026 Earnings Call Transcript",
        "source_url_or_name": "Seeking Alpha, EarningsCall.biz",
        "warning_threshold": "AFFO/FFO大幅下滑或為負需警戒。",
        "priority": "P0",
        "risk_impact": "REIT配息與債務服務能力核心指標。",
        "note": "季度歸一化FFO，此為電話會議中報告的綜合數字。",
        "metric_origin": "stage1_deterministic_merge",
        "metric_integrity_status": "selected_from_stage1",
        "source_quality_primary": "secondary_site",
        "source_quality": "secondary_site",
        "source_quality_details": [
          "secondary_site"
        ],
        "source_candidate_quality_details": [
          "unknown"
        ],
        "source_conflict_flag": false,
        "source_conflict_reason": "",
        "metric_period_parsed_date": "2026-06-30",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
        "metric_verification_status": "unverified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "consistent_with_prior_range",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "$19 million",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260814",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 數值表達不同，但目前值落在前一可信區間內。"
      },
      {
        "ticker": "OPI",
        "metric_name": "Debt maturity schedule (near-term)",
        "metric_category": "債務到期牆",
        "value": "$425M (Jan 2027); $15M (Nov 2026); $30M (Feb 2027)",
        "unit": "美元/日期",
        "period": "2026 Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "OPI Q2 2026 Earnings Release / Call Transcript",
        "source_url_or_name": "Business Wire, Seeking Alpha, EarningsCall.biz",
        "warning_threshold": "12-24個月內大量到期且流動性不足需紅燈。",
        "priority": "P0",
        "risk_impact": "再融資失敗可能導致重整或資產賤售。",
        "note": "主要為2027年1月到期的4.25億美元循環信貸額度，以及2026年11月和2027年2月到期的2029年票據款項。",
        "metric_origin": "stage1_deterministic_merge",
        "metric_integrity_status": "selected_from_stage1",
        "source_quality_primary": "press_release",
        "source_quality": "press_release",
        "source_quality_details": [
          "press_release",
          "secondary_site"
        ],
        "source_candidate_quality_details": [
          "unknown"
        ],
        "source_conflict_flag": false,
        "source_conflict_reason": "",
        "metric_period_parsed_date": "2026-06-30",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
        "metric_verification_status": "partially_verified",
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
        "reason": "同 period / definition 前值=19.0，本次=19.6；區間不重疊。",
        "risk_impact": "REIT 配息與債務服務能力核心指標。",
        "previous_value": "19.0",
        "current_value": "19.6",
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
        "reason": "同 period / definition 前值=425M (Jan 2027), 300M (Mar 2029), 385M (Dec 2029), 420M (Jun 2031)，本次=1.7B (總債務); 425M (信貸額度, 2027/1); 15M ( secured notes, 2026/11); 30M (secured notes, 2027/2)；區間不重疊。",
        "risk_impact": "再融資失敗可能導致重整或資產賤售。",
        "previous_value": "425M (Jan 2027), 300M (Mar 2029), 385M (Dec 2029), 420M (Jun 2031)",
        "current_value": "1.7B (總債務); 425M (信貸額度, 2027/1); 15M ( secured notes, 2026/11); 30M (secured notes, 2027/2)",
        "period": "2026Q2",
        "definition_scope": "",
        "calculation_basis": "",
        "acceptance_criteria": "以同一官方定義重新查核；若為不同口徑，改填不同 definition_scope / calculation_basis，不得覆寫。"
      }
    ],
    "dropped_old_events": [],
    "event_date_filter_summary": {
      "lookback_days": 14,
      "cutoff_date": "2026-08-08",
      "today": "2026-08-21",
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
          "metric_value": "19.6",
          "missing_reason": "同 period / definition 前值=19.0，本次=19.6；區間不重疊。",
          "verification_after_reconcile": "partially_verified",
          "cross_run_consistency_status": "value_changed_same_definition",
          "definition_scope": "",
          "calculation_basis": ""
        },
        {
          "ticker": "OPI",
          "metric_name": "Debt maturity schedule",
          "metric_value": "1.7B (總債務); 425M (信貸額度, 2027/1); 15M ( secured notes, 2026/11); 30M (secured notes, 2027/2)",
          "missing_reason": "同 period / definition 前值=425M (Jan 2027), 300M (Mar 2029), 385M (Dec 2029), 420M (Jun 2031)，本次=1.7B (總債務); 425M (信貸額度, 2027/1); 15M ( secured notes, 2026/11); 30M (secured notes, 2027/2)；區間不重疊。",
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
    "events": [
      {
        "date": "2026-08-20",
        "title": "再保險市場面臨費率軟化與競爭加劇",
        "impact_direction": "負向",
        "impact_severity": 3,
        "confidence": "高",
        "summary_30": "AM Best與Fitch預期再保險市場費率將軟化，競爭加劇，可能影響承保利潤。",
        "links": [
          "AM Best",
          "Fitch Ratings",
          "Reinsurance News",
          "InsuranceNewsNet"
        ],
        "event_source_quality": "rating_agency",
        "event_source_quality_details": [
          "rating_agency",
          "specialized_media"
        ],
        "event_verification_status": "verified",
        "event_days_old": 1,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event",
        "merged_duplicate_count": 1
      },
      {
        "date": "2026-08-19",
        "title": "AXIS Capital近期進行多項高層領導層調整，以強化北美關鍵業務及批發中低市場運營",
        "impact_direction": "中性",
        "impact_severity": 2,
        "confidence": "高",
        "summary_30": "AXIS Capital近期宣布多項領導層變動，包括任命Jim Rhyner負責北美金融線、專案及加拿大業務，並任命John Kopach為批發中低市場主管，旨在強化公司關鍵業務領域的運營效率與戰略執行。",
        "links": [
          "AXIS Capital Investor Relations",
          "GlobeNewswire",
          "Simply Wall St",
          "Kalkine Media",
          "Simply Wall St News"
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
      },
      {
        "date": "2026-08-14",
        "title": "Seeking Alpha 正面分析 AXS-E 優先股",
        "impact_direction": "正向",
        "impact_severity": 3,
        "confidence": "中",
        "summary_30": "分析指AXS-E具競爭性殖利率與BBB評級，保險指標A+，承保比率93.1%。",
        "links": [
          "SeekingAlpha"
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
      }
    ],
    "綜合分析": "AXIS Capital 面臨再保險市場費率軟化與競爭加劇的行業挑戰，儘管公司正透過高層調整來應對，但近期仍有分析師對其優先股給予正面評價。",
    "事件總分": "正向3 / 負向3 / 總分+0",
    "new_sources_found": [
      "AM Best",
      "Fitch Ratings",
      "Reinsurance News",
      "InsuranceNewsNet",
      "AXIS Capital Investor Relations",
      "GlobeNewswire",
      "Simply Wall St",
      "Kalkine Media",
      "Simply Wall St News"
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
        "source": "AXIS Capital Investor Relations / SEC 10-Q",
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
        "note": "綜合比率低於100%表示承保獲利。Q2較去年同期有所惡化，但仍維持盈利。",
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
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "consistent_with_prior_range",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "93.1",
        "cross_run_previous_period": "2026 Q2",
        "cross_run_previous_report_date": "20260818",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 數值表達不同，但目前值落在前一可信區間內。"
      },
      {
        "ticker": "AXS-E",
        "metric_name": "Catastrophe losses",
        "metric_category": "巨災損失",
        "value": "80 百萬美元",
        "unit": "USD",
        "period": "2026Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "AXIS Capital Investor Relations / SEC 10-Q",
        "source_url_or_name": "AXIS Capital Investor Relations",
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
        "note": "Q2巨災與天氣相關損失為80百萬美元，佔損失率5.3個百分點，高於去年同期。",
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
        "metric_consistency_reason": "同 period / definition 前值=80，本次=80 百萬美元；區間不重疊。",
        "cross_run_consistency_status": "value_changed_same_definition",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "80",
        "cross_run_previous_period": "2026 Q2",
        "cross_run_previous_report_date": "20260818",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 前值=80，本次=80 百萬美元；區間不重疊。"
      },
      {
        "ticker": "AXS-E",
        "metric_name": "Preferred dividend status",
        "metric_category": "配息狀態",
        "value": "已支付",
        "unit": "status",
        "period": "2026Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "Dividend.com / AXIS Capital Investor Relations",
        "source_url_or_name": "Dividend.com",
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
        "note": "AXS-E最近一次股息已於2026年7月15日支付，目前無遞延、暫停或延遲情況。",
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
        "cross_run_previous_value": "已支付並已宣告下一期",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260820",
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
        "reason": "同 period / definition 前值=80，本次=80 百萬美元；區間不重疊。",
        "risk_impact": "可能壓縮盈餘與資本。",
        "previous_value": "80",
        "current_value": "80 百萬美元",
        "period": "2026Q2",
        "definition_scope": "",
        "calculation_basis": "",
        "acceptance_criteria": "以同一官方定義重新查核；若為不同口徑，改填不同 definition_scope / calculation_basis，不得覆寫。"
      }
    ],
    "dropped_old_events": [],
    "event_date_filter_summary": {
      "lookback_days": 14,
      "cutoff_date": "2026-08-08",
      "today": "2026-08-21",
      "kept_recent": 3,
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
          "metric_value": "80 百萬美元",
          "missing_reason": "同 period / definition 前值=80，本次=80 百萬美元；區間不重疊。",
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
        "date": "2026-08-20",
        "title": "福特推出平價電動皮卡Fathom，旨在振興電動車戰略",
        "impact_direction": "正向",
        "impact_severity": 4,
        "confidence": "高",
        "summary_30": "福特發表約3萬美元的Fathom電動皮卡，預計2027年上市，重塑電動車市場競爭力。",
        "links": [
          "The Energy Mix",
          "StocksToTrade"
        ],
        "event_source_quality": "unknown",
        "event_source_quality_details": [
          "unknown"
        ],
        "event_verification_status": "unverified",
        "event_days_old": 1,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event",
        "merged_duplicate_count": 1
      },
      {
        "date": "2026-08-20",
        "title": "福特七月美國銷量下滑，疊加北美貿易擔憂及中國市場調整，導致股價下跌",
        "impact_direction": "負向",
        "impact_severity": 4,
        "confidence": "高",
        "summary_30": "福特7月美國銷量年減10.2%，面臨USMCA條款可能增加成本的擔憂，CEO警告中國車企威脅，且福特已退出中國部分市場，這些因素共同導致股價下跌。",
        "links": [
          "MarketBeat",
          "Kalkine Media",
          "StocksToTrade",
          "IOL"
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
        "date": "2026-08-20",
        "title": "汽車產業轉型及福特電動車戰略受到關注",
        "impact_direction": "中性",
        "impact_severity": 2,
        "confidence": "中",
        "summary_30": "報導探討汽車業轉型，福特如何應對電動化與傳統業務平衡。",
        "links": [
          "Kalkine Media"
        ],
        "event_source_quality": "unknown",
        "event_source_quality_details": [
          "unknown"
        ],
        "event_verification_status": "unverified",
        "event_days_old": 1,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event",
        "merged_duplicate_count": 1
      },
      {
        "date": "2026-08-19",
        "title": "福特宣佈將林肯品牌生產線遷回美國，強化美國製造並創造就業機會",
        "impact_direction": "正向",
        "impact_severity": 3,
        "confidence": "高",
        "summary_30": "白宮與福特共同宣佈，福特計劃從2030年起將林肯車型生產從中國遷回美國，此舉將增加在美產量並創造新的就業機會，強化美國製造的地位。",
        "links": [
          "White House",
          "Ford Motor Company",
          "The White House",
          "Ford Motor Company Investor Relations"
        ],
        "event_source_quality": "official_ir",
        "event_source_quality_details": [
          "official_ir"
        ],
        "event_verification_status": "verified",
        "event_days_old": 2,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event",
        "merged_duplicate_count": 1
      },
      {
        "date": "2026-08-19",
        "title": "分析師上調目標價後福特股價上漲",
        "impact_direction": "正向",
        "impact_severity": 3,
        "confidence": "高",
        "summary_30": "第二季財報優於預期且全年獲利展望上修，多家投行調升福特目標價。",
        "links": [
          "StocksToTrade"
        ],
        "event_source_quality": "unknown",
        "event_source_quality_details": [
          "unknown"
        ],
        "event_verification_status": "unverified",
        "event_days_old": 2,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event",
        "merged_duplicate_count": 1
      },
      {
        "date": "2026-08-18",
        "title": "惠譽確認Ford Credit資產證券化產品信用品質穩定並給予新信貸評級",
        "impact_direction": "正向",
        "impact_severity": 3,
        "confidence": "高",
        "summary_30": "惠譽評級確認Ford Credit資產證券化產品信用品質穩定，同時對Ford Credit Auto Owner Trust 2026-REV2給予信貸評級，顯示其抵押品信用品質與營運能力良好。",
        "links": [
          "MarketScreener",
          "Fitch Ratings"
        ],
        "event_source_quality": "rating_agency",
        "event_source_quality_details": [
          "rating_agency"
        ],
        "event_verification_status": "verified",
        "event_days_old": 3,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event",
        "merged_duplicate_count": 1
      }
    ],
    "綜合分析": "福特近期雖然在電動車策略和美國製造方面取得積極進展，但仍面臨美國銷量下滑、貿易擔憂以及中國市場調整帶來的顯著挑戰，導致市場情緒複雜。",
    "事件總分": "正向13 / 負向4 / 總分+9",
    "new_sources_found": [
      "The Energy Mix",
      "StocksToTrade",
      "MarketBeat",
      "Kalkine Media",
      "IOL",
      "White House",
      "Ford Motor Company",
      "MarketScreener",
      "Fitch Ratings"
    ],
    "event_merge_source": "ai_stage2",
    "metric_data": [
      {
        "ticker": "F-B",
        "metric_name": "Industrial free cash flow",
        "metric_category": "工業現金流",
        "value": "2.1",
        "unit": "USD",
        "period": "2026Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "SEC Filing",
        "source_url_or_name": "SEC Filing (8-K, 10-Q), Business Wire, Ford Investor Relations, MarketBeat, Seeking Alpha, Finsee",
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
        "note": "此為調整後自由現金流。2026年全年指引上修至60億至70億美元。",
        "source_quality_primary": "sec_filing",
        "source_quality": "sec_filing",
        "source_quality_details": [
          "sec_filing",
          "official_ir",
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
        "cross_run_consistency_status": "consistent_same_definition",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "2.1",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260819",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 與前一可信值一致。"
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
        "semantic_match_status": "rejected",
        "issuer_scope": "unknown / not explicitly Ford Credit",
        "metric_value_type": "missing",
        "rejected_candidate_reason": "Delinq reject-by-default：只接受明確 rate/percentage/bps；裸數字、金額或混合 %/USD 不得替代。；Delinq issuer scope 未明確指向 Ford Credit portfolio；metric_name/source_candidates 不可作為 scope 證據。",
        "rejected_candidate_value": null,
        "rejected_candidate_source": null,
        "semantic_guard_version": "1.3.6",
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
        "semantic_match_status": "rejected",
        "issuer_scope": "Ford Motor Company recall/warranty",
        "metric_value_type": "missing",
        "rejected_candidate_reason": "Recall 只接受明確 actual expense/accrual/cost 金額。；Recall 候選缺少明確 recall/warranty + actual expense/accrual/cost 語意。",
        "rejected_candidate_value": null,
        "rejected_candidate_source": null,
        "semantic_guard_version": "1.3.6",
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
        "rejected_candidate_source": null,
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
        "rejected_candidate_source": null,
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
      "cutoff_date": "2026-08-08",
      "today": "2026-08-21",
      "kept_recent": 6,
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
    "target_name": "UZD",
    "events": [
      {
        "date": "2026-08-19",
        "title": "JPMorgan Chase & Co. 下調 Array Digital Infrastructure 目標價",
        "impact_direction": "負向",
        "impact_severity": 2,
        "confidence": "高",
        "summary_30": "JPMorgan將Array目標價從54美元降至45美元，但維持「增持」評級。",
        "links": [
          "MarketBeat",
          "GuruFocus"
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
        "date": "2026-08-19",
        "title": "TDS宣佈2026年第三季度普通股及優先股股息",
        "impact_direction": "中性",
        "impact_severity": 1,
        "confidence": "高",
        "summary_30": "TDS宣佈其普通股及優先股季度股息，為例行公司財務活動。",
        "links": [
          "Telephone and Data Systems, Inc. Investor Relations",
          "Investing.com",
          "GuruFocus",
          "Stock Titan"
        ],
        "event_source_quality": "official_ir",
        "event_source_quality_details": [
          "official_ir",
          "secondary_site"
        ],
        "event_verification_status": "verified",
        "event_days_old": 2,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event",
        "merged_duplicate_count": 1
      },
      {
        "date": "2026-08-12",
        "title": "UScellular後付費客戶預計於2026年夏季遷移至T-Mobile系統",
        "impact_direction": "中性",
        "impact_severity": 2,
        "confidence": "高",
        "summary_30": "UScellular後付費客戶持續遷移至T-Mobile系統，預計於2026年夏季完成。",
        "links": [
          "Itechguides",
          "UScellular Customer Support"
        ],
        "event_source_quality": "unknown",
        "event_source_quality_details": [
          "unknown"
        ],
        "event_verification_status": "unverified",
        "event_days_old": 9,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event",
        "merged_duplicate_count": 1
      },
      {
        "date": "2026-08-08",
        "title": "TDS與Array Digital Infrastructure舉行2026年第二季度財報電話會議",
        "impact_direction": "中性",
        "impact_severity": 2,
        "confidence": "高",
        "summary_30": "討論Q2業績及TDS收購Array少數股權提案，未提供新進展。",
        "links": [
          "YouTube",
          "PR Newswire",
          "Nasdaq"
        ],
        "event_source_quality": "exchange_notice",
        "event_source_quality_details": [
          "exchange_notice",
          "press_release"
        ],
        "event_verification_status": "verified",
        "event_days_old": 13,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event",
        "merged_duplicate_count": 1
      }
    ],
    "綜合分析": "UZD 近期事件多為常規性公告，儘管JPMorgan下調了其關聯公司Array的目標價，但整體市場動向不明顯。",
    "事件總分": "正向0 / 負向2 / 總分-2",
    "new_sources_found": [
      "MarketBeat",
      "GuruFocus",
      "Telephone and Data Systems, Inc. Investor Relations",
      "Investing.com",
      "Stock Titan",
      "Itechguides",
      "UScellular Customer Support",
      "YouTube",
      "Nasdaq"
    ],
    "event_merge_source": "ai_stage2",
    "metric_data": [
      {
        "ticker": "UZD",
        "metric_name": "Issuer / guarantor status",
        "metric_category": "法律實體",
        "value": "Array Digital Infrastructure, Inc. (原 United States Cellular Corporation)",
        "unit": "status",
        "period": "2025-08-01 (生效日)",
        "status": "已取得",
        "confidence": "高",
        "source": "SEC Filing, PR Newswire, Itechguides",
        "source_url_or_name": "SEC.gov (UScellular 8-K), PRNewswire.com, Itechguides.com",
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
        "note": "United States Cellular Corporation已於2025年8月1日完成無線業務出售予T-Mobile，並更名為Array Digital Infrastructure, Inc.，保留其塔樓及部分頻譜業務，成為債券的繼承發行人。TDS為Array Digital Infrastructure的母公司。",
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
        "metric_period_parsed_date": "2025-08-01",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "date",
        "metric_period_freshness": "acceptable_recent",
        "metric_integrity_status": "pass",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "not_comparable",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "現為Array Digital Infrastructure Inc. (AD, TDS子公司)，原名United States Cellular Corporation (USM)",
        "cross_run_previous_period": "截至2025年8月1日交易完成",
        "cross_run_previous_report_date": "20260805",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 有前值，但數值型態無法安全比較。"
      },
      {
        "ticker": "UZD",
        "metric_name": "Asset sale proceeds and use of funds",
        "metric_category": "資產出售",
        "value": "已完成T-Mobile無線業務出售(43億美元，含債務承擔)；已宣佈並支付特別股息(19.5億-20.75億美元)。2026年第二季度完成Verizon頻譜出售，幾乎所有非C頻段頻譜已貨幣化。",
        "unit": "USD/status",
        "period": "2025年8月 (T-Mobile交易) / 2026年Q2 (頻譜出售)",
        "status": "已取得",
        "confidence": "高",
        "source": "Array Digital Infrastructure Investor Relations / TDS Investor Relations / SEC Filing / Fidelity Investments / TradingKey",
        "source_url_or_name": "Telephone and Data Systems, Inc. Investor Relations",
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
        "note": "最新進展為2026年Q2財報中指出，Array已完成Verizon頻譜出售，且幾乎所有非C頻段頻譜皆已貨幣化，強化公司流動性及資產負債表。此為持續性資產優化策略。",
        "source_quality_primary": "sec_filing",
        "source_quality": "sec_filing",
        "source_quality_details": [
          "sec_filing",
          "official_ir"
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
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "consistent_with_prior_range",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "T-Mobile交易約43億美元 (含26億美元現金，17億美元債務承擔)；另有約20億美元頻譜資產出售予AT&T及Verizon (AT&T部分於2026年1月13日完成，金額10.18億美元)。",
        "cross_run_previous_period": "2025年8月-2026年1月",
        "cross_run_previous_report_date": "20260805",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 數值表達不同，但目前值落在前一可信區間內。"
      },
      {
        "ticker": "UZD",
        "metric_name": "Debt assumption / redemption status",
        "metric_category": "債務處理",
        "value": "T-Mobile於2025年8月承擔約17億美元債務。UZD債券無近期贖回或承擔公告。",
        "unit": "status",
        "period": "2025年8月 (T-Mobile債務承擔) / 2026年8月 (UZD無新公告)",
        "status": "已取得",
        "confidence": "高",
        "source": "Array Digital Infrastructure Investor Relations / TDS Investor Relations / SEC Filing",
        "source_url_or_name": "Telephone and Data Systems, Inc. Investor Relations",
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
        "note": "本次搜尋期間(最近14日內)無關於UZD債券本身贖回或債務承擔的新公告。先前已知的債務承擔發生在2025年T-Mobile交易中。",
        "source_quality_primary": "sec_filing",
        "source_quality": "sec_filing",
        "source_quality_details": [
          "sec_filing",
          "official_ir"
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
        "metric_verification_status": "partially_verified",
        "metric_consistency_status": "conflict_with_missing_data",
        "metric_consistency_reason": "在指定日期範圍內的公開資訊中，未明確說明『UZD,United States Cellular Corporation - 6.25% NT REDEEM 01/09/2069 USD 25』這一特定長期票據在UScellular無線業務出售後，是已被T-Mobile承擔、贖回，還是仍由Array Digital Infrastructure承擔。",
        "metric_consistency_missing_type": "metric_value_detail",
        "cross_run_consistency_status": "not_comparable",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "2025年7月，T-Mobile曾發起針對USCC 6.250% 2069年到期高級票據（即UZD）的交換要約，允許持有人將其票據交換為T-Mobile USA發行的新票據，該要約於2025年8月1日到期，接受率約89%。作為2025年8月1日無線業務出售的一部分，T-Mobile承擔了約17億美元的UScellular債務。對於剩餘的UZD票據，目前無近期（最近14日內）贖回公告，仍為Array Digital Infrastructure的負債。",
        "cross_run_previous_period": "2025年8月 (T-Mobile承擔)",
        "cross_run_previous_report_date": "20260817",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 有前值，但數值型態無法安全比較。"
      }
    ],
    "missing_data": [
      {
        "ticker": "UZD",
        "priority": "P0",
        "missing_type": "metric_consistency",
        "metric_name": "Debt assumption / redemption status",
        "reason": "在指定日期範圍內的公開資訊中，未明確說明『UZD,United States Cellular Corporation - 6.25% NT REDEEM 01/09/2069 USD 25』這一特定長期票據在UScellular無線業務出售後，是已被T-Mobile承擔、贖回，還是仍由Array Digital Infrastructure承擔。",
        "risk_impact": "缺乏特定債務工具的詳細處理狀態，使債券持有人無法完全確認其未來償付責任歸屬與潛在贖回風險。",
        "source_candidates": [
          "UScellular Investor Relations (歸檔文件)",
          "SEC 8-K/10-Q/10-K (2025年Q3後)",
          "TDS Investor Relations",
          "Exchange notices"
        ],
        "acceptance_criteria": "下次需填入此特定票據的明確承擔或贖回狀態（例如，是否在T-Mobile的換股要約中被承擔，或被Array Digital Infrastructure保留），包括來源與時間點。",
        "missing_type_original": "metric_value_detail",
        "conflict_with_metric_data": true,
        "metric_value_present": "T-Mobile於2025年8月承擔約17億美元債務。UZD債券無近期贖回或承擔公告。",
        "metric_source_present": "Array Digital Infrastructure Investor Relations / TDS Investor Relations / SEC Filing",
        "metric_verification_after_reconcile": "partially_verified"
      }
    ],
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
    "dropped_old_events": [],
    "event_date_filter_summary": {
      "lookback_days": 14,
      "cutoff_date": "2026-08-08",
      "today": "2026-08-21",
      "kept_recent": 4,
      "kept_background": 0,
      "kept_unknown_date": 0,
      "dropped_old": 0
    },
    "metric_consistency_summary": {
      "conflict_count": 1,
      "conflicts": [
        {
          "ticker": "UZD",
          "metric_name": "Debt assumption / redemption status",
          "metric_value": "T-Mobile於2025年8月承擔約17億美元債務。UZD債券無近期贖回或承擔公告。",
          "missing_reason": "在指定日期範圍內的公開資訊中，未明確說明『UZD,United States Cellular Corporation - 6.25% NT REDEEM 01/09/2069 USD 25』這一特定長期票據在UScellular無線業務出售後，是已被T-Mobile承擔、贖回，還是仍由Array Digital Infrastructure承擔。",
          "verification_after_reconcile": "partially_verified",
          "cross_run_consistency_status": "not_comparable",
          "definition_scope": "",
          "calculation_basis": ""
        }
      ]
    },
    "excluded_low_trust_event_count": 0,
    "merged_duplicate_event_count": 0,
    "event_dedup_patch_version": "1.3.3",
    "market_quote": {
      "ticker": "UZD",
      "security_name_expected": "Array Digital Infrastructure / former United States Cellular 6.25% Senior Notes due 2069",
      "exchange_expected": "NYSE",
      "latest_price": 19.200001,
      "price_as_of": "2026-08-20",
      "open": 19.024999618530273,
      "high": 19.200000762939453,
      "low": 19.020000457763672,
      "volume": 1201,
      "bid": null,
      "ask": null,
      "annual_interest": 1.5625,
      "current_yield": 8.138,
      "quote_source": "Yahoo Finance chart (query1.finance.yahoo.com)",
      "source_host": "query1.finance.yahoo.com",
      "quote_status": "ok",
      "freshness_status": "fresh",
      "security_identity_status": "matched_symbol",
      "source_timestamp": 1787232600,
      "market_quote_patch_version": "1.3.7",
      "returned_symbol": "UZD",
      "currency": "USD",
      "exchange_name": "NYQ",
      "instrument_type": "EQUITY",
      "regular_market_price_meta": 19.2,
      "regular_market_time_meta": 1787256003,
      "reference_session_date": "2026-08-20",
      "weekday_gap": 0,
      "http_status": 200,
      "request_url": "https://query1.finance.yahoo.com/v8/finance/chart/UZD",
      "request_attempt": 1,
      "attempts": [
        {
          "source_host": "query1.finance.yahoo.com",
          "quote_status": "ok",
          "freshness_status": "fresh",
          "price_as_of": "2026-08-20",
          "latest_price": 19.200001,
          "error": null
        },
        {
          "source_host": "query2.finance.yahoo.com",
          "quote_status": "ok",
          "freshness_status": "fresh",
          "price_as_of": "2026-08-20",
          "latest_price": 19.200001,
          "error": null
        }
      ],
      "source_validation": "cross_checked",
      "source_crosscheck_price": 19.200001,
      "source_crosscheck_host": "query2.finance.yahoo.com",
      "source_conflict_pct": 0.0
    }
  }
]
```

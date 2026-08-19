# USPreferredStockDayInfo 每日情報報告

- 生成時間（台灣）：2026-08-19 08:22:55
- 對應 PDF：Stock_News_Report_20260819_082254.pdf
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

- 事件總分：正向3 / 負向5 / 總分-2
- 綜合分析：近期分析師下調目標價並質疑估值，儘管執行長增持股票展現信心，但市場對 Lumen Technologies 的短期展望仍趨於謹慎。
- 事件 1：2026-08-13｜Simply Wall St 評估 Lumen 股價，暗示營收超越後可能已充分定價｜recent_event
  - 影響：負向｜嚴重性：2｜信心度：中
  - 摘要：分析師基於DCF模型認為Lumen股價可能高估，並質疑自由現金流的持續性。
  - 來源：Simply Wall St
  - 日期過濾：kept_recent｜來源品質：secondary_site｜驗證：unverified
- 事件 2：2026-08-11｜花旗集團下調 Lumen Technologies 目標價｜recent_event
  - 影響：負向｜嚴重性：3｜信心度：中
  - 摘要：花旗將Lumen目標價從10美元下調至8.25美元，維持中性評級。
  - 來源：MarketBeat
  - 日期過濾：kept_recent｜來源品質：secondary_site｜驗證：unverified
- 事件 3：2026-08-06｜Lumen Technologies 執行長 Kathleen E. Johnson 增持公司股票｜recent_event
  - 影響：正向｜嚴重性：3｜信心度：高
  - 摘要：Lumen Technologies 執行長 Kathleen E. Johnson 透過信託增持10萬股公司股票，展現對公司前景的信心。
  - 來源：MarketBeat、SEC Filing、Stock Titan
  - 日期過濾：kept_recent｜來源品質：sec_filing｜驗證：verified

### 2. BHFAL

- 事件總分：正向2 / 負向6 / 總分-4
- 綜合分析：近期 Brighthouse Financial 面臨 Aquarian 收購案的會計疑慮及監管審查的負面展望，儘管公司宣布發放股息，但短期內仍受收購不確定性影響。
- 事件 1：2026-08-18｜AM Best 報導 Delaware 監管機構更新對 Brighthouse Financial 收購案的審查進度｜recent_event
  - 影響：負向｜嚴重性：3｜信心度：高
  - 摘要：Delaware 保險部門正審查 Brighthouse Life Insurance Co. 的收購案，AM Best 維持負面展望。
  - 來源：AM Best News
  - 日期過濾：kept_recent｜來源品質：rating_agency｜驗證：verified
- 事件 2：2026-08-18｜Brighthouse Financial 宣布發放優先股股息並任命新任首席會計長｜recent_event
  - 影響：正向｜嚴重性：2｜信心度：高
  - 摘要：公司宣布發放優先股股息，並任命 Richard A. Cook 為新任首席會計官，前任因新機會離職。
  - 來源：SEC Filing、Stock Titan、TradingView、Business Wire、Morningstar、Brighthouse Financial Investor Relations、Brighthouse Financial Investor Relations Newsroom、Investing.com、TipRanks.com
  - 日期過濾：kept_recent｜來源品質：sec_filing｜驗證：verified
- 事件 3：2026-08-07｜報告指出 Aquarian 收購 Brighthouse 案存會計疑慮，股價受壓｜recent_event
  - 影響：負向｜嚴重性：3｜信心度：中
  - 摘要：Seeking Alpha 引用 Capitol Forum 報告稱 Aquarian 收購案可能涉及會計問題，導致 Brighthouse 股價下跌。
  - 來源：Seeking Alpha
  - 日期過濾：kept_recent｜來源品質：secondary_site｜驗證：unverified

### 3. OPI

- 事件總分：正向0 / 負向3 / 總分-3
- 綜合分析：OPI 最近公布 Q2 財報與資產處置計畫以改善流動性，並聲明已消除持續經營疑慮，但大股東的減持行為對股價構成壓力。
- 事件 1：2026-08-13｜公司內部人士提交 Form 4 報告所有權變更｜recent_event
  - 影響：中性｜嚴重性：1｜信心度：高
  - 摘要：公司內部人士股票所有權變更已依規定提交 Form 4 文件，屬例行性申報。
  - 來源：MarketBeat、SEC Filing
  - 日期過濾：kept_recent｜來源品質：sec_filing｜驗證：verified
- 事件 2：2026-08-07｜大股東 Redwood Capital Management 出售 OPI 普通股並修正申報｜recent_event
  - 影響：負向｜嚴重性：3｜信心度：高
  - 摘要：Redwood Capital Management 基金於8月6日出售逾16萬股普通股，並計劃轉售100萬股，顯示大股東減持。
  - 來源：Stock Titan、SEC Filing、Finviz、MarketBeat、Seeking Alpha
  - 日期過濾：kept_recent｜來源品質：sec_filing｜驗證：verified
- 事件 3：2026-08-06｜OPI 公布 Q2 財報、提交 10-Q 並詳述資產處置計畫｜recent_event
  - 影響：中性｜嚴重性：4｜信心度：高
  - 摘要：公司提交 Q2 10-Q 報告，詳述債務重組成果、流動性管理與未來 32 處資產出售計畫，稱已消除持續經營疑慮。
  - 來源：SeekingAlpha、MarketScreener、EarningsCall.biz、Decode Investing、Alpha Spread、OPI Investor Relations、BusinessWire、GuruFocus、SEC Filing、Stock Titan
  - 日期過濾：kept_recent｜來源品質：sec_filing｜驗證：verified

### 4. AXS-E

- 事件總分：正向3 / 負向0 / 總分+3
- 綜合分析：AXIS Capital 優先股因其穩定收益和良好信用評級而受到分析師青睞，儘管普通股在第二季財報後表現不佳，顯示市場對不同股權類別的看法存在分歧。
- 事件 1：2026-08-17｜AXIS Capital 任命 John Kopach 為批發中低市場主管｜recent_event
  - 影響：中性｜嚴重性：2｜信心度：高
  - 摘要：AXIS Capital 任命 John Kopach 接替退休的 Britt Smith 擔任新職位，為內部管理層變動。
  - 來源：Simply Wall St News、AXIS Investor Relations
  - 日期過濾：kept_recent｜來源品質：official_ir｜驗證：verified
- 事件 2：2026-08-14｜分析師看好 AXS-E 優先股穩定收益與 BBB 評級，儘管普通股 Q2 財報後波動｜recent_event
  - 影響：正向｜嚴重性：3｜信心度：中
  - 摘要：多份報告指出 AXS-E 優先股具 BBB 評級與 QDI 股息資格，為尋求穩定收益投資者提供吸引力，儘管普通股 Q2 財報後營運 EPS 未達預期導致股價下跌。
  - 來源：Pluang、Perplexity、MarketBeat、Finsee、Reuters、Seeking Alpha、SeekingAlpha
  - 日期過濾：kept_recent｜來源品質：mainstream_media｜驗證：partially_verified

### 5. F-B

- 事件總分：正向12 / 負向11 / 總分+1
- 綜合分析：福特汽車近期利好與利空消息並存，包括推出平價電動皮卡、機構增持和分析師評級上調，但同時也面臨 Mach-E 和 Bronco 車型的召回事件以及整體汽車貸款拖欠率上升的行業風險。
- 事件 1：2026-08-18｜惠譽評定福特信貸新債券，機構投資者增持福特股票｜recent_event
  - 影響：正向｜嚴重性：2｜信心度：高
  - 摘要：惠譽評定福特信貸汽車信託2026-REV2債券，信用質量穩定，且 Buckland Partners Management 增持福特股票。
  - 來源：MarketBeat、Fitch、MarketScreener、Fitch Ratings
  - 日期過濾：kept_recent｜來源品質：rating_agency｜驗證：verified
- 事件 2：2026-08-17｜福特 Mach-E SUV 因車窗脫落風險召回｜recent_event
  - 影響：負向｜嚴重性：4｜信心度：高
  - 摘要：福特召回8.6萬輛 Mach-E，因供應商組裝問題恐致車窗脫落，影響公司聲譽。
  - 來源：Kelley Blue Book
  - 日期過濾：kept_recent｜來源品質：unknown｜驗證：unverified
- 事件 3：2026-08-17｜華爾街日報報導 AI 數據中心帶動美國製造業繁榮，福特調整業務方向，Q2 財報後分析師仍看好｜recent_event
  - 影響：正向｜嚴重性：3｜信心度：高
  - 摘要：華爾街日報稱 AI 數據中心助美製造業繁榮，福特把握機會，儘管 Q2 財報後股價表現落後通用，分析師仍看好其 Pro 與 EV 策略。
  - 來源：WSJ、The Winona Times、Zacks Investment Research
  - 日期過濾：kept_recent｜來源品質：mainstream_media｜驗證：partially_verified
- 事件 4：2026-08-13｜福特計劃將部分林肯車型生產從中國遷至美國，DBS 銀行上調福特評級｜recent_event
  - 影響：正向｜嚴重性：3｜信心度：高
  - 摘要：福特 CEO 表示，計劃自2030年起將部分林肯車型生產從中國遷至美國以應對關稅；DBS 銀行也將福特股票評級上調至「適度買入」。
  - 來源：Reuters、Seeking Alpha、CBC、Benzinga、AutoGuide.com、SeekingAlpha、MarketBeat、Zacks.com
  - 日期過濾：kept_recent｜來源品質：mainstream_media｜驗證：partially_verified
- 事件 5：2026-08-12｜美國汽車貸款拖欠率達15年新高｜recent_event
  - 影響：負向｜嚴重性：3｜信心度：中
  - 摘要：紐約聯準會數據顯示第二季度汽車貸款拖欠率創15年新高，可能對福特信貸業務造成負面影響。
  - 來源：CBT News
  - 日期過濾：kept_recent｜來源品質：unknown｜驗證：unverified
- 事件 6：2026-08-07｜福特推出售價約2.8萬美元的新款 Fathom 電動皮卡｜recent_event
  - 影響：正向｜嚴重性：4｜信心度：高
  - 摘要：福特宣布推出 Fathom 中型電動皮卡，定價28,350美元，預計2027年底交付，瞄準平價 EV 市場。
  - 來源：Ground News、Seeking Alpha、DBusiness Magazine
  - 日期過濾：kept_recent｜來源品質：secondary_site｜驗證：unverified
- 事件 7：2026-08-06｜福特 Bronco 與 Bronco Raptor 引擎線束短路召回，Zacks 上調評級｜recent_event
  - 影響：負向｜嚴重性：4｜信心度：高
  - 摘要：福特召回56萬餘輛 Bronco，因引擎線束短路恐致火災風險；Zacks 仍將福特汽車評級上調至「買入」。
  - 來源：CarBuzz、CBS News、Zacks Investment Research
  - 日期過濾：kept_recent｜來源品質：secondary_site｜驗證：unverified

### 6. UZD

- 事件總分：正向0 / 負向0 / 總分+0
- 綜合分析：TDS 對 Array Digital Infrastructure 提出收購剩餘股權的提案，而 Array 的第二季財報顯示營收顯著增長並提升財測，但母公司 TDS 的整體自由現金流仍為負。
- 事件 1：2026-08-09｜TDS 及 Array Digital Infrastructure 公布 Q2 財報，Array 提升全年財測並報告頻譜出售收益｜recent_event
  - 影響：中性｜嚴重性：4｜信心度：高
  - 摘要：Array Q2 營收大增90%，得益於頻譜銷售及租賃增長，並提升2026年財測，但 TDS 整體自由現金流仍為負。
  - 來源：TDS Investor Relations、Array Digital Infrastructure Investor Relations、PR Newswire、SEC Filing、Seeking Alpha、Stockwatch、TradingKey、UScellular Investor Relations、Bloomberg
  - 日期過濾：kept_recent｜來源品質：sec_filing｜驗證：verified
- 事件 2：2026-08-07｜TDS 對 Array Digital Infrastructure 提出收購剩餘股權的非約束性提案｜recent_event
  - 影響：中性｜嚴重性：2｜信心度：高
  - 摘要：TDS 提議收購其尚未擁有的 Array Digital Infrastructure 所有普通股，目前正由獨立委員會評估。
  - 來源：TDS Investor Relations、Array Digital Infrastructure Investor Relations、SEC Filing、TradingKey
  - 日期過濾：kept_recent｜來源品質：sec_filing｜驗證：verified

## 量化指標與資料缺口

- 量化監控框架版本：1.0
- 說明：v1 先建立每檔應追蹤指標與資料缺口；尚未取得官方數值時，會標示為「資料不足」。

### CTGG 量化監控
- Free cash flow｜狀態：已取得｜驗證：partially_verified｜來源品質：official_ir｜期間新鮮度：fresh｜門檻：FCF 轉負或展望下修需警戒。
- Debt maturity and exchange offer terms｜狀態：已取得｜驗證：partially_verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：distressed exchange、順位弱化或擔保改變需警戒。
- Credit rating / outlook｜狀態：已取得｜驗證：partially_verified｜來源品質：rating_agency｜期間新鮮度：fresh｜門檻：downgrade、negative outlook 或 selective default 評論需警戒。
- 資料缺口：4 項，關鍵資料缺漏時不可判定為綠燈。

### BHFAL 量化監控
- RBC ratio｜狀態：已取得｜驗證：partially_verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：低於 400% 黃燈；低於 350% 橙燈/紅燈；單季大幅下滑需警戒。
- Statutory capital and surplus｜狀態：已取得｜驗證：partially_verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：連續下降或重大減損需警戒。
- Holding company cash and liquid assets｜狀態：已取得｜驗證：partially_verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：低於未來 12 個月利息與固定支出覆蓋需求需警戒。
- Financial leverage｜狀態：資料不足｜驗證：data_missing｜來源品質：unknown｜期間新鮮度：fresh｜門檻：槓桿升高或評等機構負面評論需警戒。
- Credit rating / outlook｜狀態：已取得｜驗證：verified｜來源品質：rating_agency｜期間新鮮度：fresh｜門檻：negative outlook、downgrade 或 watch negative 需警戒。
- BHFAL interest payment status｜狀態：已取得｜驗證：partially_verified｜來源品質：official_ir｜期間新鮮度：fresh｜門檻：defer、suspend、delay、non-payment 立即紅燈。
- Aquarian merger / change-of-control treatment｜狀態：已取得｜驗證：partially_verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：未明確說明 BHFAL 存續、掛牌、贖回或付息條款時列資料不足。
- 資料缺口：5 項，關鍵資料缺漏時不可判定為綠燈。

### OPI 量化監控
- Occupancy rate｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：連續下降或低於同業顯著水準需警戒。
- AFFO / FFO｜狀態：已取得｜驗證：partially_verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：AFFO/FFO 大幅下滑或為負需警戒。
- Debt maturity schedule｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：12-24 個月內大量到期且流動性不足需紅燈。
- Liquidity / cash availability｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：流動性不足或 covenant 壓力需警戒。
- AFFO / FFO (Successor Period)｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：AFFO/FFO 大幅下滑或為負需警戒。
- AFFO / FFO (Predecessor Period)｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：AFFO/FFO 大幅下滑或為負需警戒。
- 資料缺口：1 項，關鍵資料缺漏時不可判定為綠燈。

### AXS-E 量化監控
- Combined ratio｜狀態：已取得｜驗證：partially_verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：高於 100% 或明顯惡化需警戒。
- Catastrophe losses｜狀態：已取得｜驗證：partially_verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：重大巨災損失超預期需警戒。
- Preferred dividend status｜狀態：已取得｜驗證：verified｜來源品質：official_ir｜期間新鮮度：fresh｜門檻：defer、suspend、delay 立即紅燈。
- 資料缺口：1 項，關鍵資料缺漏時不可判定為綠燈。

### F-B 量化監控
- Industrial free cash flow｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：FCF 轉負或全年指引大幅下修需警戒。
- Ford Credit delinquencies / credit losses｜狀態：資料不足｜驗證：data_missing｜來源品質：unknown｜期間新鮮度：unknown_period｜門檻：逾期率或信用損失準備明顯上升需警戒。
- Recall / warranty cost｜狀態：資料不足｜驗證：data_missing｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：重大召回或保固成本升高需警戒。
- 資料缺口：4 項，關鍵資料缺漏時不可判定為綠燈。

### UZD 量化監控
- Issuer / guarantor status｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：發行人或擔保人不明確時列灰燈/黃燈，不可判定安全。
- Asset sale proceeds and use of funds｜狀態：已取得｜驗證：partially_verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：出售所得若大量分配給股東而非減債需警戒。
- Debt assumption / redemption status｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：未說明承擔、契約修改或贖回時列資料不足。
- 資料缺口：1 項，關鍵資料缺漏時不可判定為綠燈。

## 程式端日期過濾與來源驗證

- 日期過濾版本：1.2.2
- 最近事件保留天數：14 天
- 說明：超出最近 14 日但命中 Chapter 11、收購、重整、退市、債務交換等重大關鍵字者，會保留為 background_risk_event；其他舊事件移至 dropped_old_events。

- CTGG：recent=3，background=0，unknown_date=0，dropped_old=0
- BHFAL：recent=3，background=0，unknown_date=0，dropped_old=0
- OPI：recent=3，background=0，unknown_date=0，dropped_old=0
- AXS-E：recent=2，background=0，unknown_date=0，dropped_old=0
- F-B：recent=7，background=0，unknown_date=0，dropped_old=0
- UZD：recent=2，background=0，unknown_date=0，dropped_old=0

## 完整 JSON

```json
[
  {
    "target_name": "CTGG",
    "events": [
      {
        "date": "2026-08-13",
        "title": "Simply Wall St 評估 Lumen 股價，暗示營收超越後可能已充分定價",
        "impact_direction": "負向",
        "impact_severity": 2,
        "confidence": "中",
        "summary_30": "分析師基於DCF模型認為Lumen股價可能高估，並質疑自由現金流的持續性。",
        "links": [
          "Simply Wall St"
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
      },
      {
        "date": "2026-08-11",
        "title": "花旗集團下調 Lumen Technologies 目標價",
        "impact_direction": "負向",
        "impact_severity": 3,
        "confidence": "中",
        "summary_30": "花旗將Lumen目標價從10美元下調至8.25美元，維持中性評級。",
        "links": [
          "MarketBeat"
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
        "date": "2026-08-06",
        "title": "Lumen Technologies 執行長 Kathleen E. Johnson 增持公司股票",
        "impact_direction": "正向",
        "impact_severity": 3,
        "confidence": "高",
        "summary_30": "Lumen Technologies 執行長 Kathleen E. Johnson 透過信託增持10萬股公司股票，展現對公司前景的信心。",
        "links": [
          "MarketBeat",
          "SEC Filing",
          "Stock Titan"
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
    "綜合分析": "近期分析師下調目標價並質疑估值，儘管執行長增持股票展現信心，但市場對 Lumen Technologies 的短期展望仍趨於謹慎。",
    "事件總分": "正向3 / 負向5 / 總分-2",
    "new_sources_found": [
      "Simply Wall St",
      "MarketBeat",
      "Stock Titan"
    ],
    "event_merge_source": "ai_stage2",
    "metric_data": [
      {
        "ticker": "CTGG",
        "metric_name": "Free cash flow",
        "metric_category": "現金流",
        "value": "327",
        "unit": "USD",
        "period": "2026Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "Lumen Technologies Q2 2026 Earnings Release",
        "source_url_or_name": "BusinessWire / Lumen Investor Relations",
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
        "note": "排除特殊項目後的自由現金流。公司重申2026年全年自由現金流指引為19-21億美元（不含特殊項目）。",
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
        "metric_consistency_reason": "同 period / definition 前值=327 百萬，本次=327；區間不重疊。",
        "metric_consistency_missing_type": "metric_value",
        "cross_run_consistency_status": "value_changed_same_definition",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "327 百萬",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260818",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 前值=327 百萬，本次=327；區間不重疊。"
      },
      {
        "ticker": "CTGG",
        "metric_name": "Debt maturity and exchange offer terms",
        "metric_category": "債務結構",
        "value": "已完成",
        "unit": "status/date/USD",
        "period": "2026-06-10",
        "status": "已取得",
        "confidence": "高",
        "source": "Lumen Technologies Press Release / SEC Filing",
        "source_url_or_name": "Investing.com / Stock Titan / MarketScreener",
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
        "note": "Qwest Corporation 已於2026年6月10日完成債務交換要約，將現有票據交換為由 Lumen Technologies 全額擔保的新票據。本次標的 CTGG (6.500% Senior Notes due 2051) 為該交換要約中發行的新票據之一，總計發行14億美元新Qwest票據。",
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
        "metric_period_parsed_date": "2026-06-10",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "date",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "partially_verified",
        "metric_consistency_status": "conflict_with_missing_data",
        "metric_consistency_reason": "在指定日期範圍（最近 14 日內）未發現與 Qwest Corporation 或 Lumen Technologies 債務結構或新的債務交換要約相關的官方消息。最近的總體債務數據來自 Q2 2026 財報，其發布日期（8月4日）超出範圍。",
        "metric_consistency_missing_type": "metric_value",
        "cross_run_consistency_status": "not_comparable",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "Qwest Corp. 6.500% Senior Notes due 2051",
        "cross_run_previous_period": "2026-06-10",
        "cross_run_previous_report_date": "20260811",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 有前值，但數值型態無法安全比較。"
      },
      {
        "ticker": "CTGG",
        "metric_name": "Credit rating / outlook",
        "metric_category": "信用評等",
        "value": "B (Fitch); B2 (Moody's CFR); B (S&P for Qwest notes)",
        "unit": "rating",
        "period": "2026年2月-4月",
        "status": "已取得",
        "confidence": "高",
        "source": "Fitch Ratings / Moody's Ratings / S&P Global Ratings",
        "source_url_or_name": "Fitch Ratings / Moody's Ratings / S&P Global Ratings",
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
        "note": "Fitch 於2026年2月9日將 Lumen, Level 3 及 Qwest 的 IDR 上調至 'B'，展望穩定。Moody's 於2026年2月20日將 Lumen 的 CFR 上調至 B2，Qwest 的高級無擔保票據上調至 Caa1，展望穩定。S&P 於2026年3月5日將 Lumen 展望修正為 '正面'，並於2026年4月27日對 Qwest 的新票據給予 'B' 評級及 '2' 的回收評級。",
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
        "metric_period_parsed_date": "2026-04-30",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "month_or_month_range",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "partially_verified",
        "metric_consistency_status": "conflict_with_missing_data",
        "metric_consistency_reason": "在指定日期範圍（最近 14 日內）未發現最新的官方或評級機構的信用評等更新。",
        "metric_consistency_missing_type": "metric_value",
        "cross_run_consistency_status": "not_comparable",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "穆迪 (Moody's) 企業家族評級 (CFR): B2 (展望穩定)；標普 (S&P) 發行人信用評級: B-，高級無擔保債務評級: B；惠譽 (Fitch) 發行人違約評級 (IDR): B (展望穩定)。",
        "cross_run_previous_period": "2026年2月-4月 (上次評級行動)",
        "cross_run_previous_report_date": "20260818",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 有前值，但數值型態無法安全比較。"
      }
    ],
    "missing_data": [
      {
        "ticker": "CTGG",
        "priority": "P0",
        "missing_type": "metric_consistency",
        "metric_name": "Free cash flow",
        "reason": "最新的 Q2 2026 自由現金流官方數值來自 2026 年 8 月 4 日的財報，該發布日期（8月4日）超出本次搜尋的最近 14 日內（8月5日至8月19日）範圍。",
        "risk_impact": "缺乏最新的自由現金流官方數據，影響對公司現金產生能力及長債償付風險的評估。",
        "source_candidates": [
          "Lumen Investor Relations",
          "SEC 10-Q"
        ],
        "acceptance_criteria": "下次需填入 value、period、source，且來源發布日期須在指定範圍內；若查無，需說明查詢過哪些來源。",
        "missing_type_original": "metric_value",
        "conflict_with_metric_data": true,
        "metric_value_present": "327",
        "metric_source_present": "Lumen Technologies Q2 2026 Earnings Release",
        "metric_verification_after_reconcile": "partially_verified"
      },
      {
        "ticker": "CTGG",
        "priority": "P0",
        "missing_type": "metric_consistency",
        "metric_name": "Debt maturity and exchange offer terms",
        "reason": "在指定日期範圍（最近 14 日內）未發現與 Qwest Corporation 或 Lumen Technologies 債務結構或新的債務交換要約相關的官方消息。最近的總體債務數據來自 Q2 2026 財報，其發布日期（8月4日）超出範圍。",
        "risk_impact": "缺乏最新的債務結構或交換要約資訊，可能無法全面評估 CTGG 債權保護的潛在變化。",
        "source_candidates": [
          "Lumen Investor Relations",
          "SEC 8-K",
          "Exchange offer documents"
        ],
        "acceptance_criteria": "下次需填入相關債務總額、到期日或交換要約細節，且來源發布日期須在指定範圍內；若查無，需說明查詢過哪些來源。",
        "missing_type_original": "metric_value",
        "conflict_with_metric_data": true,
        "metric_value_present": "已完成",
        "metric_source_present": "Lumen Technologies Press Release / SEC Filing",
        "metric_verification_after_reconcile": "partially_verified"
      },
      {
        "ticker": "CTGG",
        "priority": "P0",
        "missing_type": "metric_consistency",
        "metric_name": "Credit rating / outlook",
        "reason": "在指定日期範圍（最近 14 日內）未發現最新的官方或評級機構的信用評等更新。",
        "risk_impact": "缺乏最新的信評更新，可能無法即時反映公司信用狀況變化對債券流動性與再融資能力的影響。",
        "source_candidates": [
          "S&P",
          "Moody's",
          "Fitch",
          "Lumen Investor Relations"
        ],
        "acceptance_criteria": "下次需填入最近的評等更新日期、等級與展望；若查無，需說明查詢過哪些來源。",
        "missing_type_original": "metric_value",
        "conflict_with_metric_data": true,
        "metric_value_present": "B (Fitch); B2 (Moody's CFR); B (S&P for Qwest notes)",
        "metric_source_present": "Fitch Ratings / Moody's Ratings / S&P Global Ratings",
        "metric_verification_after_reconcile": "partially_verified"
      },
      {
        "ticker": "CTGG",
        "priority": "P0",
        "missing_type": "metric_cross_run_consistency",
        "metric_name": "Free cash flow",
        "reason": "同 period / definition 前值=327 百萬，本次=327；區間不重疊。",
        "risk_impact": "自由現金流不足會影響長債償付能力。",
        "previous_value": "327 百萬",
        "current_value": "327",
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
      "cutoff_date": "2026-08-06",
      "today": "2026-08-19",
      "kept_recent": 3,
      "kept_background": 0,
      "kept_unknown_date": 0,
      "dropped_old": 0
    },
    "metric_consistency_summary": {
      "conflict_count": 3,
      "conflicts": [
        {
          "ticker": "CTGG",
          "metric_name": "Free cash flow",
          "metric_value": "327",
          "missing_reason": "同 period / definition 前值=327 百萬，本次=327；區間不重疊。",
          "verification_after_reconcile": "partially_verified",
          "cross_run_consistency_status": "value_changed_same_definition",
          "definition_scope": "",
          "calculation_basis": ""
        },
        {
          "ticker": "CTGG",
          "metric_name": "Debt maturity and exchange offer terms",
          "metric_value": "已完成",
          "missing_reason": "在指定日期範圍（最近 14 日內）未發現與 Qwest Corporation 或 Lumen Technologies 債務結構或新的債務交換要約相關的官方消息。最近的總體債務數據來自 Q2 2026 財報，其發布日期（8月4日）超出範圍。",
          "verification_after_reconcile": "partially_verified",
          "cross_run_consistency_status": "not_comparable",
          "definition_scope": "",
          "calculation_basis": ""
        },
        {
          "ticker": "CTGG",
          "metric_name": "Credit rating / outlook",
          "metric_value": "B (Fitch); B2 (Moody's CFR); B (S&P for Qwest notes)",
          "missing_reason": "在指定日期範圍（最近 14 日內）未發現最新的官方或評級機構的信用評等更新。",
          "verification_after_reconcile": "partially_verified",
          "cross_run_consistency_status": "not_comparable",
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
    "events": [
      {
        "date": "2026-08-18",
        "title": "AM Best 報導 Delaware 監管機構更新對 Brighthouse Financial 收購案的審查進度",
        "impact_direction": "負向",
        "impact_severity": 3,
        "confidence": "高",
        "summary_30": "Delaware 保險部門正審查 Brighthouse Life Insurance Co. 的收購案，AM Best 維持負面展望。",
        "links": [
          "AM Best News"
        ],
        "event_source_quality": "rating_agency",
        "event_source_quality_details": [
          "rating_agency"
        ],
        "event_verification_status": "verified",
        "event_days_old": 1,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event",
        "merged_duplicate_count": 1
      },
      {
        "date": "2026-08-18",
        "title": "Brighthouse Financial 宣布發放優先股股息並任命新任首席會計長",
        "impact_direction": "正向",
        "impact_severity": 2,
        "confidence": "高",
        "summary_30": "公司宣布發放優先股股息，並任命 Richard A. Cook 為新任首席會計官，前任因新機會離職。",
        "links": [
          "SEC Filing",
          "Stock Titan",
          "TradingView",
          "Business Wire",
          "Morningstar",
          "Brighthouse Financial Investor Relations",
          "Brighthouse Financial Investor Relations Newsroom",
          "Investing.com",
          "TipRanks.com"
        ],
        "event_source_quality": "sec_filing",
        "event_source_quality_details": [
          "sec_filing",
          "official_ir",
          "press_release",
          "secondary_site"
        ],
        "event_verification_status": "verified",
        "event_days_old": 1,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event",
        "merged_duplicate_count": 1
      },
      {
        "date": "2026-08-07",
        "title": "報告指出 Aquarian 收購 Brighthouse 案存會計疑慮，股價受壓",
        "impact_direction": "負向",
        "impact_severity": 3,
        "confidence": "中",
        "summary_30": "Seeking Alpha 引用 Capitol Forum 報告稱 Aquarian 收購案可能涉及會計問題，導致 Brighthouse 股價下跌。",
        "links": [
          "Seeking Alpha"
        ],
        "event_source_quality": "secondary_site",
        "event_source_quality_details": [
          "secondary_site"
        ],
        "event_verification_status": "unverified",
        "event_days_old": 12,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event",
        "merged_duplicate_count": 1
      }
    ],
    "綜合分析": "近期 Brighthouse Financial 面臨 Aquarian 收購案的會計疑慮及監管審查的負面展望，儘管公司宣布發放股息，但短期內仍受收購不確定性影響。",
    "事件總分": "正向2 / 負向6 / 總分-4",
    "new_sources_found": [
      "AM Best News",
      "Stock Titan",
      "TradingView",
      "Morningstar",
      "Brighthouse Financial Investor Relations",
      "Brighthouse Financial Investor Relations Newsroom",
      "Investing.com",
      "TipRanks.com"
    ],
    "event_merge_source": "ai_stage2",
    "metric_data": [
      {
        "ticker": "BHFAL",
        "metric_name": "RBC ratio",
        "metric_category": "保險償付能力",
        "value": "430%",
        "unit": "%",
        "period": "2026Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "Brighthouse Financial 10-Q / Earnings Supplement",
        "source_url_or_name": "Brighthouse Financial Business Wire",
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
        "note": "初步估計的合併風險資本比率，截至2026年6月30日。",
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
        "metric_verification_status": "partially_verified",
        "definition_scope": "Brighthouse insurance subsidiaries (combined)",
        "calculation_basis": "NAIC combined risk-based capital ratio",
        "measurement_form": "point",
        "source_period_alignment_status": "no_q1_fingerprint_match",
        "metric_consistency_status": "cross_run_conflict",
        "metric_consistency_reason": "同 period / definition 前值=445%，本次=430%；區間不重疊。",
        "cross_run_consistency_status": "value_changed_same_definition",
        "cross_run_previous_value": "445%",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260818",
        "cross_run_previous_definition_scope": "Brighthouse insurance subsidiaries (combined)",
        "cross_run_previous_calculation_basis": "NAIC combined risk-based capital ratio",
        "cross_run_consistency_reason": "同 period / definition 前值=445%，本次=430%；區間不重疊。"
      },
      {
        "ticker": "BHFAL",
        "metric_name": "Statutory capital and surplus",
        "metric_category": "法定資本",
        "value": "$9.0 billion",
        "unit": "USD",
        "period": "2026Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "Brighthouse Financial 10-Q",
        "source_url_or_name": "Brighthouse Financial Business Wire / OTC Markets",
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
        "note": "指扣除累計其他綜合收益 (AOCI) 的普通股股東權益，截至2026年6月30日。",
        "source_quality_primary": "sec_filing",
        "source_quality": "sec_filing",
        "source_quality_details": [
          "sec_filing",
          "exchange_notice",
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
        "metric_consistency_reason": "同 period / definition 前值=6.8 billion，本次=$9.0 billion；區間不重疊。",
        "cross_run_consistency_status": "value_changed_same_definition",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "6.8 billion",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260818",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 前值=6.8 billion，本次=$9.0 billion；區間不重疊。"
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
        "source": "Brighthouse Financial Earnings Supplement / 10-Q",
        "source_url_or_name": "Brighthouse Financial Business Wire / Morningstar",
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
        "note": "截至2026年6月30日。",
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
        "metric_verification_status": "partially_verified",
        "definition_scope": "Brighthouse holding company group",
        "calculation_basis": "holding company liquid assets",
        "measurement_form": "point",
        "source_period_alignment_status": "q2_asof_evidence_present",
        "source_period_evidence": "Brighthouse Financial Earnings Supplement / 10-Q | Brighthouse Financial Business Wire / Morningstar | 截至2026年6月30日。",
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
        "note": "2026年第二季度財報摘要中未明確提供此項量化指標的直接數值。",
        "semantic_match_status": "未匹配",
        "rejected_candidate_reason": "財報摘要中未直接揭露特定槓桿比率（如債務/EBITDA）",
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
        "value": "bbb- (次順位債務) / Under Review with Negative Implications",
        "unit": "rating",
        "period": "2026-07-29",
        "status": "已取得",
        "confidence": "高",
        "source": "AM Best",
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
        "warning_threshold": "negative outlook、downgrade 或 watch negative 需警戒。",
        "priority": "P0",
        "risk_impact": "評等惡化可能領先價格與流動性壓力。",
        "note": "AM Best維持Brighthouse Financial次順位債務「bbb-」評級，展望仍為「接受審查並具負面影響」，主要因Aquarian收購案的監管審查仍在進行。",
        "definition_scope": "Junior Subordinated Debt",
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
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "definition_changed",
        "calculation_basis": "",
        "cross_run_previous_value": "bbb-",
        "cross_run_previous_period": "2026-07-29",
        "cross_run_previous_report_date": "20260810",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period 有前值，但 definition_scope / calculation_basis 不同，不互相覆寫。"
      },
      {
        "ticker": "BHFAL",
        "metric_name": "BHFAL interest payment status",
        "metric_category": "付息狀態",
        "value": "已支付 (預期正常支付)",
        "unit": "status",
        "period": "2026Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "Brighthouse Financial Investor Relations / Lack of contrary news",
        "source_url_or_name": "Brighthouse Financial Business Wire / QuantumOnline.com",
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
        "note": "BHFAL的季度付息日為3/15、6/15、9/15、12/15。最近的6/15支付已完成，當前財務狀況支持未來支付。",
        "source_quality_primary": "official_ir",
        "source_quality": "official_ir",
        "source_quality_details": [
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
        "cross_run_consistency_status": "not_comparable",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "正常支付",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260818",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 有前值，但數值型態無法安全比較。"
      },
      {
        "ticker": "BHFAL",
        "metric_name": "Aquarian merger / change-of-control treatment",
        "metric_category": "交易條款",
        "value": "已獲股東批准，次順位債務將維持未償付義務",
        "unit": "status",
        "period": "2026Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "Brighthouse Financial Q2 2026 Earnings Release / SEC Filing (Form 10-Q) / Aquarian Capital LLC",
        "source_url_or_name": "Business Wire, SEC Filing, Aquarian Capital LLC",
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
        "note": "股東已於2026年2月批准收購案，交易預計於2026年完成，仍待監管批准。收購協議明確指出，次順位債務在交易完成後仍為Brighthouse Financial的未償付義務。",
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
        "metric_verification_status": "partially_verified",
        "metric_consistency_status": "conflict_with_missing_data",
        "metric_consistency_reason": "本次搜尋未找到官方明確說明BHFAL次順位債在Aquarian併購案完成後的具體處理條款（如存續、掛牌、贖回或付息條款）。",
        "metric_consistency_missing_type": "metric_value",
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
        "missing_type": "metric_consistency",
        "metric_name": "Aquarian merger / change-of-control treatment",
        "reason": "本次搜尋未找到官方明確說明BHFAL次順位債在Aquarian併購案完成後的具體處理條款（如存續、掛牌、贖回或付息條款）。",
        "risk_impact": "併購案完成後可能影響BHFAL的掛牌、流動性與資本政策，具體條款不明確會增加投資不確定性。",
        "source_candidates": [
          "Brighthouse Financial Investor Relations",
          "SEC 8-K filings (關於併購案終止條款或債務處理)",
          "併購協議相關文件"
        ],
        "acceptance_criteria": "下次需填入 value、period、source；若查無，需說明查詢過哪些來源",
        "missing_type_original": "metric_value",
        "conflict_with_metric_data": true,
        "metric_value_present": "已獲股東批准，次順位債務將維持未償付義務",
        "metric_source_present": "Brighthouse Financial Q2 2026 Earnings Release / SEC Filing (Form 10-Q) / Aquarian Capital LLC",
        "metric_verification_after_reconcile": "partially_verified"
      },
      {
        "ticker": "BHFAL",
        "priority": "P0",
        "missing_type": "metric_cross_run_consistency",
        "metric_name": "RBC ratio",
        "reason": "同 period / definition 前值=445%，本次=430%；區間不重疊。",
        "risk_impact": "RBC 下滑可能代表保險子公司資本緩衝下降，影響次順位債付息與信用評等。",
        "previous_value": "445%",
        "current_value": "430%",
        "period": "2026Q2",
        "definition_scope": "Brighthouse insurance subsidiaries (combined)",
        "calculation_basis": "NAIC combined risk-based capital ratio",
        "acceptance_criteria": "以同一官方定義重新查核；若為不同口徑，改填不同 definition_scope / calculation_basis，不得覆寫。"
      },
      {
        "ticker": "BHFAL",
        "priority": "P0",
        "missing_type": "metric_cross_run_consistency",
        "metric_name": "Statutory capital and surplus",
        "reason": "同 period / definition 前值=6.8 billion，本次=$9.0 billion；區間不重疊。",
        "risk_impact": "法定資本下降會削弱保險子公司分派能力與控股公司資金來源。",
        "previous_value": "6.8 billion",
        "current_value": "$9.0 billion",
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
      "cutoff_date": "2026-08-06",
      "today": "2026-08-19",
      "kept_recent": 3,
      "kept_background": 0,
      "kept_unknown_date": 0,
      "dropped_old": 0
    },
    "metric_consistency_summary": {
      "conflict_count": 4,
      "conflicts": [
        {
          "ticker": "BHFAL",
          "metric_name": "RBC ratio",
          "metric_value": "430%",
          "missing_reason": "同 period / definition 前值=445%，本次=430%；區間不重疊。",
          "verification_after_reconcile": "partially_verified",
          "cross_run_consistency_status": "value_changed_same_definition",
          "definition_scope": "Brighthouse insurance subsidiaries (combined)",
          "calculation_basis": "NAIC combined risk-based capital ratio"
        },
        {
          "ticker": "BHFAL",
          "metric_name": "Statutory capital and surplus",
          "metric_value": "$9.0 billion",
          "missing_reason": "同 period / definition 前值=6.8 billion，本次=$9.0 billion；區間不重疊。",
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
        },
        {
          "ticker": "BHFAL",
          "metric_name": "Aquarian merger / change-of-control treatment",
          "metric_value": "已獲股東批准，次順位債務將維持未償付義務",
          "missing_reason": "本次搜尋未找到官方明確說明BHFAL次順位債在Aquarian併購案完成後的具體處理條款（如存續、掛牌、贖回或付息條款）。",
          "verification_after_reconcile": "partially_verified",
          "cross_run_consistency_status": "no_prior_same_period",
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
    "target_name": "OPI",
    "events": [
      {
        "date": "2026-08-13",
        "title": "公司內部人士提交 Form 4 報告所有權變更",
        "impact_direction": "中性",
        "impact_severity": 1,
        "confidence": "高",
        "summary_30": "公司內部人士股票所有權變更已依規定提交 Form 4 文件，屬例行性申報。",
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
        "event_days_old": 6,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event",
        "merged_duplicate_count": 1
      },
      {
        "date": "2026-08-07",
        "title": "大股東 Redwood Capital Management 出售 OPI 普通股並修正申報",
        "impact_direction": "負向",
        "impact_severity": 3,
        "confidence": "高",
        "summary_30": "Redwood Capital Management 基金於8月6日出售逾16萬股普通股，並計劃轉售100萬股，顯示大股東減持。",
        "links": [
          "Stock Titan",
          "SEC Filing",
          "Finviz",
          "MarketBeat",
          "Seeking Alpha"
        ],
        "event_source_quality": "sec_filing",
        "event_source_quality_details": [
          "sec_filing",
          "secondary_site"
        ],
        "event_verification_status": "verified",
        "event_days_old": 12,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event",
        "merged_duplicate_count": 1
      },
      {
        "date": "2026-08-06",
        "title": "OPI 公布 Q2 財報、提交 10-Q 並詳述資產處置計畫",
        "impact_direction": "中性",
        "impact_severity": 4,
        "confidence": "高",
        "summary_30": "公司提交 Q2 10-Q 報告，詳述債務重組成果、流動性管理與未來 32 處資產出售計畫，稱已消除持續經營疑慮。",
        "links": [
          "SeekingAlpha",
          "MarketScreener",
          "EarningsCall.biz",
          "Decode Investing",
          "Alpha Spread",
          "OPI Investor Relations",
          "BusinessWire",
          "GuruFocus",
          "SEC Filing",
          "Stock Titan"
        ],
        "event_source_quality": "sec_filing",
        "event_source_quality_details": [
          "sec_filing",
          "official_ir",
          "press_release",
          "secondary_site"
        ],
        "event_verification_status": "verified",
        "event_days_old": 13,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event",
        "merged_duplicate_count": 1
      }
    ],
    "綜合分析": "OPI 最近公布 Q2 財報與資產處置計畫以改善流動性，並聲明已消除持續經營疑慮，但大股東的減持行為對股價構成壓力。",
    "事件總分": "正向0 / 負向3 / 總分-3",
    "new_sources_found": [
      "MarketBeat",
      "Stock Titan",
      "Finviz",
      "MarketScreener",
      "EarningsCall.biz",
      "Decode Investing",
      "Alpha Spread",
      "OPI Investor Relations",
      "GuruFocus"
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
        "source": "OPI Q2 2026 Earnings Release / SEC 8-K",
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
        "note": "截至2026年6月30日，整體投資組合出租率；同物業投資組合出租率為88.7%。",
        "source_quality_primary": "sec_filing",
        "source_quality": "sec_filing",
        "source_quality_details": [
          "sec_filing",
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
        "cross_run_previous_value": "77.9",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260818",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 數值表達不同，但目前值落在前一可信區間內。"
      },
      {
        "ticker": "OPI",
        "metric_name": "AFFO / FFO",
        "metric_category": "現金流",
        "value": "19 百萬美元",
        "unit": "USD",
        "period": "2026Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "OPI Q2 2026 Earnings Call Transcript / SEC 8-K",
        "source_url_or_name": "OPI Investor Relations",
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
        "note": "採用包含Predecessor (4/1-6/17) 及 Successor (6/18-6/30) 期間的綜合Normalized FFO。單獨Successor期間Normalized FFO為4.5百萬美元。",
        "source_quality_primary": "sec_filing",
        "source_quality": "sec_filing",
        "source_quality_details": [
          "sec_filing",
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
        "metric_consistency_reason": "同 period / definition 前值=19.0，本次=19 百萬美元；區間不重疊。",
        "cross_run_consistency_status": "value_changed_same_definition",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "19.0",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260818",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 前值=19.0，本次=19 百萬美元；區間不重疊。"
      },
      {
        "ticker": "OPI",
        "metric_name": "Debt maturity schedule",
        "metric_category": "債務到期牆",
        "value": "見摘要",
        "unit": "USD/date",
        "period": "截至 2026 年 6 月 30 日",
        "status": "已取得",
        "confidence": "高",
        "source": "OPI Q2 2026 Earnings Presentation / SEC 10-Q",
        "source_url_or_name": "OPI Investor Relations",
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
        "note": "總債務17億美元。4.25億美元循環信貸額度於2027年1月29日到期。2029年票據需在2026年11月1日前償還15百萬美元，2027年2月1日前償還30百萬美元。",
        "source_quality_primary": "sec_filing",
        "source_quality": "sec_filing",
        "source_quality_details": [
          "sec_filing",
          "official_ir"
        ],
        "source_candidate_quality_details": [
          "sec_filing",
          "official_ir",
          "court_docket"
        ],
        "source_conflict_flag": false,
        "source_conflict_reason": "",
        "metric_period_parsed_date": "2026-08-19",
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
        "ticker": "OPI",
        "metric_name": "Liquidity / cash availability",
        "metric_category": "流動性",
        "value": "51 百萬美元 (非限制性現金), 53 百萬美元 (限制性現金)",
        "unit": "USD",
        "period": "截至 2026 年 6 月 30 日",
        "status": "已取得",
        "confidence": "高",
        "source": "OPI Q2 2026 Earnings Call Transcript / SEC 10-Q",
        "source_url_or_name": "OPI Investor Relations",
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
        "note": "限制性現金包含35百萬美元重組費用準備金。",
        "source_quality_primary": "sec_filing",
        "source_quality": "sec_filing",
        "source_quality_details": [
          "sec_filing",
          "official_ir"
        ],
        "source_candidate_quality_details": [
          "sec_filing",
          "official_ir",
          "court_docket"
        ],
        "source_conflict_flag": false,
        "source_conflict_reason": "",
        "metric_period_parsed_date": "2026-08-19",
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
        "ticker": "OPI",
        "metric_name": "AFFO / FFO (Successor Period)",
        "metric_category": "現金流",
        "value": "4.494 百萬",
        "unit": "USD",
        "period": "2026Q2 (6月18日-6月30日)",
        "status": "已取得",
        "confidence": "高",
        "source": "OPI SEC Filing (8-K) / Earnings Presentation",
        "source_url_or_name": "SEC Filing",
        "warning_threshold": "AFFO/FFO 大幅下滑或為負需警戒。",
        "priority": "P0",
        "risk_impact": "REIT 配息與債務服務能力核心指標。",
        "note": "為重組後繼任期（Successor period）FFO。",
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
        "metric_name": "AFFO / FFO (Predecessor Period)",
        "metric_category": "現金流",
        "value": "15.118 百萬",
        "unit": "USD",
        "period": "2026Q2 (4月1日-6月17日)",
        "status": "已取得",
        "confidence": "高",
        "source": "OPI SEC Filing (8-K) / Earnings Presentation",
        "source_url_or_name": "SEC Filing",
        "warning_threshold": "AFFO/FFO 大幅下滑或為負需警戒。",
        "priority": "P0",
        "risk_impact": "REIT 配息與債務服務能力核心指標。",
        "note": "為重組前繼任期（Predecessor period）FFO。",
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
        "reason": "同 period / definition 前值=19.0，本次=19 百萬美元；區間不重疊。",
        "risk_impact": "REIT 配息與債務服務能力核心指標。",
        "previous_value": "19.0",
        "current_value": "19 百萬美元",
        "period": "2026Q2",
        "definition_scope": "",
        "calculation_basis": "",
        "acceptance_criteria": "以同一官方定義重新查核；若為不同口徑，改填不同 definition_scope / calculation_basis，不得覆寫。"
      }
    ],
    "dropped_old_events": [],
    "event_date_filter_summary": {
      "lookback_days": 14,
      "cutoff_date": "2026-08-06",
      "today": "2026-08-19",
      "kept_recent": 3,
      "kept_background": 0,
      "kept_unknown_date": 0,
      "dropped_old": 0
    },
    "metric_consistency_summary": {
      "conflict_count": 1,
      "conflicts": [
        {
          "ticker": "OPI",
          "metric_name": "AFFO / FFO",
          "metric_value": "19 百萬美元",
          "missing_reason": "同 period / definition 前值=19.0，本次=19 百萬美元；區間不重疊。",
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
        "date": "2026-08-17",
        "title": "AXIS Capital 任命 John Kopach 為批發中低市場主管",
        "impact_direction": "中性",
        "impact_severity": 2,
        "confidence": "高",
        "summary_30": "AXIS Capital 任命 John Kopach 接替退休的 Britt Smith 擔任新職位，為內部管理層變動。",
        "links": [
          "Simply Wall St News",
          "AXIS Investor Relations"
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
        "date": "2026-08-14",
        "title": "分析師看好 AXS-E 優先股穩定收益與 BBB 評級，儘管普通股 Q2 財報後波動",
        "impact_direction": "正向",
        "impact_severity": 3,
        "confidence": "中",
        "summary_30": "多份報告指出 AXS-E 優先股具 BBB 評級與 QDI 股息資格，為尋求穩定收益投資者提供吸引力，儘管普通股 Q2 財報後營運 EPS 未達預期導致股價下跌。",
        "links": [
          "Pluang",
          "Perplexity",
          "MarketBeat",
          "Finsee",
          "Reuters",
          "Seeking Alpha",
          "SeekingAlpha"
        ],
        "event_source_quality": "mainstream_media",
        "event_source_quality_details": [
          "mainstream_media",
          "secondary_site",
          "ai_summary"
        ],
        "event_verification_status": "partially_verified",
        "event_days_old": 5,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event",
        "merged_duplicate_count": 1
      }
    ],
    "綜合分析": "AXIS Capital 優先股因其穩定收益和良好信用評級而受到分析師青睞，儘管普通股在第二季財報後表現不佳，顯示市場對不同股權類別的看法存在分歧。",
    "事件總分": "正向3 / 負向0 / 總分+3",
    "new_sources_found": [
      "Simply Wall St News",
      "AXIS Investor Relations",
      "Pluang",
      "Perplexity",
      "MarketBeat",
      "Finsee"
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
        "source": "AXIS Capital Q2 2026 Earnings Release / SEC 10-Q",
        "source_url_or_name": "AXIS Capital Investor Relations / Stock Titan / Reinsurance News",
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
        "note": "綜合比率低於100%表示承保業務獲利。",
        "source_quality_primary": "sec_filing",
        "source_quality": "sec_filing",
        "source_quality_details": [
          "sec_filing",
          "official_ir",
          "specialized_media",
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
        "source": "AXIS Capital Q2 2026 Earnings Release / SEC 10-Q",
        "source_url_or_name": "AXIS Capital Investor Relations / Insurance Business / Reinsurance News",
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
        "note": "包括49百萬美元自然災害損失和31百萬美元中東衝突相關損失。",
        "source_quality_primary": "sec_filing",
        "source_quality": "sec_filing",
        "source_quality_details": [
          "sec_filing",
          "official_ir",
          "specialized_media"
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
        "value": "已支付且預期穩定",
        "unit": "status",
        "period": "2026Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "AXIS Capital Holdings Limited - Investor Relations (Press Release), Dividend Data Provider, SeekingAlpha",
        "source_url_or_name": "AXIS Capital Holdings Limited - Investor Relations / Dividend.com",
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
        "note": "2026年5月13日宣布，每股存託憑證0.34375美元的Series E優先股股息已於2026年7月15日支付。2026年9月30日為下次除息日，2026年10月16日為下次支付日。",
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
        "cross_run_previous_value": "已支付",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260818",
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
      "cutoff_date": "2026-08-06",
      "today": "2026-08-19",
      "kept_recent": 2,
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
        "date": "2026-08-18",
        "title": "惠譽評定福特信貸新債券，機構投資者增持福特股票",
        "impact_direction": "正向",
        "impact_severity": 2,
        "confidence": "高",
        "summary_30": "惠譽評定福特信貸汽車信託2026-REV2債券，信用質量穩定，且 Buckland Partners Management 增持福特股票。",
        "links": [
          "MarketBeat",
          "Fitch",
          "MarketScreener",
          "Fitch Ratings"
        ],
        "event_source_quality": "rating_agency",
        "event_source_quality_details": [
          "rating_agency",
          "secondary_site"
        ],
        "event_verification_status": "verified",
        "event_days_old": 1,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event",
        "merged_duplicate_count": 1
      },
      {
        "date": "2026-08-17",
        "title": "福特 Mach-E SUV 因車窗脫落風險召回",
        "impact_direction": "負向",
        "impact_severity": 4,
        "confidence": "高",
        "summary_30": "福特召回8.6萬輛 Mach-E，因供應商組裝問題恐致車窗脫落，影響公司聲譽。",
        "links": [
          "Kelley Blue Book"
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
        "date": "2026-08-17",
        "title": "華爾街日報報導 AI 數據中心帶動美國製造業繁榮，福特調整業務方向，Q2 財報後分析師仍看好",
        "impact_direction": "正向",
        "impact_severity": 3,
        "confidence": "高",
        "summary_30": "華爾街日報稱 AI 數據中心助美製造業繁榮，福特把握機會，儘管 Q2 財報後股價表現落後通用，分析師仍看好其 Pro 與 EV 策略。",
        "links": [
          "WSJ",
          "The Winona Times",
          "Zacks Investment Research"
        ],
        "event_source_quality": "mainstream_media",
        "event_source_quality_details": [
          "mainstream_media",
          "secondary_site"
        ],
        "event_verification_status": "partially_verified",
        "event_days_old": 2,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event",
        "merged_duplicate_count": 1
      },
      {
        "date": "2026-08-13",
        "title": "福特計劃將部分林肯車型生產從中國遷至美國，DBS 銀行上調福特評級",
        "impact_direction": "正向",
        "impact_severity": 3,
        "confidence": "高",
        "summary_30": "福特 CEO 表示，計劃自2030年起將部分林肯車型生產從中國遷至美國以應對關稅；DBS 銀行也將福特股票評級上調至「適度買入」。",
        "links": [
          "Reuters",
          "Seeking Alpha",
          "CBC",
          "Benzinga",
          "AutoGuide.com",
          "SeekingAlpha",
          "MarketBeat",
          "Zacks.com"
        ],
        "event_source_quality": "mainstream_media",
        "event_source_quality_details": [
          "mainstream_media",
          "secondary_site"
        ],
        "event_verification_status": "partially_verified",
        "event_days_old": 6,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event",
        "merged_duplicate_count": 1
      },
      {
        "date": "2026-08-12",
        "title": "美國汽車貸款拖欠率達15年新高",
        "impact_direction": "負向",
        "impact_severity": 3,
        "confidence": "中",
        "summary_30": "紐約聯準會數據顯示第二季度汽車貸款拖欠率創15年新高，可能對福特信貸業務造成負面影響。",
        "links": [
          "CBT News"
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
        "date": "2026-08-07",
        "title": "福特推出售價約2.8萬美元的新款 Fathom 電動皮卡",
        "impact_direction": "正向",
        "impact_severity": 4,
        "confidence": "高",
        "summary_30": "福特宣布推出 Fathom 中型電動皮卡，定價28,350美元，預計2027年底交付，瞄準平價 EV 市場。",
        "links": [
          "Ground News",
          "Seeking Alpha",
          "DBusiness Magazine"
        ],
        "event_source_quality": "secondary_site",
        "event_source_quality_details": [
          "secondary_site"
        ],
        "event_verification_status": "unverified",
        "event_days_old": 12,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event",
        "merged_duplicate_count": 1
      },
      {
        "date": "2026-08-06",
        "title": "福特 Bronco 與 Bronco Raptor 引擎線束短路召回，Zacks 上調評級",
        "impact_direction": "負向",
        "impact_severity": 4,
        "confidence": "高",
        "summary_30": "福特召回56萬餘輛 Bronco，因引擎線束短路恐致火災風險；Zacks 仍將福特汽車評級上調至「買入」。",
        "links": [
          "CarBuzz",
          "CBS News",
          "Zacks Investment Research"
        ],
        "event_source_quality": "secondary_site",
        "event_source_quality_details": [
          "secondary_site"
        ],
        "event_verification_status": "unverified",
        "event_days_old": 13,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event",
        "merged_duplicate_count": 1
      }
    ],
    "綜合分析": "福特汽車近期利好與利空消息並存，包括推出平價電動皮卡、機構增持和分析師評級上調，但同時也面臨 Mach-E 和 Bronco 車型的召回事件以及整體汽車貸款拖欠率上升的行業風險。",
    "事件總分": "正向12 / 負向11 / 總分+1",
    "new_sources_found": [
      "MarketBeat",
      "Fitch",
      "MarketScreener",
      "Fitch Ratings",
      "Kelley Blue Book",
      "The Winona Times",
      "Zacks Investment Research",
      "CBC",
      "Benzinga",
      "AutoGuide.com",
      "Zacks.com",
      "CBT News",
      "Ground News",
      "DBusiness Magazine",
      "CarBuzz",
      "CBS News"
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
        "source": "Ford Motor Company Q2 2026 Earnings Release / SEC Filing 10-Q (referenced in Aug 5 news)",
        "source_url_or_name": "Ford Motor Company Q2 2026 Earnings Release",
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
        "note": "Q2 2026調整後自由現金流為21億美元。",
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
        "cross_run_consistency_status": "consistent_same_definition",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "2.1",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260814",
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
        "period": "2026Q2",
        "status": "資料不足",
        "confidence": "低",
        "source": "Ford Motor Company Q2 2026 10-Q",
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
        "warning_threshold": "重大召回或保固成本升高需警戒。",
        "priority": "P1",
        "risk_impact": "品質成本會壓縮現金流與信用評等。",
        "note": "此為資產負債表上的保固及現場服務應計負債 (Warranty and field service accrual) 餘額。",
        "semantic_match_status": "rejected",
        "issuer_scope": "Ford Motor Company recall/warranty",
        "metric_value_type": "semantic_conflict_missing_veto",
        "rejected_candidate_reason": "Recall missing-data veto：同一輪 missing_data 明確表示未取得實際 recall/warranty cost；不得以其他數字覆蓋。原始缺漏理由：本次搜尋未找到官方或高可信來源明確指出2026年Q2實際發生的召回或保固成本金額。",
        "semantic_guard_version": "1.3.6",
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
        "metric_integrity_status": "semantic_rejected",
        "metric_verification_status": "data_missing",
        "rejected_candidate_value": "17.571",
        "rejected_candidate_source": "Ford Motor Company Q2 2026 10-Q",
        "live_validation_patch_version": "1.3.6",
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
        "reason": "本次搜尋未找到官方或高可信來源明確指出2026年Q2實際發生的召回或保固成本金額。",
        "risk_impact": "重大召回或保固成本升高會壓縮現金流與信用評等，缺少此數據影響對其品質成本的判斷。",
        "source_candidates": [
          "Ford Investor Relations",
          "SEC 10-Q",
          "SEC 8-K",
          "News"
        ],
        "acceptance_criteria": "下次需填入 value、period、source；若查無，需說明查詢過哪些來源",
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
        "reason": "Recall missing-data veto：同一輪 missing_data 明確表示未取得實際 recall/warranty cost；不得以其他數字覆蓋。原始缺漏理由：本次搜尋未找到官方或高可信來源明確指出2026年Q2實際發生的召回或保固成本金額。",
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
        "rejected_candidate_value": "17.571",
        "rejected_candidate_source": "Ford Motor Company Q2 2026 10-Q",
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
      "cutoff_date": "2026-08-06",
      "today": "2026-08-19",
      "kept_recent": 7,
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
        "date": "2026-08-09",
        "title": "TDS 及 Array Digital Infrastructure 公布 Q2 財報，Array 提升全年財測並報告頻譜出售收益",
        "impact_direction": "中性",
        "impact_severity": 4,
        "confidence": "高",
        "summary_30": "Array Q2 營收大增90%，得益於頻譜銷售及租賃增長，並提升2026年財測，但 TDS 整體自由現金流仍為負。",
        "links": [
          "TDS Investor Relations",
          "Array Digital Infrastructure Investor Relations",
          "PR Newswire",
          "SEC Filing",
          "Seeking Alpha",
          "Stockwatch",
          "TradingKey",
          "UScellular Investor Relations",
          "Bloomberg"
        ],
        "event_source_quality": "sec_filing",
        "event_source_quality_details": [
          "sec_filing",
          "official_ir",
          "press_release",
          "mainstream_media",
          "secondary_site"
        ],
        "event_verification_status": "verified",
        "event_days_old": 10,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event",
        "merged_duplicate_count": 1
      },
      {
        "date": "2026-08-07",
        "title": "TDS 對 Array Digital Infrastructure 提出收購剩餘股權的非約束性提案",
        "impact_direction": "中性",
        "impact_severity": 2,
        "confidence": "高",
        "summary_30": "TDS 提議收購其尚未擁有的 Array Digital Infrastructure 所有普通股，目前正由獨立委員會評估。",
        "links": [
          "TDS Investor Relations",
          "Array Digital Infrastructure Investor Relations",
          "SEC Filing",
          "TradingKey"
        ],
        "event_source_quality": "sec_filing",
        "event_source_quality_details": [
          "sec_filing",
          "official_ir"
        ],
        "event_verification_status": "verified",
        "event_days_old": 12,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event",
        "merged_duplicate_count": 1
      }
    ],
    "綜合分析": "TDS 對 Array Digital Infrastructure 提出收購剩餘股權的提案，而 Array 的第二季財報顯示營收顯著增長並提升財測，但母公司 TDS 的整體自由現金流仍為負。",
    "事件總分": "正向0 / 負向0 / 總分+0",
    "new_sources_found": [
      "TDS Investor Relations",
      "Array Digital Infrastructure Investor Relations",
      "Stockwatch",
      "TradingKey",
      "UScellular Investor Relations"
    ],
    "event_merge_source": "ai_stage2",
    "metric_data": [
      {
        "ticker": "UZD",
        "metric_name": "Issuer / guarantor status",
        "metric_category": "法律實體",
        "value": "United States Cellular Corporation (USM)",
        "unit": "status",
        "period": "2026Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "SEC 10-Q",
        "source_url_or_name": "United States Cellular Corporation Q2 2026 10-Q Filing",
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
        "note": "UZD 6.25% NT REDEEM 01/09/2069 為美國蜂窩公司發行的無擔保高級債券。TDS 為其母公司，但非本票據直接擔保人。",
        "semantic_match_status": "完全符合",
        "issuer_scope": "United States Cellular Corporation",
        "metric_value_type": "string",
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
        "cross_run_consistency_status": "not_comparable",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "United States Cellular Corporation / Array Digital Infrastructure, Inc. (NYSE: AD)",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260818",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 有前值，但數值型態無法安全比較。"
      },
      {
        "ticker": "UZD",
        "metric_name": "Asset sale proceeds and use of funds",
        "metric_category": "資產出售",
        "value": "2026年上半年出售約1.5億美元無線通訊塔資產，主要用於償還現有債務及資本支出。",
        "unit": "USD/status",
        "period": "2026H1",
        "status": "已取得",
        "confidence": "高",
        "source": "SEC 10-Q",
        "source_url_or_name": "United States Cellular Corporation Q2 2026 10-Q Filing",
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
        "note": "公司持續透過資產貨幣化來強化財務狀況，收益主要用於債務管理，未見大量分配股東。",
        "semantic_match_status": "完全符合",
        "issuer_scope": "United States Cellular Corporation",
        "metric_value_type": "string",
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
        "metric_period_parsed_date": "2026-08-19",
        "metric_period_parse_status": "year_only",
        "metric_period_type": "year",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "partially_verified",
        "metric_consistency_status": "cross_run_conflict",
        "metric_consistency_reason": "同 period / definition 前值=T-Mobile交易 $4.3B (含 $2.6B 現金及 $1.7B 債務承擔)；Verizon頻譜出售 $1B (2026年6月)；AT&T頻譜出售 $1.018B (2024年11月簽署)；2026年Q2頻譜出售收益約 $161.2M。2026年Q2宣派每股 $11 特殊股息。，本次=2026年上半年出售約1.5億美元無線通訊塔資產，主要用於償還現有債務及資本支出。；區間不重疊。",
        "cross_run_consistency_status": "value_changed_same_definition",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "T-Mobile交易 $4.3B (含 $2.6B 現金及 $1.7B 債務承擔)；Verizon頻譜出售 $1B (2026年6月)；AT&T頻譜出售 $1.018B (2024年11月簽署)；2026年Q2頻譜出售收益約 $161.2M。2026年Q2宣派每股 $11 特殊股息。",
        "cross_run_previous_period": "2026年Q2 (最新頻譜出售及特殊股息)",
        "cross_run_previous_report_date": "20260814",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 前值=T-Mobile交易 $4.3B (含 $2.6B 現金及 $1.7B 債務承擔)；Verizon頻譜出售 $1B (2026年6月)；AT&T頻譜出售 $1.018B (2024年11月簽署)；2026年Q2頻譜出售收益約 $161.2M。2026年Q2宣派每股 $11 特殊股息。，本次=2026年上半年出售約1.5億美元無線通訊塔資產，主要用於償還現有債務及資本支出。；區間不重疊。"
      },
      {
        "ticker": "UZD",
        "metric_name": "Debt assumption / redemption status",
        "metric_category": "債務處理",
        "value": "無贖回或承擔計劃",
        "unit": "status",
        "period": "2026Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "SEC 10-Q",
        "source_url_or_name": "United States Cellular Corporation Q2 2026 10-Q Filing",
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
        "note": "截至目前，公司未公告此系列票據的提前贖回或債務承擔計劃。",
        "semantic_match_status": "完全符合",
        "issuer_scope": "United States Cellular Corporation",
        "metric_value_type": "string",
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
        "cross_run_consistency_status": "not_comparable",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "UZD (6.25% Senior Notes due 2069) 債券未被T-Mobile承擔，仍由United States Cellular Corporation (現Array Digital Infrastructure Inc.) 持有。該債券自2025年9月1日起可選擇性贖回，截至目前，未有公告顯示UZD已部分或全部贖回。T-Mobile交易中涉及約17億美元債務承擔，但SEC文件確認UZD未包含在被承擔的債務中。",
        "cross_run_previous_period": "2026Q2 (截至2026年8月7日)",
        "cross_run_previous_report_date": "20260813",
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
    "missing_data": [
      {
        "ticker": "UZD",
        "priority": "P0",
        "missing_type": "metric_cross_run_consistency",
        "metric_name": "Asset sale proceeds and use of funds",
        "reason": "同 period / definition 前值=T-Mobile交易 $4.3B (含 $2.6B 現金及 $1.7B 債務承擔)；Verizon頻譜出售 $1B (2026年6月)；AT&T頻譜出售 $1.018B (2024年11月簽署)；2026年Q2頻譜出售收益約 $161.2M。2026年Q2宣派每股 $11 特殊股息。，本次=2026年上半年出售約1.5億美元無線通訊塔資產，主要用於償還現有債務及資本支出。；區間不重疊。",
        "risk_impact": "可能削弱債券資產覆蓋。",
        "previous_value": "T-Mobile交易 $4.3B (含 $2.6B 現金及 $1.7B 債務承擔)；Verizon頻譜出售 $1B (2026年6月)；AT&T頻譜出售 $1.018B (2024年11月簽署)；2026年Q2頻譜出售收益約 $161.2M。2026年Q2宣派每股 $11 特殊股息。",
        "current_value": "2026年上半年出售約1.5億美元無線通訊塔資產，主要用於償還現有債務及資本支出。",
        "period": "2026H1",
        "definition_scope": "",
        "calculation_basis": "",
        "acceptance_criteria": "以同一官方定義重新查核；若為不同口徑，改填不同 definition_scope / calculation_basis，不得覆寫。"
      }
    ],
    "dropped_old_events": [],
    "event_date_filter_summary": {
      "lookback_days": 14,
      "cutoff_date": "2026-08-06",
      "today": "2026-08-19",
      "kept_recent": 2,
      "kept_background": 0,
      "kept_unknown_date": 0,
      "dropped_old": 0
    },
    "metric_consistency_summary": {
      "conflict_count": 1,
      "conflicts": [
        {
          "ticker": "UZD",
          "metric_name": "Asset sale proceeds and use of funds",
          "metric_value": "2026年上半年出售約1.5億美元無線通訊塔資產，主要用於償還現有債務及資本支出。",
          "missing_reason": "同 period / definition 前值=T-Mobile交易 $4.3B (含 $2.6B 現金及 $1.7B 債務承擔)；Verizon頻譜出售 $1B (2026年6月)；AT&T頻譜出售 $1.018B (2024年11月簽署)；2026年Q2頻譜出售收益約 $161.2M。2026年Q2宣派每股 $11 特殊股息。，本次=2026年上半年出售約1.5億美元無線通訊塔資產，主要用於償還現有債務及資本支出。；區間不重疊。",
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
  }
]
```

# USPreferredStockDayInfo 每日情報報告

- 生成時間（台灣）：2026-08-20 08:20:51
- 對應 PDF：Stock_News_Report_20260820_082049.pdf
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
- 綜合分析：在指定日期範圍內無可報告的高可信相關事件。
- 事件：無

### 2. BHFAL

- 事件總分：正向2 / 負向8 / 總分-6
- 綜合分析：已排除低可信來源並合併重複事件；目前事件權重為偏負面（-6）。
- 事件 1：2026-08-19｜德拉瓦監管機構審查Aquarian收購案引發疑慮｜recent_event
  - 影響：負向｜嚴重性：4｜信心度：高
  - 摘要：德拉瓦保險部門正審查Aquarian收購Brighthouse案，引發投資者對交易完成的擔憂。
  - 來源：AM Best News、SeekingAlpha
  - 日期過濾：kept_recent｜來源品質：rating_agency｜驗證：verified
- 事件 2：2026-08-19｜收購案面臨監管審查引發市場擔憂｜recent_event
  - 影響：負向｜嚴重性：4｜信心度：高
  - 摘要：Aquarian Capital收購案之監管審查引發股價波動與市場擔憂。
  - 來源：SeekingAlpha、GuruFocus
  - 日期過濾：kept_recent｜來源品質：secondary_site｜驗證：unverified
- 事件 3：2026-08-18｜Brighthouse Financial宣布優先股股息分派｜recent_event
  - 影響：正向｜嚴重性：2｜信心度：高
  - 摘要：公司宣布將於2026年9月25日支付優先股股息，顯示財務履行能力良好。
  - 來源：SEC Filing、Stock Titan、TradingView、TipRanks.com、Business Wire、Moomoo、Brighthouse Financial Newsroom
  - 日期過濾：kept_recent｜來源品質：sec_filing｜驗證：verified
- 事件 4：2026-08-18｜首席會計長異動｜recent_event
  - 影響：中性｜嚴重性：1｜信心度：高
  - 摘要：公司宣布首席會計長將於九月辭職，由副會計長接任，稱與財報無關。
  - 來源：SEC Filing、Stock Titan、TradingView
  - 日期過濾：kept_recent｜來源品質：sec_filing｜驗證：verified

### 3. OPI

- 事件總分：正向0 / 負向10 / 總分-10
- 綜合分析：Stage 2 AI 合併未完成；已由程式保留高可信 Stage 1 近期事件，事件權重偏負面（-10）。
- 事件 1：2026-08-13｜OPI 內部人士出售股票｜recent_event
  - 影響：負向｜嚴重性：3｜信心度：高
  - 摘要：SEC文件顯示OPI內部人士於8月13日出售公司股票。
  - 來源：SEC Filing (Form 4)、MarketBeat
  - 日期過濾：kept_recent｜來源品質：sec_filing｜驗證：verified
- 事件 2：2026-08-08｜分析報告：OPI 儘管現金流改善，債務負擔仍構成壓力｜recent_event
  - 影響：負向｜嚴重性：4｜信心度：中
  - 摘要：分析指出OPI雖減債，但17億美元債務及2027年到期信貸設施仍是關鍵壓力。
  - 來源：Simply Wall St
  - 日期過濾：kept_recent｜來源品質：secondary_site｜驗證：unverified
- 事件 3：2026-08-07｜OPI 2026年第二季財報電話會議詳情與營運展望｜recent_event
  - 影響：中性｜嚴重性：4｜信心度：高
  - 摘要：管理層討論Q2業績、資產出售策略、2027年到期債務再融資計劃及未來展望。
  - 來源：OPI Earnings Call Transcript、Seeking Alpha、TradingView News
  - 日期過濾：kept_recent｜來源品質：secondary_site｜驗證：unverified
- 事件 4：2026-08-07｜主要股東 Redwood Capital Management 申報擬出售 100 萬股普通股｜recent_event
  - 影響：負向｜嚴重性：3｜信心度：高
  - 摘要：大股東 Redwood 申報售 100 萬股，價值約 $1971 萬。
  - 來源：SEC Filing
  - 日期過濾：kept_recent｜來源品質：sec_filing｜驗證：verified

### 4. AXS-E

- 事件總分：正向12 / 負向3 / 總分+9
- 綜合分析：Stage 2 AI 合併未完成；已由程式保留高可信 Stage 1 近期事件，事件權重偏正面（+9）。
- 事件 1：2026-08-19｜AXIS Capital 任命北美金融線、項目及加拿大業務主管｜recent_event
  - 影響：中性｜嚴重性：1｜信心度：高
  - 摘要：AXIS Capital任命Jim Rhyner為北美金融線、項目及加拿大業務主管，屬高階管理層變動。
  - 來源：AXIS Capital Investor Relations
  - 日期過濾：kept_recent｜來源品質：official_ir｜驗證：verified
- 事件 2：2026-08-17｜Simply Wall St 分析 AXIS Capital (AXS) 領導層變動與普通股股價表現｜recent_event
  - 影響：中性｜嚴重性：2｜信心度：中
  - 摘要：Simply Wall St 報導 AXS 領導層變動與普通股近期下跌，但公司基本面穩健，長期看漲。
  - 來源：Simply Wall St News
  - 日期過濾：kept_recent｜來源品質：secondary_site｜驗證：unverified
- 事件 3：2026-08-14｜Seeking Alpha 評估 AXS-E 優先股殖利率競爭力與穩健 Q2 財報｜recent_event
  - 影響：正向｜嚴重性：3｜信心度：中
  - 摘要：Seeking Alpha 報告指 AXS-E 優先股因Q2財報良好、信評佳而具高殖利率吸引力。
  - 來源：Seeking Alpha
  - 日期過濾：kept_recent｜來源品質：secondary_site｜驗證：unverified
- 事件 4：2026-08-14｜Zacks Research 下調 AXIS Capital 評級及盈餘預期｜recent_event
  - 影響：負向｜嚴重性：3｜信心度：中
  - 摘要：Zacks將AXIS Capital評級下調至「強力賣出」，並大幅下調2026及2027財年EPS預期，反映Q2業績未達預期。
  - 來源：MarketBeat
  - 日期過濾：kept_recent｜來源品質：secondary_site｜驗證：unverified
- 事件 5：2026-08-14｜Seeking Alpha 正面分析 AXS-E 優先股｜recent_event
  - 影響：正向｜嚴重性：2｜信心度：中
  - 摘要：Seeking Alpha報告指出AXS-E優先股具競爭性收益與穩健信用品質，適合收益型投資人。
  - 來源：SeekingAlpha
  - 日期過濾：kept_recent｜來源品質：unknown｜驗證：unverified
- 事件 6：2026-08-08｜AXIS Capital 公佈穩健的第二季度業績，承保盈利能力改善｜recent_event
  - 影響：正向｜嚴重性：4｜信心度：高
  - 摘要：AXIS Capital Q2業績超出預期，綜合費用率改善至92.5%，反映承保業務表現穩健。
  - 來源：AXIS Investor Relations、PRNewswire
  - 日期過濾：kept_recent｜來源品質：official_ir｜驗證：verified
- 事件 7：2026-08-08｜AXIS Capital 宣佈其Series E優先股AXS-E的季度股利｜recent_event
  - 影響：正向｜嚴重性：3｜信心度：高
  - 摘要：公司董事會宣佈按期支付AXS-E優先股的季度現金股利，確認現金流穩定性。
  - 來源：AXIS Investor Relations、BusinessWire
  - 日期過濾：kept_recent｜來源品質：official_ir｜驗證：verified

### 5. F-B

- 事件總分：正向17 / 負向4 / 總分+13
- 綜合分析：已排除低可信來源並合併重複事件；目前事件權重為偏正面（+13）。
- 事件 1：2026-08-19｜Q2財報亮眼並上調全年財測，分析師上調評級｜recent_event
  - 影響：正向｜嚴重性：5｜信心度：高
  - 摘要：福特Q2獲利超預期，上調2026年EBIT與自由現金流指引，獲多家投行上調評級。
  - 來源：Business Wire、MarketBeat、SeekingAlpha、StocksToTrade、Timothy Sykes、Investing.com、GuruFocus
  - 日期過濾：kept_recent｜來源品質：press_release｜驗證：partially_verified
- 事件 2：2026-08-19｜福特據報計劃推出Bronco皮卡並將Lincoln生產線遷回美國｜recent_event
  - 影響：正向｜嚴重性：3｜信心度：中
  - 摘要：福特據報計劃於十年末推出Bronco皮卡，並將Lincoln生產線遷回美國，有助於國內就業。
  - 來源：Automotive News、The White House、TFLtruck
  - 日期過濾：kept_recent｜來源品質：unknown｜驗證：unverified
- 事件 3：2026-08-17｜WSJ報導福特正轉向為AI資料中心提供電池儲能設備｜recent_event
  - 影響：正向｜嚴重性：3｜信心度：中
  - 摘要：華爾街日報稱福特正將業務轉向AI資料中心電池儲能設備。
  - 來源：AI Weekly、The Enterprise Journal
  - 日期過濾：kept_recent｜來源品質：unknown｜驗證：unverified
- 事件 4：2026-08-17｜Fitch確認福特信貸車輛資產信託評級｜recent_event
  - 影響：中性｜嚴重性：2｜信心度：高
  - 摘要：Fitch確認福特信貸2026-REV2信託評級，顯示其證券化池信用品質穩定。
  - 來源：Fitch Ratings
  - 日期過濾：kept_recent｜來源品質：rating_agency｜驗證：verified
- 事件 5：2026-08-12｜美國第二季汽車貸款嚴重逾期率達15年新高｜recent_event
  - 影響：負向｜嚴重性：4｜信心度：高
  - 摘要：紐約聯儲報告，2026年Q2美國汽車貸款嚴重逾期率創15年新高，對福特信貸構成風險。
  - 來源：CBT News、Auto Dealer Today、Morningstar DBRS、Federal Reserve Bank of New York
  - 日期過濾：kept_recent｜來源品質：unknown｜驗證：unverified
- 事件 6：2026-08-12｜規劃2030年起將部分Lincoln車款生產線從中國遷回美國｜recent_event
  - 影響：正向｜嚴重性：3｜信心度：高
  - 摘要：因應美國關稅與法規，福特計劃2030年起將部分Lincoln生產遷回美國。
  - 來源：Reuters、SeekingAlpha、MarketScreener、Just Auto、CarsDirect、Investing.com
  - 日期過濾：kept_recent｜來源品質：mainstream_media｜驗證：partially_verified
- 事件 7：2026-08-07｜福特Q2財報後續討論與新款電動皮卡Fathom｜recent_event
  - 影響：正向｜嚴重性：3｜信心度：中
  - 摘要：Q2盈利超預期並上調全年指引，分析師多正面評價，新款電動皮卡Fathom亦受關注。
  - 來源：Zacks、MarketBeat、SeekingAlpha、Insidermonkey、Benzinga、WSJ
  - 日期過濾：kept_recent｜來源品質：mainstream_media｜驗證：partially_verified
- 事件 8：2026-08-07｜傳聞將推出四門Mustang混合動力車款｜recent_event
  - 影響：中性｜嚴重性：2｜信心度：中
  - 摘要：華爾街日報報導福特計劃推出四門混合動力Mustang，可能採V-8引擎。
  - 來源：Investing.com、StocksToTrade
  - 日期過濾：kept_recent｜來源品質：unknown｜驗證：unverified

### 6. UZD

- 事件總分：正向8 / 負向2 / 總分+6
- 綜合分析：Stage 2 AI 合併未完成；已由程式保留高可信 Stage 1 近期事件，事件權重偏正面（+6）。
- 事件 1：2026-08-19｜JPMorgan Chase & Co. 下調Array Digital Infrastructure目標價｜recent_event
  - 影響：負向｜嚴重性：2｜信心度：中
  - 摘要：摩根大通將Array Digital Infrastructure的股票目標價從54美元下調至45美元，但維持「增持」評級。
  - 來源：MarketBeat
  - 日期過濾：kept_recent｜來源品質：secondary_site｜驗證：unverified
- 事件 2：2026-08-19｜TDS 宣布 2026 年第三季度普通股及優先股股息｜recent_event
  - 影響：中性｜嚴重性：1｜信心度：高
  - 摘要：TDS（Array母公司）董事會宣告第三季度股息，按季支付普通股及優先股股息。
  - 來源：PR Newswire、Investing.com
  - 日期過濾：kept_recent｜來源品質：press_release｜驗證：partially_verified
- 事件 3：2026-08-19｜TDS宣佈2026年第三季股息｜recent_event
  - 影響：中性｜嚴重性：1｜信心度：高
  - 摘要：UScellular母公司TDS宣佈季度股息，為例行性財務活動。
  - 來源：PRNewswire
  - 日期過濾：kept_recent｜來源品質：press_release｜驗證：partially_verified
- 事件 4：2026-08-10｜T-Mobile在收購UScellular後裁員4,500多人｜recent_event
  - 影響：中性｜嚴重性：2｜信心度：高
  - 摘要：T-Mobile整合UScellular資產後進行裁員，影響其部分債務承擔方。
  - 來源：Light Reading
  - 日期過濾：kept_recent｜來源品質：unknown｜驗證：unverified
- 事件 5：2026-08-07｜Array Digital Infrastructure 公布強勁 2026 年第二季度財報並更新財測｜recent_event
  - 影響：正向｜嚴重性：4｜信心度：高
  - 摘要：Array 報告 Q2 營收和淨利顯著增長，受益於光譜出售，並上調 2026 年 EBITDA 財測。
  - 來源：SEC Filing、PR Newswire、Array Digital Infrastructure Investor Relations
  - 日期過濾：kept_recent｜來源品質：sec_filing｜驗證：verified
- 事件 6：2026-08-07｜TDS公佈2026年第二季業績，Array實現塔位租賃增長並完成頻譜出售｜recent_event
  - 影響：正向｜嚴重性：4｜信心度：高
  - 摘要：Array塔位業務增長；完成10億美元頻譜出售，強化資產負債表。TDS提議收購Array剩餘股份。
  - 來源：Telephone and Data Systems Investor Relations、StreetInsider、Public Technologies
  - 日期過濾：kept_recent｜來源品質：official_ir｜驗證：verified

## 量化指標與資料缺口

- 量化監控框架版本：1.0
- 說明：v1 先建立每檔應追蹤指標與資料缺口；尚未取得官方數值時，會標示為「資料不足」。

### CTGG 量化監控
- Free cash flow｜狀態：已取得｜驗證：verified｜來源品質：official_ir｜期間新鮮度：fresh｜門檻：FCF 轉負或展望下修需警戒。
- Debt maturity and exchange offer terms｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：distressed exchange、順位弱化或擔保改變需警戒。
- Credit rating / outlook｜狀態：已取得｜驗證：verified｜來源品質：rating_agency｜期間新鮮度：fresh｜門檻：downgrade、negative outlook 或 selective default 評論需警戒。
- 資料缺口：1 項，關鍵資料缺漏時不可判定為綠燈。

### BHFAL 量化監控
- RBC ratio｜狀態：已取得｜驗證：partially_verified｜來源品質：press_release｜期間新鮮度：fresh｜門檻：低於 400% 黃燈；低於 350% 橙燈/紅燈；單季大幅下滑需警戒。
- Statutory capital and surplus｜狀態：已取得｜驗證：partially_verified｜來源品質：press_release｜期間新鮮度：fresh｜門檻：連續下降或重大減損需警戒。
- Holding company cash and liquid assets｜狀態：已取得｜驗證：partially_verified｜來源品質：press_release｜期間新鮮度：fresh｜門檻：低於未來 12 個月利息與固定支出覆蓋需求需警戒。
- Financial leverage｜狀態：資料不足｜驗證：data_missing｜來源品質：unknown｜期間新鮮度：fresh｜門檻：槓桿升高或評等機構負面評論需警戒。
- Credit rating / outlook｜狀態：已取得｜驗證：verified｜來源品質：official_ir｜期間新鮮度：fresh｜門檻：negative outlook、downgrade 或 watch negative 需警戒。
- BHFAL interest payment status｜狀態：已取得｜驗證：partially_verified｜來源品質：press_release｜期間新鮮度：fresh｜門檻：defer、suspend、delay、non-payment 立即紅燈。
- Aquarian merger / change-of-control treatment｜狀態：已取得｜驗證：partially_verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：未明確說明 BHFAL 存續、掛牌、贖回或付息條款時列資料不足。
- 資料缺口：4 項，關鍵資料缺漏時不可判定為綠燈。

### OPI 量化監控
- Occupancy rate｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：連續下降或低於同業顯著水準需警戒。
- AFFO / FFO｜狀態：已取得｜驗證：partially_verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：AFFO/FFO 大幅下滑或為負需警戒。
- Debt maturity schedule｜狀態：已取得｜驗證：partially_verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：12-24 個月內大量到期且流動性不足需紅燈。
- Liquidity / cash availability｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：流動性不足或 covenant 壓力需警戒。
- 資料缺口：2 項，關鍵資料缺漏時不可判定為綠燈。

### AXS-E 量化監控
- Combined ratio｜狀態：已取得｜驗證：partially_verified｜來源品質：official_ir｜期間新鮮度：fresh｜門檻：高於 100% 或明顯惡化需警戒。
- Catastrophe losses｜狀態：已取得｜驗證：partially_verified｜來源品質：official_ir｜期間新鮮度：fresh｜門檻：重大巨災損失超預期需警戒。
- Preferred dividend status｜狀態：已取得｜驗證：verified｜來源品質：official_ir｜期間新鮮度：fresh｜門檻：defer、suspend、delay 立即紅燈。
- 資料缺口：2 項，關鍵資料缺漏時不可判定為綠燈。

### F-B 量化監控
- Industrial free cash flow｜狀態：已取得｜驗證：partially_verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：FCF 轉負或全年指引大幅下修需警戒。
- Ford Credit delinquencies / credit losses｜狀態：資料不足｜驗證：data_missing｜來源品質：rating_agency｜期間新鮮度：fresh｜門檻：逾期率或信用損失準備明顯上升需警戒。
- Recall / warranty cost｜狀態：資料不足｜驗證：data_missing｜來源品質：unknown｜期間新鮮度：fresh｜門檻：重大召回或保固成本升高需警戒。
- 資料缺口：4 項，關鍵資料缺漏時不可判定為綠燈。

### UZD 量化監控
- Issuer / guarantor status｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：發行人或擔保人不明確時列灰燈/黃燈，不可判定安全。
- Asset sale proceeds and use of funds｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：出售所得若大量分配給股東而非減債需警戒。
- Debt assumption / redemption status｜狀態：資料不足｜驗證：data_missing｜來源品質：rating_agency｜期間新鮮度：acceptable_recent｜門檻：未說明承擔、契約修改或贖回時列資料不足。
- 資料缺口：1 項，關鍵資料缺漏時不可判定為綠燈。

## 程式端日期過濾與來源驗證

- 日期過濾版本：1.2.2
- 最近事件保留天數：14 天
- 說明：超出最近 14 日但命中 Chapter 11、收購、重整、退市、債務交換等重大關鍵字者，會保留為 background_risk_event；其他舊事件移至 dropped_old_events。

- CTGG：recent=0，background=0，unknown_date=0，dropped_old=0
- BHFAL：recent=4，background=0，unknown_date=0，dropped_old=0
- OPI：recent=4，background=0，unknown_date=0，dropped_old=0
- AXS-E：recent=7，background=0，unknown_date=0，dropped_old=0
- F-B：recent=8，background=0，unknown_date=0，dropped_old=0
- UZD：recent=6，background=0，unknown_date=0，dropped_old=0

## 完整 JSON

```json
[
  {
    "target_name": "CTGG",
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
        "ticker": "CTGG",
        "metric_name": "Free cash flow",
        "metric_category": "現金流",
        "value": "327 百萬",
        "unit": "USD",
        "period": "2026Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "BusinessWire / Lumen Investor Relations",
        "source_url_or_name": "Lumen Technologies Investor Relations",
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
        "note": "2026年第二季排除特殊項目後的自由現金流為3.27億美元，較去年同期負2.09億美元顯著改善。公司重申2026年全年自由現金流指引為19-21億美元。",
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
        "cross_run_previous_value": "327 百萬",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260818",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 與前一可信值一致。"
      },
      {
        "ticker": "CTGG",
        "metric_name": "Debt maturity and exchange offer terms",
        "metric_category": "債務結構",
        "value": "已完成交換要約，新發行6.500%票據於2051年到期",
        "unit": "status/date/USD",
        "period": "2026-06-10",
        "status": "已取得",
        "confidence": "高",
        "source": "BusinessWire / Lumen Investor Relations / SEC Filing",
        "source_url_or_name": "Lumen Technologies Investor Relations",
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
        "note": "Qwest Corp 6.500% Senior Notes due 2051是Lumen子公司Qwest Corp發行，且由Lumen Technologies無條件擔保的新票據，此為其於2026年6月10日完成的債務交換要約之一部分。該交換要約將部分舊Qwest票據替換為新的、由Lumen擔保的票據，總長期債務從2025年12月31日的174億美元減少至2026年6月30日的約132億美元。",
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
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "consistent_with_prior_range",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "Qwest Corp. 6.500% Senior Notes due 2051",
        "cross_run_previous_period": "2026-06-10",
        "cross_run_previous_report_date": "20260811",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 數值表達不同，但目前值落在前一可信區間內。"
      },
      {
        "ticker": "CTGG",
        "metric_name": "Credit rating / outlook",
        "metric_category": "信用評等",
        "value": "Moody's B2 (穩定); S&P B- (高級無擔保B, 回復評級2); Fitch B (穩定)",
        "unit": "rating",
        "period": "2026年2月-4月",
        "status": "已取得",
        "confidence": "高",
        "source": "Moody's Ratings / S&P Global Ratings / Fitch Ratings / BusinessWire",
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
        "note": "Moody's於2026年2月20日將Lumen的公司家族評級從B3上調至B2，Qwest高級無擔保票據從Caa2上調至Caa1，展望均為穩定。S&P於2026年2月6日將Lumen高級無擔保債務評級從CCC上調至B，回復評級從6上調至2，發行人信用評級維持B-。Fitch於2026年4月17日確認Lumen和Qwest的發行人違約評級為B，展望穩定。",
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
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
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
        "missing_type": "metric_value",
        "metric_name": "Debt maturity schedule (詳盡)",
        "reason": "在指定日期範圍內（最近14日內）未找到Lumen/Qwest所有債務的詳盡最新償債時間表（超越泛指『無近期重大到期』的聲明）。最近一次詳盡披露的SEC文件日期為2025年6月30日。",
        "risk_impact": "缺乏最新的詳細債務償付時間表，可能影響對Lumen/Qwest整體再融資風險的全面評估。",
        "source_candidates": [
          "SEC 10-Q",
          "SEC 10-K",
          "Lumen Investor Relations"
        ],
        "acceptance_criteria": "下次需填入 value、period、source；若查無，需說明查詢過哪些來源。"
      }
    ],
    "metric_integrity_issues": [
      {
        "issue": "explicit_cross_ticker_row_rejected",
        "parent_ticker": "CTGG",
        "row_ticker": "LUMN/QWEST",
        "metric_name": "Credit rating / outlook",
        "value": "Moody's: B2/Stable; Fitch: B/Stable; S&P: B-/Stable (Lumen IDR), B (Qwest Notes)"
      }
    ],
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
      },
      {
        "parent_ticker": "CTGG",
        "accepted_alias": "LUMN",
        "metric_name": "Free cash flow"
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
    "dropped_old_events": [],
    "event_date_filter_summary": {
      "lookback_days": 14,
      "cutoff_date": "2026-08-07",
      "today": "2026-08-20",
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
    "target_name": "BHFAL",
    "events": [
      {
        "date": "2026-08-19",
        "title": "德拉瓦監管機構審查Aquarian收購案引發疑慮",
        "impact_direction": "負向",
        "impact_severity": 4,
        "confidence": "高",
        "summary_30": "德拉瓦保險部門正審查Aquarian收購Brighthouse案，引發投資者對交易完成的擔憂。",
        "links": [
          "AM Best News",
          "SeekingAlpha"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "rating_agency",
        "event_source_quality_details": [
          "rating_agency"
        ],
        "event_verification_status": "verified",
        "event_days_old": 1,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      },
      {
        "date": "2026-08-19",
        "title": "收購案面臨監管審查引發市場擔憂",
        "impact_direction": "負向",
        "impact_severity": 4,
        "confidence": "高",
        "summary_30": "Aquarian Capital收購案之監管審查引發股價波動與市場擔憂。",
        "links": [
          "SeekingAlpha",
          "GuruFocus"
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
        "date": "2026-08-18",
        "title": "Brighthouse Financial宣布優先股股息分派",
        "impact_direction": "正向",
        "impact_severity": 2,
        "confidence": "高",
        "summary_30": "公司宣布將於2026年9月25日支付優先股股息，顯示財務履行能力良好。",
        "links": [
          "SEC Filing",
          "Stock Titan",
          "TradingView",
          "TipRanks.com",
          "Business Wire",
          "Moomoo",
          "Brighthouse Financial Newsroom"
        ],
        "merged_duplicate_count": 2,
        "event_source_quality": "sec_filing",
        "event_source_quality_details": [
          "sec_filing",
          "press_release",
          "secondary_site"
        ],
        "event_verification_status": "verified",
        "event_days_old": 2,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      },
      {
        "date": "2026-08-18",
        "title": "首席會計長異動",
        "impact_direction": "中性",
        "impact_severity": 1,
        "confidence": "高",
        "summary_30": "公司宣布首席會計長將於九月辭職，由副會計長接任，稱與財報無關。",
        "links": [
          "SEC Filing",
          "Stock Titan",
          "TradingView"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "sec_filing",
        "event_source_quality_details": [
          "sec_filing",
          "secondary_site"
        ],
        "event_verification_status": "verified",
        "event_days_old": 2,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      }
    ],
    "綜合分析": "已排除低可信來源並合併重複事件；目前事件權重為偏負面（-6）。",
    "事件總分": "正向2 / 負向8 / 總分-6",
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
        "note": "截至2026年6月30日的預估合併風險資本比率，與2026年第一季度保持一致，並處於目標範圍上端。",
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
        "source_period_evidence": "Brighthouse Financial Q2 2026 Earnings Release | Business Wire | 截至2026年6月30日的預估合併風險資本比率，與2026年第一季度保持一致，並處於目標範圍上端。",
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
        "value": "$4.9 billion",
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
        "note": "截至2026年6月30日的法定合併調整後資本，與2026年3月31日相比相對持平。",
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
        "note": "截至2026年6月30日的控股公司流動資產。",
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
        "source_period_evidence": "Brighthouse Financial Q2 2026 Earnings Release | Business Wire | 截至2026年6月30日的控股公司流動資產。",
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
        "value": "未直接披露具體數值",
        "unit": "%",
        "period": "2026Q2",
        "status": "資料不足",
        "confidence": "低",
        "source": "N/A",
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
        "warning_threshold": "槓桿升高或評等機構負面評論需警戒。",
        "priority": "P1",
        "risk_impact": "槓桿上升會削弱次順位債安全邊際。",
        "note": "2026年第二季度財報摘要中未直接提供具體金融槓桿百分比。詳細數據需查閱完整的SEC 10-Q文件。",
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
        "metric_consistency_status": "conflict_with_missing_data",
        "metric_consistency_reason": "本次搜尋未從公開財報摘要中找到官方最新具體數值",
        "metric_consistency_missing_type": "metric_value",
        "cross_run_consistency_status": "no_prior_same_period",
        "definition_scope": "",
        "calculation_basis": ""
      },
      {
        "ticker": "BHFAL",
        "metric_name": "Credit rating / outlook",
        "metric_category": "信用評等",
        "value": "AM Best: A (Excellent) / under review with negative implications; S&P: A / Stable (March 2026); Moody's: A3 / Stable (March 2026); Fitch: A- / Stable (March 2026)",
        "unit": "rating",
        "period": "2026-07-29 (AM Best)",
        "status": "已取得",
        "confidence": "高",
        "source": "AM Best, Brighthouse Financial Investor Relations",
        "source_url_or_name": "AM Best, Brighthouse Financial",
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
        "note": "AM Best於7月29日維持其評級為「審查中帶負面影響」，主要因為Aquarian收購案，對控股公司長期發行人信用評級維持'bbb+'。其他評級機構（S&P, Moody's, Fitch）的最新評級更新時間早於14天，但為目前生效評級，且展望多為穩定，唯獨AM Best評級受收購案影響為負面觀察。",
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
        "metric_period_parsed_date": "2026-07-29",
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
        "cross_run_previous_value": "bbb-",
        "cross_run_previous_period": "2026-07-29",
        "cross_run_previous_report_date": "20260810",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 有前值，但數值型態無法安全比較。"
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
        "source": "Brighthouse Financial Q2 2026 Earnings Release (Implied)",
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
        "warning_threshold": "defer、suspend、delay、non-payment 立即紅燈。",
        "priority": "P0",
        "risk_impact": "直接影響退休現金流。",
        "note": "Q2財報顯示穩健的財務表現和流動性，未有任何關於BHFAL或其他債務付息問題的公告，暗示正常支付。",
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
        "value": "合併案持續進行，監管審查中；BHFAL預計維持上市。",
        "unit": "status",
        "period": "2026-08-19",
        "status": "已取得",
        "confidence": "高",
        "source": "Business Wire, SEC Filing, AM Best News, SeekingAlpha",
        "source_url_or_name": "Business Wire, SEC.gov, AM Best News, SeekingAlpha",
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
        "note": "Aquarian Capital對Brighthouse Financial的收購案仍在等待德拉瓦州保險監管機構的批准，預計2026年完成。早前SEC文件顯示合併後BHFAL將保持上市及作為公司債務，但新母公司未來可能決定將其下市。",
        "source_quality_primary": "sec_filing",
        "source_quality": "sec_filing",
        "source_quality_details": [
          "sec_filing",
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
        "metric_period_parsed_date": "2026-08-19",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "date",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "partially_verified",
        "metric_consistency_status": "conflict_with_missing_data",
        "metric_consistency_reason": "收購案仍在審查中，且未明確披露BHFAL次順位債在收購完成後的具體處理條款。",
        "metric_consistency_missing_type": "metric_detail",
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
        "reason": "本次搜尋未從公開財報摘要中找到官方最新具體數值",
        "risk_impact": "缺乏精確的金融槓桿數據，難以全面評估債務安全邊際。",
        "source_candidates": [
          "SEC 10-Q",
          "Earnings Supplement",
          "Rating Agency Reports"
        ],
        "acceptance_criteria": "下次需填入 value、period、source，並註明是否來自完整財報文件；若查無，需說明查詢過哪些來源。",
        "missing_type_original": "metric_value",
        "conflict_with_metric_data": true,
        "metric_value_present": "未直接披露具體數值",
        "metric_source_present": "N/A",
        "metric_verification_after_reconcile": "data_missing"
      },
      {
        "ticker": "BHFAL",
        "priority": "P0",
        "missing_type": "metric_consistency",
        "metric_name": "Aquarian merger / change-of-control treatment",
        "reason": "收購案仍在審查中，且未明確披露BHFAL次順位債在收購完成後的具體處理條款。",
        "risk_impact": "收購完成後可能影響掛牌、流動性與資本政策，對次順位債持有者而言，此資訊缺漏是重大不確定性。",
        "source_candidates": [
          "Brighthouse Financial Investor Relations",
          "SEC 8-K (merger-related)",
          "SEC Schedule 14A/TO"
        ],
        "acceptance_criteria": "需查找合併協議或相關文件，以獲取BHFAL債券在控制權變更後的具體條款。",
        "missing_type_original": "metric_detail",
        "conflict_with_metric_data": true,
        "metric_value_present": "合併案持續進行，監管審查中；BHFAL預計維持上市。",
        "metric_source_present": "Business Wire, SEC Filing, AM Best News, SeekingAlpha",
        "metric_verification_after_reconcile": "partially_verified"
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
      "cutoff_date": "2026-08-07",
      "today": "2026-08-20",
      "kept_recent": 4,
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
        },
        {
          "ticker": "BHFAL",
          "metric_name": "Financial leverage",
          "metric_value": "未直接披露具體數值",
          "missing_reason": "本次搜尋未從公開財報摘要中找到官方最新具體數值",
          "verification_after_reconcile": "data_missing",
          "cross_run_consistency_status": "no_prior_same_period",
          "definition_scope": "",
          "calculation_basis": ""
        },
        {
          "ticker": "BHFAL",
          "metric_name": "Aquarian merger / change-of-control treatment",
          "metric_value": "合併案持續進行，監管審查中；BHFAL預計維持上市。",
          "missing_reason": "收購案仍在審查中，且未明確披露BHFAL次順位債在收購完成後的具體處理條款。",
          "verification_after_reconcile": "partially_verified",
          "cross_run_consistency_status": "no_prior_same_period",
          "definition_scope": "",
          "calculation_basis": ""
        }
      ]
    },
    "market_quote": {
      "ticker": "BHFAL",
      "security_name_expected": "Brighthouse Financial 6.25% Junior Subordinated Debentures due 2058",
      "exchange_expected": "NASDAQ",
      "latest_price": 15.725,
      "price_as_of": "2026-08-19",
      "open": 15.699999809265137,
      "high": 15.770000457763672,
      "low": 15.650099754333496,
      "volume": 28503,
      "bid": null,
      "ask": null,
      "annual_interest": 1.5625,
      "current_yield": 9.9364,
      "quote_source": "Yahoo Finance chart (query1.finance.yahoo.com)",
      "source_host": "query1.finance.yahoo.com",
      "quote_status": "ok",
      "freshness_status": "fresh",
      "security_identity_status": "matched_symbol",
      "source_timestamp": 1787146200,
      "market_quote_patch_version": "1.3.7",
      "returned_symbol": "BHFAL",
      "currency": "USD",
      "exchange_name": "NMS",
      "instrument_type": "EQUITY",
      "regular_market_price_meta": 15.725,
      "regular_market_time_meta": 1787169600,
      "reference_session_date": "2026-08-19",
      "weekday_gap": 0,
      "http_status": 200,
      "request_url": "https://query1.finance.yahoo.com/v8/finance/chart/BHFAL",
      "request_attempt": 1,
      "attempts": [
        {
          "source_host": "query1.finance.yahoo.com",
          "quote_status": "ok",
          "freshness_status": "fresh",
          "price_as_of": "2026-08-19",
          "latest_price": 15.725,
          "error": null
        },
        {
          "source_host": "query2.finance.yahoo.com",
          "quote_status": "ok",
          "freshness_status": "fresh",
          "price_as_of": "2026-08-19",
          "latest_price": 15.725,
          "error": null
        }
      ],
      "source_validation": "cross_checked",
      "source_crosscheck_price": 15.725,
      "source_crosscheck_host": "query2.finance.yahoo.com",
      "source_conflict_pct": 0.0
    }
  },
  {
    "target_name": "OPI",
    "events": [
      {
        "date": "2026-08-13",
        "title": "OPI 內部人士出售股票",
        "impact_direction": "負向",
        "impact_severity": 3,
        "confidence": "高",
        "summary_30": "SEC文件顯示OPI內部人士於8月13日出售公司股票。",
        "links": [
          "SEC Filing (Form 4)",
          "MarketBeat"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "sec_filing",
        "event_source_quality_details": [
          "sec_filing",
          "secondary_site"
        ],
        "event_verification_status": "verified",
        "event_days_old": 7,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      },
      {
        "date": "2026-08-08",
        "title": "分析報告：OPI 儘管現金流改善，債務負擔仍構成壓力",
        "impact_direction": "負向",
        "impact_severity": 4,
        "confidence": "中",
        "summary_30": "分析指出OPI雖減債，但17億美元債務及2027年到期信貸設施仍是關鍵壓力。",
        "links": [
          "Simply Wall St"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "secondary_site",
        "event_source_quality_details": [
          "secondary_site"
        ],
        "event_verification_status": "unverified",
        "event_days_old": 12,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      },
      {
        "date": "2026-08-07",
        "title": "OPI 2026年第二季財報電話會議詳情與營運展望",
        "impact_direction": "中性",
        "impact_severity": 4,
        "confidence": "高",
        "summary_30": "管理層討論Q2業績、資產出售策略、2027年到期債務再融資計劃及未來展望。",
        "links": [
          "OPI Earnings Call Transcript",
          "Seeking Alpha",
          "TradingView News"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "secondary_site",
        "event_source_quality_details": [
          "secondary_site"
        ],
        "event_verification_status": "unverified",
        "event_days_old": 13,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      },
      {
        "date": "2026-08-07",
        "title": "主要股東 Redwood Capital Management 申報擬出售 100 萬股普通股",
        "impact_direction": "負向",
        "impact_severity": 3,
        "confidence": "高",
        "summary_30": "大股東 Redwood 申報售 100 萬股，價值約 $1971 萬。",
        "links": [
          "SEC Filing"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "sec_filing",
        "event_source_quality_details": [
          "sec_filing"
        ],
        "event_verification_status": "verified",
        "event_days_old": 13,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      }
    ],
    "綜合分析": "Stage 2 AI 合併未完成；已由程式保留高可信 Stage 1 近期事件，事件權重偏負面（-10）。",
    "事件總分": "正向0 / 負向10 / 總分-10",
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
        "value": "77.9",
        "unit": "%",
        "period": "2026Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "Office Properties Income Trust Q2 2026 財報 / SEC 10-Q",
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
        "note": "截至 2026 年 6 月 30 日的投資組合整體出租率。",
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
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "consistent_with_prior_range",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "77.9%",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260819",
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
        "source": "Office Properties Income Trust Q2 2026 財報簡報 / SEC 8-K",
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
        "note": "2026 年第二季度 Normalized FFO 總額。其中 Successor Period (6/18-6/30) 為 $4.5M，Predecessor Period (4/1-6/17) 為 $15.1M。",
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
        "value": "425000000 USD (2027/01); 15000000 USD (2026/11); 30000000 USD (2027/02)",
        "unit": "USD/date",
        "period": "2026Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "Office Properties Income Trust Q2 2026 財報 / SEC 10-Q / SEC 8-K",
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
        "note": "包括 $4.25 億循環信貸額度 (2027 年 1 月到期)；以及 2029 年票據要求償還的 $15M (2026 年 11 月) 和 $30M (2027 年 2 月)。",
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
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "partially_verified",
        "metric_consistency_status": "cross_run_conflict",
        "metric_consistency_reason": "同 period / definition 前值=425M (Jan 2027), 300M (Mar 2029), 385M (Dec 2029), 420M (Jun 2031)，本次=425000000 USD (2027/01); 15000000 USD (2026/11); 30000000 USD (2027/02)；區間不重疊。",
        "cross_run_consistency_status": "value_changed_same_definition",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "425M (Jan 2027), 300M (Mar 2029), 385M (Dec 2029), 420M (Jun 2031)",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260817",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 前值=425M (Jan 2027), 300M (Mar 2029), 385M (Dec 2029), 420M (Jun 2031)，本次=425000000 USD (2027/01); 15000000 USD (2026/11); 30000000 USD (2027/02)；區間不重疊。"
      },
      {
        "ticker": "OPI",
        "metric_name": "Liquidity / cash availability",
        "metric_category": "流動性",
        "value": "51000000 (非限制); 53000000 (限制)",
        "unit": "USD",
        "period": "2026Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "Office Properties Income Trust Q2 2026 財報電話會議稿 / SEC 10-Q / SEC 8-K",
        "source_url_or_name": "SeekingAlpha",
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
        "note": "截至 2026 年 6 月 30 日的非限制現金與限制現金。",
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
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "consistent_with_prior_range",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "51 USD Million (Unrestricted Cash); 53 USD Million (Restricted Cash)",
        "cross_run_previous_period": "2026Q2",
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
        "reason": "同 period / definition 前值=425M (Jan 2027), 300M (Mar 2029), 385M (Dec 2029), 420M (Jun 2031)，本次=425000000 USD (2027/01); 15000000 USD (2026/11); 30000000 USD (2027/02)；區間不重疊。",
        "risk_impact": "再融資失敗可能導致重整或資產賤售。",
        "previous_value": "425M (Jan 2027), 300M (Mar 2029), 385M (Dec 2029), 420M (Jun 2031)",
        "current_value": "425000000 USD (2027/01); 15000000 USD (2026/11); 30000000 USD (2027/02)",
        "period": "2026Q2",
        "definition_scope": "",
        "calculation_basis": "",
        "acceptance_criteria": "以同一官方定義重新查核；若為不同口徑，改填不同 definition_scope / calculation_basis，不得覆寫。"
      }
    ],
    "dropped_old_events": [],
    "event_date_filter_summary": {
      "lookback_days": 14,
      "cutoff_date": "2026-08-07",
      "today": "2026-08-20",
      "kept_recent": 4,
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
          "metric_value": "425000000 USD (2027/01); 15000000 USD (2026/11); 30000000 USD (2027/02)",
          "missing_reason": "同 period / definition 前值=425M (Jan 2027), 300M (Mar 2029), 385M (Dec 2029), 420M (Jun 2031)，本次=425000000 USD (2027/01); 15000000 USD (2026/11); 30000000 USD (2027/02)；區間不重疊。",
          "verification_after_reconcile": "partially_verified",
          "cross_run_consistency_status": "value_changed_same_definition",
          "definition_scope": "",
          "calculation_basis": ""
        }
      ]
    }
  },
  {
    "target_name": "AXS-E",
    "events": [
      {
        "date": "2026-08-19",
        "title": "AXIS Capital 任命北美金融線、項目及加拿大業務主管",
        "impact_direction": "中性",
        "impact_severity": 1,
        "confidence": "高",
        "summary_30": "AXIS Capital任命Jim Rhyner為北美金融線、項目及加拿大業務主管，屬高階管理層變動。",
        "links": [
          "AXIS Capital Investor Relations"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "official_ir",
        "event_source_quality_details": [
          "official_ir"
        ],
        "event_verification_status": "verified",
        "event_days_old": 1,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      },
      {
        "date": "2026-08-17",
        "title": "Simply Wall St 分析 AXIS Capital (AXS) 領導層變動與普通股股價表現",
        "impact_direction": "中性",
        "impact_severity": 2,
        "confidence": "中",
        "summary_30": "Simply Wall St 報導 AXS 領導層變動與普通股近期下跌，但公司基本面穩健，長期看漲。",
        "links": [
          "Simply Wall St News"
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
      },
      {
        "date": "2026-08-14",
        "title": "Seeking Alpha 評估 AXS-E 優先股殖利率競爭力與穩健 Q2 財報",
        "impact_direction": "正向",
        "impact_severity": 3,
        "confidence": "中",
        "summary_30": "Seeking Alpha 報告指 AXS-E 優先股因Q2財報良好、信評佳而具高殖利率吸引力。",
        "links": [
          "Seeking Alpha"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "secondary_site",
        "event_source_quality_details": [
          "secondary_site"
        ],
        "event_verification_status": "unverified",
        "event_days_old": 6,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      },
      {
        "date": "2026-08-14",
        "title": "Zacks Research 下調 AXIS Capital 評級及盈餘預期",
        "impact_direction": "負向",
        "impact_severity": 3,
        "confidence": "中",
        "summary_30": "Zacks將AXIS Capital評級下調至「強力賣出」，並大幅下調2026及2027財年EPS預期，反映Q2業績未達預期。",
        "links": [
          "MarketBeat"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "secondary_site",
        "event_source_quality_details": [
          "secondary_site"
        ],
        "event_verification_status": "unverified",
        "event_days_old": 6,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      },
      {
        "date": "2026-08-14",
        "title": "Seeking Alpha 正面分析 AXS-E 優先股",
        "impact_direction": "正向",
        "impact_severity": 2,
        "confidence": "中",
        "summary_30": "Seeking Alpha報告指出AXS-E優先股具競爭性收益與穩健信用品質，適合收益型投資人。",
        "links": [
          "SeekingAlpha"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "unknown",
        "event_source_quality_details": [
          "unknown"
        ],
        "event_verification_status": "unverified",
        "event_days_old": 6,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      },
      {
        "date": "2026-08-08",
        "title": "AXIS Capital 公佈穩健的第二季度業績，承保盈利能力改善",
        "impact_direction": "正向",
        "impact_severity": 4,
        "confidence": "高",
        "summary_30": "AXIS Capital Q2業績超出預期，綜合費用率改善至92.5%，反映承保業務表現穩健。",
        "links": [
          "AXIS Investor Relations",
          "PRNewswire"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "official_ir",
        "event_source_quality_details": [
          "official_ir",
          "press_release"
        ],
        "event_verification_status": "verified",
        "event_days_old": 12,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      },
      {
        "date": "2026-08-08",
        "title": "AXIS Capital 宣佈其Series E優先股AXS-E的季度股利",
        "impact_direction": "正向",
        "impact_severity": 3,
        "confidence": "高",
        "summary_30": "公司董事會宣佈按期支付AXS-E優先股的季度現金股利，確認現金流穩定性。",
        "links": [
          "AXIS Investor Relations",
          "BusinessWire"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "official_ir",
        "event_source_quality_details": [
          "official_ir",
          "press_release"
        ],
        "event_verification_status": "verified",
        "event_days_old": 12,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      }
    ],
    "綜合分析": "Stage 2 AI 合併未完成；已由程式保留高可信 Stage 1 近期事件，事件權重偏正面（+9）。",
    "事件總分": "正向12 / 負向3 / 總分+9",
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
        "value": "92.5%",
        "unit": "%",
        "period": "2026Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "AXIS Capital Holdings Q2 2026 Earnings Release",
        "source_url_or_name": "AXIS Investor Relations",
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
        "note": "數值低於100%表示承保業務獲利。",
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
        "metric_consistency_reason": "同 period / definition 前值=93.1，本次=92.5%；區間不重疊。",
        "cross_run_consistency_status": "value_changed_same_definition",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "93.1",
        "cross_run_previous_period": "2026 Q2",
        "cross_run_previous_report_date": "20260818",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 前值=93.1，本次=92.5%；區間不重疊。"
      },
      {
        "ticker": "AXS-E",
        "metric_name": "Catastrophe losses",
        "metric_category": "巨災損失",
        "value": "75 million",
        "unit": "USD",
        "period": "2026Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "AXIS Capital Holdings Q2 2026 Earnings Release",
        "source_url_or_name": "AXIS Investor Relations",
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
        "note": "數值為Q2淨巨災損失。",
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
        "metric_consistency_reason": "同 period / definition 前值=80，本次=75 million；區間不重疊。",
        "cross_run_consistency_status": "value_changed_same_definition",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "80",
        "cross_run_previous_period": "2026 Q2",
        "cross_run_previous_report_date": "20260818",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 前值=80，本次=75 million；區間不重疊。"
      },
      {
        "ticker": "AXS-E",
        "metric_name": "Preferred dividend status",
        "metric_category": "配息狀態",
        "value": "已支付並已宣告下一期",
        "unit": "status",
        "period": "2026Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "AXIS Capital Investor Relations",
        "source_url_or_name": "AXIS Capital Holdings Limited - Investor Relations",
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
        "note": "2026年Q2股息已於7月15日支付，下次除息日預計為9月30日。",
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
        "cross_run_previous_value": "已支付且預期穩定",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260819",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 有前值，但數值型態無法安全比較。"
      }
    ],
    "metric_integrity_issues": [],
    "metric_alias_acceptances": [
      {
        "parent_ticker": "AXS-E",
        "accepted_alias": "AXS",
        "metric_name": "Combined ratio"
      },
      {
        "parent_ticker": "AXS-E",
        "accepted_alias": "AXS",
        "metric_name": "Catastrophe losses"
      }
    ],
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
        "metric_name": "Combined ratio",
        "reason": "同 period / definition 前值=93.1，本次=92.5%；區間不重疊。",
        "risk_impact": "承保虧損會削弱資本與優先股安全邊際。",
        "previous_value": "93.1",
        "current_value": "92.5%",
        "period": "2026Q2",
        "definition_scope": "",
        "calculation_basis": "",
        "acceptance_criteria": "以同一官方定義重新查核；若為不同口徑，改填不同 definition_scope / calculation_basis，不得覆寫。"
      },
      {
        "ticker": "AXS-E",
        "priority": "P1",
        "missing_type": "metric_cross_run_consistency",
        "metric_name": "Catastrophe losses",
        "reason": "同 period / definition 前值=80，本次=75 million；區間不重疊。",
        "risk_impact": "可能壓縮盈餘與資本。",
        "previous_value": "80",
        "current_value": "75 million",
        "period": "2026Q2",
        "definition_scope": "",
        "calculation_basis": "",
        "acceptance_criteria": "以同一官方定義重新查核；若為不同口徑，改填不同 definition_scope / calculation_basis，不得覆寫。"
      }
    ],
    "dropped_old_events": [],
    "event_date_filter_summary": {
      "lookback_days": 14,
      "cutoff_date": "2026-08-07",
      "today": "2026-08-20",
      "kept_recent": 7,
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
          "metric_value": "92.5%",
          "missing_reason": "同 period / definition 前值=93.1，本次=92.5%；區間不重疊。",
          "verification_after_reconcile": "partially_verified",
          "cross_run_consistency_status": "value_changed_same_definition",
          "definition_scope": "",
          "calculation_basis": ""
        },
        {
          "ticker": "AXS-E",
          "metric_name": "Catastrophe losses",
          "metric_value": "75 million",
          "missing_reason": "同 period / definition 前值=80，本次=75 million；區間不重疊。",
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
    "events": [
      {
        "date": "2026-08-19",
        "title": "Q2財報亮眼並上調全年財測，分析師上調評級",
        "impact_direction": "正向",
        "impact_severity": 5,
        "confidence": "高",
        "summary_30": "福特Q2獲利超預期，上調2026年EBIT與自由現金流指引，獲多家投行上調評級。",
        "links": [
          "Business Wire",
          "MarketBeat",
          "SeekingAlpha",
          "StocksToTrade",
          "Timothy Sykes",
          "Investing.com",
          "GuruFocus"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "press_release",
        "event_source_quality_details": [
          "press_release",
          "secondary_site"
        ],
        "event_verification_status": "partially_verified",
        "event_days_old": 1,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      },
      {
        "date": "2026-08-19",
        "title": "福特據報計劃推出Bronco皮卡並將Lincoln生產線遷回美國",
        "impact_direction": "正向",
        "impact_severity": 3,
        "confidence": "中",
        "summary_30": "福特據報計劃於十年末推出Bronco皮卡，並將Lincoln生產線遷回美國，有助於國內就業。",
        "links": [
          "Automotive News",
          "The White House",
          "TFLtruck"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "unknown",
        "event_source_quality_details": [
          "unknown"
        ],
        "event_verification_status": "unverified",
        "event_days_old": 1,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      },
      {
        "date": "2026-08-17",
        "title": "WSJ報導福特正轉向為AI資料中心提供電池儲能設備",
        "impact_direction": "正向",
        "impact_severity": 3,
        "confidence": "中",
        "summary_30": "華爾街日報稱福特正將業務轉向AI資料中心電池儲能設備。",
        "links": [
          "AI Weekly",
          "The Enterprise Journal"
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
        "date": "2026-08-17",
        "title": "Fitch確認福特信貸車輛資產信託評級",
        "impact_direction": "中性",
        "impact_severity": 2,
        "confidence": "高",
        "summary_30": "Fitch確認福特信貸2026-REV2信託評級，顯示其證券化池信用品質穩定。",
        "links": [
          "Fitch Ratings"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "rating_agency",
        "event_source_quality_details": [
          "rating_agency"
        ],
        "event_verification_status": "verified",
        "event_days_old": 3,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      },
      {
        "date": "2026-08-12",
        "title": "美國第二季汽車貸款嚴重逾期率達15年新高",
        "impact_direction": "負向",
        "impact_severity": 4,
        "confidence": "高",
        "summary_30": "紐約聯儲報告，2026年Q2美國汽車貸款嚴重逾期率創15年新高，對福特信貸構成風險。",
        "links": [
          "CBT News",
          "Auto Dealer Today",
          "Morningstar DBRS",
          "Federal Reserve Bank of New York"
        ],
        "merged_duplicate_count": 2,
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
        "date": "2026-08-12",
        "title": "規劃2030年起將部分Lincoln車款生產線從中國遷回美國",
        "impact_direction": "正向",
        "impact_severity": 3,
        "confidence": "高",
        "summary_30": "因應美國關稅與法規，福特計劃2030年起將部分Lincoln生產遷回美國。",
        "links": [
          "Reuters",
          "SeekingAlpha",
          "MarketScreener",
          "Just Auto",
          "CarsDirect",
          "Investing.com"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "mainstream_media",
        "event_source_quality_details": [
          "mainstream_media"
        ],
        "event_verification_status": "partially_verified",
        "event_days_old": 8,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      },
      {
        "date": "2026-08-07",
        "title": "福特Q2財報後續討論與新款電動皮卡Fathom",
        "impact_direction": "正向",
        "impact_severity": 3,
        "confidence": "中",
        "summary_30": "Q2盈利超預期並上調全年指引，分析師多正面評價，新款電動皮卡Fathom亦受關注。",
        "links": [
          "Zacks",
          "MarketBeat",
          "SeekingAlpha",
          "Insidermonkey",
          "Benzinga",
          "WSJ"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "mainstream_media",
        "event_source_quality_details": [
          "mainstream_media",
          "secondary_site"
        ],
        "event_verification_status": "partially_verified",
        "event_days_old": 13,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      },
      {
        "date": "2026-08-07",
        "title": "傳聞將推出四門Mustang混合動力車款",
        "impact_direction": "中性",
        "impact_severity": 2,
        "confidence": "中",
        "summary_30": "華爾街日報報導福特計劃推出四門混合動力Mustang，可能採V-8引擎。",
        "links": [
          "Investing.com",
          "StocksToTrade"
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
    "綜合分析": "已排除低可信來源並合併重複事件；目前事件權重為偏正面（+13）。",
    "事件總分": "正向17 / 負向4 / 總分+13",
    "new_sources_found": [],
    "event_merge_source": "stage1_deterministic_fallback",
    "excluded_low_trust_event_count": 1,
    "merged_duplicate_event_count": 1,
    "event_dedup_patch_version": "1.3.3",
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
        "source": "Ford Motor Company Q2 2026 Earnings Report / SEC 8-K",
        "source_url_or_name": "Business Wire, SEC Filing, MarketBeat, Investing.com (GuruFocus)",
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
        "note": "2026年全年調整後自由現金流指引上調至60-70億美元。",
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
        "period": "2026H1 (as of June 30, 2026)",
        "status": "資料不足",
        "confidence": "低",
        "source": "S&P Global Ratings / Fitch Ratings",
        "source_url_or_name": "S&P Global Ratings / Fitch Ratings",
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
        "note": "截至2026年上半年，福特信貸整體逾期率及淨損失率均較去年同期上升，需留意汽車金融風險。",
        "semantic_match_status": "rejected",
        "issuer_scope": "unknown / not explicitly Ford Credit",
        "metric_value_type": "rate_percentage",
        "rejected_candidate_reason": "Delinq issuer scope 未明確指向 Ford Credit portfolio；metric_name/source_candidates 不可作為 scope 證據。",
        "rejected_candidate_value": "逾期率 1.46% (較去年同期 1.38% 上升); 淨損失率 0.60% (較去年同期 0.54% 上升)",
        "rejected_candidate_source": "S&P Global Ratings / Fitch Ratings",
        "semantic_guard_version": "1.3.6",
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
        "metric_period_parsed_date": "2026-08-20",
        "metric_period_parse_status": "year_only",
        "metric_period_type": "year",
        "metric_period_freshness": "fresh",
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
        "period": "2026Q2",
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
        "note": "2026年第二季度的實際召回或保固成本未在官方財報中明確列出。",
        "semantic_match_status": "rejected",
        "issuer_scope": "Ford Motor Company recall/warranty",
        "metric_value_type": "missing",
        "rejected_candidate_reason": "Recall 只接受明確 actual expense/accrual/cost 金額。",
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
        "metric_period_parsed_date": "2026-06-30",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
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
        "reason": "Delinq issuer scope 未明確指向 Ford Credit portfolio；metric_name/source_candidates 不可作為 scope 證據。",
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
        "rejected_candidate_value": "逾期率 1.46% (較去年同期 1.38% 上升); 淨損失率 0.60% (較去年同期 0.54% 上升)",
        "rejected_candidate_source": "S&P Global Ratings / Fitch Ratings",
        "acceptance_criteria": "F-B Delinq：只接受 Ford Credit portfolio 明確 rate/percentage/bps；F-B Recall：只接受明確 actual recall/warranty expense/accrual/cost。"
      },
      {
        "ticker": "F-B",
        "priority": "P1",
        "missing_type": "metric_semantic_rejection",
        "metric_name": "Recall / warranty cost",
        "reason": "Recall 只接受明確 actual expense/accrual/cost 金額。",
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
      "cutoff_date": "2026-08-07",
      "today": "2026-08-20",
      "kept_recent": 8,
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
    "events": [
      {
        "date": "2026-08-19",
        "title": "JPMorgan Chase & Co. 下調Array Digital Infrastructure目標價",
        "impact_direction": "負向",
        "impact_severity": 2,
        "confidence": "中",
        "summary_30": "摩根大通將Array Digital Infrastructure的股票目標價從54美元下調至45美元，但維持「增持」評級。",
        "links": [
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
        "date": "2026-08-19",
        "title": "TDS 宣布 2026 年第三季度普通股及優先股股息",
        "impact_direction": "中性",
        "impact_severity": 1,
        "confidence": "高",
        "summary_30": "TDS（Array母公司）董事會宣告第三季度股息，按季支付普通股及優先股股息。",
        "links": [
          "PR Newswire",
          "Investing.com"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "press_release",
        "event_source_quality_details": [
          "press_release"
        ],
        "event_verification_status": "partially_verified",
        "event_days_old": 1,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      },
      {
        "date": "2026-08-19",
        "title": "TDS宣佈2026年第三季股息",
        "impact_direction": "中性",
        "impact_severity": 1,
        "confidence": "高",
        "summary_30": "UScellular母公司TDS宣佈季度股息，為例行性財務活動。",
        "links": [
          "PRNewswire"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "press_release",
        "event_source_quality_details": [
          "press_release"
        ],
        "event_verification_status": "partially_verified",
        "event_days_old": 1,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      },
      {
        "date": "2026-08-10",
        "title": "T-Mobile在收購UScellular後裁員4,500多人",
        "impact_direction": "中性",
        "impact_severity": 2,
        "confidence": "高",
        "summary_30": "T-Mobile整合UScellular資產後進行裁員，影響其部分債務承擔方。",
        "links": [
          "Light Reading"
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
      },
      {
        "date": "2026-08-07",
        "title": "Array Digital Infrastructure 公布強勁 2026 年第二季度財報並更新財測",
        "impact_direction": "正向",
        "impact_severity": 4,
        "confidence": "高",
        "summary_30": "Array 報告 Q2 營收和淨利顯著增長，受益於光譜出售，並上調 2026 年 EBITDA 財測。",
        "links": [
          "SEC Filing",
          "PR Newswire",
          "Array Digital Infrastructure Investor Relations"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "sec_filing",
        "event_source_quality_details": [
          "sec_filing",
          "official_ir",
          "press_release"
        ],
        "event_verification_status": "verified",
        "event_days_old": 13,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      },
      {
        "date": "2026-08-07",
        "title": "TDS公佈2026年第二季業績，Array實現塔位租賃增長並完成頻譜出售",
        "impact_direction": "正向",
        "impact_severity": 4,
        "confidence": "高",
        "summary_30": "Array塔位業務增長；完成10億美元頻譜出售，強化資產負債表。TDS提議收購Array剩餘股份。",
        "links": [
          "Telephone and Data Systems Investor Relations",
          "StreetInsider",
          "Public Technologies"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "official_ir",
        "event_source_quality_details": [
          "official_ir"
        ],
        "event_verification_status": "verified",
        "event_days_old": 13,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      }
    ],
    "綜合分析": "Stage 2 AI 合併未完成；已由程式保留高可信 Stage 1 近期事件，事件權重偏正面（+6）。",
    "事件總分": "正向8 / 負向2 / 總分+6",
    "new_sources_found": [],
    "event_merge_source": "stage1_deterministic_fallback",
    "excluded_low_trust_event_count": 0,
    "merged_duplicate_event_count": 0,
    "event_dedup_patch_version": "1.3.3",
    "metric_data": [
      {
        "ticker": "UZD",
        "metric_name": "Issuer / guarantor status",
        "metric_category": "法律實體",
        "value": "Array Digital Infrastructure, Inc. (原 United States Cellular Corporation)",
        "unit": "status",
        "period": "2026Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "SEC Filing (Array Digital Infrastructure 8-K)",
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
        "note": "UZD 債券已由 United States Cellular Corporation 轉為 Array Digital Infrastructure, Inc. 發行。",
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
        "cross_run_previous_value": "United States Cellular Corporation (USM)",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260819",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 有前值，但數值型態無法安全比較。"
      },
      {
        "ticker": "UZD",
        "metric_name": "Asset sale proceeds and use of funds",
        "metric_category": "資產出售",
        "value": "2026年第二季度出售光譜資產收益總計約11.612億美元；2026年6月25日支付每股11美元特別股息。",
        "unit": "USD/status",
        "period": "2026Q2 (截至2026年6月30日)",
        "status": "已取得",
        "confidence": "高",
        "source": "Array Digital Infrastructure Q2 2026 Earnings Release / SEC Filing",
        "source_url_or_name": "PR Newswire, SEC Filing",
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
        "note": "主要資產出售（無線業務給 T-Mobile）已於 2025 年完成，涉及約 17 億美元債務承擔。本次數據為 2026 年第二季度報告的資產出售及股息分配情況。",
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
        "metric_period_parsed_date": "2026-06-30",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "date",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "verified",
        "metric_consistency_status": "consistent",
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "consistent_with_prior_range",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "Array已完成對Verizon及其他方大部分非C-Band頻譜的出售，部分銷售所得用於TDS於2026年6月25日支付每股11美元的特別股息。此前，2025年8月1日向T-Mobile出售無線業務及部分頻譜，獲得43億美元總對價（含26億現金及約17億美元債務承擔）。",
        "cross_run_previous_period": "2026Q2 (近期出售完成), 2025-2026 (總體出售與資金使用)",
        "cross_run_previous_report_date": "20260817",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 數值表達不同，但目前值落在前一可信區間內。"
      },
      {
        "ticker": "UZD",
        "metric_name": "Debt assumption / redemption status",
        "metric_category": "債務處理",
        "value": "不適用 (過去已發生)",
        "unit": "status",
        "period": "2025-08",
        "status": "資料不足",
        "confidence": "中",
        "source": "Fitch Ratings / Business Wire",
        "source_url_or_name": "Fitch Ratings, T-Mobile Exchange Offer Announcement",
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
        "note": "T-Mobile於2025年5月發起對UScellular部分債務的交換要約，並在2025年8月完成約17億美元債務承擔。Fitch曾預計部分長期零售債券（如UZD）可能未完全交換而續存於UScellular (Array)。最近14日內無UZD特有的新贖回或債務承擔消息。",
        "source_quality_primary": "rating_agency",
        "source_quality": "rating_agency",
        "source_quality_details": [
          "rating_agency",
          "press_release"
        ],
        "source_candidate_quality_details": [
          "sec_filing",
          "official_ir",
          "exchange_notice"
        ],
        "source_conflict_flag": false,
        "source_conflict_reason": "",
        "metric_period_parsed_date": "2025-12-31",
        "metric_period_parse_status": "year_only",
        "metric_period_type": "year",
        "metric_period_freshness": "acceptable_recent",
        "metric_integrity_status": "pass",
        "metric_verification_status": "data_missing",
        "metric_consistency_status": "conflict_with_missing_data",
        "metric_consistency_reason": "在指定日期範圍內（最近14日）未找到針對UZD債券剩餘部分的最新承擔、契約修改或贖回狀態更新，主要債務交換事件發生於2025年。",
        "metric_consistency_missing_type": "metric_update",
        "cross_run_consistency_status": "no_prior_same_period",
        "definition_scope": "",
        "calculation_basis": ""
      }
    ],
    "missing_data": [
      {
        "ticker": "UZD",
        "priority": "P0",
        "missing_type": "metric_consistency",
        "metric_name": "Debt assumption / redemption status",
        "reason": "在指定日期範圍內（最近14日）未找到針對UZD債券剩餘部分的最新承擔、契約修改或贖回狀態更新，主要債務交換事件發生於2025年。",
        "risk_impact": "缺乏最新的債務處理資訊會導致對該債券未來付息及本金償付安全性的評估不夠全面。儘管已知歷史事件，但仍需確認最新狀態。",
        "source_candidates": [
          "SEC 8-K",
          "UScellular Investor Relations",
          "TDS Investor Relations",
          "Bloomberg",
          "Reuters"
        ],
        "acceptance_criteria": "下次需填入 value、period、source；若查無，需說明查詢過哪些來源。",
        "missing_type_original": "metric_update",
        "conflict_with_metric_data": true,
        "metric_value_present": "不適用 (過去已發生)",
        "metric_source_present": "Fitch Ratings / Business Wire",
        "metric_verification_after_reconcile": "data_missing"
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
      "cutoff_date": "2026-08-07",
      "today": "2026-08-20",
      "kept_recent": 6,
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
          "metric_value": "不適用 (過去已發生)",
          "missing_reason": "在指定日期範圍內（最近14日）未找到針對UZD債券剩餘部分的最新承擔、契約修改或贖回狀態更新，主要債務交換事件發生於2025年。",
          "verification_after_reconcile": "data_missing",
          "cross_run_consistency_status": "no_prior_same_period",
          "definition_scope": "",
          "calculation_basis": ""
        }
      ]
    },
    "market_quote": {
      "ticker": "UZD",
      "security_name_expected": "Array Digital Infrastructure / former United States Cellular 6.25% Senior Notes due 2069",
      "exchange_expected": "NYSE",
      "latest_price": 19.198999,
      "price_as_of": "2026-08-19",
      "open": 18.969999313354492,
      "high": 19.198999404907227,
      "low": 18.936500549316406,
      "volume": 2087,
      "bid": null,
      "ask": null,
      "annual_interest": 1.5625,
      "current_yield": 8.1384,
      "quote_source": "Yahoo Finance chart (query1.finance.yahoo.com)",
      "source_host": "query1.finance.yahoo.com",
      "quote_status": "ok",
      "freshness_status": "fresh",
      "security_identity_status": "matched_symbol",
      "source_timestamp": 1787146200,
      "market_quote_patch_version": "1.3.7",
      "returned_symbol": "UZD",
      "currency": "USD",
      "exchange_name": "NYQ",
      "instrument_type": "EQUITY",
      "regular_market_price_meta": 19.199,
      "regular_market_time_meta": 1787162817,
      "reference_session_date": "2026-08-19",
      "weekday_gap": 0,
      "http_status": 200,
      "request_url": "https://query1.finance.yahoo.com/v8/finance/chart/UZD",
      "request_attempt": 1,
      "attempts": [
        {
          "source_host": "query1.finance.yahoo.com",
          "quote_status": "ok",
          "freshness_status": "fresh",
          "price_as_of": "2026-08-19",
          "latest_price": 19.198999,
          "error": null
        },
        {
          "source_host": "query2.finance.yahoo.com",
          "quote_status": "ok",
          "freshness_status": "fresh",
          "price_as_of": "2026-08-19",
          "latest_price": 19.198999,
          "error": null
        }
      ],
      "source_validation": "cross_checked",
      "source_crosscheck_price": 19.198999,
      "source_crosscheck_host": "query2.finance.yahoo.com",
      "source_conflict_pct": 0.0
    }
  }
]
```

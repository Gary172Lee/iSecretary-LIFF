# USPreferredStockDayInfo 每日情報報告

- 生成時間（台灣）：2026-08-18 11:24:42
- 對應 PDF：Stock_News_Report_20260818_112441.pdf
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
- 綜合分析：Stage 2 AI 合併未完成；已由程式保留高可信 Stage 1 近期事件，事件權重偏負面（-1）。
- 事件 1：2026-08-14｜Lumen Technologies 股價下跌，市場對轉型前景看法分歧｜recent_event
  - 影響：負向｜嚴重性：2｜信心度：中
  - 摘要：LUMN 股價過去 90 天下跌 36%，市場對其轉型存疑。
  - 來源：Investing.com
  - 日期過濾：kept_recent｜來源品質：unknown｜驗證：unverified
- 事件 2：2026-08-11｜華爾街投行下調Lumen目標價，分析師持謹慎態度｜recent_event
  - 影響：負向｜嚴重性：2｜信心度：中
  - 摘要：花旗、富國銀行及高盛下調Lumen目標價，市場觀點趨謹慎。
  - 來源：MarketBeat、Investing.com
  - 日期過濾：kept_recent｜來源品質：secondary_site｜驗證：unverified
- 事件 3：2026-08-06｜Lumen Technologies CEO增持公司股份｜recent_event
  - 影響：正向｜嚴重性：3｜信心度：高
  - 摘要：CEO買入10萬股LUMN股票，顯示對公司前景信心。
  - 來源：Stock Titan、MarketBeat、SEC Filing
  - 日期過濾：kept_recent｜來源品質：sec_filing｜驗證：verified

### 2. BHFAL

- 事件總分：正向6 / 負向4 / 總分+2
- 綜合分析：已排除低可信來源並合併重複事件；目前事件權重為偏正面（+2）。
- 事件 1：2026-08-17｜Brighthouse Financial 宣布發放優先股股息｜recent_event
  - 影響：正向｜嚴重性：2｜信心度：高
  - 摘要：公司宣布如期發放多類優先股季度股息，顯示財務能力穩健。
  - 來源：Business Wire、BusinessWire、Nasdaq
  - 日期過濾：kept_recent｜來源品質：exchange_notice｜驗證：verified
- 事件 2：2026-08-07｜報導稱Aquarian收購案涉及會計問題｜recent_event
  - 影響：負向｜嚴重性：4｜信心度：中
  - 摘要：報導指Brighthouse Reinsurance存在會計問題，可能影響Aquarian收購。
  - 來源：Seeking Alpha、SeekingAlpha
  - 日期過濾：kept_recent｜來源品質：secondary_site｜驗證：unverified
- 事件 3：2026-08-06｜Brighthouse Financial 公布 2026 年第二季度財報｜recent_event
  - 影響：正向｜嚴重性：4｜信心度：高
  - 摘要：RBC比率430%-450%，控股公司流動資產9億美元，法定資本49億美元；併購案持續推進，但營收不及預期。
  - 來源：Business Wire、GuruFocus、MarketBeat、TradingView、Perplexity、BusinessWire、StockTitan、Brighthouse Financial Investor Relations、Morningstar、Webull、SEC Filing
  - 日期過濾：kept_recent｜來源品質：sec_filing｜驗證：verified
- 事件 4：2026-08-06｜提交 2026 年第二季度 10-Q 報告｜recent_event
  - 影響：中性｜嚴重性：1｜信心度：高
  - 摘要：公司向 SEC 提交了截至 2026 年 6 月 30 日的季度報告，確認財務數據。
  - 來源：SEC Filing、TradingView
  - 日期過濾：kept_recent｜來源品質：sec_filing｜驗證：verified

### 3. OPI

- 事件總分：正向7 / 負向6 / 總分+1
- 綜合分析：已排除低可信來源並合併重複事件；目前事件權重為偏正面（+1）。
- 事件 1：2026-08-14｜主要股東Redwood Capital Management減持OPI股份｜recent_event
  - 影響：負向｜嚴重性：3｜信心度：高
  - 摘要：主要股東Redwood Capital Management近期持續出售OPI股份，顯示大股東減持動態。
  - 來源：MarketBeat、Stock Titan
  - 日期過濾：kept_recent｜來源品質：secondary_site｜驗證：unverified
- 事件 2：2026-08-13｜Barclays PLC 揭露取得 OPI 8.43% 被動股權｜recent_event
  - 影響：正向｜嚴重性：2｜信心度：高
  - 摘要：Barclays PLC揭露取得OPI 8.43%股權。
  - 來源：SEC Filing (SC 13G)
  - 日期過濾：kept_recent｜來源品質：sec_filing｜驗證：verified
- 事件 3：2026-08-06｜OPI公布2026年第二季財報，債務大幅削減並重組成功｜recent_event
  - 影響：正向｜嚴重性：5｜信心度：高
  - 摘要：OPI Q2財報：重組債務減$7.14億，FFO$1900萬，出租率77.9%。
  - 來源：Seeking Alpha、newsfilter.io、BusinessWire、Nasdaq、SEC Filing、OPI Investor Relations、SEC Filing (10-Q)、Kalkine、Morningstar、Stock Titan、Barchart.com、Simply Wall St、SeekingAlpha、Decode Investing
  - 日期過濾：kept_recent｜來源品質：sec_filing｜驗證：verified
- 事件 4：2026-08-06｜大股東Redwood Capital Management減持OPI股票｜recent_event
  - 影響：負向｜嚴重性：3｜信心度：高
  - 摘要：大股東Redwood Capital Management於8月減持OPI股票。
  - 來源：MarketBeat、SEC Filing (Form 4/A)
  - 日期過濾：kept_recent｜來源品質：sec_filing｜驗證：verified

### 4. AXS-E

- 事件總分：正向8 / 負向1 / 總分+7
- 綜合分析：Stage 2 AI 合併未完成；已由程式保留高可信 Stage 1 近期事件，事件權重偏正面（+7）。
- 事件 1：2026-08-17｜分析師探討AXIS資本在Meta訴訟背景下的網路責任保險風險｜recent_event
  - 影響：負向｜嚴重性：1｜信心度：中
  - 摘要：媒體討論AXIS資本在專業與網路責任險領域，可能受Meta訴訟影響的潛在風險。
  - 來源：Simply Wall St News、Kalkine Media
  - 日期過濾：kept_recent｜來源品質：secondary_site｜驗證：unverified
- 事件 2：2026-08-05｜AXIS Capital 宣布收購 DUAL 北美超額責任業務的續保權利｜recent_event
  - 影響：正向｜嚴重性：3｜信心度：高
  - 摘要：AXIS Capital 透過收購 DUAL 北美超額責任業務續保權利，擴大其專業保險產品線。
  - 來源：AXIS Capital Investor Relations、Press Releases
  - 日期過濾：kept_recent｜來源品質：official_ir｜驗證：verified
- 事件 3：2026-08-05｜AXIS Capital 同意收購 DUAL North America 的超額責任保險續保權｜recent_event
  - 影響：正向｜嚴重性：3｜信心度：高
  - 摘要：AXIS Capital 透過收購 DUAL North America 續保權以擴展業務，預計增強市場地位。
  - 來源：AXIS Investor Relations
  - 日期過濾：kept_recent｜來源品質：official_ir｜驗證：verified
- 事件 4：2026-08-05｜AXIS資本收購DUAL北美區超額責任業務的續保權並任命新領導｜recent_event
  - 影響：正向｜嚴重性：2｜信心度：高
  - 摘要：AXIS資本透過收購DUAL超額責任業務續保權強化意外險平台，並任命John Kopach為新領導。
  - 來源：AXIS Capital Holdings Investor Relations、MarketScreener、PRNewswire
  - 日期過濾：kept_recent｜來源品質：official_ir｜驗證：verified

### 5. F-B

- 事件總分：正向16 / 負向13 / 總分+3
- 綜合分析：Stage 2 AI 合併未完成；已由程式保留高可信 Stage 1 近期事件，事件權重偏正面（+3）。
- 事件 1：2026-08-17｜福特召回86,543輛Mach-E SUV，因後側窗玻璃可能脫落｜recent_event
  - 影響：負向｜嚴重性：3｜信心度：高
  - 摘要：福特因供應商組裝問題召回2023-2025年Mach-E車型，無事故傷害報告。
  - 來源：Kelley Blue Book
  - 日期過濾：kept_recent｜來源品質：unknown｜驗證：unverified
- 事件 2：2026-08-17｜Fitch授予Ford Credit汽車業主信託2026-REV2初步評級｜recent_event
  - 影響：正向｜嚴重性：2｜信心度：高
  - 摘要：Fitch對Ford Credit新資產擔保證券給予穩定評級，肯定其強勁信貸品質。
  - 來源：Fitch
  - 日期過濾：kept_recent｜來源品質：rating_agency｜驗證：verified
- 事件 3：2026-08-17｜Fitch確認Ford Credit資產擔保債券評級，展望穩定｜recent_event
  - 影響：正向｜嚴重性：2｜信心度：高
  - 摘要：Fitch對Ford Credit Auto Owner Trust 2026-REV2維持穩定評級，顯示其資產質量強勁。
  - 來源：Fitch Ratings
  - 日期過濾：kept_recent｜來源品質：rating_agency｜驗證：verified
- 事件 4：2026-08-17｜2027年Ford F-150 Raptor基本款降價4,010美元｜recent_event
  - 影響：中性｜嚴重性：2｜信心度：中
  - 摘要：福特F-150 Raptor基本款降價5%至74,995美元，以競爭對手，但部分功能減少。
  - 來源：CarsDirect
  - 日期過濾：kept_recent｜來源品質：unknown｜驗證：unverified
- 事件 5：2026-08-17｜福特Hypercar首次進行賽道測試，為2027年利曼賽事準備｜recent_event
  - 影響：正向｜嚴重性：1｜信心度：中
  - 摘要：福特新Hypercar於8月5日開始測試，將於2027年FIA世界耐力錦標賽首次亮相。
  - 來源：RoadandTrack.com
  - 日期過濾：kept_recent｜來源品質：unknown｜驗證：unverified
- 事件 6：2026-08-13｜Dbs Bank將福特汽車評級上調至「適度買入」｜recent_event
  - 影響：正向｜嚴重性：3｜信心度：中
  - 摘要：Dbs Bank看好福特前景，將其評級從「持有」上調至「適度買入」。
  - 來源：MarketBeat
  - 日期過濾：kept_recent｜來源品質：secondary_site｜驗證：unverified
- 事件 7：2026-08-13｜福特計劃自2030年起將部分Lincoln車型生產從中國轉移至美國｜recent_event
  - 影響：正向｜嚴重性：3｜信心度：高
  - 摘要：因高額關稅及中國技術限制，福特將調整Lincoln生產線，長期有利於美國市場。
  - 來源：Reuters、Benzinga、Just Auto、investingLive
  - 日期過濾：kept_recent｜來源品質：mainstream_media｜驗證：partially_verified
- 事件 8：2026-08-13｜福特宣布自2030年起增加美國Lincoln車款生產並逐步淘汰中國進口｜recent_event
  - 影響：正向｜嚴重性：2｜信心度：高
  - 摘要：福特長期戰略調整，強化本土製造，降低對中國進口依賴。
  - 來源：GuruFocus、Ford Company News
  - 日期過濾：kept_recent｜來源品質：secondary_site｜驗證：unverified
- 事件 9：2026-08-12｜美國第二季汽車貸款逾期率達15年新高｜recent_event
  - 影響：負向｜嚴重性：3｜信心度：中
  - 摘要：聯準會數據顯示，整體汽車貸款市場逾期率上升，對汽車金融構成潛在風險。
  - 來源：CBT News
  - 日期過濾：kept_recent｜來源品質：unknown｜驗證：unverified
- 事件 10：2026-08-12｜美國第二季度汽車貸款拖欠率創15年新高｜recent_event
  - 影響：負向｜嚴重性：3｜信心度：高
  - 摘要：紐約聯儲報告顯示，2026年第二季度美國汽車貸款嚴重拖欠率達2010年來最高。
  - 來源：CBT News、TransUnion
  - 日期過濾：kept_recent｜來源品質：unknown｜驗證：unverified
- 事件 11：2026-08-06｜福特召回2025-2026年Bronco車款，因引擎故障恐失動力｜recent_event
  - 影響：負向｜嚴重性：4｜信心度：高
  - 摘要：福特宣布召回2025-2026年Bronco、Explorer和Ranger，因引擎故障有失去動力的風險。
  - 來源：CarBuzz
  - 日期過濾：kept_recent｜來源品質：unknown｜驗證：unverified
- 事件 12：2026-08-06｜Zacks將福特汽車評級上調至「買入」｜recent_event
  - 影響：正向｜嚴重性：3｜信心度：中
  - 摘要：Zacks基於盈利預期上調福特評級，預示股價潛在上漲空間。
  - 來源：Zacks Investment Research
  - 日期過濾：kept_recent｜來源品質：secondary_site｜驗證：unverified

### 6. UZD

- 事件總分：正向4 / 負向3 / 總分+1
- 綜合分析：已排除低可信來源並合併重複事件；目前事件權重為偏正面（+1）。
- 事件 1：2026-08-07｜Array Digital Infrastructure (前身UScellular) 公布亮眼第二季度業績及頻譜出售收益｜recent_event
  - 影響：正向｜嚴重性：4｜信心度：高
  - 摘要：Array Digital Infrastructure公布Q2業績，頻譜出售推動收入及淨利潤顯著增長，完成多項頻譜交易。
  - 來源：PRNewswire、Array Digital Infrastructure Investor Relations、TDS Investor Relations、MarketScreener、SeekingAlpha
  - 日期過濾：kept_recent｜來源品質：official_ir｜驗證：verified
- 事件 2：2026-08-07｜Array Digital Infrastructure 支付特別股息｜recent_event
  - 影響：負向｜嚴重性：3｜信心度：高
  - 摘要：Array Digital Infrastructure宣布支付每股11美元特別股息，資金來自頻譜出售收益，流向股東。
  - 來源：PRNewswire、Array Digital Infrastructure Investor Relations、TDS Investor Relations
  - 日期過濾：kept_recent｜來源品質：official_ir｜驗證：verified

## 量化指標與資料缺口

- 量化監控框架版本：1.0
- 說明：v1 先建立每檔應追蹤指標與資料缺口；尚未取得官方數值時，會標示為「資料不足」。

### CTGG 量化監控
- Free cash flow｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：FCF 轉負或展望下修需警戒。
- Debt maturity and exchange offer terms｜狀態：已取得｜驗證：partially_verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：distressed exchange、順位弱化或擔保改變需警戒。
- Credit rating / outlook｜狀態：已取得｜驗證：verified｜來源品質：rating_agency｜期間新鮮度：fresh｜門檻：downgrade、negative outlook 或 selective default 評論需警戒。
- 資料缺口：1 項，關鍵資料缺漏時不可判定為綠燈。

### BHFAL 量化監控
- RBC ratio｜狀態：資料不足｜驗證：data_missing｜來源品質：press_release｜期間新鮮度：fresh｜門檻：低於 400% 黃燈；低於 350% 橙燈/紅燈；單季大幅下滑需警戒。
- Statutory capital and surplus｜狀態：已取得｜驗證：partially_verified｜來源品質：press_release｜期間新鮮度：fresh｜門檻：連續下降或重大減損需警戒。
- Holding company cash and liquid assets｜狀態：資料不足｜驗證：data_missing｜來源品質：press_release｜期間新鮮度：fresh｜門檻：低於未來 12 個月利息與固定支出覆蓋需求需警戒。
- Financial leverage｜狀態：資料不足｜驗證：data_missing｜來源品質：unknown｜期間新鮮度：unknown_period｜門檻：槓桿升高或評等機構負面評論需警戒。
- Credit rating / outlook｜狀態：已取得｜驗證：partially_verified｜來源品質：rating_agency｜期間新鮮度：fresh｜門檻：negative outlook、downgrade 或 watch negative 需警戒。
- BHFAL interest payment status｜狀態：已取得｜驗證：partially_verified｜來源品質：press_release｜期間新鮮度：fresh｜門檻：defer、suspend、delay、non-payment 立即紅燈。
- Aquarian merger / change-of-control treatment｜狀態：已取得｜驗證：partially_verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：未明確說明 BHFAL 存續、掛牌、贖回或付息條款時列資料不足。
- 資料缺口：6 項，關鍵資料缺漏時不可判定為綠燈。

### OPI 量化監控
- Occupancy rate｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：連續下降或低於同業顯著水準需警戒。
- AFFO / FFO｜狀態：已取得｜驗證：partially_verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：AFFO/FFO 大幅下滑或為負需警戒。
- Debt maturity schedule｜狀態：已取得｜驗證：partially_verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：12-24 個月內大量到期且流動性不足需紅燈。
- Liquidity / cash availability｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：流動性不足或 covenant 壓力需警戒。
- 資料缺口：1 項，關鍵資料缺漏時不可判定為綠燈。

### AXS-E 量化監控
- Combined ratio｜狀態：已取得｜驗證：verified｜來源品質：official_ir｜期間新鮮度：fresh｜門檻：高於 100% 或明顯惡化需警戒。
- Catastrophe losses｜狀態：已取得｜驗證：verified｜來源品質：official_ir｜期間新鮮度：fresh｜門檻：重大巨災損失超預期需警戒。
- Preferred dividend status｜狀態：已取得｜驗證：verified｜來源品質：official_ir｜期間新鮮度：fresh｜門檻：defer、suspend、delay 立即紅燈。

### F-B 量化監控
- Industrial free cash flow｜狀態：已取得｜驗證：partially_verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：FCF 轉負或全年指引大幅下修需警戒。
- Ford Credit delinquencies / credit losses｜狀態：資料不足｜驗證：data_missing｜來源品質：unknown｜期間新鮮度：unknown_period｜門檻：逾期率或信用損失準備明顯上升需警戒。
- Recall / warranty cost｜狀態：資料不足｜驗證：data_missing｜來源品質：unknown｜期間新鮮度：unknown_period｜門檻：重大召回或保固成本升高需警戒。
- 資料缺口：5 項，關鍵資料缺漏時不可判定為綠燈。

### UZD 量化監控
- Issuer / guarantor status｜狀態：已取得｜驗證：verified｜來源品質：sec_filing｜期間新鮮度：fresh｜門檻：發行人或擔保人不明確時列灰燈/黃燈，不可判定安全。
- Asset sale proceeds and use of funds｜狀態：已取得｜驗證：partially_verified｜來源品質：official_ir｜期間新鮮度：fresh｜門檻：出售所得若大量分配給股東而非減債需警戒。
- Debt assumption / redemption status｜狀態：資料不足｜驗證：data_missing｜來源品質：unknown｜期間新鮮度：unknown_period｜門檻：未說明承擔、契約修改或贖回時列資料不足。
- 資料缺口：2 項，關鍵資料缺漏時不可判定為綠燈。

## 程式端日期過濾與來源驗證

- 日期過濾版本：1.2.2
- 最近事件保留天數：14 天
- 說明：超出最近 14 日但命中 Chapter 11、收購、重整、退市、債務交換等重大關鍵字者，會保留為 background_risk_event；其他舊事件移至 dropped_old_events。

- CTGG：recent=3，background=0，unknown_date=0，dropped_old=0
- BHFAL：recent=4，background=0，unknown_date=0，dropped_old=0
- OPI：recent=4，background=0，unknown_date=0，dropped_old=0
- AXS-E：recent=4，background=0，unknown_date=0，dropped_old=0
- F-B：recent=12，background=0，unknown_date=0，dropped_old=0
- UZD：recent=2，background=0，unknown_date=0，dropped_old=0

## 完整 JSON

```json
[
  {
    "target_name": "CTGG",
    "events": [
      {
        "date": "2026-08-14",
        "title": "Lumen Technologies 股價下跌，市場對轉型前景看法分歧",
        "impact_direction": "負向",
        "impact_severity": 2,
        "confidence": "中",
        "summary_30": "LUMN 股價過去 90 天下跌 36%，市場對其轉型存疑。",
        "links": [
          "Investing.com"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "unknown",
        "event_source_quality_details": [
          "unknown"
        ],
        "event_verification_status": "unverified",
        "event_days_old": 4,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      },
      {
        "date": "2026-08-11",
        "title": "華爾街投行下調Lumen目標價，分析師持謹慎態度",
        "impact_direction": "負向",
        "impact_severity": 2,
        "confidence": "中",
        "summary_30": "花旗、富國銀行及高盛下調Lumen目標價，市場觀點趨謹慎。",
        "links": [
          "MarketBeat",
          "Investing.com"
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
        "date": "2026-08-06",
        "title": "Lumen Technologies CEO增持公司股份",
        "impact_direction": "正向",
        "impact_severity": 3,
        "confidence": "高",
        "summary_30": "CEO買入10萬股LUMN股票，顯示對公司前景信心。",
        "links": [
          "Stock Titan",
          "MarketBeat",
          "SEC Filing"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "sec_filing",
        "event_source_quality_details": [
          "sec_filing",
          "secondary_site"
        ],
        "event_verification_status": "verified",
        "event_days_old": 12,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      }
    ],
    "綜合分析": "Stage 2 AI 合併未完成；已由程式保留高可信 Stage 1 近期事件，事件權重偏負面（-1）。",
    "事件總分": "正向3 / 負向4 / 總分-1",
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
        "source": "Lumen Investor Relations / SEC 8-K",
        "source_url_or_name": "BusinessWire",
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
        "note": "排除特殊項目後的自由現金流。",
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
        "metric_consistency_reason": "",
        "cross_run_consistency_status": "consistent_with_prior_range",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "327 百萬美元",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260818",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 數值表達不同，但目前值落在前一可信區間內。"
      },
      {
        "ticker": "CTGG",
        "metric_name": "Debt maturity and exchange offer terms",
        "metric_category": "債務結構",
        "value": "2051-09-01 (到期日); 13.2 億 (總長債)",
        "unit": "status/date/USD",
        "period": "2026Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "SEC 10-Q / MarketScreener",
        "source_url_or_name": "Moomoo AI",
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
        "note": "Lumen 截至 2026 年 6 月 30 日的總長債為 13.2 億美元，較 2025 年底的 17.4 億美元有所下降，主要得益於資產出售和債務交換。CTGG 的發行是 Qwest 債務交換計劃的一部分，該計劃於 2026 年 6 月 11 日完成。",
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
        "value": "B / 穩定 (發行人); B / 2 (回收評級)",
        "unit": "rating",
        "period": "2026-04-27 (S&P 發行評級); 2026-02-20 (Moody's 發行人評級)",
        "status": "已取得",
        "confidence": "高",
        "source": "S&P Global Ratings / Moody's Ratings / Fitch Ratings",
        "source_url_or_name": "S&P Global Ratings / Moody's Ratings / Fitch Ratings",
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
        "note": "S&P對Qwest新高級無擔保票據（如CTGG）給予'B'發行評級和'2'回收評級（預期70-90%回收）。Moody's將Lumen CFR上調至B2，Qwest高級無擔保債券上調至Caa1，展望穩定。Fitch維持Lumen及Qwest IDR為'B'，展望穩定，預期所有Lumen/Qwest債務為'RR1'回收水平。",
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
        "metric_period_parsed_date": "2026-04-27",
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
        "cross_run_previous_value": "Caa1 (Moody's) / B (Fitch) / B (S&P issue-level) / B- (S&P issuer)",
        "cross_run_previous_period": "2026-02-20 (Moody's); 2026-02-09 (Fitch); 2026-04-27 (S&P issue-level)",
        "cross_run_previous_report_date": "20260814",
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
        "metric_name": "Debt maturity schedule (Lumen Technologies consolidated)",
        "reason": "本次搜尋未找到 Lumen Technologies 最新 (2026Q2) 的完整綜合債務到期時間表細節。",
        "risk_impact": "缺少母公司完整的債務到期時間表，影響對集團整體再融資壓力的判斷，進而可能間接影響 CTGG 債權保護。",
        "source_candidates": [
          "SEC 10-Q (Q2 2026)",
          "Lumen Investor Relations (Debt Profile)"
        ],
        "acceptance_criteria": "下次需填入 value、period、source；若查無，需說明查詢過哪些來源。"
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
    "dropped_old_events": [],
    "event_date_filter_summary": {
      "lookback_days": 14,
      "cutoff_date": "2026-08-05",
      "today": "2026-08-18",
      "kept_recent": 3,
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
        "date": "2026-08-17",
        "title": "Brighthouse Financial 宣布發放優先股股息",
        "impact_direction": "正向",
        "impact_severity": 2,
        "confidence": "高",
        "summary_30": "公司宣布如期發放多類優先股季度股息，顯示財務能力穩健。",
        "links": [
          "Business Wire",
          "BusinessWire",
          "Nasdaq"
        ],
        "merged_duplicate_count": 2,
        "event_source_quality": "exchange_notice",
        "event_source_quality_details": [
          "exchange_notice",
          "press_release"
        ],
        "event_verification_status": "verified",
        "event_days_old": 1,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      },
      {
        "date": "2026-08-07",
        "title": "報導稱Aquarian收購案涉及會計問題",
        "impact_direction": "負向",
        "impact_severity": 4,
        "confidence": "中",
        "summary_30": "報導指Brighthouse Reinsurance存在會計問題，可能影響Aquarian收購。",
        "links": [
          "Seeking Alpha",
          "SeekingAlpha"
        ],
        "merged_duplicate_count": 2,
        "event_source_quality": "secondary_site",
        "event_source_quality_details": [
          "secondary_site"
        ],
        "event_verification_status": "unverified",
        "event_days_old": 11,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      },
      {
        "date": "2026-08-06",
        "title": "Brighthouse Financial 公布 2026 年第二季度財報",
        "impact_direction": "正向",
        "impact_severity": 4,
        "confidence": "高",
        "summary_30": "RBC比率430%-450%，控股公司流動資產9億美元，法定資本49億美元；併購案持續推進，但營收不及預期。",
        "links": [
          "Business Wire",
          "GuruFocus",
          "MarketBeat",
          "TradingView",
          "Perplexity",
          "BusinessWire",
          "StockTitan",
          "Brighthouse Financial Investor Relations",
          "Morningstar",
          "Webull",
          "SEC Filing"
        ],
        "merged_duplicate_count": 4,
        "event_source_quality": "sec_filing",
        "event_source_quality_details": [
          "sec_filing",
          "official_ir",
          "press_release",
          "secondary_site",
          "ai_summary"
        ],
        "event_verification_status": "verified",
        "event_days_old": 12,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      },
      {
        "date": "2026-08-06",
        "title": "提交 2026 年第二季度 10-Q 報告",
        "impact_direction": "中性",
        "impact_severity": 1,
        "confidence": "高",
        "summary_30": "公司向 SEC 提交了截至 2026 年 6 月 30 日的季度報告，確認財務數據。",
        "links": [
          "SEC Filing",
          "TradingView"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "sec_filing",
        "event_source_quality_details": [
          "sec_filing"
        ],
        "event_verification_status": "verified",
        "event_days_old": 12,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      }
    ],
    "綜合分析": "已排除低可信來源並合併重複事件；目前事件權重為偏正面（+2）。",
    "事件總分": "正向6 / 負向4 / 總分+2",
    "new_sources_found": [],
    "event_merge_source": "stage1_deterministic_fallback",
    "excluded_low_trust_event_count": 1,
    "merged_duplicate_event_count": 5,
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
        "source": "Brighthouse Financial 2Q26 Earnings Release",
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
        "note": "為預估合併風險資本比率 (Estimated combined risk-based capital ratio)，反映初步法定結果。",
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
        "metric_period_type": "date",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "source_period_rejected",
        "metric_verification_status": "data_missing",
        "definition_scope": "Brighthouse insurance subsidiaries (combined)",
        "calculation_basis": "NAIC combined risk-based capital ratio",
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
        "value": "4.9 billion",
        "unit": "USD",
        "period": "2026Q2 (截至 2026-06-30)",
        "status": "已取得",
        "confidence": "高",
        "source": "Brighthouse Financial 2Q26 Earnings Release",
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
        "note": "為法定合併調整後總資本 (Statutory combined total adjusted capital)，反映初步法定結果。",
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
        "metric_period_type": "date",
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
        "value": null,
        "unit": "USD",
        "period": "2026Q2 (截至 2026-06-30)",
        "status": "資料不足",
        "confidence": "低",
        "source": "Brighthouse Financial 2Q26 Earnings Release",
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
        "note": "指控股公司層級的現金及流動資產。",
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
        "metric_period_type": "date",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "source_period_rejected",
        "metric_verification_status": "data_missing",
        "definition_scope": "Brighthouse holding company group",
        "calculation_basis": "holding company liquid assets",
        "measurement_form": "point",
        "source_period_rejected_value": "0.9 billion",
        "source_period_expected": "2026Q2 / as of 2026-06-30",
        "source_period_alignment_status": "rejected_prior_period_fingerprint",
        "source_period_rejection_reason": "候選值 0.9 billion 與已驗證的 Brighthouse 1Q26 holding company liquid assets $0.9B 完全一致，但實際來源/備註未提供截至 2026-06-30 的 Q2 來源期證據；為避免把 2026Q1 數字錯標成 2026Q2，已停止採用。",
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
        "value": "Under Review With Negative Implications (AM Best)",
        "unit": "rating",
        "period": "Ongoing (Latest reference Aug 2026)",
        "status": "已取得",
        "confidence": "中",
        "source": "AM Best News",
        "source_url_or_name": "AM Best News",
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
        "note": "反映AM Best持續的審查。具體信貸評級字母未在近14日內明確更新，但展望關鍵。",
        "definition_scope": "Issuer/Entity Level",
        "calculation_basis": "Agency Rating/Outlook",
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
        "metric_period_parsed_date": "2026-08-18",
        "metric_period_parse_status": "parsed",
        "metric_period_type": "ongoing",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "partially_verified",
        "metric_consistency_status": "conflict_with_missing_data",
        "metric_consistency_reason": "在指定日期範圍（最近14日內）內未找到主要信用評級機構（AM Best, S&P, Moody's, Fitch）關於Brighthouse Financial的最新信用評級或展望更新。",
        "metric_consistency_missing_type": "metric_value",
        "cross_run_consistency_status": "definition_changed",
        "cross_run_previous_value": "S&P: A- (穩定); Moody's: A3 (穩定); Fitch: A- (穩定)",
        "cross_run_previous_period": "2026-07",
        "cross_run_previous_report_date": "20260818",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period 有前值，但 definition_scope / calculation_basis 不同，不互相覆寫。"
      },
      {
        "ticker": "BHFAL",
        "metric_name": "BHFAL interest payment status",
        "metric_category": "付息狀態",
        "value": "已正常支付",
        "unit": "status",
        "period": "2026Q2 / Latest",
        "status": "已取得",
        "confidence": "高",
        "source": "BusinessWire, 無負面報導",
        "source_url_or_name": "BusinessWire",
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
        "note": "優先股股息已如期宣告並發放，間接證明控股公司具備支付次順位債利息的能力。",
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
        "value": "進行中，待監管批准；BHFAL 債務預計存續",
        "unit": "status",
        "period": "2026Q2 (截至 2026-06-30)",
        "status": "已取得",
        "confidence": "高",
        "source": "Brighthouse Financial 2Q26 Earnings Release / SEC Filing",
        "source_url_or_name": "Business Wire, SEC Filing",
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
        "note": "合併預計於 2026 年完成，但仍需特拉華州、紐約州和麻薩諸塞州的保險監管批准。若 9 月 6 日未完成，協議將延至 12 月 6 日。次順位債券預計將繼續作為 Brighthouse Financial 的義務而存續。Seeking Alpha 報導指出可能存在與 Brighthouse Reinsurance Company of Delaware 相關的會計問題，恐影響監管批准進度。",
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
        "metric_period_type": "date",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "partially_verified",
        "metric_consistency_status": "conflict_with_missing_data",
        "metric_consistency_reason": "收購案預計2026年完成，股東已批准，待監管批准。但本次搜尋未明確找到針對BHFAL次順位債在變更控制後的存續、掛牌、贖回或付息條款的具體說明。",
        "metric_consistency_missing_type": "metric_definition_details",
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
        "reason": "收購案預計2026年完成，股東已批准，待監管批准。但本次搜尋未明確找到針對BHFAL次順位債在變更控制後的存續、掛牌、贖回或付息條款的具體說明。",
        "risk_impact": "收購完成後可能影響掛牌、流動性與資本政策。",
        "source_candidates": [
          "SEC 8-K (Merger Agreement)",
          "Brighthouse Financial Investor Relations Q&A on Merger"
        ],
        "acceptance_criteria": "需確認合併協議中對次順位債務的具體處理條款",
        "missing_type_original": "metric_definition_details",
        "conflict_with_metric_data": true,
        "metric_value_present": "進行中，待監管批准；BHFAL 債務預計存續",
        "metric_source_present": "Brighthouse Financial 2Q26 Earnings Release / SEC Filing",
        "metric_verification_after_reconcile": "partially_verified"
      },
      {
        "ticker": "BHFAL",
        "priority": "P0",
        "missing_type": "metric_consistency",
        "metric_name": "Credit rating / outlook",
        "reason": "在指定日期範圍（最近14日內）內未找到主要信用評級機構（AM Best, S&P, Moody's, Fitch）關於Brighthouse Financial的最新信用評級或展望更新。",
        "risk_impact": "評等惡化可能領先價格與流動性壓力，其缺乏會使債券信用風險判斷不夠完整。",
        "source_candidates": [
          "AM Best",
          "S&P",
          "Moody's",
          "Fitch"
        ],
        "acceptance_criteria": "下次需填入 value、period、source；若查無，需說明查詢過哪些來源。",
        "missing_type_original": "metric_value",
        "conflict_with_metric_data": true,
        "metric_value_present": "Under Review With Negative Implications (AM Best)",
        "metric_source_present": "AM Best News",
        "metric_verification_after_reconcile": "partially_verified"
      },
      {
        "ticker": "BHFAL",
        "priority": "P0",
        "missing_type": "metric_source_period_alignment",
        "metric_name": "RBC ratio",
        "reason": "候選值 430%-450% 與已驗證的 Brighthouse 1Q26 estimated combined RBC 430%-450% 完全一致，但實際來源/備註未提供截至 2026-06-30 的 Q2 來源期證據；為避免把 2026Q1 數字錯標成 2026Q2，已停止採用。",
        "risk_impact": "RBC 下滑可能代表保險子公司資本緩衝下降，影響次順位債付息與信用評等。",
        "rejected_candidate_value": "430%-450%",
        "source": "Brighthouse Financial 2Q26 Earnings Release",
        "acceptance_criteria": "若宣稱 2026Q2，實際來源/備註需能對應截至 2026-06-30（或等價明確 Q2 as-of date）；否則不得沿用已知 2026Q1 官方指紋值。"
      },
      {
        "ticker": "BHFAL",
        "priority": "P0",
        "missing_type": "metric_source_period_alignment",
        "metric_name": "Holding company cash and liquid assets",
        "reason": "候選值 0.9 billion 與已驗證的 Brighthouse 1Q26 holding company liquid assets $0.9B 完全一致，但實際來源/備註未提供截至 2026-06-30 的 Q2 來源期證據；為避免把 2026Q1 數字錯標成 2026Q2，已停止採用。",
        "risk_impact": "控股公司流動性不足可能影響 BHFAL 利息支付。",
        "rejected_candidate_value": "0.9 billion",
        "source": "Brighthouse Financial 2Q26 Earnings Release",
        "acceptance_criteria": "若宣稱 2026Q2，實際來源/備註需能對應截至 2026-06-30（或等價明確 Q2 as-of date）；否則不得沿用已知 2026Q1 官方指紋值。"
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
        "period": "2026Q2 (截至 2026-06-30)",
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
      "cutoff_date": "2026-08-05",
      "today": "2026-08-18",
      "kept_recent": 4,
      "kept_background": 0,
      "kept_unknown_date": 0,
      "dropped_old": 0
    },
    "metric_consistency_summary": {
      "conflict_count": 3,
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
          "metric_name": "Credit rating / outlook",
          "metric_value": "Under Review With Negative Implications (AM Best)",
          "missing_reason": "在指定日期範圍（最近14日內）內未找到主要信用評級機構（AM Best, S&P, Moody's, Fitch）關於Brighthouse Financial的最新信用評級或展望更新。",
          "verification_after_reconcile": "partially_verified",
          "cross_run_consistency_status": "definition_changed",
          "definition_scope": "Issuer/Entity Level",
          "calculation_basis": "Agency Rating/Outlook"
        },
        {
          "ticker": "BHFAL",
          "metric_name": "Aquarian merger / change-of-control treatment",
          "metric_value": "進行中，待監管批准；BHFAL 債務預計存續",
          "missing_reason": "收購案預計2026年完成，股東已批准，待監管批准。但本次搜尋未明確找到針對BHFAL次順位債在變更控制後的存續、掛牌、贖回或付息條款的具體說明。",
          "verification_after_reconcile": "partially_verified",
          "cross_run_consistency_status": "no_prior_same_period",
          "definition_scope": "",
          "calculation_basis": ""
        }
      ]
    }
  },
  {
    "target_name": "OPI",
    "events": [
      {
        "date": "2026-08-14",
        "title": "主要股東Redwood Capital Management減持OPI股份",
        "impact_direction": "負向",
        "impact_severity": 3,
        "confidence": "高",
        "summary_30": "主要股東Redwood Capital Management近期持續出售OPI股份，顯示大股東減持動態。",
        "links": [
          "MarketBeat",
          "Stock Titan"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "secondary_site",
        "event_source_quality_details": [
          "secondary_site"
        ],
        "event_verification_status": "unverified",
        "event_days_old": 4,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      },
      {
        "date": "2026-08-13",
        "title": "Barclays PLC 揭露取得 OPI 8.43% 被動股權",
        "impact_direction": "正向",
        "impact_severity": 2,
        "confidence": "高",
        "summary_30": "Barclays PLC揭露取得OPI 8.43%股權。",
        "links": [
          "SEC Filing (SC 13G)"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "sec_filing",
        "event_source_quality_details": [
          "sec_filing"
        ],
        "event_verification_status": "verified",
        "event_days_old": 5,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      },
      {
        "date": "2026-08-06",
        "title": "OPI公布2026年第二季財報，債務大幅削減並重組成功",
        "impact_direction": "正向",
        "impact_severity": 5,
        "confidence": "高",
        "summary_30": "OPI Q2財報：重組債務減$7.14億，FFO$1900萬，出租率77.9%。",
        "links": [
          "Seeking Alpha",
          "newsfilter.io",
          "BusinessWire",
          "Nasdaq",
          "SEC Filing",
          "OPI Investor Relations",
          "SEC Filing (10-Q)",
          "Kalkine",
          "Morningstar",
          "Stock Titan",
          "Barchart.com",
          "Simply Wall St",
          "SeekingAlpha",
          "Decode Investing"
        ],
        "merged_duplicate_count": 4,
        "event_source_quality": "sec_filing",
        "event_source_quality_details": [
          "sec_filing",
          "official_ir",
          "exchange_notice",
          "press_release",
          "secondary_site"
        ],
        "event_verification_status": "verified",
        "event_days_old": 12,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      },
      {
        "date": "2026-08-06",
        "title": "大股東Redwood Capital Management減持OPI股票",
        "impact_direction": "負向",
        "impact_severity": 3,
        "confidence": "高",
        "summary_30": "大股東Redwood Capital Management於8月減持OPI股票。",
        "links": [
          "MarketBeat",
          "SEC Filing (Form 4/A)"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "sec_filing",
        "event_source_quality_details": [
          "sec_filing",
          "secondary_site"
        ],
        "event_verification_status": "verified",
        "event_days_old": 12,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      }
    ],
    "綜合分析": "已排除低可信來源並合併重複事件；目前事件權重為偏正面（+1）。",
    "事件總分": "正向7 / 負向6 / 總分+1",
    "new_sources_found": [],
    "event_merge_source": "stage1_deterministic_fallback",
    "excluded_low_trust_event_count": 1,
    "merged_duplicate_event_count": 3,
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
        "source": "Office Properties Income Trust Q2 2026 Earnings Release / 10-Q Filing",
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
        "note": "截至2026年6月30日的整體投資組合出租率；同物業出租率為88.7%。",
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
        "cross_run_previous_period": "2026Q2 (截至 6 月 30 日)",
        "cross_run_previous_report_date": "20260817",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 數值表達不同，但目前值落在前一可信區間內。"
      },
      {
        "ticker": "OPI",
        "metric_name": "AFFO / FFO",
        "metric_category": "現金流",
        "value": "19",
        "unit": "USD",
        "period": "2026Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "Office Properties Income Trust Q2 2026 Earnings Call Transcript / 10-Q Filing",
        "source_url_or_name": "Seeking Alpha",
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
        "note": "2026年第二季度的Normalized FFO (Funds From Operations)。",
        "source_quality_primary": "sec_filing",
        "source_quality": "sec_filing",
        "source_quality_details": [
          "sec_filing",
          "secondary_site"
        ],
        "source_candidate_quality_details": [
          "sec_filing",
          "official_ir",
          "court_docket"
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
        "cross_run_previous_value": "19.0",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260818",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 數值表達不同，但目前值落在前一可信區間內。"
      },
      {
        "ticker": "OPI",
        "metric_name": "Debt maturity schedule",
        "metric_category": "債務到期牆",
        "value": "1.7",
        "unit": "USD/date",
        "period": "2026-06-30",
        "status": "已取得",
        "confidence": "高",
        "source": "Office Properties Income Trust Q2 2026 Earnings Call Transcript / 10-Q Filing",
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
        "note": "截至2026年6月30日，總債務為17億美元。其中4.25億美元循環信貸工具將於2027年1月到期；2029年到期的高級擔保票據需在2026年支付2000萬美元本金，2027年支付3000萬美元，2028-2029年各支付4500萬美元。",
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
        "metric_verification_status": "partially_verified",
        "metric_consistency_status": "cross_run_conflict",
        "metric_consistency_reason": "同 period / definition 前值=總債務 $1.7B / 2027年1月到期 $4.25億信貸額度 / 2029年12月到期債務需支付本金，本次=1.7；區間不重疊。",
        "cross_run_consistency_status": "value_changed_same_definition",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "總債務 $1.7B / 2027年1月到期 $4.25億信貸額度 / 2029年12月到期債務需支付本金",
        "cross_run_previous_period": "2026年6月30日",
        "cross_run_previous_report_date": "20260813",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 前值=總債務 $1.7B / 2027年1月到期 $4.25億信貸額度 / 2029年12月到期債務需支付本金，本次=1.7；區間不重疊。"
      },
      {
        "ticker": "OPI",
        "metric_name": "Liquidity / cash availability",
        "metric_category": "流動性",
        "value": "51",
        "unit": "USD",
        "period": "2026-06-30",
        "status": "已取得",
        "confidence": "高",
        "source": "Office Properties Income Trust Q2 2026 Earnings Call Transcript / 10-Q Filing",
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
        "note": "截至2026年6月30日，非受限現金約5100萬美元，受限現金約5300萬美元。",
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
        "cross_run_consistency_status": "consistent_with_prior_range",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "非限制性現金 $51M / 限制性現金 $53M",
        "cross_run_previous_period": "2026年6月30日",
        "cross_run_previous_report_date": "20260813",
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
        "metric_name": "Debt maturity schedule",
        "reason": "同 period / definition 前值=總債務 $1.7B / 2027年1月到期 $4.25億信貸額度 / 2029年12月到期債務需支付本金，本次=1.7；區間不重疊。",
        "risk_impact": "再融資失敗可能導致重整或資產賤售。",
        "previous_value": "總債務 $1.7B / 2027年1月到期 $4.25億信貸額度 / 2029年12月到期債務需支付本金",
        "current_value": "1.7",
        "period": "2026-06-30",
        "definition_scope": "",
        "calculation_basis": "",
        "acceptance_criteria": "以同一官方定義重新查核；若為不同口徑，改填不同 definition_scope / calculation_basis，不得覆寫。"
      }
    ],
    "dropped_old_events": [],
    "event_date_filter_summary": {
      "lookback_days": 14,
      "cutoff_date": "2026-08-05",
      "today": "2026-08-18",
      "kept_recent": 4,
      "kept_background": 0,
      "kept_unknown_date": 0,
      "dropped_old": 0
    },
    "metric_consistency_summary": {
      "conflict_count": 1,
      "conflicts": [
        {
          "ticker": "OPI",
          "metric_name": "Debt maturity schedule",
          "metric_value": "1.7",
          "missing_reason": "同 period / definition 前值=總債務 $1.7B / 2027年1月到期 $4.25億信貸額度 / 2029年12月到期債務需支付本金，本次=1.7；區間不重疊。",
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
        "date": "2026-08-17",
        "title": "分析師探討AXIS資本在Meta訴訟背景下的網路責任保險風險",
        "impact_direction": "負向",
        "impact_severity": 1,
        "confidence": "中",
        "summary_30": "媒體討論AXIS資本在專業與網路責任險領域，可能受Meta訴訟影響的潛在風險。",
        "links": [
          "Simply Wall St News",
          "Kalkine Media"
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
        "date": "2026-08-05",
        "title": "AXIS Capital 宣布收購 DUAL 北美超額責任業務的續保權利",
        "impact_direction": "正向",
        "impact_severity": 3,
        "confidence": "高",
        "summary_30": "AXIS Capital 透過收購 DUAL 北美超額責任業務續保權利，擴大其專業保險產品線。",
        "links": [
          "AXIS Capital Investor Relations",
          "Press Releases"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "official_ir",
        "event_source_quality_details": [
          "official_ir",
          "press_release"
        ],
        "event_verification_status": "verified",
        "event_days_old": 13,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      },
      {
        "date": "2026-08-05",
        "title": "AXIS Capital 同意收購 DUAL North America 的超額責任保險續保權",
        "impact_direction": "正向",
        "impact_severity": 3,
        "confidence": "高",
        "summary_30": "AXIS Capital 透過收購 DUAL North America 續保權以擴展業務，預計增強市場地位。",
        "links": [
          "AXIS Investor Relations"
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
      },
      {
        "date": "2026-08-05",
        "title": "AXIS資本收購DUAL北美區超額責任業務的續保權並任命新領導",
        "impact_direction": "正向",
        "impact_severity": 2,
        "confidence": "高",
        "summary_30": "AXIS資本透過收購DUAL超額責任業務續保權強化意外險平台，並任命John Kopach為新領導。",
        "links": [
          "AXIS Capital Holdings Investor Relations",
          "MarketScreener",
          "PRNewswire"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "official_ir",
        "event_source_quality_details": [
          "official_ir",
          "press_release"
        ],
        "event_verification_status": "verified",
        "event_days_old": 13,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      }
    ],
    "綜合分析": "Stage 2 AI 合併未完成；已由程式保留高可信 Stage 1 近期事件，事件權重偏正面（+7）。",
    "事件總分": "正向8 / 負向1 / 總分+7",
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
        "value": "93.1",
        "unit": "%",
        "period": "2026 Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "AXIS Capital Holdings Q2 2026 Earnings Release",
        "source_url_or_name": "AXIS Capital Holdings Investor Relations",
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
        "note": "雖然低於100%表示承保盈利，但此數據高於去年同期88.9%，顯示承保表現有所惡化。",
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
        "cross_run_previous_value": "93.1",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260818",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 與前一可信值一致。"
      },
      {
        "ticker": "AXS-E",
        "metric_name": "Catastrophe losses",
        "metric_category": "巨災損失",
        "value": "80",
        "unit": "USD",
        "period": "2026 Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "AXIS Capital Holdings Q2 2026 Earnings Release",
        "source_url_or_name": "AXIS Capital Holdings Investor Relations",
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
        "note": "此金額為稅前、再保後巨災及天氣相關損失，其中包含4900萬美元的自然巨災損失和3100萬美元的中東衝突相關損失。",
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
        "cross_run_previous_value": "80",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260818",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 與前一可信值一致。"
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
        "source": "AXIS Capital Investor Relations / GlobeNewswire",
        "source_url_or_name": "AXIS Capital Declares Quarterly Dividends",
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
        "note": "每股存託憑證支付 0.34375 美元股息。",
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
        "cross_run_previous_value": "已宣佈/已支付",
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
    "missing_data": [],
    "dropped_old_events": [],
    "event_date_filter_summary": {
      "lookback_days": 14,
      "cutoff_date": "2026-08-05",
      "today": "2026-08-18",
      "kept_recent": 4,
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
        "date": "2026-08-17",
        "title": "福特召回86,543輛Mach-E SUV，因後側窗玻璃可能脫落",
        "impact_direction": "負向",
        "impact_severity": 3,
        "confidence": "高",
        "summary_30": "福特因供應商組裝問題召回2023-2025年Mach-E車型，無事故傷害報告。",
        "links": [
          "Kelley Blue Book"
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
        "title": "Fitch授予Ford Credit汽車業主信託2026-REV2初步評級",
        "impact_direction": "正向",
        "impact_severity": 2,
        "confidence": "高",
        "summary_30": "Fitch對Ford Credit新資產擔保證券給予穩定評級，肯定其強勁信貸品質。",
        "links": [
          "Fitch"
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
        "date": "2026-08-17",
        "title": "Fitch確認Ford Credit資產擔保債券評級，展望穩定",
        "impact_direction": "正向",
        "impact_severity": 2,
        "confidence": "高",
        "summary_30": "Fitch對Ford Credit Auto Owner Trust 2026-REV2維持穩定評級，顯示其資產質量強勁。",
        "links": [
          "Fitch Ratings"
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
        "date": "2026-08-17",
        "title": "2027年Ford F-150 Raptor基本款降價4,010美元",
        "impact_direction": "中性",
        "impact_severity": 2,
        "confidence": "中",
        "summary_30": "福特F-150 Raptor基本款降價5%至74,995美元，以競爭對手，但部分功能減少。",
        "links": [
          "CarsDirect"
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
        "title": "福特Hypercar首次進行賽道測試，為2027年利曼賽事準備",
        "impact_direction": "正向",
        "impact_severity": 1,
        "confidence": "中",
        "summary_30": "福特新Hypercar於8月5日開始測試，將於2027年FIA世界耐力錦標賽首次亮相。",
        "links": [
          "RoadandTrack.com"
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
        "date": "2026-08-13",
        "title": "Dbs Bank將福特汽車評級上調至「適度買入」",
        "impact_direction": "正向",
        "impact_severity": 3,
        "confidence": "中",
        "summary_30": "Dbs Bank看好福特前景，將其評級從「持有」上調至「適度買入」。",
        "links": [
          "MarketBeat"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "secondary_site",
        "event_source_quality_details": [
          "secondary_site"
        ],
        "event_verification_status": "unverified",
        "event_days_old": 5,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      },
      {
        "date": "2026-08-13",
        "title": "福特計劃自2030年起將部分Lincoln車型生產從中國轉移至美國",
        "impact_direction": "正向",
        "impact_severity": 3,
        "confidence": "高",
        "summary_30": "因高額關稅及中國技術限制，福特將調整Lincoln生產線，長期有利於美國市場。",
        "links": [
          "Reuters",
          "Benzinga",
          "Just Auto",
          "investingLive"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "mainstream_media",
        "event_source_quality_details": [
          "mainstream_media",
          "secondary_site"
        ],
        "event_verification_status": "partially_verified",
        "event_days_old": 5,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      },
      {
        "date": "2026-08-13",
        "title": "福特宣布自2030年起增加美國Lincoln車款生產並逐步淘汰中國進口",
        "impact_direction": "正向",
        "impact_severity": 2,
        "confidence": "高",
        "summary_30": "福特長期戰略調整，強化本土製造，降低對中國進口依賴。",
        "links": [
          "GuruFocus",
          "Ford Company News"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "secondary_site",
        "event_source_quality_details": [
          "secondary_site"
        ],
        "event_verification_status": "unverified",
        "event_days_old": 5,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      },
      {
        "date": "2026-08-12",
        "title": "美國第二季汽車貸款逾期率達15年新高",
        "impact_direction": "負向",
        "impact_severity": 3,
        "confidence": "中",
        "summary_30": "聯準會數據顯示，整體汽車貸款市場逾期率上升，對汽車金融構成潛在風險。",
        "links": [
          "CBT News"
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
        "date": "2026-08-12",
        "title": "美國第二季度汽車貸款拖欠率創15年新高",
        "impact_direction": "負向",
        "impact_severity": 3,
        "confidence": "高",
        "summary_30": "紐約聯儲報告顯示，2026年第二季度美國汽車貸款嚴重拖欠率達2010年來最高。",
        "links": [
          "CBT News",
          "TransUnion"
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
        "date": "2026-08-06",
        "title": "福特召回2025-2026年Bronco車款，因引擎故障恐失動力",
        "impact_direction": "負向",
        "impact_severity": 4,
        "confidence": "高",
        "summary_30": "福特宣布召回2025-2026年Bronco、Explorer和Ranger，因引擎故障有失去動力的風險。",
        "links": [
          "CarBuzz"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "unknown",
        "event_source_quality_details": [
          "unknown"
        ],
        "event_verification_status": "unverified",
        "event_days_old": 12,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      },
      {
        "date": "2026-08-06",
        "title": "Zacks將福特汽車評級上調至「買入」",
        "impact_direction": "正向",
        "impact_severity": 3,
        "confidence": "中",
        "summary_30": "Zacks基於盈利預期上調福特評級，預示股價潛在上漲空間。",
        "links": [
          "Zacks Investment Research"
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
      }
    ],
    "綜合分析": "Stage 2 AI 合併未完成；已由程式保留高可信 Stage 1 近期事件，事件權重偏正面（+3）。",
    "事件總分": "正向16 / 負向13 / 總分+3",
    "new_sources_found": [],
    "event_merge_source": "stage1_deterministic_fallback",
    "excluded_low_trust_event_count": 0,
    "merged_duplicate_event_count": 0,
    "event_dedup_patch_version": "1.3.3",
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
        "source": "Ford Motor Company Q2 2026 Financial Results",
        "source_url_or_name": "Business Wire, Ford Investor Relations, SEC Filing",
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
        "note": "2026年Q2調整後自由現金流為21億美元。全年調整後自由現金流指引上調至60億至70億美元。",
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
        "metric_verification_status": "partially_verified",
        "metric_consistency_status": "cross_run_conflict",
        "metric_consistency_reason": "同 period / definition 前值=2.1，本次=2.1 billion；區間不重疊。",
        "cross_run_consistency_status": "value_changed_same_definition",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "2.1",
        "cross_run_previous_period": "2026Q2",
        "cross_run_previous_report_date": "20260814",
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
      "cutoff_date": "2026-08-05",
      "today": "2026-08-18",
      "kept_recent": 12,
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
    }
  },
  {
    "target_name": "UZD",
    "events": [
      {
        "date": "2026-08-07",
        "title": "Array Digital Infrastructure (前身UScellular) 公布亮眼第二季度業績及頻譜出售收益",
        "impact_direction": "正向",
        "impact_severity": 4,
        "confidence": "高",
        "summary_30": "Array Digital Infrastructure公布Q2業績，頻譜出售推動收入及淨利潤顯著增長，完成多項頻譜交易。",
        "links": [
          "PRNewswire",
          "Array Digital Infrastructure Investor Relations",
          "TDS Investor Relations",
          "MarketScreener",
          "SeekingAlpha"
        ],
        "merged_duplicate_count": 1,
        "event_source_quality": "official_ir",
        "event_source_quality_details": [
          "official_ir",
          "press_release"
        ],
        "event_verification_status": "verified",
        "event_days_old": 11,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      },
      {
        "date": "2026-08-07",
        "title": "Array Digital Infrastructure 支付特別股息",
        "impact_direction": "負向",
        "impact_severity": 3,
        "confidence": "高",
        "summary_30": "Array Digital Infrastructure宣布支付每股11美元特別股息，資金來自頻譜出售收益，流向股東。",
        "links": [
          "PRNewswire",
          "Array Digital Infrastructure Investor Relations",
          "TDS Investor Relations"
        ],
        "merged_duplicate_count": 2,
        "event_source_quality": "official_ir",
        "event_source_quality_details": [
          "official_ir",
          "press_release"
        ],
        "event_verification_status": "verified",
        "event_days_old": 11,
        "event_date_filter_status": "kept_recent",
        "event_recency_type": "recent_event"
      }
    ],
    "綜合分析": "已排除低可信來源並合併重複事件；目前事件權重為偏正面（+1）。",
    "事件總分": "正向4 / 負向3 / 總分+1",
    "new_sources_found": [],
    "event_merge_source": "stage1_deterministic_fallback",
    "excluded_low_trust_event_count": 0,
    "merged_duplicate_event_count": 1,
    "event_dedup_patch_version": "1.3.3",
    "metric_data": [
      {
        "ticker": "UZD",
        "metric_name": "Issuer / guarantor status",
        "metric_category": "法律實體",
        "value": "United States Cellular Corporation / Array Digital Infrastructure, Inc. (NYSE: AD)",
        "unit": "status",
        "period": "2026Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "SEC Filing, Array Digital Infrastructure Investor Relations",
        "source_url_or_name": "SEC Filing (Form 10-K, 8-K), Array Digital Infrastructure Investor Relations",
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
        "note": "United States Cellular Corporation 是債券的法律發行人，自2025年8月1日起已更名為 Array Digital Infrastructure, Inc.，股票代碼變更為 AD，TDS 為其母公司。",
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
        "cross_run_previous_value": "United States Cellular Corporation",
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
        "value": "超過10億美元（Q2 2026頻譜出售）；4.164億美元現金及約當物（截至2026年6月30日）",
        "unit": "USD/status",
        "period": "2026Q2",
        "status": "已取得",
        "confidence": "高",
        "source": "Array Digital Infrastructure Investor Relations, PRNewswire",
        "source_url_or_name": "Array Digital Infrastructure Investor Relations Q2 2026 Earnings, PRNewswire",
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
        "note": "Array Digital Infrastructure 在2026年第二季度完成多項頻譜出售，總計超過10億美元。公司於2026年6月25日支付了每股11美元的特別股息。截至2026年6月30日，公司現金及約當物為4.164億美元，長期債務約為6.75億美元。",
        "source_quality_primary": "official_ir",
        "source_quality": "official_ir",
        "source_quality_details": [
          "official_ir",
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
        "metric_period_type": "quarter",
        "metric_period_freshness": "fresh",
        "metric_integrity_status": "pass",
        "metric_verification_status": "partially_verified",
        "metric_consistency_status": "cross_run_conflict",
        "metric_consistency_reason": "同 period / definition 前值=Array已完成對Verizon及其他方大部分非C-Band頻譜的出售，部分銷售所得用於TDS於2026年6月25日支付每股11美元的特別股息。此前，2025年8月1日向T-Mobile出售無線業務及部分頻譜，獲得43億美元總對價（含26億現金及約17億美元債務承擔）。，本次=超過10億美元（Q2 2026頻譜出售）；4.164億美元現金及約當物（截至2026年6月30日）；區間不重疊。",
        "cross_run_consistency_status": "value_changed_same_definition",
        "definition_scope": "",
        "calculation_basis": "",
        "cross_run_previous_value": "Array已完成對Verizon及其他方大部分非C-Band頻譜的出售，部分銷售所得用於TDS於2026年6月25日支付每股11美元的特別股息。此前，2025年8月1日向T-Mobile出售無線業務及部分頻譜，獲得43億美元總對價（含26億現金及約17億美元債務承擔）。",
        "cross_run_previous_period": "2026Q2 (近期出售完成), 2025-2026 (總體出售與資金使用)",
        "cross_run_previous_report_date": "20260817",
        "cross_run_previous_definition_scope": "",
        "cross_run_previous_calculation_basis": "",
        "cross_run_consistency_reason": "同 period / definition 前值=Array已完成對Verizon及其他方大部分非C-Band頻譜的出售，部分銷售所得用於TDS於2026年6月25日支付每股11美元的特別股息。此前，2025年8月1日向T-Mobile出售無線業務及部分頻譜，獲得43億美元總對價（含26億現金及約17億美元債務承擔）。，本次=超過10億美元（Q2 2026頻譜出售）；4.164億美元現金及約當物（截至2026年6月30日）；區間不重疊。"
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
      },
      {
        "ticker": "UZD",
        "priority": "P0",
        "missing_type": "metric_cross_run_consistency",
        "metric_name": "Asset sale proceeds and use of funds",
        "reason": "同 period / definition 前值=Array已完成對Verizon及其他方大部分非C-Band頻譜的出售，部分銷售所得用於TDS於2026年6月25日支付每股11美元的特別股息。此前，2025年8月1日向T-Mobile出售無線業務及部分頻譜，獲得43億美元總對價（含26億現金及約17億美元債務承擔）。，本次=超過10億美元（Q2 2026頻譜出售）；4.164億美元現金及約當物（截至2026年6月30日）；區間不重疊。",
        "risk_impact": "可能削弱債券資產覆蓋。",
        "previous_value": "Array已完成對Verizon及其他方大部分非C-Band頻譜的出售，部分銷售所得用於TDS於2026年6月25日支付每股11美元的特別股息。此前，2025年8月1日向T-Mobile出售無線業務及部分頻譜，獲得43億美元總對價（含26億現金及約17億美元債務承擔）。",
        "current_value": "超過10億美元（Q2 2026頻譜出售）；4.164億美元現金及約當物（截至2026年6月30日）",
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
      "cutoff_date": "2026-08-05",
      "today": "2026-08-18",
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
          "metric_value": "超過10億美元（Q2 2026頻譜出售）；4.164億美元現金及約當物（截至2026年6月30日）",
          "missing_reason": "同 period / definition 前值=Array已完成對Verizon及其他方大部分非C-Band頻譜的出售，部分銷售所得用於TDS於2026年6月25日支付每股11美元的特別股息。此前，2025年8月1日向T-Mobile出售無線業務及部分頻譜，獲得43億美元總對價（含26億現金及約17億美元債務承擔）。，本次=超過10億美元（Q2 2026頻譜出售）；4.164億美元現金及約當物（截至2026年6月30日）；區間不重疊。",
          "verification_after_reconcile": "partially_verified",
          "cross_run_consistency_status": "value_changed_same_definition",
          "definition_scope": "",
          "calculation_basis": ""
        }
      ]
    }
  }
]
```

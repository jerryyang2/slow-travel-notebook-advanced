# 慢慢走旅行手帳

精緻手繪風格、繁體中文／英文、手機優先的旅行 App，將原版與進階版整合為一個單一 HTML。

主要網址：[慢慢走旅行手帳](https://slow-travel-notebook-20261119.asterina-co.chatgpt.site)

原進階版網址保留為相容入口：[GitHub Pages](https://jerryyang2.github.io/slow-travel-notebook-advanced/)。兩個入口提供相同功能，私人紀錄仍依網址、瀏覽器分開儲存；不會自動跨站同步。

## 繁體中文與 English 切換

每頁上方提供「繁中／English」，會記住目前瀏覽器及入口的語言偏好。主要導覽、操作表單、按鈕、進度與提示支援雙語；手機原生日期、時間選擇器依裝置系統語言顯示。網址可使用 `?lang=en` 或 `?lang=zh-TW` 指定初始語言，入口頁會帶入所選語言。

個人填寫的行程標題、筆記、每日手記、備忘、購物內容、住宿及照片文字不會因切換語言而改寫。城市與景點保留中文與英文／原文名稱；尚無可靠譯名時保留現有名稱。內建準備清單只翻譯未修改的預設項目，自訂內容保持原文。

## 隨目的地更新的旅行資訊

安全資訊統一依目前旅程的國家及城市顯示，包含官方旅遊警示入口、疾管署、簽證／入境、氣象及急難資訊。台灣國內旅程顯示國內旅遊、交通與防災資訊；沒有專屬資料的國家提供官方查詢目錄，不沿用其他國家的內容或電話。

近期天氣由 Open-Meteo 依目的地座標與時區查詢，含七日高低溫、降雨機率及簡要穿搭建議；切換城市會重新查詢，可手動更新。預報顯示取得時間；更新失敗時保留上次預報與時間。近期預報不代表較遠旅行日期的天氣。較晚回傳的前一城市請求不會覆蓋目前城市畫面。

警示、疫情與入境資格並未自動即時同步，本頁不顯示推定安全等級或免簽承諾。請開啟對應官方來源查詢。連結核對日期與個人「已查閱」時間分別標示，皆不當成官方公告更新時間。日本、德國及台灣提供已核對來源的當地急難號碼與離線 PNG 卡；其他地區先提供官方查詢入口。駐外館處須依實際旅行區域選擇。

- [外交部旅遊警示](https://www.boca.gov.tw/sp-trwa-list-1.html)
- [外交部簽證與國家資訊](https://www.boca.gov.tw/sp-foof-countrylp-01-1.html)
- [疾管署國際旅遊疫情建議](https://www.cdc.gov.tw/InternationalEpidemicLevel/Index/6U0eCorDVCOBl2dEQchLcQ)
- [日本外務省簽證資訊](https://www.mofa.go.jp/j_info/visit/visa/index.html)、[日本 JNTO 急難資訊](https://www.jnto.go.jp/emergency/eng/mi_guide.html)
- [德國官方急難號碼](https://im.baden-wuerttemberg.de/de/sicherheit/wichtige-rufnummern-fuer-den-notfall)、[台北市政府緊急電話](https://english.gov.taipei/News_Content.aspx?n=2991F84A4FAF842F&s=58A14F503DDDA3D7)

## 可以做什麼

- 搜尋目的地、設定天數與日期；每日行程可新增、修改、刪除、排序及跨日移動，並標示固定預約與交通待確認。航班、住宿、心願、出發前清單、行李、購物清單皆可自行編輯。
- 「地圖」頁可搜尋城市、標記目前城市，或點擊地圖新增任意去過的地點，記下日期與回憶。足跡集中顯示所有旅程，也可篩選目前旅程，支援修改、刪除、復原與備份。最多 500 個足跡；不會因行程打卡或城市刪除而自動新增／刪除足跡。
- 台灣 368 個鄉鎮市區支援中文搜尋、台／臺寫法及所屬縣市辨識。例：台北、臺北市、花蓮、花蓮縣、瑞芳、池上、恆春、中正區。查詢同名行政區時，請確認縣市。行政區位置是景點或界線的參考點，並非公所地址、交通集合點或精確導航點。
- 台灣行程及景點推薦使用交通部觀光署的景點資料。內建 6,201 筆公開景點的精簡快照（資料版本 2026-11-20），可在城市選單更新官方資料。規劃時排除資料中非正常營運、非公開場域與登山步道，依約 25 公里內地點編排；鄉鎮選擇會限於該行政區。資料不足時仍可建立手動行程。
- 首頁提供「城市重點景點」，選擇喜歡的地點、日期與時間後加入行程。國外城市及景點使用中文與英文／原文；原始資料缺少譯名時，可在地點編輯器自行補充。
- 「行程」頁的「匯入行程」接受文字、TXT 或 CSV。先預覽、修改並選擇日期，再附加到既有行程；可復原最近一次匯入。一次最多 200 項，每天最多 40 項。僅解析文字格式，不會自動理解旅行社長篇文案、讀取私人分享連結或建立訂位。複雜行程可先整理為每天一段、每行一個地點。
- 備忘錄支援重要置頂、日期、搜尋、完成狀態及刪除復原；每日手記依天數儲存。可自行拍照製作明信片。花費可手動填寫消費日期及選填時間，修改、刪除復原及備份會保留日期、時間與目的地時區。舊資料未填的日期時間保持空白；亦可用收據 OCR 輔助辨識後確認入帳。手動與收據記帳皆限制每趟 500 筆；儲存失敗時保留編輯內容，不會直接關閉。
- 「備忘」頁的完整備份包含保留中的旅程、清單、備忘、每日手記、照片與地圖足跡；匯入會另建旅程副本。回收區的旅程請先還原再備份。地圖另有獨立足跡備份。

## 貼上文字的例子

```text
第 1 天
09:30 瑪利亞廣場 | 看建築與廣場
13:30 慕尼黑王宮
第 2 天
10:00 英國花園
```

CSV 第一列可用 `天數,時間,地點,備註,地址`。時間未提供時標為「時間待定」。若來源的天數超過目前手帳，須在預覽指定日期後才能加入。飛行日、班機、飯店、價格與預約仍須自行確認。

## 加入手機主畫面

首頁「打開每日行程」旁與頁尾都有「加入手機主畫面」。按下後依手機選擇 iPhone／iPad 或 Android 操作提示，也可手動切換分頁與複製目前入口網址。iPhone 使用 Safari 的分享選單加入；Android 使用 Chrome 的加入主畫面或建立捷徑功能。僅當瀏覽器實際提供原生安裝事件時，說明視窗才會出現直接安裝按鈕。已從主畫面開啟時，入口改為「主畫面使用說明」。

加入圖示與安裝提示不會修改旅行紀錄。跨瀏覽器、網址或手機使用時，可從「備忘 → 備份與匯入」搬移紀錄。

## 複製景點名稱

每日行程與首頁景點推薦卡片均有「複製景點名稱」。按下後，會把目前顯示的繁體中文及英文／原文名稱整理成同一行，方便貼到 Google Maps。相同名稱只保留一次；尚未提供其中一種名稱時，複製現有名稱。內容僅含名稱，不包含時間、筆記或座標。瀏覽器未提供或未允許自動複製時，會開啟已選取名稱的視窗，可長按複製或按「再試一次」。

## 景點中英文名稱

行程卡片以繁體中文名稱與英文／原文名稱並列。先前只存英文、且有 Wikipedia 景點來源的紀錄，會以原始景點編號查詢中文語言連結，補上名稱；不會傳送私人備註。資料沒有可靠中文名稱時保留原名，可在「編輯」填寫中文名稱及英文／原文名稱。既有行程順序、地點座標與筆記保留。

## 繁體中文顯示

介面與外部資料的中文顯示會在裝置內轉為繁體中文，包含城市、行政區、景點、介紹及圖片替代文字；英文與標示為原文的名稱保持原樣。使用內嵌 OpenCC-JS 字典，轉換不需要連線，也不會改寫既有紀錄、輸入欄位、備份或網址。

## 資料與隱私

升級會沿用該網址原有的紀錄與照片，不會把個人紀錄放到公開網站。不同裝置或網址之間，請下載完整備份再匯入。一般儲存只在瀏覽器內；城市搜尋會傳送查詢字詞，地圖底圖會取得可見範圍的圖磚。清除瀏覽器資料會刪除本機紀錄，請定期備份。

單一 HTML 內嵌所有插畫、地圖程式與台灣資料快照。下載檔案可離線管理已保存的資料與台灣行政區查詢；網路字型、底圖、海外搜尋、官方資料更新與 OCR 元件需要網路。資料庫營運狀態不等於即時開放資訊，出發前請查景點管理單位與交通服務。

## 公開資料與授權

- 台灣景點：[交通部觀光署／政府資料開放平臺](https://data.gov.tw/dataset/7777)，依政府資料開放授權條款第 1 版使用。僅內嵌公開景點名稱、座標、行政區、狀態與更新時間。
- 行政區名單與參考點：[內政部國土測繪中心](https://maps.nlsc.gov.tw/pro/download.jsp)。368 個代碼與名稱已與 ListCounty／ListTown1 現行服務逐項核對。
- 城市座標與近期天氣：[Open-Meteo／GeoNames](https://open-meteo.com/)。
- 海外景點及中英文名稱：[Wikipedia／MediaWiki](https://www.mediawiki.org/wiki/API:Main_page)；餐廳、市集與商店：[OpenStreetMap](https://www.openstreetmap.org/copyright)。
- 底圖：© OpenStreetMap contributors；地圖程式 Leaflet 1.9.4，BSD 2-Clause License，完整授權保留於 HTML 及第三方授權文件。

`index.html` 為唯一主要來源；`慢慢走旅行手帳-進階版.html` 是相容副本。合併前的兩版可由 Git 提交 `62cc00f` 還原；本機另保留快照。

## English quick start

Choose **English** above the page to switch the interface. Your choice is remembered in this browser. Personal notes, itinerary content, shopping items and photo captions keep their original wording. City and place names retain their available Chinese and English / original names. Native date and time controls follow your device language.

Use **Trips** to change cities and dates, **Itinerary** to reorder stops or move them across days, **Lists** for preparation and shopping, **Expenses** for dated and timed spending, and **Notes → Backup and import** to move your journals and photos between devices or addresses. Flights and fixed reservations remain locked during reordering. Check transport and timing after changing the plan.

Travel information follows the selected destination. Near-term forecasts refresh by city coordinates. Official advisories, health notices and entry eligibility require checking the linked government sources; no live safety rating or visa-free eligibility is inferred. Existing addresses, QR codes and browser records remain available.

## 每日 8 個景點選擇與熱門景點規劃

每日行程的「看今天 8 個景點選擇」提供真實景點候選，午餐、休息、晚餐與自由時間不列入景點數。可直接加入今天；已排在其他天的景點可以調整日期。新行程依節奏安排約 3、4–5 或 5–6 處，並保留用餐與交通緩衝。備選不是要求同一天全部走完；較長停留的博物館、交通距離與資料不足可能使實際安排較少。

代表景點清單優先，其後綜合景點類型、Wikipedia 近 7 日文章閱覽資料與位置；文章長度不再作為熱門度。文章閱覽量只是排序參考，不代表旅客到訪人數或即時人氣排名。一般公園降低優先順序，每天自動排程至多一處自然風景。景點按區域順遊，不重複塞入同一地點；若符合條件的候選不足 8 處，會顯示取得數量與缺額，不捏造地點。

已存旅程不會自動覆寫。按「重新規劃熱門景點」可先預覽每天的安排與候選，再「另存新旅程」。原手帳中的編輯、航班、住宿、花費、照片與備忘留在原手帳。新旅程的資料會沿用原網址的瀏覽器儲存區，並支援既有備份與匯入功能。

代表景點資料版本：2026-11-21。國外景點名稱與座標由各 Wikipedia 景點條目核對；慕尼黑、布拉格、京都、東京、巴黎、倫敦、羅馬、福岡、大阪、首爾附有代表景點種子清單，其他城市仍可查詢公開景點。台灣沿用交通部觀光署的正常營運、公開景點資料；台北、花蓮、台中、台南、高雄、宜蘭另提高代表景點優先度，鄉鎮查詢維持行政區範圍。資料查詢僅傳送目的地與公開景點編號，不傳送私人行程或筆記。

規劃參考：[慕尼黑官方遊程](https://www.munich.travel/en/topics/things-to-do/itinerary-suggestions)、[布拉格官方一日遊](https://prague.eu/en/home/discover/one-day-in-prague-you-wont-want-to-leave/)、[京都官方區域交通導覽](https://kyoto.travel/en/getting-around/)、[東京官方五日遊](https://www.gotokyo.org/en/story/walks-and-tours/tokyo-itinerary/index.html)、[巴黎必看地標](https://parisjetaime.com/eng/article/Paris-10-must-sees-a992)、[倫敦熱門景點](https://www.visitlondon.com/things-to-do/sightseeing/london-attraction/top-ten-attractions)、[臺北熱門景點](https://www.travel.taipei/zh-tw/must-visit/attractions/)。時間為規劃範例，開放日、門票、預約與實際交通仍應依景點官方資訊調整。

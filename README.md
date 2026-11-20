# 慢慢走旅行手帳・進階版

單一 HTML、繁體中文、手機優先的本機旅行手帳。直接開啟 `慢慢走旅行手帳-進階版.html`，或使用對應的 GitHub Pages 網址。

- 精緻手繪速寫：和紙白、Huninn 字型、墨棕細線與粉彩；城市封面依慕尼黑、福岡、東京自動變換。其他城市使用明確標示的旅行靜物，不套用其他城市地標。
- 保留城市搜尋、旅行日期與天數、航班及住宿資料、照片明信片相簿、待辦購物清單與花費記錄。
- 拖住行程卡片的「拖曳」把手即可排序；拖到上方其他日期可跨日移動。航班及固定預約不能拖動。調整後標記交通待重查，並提示時間重複、逆序或已有停留時間的重疊。可復原最近一次移動；交通與班次仍需自行查證。
- 重要備忘錄支援新增、編輯、重要置頂、搜尋、指定旅行日、完成狀態與刪除復原。每份旅程最多 200 則。舊備忘及隨手便條保留；每日手記依日期分開記錄。
- 「備忘」頁底部提供備份與匯入，包含保留中的旅程、每日手記、清單、備忘與照片。匯入會另建副本；回收區旅程請先還原再備份。最多匯入 50 份旅程，JSON 上限 150 MB。
- 個人紀錄只保存在目前瀏覽器。兩個版本使用獨立的 localStorage／IndexedDB，互不覆寫；跨裝置請使用備份匯入。分享公開網址只分享程式，不會分享私人紀錄。
- 所有插畫內嵌於 HTML；Huninn 網路字型、城市資料搜尋、OCR 辨識元件與地圖需要網路，沒有網路時採用系統字型。

原版 `index.html` 及原 Sites 網址獨立維護；本進階版不取代原版或另一份旅遊小幫手。

## 新增城市插畫

使用內建 imagegen 產生，縮為 1280 × 853 JPEG，移除 EXIF／IPTC／註解後內嵌。既有八張手繪插畫沿用專案素材；沒有將個人照片或測試備份放入公開版本。

- `assets/illustrations/fukuoka-handdrawn.jpg`：福岡塔、中洲屋台、那珂川、太宰府梅花、拉麵與旅行箱的旅行意象拼貼，非單一實際視角。
- `assets/illustrations/tokyo-handdrawn.jpg`：淺草雷門、晴空塔、街屋、電車、相機與花草。

共用繪製提示詞：Exquisite brown-gray fine pen lines, naturally irregular pencil strokes and delicate crosshatching, soft translucent pastel watercolor, subtle dry pigment, warm ivory paper #FFFCF6, muted coral #F2A497, pale ochre #F6D27A, powder blue #A8D3E6 and sage #B9DAA5. Carefully observed miniature architecture, botanical detail, soft daylight, airy ivory feathered edges. Landscape 3:2. No writing, logos, UI, watermark, flat vector, 3D or photorealism.

福岡主題提示詞：Slender triangular Fukuoka Tower with lattice detail; Nakasu yatai stall with coral awning and paper lanterns beside Nakagawa river, stools, steaming ramen, riverside houses, trees, low bridge, water reflections, Dazaifu plum blossom branch, small coral suitcase. Artist travel collage, not a literal view.

東京主題提示詞：Asakusa Kaminarimon gate with a large red lantern without writing, traditional shop facades and plants, Tokyo Skytree with circular observation decks, a modest train, tea cup, camera, ginkgo leaves and flowers. Travel collage with observed proportions and roof details; no other city landmarks.

# 皮膚新編（Sinica 1790）v0.2.1 訂正附檔

這次對第八批細讀筆記中列出的 30 個位置回圖，採納 18 處，共 19 字。另有 12 處保留原讀，其中 7 處仍待細辨。全書轉錄使用[固定 v0.2.0](https://doi.org/10.5281/zenodo.24147444)；引用訂正內容時請列出底本 DOI、附檔版本與單元 ID。

- `ERRATA.json` 提供每處的舊字、新字、原件位置、底本雜湊與單元定位。
- `CORRECTIONS.md` 列出訂正依據、原讀保留和待查狀態。
- `SHA256SUMS` 供查核同一版本附檔。

套用資料時，先核對 ZIP 內 `book.json` 的 SHA-256，再用 `page_id` 及 `unit_id` 找到單元。按 `range` 讀取單元的 `text`，以 Unicode 碼位從零起算且結束位置不含在內。舊字吻合才替換。此次訂正等長，公開資料保留底本位置。

訂正採 AI 輔助逐處回圖，未經人類全文雙校或專家審定。訂正資料與說明由曲宸宇整理，以 [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) 釋出。影像原件由牛津博德利圖書館提供。[館方原件](https://digital.bodleian.ox.ac.uk/objects/82eb7f9d-ea3e-4f71-a835-74f2c5164161/)

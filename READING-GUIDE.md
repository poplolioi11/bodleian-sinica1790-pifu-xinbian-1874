# 如何閱讀本版

先選book.json中的page_id，再利用SOURCE-MAP.json的官方canvas/影像、整幀hash和面裁框回到原件。`fNNN-R/L`是官方影像的右/左面定位，不是推算的原印頁碼；有讀出的原頁碼則在paratext單位，未解者不依序補數。

book.txt依原有單位陣列輸出。漢文主欄通常由右至左、欄內由上至下；英文導言由段落上至下。每單位的換行以及頁標籤是資料導航，不是古書新增句讀。這個TXT不是另製的通順連讀本。

目錄與冊題的小字句尾另列單位；READING-MAP中continuation_of指向它接續的主文。小註的attachment_to與insertion_after保留已觀察的掛接；沒有可靠錨點者留空，不猜成確定插入位置。圖內只錄「第一」至「第五」等可見標號；沒有圖時應按來源連結核對，不能將圖號當正文數列。

中英醫名表按原印橫列中文左至右、行由上至下，同row_id連到英文；類目、旁註及章節引用分層。`„`是對低位雙逗狀重複記號的所選表示，沒有替它展開前一病名，精確碼位未認證。TABLE-CELLS.csv保存同一批原字串；row_id缺另一語言時不補造譯名。

疑讀以uncertainty_ids掛接側檔。這份初錄保留暫讀字，因此不一定在TXT每字插入符號；引用與計量研究須同時看uncertainties.json。`□`是原初錄已有的單字方框；空字串配unknown-extent表示已看但未解的邊字/墨痕，不是零個原字，也不是尚未處理。gaiji的穩定ID只供回指，沒有代換原字串。

## English guide

Page IDs locate right/left faces within official source frames; they do not infer printed page numbers. TXT follows saved unit order and is not a modern continuous reading edition. Small notes and wrap endings remain separate and are linked where an attachment was observed. Chinese terminology cells are read horizontally and paired with English by row_id; ditto marks are preserved rather than expanded. Consult uncertainty and gaiji sidecars before quoting or counting words. Only labels of the five source figures are transcribed; follow the official image links to inspect their visual content.

# 皮膚新編：轉錄與中英醫名對照

Pi fu xin bian [Manual of skin diseases]: Transcription and bilingual terminology

版本 0.1.0，AI 初錄。[倉庫](https://github.com/poplolioi11/bodleian-sinica1790-pifu-xinbian-1874)與[版本發行頁](https://github.com/poplolioi11/bodleian-sinica1790-pifu-xinbian-1874/releases/tag/v0.1.0)提供本版資料；製備時 DOI 尚未指派，正式封存識別碼以後續紀錄為準。

《皮膚新編》（Pi fu xin bian）是嘉約翰（John Glasgow Kerr）口譯、林湘東筆述，1874年由廣州（Canton）博濟醫局刊行的皮膚病漢文著作，現藏牛津Bodleian Libraries，館藏號Sinica 1790。英文導言說明以Fenwick的Medical Diagnosis後部為基礎，並交代廣州地方用名、外國名稱音譯及跨地區術語徵集的做法。全書分八冊、共128節，包含皮膚症狀與病名分類、附方、圖號及中英醫名對照，可供晚清醫學史、翻譯史與醫療傳教史研究。本版提供117個原印書面的AI初錄，以JSON、TXT及TEI逐面對應官方原件，另附小註與表格讀序、疑讀及來源定位；不含來源影像。疑讀已標記，尚未經人類全文校勘或專家審定。

Pi fu xin bian [Manual of skin diseases] was orally translated by John Glasgow Kerr (嘉約翰) and written down by Lin Xiangdong (林湘東), and published by the Boji medical institution in Canton (Guangzhou) in 1874; this copy is Bodleian Sinica 1790. Its English introductory notice identifies the latter part of Fenwick’s Medical Diagnosis as its basis and explains the use of Canton names, transliteration of foreign names and collection of terminology from other regions. The work contains 128 sections in eight internal divisions, with classifications of skin conditions, appended formulas, figure numbers and a bilingual terminology table. This dataset supports histories of medicine, translation and medical missions through an AI-assisted initial transcription of 117 original-print faces in JSON, TXT and TEI, linked to the official facsimile with note, table and uncertainty records. Source images are excluded. Uncertain readings are marked; the text has not undergone full human collation or expert approval.

117個原印書面、1,660個文字單位、472筆疑讀。JSON/TXT/TEI保留相同字串及單位順序。正文的128節與八冊是書內編排；本館藏是一冊，不能把八冊計為八本已完成作品。另附40項原書附方文字和五圖的編號，沒有散布圖像或將舊說改寫為現代指引。

- [book.json](book.json)：文字、單位、來源與層別主本。
- [book.txt](book.txt)：依固定單位順序的直接閱讀檔；頁標籤/分隔換行是導航。
- [book.tei.xml](book.tei.xml)：TEI P5交換檔，逐單位文字可回讀。
- [READING-GUIDE.md](READING-GUIDE.md)及[READING-MAP.json](READING-MAP.json)：小字、跨欄續文及中英表的閱讀關係。
- [TABLE-CELLS.csv](TABLE-CELLS.csv)：原表文字、row_id與語言；不現代化醫名或展開重複符。
- [uncertainties.json](uncertainties.json)、[gaiji.json](gaiji.json)：疑字、空痕與既有方框的候選及位置。

請先讀[QUALITY.md](QUALITY.md)、[METHODS.md](METHODS.md)、[TRANSCRIPTION-POLICY.md](TRANSCRIPTION-POLICY.md)及[RIGHTS.md](RIGHTS.md)。本初錄版未採入另行獨立讀稿，尚未經人類全文雙校、專家審定、同儕審查或準確率量測。

整理者：曲宸宇（Chu, Chen-Yu；帳號poplolioi11），[ORCID](https://orcid.org/0009-0003-9738-6914)。歷史作者/口譯/筆述責任不列為現代資料集共同作者。引用見[CITATION.cff](CITATION.cff)。

[Digital Bodleian原件](https://digital.bodleian.ox.ac.uk/objects/82eb7f9d-ea3e-4f71-a835-74f2c5164161/) · [館目](https://east-asian.bodleian.ox.ac.uk/catalog/volume_1541) · [IIIF manifest](https://iiif.bodleian.ox.ac.uk/iiif/manifest/82eb7f9d-ea3e-4f71-a835-74f2c5164161.json)。來源影像、裁片、專用程式、提示及完整私人工作紀錄不公開；未提供從影像完整重跑的公開方法。本資料不代表館方背書。

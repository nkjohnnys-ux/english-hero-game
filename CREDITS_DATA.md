# 字庫與資料來源（v5）

| 資料 | 來源 | 授權 | 用途 |
|---|---|---|---|
| NGSL 1.2 (New General Service List) | Browne, C., Culligan, B. & Phillips, J. — newgeneralservicelist.com（取自 Hugging Face nltk-data-hub/words, config `ngsl`） | CC BY-SA 4.0 | 字表與詞頻排序（取前 2000 名，去除功能字後 1826 字） |
| BSL 1.2 (Business Service List) | Browne, C. & Culligan, B. — newgeneralservicelist.com（同上, config `bsl`） | CC BY-SA 4.0 | 商用字表（與 NGSL 不重複的 1733 字） |
| ECDICT | skywind3000/ECDICT | MIT | 中文釋義與詞性（經 OpenCC s2twp 轉台灣繁體） |
| Tatoeba 中英句對 | tatoeba.org，經 manythings.org/anki `cmn-eng.zip` | CC BY 2.0 FR | 例句與中文翻譯（經 OpenCC 轉繁） |
| 字根圖鑑 | 人工整理（58 個字首／字根／字尾） | — | 成員字由人工指定 |

字庫（遊戲內 VOCAB 資料，也就是 vocab.js）是以上 NGSL／BSL 字表的衍生作品，依 CC BY-SA 4.0 以相同授權釋出。
「聯想」是幫助記憶的聯想，不代表字源。

## v6 新增資料
- NGSL 2001+ 字、TSL 1.1（TOEIC Service List）、NAWL 1.0（New Academic Word List）：Browne, C., Culligan, B. & Phillips, J., CC BY-SA 4.0（newgeneralservicelist.com）；CSV 取自 koba-ninkigumi GitHub 整理版。
- ECDICT（skywind3000, MIT）：中文釋義與 IELTS 標記。
- Tatoeba（CC BY 2.0 FR）：例句。
- CEFR 等級為依來源清單推估：NGSL/BSL→B1、NGSL 2001+/TSL→B2、NAWL/IELTS→C1。

## v7
- 心流模式卡牌：原創文字＋表情符號設計，未使用任何真人照片或姓名。
- 新增的劇情干擾選項與中文翻譯為自行撰寫。

'''人工言語知識情報標準(CLaKIS: <span style="color:#3f9877;">C</span>on<span style="color:#3f9877;">La</span>ng <span style="color:#3f9877;">K</span>nowledge and <span style="color:#3f9877;">I</span>nformatics <span style="color:#3f9877;">S</span>tandard)'''は、人工言語界隈において共通的な事項や統一的に扱うべき事項、ならびに人工言語のための情報システムに関する技術や仕様について文書化し体系的に収載するための枠組み・標準である。

## CLaKIS 人工言語知識情報標準

### 扱う対象

- 共通的な事項:　りんご文など
- 統一的に扱うべき事項:　 CLA コードなど
- 情報システムに関する事項:　辞書システムなど

### 附番

領域分類のあとに成立西暦年四桁・連番五桁。年不明の場合は X000 と記す。連番の冒頭 0 パディングは必要のないときは省略して記述することができる。軽微な修正の場合は R 字に続けて連番三桁を付加し、そうでない場合は新たな番号を附番する。

`CLaKIS [a-z]{2}([0-9]{4}|X000)-[0-9]{5}(R[0-9]{3})?`

## BERN 基礎末端点資料記述子

基礎末端点資料記述子(BERN: Basic Endpoint Reference Notifier)は、同一の事項を扱う複数の標準(CLaKIS)文書を集成したもの。BCP に範をとっている。

### 附番

領域分類のあとに連番四桁。連番の冒頭 0 パディングは必要のないときは省略して記述することができる。

`BERN [a-z]{2}[0-9]{4}`

## 領域分類

CLaKIS 番号及び BERN 番号につけられる領域分類は次の通りである。なお、記号の直後に記載されている括弧内の数字は、前者がその分類に属する BERN の基点項目の数、後者が同じく CLaKIS 標準文書の数である(現在時点)。

- C：Classfication 　言語コード・言語分類
  - [C](./../index_repo/CC/CC.md)(2/6)：Code コード類(CLA コード、CSC コードなど)
  - [T](./../index_repo/CT/CT.md)(1/2)：Taxonomy 分類(Se 分類、モユネ分類など)
  - [X](./../index_repo/CX/CX.md)(0/0)：Others その他
- S：Software System ソフトウェアシステム
  - [D](./../index_repo/SD/SD.md)(0/0)：Dictionary 辞書
  - [P](./../index_repo/SP/SP.md)(0/0)：Pronunciation/Phonology/Phonetics 発音・音韻・音声
  - [W](./../index_repo/SW/SW.md)(0/0)：Word Creation 造語・語彙自動生成
  - [F](./../index_repo/SF/SF.md)(0/0)：Inflection 語形変化
  - [T](./../index_repo/ST/ST.md)(0/0)：Translator 翻訳機
  - [R](./../index_repo/SR/SR.md)(0/0)：Character/Sound Recognition 文字認識・音声認識
  - [C](./../index_repo/SC/SC.md)(1/2)：Corpus Management コーパス・例文管理
  - [S](./../index_repo/SS/SS.md)(0/0)：Social Platform 交流サイト・SNS
  - [X](./../index_repo/SX/SX.md)(0/0)：Others その他製作支援システム
- E：Encoding 文字エンコーディング
  - [E](./../index_repo/EE/EE.md)(0/0)：Extended Encoding 文字エンコーディング拡張
  - [C](./../index_repo/EC/EC.md)(0/0)：Custom Encoding 独自の文字エンコーディング
- T：Typesetting 組版・フォント
  - [R](./../index_repo/TR/TR.md)(0/0)：Custom Font Renderer 独自フォントレンダラ
  - [F](./../index_repo/TF/TF.md)(0/0)：Font Creation 個別フォント製作
  - [X](./../index_repo/TX/TX.md)(0/0)：Others その他
- D：Documentation 文書化
  - [S](./../index_repo/DS/DS.md)(1/1)：Sentence 人工言語の文例
  - [R](./../index_repo/DR/DR.md)(0/0)：Reference 人工言語の解説書
  - [X](./../index_repo/DX/DX.md)(0/0)：Others その他人工言語の資料
- F：Formal Description 形式的記述
  - [F](./../index_repo/FF/FF.md)(0/0)：Formal Grammar 形式文法
  - [X](./../index_repo/FX/FX.md)(0/0)：Others その他形式的記述
- R：Organisation Affairs 組織事務
  - [D](./../index_repo/RD/RD.md)(0/0)：Organisation Identifier 組織識別表現(名前やシンボルマーク、ロゴ、ドメインなど)
  - [R](./../index_repo/RR/RR.md)(0/0)：Resource 議事録・イベント資料
  - [B](./../index_repo/RB/RB.md)(0/0)：Bots ボット
  - [X](./../index_repo/RX/RX.md)(0/0)：Others その他

## 例示

- CC2015-1 CLA コード第 1 版
- CC2021-1 CLA コード第 2 版
- CC2021-2 CLA コード第 3 版基本
- CC2021-3 CLA コード第 3 版データ
- CC2021-4 CLA コード第 3 版手続
- CC2021-5 CLA コード第 3 版ソフトウェア
- CTX000-1 Se 分類
- CT2014-1 モユネ分類
- DS2021-1 SCJ 共通りんご文

# 「Competitive Programming / 競技プログラミング」用語史：URL列挙と“どの主張の証拠か”整理

あなたが書いたストーリー（以下の P1〜P5）に対応づけて、ここまで出てきた URL を **「そのリンクが何の証拠になっているか」**という観点で整理しました。

- **P1**: 1999年の NUS が最初期の “competitive programming” の明確な用例（少なくとも授業名として）。
- **P2**: 2000年代は “programming contest / programming competition / algorithm contest / sport programming …” 等が並列で、ジャンル名が収斂していない。
- **P3**: 2000年代の “competitive programming” は（存在はするが）覇権ではなく、用例は散発的。
- **P4**: 2010年に Halim が “Competitive Programming” を出版（授業 CS3233 由来）し、ラベルとして拡散の核になった。
- **P5**: 2012年頃には（少なくとも英語圏の複数ソースで）“competitive programming” が一般的な言い方として目立つようになる（＝収斂が進む）。

---

## 1) P1（1999 NUSが最初期）を直接支える一次資料

- `https://www.comp.nus.edu.sg/~cs3233/1999/info.html`  
  → 1999年の **CS3233 の Course Information**。見出しに **“CS3233 Competitive Programming”** とあり、授業名として明示。  
  → **P1 の中核証拠**（「1999年に NUS が授業名として使っている」）。

- `https://www.comp.nus.edu.sg/~cs3233/1999/`  
  → 1999年コースの入口（Course Information へ辿れる）。  
  → **P1 の補助**（1999コース一式が残っている）。

- `https://www.comp.nus.edu.sg/~cs3233/`  
  → CS3233 のページ（2008/09 表示だが、アーカイブに **“1999/2000”** が列挙され、1999ページへリンク）。  
  → **P1 の補助**（“1999がアーカイブにある”ことの確認経路）。

- `https://www.cs.tufts.edu/~nr/cs257/archive/brenda-cheang/automated-grading.pdf`  
  → （後述の論文のPDFミラー）本文に **「Online Judge が 1999年7月に “CS3233 Competitive Programming” で使われた」**旨が書かれている。  
  → **P1 の補助**（1999の CS3233=Competitive Programming を“第三者の論文”が言及）。

---

## 2) P2（2000年代は用語が並列）と、P3（CPは覇権でない）を支える「主流ラベルは別だった」資料

### 2.1 “programming contest(s)” が前面に出ている（2000年代以前〜2000年代の代表例）

- `https://www.cs.dartmouth.edu/~kotz/research/astrachan-contest/astrachan-contest.pdf`  
  （SIGCSE’93 の “The Internet Programming Contest: A Report and Philosophy” のPDF）  
  → 1990年代の文脈で、中心語彙は **programming contest(s)**。  
  → **P2 の下支え**（少なくとも90年代は “competitive programming” が一般ラベルではない）。

- `https://users.cs.duke.edu/~ola/papers/internet.pdf`  
  → 同論文の別ホスト版（Duke）。  
  → **P2 の補助**（同じ一次資料の別入手経路）。

- `https://katahdin.dartmouth.edu/~kotz/research/astrachan-contest/index.html`  
  → 同論文の索引ページ（DOI等への導線）。  
  → **P2 の補助**（書誌・位置づけの確認用）。

- `https://users.cs.duke.edu/~ola/ipc.html`  
  → Duke の Internet Programming Contest ページ。  
  → **P2 の補助**（当時の “programming contest” 文化の語り口が見える）。

### 2.2 2003年の“定番本”が「Programming Contest Training Manual」を名乗っている（＝当時の覇権語彙が別）

- `https://link.springer.com/book/10.1007/b97559`  
  → Skiena & Revilla の本が **“Programming Challenges: The Programming Contest Training Manual”** であることが出版社ページで確認できる。  
  → **P2/P3 の強い補強**（2003年に世界的に読まれた本の看板語は “programming contest”）。

- `https://books.google.com/books/about/Programming_Challenges.html?id=lcnSCDcDocMC`  
  → Google Books で同書を確認。  
  → **P2/P3 の補助**（発行年・書名の確認）。

- `https://archive.org/details/programmingchall0000skie`  
  → Internet Archive の書誌（2003、タイトルに “programming contest training manual”）。  
  → **P2/P3 の補助**（書誌情報の別経路）。

- `https://www3.cs.stonybrook.edu/~skiena/392/programs/`  
  → Skiena 本人（Stony Brook）のページで、同書名を明記。  
  → **P2/P3 の補助**（著者側のページで “Programming Contest” を看板語にしている）。

### 2.3 ICPC 側の呼称が “Programming Contest” で回っている痕跡（2000年代）

- `https://is.ifmo.ru/download/_acm_standings_2004.pdf`  
  → 2004年の standings PDF（見出し等に “Programming Contest” 系の表現が出る）。  
  → **P2/P3 の補助**（少なくとも 2004 では “Programming Contest” が自然語彙として流通）。

- `https://icpc.global/regionals/finder/world-finals-2004`  
  → ICPC 側の World Finals 2004 情報ページ。  
  → **P2 の補助**（“ICPC=Programming Contest” の枠組みが継続）。

### 2.4 2000年代の競技界隈で「OJ／ICPCフォーマットのコンテスト」語彙が前面（“competitive programming” ではない）

- `https://ioinformatics.org/files/ioi-journal/INFOL035.pdf`  
  → IOI/教育寄りの記事（本文の語り口は **“programming contest training sites”** 等）。  
  → **P2/P3 の補助**（競技系を指す語彙として “programming contest” が自然）。

---

## 3) P3（2000年代の “competitive programming” は散発）を支える「“competitive programming” の早期用例」＝ただし少数派っぽい例

> “存在しない” の証明はできないので、ここは **「（A）当時の主流資料は別の言い方」**＋**「（B）competitive programming という語も少数ながら出る」**の両建てで説得するのが現実的です。  
> この節は（B）側。

- `https://web.cecs.pdx.edu/~bart/papers/pnsqc-acm.pdf`  
  → 2001年 “Experience With A Process For Competitive Programming” （論文PDF）。  
  → **P3 の重要証拠**（NUS外でも 2001 に “competitive programming” をタイトルに採用している例がある＝ただし学術寄り・散発）。

- `https://web.cecs.pdx.edu/~bart/bib.html`  
  → 上の論文が **2001年（PNSQC 2001 / October 2001）**であることの書誌確認。  
  → **P3 の補助**（年の裏取り）。

- `https://bibtex.github.io/ITiCSE-2008-JiWC.html`  
  → ITiCSE 2008 の論文 “An experience of detecting plagiarized source codes in competitive programming contests” の書誌。  
  → **P3 の補助**（2008にも “competitive programming contests” が学会系で使われる）。

- `https://www.researchgate.net/profile/Hwan-Gue-Cho/publication/220808406_An_experience_of_detecting_plagiarized_source_codes_in_competitive_programming_contests/links/5eb2147e92851cb267780bae/An-experience-of-detecting-plagiarized-source-codes-in-competitive-programming-contests.pdf`  
  → 上論文のPDF（ResearchGate）。  
  → **P3 の補助**（本文確認用）。

---

## 4) P4（2010 Halim本＝NUS授業名が拡散核）を支える資料

### 4.1 “Competitive Programming 1 (CP1)” 本体（授業由来の明記）

- `https://www.comp.nus.edu.sg/~stevenha/myteaching/competitive_programming/cp1.pdf`  
  → CP1 のPDF。Acknowledgements / Copyright 付近に  
  **「CS3233 - ‘Competitive Programming’ module からこの本が生まれた」**趣旨の記載がある。  
  → **P4 の一次証拠**（“授業名→本タイトル”の接続が本人の文面で出る）。

### 4.2 CPシリーズの公式/半公式ハブ（2010〜継続の宣言）

- `https://cpbook.net/`  
  → CPシリーズのコンパニオンサイト。トップで **“2010 - present”** のような説明があり、シリーズが2010開始の自己申告になっている。  
  → **P4 の補助**（2010起点の自己記述）。

- `https://cpbook.net/details?cp=1`  
  → CP1 の詳細ページ（シリーズ構成の導線）。  
  → **P4 の補助**。

### 4.3 Halim が NUS の CS3233 と結びついた人物であること（背景）

- `https://www.comp.nus.edu.sg/~stevenha/CV.pdf`  
  → Steven Halim の CV（学歴・所属などの確認用）。  
  → **P4 の補助**（「NUS の教員として CS3233 と関係」周辺事情）。

- `https://www.comp.nus.edu.sg/~stevenha/cs3233.html`  
  → Halim 個人サイト内の CS3233 案内（現行情報も混ざるが、CS3233=Competitive Programming の位置づけが読み取れる）。  
  → **P4 の補助**。

---

## 5) P5（2012ごろ “competitive programming” が目立ってくる）を支える資料

### 5.1 2012：CP2 が “Competitive Programming” を看板に出版（＝本タイトルとして定着が進む）

- `https://books.google.com/books/about/Competitive_Programming_2.html?id=z0AvMwEACAAJ`  
  → Google Books に **“Lulu.com, 2012”** として掲載。  
  → **P5 の強い証拠**（2012時点で “Competitive Programming” がシリーズ名として前面）。

### 5.2 2012：TopCoder 文脈でも “competitive programming” が PR で使われる

- `https://www.prnewswire.com/news-releases/topcoder-announces-dena-as-sponsor-of-the-2012-tco-151364365.html`  
  → 2012-05-14 の PR Newswire。TopCoder Open を **“competitive computer programming … tournament”** 的に表現。  
  → **P5 の強い証拠**（企業PR文脈で “competitive programming” が普通に出る）。

- `https://www.prnewswire.com/news-releases/topcoder-announces-champions-of-2012-topcoder-open-in-orlando-172857771.html`  
  → 2012-10-05 の PR Newswire。TCO を **“competitive programming … tournament”** と表現。  
  → **P5 の補強**（同年に複数回出る）。

> 参考：TopCoder の当時ページ（`archive.topcoder.com` 配下）は、検索スニペットでは取得できても、現在アクセスが 403 になるものが多いです。  
> そのため「TopCoderサイト本文の一次確認」よりも、上の PRNewswire のような“日付つき第三者アーカイブ”の方が引用しやすいです。

### 5.3 2013：Wikipedia に “Competitive programming” が独立項目として立つ（＝一般概念としての定着）

- `https://en.wikipedia.org/wiki/Competitive_programming`  
  → 現在の項目本体。  
  → **P5 の補助**（項目として成立している事実）。

- `https://en.wikipedia.org/w/index.php?title=Competitive_programming&action=history`  
  → 履歴ページ。**初版がいつか（2013主張の検証）**をここで確認できる。  
  → **P5 の検証用リンク**（あなたの「2013年に項目」が事実かを最終確認する場所）。

---

## 6) ユーザーが挙げた「後年の資料」＝“定着後”を示す（ただし初期史の証拠としては弱い）

- `https://cphof.org/`  
  → Competitive Programming Hall of Fame（2021年開始のサイト）。  
  → **“用語の覇権が確立した後”の証拠**（P5以降の世界の反映）。初期史の一次証拠にはなりにくい。

- `https://cphof.org/standings/tco_algo/2012`  
  → Hall of Fame 側の TCO 2012 standings（後年編集のまとめ）。  
  → **“後から見た整理”**としては便利だが、P5以前の一次資料ではない点に注意。

- `https://cses.fi/book/index.html`  
  → Competitive Programmer’s Handbook（CSES、2018）。  
  → **“用語が完全に定着した後の教科書”**としての証拠。

- `https://codeforces.com/blog/entry/112340`  
  → 2023年の Codeforces 記事。  
  → **“用語定着後の言説”**。初期の命名過程の一次資料にはならない。

---

## 7) 「2000年代に competitive programming が弱い単語だった」を“証拠で言う”ための組み立て方（実務メモ）

「弱い／覇権でない」を言い切るには“負の証明”になりがちなので、次の形が安全です：

1. **当時の中心プレイヤーや定番教材が何と呼んでいたか**を示す（＝主流語彙の提示）  
   - 2003年の定番本：`https://link.springer.com/book/10.1007/b97559`（Programming Contest Training Manual）  
   - 1993年の分散コンテスト論文：`https://www.cs.dartmouth.edu/~kotz/research/astrachan-contest/astrachan-contest.pdf`（Programming Contest）  
   - 2004年のICPC文脈：`https://is.ifmo.ru/download/_acm_standings_2004.pdf`（Programming Contest 系）

2. そのうえで **competitive programming という語も“存在はするが散発”** と示す  
   - 2001年：`https://web.cecs.pdx.edu/~bart/papers/pnsqc-acm.pdf`  
   - 2008年：`https://bibtex.github.io/ITiCSE-2008-JiWC.html`

3. 最後に **2010（Halim本）→2012（企業PRやCP2）** の“収斂の兆候”を置く  
   - 2010ごろのCP1：`https://www.comp.nus.edu.sg/~stevenha/myteaching/competitive_programming/cp1.pdf`  
   - 2012のCP2：`https://books.google.com/books/about/Competitive_Programming_2.html?id=z0AvMwEACAAJ`  
   - 2012のTopCoder系PR：`https://www.prnewswire.com/news-releases/topcoder-announces-dena-as-sponsor-of-the-2012-tco-151364365.html`

この3段構成なら、
- 「2000年代は別語彙が主流」も、
- 「でも “competitive programming” の先行例はある」も、
- 「2010〜2012で収斂が進んだ」も、
同時に“資料で”言えます。

---

# 用語史エビデンス一覧（ラベル別 URL と「どの主張の証拠か」）

**前提のストーリー（P1–P5）**
- **P1**: 1999年の NUS が最初期の “competitive programming” の明確な用例（少なくとも授業名として）。  
- **P2**: 2000年代は *programming contest / programming competition / sport programming / algorithmic programming contest / programming challenges / online judge* 等の表現が並列していた。  
- **P3**: 2000年代の “competitive programming” は存在したが主流ではなく、散発的な用例があるに留まる。  
- **P4**: 2010年に Steven Halim（NUS）が `Competitive Programming` をタイトルとする教材／書籍を出し、可視化・拡散の核になった。  
- **P5**: 2012–2013 年ごろまでに `competitive programming` がジャンル名として目立つようになった（企業PR・Wikipedia 等で可視化）。

---

## A. **“competitive programming” — NUS 起点の一次証拠（P1, P4）**
- **NUS CS3233 (1999) — コース情報 / Course information**  
  - https://www.comp.nus.edu.sg/~cs3233/1999/info.html  
  - **何を示すか**: 1999年に `CS3233 — Competitive Programming` が授業名として存在していた（P1 の一次証拠）。 :contentReference[oaicite:0]{index=0}
- **CS3233 アーカイブ（コース一覧）**  
  - https://www.comp.nus.edu.sg/~cs3233/  
  - **何を示すか**: 1999 のアーカイブが残っている（P1 補強）。 :contentReference[oaicite:1]{index=1}
- **Steven Halim — CP1（授業由来の教材 PDF）**  
  - https://www.comp.nus.edu.sg/~stevenha/myteaching/competitive_programming/cp1.pdf  
  - **何を示すか**: 教材（CP1）が CS3233 に結び付けられており、2010 前後に授業外へ配布が始まったことの本人／教材上の記述（P4）。 :contentReference[oaicite:2]{index=2}
- **CP シリーズ公式ページ（自己申告: 2010–present）**  
  - https://cpbook.net/  
  - **何を示すか**: Halim 系 CP 書籍シリーズのポータル（P4 補強）。 :contentReference[oaicite:3]{index=3}

---

## B. **「programming contest / programming competition」系 — 90年代〜2000年代の主流ラベルを示す例（P2）**
- **Duke — Internet Programming Contest (1990s)**  
  - https://users.cs.duke.edu/~ola/ipc.html  
  - https://contest.mff.cuni.cz/old/archive/duke1993/index.html  
  - **何を示すか**: 1990年代から “Internet Programming Contest” / “programming contest” が使われていた（P2：90年代の主流語彙）。 :contentReference[oaicite:4]{index=4}
- **Skiena & Revilla — *Programming Challenges: The Programming Contest Training Manual* (2003)**  
  - Springer: https://link.springer.com/book/10.1007/b97559  
  - Internet Archive / PDF: https://ia903207.us.archive.org/8/items/compatitive-programming/Books/Programming_Challenges.pdf  
  - **何を示すか**: 2000年代の代表的テキストが “Programming Contest” を冠している（P2 の強い証拠）。 :contentReference[oaicite:5]{index=5}
- **Programming contest 問題アーカイブ（各大会 — 1990s〜）**  
  - https://www.cs.nthu.edu.tw/~progcont/Olympia/  
  - **何を示すか**: 多数の大学・地域で “programming contest/competition” が運用されている実例群（P2 補強）。 :contentReference[oaicite:6]{index=6}

---

## C. **「algorithmic programming contest / ICPC」系（P2）**
- **ICPC（International Collegiate Programming Contest）公式**  
  - https://icpc.global/  — “the International Collegiate Programming Contest is an algorithmic programming contest…”  
  - https://icpc.global/regionals/abouticpc  
  - **何を示すか**: ICPC は公式に “algorithmic programming contest” と表現しており、学会・大会側で別語彙が強く使われている（P2）。 :contentReference[oaicite:7]{index=7}

---

## D. **「sport(s) programming / sports programming / competitive programming（地域語）」系（P2）**
- **“Sports programming / Sport programming” 用例（説明記事・スライド）**  
  - https://ii.uni.wroc.pl/media/uploads/2021/12/06/bartosz-kostka.pdf  
  - **何を示すか**: 欧州語圏や東欧圏では“sports programming / sport programming（スポーツ的プログラミング）”という呼称が一般的で、地域語と英語表記が混在している（P2）。 :contentReference[oaicite:8]{index=8}
- **Codeforces 等コミュニティ議論（言語差）**  
  - https://codeforces.com/blog/entry/67253  
  - **何を示すか**: ロシア語・ポーランド語等で “sports programming” が一般名として使われる事情（P2 補強）。 :contentReference[oaicite:9]{index=9}

---

## E. **“competitive programming” が散発に見える（P3 の証拠） — NUS 外の早期例／学会例**
- **Bart Massey — “Experience With A Process For Competitive Programming” (PNSQC 2001)**  
  - https://web.cecs.pdx.edu/~bart/papers/pnsqc-acm.pdf  
  - **何を示すか**: 2001 年に `competitive programming` をタイトルに使う大学側の例がある（NUS外の散発例 → P3）。 :contentReference[oaicite:10]{index=10}
- **ITiCSE / SIGCSE など学会における “competitive programming contests” の使用（2008）**  
  - DB / BibSLEIGH: https://bibtex.github.io/ITiCSE-2008-JiWC.html  
  - PDF: https://www.researchgate.net/profile/Hwan-Gue-Cho/publication/220808406_An_experience_of_detecting_plagiarized_source_codes_in_competitive_programming_contests/links/5eb2147e92851cb267780bae/An-experience-of-detecting-plagiarized-source-codes-in-competitive-programming-contests.pdf  
  - **何を示すか**: 2008 年に学術会議タイトル／論文中で `competitive programming contests` と言語化されている（P3）。 :contentReference[oaicite:11]{index=11}

---

## F. **Halim の書籍群（2010–）と 2012 前後の可視化（P4–P5）**
- **CP シリーズ（Halim） — CP1 PDF（授業由来）、CP2/CP3/CP4 の出版情報**  
  - CP1 PDF（NUS 教材）: https://www.comp.nus.edu.sg/~stevenha/myteaching/competitive_programming/cp1.pdf  
  - CP portal / CP2 Google Books: https://books.google.com/books/about/Competitive_Programming_2.html?id=z0AvMwEACAAJ  
  - CP portal: https://cpbook.net/  
  - **何を示すか**: 2010 年前後から Halim 系の `Competitive Programming` 書籍が出回り、教材として広く参照されるようになった（P4）。 :contentReference[oaicite:12]{index=12}
- **TopCoder（企業／大会側）の 2012 年頃の PR（“competitive programming” の用例）**  
  - PR Newswire (TopCoder Open 2012): https://www.prnewswire.com/news-releases/topcoder-announces-champions-of-2012-topcoder-open-in-orlando-172857771.html  
  - Topcoder Open archives: https://archive.topcoder.com/TCO/index.html  
  - **何を示すか**: 2012 年の企業PRで `competitive programming` を用いており、（大会運営側でも用語が普通に使われる水準に達している）ことを示す（P5）。 :contentReference[oaicite:13]{index=13}
- **Wikipedia 項目作成（2013）**  
  - https://en.wikipedia.org/wiki/Competitive_programming  
  - 履歴: https://en.wikipedia.org/w/index.php?title=Competitive_programming&action=history  
  - **何を示すか**: 2013 年に独立項目ができることで「一般概念としての可視化」が確定する（P5）。 :contentReference[oaicite:14]{index=14}

---

## G. **補助資料（用語の多様さを示す追加例）**
- **“algorithmic programming contest” (regional contest usages / event names)**  
  - https://icpc.global/regionals/finder/world-finals-2004  — （ICPC の語彙） :contentReference[oaicite:15]{index=15}
- **各大学の “programming contest” ページ（1990s–2000s）**  
  - University of Texas 1995 ACM Programming Contest: https://www.cs.utexas.edu/~cline/ACM/acmprob95.html :contentReference[oaicite:16]{index=16}
  - Saint Louis / other ICPC resources: https://cs.slu.edu/~goldwasser/icpc/resources/ :contentReference[oaicite:17]{index=17}
- **問題アーカイブ群（複数大会で “programming contest” 表現）**  
  - https://www.cs.nthu.edu.tw/~progcont/Olympia/ :contentReference[oaicite:18]{index=18}

---

## H. **「これで P2/P3 をどう実証するか（論理構成の提案）」**
1. **当時の代表教材・大会名（2000s）の語彙**を見せる（→ Skiena 2003、ICPC、Duke IPC、各大学アーカイブ）。これで「2000年代の主流が **programming contest / programming competition / algorithmic programming contest** 系であった」ことを示す。 :contentReference[oaicite:19]{index=19}  
2. **NUS（1999）での `Competitive Programming` の早期固定例**を添える（→ CS3233 1999 の Course Info）。これで「competitive programming は 1999 にすでに科目名として存在した」という強い一次証拠を押さえる。 :contentReference[oaicite:20]{index=20}  
3. **NUS外での `competitive programming` の散発例**を示す（→ Bart Massey 2001、ITiCSE 2008）。これで「（存在はあるが）当時は散発例に留まっていた」ことを補強する。 :contentReference[oaicite:21]{index=21}  
4. **2010 年代（Halim 書籍）→ 2012 年頃の企業PR / Wikipedia の登場**を示し、語が可視的に収斂した経緯を描く（→ cpbook / TopCoder PR / Wikipedia）。 :contentReference[oaicite:22]{index=22}

---

## I. **注記・限界**
- 「用語が **絶対に**どの年に ‘覇権’ を取ったか」はコーパス（Web全体 /書籍 / Usenet /メールアーカイブ）を定量解析しないと断定はできません。上の整理は **“一次資料を年代順に並べ、主語彙の分布を示す”** ための準備です。  
- ここで示した証拠は **“2000年代に主流だった別ラベル（programming contest 等）が数多く存在し、competitive programming は局所的（NUS等）に早期出現していた”** ことを示すために十分実用的だと考えます。  
- （もしご希望なら）次は **Google Books Ngram / Usenet（Google Groups）全文検索 / Internet Archive の Wayback の定量調査**をやって、語頻度推移を数値で示せます（ワークフロー提案可）。

---

## J. **要点の短いまとめ（引用付き）**
- **1999 年：NUS が `CS3233 — Competitive Programming` を科目として掲示している**（一次証拠）。 :contentReference[oaicite:23]{index=23}  
- **1990s–2000s：代表教材・大会では “programming contest / programming competition / algorithmic programming contest” が主流語彙として見える（Skiena 2003、ICPC、Duke IPC 等）。** :contentReference[oaicite:24]{index=24}  
- **2001 / 2008：NUS 以外にも `competitive programming` の散発的用例は存在（Bart Massey 2001、ITiCSE 2008 等）** — しかし当時はまだ主流語ではなかった。 :contentReference[oaicite:25]{index=25}  
- **2010 年前後：Halim の教材／書籍が `Competitive Programming` を表題として流通し、2012–2013 年には企業PRや Wikipedia による可視化で語が広く認知されるようになった。** :contentReference[oaicite:26]{index=26}


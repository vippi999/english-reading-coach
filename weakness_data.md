> 保存記録です。初期データの暫定集計であり、現在の確定診断ではありません。通常の実践チャットは、下の「実読メモ」だけを追記します。

# 弱点の定量集計(Session 1 全詰まり事例)

作成:2026-07-12 / 母数:長文2本(犬猫・NZ羊)で観測された全31事例。恣意的判断を排し、ログの記録のみから分類

## 1. 全事例一覧

| # | 箇所 | 起きたこと | 分類 |
|---|---|---|---|
| 1 | as though | かたまり未知→「どこがイコール?」で迷子 | 熟語系(チャンク) |
| 2 | one(hear one say) | 初読で処理せず常識で復元 | 未処理(自動化) |
| 3 | they / do this | 白紙で読み飛ばし | 未処理(自動化) |
| 4 | as dogs became... | asを見てもいない | 未処理(自動化) |
| 5 | studied the amount of time をMと誤読 | O/M判定不能。原因は下記#6の構文未知 | 熟語系(構文パターン)+構文 |
| 6 | it took for ... to be adopted | 「take forの熟語?」→パターン未知 | 熟語系(基本動詞構文) |
| 7 | adopted / adapted | 語義混線→「適用」で誤確定 | 単語運用 |
| 8 | shelter | 既知だが検索遅延→以降ぐちゃぐちゃ | 単語運用 |
| 9 | wagging | 未知語 | 単語運用 |
| 10 | tail | 「耳」と誤固定(自己修正) | 単語運用 |
| 11 | visitors | 「取材した人」と誤読 | 単語運用 |
| 12 | that is | 言い換えと正しく処理 | **OK** |
| 13 | 長い主語+挿入+and並列 | つなげられず | 構文(保持・切れ目) |
| 14 | that raised(関係詞) | 主語欠落から正しく判定 | **OK** |
| 15 | the reason is because | パターン未知で停止 | 熟語系(構文パターン) |
| 16 | perhaps | 既知だが検索失敗 | 単語運用 |
| 17 | Take me home | 訳せず | 熟語系(基本動詞) |
| 18 | sheep読み飛ばし→thanで再読 | 再読で回復 | 処理速度(回復は適切) |
| 19 | in 1982: 22 | コロン=具体化を知らず「1982対22」 | 記号 |
| 20 | 22 sheep for every person | 「〜につき」パターン未知 | 熟語系(数量表現) |
| 21 | conditions impossible for humans | 後置修飾が取れず | 構文(切れ目) |
| 22 | With their amazing wool, clothing and shelter | 切れ目誤り(3名詞の列挙と解析) | 構文(切れ目) |
| 23 | 急にbirth-rate? | 列挙という段落構造の予測なし | 談話構造 |
| 24 | mind their own business | 断片的 | 熟語系(チャンク) |
| 25 | just over 5 sheep for every NZer | 「5匹減った」と誤読(for every 2回目) | 熟語系(数量表現) |
| 26 | fell by more than 7 million | byを使えず常識で正解に到達 | 熟語系(数量表現) |
| 27 | million | 即時換算不可→「多いぐらい」の霧 | 熟語系(数量表現) |
| 28 | セミコロン+日本の15,000 | 記号機能と文の役割が不明 | 記号+談話構造 |
| 29 | far to the south | far(程度)未知 | 熟語系(数量・程度) |
| 30 | regardless of | 速度内で正しく処理 | **OK** |
| 31 | high above のつなぎ | 曖昧なまま | 構文(軽) |

## 2. 集計(OK・回復3件を除く28件)

| 分類 | 件数 | 割合 | 中身 |
|---|---|---|---|
| **熟語系(広義)** | 11 | **39%** | チャンク(as though等)+基本動詞構文(it takes for to / take home)+数量・程度表現(for every / by / just over / million / far) |
| **単語の運用** | 6 | 21% | 全て1900圏内の語。未知1(wagging)、残り5は「知っているのに出ない・誤る」 |
| **構文(解析そのもの)** | 5 | 18% | 全て「切れ目・保持」型(長い主語、文頭前置詞句、後置修飾)。SVOC・関係詞・品詞の判定失敗は0件 |
| **未処理(自動化)** | 3+底流 | 11%+ | 初読で処理自体が走らない。件数は3だが、白紙化として全長文の底流に存在 |
| 記号 | 2 | 7% | コロン・セミコロン |
| 談話構造 | 2 | 7% | 「なぜこの文がここに?」 |

## 3. 二択への回答(データによる)

質問:「構文を英語のまま読めない」のか「熟語が分からない」のか

- **最大は熟語(39%)。ただし熟語帳に載る型より広い**。数量表現(for every, by, million)・基本動詞の構文(it takes for to)・接続のかたまり(as though)を含む「言い回しの知識」
- **構文知識の欠陥は小さい(18%)**。しかも全て「切れ目・保持」型で、SVOC・関係詞・品詞の判定ミスはゼロ。対照段落(NZ第2段落)では初読でも構文が通った。構文の勉強をゼロからやり直す必要はデータ上ない
- **「英語のまま読めない」の正体は構文力ではなく自動化**。初読で処理が走らず(未処理3件+白紙化)、精読すれば解けた事例(one, 関係詞判定)が複数ある。これは知識ではなく反復量の問題で、音読・再読でしか解決しない
- adopte型(単語運用)は21%で実在。1900の再起動はデータ上も正当

## 4. 注意

- 母数28件・長文2本。割合は今後の蓄積で変動しうる。週次プロトコルの欠落ノートで毎週更新する
- 「簡単な単語しかないのに読めない」の内訳はこれで説明がつく:簡単な単語で書かれた文の難所は、単語ではなく (a)言い回し39% (b)切れ目18% (c)処理が走らない、に集中している

## 5. 実読メモ

実践チャットが、ユーザー自身の発言を短く事実として追記する欄です。分類・診断・推測は行いません。

| 日付 | 出典 | 箇所 | ユーザーのメモ |
|---|---|---|---|
| 2026-07-18 | The Rules 1・Lesson 4 | 本文全体／but | butをそのままスラスラ読み進めた。butは言いたいところのはずだが、日本語では文末に付け足される感覚があり流してしまうので、見たら一旦心の中で区切ってみたい。 |
| 2026-07-22 | The Rules 1・Lesson 7 | 動詞直後のthe・a | 動詞の直後にtheやaが来たら、その後ろにthatが省略されていることが多いと考えるのはどうか。 |
| 2026-07-22 | The Rules 1・Lesson 7 | no game centers or movies with school friends／for me | noはその後の文全体を否定し、前置詞句も否定するのか。ここは動詞がなく文ではないが何なのか。for meは主語的に見えるが、forにそういう文法的意味があるのか。 |
| 2026-07-25 | The Rules 1・Lesson 7 | they／them | theyとかthemは確定させて読む。 |
| 2026-08-19 | ターゲット1900 |  | 動詞のplaceはほぼputの意。giveの過去形はgave。give thought：考慮する。enjoy：享受する。practiceはputする・実行する。roleはplayする・役割を果たす。命令文は主語を省く。somethingは主語になる。〜timeで接続詞になることがある。SVO＋前置詞はOが長いと先に前置詞がくる。people who=those who。much as SV＝どんなに〜しても。sharp rise＝急上昇。processは処理という意味もある。 |
| 2026-08-23 | 駒澤大学 2022 | woodblock prints本文 | ever since：sinceの強意。serious：重大、本気。originally：もともと。althoughは譲歩。large sums of moneyは名詞＋of＋名詞。目的語に関係代名詞が来るときは、惑わされずその後の接続詞をちゃんと主文と繋げるようにする。you can imagineは英語の強調。 |
| 2026-08-23 | 駒澤大学 2022・問題II | Bauhaus本文 | championed：強く支持する／aがつかないlittleは「ない」と言いたい／architect・chemistは人／代名詞の後ろにall・both／as分詞as／direct動詞／manifest／分詞でも元の動詞語法／whose＋その後の語／haveは名詞側に訳をあわせる。 |
| 2026-08-23 | 駒澤大学 2022・問題III | food waste本文 | furtherは数量でさらに追加、respectivelyは対応関係を明示、SVをandで繋ぐ時は直後にディスコースマーカーが来る場合がある、levelは段階、noteは指摘する、justは疑問詞を強調する。 |
| 2026-08-25 | 近畿大学 2024・VII | 自動販売機本文 p.12-13 | vend／for currency／century／devise／to不定詞／string／OCの受動関係／plug／tie／名詞use／get／otherwise／for／penny／figure／practical⇔ideal／to不定詞受動態／there＋助動詞。 |
| 2026-08-25 | 近畿大学 2024・II | ゾウの記憶についての本文 p.5 | fairly／square kilometers／名詞→形容詞→副詞の修飾／in the same way／as is the case with／It's time for〜／when it comes toの限定／hold true。 |
| 2026-08-26 | 専修大学 2024・II | ChatGPT本文 p.8-10 | amid／pretty／state／oblige／inherently／be supposed to do／whatsoever／knowledgeable／well／at all／There has never been／as individuals／on our own／behalf／on our behalf／single／all while／something系の後置修飾／utter／exploit／misuse／mislead／have come to define／comeの過去分詞。 |
| 2026-08-27 | 専修大学 2024・I | 本文 p.1-2 | adversely affect：悪影響／all sorts of：all kind of／anything from A to B：AからBまでなんでも／solitary：ひとり／a great deal of：a large amount of／sleep-deprived：sleep-starved／effectはon／subsequentと名詞で、次の名詞／function動詞：機能する／disastrous：catastrophic／counter動詞：oppose／by〜ing：することによって／jobがterminationで解雇／convince…思い込む／putting (you) in：状況下におく／breakup：破局／you may want to は提案／formulate動詞：明確に表現／thread：一貫した特徴★／conform to：一致／consideringは前置詞になる／not necessarilyは部分否定／perception：perceiveの名詞／ambition：野心or大きな目標／over time：時間をかけて／built up：accumulated。 |
| 2026-08-28 | 早稲田社学 2024・II | 本文 p.3-4 | navigate：cope with／hire：employ／personal：private／also known as：としても知られている／by-product：副産物／look at…調べる／involve：include／durable：lasting★／more than one：多数／couch：ソファー／correlate to：相関する／autism：自閉症★／exchange：やり取り／level the playing field：公平にする／school year：年度／beforeは空間的に〜の前という意味がある／be there to：するためにそこにいる／call back：返す／drawing：絵／ultimately：最終的に／reasonの後はよく関係副詞のwhyが省かれる／land with：行き着く★／give permission：許可を与える／not just：だけでない／outgoing：社交的／unlikeをスラスラ読まない／beで終わるのがあれば、強く「存在」の意を意識する／the most↔the least／come out of…困難から脱する。 |
| 2026-08-29 | 早稲田社学 2024・III |  | butの後にalsoがあれば、ネガ、ポジ変わらない。／whileは 間、だけど、だけれども／「it's something 後ろから説明」に慣れる／コンマの後ろに名詞がもう一度出てきたら、前の名詞を言い換えているかも／help原型で役立つ |
| 2026-09-04 | 専修大学 2023・1 |  | at allは否定の強調／go on doingは〜し続けるだが、go on to doは、その後、というイメージ／even with：たとえもっていても／youの目的格はyou／tricky：難しい／rate動詞：評価する／受動態のbeをgetにすることがある／popularize：普及する／define･･･regard型／according to：よるとor応じて／find OCで そう感じる／draw A from B：get A from B★／notionもofのついてのルール／increasingly：ますます／suggestがsuggest型になっていない時、示唆するという意味／matterの動詞は気づきにくい。／excel at：秀る／discourage A from doing：思いとどまらせる |
| 2026-09-04 | 専修大学 2023・2 |  | riot：暴動★／fight back：反撃する／set A on fire：火をつける／manyは主語になる／credit A with B：もたらしたとされる／完了形の受身はbeen追加されてるだけ／exposeの受身は、触れる／coverage：報道／betweenは3つ以上をつなげれる／prior to A：Aより前 (M)／disown：縁を切る★／exclusively：〜だけ／by doing：することによって(M)／incorporate：取り入れる／object to：反対する(V)／否定のasasはそこまで／left out ：除外／on the ground：現地(M) |
| 2026-09-04 | 日本大学 2024・4 |  | laterが副詞句にあった場合、その後の地点がが現在をさしている／great：巨大／tidal wave：tsunami／neverは、no everを意識する／rather thanの後はそうでないほう |
| 2026-09-04 | 日本大学 2024・5 |  | wasting：wasteの分詞／outer space：宇宙空間／引用符がある場合、物に人に使う動詞を使っている／make use of：を利用している／a few of：のうちの少数／there will be：あの構文の未来 |
| 2026-09-05 | 近畿大学 2025・7 |  | virtually：事実上／renown：有名★／compose：作曲する／understandably：当然ながら★／be drawn to：惹かれる／heard：hearの過去形、pp／learn：学ぶorできるようになる／appreciate：感謝するor理解する／association：団体／aspire：目指す★ |
| 2026-09-05 | 近畿大学 2025・2 |  | coffin：⚰️／fetus：胎児★ |
| 2026-09-05 | 東洋大学 2024・1 |  | ask for：求める／depend on：依存or次第で／just the right：ぴったり／fit into：収まる／translate into：翻訳or結果になる／more of：むしろ／first and foremost：第1に／must be able toはcanを強制する／fewは少ないというよりないほうを言いたい／someoneの後は関係詞きがち |
| 2026-09-05 | 東洋大学 2024・2 |  | game：獲物／a window into：手がかり／paper：論文／intentional：intentの形容詞／rival動詞：匹敵する／take down：仕留める／remain of women：女性の遺体 |
| 2026-09-05 | 京都産業大学 2023・1 |  | shockは驚くだけ／be at it：それをやっている／cities：cityの複数形 |
| 2026-09-05 | 京都産業大学 2023・2 |  | fond：好む★／go both ways：両方当てはまる／come across：run across／note動詞：書き留めるor気づく／howは直後の副詞とセット |
| 2026-09-07 | 東洋大学 2023 |  | it take 人 時間(努力)は、人がよく省略される／determination：決心／realize：気づくor実現する／suggest型は、svocを取るものもある／take A to B：連れていく／push through ：やり抜く／keep up with：遅れずついていく(V) |
| 2026-09-07 | 甲南大学 2021・1 |  | design･･･考案する／lives：lifeの複数／place importance on：重視する(V)／bring up：話を持ち出す(V)／to a significant degree：かなりの程度(M) |
| 2026-09-07 | 甲南大学 2021・2 |  | bakeryは店、breadがパン／beer：🍺／foodがgenerousでたっぷりの食事／thereforeは、この論理でいくとこうなるよね／on showはM／on the move：移動中 |
| 2026-09-07 | 甲南大学 2021・3 |  | 所有格 only 名詞の訳気をつける／dawn：夜明け／to this end：この目的のために、／direction：方向or指示／eclipse：日食★ |
| 2026-09-08 | 早稲田社学 2024・5 |  | come away feeling：離れて、思う。／fromかきかおす／be common in：そこで一般的／contrive：不自然★／this sort：この種の／make a choice：きめる(V)／reasonable：合理的な／ranging：rangeの分詞／what should be：であるべきであるもの／consequential：重要な／payの受身は受け取る／findings：研究結果／verify：正しいか確認する★／conceive：思いつく★／overlap：一部重なる★／devastate：破壊する★／valid：妥当or有効 |
| 2026-09-10 | 早稲田社学 2024・4 |  | yield：屈するor産出する／halveは動詞で半分／on the back of：を受けて、／in some way：どうにかして／together：一緒にor合わせて／deplete：枯渇させる★／evident：明らか／causeはsvoc！／merely見たらnot onlyのやつじゃないか？／be slow to do：なかなかしない(V)／A over Bは、Aの方が上、イイネって感じ／replaceはwith／sort out：整理or解決する／〜化と訳すのは、イゼーション、アイゼーション／make：状態にする |
| 2026-09-13 | 日本大学 2024・8 |  | people inは、後ろから人の説明／take from：取る／no one but：だけ |
| 2026-09-13 | 専修大学 2024・3 |  | thoughは、これから2文使われますよを意識／have trouble ：苦労する／control for ：条件を取り除いたり／get A out of B：Bから取り出されるA／make more of：もっと活用する |
| 2026-09-13 | 甲南大学 2023・1 |  | proposal：提案or計画案／serve as：として機能する／with the intent of：を目的として(前)／contractで契約、人で請負業者／pit：くぼみ★／seek to：しようと務める／condemn：非難する／in favor of：賛成して／rule･･･判決をする／to please：喜ばせる |
| 2026-09-26 | 明治大学情 2024・2 |  | put away ：とっておく／conceive：考え／goの後に動詞が並ぶことがある／attraction：魅力／longing：切望／how単独：どのように／how形容詞副詞：どれくらい／疑問詞to doは、「べき」と訳す／some surely have：そうした人もいる／beside oneself：取り乱して／put through：経験させる |
| 2026-09-26 | 明治大学情 2024・1 |  | be fond of：好んでいる／seeのsvocは、ingを取る知覚動詞orみなす／nowhereはnowじゃないです。／動詞になるのはacrossじゃなくて、cross／fewは数えられるものが、／a handful ofはひと握り！100ではないw／effectがstrongerなら、より影響をうける／occurは自動詞／not always result in：常にそういう結果にならなくても／adverse：形容詞で、不利な／it depends：場合による／work for：上手くいく／alone together：2人だけ／deserve：値する |
| 2026-09-27 | 明治大学政 |  | cities：cityの複数形!!!!／set out：始める／seemは現在形です。svcもよくとる。／be skilled at：be good at／show up：姿を表す／just world：公平な世界／関代はthat'sにしていい／futile：無駄な★／20-somethings：20代の人々／a third：3分の1.／arguably：おそらくー／crave：強く欲する／engineer動詞：設計する／meanwhile：一方で／beyond：加えて |
| 2026-09-15 | ポラリス1・1 |  | accompany：伴って、／hold up：上げるor遅らせる／bruise：あざ★／It is common for A：よくあることだ。／visually impaired：視覚障害／pose：引き起こす／stairways：階段／tactile paving ：点字ブロック |
| 2026-09-15 | ポラリス1・2 |  | work (her) way through：苦労して進む／winding：曲がりくねった／top動詞：上回る／compete with：競合する／a day ofなんちゃらで、なんちゃらする日／spur：促す★ |
| 2026-09-15 | ポラリス1・3 |  | observeはSVOCをとる／regulate：規制or調整／miss out on：見逃す／in an effort to：しようとして／loud：音が大／a scene of：という感じ／I'm just boringは、ただつまらない人です。 |
| 2026-10-03 | 明治大学政 2020・2 |  | as long as：する限り、、、／far from：するどころか／be tried：裁判にかけられる／tell A off：叱る／expect：予測するor期待する／attain：達成する／driveはenable型で、追いやる／take away：取り除く／inward：内側／let’s face it：現実を認めよう／svocはnot to doにできる。／separate A from B：区別する／peril：危険★／spot動：見つける／do little to do：役立たない／institution：施設or制度／positive：事実に基づく |
| 2026-10-03 | 明治大学政 2020・1 |  | spectacle：見世物／demand：必要とする／represent：表すor代表する／stage動：上演する／serve･･･役に立つ／facilitate：用意にする／offは供給源を意味／deny A B：与えない。take型。 |
| 2026-10-10 |  |  | decisively：断固として／commitment：献身する／the Constitution：憲法／nature：自然or本質／the object of：の対象／otherは、そのほかだからどんなのか考える／flies：ハエ／afterwardsは、副詞でその後／rate動詞：評価する／deliberate：意図的／deliver：もたらす／what if：どうなる？／measure：措置／what S be like ＝ Sがどのようなものか／find one's way into：入り込む／response：対策／impair：損なう／coinが硬貨、billが紙幣／appeal：訴えor魅力／ba backed up：裏付けられている／thenはその時〜〜〜〜〜ー〜ー〜／get on with：進める／dying：死にかけている／it is…who：強調構文です／all of which：その全て／into↔out ofでどちらも前置詞／self-fulfilling：思い込みが本当にそうなってしまう意／trick：だます／too to：しすぎてできない／訳しにくいsomething：もの／in response：それを受け／third party：第三者／stock prices：株価／A, and never B ： Aであるべきで、決してBではない／drive：引き起こす／while alsoはもう一個の特徴が追加／demographic：人口統計／competency：能力／mismatch：不一致。それだけの意味／coupled with：結びついて／exert：力を及ぼす／capitalize on：上手く利用する／consequence：結果or影響／headcount：従業員数／sweeping：広範囲に／anticipate：予測する／soften：柔らかく／meantの根底は意図／基準のby！／whatは先行詞なしで関代つかえる。／shipは名詞化／dispose to したい気分 dispose of 捨てる／totally：完全に／adequacy：妥当／peer：名詞 同年代 or 動詞 じっとみる／useのsvocは 〜するためにOを使う／provide型はwithだけではなく、物と人を入れ替えてtoやforでも使われる |
| 2026-10-18 |  |  | after all ：結局のところor何しろ／by all means：ぜひ(なんとしてでも)／for all he knows：彼の知る限り／once and for all：これを最後に／dispose OC：したくさせる／either A or B：AかBのどちらか／worth(前置詞)は仮主語の後にingをおく。／which is why〜：これが理由です▶︎明示／肯定文▶︎too 否定文▶︎either／don't you think：じゃない？／rule out：除外する／most ofのあとは特定出来るもののみ／over the phone：電話で／喉まで出ているはタンをつかう。／alcohol free：飲酒禁止／the play：劇／improve：向上「させる」／since始点、untilは終点／almostは副詞なので、単体で修飾しない／present：現在or存在or出席or発表／catalyst：きっかけ★／Sの関係代名詞はVを超えて置く場合がある★／originate in： 起源を持つ／third most important：3番目に大事／speculate：推測する／proveの名詞はproof／room for 〜：余地／plant：工場／far fromは、物理的、概念的にとにかく離れている／far from：決してではないorどころか／of+抽象名詞で、形容詞／age-old：昔から存在する／authority：当局or権限／fromとtoが近くにあったら、あの熟語／victimは生死を問わない／relief operation：救援活動／in turn：順番orそれがまた／as isは関係代名詞とおなじ／just as：同じように |
| 2026-10-30 |  |  | helpless：無力／hardlyは完全否定語／be sick of：うんざり／whyとshouldで、疑問を強調／tearｰtoreｰtorn／biteｰbitｰbitten／deliver：配達する／perceive：気づく ／in favor of：賛成／as long as：：：成り立っている間／as far as：：：及ぶ範囲では／get run over by：轢かれる／be expected：期待されているor求められている／expense：費用／convey a message／Secretary：秘書／creditA to B：A「は」Bのおかげ／attribute A to B ：A「は」Bのおかげ／ityは、名詞を作る。／no matter+疑問詞：に関係なく／drow a conclusion：結論を出す／have nothing to do with ～：～とは何の関係もない／肯定文はsome／season動詞：味付けする／touch動：触れるor感動させる ／celebrities：有名人／take place：起こる／that way：そのような／understateのstateは述べる／drop：落とすorやめる／It's not as if：別に、、／notifyはtell型／take↔get off／stress：主張する／what it would take to do：するために何が必要か／take advantage of：利用する(形動)／prior to ing：する前／so〜that：so〜as to／employ：雇うor使用する／concern：心配するor関連する／at the moment：現時点では／on security grounds：安全上の理由／phaseout：段階的廃止／so far：これまでのところ／in line with：一致して／produce：提示する／produceの後ろは結果／a dearth of：不足 ★／application：応用or申請／out of reach：手の届かない／renewable：再生可能エネ／meet：満たす／around：about／combined：合計して／revolve around ：を中心として★／file動：正式な書類を提出する感じ。訴訟等／add to：：：追加／譲歩からの、それでもなおの、still／semiconductors：半導体／mean that〜：〜を意味する／mostの反対はleast／drive：cause／come to do：するようになる。／acknowledge：認めるor認識する／beneath：under／caution動：警告する／not least：特に／The reality is that：実際のところ／asylum：亡命／mid接辞：中間or〜中／initiative：取り組み／seek~sought~sought／criminalize：違法とする／deport：国外追放する／at the end of the day：結局のところ |

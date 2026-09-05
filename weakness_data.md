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
| 2026-08-28 | 早稲田大学 2024・II | 本文 p.3-4 | navigate：cope with／hire：employ／personal：private／also known as：としても知られている／by-product：副産物／look at…調べる／involve：include／durable：lasting★／more than one：多数／couch：ソファー／correlate to：相関する／autism：自閉症★／exchange：やり取り／level the playing field：公平にする／school year：年度／beforeは空間的に〜の前という意味がある／be there to：するためにそこにいる／call back：返す／drawing：絵／ultimately：最終的に／reasonの後はよく関係副詞のwhyが省かれる／land with：行き着く★／give permission：許可を与える／not just：だけでない／outgoing：社交的／unlikeをスラスラ読まない／beで終わるのがあれば、強く「存在」の意を意識する／the most↔the least／come out of…困難から脱する。 |
| 2026-08-29 | 早稲田大学 2024・III |  | butの後にalsoがあれば、ネガ、ポジ変わらない。／whileは 間、だけど、だけれども／「it's something 後ろから説明」に慣れる／コンマの後ろに名詞がもう一度出てきたら、前の名詞を言い換えているかも／help原型で役立つ |
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

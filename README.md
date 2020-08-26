# cookpad-internship-2020-summer-pbl
課題：コロナで飲み屋で飲み会ができない

PBLのテーマ：一人暮らしをしている人の料理が楽しみになる

ポイント：一人暮らし、料理？


## 価値仮説

~~題名：Zoom飲み会で気軽に簡単料理を持ち込める価値仮説~~

~~ユーザー：Zoom飲み会をする普段料理をしない一人暮らしの人~~

~~欲求：美味しい料理を食べながら飲み会がしたい~~

~~課題：コロナ下で飲み屋にいくことに気後れする、料理がめんどくさい~~

~~製品の特徴：Zoomurl送信時にいくつかの簡単料理レシピを付け加え、SNSで参加者に共有する~~

**フィードバック後**

題名：一人暮らしの人同士がリアルタイム×オンラインで料理をシェアできる空間をつくる価値仮説

ユーザー：サークルや研究室、新社会人の新歓、飲み会の企画者（一人暮らしが多いコミュニティー）

欲求：コロナ下で大勢では飲み会にはいけないが寂しいのでオンラインでもいいから飲み会がしたい

課題：料理をするのは面倒臭い。自分しか食べないし、洗い物、買い物、ゴミ捨てはめんどう

製品の特徴：Zoomurl送信時にいくつかの簡単料理レシピを付け加え、SNSで参加者に共有する

ねらい：**一人で作って食べる料理は美味しいが、労力に見合わないので作らない。**
料理は家族や飲み会のようにシェアして楽しめるから良いんだなあ。  
->料理を食べる体験をシェアすることで楽しく料理ができる  
->簡単料理を覚える+慣れれば、次に一人でつくるときにも作る気になれる。（レシピを検索する、見るのも結構面倒だし）

**具体的なターゲット：**
一人暮らしをしていて、マジで料理をしない人、惣菜、弁当、UberEats、外食でほとんど済ませている人。

## 価値検証はどうやってやる？
- 実際に使ってもらわないと...
- **実装する前に検証する**？
- 作ってもらう？　->1分簡単レシピをみんなに共有する?
- 人暮らしをしている人(自分意外みんな)


## 価値検証（質問リスト）
- **台所で火を使った料理をする頻度について（最後に火をつかったのはいつ？）**
    - 昨日、二週間前
- **一人暮らしをしてからおつまみを作ったことはありますか？**
    - どんなおつまみ？
        - ピーマン炒め+ツナ缶、🍟、作らない
- **Zoomオンライン飲み会の頻度**
    - 月一くらい、今は飲み屋にいく
- **オンライン飲み会は何か食べながらやる？食べることに気後れする？**
    - 火を使うことはなさそう、スナックとか惣菜を買って食べるくらい
- **もし一分でなにかつくれるとしたら？作りたい（例↓）？**
    - [焼き鳥でつくるチーズダッカルビ　レンチン](https://entabe.jp/26419/yakitori-can-cheese-dak-galbi-easy-recipe)
    - [サバ缶一分おつまみ](https://cookpad.com/recipe/5465688)
    - [サバ缶キムチ和え](http://ainoouchigohan.blog.jp/archives/1065020112.html)
        - 食器洗うのがめんどくさい、缶詰があればつくるかな



## なぜこのサービス？
- 自分が飲み会に参加する時、1分程度で缶詰と卵をフライパンで和えたらとてもよかった。
- 一人暮らしだと料理に慣れてないので、おつまみのレシピが思いつかない
- 定番おつまみレシピを持ってる人は作りそう
- コロナが蔓延した時に

## 懸念
- 飲み会を楽しくするために料理をする？(テーマと矛盾してないか)
-> 簡単に作れる料理でも美味しくできることをしれる
-> 料理が楽しみになる
- 一人暮らしだと買い物からはじめないといけないので、結構料理のハードルが高い...
- コンビニにいくついでに買ってこれるような食材だといいけど
- Zoomをわざわざ繋いで飲み会することも少ないのか...
- Line通話はどう？
- 研究室飲み、サークル飲み、大勢での飲みはできないか?

## 作るページ(webサービス)：
1. Zoomの招待url(Zoomミーティング作成時にできる招待用text)投稿画面(メインのページ) 
    -
    - 簡単レシピの推薦の仕方をoptionで選ぶ?
        - いやいらないかな
    - 結構ランダムでレシピを3個くらい紐づける
        
2. Zoom招待ページ(参加者への共有用)
    -
    - 調整さんのようにURLをhash値にして共有できるようにする
    - line,insta,twitterへの投稿ボタンをつける
    - レシピごとにチェックボックスで作ったかどうかのPOSTができるようにする
    ->よく作成されるレシピはよく推薦されるようにする
    
    
3. よく作られているレシピ一覧ページ(ついで)
    - 
    - よく作られるレシピはソートで並び替えをする
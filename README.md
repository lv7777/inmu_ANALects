﻿####現在、田所工事中・・・####

---

###inmu_ANALects by kurosuke18 \<<nonke_homo@outlook.com>\>###

---

##inmu_ANALectsって何だよ（疑問）##

Microsoft IME用の淫夢語録辞書ファイル（テキスト形式）です☆

簡単に語録を入力出来るようになります☆（辞書への登録が簡単だとは言ってない）

##使い方を教えるんだよ、あくしろよ##

**1. cloneして、どうぞ**

`git clone https://github.com/kurosuke18/inmu_ANALects.git`

**2. ユーザー辞書に登録、しよう！**

1. タスクバーにあるIMEのアイコンを右クリック
2. ユーザー辞書ツールを選択
3. ツール→テキストファイルからの登録を選択
4. cloneしたディレクトリから、登録したい語録が登録されているテキストを選択

**3. 終わり！閉廷！**

他の人に迷惑が掛からない程度に使ってくれよな～頼むよ～

ちなみにニコニコ動画でコメントするなら、システム辞書にまとめる必要ありますあります（経験済み）

---

##ちょっと待って！語録がほとんど入ってないやん！どうしてくれんのこれ？##

とりあえず開発中なんだよね、それ一番言われてるから。悲しいなぁ...

早めに咥え入れて欲しい語録があれば、イシュー・・・にでも書いてホラホラ

---

##参考 語録などを追加する際の規則##

**1. ブランチについて**

ブランチの運用モデルは[こ↑こ↓][site]をパクｒ...参考にしたナリよ（すっとぼけ）
[site]:http://www.backlog.jp/git-guide/stepup/stepup1_5.html
以下はinmu_ANALectsで利用する各ブランチの説明ナリ。

- リモート上のブランチ
	- master : 安定版。リリース番号（バージョン）をタグ付けして管理するナリ。
	- develop : 開発（意味深）版。基本的に、作業はこのブランチで行うナリ。
- ローカル上のブランチ
	- feature（名称は適当） : developから分岐して、新しい語録ファイルなどを追加する際に作るブランチ。完成したらdevelopに取り込むナリ。
	- release-＜バージョン＞ : 仕様がある程度固まったら、リリースに向けてdevelopから分岐するブランチ。細かい修正などが終わり次第、masterとdevelopにそれぞれ取り込むナリ。
	- hotfix-＜バージョン＞ : masterから分岐して、バグなどの修正を行うブランチ。修正が終わったらmasterとdevelopにそれぞれ取り込むナリ。

**2. コミットメッセージの規則**

コミットメッセージはこのように書いているナリよ。ナニをしたのかが分かりやすい...分かりやすくない？

`1行目：[＜操作＞] ＜ブランチ＞`

`2行目：変更点を説明`

inmu_ANALectsディレクトリ（このファイルと同じ階層）を ' \ '（ルートディレクトリ）として、変更したディレクトリ又はファイル名まで記述しているナリ。

多分ログを見たほうが早いと思うんですけど（名推理）

※（書き方がいまいち安定して）ないです。

また、操作は以下の通りナリ。

- add : 語録ファイルを追加
- delete : ディレクトリ以下全て、又は個別に語録ファイルを削除
- modify : ファイルの中身を変更（追加、又は削除）
- rename : ディレクトリ、語録ファイルの名称を変更
- fix : バグ修正、こマ？かい修正

---

##今後の予定##

- さらに語録を追加していきますよ、イクイク・・・（全部追加できるとは言ってない）
	- 淫夢（COAT、Acceed他）
	- レスリング
	- クッキー☆
	- 大物youtuber
	- 一般男性シリーズ

- このREADMEを書き終える（淫夢要素が足りない...足りなくない？）

- ウィキ！の活用

######本当はさっさと語録を登録したいけど、（時間が）ないです...######

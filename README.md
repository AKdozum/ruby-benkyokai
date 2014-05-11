# Ruby勉強会 - 概要

他のLLは書いたことあるけど、Rubyは初心者という人向けの社内勉強会です。

レポジトリ: https://github.dena.jp/nakatani-sho/ruby-benkyokai

毎回の予告などもこのレポジトリでしていくつもりです。
特にゲスト発表なさる方には、コミット権もどんどん与えていくので、遠慮なくお申し付けください。

主に中谷@Rubyド素人が30~60min喋る感じのイベントになります。
少なくとも最初のうちは、『パーフェクトRuby』に沿った内容を発表していくつもりです。

皆様の発表もお待ちしてますので、やりたい方はご連絡をお願いします。
また、周りに興味ありそうな方がいれば、ご自由にこの会のカレンダーに追加してください。


# 発表ポリシー

中谷の発表ポリシーです。
ただのつまらない言語紹介にしないために心掛けることです。

## 他言語との比較

- Rubyの言語仕様や機能を、PerlやPythonなどの他言語のものと(効果的ならば)比較します
  - 「この機能はPythonのこれだよね。Pythonのほうが綺麗に書けるね」
  - 「そんなことねーよ、お前がRubyらしい書き方し切れてないだけだろ」
  - みたいなケンカができると最高

## 中級者には学びを、上級者には納得を

- 1回の発表につき少なくとも1つは、Rubyの中級者にとっては「知らなかった」と思わせ、
  上級者に対しては「ほう、抑えてあるねぇ」と思わせようと思います

## 網羅性は重視 **しない**

- 本に書いてあること全てを発表することにこだわりません
- Rubyで実践的にプログラムを組めるのを最終的なゴールにし、ゴールが達成できた後に
  「どうせこういう機能もあるよね」で調べれば気づけるようなものは意図的に無視することがあります。
- 例: `while`を紹介した後に、わざわざ`until`を紹介するか


# 各回のスケジュール

## 第1回(2014/05/12)

- Rubyでサンプルコード動かすための最低限とOOP(中谷)

- Rubyでよく使われてるイディオムについて紹介しようと思ってます。(村上, 15min)


## 第2回(2014/05/19)

- クラスその2、モジュール、インスタンス(中谷)

- procとblockについて話します(加藤龍)


# その他のネタ帳

「このネタなら俺だろ」っていうのがあれば、ゲスト発表でネタを使っていただいても構いません。

- 制御構造
- メソッド
- モジュール
- TDD, BDD
- お世話になる組み込み型
- メタプログラミング
- デバッグ、パフォーマンス計測
- Rubyで実装! ooxx


# ゲスト発表

毎回1人以内のゲスト発表を受け付けてます。スーパーウェルカムです。

やりたい人は中谷までご連絡ください。調整しましょう。

ゲスト発表に使用する資料は、このレポジトリにpull-reqを投げてください。
その際、下記のファイル・ディレクトリ構成はゆるやかに守っていただけると助かります。


# ファイル・ディレクトリ構成

- `XX/`
  - 第XX回の資料を入れるディレクトリ
- `XX/SubjectToday-yourname.(md|rst|org|txt|...)`
  - 担当者yournameのSubjectTodayに関する資料。フォーマットは**聴衆にやさしければ**何でも良いです。
- `XX/src/`
  - 第XX回で使用するサンプルコードを入れるディレクトリ(任意)。
    ゲスト発表者との名前の衝突に注意。衝突したらpull-reqをmergeする時に何とかします。

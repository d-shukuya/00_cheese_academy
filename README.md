# 00_cheese_academy
「00 チーズアカデミー」の課題用リポジトリ

# まずは忠実チーズアカデミー

## DEMO

- なし

## 紹介と使い方

- 架空のアカデミー「チーズアカデミー東京」のホームページの HTML と CSS

- 一式ローカルに配置し、index.html をブラウザで開けば閲覧可能

## 工夫した点

- 表組みっぽいところ（アクセスの文字部分やコンタクトのフォーム部分など）を div で組んでみたり、テーブルで組んでみたり、 gridで組んでみたりした
- アバウト部分の画像を無限ループのスライダーにしてみた
- ホバーで意図した変化を出すために、構造を作り変えたりした

## 苦戦した点

- 行き当たりばったりでソリューションを選択してコーディングしたため、コードの最初と最後で書き方が変わってしまった。
  次はコードの統一性を意識して作りたい。
- 特に下記あたりをどう統一するのがスマートなのかを考えてみる。
  - マージンの取り方
  - 表の作り方
  - CSSを書く単位（共通化や再利用などを想定した）
  - 中央寄せなどの配置の方法
  - display: flax; はもういっそ body にあててしまったら良いのでは？

## 参考にした web サイトなど

- https://flexboxfroggy.com/#ja
  - display: flex; の勉強に良かった
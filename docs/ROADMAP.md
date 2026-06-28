# Bao la Kiswahili 日本語完全ガイド プロジェクトロードマップ

> Repository: **bao-la-kiswahili-ja**
>
> 日本語で最も正確かつ読みやすい **Bao la Kiswahili（ザンジバル版）** のルールブック・リファレンス・教材をオープンソースで制作する。

---

# プロジェクト概要

本プロジェクトは、Bao la Kiswahili の正式ルールを学術資料・競技ルール・一次資料をもとに整理し、日本語話者が安心して学べる包括的なガイドを作成することを目的とする。

目標は単なる翻訳ではない。

* 初心者向け教材
* 正式ルールブック
* リファレンス
* 用語辞典
* 戦術入門

これらを一体化した「日本語版 Bao la Kiswahili 完全ガイド」を制作する。

---

# プロジェクト方針

本プロジェクトでは次の4点を重視する。

* 正確性
* 可読性
* 保守性
* 再利用性

また、

* GitHub
* PDF
* Webサイト
* EPUB

への展開を前提としてMarkdownで執筆する。

---

# リポジトリ

```
Repository

bao-la-kiswahili-ja
```

Description

> Japanese Complete Guide to Bao la Kiswahili

---

# ディレクトリ構成

```text
bao-la-kiswahili-ja/

├── README.md
├── LICENSE
├── CONTRIBUTING.md
│
├── docs/
│   ├── ROADMAP.md          ← この文書
│   ├── STYLE_GUIDE.md
│   ├── REFERENCES.md
│   ├── REVIEW.md
│   ├── CHANGELOG.md
│   ├── TODO.md
│   ├── figures/
│   └── drafts/
│
├── guide/
│   ├── 00-preface.md
│   ├── 01-introduction.md
│   ├── 02-board.md
│   ├── 03-setup.md
│   ├── 04-glossary.md
│   ├── 05-namua.md
│   ├── 06-mtaji.md
│   ├── 07-capture.md
│   ├── 08-relay-sowing.md
│   ├── 09-nyumba.md
│   ├── 10-endgame.md
│   ├── 11-kujifunza.md
│   ├── 12-strategy.md
│   └── 13-faq.md
│
└── assets/
    └── images/
```

---

# 各ディレクトリの役割

## docs/

プロジェクト運営資料。

* 執筆計画
* 表記ルール
* 参考文献
* 校正履歴
* TODO

などを管理する。

---

## guide/

完成するルールブック本文。

最終的にはこのディレクトリだけで一冊の本になる構成を目指す。

---

## assets/

図版・イラスト・アイコンなどを格納する。

---

# ファイル一覧

## docs/

| ファイル           | 内容       |
| -------------- | -------- |
| ROADMAP.md     | 全体計画     |
| STYLE_GUIDE.md | 表記・用語ルール |
| REFERENCES.md  | 参考文献一覧   |
| REVIEW.md      | レビュー履歴   |
| CHANGELOG.md   | 更新履歴     |
| TODO.md        | 未解決事項    |

---

## guide/

| ファイル               | 内容     |
| ------------------ | ------ |
| 00-preface.md      | はじめに   |
| 01-introduction.md | Baoとは  |
| 02-board.md        | ボード    |
| 03-setup.md        | 初期配置   |
| 04-glossary.md     | 基本用語   |
| 05-namua.md        | namua  |
| 06-mtaji.md        | mtaji  |
| 07-capture.md      | 捕獲     |
| 08-relay-sowing.md | 連続蒔き   |
| 09-nyumba.md       | nyumba |
| 10-endgame.md      | 勝敗     |
| 11-kujifunza.md    | 簡略版    |
| 12-strategy.md     | 戦術     |
| 13-faq.md          | FAQ    |

---

# 執筆ロードマップ

## Phase 0

着手前整理

### 目的

* 調査・執筆・レビューの記録方法を決める
* 未確認事項と確定事項を分離できる作業環境を整える
* 各Phaseの着手条件と完了条件を共有する

成果物

* STYLE_GUIDE.md
* REFERENCES.md
* REVIEW.md
* CHANGELOG.md
* TODO.md
* 調査メモ、図版設計、本文原稿の配置先

### 完了条件

* 運営文書の雛形がそろっている
* Phase 1の調査項目と記録方法がTODOに明記されている
* 出典、確認状態、地域差を区別して記録できる

**状態: 完了**

## Phase 1

資料調査

### 目的

* 正式ルールの確認
* 用語整理
* 地域差の整理

成果物

* REFERENCES.md
* 用語一覧

### 完了条件

* ザンジバル版の基準資料候補が列挙されている
* 採用する資料の書誌情報と確認箇所が記録されている
* 主要用語の原語、暫定的な日本語説明、根拠が整理されている
* 資料間の不一致と未解決事項がTODOまたは調査メモに残されている

**状態: 進行中**

---

## Phase 2

構成設計

章構成を決定する。

成果物

* guide ディレクトリ
* 各章の雛形

---

## Phase 3

図版設計

本文を書く前に図を制作する。

対象

* ボード
* marker
* capture
* nyumba
* relay sowing
* kichwa
* kimbi

---

## Phase 4

本文執筆

各章を順番に執筆する。

各章は

1. 初心者向け説明
2. 正式ルール
3. 具体例
4. 注意点
5. 地域差

で統一する。

---

## Phase 5

実例集

局面図を多数追加する。

目標

30〜50例。

---

## Phase 6

用語辞典

すべての専門用語を整理する。

例

* nyumba
* namua
* mtaji
* takata
* marker
* kichwa
* kimbi
* taxation
* relay sowing

---

## Phase 7

FAQ

初心者が疑問に思う内容を体系化する。

目標

50問程度。

---

## Phase 8

戦術入門

* 初級
* 中級
* 上級

まで執筆する。

---

## Phase 9

校正

確認項目

* 誤字
* 表記揺れ
* 用語統一
* 図番号
* 相互参照

---

## Phase 10

レビュー

可能であれば

* Bao競技者
* 学術研究者
* 英語資料との照合

を実施する。

---

# 品質目標

完成版は以下を満たすことを目標とする。

* 正式ルールと矛盾しない
* 初心者でも読める
* 図だけでも理解できる
* 用語が統一されている
* 地域差を明記している
* 出典が明確である
* 継続的な改訂が可能である

---

# 将来展開

本プロジェクトは以下への展開を想定する。

* GitHub Pages
* PDF
* EPUB
* 印刷版
* 英語版
* スワヒリ語版
* 対話型ルールブック
* Bao学習アプリ

---

# 最終目標

Bao la Kiswahili を日本語で正確に学べる環境を整備し、初心者から競技プレイヤーまで利用できる「決定版ガイド」をオープンソースとして公開・継続的に発展させる。

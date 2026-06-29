# 参考文献

Bao la Kiswahili（ザンジバル版）のルール、用語、地域差を検証するための資料を記録する。

## 採用方針

資料は、おおむね次の順で優先する。

1. 競技団体などが公表する規則
2. 競技者・伝承者への聞き取りを記録した一次資料
3. 査読済み論文、学術書、博物館等の資料
4. 出典を明記した専門的な解説
5. その他のWeb情報

資料の新しさだけで優先順位を決めず、対象地域、採録方法、版、記述の具体性を確認する。

## 記録項目

各資料には、可能な範囲で次を記録する。

- 著者・編者
- タイトル
- 出版者または掲載元
- 出版年・更新日
- URL、DOI、ISBN等
- Web資料の確認日
- 対象地域・ルールの系統
- 本プロジェクトで確認した項目
- 資料の位置づけと注意点

## 参考文献一覧

### R-001: de Voogt (1995)

- 著者: Alex de Voogt
- タイトル: *Limits of the Mind: Towards a Characterisation of Bao Mastership*
- 出版者: CNWS Publications, Leiden
- 出版年: 1995
- ISBN: 90-73782-50-3
- URL: https://www.researchgate.net/publication/280132772_Limits_of_the_Mind_towards_a_characterisation_of_Bao_mastership
- 確認日: 2026-06-28
- 対象: ザンジバルの Bao と Bao 名人
- 確認項目: 書誌情報、ザンジバルの名人に基づく調査であること、ルール記述を含むこと
- 位置づけ: 本プロジェクトの基準資料候補。著者が公開した全文への導線は確認できたが、ルール本文はまだ通読していない。

### R-002: Donkers (2003)

- 著者: H. H. L. M. Donkers
- タイトル: *Nosce Hostem: Searching with Opponent Models*
- 種別: Maastricht University 博士論文
- 出版者: Universitaire Pers Maastricht
- 出版年: 2003
- ISBN: 90-5278-390-X
- DOI: https://doi.org/10.26481/dis.20031205hd
- PDF: https://project.dke.maastrichtuniversity.nl/games/files/phd/Donkers_thesis.pdf
- 確認日: 2026-06-28
- 対象: Appendix C, “Zanzibar Bao Rules for the Computer”, pp. 163–168
- 確認項目: ボード、初期配置、namua、mtaji、捕獲、endelea、nyumba、takasa、takasia、終局、棋譜表記
- 位置づけ: R-001をもとに計算機向けに形式化した比較資料。無限手の扱いなど、競技規則そのものではない追加規則を含むため、R-001より優先しない。

### R-003: de Voogt (2000–2001)

- 著者: Alex de Voogt
- タイトル: “Strategy in Bao: An Introduction” および “Strategy in Bao: Notation and the House”
- 掲載誌: *Abstract Games*, Issue 4（Winter 2000）, pp. 21–22、およびIssue 5（Spring 2001）, pp. 22–23
- Issue 4: https://www.abstractgames.org/uploads/1/1/6/4/116462923/abstract_games_issue_4.pdf
- Issue 5: https://www.abstractgames.org/uploads/1/1/6/4/116462923/abstract_games_issue_5.pdf
- 確認日: 2026-06-28
- 対象: Baoの基本ルール、nyumba、棋譜、基本手
- 位置づけ: R-001の著者自身による入門的解説。Issue 5にIssue 4の記述を訂正する箇所があるため、単独号だけを根拠にしない。

### R-004: Kronenburg, Donkers and de Voogt (2006)

- 著者: Tom Kronenburg, H. H. L. M. Donkers, Alex J. de Voogt
- タイトル: “Never-Ending Moves in Bao”
- 掲載誌: *ICGA Journal*, 29(2)
- 出版年: 2006
- DOI: https://doi.org/10.3233/ICG-2006-29204
- 確認日: 2026-06-28
- 対象: 終わらない連続蒔き
- 位置づけ: 特殊局面の検証資料。通常のルール全体を定める資料としては使用しない。

### R-005: BaoルールのWeb上の統合解説

- タイトル: “Bao la Kiswahili”
- 掲載元: Mancala World Wiki
- URL: https://mancala.fandom.com/wiki/Bao_la_Kiswahili
- 確認日: 2026-06-28
- 確認項目: `takata`、`marker`、`taxation` に相当する説明、nyumbaの地域差
- 位置づけ: 出典階層の低い補助資料。R-001〜R-004にない英語圏の用語用例を確認するためだけに使い、正式ルールの根拠にはしない。

### R-006: de Voogt (2001), “The Beauty Is in Complexity”

- 著者: Alex de Voogt
- タイトル: “Strategy in Bao: The Beauty Is in Complexity”
- 掲載誌: *Abstract Games*, Issue 7（Autumn 2001）, pp. 24–25
- URL: https://www.abstractgames.org/uploads/1/1/6/4/116462923/abstract_games_issue_7.pdf
- 確認日: 2026-06-29
- 対象: 捕獲手とtakasaの候補探索、初心者にとっての選択肢の多さ、namua・mtajiのtakasa規則
- 位置づけ: R-003に続く同著者の入門記事。戦術上の一般則や定跡を網羅する資料ではなく、候補探索と学習上の注意を確認するために用いる。

## 基準資料の暫定順位

1. R-001をザンジバル版の中心資料候補とする。
2. R-002で規則の条件分岐、用語、実装可能性を照合する。
3. R-003で初心者向け説明とR-001以後の訂正を確認する。
4. R-004は終わらない手に関する論点だけに用いる。
5. R-006で候補手の探索と初心者向けの戦術学習を補う。
6. R-005は用語用例の確認に限って参照する。

この順位は暫定である。ザンジバルの競技団体が公表した規則、または現地競技者による新しい一次資料が見つかった場合は再評価する。

## Phase 1で確認できなかった資料

- R-001は著者公開の全文配布ページまで確認したが、2026-06-28時点で配布元のアクセス制限によりルール本文を取得・通読できなかった。
- ザンジバルの競技団体または現地競技者が現在公開している規則本文は、2026-06-28の検索では確認できなかった。
- Chama cha Baoやザンジバルの大会・団体の存在に触れる二次資料はあるが、規則本文と発行主体を検証できないため基準資料には加えていない。

これらは資料不存在の断定ではない。入手できた時点で追加調査し、R-002・R-003に依存する暫定判断を再評価する。

## 資料間の差異

差異を発見した場合は結論だけに統合せず、`docs/drafts/` の比較メモと `docs/TODO.md` に記録する。

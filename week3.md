# week3

## Classification(分類)

### ロジスティック回帰アルゴリズム
* 分類問題はeメールがスパムかそうじゃないか、腫瘍が良性か悪性か、など
* yが0か1の2値で表される
* 0のものをネガティブクラス、1のものをポジティブクラス、という
* Sigmoid Function または Logistic Functionというアルゴリズム(呼び方が違うだけでどちらも同じもの)を使うと0と1の間の値を返すので、これを使う

![hypothesis_representation](img/hypothesis_representation_1.png)

* こんな感じになる
* P(y=1|x;θ)=0.7 みたいな書き方は「yが1である確率は70%」と読む

### Decision Boundary(決定境界)
* y=1とy=0になる境界線のこと
* ↑の図だと0.5




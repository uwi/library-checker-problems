問題文
=========

長さ $N$ の文字列 $S$ が与えられます。以下の条件を満たす配列 $a_0, a_1, ..., a_{N - 1}$ を出力してください。

- $a_i$ は、$S$ と $S.substr(i)$ の LCP(longest common prefix)


制約
=========

- $1 \leq N \leq 500,000$
- $S$ は英小文字のみからなる

入力
=========

~~~
$S$
~~~

出力
=========

~~~
$a_0$ $a_1$ $a_2$ ... $a_N$
~~~

サンプル
=========

{{example example_00}}

{{example example_01}}

{{example example_02}}

{{example example_03}}

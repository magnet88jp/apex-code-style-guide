# 垂直の空白

単一の空行は、以下の場合で使われます。

1. クラスの連続するメンバ（あるいは初期化子）の間。フィールド、コンストラクタ、メソッド、ネストしたクラス、static初期化子、インスタンス初期化子。
  * 例外 ：2個の連続するフィールド（その間にコードがないもの）間での空行は任意である。そのような空行はフィールドの 論理的なグループ分け をするのに必要です。
2. メソッド本体内で、文を 論理的にグループ分けしたい場合。
3. 必要な場合、クラスの最初のメンバーの前と最終メンバーの後。（推奨も禁止もしない）
4. 本文書の別の節で入れるよう求められた場所（3.3節の インポート文 など）

複数の連続した空行を入れて良いが、必須でも推奨でもない。

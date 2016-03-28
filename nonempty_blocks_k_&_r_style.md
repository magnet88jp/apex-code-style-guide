# 空でないブロック：K&Rスタイル

中括弧は空でないブロックや、ブロック様の構造物ではカーニハン・リッチースタイル（Egyptian Brackets）に従います。

* 開始中括弧の前に改行を入れません。
* 開始中括弧の後に改行を入れます。
* 終了中括弧の前に改行を入れます。
* もし終了中括弧が文やメソッドの本体を終えるならばその中括弧の後に改行を入れます。例えば終了中括弧の後に else や、カンマが続く場合は改行を入れません。

例：

```
return new MyClass() {
  @Override public void method() {
    if (condition()) {
      try {
        something();
      } catch (ProblemException e) {
        recover();
      }
    }
  }
};
```
列挙型でのいくつかの例外は、4.8.1節 列挙型 にて示されます。

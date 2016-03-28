# フォールスルーにはコメントを入れます

スイッチブロック内では、各ステートメントグループは突然処理が終了する（ break か continue か return か例外のスロー）か、実行が次のステートメントグループに進むようなコメントが付けられるかのどちらかだけです。フォールスルーということを示すコメントも効果的である。 （典型的には // fall through ）この特別なコメントは、最後のステートメントグループには必要ありません。

例：

```
switch (input) {
 case 1:
 case 2:
   prepareOneOrTwo();
   // fall through
 case 3:
   handleOneTwoOrThree();
   break;
 default:
   handleLargeNumber(input);
```

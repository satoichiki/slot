# スロットマシンを作る

簡単なスロットマシンをJSで作りました。
  
 http://satoichiki.github.io/slot/
  
Slot.jsを導入して、scriptで以下のように記述すればスロットマシンが出来ます。

```javascript
var slot1 = new Slot(
  ["f1.jpg", "f2.jpg", "f3.jpg"],//画像のURL
  100,    //画像の幅
  100,    //画像の高さ
  100,    //スロットのx座標
  0,      //スロットのy座標
  "slot1" //id名
  );
```
  

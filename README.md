* [實作示範的播放清單](https://www.youtube.com/playlist?list=PLRle6wVrCU6OS5tFzDAzAaDKiSw41_cz5)

-----

透過初學者的用書學習，難以寫出好的程式碼。

>> 除了那些教你如何寫出好的程式碼的書之外。

# 日記程式 Code Review

* 什麼是 Code Review ?
* 程式本身有什麼問題？
* 缺乏與自身經驗連結的範例

----


* 討論串：https://www.facebook.com/groups/1403852566495675/permalink/2562730467274540/
* 主程式：https://github.com/SaviorDT/-/blob/master/src/frame/Main.java

## 對 GUI 實作的觀念

* 常見的 Pattern 不一定要很早就學: MVC, MVVM, MVP
* GUI 是與使用者互動的媒界，視為 I/O 的一種徑途
* GUI 不管用何種 Pattern 都是 View 的角色
  * 負責傳遞外界的 event
  * 負責顯示結果
  * 就是不會有核心邏輯

## 值得先投入的基本習慣

* 儘可能縮小變數的 scope
* 每個 class 不要超過 150 行
* 每個 method 不要超過 1 個畫面
* 避免直接取用 field

## 長期投資的概念

* Refactoring
* TDD
* DDD
* Clean Architecture
* SOLID



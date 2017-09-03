# 台灣麻將 Taiwan Mah Jong

不限思考時間的線上單機練習: https://leoliu1313.github.io/ma/

麻將原稱麻雀 民國初年由大陸傳入台灣 慢慢地從廣東的十三張玩法演變成台灣的十六張玩法 麻將大致上有北京/南昌/廣東/香港/日本等幾種分支 但台灣麻將有一些從古至今全世界都沒有的限制: 過水不可胡牌的限制 碰槓的限制

## Rules

- https://zh.wikipedia.org/zh-tw/%E5%8F%B0%E7%81%A3%E9%BA%BB%E5%B0%87
- http://www.gametower.com.tw/Games/Freeplay/MJ/Star31/Data/mjintro.aspx
- http://www.gametower.com.tw/Games/Freeplay/MJ/Star31/Data/jargon.aspx
- http://www.gametower.com.tw/Games/Freeplay/MJ/Star31/Data/count.aspx

台灣麻將在開始時 先隨便坐好並準備好三顆骰子和東南西北四張牌 用三顆骰子決定哪邊是東風 (東風右手邊為南風 南風右手邊為西風 西風右手邊為北風) 接著按東南西北的順序抽那四張牌決定自己坐在哪一個門風 東風圈是第一圈 坐在東風的是第一圈第一盤的莊家

除了"牌被抓"的順序是順時鐘之外 所有的順序都是逆時鐘 例如東風抓完CD兩疊共四張牌換南風抓EF兩層共四張牌 東風>南風是逆時鐘 CD>EF是順時鐘

```
 ABCDEFGHIJKLMNOPQR
R                  A
Q                  B
P                  C
... 總共18(A-R)*2(層)*4(風位)=144張牌
```

眼=將眼=雀眼=將頭=雀頭=將牌=雀牌=對子=22

順子=234

刻子=222

槓子=2222

面子=順子/刻子/槓子

胡牌=和牌=五面一眼=十七張標準牌 自摸成和牌的那一張牌 不可隨意插入手牌之中 就單獨擺放 以便核查: 過水不可胡牌的限制 碰槓的限制

打出的牌必須先放在自己門前明示一下 然後歸入牌池內 放入牌池內的牌子要有序地從左向右擺放 放置到第6張後 再依次另放一行 排列要整齊 以便於觀察

### 時間

- [日本麻將規則](https://zh.wikipedia.org/zh-tw/%E6%97%A5%E6%9C%AC%E9%BA%BB%E5%B0%86%E8%A7%84%E5%88%99#.E5.89.AF.E9.9C.B2.E7.9A.84.E4.BC.98.E5.85.88.E9.A1.BA.E5.BA.8F)
- [中國麻將競賽規則](https://zh.wikisource.org/zh-hant/%E4%B8%AD%E5%9B%BD%E9%BA%BB%E5%B0%86%E7%AB%9E%E8%B5%9B%E8%A7%84%E5%88%99)

要吃牌的人應先等待2~3秒讓碰牌的玩家決定要不要碰

超過3秒鐘才碰牌 即為犯規 在一盤比賽內 第一次警告

上家未打出牌 即動手摸牌 視為犯規 在一盤比賽內 第一次警告

如手中有花牌 首先由莊家補花 再由南家、西、北家逐補完 全部時間不得超過30秒 然後莊家打出第一張牌

每次從上家打出牌後 到自己出牌的時限為15秒

### 過水不可胡牌的限制

當你可『胡牌』 卻放棄了胡牌的機會 會受到『過水不可胡牌』的限制 直到你下次打出一張『不是你所聽的牌』 才能解除『過水不可胡牌』的限制 這是避免有心人拼自摸或是刻意不胡自己的朋友違反運動家精神 這是台灣麻將才有的限制

例如你聽很多張牌 有五筒和其他張牌 任何一家打了五筒 你沒有胡 此時起算 你不可以胡牌

如果後來任何一家打了任何『你所聽的牌』 你都不可以胡牌

如果後來你摸到『不是你所聽的牌』 打出去 此時起算 你又可以開始等胡牌

如果後來你摸到『你所聽的牌』 不算自摸 此時有兩種選擇

- 打出摸到的那張牌 然後再等下一次摸牌 直到你摸到『不是你所聽的牌』 打出去 才可以解除過水
- 轉聽其他的牌 打出其他張牌 如果這張打出的牌還是『你所聽的牌』 過水還是沒有解除

### 碰槓的限制

如果你有三張掀開的牌是一樣的(刻子) 你自己摸到了第四張要槓 這就叫做"加槓"=補槓=小明槓

如果你手裡有三張一樣的牌(刻子) 你自己摸到了第四張要槓 這就叫做"暗槓" 要把你槓的牌蓋起來推出去 從補花那裡摸一張牌 再打一張出去

如果你手裡有三張一樣的牌(刻子) 而別人打出了第四張 你要槓 你就要喊槓 然後把牌推出去(掀開) 一樣是要從補花那裡摸一張 然後打出去 這就叫做"碰槓"=明槓=大明槓

但是有兩種情形不能"碰槓" 這是避免有心人做牌作弊 這是台灣麻將才有的限制

- 上家打的牌不能"碰槓"

- 聽牌時不能"碰槓" 但聽牌時"加槓"或"暗槓"是可以的

如果你先碰再"加槓" 之後無論哪一家打你想碰的話或是上家打你想吃的牌 你都可以吃可以碰阿 就等下一輪再"加槓"就好

## Strategy

- [依照牌理打牌](https://zh.wikibooks.org/zh-hant/%E6%97%A5%E6%9C%AC%E9%BA%BB%E5%B0%87%E4%B8%AD%E9%9A%8E/%E4%BE%9D%E7%85%A7%E7%89%8C%E7%90%86%E6%89%93%E7%89%8C)
- http://www.gametower.com.tw/Games/Freeplay/MJ/Star31/Data/teach.aspx
- [吃碰槓的不利](https://zh.wikipedia.org/zh-tw/%E6%97%A5%E6%9C%AC%E9%BA%BB%E5%B0%86%E8%A7%84%E5%88%99#.E5.89.AF.E9.9C.B2.E7.9A.84.E4.B8.8D.E5.88.A9)
- [槓的不利](https://zh.wikipedia.org/zh-tw/%E6%97%A5%E6%9C%AC%E9%BA%BB%E5%B0%86%E8%A7%84%E5%88%99#.E6.9D.A0.E7.9A.84.E6.9C.89.E5.88.A9.E4.B8.8E.E4.B8.8D.E5.88.A9.E4.B9.8B.E5.A4.84)

## References

- https://www.ptt.cc/bbs/MJ/M.1195752533.A.343.html
- https://tw.answers.yahoo.com/question/index?qid=20050601000011KK03116
- https://tw.answers.yahoo.com/question/index?qid=20110119000015KK08137
- http://www.i-gamer.net/play/1926.html

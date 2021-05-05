# SnakeWithTypeScript
>- Editor: Jung

## 貪吃蛇練習
最近在學TypeScript想透過一些實作 - 貪吃蛇的小遊戲，來熟悉TS。
### 主要有幾個類
蛇 - 成員屬性: 蛇的contaier、蛇的身體、蛇的頭；成員方法: 增加身體、移動身體、檢查頭和身體有無重疊。
食物 - 成員屬性: 食物本體；成員方法: 修改食物位置。
得分版 - 成員屬性: 分數、等級；成員方法:加分、升等。
遊戲控制 - 成員屬性:蛇、食物、得分版、方向、遊戲狀態；成員方法: 遊戲初始化、鍵盤事件、蛇移動的方法、吃食物。

### 使用webpack打包工具
適用瀏覽器: ie:^11

### 補充知識
- [Function.prototype.bind()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_objects/Function/bind)
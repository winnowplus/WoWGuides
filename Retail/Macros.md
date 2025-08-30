# 魔兽世界正式服 | 实用宏命令

## 1. 基本格式

+ 使用装备宏
  
  ```text
  #showtooltip <inventorySlot>
  /use <inventorySlot>;
  ```
  
  | inventorySlot | 部位         |
  | :------------ | :----------- |
  | ~~0~~         | ~~弹药~~     |
  | 1             | 头部         |
  | 2             | 颈部         |
  | 3             | 肩部         |
  | 4             | 衬衣         |
  | 5             | 胸部         |
  | 6             | 腰部         |
  | 7             | 腿部         |
  | 8             | 脚部         |
  | 9             | 腕部         |
  | 10            | 手部         |
  | 11            | 手指1        |
  | 12            | 手指2        |
  | 13            | 饰品1        |
  | 14            | 饰品2        |
  | 15            | 披风         |
  | 16            | 主手         |
  | 17            | 副手         |
  | ~~18~~        | ~~远程武器~~ |
  | 19            | 战袍         |
  | 20+           | 专业工具     |

+ 友方施法宏 自我(按下ALT)>目标>指向>自我
  
  ```text
  #showtooltips
  /cast [mod:alt, @player][help, nodead][@mouseover, help, nodead][@player]<法术名>;
  ```

+ 不切换目标施法宏
  
  ```text
  #showtooltips
  /clearfocus [@focus, dead]
  /cleartarget [@focus, noexists]
  /targetenemy [@focus, noexists]
  /cast [@focus, harm, nodead][]<法术名>;
  /targetlasttarget [@focus, noexists]
  /startattack
  ```

## 2. 圣骑士示例

+ 圣光闪现
  
  ```text
  #showtooltips
  /cast [mod:alt, @player][help, nodead][@mouseover, help, nodead][@player]圣光闪现;
  ```
  
+ 圣疗术
  
  ```text
  #showtooltips
  /cast [mod:alt, @player][help, nodead][@mouseover, help, nodead][@player]圣疗术;
  ```

+ 清毒术
  
  ```text
  #showtooltips
  /cast [mod:alt, @player][help, nodead][@mouseover, help, nodead][@player]清毒术;
  ```

+ 责难
  
  ```text
  #showtooltips
  /clearfocus [@focus, dead]
  /cleartarget [@focus, noexists]
  /targetenemy [@focus, noexists]
  /cast [@focus, harm, nodead, combat][combat]责难;分解;
  /targetlasttarget [@focus, noexists]
  /startattack
  ```

+ 复仇者之盾
  
  ```text
  #showtooltips
  /cleartarget
  /targetenemy
  /cast 复仇者之盾;
  /targetlasttarget
  /startattack
  ```

+ 惩戒爆发
  
  ```text
  #showtooltips
  /cast [mod, known:盲目之光]盲目之光;[mod, known:忏悔]忏悔;[mod]制裁之锤;
  /castsequence [known:神圣之锤, @player] reset=10 最终清算,灰烬觉醒,灰烬觉醒,圣洁鸣钟,灰烬觉醒;
  /cast [known:处决宣判]处决宣判;[known:最终清算, @player]最终清算;[known:神圣棱镜]神圣棱镜;
  /use [nomod]13;
  ```

# 临时自用

## 待考察插件

+ _AntInvite - 阻止 15 级以下人员的邀请
+ ActionButtonUtils - 高亮动作条图标
+ aDF - 显示目标的防御信息，包括护甲、抗性和特定减益
+ BetterCharacterStats - 属性页面增强
+ CCWatch - 控制时间条
+ Channel monitor - 监控聊天频道的特定关键字
+ ChroniclesBuffAssignments - 自动分配团队 Buff，分配结果可以粘贴到聊天框
+ CleveRoidMacros - CleverMacro + Roid-Macros
+ DebuffFilter - 过滤出重要的Debuff单独显示，类似 PowerAura
+ Decursive - 一键驱散
+ Distance - 基于 Player 各类法术的施法距离估算目标距离
+ EasyCloak - 黑龙披风助手
+ EnemyFrames - 战场敌对框架
+ Flyout - 弹出式法术菜单
+ FocusFrame - 焦点支持
+ SimpleActionSets

## 战场

排队

```text
/script local battlefieldName = "奥特兰克山谷";LeaveBattlefield();VanillaPlus.SetBattlefieldProperty(battlefieldName, "report", true);VanillaPlus.AutoRejoinTWBattlefield(battlefieldName);
```

退排

```text
/script VanillaPlus.AcceptBattlefieldPortByName("奥特兰克山谷", 0)
```

追场

```text
/script local battlefieldName = "奥特兰克山谷";VanillaPlus.JoinNewestTWBattlefield(battlefieldName)
```

使用说明

- 排队宏，会自动加入排队，自动退100秒以上的坑场；掉坑就猛按，没出场几秒按一次刷新；
- 100秒以内的坑场，使用退排宏；
- 排队宏每10秒或出现新场时，会重新报新场；如果报的新场变了，自己没出场，按追场宏，会自动追100秒以内的最新场。

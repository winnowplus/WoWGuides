# 临时自用

## 装备导出

惩戒骑士

```txt
/script local C = VP_Gear_Coll; XyExportEdit:SetText(ExportGearStats(C.T35Paladin_Retribution, C.T3Paladin_Retribution, C.AQ40Paladin_Retribution, C.PVPPaladin, 21623, 23667, 23668));XyExportFrame:Show();
```

神圣骑士

```txt
/script local C = VP_Gear_Coll; XyExportEdit:SetText(ExportGearStats(C.T35Paladin_Holy, C.T3Paladin_Holy, 16951, 16956, 16952, 21604, 20264, 21582));XyExportFrame:Show();
```

## 附魔检查

惩戒骑士Pvp

```txt
/script local expect = {2584,928,2716,0,1891,92,2584,1068,1886,2564,928,928,0,0,849,1900}; for s,e in ipairs(expect) do InspectInventoryEnchant("player", s, e); end
```

惩戒骑士Pve

```txt
/script local expect = {3016,928,2716,0,1891,92,3016,1887,1885,2564,928,928,0,0,849,1900}; for s,e in ipairs(expect) do InspectInventoryEnchant("player", s, e); end
```

神圣骑士

```txt
/script local expect = {2584,96,2715,0,1891,359,2584,1068,2566,2617,96,96,0,0,1888,2505,929}; for s,e in ipairs(expect) do InspectInventoryEnchant("player", s, e); end
```

## 待考察插件

+ _AntInvite - 阻止 15 级以下人员的邀请
+ ActionButtonUtils - 高亮动作条图标
+ aDF - 显示目标的防御信息，包括护甲、抗性和特定减益
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

+ 排队宏，会自动加入排队，自动退100秒以上的坑场；掉坑就猛按，没出场几秒按一次刷新；
+ 100秒以内的坑场，使用退排宏；
+ 排队宏每10秒或出现新场时，会重新报新场；如果报的新场变了，自己没出场，按追场宏，会自动追100秒以内的最新场。

# 魔兽世界香草服 | 实用宏命令

Command 格式的宏 (如 `/cast`) 需要安装 ClassicMacros 插件。

## 1. 战场排队

打开战场列表：

```text
/script local m,d,db,b=TWMiniMapBattlefieldFrame,DropDownList1,DropDownList1Button3,BattlefieldFrame;if not b:IsShown() then if d:IsShown() then db:Click(); else m:Click();db:Click(); end end
```

宏命令中的 `DropDownList1Button3` 可修改为 DropDownList1Button3 ~ DropDownList1Button7，依次对应:

- 血环竞技场 (Blood Ring)
- 战歌峡谷 (Warsong Gulch)
- 阿拉希盆地 (Arathi Basin)
- 奥特兰特山谷 (Alterac Valley)
- 阳光林地山谷 (Sunnyglade)

加入战斗：

```text
/script BattlefieldFrameJoinButton:Click();
```

打开战场列表和加入战斗也可以合并到一个宏：

```text
/script local m,d,db,b=TWMiniMapBattlefieldFrame,DropDownList1,DropDownList1Button3,BattlefieldFrame;if not b:IsShown() then if d:IsShown() then db:Click(); else m:Click();db:Click(); end end BattlefieldFrameJoinButton:Click();
```

## 2. 切换分配方式

切换队伍分配和队长分配 (将宏中的 masterPlayer 修改为团队分配者的名字)：

```text
/script local lootmethod, masterlooterPartyID, masterlooterRaidID = GetLootMethod();if(lootmethod ~= "master") then SetLootMethod("master","masterPlayer") elseif(lootmethod ~= "group") then SetLootMethod("group") end
```

## 3. 一键输出 | 更新中

### 3.1. 战士

1级 - 英勇打击平砍

```text
#showtooltip
/cast 英勇打击;
/startattack
```

4级 - 增加战斗怒吼和撕裂

```text
#showtooltip
/cast [nomybuff:战斗怒吼]战斗怒吼;[notardebuff:撕裂]撕裂;英勇打击;
/startattack
```

### 3.2. 圣骑士

1级 - 挂正义圣印平砍

```text
#showtooltip
/cast [nomybuff:正义圣印]正义圣印;
/startattack
```

4级 - 增加力量祝福和审判

```text
#showtooltip
/cast [nomybuff:祝福,@player]力量祝福;[nomybuff:正义圣印]正义圣印;审判;
/startattack
```

10级 - 增加神圣打击 (可修改力量祝福为智慧祝福，正义圣印为命令圣印等)

```text
#showtooltip
/cast [nomybuff:祝福,@player]力量祝福;[nomybuff:正义圣印]正义圣印;审判;
/cast [nocd:神圣打击]神圣打击;
/startattack
```

全程智慧圣印，十字军打击

```text
#showtooltip
/cast [nomybuff:祝福,@player]智慧祝福;[nomybuff:智慧圣印]智慧圣印;[cd:审判][tardebuff:智慧审判]十字军打击(等级 1);审判;
/cast [nocd:神圣打击]神圣打击;
/startattack
```

全程命令圣印，蓝量充足或智慧审判时十字军打击

```text
#showtooltip
/cast [nomybuff:命令圣印]命令圣印;[cd:审判,mymp>30][cd:审判,tardebuff:智慧审判]十字军打击(等级 1);审判;
/cast [nocd:神圣打击]神圣打击;
/startattack
```

保证智慧审判后命令圣印

```text
#showtooltip
/cast [nocd:审判,nomybuff:智慧圣印,notardebuff:智慧审判]智慧圣印;[nomybuff:圣印]命令圣印;[cd:审判,mymp>30]十字军打击;[cd:审判]十字军打击(等级 1);审判;
/cast [nocd:神圣打击]神圣打击;
/startattack
```

十字军圣印审判，命令圣印平砍

```text
#showtooltip
/cast [nocd:审判,nomybuff:十字军圣印]十字军圣印(等级 4);[nomybuff:圣印]命令圣印(等级 1);审判;
/cast [nocd:神圣打击,mymp>30]神圣打击;[nocd:神圣打击]神圣打击(等级 1);
/startattack
```

## 4. 附录：ClassicMacros 说明书

### 4.1. 命令列表

```text
# ClassicMacros
Bringing retail macro commands to classic WoW.

"/cast [condition,@unit]<spell>;"         Cast spell if condition met
"/use <item>"                             Use an equipped item or an item from your inventory
"/castrandom <spell1>, <spell2>, etc"     Cast one of the specified spells at random
"/stopcasting"                            Cancels your current cast

"/cancelform"                             Takes druids out of form and rogues out of stealth
"/cancelaura <Auraname>"                  Cancels the specified buff

"/startattack"                            Initiates melee combat
"/stopattack"                             Stops melee combat

"/petaggressive"                          Sets your pet to agressive
"/petpassive"                             Sets your pet to passive
"/petdefensive"                           Sets your pet to defensive
"/petattack"                              Commands your pet to attack your target
"/petfollow"                              Commands your pet to follow you
"/petstay"                                Commands your pet to stay at its location

"/cleartarget"                            Deselects your target
"/lasttarget"                             Selects your previous target

*** WARNING: THE FOCUS FUNCTION ONLY SAVES THE NAME OF YOUR CURRENT TARGET. UPON REAQUIRING YOUR FOCUS YOU MIGHT GET A DIFFERENT MOB WITH THE SAME NAME ***

"/clearfocus"                             Clears your focus
"/focus"                                  Saves your current target as your focus
"/targetfocus"                            Targets your focus

*** WARNING: THE FOCUS FUNCTION ONLY SAVES THE NAME OF YOUR CURRENT TARGET. UPON REAQUIRING YOUR FOCUS YOU MIGHT GET A DIFFERENT MOB WITH THE SAME NAME ***
```

### 4.2. cast 宏

#### 4.2.1. 基本格式

```text
#showtooltip
/cast [condition1,@unit1][condition2,condition3,@unit2]spell1;[condition4,@unit4]spell2;
```

比如：

```text
#showtooltip
/cast [@mouseover,help,nodead][help,nodead][@player]圣光术;
```

- 若鼠标指向友方，对指向目标施放圣光术；
- 否则若目标为友方，对目标施放圣光术；
- 否则对自身施放圣光术；

#### 4.2.2. 支持的Conditions

```text
exists                              UnitExists
help                                UnitCanAssist
harm                                UnitCanAttack
dead/alive                          UnitIsDead or UnitIsGhost
isnpc                               not UnitIsPlayer

combat                              UnitAffectingCombat("player")
stealth                             Is *player* stealth, for Rogue or Druid
move                                Is *player* on moving

mod:alt/ctrl/shift                  IsAltKeyDown/IsControlKeyDown/IsShiftKeyDown
alt/ctrl/shift                      Same as above

form:1/2/3...                       ShapeshiftForm met
stance:1/2/3...                     Same as above
cp:1~5                              ComboPoints met

cd:spellname                        Cooldown of spell more than 1.5 seconds
mybuff:buffname                     Player has buff
mydebuff:debuffname                 Player has debuff
tarbuff:buffname                    Target has buff
tardebuff:debuffname                Target has debuff
myhp<(>)percentage of health        Health of player more(less) than giving percentage
mymp<(>)percentage of mana          Health of player more(less) than giving percentage
tarhp<(>)percentage of health       Mana of target more(less) than giving percentage
tarmp<(>)percentage of mana         Mana of target more(less) than giving percentage
```

#### 4.2.3. 支持的Units

```text
player
pet
party1~5
partypet1~5
raid1~40
raidpet1~40
target
targettarget
mouseover
```

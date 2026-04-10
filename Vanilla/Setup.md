# 魔兽世界香草服 | 客户端 & 插件

## 客户端

建议从香草服网站下载启动器来安装客户端。

### 自定义模组

+ dxvk：
+ nampower：√
+ no1600x1200：
+ transmogFix：
+ unitXp：
+ vanillaFixes：
+ vanillaHelpers：

### 游戏选项

+ 声音
  + 综合
    + 主音量：3档
    + 音效音量：3档
    + 音乐音量：1档
    + 环境音量：2档
+ 界面
  + 动作条
    + 锁定动作条：√
  + 镜头
    + 最大镜头距离：高
  + 控制
    + 目标锁定：√
    + 自动自我施法：×
  + 显示
    + 显示本人名字：√

### CVar（待用于自动游戏配置）

+ MusicVolume "0.1"
+ SoundVolume "0.3"
+ MasterVolume "0.3"
+ AmbienceVolume "0.2"
+ gxResolution "1920x1080"
+ cameraDistanceMaxFactor "2"
+ CameraDistanceMax "50"
+ UnitNameOwn "1"

## 插件

### 插件管理器

[GitAddonsManager](https://woblight.gitlab.io/overview/gitaddonsmanager/) 用于从 Git 仓库更新插件。 *从 Microsoft Store 安装 Watt Toolkit 加速访问 Github。*

+ 在 Options 标签页点击 Add directory 添加插件文件夹

  ![GitAddonsManager_Options](/Images/GitAddonsManager_Options.jpg)

+ 在 Addons 标签页点击 + 添加插件

  ![GitAddonsManager_Options](/Images/GitAddonsManager_Addons.jpg)

### 推荐插件

+ 通用

    | 名称                      | 简介               | URL                                                           |
    | :------------------------ | :----------------- | :------------------------------------------------------------ |
    | AdvancedTradeSkillWindow2 | 专业技能增强       | <https://github.com/Shellyoung/AdvancedTradeSkillWindow2.git> |
    | aux-addon                 | 拍卖行增强         | <https://github.com/OldManAlpha/aux-addon.git>                |
    | DPSMate                   | 战斗统计           | <https://github.com/jrc13245/DPSMate.git>                     |
    | Lern2Spell                | 自动替换低等级技能 | <https://github.com/mr-rosh/Lern2Spell.git>                   |
    | Outfitter                 | 一键换装           | <https://github.com/pepopo978/Outfitter.git>                  |
    | pfQuest                   | 任务助手           | <https://github.com/The-Kludge-Bureau/pfQuest.git>            |
    | pfQuest-turtle            | 乌龟任务数据库     | <https://github.com/The-Kludge-Bureau/pfQuest-turtle.git>     |
    | pfUI                      | UI整合             | <https://github.com/me0wg4ming/pfUI.git>                      |
    | pfUI-eliteoverlay         |                    | <https://github.com/shagu/pfUI-eliteoverlay.git>              |
    | TurtleMail                | 邮件增强           | <https://github.com/sica42/TurtleMail.git>                    |
    | VanillaStoryline          | 沉浸式任务对话     | <https://github.com/tubtubs/VanillaStoryline.git>             |

+ 中文客户端

    | 名称                 | 简介         | URL                                                                |
    | :------------------- | :----------- | :----------------------------------------------------------------- |
    | Atlas                | 副本地图     | <>                                                                 |
    | AtlasLoot            | 副本掉落     | <>                                                                 |
    | AtlasQuest           | 副本任务     | <>                                                                 |
    | BetterCharacterStats | 角色面板增强 | <https://gitee.com/twow-cn/BetterCharacterStats.git>               |
    | BigWigs              | 副本警报     | <https://github.com/winnowplus/BigWigs-Turtle-zhCN-Standalone.git> |
    | QuickHeal            | 一键治疗     | <https://gitee.com/WinnowPlus/QuickHeal.git>                       |

+ 英文客户端

    | 名称                 | 简介         | URL                                                     |
    | :------------------- | :----------- | :------------------------------------------------------ |
    | Atlas                | 副本地图     | <https://github.com/Otari98/Atlas.git>                  |
    | AtlasLoot            | 副本掉落     | <https://github.com/Otari98/AtlasLoot.git>              |
    | AtlasQuest           | 副本任务     | <https://github.com/Otari98/AtlasQuest.git>             |
    | BetterCharacterStats | 角色面板增强 | <https://github.com/Otari98/BetterCharacterStats.git>   |
    | BigWigs              | 副本警报     | <>                                                      |
    | QuickHeal            | 一键治疗     | <https://github.com/Bestoriop/QuickHeal-Turtle-Wow.git> |

### 插件设置（个人向）

#### pfQuest

+ 常规
  + 显示数据库 ID：√
  + 在任务日志上显示等级：√
+ 任务
  + 显示低等级任务发放者：√
+ 路径
  + 沿路径显示箭头：×

#### pfUI

以预设配置 **Legacy** 为基准，进行如下设置。

##### 一般设置

+ 头像框架
  + 点击施法
    + 启动 玩家 点击施法：√
    + 启动 目标 点击施法：√
    + 启动 目标的目标 点击施法：√
    + 启动 焦点 点击施法：√
    + 启动 小队 点击施法：√
    + 启动 团队 点击施法：√
  + 玩家
    + 能量(蓝)条 - 右侧文字：动态法力值和百分比
    + 驱散指示器 - 显示驱散指示器：图标
  + 目标
    + 能量(蓝)条 - 右侧文字：动态法力值和百分比
    + 驱散指示器 - 显示驱散指示器：图标
  + 目标的目标
    + 驱散指示器 - 显示驱散指示器：图标
  + 焦点
    + 驱散指示器 - 显示驱散指示器：图标
  + 小队
    + 驱散指示器 - 显示驱散指示器：图标
  + 团队
    + 驱散指示器 - 显示驱散指示器：图标
+ 背包和银行
  + 自动贩卖灰色物品：√
  + 自动修理装备：√
+ 动作条
  + 默认
    + 自我施法：Alt键：√
    + 字体设置 - 字体：PT-Sans-Narrow-Bold
    + 字体设置 - 快捷键文本大小：9
+ 面板
  + 显示菜单栏：√
+ 姓名板
  + ~~叠加显示~~：√
+ 第三方插件接口
  + DPSMate（皮肤）：√
  + DPSMate（停靠）：√
+ 组件
  + 模块 - 禁用 macrotweak：√
  + 皮肤 - 禁用皮肤 Gossip and Quest：√

##### 布局设置

| 框体               | 属性                     | 布局               |
| :----------------- | :----------------------- | :----------------- |
| MarkTracking       |                          | CENTER (0, 26)     |
| LootRollFrame1     |                          | CENTER (0, 0)      |
| LootRollFrame2     |                          | CENTER (0, -35)    |
| LootRollFrame3     |                          | CENTER (0, -70)    |
| LootRollFrame4     |                          | CENTER (0, -105)   |
|                    |                          |                    |
| Player             |                          | BOTTOM (-175, 188) |
| Target             |                          | BOTTOM (175, 188)  |
| Focus              |                          | BOTTOM (-280, 404) |
| TargetTargetTarget |                          | BOTTOM (0, 263)    |
| Pet                |                          | BOTTOM (0, 226)    |
| TargetTarget       |                          | BOTTOM (0, 188)    |
|                    |                          |                    |
| Group1             |                          | BOTTOM (280, 310)  |
| Group2             |                          | BOTTOM (280, 385)  |
| Group3             |                          | BOTTOM (280, 460)  |
| Group4             |                          | BOTTOM (280, 535)  |
|                    |                          |                    |
| ActionBarStances   | 图标大小：20             | BOTTOM (0, 111)    |
| Totems             |                          | BOTTOM (0, 111)    |
| ChatInputBox       |                          | BOTTOM (0, 111)    |
| ActionBarPet       | 图标大小：20             | BOTTOM (-246, 4)   |
| ActionBarMain      | 图标大小：24             | BOTTOM (0, 4)      |
| ActionBarTop       | 图标大小：24             | BOTTOM (0, 40)     |
| ActionBarLeft      | 图标大小：24，布局：12×1 | BOTTOM (0, 76)     |

##### 配置字符串

不忽略布局：

```text
Y3AAZgBVAEkAXwBjAG8AbgBmAGkAZwAgAD0AIAB7AAoAIAAgAFsAIgBkAGkAcwBhAGIAbABlAGQAIgBdAAsBDQEPARAB
EQEiAHQAbwB0AGUAbQBzABwBHgEiADAAIgAsACABEAESAXAAaQB4AGUAbABwAGUAcgBmAGUAYwB0ACoBDAEsAS4BMAEi
AXMAawBpAG4AXwBTADgBbABsAGIAbwBvAGsAPwEgAEEBLwEhAUQBRgFIAU8AcAB0AGkABgFzACAALQAgAFMAbwB1AG4A
GwEdAUABLQFVASEBEgFFAUcBXwBLAGUAeQBCAEcBFAFuAGcAKQFoAVMBagFDARIBZQFsAG8AYwBRAXoBVAF9ASIAbgFI
AVEAdQBlAHMAdAAgAEwAbwBnAFIBhQFWARIBYQBkAGQABgEFAW0AcABhAD4BhAF8AZUBIgA7AQkBZgFlAJ4BaACTAaEB
bAEiAGMAaACeAQUBcAB5AKoBQgGiAXQAcgBhAIIBRwGSAaABtQGsAWcAcgB5AHAAaABeAbQBawExAa0BYQCNAWIAYQBy
AMYBhgFtAGEAcADPAaIBiAFfAFoBuQFpAHQAswG9AccBVwFvAVQAuAFHATkB1AGsAdYBQgDNAWIAOQFzAMQB0wHdAYYB
1gFQAHIAbwA7AXMAcwBdAW4A5QHIASQBbwBsAFwB7gErAasByAHWAVQAYQAZAW4AdAB5AQECvgEDAlgBXwBSAKcBZAB5
AK4BPAGDAQsC3gESAWgAZADAAdIBaABpAGMA+gEiAXAAbABhAHkA5AHvAaIBCAFyAI0BcgBlASECfgFwAGQAngFlAG4A
JQFpAGYA3AEXAoYBaABlASYBcgDMAc4BKALmAQ4CRwBvAPYBaQBwACAAYQBmASAAigGMAZ8BKwExAAwCIgFlAdoBeAAA
AmkBUwJtAQ4CTwB1AHQACAF0AD4CLwKHAYEBaQAGAm0AbwBnAToC1QEOAkMA/QFvAHIAIABQAB8CawAnAmsCrAFiAHUA
ZgBmAHcAsAGpAUIC+wHNAWcAZQBhAoIChAJ0AIYCUAJZAhgCIgDRAXAAcgBlAHYApwFsAGMCzAF4AWMCcwB1ADgBcgB3
AG8AdwBjAq4BngFjAmEAXgJGAh4CZgCKAnsBWgKHAQ4CVAClAnIAZgKUAoACIgF0AHUAcgB0ABkBLQCdAp8CswJbAm8B
UgBhAGkAZAACAWMCdAAeAnIAZACdAbcCeQAtAHYASwJpAEwBYQBjAuIBagKLAvABDgJNAMECTQFvAHgAmAJjAJACNALs
ASUBmAKtArYCuAJlAGIB7QHkAm8BUACEAtoB+AHrAkgBRwB1ANACZAAgABACZwAVAbcBzQHxAkkBiAKCAWIBIwLaAf0C
SAA2AVgCqgKMAogCcgCDAqkClAGsAQoDDAMQA4QCmAI2AWwAzgJsAIsB/QLhAUsCcwBoArwBdwLIAfMBTAH9AloBXAFe
AWABIABWAMICZQBvAKMCpQKSAmYBcAJjAm4AYQBtAGUAIwIzAgoC1gJsAm8BJQP4AV8BYQFJAAgCOQFmALkBZQBjAkUA
bADaAWUATwCSAnIAJAI5AjsDQwLgAeYCGQHZAtACmAKvAZAC/QLtAo4BUwCIAhgB6ALZAo0BdgJSAw0CbwHZAt8CLQO9
AiIAeQJ7ApUCdQBiAGEDOgMIA/ABdwC7AVwBNgNBAiAD3wFIAUIATwFrAHQDDgPIAacBZAOQAmcAHwNmA30DXwDzAvUC
IAAFAkAC1QJ1AzwDfgOeAecCCAE2AfYCTQBHAWkAjgJjAnoCXwC1AmsA9ALxAmMC0QFyAGsA+wK6AXcB/QJFAE4DgAFQ
ASAAQgDzAZcBYwDKAVwBrANsAzQDnAGeAmUDkwNTA0gBRACQAvYBIABVAEkCRgC4ATYDYwJHAQgBZwBoAA0DAgIiAXEA
iwGNAUsDbQBjAlcCQAKjApgBxQFsA5cBmQFuAHkCYQLdA3wDvgJIAcgDaQA0AmQAggPRAzIBEwNsAwQCVQPoAkwARgBU
AMUCxwLJAs0B2wFjAncAHgJzAJsCjwLcAlEDvwNnA/ICNQNiAzQCdQD9Am4CRwFyAnQCmgILBFoDuQFiAmwDjgIFAYAB
KwJjAjQCOQFnAHkAXAGCAaYDaQByAPMBtwKdA+sB/QLoAWECGQGYA2wAkgODA4sDQQB1AD0B+AHEAXUAcwBHA2wDZQBx
AJsBygI4BOUDIgBnANcDbAPAAWQBBwMvBBIBRQNyAG0AaAJkAD4EigMSAdEBagN0AHcApwEWAkABUgKMAm0AnAOeAxUE
ZAE3BG8ATgOfA24ANgQXARkBJANbAT8DKANOAGUAvAI/BAQCuAFNBCgElgMrBOkDLQRiAQUBWwPwA9gCOQGhAggC/QJG
AEoDzgN0ANEBhgP9Ak4CjQGPAyYEewNPBCIAnQFuADYBlQJ4AXgETgQEBIsDUABvAHAAmgIgAEQAsQKRAewDqwLEAU4D
YgB1AcsDJgFtAGMASgMgBGwDsAPQA6sCOAGFAgsD7wM/BGYAgQE2BP0CQgP/AzwBrQSMAmEAZgBrALYDQgQ/BGMANgQk
AcEEjAQTBPgB2gN6BG8BRwBNAGIBtgKSAgMERwSsAuABTwH+AUgCnwSMAgUB/QGZAXcA+QFsA5sBTgFwAG8ARwEJAuUB
fQBrARIBoQKpAg4BogGwAoIEUgHtBFYBIgE0AmUElAQiAFgEQwHoBCAB+wTIAY8EdwBfAEwEdQAZAV8A4wT3ASYDbgB0
A/IEyAEAAdkCqAMbA6sDiQMfAfMEIgFXAkYCUgE0AN4BDAXNATQCDQMCAVAAHAV+BBoFIgHCARcFegEtADEANwAjBZYB
bgCuATIDhAFMAEUA9QNTAv0ErAEAAVMAdwN3AVQAigTAAncBGgHxBEMByAEWBXQDMAArBY0EIQUeBUkAIAWQAiIFQQUk
BQYFUgEyADIAOABGBUsCLgWLBFMBQgBPAFQAVABPAE0ANAWMAjcFOQVnADsFegNXA24ArwFmAUAFFAUSAUMFUgFFBU4F
MgFIBZMBHwVzBUYFJQV0AzIANABUBXEFIgBWBcQBWAUiAFoFXAVeBWAF/ATpBG0DzQEKBYYBQAIzAGsF8wR+AY8EMAOT
AUQAngL5Ad4BNQXIAUACOACPBaIBZQGRAjQClAWWBYYFogFAAjkAnQWsAZ8FkwWEAZUF3gSkBXgCzQExAFICegELBawB
HwIGAV8A9wF6APcEMgDRA8gBqgWhBawFowWYBYwCtAR+BIQBQgM+AkUDYwBlAFwAXABBAJgBTwAJBc4FAAECAc4FxgUJ
As4FUABUAC0AUwAcAy0ATgDNAfMBdwAtAH8DLQQuAGECZgCrAkACNwCoBb8FkgXBBSsBrQWXBfoEvAT+ATcEbADqBYQB
+QSlBbEFMgDuBSIBtwVIAboFvAW+BVQC8AXfBPIFwwX1BYwFsQUtAbQFfQXABQkGQAHzBa8FmgV1AbkFaQC7BZMBpwWM
AkAC/wUQBmwFIgASBqIFrgXEBQ0GcgA2AAAGEgECBhkGGwaEAXoFUwLvBaAFEwZTARUGJwb9BXIANQArBqMBcAJtAMsF
JAGBBTEAMgAgAHgAIAD8BZAFIgAtBgQGkwExBkYFJAYwBWUAqAIWBiIBQAKzBR4BtQXIAUsGGga8BTQAMgYHBjQGJQb0
BVYBmQVVBs0BXgYhBkkGUAYKBiYGDAYQATUFEgFnAIABzAGyAlgGhgGkAkEGNwPBAkIGrgTzAQgBZgSEAW4CSwQGAasC
eAZGAhUDkwFIBnAGIwZuANoBZgDJA4wBqAUSARID7AR9BagEdAK2A40BiQZfBhIBTQRuA2YAXwB1AR8CngEvBSsBXgZG
BXQAeAB0AOMEVAQjBAkBzwOTAawGOQESAmMGIQFlBjIBUAO+A1kGIgGXBoIBmQYNA0gGtgGqBrIGrgbwBIQBxAa0BpwG
EwFlAJ8GoQZmAaMGQQaTAacGbgasAdQCPAa9Br8EtwObBkYFngZ6AqAGoga2A9EGhAHTBmQGCQOUBjwG3QZ7As4GFAHh
BqUGQAHkBkkG2Aa/BtsG1AbIAUQEEARpBqIB6QbfBs8G7QaBBfAGogHyBtoG+wVUBkgEtQSLBSIGAgeaBgQH3AbMBt4G
6wbQBu4GUwEAByAANQWLBsYCIgT5A8sCkgYTAXAAHQMzAugGgQFWBFMBwQbAA/QG5QaHBSABcgWPBHUGDAG1BVAEHwLz
ATwG9QRhAycHtgZrAYsGTgP3AYQGhAE4AC4AMwAuAKsBMgFGAu8CPAd2BqIBAAFGAAcHPAZuBScFUwVwBSIGfwUSB4IF
WwVdBV8FdwVQBXoBNAAwABkFfQU9BMcFKwF1BUwFPgE4BjYFZgBBADMEBgHoAXIATABSBpUGIgZNBx4BUAdJBlIHgQWD
BVYHygZ4BVIBNwA2AEYFXwdJBUsFHQUFB40EZgCQASUBUgD9AWwAyAMHBFcGLgd9BXEHDAFzB6IBdQeTAUMARQBOAFQA
RQBSAHkHWQdyB34HcwWEAWIHggdlBwwFhQdPAXQAiAdMAYsHNgOOBfkGrAGQByAAkgesAZQHgQaXB5kHmwdYByYFHgEt
ADcAsgcbBWMHdAVKBXYF9QYiAmYABQKxBG8HSQawBykFNQBVBS0FgAWTAXcHhQW5B3QDMQA4AHwFIgZ/B8EHgQdNBSgH
SAdnB2kHbgBrB10DTAedBwwBLQB6BX0HfQW0BysB0gdXB30FegdaB58HwAehB8IHwAekB8UHaAcIBWsHVACYBOUHugeR
B84HVwXRB1UH0wfwB+YHIABbB/MHggf1B9wHZAfEBzIBZgBQALkGWAW7Bm0FCAgoBTcAzQfrB88HUwfuB5wHAAhHBtcH
CwhgB0ABogfdBzcHhgEAAYYHqAeJB6sHZQAgBkcHygcICL4HIgHsB0ABlgeYB5oHIAh0Ay0AMwAbCNkHoAdhB/YHowcQ
CIQHRwDzAZoCjQcTBTMIIQhPBwII0AeEAR8I1AdSATMAMQA1CHIF9AdDCA4IgwcAAUgIRQStBzIIogGwB08IHAgDCFII
BQjvByIG8QceATQANgBYCEcFWggmCEQIKAhvBowCVwBwAi0E2QJwAC8IPAZzALYDgAZyBy4AKgXrBzcBrwFSATEA+AcR
CCwIqQeKB5AGaAZiCK8HNAhQCFMHOQi3BzwIUgEoBTAAQAhJBtoHDQjDB94HZgdDAK8BdABCA5kEdAB/A90CrgdCBZMI
ZghRCO0HaQiYCHoBsgWJCF4HQghzCFwIighHCEkIcACQCI4HcAcICGUIUQcdCHYHsQhUCHoBNQA/CCQIgAegCCkI3wfH
BwwD0AiyBL8ITQhEBZQIxQiEBWoISQZsCAwB1gfYB50ItwhTAScIDwihCKUH0gh0AOcI5wj/B9YIrggeCMYIBwhOCDYA
MwDLCNsHzQh2CCoIZgBfCJoCMQjUCGMIwQg4AHAINwhZBe8IawgICDMAOACcCEgH4QgiAOMIXQhmAA4FawAQBVgBEgUW
CCIAsAcBCcQIlQe2BzsIxwgeATIA6gdBCHII4gh0COQIzghmB/0HpgQIB9UIbwXXCAQI2QiyCB4BtAj0CJ8I9wdGCAAB
+gf4AWsHXwNWBZEGqwgVBa0IwwhnCLAILwkdCd0IsgUzCVsI9ggVB2EFEgjTCEwI/gghCBgJQglAAVMI8Ah5BR8JSAm4
CEoJtwaEBzgJagfNAWcF6wgsCe0I2Ah4B0UJCQhZCSMJuQjUBosGSQNLA00DOQFQAxwHBgVFBzUGIgDvBLAGOAcvAX0A
CgA=
```

忽略布局：

```text
Y3AAZgBVAEkAXwBjAG8AbgBmAGkAZwAgAD0AIAB7AAoAIAAgAFsAIgBjAGgAYQB0ACIAXQALAQ0BDwEQAREBIgByAAkB
aAAXARkBDAEOAR0BHQESAWUAbgBhAGIAbABlABgBGgEiADEAIgAsABwBEAF9ADUBNwE5AR4BbgBlAHcAXwBtAG8AZAB1
AC4BXwBwAG8AcwBpAHQAaQAGAXMAMAElATYBHgEAAU0AYQByAGsAVAByAGEAYwBrAGkAbgBnAE8BGwEnARABEgF4AEcB
TgEkASAANAA7AScBEgFwAFUBKgEjATEBAgFQAG8BbgAXAWsBKAEiAHkAZgFgAS0AMQA3AHgBYwEiAGEAbgAUAW8AcgBg
ASIATABFAEYAVAA0AVEBOAFRAW0BZgBTAHcAXQFnAFQAaQBtAGUAcgBSAIQBZwBlAGQAYAEmAWIBZAF8AWgBMACBAVIB
dQFxAQwBIgBzAawBjwFiAR4BewFIAWABMgAyADgAqgESAYQBhgGIAWgBIgBCAE8AVABUAE8ATQCyAR0BkQFsASIAAAGV
AZcBmQGbAXIAVAFdARUBbgCiAWgBpAHLAWUBtgGoAbsBzAGxAcABsAFyAHAByAHLAbUBZwEaATIANAC6AVEBggG9AWgA
hwGJAcIBxAHGAeUBIADKAfcBOwESAWIAVQHoAVABywH8AXIAOQCjAe0BHgF1AD0BdgAqAYkBRABvAHcAbgD2AfgBggEB
AjMB2AEFAhIBBwJlAAkCDwLAAQwCDgL2AYIBaQAFAW4AXwBJAXoALwHAAeoBEAJ4ARIBZgAGAa0BIAAiAEkAdgGcAWYA
WgFlAFwAXABBAGQAZABPAG4AcwA4AgABAgE4Ai0CdgE/AlwAUABUAC0AUwCEAXMALQBOAFUBcgANAi0AQgBvAGwAZAAu
AHQAdABmAPYB+wFVATcABAKzARcCCAIKAhwCDQIPAngBEQIeAWEAbAB0AHMAZQBsAFsCwAEzASsCIgATAjIAYAKlASIA
GAIaAgsCZgIfAh4BIQIGASQCaQAmAokBMgAwACoCkgF1AlUBMQCIAhUCYQJ6AmMCGwIxAR0CZwKQAXQCYgBdAWQAgwKF
AsABAwKYAlUBOAB4AssBewJkApQCfgJoAqACcgAzAKMCeQGlApMCrgGVAokCAAJVAXcCjwJ5Aq8CfQIeAqkCigIBAjYA
rQKCAbkCZQK7AhYCIgCBAiMCJQInAjEBKQK8ArQCcgA1AMACBgKSAokBTABlAGYAdwHFAi0CcgBtADUCYwB0APEBcgIy
ACAAeAAgAHMCxQLHApwCygKuAcwClwK9AowCFAIaAdkBrgLTAsMClgKQAugCyQKGAogCzQJ5AQECNADRAmICGQKmArEC
qALtAjoBHAESAWcAbABvAPwBbACtArwBdQDfAuMBbgFpAL8BMQHmAssBcABRAggBLgGJAUMAbwBtAEEB9gJ5AWEAEQNI
AW8CDgNyAsgB+AFiAkoBZgBZAZsB/gFhAXkBWQJVAaABLwLyAoIBYwBsACECawBjAGEAcwAvAjIBfwISAWQAZQBiAHUA
ZgBmAF8AmgIhAhYB4AIxAf8C/AKCAXAAbABhAHkAnAEAAyIAdAB4AHQARwF3AJwBIAFnACIBiQFfA5wBZAB5ACMDywFG
A0gDSgNMA9YBTgMSA4kBUgPFAjsDPQM/A0EDiQEYA8kBdAItAmMAdQAyAzkDHgFsA0kDSwNNAz8DcgPAAXQDkAJ2A1sB
eANCA3sDBwPLAVkBaQDXAfECdQM8A44DQAOQA0QDIgCEA24DhwNPAxYDrgGLA3wDigJ0ADYDZQA4A8UCnwOGA3ADiANQ
A6QDnQONAz4DmwN6A50DXANeAw0CYQMhAUIDZgNyAGgDagP5AYoCZwBRAnUAcABaA7QDjwO3A94BrQNvA2QAcQOxAzAC
pQOSA8MDggF0AGgAFQNkAG4BcgB0AHkADwOeA3AAcwBtABYB6gIzA2sDbwBbAcwDxQJzAFwBsAIwApED1gPyA20BhAFv
AuADbQAhAlECWgMqASwBHQMqA/wCLAMiAAkCcgBJAQYBiQE4AC4AMwAuAPsCCAMiAEUAPAN0AGUATwADBFYD3wO3AlQD
SAFKAUwB7wMfAb0DKwM1AX0ACgA=
```

#### 其他插件

+ DPSMate
  + 锁定窗口：√

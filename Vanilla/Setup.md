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

    | 名称                      | 简介                 | URL                                                           |
    | :------------------------ | :------------------- | :------------------------------------------------------------ |
    | AdvancedTradeSkillWindow2 | 专业技能增强         | <https://github.com/Shellyoung/AdvancedTradeSkillWindow2.git> |
    | Atlas-TW                  | 副本地图、掉落、任务 | <https://github.com/byCFM2/Atlas-TW.git>                      |
    | aux-addon                 | 拍卖行增强           | <https://github.com/OldManAlpha/aux-addon.git>                |
    | DPSMate                   | 战斗统计             | <https://github.com/jrc13245/DPSMate.git>                     |
    | Lern2Spell                | 自动替换低等级技能   | <https://github.com/mr-rosh/Lern2Spell.git>                   |
    | Outfitter                 | 一键换装             | <https://github.com/pepopo978/Outfitter.git>                  |
    | pfQuest                   | 任务助手             | <https://github.com/The-Kludge-Bureau/pfQuest.git>            |
    | pfQuest-turtle            | 乌龟任务数据库       | <https://github.com/The-Kludge-Bureau/pfQuest-turtle.git>     |
    | pfUI                      | UI整合               | <https://github.com/me0wg4ming/pfUI.git>                      |
    | pfUI-eliteoverlay         |                      | <https://github.com/shagu/pfUI-eliteoverlay.git>              |
    | TurtleMail                | 邮件增强             | <https://github.com/sica42/TurtleMail.git>                    |
    | VanillaStoryline          | 沉浸式任务对话       | <https://github.com/tubtubs/VanillaStoryline.git>             |

+ 中文客户端

    | 名称                 | 简介         | URL                                                                |
    | :------------------- | :----------- | :----------------------------------------------------------------- |
    | BetterCharacterStats | 角色面板增强 | <https://gitee.com/twow-cn/BetterCharacterStats.git>               |
    | BigWigs              | 副本警报     | <https://github.com/winnowplus/BigWigs-Turtle-zhCN-Standalone.git> |
    | QuickHeal            | 一键治疗     | <https://gitee.com/WinnowPlus/QuickHeal.git>                       |

+ 英文客户端

    | 名称                 | 简介         | URL                                                     |
    | :------------------- | :----------- | :------------------------------------------------------ |
    | BetterCharacterStats | 角色面板增强 | <https://github.com/Otari98/BetterCharacterStats.git>   |
    | BigWigs              | 副本警报     | <https://github.com/ElesionWoW/BigWigs.git>             |
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
  + 叠加显示：√
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

```text
Y3AAZgBVAEkAXwBjAG8AbgBmAGkAZwAgAD0AIAB7AAoAIAAgAFsAIgBkAGkAcwBhAGIAbABlAGQAIgBdAAsBDQEPARAB
EQEiAHQAbwB0AGUAbQBzABwBHgEiADAAIgAsACABEAESAXAAaQB4AGUAbABwAGUAcgBmAGUAYwB0ACoBDAEsAS4BMAEi
AXMAawBpAG4AXwBNADkBYwBoAGEAbgA+AR0BQAEtAS8BIQFEAUYBSAFPAHAAdABpAAYBcwAgAC0AIABTAG8AdQBuABsB
UQEgAEEBVAEhARIBRQFHAV8AWQFbAV0BXwEgAFYAaQBkAGUAbwA/AWgBUwFDARIBZAFsAG8AYwBrAHoBaQF9ASIAcgBv
AGwAbACEAXwBVQESATsBCQFlAWUAYQB0AGgAjAFCAY4BIgBMAZQBBQFwAHkAlwFqATEBIgBnAHIAeQBwAGgAXQGgAYYB
BQFtAGIAbwBwAG8ARwF0ACkBZwGFAZkBbQBhAHAAqgGZAQUBiQFkAG8AdwBuALsBawEiAG0BSAFUAHIAYQBHATkBwwGi
AcYBXwBCAGEAcgBiADkBcwCoAboBtQGNAcQBzwFQAIgBOwFzAHMAXAHCAdkBmAHEASQBiQFbAdgBKwHaAc4BVwFfAFQA
dQByAHQAGQFhAdcBzQFEAWMAcgBlAGUAbgDWASUB9wESAWgAZACkAbkBaABpAGMAAAIiAHAAbABhAHkAzAHkAaEBVgFu
AUkA/QE4AT0BCQJ1AHAAZACUAfwBJQFpAGYAnwEQAoYBaABkASYB0wHSAQkCYQA9AeIBYgAoAiICmQFkAWkAdAB4AOoB
UgHlAaIBYwB1AHMAJAFtACkCZgBrAGMAYQA9Ai8C2wHuAUYAbAAJAWgAdAC4ATsCDwLrATcCIgF0ANIBZwBlAHQAUgJy
AFQCVgJTAlUCCQK4AXAA+gF2AJMBiwFEAs4BgQFpAGEAbABtAG8AZgFPAhECEgEtAmcAtAFtAoYBcwAZAjkBdwDAAQkC
mwFQAXMCmQFhAHUAJAHWAR8CfAI2Am4CxQHuAUMAiQFvAHIAIABQAAcCawBOAoUChgF0APEB8wFlAC0AeAJ3AAkCzwFS
AMoBZAACAQkClQFpAHIAZABwANIBdAB5AC0AdgBOAWkAigFhAAkCyQF2AZsC7gFHAE0AYQHxAWECIQJ9AkUCbgFQAK8B
GQIgAEQAZwKAAXECCQIyAicBYwBIAoIBswK9AlUCMgLiAcwCSAFHAHUArQJkACAAUgBlAGcAFQF0AMkBcgDRAl8AUwBS
AoIBYQELAjIC3wJIADYBNQJ7AVACEgFBAjsCLQLeAmQCUQJbAloCWAJcAvICbAE2AWwAqwJsAHUAZQDfAsgBTgFzAGoC
ZwDfAk8AgAIIAVYCkQLrAoYCzwFUAGgC/AGzAaEC9AIGA6YCYwAyAroCkgKZAWIAcQIFAfoBCQJFAEgCJgFPAGECcgAM
AhkDDAOGAYAB/wH4AsUBTQEfAy0D3AFVAmEBUgIYAWUAIABNAGEATQLxArsC7QFuAUsAZQB5AEIARwEUAW4AxQItA2IA
dQBmAGYACQJJA2IANgNyAhoDvALHAZUCGQE5A60C3wJCAG8AbwBrAFEDKQOZAZMBOwPZAgUDMQPuAVMAOAGKAa4BXANZ
A5QBlgIIATYB1gJNAEcBaQBeAhgCZgBfAJQCawDUAtECAAPJAXcB3wLTAtUCIAAPA/ACbAJSA6IBbgBCArABdwALA7YB
UwNvAVoB4gFeAWABTgBlAJoCLQNHAQgBZwBKAhgCbgA6AhcBGQEJAjQC8AIpAmQAvwH9AV0CYwFzAHgBJQNdAioCiAF0
AIwDYQCDAbUBMQDsAocCbgFGAHIAaQD8AWQAXgOOA6IBbQBzA3UDLQOiAqQCpgLyASgDwAMSAkgBiQJHAY0CjwIZAoAD
QgI3A0oBngMJAmYA0gFtAGoCfwMtA14CBQGAAXIAvwPsASIBZwBDAj0DIgFlAHEArAHIA/8CLQP8ATkBZwB5AFsBywJl
A24BQQB1ACsCBgGoAToC7gPoA2wB7gHRAVYCGQFvA2wAhgNfA8QBwgNyAIgB8gF0A9UB3wJDAC8DKgImAgkCpAFjAeoC
ywMABG4B8AHyAfQBTABGAFQACQJ3AAYCcwA4AXIAXwJvAHgAygPkAxIBYQCmAwYBSQNWAqkBLQM4AYQCCASiAXEA/gI7
AscC5wOHA8wDXwBEAPoB4AEgAFUAcAAgALoD1APfAkUAJQMrA2sAIABCAIgBLgTuAlsBRgNsAwMEZQAFBNYCUwAeA/4D
PgQtBIACbwBhAmUBiwLfAjkD+QF5AfYDSAFRADoEdACDAw4EPANeBAoCTgE2AaUDpwPsA5QBFQNxAf0BcwEUAiYC2QNj
AF0ENwQiAagBJQNiAEQDZQTKAWwArgF4AAkCiQNtAGUACwIcAuMDtwM1BFcCWQJNA0oDZgB3AJwBlgEtA2YAgQE6AoAD
bwDgAWkARgROAdYCawRlADsChAG2A4YCCAHiA9wCZAHfAtgCLgR5AEwBPAG0A/8DuANUAyQBuwNoAgADWwNsAOkBkwSG
AtwCKgJXAWQDugTPAakEOwIgAEwAbwDJBFIDfQBqAe0CTQE2BA4BmQG7A5sD1wRDAaIB/AGgA4EEIgCtBEMB0wQgAeUE
iAOWA18A3AN1ABkBXwCwAeEBegReA9gExAEAATkDcgBrAAEDggFHAdEEHwFVAaIBNAKjBHoBNAARAqIBTgFMAWQEtQFM
AEUAIARQAqIBpgEBBWcBLQAxADcABAUiAe0DTwGEAQIBUADSAREDUALnBPQEZgBTAHcA+wRUAG8EVwNuAE0BZQF6AfME
mQEABV4DMAAVBS0EbgAHBXAEaAFCAE8AVABUAE8ATQANBSIBDwVeAzIANAA4ADEFcgT6ARgFtQEaBRwFGAURAh8FogEA
ASIFJAVvBJ0CRgMaASsF3QQiAS4FegEwBVcFMgU0BYQBNwU5BTsFPQUSAT8FegEyADIAQwVcBUUFHQVIBUkAGwVGBT4B
TAVqAR8FMgFzBGMCHgEsBSIBwgNnBFYF/gTpA4kDNgOsBB4FcwXUBCIAMQJ0AGYAyQGPBPIEhgGRBA4CNQV5BTgCygJA
AjoDNgTiBGMFIwF4AHQAiwM5AdoEnAO1AZwFpAJ5AMIBRAV3AUkDSwNfAEQDBwKUAQgFKwE0AIMFhgGfBDkCjAV+Be0C
kwVTBIIFpQVlAKcFdwOqBUECvQSEAa8FcgWGAbECBwSRBSIByQKPArgFtQOYBaYFmQSpBWUBqwXABbUBwgXkBMUElgT3
AngFagXOBagFvgWsBTUFIgDVBbUFmgG3BZUFuQXWBYYBFgTSA2cBxwUSAdwFvQXRBb8FrQVAAeIF/gS2BcoF5gXMBcMF
mQHYBdwE4wXvBdAFFAHyBeAF9QW8AeUFqwT6BWoFMwKbBcABnQVJApYFoQVkAKMFsAUQAXQFowGAAS0CdwUMAXkFXwS9
BJAEygHgBeMEfgJgBKsDigHnBZkBKAQIAaEDtQGJAtsDBgHlARYGxgOlAqcCKAMcBhMBcAADAxwCfQX2BbsEJwY8Br8B
9QMrASIGIQEfBRYGJQPhAS8GtQE4AC4AMwAuANoBMgGjBM8CSQbaBSgGZgBGAKAEtAU8BlkFEQVoBVsF4wUXBZYFSQVw
BZgFZQVnATQAMAADBWoFBgWoAeAFYAU6BTwF+wUgBUEA+gNuANEBcgBMAFgE/gVaBu8EWgVEBWAGGQVuBUoFcQVqBWUG
HgE3ADYARAVrBvMFNgU4BW8GFAYgBc8EJQFSAIkBbABIBI8EtgPsBWoFWwYeAV4GPAZ/Bm0FbwUdBUQFhQYMAZ0GfgIz
BWwGhAFDAEUATgBUAEUAUgCPBk4FZgCRBnQAkwaKAZYGZQAzADsGLQV8BmcBpgb0BIIGgAahBksFhAa9Bh4BLQA3AL8G
BQWoBosGIgCrBq0GrwaxBhYFZgAPA/YCega8BhAFHgETBTUAfgbBBqAGwQajBsYGDAExADgAaQXjBYoGbQaNBmIFcQay
BnMGegR2BlAA2QUbBpoG4gZfAUEFiAZqBZ8GKwFiBqIGxQbZBgwBaQbnBswG6QZhBXAG6AVVBu4G4gF2BlQArwG7BsQB
mwalBt0GYwbfBmMG4Qb/BiAAZwaJBgMHXwXqBgYHVQFNBdMGUAAnAwsD7QUiABAHXwHbBhIHbAX7BoEGFQf+Bl4D5Abm
BjwG6AYcBwUH0gYyAbMGWwO1BpQGuAYyAA4H/wT1BsoGFgXeBiwHwwaDBuMFpAZfATMA3AZqBhsHLAasBq4GsAbsBtMG
RwCIARkCmAZUBnsGFwddBioHRwVFB+AGLwd6ATMAMQBCB10FqQa1AW4G6wYHByAFVQcXBLoGmQbjBScHXAf5BkQHQAH8
BsQGSAf1BjQANgBlByIANAdoBx0HNwciAFcAiwIGBDkDcAC4Bj8H+AEQA1oFLgAUBWoGNwFNAXoBMQBTBzgHCQcGAXYG
JwWKBxIBJwd9B/oGdgctB/0GeQcXBwEHMwdOBysBaQceB0QGhgIAAREElAEUAnAAgAJaA4wEcAdaBy8FXQdhBqEHeAc8
BkkHMQC+BxoHXgWABzYHlQcKAmYAlwd1BtIB4QIGBaoEmwcmB0EHuAfCBmAHowcwB78HTQfBB6gHgQfEBwABDAcmASgB
zQedB9AHFAeiB7wH9Qa+B5QH1gdnB9gHwwdrB7IG1QZZAu4H8gb9BLYHfQZ0BxMHXwcuB9MHkwflBsAH6QdAAakHggf1
BNIB+ATJAfoEVQS1B9gGtwf1BysHoAdGB2QG9QYyAPgGAgfXB0ABzwZRBwAIZgBtBxkCPgcHCA8HDwg4AJ4HdQdoAXcH
RwfkBxcHMwA4AEwHEgj9B4wG6wcfB6wH1Ab0AvAHdAAyCN8HzwcKCF4HDAjSByUIQAU2ADMA/AfNBv8H2gcYCFYHcACv
BRwIQAdbBx8I4Qf3B+MHmQFJBzUASwc/CAQHjgZCCPEG1wYdCBcHIAj2BzkI+Ac7CGYFEAhSCDUHVAjsB9MGtAa2BpUG
igVlAEYIWQcICPQHXwYhCCIAIwgOCBcHEgUwACkIpgcTCGgBFQjRBnEGFgaOBJAEDAImAVkGogFhBDkBDAIYBEMGFgbw
AoMIIgHwAm8HbAjEAWQBZQBiBIQBRADAAaQFZAhvAtIBOQDNB5IIlAi1AZYIwQGCB/ACWAfzBuMFBwIGAV8A4QF6AOEE
QQWYBZ4I/AGVCJcIggefBDgIaAF9BDkBfwRlAFwAXABBAKYDTwD9AbwIAAECAbwItQizAbwIUABUAC0AUwACAy0ATgDS
AYgBdwAtAFoDBgQuAFYCTAOGAvACNwCdCG4AkwixCKAIswjEB2gCswE2AUwDCQYbA9IBMQAbCJAIogGoCEgBqwitCOQD
ogGwCOMBKwGhCJgILgiGAaQILQFHCCIB9AiyCKIIxAfwAmsIpgg8Bv8I4AgBCZkIIgDwAusIBQkwAt0Inwj2COEICgnw
AjYAzQfuCKoIaQCsCIQBrghEBQcJEgkJCfkI6AhyADUAzQefBHIAbQB/BNMFQgYyACAAeAAgAEMGmQEYCfAIHAkFBpEI
EAnfCCsBeAZmACQIFQbZCNIBOADcCN4I9QhAAfcIowjpCKUI8gcyCQUB7wgaCfEIrwg4CUQJaAFGCQIJRAMZCRsJtQGc
CIQFIAESASEDxwIkA4YIDQIOB1AG8ATQArUBngUkCOUEfQAKAA==
```

#### 其他插件

+ DPSMate
  + 锁定窗口：√

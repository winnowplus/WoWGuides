# 临时自用

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

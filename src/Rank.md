# 等级 | Rank

## 玩家等级

### Player Rank

* 记录原版获得过的exp，再根据该数值计算玩家的等级
* 玩家等级每提升一级，均可获得1点自由分配属性点数
* 玩家等级每提升五级，玩家所有属性点+1

## 世界等级

### World Rank

* 该数值会提升世界上的生物的血量上限、速度、攻击伤害
* 世界等级计算方法为世界上所有玩家的平均等级除5以后去掉小数部分
* `WorldRank = ( sum( %AllPlayerRank% ) / %PlayerCount% ) // 5`

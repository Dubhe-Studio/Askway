# 玩家

## 元素

### Element

* 基本元素
    * 玩家可以在八种元素中任意挑选一种（或几种）元素作为自己的基本元素
    * 玩家升级所需的经验与基本元素的数量关系如下
        * `基本经验 * 1 + (基本元素数量 - 1) * 0.5`
    * 基本元素限制了玩家所能使用的法术元素，玩家只能施放与自身基本元素对应的法术
* 附着元素
    * 在玩家收到元素伤害或与自然元素接触时，元素将附着与玩家体外，此时使用法术将触发法术元素与附着元素之间的反应
        * 如附着元素与法术元素相同时，将提升法术元素威力
        * 附着元素与法术元素存在反应机制时，将按照对应反应机制处理
          * 例如在附着火元素的同时使用水元素法术，可能导致自身受到来自水火相克所产生的伤害

## 基本属性

### Base Attribute

* 生命 MaxHP
    * 20
* 体力 MaxHunger
    * 20
* 防御 DEF
    * 0
* 法抗 Element DEF
    * 0
* 攻速 ATK Speed
    * 1
* 物伤 ATK DMG
    * 1
* 法伤 Element DMG
    * 1
* 恢复 Element RES
    * 1
* 暴击 CRIT DMG
    * 20%
* 暴率 CRIT Rate
    * 15%
* 速度 Speed
    * 5
* 跳跃 Jump
    * 1.5

## 属性点

### Attribute Point

属性点最高均为30点

* 生命 MaxHP
    * 每个属性点提升5%生命上限
* 体力 MaxHunger
    * 每个属性点提升5%体力上限上限
* 防御 DEF
    * 每个属性点提升5%防御值
* 法抗 Element DEF
    * 每个属性点提升5%法抗值
* 攻速 ATK Speed
    * 每个属性点提升20%攻速
* 物伤 ATK DMG
    * 每个属性点提升20%攻击力
* 法伤 Element DMG
    * 每个属性点提升10%法术伤害
* 恢复 Element RES
    * 每个属性点提升10%法术恢复速度
* 暴击 CRIT DMG
    * 每个属性点提升5%暴击伤害
* 暴率 CRIT Rate
    * 每个属性点提升3%暴击几率
* 速度 Speed
    * 每个属性点提升2%速度
* 跳跃 Jump
    * 每个属性点提升2%跳跃高度

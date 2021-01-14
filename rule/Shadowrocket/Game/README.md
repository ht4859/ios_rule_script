# 游戏

## 前言

本项目的游戏分流规则由爬虫程序自动维护。

定时爬取互联网上开源的游戏分流规则，将其进行清洗、去重、合并、优化后，形成单一的分流规则文件，旨在解决引用大量外部规则造成规则重复的问题。

**含有Steam、Blizzard、Discord、Rockstar等分流规则**


最后检查时间：2021-01-14 20:44:38。

## 规则统计

总计规则：64 条。

各类型规则统计：

| 类型 | 数量(条) |
| ---- | ---- |
| DOMAIN-SUFFIX | 31 |
| DOMAIN | 10 |
| IP-CIDR | 22 |
| DOMAIN-KEYWORD | 1 |
## 配置说明

实时版：爬虫程序定时更新，更新频率高，能尽快同步数据源变化

稳定版：不定时手动更新，更新频率低，稳定性好

### Shadowrocket 
实时版：

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/Game/Game.list

稳定版：

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/Shadowrocket/Game/Game.list

## 重复统计


当前分流规则，未包含其他子规则。


当前分流规则，与本项目其他分流规则重复情况统计(点击重复数量可查看明细)。



| 名称 | 数量 | 重复 | 重合度 |
| ---- | ---- | ---- | ------ |
|  [China](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/China)    | 688   | [17](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/Game/Game_Repeat.list)   |   2.47% |
|  [ChinaTest](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/ChinaTest)    | 72126   | [17](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/Game/Game_Repeat.list)   |   0.02% |
|  [Blizzard](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/Blizzard)    | 38   | [3](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/Game/Game_Repeat.list)   |   7.89% |
|  [Steam](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/Steam)    | 31   | [11](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/Game/Game_Repeat.list)   |   35.48% |
|  [Rockstar](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/Rockstar)    | 5   | [1](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/Game/Game_Repeat.list)   |   20.0% |
|  [PlayStation](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/PlayStation)    | 4   | [4](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/Game/Game_Repeat.list)   |   100.0% |
|  [Epic](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/Epic)    | 15   | [2](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/Game/Game_Repeat.list)   |   13.33% |
|  [SteamCN](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/SteamCN)    | 14   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/Game/Game_Repeat.list)   |   35.71% |
|  [WildRift](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/WildRift)    | 3   | [3](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/Game/Game_Repeat.list)   |   100.0% |
|  [Supercell](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/Supercell)    | 24   | [24](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/Game/Game_Repeat.list)   |   100.0% |
|  [Riot](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/Riot)    | 54   | [3](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/Game/Game_Repeat.list)   |   5.56% |
|  [Proxy](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/Proxy)    | 27896   | [26](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/Game/Game_Repeat.list)   |   0.09% |
|  [Global](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/Global)    | 1294   | [9](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/Game/Game_Repeat.list)   |   0.7% |
|  [BlackList](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/BlackList)    | 772   | [3](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/Game/Game_Repeat.list)   |   0.39% |
|  [Discord](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/Discord)    | 6   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/Game/Game_Repeat.list)   |   100.0% |
|  [Sony](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Shadowrocket/Sony)    | 6   | [4](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Shadowrocket/Game/Game_Repeat.list)   |   66.67% |
### 特别说明
程序在实际运算时，会根据DOMAIN、DOMAIN-SUFFIX、IP-CIDR、IP-CIDR6间的包含关系进行去重，而出于运行效率考虑，重复规则只统计纯文本匹配，所以可能与实际效果有所出入，仅供参考。

## 数据来源

本项目的游戏分流规则的数据来自以下链接，通常已涵盖所有数据来源的分流规则。如果你正在使用这些分流规则，建议不要与本项目的游戏分流规则混合使用，以免造成规则重复。

- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/Extra/Game/Supercell.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/Extra/Game/WildRift.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Extra/Game/Blizzard.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Extra/Game/Discord.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Extra/Game/Steam.list
- https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/source/rule/PlayStation/PlayStation.list
- https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/source/rule/Rockstar/Rockstar.list
- https://raw.githubusercontent.com/lhie1/Rules/master/Surge/Surge%203/Provider/Steam.list
- https://raw.githubusercontent.com/sve1r/Rules-For-Quantumult-X/develop/Rules/Games/Epic.list
- https://raw.githubusercontent.com/sve1r/Rules-For-Quantumult-X/develop/Rules/Games/GamesAll.list


感谢以上分流规则作者的辛勤付出（排名不分先后）。

如果您有更好的分流规则，欢迎提交给我，我会将它加到数据源中继续完善。

## 程序特点

### 断链处理

对于某些已删除或失效的数据源，继续使用本地缓存的文件，减少因为断链造成的影响。

### 规则过滤

通过关键字、正则、模糊匹配三种方式对规则进行过滤，以移除部分数据源中的错误规则。

### 合并去重

不仅对完全相同的规则进行去重，还会根据DOMAIN、DOMAIN-SUFFIX、IP-CIDR、IP-CIDR6等规则间的包含关系进行合并去重。

### 域名解析

对DOMAIN类型的规则进行DNS解析记录查询，丢弃连续多次无法解析的域名。

### 正则合并

通过程序对相似正则进行合并，不定时手动核验正则合并结果。

### 正则推导

通过程序对含有正则的规则，推导需要MITM的主机名，不定时手动核验推导结果。

### 正则编译

通过程序对正则类型的规则进行编译，去除无法通过编译的正则。

## 最后

### 完善规则

如果您：

1. 有更优的原始规则数据
2. 有更多的黑名单规则数据
3. 有更好的优化建议
4. 在使用分流规则时出现异常
5. 有其他问题

欢迎通过[issues](https://github.com/blackmatrix7/ios_rule_script/issues/new)提交反馈，共同完善本项目的游戏分流规则。

感谢

[@fiiir](https://github.com/fiiir) [@Tartarus2014](https://github.com/Tartarus2014) [@zjcfynn](https://github.com/zjcfynn) [@chenyiping1995](https://github.com/chenyiping1995) 

提供规则数据源及改进建议

### 其他问题

爬虫开发的初衷是为满足自己几方面需求：

1. 去除混用多个去广告规则造成的重复
2. 去除多个去广告规则中某些规则
3. 多个分流规则间重复情况检查
4. 定时同步数据源更新

本项目的分流规则还是以自用为主，请不要对外宣传此分流规则。所以，还是请低调使用吧。
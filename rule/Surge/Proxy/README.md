# Proxy

## 前言

本项目的Proxy分流规则由爬虫程序自动维护。

定时爬取互联网上开源的Proxy分流规则，将其进行清洗、去重、合并、优化后，形成单一的分流规则文件，旨在解决引用大量外部规则造成规则重复的问题。

最后检查时间：2021-03-14 01:54:44.570901。

## 规则统计

总计规则：28685 条。

各类型规则统计：

| 类型 | 数量(条) |
| ---- | ---- |
| DOMAIN-SUFFIX | 28514 |
| USER-AGENT | 12 |
| DOMAIN | 39 |
| DOMAIN-KEYWORD | 29 |
| IP-CIDR | 88 |
| IP-CIDR6 | 3 |
## 配置说明

实时版：爬虫程序定时更新，更新频率高，能尽快同步数据源变化

稳定版：不定时手动更新，更新频率低，稳定性好

### Surge 
实时版：

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy.list

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Domain.list

稳定版：

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/Surge/Proxy/Proxy.list

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/Surge/Proxy/Proxy_Domain.list

如果稳定版无法访问 ，可能是尚未从实时版的分支合并，建议您先使用实时版，或等待下次稳定版分支合并。

### 特别说明

Proxy.list请使用RULE-SET。

Proxy_Domain.list请使用DOMAIN-SET。

## 重复统计


当前分流规则，未包含其他子规则。


当前分流规则，与本项目其他分流规则重复情况统计(点击重复数量可查看明细)。



| 名称 | 数量 | 重复 | 重合度 |
| ---- | ---- | ---- | ------ |
|  [9to5](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/9to5)    | 7   | [7](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   100.0% |
|  [ATTWatchTV](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/ATTWatchTV)    | 6   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   100.0% |
|  [Atlassian](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Atlassian)    | 5   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   100.0% |
|  [CNN](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/CNN)    | 6   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   100.0% |
|  [Comodo](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Comodo)    | 5   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   100.0% |
|  [DigiCert](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/DigiCert)    | 5   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   100.0% |
|  [Espn](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Espn)    | 5   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   100.0% |
|  [Jwplayer](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Jwplayer)    | 5   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   100.0% |
|  [Picsee](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Picsee)    | 6   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   100.0% |
|  [Sectigo](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Sectigo)    | 7   | [7](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   100.0% |
|  [Shopify](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Shopify)    | 8   | [8](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   100.0% |
|  [Slack](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Slack)    | 8   | [8](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   100.0% |
|  [Sling](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Sling)    | 5   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   100.0% |
|  [Snap](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Snap)    | 6   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   100.0% |
|  [Spark](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Spark)    | 5   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   100.0% |
|  [Stackexchange](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Stackexchange)    | 15   | [15](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   100.0% |
|  [VK](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/VK)    | 7   | [7](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   100.0% |
|  [Voxmedia](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Voxmedia)    | 16   | [16](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   100.0% |
|  [WIX](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/WIX)    | 9   | [9](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   100.0% |
|  [Wikimedia](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Wikimedia)    | 20   | [20](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   100.0% |
|  [Wikipedia](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Wikipedia)    | 12   | [12](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   100.0% |
|  [Wordpress](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Wordpress)    | 8   | [8](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   100.0% |
|  [Zendesk](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Zendesk)    | 6   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   100.0% |
|  [Global](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Global)    | 28769   | [28599](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   99.41% |
|  [BlackList](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/BlackList)    | 772   | [759](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   98.32% |
|  [VOA](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/VOA)    | 51   | [49](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   96.08% |
|  [Developer](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Developer)    | 24   | [23](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   95.83% |
|  [DtDNS](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/DtDNS)    | 17   | [16](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   94.12% |
|  [Vimeo](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Vimeo)    | 16   | [15](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   93.75% |
|  [EA](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/EA)    | 163   | [150](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   92.02% |
|  [Adobe](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Adobe)    | 138   | [126](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   91.3% |
|  [Bloomberg](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Bloomberg)    | 22   | [20](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   90.91% |
|  [Line](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Line)    | 22   | [20](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   90.91% |
|  [Discord](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Discord)    | 10   | [9](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   90.0% |
|  [PayPal](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/PayPal)    | 248   | [222](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   89.52% |
|  [Dell](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Dell)    | 117   | [104](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   88.89% |
|  [Dropbox](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Dropbox)    | 17   | [15](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   88.24% |
|  [HuluUSA](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/HuluUSA)    | 51   | [45](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   88.24% |
|  [Fox](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Fox)    | 257   | [226](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   87.94% |
|  [DynDNS](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/DynDNS)    | 8   | [7](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   87.5% |
|  [Riot](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Riot)    | 54   | [45](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   83.33% |
|  [Gucci](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Gucci)    | 6   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   83.33% |
|  [Xbox](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Xbox)    | 35   | [29](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   82.86% |
|  [Github](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Github)    | 23   | [19](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   82.61% |
|  [Zee](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Zee)    | 22   | [18](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   81.82% |
|  [Bestbuy](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Bestbuy)    | 82   | [66](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   80.49% |
|  [Hulu](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Hulu)    | 56   | [45](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   80.36% |
|  [BrightCove](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/BrightCove)    | 14   | [11](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   78.57% |
|  [ZeeTV](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/ZeeTV)    | 9   | [7](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   77.78% |
|  [Cisco](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Cisco)    | 118   | [91](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   77.12% |
|  [AppleDaily](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/AppleDaily)    | 13   | [10](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   76.92% |
|  [IBM](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/IBM)    | 13   | [10](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   76.92% |
|  [Samsung](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Samsung)    | 13   | [10](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   76.92% |
|  [Nintendo](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Nintendo)    | 123   | [94](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   76.42% |
|  [CBS](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/CBS)    | 30   | [22](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   73.33% |
|  [SmarTone](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/SmarTone)    | 15   | [11](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   73.33% |
|  [Vercel](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Vercel)    | 15   | [11](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   73.33% |
|  [PCCW](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/PCCW)    | 25   | [18](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   72.0% |
|  [Scholar](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Scholar)    | 177   | [127](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   71.75% |
|  [KKBOX](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/KKBOX)    | 7   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   71.43% |
|  [KakaoTalk](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/KakaoTalk)    | 14   | [10](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   71.43% |
|  [Zoho](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Zoho)    | 13   | [9](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   69.23% |
|  [NYTimes](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/NYTimes)    | 16   | [11](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   68.75% |
|  [Facebook](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Facebook)    | 68   | [46](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   67.65% |
|  [Game](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Game)    | 532   | [356](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   66.92% |
|  [Google](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Google)    | 111   | [74](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   66.67% |
|  [Logitech](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Logitech)    | 9   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   66.67% |
|  [Manorama](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Manorama)    | 12   | [8](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   66.67% |
|  [Mozilla](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Mozilla)    | 18   | [12](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   66.67% |
|  [Pixnet](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Pixnet)    | 9   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   66.67% |
|  [Whatsapp](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Whatsapp)    | 21   | [14](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   66.67% |
|  [Twitter](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Twitter)    | 26   | [17](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   65.38% |
|  [Pinterest](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Pinterest)    | 23   | [15](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   65.22% |
|  [AbemaTV](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/AbemaTV)    | 22   | [14](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   63.64% |
|  [Nike](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Nike)    | 11   | [7](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   63.64% |
|  [Qualcomm](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Qualcomm)    | 44   | [28](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   63.64% |
|  [Telegram](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Telegram)    | 30   | [19](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   63.33% |
|  [Rarbg](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Rarbg)    | 16   | [10](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   62.5% |
|  [Disney](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Disney)    | 132   | [81](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   61.36% |
|  [Amazon](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Amazon)    | 168   | [103](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   61.31% |
|  [iCloud](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/iCloud)    | 51   | [31](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   60.78% |
|  [Microsoft](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Microsoft)    | 471   | [281](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   59.66% |
|  [Duckduckgo](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Duckduckgo)    | 43   | [25](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   58.14% |
|  [Spotify](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Spotify)    | 21   | [12](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   57.14% |
|  [TikTok](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/TikTok)    | 16   | [9](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   56.25% |
|  [Shopee](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Shopee)    | 11   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   54.55% |
|  [Cloudflare](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Cloudflare)    | 41   | [20](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   48.78% |
|  [BMW](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/BMW)    | 729   | [354](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   48.56% |
|  [Intel](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Intel)    | 263   | [126](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   47.91% |
|  [OneDrive](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/OneDrive)    | 19   | [9](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   47.37% |
|  [Dailymail](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Dailymail)    | 17   | [8](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   47.06% |
|  [AmazonPrimeVideo](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/AmazonPrimeVideo)    | 26   | [12](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   46.15% |
|  [BBC](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/BBC)    | 22   | [10](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   45.45% |
|  [Oracle](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Oracle)    | 25   | [11](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   44.0% |
|  [HBOHK](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/HBOHK)    | 14   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   42.86% |
|  [Garena](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Garena)    | 15   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   40.0% |
|  [Verizon](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Verizon)    | 182   | [71](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   39.01% |
|  [Globalsign](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Globalsign)    | 13   | [5](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   38.46% |
|  [HBO](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/HBO)    | 32   | [12](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   37.5% |
|  [Apple](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Apple)    | 116   | [43](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   37.07% |
|  [Sony](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Sony)    | 116   | [43](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   37.07% |
|  [Naver](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Naver)    | 52   | [19](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   36.54% |
|  [Verisign](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Verisign)    | 33   | [12](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   36.36% |
|  [Huffpost](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Huffpost)    | 18   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   33.33% |
|  [TVB](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/TVB)    | 21   | [7](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   33.33% |
|  [Twitch](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Twitch)    | 18   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   33.33% |
|  [ThomsonReuters](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/ThomsonReuters)    | 31   | [10](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   32.26% |
|  [eBay](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/eBay)    | 44   | [14](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   31.82% |
|  [YouTube](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/YouTube)    | 180   | [57](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   31.67% |
|  [DAZN](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/DAZN)    | 19   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   31.58% |
|  [Canon](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Canon)    | 70   | [22](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   31.43% |
|  [Westerndigital](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Westerndigital)    | 23   | [7](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   30.43% |
|  [Starbucks](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Starbucks)    | 32   | [9](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   28.12% |
|  [McDonalds](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/McDonalds)    | 26   | [7](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   26.92% |
|  [Gettyimages](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Gettyimages)    | 25   | [6](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   24.0% |
|  [Blizzard](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/Blizzard)    | 61   | [14](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   22.95% |
|  [VISA](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Surge/VISA)    | 99   | [21](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Surge/Proxy/Proxy_Repeat.list)   |   21.21% |
### 特别说明
程序在实际运算时，会根据DOMAIN、DOMAIN-SUFFIX、IP-CIDR、IP-CIDR6间的包含关系进行去重，而出于运行效率考虑，重复规则只统计纯文本匹配，所以可能与实际效果有所出入，仅供参考。

## 数据来源

本项目的Proxy分流规则的数据来自以下链接，通常已涵盖所有数据来源的分流规则。如果你正在使用这些分流规则，建议不要与本项目的Proxy分流规则混合使用，以免造成规则重复。

- https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/ProxyGFWlist.list
- https://raw.githubusercontent.com/ACL4SSR/ACL4SSR/master/Clash/ProxyLite.list
- https://raw.githubusercontent.com/GeQ1an/Rules/master/QuantumultX/Filter/Outside.list
- https://raw.githubusercontent.com/Hackl0us/SS-Rule-Snippet/master/Rulesets/Surge/Basic/Apple-proxy.list
- https://raw.githubusercontent.com/Loyalsoldier/surge-rules/release/ruleset/gfw.txt
- https://raw.githubusercontent.com/Loyalsoldier/surge-rules/release/ruleset/greatfire.txt
- https://raw.githubusercontent.com/Loyalsoldier/surge-rules/release/ruleset/proxy.txt
- https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/source/rule/BlackList/BlackList.list
- https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/source/rule/Proxy/Proxy.list
- https://raw.githubusercontent.com/lhie1/Rules/master/Surge/Surge%203/Provider/Proxy.list


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

欢迎通过[issues](https://github.com/blackmatrix7/ios_rule_script/issues/new)提交反馈，共同完善本项目的Proxy分流规则。

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
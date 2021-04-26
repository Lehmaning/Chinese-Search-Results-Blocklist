# 搜索结果黑名单
这个列表受[Google 中文搜索结果屏蔽黑名单](https://github.com/cobaltdisco/Google-Chinese-Results-Blocklist)启发，并在其基础上增加了更多域名（我并没有取得授权，所以[本列表](https://raw.githubusercontent.com/Lehmaning/Search-Results-Blocklist/master/perma-ban.txt)所有内容其实都是自己搜集的，不过未来重合度会很大）。

将会屏蔽的搜索结果有：内容农场、无良自媒体营销号、广告软件下载站、引流导航站、重定向网站、机翻别站内容的网站、长期下线网站、小黄网和博彩网站。

## 使用方法
由于 uBlacklist 适用范围更广，此处推荐使用 uBlacklist。

**1. uBlacklist**
（插件地址：[Firefox](https://addons.mozilla.org/zh-CN/firefox/addon/ublacklist/) [Chrome](https://chrome.google.com/webstore/detail/ublacklist/pncfbmialoiaghdehhbnbhkkgmjanfhe)）
 - 复制[此链接](https://raw.githubusercontent.com/Lehmaning/Search-Results-Blocklist/master/ulist.txt)，添加到 Subscription 中。
 - 如果你正在使用其他的订阅列表，那么你可以直接复制本列表中的内容，粘贴到 uBlacklist 中，然后保存。
 - **注意，若不使用列表订阅功能，则需要手动更新列表，防止误伤情况出现，否则可能会导致无法搜到想要的结果。**

**2. Google Hit Hider by Domain**
（脚本地址：[GreasyFork](https://greasyfork.org/zh-CN/scripts/1682-google-hit-hider-by-domain-search-filter-block-sites)）
 - 复制[该列表](https://raw.githubusercontent.com/Lehmaning/Search-Results-Blocklist/master/perma-ban.txt)内容，点击 List Util → Import，然后粘贴内容并导入到 **Perma-ban** 中。
 - 复制[该列表](https://raw.githubusercontent.com/Lehmaning/Search-Results-Blocklist/master/block.txt)内容，点击 List Util → Import，然后粘贴内容并导入到 **Block** 中。
 - **此脚本仅支持导入域名，而非 URL，因此可能屏蔽内容不全面。**

**3. AC-baidu**
（脚本地址：[GreasyFork](https://greasyfork.org/zh-CN/scripts/14178-ac-baidu-%E9%87%8D%E5%AE%9A%E5%90%91%E4%BC%98%E5%8C%96%E7%99%BE%E5%BA%A6%E6%90%9C%E7%8B%97%E8%B0%B7%E6%AD%8C%E5%BF%85%E5%BA%94%E6%90%9C%E7%B4%A2-favicon-%E5%8F%8C%E5%88%97)）
 - 复制[该列表](https://raw.githubusercontent.com/Lehmaning/Search-Results-Blocklist/master/perma-ban.txt)内容，启用“附加2-自主拦截域名”，点击 DIY，然后将复制的内容导入。
 - ~~其实我还没用过，不知道具体如何……~~


<!-- 在手机上使用本列表-->

## 可选列表
为了防止误伤，对部分网站做了分类，你可以选择性添加这些分类下的域名到 Block 或 Perma-ban 列表中。
- [block.txt](https://raw.githubusercontent.com/Lehmaning/Search-Results-Blocklist/master/block.txt) 以下列表的总和。
- [app.txt](https://raw.githubusercontent.com/Lehmaning/Search-Results-Blocklist/master/groups/app.txt) 国内常见应用商店和下载站的域名。
- [down.txt](https://raw.githubusercontent.com/Lehmaning/Search-Results-Blocklist/master/groups/down.txt) 长期下线网站的域名。
- [list.txt](https://raw.githubusercontent.com/Lehmaning/Search-Results-Blocklist/master/groups/list.txt) （京东、搜狗、Bilibili等）网站站内搜索结果列表的域名。
- [mirror.txt](https://raw.githubusercontent.com/Lehmaning/Search-Results-Blocklist/master/groups/mirror.txt) 镜像钓鱼网站的域名。
- [novel.txt](https://raw.githubusercontent.com/Lehmaning/Search-Results-Blocklist/master/groups/novel.txt) 网文小说站的域名。
- [political.txt](https://raw.githubusercontent.com/Lehmaning/Search-Results-Blocklist/master/groups/political.txt) 轮子等政治敏感网站的域名。

----

## 列表来源
以下是 [omni.txt](https://raw.githubusercontent.com/Lehmaning/Search-Results-Blocklist/master/omni.txt) 和 [ulist.txt](https://raw.githubusercontent.com/Lehmaning/Search-Results-Blocklist/master/ulist.txt) 中域名的来源：
- https://github.com/cobaltdisco/Google-Chinese-Results-Blocklist
- https://zh.wikipedia.org/zh-hans/%E5%85%A7%E5%AE%B9%E8%BE%B2%E5%A0%B4
- https://www.zhihu.com/question/347418658
- https://www.thenewslens.com/feature/content-farm/126592
- https://www.quora.com/Where-can-I-find-a-good-list-of-content-farms
<!--https://github.com/danny0838/content-farm-terminator/tree/gh-pages--> 
- https://qiita.com/shikato/items/0bbbd3c00499845d4579
- https://www.granneman.com/tech/search/blockjunkfromgoogle

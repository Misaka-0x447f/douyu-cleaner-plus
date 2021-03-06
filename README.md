# self.Name >>> "douyu-cleaner-plus"

为增强 [Douyu cleaner](https://github.com/weijohn/Douyu-Cleaner) 功能而设计的样式表，使用非常激进的策略清理斗鱼界面。

# Deployment

Install stylish

https://chrome.google.com/webstore/detail/stylish-custom-themes-for/fjnbnpbmkenffdnngjfgmeleoegfcffe?utm_source=gmail

Install Douyu cleaner

https://userstyles.org/styles/132037/douyu-cleaner

Install Douyu cleaner plus

https://userstyles.org/styles/136524/

# Introduction on stylish
因为不愿意提供手机号，斗鱼把我号封了。若无意外将不再为已登入后的体验进行优化。新增未登入体验优化选项。

这个主题不是Douyu cleaner作者授权或负责维护的，到那边写评论我看不到原作者也不会管。
如果有任何不爽都可以写邮件或者留评论或者到github上告诉我（建议用邮件因为只有发邮件我才能收到通知）

如果你的直播间用此样式时出现问题，欢迎联系 447f.misaka@outlook.com 或 2917433887@qq.com

<i>
请注意需要同时安装本体：
<a href="https://userstyles.org/styles/132037/douyu-cleaner">https://userstyles.org/styles/132037/douyu-cleaner</a>
</i>

Fork me on github:
https://github.com/Misaka-0x447f/douyu-cleaner-plus

使用更激进的策略进一步清理直播界面和聊天框，隐藏大部分付费内容，适用于只用斗鱼看特定主播，例如星际老流氓、同卵双狗和电竞慈禧，不关注斗鱼其他活动的人。此样式只负责屏蔽**一般直播间**的东西。

此样式仅在Windows版Google chrome上测试过，更多的只为我自己考虑，也不会测试其他浏览器的兼容性。

视频区域的礼物特效我也没办法的呀，那个是shockwave flash做的播放器并不是html做的东西stylish屏蔽不了的，我相信用stylish的大部分应该有web方面鸡本功的对不对。想屏蔽的话还是建议用第三方播放器比较好。

Support me via Litecoin: LL5oL8mYPxzHUkxwVZFQVdbs3GSwYpJDct

## Changelog
[2018/9/17]
[+]屏蔽斗鱼年度活动

[2018/6/22]
[+]屏蔽世界杯

[2018/5/20]
[+]干掉右上角开播按钮
[+]处理部分特殊直播间

[2018/3/10]
[+]因为不提供手机号，斗鱼把我号封了。从这个版本开始若无意外将不再为已登入后的体验进行优化。
[+]新增不可登入体验优化选项。

[2018/2/28]
[+]新增屏蔽元素关键字"-mall"。

[2018/2/25]
[+]尝试解除对官方H5播放器（试用支持）的屏蔽。我们仍然建议用家使用第三方H5。由于放行规则较为宽松，也许会放过一些广告，遇到此种情形请反馈。

[2018/2/23]
[+]允许竞猜功能显示，并改善竞猜功能外观

[2018/2/9]
[+]暗色主题上线。
[#]斗鱼做了个过节背景。我个人不喜欢过年。已尝试进行最大限度的恢复。
[+]增加了通知。用户可以主动关闭未来所有通知。受css能力限制，做不了不再提醒按钮。

[2018/2/8]
[+]适配了Stylish主题选项。现在你可以指定背景图像了。默认值：禁用。
[+]尝试修正网页底部多出来一块的问题
[#]调整宝箱计数器位置

[2018/2/4]
[#]对聊天区颜色进行调整以便突出聊天文字内容。
[#]对规则生效范围进行调整。现在此样式表不会影响首页、cms和全部直播页，以便于减少误伤，方便需要查看斗鱼的更多页面的用户。
[+]移除认证女性用户icon。

[2018/2/3]
[+]尝试对直播间主窗口大小进行修正。部分特殊直播间已尽力。目前在16:9屏幕上不点网页全屏也能表现良好。
[+]调整聊天选项，干掉需要付费的选项。
[+]统一聊天文字颜色和大部分界面颜色
[+]调整宝箱外观

[2018/2/2]
[#]修复全部视频页面消失问题，将"broadcast"及"padding"添加到屏蔽元素白名单

[2018/2/1]
[+]解决广告带来的遮罩问题

[2018/1/28]
[#]复现成功，尝试避免误伤验证码滑条，试图2

[2018/1/26]
[#]尝试避免误伤验证码滑条

[2018/1/25]
[+]尝试屏蔽所有贵族元素和广告元素。如有错误的屏蔽请让我知道。
[#]干死领取广告。斗鱼有完没完啊。

[2018/1/5]
[#]更改标题背景配色为官方header颜色
[+]对斗鱼视频做了一些适配，依旧是只适合看特定主播的人。隐藏推荐模块，淡化搜索框。
[+]隐藏不可以领取时等待领取的按钮。将领取按钮显示在计时器上。

[2018/1/3] issued by Zed
[#]对标题添加背景，避免出现和页面的重叠

[2018/1/2]
[+]干掉了动作列表。如果觉得精简过头了的话请写邮件告诉我。

[2017/12/28] issued by Zed
[#]对昨天的版本做patch，修复部分房间聊天框消失问题。
[+]尝试屏蔽所有“坠饰”(包括今天出现的什么盛典那个)

[2017/12/27]
[//]过了半个月看一次斗鱼又多出来一堆广告很生气。这次来试着干掉未来的一些垃圾元素吧。
[+]尝试屏蔽礼物区未来会出现的所有广告
[+]尝试屏蔽所有具有节日性质或引导性质的元素(即class名称包含festival, guide或者notice)

[2017/12/15]
[#]改进了对于<a href="https://chrome.google.com/webstore/detail/hbocinidadgpnbcamhjgfbgiebhpnmfj">斗鱼H5播放器</a>的兼容性。你现在也许可以同时使用这两个组件。
[+]清理部分活动送鱼丸链接和未登录广告
[#]清理描述中的部分错误。naive!
[+]清了个下载按钮。

[2017/12/2]
[#]聊天区域清理新增清理女性进入直播间提示

[2017/11/19]
[+]屏蔽了所有视频特效，flash视频（也就是直播视频）除外。
[+]屏蔽了搜索建议的内容。
[+]屏蔽了游戏推广。
[+]屏蔽了新出现的header特效。

[2017/11/13] contributed by @weijohn
[#]修复点击领取鱼丸按钮出现提示导致领取鱼丸列表向上偏移

[2017/8/29]
[#]将背包按钮加入回来（因为签到不怎么送鱼丸只送礼物了）

[2017/7/24]
[#]试图屏蔽这段时间以来新出现的通知

[2017/5/20]
[+]屏蔽澳门首个主播等级系统上线啦和斗鱼嘉年华什么的
[#]修复了douyu-cleaner造成的样式错误的大部分影响。现在样式稍微正常了一点。

[2017/3/5]
[+]屏蔽新功能提醒和斗鱼贵族功能提醒

[2017/2/25]
[+]清理用户面板。考虑了很久之后发现只有用户等级、用户名和‘登出’是有用的。
   毕竟是激进清理嘛。
[+]清理聊天窗口上方的按钮。仅保留2个有可能有用的按钮。

[2017/2/22]
[#]刷存在感。
[+]添加github版本控制
   (虽然一个人做这个没什么好控制的，但是还是希望能收到pull request。)
   ([2017/11/13]收到了 Douyu cleaner 作者的 pull request!)

[2017/1/14]
[+]头图烦死，屏蔽掉。

[2017/1/8]
[+]屏蔽微信提示。

[2017/1/3]
[+]屏蔽掉昨天忘了屏蔽的背包提示。

[2017/1/2]
[+]屏蔽首充提示。
[#]新年快乐！

[2016/12/25]
[+]屏蔽圣诞活动按钮，估计也能屏蔽以后的所有活动，除非斗鱼改dom结构。
[#]修正一个界面元素屏蔽问题。站内信按钮和排名情况我觉得不需要显示，平时没
人关注这些东西，想看的话临时取消一下屏蔽就好了。
[#]将Release notes改为倒序(这也能写进Release notes啊)

[2016/12/23]
[#]紧急修复了不显示礼物名不是"100鱼丸"但可用鱼丸购买的礼物的问题。
现在礼物区域显示所有鱼丸可送的礼物(如果有，例如圣诞节推出的实际上还是100鱼
丸的冰淇淋球)

[2016/12/22]
[+]改进了鱼丸领取的位置。现在，鱼丸领取时间直接显示在原打开领取窗口
按钮的位置，鱼丸领取按钮直接显示在控制栏中。(css原来这么强啊)
[+]屏蔽了新出现了主播商品推荐窗口。
[#]修正了"分享了直播间"前不显示用户名的问题(技术限制未能完全屏蔽此类消息)。

[2016/12/18]
[#]更新描述，修正了屏蔽正常的聊天消息的问题

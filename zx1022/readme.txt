

更多使用信息参阅https://t.me/juejijianghu 发布频道
             https://t.me/juejijianghuchat 聊天频道

各网盘ck配置可以参考alist里的网盘添加

配置"pwdRb115": "" 115安全删除密码后 会自动删除转的文件 空间大的留空就行
阿里源的原画 为阿里秒传115  （115不限速 非会员限制5g以下秒传）
网盘集合.json 支持根据share_index名进行聚合（不同网盘也可以随意聚合）以减少分类数目  分类更加清晰  可以参考网盘集合.json写法




今日更新
1.修复网盘-片库


1.修复115分享无法播放 115没会员的可以转阿里播放 阿里限速的可以去申请开发者 不想申请开发者的 花钱买网盘会员
2.修复阿里登陆困难
3.peizhi.json中panOrder配置不仅支持排序还支持屏蔽网盘源（比如未配置p123就不会显示123网盘源）
4.tg搜的结果也按照panOrder配置
5.非会员扫uc tv可以看伪4k
6.修复盘他系
7.优化玩偶系分类显示
  需更新goProxy


1.优化推送界面
2.盘123 支持配置中心输入
3.兼容天意其他分享格式（h5打头）推送
  需更新goProxy






 注意:由于不可抗力原因，需要关闭在线仓库、之后所有的包全都本地化
     之前的包可能在节后关闭，请升级到最新本地包版本
1.每次更新jar，都需更新peizhi.json里的exeMd5值到最新
2.包分为全量包（包含所有运行的二进制文件）和增量包（只有goProxy二进制文件）
3.除非goProxy以外的二进制文件更新，否则只发增量包减少分发体积大小



1.增加游戏直播源
2.网盘顺序可配置在json文件(优先级: 配置中心输入>本地文件>json配置)
3.自定义uc ut



1.网盘尝试适配更低版本安卓


1.配置中心 网盘顺序、画质选项 可配置隐藏普画


1.修天意搜，增加p123排序
2.修异动


1.代理不再支持本地运行
2.新增123盘(推送和tgsou)


1.仅限原版壳子（ok影视/pro、FM、影视仓、easybox）使用，其他后面加
2.以前的包 可能都不能用了 必须强制更这版及以后

1.优化玩偶系网站的搜索结果显示
2.tg搜索结果增加网盘类型显示
3.修复singbox在线地址无法订阅
4.修星剧社



1.兼容天意其他分享地址
2.新增二小 玩偶站
3.ucToken可以在json中配置


1.非会员uc需要扫两个码（一个是之前的cookie,另一个是token），才能看
2.修复uc(采用alist里uctv驱动实现)




1.uc加入多线程播放（默认6线程），如果播放大的影片卡顿，可以配置中心自己适当调整。
2.根据会员等级自动调整线程数（如果从未主动设置过线程数）
3.修复uc普画播放


1.兼容115网盘 新域名
2.tgsou兼容115网盘新域名（仅armv8和x86-linux）


1.goProxy支持本地运行 位置跟其他二进制一样在tv/lib 需要命名为goProxy 本地运行goProxy将不会自动更新 每次新jar 需要到仓库下载（https://www.gitlink.org.cn/aweqv/jueji）替换
2.提高代理加载稳定性。
3.所有二进制都支持本地运行


近期更新
1.由于依赖的gitlab仓库即将退出zg,切换到新仓库。
2.所有网盘适配iso播放，iso外调支持kodi系播放器、vlc播放器、当贝播放器等，内放支持okpro电视版vlc播放器。
3.增加天意搜站
4.增加片库网盘（类似观影、tgsou） 自己去这里（https://www.qn63.com/）找自己能访问的网址 配置下
  片库搜索功能是需要ck 我内置了一个 ck每小时需要验证下 只要有一个人验证（jar自动验证）过 其他人就不用验证 搜索会非常快
5.修星剧社（可配置访问地址）
6.tgsou服务器和tgsou本地 支持通过count参数自定义每个频道的返回的数量（默认为4）
7.goProxy支持本地运行 位置跟其他二进制一样在tv/lib 需要命名为goProxy 本地运行goProxy将不会自动更新 每次新jar 需要到仓库下载（https://www.gitlink.org.cn/aweqv/jueji）替换
8.至此所有二进制都支持本地运行了





1.iso支持kodi播放 (之前不能放是因为请求的链接不是.iso结尾 vlc 当贝没有这个限制 所以这次把链接改下就行了 非常离谱)
  测试软件：kodinerds最新版（pc和安卓）
2.网盘集合新增115个人网盘显示（格式参考网盘集合.json）ck需要带kid的ck
3.兼容115新域名 同步更新tgsou  win版和armV7暂时不更了



1.配置中心新增alist 默认不开启 点击后开启该功能
2.配合csp_AList访问 解锁所有网盘
3.由于alist比较大 建议采用本地运行方式  参考之前的方式




1.修星剧社
2.增加木偶盘
3.配置顺序微调


1.配置中心新增fileBrowser 可以方便在web端管理电视sd卡目录 端口8080 默认不开启 点击后开启该功能



1.tgsou服务器本地运行 只支持从配置中心导入session 增加tg扫码登陆
2.由于tgsou加入扫码功能 体积都变大了 建议本地加载运行
3.具体功能运行-h 获取
options:
  -h, --help     show this help message and exit
  --auth AUTH    Authorization string for the session
  --proxy PROXY  Proxy in the format: type:host:port. Type can be 'socks4', 'socks5', or 'http'.
  --port PORT    start port default 9999
  --qr           Enable QR code login
  --picNone      Disable pic server


1.新增从本地tv/lib 文件夹 加载二进制文件（singbox,allinone,tgsou）,所需文件可以从gitlab(https://gitlab.com/tvbox2/telegram-channel-video-downloader)自己下载后放入，比如tv/lib/allinone-arm64
  注意：1.优先加载本地，本地没有的自动加载gitlab上的文件 singbox,allinone,tgsou文件如果更新 本地的需要自己手动更新 无法ota
       2.go代理由于和jar有验证绑定关系 并且文件很小 规则暂时保持不变 不做本地化
       3.删除本地tv/lib下二进制文件 即可恢复在线方式加载
       4.在线加载二进制文件方式 只会下载一次 后面只会校验md5 以确定是否ota  除非软件重置或出现网络抖动





1.新增csp_TgYunDouBanPan 直接从豆瓣播放tg搜索结果


1.之前的仓库炸了 必须换别的仓



1.提高sb运行成功率，增加sb错误日志

1.新增lf zb转点播（去掉原lf 18+频道）

1.新增肥羊zb(感谢pg佬编译文件和配置文件) 需更新FongMi.json配置源
2.豆瓣增加网盘初始化事件 需更新douban配置源


1.整理配置文件路径
2.去除豆瓣js 改为java
3.tgsou 兼容更多手机运行 运行日志在tv/my_tgoutput.log目录
4.新增几个caiji源


1.singbox和tgsou内核改为gitlab cdn下载 又快又稳



1.新增tgsou 服务器本地运行模式
  配置中增加 "tgsou_api_session":"" 替换成自己的193316_session_0.txt文件里的值，第一次运行需要过一下网盘类csp 启动服务
  注意：新的授权方式 可以用其他服务器 先获取193316_session_0.txt授权文件  之后就可以复制文件的值 填到tgsou_api_session配置处




1.修复tg搜遗留bug
2.优化tg服务器搜索速度（需要部署文件）

今日大更新
1.115原盘iso起播加速到秒级（测试软件：vlc手机版、vlc pc版、当贝1.4.9  有默认播放器设置的 需要先清除默认播放器设置 然后选择vlc  vlc 最佳 当贝不是太稳定、kodi播放似乎有点问题）



1.youtube 支持登陆 解锁节点不支持播放（pc网页登陆油管后 找一个请求 获取请求头中x-Goog-visitor-id的值 填到youtube配置cookie）
2.修复youtube 之前遗留bug




1.修复youtube推送
2.tg搜支持一次配置多个频道（参考FongMi.json）
3.修复易搜（需配置cookie）
4.更新singbox 下载cdn为https://ghp.ci




1、兼容低版本安卓 部分网盘播放



1.内置代理设为可配置（需更新配置文件 "proxy":"http://127.0.0.1:1072"）支持http、socks5端口       不配置或留空 就用外部科学上网



1.由于夸克近期对非会员不同下载链接进行不同策略限速   优化夸克扫码和非会员播放(默认60线程)


1.增加推送有图比视频、直播,单视频播放 增加up主频道列表
2.推送输入支持大文本 可以从手机直接推hiddify配置到电视.


1.有图比 增加热门视频分类、近期刚发布视频分类（参考模板）


1.有图比 增加zb zm
2.修复有图比一些bug


1.更改bili 配置到tv 优先级逻辑为扫码大于本地大于配置
2.增加youtube（简易版） 可手动选择节点


1.修复阿里扫码不显示bug
2.增强jar 安全
3.新增小纸条



1.优化jar验证机制 减少闪退
2.网盘合集夸克 uc增加对share_name的检索
3.建议升级到最新版



1.配置中心 增加singbox(端口：1072 tg搜已写死1072端口) 可输入订阅地址或者直接用hiddify导出的配置 导入到jar
  有些订阅地址限制浏览器直接访问的 需要用到hiddify导出的配置 导入到jar  下载地址：https://hiddify.com/app/
2.增加singbox ui
3.阿里云盘弃用alist授权 稳定性更高


1.增加tg搜(本地 需科学上网)



1.增加115秒传阿里（玩玩就行）
2.增加豆瓣源，bili(需扫码登陆)
3.修玩偶表哥系翻页





1.配置中心增加网盘iso原盘调用外部播放器 开关
2.配置中心增加网盘下载 开关
3.网盘支持内置下载器下载
4.继续优化夸克  会员默认线程改为14 如果以前设置过32  可以调回14  非会员64线程

1.打开 阿里秒传115 自动删除转存文件功能
2.修复115 文件排序
3.优化下配置中心
4.115原盘 使用外置播放器打开
5.优化列表文件显示


1.配置中心增加uc、夸克、阿里扫码、网盘排序等（壳子需先获取外部存储权限）
2.阿里、夸克根据是否会员自适应播放（夸克非会员线程默认64 可适当往上加）
3.支持win 安卓模拟器使用

本包仅供技术学习交流



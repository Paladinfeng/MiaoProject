# Miao Project Version 2.4.4 Update Notes
- 修复：开启播放链接优化后，PCDN优化失效的问题

# Miao Project Version 2.4.3 Update Notes
- 新增：Akamai CDN 优先，处理海外用户播放视频卡顿的问题
- 新增：「匹配动态范围和帧率」 - 「强制 SDR / 59.94 fps」，开启之后，将所有视频信号输出为SDR / 59.94 fps，与系统设置保持一致时，不再会出现黑屏的问题
- 新增：适配 AI 字幕
- 更新：视频字幕黑名单
- 修复：PCDN导致部分用户播放卡顿的问题

# Miao Project Version 2.4.2 Update Notes
- 修复：某些帐号的用户详情页报错
- 修复：tvOS 26 下播放器不切换到高码率视频流
- 修复：不开启设置中的「匹配视频动态范围和帧率」，将输出 SDR 60FPS 信号，如果和系统设置一致，打开视频就不会黑屏切换 HDMI 信号
- PS：tvOS 26 也许有某些温控策略，设备高温的时候，会限制视频流的码率

# Miao Project Version 2.4.1 Update Notes
- 新增：设置 - 番剧自动跳过片头片尾
- 新增：设置 - 直播强制使用VLC播放器
- 修复：推荐页面刷新可能发生崩溃
- 修复：播放结束可能发生崩溃崩溃

# Miao Project Version 2.4.0 Update Notes
- 新增：视频广告自动跳过/视频广告屏蔽器（默认关闭，需要在设置中手动开启）
- 优化：自动跳过番剧片头片尾
- 更新：直播播放器
- 修复：登录过期的判断条件
- 修复：播放时数据解析可能导致崩溃

# Miao Project Version 2.3.4 Update Notes
- 新增：番剧支持 HDR（需要在设置中手动开启）

# Miao Project Version 2.3.3 Update Notes
- 修复：直播报错352
- 优化：视频字幕黑名单
- 优化：直播播放器

# Miao Project Version 2.3.2 Update Notes
- 修复：直播报错352
- 修复：排行榜不刷新

# Miao Project Version 2.3.1 Update Notes
- 修复：视频字幕显示错乱
- 修复：屏蔽视频字幕中的广告
- 修复：港澳台番剧无法加载视频字幕
- 修复：部份弹幕屏蔽词没有生效
- 修复：番剧页面，banner图片比例
- 修复：历史记录触发重复请求
- 优化：直播播放器

# Miao Project Version 2.3.0 Update Notes
- 新增：弹幕屏蔽器（自动同步屏蔽词）
- 修复：某些情况下视频播放完成可能会发生闪退

# Miao Project Version 2.2.13 Update Notes
- 新增：视频单集循环
- 修复：推荐页面充电视频无法打开
- 修复：账号列表中出现空白账号的问题
- 修复：部分直播间黑屏无法播放
- 修复：部分视频播放报错
- 修复：由于某脚本重写网络请求，导致动态页面报错
- 修复：历史记录加载更多时滑动到列表最上端

# Miao Project Version 2.2.12 Update Notes
- 优化：直播播放体验
- 优化：进入后台15分钟后，刷新「热门」/「排行榜」/「动态」数据
- 修复：动态页面直播的UP主显示不全

# Miao Project Version 2.2.11 Update Notes
- 修复：动态页面报错

# Miao Project Version 2.2.10 Update Notes
- 修复：无直播弹幕

# Miao Project Version 2.2.9 Update Notes
- 优化：凭证页面以及激活报错页面无法显示完整ID
- 优化：视频分享采用匿名链接
- 优化：历史记录以及收藏夹刷新模式
- 修复：部分地区进入直播后黑屏
- 修复：由于音频播放链接不可用导致整个视频无法播放

# Miao Project Version 2.2.8 Update Notes
- 优化：帧率匹配模式
- 修复： HEVC优先导致部分视频最高分辨率丢失
- 修复：部分本来可以打开的番剧Banner报错类型不支持

# Miao Project Version 2.2.7 Update Notes
- 修复：搜索报错

# Miao Project Version 2.2.6 Update Notes
- 修复：tvOS 17.2 下 App 闪退的问题

# Miao Project Version 2.2.5 Update Notes
- 新增：仅 HDR/DV 的时候开启匹配内容
- 新增：关闭匹配的状态下，不再获取杜比视界 / HDR 的视频源
- 修复：tvOS 17 置顶图片
- 修复：iCloud 环境在 tvOS 17 显示未知

# Miao Project Version 2.2.4 Update Notes
- 新增：播放报错收集机制
- 新增：使用 Sentry 收集 App 的崩溃日志
- 修复：直播弹幕在某些情况下不显示
- 修复：视频播放结束时可能发生的崩溃问题

# Miao Project Version 2.2.3 Update Notes
- 新增：设置 - 连续播放提示信息
- 修复：直播弹幕异常
- 修复：播放时可能发生的崩溃

# Miao Project Version 2.2.2 Update Notes
- 修复：镜像功能在 tvOS 16 上不起作用
- 修复：显示隐藏「动态」时，App 可能会发生崩溃
- 修复：修改播放速率可能导致 App 崩溃
- 修复：读取 iCloud 数据可能导致 App 崩溃

# Miao Project Version 2.2.1 Update Notes
- 新增：视频镜像（播放页面单次开启）
- 优化：激活报错中关于凭证的错误信息
- 优化：视频详情中分P / 合集 / 番剧，会滑动到相应位置
- 修复：超长剧集点击播放后长时间卡顿
- 修复：番剧展开全部无法播放
- 修复：倍速播放暂停后恢复一倍速
- 修复：番剧跳过OP/ED功能失效
- 修复：「即将播放」提示不自动消失

# Miao Project Version 2.2.0 Update Notes
- 新增：连续播放
- 新增：剥离番剧中的预告
- 新增：设置 - AI字幕默认状态
- 更新：番剧接口API
- 更新：登录接口
- 修复：《古相思曲》这部剧集数是反的，继续播放功能错误

# Miao Project Version 2.1.6 Update Notes
- 紧急修复：播放链接预解析导致无法播放

# Miao Project Version 2.1.5 Update Notes
- 修复：搜索报错

# Miao Project Version 2.1.4 Update Notes
- 修复：刷新回弹问题

# Miao Project Version 2.1.3 Update Notes
- 修复：tvOS 16 以下的用户，网络请求可能会出现API校验错误
- 修复：请求鉴权失败，将删除全部的登录信息，请重新登录
- 修复：番剧更新为新的banner类型

# Miao Project Version 2.1.2 Update Notes
- 新增：App Icon 切换
- 修复：追番接口变更
- 修复：某些情况下弹出错误HUD可能导致应用崩溃
- ⚠️  本次更新将会强制登出所有登录状态，请重新登录

# Miao Project Version 2.1.1 Update Notes
- 紧急修复：扫码登录手机端无法点击确认
- 修复：「过滤超过60帧的视频」导致视频无法播放

# Miao Project Version 2.1.0 Update Notes
- 新增：更换新 icon
- 新增：更换新的置顶图
- 新增：番剧选集播放页切换（下一个EP）
- 新增：字幕端口切换
- 新增：播放器内部调整弹幕区域
- 新增：弹幕描边设置
- 新增：热门匿名模式设置
- 修复：视频简介超出边界
- 优化：倍速播放在 tvOS 16.2 之后已经正常
- 优化：倍速播放增加 1.75，2.0 选项
- 优化：默认关闭「匹配视频动态范围和帧率」
- 优化：默认开启「过滤超过60帧的视频」

# Miao Project Version 2.0.3 Update Notes
- 新增：播放进度缩略图
- 修复：NowPlaying 停在0秒的问题
- 优化：视频加载速度
- 优化：修改视频缓冲策略
- 优化：默认开启「主CDN优先加载」

# Miao Project Version 2.0.2 Update Notes
- 新增：兼容 HDR 格式
- 新增：「设置」- 播放链接主CDN优先模式
- 优化：缩略图清晰度
- 修复：由于系统 BUG，tvOS 16 连接 HomePod 时，倍速功能将失效

# Miao Project Version 2.0.1 Update Notes
- 新增：登陆页进度提示
- 修复：新注册用户无法登陆的问题
- 修复：多用户多设备切换时同步数据导致冲突，改为本地保存选中的用户
- 修复：番剧未开播，点击播放导致崩溃

# Miao Project Version 2.0.0 Update Notes
- 新增：重新开放激活通道，新激活通道允许6个iCloud调用激活

# Miao Project Version 1.1.6 Update Notes
- 新增：暂时关闭激活入口
- 新增：部分番剧支持跳过OP/ED
- 优化：大幅减少程序需要的内存占用
- 修复：视频详情页继续播放可能发生崩溃

# Miao Project Version 1.1.5 Update Notes
- 新增：FLAC音频支持
- 新增：二维码分享
- 优化：视频点击继续播放
- 修复：视频记录不显示已完成
- 修复：竖屏直播画面出现裁切
- 修复：tvOS 16 详情页推荐点击闪退
- 修复：tvOS 16 详情页简介内容越界
- 修复：tvOS 16.1 播放报错

# Miao Project Version 1.1.4 Update Notes
- 新增：flv直播播放器
- 优化：不再默认选择AI生成的字幕
- 优化：默认在支持HEVC硬解设备上开启HEVC优先设置
- 修复：杜比视界部分编码无法打开
- 实验室：播放链接优化（播放链接预解析 / 播放链接重写）

# Miao Project Version 1.1.3 Update Notes
- 新增：自动刷新机制
- 新增：港澳台番剧特殊标记
- 优化：播放链接选择器
- 优化：5秒内的播放记录，不会触发「继续播放」
- 修复：视频详情页 - 推荐视频，点击后页面滚动问题

# Miao Project Version 1.1.2 Update Notes
- 修复：无法观看直播

# Miao Project Version 1.1.1 Update Notes
- 新增：影视推荐
- 新增：错误重试页面
- 优化：更新番剧推荐接口
- 优化：弹幕速度调节
- 实验室：全局倍速播放
- 实验室：匹配动态范围和帧率

# Miao Project Version 1.1 Update Notes
- 新增：详情页视频合集
- 新增：播放页面，查看视频调试信息
- 新增：查看 iCloud 状态
- 新增：清空 iCloud 中所有账户信息
- 优化：更新排行榜的API
- 优化：更新应用内操作说明 
- 优化：CDN排序
- 优化：番剧连续播放调整为播放完跳转
- 修复：倍速播放暂停后被重置
- 修复：过滤60帧以上视频的功能某些情况下失效

# Miao Project Build 69 Update Notes
- 更新应用图标和置顶图

# Miao Project Build 68 Update Notes
- 修复：某些用户硬币数超过上限导致崩溃

# Miao Project Build 67 Update Notes
- 新增：番剧详情页显示剧集是否需要会员等额外信息
- 新增：视频详情页，相关推荐，提供多种弹出方式
- 新增：「我的追番」入口
- 优化：调整「切换账户」的位置
- 修复：某些个人页面可能会引发崩溃
- 修复：列表页刷新的时候，可能产生多余的跳动
- 修复：「我的」页面，从下级页面返回，丢失选中效果

# Miao Project Build 66 Update Notes
- 修复：某些用户登陆闪退的问题

# Miao Project Build 65 Update Notes
- 注意⚠️：本次更新会清空激活状态 / 个人设置 / 账户信息，用户需要重新激活登陆
- 新增：多账户系统，并且支持iCloud同步，最多添加5个Profile
- 新增：通过iCloud同步设置信息
- 新增：通过iCloud同步 App 激活状态
- 修复：「我的」页面可能发生奔溃的问题

# Miao Project Build 64 Update Notes
- 修复：动态页加载更多，可能发生崩溃

# Miao Project Build 63 Update Notes
- 修复：更新 tvOS 15.4 后，列表无法流畅滑动的问题
- 新增：设置 -「过滤超过60帧的视频」，开启后可能会改善某些视频丢帧导致无法正常观看的问题，请仔细阅读说明和副作用，仅建议有此问题的用户自行尝试

# Miao Project Build 57 Update Notes
- 新增：显示具体播放错误
- 修复：播放资源502报错，可能导致应用崩溃的问题

# Miao Project Build 56 Update Notes
- 新增：设置页面显示版本信息
- 修复：番剧自动播放导致弹幕开关失效的问题
- 修复：视频播放记录少一秒的问题
- 修复：番剧自动播放下一集可能包含上一集弹幕的问题

# Miao Project Build 55 Update Notes
- 新增「番剧连续播放」开关设置
- 修复番剧连续播放，手动点击播放后，自动退出的问题

# Miao Project Build 54 Update Notes
- 重构播放资源加载流程
- 新增番剧自动播放下一集
- 修复了播放界面Loading过程中无法退出的问题

# Miao Project Build 53 Update Notes
- 修复了收藏夹「查看全部」按钮无法显示的问题
- 修复了某些剧集缺少数据，导致追剧列表报错的问题

# Miao Project Build 52 Update Notes
- 也许优化了 Apple TV HD 的播放体验，未经过测试
- 修复了某些视频播放过程中，无法退出页面，遥控器失去响应的问题

# Miao Project Build 51 Update Notes
- 「仅加载HEVC」修改为「优先加载HEVC」策略，并修复了某些资源没有压制HEVC导致视频无法播放的问题

# Miao Project Build 50 Update Notes
- 新增「仅加载HEVC」选项，开启后只会加载HEVC（H265）资源，相同画质下，占用的带宽会降低一半左右
- 也许现在 Dolby Atmos 可以点亮图标了，未经过测试

# Miao Project Build 49 Update Notes
- 支持杜比视界（Dolby Vision 8.4 + HLG 或者 Dolby Vision 5 + PQ）
- 支持杜比全景声（Dolby Digital Plus with Dolby Atmos）
- 现在可以正确匹配视频的动态范围和帧率了
- 新增「加载杜比视界」设置

# Miao Project Build 48 Update Notes
- 移除关于 CDN 的屏蔽，因为部分地区的用户只能收到 szbdyd 的播放链接，屏蔽之后无法正常播放

# Miao Project Build 47 Update Notes
- 更新屏蔽的 CDN 列表，屏蔽 szbdyd

# Miao Project Build 46 Update Notes
- 支持8K分辨率视频播放
- 更新番剧接口，现在部分番剧支持4K分辨率啦！
- 移除「首选分辨率」设置

# Miao Project Build 45 Update Notes
- 推荐页可以显示直播内容
- 更新收藏接口，并支持了收藏订阅功能
- 修复了收藏夹中的番剧不显示的问题
- 修复了搜索功能在某些情况下数据解析错误

# Miao Project Build 44 Update Notes
- 修复了直播弹幕开关消失的问题

# Miao Project Build 43 Update Notes
- 修复了排行榜科技区部分数据解析错误

# Miao Project Build 42 Update Notes
- 项目贡献者可以使用 Mod 组的特殊角标
- 自动去除输入的激活码里所有的空格
- 优化了弹幕的生成效率
- 修复了部分视频详情中包含未上映番剧导致无法打开的问题
- 修复了未上映番剧封面不显示的问题
- 修复了 AI 生成的中文字幕无法自动选中的问题

# Miao Project Build 41 Update Notes
- 更新 Top Shelf，并支持深色模式

# Miao Project Build 40 Update Notes
- 新增直播搜索功能
- 新增直播清晰度选择功能，最高画质卡顿的用户，可自行降低画质

# Miao Project Build 36 Update Notes
- 修复了音频切片信息错误导致无法播放的问题

# Miao Project Build 35 Update Notes
- 这次应该真的修复了码率降低之后不升高的问题

# Miao Project Build 34 Update Notes
- 可能改善了 HLS 降低分辨率的情况
- 修复了由于 SIDX 无法加载，导致视频一直在 Loading 的问题
- 播放器现在可以正确匹配视频帧率（仅限支持的帧率），播放开始/结束时，出现黑屏时正常情况

# Miao Project Build 33 Update Notes
- 新增「设置」-「弹幕显示区域」
- 拓展弹幕不透明的选择范围
- 修复了弹幕重叠的问题
- 添加章节的封面占位图

# Miao Project Build 32 Update Notes
- 新增 UGC 视频分段章节
- 新增直播弹幕
- 新增直播页弹幕显示 / 隐藏设置（tvOS 15 限定）
- 修复了直播页退出之后声音延迟释放的问题

# Miao Project Build 31 Update Notes
- 支持观看直播，直播弹幕的功能还在制作中
- 允许查看关注UP主的直播状态，这是第一个直播版本的唯一入口

# Miao Project Build 30 Update Notes
- 视频资源的CDN选择切换为黑名单模式
- 超长番剧允许直接展开所有剧集
- 修复了番剧页面非番剧的 Banner 进入报错的问题
- 隐藏搜索页出现的查看全部按钮（功能未支持）

# Miao Project Build 29 Update Notes
- UP 主详情页，新增按播放数量排序
- 弹幕字号允许设置为 42 pt
- 修复了「动态」、「历史记录」中可能出现的数据解析错误
- 修复了登录后，动态栏出现在错误的位置

# Miao Project Build 28 Update Notes
- 修复了海外用户无法正确加载过滤CDN的问题
- 更新「我的追番」的使用说明

# Miao Project Build 27 Update Notes
- 已撤回

# Miao Project Build 26 Update Notes
- 新增「我的追剧」，入口是和「我的追番」同一个页面
- 目前仅采用官方CDN，希望可以改善播放中可能会出现的卡顿
- 修复了无音轨的视频文件无法正常播放的问题

# Miao Project Build 25 Update Notes
- 让大家久等了，本次更新「番剧」模块终于上线了
- 修复了「热门」中无法正确进入番剧详情页的问题

# Miao Project Build 24 Update Notes
- 修复番剧由于不支持的音源，导致无法快进的问题

# Miao Project Build 23 Update Notes
- 修复「设置」-「仅加载最高分辨率」会将番剧清晰度锁死在最低的问题

# Miao Project Build 22 Update Notes
- 新增「设置」-「仅加载最高分辨率」，本设置是为了处理即使带宽足够，播放器也会降低分辨率的情况，请用户根据自己的情况自行开启
- 更新 App 内的「使用说明」
- 更新 tvOS 15 播放器展示的元数据信息
- 修复了播放器释放延迟的问题

# Miao Project Build 21 Update Notes
- 新增播放页弹幕显示 / 隐藏设置（tvOS 15 限定）
- 新增播放页倍速播放（tvOS 15 限定）倍速播放可能会导致部分视频画面掉帧，目前还没找到解决方法

# Miao Project Build 20 Update Notes
- 修复了 tvOS 15 Beta 无法加载弹幕的问题，本次修复仅使用其他方法避过了原来问题，网络请求缓慢时可能导致弹幕加载不出或者加载延迟

# Miao Project Build 19 Update Notes
- 修复了部分视频由于没有 Tag 导致数据解析错误的问题

# Miao Project Build 18 Update Notes
- 支持显示外挂字幕
- 允许设置弹幕屏蔽等级

# Miao Project Build 17 Update Notes
- 修复了负时间线弹幕导致播放器崩溃的问题

# Miao Project Build 16 Update Notes
- 修复弹幕属性更新导致的解析错误
- 修复部分用户点击播放时，解析SIDX出错导致的崩溃问题

# Miao Project Build 15 Update Notes
- 更新用户 Token 刷新机制
- 修复了视频第一秒弹幕会多次出现在屏幕的问题
- 集成 Flurry 收集崩溃信息

# Miao Project Build 14 Update Notes
- 更新用户授权机制（番剧相关）
- 修复了部分番剧不能正常播放的问题
- 修复了部分用户播放视频直接崩溃的问题
- 动态和UP主详情页显示投稿时间
- 注：本次更新后，需要用户重新登录

# Miao Project Build 13 Update Notes
- 新增 UGC 视频的点赞、投币、收藏操作
- 新增「视频详情页、UP主详情页」关注UP主的功能
- 新增查看「我的关注」列表
- 修复搜索结果中，电影无法点击的问题

# Miao Project Build 12 Update Notes
- 支持视频资源切片
- 支持中文系统 UI
- 恢复「继续播放」功能
- 修复了快进等待时间过长的问题
- 修复了电影级长视频播放中出现崩溃的问题
- 修复了HLS自动切换分辨率过程中，出现视频重置的情况

# Miao Project Build 11 Update Notes
- 修复了部分用户播放视频导致应用崩溃的问题

# Miao Project Build 10 Update Notes
- 支持 tvOS 原生播放器
- 根据网络带宽自动选择分辨率
- 支持原生播放器手势
- 修复 4K 高码率视频播放时出现卡顿，声画不同步的情况

* 本次更新由于没有支持视频切片，暂时停用了「继续播放」功能
* 快进的时候也可能出现较长时间的等待

# Miao Project Build 9 Update Notes
- 新增「设置 - 弹幕透明度」
- 新增「设置 - 弹幕字号」
- 修复无历史记录时报错的问题

# Miao Project Build 8 Update Notes
- 新增「设置 - 首选分辨率」

# Miao Project Build 7 Update Notes
- 新增操作提示

# Miao Project Build 6 Update Notes
- 不完美适配 AirPlay，播放过程中切换可能会导致声画不同步
- 未登录状态下允许修改播放器设置

# Miao Project Build 5 Update Notes
- 优化应用启动速度
- 优化内存占用
- 播放状态下，自动隐藏进度条
- 修复「排行榜 / 我的」页面返回出现闪屏的情况
- 深色弹幕使用浅色边框
- 更新热门模块API
- 优化登录页面二维码

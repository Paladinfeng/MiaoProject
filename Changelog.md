# Miao Project Build 40 Update Notes
- 新增直播搜索功能
- 新增直播清晰度选择功能，最高画质卡顿的功能，可自行降低画质

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

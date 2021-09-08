收录一些大厂技术分享、实用一直维护的开源库、面试题

## 目录

* [Github开源库](#Github开源库)
* [大厂分享](#大厂分享)
    * [腾讯](#腾讯)
    * [字节跳动](#字节跳动)
    * [支付宝](#支付宝)
    * [百度](#百度)
    * [搜狐](#搜狐)
    * [携程](#携程)
    * [滴滴](#滴滴)
    * [网易](#网易)
    * [美团](#美团)
    * [有赞微商城](#有赞微商城)
    * [京东](#京东)
    * [饿了么](#饿了么)
    * [高德](#高德)
    * [即刻](#即刻)
    * [天天P图攻城狮](#天天P图攻城狮)
    * [爱奇艺](#爱奇艺)   
    * [知乎](#知乎)
    * [天猫精灵技术](#天猫精灵技术)
    * [花椒技术](#花椒技术)
    * [携程技术](#携程技术)
    * [西瓜技术](#西瓜技术)
    * [闲鱼技术](#闲鱼技术)
    * [猫眼技术团队](#猫眼技术团队)
    * [快手技术团队](#快手技术团队)
    * [咕咚移动技术团队](#咕咚移动技术团队) 
    * [有赞](#有赞)
    * [贝壳产品技术](#贝壳产品技术)
    * [淘系技术](#淘系技术)
    * [vivo互联网技术](#vivo互联网技术)
    * [自如大前端团队](#自如大前端团队)     
* [实用工具](#实用工具)
* [Gradle相关](#Gradle相关)
* [课程](#课程)
* [面试相关](#面试相关)
* [性能优化](#性能优化)
* [知识整理](#知识整理)

### Github开源库
* 开源一个自用的Android IM库 https://www.jianshu.com/p/00ba0ac2fc96

    这是一篇非常棒的文章，作者从事直播、即时通讯、短视频等项目3，4年，有这样经历的作者来开源一个IM库是可遇不可求的。

    项目地址： https://github.com/FreddyChen/NettyChat

    文章包含：

    * Protobuf序列化

    * TCP拆包与粘包

    * 长连接握手认证

    * 心跳机制

    * 重连机制

    * 消息重发机制

    * 读写超时机制

    * 离线消息

    * 线程池

* Leetcode算法图解 [https://github.com/MisterBooo/LeetCodeAnimation](https://github.com/MisterBooo/LeetCodeAnimation)

* 卓高级UI代码整理和博客代码Demo [https://github.com/zincPower/UI2018](https://github.com/zincPower/UI2018)

* 在编译生成APK期间，将需要翻译的layout翻译生成对应的java文件 [https://github.com/iReaderAndroid/X2C](https://github.com/iReaderAndroid/X2C)

* Flutter系列教程 [https://github.com/CarGuo/GSYGithubAppFlutter](https://github.com/CarGuo/GSYGithubAppFlutter)

    * [Dart 语言和 Flutter 基础](https://juejin.im/entry/5b631e3e51882519861c2ef1)
    * [快速开发实战篇](https://juejin.im/entry/5b685bd4e51d451994602cae)
    * [打包填坑篇](https://juejin.im/entry/5b6fd5ee6fb9a009d36a4104)
    * [Redux、主题、国际化](https://juejin.im/post/5b79767ff265da435450a873 )
    * [深入探索](https://juejin.im/post/5bc450dff265da0a951f032b )
    * [深入Widget原理](https://juejin.im/post/5c7e853151882549664b0543 )
    * [深入布局原理](https://juejin.im/post/5c8c6ef7e51d450ba7233f51)
    * [实用技巧与填坑](https://juejin.im/post/5c9e328251882567b91e1cfb)
    * [深入绘制原理](https://juejin.im/post/5ca0e0aff265da309728659a)
    * [深入图片加载流程](https://juejin.im/post/5cb1896ce51d456e63760449)
    * [全面深入理解Stream](https://juejin.im/post/5cc2acf86fb9a0321f042041)
    * [全面深入理解状态管理设计](https://juejin.im/post/5cc816866fb9a03231209c7c)
    * [全面深入触摸和滑动原理](https://juejin.im/post/5cd54839f265da03b2044c32)

* 整合第三方登录的工具 [https://github.com/zhangyd-c/JustAuth](https://github.com/zhangyd-c/JustAuth)

* 用于给 view 添加阴影 [https://github.com/SilenceDut/fpsviewer](https://github.com/SilenceDut/fpsviewer)

* Android 开源项目解析 [https://github.com/sucese/android-open-framework-analysis](https://github.com/sucese/android-open-framework-analysis)

* Android学习路线图 [https://github.com/mobile-roadmap/android-developer-roadmap](https://github.com/mobile-roadmap/android-developer-roadmap)

* Android架构合集(一) https://github.com/CameloeAnthony/AndroidArchitectureCollection](https://github.com/CameloeAnthony/AndroidArchitectureCollection)

* Android架构合集(二) [https://github.com/Juude/Awesome-Android-Architecture](https://github.com/Juude/Awesome-Android-Architecture)

* 获取手机的全部硬件信息 [https://github.com/guxiaonian/MobileInfo](https://github.com/guxiaonian/MobileInfo)

* 表情包大全 [https://github.com/zhaoolee/ChineseBQB](https://github.com/zhaoolee/ChineseBQB)

* 字节跳动开源一系列插件 [https://github.com/bytedance/ByteX](https://github.com/bytedance/ByteX)
    -   access-inline-plugin（access方法内联）
    -   shrink-r-plugin（R文件瘦身和无用资源检查）
    -   closeable-check-plugin（文件流的close检查）
    -   const-inline-plugin（常量内联）
    -   field-assign-opt-plugin（优化多余赋值指令）
    -   getter-setter-inline-plugin （getter和setter方法内联）
    -   method-call-opt-plugin（干净地删除某些方法调用，如Log.d）
    -   coverage-plugin（线上代码覆盖率）
    -   refer-check-plugin（检查是否有调用不存在的方法和引用不存在的字段）
    -   serialization-check-plugin（序列化检查）
    -   SourceFileKiller（删除SourceFile和行号属性）

* 百度对外开源文章详情页 webview+recyclerview+一些原生控件联动效果 [https://github.com/baiduapp-tec/ELinkageScroll](https://github.com/baiduapp-tec/ELinkageScroll)
* Android 逆向攻防相关的话题(一) https://github.com/Hack-with-Github/Awesome-Hacking
* Android 逆向攻防相关的话题(二) https://github.com/carpedm20/awesome-hacking 
* 一个hook库 [https://github.com/eleme/lancet](https://github.com/eleme/lancet)
* 一个算法仓库 [https://github.com/labuladong/fucking-algorithm](https://github.com/labuladong/fucking-algorithm)
* 爱奇艺开源德xCrash [https://github.com/iqiyi/xCrash](https://github.com/iqiyi/xCrash)
* 研发效率工具 奇艺开源 [https://github.com/iqiyi/Lens](https://github.com/iqiyi/Lens)
* 研发效率工具 饿了么开源 [https://github.com/eleme/UETool](https://github.com/eleme/UETool)
* 依赖库查看版本 [https://github.com/wuyr/GoogleLibraryVersionQuerier](https://github.com/wuyr/GoogleLibraryVersionQuerier)
* 阿里路由框架 [https://github.com/alibaba/ARouter](https://github.com/alibaba/ARouter)
* Bilibi路由框架 [https://github.com/bilibili/BRouter](https://github.com/bilibili/BRouter)
* 美团路由框架 [https://github.com/meituan/WMRouter](https://github.com/meituan/WMRouter)
* 开源内存快照裁剪压缩压缩工具  [https://github.com/bytedance/tailor](https://github.com/bytedance/tailor)
* 字节跳动开源 Android PLT hook 方案 bhook [https://github.com/bytedance/bhook](https://github.com/bytedance/bhook)
* 字节跳动开源移动研发工具链 MBox [https://github.com/mboxplus/mbox](https://github.com/mboxplus/mbox)
* 移动端操作行为的工具 [https://github.com/didi/DiDiPrism](https://github.com/didi/DiDiPrism)
* Dokit For Flutter [https://github.com/didi/DoraemonKit/tree/master/Flutter](https://github.com/didi/DoraemonKit/tree/master/Flutter)
* 好用的Android Studio插件集合 [https://github.com/getActivity/StudioPlugins](https://github.com/getActivity/StudioPlugins)
* Android Signature V2 Scheme签名下的新一代渠道包打包神器 [https://github.com/Meituan-Dianping/walle](https://github.com/Meituan-Dianping/walle)

### 大厂分享
#### 腾讯
* [腾讯 matrix ](https://github.com/Tencent/matrix) Matrix 是一款微信团队研发并日常使用的应用性能接入框架。 Matrix 通过接入各种性能监控方案，对性能监控项的异常数据进行采集和分析，输出相应的问题分析、定位与优化建议，从而帮助开发者开发出更高质量的应用
* [腾讯 QMUI ](https://github.com/Tencent/QMUI_Android)
* [对字符串匹配算法的一点理解](https://mp.weixin.qq.com/s/aC7XEsz3eGSWj3oWHpQE7w)
* [腾讯 Shadow](https://github.com/Tencent/Shadow)
* [腾讯 Bugly：动态下发 so 库在 Android APK 安装包瘦身方面的应用](https://mp.weixin.qq.com/s/X58fK02imnNkvUMFt23OAg)
* [QQ音乐Android客户端Web页面通用性能优化实践](https://juejin.im/post/5f10446af265da230d324813)
* [底弄懂浏览器缓存策略](彻底弄懂浏览器缓存策略)
* [QQ音乐Android编译提速之路](https://mp.weixin.qq.com/s/9vbt73d7nIbTbXVyyRAH3A)
* [全民k歌适配arm64-v8a方案](https://mp.weixin.qq.com/s/SHFqS3RKKlprijlf6hL09w)
* [Android的离奇陷阱 — 设置线程优先级导致的微信卡顿惨案](https://mp.weixin.qq.com/s/oLz_F7zhUN6-b-KaI8CMRw)
* [介绍一种性能较好的 Android native unwind 技术](https://mp.weixin.qq.com/s/g4RWAS3vNjFu2IoU9OxRaQ)
* [Android全量编译加速——（透明依赖）](https://mp.weixin.qq.com/s/tK9z6QjMvMeakpTHdTBBBg)
* [全民K歌内存篇1——线上监控与综合治理](https://mp.weixin.qq.com/s/KWaueLMZwwLSjGGJya6qFA)
* [全民K歌内存篇2——虚拟内存浅析](https://mp.weixin.qq.com/s/pbLLLCXlkz6gp9ps65rMYA)
* [全民K歌内存篇3——native内存分析与监控](https://mp.weixin.qq.com/s/0cF5Q6_LXrkLAdjkXIwrVQ)
* [微信Android客户端的卡顿监控方案](https://mp.weixin.qq.com/s/3dubi2GVW_rVFZZztCpsKg)
* [微信Android客户端的ANR监控方案](https://mp.weixin.qq.com/s/fWoXprt2TFL1tTapt7esYg)
* [快速缓解 32 位 Android 环境下虚拟内存地址空间不足的“黑科技”](https://mp.weixin.qq.com/s/ZbFQQ5AVsHy0YL_kKMAiYA)
* [Android App 电量统计原理与优化](https://mp.weixin.qq.com/s/9Pi-rHj-G2omqu3dCtuuZA)
* [线程：“你可能把握不住”—— Android 平台下线程导致的内存问题](https://mp.weixin.qq.com/s/tEhMs2xa05E8aAvynXMpSw)
* [全民K歌折叠屏适配探索](https://mp.weixin.qq.com/s/2rbQOsNlBqJ24MKyyg0b8A)
* [MOO音乐的Flutter实战总结之内存治理（上）](https://mp.weixin.qq.com/s/v4Cdheo-ZBHGuAQd12XEMA)
* [MOO音乐的Flutter实战总结之内存治理（中）](https://mp.weixin.qq.com/s/njtOELCVZQpo9e29H9ykjA)
* [MOO音乐的Flutter实战总结之内存治理（下）](https://mp.weixin.qq.com/s/qxHip7Y50yPcqui6dudK2g)
#### 字节跳动
* [二维码扫描优化](https://mp.weixin.qq.com/s/MT55JhiYcYiSy5pDQaHXwg)
* [连载 | 深入理解Gradle框架之一：Plugin, Extension, buildSrc](https://mp.weixin.qq.com/s/mDCTtQZb6mhWOFAvLYKBSg)
* [连载 | 深入理解gradle框架之二：依赖实现分析](https://mp.weixin.qq.com/s/WQCqUaYDPHDIjUHlxjRIkw)
* [开源 | Scene：Android 开源页面导航和组合框架](https://mp.weixin.qq.com/s/KKv8oj-ZspCIUTYwlCC2VQ) 开源地址：[https://github.com/bytedance/scene ](https://github.com/bytedance/scene )
* [抖音BoostMultiDex优化实践：Android低版本上APP首次启动时间减少80%](https://mp.weixin.qq.com/s/ECS83wzApgwisqOwZFIqTg)
* [抖音BoostMultiDex优化实践：Android低版本上APP首次启动时间减少80%（二）](https://mp.weixin.qq.com/s/ILDTykAwR0xIkW-d1YzRHw)
* [抖音包大小优化-资源优化](https://mp.weixin.qq.com/s/xxrvRKXXDquJaezjrOlLwA)
* [开源 | BoostMultiDex：挽救 Android Dalvik 机型APP升级安装体验](https://mp.weixin.qq.com/s/0gtkc7IQdhKjFxrHCuNZwQ)
* [另类 BadTokenException 问题分析和解决](https://mp.weixin.qq.com/s/DmN9sN_MdugpVm73vnVqww)
* [今日头条 Android '秒' 级编译速度优化](https://mp.weixin.qq.com/s/e1L6gB_s5H38unSfhf4c6A)
* [Android Camera内存问题剖析](https://mp.weixin.qq.com/s/-oaN-bOqHDjN30UP1FMpgA)
* [抖音 Android 性能优化系列：Java 内存优化篇](https://mp.weixin.qq.com/s/AQI2S2oK7HFDs9lH-nsx5g)
* [今日头条 ANR 优化实践系列 - 设计原理及影响因素](https://mp.weixin.qq.com/s/ApNSEWxQdM19QoCNijagtg)
* [今日头条 ANR 优化实践系列 - 监控工具与分析思路](https://mp.weixin.qq.com/s/_Z6GdGRVWq-_JXf5Fs6fsw)
* [今日头条 ANR 优化实践系列 - 告别 SharedPreference 等待](https://mp.weixin.qq.com/s/kfF83UmsGM5w43rDCH544g)
* [今日头条 ANR 优化实践系列 - Barrier 导致主线程假死](https://mp.weixin.qq.com/s/OBYWrUBkWwV8o6ChSVaCvw)
* [今日头条 ANR 优化实践系列分享 - 实例剖析集锦](https://mp.weixin.qq.com/s/4-_SnG4dfjMnkrb3rhgUag)
* [字节跳动安全合规检测技术之Android篇](https://mp.weixin.qq.com/s/3LUieGAu6rNh27naB9klmA)
* [西瓜视频稳定性治理体系建设二：Raphael 原理及实践](https://mp.weixin.qq.com/s/RF3m9_v5bYTYbwY-d1RloQ)
* [西瓜视频稳定性治理体系建设三：Sliver 原理及实践](https://mp.weixin.qq.com/s/LW3eMK9O2tfFtZcu5eqitg)
* [Flutter 疑难杂症系列：键盘原理及常见问题解决方案](https://mp.weixin.qq.com/s/snU-mNlmEnOUHw3I-DrJ_w)
* [Flutter 疑难杂症系列：实现中文文本的垂直居中](https://mp.weixin.qq.com/s/34OvLqsqJLj-jt2DqCmcPQ)
* [西瓜卡顿 & ANR 优化治理及监控体系建设](https://mp.weixin.qq.com/s/2sjG5qkrUNQsI0jEsnh4kQ)
* [抖音Android无障碍开发知识总结](https://mp.weixin.qq.com/s/2JBMfaV4oa0XLrJ-55sPdg)
* [一文读懂字节跳动自研移动研发工具链 MBox](https://mp.weixin.qq.com/s/5_IlQPWnCug_f3SDrnImCw)
#### 支付宝
* [支付宝客户端架构解析：Android 客户端启动速度优化之「垃圾回收」](https://mp.weixin.qq.com/s/ePjxcyF3N1vLYvD5dPIjUw)
* [支付宝 App 构建优化解析：通过安装包重排布优化 Android 端启动性能](https://mp.weixin.qq.com/s/79tAFx6zi3JRG-ewoapIVQ)
* [支付宝 App 构建优化解析：Android 包大小极致压缩](https://mp.weixin.qq.com/s/_gnT2kjqpfMFs0kqAg4Qig)
* [解决支付宝包体积优化的遗留问题：运行时获取dexpc](https://mp.weixin.qq.com/s/BbfwyhNiPK_tPCs2lN5iQg)
#### 百度
* [Android H5首屏优化实践](https://mp.weixin.qq.com/s/AqQgDB-0dUp2ScLkqxbLZg)
* [百度App组件化之路](https://mp.weixin.qq.com/s/P-vREnrw4xGyhiugpzB-1Q)
* [百度App网络深度优化系列《三》弱网优化](https://mp.weixin.qq.com/s/BIfya6eVaWZW9ZEVz8RRcg)
* [一种简单优雅的TextView行间距适配方案](https://mp.weixin.qq.com/s/xQ5I0omWC8-6W4RAYl0hkA)
* [Gradle 与 Android 构建入门](https://mp.weixin.qq.com/s/HdCrhiY3VSsEjmu0FKLlyg)
#### 搜狐
* [深入理解Flutter多线程](https://mp.weixin.qq.com/s/0dhV1FG0W7L45sCN49yLnQ)
#### 携程
* [干货 | 从智行 Android 项目看组件化架构实践](https://mp.weixin.qq.com/s/_v2NMSQmZA9HLVq03AzbWQ)
#### 滴滴
* [滴滴开源 DoraemonKit：一款像哆啦A梦般全能的App研发工具](https://github.com/didi/DoraemonKit )
* [滴滴 booster](https://github.com/didi/booster) Booster 是专门为移动应用而设计的简单易用、轻量级、功能强大且可扩展的质量优化工具包，其通过动态发现和加载机制提供可扩展的能力，换言之，Booster 也是一个移动应用质量优化框架。
#### 网易
* [网易严选技术专家解读ABTest 设计与原理](https://www.jianshu.com/p/4e7a271cd54a)
* [AOP技术在客户端的应用与实践](https://mp.weixin.qq.com/s/WRrpC30g4r_AyJa6BPNf8Q)
* [网易大数据|互联网产品决策秘笈: AB测试](https://mp.weixin.qq.com/s/NnPoAZirm8ZCF2B2Hw2kZA)
* [网易新闻客户端 H5 秒开优化](https://mp.weixin.qq.com/s/AV2SwFfwwJH7xyrIBJemgw)
* [NRTripod：App线上风险控制系统](https://mp.weixin.qq.com/s/QWEfjLDmZgWUyWrjW1zNPw)
* [网易新闻构建优化：如何让你的构建速度“势如闪电”？](https://mp.weixin.qq.com/s/2Y8-NqVPdOqtLGZDMrhGyQ)
* [Android 开发，如何写出符合规范的异常处理代码](https://mp.weixin.qq.com/s/SOTCVjJ4-V2cNT8lqWFUDA)
* [AGP 升级之旅](https://mp.weixin.qq.com/s/ccdY77Ys44Hw5E20QbAxdg)
#### 美团
* [漫谈美团APP对Crash的治理之路](https://www.jianshu.com/p/923a24755456)
* [Android静态代码扫描效率优化与实践](https://mp.weixin.qq.com/s/cY6rUrrjYRaIV--UzjiUgA)
* [Probe：Android线上OOM问题定位组件](https://mp.weixin.qq.com/s/tO1yxFs2qNQlQ2bJ8vGzQA)
* [移动端UI一致性解决方案](https://mp.weixin.qq.com/s/oq7ylltdRIdJuSlL7EIiNA)
* [设计稿（UI视图）自动生成代码方案的探索](https://mp.weixin.qq.com/s/rwl6rX_cGTtVYkVDy94bQQ)
#### 有赞微商城
* [有赞微商城-Android组件化方案](https://tech.youzan.com/you-zan-yi-dong-androidzu-jian-hua-fang-an/)
#### 京东
* [任意URL跳转漏洞修复与JDK中getHost()方法之间的坑](https://mp.weixin.qq.com/s/Lj7FDZj_ke5djzgJNwipbQ)
* [LayoutInflater原理分析与复杂布局优化实践](https://mp.weixin.qq.com/s/1Zk4on7WTF7nrBm2EsYgLg)
* [JAVA原生线程池源码解析及使用建议](https://mp.weixin.qq.com/s/t5BXaLF5bYVuza_9xTNTtA)
* [京东APP中Flutter探索及优化](https://mp.weixin.qq.com/s/alglGvnNKIzr7f8SwRZucA)
* [AOP技术在APP开发中的多场景实践](https://mp.weixin.qq.com/s/yWZew3XefM6Rl0glD-UVXg)
#### 饿了么
* [你需要知道的那些 Java 字节码知识](https://juejin.im/post/5ca18229f265da307261f7b6)
* [Java动态编程初探](https://juejin.im/post/5cdcd37151882520226ce13c)
#### 高德
* [Android Native 内存泄漏系统化解决方案](https://mp.weixin.qq.com/s/1Vb3qk6H-2CekgPQzCni-g)
#### 即刻
* [ConstraintLayout 介绍与实战 ](https://juejin.im/post/5ce3b68b518825336e0a5190)
#### 天天P图攻城狮
* [例说 Constraint Layout（三）—— 性能测评](https://mp.weixin.qq.com/s/mVOcE7KBZu9ZjlNf8qsJrA)
* [Android P之Smart Linkify](https://mp.weixin.qq.com/s/kXge9_oBjt8qG766lAIdnw)
#### 爱奇艺
* [干货|安卓APP崩溃捕获方案——xCrash](https://mp.weixin.qq.com/s/bJKvrfO6B8NTGWySpeCYgA)
* [Android篇 | 爱奇艺App启动优化实践分享](https://mp.weixin.qq.com/s/HfNYsv1-CHTkb-jG__1P0Q)
* [二维码扫描优化及爱奇艺App的实践](https://mp.weixin.qq.com/s/tB7htYzrmP0wGUFCkCvBUw)
* [爱奇艺App架构升级之路——64位适配探索与实践](https://mp.weixin.qq.com/s/0Za1VoPFxIHGRy4kPMVA-Q)
* [爱奇艺App架构升级之路——64位适配探索与实践](https://cloud.tencent.com/developer/news/677788)
* [如何在Android 8.0以下高效地复用图片？](https://mp.weixin.qq.com/s/wrvCa3YK0L8qX1ECQkrnug)
#### 知乎
* [知乎 Android 客户端三方库敏感代码扫描机制](https://www.jianshu.com/p/248ef6db02c5)

#### 天猫精灵技术
* [史上最全Android渲染机制讲解（长文源码深度剖析）](https://mp.weixin.qq.com/s/0OOSmrzSkjG3cSOFxWYWuQ)
* [天猫精灵App首页信息流是怎样实现的](https://mp.weixin.qq.com/s/Goob5z-cRC8S04mBkXn7CA)

#### 花椒技术
* [花椒Android端自动化测试实践](https://mp.weixin.qq.com/s/aaKTyZfk1fWfckUD_QIsFg)

#### 携程技术
* [携程Android 10适配踩坑指南](https://mp.weixin.qq.com/s/syAzZLYLmTC7AebICb22AQ)
* [全网最详！暗黑模式在 Trip.com App 的实践](https://mp.weixin.qq.com/s/oU13hMQ2MJIYZoJWC74EMQ)

#### 西瓜技术
* [AwCookieManager.nativeGetCookie crash 排查](https://mp.weixin.qq.com/s/YbotiMLHGz5fzLbF4CpPEA)
* [Android D8编译器“bug”导致Crash的问题排查](https://mp.weixin.qq.com/s/483_hesZalaGRPebzz5tPA)

#### 闲鱼技术
* [曾梦想 if-else 走天涯？看看“责任树模式”优化](https://mp.weixin.qq.com/s/BdSeTrjDCo9zW0Daxffb7Q)
* [闲鱼如何在2个月内实现Android启动速度翻倍的？](https://mp.weixin.qq.com/s/fYqU-Rd-CBcO1_xpDLeYFA)
* [关于闲鱼的ANR治理，我有几条心得...](https://mp.weixin.qq.com/s/WMmMTw-Ida2qQaqXb2IGWA)
#### 猫眼技术团队
* [一次线程OOM排查看线程使用注意事项](https://juejin.im/post/5f0d55a8e51d4534ac1e5968)

#### 快手技术团队
* [Flutter 上的内存泄漏监控](https://juejin.im/post/5ee748df5188251f8649a226)
* [快手客户端稳定性体系建设](https://juejin.im/post/6860014199973871624)
* [快手开源的高性能线上内存监控方案KOOM](https://github.com/KwaiAppTeam/KOOM)
* [卡死 App 的神秘字符串，究竟是何方神圣（上）](https://mp.weixin.qq.com/s/EOD6CuQS9wrGph_p3oRrKQ)
* [卡死 App 的神秘字符串，究竟是何方神圣（下）](https://mp.weixin.qq.com/s/lT24r_VxgC47o7WSiLSZtg)

#### 咕咚移动技术团队
* [项目创建了几百个线程，你要怎么优化？](https://juejin.im/user/2682464102255335/posts)

#### 有赞
* [有赞移动Crash平台建设](https://mp.weixin.qq.com/s/QJr3MyoUj__K6DjNvI1Asg)

#### 贝壳产品技术
* [贝壳APP Top Experience系列 | Android方法耗时统计工具](https://mp.weixin.qq.com/s/J9xaUKKfdqhpT0zxOogzhw)
* [一种按照library的维度进行Android包大小分析的方法和实践](https://mp.weixin.qq.com/s/vE4aOxQM136-gIgly1GUJQ)

#### 淘系技术
* [一个 Crash 引发的血案](https://mp.weixin.qq.com/s/Ij9gqqsVNwAOzAiIiDchbg)

#### vivo互联网技术
* [dex优化对Arouter查找路径的影响](https://mp.weixin.qq.com/s/9O4XckDXM-xSVSJkbvgO9g)
* [干货：ANR日志分析全面解析](https://mp.weixin.qq.com/s/TDtjQdOktLcUYec3ldhh5g)
* [Android客户端网络预连接优化机制探究](https://mp.weixin.qq.com/s/8bEb4kPKLK19jMN20Mcmkg)
* [Android系统Bitmap内存分配原理与优化](https://mp.weixin.qq.com/s/0hnmYOTwRkywh_Msr7MWIQ)
* [手把手教你实现Android编译期注解](https://mp.weixin.qq.com/s/Jv-bMq1MinQnficiNZVhcQ)
* [Android模块化开发实践](https://mp.weixin.qq.com/s/EF1tJj21iIRLLKixJC3nkA)

#### 自如大前端团队
* [自如客APP裸眼3D效果的实现](https://juejin.cn/post/6989227733410644005)
* [Android_增量更新(BSDiff)详解](https://juejin.cn/post/6991279283620544543)
* [深入理解内存泄漏](https://juejin.cn/post/6992508087336697887)
* [玩转ViewPager2以及在自如中的应用](https://juejin.cn/post/6998063057649811486)

### 实用工具
* Git的奇技和技巧 [https://github.com/git-tips/tips](https://github.com/git-tips/tips)
* 玩游戏一样学习Git [https://learngitbranching.js.org/](https://learngitbranching.js.org/)
* 开发效率提升：Mac生产力工具链推荐 [https://github.com/Louiszhai/tool](https://github.com/Louiszhai/tool)
* Mock你的数据，放个大招 [https://www.jianshu.com/p/654961493846](https://www.jianshu.com/p/654961493846)
* Android 代码搜索一 [https://cs.android.com/](https://cs.android.com/)
* Android 代码搜索二 [https://www.androidos.net.cn/sourcecode](https://www.androidos.net.cn/sourcecode)
* Android 代码搜索三 [http://aospxref.com/](http://aospxref.com/)

### Gradle相关
* [Gradle插件-基础篇](https://linxiaotao.github.io/2018/05/16/Gradle%E6%8F%92%E4%BB%B6-%E5%9F%BA%E7%A1%80%E7%AF%87/)
* [Gradle插件-提高篇](https://linxiaotao.github.io/2018/05/21/Gradle%E6%8F%92%E4%BB%B6-%E6%8F%90%E9%AB%98%E7%AF%87/)
* [带你实现自定义Gradle插件](https://juejin.cn/post/6844903978233233415)
* [从Gradle生命周期到自定义Task挂接到Build构建流程全解](https://zhuanlan.zhihu.com/p/387871046)
* [Android中Gradle原理以及机制深入分析](http://www.youkmi.cn/2020/01/01/android-zhong-gradle-yuan-li-yi-ji-ji-zhi-shen-ru-fen-xi/)


### 课程
#### 一些名校课程

* 浙江大学课程攻略共享计划 https://github.com/QSCTech/zju-icicles

* 清华大学计算机系课程攻略 https://github.com/PKUanonym/REKCARC-TSC-UHT

* 贵校课程资料整理 https://github.com/lib-pku/libpku

* 上海交通大学课程资料分享 https://github.com/CoolPhilChen/SJTU-Courses

#### Google 工程师中文演讲 | 深入了解 Flutter 的高性能图形渲染

https://www.bilibili.com/video/av48772383

PPT下载下载 https://go2url.cn/gdd-flutter-yuqian-slide

Google Flutter 团队的工程师 Yuqian Li 将为你介绍 Flutter 的高性能渲染原理，以及遇到 Flutter 性能相关问题的时候如何调试。

B站快要成为一个学习站点啦，不要忽视哟！

#### 计算机科学速成课（视频）

https://www.yuque.com/computer/crush-course

我们要学很多东西，但预先说明，我们 *不会* 教你怎么编程，我们会从高层次上纵览一系列计算机话题。

#### 字节跳动bytex 学习资料
https://github.com/bytedance/ByteX



### 面试相关
* 每天一道Android 面试题 https://github.com/Moosphan/Android-Daily-Interview
* 一个Android 面试题合集 https://github.com/MindorksOpenSource/android-interview-questions
* Android 复习资料汇总版 https://juejin.cn/post/6844903907047505934#heading-6
* 常见面试算法 https://juejin.cn/post/6844903889003642887#comment
* Awesome-Android-Interview https://github.com/JsonChao/Awesome-Android-Interview
* Android技术笔记 https://github.com/jeanboydev/Android-ReadTheFuckingSourceCode
* 涵盖Android知识点面试题算法等 https://github.com/hornhuang/android_interviews
* 程序员徐公笔记 https://github.com/gdutxiaoxu/AndroidGuide

### 性能优化
* 一个非常全面的关于性能工具的使用、Android App 优化知识、Android Framework 知识讲解，性能理论知识讲解博客网站 https://www.androidperformance.com
* Android 面试之必问性能优化 https://juejin.cn/post/6970613873040687141
* 深入探索 Android 包体积优化（匠心制作-上） https://juejin.cn/post/6844904103131234311#heading-56
* 深入探索 Android 包体积优化（匠心制作-下） https://juejin.cn/post/6872920643797680136


### 知识整理
* 一份涵盖大部分Java程序员所需要掌握的核心知识 [https://github.com/Snailclimb/JavaGuide](https://github.com/Snailclimb/JavaGuide)
* Java成长路线，但学到的不仅仅是Java [https://github.com/javagrowing/JGrowing](https://github.com/javagrowing/JGrowing)
* ZXBlog主要为算法和数据结构的开源库 [https://github.com/ZXZxin/ZXBlog](https://github.com/ZXZxin/ZXBlog)
* 可视化算法学习(一) [https://github.com/algorithm-visualizer/algorithm-visualizer](https://github.com/algorithm-visualizer/algorithm-visualizer)
* 可视化算法学习(二) [https://algorithm-visualizer.org/brute-force/bubble-sort](https://algorithm-visualizer.org/brute-force/bubble-sort) 
* RxJava2极速入门系列
    * [RxJava2极速入门——Rxjava理念与基础知识](https://blog.csdn.net/qq_29856589/article/details/88578579)
    * [RxJava2极速入门——Rxjava操作符详解之创建操作符](https://blog.csdn.net/qq_29856589/article/details/88743270)
    * [RxJava2极速入门——Rxjava操作符详解之转换操作符](https://blog.csdn.net/qq_29856589/article/details/88821849)
    * [RxJava2极速入门——Rxjava操作符详解之过滤操作符](https://blog.csdn.net/qq_29856589/article/details/89054897)
    * [RxJava2极速入门——Rxjava操作符详解之条件布尔操作符](https://blog.csdn.net/qq_29856589/article/details/89288057)
* 死磕Framework相关系列
    * [死磕Android_View工作原理你需要知道的一切](https://blog.csdn.net/xfhy_/article/details/90270630)
    * [死磕Android_Handler机制你需要知道的一切](https://blog.csdn.net/xfhy_/article/details/90347636)
    * [死磕Android_App 启动过程（含 Activity 启动过程）](https://blog.csdn.net/xfhy_/article/details/90679525)
    * [死磕Android_AOSP编译过程](https://blog.csdn.net/xfhy_/article/details/91649717)
    * [死磕Android_Service启动流程分析(一)](https://blog.csdn.net/xfhy_/article/details/91907411)
    * [死磕Android_Service绑定流程分析(二)](https://blog.csdn.net/xfhy_/article/details/92233730)
* 腾讯 Shadow
    * [Shadow为什么要求插件和宿主包名一致](https://juejin.im/post/5d13579cf265da1b957067af)
    * [Shadow的缺点介绍](https://juejin.im/post/5d13214cf265da1bc41462c1)
    * [Shadow解决Activity等组件生命周期的方法解析](https://juejin.im/post/5d15d9a06fb9a07ef71087ca)
    * [Shadow的跨进程设计与插件Service原理](https://juejin.im/post/5d1968545188255543342406)
    * [Shadow的全动态设计原理解析](https://juejin.im/post/5d1b466f6fb9a07ed524b995)
    * [Shadow解决插件和宿主有同名View的方法解析](https://juejin.im/post/5d1c2150e51d4556dc29369a)
    * [Shadow支持WebView使用file:///android_asset/协议加载插件资源的方法](https://juejin.im/post/5d1d6027e51d4510b71da654)
    * [调试研究Shadow对字节码编辑的正确姿势](https://juejin.im/post/5d1f03dce51d455d877e0d91)
    * [Shadow对插件包管理的设计](https://juejin.im/post/5d2ec812e51d45778f076de3)
    * [Shadow对PackageManager的处理方法](https://juejin.im/post/5d37dcf1e51d4510664d17d4)
* 独立博客 [https://github.com/timqian/chinese-independent-blogs](https://github.com/timqian/chinese-independent-blogs)
* Android 面试宝典、数据结构和算法、音视频 [https://github.com/yangkun19921001/Blog](https://github.com/yangkun19921001/Blog)
* 却把青梅嗅的反思系列 [https://github.com/qingmei2/blogs](https://github.com/qingmei2/blogs)
* 系列文章 Android Performance
    * [Android Systrace 基础知识(1) -- Systrace 简介](https://juejin.cn/post/6844904163407560712)
    * [Android Systrace 基础知识(2) -- 分析 Systrace 预备知识](https://juejin.cn/post/6844904165336940551)
    * [Android Systrace 基础知识(3) -- Why 60 fps ？](https://juejin.cn/post/6844904165689262087)
    * [Android Systrace 基础知识(4) - SystemServer 解读](https://juejin.cn/post/6844904165718622221)
    * [Android Systrace 基础知识(5) - SurfaceFlinger 解读](https://juejin.cn/post/6844904169573187597)
    * [Android Systrace 基础知识(6) - Input 解读](https://juejin.cn/post/6844904169535438862)
    * [Android Systrace 基础知识(7) - Vsync 解读](https://juejin.cn/post/6844904178444140551)
    * [Android Systrace 基础知识(8) - Vsync-App ：基于 Choreographer 的渲染机制详解](https://juejin.cn/post/6844904179216056327)
    * [Android Systrace 基础知识(9)-MainThread 和 RenderThread 解读](https://juejin.cn/post/6844904184806899719)
    * [Android Systrace 基础知识(10) - Binder 和锁竞争解读](https://juejin.cn/post/6844904182818816007)
    * [Android Systrace 基础知识(11) - Triple Buffer 解读](https://juejin.cn/post/6844904184899338254)
    * [Android Systrace 基础知识(12) - Kernel 中的 CPU Info 解读](https://juejin.cn/post/6844904185834504199)
    * [Systrace 流畅性实战 1 ：了解卡顿原理](https://juejin.cn/post/6963656387733749773)
    * [Systrace 流畅性实战 2 ：案例分析 - MIUI 桌面滑动卡顿分析](https://juejin.cn/post/6963656535067066405)
    * [Systrace 流畅性实战 3 ：卡顿分析过程中的一些疑问](https://juejin.cn/post/6963654615824875533)
* LeetCode 刷题攻略 [https://github.com/youngyangyang04/leetcode-master](https://github.com/youngyangyang04/leetcode-master)
* Android ANR问题总结 [https://mp.weixin.qq.com/s/-yfJoRxHe_J3PNLkGw19Cg](https://mp.weixin.qq.com/s/-yfJoRxHe_J3PNLkGw19Cg)
* 最全的Android技术栈 [https://github.com/chiclaim/AndroidAll](https://github.com/chiclaim/AndroidAll)


## License

```text
Copyright 2021 Knight

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```


     


        
        
版本：V2.3.2 2014-01-15
- 快捷分享提供网络图片预览功能
- 优化核心代码
- 新浪微博提供授权自定义权限的功能
- 修正qq空间分享会将空格变成+号的问题
- 修复人人网当用户生日设置为“X0后”时会授权失败的问题
- 修复快捷分享中选择instagram会错误提示客户端未安装的问题

版本：V2.3.1 2014-01-07
- QQ分享添加分享音乐的功能
- Zone分开图片分享和网页分享
- 修复qq空间未授权前无法分享本地图片的问题
- 修改Service的构造方法
- 合并ShareSDK中的setXXXDevinfo方法组

版本：V2.3.0 2013-12-27
- 添加评论与赞组件

版本：V2.2.1 2013-12-26
- 优化九宫格列表性能
- 授权用户数据库提供更多获取用户资料的方法
- 快捷分享添加对零长度字符串和null的等同处理
- 快捷分享提供统一关闭sso功能
- 规避android 2.2和2.3无网络打开网页授权会崩溃的问题
- 规避微信、易信分享纯时，当文本超过1024个字符以后拒绝分享的问题
- 修复QQ分享内容没有转短链的问题
- 修复新浪微博正确签名后依然无法使用SSO的问题

版本：V2.2.0 2013-12-23
- 添加易信分享文字、图片、音乐、视频和网页
- 添加易信朋友圈分享文字、图片、音乐、视频和网页
- 添加向微信收藏发送文字、图片、音乐、视频、网页和文件
- QZone分享使用新的接口
- 快捷分享屏蔽QZone一键分享功能
- 快捷分享添加对微信分享动画的支持
- 新增插件服务框架
- 利用插件服务框架实现评论与赞功能
- 修复快捷分享instagram不能使用的问题

版本：V2.1.3 2013-12-04
- 优化统计接口
- 添加插件服务框架，方便后续基于Share SDK的插件开发
- 添加微信收藏
- 添加易信好友和易信朋友圈
- 修复微信部分网络图片无法分享的问题
- 删除QQ客户端分享时强制要求设置titleUrl的问题

版本：V2.1.2 2013-10-18
- 添加VK和Instagram
- qq客户端分享添加纯文本和纯图片两种分享模式
- 快捷分享添加横屏支持
- 添加不删除jar包而隐藏平台的功能
- 在sdk内部集成新浪微博sso的配置文件，集成SDK时无须再添加其aidl文件
- 修正印象笔记设置了ShareByAppClient后可能导致逻辑矛盾的问题

版本：V2.1.1 2013-09-29
- 印象笔记添加优先使用客户端进行分享的支持
- 改进快速集成工具
- 修改网络层发送机制
- 修正qq分享没有回调的问题

版本：V2.1.0 2013-09-23
- 添加新平台：Pinterest、Flickr、Tumblr和Dropbox
- 优化快捷分享，提供更多的自定义功能
- 修正快捷分享platform和silent字段冲突问题
- 修复快捷分享中微信单独分享文字会出现文件找不到的问题

版本：V2.0.3 2013-08-27
- 修复无法获取应用后台应用信息的问题
- 修复QQ空间不能授权的问题

版本：V2.0.2 2013-08-23
- QQ客户端分享添加分享网络图片的功能
- 快捷分享提供微信分享网络图片的功能
- 添加搜狐随身看平台
- 为SDK添加英文语言支持
- 去除QQ客户端分享的“应用名”字段，改为自动获取
- 修正微信新版本不能关注的问题
- 修正QQ空间SSO授权可能出现崩溃的问题
- 修正一个快捷分享获取平台列表可能出现的多线程冲突问题
- 修正短链转换过程丢失文本信息的问题
- 修正部分QQ空间应用不能授权的问题

版本：V2.0.1 2013-08-09
- 提高统计功能的安全性
- 优化Twitter的授权流程
- 添加设置xml中设置是否开启短链转换功能
- 修复上个版本的一些bug

版本：V2.0.0 2013-08-02
- 核心类改名具体参看SDK说明文档和JavaDoc
- 添加对QQ客户端分享的支持
- 腾讯微博添加sso支持
- 人人网的接口到api 2.0并添加SSO支持
- 快捷分享添加根据平台差异化分享内容的支持
- 微信添加imageurl功能并强化发送音乐和图片的功能
- 为微信提供接受其客户端消息的功能
- 去除微信多余图字段，合并为imagePath和imageData
- 添加自定义授权权限列表的授权方式
- 添加支持应用后台配置应用信息的功能
- 修复新浪微博api升级导致新注册应用无法授权的问题
- 去除微信朋友圈实际不能支持但还保留接口的发送文件以及发送应用的方法
- 修正短链转中，若存在“父子链”时，会出现转换错误的问题
- 修复部分机型上无法将文字带进彩信输入框中的问题
- Sample中获取关注列表页面bug修复
- 修改快捷分享参数设置方式
- 修复开心网，分享纯文本出错的问题

版本：V1.2.1 2013-06-28
- 优化印象笔记，放弃使用其原生的SDK
- 添加自定义方法，允许开发者自行配置接口
- 适配Unity3D等工具不能引用项目，而必须复制jar和资源的情况
- 强化快捷分享功能，添加获取关注或者朋友列表的界面
- 调整新浪微博分享图片的优先级
- 修正未安装客户端时QZone SSO会导致点击无反应问题
- 修正微信无法分享网页的问题
- 修复授权正确以后返回错误事件代号的问题

版本：V1.2.0 2013-06-08
- 重新组织SDK的结构
- qq空间、facebook添加SSO支持
- 新浪微博提供分享网络图片的功能
- 微信添加发bitmap的功能
- 快捷分享添加自定义外部回调的功能
- 添加微信分享应用的功能
- 添加开心网、有道云笔记、Linkedin、Google+和FourSquare等新平台
- 添加新代码处理当新浪微博客户端SSO返回错误信息
- 添加新代码处理HTC机器不能发彩信的问题

版本：V1.1.6 2013-05-22
- 修正升级到adt 22以后，导入项目无法直接运行的问题
- 修正授权时按物理返回键无法调用onCancel的问题
- 添加禁止授权动画的方法

版本：V1.1.5 2013-05-15
- 添加搜狐微博平台
- 简化平台搜索方式，提高平台列表获取速度
- 为QQ空间和人人网添加分享本地图片的功能
- 重写新浪微博、人人网、Facebook等平台，放弃对其SDK的依赖
- 扩展新浪微博、腾讯微博分享功能，允许携带经纬度信息
- 扩展印象笔记的分享功能，允许多图分享
- 扩张email分享功能，提供html支持
- 提供自定义授权页面GUI和逻辑的示例
- 微调授权页面显示效果
- 提高微信分享的缩略图质量
- 修复部分集成者不能混淆代码的问题
- 修复新浪微博sso失效的Bug
- 修复豆瓣不能不分享图片的bug
- 修复取消授权时未调用调用onCancel事件的bug

版本：V1.1.4 2013-04-24
- 提供阻止分享时转短链的功能
- 适配Unity3D平台无法找到Core中的资源的问题
- 提供批量导出和导入WeiboDb中授权信息的功能，方便对用户系统的实现
- 修复部分手机上，Email分享会崩溃的问题
- 修复腾讯微博分享完成以后不通过Action_Share返回的问题

版本：V1.1.3 2013-04-22
- 为sinaweibo、tencentweibo、twitter实现获取关注列表的方法
- 简化新浪微博sso授权的代码
- 修复新浪微博不能分享gif的问题
- 添加授权页面监听和自定义工具
- 改进快捷分享宫格列表的现实效率

版本：V1.1.2 2013-04-11
- 迁移twitter的api到1.1版本
- 删除对common-httpclient的依赖
- 重写twitter的sdk，不再依赖twitter4j
- 重写qq空间的sdk，不再依赖tencnt-openapi
- 迁移人人网share接口，并使用Feed.publishFeed
- 修正腾讯微博授权时，部分机型提示SSL错误的问题

版本：V1.1.1 2013-04-03
- 修复新浪微博无法使用网页方式授权的问题
- 修复无通信模块平板设备上闪退的问题
- 提供不使用SSO方式完成新浪微博授权的方法
- 迁移腾讯微博接入方式到OAuth 2.0

版本：V1.1.0 2013-04-01
- 重写网易微博平台，放弃使用其SDK
- 添加授权页面标题栏隐藏功能
- 优化快捷分享模块
- 添加短信和邮件分享
- 添加微信剩余接口
- 添加新的分享接口，以适应平台差异（暂时仅支持微信平台）

版本：V1.0.3 2013-03-26
- 修复测试发现的bug
- 添加Api文档
- 添加运行时修改开发者信息的功能

版本：V1.0.2 2013-03-22
- 修复部分机型上无法显示宫格分享列表
- 修改中小屏幕上宫格列表图标过大的问题
- 添加SortId字段，方便开发者自行排序
- 解除Core包对apache-common的依赖
- 更新说明文档

版本：V1.0.1 2013-03-20
- 添加一个快捷分享GUI模块
- 优化分享框架结构
- 简化说明文档

版本：V1.0.0 2013-03-18
- 更新内容：ShareSDK Android 版本正式推出
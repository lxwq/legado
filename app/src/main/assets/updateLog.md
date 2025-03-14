# 更新日志

* 关注公众号 **[开源阅读]** 菜单•软件下载 提前享受新版本。
* 关注合作公众号 **[小说拾遗]** 获取好看的小说。

## **必读**

【温馨提醒】 *更新前一定要做好备份，以免数据丢失！*

* 阅读只是一个转码工具，不提供内容，第一次安装app，需要自己手动导入书源，可以从公众号 **[开源阅读]**、QQ群、酷安评论里获取由书友制作分享的书源。
* 正文出现缺字漏字、内容缺失、排版错乱等情况，有可能是净化规则或简繁转换出现问题。
* 漫画源看书显示乱码，**阅读与其他软件的源并不通用**，请导入阅读的支持的漫画源！

**2022/12/19**

* 支持PDF格式 by ag2s20150909

**2022/12/15**

* 更新cronet: 108.0.5359.128
* 正文添加移除重复标题开关,针对单个章节,默认开启,极个别特殊情况章节开头和标题一样但是不是标题
* 一些优化 by Horis

**2022/12/10**

* 更新cronet: 108.0.5359.79
* 阅读界面添加了自定义分隔线颜色功能 by Horis
* 修复目录界面本地规则选择不生效的bug
* 修复一些tts引擎因全标点段落朗读进度不准的问题

**2022/12/01**

* 更新cronet: 108.0.5359.61
* 修复验证码同一网址不刷新的bug
* 一些优化

**2022/11/22**

* 修复朗读长时间暂停后恢复时朗读速度可能不对的bug
* addBookshelf url参数添加origin,可以指定书源
* 通过增加特定标识使用无UA请求，适用于网络导入书源等,用法：http://xxx.xxx/xxxx#requestWithoutUA
* 修复cookie.getCookie(source.getKey())返回的cookie不及时的bug
* 书签添加导出功能

**2022/11/13**

* 订阅添加js注入
* 重要更改：登录按钮支持调用登录URL里的函数 by Xwite
* 书源编辑时可修改书源变量，添加平板双页，其他优化 by Horis

**2022/11/08**

* 更新cronet: 107.0.5304.105
* 发现不采用详情页url正则
* 目录更新完再缓存章节,缓存章节可以设置为0,为0时不缓存
* 添加书籍协议legado://import/addToBookshelf?src={url}

**2022/10/29**

* 更新cronet: 107.0.5304.91
* 朗读菜单的闹钟点击后可以保存设定时间，下次启动朗读自动设定时间，调不了时间、朗读固定的时间后停止的把进度条拉到0然后点一下闹钟就可以了 by Horis
* 多页目录和正文添加并发访问限制
* 阅读界面点击区域支持更多选项,中间区域也可设置
* 朗读服务和音频服务添加唤醒锁配置

**2022/10/22**

* 搜索范围保持分组排序
* 替换规则支持复制粘贴
* 修复混淆引起的一些问题
* 其它一些优化 by 821938089
* 添加对 WebDav 书籍使用的简明教程 by qianfanguojin

**2022/10/20**

* 优化搜索范围的选择,不改变原来的使用习惯
* 添加web服务唤醒锁开关,默认关闭,有些手机开启唤醒锁会被杀后台
* 添加设备名称设置，会在webdav备份文件名上显示 by 821938089
* 添加禁用滚动点击动画设置 by 821938089
* 移除子文件夹为空检查 by 821938089
* 重构httpTTS部分代码 by 821938089
* 使用事件总线的方式来调用手动翻页/下一章朗读，可能可以解决只能读一章的问题 by 821938089
* 修复并发率判断可能会发生死锁的问题 by 821938089
* 精简一些代码 by 821938089
* 优化web源编辑和web书架 by Xwite

**2022/10/17**

* 搜索界面菜单可修改搜索范围
* 内置对称加密不再自动转换Hex Base64 by Xwite
* 保留之前的对称加密函数,标记为不建议使用
* 继续优化本地书籍加载速度
* 换源不再更新最新阅读时间 by 821938089

**2022/10/16**

* 添加更新失败分组
* web服务和朗读服务添加唤醒锁
* 修复搜索禁用书源的bug
* 修复本地书籍很慢的问题
* 更改内置对称加密函数，请看文档 by Xwite
* 一些优化 by 821938089

**2022/10/14**

* 更新cronet: 106.0.5249.126
* 替换规则支持js,可以用js判断匹配到的内容决定替换为什么,匹配到的内容变量为result,替换为@js:开头则自动采用js判断替换内容
* 书架管理添加筛选功能
* 搜索支持搜索范围多分组和单书源设置
* 书源管理界面书源菜单添加单书源搜索书籍功能
* 复web阅读时app未退出阅读界面导致的进度bug by Xwite

**2022/10/09**

* 更新cronet: 106.0.5249.118
* 添加源编辑输入框最大行数设置
* 添加正文阅读界面进度条(本章/整本）设置 by 821938089
* 优化下拉加载更多相关界面
* 修复横屏竖屏切换后主题改变的bug by 821938089
* 优化章节替换净化 by Xwite
* 封面支持svg 正文img标签支持svg图片链接 by Xwite
* 调整申请设置书籍保存位置的时机 by Xwite

**2022/10/05**

* 优化书架数据库查询速度
* 如果WebDav的书籍比本地新,详情页的刷新可以更新本地书籍,之前的书籍不行没有记录远程书籍地址
* 本地文件被删除如果记录了webDav地址会自动下载webDav书籍 by Xwite
* 一些优化 by 821938089

**2022/10/01**

* 更新cronet: 106.0.5249.79
* 正文选择菜单朗读按钮长按可切换朗读选择内容和从选择开始处一直朗读
* 源编辑输入框设置最大行数12,在行数特别多的时候更容易滚动到其它输入
* 修复某些情况下无法搜索到标题的bug，净化规则较多的可能会降低搜索速度 by Xwite
* 修复文件类书源换源后阅读bug by Xwite
* Cronet 支持DnsHttpsSvcb by g2s20150909
* 修复web进度同步问题 by 821938089
* 启用混淆以减小app大小 有bug请带日志反馈
* 其它一些优化

**2022/09/26**

* 修复发现刷新bug
* 书架管理添加书源显示
* 优化web写源 by Xwite
* 一些优化 by Horis
* 修复设置图片时文件重名带来的一些问题
* 修复书籍导入出错时没有弹出书籍保存设置的问题
* 优化多线程TXT导出

**2022/09/23**

* 未分组分为网络未分组和本地未分组,可隐藏
* 优化web写源 by Xwite

**2022/09/22**

* 优化web源编辑
* 添加[图片解密规则](https://github.com/gedoor/legado/pull/2314)
* 修复调试无输出的问题 by 821938089
* epub模板添加[ori_title变量](https://github.com/gedoor/legado/pull/2309)
* 优化换源和文件权限提示
* 其它一些优化

**2022/09/20**

* 发现为空时不校验
* 订阅添加刷新分类功能,菜单中
* 修复webView因为不支持新夜间模式导致的崩溃
* 修复阅读背景分主题设置bug by 821938089
* 修复朗读高亮位置不对的问题 by 821938089
* 添加忽略音频焦点设置 by 821938089
* 优化web端写源 by Xwite

**2022/09/17**

* SDK暂时退回32,解决webView夜间模式不起作用的问题
* android studio新版本有bug,快捷方式报错,采用idea编译
* 音频从默认未分组移除
* 修复图片文字样式错误bug
* 修复阅读界面主题bug by 821938089

**2022/09/15**

* 更新cronet: 105.0.5195.136
* SDK 更新到 33
* 修复一些对话框可能会被键盘遮住的问题
* 自带的未分组包含本地和音频未分组
* 编辑书源分组时?中添加了插入分组功能
* 添加图片解密规则 by Xwite
* 优化在线TTS by 821938089
* 更新web端书源编辑 by jgckM
* 修复仿真翻页点击时翻页动画异常,化仿真翻页点击翻页效果 by 821938089
* 其它一些优化

**2022/08/31**

* 更新cronet: 105.0.5195.68
* 修复一些bug
* 给书源点赞 by SJJ-dot
* 墨水屏模式下，书籍信息页不显示模糊书籍封面作为背景

**2022/08/23**

* 验证码输入框显示来自哪个书源
* 修复一键导入丢失url参数的问题

**2022/08/19**

* 更新cronet: 104.0.5112.97
* 现在选择文本朗读会从选择处一直往下朗读,朗读更方便
* 阅读界面的TXT目录正则 弹框中也支持正则标题示例
* 一些优化 by 821938089
* 优化epub封面加载，修复图片读取，修复目录索引问题
* 本地内容获取时尝试HTML实体解码，优化报错提示和添加日志
* 优化书源校验，注释Error行
* 订阅源、书架管理添加选中所选区间
* 优化订阅源分组显示已启用分组，订阅源管理增加已启用、已禁用、需要登录、未分组分组
* 订阅源长按菜单添加禁用源、分组管理排序
* 添加返回时提示放入书架设置
* 优化备份设置子文件夹对话框内容显示和校验
* 修复搜索手动停止滑到底又重新搜索

**2022/08/02**

* 更新cronet: 104.0.5112.69
* 修复一些bug by 821938089
* 备份自定义直链上传规则
* 尝试修复epub加载OOM的问题
* 图片添加保存按钮
* 一些优化

**2022/07/21**

* 更新cronet: 103.0.5060.129
* 修复登陆界面部分网页按钮无反应问题
* 阅读记录添加按最后阅读时间排序
* 阅读记录添加搜索
* 修复其它一些bug

**2022/07/16**

* 针对自建webDav进行优化,解决一些问题 by 821938089
* 修复全文搜索新关键词时,老关键词搜索没有停止的bug
* 优化全文搜索 by 821938089

**2022/07/10**

* 修复bug

**2022/07/09**

* 书源添加未分组筛选
* 修复使用自建WebDav一些bug by 821938089
* 修复换源按钮长按只能生效一次的bug
* 修复java.post等不能保存cookie的bug

**2022/07/07**

* 更新cronet: 103.0.5060.71
* 修复一些bug
* webDav书籍排序
* 更新一些库
* web端支持自定义字体 by qianfanguojin

**2022/06/23**

* 更新cronet: 103.0.5060.53
* 继续优化webDav导入,改成和本地导入界面一样,可以批量导入

**2022/06/16**

* 导出使用单线程,导出占用大量内存,并行容易OOM
* 导出到WebDav文件夹改为books,方便导入
* WebDav导入基本能用了

**2022/06/10**

* 更新cronet: 102.0.5005.125
* 添加源变量说明,输入源变量界面显示说明
* 修复阅读界面因WebDav连接不上无响应的bug

**2022/06/01**

* 更新cronet: 102.0.5005.78
* 缓存导出添加导出图片文件选项 by Xwite
* 其他设置添加图片绘制缓存选项 by Xwite
* 移除书源详情页规则添加刷新时重新获取目录页链接Url
* 添加刷新前Js,功能更强大,可重新获取书籍和刷新目录Url
* java.reGetBook(), 重新获取书籍
* java.refreshTocUrl(), 刷新目录Url
* 修复一些bug by Xwite

**2022/05/27**

* 书源详情页规则添加刷新时重新获取目录页链接Url的配置,true or false
* 修复bug

**2022/05/26**

* 修复部分txt章节结尾乱码bug
* 优化翻页流畅度
* js添加des HMac
* 登录ui用户信息默认加密方式改变，需要重新登录
* 修复图片加载错误时一直重复获取图片导致卡顿的bug
* web端优化并添加无限滚动开关 by Xwite Netrvin

**2022/05/21**

* 修复更改本地文件后每次打开都刷新目录的bug
* 删除一些不必要的权限
* 添加WebDav书籍 by qianfanguojin 未完成

**2022/05/16**

* 添加firebase性能监测
* 清除cookie时清除webView的cookie

**2022/05/15**

* 源编辑添加cookieJar选项
* 源编辑菜单里添加清除cookie,如果之前能用的书源不能用了,可以关闭cookieJar后点下菜单里的清除cookie后再试
* 书源支持文件类型 by Xwite
* 启用firebase收集崩溃日志
* web端阅读实现无限滚动 by Xwite
* 进入阅读界面时如果本地书籍有更新自动刷新目录

**2022/05/11**

* 修复替换报错的bug
* 优化目录界面替换

**2022/05/10**

* 更新cronet: 101.0.4951.61
* 更新到SDK 32
* js添加 getVerificationCode startBrowserAwait
* 监测网络变化及时更新web服务的IP
* 优化在线tts导入
* 优化txt规则导入
* 替换规则添加超时字段
* 其它一些bug修复

**2022/05/02**

* 优化强调色和文字颜色一样的情况下一些文字的显示
* 修复bug
* js添加 java.startBrowser

**2022/05/01**

* 更新cronet: 101.0.4951.41
* 优化webDav备份,显示错误代码,自动备份错误不提示只记录错误日志,
* 修复图片加载失败卡顿的问题
* 打开应用时如果服务器备份比本地新,提示是否恢复

**2022/04/23**

* 修复js问题
* 音频界面显示缓冲进度 by ag2s
* 修复图片文字缓存bug
* 修复在线朗读bug
* 修复mlns epub目录识别失败

**2022/04/22**

* 键盘辅助配置加入备份恢复文件
* 修复源管理界面添加删除分组不及时显示的bug
* 修复其它一些bug
* 更新js库

```
实现 ES6 Object.values Object.entries Object.fromEntries
实现 ES2017 Object.getOwnPropertyDescriptors
添加：支持“catch”中的可选变量绑定
添加：反单引号里`${}`语法支持（用于字符串连接）
添加：equals (==) 等号的支持
添加：NativeArray.subList()
添加：Object.hasOwn
修复：（for of）导出字符串 of前无空格导致语法错误问题
其他一些优化
```

**2022/04/17**

* 缓存导出包含图片类型
* 图片长按弹出查看和刷新菜单
* 修复因大小写问题引发的UserAgent重复bug

**2022/04/14**

* 更新cronet: 100.0.4896.127
* 修复解码正文图片报错，添加解码日志
* js文档：java.toast java.longToast
* cookie保存策略更改，若登录失效请重新登录
* cronet和okHttp共用线程池
* 限制图片缓存大小,超过自动清除,防止OOM
* 其它一些优化

**2022/04/12**

* 更新cronet: 100.0.4896.88
* 恢复epub加载方式
* 添加替换超时判断,替换超时自动禁用替换规则并重启应用,正则无限执行会导致耗电异常且没有办法主动结束线程只能重启应用
* 使用glide解码正文图片 by Xwite
* fix:缓存图片后缀错误拼接 by Xwite

**2022/04/07**

* 实现epub的懒加载 by ag2s20150909
* 解决txt无法导入
* 优化换源

**2022/04/05**

* 更新cronet: 100.0.4896.79
* 添加所有书签
* 添加批量换源

**2022/03/31**

* 添加java.importScript，详情见js帮助文档
* 本地书籍信息匹配`(.*?)《([^《》]+)》(.*)`, `(^)(.+) 作者：(.+)$`, `(^)(.+) by (.+)$`

**2022/03/29**

* 更新cronet: 100.0.4896.58
* tts朗读不在指定为中文,跟随系统设置,因为有些人需要朗读英文,如果朗读不出来可以去tts设置里看看是不是中文
* 修复详情也封面背景模糊失效的bug
* 优化音频界面定时设定

**2022/03/25**

* 更新cronet: 99.0.4844.88
* 分组搜索结果为空是提示是否切换到全部分组搜索
* 修复bug

**2022/03/21**

* 一些优化和bug修复

**2022/03/17**

* 添加仅在wifi下加载网络封面
* 修复web书架白条
* 换源增加当前源快速定位

**2022/03/15**

* 更新cronet: 99.0.4844.73
* 引入compose包
* 书源类型为image的书源,翻译默认为滚动,图片样式默认为FULL
* url参数辅助输入
* 修复一些bug

**2022/03/12**

* 存储变量长度超过10000直接存储到文件,防止书籍太大备份失败
* 编辑源辅助输入支持自定义

**2022/03/09**

* 添加通用封面规则,在封面设置里,进入详情页会使用此规则重新获取封面
* 修复一些bug

**2022/03/07**

* 更新cronet: 99.0.4844.58
* 导入本地书籍界面添加排序功能
* 修复txt最后一句不显示的bug
* pro版本可以单独设置启动画面
* 优化目录界面,书签自动定位到当前章节位置
* 修复图片有左边距的bug
* 其它一些优化

**2022/03/04**

* 更新cronet: 99.0.4844.48
* 修复web端添加同步阅读配置导致的bug

**2022/03/02**

* 单章换源和更多刷新放到长按里面
* 优化web端,修复一些封面无法访问bug,代理正文图片
* web端同步阅读配置
* 其它一些优化

**2022/02/28**

* APP内编写规则时，对由XPath|JSOUP|CSS组成的规则进行简单的默认补全。需手动开启,单次生效
  * 对需求文本的获取text
  * 对需求文本的img元素(以img结尾)的获取alt属性
  * 对需求链接的获取href属性
  * 对需求图片的获取src属性
  * 详情页预处理存在js/json/正则的不对详情页规则进行补全
  * 多条规则只补全最后一条规则
  * 书源编辑页点击调试/保存时补全开始生效
  * 注意:不改变编辑框内容显示，保存后再次编辑可查看补全后的规则，方便调试时快速修改规则
* 在线朗读采用exoPlayer
* 其它一些优化

**2022/02/26**

* 自动备份检测到webDav已有备份时不会重复备份
* 修复黑屏卡顿问题

**2022/02/25**

* 修复排版导入不能导入背景图片的bug
* 修复txt目录识别的一些问题
* 修复换源慢的bug
* 修复在线朗读遇到单行标点时停止的bug

**2022/02/22**

* 添加编辑章节内容,编辑章节内容不会修改源文件,只是保存缓存
* 修复未读章节为0时可能不隐藏的bug
* 修复webView使用post是url不是跳转后url的bug
* 添加单章换源功能

**2022/02/16**

* 目录正文现在按照搜索发现分别校验
* 书源校验的超时校验存在bug
* 标题支持换行
* 修复校验超时判断
* 优化txt目录识别,超长章节单独拆分,不在全文拆分
* 刷新章节添加刷新当前章节,刷新之后章节,刷新全部章节

**2022/02/11**

* 可以单独给书籍设置朗读tts
* 目录界面菜单添加替换开关,开启替换加载时间会长一些
* 书源校验添加规则失效分组，更新书源界面帮助文档
* 替换规则添加作用于标题和作用于正文
* 导出支持本地书籍再次导出
* 紧急修复不自动朗读下一章的bug
* 修复其它一些bug

**2022/02/09**

* 校验失效分组具体到搜索发现目录正文 by Xwite
* txt文件初次解析目录不选择禁用的正则
* txt单章字数超102400均分txt，添加开关 by Xwite
* 修复tts被回收后无法继续朗读的bug,重新初始化tts
* webDav备份支持自定义文件夹
* 其它一些优化

**2022/02/03**

* 字符串大于1024时禁用代码高亮
* 修复baseUrl丢失参数的bug
* 添加更新bookUrl和更新tocUrl函数
* 标题单独净化,防止出现正文标题没了的问题
* 修复一个null报错
* 修复进度同步bug
* 按返回键关闭搜索界面 by Xwite
* 其它一些优化 by Xwite

**2022/01/28**

* 阅读背景添加透明度调节
* 添加其他设置-校验设置 by Xwite
* 修复一些bug

**2022/01/26**

* 修复web写源订阅源保存失败bug
* http朗读下载错误连续5次后自动暂停
* 其它一些优化

**2022/01/20**

* 添加payAction规则，返回购买链接
* 书源编辑中的辅助键盘❓中可查看js说明文档 by Xwite
* 其它一些优化

**2022/01/11**

* 紧急修复在线tts朗读bug
* 紧急修复登录问题
* 添加isVolume规则，支持二级目录，正文标题显示优化 by Xwite

**2022/01/10**

* 继续修复txt目录识别,现在识别启用的规则,再识别禁用的规则,按目录匹配数由多到少识别,如果有章节大于5万字就尝试下一个目录规则,如果没有任何目录匹配或每章都小于5万字则自动分段
* 修复全局搜索跳转bug
* 从外部打开的文件如果书架上已有会对比更新时间,如果打开的文件更新会替换原文件

**2022/01/06**

* 弃用java.getCookie(tag,key)，请使用cookie.getKey(url,key)
* js添加java.cacheFile(url, saveTime),缓存网络链接，返回文件内容，可实现代码共用和减少代码量

```js
eval(String(java.cacheFile(url)))
```

* 设置里增加书籍文件夹配置,方便切换外部书籍保存文件夹
* 修复打开Web服务，切出app后很快崩溃 #1489
* 修复低版本手机打开本地文件出错的bug #1491
* 校验和调试时不保存正文

**2022/01/03**

* 重新安装应用后没有权限的本地书籍会提示选择文件所在文件夹,不需要重新添加
* 更新okhttp和cronet
* 修复web阅读纪录同步问题 解决bug #1478
* 去除html中一些乱码&nbsp;&ensp;等 解决bug 页面乱码 #1465

**2022/01/01**

* 修复本地txt问题,不在拷贝到私有目录,可以正常打开
* 优化txt目录识别,取目录数量最多的规则

用于新浪微博开放平台的Delphi SDK. 内含能直接使用的DEMO.

更新
2011年10月21日 发布V1版Delphi SDK，

基于 http://open.weibo.com/wiki/API%E6%96%87%E6%A1%A3 中的最新接口封装

(实现OAuth1.0验证，发送文字和图片微博，获取最新微博列表等)


说明
如何申请API Key

你需要有一个新浪微博开放平台的API Key.
这里申请: http://open.weibo.com

这是我用Delphi实现的新浪微博SDK

在Delphi 2010下编译运行通过，

接口返回解析使用的是应用比较广泛的uLKJson单元，

此外加密算法用的是Indy10控件里的几个单元。

在实例中实现了OAUTH验证、发送图片和文本微博、

获取微博列表等几个入门级的接口，

希望对你们开发微博应用有所帮助。


整整花了二十个夜晚，献给广大的Delphier

> 作者:悟能 QQ:452330643 EMail:ggggcexx@163.com
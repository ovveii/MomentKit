# MomentKit

仿WeChat朋友圈的界面效果，代码整洁易读，静态页面，无网络交互。里面的功能并没有全部完善，可以根据自己的需求去补充一下。欢迎[留言](https://github.com/ChellyLau/MomentKit/issues)，互相学习。


## 功能介绍


### 1、一级页面

1. 消息页面（模型：`Message`）；
2. 通讯录页面（包含索引，模型：`User`）；
3. 发现页面；
4. 我的页面；

PS：这些页面只是为了不让一级页面显得空，本控件主要是**朋友圈**功能的分享。



###  2、二级页面 > 朋友圈页面（MVC模式）

1. 控制器（`Controller`）：朋友圈列表`MomentViewController`； 
2. 模型（`Model`）：`Moment`、`Comment`； 
3. 视图（`View`）：

* 单个朋友圈动态视图（`MomentCell`）；
* 朋友圈图片区视图（`MMImageListView`）；
* 图片预览视图（`MMImagePreviewView`）；
* 赞|评论操作视图（`MMOperateMenuView`）等；



###  3、朋友圈的功能点

1. 支持富文本（`MLLinkLabel`）：链接、表情、电话、邮箱等；
2. 支持链接查看，顶部带进度条（`MMWebView`）、电话拨打|拷贝、邮箱调取；
3. 支持网络图片加载（`SDWebImage`）；
4. 支持图片预览：双击放大、双指捏合缩放、滚动预览等；
5. 支持数据库增删改查（`FMDB`+`JKDBModel`）；
6. 支持上拉加载更多（`MJRefresh`）； 
7. 支持点赞 | 取消点赞；
8. 其他功能 > 未完待续；


## 效果图（动画）

![MomentKit](https://github.com/ChellyLau/MomentKit/blob/master/Screenshot/screenshot.gif)


## 效果图（静态）

![MomentKit](https://github.com/ChellyLau/MomentKit/blob/master/Screenshot/screenshot_1.png)
![MomentKit](https://github.com/ChellyLau/MomentKit/blob/master/Screenshot/screenshot_2.png)
![MomentKit](https://github.com/ChellyLau/MomentKit/blob/master/Screenshot/screenshot_3.png)


## 后记

我这个控件大约是GitHub上最简单易读的，我没有其他大佬的技术牛，我做这个主要是自我学习。会不定时更新，如果有问题欢迎给我[留言](https://github.com/ChellyLau/MomentKit/issues)，我会及时回复。如果这个工具对你有一些帮助，请给我一个star，谢谢🌹🌹。





# BasicAppToDevelop
    本App是站在宏观角度,对Android系统的底层硬件API进行操作
    (如添加联系人黑名单,获取所有已安装App,给各App加密...) 
###目的:
    (其实不是为了让你学习操作系统的API,主要是为了让你学习四大组件之间的联系)   

#啥也不说了,先上福利


![图灵社区](http://ww4.sinaimg.cn/mw690/e75a115bgw1f3rrbzv1m8g209v0diqv7.gif)




#安全卫士 
### 这个项目中用的API基本都是站在安卓系统的角度去操作,比如:
>  获取系统的接打电话权限  
>  控制收发短信  
>  操作系统的短信数据库   
>  操作系统的联系人数据库,获取到系统内的已安装软件…..  
	
###学会了这些,相当于对安卓的四大组件有了一些更宏观的认识.整个项目,应用到了以下技术点:

>1,GridView的使用  
>2,AlertDialog的使用  
>3,自定义UI组合控件,并设置其属性  
>4,获取联系人数据库,并查询回显  
>5,了解超级管理员API以及GPS定位  
>6,自己创建黑名单数据库,并完成的增删改查,以及拦截电话,短信的具体功能.  
>7,完成小火箭动画  
>8,理解不同业务功能回显的必要  
>9,自己创建Xml备份短信  
>10,自定义吐司,设置其何时显示何时消失,并可实时滑动.  
>11,ExpandableListView的使用  
>12,懂得操作系统中已安装的app信息  
>13,PopupWindow入门   
>14通过源码,懂得对已安装的app进行分享,删除,打开操作.

#个人心得
##还算有点技术含量的大概有以下几点:  
>* 自定义组合控件(用到了TextView和CheckBox的组合,自定义了一个Toast)  
>* 远程调用系统提供的AIDL
>* BroadCastReceiver和ContentReslover的使用与区别
>* ListView的优化
>* FrameLayOut权重含义:让其他控件先显示,然后把剩余空间给自己
>* 反射的应用:获取到Android系统隐藏的API

3qforWatching

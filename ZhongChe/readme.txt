a01.server服务器地址固定

a02:包名:com.growatt.zhongche

a03：修改demo账号密码：guest--zhongche

a04：重要-修改tinkerid(gitSha)的值

a1.屏蔽掉客服电话

a2.用户协议替换

a3.资料中心：公司官网修改（名称和网址）

a4.修改密码问题：
	4.1:RetrievepwdActivity：(这个界面有2个地方需要修改)；获取服务器地址为空，已用Urlsutil中Urlsutil.url_host默认地址

a5.修改app名称

a6.修改App和热更新xml下载地址：App名字为文件夹名称/App名称修改后自动更换地址(ZhongChe)

a7.数据库版本名字修改（根据包名自动完成：ShinePhone/Google/SMTEN）

a8.server更新功能（根据google版本包名屏蔽更新），此版本具有更新功能
   修改app更新包名字和热更新名字:ZhongChe.apk

a9.Crasheye修改（ShineApplication）
	key：0e38ac70
	
a10.屏蔽掉提交问题入口
	10.1：CommondataActivity：屏蔽掉提问
	10.2：UserdataActivity：屏蔽掉+
	
a11.关于里面App名字修改：已自动完成	

a12.App启动页改成一种：welcome图片在两个资源文件夹，Smten不区分中英文界面

a13.资料中心中英文公司名字修改

a14.屏蔽主界面提示资料中心图片fragment/getAPPMessage()

15.关闭调试

//清单配置修改
a二.百度地图key修改
百度定位key:com.baidu.lbsapi.API_KEY（修改一个位置）
KEY:9DOZ6mjjDcaRZHqxPp8huVDyGzw5BBux

a三.极光推送key修改
	3.1.极光推送app_key:JPUSH_APPKEY（修改一个位置）
	key:272a3c6f940d958e0694a7a2
	3.2.修改极光相关的包名（6个）
	
	
*检查manifest中activity是否限制为竖屏
*发布版SHA1:
F7:A0:E6:E8:A9:2F:B6:92:D4:5C:F2:92:CE:F1:CA:3F:FB:DB:D4:91

开发版SHA1:
D5:B4:CA:2C:E4:ED:53:D4:BF:37:DA:BB:E5:06:0A:8F:9E:4C:21:2B







公司中文名：江苏爱康绿色家园科技有限公司

手机APP名称： 爱康家电站-R
客户电话：  0512-4001017000 
公司邮箱： Ak-Service@akcome.com
下载地址：http://cdn.growatt.com/apk/AiKang/ShinePhone_TinkerPatch.xml
			http://cdn.growatt.com/apk/AiKang/AiKang.apk
http://www.akgroup.com.cn/

微信支付相关：
	AppID：wx2e0de21c2f509b30
	AppSecret：b99b431277a4f12c87a4d2ae484aecd6
	商户号1514381161（服务器）：akakc3t4p6hvkt4hy3ugamio5o1lh55r


下载页面
http://ak.smten.com/app/xml/download_ak.png.jsp
	/**
	 * smten odm类型：0:默认+
	 1;Haier
	 2:ujass
	 */
	public final static String odm_type = "2";
	Constant.odm_type = “2”;
上线问题：
若无软著可以暂时用网站备案信息截图＋网站截图＋网址截图以及两个外市场已 上线同款应用的前后台截图，之后再补充软著 

00：修改circledialog button颜色com.mylhyl.circledialog.res.values.CircleColor
00:数据库名称修改：sqldataAiKang.db
a01.server服务器地址固定：http://ak.smten.com

a02:包名:com.growatt.aikang

a03：修改demo账号密码：guest  123456

a04：重要-修改tinkerid(gitSha)的值

a1.屏蔽掉客服电话

a2.用户协议替换

a3.资料中心：公司官网修改（名称和网址）

a4.修改密码问题：
	4.1:RetrievepwdActivity：(这个界面有2个地方需要修改)；获取服务器地址为空，已用Urlsutil中Urlsutil.url_host默认地址

a5.修改app名称

a6.修改App和热更新xml下载地址：App名字为文件夹名称/App名称修改后自动更换地址(爱康家电站-R)

a7.数据库版本名字修改（根据包名自动完成：ShinePhone/Google/SMTEN）：sqldataAiKang.db

a8.server更新功能（根据google版本包名屏蔽更新），此版本具有更新功能
   修改app更新包名字和热更新名字:AiKang.apk

a9.Crasheye修改（ShineApplication）
	key：731931a0
	
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
KEY:gpbXglhQEruwR2GNHFBV4Yrm2tdmSN6w

a三.极光推送key修改
	3.1.极光推送app_key:JPUSH_APPKEY（修改一个位置）
	key:58bdc3e3b0c7de33009e7e17
	3.2.修改极光相关的包名（6个）
	
	
*检查manifest中activity是否限制为竖屏
*发布版SHA1:
F7:A0:E6:E8:A9:2F:B6:92:D4:5C:F2:92:CE:F1:CA:3F:FB:DB:D4:91

开发版SHA1:
D5:B4:CA:2C:E4:ED:53:D4:BF:37:DA:BB:E5:06:0A:8F:9E:4C:21:2B







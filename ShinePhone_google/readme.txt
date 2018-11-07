注意
1.将xutils tag输出模式设置为false
2：build正式版debugger = false关闭调试功能
*发布版SHA1:
F7:A0:E6:E8:A9:2F:B6:92:D4:5C:F2:92:CE:F1:CA:3F:FB:DB:D4:91

开发版SHA1:
D5:B4:CA:2C:E4:ED:53:D4:BF:37:DA:BB:E5:06:0A:8F:9E:4C:21:2B

*检查manifest中activity是否限制为竖屏

0:包名
ShinePhone:com.growatt.shinephone
ShinePhone_google:com.growatt.shinephones

1.去除掉server更新功能（根据包名自动完成）

2.极光推送app_key:JPUSH_APPKEY（修改一个位置）
ShinePhone:e07f88f9890a521f16e38956
ShinePhone_google:9a7abaddde4f2cdd685c906b

3.修改极光相关的包名（6个）

4.百度定位key:com.baidu.lbsapi.API_KEY（修改一个位置）
ShinePhone:yTMfft0thqEEDirYWta3Gfb38oE4El6j
ShinePhone_google:7LZGWG04glXRQrgezGBEG6tUaMaRiDMG

5:.去掉CrashEye监控（根据包名自动完成）

6.sqlite数据库名字修改（已根据包名自动完成）

7.修改xutils中的类org.xutils.x$Ext$1
if(TextUtils.isEmpty(hostname)||session==null||session.getPeerHost()==null){
    return false;
}
if(hostname.contains("growatt")||session.getPeerHost().contains("growatt")){
    return true;
} else {
    return false;
}



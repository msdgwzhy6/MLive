# MLive
如何从无到有一条龙建立直播？看我就对了。趁着这些天公司没事干，码一个android端直播平台放上来，(包括主播段、服务器、直播端)。如果对大家有用的话，就点个赞哈。
---
## UI界面
采用类映客界面模式，有主播段和视频播放端，采用Material Design风格，（话说谷歌5.0推出的Material Design风格真的很不错耶，趁着这个项目练个手哈）！
---
## 推流端
采用百度LSS 推流SDK，（话说简单好用的推流sdk真的不好找啊，七牛云听说还不错，大家可以试下，我采用了LSS2.0的SDK，之所以用这个是因为2.0的sdk不需要申请域名，唯一缺点是2017年开始不再提供支持）
---
## 服务端
买个云服务器好麻烦的说，所以先在本地电脑上搭个服务器访问lss吧，只是做个直播的Demo，就不要那么正式了哈，经测试在本地服务器上运行没问题。
---
## 播放端
Vitamio还不错，api跟android官方的挺像的，就用它了。
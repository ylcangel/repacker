## repacker
	ApktoolRepacker容器，即能正常跑起来的目录文件依赖，容器内部apk和证书均为我自己创建用于测试的，真正运行时你需要替换或者添加为实际文件。
	
### 文件目录介绍

	- apks/目录用于存放需要重打包的apk，apk数目不限
	- cert/目录用于存放证书，证书目前只能命名为CERT.RSA（需要替换成你需要hook的证书）；虽然源码中集成了v2版本证书解析，但目前仅实现支持v1版
	- dex/目录存放的repacker dex，你不要动它
	- lib/目录存放的是repacker lib，你不要动它
	- ApktoolRepacker-3.0.2.jar
	
### 相关链接
> [ApktoolReapcker](https://github.com/ylcangel/ApktoolRepacker)
>
> [repacker](https://github.com/ylcangel/repacker)
>
> [RepackerHook](https://github.com/ylcangel/RepackerHook)
>
### 关于作者

网络ID: **AngelToms** <br />
邮箱: ylcangel@gmail.com <br />

B站: https://space.bilibili.com/1332269071<br />
github: https://github.com/ylcangel<br />
csdn: https://blog.csdn.net/ylcangel,已不更新<br />
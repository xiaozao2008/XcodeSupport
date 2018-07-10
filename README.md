Xcode真机支持组件.

<font color=#0099ff size=18 face="微软雅黑">注意需要彻底重启Xcode才有效.</font>

每次升级Xcode可能隐含一些坑, 所以很多Developer可能还在使用旧版本的Xcode.

但是旧Xcode无法支持高版本的真机.

此文件下载放置指定目录可以让旧版本xcode支持高版本真机.


### 使用方法

> 把此zip解压放到xcode的指定路径即可

#### Xcode路径

> Xcode.app -> 显示包内容 -> Contents -> Developer -> Platforms -> iPhoneOS.platform -> DeviceSupport

> 或者

	open /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport 



#### 下载zip

> 下载整个工程太大, 一般来说我们只是需要最新或者特定版本支持文件.

> 单个zip下载方法, 终端cd后直接使用 curl -O 或者 wget 下载


	curl -O https://raw.githubusercontent.com/xiaozao2008/XcodeSupport/master/8.0.zip
	
	curl -O https://raw.githubusercontent.com/xiaozao2008/XcodeSupport/master/8.1.zip
	
	curl -O https://raw.githubusercontent.com/xiaozao2008/XcodeSupport/master/8.2.zip
	
	curl -O https://raw.githubusercontent.com/xiaozao2008/XcodeSupport/master/8.3.zip
	
	curl -O https://raw.githubusercontent.com/xiaozao2008/XcodeSupport/master/8.4.zip
	
	curl -O https://raw.githubusercontent.com/xiaozao2008/XcodeSupport/master/9.0.zip
	
	curl -O https://raw.githubusercontent.com/xiaozao2008/XcodeSupport/master/9.1.zip
	
	curl -O https://raw.githubusercontent.com/xiaozao2008/XcodeSupport/master/9.2.zip
	
	curl -O https://raw.githubusercontent.com/xiaozao2008/XcodeSupport/master/9.3.zip
	
	curl -O https://raw.githubusercontent.com/xiaozao2008/XcodeSupport/master/10.0.zip
	
	curl -O https://raw.githubusercontent.com/xiaozao2008/XcodeSupport/master/10.1.zip
	
	curl -O https://raw.githubusercontent.com/xiaozao2008/XcodeSupport/master/10.2.zip
	
	curl -O https://raw.githubusercontent.com/xiaozao2008/XcodeSupport/master/10.3.zip
	
	curl -O https://raw.githubusercontent.com/xiaozao2008/XcodeSupport/master/11.0.zip
	
	curl -O https://raw.githubusercontent.com/xiaozao2008/XcodeSupport/master/11.1.zip
	
	curl -O https://raw.githubusercontent.com/xiaozao2008/XcodeSupport/master/11.2.zip
	
	curl -O https://raw.githubusercontent.com/xiaozao2008/XcodeSupport/master/11.3.zip
	
	curl -O https://raw.githubusercontent.com/xiaozao2008/XcodeSupport/master/11.4.zip
	
	curl -O https://raw.githubusercontent.com/xiaozao2008/XcodeSupport/master/12.0.zip

	
> 或者把 'curl -O' 改为 'wget'

> 注意需要彻底重启Xcode才有效.

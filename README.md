ipa_pack
========

iOS多渠道打包工具使用说明:

（1） 修改`project－Info.plist`文件，增加渠道标识字段

![image](https://raw.githubusercontent.com/akzhou/ipa_pack/master/images/ECFF25FF-B270-4FE9-88BE-5A5F88626951.png)

（2） 程序获取渠道标识

![image](https://raw.githubusercontent.com/akzhou/ipa_pack/master/images/ECFF25FF-B270-4FE9-88BE-5A5F88626952.png)
	
（3） 修改`ipa_pack.sh`中的channel_array为你需要打包的渠道标识

![image](https://raw.githubusercontent.com/akzhou/ipa_pack/master/images/ECFF25FF-B270-4FE9-88BE-5A5F88626953.png)

（4） `ipa_pack.sh`放在工程根目录运行

![image](https://raw.githubusercontent.com/akzhou/ipa_pack/master/images/ECFF25FF-B270-4FE9-88BE-5A5F88626954.png)

![image](https://raw.githubusercontent.com/akzhou/ipa_pack/master/images/ECFF25FF-B270-4FE9-88BE-5A5F88626955.png)
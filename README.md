## SDK 获取
本项目目录 `chinaDemo/BadamSdkLib` 下的文件为接入所需要的 .jar 包和所需的资源文件

## 巴达木(Badam)SDK Ecilpse 接入 demo
BadamSdk(下称SDK) 包含中国地区, 和海外地区两个版本,不同版本接入时有差异，请CP接入时选择对应的地区版本即可。


每个地区版本都包含用户+支付两个模块，不同地区版本的用户模块都一致，仅支付模块包含的支付渠道不同。由于将所有支付通道都集合到一起会造成sdk包体过大，所以我们将不同地区的渠道支付渠道分开，让CP在接入时不过多地增加 .apk 包体大小

### 版本号-目录版本号
SDK 包含多个版本, 下面这个表格简单明了地给出不不同版本同目录的对应关系

目录名称| SDK 版本|当前SDK版本号|接入文档
--- | --- | --- | ---
chinaDemo|中国(新疆)地区|210|[README.md](https://github.com/BadamSDK/ClientEclipse/blob/master/chinaDemo/README.md)

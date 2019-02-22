# rootlessJB3_Plugin
这是一个收集整理在rootlessJB3上适用于IOS12的插件，如侵犯到阁下权益,请及时通知我,我会及时处理。
## 一、安装
Deb格式的插件请导入至Filza 直接安装后注销，注销后若插件没有生效请阁下尝试手动重启再越狱。

Deb格式直接安装失败和zip、rar等压缩包打包的插件请尝试用如下方法手动安装：
1. 使用shu等支持解压deb格式的文件管理器把插件里面的data开头的压缩包解压。
2. 将解压后得到的文件用Filza分别移入到对应文件夹
* MobileSubstrate里的dylib和plist格式的文件放到路径 _var_LIB/TweakInject
* PreferenceLoader_Preference里plist格式的文件放到路径 /var_LIB_PreferenceLoader_Preference
* PreferenceBundles里后缀为bundle的文件夹放到路径 _var_LIB/PreferenceBundles
* Applicationsupport下的文件放到路径var_mobile_Library/Application Support
**解压缩后没有文中提及的某些文件或是多出来一些文件不用理会，将文中提及的文件放到对应文件夹后手动重启再越狱即可**
## 二、卸载
1. 以zip、rar等压缩包打包的插件直接删除之前移动的对应文件即可。
2. 用Filza直接安装Deb格式插件的请用Filza找到对应的deb包打开后复制**package:**后的字段，如com.wxhbts.undertime（也就是插件的包名），之后再点安装 安装完成后到内容的最后输入 **dpkg -r 插件包名**
换行，注销；至此插件已卸载完成。🎈



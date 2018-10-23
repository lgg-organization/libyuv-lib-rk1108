# libyuv-lib-rk1108
libyuv-lib-rk1108, libyuv库。rk1108交叉编译。

交叉编译环境变量配置：
编辑 ~/.bashrc 文件，然后，执行命令 source ~/.bashrc

export CVR_SDK_ROOT=/home/liu/rk1108/29_rk1108-cvr
export PATH=$PATH:$CVR_SDK_ROOT/prebuilts/toolschain/usr/bin
export PATH=$PATH:$CVR_SDK_ROOT/prebuilts/toolschain/usr/arm-rkcvr-linux-uclibcgnueabihf/bin

编译说明：
1. ndk_system: 包含NDK，ANDROID.mk 语法实现。
2. rk_system: 存放，系统库及头文件。默认，自动会查找该路径。

productConfigs.mk，说明：
存放一些编译选项，一般不需要改。
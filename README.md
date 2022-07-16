Geomagic Touch力反馈设备的项目
一、控制Dobot主从控制
运行环境：Windows
运行步骤：
1、Geomagic Touch（原Phantom omni）驱动下载：https://support.3dsystems.com/s/article/Haptic-Device-Drivers?language=en_US
驱动下载成功进行配置Touch Smart Setup，可以检测位置、力反馈等信息。
2、配置：
     设置头文件包含目录：    属性>C/C++>常规>附加包含目录：该文件夹在您电脑上的文件路径H:\Geomagic_Touch_System\include
     添加库文件：           项目>属性>链接器>输入>附加依赖项 中添加定义该外部函数的库的名称 ：库的名称不用改
     设置附加库目录:       项目>属性>链接器>常规>附加库目录 中添加定义该外部函数的库的目录：该文件夹在您电脑上的文件路径Geomagic_Touch_System\lib
该文件夹在您电脑上的文件路径Geomagic_Touch_System\lib\Win32\Debug
二、Geomagic Touch简单的位置读取项目

# ReconstructMe 3D扫描教程 
## 软件下载地址：https://www.reconstructme.net/
  简介
ReconstructMe是一款3D重建软件，实时显示3D扫描模型的视觉效果。他兼容微软Kinect (Xbox和PC版)和华硕Xtion Pro版。ReconstructMe只支持Windows操作系统，运行环境要求使用高品质显卡。目前，软件分为免费的非商业版和付费的商业版。ReconstructMe在大型物体扫描方面呈现出色的性能，但不适合具有精致细节的小物件扫描。
目前，想要获得快速又完整的扫描也有一些不可避免的限制。首先，ReconstructMe仅适用与Windows系统，但可以通过虚拟机或在Mac上运行Boot Camp实现跨平台运行。你还需要一块相当高端的显卡来支持软件的运行。它对电脑安装的Open CL版本有要求（可以在显卡上运行指令的电脑代码库）。
提示
    ReconstructMe 采用图形化用户界面，与ReconstructMe控制台应用程序类似。它使用ReconstructMe SDK，提供免费的非商业版和付费版软件。我们下载到的免费版本无法正常运行，与相机不兼容，始终无法创建一个完整的扫描模型。
硬件要求
显卡：
   建议的显卡为
   AMD Radeon HD 6850
   NVIDIA GeForce GTX 560，
   在使用前建议用户将显卡升级到最新的版本，因为不同版本的显卡驱动会有影响；
3D传感器
   目前开发支持的kinect为以下四种
   Microsoft kinect for Windows
   Microsoft kinect for XBox
   Asus Xtion Pro Live (RGB and Depth)
   Asus Xtion Pro (Depth only）
   注意
    Microsoft kinect for Windows和XBOX kinect属于不同的版本，一般市场上买的玩游戏的都是XBOX的版本，Microsoft kinect for Windows为微软出品的供开发使用的产品，而且在安装的过程当中需要安装不同的驱动。
驱动安装
安装华硕的Xtion Pro即时和华硕的Xtion Pro的驱动
1. 下载32位OpenNI驱动包。
2. 首先安装OpenNI，再然后是SensorKinect，然后是SensorPrimesense。（在安装之前，一定要把原来kinect的驱动卸载掉）。
3.全部安装完成以后，重启，将你的Kinect连接上电脑，可以通过查看控制面板中的设备管理器，检查你的电脑是否已 经识别Kinect。
Microsoft Kinect for Windows
1.拔下传感器。
2.下载并安装微软KinectDSK1.8
3.重新启动您的系统。
4.插入传感器，等待操作系统检测到它。
Microsoft Kinect  Xbox
1.下载openNI32位驱动程序包。(openNI已经安装或想从官方网站下载软件包，确保你选择了32位的版本。)
2.拔下传感器。
3.卸载任何以前版本openNI和/或KinectSDK的的。
4.openNI安装使用安装驱动程序包中。
5安装SensorKinect发现openNI的驱动程序包。
6.重新启动您的系统。
7.插件传感器，等待操作系统检测到它。
安装ReconstructMe
    下载ReconstructMe
为你的Kinect（适于Xbox或Windows的Kinect）或者华硕Xtion（Pro或Pro Live）下载适合版本的ReconstructMe。
    提示
如果你以前就安装过ReconstructMe，现在想要升级，那么升级前确保卸载老的驱动程序。如果不卸载老版的驱动程序的话，升级后的ReconstructMe仍会继续寻找并使用旧的驱动程序，不断崩溃。

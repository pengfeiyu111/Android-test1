# Android-test1
# Android Studio安装教程

## 前提条件

- 首先在电脑上安装并配置JDK1.7或以上版本。
- 从官网或其他可靠来源下载Android Studio的安装文件。

## 安装步骤

1. 双击运行下载的.exe文件（推荐）或解压缩.zip文件并打开android-studio/bin文件夹，启动studio64.exe（对于64位计算机）或studio.exe（对于32位计算机）。
2. 点击Next，选择是否要导入之前的Android Studio设置，然后点击OK。
3. 选择安装类型，推荐选择Custom自定义，以便修改SDK的安装路径和界面主题。
4. 在自定义安装界面，选择您喜欢的界面主题，然后点击Next。
5. 在SDK组件设置界面，修改SDK的安装路径，避免放在系统盘中，然后点击Next。
6. 等待Android Studio下载并安装所需的SDK组件，这可能需要一些时间，取决于网络速度。
7. 安装完成后，点击Finish，启动Android Studio。
![image](https://user-images.githubusercontent.com/98248583/231820114-48d16623-ccff-4bd3-8709-782680737f85.png)

## 创建第一个工程

1. 在Android Studio欢迎界面，选择Start a new Android Studio project。
2. 在选择项目模板界面，选择Empty Activity，然后点击Next。
3. 在配置项目信息界面，输入您的应用名称，包名，保存位置等信息，然后点击Finish。
4. 等待Android Studio构建您的项目，并下载所需的Gradle文件。如果出现网络问题或错误提示，请检查网络设置和Gradle配置，并尝试切换到阿里云镜像地址。
5. 构建完成后，可以在编辑器中查看和修改您的代码，并在模拟器或真机上运行应用。

![image](https://user-images.githubusercontent.com/98248583/231820381-fa2ecdbc-3946-4cbd-801e-fc514b11299f.png)


## 安装和运行模拟器

1. 在Android Studio菜单栏中，依次选择Tools > AVD Manager。
2. 在AVD Manager界面中，点击Create Virtual Device...按钮。
3. 在选择硬件界面中，选择一个您想要模拟的设备类型和尺寸，然后点击Next。
4. 在系统映像界面中，选择一个要运行的Android系统版本，并点击Download按钮下载对应的系统映像文件。
5. 下载完成后，勾选同意协议，并点击Finish按钮。
6. 点击Next按钮进入模拟器配置界面，在这里您可以修改模拟器的名称，方向，内存等设置。
7. 点击Finish按钮创建模拟器，并在AVD Manager界面中查看模拟器的状态和信息。
8. 点击Play按钮启动模拟器，并在模拟器界面中操作和测试您的应用。
![image](https://user-images.githubusercontent.com/98248583/231820681-b3a67e2f-63ba-428f-86a8-aad6d167639c.png)


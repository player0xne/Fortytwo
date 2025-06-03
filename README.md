# Fortytwo

Ubuntu 上安装 Fortytwo 节点
打开终端 (Terminal)。

创建并进入安装目录：
您可以导航到您偏好的安装目录，或者运行以下命令，在您的主目录 (~) 下创建名为 Fortytwo 的文件夹并进入该文件夹：

```
mkdir -p ~/Fortytwo && cd ~/Fortytwo
```

下载节点包，解压缩，并执行安装脚本：
请在终端中依次运行以下命令：


```
curl -L -o fortytwo-console-app.zip https://github.com/Fortytwo-Network/fortytwo-console-app/archive/refs/heads/main.zip
unzip fortytwo-console-app.zip
cd fortytwo-console-app-main
chmod +x linux.sh && ./linux.sh
```

等待

![image](https://github.com/user-attachments/assets/63b66196-cec2-43f6-a68c-d6180859c255)
如果是新用户，选择输入1，如果是老用户，希望恢复节点，选择输入2

![image](https://github.com/user-attachments/assets/4b56266e-6f84-4269-99ed-d11c61f406d1)
输入你的邀请码

![image](https://github.com/user-attachments/assets/7545064a-3a3b-4bd6-8aa6-d0ce03d86bf5)
根据上面推荐，进行选择，或者直接输入0，自动根据推荐进行选择

![image](https://github.com/user-attachments/assets/50c2184a-3796-48c9-8924-92bd4b40d226)
这样表示节点正常运行了

备注：
1. 节点将保持完全运行，直到用户终止它或系统重新启动。您可以最小化终端窗口或切换到其他应用程序——节点将继续在后台运行。
2. Fortytwo 节点应用程序在每次启动时都会自动更新。当您启动节点时，应用程序会检查可用的最新版本，并在运行前安装任何更新。

停止您的节点
在运行节点的终端窗口中按 Ctrl+C 来终止节点进程。

重启 Fortytwo 节点 (Ubuntu)
打开终端 (Terminal)。

使用 cd 命令导航到节点的安装目录。如果节点安装在默认位置，运行：

```
cd ~/Fortytwo/fortytwo-console-app-main
```

运行节点启动脚本：
根据您提供的 Ubuntu 安装说明，安装时使用的是 linux.sh 脚本。因此，从逻辑上讲，重启节点时也应该使用相同的脚本。
我们建议您尝试运行：

```
./linux.sh
```

按照屏幕上的指示操作。
节点将会自动启动。

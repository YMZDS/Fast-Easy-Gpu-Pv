# FastGPUP in hyper-v
A WIP GUI app to make GPU-P way easier!
Based on : https://github.com/jamesstringerparsec/Easy-GPU-PV

这是一个gpu-pv的.net6.03的可视化程序，基于https://github.com/jamesstringerparsec/Easy-GPU-PV
可用于hyper-v显卡虚拟化
# Usage
The usage is simple, choose VM, choose GPU, slide the percentage you want to allocate of it and then press Add. 
For drivers you press Mount VHD, when done it will open disk management where you'll assign a letter for the mounted drive (if it doesn't already has one) and then you choose that drive letter on the tool and press "install/update driver" button. 

使用教程:
选择虚拟机名称，
选择gpu，
选择虚拟磁盘并挂载 以后将会弹出磁盘管理器，
请选择挂载的虚拟磁盘并右键分配盘符，
在软件中选择盘符并点击安装驱动，
等待十几秒将自动把宿主机驱动复制到虚拟机磁盘。

by:夜明珠大神
@YMZDS

# Troubleshooting
At the time of this last edit (12:02am GMT-4 16/3/2022) this wasn't tested outside my own PC, if you get an error related to Execution Policy you should execute:
"Set-ExecutionPolicy -ExecutionPolicy Unrestricted" on PowerShell


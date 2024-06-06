## USB闪存盘准备

提供的恢复映像文件位于以下目录中：

```
/home/partimag/DARwIn_Recovery_[恢复创建日期(yyyy-mm-dd)]
```

恢复映像链接：https://pan.baidu.com/s/1NFeG1IVUQGNuktuHoZlLYg?pwd=x77g 
提取码：x77g 

## 启动顺序

1. 将 USB 闪存盘连接到 USB 端口。
2. 打开 DARWIN-OP 并按 F2 键访问 Phoenix(tm) 设置实用程序press the F2 key to access Phoenix(tm) Setup Utility（DARWIN-OP 的 PC 系统 BIOS）。
3. 选择“启动”选项卡，然后选择“启动顺序”。选择 USB HDD 作为最高优先级。
4. 启动选择后，转到“退出”选项卡并选择“退出并保存更改”，选择“是”。

## 使用 Clonezilla 进行操作系统恢复

1. Clonezilla 的第一个选项：从菜单中选择默认选项
   - Clonezilla live（默认设置，VGA 800x600）
2. 选择语言：英语（默认）
   - en_US.UTF-8 英语
3. 配置控制台数据：从菜单中选择默认选项
   - 不要触摸键盘映射
4. 启动 Clonezilla：从菜单中选择默认选项
   - Start_Clonezilla 启动 Clonezilla
5. Clonezilla：从菜单中选择默认选项
   - device-image 使用图像处理磁盘或分区
6. 挂载Clonezilla镜像目录：选择以下内容
   - skip 使用现有的 /home/partimag (可写设备。例如硬盘/USB 驱动器)
   - <按“Enter”继续……> ：按“Enter”键
7. Clonezilla – 开源克隆系统 (OCS) ：从菜单中选择默认选项
   - 初学者初学者模式：接受默认选项
8. Clonezilla：选择模式：选择以下内容
   - restoredisk 将映像还原到本地磁盘
9. Clonezilla – 开源克隆系统 (OCS) | 模式：restoredisk：选择要恢复的映像文件
   - 例如）DARwIn_Recovery_2012-03-19 2012-0316-1405_sda
10. Clonezilla – 开源克隆系统 (OCS) | 模式：restoredisk：选择目标磁盘
    - sda 4096MB_4GB_NANDrive__ata-4GB_NANDrive_0000000000R1Q199982a
    - <按“Enter”继续……> ：按“Enter”键
    - < 您确定要继续吗？？ (y/n) > ：按“Y”键并按“Enter”键
    - < 让我再问你一次。你确定要继续吗？？ (y/n) > ：按“Y”键并按“Enter”键
11. 开始将图像恢复到设备。等待完成。
12. 完成修复后
    - <按“Enter”继续...>：按“Enter”键。
13. 现在您可以选择：选择 0 或 1
    - （0）关机
    - （1）重启
14. 确保移除 USB 闪存盘，然后重新启动 DARWIN-OP。

### 英文版Operating System Recovery with Clonezilla

1. The first option from Clonezilla: Select the default option from the menu
   - Clonezilla live (Default settings, VGA 800x600)
2. Choose language: English (default)
   - en_US.UTF-8 English
3. Configuring console-data: Select the default option from the menu
   - Don’t touch keymap
4. Start Clonezilla: Select the default option from the menu
   - Start_Clonezilla Start Clonezilla
5. Clonezilla: Select the default option from the menu
   - device-image work with disks or partitions using images
6. Mount Clonezilla image directory: Select the following
   - skip Use existing /home/partimag (Writable device. E.g. hard disk/USB drive)
   - < Press “Enter” to continue……> : Press “Enter” key
7. Clonezilla – Opensource Clone System (OCS) : Select the default option from the menu
   - Beginner Beginner mode: Accept the default options
8. Clonezilla: Select mode: Select the following
   - restoredisk Restore_an_image_to_local_disk
9. Clonezilla – Opensource Clone System (OCS) | Mode: restoredisk : Choose the image file to restore
   - Ex) DARwIn_Recovery_2012-03-19 2012-0316-1405_sda
10. Clonezilla – Opensource Clone System (OCS) | Mode: restoredisk : Choose the target disk
    - Sda 4096MB_4GB_NANDrive__ata-4GB_NANDrive_0000000000R1Q199982a
    - < Press “Enter” to continue …… > : Press “Enter” key
    - < Are you sure you want to continue? ? (y/n) > : Press ‘Y’ key and Press “Enter” key
    - < Let me ask you again. Are you sure you want to continue? ? (y/n) > : Press ‘Y’ key and Press “Enter” key
11. Starting to restore image to device. Wait until done.
12. After completing restoration
    - < Press “Enter” to continue…> : Press “Enter” key.
13. Now you can choose to: Choose 0 or 1
    - (0) Poweroff
    - (1) Reboot
14. Make sure you remove the USB thumbdrive, and reboot the DARWIN-OP.

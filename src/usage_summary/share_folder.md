# 共享文件夹

## 启动共享文件夹

安装了`VMWare Tools`后，再去开启`共享文件夹`

`文件夹共享`默认是关闭的：

![vmware_settings_share_folder](../assets/img/vmware_settings_share_folder.png)

点击：`总是启用`

![vmware_share_always_enabled](../assets/img/vmware_share_always_enabled.png)

会进入：添加文件夹向导

![vmware_welcome_add_folder](../assets/img/vmware_welcome_add_folder.png)

命名共享文件夹：

![vmware_share_folder_name](../assets/img/vmware_share_folder_name.png)

选择一个路径，起个名字，即可：

![vmware_folder_path_and_name](../assets/img/vmware_folder_path_and_name.png)

指定共享文件夹属性

此次勾选：`启用此共享`

![vmware_folder_enable_share](../assets/img/vmware_folder_enable_share.png)

即：

![vmware_share_folder_settings](../assets/img/vmware_share_folder_settings.png)

## 去客户端系统找到共享出的文件夹

设置好之后，去客户端操作系统找到对应共享出来的文件夹。

此处的macOS中，找到：`VMware Shared Folders`

`macOS`->`Finder访达`->`前往`->`电脑`->`VMware Shared Folders`

![macos_finder_go_computer](../assets/img/macos_finder_go_computer.png)

然后是看不到共享文件夹的：

![macos_no_shared_folder](../assets/img/macos_no_shared_folder.png)

需要重启macOS虚拟机后，才能看到：

![macos_see_shared_folder](../assets/img/macos_see_shared_folder.png)

然后去创建文件夹和文件，即可共享：

客户端操作系统macOS中新建文件夹：

![macos_new_folder](../assets/img/macos_new_folder.png)

主机host端系统Win中能看到了：

![host_win_see_new_folder](../assets/img/host_win_see_new_folder.png)

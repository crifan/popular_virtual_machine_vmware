# 安装后所支持的功能

此处介绍`macOS`的`VMWare Tools`=`darwin.iso`安装后的效果，即支持了哪些功能：

## 剪贴板共享

剪贴板共享是有用的：

比如从虚拟机客户端macOS中复制了内容

![macos_copy_from_client](../../../assets/img/macos_copy_from_client.jpg)

是可以粘贴到主机Windows中的。

## 拖放复制文件

以及通过拖放实现复制文件也是支持的：

![macos_win_drag_copy_file](../../../assets/img/macos_win_drag_copy_file.png)

注：

首次拖放文件，会触发`vmware-tools-deamon`的进程授权弹框：

![macos_vmware_tools_deamon_auth_popup](../../../assets/img/macos_vmware_tools_deamon_auth_popup.jpg)

去设置中给与权限即可：

去 `设置`->`安全与隐私`->`隐私`->`辅助功能`：

![macos_security_auxiliary](../../../assets/img/macos_security_auxiliary.jpg)

点击勾选：`vmware-tools-deamon`

![macos_select_vmware_tools_deamon](../../../assets/img/macos_select_vmware_tools_deamon.jpg)


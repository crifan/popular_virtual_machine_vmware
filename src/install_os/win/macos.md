# 安装macOS系统

此处介绍在Win中用VMWare安装macOS操作系统。

## 前提

如前所述，已经做好了准备工作：

* Win中安装了VMWare
  * 详见前面章节：[Win中安装VMWare](https://book.crifan.com/books/popular_virtual_machine_vmware/website/download_install/win.html)
* 且在VMWare创建了macOS的虚拟机
  * 详见前面章节： [创建macOS虚拟机](https://book.crifan.com/books/popular_virtual_machine_vmware/website/create_machine/win/macos.html)
* 已找到了合适版本的macOS的镜像文件（`ISO`或`cdr`）：`MacOS_Mojave_10.14.4_x5(www.w3h5.com推荐下载这个).iso`
  * 详见前面章节：[macOS的安装镜像](https://book.crifan.com/books/popular_virtual_machine_vmware/website/search_image/macos_iso.html)

挂载iso镜像：

`虚拟机设置`->`CD/DVD(SATA)`->`连接`->`使用ISO镜像文件`->选择之前找到的：`MacOS_Mojave_10.14.4_x5(www.w3h5.com推荐下载这个).iso`

![vmware_use_macos_ios](../../assets/img/vmware_use_macos_ios.png)

去启动虚拟机，安装macOS系统：

![vmware_start_macos_machine](../../assets/img/vmware_start_macos_machine.png)

## 安装MacOS

macOS启动中：

![vmware_launching_macos](../../assets/img/vmware_launching_macos.png)

进入：语言选择界面

![macos_choose_language_page](../../assets/img/macos_choose_language_page.jpg)

移动键盘上下键，选择：`简体中文`

![macos_choose_language_zhcn](../../assets/img/macos_choose_language_zhcn.png)

进入 macOS实用工具 页：

![macos_util_page](../../assets/img/macos_util_page.jpg)

说明：此处需要先去（用`磁盘工具`）格式化硬盘，能让macOS识别出硬盘，才能继续安装。

所以点击`磁盘工具`：

![macos_click_disk_tool](../../assets/img/macos_click_disk_tool.jpg)

可以看到磁盘列表。

默认选择的是磁盘是：`VMWare Virtual SATA Hard Drive Media`，状态是：`未初始化`

![macos_disk_virutal_sata](../../assets/img/macos_disk_virutal_sata.jpg)

再点击`抹掉`，出现确认弹框：

要抹掉 VMWare Virtual SATA Hard Drive Media 吗？

确保选项是：

* 名称：`MacOS10.14`
  * 随便起个名字即可
* 格式：`Mac OS 扩展（日志式）`
* 方案：`GUID分区图`

![macos_erase_disk](../../assets/img/macos_erase_disk.jpg)

正在抹掉 并创建

![macos_is_erasing_create_disk](../../assets/img/macos_is_erasing_create_disk.jpg)

格式化完毕后，可以看到状态变成：`PCI 内置物理宗卷 Mac OS 扩展（日志式）`

![macos_disk_formatted](../../assets/img/macos_disk_formatted.jpg)

点击左上角**红色x**按钮关闭退出窗口：

![macos_left_upper_red_close](../../assets/img/macos_left_upper_red_close.jpg)

回来之前界面，选择：`安装macOS`

![macos_install_macos](../../assets/img/macos_install_macos.jpg)

继续安装：

若要设置安装 macOS Mojave，请点按”继续“

![macos_start_install_mojave](../../assets/img/macos_start_install_mojave.jpg)

若要继续安装软件，您必须同意软件许可协议中的条款

点击`同意`

![macos_accept_use_aggrement](../../assets/img/macos_accept_use_aggrement.jpg)

出现弹框，点击`同意`

![macos_popup_accept](../../assets/img/macos_popup_accept.jpg)

macOS Mojave 将安装在磁盘 "MacOS10.14"

点击`安装`

![macos_will_install_mojave](../../assets/img/macos_will_install_mojave.jpg)

开始安装过程：

![macos_installing_remain](../../assets/img/macos_installing_remain.jpg)

期间可能会重启，之后继续安装：

![macos_reboot_continue_installing](../../assets/img/macos_reboot_continue_installing.png)

然后进入`欢迎使用`界面：

![macos_welcome_use_page](../../assets/img/macos_welcome_use_page.jpg)

选择：`中国大陆`

![macos_choose_china_mainland](../../assets/img/macos_choose_china_mainland.jpg)

进入：`选择您的键盘`

此处选择：

* 选择键盘布局：`简体中文`
* 您喜欢哪些输入方式：`简体拼音`

![macos_select_your_keyboard](../../assets/img/macos_select_your_keyboard.jpg)

您如何连接？

选择电脑连接到互联网的方式：

* 此处选择：
  * 本地网络（以太网） = 有线网络

![macos_how_connect_local](../../assets/img/macos_how_connect_local.jpg)

您的互联网连接

![macos_your_internet_detail](../../assets/img/macos_your_internet_detail.jpg)

继续到`数据与隐私`

![macos_data_privacy](../../assets/img/macos_data_privacy.jpg)

传输信息到这台Mac

此处选：`现在不传输任何信息`

![macos_transfer_data_to_mac](../../assets/img/macos_transfer_data_to_mac.jpg)

使用您的Apple ID登录

此处不用，所以点击：`稍后设置`

![macos_later_set_apple_id](../../assets/img/macos_later_set_apple_id.jpg)

继续点击`跳过`

![macos_jump_over_apple_id](../../assets/img/macos_jump_over_apple_id.jpg)

条款和条件，点击`同意`

![macos_terms_and_conditions](../../assets/img/macos_terms_and_conditions.jpg)

我已经阅读并同意 软件许可协议

![macos_has_read_aggrement](../../assets/img/macos_has_read_aggrement.jpg)

创建电脑账号

![macos_create_compute_account](../../assets/img/macos_create_compute_account.png)

输入自己的用户名和密码：

![macos_input_account_info](../../assets/img/macos_input_account_info.png)

快捷设置

![macos_fast_settings](../../assets/img/macos_fast_settings.jpg)

选取您的外观

![macos_choose_look_like](../../assets/img/macos_choose_look_like.jpg)

正在设置您的Mac

![macos_do_setting_for_your_mac](../../assets/img/macos_do_setting_for_your_mac.png)

终于进入Mac桌面了：

![macos_into_mac_desktop](../../assets/img/macos_into_mac_desktop.jpg)

去看看`关于本机`：

![mac_about_this_computer](../../assets/img/mac_about_this_computer.jpg)

![mac_about_version_details](../../assets/img/mac_about_version_details.jpg)

此处信息是：

* `macOS Mojave`
  * 版本：`10.14.4`
* Mac
  * 处理器：`2.77GHz` 未知
  * 内存：`3.02GB` DRAM
  * 启动磁盘：`MacOS10.14`
  * 图形卡：显示器 `3MB`
  * 序列号：`VMfvNykazWi`

## 安装完成后

安装完成后，就是正常的使用macOS了。

此处关闭虚拟机后是：

![macos_machine_after_closed](../../assets/img/macos_machine_after_closed.png)

点击：`开启此虚拟机`，即可启动macOS，进去登录页面：

![macos_login_page](../../assets/img/macos_login_page.jpg)

登录后，再次进入系统：

![macos_again_into_desktop](../../assets/img/macos_again_into_desktop.jpg)


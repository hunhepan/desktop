# 混合盘 (HunHePan)

## 下载使用

### Windows 用户
1. 在 Release 页面下载最新版本的 Windows 便携版（Portable Version）
2. 解压下载的压缩包到您想要的位置
3. 直接运行解压后的文件夹中的 hunhepan.exe 即可使用
4. 建议创建快捷方式到桌面，方便后续使用

### Mac 用户

#### Apple Silicon (M1-M4) Mac
1. 在 Release 页面下载 Mac ARM 版本
2. 将应用拖入 Applications 文件夹
3. 首次运行可能提示应用程序已损坏，请按以下步骤操作：
   - 打开终端(Terminal)：
     * 使用 Spotlight 搜索（⌘ + 空格键），输入 "Terminal"
     * 或在应用程序/实用工具中找到 Terminal
   - 复制粘贴以下命令并回车：
     ```bash
     xattr -cr /Applications/hunhepan.app
     ```
   - 现在您可以正常打开应用了

#### Intel Mac
1. 在 Release 页面下载 Mac Intel 版本
2. 将应用拖入 Applications 文件夹
3. 如遇到应用程序已损坏的提示，请按照上述 Apple Silicon Mac 的步骤 3 操作


## 测试规则

你可以到 https://github.com/hunhepan/hunhepan-rule-template 下载zip包，然后到本地解压后，在软件【规则管理】、【目录导入】中选择解压后的dist/目录。

或者 直接【规则管理】、【通过git导入】，输入地址：https://github.com/hunhepan/hunhepan-rule-template 

## 常见问题

如果您在使用过程中遇到任何问题，请查看我们的问题反馈页面或提交新的 Issue。

## 更新日志

请查看 Release 页面了解每个版本的更新内容。

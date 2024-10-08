# Tools Help
## File Manager

---

![文件管理面板](/files/doc/help/file_manager/file_manager_1_5_9.jpg)

### 简介

---

- 文件管理面板位于侧边面板，点击侧边栏按钮，打开侧边面板

![侧边栏按钮](/files/doc/help/file_manager/img.png)

- 默认打开路径 ```/storage/emulated/0```
- 文件管理面板，上方为功能区，下方为文件路径

![文件管理面板](/files/doc/help/file_manager/img_1.png)

### 按钮功能及使用方法

---

1. ```F``` 打开默认PC下载保存文件夹
2. ```UP``` 上传剪贴板中文件至**当前**目录
      > 注意，若使用粘贴手势，文件将粘贴至默认（MYScrcpy）目录下
3. ```DLD``` 下载选中文件
4. ```DEL``` 删除选中文件
5. ```0 selected``` 选中文件数，鼠标悬浮上可看到选中列表
6. ```A``` 全部选中
7. ```C``` 取消选中
8. 过滤框，过滤当前目录下文件
   1. xx,xx 并选
   2. -xx 排除
      > 注意，全部选中此处**不**生效！
9. ```R``` 刷新当前目录
10. ```..``` 返回上级
11. 当前目录
12. ```cb``` 序号&功能列
    - 左键序号，选中当前路径/文件，支持多选
    - 右键序号，进行预览（文件 < 100MB），下载及删除
13. ```path``` 目录/文件，
- 目录前带 ```>``` 符号，点击进入该目录
- 鼠标悬浮可查看详细信息

### 适用场景

---

- 无线ADB连接（推荐）
- 有线连接
	- 可开启设备文件传输模式，使用系统自动文件浏览器管理
	- 也可使用本文件管理器进行管理，上传下载预览等，无需反复切资源管理器窗口
- 配合MYScrcpy，在手机上进行图片编辑、批量文件传输等场景下使用
- 在 termux 中运行项目，编辑源代码、上传下载文件时使用
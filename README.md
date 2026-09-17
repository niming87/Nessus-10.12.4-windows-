# Nessus-10.12.4-windows-pluging 配置教程
## 安装步骤
### 方法一
1. 双击msi文件
2. 一直下一步安装好即可
3. 会自动打开网页，点击 connect ssl 此时什么都不勾，直接下一步
4. 选择Register for Nessus Essentials
5. 填入名字（建议英文）和 工作邮箱（gmail也可以），点击 register
6. 此时邮箱会发送一个验证消息，点击 验证即可，然后 单击我们网站的 验证按钮
7. 然后 点击继续，此时设置账号和密码，建议admin 和 admin 简单好记，然后下一步，然后开始初始化下载安装中。
8. 此时可以等待下载完成，但是会很漫长，我们的压缩包里面提供了插件压缩包。
9. 先关掉网页，然后重新访问网页，重新进入等待初始化 然后输入账号admin 密码 admin ，然后下一步，然后会进入主页
10. 点击 setting —— 然后点击Software Update —— Manual Software Update——  Upload your own plugin archive —— Continue
11. 浏览并选择你打包好的 .tar.gz 或 .tgz 文件，点击 Open（打开）。Nessus 会自动上传并更新插件库。
### 方法二
1. 进入到Nessus 安装目录，进入该命令行终端 执行下列命令

```cmd
nessuscli update <你的插件包文件名>.tar.gz

```
## 结尾
- 等待软件插件更新好后，关掉网页重新访问，然后就能使用了

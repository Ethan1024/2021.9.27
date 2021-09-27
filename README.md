# github 使用git上传本地项目
下载安装 git :https://gitforwindows.org/
注册github账号 新建项目：Create a new repository 填写项目名称、描述
打开Git Bash：它基于CMD，在CMD的基础上增添一些新的命令与功能，平时主要用这个
配置git上的用户名和邮箱：git config --global user.email "you@example.com"   git config --global user.name "Your Name"
打开本地项目所在文件夹，右键Git Bash Here，自动出现Git Bash窗口，输入git clone 项目地址(git clone https://github.com/Ethan1024/LoRa-transmit-receive.git)
本地文件夹新增“LoRa-transmit-receive”文件夹，复制要上传的文件到这里
cd LoRa-transmit-receive
git add .
gir commit -m "Ethan"
git push -u origin master

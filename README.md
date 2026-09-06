# Splash_builder
搭建Splash环境

# 1.安装DOCKER   
官网地址https://www.docker.com,下载电脑系统相对应的文件。双击Docker Desktop Installer.exe文件，默认安装。     
# 2.安装Splash   
命令窗口输入（docker pull scrapinghub/splash)命令，回车安装即可。
# 3.启动Splash
docker run -p 8050:8050 scrapinghub/splash
# 4打开Splash
在浏览器中输入http://lcoalhost:8050/

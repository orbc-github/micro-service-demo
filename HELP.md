#目录：

orbc
    demo
        eureka-8375 : eureka 演示
    project
    
# git 上传代码到 github

先登录到git

    git config --global user.name "your name"（注册时填写的名字）

    git config --global user.email "email@qq.com"（自己的邮箱）
    
    1. git init //初始化仓库

    2. git add .(文件name) //添加文件到本地仓库

    3. git commit -m "first commit" //添加文件描述信息

    4. git remote add origin + 远程仓库地址 //链接远程仓库，创建主分支   
       git remote rm origin 移除连接

    5. git pull origin master // 把本地仓库的变化连接到远程仓库主分支

    6. git push -u origin master //把本地仓库的文件推送到远程仓库     
    
      



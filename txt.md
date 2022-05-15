    git add . 将所有文件添加到暂存区
    复合属性 添加到暂存区并且提交  git commit -a -m '描述信息'
    
    使用HTTPS发送  如果用户密码输入错误 
    可以去 控制面板\用户帐户\凭据管理器\编辑普通凭据  删除账户凭证

    账户密码都正确的情况下，还需要生成一个个人的登录token

    1、git remote add origin https://github.com/DongXuWei/project_001.git
    remote: 表示远程的意思
    add: 添加
    origin: 就是后面git仓库地址的别名
    远程仓库地址:https://github.com/DongXuWei/project_001.git

    2、git branch -M main (把默认的master分支名称改成main)

    3、git push -u origin main 
       表示第一次本地仓库朝远程仓库提交的时候
       push: 表示推送的意思
       -u: 表示第一个推送的时候 必须添加-u参数
       origin: 就是表示你要把工程往哪儿推 这个名字代表的就是远程仓库的地址

    *后面修改完代码之后 再次提交的时候 只需要 git push即可
    
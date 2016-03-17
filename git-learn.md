#git学习

ssh 密钥的生成，方便提交代码

ssh-keygen -t rsa -C "abc@gmail.com"
生成后，拷贝到 github上边 不用输入密码了

切换ssh
git remote -v
github上 复制ssh信息
git remote set-url origin <你复制的url>

###将一个分支推到远端
git push origin test

###查看分支信息
git branch

### 切换分支
git checkout test

###git 命令执行流程
git clone
git add xxx
git commit -m'xxxx'
git push

###注意事项
clone是本地没有repository时，将远程repository整个下载过来。
pull是本地有repository时，将远程repository里新的commit数据(如有的话)下载过来，并且与本地代码merge。

不要用git pull，用git fetch和git merge代替它。

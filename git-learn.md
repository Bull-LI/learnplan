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

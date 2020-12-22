# ssh git
* ssh-keygen -t rsa -C "your_email@example.com"
* 
git config --global user.name "DJlv"   
git config --global user.email "2743535685@qq.com"  
# 提交代码  
git commit -m "你的提交注释"    
# 链接远程仓库  
git remote add origin git@github.com:shutongit/项目名称.git
   -  1、 在github上创建项目
   - 2、 使用$ git clone https://github/xx账号/xx项目.git克隆到本地
   -  3、 编辑项目
   -  4、 $ git add .(将改动添加到暂存区)
   -  5、 $ git commit –m”提交说明”
   -  6、 $ git push origin 将本地更改推送到远程master分支

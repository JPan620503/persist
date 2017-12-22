Username for 'https://github.com': 375358238@qq.com
Password for 'https://375358238@qq.com@github.com':fzl620503f!!!

一、生成公钥和验证
ssh-keygen -t rsa -C "youremail@.com"
ssh git@github.com 或 ssh -T git@github.com

二、创建文件
1、mkdir runoob-git-test                       # 创建测试目录
2、cd runoob-git-test/                         # 进入测试目录
3、echo "# 菜鸟教程 Git 测试" >> README.md     # 创建 README.md 文件并写入内容
4、ls                                          # 查看目录下的文件
5、git status -s                               # 查看项目的当前状态。                                      

5、 git init                                   # 初始化
6、 git add README.md                          # 添加文件
7、 git commit -m "添加 README.md 文件"        # 提交并备注信息

三、删除远程仓库文件
1、git rm -- cached                            # 路径+文件名 
2、git commit -m "注释"                        # 提交到本地仓库
3、git push                                    # 推送到github

三、推送到github
git remote add origin [url]
git push -u origin master
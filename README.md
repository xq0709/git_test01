1.先在自己的github上面创建一个仓库，然后再复制仓库的链接，该步骤就不过多缀述。(git已安装)

2.在本地选择要上传的文档，并在该文档下打开git bash here ，如下图所示![image](https://github.com/xq0709/git_test01/assets/37392093/cffd21d5-e2f6-4fa1-b88b-ebfdd2dae281)

3.git init初始化之前要先连接自己的邮箱，因为 Git 是分布式版本控制系统，所以需要填写用户名和邮箱作为一个标识。
  建议 Git 的用户名和邮箱与 GitHub 的用户名和邮箱保持一致
  
  git config --global user.name "你的用户名"
  
  git config --global user.email "你的邮箱"  
  
![image](https://github.com/xq0709/git_test01/assets/37392093/eb6cadaa-50b9-48ad-ad67-2216927d41eb)

4.将项目所有的文件添加到仓库中，输入git add . 如下图所示：

![image](https://github.com/xq0709/git_test01/assets/37392093/b1322366-3d14-485b-899b-8f5add627e00)

5.接下来 git commit -m “提交的信息”    双引号里面的内容可以根据个人的需要修改

![image](https://github.com/xq0709/git_test01/assets/37392093/e6b9ca49-c2a5-415f-a045-33a8a9bca4fe)

6.将本地文件与仓库连接（在第一步中复制的链接）：git remote add origin 后面 粘贴复制的仓库地址。如图所示：

![image](https://github.com/xq0709/git_test01/assets/37392093/5d32cb81-18fa-4ce7-bed6-cc2340fb1a1c)

7.最后一步，输入git push -u origin master，意思是把代码上传到 GitHub仓库的意思 稍等一会。如下图所示：

![image](https://github.com/xq0709/git_test01/assets/37392093/a4462600-d267-4931-ad5d-6937648154c6)

8.在GitHub上找到自己创建的master 就可以看到本地文档的内容，至此，上传成功。 

关于Java的学习资源

1.在https://github.com   new repository

2.在eclipse中new project  比如:Test项目

3.右击"Test"->Team->share project...  ->select a repository type：Git
eclipse提交项目到github

勾选  Use or create repository in parent folder of project
eclipse提交项目到github

点击  Create Repository  ->  Finish
这时候打开在workspace中的Test目录会发现多了一个.git文件夹。

4.右击"Test"->Team->commit 本地提交

5.再右击"Test"->Team->Remote->Push
eclipse提交项目到github

URI就是github上面指定的地址:
eclipse提交项目到github
username和password就是github网站的用户名和密码

5.finish
eclipse提交项目到github
source ref 选择 refs/heads/master  destination ref会自动填充，点击  Add Spec勾选Focus update
开始提交。

6.可以刷新网页查看提交的代码了。。。

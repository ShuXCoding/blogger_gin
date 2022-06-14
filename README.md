# BloggerGin
利用gin框架＋gorm实现的一个前后端分离的个人博客项目
## 项目的介绍
使用Go语言实现一个前后端分离的个人博客项目，实现了用户登陆，注册，在用户界面实现了发布评论，查看文章。在后台管理页面实现了用户管理模块（增加用户、删除用户、更改用户权限），评论管理模块（查看评论、上线评论、删除评论），文章管理模块（发布文章、修改文章、删除文章）。
### 项目的部署及使用
1. 将项目下载下来，对/Congfig/config.ini文件进行配置更改
2. sudo go mod tidy :依照go.mod文件将依赖进行下载
3. go run main.go :项目启动

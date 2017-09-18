1.管理员打开cmd,全局安装路径为C:/Users/ash> (此时我的电脑系统为Windows10)

2.执行全局安装命令(我特么的一直没弄明白这个全局安装的意思,导致一直安装不成功,全局安装看上面,就是让这个电脑都可以用,不是指的某个盘根路径,也不能随变到其他盘执行命令)
就是它==> npm install webpack -g

3.用命令跳到你想安装的项目路径,我这次放到了E盘,所以就 C:\Users\ash>e:

4.然后建立一个项目文件夹,你手动建用命令的建都行 mkdir webpack-project

5.然后你要初始化这个项目目录  npm  init  从空目录生成一个package.json 就这一个文件,网上说的还有node_modules都他们在唬老子,那是下一步生成的

6.现在本地安装 就是它==> npm  install webpack --save-dev  这回有那个node_modules文件了 还多了一个package-lock.json文件

7.ok 现在可以用webpack命令了 用webpack -h查看一下信息吧

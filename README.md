# MyCDN
differencer的素材库


（支持20M以内的图片、视频、js、css等）


原理：将github上的资源转为快速访问网址
https://cdn.jsdelivr.net/gh/你的用户名/你的仓库名@发布的版本号/文件路径

**确切的说@后面应该是每次发布版本时填写的 tag！！！！！！！！ title 反而无所谓，填什么都可以！！！！**

https://cdn.jsdelivr.net/gh/differencer/MyCDN@1.0.4/img/logo/upyun.png

https://cdn.jsdelivr.net/gh/differencer/MyCDN/img/logo/upyun.png
不加 版本号 默认最新版本 

更新方法

- 1、【第一次或覆盖用】本地 MyCDN 文件夹上一级目录 
```
git bash：git clone https://github.com/differencer/MyCDN.git
```
- 2、【上传更新文件】
```
git status                    //查看状态
git add .                     //添加所有文件到暂存区
git commit -m '第一次提交'      //把文件提交到仓库
git push                      //推送至远程仓库
```



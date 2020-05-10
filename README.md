##### 关于
基于hexo构建的博客demo，主题使用[Butterfly](https://github.com/jerryc127/hexo-theme-butterfly)
##### 配置问题
###### 1.仓库的命名问题
- 通过修改配置文件root路径值，不必将仓库名设为username.github.io
###### 2.部署工具
- npm install hexo-deployer-git --save
- 可以实现同时向github, gitee, coding推送网页静态文件
###### 3.shh key设置
- 设置之后需运行代码令配置生效
```
ssh -T git@e.coding.net
ssh -T git@github.com
ssh -T git@gitee.com
```
###### 4.用到的hexo命令
```
hexo init：初始化
hexo g：生成网页静态文件
hexo s：本地运行
hexo d：推送到远程仓库
hexo clean：清楚已生成的内容
```

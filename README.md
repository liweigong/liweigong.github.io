#使用hexo模板和indigo主题创建


##使用中的一些问题.


### README.md每次都被覆盖的问题.

参考:http://www.jianshu.com/p/dc94b1ece326

但是部署后会覆盖掉github上的CNAME和README.md，需要在hexo的source目录添加CNAME和README.md，但是执行hexo generate后README.md会生成README.html，因此需要配置下，不让其渲染README.md。
修改Hexo目录下的_config.yml

```skip_render: README.md```



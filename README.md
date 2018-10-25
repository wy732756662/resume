## 本地搭建

在本地安装[Jekyll](https://jekyllrb.com/).
然后在项目目录执行`jekyll s`命令,如下

```bash
[root@localhost ~]# jekyll s
Configuration file: C:/..../resume.io/_config.yml
            Source: C:/..../resume.io
       Destination: C:/..../resume.io/_site
 Incremental build: disabled. Enable with --incremental
      Generating...
                    done in 0.371 seconds.
  Please add the following to your Gemfile to avoid polling for changes:
    gem 'wdm', '>= 0.1.0' if Gem.win_platform?
 Auto-regeneration: enabled for 'C:/..../resume.io'
    Server address: http://127.0.0.1:4000/resume.io/
  Server running... press ctrl-c to stop.
```

然后可以访问[http://127.0.0.1:4000/resume.io/](http://127.0.0.1:4000/resume.io/)来访问本地的服务了。


## 参考

本简历模板基于[Certy](http://sc.chinaz.com/moban/170307198220.htm)修改而来。保留了所有的样式，基于Jekyll重构了页面框架，并去掉了一些没有必要的内容，整合一页简历。

## 开源协议
[MIT](https://gitee.com/xiaodan_yu/resume.io/blob/master/LICENSE)

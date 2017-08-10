# 安装
安装依赖包

```
$npm install
```

# 使用
用于做练习的脚手架，在该目录执行如下命令。

```
$gulp
```

然后访问`http://localhost:8000/index.html`，然后编辑`src/index.html`及其引用的文件，将可以在浏览器看到变化。

# 使用
`gulpfile`有以下功能:

* vendor 将第三方库(jQuery, bootstrap)移到目标目录(dist)
* sass 将样式文件(src/sass/)编译后放到目标目录(dist)
* html 将src/index.html编译后放到目标目录(./)
* watch 监听src目录的文件变化
* serve 启动服务器，监听8000端口，方便调试
* default 将以上命令按顺序执行一遍

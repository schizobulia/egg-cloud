# egg-cloud

一个简单实用的在线云盘

### 技术栈
- Egg.js
- Bootstrap
- 无需使用数据库之类的

### 版本要求
- node>v10.10.0


### 开发
- 所有的文件相当于在/mirror 下
- 部署之后推荐使用ftp对文件进行操作
- 如果需要加密访问或者实现在浏览器中对文件操作可以[参考](https://github.com/508lab/outbreak)
- 欢迎PR
```bash
$ npm i
$ npm run dev
$ open http://localhost:7001/
```

### Docker
```bash
$ docker build -t egg:cloud .
$ docker run -it -p 7001:7001 egg:cloud
$ docker exec -it container_id  /bin/bash
$ npm start && exit
```


### 相关链接
- [egg](https://eggjs.org)

----------
让代码简单一点

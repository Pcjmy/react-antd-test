## README

react-antd-test

### Ant Design源码调试

1.下载[Ant Design](https://github.com/Pcjmy/ant-design)项目，执行README构建中的命令
2.将`dist`目录下会生成的`antd.js`和`antd.js.map`复制到本项目的`node_modules/antd/dist`下，清一下`babel-loader`的缓存，删除整个`.cache`目录
3.组件从`antd/dist/antd`引入

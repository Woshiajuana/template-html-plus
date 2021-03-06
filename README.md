# template-multi-html

> webpack 多页面打包，构建页面更方便

## Author

> Ajuan <979703986@qq.com>

## 目录结构

```
project
├── build                                   // 打包脚本目录
|   ├── art-template-loader.js              // art-template loader 改写了一点东西，可以忽略一些文件。
|   ├── utils.js                            // 工具 js
|   ├── webpack.base.config.js              // webpack 基础配置
|   ├── webpack.dev.config.js               // webpack 开发环境配置
|   ├── webpack.hot.config.js               // webpack devserver 配置
|   ├── webpack.prod.config.js              // webpack 生产环境配置
├── dist                                    // 打包出来的js目录（用户部署生产）
|   ├── assets                              // 静态文件目录
│   |   └── css                             // 样式资源
│   |   └── images                          // 图片资源
│   |   └── js                              // js资源
│   |   └── lib                             // 三方库资源
│   |   └── media                           // 其他资源
|   ├── [xxx].html                          // 页面
├── node_modules                            // 依赖
├── src                                     // 项目开发目录
│   ├── assets                              // 静态资源目录
│   ├── config                              // 项目配置目录
│   ├── utils                               // 工具目录
│   ├── views                               // 页面目录
│   |   └── page
├── .babelrc                                // babel 配置文件
├── .editorconfig                           // 代码格式文件
├── .gitignore                              // 忽略文件
├── package.json
├── package-lock.json
├── README.md
```

## 操作命令

> npm run dev   => 开发页面，自动刷新

> npm run build:dev  => 测试打包项目

> npm run build:prod => 生产打包项目


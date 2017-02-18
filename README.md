Cloud-UI
===

## 环境依赖:
- node v4.x+ (官网下载地址:http://nodejs.org)


## 运行
1. 安装 `nodejs`
2. 全局安装 `npm`: npm install gulp -g
3. 在项目中安装 `npm`: npm install
4. 运行 `gulp build`


## 目录结构及文件
<pre>
└─cloudUI
    ├─dist         ---> 生成目录
    │  ├─css
    │  └─fonts
    ├─src          ---> 开发目录
    │  ├─asset
    │  ├─css
    │  ├─fonts
    │  └─less
    └─docs         ---> 文档目录
       ├─css
       ├─js
       └─less
</pre>

------------

**source**: 

**node_modules**: npm 工具目录

**cloudUI**: 开发目录

**dist**: 优化压缩后的交付目录

**gulpfile.js**: 自动化构建脚本

**package.json**: 项目信息

License
-------


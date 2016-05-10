# 环境配置
1. 去[nodejs.org](https://nodejs.org/en/)下载node
2. 去[git-scm.com](https://git-scm.com/download/)下载git
3. 打开<code>git bash</code>命令窗口或者cmd窗口
4. 运行<code>git clone https://github.com/jxmyh99/wl-gulp</code>即可
5. 这里推荐您使用<code>cnpm</code>来下载各个组件。天朝，你懂的。

# 常用组件
    "babel-core": "^6.8.0",
    "babel-preset-es2015": "^6.6.0",
    "babel-register": "^6.8.0",
    "browser-sync": "^2.12.5",
    "del": "^2.2.0",
    "gulp": "^3.9.1",
    "gulp-autoprefixer": "^3.1.0",
    "gulp-babel": "^6.1.2",
    "gulp-cache": "^0.4.4",
    "gulp-cssnano": "^2.1.2",
    "gulp-eslint": "^2.0.0",
    "gulp-htmlmin": "^2.0.0",
    "gulp-if": "^2.0.1",
    "gulp-imagemin": "^3.0.0",
    "gulp-jade": "^1.1.0",
    "gulp-load-plugins": "^1.2.2",
    "gulp-plumber": "^1.1.0",
    "gulp-sass": "^2.3.1",
    "gulp-size": "^2.1.0",
    "gulp-sourcemaps": "^2.0.0-alpha",
    "gulp-uglify": "^1.5.3",
    "gulp-useref": "^3.1.0",
    "main-bower-files": "^2.13.0",
    "wiredep": "^4.0.0"
# 支持功能
1. jade模板引擎
2. es6的支持，会自动转换为es5
3. sass的支持

# 一些问题
- 后面的可能加入json-serve
    https://github.com/typicode/json-server
    这个可以更好的调试后台的数据
- 针对不同的业务生成不同的目录。
- bower的目录的支持问题
- 后面会把这个加入到yeoman-generator的脚手架去，这样就会更简单创建项目了
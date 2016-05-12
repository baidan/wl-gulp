# 环境配置
1. 去[nodejs.org](https://nodejs.org/en/)下载node
2. 去[git-scm.com](https://git-scm.com/download/)下载git
3. 打开<code>git bash</code>命令窗口或者cmd窗口
4. 运行<code>git clone https://github.com/jxmyh99/wl-gulp</code>即可
5. 这里推荐您使用<code>cnpm</code>来下载各个组件。天朝，你懂的。

# 环境要求

# 常用组件
    "babel-core": "^6.8.0",
    "babel-preset-es2015": "^6.6.0",
    "babel-register": "^6.8.0",
    "browser-sync": "^2.12.5",
    "gulp": "^3.9.1",
    "gulp-autoprefixer": "^3.1.0",
    "gulp-babel": "^6.1.2",
    "gulp-cache": "^0.4.4",
    "gulp-concat": "^2.6.0",
    "gulp-cssnano": "^2.1.2",
    "gulp-eslint": "^2.0.0",
    "gulp-htmlmin": "^2.0.0",
    "gulp-if": "^2.0.1",
    "gulp-imagemin": "^3.0.1",
    "gulp-jade": "^1.1.0",
    "gulp-load-plugins": "^1.2.2",
    "gulp-plumber": "^1.1.0",
    "gulp-rename": "^1.2.2",
    "gulp-rev-collector": "^1.0.3",
    "gulp-rimraf": "^0.2.0",
    "gulp-sass": "^2.3.1",
    "gulp-size": "^2.1.0",
    "gulp-sourcemaps": "^2.0.0-alpha",
    "gulp-uglify": "^1.5.3",
    "gulp-useref": "^3.1.0",
    "gulp-zip": "^3.2.0",
    "gulp.spritesmith": "^6.2.1",
    "imagemin-pngquant": "^5.0.0",
    "main-bower-files": "^2.13.0",
    "merge-stream": "^1.0.0",
    "vinyl-buffer": "^1.0.0",
    "wiredep": "^4.0.0"

#目录结构及文件
<pre>
├─.tmp               ---> 本地服务器
|
├─templter           ---> 模板文件
|   ├─jade
|   ├─js
|   |  └─public      -- 自定义的公用库
|   └─scss
|      └─public      -- 公用的scss的库
├─rev                ---> md5码生成目录
|   └─rev-manifest.json   md5码的json文件
|
└─webstart
    ├─build          ---> 开发目录
    │  ├─img
    │  │  └─sprite   -- 待合并成雪碧图的图片文件
    │  ├─js          -- js目录
    │  └─scss        -- 待编译的SCSS文件
    └─dist           ---> 生成目录
       ├─img
       ├─css
       └─js
</pre>

# 支持功能
1. jade模板引擎
2. es6的支持，会自动转换为es5
3. sass的支持
4. css,js,image增加缓存机制，即增加md5码
# 一些问题
- 后面的可能加入json-serve
    https://github.com/typicode/json-server
    这个可以更好的调试后台的数据
- 针对不同的业务生成不同的目录。
- bower的目录的支持问题
- 后面会把这个加入到yeoman-generator的脚手架去，这样就会更简单创建项目了
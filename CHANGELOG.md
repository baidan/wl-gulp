- 2015/5/10 
    - 收集了一些实用插件
- 2015/5/11
    - es6改写了gulpfile.babel.js文件
    - 新增加了雪碧图生成
    - 新增加了图片压缩
- 2015/5/12
    - 新增加了字体生成
    - 加入了bower
    - 修改了serve task
    - 修改了打包task
        - 新增加了zip:disk打包生产目录的文件
    - 修改了md5码生成的task
    - 整合了合并css,js和压缩css,js，并且更新task名为html
    - 修改了sprite的task，因为如果没有2倍图片的话。会出错。所以分开成两个sprite task
    - 新增加了两个clean task
        + clean:rev 清除md5码生成 的json文件
        + clean:build 清除工作目录
        + clean 清除.tmp和dest目录
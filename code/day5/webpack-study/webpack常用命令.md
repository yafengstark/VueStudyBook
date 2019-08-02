npm i cnpm -g 安装cnpm


先运行 npm install 安装依赖包

尽量不要全局安装webpack

npm install --save-dev webpack@3.11.0 安装特定版本

4.0.0版本以上需要安装webpack-cli,变化较大

## 那么，我们应该如何使用局部webpack命令呢？

[https://segmentfault.com/a/1190000014159004](https://segmentfault.com/a/1190000014159004)

1、利用package.json设置中的scripts属性
2、通过向 npm run [命令]和参数之间添加两组两个中横线，
可以将自定义参数传递给 npm 脚本，例如：npm run lwebpack -- --v。


在命令行下，$ npm run，然后回车，
就会显示所有可以使用的命令。npm run 是npm run-script的缩略。


## 卸载

npm uninstall webpack-cli


## 
在安装一个要打包到生产环境的安装包时，你应该使用 npm install --save，
如果你在安装一个用于开发环境的安装包（例如，linter, 测试库等），
你应该使用 npm install --save-dev


## 查看版本

node -v

npm -v

## 4.0.0版本以上需要安装webpack-cli

npx webpack 编译整个项目


## 解决报错
html-webpack-plugin\lib\compiler.js:81

解决方法：升级到最新版

 npm i --save-dev html-webpack-plugin@next
 
 
 再执行打包命令，亲测可用
 
##

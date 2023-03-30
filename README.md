mkdir ext-tools
cd ext-tools

初始化项目
npm init

安装 ESLint
cnpm install eslint --save-dev
生成 ESLint配置文件
npm init @eslint/config

安装打包工具
npm install rollup --save-dev
打包代码
rollup -c rollup.config.js

发布
npm publish

npm version后面参数说明：
patch：小变动，比如修复bug等，版本号变动 v1.0.0->v1.0.1
minor：增加新功能，不影响现有功能,版本号变动 v1.0.0->v1.1.0
major：破坏模块对向后的兼容性，版本号变动 v1.0.0->v2.0.0
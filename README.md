# CalculatorOnline
基于Vue.js的在线计算器，可实现自定义表单计算，如清单计算等等



如果要在你的本地启动Vue项目，需要配置环境，请根据以下步骤完成：

    1、安装node.js
    检查node.js是否安装成功：node -v
    检查  npm  是否安装成功：npm -v
    node安装电梯：https://www.runoob.com/nodejs/nodejs-install-setup.html

    2、安装npm的淘宝镜像（如果命令行安装不了，报code ENOLOCAL，试着使用Git Bash安装）
    （命令行）： npm install -g cnpm –registry=https://registry.npm.taobao.org

    3、安装全局vue-cli脚手架
    （命令行）： cnpm install -g vue-cli
     检查 vue 是否安装成功：vue -V

    4、创建一个testVue项目，该步骤主要是在本地初始化一个vue项目，然后把里面的 node_modules （依赖文件）引入到项目中
    由于node_modules文件夹中的文件非常多，不可能全部Git到远程仓库中，因此做这个本地初始化的工作

    （命令行 在DHG目录下）：vue init webpack testVue

    ? Project name  ……………………………………………………………………………………………………… y
    ? Project description  …………………………………………………………………………………………… 回车
    ? Author  ……………………………………………………………………………………………………………… 回车
    ? Vue build …………………………………………………………………………………………………………… 回车
    ? Install vue-router? ……………………………………………………………………………………………… y
    ? Use ESLint to lint your code? ………………………………………………………………………………… n
    ? Set up unit tests  ………………………………………………………………………………………………… n
    ? Setup e2e tests with Nightwatch?  …………………………………………………………………………… n
    ? Should we run `npm install` for you after the project has been created? (recommended) ……… 回车

    最终效果：
    ? Project name y
    ? Project description y
    ? Author y
    ? Vue build standalone
    ? Install vue-router? Yes
    ? Use ESLint to lint your code? No
    ? Set up unit tests No
    ? Setup e2e tests with Nightwatch? No
    ? Should we run `npm install` for you after the project has been created? (recommended) npm

    5、移动vue初始化的文件到本项目中
    （命令行）： move testVue\node_modules Vue\node_modules

    6、删除该testVue
    （命令行）： rmdir /s/q testVue
    其中：
    /s 是代表删除所有子目录跟其中的档案。
    /q 是不要它在删除档案或目录时，不再问我 Yes or No 的动作。

    7、cd 到Vue中
    （命令行）： cd Vue

    8、安装elementUI（必须要用npm才能正常）
    （命令行）： npm i element-ui -S

    9、启动项目
    （命令行）： npm run dev




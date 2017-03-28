# 简介
nodejs领域 ，jasmine做单元测试， karma自动化完成单元测试，grunt启动karma统一项目管理。
集成jasmine+karma完成自动话测试。
karma是一个基于node.js的javascript测试执行过程管理工具（Test Runner）。 该工具可用于测试所有主流Web浏览器，也可集成到CI（continuous integration）工具，也可和其他代码编辑器一起使用。

这个测试工具一个强大的特性就是，可以watch文件变化，然后自动执行，通过console.log显示测试结果。

Jasmine是单元测试框架，本单将介绍用karma让Jasmine测试自动化完成。

# 安装karma
sudo npm install -g karma

karma start 测试是否安装成功

初始化Karma配置文件karma.conf.js. 使用命令 sudo karma init

安装集成包 karma-jasmine

# 自动化单元测试
3步准备工作：
1. 创建源文件： 用于实现某种业务逻辑的文件，就是我们平时写的脚本

2. 创建测试文件： 符合jasmine API的测试js脚本

3. 修改iakarma.conf.js配置文件

4. 启动测试  karma start karma.config.js
npx jest --init
初始化jest

coverageDirectory: "coverage"
coverage是代码覆盖率文件夹名称，可以自定义

npx jest --coverage
代码测试覆盖率

执行npm run jest时，jest内置babel-jest,检测是否安装了babel-core,取.babelrc配置，在运行测试之前，结合babel,先把代码转化一次,运行转化过的测试用例代码
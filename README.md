1.1. 项目描述
1) 此项目为一个前后台分离的招聘的 SPA, 包括前端应用和后端应用
2) 包括用户注册/登陆, 大神/老板列表, 实时聊天等模块
3) 前端: 使用 React 全家桶+ES6+Webpack 等技术
4) 后端: 使用 Node + express + mongodb + socketIO 等技术
5) 采用模块化、组件化、工程化的模式开发
2.1. 开启项目开发
2.1.1. 使用 create-react-app( 脚手架) 搭建项目
1) create-react-app 是 react 官方提供的用于搭建基于 react+webpack+es6 项目的脚手架
2) 操作:
npm install -g create-react-app : 全局下载工具
create-react-app gzhipin-client :下载模板项目
cd gzhipin
npm start
访问: localhost:3000
2.1.2. 编码测试与打包发布项目
1) 编码测试
1.进入lingjoyzhipin-client
npm install
npm start
访问: http://localhost:3000
2.进入lingjoyzhipin-server
npm start
编码, 自动编译打包刷新(live-reload), 查看效果
2) 打包发布
npm run build
npm install -g serve
serve build

 

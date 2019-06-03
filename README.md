# 项目说明

基本目标是展示无人机采集的数据，检测无人机状态等。目前要展示的数据尚未确定，未和后端进行沟通，因此目前展示的数据均为随机模拟。
可以认为目前仅完成 UI 部分。

# 技术栈

由于主要使用 Ant Design (pro) UI 库，因此采用 React 编写。框架采用 Umi，包管理用 npm/cnpm 。

# 项目结构

- package.json, .gitignore, .git：略
- .umirc.js：umi 配置文件
- layouts/index.js：页面布局文件
- mock：模拟后端数据文件
- pages：页面的实际内容
    - .umi：临时文件，请勿改动
    - index.js：首页内容

# 相关资料

- Ant Design 文档：https://ant.design/index-cn （大部分 UI 组件从这里找资料）
- Ant Design Pro 文档：https://pro.ant.design/index-cn （表格组件从这里找资料）
- Umi 文档：https://umijs.org/ （框架部分从这里找）
- React 文档：https://react.docschina.org/
- npm 文档：https://www.npmjs.cn/

# 调试和构建项目

把本项目下载到本地后，从命令行打开，确认 npm/cnpm 安装后执行 

```
npm install
```

安装依赖项，生成 node_modules 文件夹。

之后按照文档安装 umi 。

输入 npm start 进行调试，输入 npm run build 进行构建。

# 其他

有问题再联系。目前已知 bug 为图表有溢出现象，之后修改。
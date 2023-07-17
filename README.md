# Vue Starter

这是一个基于Vue的空项目模板，用于快速启动Vue项目的开发。

## 功能特点

- 使用Vue 3进行开发
- 集成了Element Plus UI库
- 使用Vue Router进行路由管理
- 使用Pinia进行状态管理
- 使用Vite作为开发服务器和构建工具

## 开发环境准备

在开始之前，请确保您的开发环境已经安装了以下工具和依赖：

- Node.js (推荐使用最新的稳定版本)
- npm 或 yarn

## 快速开始

1. 克隆项目到本地：

   ```bash
   git clone https://github.com/BlueSgler/vue-starter.git
   ```

2. 进入项目目录：

   ```bash
   cd vue-starter
   ```

3. 安装项目依赖：

   ```bash
   npm install
   # 或
   yarn install
   ```

4. 启动开发服务器：

   ```bash
   npm run dev
   # 或
   yarn dev
   ```

   该命令将启动一个开发服务器，并在浏览器中打开项目。

   **注意：** 如果您需要在开发过程中使用环境变量，请确保在启动开发服务器之前将环境变量配置到项目中。您可以在项目根目录下创建一个`.env`文件，并在其中定义您的环境变量。例如：

   ```
   VUE_APP_API_URL=http://localhost:3000/api
   ```

   然后，在您的代码中可以使用`process.env.VUE_APP_API_URL`来访问该环境变量。

5. 开始开发：

   您可以在`src`目录中开始编写您的Vue组件和逻辑。

## 构建项目

要构建项目，运行以下命令：

```bash
npm run build
# 或
yarn build
```

该命令将生成一个用于生产环境的优化和压缩后的代码。

## 预览构建结果

要预览构建结果，运行以下命令：

```bash
npm run preview
# 或
yarn preview
```

该命令将启动一个本地服务器，并在浏览器中预览构建结果。

## 代码质量检查

该项目集成了ESLint进行代码质量检查。要运行代码检查，运行以下命令：

```bash
npm run lint
# 或
yarn lint
```

该命令将检查项目中的代码，并输出任何错误或警告。

## 贡献

如果您发现任何问题或有任何改进意见，请随时提出issue或提交pull请求。我们欢迎您的贡献！

## 许可证

该项目基于MIT许可证进行发布。有关更多信息，请参阅[LICENSE](./LICENSE)文件。

请根据您的实际情况进行调整和修改。希望这个README文档对您有所帮助！
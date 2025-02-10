# 计算器应用

一个使用 Vue.js 和 Tauri 构建的现代计算器应用程序，提供跨平台的桌面体验。

## 功能特性

- 基本算术运算（加、减、乘、除）
- 响应式设计
- 跨平台支持（Windows、macOS、Linux）
- Storybook 组件文档
- 使用 Cypress 进行端到端测试

## 安装

1. 克隆仓库：

   ```bash
   git clone https://github.com/yourusername/calculator.git
   cd calculator
   ```

2. 安装依赖：

   ```bash
   yarn install
   ```

3. 启动开发服务器：

   ```bash
   yarn dev
   ```

## 使用

开发模式运行应用：

```bash
yarn dev
```

生产环境构建应用：

```bash
yarn build
```

## 测试

运行单元测试：

```bash
yarn test:unit
```

运行端到端测试：

```bash
yarn test:e2e
```

## Storybook

查看组件文档：

```bash
yarn storybook
```

## 桌面应用构建

使用 Tauri 构建桌面应用：

1. 安装 Tauri CLI（如果尚未安装）：

   ```bash
   cargo install tauri-cli
   ```

2. 构建应用：

   ```bash
   yarn tauri build
   ```

## 贡献指南

欢迎贡献！请按照以下步骤进行：

1. Fork 本仓库
2. 创建新分支 (`git checkout -b feature/你的功能名称`)
3. 提交更改 (`git commit -m '添加某个功能'`)
4. 推送到分支 (`git push origin feature/你的功能名称`)
5. 提交 Pull Request

## 许可证

本项目采用 MIT 许可证 - 详情请见 [LICENSE](LICENSE) 文件。

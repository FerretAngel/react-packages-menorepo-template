# 🚀 React Packages Monorepo Template

一个现代化的 React 组件开发模板，让你轻松构建和发布高质量的 React 组件！

## ✨ 特性

- 📦 基于 Monorepo 架构，同时管理多个相关项目
- 🎨 内置 TailwindCSS，快速构建美观的 UI
- 🎯 包含示例页面项目，方便组件预览和测试
- 📚 独立的组件库项目，支持按需引入
- 🖼️ 集成 Iconify，海量图标随心用
- ⚡️ 基于 Vite，开发体验极速

## 🏗️ 项目结构

```
.
├── docs             # 示例页面（可以直接发布到github page）
├── packages/
│   ├── page/        # 示例页面项目
│   └── lib/         # 组件库项目
├── package.json
└── README.md
```

## 🚀 快速开始

1. 克隆项目
```bash
git clone https://github.com/FerretAngel/react-packages-menorepo-template.git
```

2. 安装依赖
```bash
pnpm install
```

3. 启动开发服务器
```bash
pnpm dev
```

## 📦 使用组件库

```jsx
import { Button } from '@your-scope/lib'

function App() {
  return <Button>点击我</Button>
}
```

## 🛠️ 开发指南

- 在 `packages/lib` 中开发你的组件
- 在 `packages/page` 中预览和测试组件
- 使用 `pnpm build:page` 构建页面
- 使用 `pnpm build:lib` 构建库


## 📄 许可证
MIT

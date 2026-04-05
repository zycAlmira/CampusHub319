# CampusHub

> 校园综合服务平台

## 项目简介

<!-- TODO: 补充项目描述 -->

## 团队成员

<!-- TODO: 补充团队成员信息 -->

| 姓名 | 学号 | 角色 |
|------|------|------|
|      |      | 需求负责人 |
|      |      | 架构负责人 |
|      |      | 开发负责人 |
|      |      | 测试负责人 |

## 技术栈

- **前端框架**：Vue 3
- **构建工具**：Vite
- **语言**：JavaScript
- **包管理**：npm

## 分支策略

| 分支 | 用途 |
|------|------|
| `main` | 生产环境，保持稳定 |
| `dev` | 开发主线，功能合并到此 |
| `feature/*` | 功能开发分支，如 `feature/login` |

## 快速开始

```bash
# 安装依赖
npm install

# 启动开发服务器
npm run dev

# 构建生产版本
npm run build

# 代码风格检查
npm run lint
```

## 项目结构

```
CampusHub/
├── src/
│   ├── api/          # API 请求封装
│   ├── assets/       # 静态资源
│   ├── components/   # 公共组件
│   ├── router/       # 路由配置
│   ├── store/        # 状态管理
│   ├── utils/        # 工具函数
│   └── views/        # 页面视图
├── public/           # 公共静态文件
├── tests/            # 测试文件
├── docs/             # 项目文档
│   └── P0/           # Phase 0 交付物
└── .github/
    └── workflows/    # CI/CD 配置
```

## CI 状态

![CI](https://github.com/zycAlmira/CampusHub319/actions/workflows/ci.yml/badge.svg)

# 基于 Tailwind CSS 和 Shadcn UI 的专业 SaaS 模板

<p align="center">
  <a href="https://127.0.0.1:3000"><img height="300" src="public/assets/images/nextjs-starter-banner.png?raw=true" alt="Next.js SaaS 模板"></a>
</p>

🚀 **SaaS 模板**是一个功能强大且完全可定制的模板，用于快速启动您的 SaaS 应用程序。它使用 **Next.js** 和 **Tailwind CSS** 构建，并集成了 **Shadcn UI** 的模块化 UI 组件。这个 **Next.js SaaS 模板**可以帮助您以最少的工作量快速构建和启动 SaaS。

该模板包含了许多基本功能，如内置的**身份验证**、支持团队的**多租户**、**角色和权限**、数据库、国际化（i18n）、落地页、用户仪表板、表单处理、SEO 优化、日志记录、使用 [Sentry](https://sentry.io/for/nextjs/?utm_source=github&utm_medium=paid-community&utm_campaign=general-fy25q1-nextjs&utm_content=github-banner-nextjsboilerplate-logo) 的错误报告、测试、部署、监控和**用户身份模拟**等功能。

这个 **Next.js 启动套件**专为开发者设计，使用 TypeScript 确保类型安全，集成 ESLint 维护代码质量，以及使用 Prettier 保持代码格式一致。测试套件结合了 Vitest 和 React Testing Library 进行单元测试，而 Playwright 处理集成和端到端测试。持续集成和部署通过 GitHub Actions 管理。用户管理和身份验证由 [Clerk](https://go.clerk.com/zGlzydF) 处理。对于数据库操作，它使用 Drizzle ORM 进行类型安全的数据库管理，支持 PostgreSQL、SQLite 和 MySQL 等流行数据库。

无论您是构建新的 SaaS 应用还是寻找灵活的、**生产就绪的 SaaS 模板**，这个模板都能满足您的需求。这个专业的启动套件包含了您需要的一切，可以加速您的开发并轻松扩展您的产品。

克隆这个项目并用它创建您自己的 SaaS。您可以在 [SaaS 模板](https://127.0.0.1:3000) 查看在线演示，这是一个具有工作中的身份验证和多租户系统的演示。

### 特性

以开发者体验为先，极其灵活的代码结构，只保留您需要的内容：

- ⚡ 支持 App Router 的 [Next.js](https://nextjs.org)
- 🔥 使用 [TypeScript](https://www.typescriptlang.org) 进行类型检查
- 💎 集成 [Tailwind CSS](https://tailwindcss.com) 和 Shadcn UI
- ✅ TypeScript 和 [React](https://react.dev) 的严格模式
- 🔒 使用 [Clerk](https://go.clerk.com/zGlzydF) 的身份验证：注册、登录、登出、忘记密码、重置密码等
- 👤 无密码身份验证：魔法链接、多因素认证（MFA）、社交认证（Google、Facebook、Twitter、GitHub、Apple 等）、密钥登录、用户身份模拟
- 👥 多租户和团队支持：创建、切换、更新组织和邀请团队成员
- 📝 基于角色的访问控制和权限
- 📦 使用 DrizzleORM 的类型安全 ORM，兼容 PostgreSQL、SQLite 和 MySQL
- 💽 使用 PGlite 的离线和本地开发数据库
- 🌐 使用 [next-intl](https://next-intl-docs.vercel.app/) 和 [Crowdin](https://l.crowdin.com/next-js) 的多语言支持（i18n）
- ♻️ 使用 T3 Env 的类型安全环境变量
- ⌨️ 使用 [React Hook Form](https://react-hook-form.com) 的表单处理
- 🔴 使用 [Zod](https://zod.dev) 的验证库
- 📏 使用 [ESLint](https://eslint.org) 的代码检查（默认 NextJS、NextJS Core Web Vitals、Tailwind CSS 和 Antfu 配置）
- 💖 使用 [Prettier](https://prettier.io) 的代码格式化
- 🦊 用于 Git Hooks 的 Husky
- 🚫 用于在 Git 暂存文件上运行检查器的 Lint-staged
- 🚓 使用 Commitlint 检查 git 提交
- 📓 使用 Commitizen 编写标准兼容的提交消息
- 🦺 使用 [Vitest](https://vitest.dev) 和 React Testing Library 的单元测试
- 🧪 使用 [Playwright](https://playwright.dev) 的集成和端到端测试
- 👷 使用 GitHub Actions 在拉取请求上运行测试
- 🎉 用于 UI 开发的 [Storybook](https://storybook.js.org)
- 🚨 使用 [Sentry](https://sentry.io/for/nextjs/) 的错误监控
- ☂️ 使用 [Codecov](https://about.codecov.io/) 的代码覆盖率
- 📝 使用 [Pino.js](https://getpino.io) 的日志记录和使用 [Better Stack](https://betterstack.com/) 的日志管理
- 🖥️ 使用 [Checkly](https://www.checklyhq.com/) 的监控即代码
- 🎁 使用 Semantic Release 的自动更新日志生成
- 🔍 使用 Percy 的视觉测试（可选）
- 💡 使用 `@` 前缀的绝对导入
- 🗂 VSCode 配置：调试、设置、任务和扩展
- 🤖 SEO 元数据、JSON-LD 和 Open Graph 标签
- 🗺️ Sitemap.xml 和 robots.txt
- ⌘ 使用 Drizzle Studio 的数据库探索和使用 Drizzle Kit 的 CLI 迁移工具
- ⚙️ [Bundler Analyzer](https://www.npmjs.com/package/@next/bundle-analyzer)
- 🌈 包含专业的极简主题
- 💯 最大化 lighthouse 得分

### 项目理念

- 对您完全透明，允许您根据需求和偏好进行任何必要的调整
- 每月更新依赖
- 无需前期成本即可快速开始
- 易于定制
- 代码精简
- SEO 友好
- 构建 SaaS 所需的一切
- 🚀 生产就绪

### 系统要求

- Node.js 20+ 和 npm

### 快速开始

在本地环境中运行以下命令：

```shell
npm install
```

请注意，所有依赖项每月都会更新。

然后，您可以通过执行以下命令在开发模式下本地运行项目（支持实时重载）：

```shell
npm run dev
```

使用您喜欢的浏览器打开 http://localhost:3000 查看您的项目。

### 设置身份验证

在 [Clerk.com](https://go.clerk.com/zGlzydF) 创建账户，并在 Clerk 仪表板中创建新应用程序。然后，将 `NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY` 和 `CLERK_SECRET_KEY` 的值复制到 `.env.local` 文件中（该文件不会被 Git 跟踪）：

```shell
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_pub_key
CLERK_SECRET_KEY=your_clerk_secret_key
```

在您的 Clerk 仪表板中，您还需要通过导航到 `Organization management` > `Settings` > `Enable organization` 来启用组织功能。

### 设置远程数据库

该项目使用 DrizzleORM，这是一个类型安全的 ORM，兼容 PostgreSQL、SQLite 和 MySQL 数据库。默认情况下，该项目设置为与 PostgreSQL 无缝协作，您可以轻松选择任何 PostgreSQL 数据库提供商。

### 翻译（i18n）设置

对于翻译，该项目使用 `next-intl` 结合 [Crowdin](https://l.crowdin.com/next-js)。作为开发者，您只需要管理英语（或其他默认语言）版本。其他语言的翻译由 Crowdin 自动生成和处理。您可以使用 Crowdin 与您的翻译团队协作，或在机器翻译的帮助下自行翻译消息。

要设置翻译（i18n），请在 [Crowdin.com](https://l.crowdin.com/next-js) 创建账户并创建新项目。在新创建的项目中，您将能够找到项目 ID。您还需要通过转到账户设置 > API 创建新的个人访问令牌。然后，在您的 GitHub Actions 中，您需要定义以下环境变量：`CROWDIN_PROJECT_ID` 和 `CROWDIN_PERSONAL_TOKEN`。

在 GitHub Actions 中定义环境变量后，每次您向 `main` 分支推送新提交时，您的本地化文件都会与 Crowdin 同步。

### 项目结构

```shell
.
├── README.md                       # README 文件
├── .github                         # GitHub 文件夹
├── .husky                          # Husky 配置
├── .storybook                      # Storybook 文件夹
├── .vscode                         # VSCode 配置
├── migrations                      # 数据库迁移
├── public                          # 公共资源文件夹
├── scripts                         # 脚本文件夹
├── src
│   ├── app                         # Next JS App（App Router）
│   ├── components                  # 可重用组件
│   ├── features                    # 特定功能的组件
│   ├── libs                        # 第三方库配置
│   ├── locales                     # 本地化文件夹（i18n 消息）
│   ├── models                      # 数据库模型
│   ├── styles                      # 样式文件夹
│   ├── templates                   # 模板文件夹
│   ├── types                       # 类型定义
│   └── utils                       # 工具文件夹
├── tests
│   ├── e2e                         # E2E 测试，也包括监控即代码
│   └── integration                 # 集成测试
├── tailwind.config.js              # Tailwind CSS 配置
└── tsconfig.json                   # TypeScript 配置
```

### 自定义

您可以通过在整个项目中搜索 `FIXME:` 来轻松配置 Next.js SaaS 模板。以下是一些最重要的需要自定义的文件：

- `public/apple-touch-icon.png`、`public/favicon.ico`、`public/favicon-16x16.png` 和 `public/favicon-32x32.png`：您的网站图标
- `src/utils/AppConfig.ts`：配置文件
- `src/templates/BaseTemplate.tsx`：默认主题
- `next.config.mjs`：Next.js 配置
- `.env`：默认环境变量

您可以完全访问源代码进行进一步自定义。提供的代码仅是帮助您启动项目的示例。天空才是极限 🚀。

在源代码中，您还会找到标记为 `PRO` 的注释，这些注释表示仅在 PRO 版本中可用的代码。您可以轻松删除或用自己的实现替换这些代码。

### 贡献

欢迎每个人为这个项目做出贡献。如果您有任何问题或发现错误，请随时提出问题。完全欢迎建议和改进。

### 许可证

基于 MIT 许可证，版权所有 © 2024

更多信息请参见 [LICENSE](LICENSE)。

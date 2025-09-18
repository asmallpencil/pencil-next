Next.js 与 Deno 教程

本项目展示了如何使用 [Deno](https://deno.com) 运行一个 [Next.js](https://nextjs.org) 应用程序，是一个完整的教程示例，展示了如何在 Deno 运行时环境中搭建、开发和部署 Next.js 应用。

立即部署你自己的版本！

你可以立即将你的 Next.js 应用部署到 Deno Deploy。
只需点击下方按钮即可克隆并部署。

[![部署到 Deno](https://deno.com/button)](https://app.deno.com/new?clone=https://github.com/denoland/tutorial-with-next)

关于本教程

本教程项目将向你展示如何：

- 搭建 Next.js 项目
- 在 Deno 上运行项目
- 添加一个简单的后端 API 路由
- 更新前端以从后端获取数据
- 将你的 Next.js 应用部署到 Deno Deploy

查看完整的分步教程，请访问：[Deno 文档中的 Next.js 教程](https://docs.deno.com/examples/next_tutorial/)

开始上手

首先，运行开发服务器：

```bash
deno run dev
```

在浏览器中打开 [http://localhost:3000](http://localhost:3000) 查看结果。

你可以通过修改 `app/page.tsx` 来开始编辑页面。保存文件后页面会自动更新。

部署到 Deno

你可以将本项目部署到 Deno Deploy！按以下步骤操作：

1. 前往 [Deno Deploy 控制台](https://app.deno.com/)
2. 点击“新建项目”
3. 选择你的 GitHub 仓库
4. 根据提示部署你的 Next.js 应用
5. 部署完成后，你会收到一个应用上线的 URL
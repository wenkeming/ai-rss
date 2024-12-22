# AI RSS

AI RSS 是一个通过 AI 将网页内容转换为 RSS 订阅源的工具。

它包含两部分：

1. 一个浏览器插件，可以选择网页中的列表，并指定每一个数据项，最后生成一个 SDD（结构化数据描述） 文件
2. 一个服务器，可以部署到 Vercel 和 Docker/NAS 上，它读取 SDD 文件，根据配置抓取网页内容并分析，最终生成 RSS 订阅源

在浏览器插件中，用户可以一键发布 SDD 文件到服务器。

## 开始使用

由于我们使用了AI的能力来分析网页内容，所以需要先注册一个 OpenAI/API2D/SillconFlow 的账号，并获取一个 API Key。
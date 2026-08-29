# CSI Research Articles

CSI Research 已发布文章的公开 Markdown 归档。

[访问 CSI Research](https://research.aicsi.cn/) · [浏览已发布文章列表](文章列表.md)

## 关于 CSI Research

CSI Research 关注内容结构、创作者、人工智能、数字资产与下一代内容基础设施，尝试研究 AI 时代内容如何生产、分发、沉淀并形成长期价值。

本仓库只保存已经公开发布的文章，不包含 WordPress 程序、发布脚本、配置文件或凭据。文章标题、发布时间、分类和 Slug 以 CSI Research 公开 WordPress REST API 为准，并记录在 [文章列表.md](文章列表.md) 中。

## 文章分类

| 分类 | 文章数 | 目录 |
| --- | ---: | --- |
| CSI方法论 | 8 | [CSI方法论](CSI方法论/) |
| AI研究 | 6 | [AI研究](AI研究/) |
| AI与社会 | 6 | [AI与社会](AI与社会/) |
| 创作者研究 | 15 | [创作者研究](创作者研究/) |
| 平台研究 | 6 | [平台研究](平台研究/) |
| 数字资产研究 | 7 | [数字资产研究](数字资产研究/) |
| 下一代内容基础设施 | 9 | [下一代内容基础设施](下一代内容基础设施/) |
| **合计** | **57** | |

## 仓库结构

```text
csi-research-articles-public/
├── README.md
├── 文章列表.md
├── CSI方法论/
├── AI研究/
├── AI与社会/
├── 创作者研究/
├── 平台研究/
├── 数字资产研究/
└── 下一代内容基础设施/
```

每篇文章都是独立的 Markdown 文件，并通过 Front Matter 记录：

- `title`：文章标题
- `slug`：线上固定链接标识
- `excerpt`：文章摘要
- `categories`：文章分类
- `tags`：文章标签

源文件中的 `status: draft` 是文章进入 WordPress 前的发布工作流字段，不代表当前线上状态。是否已经公开发布，请以 [文章列表.md](文章列表.md) 和 [CSI Research](https://research.aicsi.cn/) 为准。

## 同步原则

- 只同步已经在 CSI Research 公开发布的文章。
- 文章按 WordPress 分类存放在对应目录中。
- `文章列表.md` 按分类分组，各分类内按发布时间从新到旧排列。
- 未发布稿、发布工具、生成载荷和凭据不进入本仓库。

## 内容许可

当前仓库尚未包含 `LICENSE` 文件。仓库公开可见不代表已经授予复制、改编、再发布或商业使用许可；具体授权方式以后续明确加入的许可文件为准。

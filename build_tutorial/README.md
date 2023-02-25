### 搭建教程

### 1. 环境概览

| 环境名称 | 文档链接                         | 说明                                                         |
| -------- | -------------------------------- | ------------------------------------------------------------ |
| Hexo     | https://hexo.io/zh-cn/docs/      | 快速、简洁且高效的博客框架                                   |
| GIt      | https://git-scm.com/download/win | 快速版本控制                                                 |
| Node     | https://nodejs.org/en/download/  | Node.js® 是基于[Chrome 的 V8 JavaScript 引擎](https://v8.dev/)构建的 JavaScript 运行时 |

### 2. 环境搭建

#### 2.1 安装 Git 

- Windows：下载并安装 [git](https://git-scm.com/download/win). 

#### 2.2 安装 Node

- Node.js 为大多数平台提供了官方的 [安装程序](https://nodejs.org/en/download/)。对于中国大陆地区用户，可以前往 [淘宝 Node.js 镜像](https://npm.taobao.org/mirrors/node) 下载。
- 使用 Node.js 官方安装程序时，请确保勾选 **Add to PATH** 选项（默认已勾选）

#### 2.3 安装 Hexo

```bash
# 使用 npm 安装 Hexo
npm install -g hexo-cli
```

### 3. 配置

#### 3.1 主题配置

一个主题可能会有以下的结构：

```json
.
├── _config.yml // 主题的配置文件。和 Hexo 配置文件不同，主题配置文件修改时会自动更新，无需重启 Hexo Server
├── languages   // 语言文件夹。请参见 国际化 (i18n)。
├── layout      // 布局文件夹。用于存放主题的模板文件，决定了网站内容的呈现方式，
├── scripts     // 脚本文件夹。在启动时，Hexo 会载入此文件夹内的 JavaScript 文件
└── source      // 资源文件夹，除了模板以外的 Asset，例如 CSS、JavaScript 文件等，都应该放在这个文件夹中。
                // 文件或文件夹开头名称为 _（下划线线）或隐藏的文件会被忽略。
```

相关资料

1. https://hexo.io/zh-cn/docs/themes

>  **选择主题** 

https://github.com/JoeyBling/hexo-theme-yilia-plus

 一个简洁优雅的hexo主题 A simple and elegant theme for hexo.

#### 3.2 目录模板

模板决定了网站内容的呈现方式，每个主题至少都应包含一个 `index` 模板，以下是各页面相对应的模板名称：

| 模板       | 用途     | 回退      |
| :--------- | :------- | :-------- |
| `index`    | 首页     |           |
| `post`     | 文章     | `index`   |
| `page`     | 分页     | `index`   |
| `archive`  | 归档     | `index`   |
| `category` | 分类归档 | `archive` |
| `tag`      | 标签归档 | `archive` |


























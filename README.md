# Obsidian Web Clipper 模板集合

这里是我个人使用的 **Obsidian Web Clipper** 插件模板集合。这些模板针对不同的网站（如 ChatGPT、Twitter/X、YouTube 等）进行了深度定制，旨在提供更整洁、更结构化的剪藏效果，方便在 Obsidian 中进行后续的知识管理。

## 📂 模板列表

| 模板文件 | 显示名称 | 说明 | 适用网站 |
| :--- | :--- | :--- | :--- |
| `chatgpt-collapsible.json` | **ChatGPT 可折叠** | 将 ChatGPT 的对话保存为可折叠的 Callout 块 (User 和 Assistant 分别折叠)，让长对话笔记看起来非常清爽。 | ChatGPT |
| `chatgpt-default.json` | **ChatGPT 默认** | 标准的 ChatGPT 对话剪藏模板，保留原始对话流。 | ChatGPT |
| `gemini-chat.json` | **Gemini 对话** | 专为 Google Gemini (原 Bard) 优化的对话剪藏模板。 | Google Gemini |
| `twitter-post.json` | **X (Twitter) Post** | 完美剪藏推文，自动提取作者 ID、发布时间、正文及图片，以结构化格式保存。 | X (Twitter) |
| `weibo-post.json` | **微博** | 剪藏微博正文内容，适配微博网页版结构。 | 新浪微博 |
| `youtube-video.json` | **YouTube 视频** | 提取视频标题、频道信息、发布时间以及视频简介。 | YouTube |
| `generic-article.json` | **通用文章** | 适用于大多数网页文章的通用模板。内置了 CSS 选择器清理规则，自动移除音频播放器、无关提示等干扰元素。 | 通用 / 默认 |

## 🚀 如何使用

1. **安装扩展**：确保你已经安装了官方的 [Obsidian Web Clipper](https://obsidian.md/clipper) 浏览器扩展。
2. **下载模板**：Clone 本仓库或直接下载你需要的 `.json` 文件。
3. **导入设置**：
    - 打开浏览器中的 Obsidian Web Clipper 扩展界面。
    - 点击右上角的菜单或设置图标，进入 **Settings** (设置)。
    - 找到 **Templates** (模板) 区域。
    - 点击 **Import** (导入) 按钮，选择下载好的 JSON 文件即可。
4. **手动配置** (可选)：
    - 你也可以用文本编辑器打开 JSON 文件，复制其中的内容。
    - 在扩展中新建一个模板，将内容粘贴到配置中。

## 🤝 贡献

如果你有更好用的模板配置，或者针对特定网站的优化建议，欢迎提交 **Pull Request** 或 **Issue** 分享给更多人！

## 📄 License

MIT

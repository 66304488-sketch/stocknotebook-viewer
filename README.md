# StockNotebook Viewer

在浏览器中查看 [StockNotebook](https://github.com/66304488-sketch/StockNotebook) 备份文件。

## 在线使用

访问 GitHub Pages：
**https://66304488-sketch.github.io/stocknotebook-viewer/**

## 本地使用

直接双击 `index.html`，或启动一个本地 HTTP 服务器：

```bash
python3 -m http.server 8766
```

然后在浏览器打开 `http://localhost:8766`。

## 使用方法

1. 点击「选择备份文件」
2. 选择 StockNotebook 导出的 JSON 备份（如 `StockNotebook_20260627_114136.json`）
3. 浏览股票列表和笔记

## 功能

- 本地解析 JSON，数据不上传到任何服务器
- 支持搜索股票名称、代码、笔记内容
- 支持按标签、状态、市场筛选
- Markdown 渲染笔记内容
- 适配手机端浏览

## 隐私说明

所有数据均在浏览器本地解析，不会上传到 GitHub 或任何第三方服务器。

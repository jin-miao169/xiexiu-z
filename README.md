# 邪修小Z · 自媒体工作台

自媒体创作一站式工作台，集成热梗采集、话题灵感、爆款拆解、记单词等功能。

## 功能

- 热梗采集：AI 实时生成热门梗文化
- 话题灵感：每日话题推荐
- 爆款拆解：内容创作方法论
- 记单词：10,000 词库，每日 60 词轮换，166 天不重样
  - CET-4 / CET-6 / 考研 / IELTS / TOEFL 分级
  - 翻转卡片、搜索、打乱顺序
  - AI 生成语义例句

## 技术

- 纯前端 HTML/CSS/JavaScript，无构建依赖
- 10,000 词库内嵌，零外部加载
- LocalStorage 缓存例句，减少 API 调用
- DeepSeek AI 生成例句（通过云函数代理）

## 部署

GitHub Pages 自动部署，访问地址：
`https://<username>.github.io/<repo-name>/`

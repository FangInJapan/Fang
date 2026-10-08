# Fang 代码库新手指南

这个仓库目前是一个非常轻量的 **GitHub Pages / Jekyll 静态站点**，用于展示个人信息。

## 项目结构

- `_config.yml`：Jekyll 配置文件。当前只设置了主题 `jekyll-theme-time-machine`。
- `index.md`：站点首页内容，使用 Markdown 编写，包含个人信息与联系方式。
- `Orlando.jpg`：静态图片资源（可在页面中引用）。

## 运行机制（新人需要先理解）

1. GitHub Pages 会读取仓库内容。
2. Jekyll 根据 `_config.yml` 和 `.md` 文件生成网页。
3. `index.md` 默认作为首页渲染。

## 维护重点

1. **内容安全与隐私**：`index.md` 当前包含手机号、邮箱、微信等敏感信息，修改前要确认公开范围。
2. **格式一致性**：页面目前是中英日混排，建议保持字段顺序与排版统一。
3. **变更可追溯**：每次更新信息都用清晰的 commit message（例如：`docs: update contact info`）。

## 建议的学习路径

1. **先会改内容**：熟悉 Markdown 标题、段落、列表、图片语法。
2. **再懂页面生成**：了解 Jekyll 的基本概念（主题、布局、配置）。
3. **最后做结构化升级**：
   - 增加 `README.md`（本文件）说明项目用途与维护方式。
   - 把个人信息拆分为可复用模块（后续可引入 `_data` 或 `_includes`）。
   - 逐步补充多页面（如 `about.md`、`projects.md`）。

## 新人第一周可执行任务

- Task 1：把 `index.md` 的信息改成统一的双语字段顺序。
- Task 2：在首页加入 `Orlando.jpg` 并调整展示说明。
- Task 3：补一个 `CHANGELOG.md`，记录每次信息更新。


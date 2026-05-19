# 个人作品集网站

这是一个纯 HTML/CSS/JavaScript 单页面作品集，包含自我介绍、项目展示、联系方式、响应式布局和暗色/亮色主题切换。

## 本地预览

直接在浏览器打开 `index.html` 即可预览。

## 自定义内容

- 在 `index.html` 中替换姓名、简介、项目案例、邮箱和社交链接。
- 在 `styles.css` 的 `:root` 与 `[data-theme="dark"]` 中调整颜色。
- 主题偏好会通过 `localStorage` 保存在浏览器中。

## 部署到 GitHub Pages

1. 在 GitHub 创建一个新仓库。
2. 把本目录中的文件提交并推送到仓库的 `main` 分支。
3. 打开仓库的 `Settings` -> `Pages`。
4. 在 `Build and deployment` 中选择 `GitHub Actions`。
5. 推送后工作流会自动部署，Pages 地址通常是 `https://你的用户名.github.io/仓库名/`。

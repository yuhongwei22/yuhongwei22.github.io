# 余宏伟 · 个人主页

基于 [Academic Pages](https://github.com/academicpages/academicpages.github.io) (Jekyll) 模板搭建的中文学术个人主页,使用 GitHub Pages 部署。

## 部署步骤

1. 在 GitHub 新建仓库,命名为 `<你的用户名>.github.io`(用户主页型仓库,根路径直接是站点)。
2. 将本目录推送到该仓库的 `main` 分支:
   ```bash
   git init
   git add .
   git commit -m "init: 个人主页"
   git branch -M main
   git remote add origin git@github.com:<你的用户名>/<你的用户名>.github.io.git
   git push -u origin main
   ```
3. 进入仓库 Settings → Pages,Source 选 `Deploy from a branch`,branch 选 `main` / `/ (root)`。
4. 等 1-2 分钟,访问 `https://<你的用户名>.github.io/`。

## 上线前必须替换的占位

`_config.yml` 中标 `# TODO` 的字段:

- `url`、`repository`:换成你的 GitHub 用户名。
- `author.github`、`author.googlescholar`、`author.orcid`、`author.linkedin`:有就填,没有先留空(留空时左侧 sidebar 不会显示对应图标)。

`images/avatar.png`:目前用模板默认头像占位,替换为你自己的证件照即可(同名覆盖)。

`_pages/about.md` 中标记 `(#)` 的论文链接:逐条替换为论文真实链接(arXiv / OpenReview / DOI)。

## 本地预览(可选)

需要 Ruby 环境:

```bash
bundle install
bundle exec jekyll serve
```

然后浏览器访问 http://localhost:4000 。

## 目录结构

- `_config.yml` — 站点元数据、左侧 sidebar 字段
- `_pages/about.md` — 主内容(7 个章节)
- `_data/navigation.yml` — 顶部锚点导航
- `_includes/author-profile.html` — sidebar 模板(已移除 Follow 按钮)
- `images/avatar.png` — 头像

## 致谢

- 模板: [academicpages/academicpages.github.io](https://github.com/academicpages/academicpages.github.io) (MIT)
- 灵感: [zh.yudongzhang.com](https://zh.yudongzhang.com/)

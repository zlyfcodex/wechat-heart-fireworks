# 微信爱心烟花 · 生日页

单文件静态页面（爱心烟花 + 文字 + 你自己的吉他弹唱《晴天》），可直接发布到 GitHub Pages。

## 发布（3 步）

1. 用 **GitHub Desktop** → File → Add local repository → 选这个文件夹：
   `C:\Users\Lenovo\Documents\Codex\2026-10-12\ban\outputs\github-pages-repo`
2. 它会列出改动（index.html、music.m4a 等）→ 填一句提交信息 → **Commit to main** → **Push origin**
3. 等 1~2 分钟，打开：`https://zlyfcodex.github.io/wechat-heart-fireworks/`
   （若第一次用：仓库 Settings → Pages → Source 选 **GitHub Actions**，然后重跑一次部署工作流）

## 撤回（3 步，用完就撤）

1. 删掉仓库里的音乐：GitHub Desktop 里右键 `music.m4a` → Delete → Commit → Push
   （页面会自动回落到内置合成曲，不会报错）
2. 或者整站下线：仓库 Settings → Pages → 把 Source 改成 **None**
3. 干脆删仓库：Settings 拉到底 → Delete this repository

## 小提示

- 页面已加 `noindex`，不会被搜索引擎收录
- 手机/微信里打开：第一次需要点一下（或划一下）才会出声，这是浏览器的自动播放限制
- 本地预览：双击 `启动预览.bat`（或在项目目录跑 `node serve.js 8099`）

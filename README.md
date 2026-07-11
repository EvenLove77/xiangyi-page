# 相倚且相依 — 项目主页

## GitHub Pages 部署步骤

### 1. 创建公开仓库
在 GitHub 新建一个**公开**仓库，名字随意（如 `xiangyi-page`）

### 2. 上传文件
```bash
cd github-pages
git init
git add index.html
git commit -m "init"
git branch -M main
git remote add origin git@github.com:你的用户名/xiangyi-page.git
git push -u origin main
```

### 3. 启用 GitHub Pages
- 进入仓库 → Settings → Pages
- Source: `Deploy from a branch`
- Branch: `main`，目录选 `/ (root)`
- 点 Save

### 4. 等待部署
几分钟后访问 `https://你的用户名.github.io/xiangyi-page/`

### 5. 提交又拍云联盟申请
把这个地址填到又拍云联盟申请表的「网站地址」栏，截图发给审核。
# MIYAIP 数据运营中心

这是可直接部署到 GitHub Pages 的静态交互原型，所有经营数字均为演示数据。

## 部署步骤

1. 新建 GitHub 仓库，例如 `miyaip-data-dashboard`。
2. 将本文件夹内的 `index.html`、`.nojekyll`、`README.md` 和整个 `assets` 文件夹上传到仓库根目录。
3. 进入仓库 `Settings` → `Pages`。
4. 在 `Build and deployment` 中选择 `Deploy from a branch`。
5. Branch选择 `main`，文件夹选择 `/(root)`，点击 `Save`。
6. 等待约1—5分钟，Pages页面会显示线上地址。

线上地址通常为：`https://你的GitHub用户名.github.io/仓库名/`

## 重要提醒

- `index.html`必须直接位于仓库根目录，不能再套一层文件夹。
- `assets`文件夹必须完整上传，不能单独修改其中的文件名。
- `.nojekyll`虽然是空文件，但需要保留。
- 更新版本时，覆盖 `index.html` 和整个 `assets` 文件夹即可。

# .github (org profile)

本仓库会被 GitHub 自动识别为组织 profile。`profile/README.md` 的内容显示在 https://github.com/nndl 主页。

## 部署

1. 在 GitHub 创建公开仓库 `github.com/nndl/.github`（仓库名是字面量 `.github`，以点开头）
2. 在本目录 push：
   ```
   git remote add origin https://github.com/nndl/.github.git
   git push -u origin main
   ```
3. 访问 https://github.com/nndl 验证 profile 显示

## 更新

直接改 `profile/README.md`，commit + push 即可。

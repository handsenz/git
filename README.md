# git

本地代码仓库的起点。

## 快速开始

```bash
git clone git@github.com:handsenz/git.git
```

## 后续放置代码

把源码放进本目录后，用以下命令提交：

```bash
git add .
git commit -m "feat: 添加初始代码"
git push
```

## 约定

- 主分支为 `main`
- 依赖目录、构建产物与本地凭据文件由 `.gitignore` 排除，不要提交

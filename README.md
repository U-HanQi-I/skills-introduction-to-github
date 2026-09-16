# skills-introduction-to-github

> GitHub Skills —— Introduction to GitHub 练习仓库

本仓库用于练习 GitHub 的基础协作流程：分支、提交、Pull Request、合并，以及 Issue 与 Actions 的联动。

## 练习内容

| 步骤 | 说明 | 涉及概念 |
| --- | --- | --- |
| 1 | 创建分支 | Branch |
| 2 | 提交一次修改 | Commit |
| 3 | 发起 Pull Request | Pull Request |
| 4 | 合并 Pull Request | Merge |
| 5 | 关闭 Issue / 完成练习 | Issue、Actions |

## 常用命令

```bash
# 克隆仓库
git clone https://github.com/U-HanQi-I/skills-introduction-to-github.git
cd skills-introduction-to-github

# 查看状态与分支
git status
git branch -a

# 新建分支并提交
git checkout -b my-branch
git add .
git commit -m "描述这次修改"
git push -u origin my-branch

# 拉取远端最新代码
git pull origin main
```

## 分支约定

- `main` —— 主分支，保持可发布状态
- 其他分支 —— 以功能或练习主题命名，完成后通过 Pull Request 合并回 `main`

## 备注

- 本仓库最初为 GitHub Skills 练习创建，内容会随练习进度更新。
- 提交信息建议使用祈使句，简明说明「做了什么」。

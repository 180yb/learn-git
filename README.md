# learn-git

我的第一个 Git 练习仓库。从零走到推上 GitHub 的全过程都在提交历史里。

🔗 线上主页：https://180yb.github.io/learn-git/

## 我在练什么

- [x] git init 建立仓库
- [x] 工作区 → 暂存区 → 提交，理解这三层
- [x] 分支与合并
- [x] 解决冲突
- [x] 推到 GitHub

## 这个仓库里发生过什么

1. `48e44b7` 初始提交：仓库骨架与主页雏形
2. `ac6ca01` 主页版本号改成 0.2
3. 从这时分叉：
   - `main` 上加了句欢迎语
   - `feature/about` 上写清楚小站要放什么
4. `242d24f` 合并两条分支，**故意撞车**，手动解决了 `index.html` 里的冲突

想看那棵分叉的树：

```bash
git lg        # 缩写，等于 git log --oneline --graph --decorate --all
```

## 一句话备忘

`git status` 是我最该常用的命令，它随时告诉我"现在处于什么状态"。

## 日常循环

```bash
git pull                        # 先拉
# 改东西
git add .
git commit -m "feat: 做了什么"
git push
```

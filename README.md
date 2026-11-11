# git-learning

我的 Git / GitHub 学习仓库。这里记录学习过程和笔记。

## 学习进度

- [x] 安装 Git
- [x] 配置用户名和邮箱
- [x] 生成 SSH 密钥并添加到 GitHub
- [x] 打通 SSH 连接（走 443 端口）
- [x] 推送第一个仓库
- [ ] 创建第一个分支
- [ ] 发起第一个 Pull Request
- [ ] 给别人的项目提一次 PR

## 学习计划

| 周次 | 主题 |
|---|---|
| 第 1 周 | Git 原理与撤销（四区模型、reset、reflog、冲突） |
| 第 2 周 | 远程仓库与 Pull Request |
| 第 3 周 | GitHub Actions 与开源贡献 |

完整路线见 [docs/学习路线.md](docs/学习路线.md)。

## 命令小抄

```bash
git status                    # 我现在在什么状态
git add -p                    # 挑选要提交的改动
git commit -m "feat: xxx"     # 拍快照
git log --oneline --graph --all   # 看历史全貌
git switch -c feat/xxx        # 开新分支
git switch main               # 回主干
git merge feat/xxx            # 合并
git push -u origin feat/xxx   # 推上去
git restore <file>            # 撤销未暂存的改动
git reset --soft HEAD~1       # 撤销提交但保留改动
git revert <sha>              # 撤销已推送的提交
git reflog                    # 后悔药
```
##我的第一条心得

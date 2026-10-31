# 克隆
```
git clone https://github.com/用户名/paranormal-bureau.git
cd paranormal-bureau
```

# 建立分支
```
git switch -c feature/分支名称
```

# 提交
```
git add .  **(提交全部更改)**
git commit -m "feat: 填写提交内容"

git push -u origin HEAD （当前分支）
git push -u origin feature/main
git push -u origin feature/分支名称
```

# 合并分支
```
- 通过 Pull Request 合并
1. 打开 GitHub 仓库。
2. 进入 Pull requests → New pull request。
3. 选择 base: main 和 compare: feature/分支名称。
4. 创建 PR，等待队友审核。
5. 检查通过后点击 Merge pull request。
```

# 同步最新主分支
- 例如已有新的分支与 main 合并，需要同步最新的 main
```
git fetch origin
git merge origin/main
```
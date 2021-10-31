## 21-10-31

### 共有部分

#### 创建项目目录

```bash
mkdir react-ts
cd react-ts
```

#### 初始化 Git 仓库

```bash
git init
```

前 2 步可换成，先在 Github 上创建项目，然后 git clone 复制下来。好处是之后 package.json 中会自动填写作者、Git Repository 地址。

```bash
# 克隆
git clone https://github.com/izypd/react-ts.git
cd react-ts
# 主分支名换为main
git branch -M main
# 添加所有文件到git
git add .
# 提交
git commit -a -m "docs: 添加README.md、CHANGELOG.md、.gitignore"
# 推送
git push -u origin main
```


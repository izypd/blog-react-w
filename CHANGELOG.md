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

#### 创建 package.json 文件

```bash
pnpm init
```

#### 添加 TypeScript

```bash
# 安装 TypeScript ，并创建 tsconfig.json
pnpm add -D typescript && pnpm tsc --init
# 通过 tsc 编译并执行
pnpm tsc && node dist/es/index.js
```

#### 添加 Prettier

```bash
pnpm add -D prettier
```

#### 添加 ESLint

```bash
pnpm add -D eslint
pnpm add -D @typescript-eslint/eslint-plugin @typescript-eslint/parser
pnpm add -D eslint-config-airbnb eslint-config-airbnb-typescript
pnpm add -D eslint-plugin-import eslint-plugin-jsx-a11y
pnpm add -D eslint-config-prettier eslint-plugin-react eslint-plugin-react-hooks
```

#### 添加 React

```bash
pnpm add react react-dom
pnpm add -D @types/react @types/react-dom
```


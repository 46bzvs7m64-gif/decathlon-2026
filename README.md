# 迪卡侬 2026 年度新品展示网站

## 🚀 GitHub Pages 部署指南

### 第一步：创建 GitHub 仓库

1. 打开 [github.com](https://github.com)
2. 点击右上角 **+** → **New repository**
3. 仓库名称填：`decathlon-2026`（可以自定义）
4. 选择 **Public**（Pages 必须是公开仓库才能免费使用）
5. 不要勾选 "Add a README file"
6. 点击 **Create repository**

### 第二步：初始化本地仓库并上传

打开终端（PowerShell / CMD / Git Bash），依次执行以下命令：

```bash
# 进入项目目录
cd D:\简历模板\dist

# 初始化 Git 仓库
git init

# 添加所有文件
git add .

# 提交
git commit -m "Initial commit"

# 关联远程仓库（把下面的 你的用户名 替换成你的 GitHub 用户名）
git remote add origin https://github.com/你的用户名/decathlon-2026.git

# 推送到 main 分支
git branch -M main
git push -u origin main
```

### 第三步：开启 GitHub Pages

1. 回到 GitHub 仓库页面
2. 点击顶部菜单 **Settings**
3. 左侧边栏找到 **Pages**（在 Code and automation 下面）
4. 在 **Build and deployment** 区域：
   - **Source** 选择 **Deploy from a branch**
   - **Branch** 选择 **main** / **root**
5. 点击 **Save**

### 第四步：等待部署完成

- 回到仓库页面 → 点击 **Actions** 标签
- 看到绿色的 ✔️ 表示部署成功
- 访问你的在线地址：
  ```
  https://你的用户名.github.io/decathlon-2026/
  ```

---

## 📁 文件说明

| 文件 | 说明 |
|------|------|
| `index.html` | 迪卡侬 2026 年度新品展示网站（单文件 HTML） |

---

## 🎨 网站特性

- 响应式设计，兼容手机与电脑
- 七大品类新品矩阵展示
- 品类筛选 Tab 交互
- 滚动入场动画与数字计数动画
- 核心战略与创新点解析
- SWOT 竞争分析

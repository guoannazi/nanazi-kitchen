# 娜娜子美妈厨房日记

一个给宝宝做辅食、给大人做美食的点餐工作台。

## 功能

- 📋 **今日菜单**：按早餐/午餐/晚餐/加餐管理当天菜品
- 📚 **菜谱库**：15 道宝宝辅食（18M+）+ 56 道大人餐（江西辣鸡爪、面食、排骨、鸡翅、村驴菜系等）
- 🎲 **点餐抽餐**：摇一摇随机抽菜，一键搭配两菜一汤
- 👨‍👩‍👧 **家人点餐**：扫码点餐，妈妈同步汇总
- 🛒 **食材清单**：自动汇总今日菜单食材，一键复制发微信

## 部署到 GitHub Pages 步骤

### 第 1 步：注册 GitHub 账号（2 分钟）

1. 打开 https://github.com/signup
2. 输入邮箱、设置密码、用户名（建议用小写字母，如 `nana-mom`）
3. 验证邮箱

### 第 2 步：创建仓库（1 分钟）

1. 登录后访问 https://github.com/new
2. **Repository name** 填：`nana-kitchen`
3. **Public**（公开）
4. ✅ 勾选 **Add a README file**
5. 点 **Create repository**

### 第 3 步：上传 index.html（1 分钟）

1. 在仓库页面点 **Add file** → **Upload files**
2. 把你电脑上的 `index.html` 拖进去
3. 点 **Commit changes**
4. 同样把 `.nojekyll` 文件也上传（如果有）

### 第 4 步：开启 GitHub Pages（1 分钟）

1. 仓库页面点 **Settings** → 左侧 **Pages**
2. **Source** 选 `Deploy from a branch`
3. **Branch** 选 `main`，文件夹选 `/ (root)`
4. 点 **Save**
5. 等 1-2 分钟，刷新页面，顶部会出现你的网址：
   ```
   https://你的用户名.github.io/nana-kitchen/
   ```

### 第 5 步：分享给家人

1. 打开你的新网址
2. 进入「家人点餐」Tab
3. 点「分享二维码」
4. 把二维码截图发到微信群，或打印贴冰箱上
5. 家人微信扫码 → 填身份 → 选菜 → 提交
6. 你打开网址 → 「家人点餐」→「同步家人点餐」→「导入今日菜单」

## 文件说明

- `index.html` — 完整工作台（单文件，双击即可用）
- `.nojekyll` — 告诉 GitHub Pages 不要跳过以下划线开头的文件

## 数据存储

- 菜谱/今日菜单：浏览器 localStorage（每个设备独立）
- 家人点餐同步：MantleDB 免费云端（无需账号）

## 备注

- GitHub Pages 完全免费，永久有效
- 微信内可直接打开
- 修改菜谱后重新上传 index.html 即可更新

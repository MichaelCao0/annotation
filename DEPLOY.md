# 部署说明

## 步骤1: 创建GitHub仓库

1. 访问 https://github.com/new
2. 仓库名: `hq1k-annotation`
3. 设置为公开仓库
4. 勾选"Add a README file"

## 步骤2: 推送代码

```bash
# 初始化Git仓库
git init
git add .
git commit -m "Initial commit: HQ1K annotation system"

# 添加远程仓库（替换your-username为实际用户名）
git remote add origin https://github.com/your-username/hq1k-annotation.git

# 推送到GitHub
git push -u origin main
```

## 步骤3: 启用GitHub Pages

1. 访问仓库设置页面
2. 滚动到"Pages"部分
3. 选择"Deploy from a branch"
4. 选择"main"分支
5. 选择"/ (root)"文件夹
6. 点击"Save"

## 步骤4: 访问应用

部署完成后，访问：
https://your-username.github.io/hq1k-annotation/

## 注意事项

1. 确保后端服务器正在运行: http://223.109.239.18:8080
2. 修改README.md中的your-username为实际用户名
3. 如果需要自定义域名，创建CNAME文件

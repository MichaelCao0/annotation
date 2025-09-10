# HQ1K 图像编辑偏好标注系统

这是一个用于图像编辑偏好标注的Web应用程序。

## 访问地址

- 主页面: https://MichaelCao0.github.io/annotation/
- 用户管理: https://MichaelCao0.github.io/annotation/user_management.html

## 功能特性

- 图像编辑偏好标注
- 用户信息管理
- 标注结果导出
- 实时数据统计

## 技术栈

- HTML5
- CSS3
- JavaScript
- Flask (后端API)

## 部署说明

本项目使用GitHub Pages进行部署，后端API运行在独立服务器上。

## 本地开发

如需本地开发，请确保后端服务器正在运行：

```bash
cd /data/zhecao181/HQ1K
conda activate flux
python start_annotation.py --server --port 8080
```

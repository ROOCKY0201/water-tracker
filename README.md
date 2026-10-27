# 今日喝水 · iPhone 桌面版

功能：
- 今日喝水目标 1500 ml
- +50 / +100 / +200 ml 三个按钮
- 中间人物喝水动画
- 自动保存每日总量和每次记录
- 历史记录查看
- 每天自动开始新的记录
- 支持 PWA，可添加到 iPhone 主屏幕
- 离线打开（首次成功加载后）

## 最简单部署方法：GitHub Pages
1. 新建一个 GitHub 仓库，例如 water-tracker。
2. 把这个文件夹里的所有文件上传到仓库根目录。
3. GitHub 仓库 → Settings → Pages。
4. Source 选择 “Deploy from a branch”。
5. Branch 选择 main / root，保存。
6. 等页面生成后，用 iPhone Safari 打开 GitHub Pages 地址。
7. Safari 底部“分享” → “添加到主屏幕”。
8. 桌面会出现“喝水”图标，打开后接近独立 App。

## 数据保存说明
数据通过浏览器 localStorage 保存在当前 iPhone / 当前网站地址中。
如果清除 Safari 网站数据、换手机或换部署网址，历史记录不会自动同步。

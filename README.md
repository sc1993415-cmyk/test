# 睿思转播 RESCAN LIVE 企业官网

适用于 GitHub Pages 的静态官网，包含桌面与手机布局、服务介绍、转播场景筛选、联系弹窗和本地生成转播需求简报。

## 开启网站

1. 打开仓库 Settings → Pages。
2. Source 选择 Deploy from a branch。
3. Branch 选择 main，文件夹选择 /(root)，点击 Save。
4. 等待部署完成后访问 https://sc1993415-cmyk.github.io/test/ 。

Custom domain 留空，不需要购买域名。

## 更新内容

- 页面文字与联系方式：index.html
- 场景详情和交互：app.js
- 样式及手机布局：style.css
- 图片：assets/

所有资源均使用相对路径，支持 /test/ 子目录。更新 main 分支后，GitHub Pages 会自动发布。

需求简报在浏览器中生成，填写的内容不会自动发送。

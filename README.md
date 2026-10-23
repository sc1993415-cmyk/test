# 睿思转播 RESCAN LIVE 企业官网

适用于 GitHub Pages 的静态官网，包含桌面与手机布局、服务介绍、转播场景筛选、联系弹窗和本地生成转播需求简报。

## 网站地址

https://sc1993415-cmyk.github.io/test/

## 自动发布

1. 打开仓库 Settings → Pages。
2. Source 选择 GitHub Actions。
3. 发布流程位于 .github/workflows/static.yml，提交到 main 后自动运行，也可以在 Actions 中手动启动。
4. 等待 Deploy static content to Pages 流程成功后访问上面的网站地址。

Custom domain 留空，不需要购买域名。

## 更新内容

- 页面文字与联系方式：index.html
- 场景详情和交互：app.js
- 样式及手机布局：style.css
- 图片：assets/

所有资源均使用相对路径，支持 /test/ 子目录。更新 main 分支后，GitHub Pages 会自动发布。

需求简报在浏览器中生成，填写的内容不会自动发送。

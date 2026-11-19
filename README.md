# Resume · GitHub Pages在线简历

独立的静态在线简历站点，使用HTML/CSS，无后端、无登录、无第三方JS。**当前为可预览的公开前候选稿。**

## 目录

```text
resume/
├── README.md           # 本说明
└── docs/
    ├── .nojekyll
    ├── index.html       # 在线简历页面
    └── assets/site.css  # 响应式样式与打印样式
```

## 发布到GitHub

1. GitHub新建名为`resume`的空仓库；将本目录作为仓库根目录，提交并推送。
2. 在仓库 **Settings → Pages** 选择 **Deploy from a branch → main → /docs → Save**。
3. 页面成功部署后，到设置页核实实际访问URL；若GitHub用户名是`SheatheLi`，预计路径为`https://sheatheli.github.io/resume/`，但在成功部署前**不是已验证的网址**。
4. 进入仓库 **About → Website** 填写经实际访问成功的网址。
5. 在其他六个项目仓库中将交互展示地址、源码地址核对后，确保本页面卡片不会产生404。

## 正式公开前的内容核验（必须）

- **工程经历：** 工作经历尚待单独核实后加入在线页面；当前网页不包含未经核实的企业任职内容。
- **个人贡献：** 对六个项目如使用AI生成/辅助编码，应准确区分个人理解、参与、实际验收与自动生成素材；不能仅以代码存在声称完全独立完成。
- **隐私：** 默认不公开电话、私人邮箱、住址和个人证件。
- **项目链接：** `docs/index.html`中预填`SheatheLi`的预期GitHub仓库与Pages路径。发布之前确认用户名、仓库确实存在及Pages已启用，不要让尚未建立的链接留在正式求职页面。
- **可打印版本：** 浏览器打印已配置样式；若需要对外PDF简历，应由通过事实核验的正式简历导出，不能直接将模拟履历公开。
- **License：** 本仓库需自行决定代码与文字授权方式；未经决定不添加默认MIT许可。

## 本地预览

在项目根目录运行：`python -m http.server 8000`，然后打开`http://localhost:8000/docs/`；也可直接用浏览器打开`docs/index.html`。

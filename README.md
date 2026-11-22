# Resume | 在线简历

基于《李昊洋简历(3).docx》整理的静态 HTML/CSS 在线简历，包含个人简介、个人优势、技术栈、工作经验、六项技术项目、教育背景与联系方式。页面可在 GitHub Pages 发布，无需后端或构建工具。

## 查看简历

- 在线地址：<https://sheatheli.github.io/resume/>
- 技术项目：页面内分别链接六个独立 GitHub 仓库及相应展示网站。
- 本地预览：在仓库根目录执行 `python -m http.server 8000`，访问 <http://localhost:8000/docs/>。

## 文件结构

```text
resume/
├── README.md
└── docs/
    ├── .nojekyll
    ├── index.html
    └── assets/site.css
```

## 页面更新

网页文字以用户提供的正式简历文件为依据，未另行添加工作年限、企业成果或荣誉。再次编辑时，应同步核对时间、职位、技术项目结果、联系方式与实际可公开信息。

## 发布

使用本包附带的统一更新脚本提交到 `SheatheLi/resume`，GitHub Pages 源分支维持 `main /docs`。网页包含电话号码和邮箱，公开后可能被搜索引擎索引；公开前请确认个人信息、经历陈述及对外披露范围。

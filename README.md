# Resume Minimal Typeset（简历简约排版 Skill）

一个 [WorkBuddy](https://www.workbuddy.cn) 技能：按固定「简约灰阶」规格生成简历 HTML，经 Chromium 打印导出为 PDF。

## ✨ 版式特征

- **单栏长页**：217 × 307 mm，无侧边栏，全文档零分隔线
- **全灰阶**：仅 #2B2B2B / #333333 / #545454 / #666666 四色，无彩色主题
- **微软雅黑**：姓名 25.5pt 加粗、章节标题 13.5pt、正文 10.5pt 行距 1.9 两端对齐
- **层级靠留白**：章节间大留白 40–68pt，不用任何边框线、下划线、色块
- **emoji 图标**：🎓 教育经历 / 💼 工作经历 / 🛠 相关技能，灰色视觉统一
- **头像**：60×80pt（3:4）圆角

## 📦 安装

把 `resume-minimal-typeset/` 目录放到 `~/.workbuddy/skills/` 下，或直接用打包好的 zip。

## 🚀 直接使用

打开 `resume-minimal-typeset/assets/resume-template.html` 替换示例内容，浏览器「打印 → 另存 PDF」（边距设「无」、勾选背景图形）即可得到成品简历 PDF。

## 🧩 Skill 结构

```
resume-minimal-typeset/
├── SKILL.md                        # 触发时机 + 生成/复刻工作流
├── references/
│   └── typography-spec.md          # 排版规格说明书（数值基准）
└── assets/
    └── resume-template.html        # 可运行模板（示例数据）
```

## 📄 License

MIT

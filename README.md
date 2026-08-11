# Skills

## 安装

1. 将 `skills/` 目录复制到指定目录

2. 一键安装到`.agents`
```bash
# ===Windows===

# 创建符号链接
mklink /D /J "%USERPROFILE%\.agents\skills" ".\skills"
# 复制
xcopy /E /I /Y ".\skills" "%USERPROFILE%\.agents\skills"




# ===Linux===

# 创建符号链接
ln -s skills ~/.agents/skills
# 复制
cp -r skills ~/.agents/skills
```

## 技能列表

| 技能 | 说明 | 来源 |
| --- | --- | --- |
| read-first-before-implementation | 在提出方案或修改代码之前，先阅读并理解相关代码。 |
| html-report | 不再输出 Markdown，而是生成一个单文件 HTML 报告，包含标签页、流程图和颜色高亮，可直接在浏览器中打开。 |
| test-driven-bug-investigation | 修复 Bug 前先编写能稳定复现问题的最小测试，确认 Bug 真实存在后，再根据证据定位根因。 |
| grilling | grill the user | [mattpocock/skills](https://github.com/mattpocock/skills/blob/main/skills/productivity/grilling/SKILL.md) |

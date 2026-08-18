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
| find-skills | vercel-labs find skills | [find-skills](https://github.com/vercel-labs/skills/blob/main/skills/find-skills/SKILL.md) |
| grilling | grill the user | [mattpocock/skills](https://github.com/mattpocock/skills/blob/main/skills/productivity/grilling/SKILL.md) |

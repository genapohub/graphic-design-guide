# Graphic Design Guide — 平面设计师方案产出指南

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-1.0.0-green.svg)](SKILL.md)

一个面向 AI 编程助手的 **平面设计师 Skill**，将视觉设计方法论转化为可执行工作流。自动识别 5 类场景（0→1 品牌识别设计 / 营销活动物料 / 单件物料 / 品牌焕新升级 / 风格探索），按对应清单产出色彩体系、字体方案、Logo设计规范、物料清单、版权检查等完整设计交付物。

## 适用场景

| 场景 | 示例 | 产出量 |
|------|------|:---:|
| 0→1 品牌识别设计 | 新品牌 VI 全案 | 10-12类 |
| 营销活动物料 | 618大促线上线下物料 | 6-8类 |
| 单件物料制作 | 一张节气海报 | 2-3类 |
| 品牌焕新/VI升级 | Logo改版 + 全渠道切换 | 8-10类 |
| 风格探索/Mood Board | 新业务的视觉风格提案 | 3-4类 |

## 触发热词

平面设计、VI设计、品牌设计、Logo设计、海报设计、Banner设计、视觉设计、品牌手册、宣传物料、品牌升级、Mood Board

---

## 安装

本 Skill 遵循 **Open Agent Skills 标准**（SKILL.md 格式），兼容以下工具：

### WorkBuddy / CodeBuddy

**方式一：克隆到 skills 目录**
```bash
# 克隆到 workbuddy skill 目录（全局可用）
git clone https://github.com/genapohub/graphic-design-guide.git ~/.workbuddy/skills/graphic-design-guide
```

**方式二：ZIP导入**
```bash
# 先下载并打包
git clone https://github.com/genapohub/graphic-design-guide.git
zip -r graphic-design-guide.zip graphic-design-guide/
```
然后在 WorkBuddy 桌面端 → **技能市场** → **添加技能/上传技能** → **点击"跳过检测，直接安装"**。

### Trae

**ZIP 导入**
```bash
# 先下载并打包
git clone https://github.com/genapohub/graphic-design-guide.git
```
然后在 Trae → **设置** → **Rules & Skills** → **创建** → 上传 `graphic-design-guide.zip`。

### Codex

```bash
# 克隆到 skills 目录
git clone https://github.com/genapohub/graphic-design-guide.git ~/.codex/skills/graphic-design-guide

# 或使用 cc switch (推荐)
git clone https://github.com/genapohub/graphic-design-guide.git ~/.cc-switch/skills/graphic-design-guide
```

重启 CC Switch客户端/Codex客户端 后自动发现。也可以在对话中输入 `$graphic-design-guide` 手动调用。

### Cursor
```bash
# 克隆到 skills 目录
git clone https://github.com/genapohub/graphic-design-guide.git ~/.cursor/skills-cursor/graphic-design-guide
```

重启 Cursor客户端 后自动发现。也可以在对话中输入 `$graphic-design-guide` 手动调用。

---

## 使用

```
帮我设计新品牌「宠宝树」的 VI 视觉系统
618 大促活动的海报和 Banner 方案
出个立秋节气海报的设计方案
我们品牌要焕新，Logo 和色系都换，出方案
```

---

## 目录结构

```
graphic-design-guide/
├── SKILL.md                  # 主指令
├── README.md
├── LICENSE
├── .gitignore
└── references/
    └── 平面设计方法论.md       # 详细方法论
```

## 许可

[MIT](LICENSE) © zhangmengbo

# KOL 建联计划与飞书表格模板 / KOL Outreach Plan and Feishu Table Templates

**简体中文** | [English](README.en.md)

利用自带模板整理 KOL 筛选标准、建联计划、进度台账和复盘表。

[下载完整项目包](https://github.com/hezonglinhzl-creator/varla-electric-mobility-skills-and-tools/raw/main/packages/skill-kol-feishu-plan-builder.zip) · [全部项目](https://github.com/hezonglinhzl-creator/varla-electric-mobility-skills-and-tools)

## 功能特性

- 目标市场和预算约束
- 飞书可粘贴表格结构
- 建联与复盘字段

## 这个包里有什么

| 内容 | 位置 |
| --- | --- |
| Skill 指令 | [SKILL.md](skill/kol-feishu-plan-builder/SKILL.md) |

本项目是 Codex 工作流/脚本 Skill，没有另外一套需要启动的网页后台。

## 下载和解压

1. 在本仓库点绿色 **Code → Download ZIP**，或者点上方“下载完整项目包”。
2. 下载完成后右键 ZIP，选择**全部解压**，打开能看到此 README 的文件夹。
3. 保留整个目录；先按下一节准备程序，再安装和使用对应 Skill。

## 1. 先准备程序

无需另装程序。准备已登录的 Codex 和下方输入资料即可；带 Python 脚本的项目再按本页脚本说明安装依赖。

## 2. 再安装 Skill

1. 回到解压后的项目根目录，双击 `安装Skill.cmd`。
2. 安装器把 `skill/kol-feishu-plan-builder` 复制到 `%USERPROFILE%\.codex\skills\kol-feishu-plan-builder`。遇到同名 Skill 会跳过，留意窗口结果。
3. 重新打开 Codex，新建对话，使用下面的 Skill 名称和示例。
4. 公司策略禁止脚本时，可先阅读 install.ps1，或手动把整个 Skill 目录复制到同一目标位置。

## 3. 第一次怎么用

| 准备项 | 内容 |
| --- | --- |
| 输入 | 车型、平台、市场、预算、目标和时间范围。 |
| 输出 | 计划文档和待复制到飞书的空白表格。 |

```text
用 kol-feishu-plan-builder，做一个美国电摩 Instagram KOL 建联计划；先给空白模板和筛选规则，不填写真实联系人。
```


## 当前限制与常见问题

这是模板 Skill；自动写飞书需要额外的飞书连接工具及访问权限。

| 问题 | 怎么处理 |
| --- | --- |
| 找不到 Skill | 检查安装窗口结果和目标 SKILL.md，重新打开 Codex 并新建对话。 |
| 程序启动失败 | 在程序目录打开 PowerShell 运行本文命令，让错误保留在窗口，再对照对应程序 README。 |
| 网页看不到插件 | 确认选中直接包含 manifest.json 的目录、网站受支持，并刷新网页。 |
| 外部服务不可用 | 配置自己的授权并检查资源权限；保留本地结果，不把失败说成同步/发送成功。 |

## 隐私与验证范围

这是程序源码与 Skill 分发包，不附带真实账号、OAuth 令牌、客户/KOL 台账、合同、订单、邮箱导出或业务媒体。服务需使用自己的配置。已检查文档和包内入口；此次文档核对没有执行真实下单、发邮件或发布内容。

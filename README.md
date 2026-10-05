# spicytater-ui-design

一套用于 AI 编码助手（Claude Code / Codex / WorkBuddy 等）的 **UI 设计参考 Skill**。

把「页面做得高级一点」「这个交互不够顺」这类模糊要求，转成可定位的问题、可选的设计风格、明确的组件行为，以及可验收的清单。

## 内容

| 文件 | 内容 |
|---|---|
| `SKILL.md` | Skill 定义：按任务读取资料的索引、把案例落实到需求的方法、来源与事实边界 |
| `references/design-styles.md` | 33 种设计风格（STYLE 编号），含适用场景与材质职责 |
| `references/components.md` | 40 个前端与交互案例（UI 编号），含控件选用与状态定义 |
| `references/workflows.md` | 方案组合、需求提示词模板与验收清单 |
| `references/video-design-workflow.md` | 从参考图到页面实现的 7 步流程；后台与管理系统美化做法 |
| `references/video-interactions.md` | 手势、动效、图片交互、无限画布、编辑历史、任务反馈、命令面板 |
| `references/bilibili-sources.md` | 24 条 B 站 UI 视频的来源索引与证据边界 |
| `assets/design-styles.jpg` | 33 种风格目录长图（用于视觉比较，非可编辑原型） |
| `agents/openai.yaml` | 面向 Codex 类客户端的界面元数据 |

## 安装

Skill 是纯目录扫描式加载，把整个仓库目录放进对应客户端的 skills 目录即可，无需注册或构建。

```bash
git clone https://github.com/DcC176/spicytater-ui-design.git
```

| 客户端 | 目标路径 |
|---|---|
| WorkBuddy（用户级） | `~/.workbuddy/skills/spicytater-ui-design/` |
| Codex | `<CODEX_HOME>/skills/spicytater-ui-design/` |

Windows 下 `~` 即 `C:\Users\<你的用户名>`。放好后重启会话，新描述与新增参考文档才会被索引。

也可以直接从 [Releases](https://github.com/DcC176/spicytater-ui-design/releases) 下载打包好的 zip 解压使用。

## 使用

在提示词中显式引用即可，例如：

```text
使用 $spicytater-ui-design，为当前页面选择合适风格并制定布局、交互状态和验收方案。
```

Skill 会按任务只读取相关部分，不会一次加载全部案例。

## 来源与事实边界

- 设计风格、前端与交互分类整理于 2026 年 10 月 4 日，来源为 **spicytater.cn** 的对应条目。
- 2026 年 10 月 5 日新增 **24 条 B 站 UI 视频**（[合集「VibeCoding：从想法到上线」](https://space.bilibili.com/1751009568/upload/video)）的归纳，基于**本地音频转写（ASR）**。
- ⚠️ **转写内容未经人工听校，也未经视频视觉核验**。结论不表示已观看或验证过视频中的实际演示，也不声称覆盖该账号全部历史投稿。主题与结论可通过 `references/bilibili-sources.md` 回溯。
- 案例说明经过归纳；需求模板、方案组合与验收建议由整理者编写，**不是网站作者或视频作者的原话**。
- 网站示例中的品牌、指标与完成态不证明真实客户、业务效果或已执行的验证。Apple HIG、Material Design 等是该站的介绍，不能替代目标平台的官方规范。
- 资料可离线使用；用户需要最新内容时应自行核对上述来源。

## 权利说明

本仓库为**参考与需求表达**用途的技术整理，**不附带任何开源许可证**，也不随仓库授予任何额外权利。

- 整理者编写的部分（流程归纳、需求模板、验收建议）可自由用于个人的设计与开发工作。
- `assets/design-styles.jpg`、`references/design-styles.md`、`references/components.md` 中的风格与案例条目标题，**版权属于 spicytater.cn 原作者**，这里作为学习与引用的索引呈现。
- 24 条视频的**原始音视频与逐字稿不在本仓库内**，仅保留整理后的结论，版权属于原视频作者。
- 本仓库**不授予**任何品牌资产复制、商业再分发或模型训练授权。

如权利人认为本仓库内容不当，请开 Issue 说明，将立即处理。

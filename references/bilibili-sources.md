# B 站 UI 视频来源与证据边界

整理时间：2026年10月5日。来源：[SpicyTater- 投稿](https://space.bilibili.com/1751009568/upload/video)，UID 1751009568，合集“VibeCoding：从想法到上线”。

取得最近 50 条投稿和该合集的 27 条记录；提炼其中 24 条 UI 视频，排除网站运营动态、Cursor 工具和 Git/GitHub 教学。账号后续分页遇到 412 风控，因此不声称覆盖全部历史投稿。

通过公开接口取得对应视频音频，在本地使用 faster-whisper large-v3-turbo 做批量与逐段两轮转写；未读取浏览器 Cookie，未上传音频到云端转写。两轮输出对照用于发现漏句和异常识别，不等于人工听校；未观看视频视觉演示。正文是整理者的简洁归纳和使用建议，不是原作者逐字指令、粉丝群 Skill 或原始私有资料。不能声称取得了作者未公开的 Skill 文件。

引用 V 编号可定位视频；时间范围是主题定位入口，不保证 ASR 字幕逐字准确。正文中的英文名称经过常见拼写归一化。没有可靠音频依据的片段不作结论。

## 视频索引

| 编号 | 视频 | 时长 | 本 Skill 使用位置 |
|---|---|---|---|
| V01 | [Vibe Coding术语库：把需求说清楚](https://www.bilibili.com/video/BV1fmba6hEjn/) | 01:39 | 需求表达与功能状态 |
| V02 | [用大白话向AI描述7种加载指令 7种常见的加载指令，你知道怎么用大白话和AI描述生成吗？](https://www.bilibili.com/video/BV1sD826SEeq/) | 01:25 | 加载 |
| V03 | [用大白话向AI描述7种常见的弹窗指令，你知道怎么用大白话和AI描述生成吗？](https://www.bilibili.com/video/BV15z8D6CE8N/) | 01:40 | 六类弹层 |
| V04 | [用大白话向AI描述7种常见的导航指令，你知道怎么用大白话和AI描述生成吗？](https://www.bilibili.com/video/BV1aQ4f6dE1C/) | 01:45 | 导航用途 |
| V05 | [用大白话向AI描述8种展开面板指令，你知道怎么用大白话和AI描述生成吗？](https://www.bilibili.com/video/BV12h466tEFk/) | 02:04 | 展开内容 |
| V06 | [用大白话向AI描述6种拖拽动效指令，你知道怎么用大白话和AI描述生成吗？](https://www.bilibili.com/video/BV1kZ4D6SEMf/) | 01:19 | 拖动用途 |
| V07 | [用大白话向AI描述7种展开动画指令，你知道怎么用大白话和AI描述生成吗？](https://www.bilibili.com/video/BV1F1tx61EGC/) | 01:38 | 容器形态变化 |
| V08 | [用大白话向AI描述8种下拉组件指令，你知道怎么用大白话和AI描述生成吗？](https://www.bilibili.com/video/BV1xytu6GEi5/) | 01:56 | 下拉选择 |
| V09 | [用大白话向AI描述7种图表交互动画指令，你知道怎么用大白话和AI描述生成吗？](https://www.bilibili.com/video/BV1LPt967EQu/) | 01:40 | 图表交互 |
| V10 | [用大白话向AI描述10种App/小程序高级动画指令，你知道怎么用大白话和AI描述生成吗？](https://www.bilibili.com/video/BV1gAtm69ER4/) | 04:34 | 组件联动 |
| V11 | [用大白话向AI描述8种App/小程序高级交互质感指令，你知道怎么用大白话和AI描述生成吗？](https://www.bilibili.com/video/BV1aEt269Ej5/) | 04:24 | 物理质感 |
| V12 | [用大白话向AI描述7种App/小程序高级交互设计指令，你知道怎么用大白话和AI描述生成吗？](https://www.bilibili.com/video/BV1c9bP69EJR/) | 03:27 | 取消与接管 |
| V13 | [用大白话向AI描述7种App/小程序高级图片交互设计指令，你知道怎么用大白话和AI描述生成吗？](https://www.bilibili.com/video/BV1E7bP6EEjp/) | 03:44 | 图片效果 |
| V14 | [用大白话向AI描述3种官网高级交互设计指令，你知道怎么用大白话和AI描述生成吗？](https://www.bilibili.com/video/BV1FjYM6gEAa/) | 03:15 | 滚动官网 |
| V15 | [用大白话向AI描述5种无限画布交互指令，你知道怎么用大白话和AI描述生成吗？](https://www.bilibili.com/video/BV1H1YL6YEub/) | 03:52 | 无限画布 |
| V16 | [用大白话向AI描述6种6种空间卡片编排指令，你知道怎么用大白话和AI描述生成吗？](https://www.bilibili.com/video/BV1coeq6bEPf/) | 03:27 | 空间卡片 |
| V17 | [同样用 AI 做页面，为什么你的像作业，别人的像产品？](https://www.bilibili.com/video/BV1V3e46JENM/) | 12:05 | 设计开发流程 |
| V18 | [AI 做的页面总像模板？你需要的不只是提示词，用 AI 设计网页：找参考、生成概念图，再交给 AI 开发](https://www.bilibili.com/video/BV1dsaw62EWy/) | 06:42 | 参考与概念图 |
| V19 | [用大白话向AI描述6种组件交互编排指令，你知道怎么用大白话和AI描述生成吗？](https://www.bilibili.com/video/BV1zHhX6oEVs/) | 04:21 | 组件编排 |
| V20 | [用大白话向AI描述5种标题动效指令，你知道怎么用大白话和AI描述生成吗？](https://www.bilibili.com/video/BV1Bmaz6xECS/) | 04:24 | 标题动效 |
| V21 | [用大白话向AI描述4种任务反馈指令，你知道怎么用大白话和AI描述生成吗？](https://www.bilibili.com/video/BV1WBaz6YE5y/) | 02:13 | 任务反馈 |
| V22 | [用大白话向AI描述3种编辑工具交互指令，你知道怎么用大白话和AI描述生成吗？](https://www.bilibili.com/video/BV1WBaz6YEAD/) | 02:24 | 编辑历史 |
| V23 | [用大白话向AI描述命令面板交互指令，你知道怎么用大白话和AI描述生成吗？](https://www.bilibili.com/video/BV1nkaz6fEn7/) | 02:26 | 命令面板 |
| V24 | [用大白话向AI描述5种导航交互指令，你知道怎么用大白话和AI描述生成吗？](https://www.bilibili.com/video/BV1rkaz6fENS/) | 04:20 | 创意导航 |

## 关键主题的时间入口

- V17：01:00–03:55 共同样式；03:55–05:20 页面与线框；05:20–06:55 核心流程；06:55–08:25 概念图；08:25–10:00 实现；10:00–12:05 资产与验证。
- V18：00:00–03:20 找参考与选方向；03:20–04:20 图片和真实组件拆分；04:20–06:42 后台组件与主题调整。
- V15：00:20–01:00 坐标缩放；01:00–01:50 框选与成组；01:50–02:30 连线；02:30–03:15 排布；03:15–03:52 小地图。
- V21：00:20–00:42 分阶段反馈；00:42–01:02 逐步结果；01:02–01:28 任务身份与取消；01:28–02:13 部分失败与超时。
- V22：00:25–00:55 非破坏编辑；00:55–01:32 撤销分组；01:32–02:23 方案快照。
- V23：00:20–00:58 命令分组与可用条件；00:58–01:27 参数步骤；01:27–02:26 键盘、中文输入、焦点恢复和手机入口。

V02–V14、V16、V19–V20、V24 为分项讲解短视频，可从对应主题标题定位整条视频。V03 标题写七类，实际音频列举六类，以正文为准。

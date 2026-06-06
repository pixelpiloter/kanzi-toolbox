# Kanzi Studio 实战工具箱

> 整理自 CSDN 博主 **chen_227** 的 43 篇 Kanzi 优化专栏文章（2022-11 → 2026-05）
> 源链接：https://blog.csdn.net/chen_227/category_11957782.html

本仓库系统梳理 Rightware **Kanzi Studio**（HMI/3D UI 设计引擎）的工程实战经验。所有内容均来自原作者公开博客，仅做归档、分类和 Markdown 化整理，**版权归原作者所有**。

## 适用人群

- 汽车智能座舱 HMI 工程师
- 使用 Kanzi Studio 做车载/嵌入式 UI 的开发人员
- 想用 **C++ / C# / OpenGL** 给 Kanzi 写插件和扩展的研究者
- 对 **MCP（Model Context Protocol）驱动 Kanzi** 感兴趣的人

## 仓库结构

```
kanzi-toolbox/
├── README.md                 ← 本文件
├── SUMMARY.md                ← 主题分类索引（40 篇）
├── articles/                 ← 原文归档（Markdown 格式）
│   ├── 128031507.md          ← Kanzi Shader 入门
│   ├── 128615163.md          ← kanzi 粒子插件
│   ├── ... (40 篇)
├── LICENSE                   ← CC BY-SA 4.0（与 CSDN 原文一致）
└── .gitignore
```

## 7 大主题分类

| # | 主题 | 篇数 | 核心方向 |
|---|------|------|----------|
| 1 | **插件与扩展开发** | 16 | 插件工程结构 / 节点 / 离屏渲染 / 视频 / 粒子 |
| 2 | **Studio 窗口插件** | 3 | 绑定美化 / 绑定查找 / HTML 转 Kanzi |
| 3 | **绑定（Binding）** | 3 | 绑定模式 / 调试 / AI 解读 |
| 4 | **3D / 渲染 / Shader** | 7 | Shader / OpenGL / 自定义材质 / 3D 时钟 / FPS 视角 |
| 5 | **多语言 / 性能优化** | 3 | 字体裁剪 / 动态加载 / 卡顿治理 |
| 6 | **MCP / AI 集成** | 2 | Kanzi Studio MCP Server / AI 解读绑定 |
| 7 | **工程工具与脚本** | 6 | DataSource / 图片替换 / 颜色流程 / 工程解析 / 节点裁切 / 跨工程拷贝 |

> 详细目录和每篇摘要见 [`SUMMARY.md`](./SUMMARY.md)

## 时间线

```
2022-11  Kanzi Shader 入门           ← 起点
2023-02  仪表 HMI 插件基础           ← 插件工程模板
2023-09  图片内存优化
2024-03  状态机 / 颜色 / 绑定 集中爆发（5 篇）
2024-04  DataSource / Prefab 加载
2024-12  窗口插件三件套（美化/查找/网页）
2025-06  视频插件 / 模型动态加载
2025-12  FPS 视角 / 多语言优化
2026-04  MCP Server 方案 / 节点转换 / 节点树可视化
2026-05  场景树预览（最新）
```

## 技术栈统计

| 类别 | 技术 |
|------|------|
| 插件开发 | C++ (Kanzi Plugin C++ API), C# (Command Plugin) |
| GUI 库 | ImGui (调试窗口), glad, glfw |
| 视频/媒体 | ffmpeg |
| 数据交换 | Named Pipe (MCP), XML 解析 (.kzproj) |
| AI/MCP | Anthropic MCP, C# JSON-RPC, Claude Code |
| 渲染 | OpenGL ES 2.0/3.0, GLSL Shader, FrameBuffer |
| 工程 | .NET 10, kanzi 3.6.10 / 3.9.8 |

## 学习路径建议

### 🟢 新手（1-2 周）
1. `articles/128912484.md` — **使用 kanzi 开发仪表 HMI 插件**（基础模板）
2. `articles/137707478.md` — **kanzi API 案例**（API 用法速查）
3. `articles/137143194.md` — **kanzi 3d 知识点**（资源汇总）

### 🟡 进阶（2-4 周）
4. `articles/128031507.md` — **Kanzi Shader 入门**（渲染基础）
5. `articles/136738815.md` — **Kanzi 绑定之绑定模式与区别**（核心概念）
6. `articles/137006368.md` — **kanzi 状态机插件**（状态机扩展）

### 🔴 高阶（4 周+）
7. `articles/160398199.md` — **Kanzi Studio MCP Server 方案**（AI 集成）
8. `articles/160254798.md` — **kanzi 绑定之 AI 解读**（AI 增强调试）
9. `articles/137334388.md` / `161015875.md` — **运行时节点状态 / 场景树预览**（调试工具链）

## 转载说明

- **原作者**：chen_227（CSDN 博客：https://blog.csdn.net/chen_227 ）
- **许可证**：本仓库采用 [CC BY-SA 4.0](./LICENSE) 与原作者 CSDN 声明一致
- **目的**：方便检索、版本管理、跨平台阅读（Kanzi 学习资料少，需要归档）
- **若原作者希望删除**，请提交 Issue，我会立即下架对应文章

## 贡献

欢迎补充以下内容：
- Kanzi 4.0 / Kanzi AI 相关教程（原作者提到 2026 北京车展将发布）
- 适配 Kanzi 3.9.10+ 的补丁
- 翻译成英文版

## 致谢

- **chen_227** 三年如一日的实战分享（43 篇原创，444+ 阅读量）
- Kanzi 中国团队（中科创达 Rightware）
- 本仓库由 AI 助手从 CSDN 专栏抓取整理，原文一切权益归原作者

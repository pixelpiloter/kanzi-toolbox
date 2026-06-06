# Kanzi 实战文章分类索引（40 篇）

> 来源：https://blog.csdn.net/chen_227/category_11957782.html
> 整理时间：2026-06-07
> 命名规范：日期 + ID + 标题（按发布顺序排列）

---

## 1. 插件与扩展开发（16 篇）

| 日期 | 文件 | 标题 | 核心点 |
|------|------|------|--------|
| 2023-02-07 | [128912484](./articles/128912484.md) | **使用 kanzi 开发仪表 HMI 插件** | ⭐ 插件工程模板，所有插件文章基础 |
| 2023-01-09 | [128615163](./articles/128615163.md) | kanzi 粒子插件 | KanziPluginParticle + Emitter 系统 |
| 2023-09-25 | [133266560](./articles/133266560.md) | kanzi 动态替换图片不增加内存方案 | BitmapImage 复用 + ResizeFilter |
| 2023-07-22 | [131868251](./articles/131868251.md) | kanzi 状态机动画打断实现方案 | 上一动画立即完成 → 播放下一个 |
| 2024-03-25 | [137006368](./articles/137006368.md) | **kanzi 状态机插件** | ⭐ 拓展原生状态机，3 状态规则引擎 |
| 2024-03-21 | [137334388](./articles/137334388.md) | kanzi 运行时节点状态展示 | ImGui 子窗口 + 离屏渲染 |
| 2024-04-15 | [137787734](./articles/137787734.md) | kanzi 3.9.8 DataSource 动态预览 | XML 变化实时刷新，免 Restart |
| 2024-04-26 | [138281054](./articles/138281054.md) | kanzi 多工程属性绑定问题 | PluginDataSourceGlobal 全局变量 |
| 2024-04-29 | [138304569](./articles/138304569.md) | kanzi Prefab View2D 异步加载入场动画 | 异步线程 + 加载完成回调 |
| 2024-06-05 | [139473541](./articles/139473541.md) | kanzi 插值属性动画打断机制 | PropertyTargetInterpolator Acceleration |
| 2025-01-07 | [144983959](./articles/144983959.md) | kanzi 将画面保存成本地图片 | FBO 离屏渲染 + glReadPixels |
| 2025-06-26 | [148920093](./articles/148920093.md) | kanzi 视频插件 | ffmpeg 集成（Windows/QNX/Linux） |
| 2025-12-25 | [156260166](./articles/156260166.md) | kanzi 实现第一人称视角移动 | 玩家胶囊 + camera 挂载 |
| 2026-01-26 | [157393281](./articles/157393281.md) | kanzi 节点转换插件 | C# PluginCommand 一键换类型 |
| 2026-05-12 | [161015875](./articles/161015875.md) | kanzi 场景树预览 | ImGui 场景树 + 离屏纹理 |
| 2025-12-22 | [156143820](./articles/156143820.md) | kanzi 多语言优化 | 字体裁剪 + 切换无卡顿 |

## 2. Studio 窗口插件（编辑器增强）（3 篇）

| 日期 | 文件 | 标题 | 核心点 |
|------|------|------|--------|
| 2024-12-05 | [144272032](./articles/144272032.md) | kanzi3.6.10 窗口插件-美化绑定内容 | 绑定代码高亮（解决黑色难读） |
| 2024-12-25 | [144720596](./articles/144720596.md) | kanzi3.6.10 窗口插件-查找绑定信息 | Ctrl+F 增强，跨工程查询 |
| 2025-07-23 | [149568661](./articles/149568661.md) | kanzi3.6.10 窗口插件-网页生成界面 | Sketch/HTML → Kanzi 自动转换 |

## 3. 绑定 Binding（3 篇）

| 日期 | 文件 | 标题 | 核心点 |
|------|------|------|--------|
| 2024-03-15 | [136738815](./articles/136738815.md) | **Kanzi 绑定之绑定模式与区别** | ⭐ One-way / Two-way / 表达式 三种模式 |
| 2024-03-19 | [136833019](./articles/136833019.md) | kanzi 快速调试绑定 | InputBindText 解析 + 重新生成绑定 |
| 2026-04-17 | [160254798](./articles/160254798.md) | kanzi 绑定之 AI 解读 | ⭐ Claude 解读复杂绑定 + 检查错误 |

## 4. 3D / 渲染 / Shader（7 篇）

| 日期 | 文件 | 标题 | 核心点 |
|------|------|------|--------|
| 2022-11-25 | [128031507](./articles/128031507.md) | **Kanzi Shader 入门** | ⭐ OpenGL ES 2.0/3.0 + 顶点/片段着色器 |
| 2023-02-20 | [129118208](./articles/129118208.md) | kanzi 中使用 opengl 描绘三角形 | 3D 插件 + RenderPassProperty |
| 2024-03-29 | [137143194](./articles/137143194.md) | kanzi 3d 知识点 | 资料汇总（视频/文档/案例） |
| 2024-04-11 | [137636738](./articles/137636738.md) | kanzi 2D 节点绘制到 3D 模型上 | 反向 render pass 渲染 |
| 2024-10-31 | [143404863](./articles/143404863.md) | 在 kanzi 3.9.8 里使用 API 创建自定义材质 | Render Target Texture + Image |
| 2024-12-30 | [144817439](./articles/144817439.md) | kanzi 做 3d 时钟屏保 | blender 建模 + kanzi 渲染 |
| 2025-06-26 | [148926776](./articles/148926776.md) | kanzi 动态加载模型 | 多模型合并 mesh，batch count 不增 |

## 5. 多语言 / 性能优化（3 篇）

| 日期 | 文件 | 标题 | 核心点 |
|------|------|------|--------|
| 2024-03-30 | [137172137](./articles/137172137.md) | **kanzi 3.9.8 多国语实现** | ⭐ 绑定快速实现动态数字翻译 |
| 2024-07-02 | [140121449](./articles/140121449.md) | kanzi3.6.10 动态加载和替换多语言方案 | 单独 kzb 导出 + Localization Table |
| 2025-07-04 | [149113101](./articles/149113101.md) | kanzi 切换多语言卡顿优化方案 | ttf 字体裁剪（30k → 几百字） |

## 6. MCP / AI 集成（2 篇）⭐ 行业首创

| 日期 | 文件 | 标题 | 核心点 |
|------|------|------|--------|
| 2026-04-17 | [160254798](./articles/160254798.md) | kanzi 绑定之 AI 解读 | Claude 解读复杂绑定逻辑 |
| 2026-04-22 | [160398199](./articles/160398199.md) | **Kanzi Studio MCP Server 方案** | ⭐⭐ C# MCP Server + Named Pipe + 3 个工具 |

> 这是**全球首个公开发布的 Kanzi Studio MCP Server 方案**，让 Claude Code 等 AI 工具直接控制 Kanzi Studio 查询节点树。

## 7. 工程工具与脚本（6 篇）

| 日期 | 文件 | 标题 | 核心点 |
|------|------|------|--------|
| 2023-07-06 | [131572237](./articles/131572237.md) | kanzi 中 DataSource 不好用的解决方案 | 递归查找 Data Context 绑定 |
| 2024-03-19 | [136847194](./articles/136847194.md) | kanzi 颜色工作流程 | sRGB / 线性伽玛色彩空间 |
| 2024-04-13 | [137707478](./articles/137707478.md) | kanzi API 案例 | 按钮事件 / 节点查找 / property 设置 |
| 2024-04-22 | [138076801](./articles/138076801.md) | kanzi 工程辅助解析 | Python 解析 .kzproj 快速上手 |
| 2024-04-24 | [138164162](./articles/138164162.md) | kanzi 节点裁切 | Clip Children 关闭方法 |
| 2024-04-26 | [138219576](./articles/138219576.md) | kanzi 工程间拷贝节点思路 | 自定义命令复制 + 粘贴节点数据 |

---

## 关键 API 速查

按调用频率整理的高频 API（综合自所有文章）：

### 节点
```cpp
// 节点查找
NodeSharedPtr node = getScreen()->lookupNode<Node2D>("/Root/Path/To/Node");

// 离屏渲染（FBO）
kr->bindFramebuffer(m_fbo);
kr->setDefaultFramebuffer(m_fbo);
kr->clear();
node2d->render(renderer, compositionStack, baseTransform);
glReadPixels(0, 0, w, h, GL_RGBA, GL_UNSIGNED_BYTE, data);
```

### 状态机
```cpp
// 切换状态
stateManagerPtr->goToState((Node*)(this), "StateGroup", "StateName", true);

// 插值打断
PropertyTargetInterpolator* pti = ...;
pti->setAcceleration(1000);
node->removeNodeComponent(pti);
node->addNodeComponent(pti);
```

### 绑定
```cpp
// 绑定源路径示例
"@../PropertyName"          // 相对路径
"@/RootPage/PropertyName"   // 绝对路径
"@/DataContext/PropertyName" // DataContext
```

### DataSource
```cpp
// DataSource 预览
shared_ptr<Node> node = dynamic_pointer_cast<Node>(getRoot());
Create_Node2D_Recursively(node);  // 递归注入

// 多工程全局变量
PluginDataSourceGlobal — 通过 datasource 机制实现
```

### 图片
```cpp
BitmapImageUniquePtr outImage;
outImage->resize(width, height, ResizeFilterBilinear);
// ResizeFilterNearestNeighbor / Bilinear / WeightedAverage
```

---

## 实战工程模板

### 模板 1：插件工程（最常用）
参考 [128912484](./articles/128912484.md) — 创建步骤：
1. Kanzi Studio → New → Plugin Project
2. 编译配置 GL_vs2015_Debug（静态库）+ GL_vs2015_Debug_DLL（动态库）
3. HMI 项目链接 .lib 静态库 + .dll 动态库
4. main 函数注册插件

### 模板 2：状态机插件
参考 [137006368](./articles/137006368.md) — 三属性设计：
- `InputIntValueProperty` — 输入值
- `InputStateValueProperty` — 状态规则（数组）
- `IdleStateValueProperty` — 默认状态

### 模板 3：MCP Server
参考 [160398199](./articles/160398199.md) — 三个文件：
- `KanziMcpService.cs` — 封装 Kanzi API
- `KanziPipeServer.cs` — Named Pipe 桥接
- `KanziMcpServer.cs` — JSON-RPC stdio 主循环

### 模板 4：窗口插件
参考 [144272032](./articles/144272032.md) / [144720596](./articles/144720596.md) — 流程：
1. 继承 Kanzi Studio 窗口插件类
2. 遍历本工程 + 跨工程绑定信息
3. 富文本控件动态生成 + 双击跳转

---

## 常见问题 FAQ（提炼自文章）

| 问题 | 解决方案 | 参考文章 |
|------|----------|----------|
| 切换多语言卡顿 | ttf 字体裁剪，剔除未用字符 | 149113101 |
| DataSource preview 需手动 Restart | 自制 PluginDynamicDataSource | 137787734 |
| 状态机无法实现"0→1 和 1→0 双向动画" | 拓展为 3 状态插件 | 137006368 |
| 跨工程属性绑定爆红 | PluginDataSourceGlobal 走 datasource | 138281054 |
| 动画无法打断 | 改 PropertyTargetInterpolator Acceleration | 139473541 |
| 动态加载图片内存增长 | BitmapImage 替换内容（不重建 Texture） | 133266560 |
| 离屏截图无法获取纹理 | 自定义 FBO + glReadPixels | 144983959 |
| 动态生成模型 batch count 暴涨 | 多模型合并到一个 mesh | 148926776 |
| 工程间无法复制节点 | C# 自定义命令 + 剪贴板数据 | 138219576 |
| 绑定复杂看不懂 | Claude AI 解读 | 160254798 |

---

## 引用本文

```bibtex
@misc{kanzi_toolbox_2026,
  author = {chen_227},
  title = {Kanzi Studio 实战工具箱 - 43 篇专栏文章整理},
  year = {2026},
  url = {https://github.com/pixelpiloter/kanzi-toolbox}
}
```

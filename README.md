#  Video Cover Designer (视频封面设计引擎 · 原版工程标准)

这是一个为 Antigravity / Claude Code / Cursor / Agent 生态打造的**科技数码品类、高点击率视频封面生成 Skill**。

---

## 🗺️ 全链路执行流程图

```mermaid
flowchart TD
    A["【第一阶段】多源输入感知<br>• 输入方式 A: 真实人物 / 硬件物件 + 视频脚本文案<br>• 输入方式 B: 纯新闻报道 / 博客评测链接 URL"]
    --> B{"【第二阶段】四大工业引擎自适应"}

    B --> C1["🛠️ 主播实操 / 工作流型<br>85mm标准焦段零畸变 + 记号黄底衬 + 经典手势互动"]
    B --> C2["⚔️ 双雄决战 / 旗舰 PK 型<br>青蓝 vs 品紫强撞色 + 撕裂 VS 标 + 悬浮品牌晶卡"]
    B --> C3["🔨 避坑揭秘 / 硬核拆解型<br>斜角大红印章‘别被骗了！’ + 底部黑黄警戒胶带"]
    B --> C4["📊 数据报道破局流 (无图链接直驱)<br>3D 破顶能量柱 / 悬浮科技星核 / 突发绝密红印"]

    C1 --> D["【第三阶段】确认制省流提案 (节省67%额度)<br>推导 2~3 组方案 + 强制 1:1 专属 ASCII 排版线框图"]
    C2 --> D
    C3 --> D
    C4 --> D

    D --> E["【第四阶段】用户决策与画幅定制<br>选定方案 + 设定 16:9 / 4:3 / 3:4 比例 (严格避让时长码)"]

    E --> F{"【第五阶段】宿主环境能力判定"}
    F -->|具备生图工具| G["【本地高保真出图】<br>仅消耗 1 次额度精准渲染成品图"]
    F -->|纯文本 / 额度耗尽| H["【单一通用提示词导出】<br>ChatGPT 网页版 / Midjourney / 即梦 直拷通用 Prompt"]

    classDef stage fill:#1E293B,stroke:#475569,color:#F8FAFC,stroke-width:1.5px;
    classDef decision fill:#0F766E,stroke:#14B8A6,color:#FFFFFF,stroke-width:2px;
    classDef engine fill:#1E1B4B,stroke:#6366F1,color:#EEF2FF,stroke-width:1.5px;
    classDef output fill:#064E3B,stroke:#10B981,color:#ECFDF5,stroke-width:1.5px;

    class A,D,E stage;
    class B,F decision;
    class C1,C2,C3,C4 engine;
    class G,H output;
```

---

## 🌟 核心特性速览（30 套工程原图逆向提取）

- **零镜头畸变与真实手势体系**：
  - 杜绝鱼眼与大头，严格采用 **85mm 标准单反人像中焦（1:1 真实骨骼比例）**；
  - 完整适配托举展示、双向对决指点、托腮凝视、拒斥 T 姿、笔记本实物互动等 5 大经典手势。
- **重工立体字与色彩体系**：
  - 主标题逆时针 `-3.0° ~ -5.0°` 动感微倾角；
  - 纯黑粗描边 + 纯黑硬实 3D 立体实底投影；
  - 避坑类（纯白 + 明黄 `#FED700` + 警示红 `#ED1C24`）、对决类（极光青蓝 `#00D2FF` vs 霓虹品紫 `#A855F7`）。
- **标志性视觉资产**：
  - 撕裂水彩“VS”对决印章、悬浮品牌全息晶卡、黑黄警示斑马胶带、斜角红方印章。
- **16:9 / 4:3 / 3:4 三比例精准重构**：
  - 横屏左右分栏避让时长码；竖屏标题自动拆为 3 行垂直堆叠，底部贯穿警戒胶带，画面全屏饱满无黑边。
- **确认制省流工作流**：前置输出 2~3 个带线框图的创意方案，待用户选定后精准单次出图，**节省 67% 生图配额**。
- **单一全通用提示词导出**：纯文本 Agent 下自动输出纯自然语言通用 Prompt，直接兼容**网页版 ChatGPT、Gemini、Midjourney、即梦、可灵**。

---

## 📂 安装方法
只需将本目录下的 `SKILL.md` 复制到任何支持 Agent Skills 的目录（如 `~/.gemini/config/skills/` 或 `~/.claude/skills/` 或 `~/.agents/skills/`），即可在任意用户的环境中开箱即用！

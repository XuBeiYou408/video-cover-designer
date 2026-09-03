#  Viral Video Cover Designer (视频封面设计引擎)

这是一个为 Antigravity / Claude Code / Cursor / Agent 生态打造的**科技信息品类、高点击率视频封面生成 Skill**。

---

## 🗺️ 全链路执行流程图

```mermaid
flowchart TD
    %% 阶段 1
    subgraph Stage1 [【阶段一】多源输入感知]
        In1[输入 A: 实拍人像 / 硬件物件 + 视频脚本文案]
        In2[输入 B: 纯新闻报道 / 博客评测链接 URL]
    end

    %% 阶段 2
    subgraph Stage2 [【阶段二】四大引擎自适应路由]
        Router{智能分析内容类型}
        E1[🎮 博主秋芝隐喻流: 1.3x大头 + 剧情换装 + 电光黄字]
        E2[🛠️ 微机硬核实测流: 50期参数锁定 + 毛玻璃 + 拆解印章]
        E3[🎙️ 电影深度社论流: ⚠️ 人像0篡改 + 伦勃朗光 + 金句双引号]
        E4[📊 数据报道破局流: 3D破顶柱状图 / 悬浮星核 / 突发红印]
    end

    %% 阶段 3
    subgraph Stage3 [【阶段三】确认制省流提案 节省67%额度]
        Propose[推导 2~3 组高张力创意方案]
        Wireframe[⚠️ 强制 1:1 附带原子化 ASCII 结构排版线框图]
    end

    %% 阶段 4
    subgraph Stage4 [【阶段四】用户决策与画幅重构]
        UserChoice[用户选定方案 A/B/C 并确认修改意见]
        Ratio[指定平台画幅: 16:9 / 4:3 / 3:4 避让右下角时长码]
    end

    %% 阶段 5
    subgraph Stage5 [【阶段五】双轨环境适配交付]
        Branch{当前 Agent 宿主环境能力}
        NativeGen[【本地生图】仅消耗 1 次额度精准渲染成品图]
        UniversalPrompt[【通用导出】输出全通用自然语言 Prompt<br>可直接复制到网页版 ChatGPT / 即梦等生成]
    end

    %% 流程连接
    In1 & In2 --> Router
    Router -->|消费AI/日常教程| E1
    Router -->|硬件/芯片/拆解| E2
    Router -->|深度访谈/播客对白| E3
    Router -->|无图/纯报道/跑分数据| E4
    
    E1 & E2 & E3 & E4 --> Propose --> Wireframe
    Wireframe --> UserChoice --> Ratio --> Branch
    Branch -->|具备生图工具| NativeGen
    Branch -->|纯文本/网页端模型| UniversalPrompt

    classDef default fill:#1E293B,stroke:#475569,color:#F8FAFC,stroke-width:1.5px;
    classDef highlight fill:#0F766E,stroke:#14B8A6,color:#FFFFFF,stroke-width:2px;
    class Stage2,Stage3,Stage5 highlight;
```

---

## 🌟 核心特性速览

- **四大流量引擎自适应**：
  - **博主秋芝隐喻流（默认）**：1.3x 情绪大头 + 脚本剧情 Cosplay 换装 + 3D 悬浮道具 + 电光黄 `#FED700` 立体字。
  - **微机硬核实测流**：50 期样本客观参数锁定，毛玻璃横幅 + 红蓝 VS 撞色 + 大红“拆！”字印章。
  - **电影深度社论流**：**人物绝对 100% 零篡改（0换装/0修脸）**，伦勃朗光影 + 巨型金色金句双引号 `“ ”` + 身份背书铭牌。
  - **数据报道破局流**：无实拍素材时，将跑分与新闻转化为 3D 破顶能量柱、全息科技星核与突发绝密红印章。
- **URL 链接直驱解析**：支持直接输入报道或评测文章链接，自动静默抓取正文与跑分表格提炼爆点。
- **确认制省流工作流**：前置输出 2~3 个带线框图的创意方案，待用户选定后精准单次出图，**节省 67% 生图配额**。
- **方案线框原子契约**：提几个方案就必须强制绑定输出几个专属 ASCII 结构排版线框图，严禁任何方案省略。
- **全平台多比例自适应**：原生适配 `16:9`（B站横屏）、`4:3`（动态卡片）、`3:4`（小红书竖屏），严格避让右下角时长码。
- **模型解耦与零锁死**：动态继承宿主 Agent 当前环境的模型与配额，绝不硬编码任何具体模型名称。
- **单一全通用提示词导出**：在纯文本 Agent 下自动输出纯自然语言通用 Prompt，直接兼容**网页版 ChatGPT、Gemini、Midjourney、即梦、可灵**。

---

## 📂 安装与分发方法

### 本地直接使用
该 Skill 现已自动安装至当前环境：
`C:\Users\ABC\.gemini\config\skills\viral-video-cover-designer\SKILL.md`
Agent 在接收到封面设计或文案配图需求时会自动唤醒。

### 分发给其他用户使用
只需将本目录下的 `SKILL.md` 复制到任何支持 Agent Skills 的目录（如 `~/.gemini/config/skills/` 或 `~/.claude/skills/` 或 `~/.agents/skills/`），即可在任意用户的环境中开箱即用！

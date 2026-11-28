# 陶瓷瓦 / 纤维绝热研究 — 2026-11-28（第三场 / night session）

> 派生自 `satellite-insulation-research` 的 `assets/2026-11-28-night.md`。
> ⚠️ 本场为**降级场**：proxy 全局归零（`nc` 假阳性，实际 HTTPS 隧道探针 5 目标全 000）、
> NTRS API 全封锁（403/000）、Google Patents + Espacenet + USPTO + PatentsView 全封锁或伪成功外壳、
> Semantic Scholar 429 + browser 路径 reset。**可用渠道仅 OpenAlex / arXiv export / NASA wp-json / SpaceNews / CASC。**

---

## 检索概要

- **渠道**：OpenAlex（串行 12 s 间隔，13/22 组成功）/ arXiv export API（8/20 组）/ arXiv listing（4/4 = 156 ID，直连）
  / NASA wp-json（含 `nasa-blog` 类型）/ SpaceNews RSS 12 条 / CASC 主页
- **候选**：369（OpenAlex 228 + arXiv export 168 + arXiv listing 156，去重）
- **语料**：GitHub 全量 **401 源 / 6,483,487 B**
- **关键词**：`SiC CMC ablation` / `phenolic ablation char recession` / `EBC rare earth silicate` /
  `ceramic matrix composite oxidation coating` / `porous carbon ablator` / `fiber composite thermal protection`

---

## 关键发现

### 1. ⭐⭐⭐⭐⭐ 陶瓷 / 纤维复合 TPS 的最新生产路线（2026-08~10，OpenAlex 语料内）

以下论文**均已在既有语料中**（非新发现），但作为**本领域当前技术基线**记录在此，便于本库后续检索时快速定位：

| 日期 | 标题要点 | 关注点 |
|---|---|---|
| 2026-10-01 | **Development and fabrication of a full-scale oxide CMC thermal protection system** | ⭐⭐⭐⭐⭐ 氧化物 CMC TPS 的**全尺寸**制造 —— 氧化物 CMC 的痛点是抗氧化层与纤维界面，本条是本领域最接近「工程化交付」的公开记录 |
| 2026-10-01 | **Structural Components of non-oxide Ceramic Matrix Composites for Space Applications** | 非氧化物 CMC 结构件（SiC/SiC、C/C）综述基线 |
| 2026-10-01 | **Ultrahigh-temperature ablation behavior of room-temperature-cured cementitious composites** | ⭐⭐⭐⭐ 室温固化水泥基材料的超高温烧蚀 —— **「免高温烧结」路线**，可大幅降工艺成本 |
| 2026-09-18 | Multi-scale characterization and progressive failure analysis of **stitched** aerospace composites | ⭐⭐⭐⭐ **缝线复合**渐进失效 —— 与 MLI 的「绗缝」工艺是同一族问题（v1.240 指出「MLI 的绗缝线必须与毯材同等选型」） |
| 2026-08-24 | A comparison of ablation resistance of **three typical phenolic resin composites** | 酚醛体系横向对比基线 |
| 2026-08-11 | From fragile insulation to self-supporting shield: **Porous SiC/B4C coated carbon** | ⭐⭐⭐⭐⭐ 「**从脆性隔热材料 → 自承力屏蔽**」—— SiC/B4C 涂层碳材料，本领域里把「隔热」与「承力」合一的路线（承 v1.240「1984 壳瓦 TPS：功能分离」的**反向**命题） |
| 2026-08-01 | Polymer Infiltration and Pyrolysis of Modified **C/C and UHTC** | PIP 工艺制备 C/C + 超高温陶瓷 |
| 2026-07-28 | Processing-window-guided fabrication of **ceramic/carbon nanofibrous composite** | 「工艺窗口导向」的纳米纤维复合材料制造 |
| 2026-10-19 | **Polysilazane-impregnated high-entropy LDH-grown cellulose nanofiber aerogels** | ⭐⭐⭐⭐⭐ **聚硅氮烷浸渍 + 高熵 LDH + 纤维素纳米纤维气凝胶** = 气凝胶的耐温强化新路线（硅氮烷交联 + 高熵层状双氢氧化物） |
| 2026-06-12 | **Ti3SiC2 modified carbon fiber/phenolic aerogel** composite: low density, high… | ⭐⭐⭐⭐ Ti3SiC₂（MAX 相）改性 C/酚醛气凝胶 —— **MAX 相作为低密度耐烧蚀填料**是本场读到的新材料族 |
| 2026-01-31 | Preparation of **Phenolic Aerogel / Quartz Fiber** Composites Modified with **POSS** | ⭐⭐⭐⭐ 酚醛气凝胶 + 石英纤维 + POSS 改性 —— **POSS（笼型倍半硅氧烷）**作为耐热改性剂 |
| 2026-09-07 | Nanostructured **Zirconia-Based Aerogels** for High-Temperature Thermal Insulation | 氧化锆基高温气凝胶 |
| 2026-06-29 | A functionally synergistic **sequential-response bilayer coating** strategy | ⭐⭐⭐⭐ 双层涂层「顺序响应」策略 —— 分层响应设计 |

### 2. ⭐⭐⭐⭐⭐ PICA-D 的「带故意缺陷」组合热-力鉴定（NASA, 2026-06-01）

- **来源**：NASA `nasa-blog` id 1223404，《NASA's Dragonfly Flight System Faces Heat》
- **内容**：Dragonfly 热盾 = **碳纤维 + 轻质树脂**（PICA-D，PICA 变体；原 PICA 用于 Curiosity / Perseverance）
  - 设施：**Sandia National Laboratories National Solar Thermal Test Facility**（新墨西哥阿尔伯克基）
  - **太阳塔**：数百面标定镜面聚焦太阳能量至塔上试件 → **~4,500 °F（≈2,500 °C）**
  - 试验项：热辐射耐受 / 快速温度变化 / **大样件同时施加机械 + 热应力**（模拟高速进入压力 + 强热）/ **曲面肩部单元**
  - ⭐⭐⭐⭐⭐ **核心方法论：故意植入缺陷再验证** —— NASA Ames TPS 负责人 Milad Mahzari：
    > *"We tested the heat shield as a complete system, including the primary PICA-D material, **gap fillers**, and potential manufacturing defects… even with the **flaws we intentionally included**, like those that might naturally occur during fabrication and integration."*
  - 测试对象是**完整系统**（主材 + **gap fillers** + 制造缺陷），非孤立材料试片
- **工程价值**：
  - ⭐⭐⭐⭐⭐ **一条可固化到 TPS 验证大纲的原则：「带缺陷鉴定」（qualification with seeded defects）** ——
    在试验设计阶段主动植入制造/装配环节可能产生的典型缺陷，再验证其在真实热-力联合载荷下的存活能力。
    **TPS 的可靠性来自「缺陷容限」的设计与验证，而非「无缺陷材料」的性能上限。**
  - ⭐⭐⭐⭐ **gap fillers 独立列为合格性子项** → 说明 TPS 工程界已把「接缝/边缘过渡区」视为**独立风险部位**，
    而非主体材料的附属细节。
  - ⭐⭐⭐⭐ **「太阳塔 = 数百面标定镜面聚焦」** 与 v1.240「平面红外灯阵 + 液氮冷壁」、
    v1.238 LOTIS「88 英尺温控真空舱 / 1 °F 均匀性」并列为三类地面热环境设施的典型配置；
    共同点：**保真度来自「热源端」+「背景端」双端控制**。

### 3. ⭐⭐⭐⭐ 可复用火箭「薄层被动 TPS」—— 中等热载荷窗口的概念设计（2026-01）

- **来源**：`https://openalex.org/W7222379041`（含德文副标题 Vorkonzeptstudie zu dünnschichtigen Hitzeschutzsystemen…）
- **内容**：
  - 目标：**可复用火箭级**以降低发射成本
  - 核心矛盾：**烧蚀体不可复用**；CMC 在**中等热载荷（< 1000 °C）**下「复杂、昂贵、尺寸过大」
  - 方法：材料特性需求 → **材料性能数据库** → 聚焦**商用可得高温耐热绝缘材料** → 概念系统化评估 →
    **热瞬态有限元仿真**（参数化可扩展模型 + **自适应优化算法调整层厚**）
- **工程价值**：
  - ⭐⭐⭐⭐⭐ **⭐ 本库最值得记的一条「中间热载荷窗口」论断** ——
    **「< 1000 °C 的中等热载荷区间，是烧蚀体与 CMC 之间的夹缝：烧蚀体不可复用，CMC 在此区间复杂/昂贵/过重。」**
    → **这是一个被本领域长期忽略的「设计空隙」**：多数 TPS 文献只讨论「高热载荷烧蚀」或「可复用 CMC」两端，
    中间带（1000 °C 附近**被动**防护）很少被正面建模。
  - ⭐⭐⭐⭐ **「商用可得材料 + 参数化仿真 + 算法优化层厚」** —— 与本领域主流（军用/航天专用材料 + 手工迭代）不同的路线：
    **把 TPS 设计变成「在材料库里做优化」，而非「开发新材料」。**
  - ⭐⭐⭐ **与 v1.238 TUFROC 可复用 TPS 谱系同主线**，但本条给出了**「中等热载荷窗口」这一更具体定位**。

### 4. ⭐⭐⭐ 地面热环境设施的第三种典型配置

| 设施 | 配置 | 来源 |
|---|---|---|
| Sandia National Solar Thermal Test Facility | **数百面标定镜面聚焦 + 太阳塔** → ~4,500 °F | 本场 Dragonfly PICA-D |
| 平面红外灯阵 + 液氮冷壁 | 双端控制 | v1.240 B-2 / CREST |
| LOTIS 温控真空舱 | 88 英尺 / 1 °F 均匀性 / class 10k | v1.238 |

→ ⭐⭐⭐⭐ **一条设施选型结论：太阳/辐射模拟的保真度来自「热源阵列 + 冷背景」的双端控制，而非单一灯具功率或单一炉体尺寸。**

---

## 渠道有效性

| 渠道 | 状态 | 备注 |
|------|------|------|
| **proxy 8001** | ❌ 全局归零 | `nc` 假阳性 succeeded，真实 HTTPS 隧道探针 5 目标全 000；3×20 s 重试均 000 |
| OpenAlex | ✅ | 直连，**串行 12 s 间隔 → 9/9 全通**；8–9 s 间隔大面积 429；3 线程并发 12/15 组 429 |
| arXiv export | ⚠️ | 8/20 组有效；**14 组返回 726–766 B 空 XML**（叠加航天限定语必然空） |
| arXiv listing | ✅ | 直连 4/4 = 156 ID（**必须 `/recent`**；`?show=2000` 404） |
| arXiv 侧真新 | **0** | 156 条全为物理类噪声，连续饱和 |
| **NTRS** | ❌ 全封锁 | 403 / 000 / r.jina 000 → **本场零产出** |
| **专利侧全系** | ❌ | Google Patents 000 / Espacenet 403 / USPTO + PatentsView 伪成功 12,258 B SPA 外壳 |
| Semantic Scholar | ❌ | 429；browser 路径 ERR_CONNECTION_RESET |
| NASA wp-json | ✅ | `posts` 15 篇零 TPS；**`nasa-blog` 类型为 TPS 博客唯一载体** |
| SpaceNews | ✅ | 12 条 |
| CASC | ✅ 零产出 | 200 / 140,612 B，栏目导航为主 |
| ESA RSS | ❌ | 404 → **连续第 7 场，正式停用** |

---

## 质量评估

- 信息完整度：⭐⭐⭐（NTRS + 专利 + S2 全废，**陶瓷/纤维侧的 NASA 报告语料本场完全缺席**）
- 数据可靠性：⭐⭐⭐⭐（差集经 v1.237 双判据 + 人工核验；**发现并剔除 2 条假 never**）
- 工程价值：⭐⭐⭐⭐（PICA-D 带缺陷鉴定 / 薄层被动 TPS 中间窗口 / 设施双端控制三条可固化）
- 可复现性：中（OpenAlex 串行 12 s；专利与 NTRS 依赖 proxy 恢复）
- 本场产出：**1 条真新**（薄层被动 TPS 概念）+ **1 条部分新**（Dragonfly PICA-D 战役）+ **1 组基线整理**（2026 陶瓷/纤维生产路线 10 条）

---

## 改进点

1. ⭐⭐⭐⭐⭐ **修 `scripts/matcher.py` 的 `W\d+`（OpenAlex 记录 ID）主键缺口** —— 当前该形态下的文献永远无法被判「已报道」
2. ⭐⭐⭐⭐ 语料侧补「英文标题/译名」字段（消除中文标题 vs 英文/日文候选的错配）
3. ⭐⭐⭐⭐ NASA 取全文三步走：`search?search=<kw>` → id + subtype → `wp-json/wp/v2/<subtype>/<id>`
4. ⭐⭐⭐⭐ OpenAlex 间隔定为 12 s 且串行；**并发是限流主因**
5. ⭐⭐⭐ 补 Crossref API 作为期刊侧冗余通道
6. ⭐⭐ 专利侧待测：EPO OPS / Lens / CNIPA / WIPO Patentscope

---

## 下一步

1. ⭐⭐⭐⭐ 下一场重点补 **NTRS 陶瓷/纤维报告轴**（本场完全缺席）：`NASA-TM-8xxxx` 编号连续段 + EBC / UHTC 概念轴
2. ⭐⭐⭐⭐ 追 **PICA-D 专门文献** 与 NASA Ames Milad Mahzari 团队的 TPS 负责人口径
3. ⭐⭐⭐ 追 **「中等热载荷（< 1000 °C）可复用被动 TPS」窗口** —— 本场新立词轴
4. ⭐⭐⭐ 深挖 **SiC/B4C 涂层碳（自承力屏蔽）** 与 **MAX 相（Ti3SiC₂）低密度耐烧蚀填料**两条新材料族
5. ⭐⭐ 下一场文件名仍按**精确路径单次 GET** 判定；⚠️ 本场已写 `2026-11-28-night-research.md` → 同日下一场须再加后缀

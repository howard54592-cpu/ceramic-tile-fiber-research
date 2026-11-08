# 卫星绝热材料研究 - 2026-11-08（晚间场）

> 版本 v1.201 ｜ 本场为当日**晚间场**（早间场 = v1.200），文件名 `2026-11-08-evening.md`，不覆盖早间场内容。

## 检索概要

- **检索渠道**：NASA NTRS API（search + `citations/{id}` 双通道）｜arXiv export API（直连优先）｜Crossref API｜OpenAlex API｜Google Patents xhr JSON｜NASA wp-json｜SpaceNews wp-json｜CASC 官网首页
- **关键词**：`thermal protection` / `multilayer insulation` / `aerogel insulation` / `heat shield reentry` / `thermal vacuum test` / `arc jet testing` / `carbon phenolic ablation` / `insulation blanket cryogenic` / `ablator test` / `thermal protection system design spacecraft` / `aerogel blanket liquid hydrogen tank` / `char layer oxidation` / `spacecraft thermal control radiator OSR` / `carbon carbon composite heat shield` / `reentry trajectory TPS` / `spacecraft materials degradation thermal cycle`
- **专利关键词**：`aerogel satellite insulation` / `multilayer insulation spacecraft` / `thermal protection reentry vehicle` / `cryogenic insulation liquid hydrogen tank` / `heat shield composite spacecraft`
- **耗时**：约 42 分钟
- **本场增量**：NTRS 100 条从未报道 → 二次归并后 90 条｜期刊 66 条严格航天复核后保留｜专利 23 条｜arXiv 池 1640 → **1643**

---

## 关键发现

### 1. ⭐⭐⭐⭐⭐ NTRS · Orion OFT-1 热防护系统仪表化（`20110012175`）

*Orion Flight Test-1 Thermal Protection System Instrumentation*（JSC-CN-23591 / JSC-CN-23987，PRESENTATION，2019-07-12）

- Orion CEV 在航天飞机退役后承担 ISS crew transport 与月球返回；随美国载人探索方向调整，项目重心转向**首次轨道飞行试验 OFT-1**。
- OFT-1 关键飞行试验目标之一即**验证再入气动/气动热环境，以及 TPS 在再入暴露下的性能**。
- ⭐⭐⭐⭐⭐ 本场**唯一 rel=14**（航天相关度满分级）的候选 —— 罕见的**载人级 TPS 全系统试验目标定义**一手记录。
- 工程价值：**「TPS 验证目标如何写」本身就是可复用的试验设计模板**；对任何新热盾方案，「再入环境验证」与「TPS 性能验证」必须并行定义。

### 2. ⭐⭐⭐⭐⭐ NTRS · 薄气凝胶作 MLI 间隔片（`20160005382` ≡ `20160005358`）

*Thin Aerogel as a Spacer in Multilayer Insulation*（OTHER，2018-06-05）

- **Aspen Aerogels** 已验证制造**薄型低密度气凝胶**的关键工艺步骤；用该薄片制成 **MLAI（多层气凝胶绝热）系统原型**。
- 核心机理：**MLI 的间隔片（spacer）厚度直接决定辐射换热**（层间距越小辐射越强），而传统间隔片（silk net / dacron）在低温下热导率不理想 → **用超薄气凝胶片同时提供机械支撑与低热导**。
- 报告称其热性能**超过当前航天应用的最先进绝热方案**（"exceeding current state-of-the-art insulation for space applications"），并提供**高真空低温绝热的新突破**与耐久材料特性。
- ⭐⭐⭐⭐⭐ **本场 MLI 技术主线第一篇**：把「MLI 间隔片」从机械件升级为**功能绝热件**。
- ⭐ 与 v1.199 的 **MLI 表观热导率机理模型（`19950070377`）**、**MLI 缝合概念（`20170008804`）**、
  v1.200 的 **MLI 重复性 ±8.4%/±16%（`20180000366`/`20170008743`）** 共同构成 MLI 四拼图：
  **机理 → 工艺退化 → 不确定度 → 间隔片材料**。四者齐备，MLI 才真正工程可用。

### 3. ⭐⭐⭐⭐⭐ NTRS · 碳纳米管增强碳酚醛烧蚀体（`20060024621`）

*Carbon Nanotube-enhanced Carbon-phenolic Ablator Material*（ABSTRACT，2019-07-17，rel=10）

- PICA 是 NASA Ames 90 年代中期为 Discovery 任务开发的 TPS，用于 **Stardust 返回舱热盾**（2006-01-15 至今最高速地球再入）。
- PICA 本体 = **多孔纤维碳绝热体浸渍酚醛树脂**，在 **1000 W/cm²** 热流下仍有效。
- **改进方向：用碳纳米管改善酚醛基体力学性能** —— 双重目的：
  ① **提升再入期 TPS 整体强度**；
  ② **提升微流星体/轨道碎片（MMOD）防护能力**（在轨阶段）。
- ⭐⭐⭐⭐⭐ 关键观察：**MMOD 防护需求正反向驱动烧蚀材料配方** —— 这是「烧蚀」与「防碎片」两条主线在同一材料上的**首次明确交汇**。
- 与 v1.199 记的 **Hubble 太阳翼热盾涂层（`20250004992`）**、v1.200 记的 **sample return 航天器 MMOD 加固（`20240009036`）** 形成三角：
  **MMOD 已从「外挂防护层」下沉为「材料本体性能指标」**。

### 4. ⭐⭐⭐⭐ NTRS · 低密度柔性碳酚醛烧蚀体（`20110015026`）

*Development of Low Density Flexible Carbon Phenolic Ablators*（ARC-E-DAA-TN3808，PRESENTATION，2019-07-12）

- PICA 密度 **0.27 g/cm³**，Stardust 用**单块整体式**热盾。
- **Orion 任务的关键教训**：PICA 在 ISS 返回与月球返回中能力验证通过，但**瓦片式（tiled）配置下的间隙填充（gap filler）问题未解**，
  导致 **Orion 最终选 AVCOAT 而非 PICA 作为主热盾材料**。
- 本工作转向**替代架构**：开发**柔性、更贴合（conformal）**的碳酚醛材料，密度与 PICA 相当。
- ⭐⭐⭐⭐ —— **「材料不行 ≠ 架构不行」**：PICA 的失败是**瓦片化架构**问题，不是烧蚀性能问题。
- 与本场第 5 条（Conformable PICA）互为印证，**构型架构是 TPS 选型的独立变量**。

### 5. ⭐⭐⭐⭐ NTRS · Conformable PICA 气动热环境性能（`20140010140`）

*Performance of Conformable Phenolic Impregnated Carbon Ablator in Aerothermal Environments*（ARC-E-DAA-TN4534，ABSTRACT，2019-08-12）

- **Conformable PICA** = PICA 的「表亲」，NASA Ames 在**基础航空计划（Fundamental Aeronautics Program）**下开发。
- PICA 用**脆性碳基体**，**失效应变极低**；Conformable PICA 改用**柔性碳基体（felt 毡）** → **失效应变显著提高**。
- 研究含**改变添加剂含量以调节化学配方**并做性能测试。
- ⭐⭐⭐⭐ —— 「柔性毡替代脆性碳基体」是 **PICA 力学瓶颈的标准解法**，与 v1.199 的 **PICA-D 莱赛尔纤维国产化**、
  v1.200 的 **PICA-NuSil 综述** 构成 PICA 家族的**三条改进路线**（纤维源国产化 / 树脂改性 / 基体柔性化）。

### 6. ⭐⭐⭐⭐ NTRS · 气凝胶绝热系统用于液氢上面级贮箱的被动冷却（`20220015764`）

*Passive Cooling in Aerogel-Based Insulation Systems for Liquid Hydrogen Upper Stage Launch Vehicle Tanks*（ACCEPTED_MANUSCRIPT，2022-10-25，rel=6）

- **SOFI（Spray-On Foam Insulation）** 是液氢级飞行贮箱**迎风面**的常规方案，在**环境压**下性能优异，
  但在**真空辐射主导**环境下远逊于反射式系统（MLI）。
- 若能用**辐射屏（radiation shield）**型绝热替代或补充迎风面 SOFI → **在轨热负载可大幅降低**，
  剩余推进剂可支持**二次任务**（复用上面级）。
- NASA **Kennedy 低温试验实验室（KSC CTL）** 长期探索此类**气凝胶毯**方案；气凝胶**纳米多孔结构**使其同时是**优异吸附剂**与低温绝热体。
- ⭐⭐⭐⭐ —— **「省下的推进剂 = 二次任务」**：把绝热性能直接换算成**任务收益**，是绝热材料经济价值最清晰的表述。
- 与 v1.200 的 **LB-MLI（`20140016533`）** 同为 KSC 体系，但角度相反：LB-MLI 是**结构承载 + 90 K 主动冷屏**，
  本条是**迎风面辐射屏 + 被动冷却** —— **两条互补的液氢贮箱热控路线**。

### 7. ⭐⭐⭐⭐ NTRS · 气凝胶作 MLI 间隔片的低温应用（`20130011366`）

*Aerogel Blanket Insulation Materials for Cryogenic Applications*（KSC-2009-129，CONFERENCE_PAPER，2019-07-12）

- 时间线：**1997 Cryogenic Engineering Conference** 首次展示气凝胶毯原型 → **2004 全面商业化**（Aspen Aerogels）。
- 在 KSC 低温试验实验室用**绝热试验低温恒温器（cryostat）**表征了多种气凝胶毯组合，给出**详细热导率数据**。
- ⭐⭐⭐⭐ —— **这是气凝胶航天化的「里程碑年表」一手证据**：1997 原型 → 2004 量产，
  比许多「新兴材料」的落地周期短得多；**商业可得性是气凝胶区别于 UHTC/CMC 的核心优势**。
- 与 v1.199 的 **ESA DRACO 软木 P50「readily available on the commercial market」** 互证：
  **TPS 选型中「现货供应」是独立于性能的评分维度**。

### 8. ⭐⭐⭐⭐ NTRS · MLI 缝合概念低温对比试验（`20130012959`）

*Cryogenic Testing of Different Seam Concepts for Multilayer Insulation Systems*（CONFERENCE_PAPER，2019-07-12）

- KSC 低温试验实验室在**圆柱形对比低温恒温器**中测试三类缝合概念：**straight overlap（直搭接）**、
  **fold-over（折返）**、**roll wrapped（卷绕）**。
- 每毯 **40 对层**（反射层 + 间隔层），总厚约 **12.5 mm**，**平均层密度 32 层/cm**；高真空 / 软真空 / 无真空三档，
  液氮维持 **77 K** 冷边界。
- **结论：三类缝合概念热性能接近，其中 fold-over 漏热最低**；且**相邻缝在圆周上错开 120°** 显著减轻缝合导致的性能退化。
- 后续试验：卷绕构型的毯**沿筒侧切开、胶带重新粘接**后再测。
- ⭐⭐⭐⭐ —— **本场 MLI 工艺侧第二篇**，与 v1.199 的 `20170008804`（20/50 层、错缝对接、退化仅 ≈2%）
  **互为印证且结论一致**：**缝合并非 MLI 的主要热漏源**；本条进一步给出**缝相位错开 120°** 的具体工程参数，
  而 v1.199 只说「内层缝相对外层错开」。**两篇合并即 MLI 缝合的完整工艺答案**。

### 9. ⭐⭐⭐⭐ NTRS · 可喷涂气凝胶珠（高剪切流变 + 低热导）（`20130012683`）

*Sprayable Aerogel Bead Compositions With High Shear Flow Resistance and High Thermal Insulation Value*（OTHER，2019-07-11）

- **可喷涂气凝胶绝热**已开发：机械完整性好，**热导率低于在役聚氨酯喷涂泡沫（PU SOFI）**，
  在相当或更低的面密度下实现 → **防止绝热层开裂与脱粘，消除飞行中碎片产生**。
- 珠状（bead form）轻质气凝胶可用于**低温贮箱、管路、空间平台、运载器**的热管理系统。
- ⭐⭐⭐⭐ —— **「消除飞行碎片」是除热性能之外的气凝胶独有能力**（喷涂整体性）；
  与 v1.199 记的 **PICA-D drop-in 认证** 同属「**用成熟工艺解决成熟痛点**」的工程思路。

### 10. ⭐⭐⭐⭐ NTRS · 3MDCP 编织热盾纱线微力学模拟（`20260008239` ≡ `20260006120`）

*Simulations of Yarn Micro-Mechanics of Woven Heat Shield Materials (3MDCP)*（2026-09-02 PRESENTATION / 2026-09-04 ABSTRACT）

- **3MDCP（3-dimensional Mid-Density Carbon Phenolic）** = 混合纤维纱束构成的 3D 编织复合材料。
- 难点：预测**脆性+韧性混合纤维**构成**加捻纱线**的微力学响应与断裂，需同时刻画**逐纤维屈服、纤维断裂、纤维间摩擦与接触**。
- 方法：**扩展键合粒子模型（BPM）** + **DEM**（LAMMPS 实现），在 Guo et al. 增量键公式上引入**分段弹塑性本构律**
  （表示**先屈服后失效**的纤维）。
- **3MDCP 纱线用实测纤维半径分布 + 螺旋加捻几何**建模；单纱拉伸模拟与**供应商实测应力-应变**吻合良好；
  纤维断裂模型显示**断裂自纱线径向中心向外传播**。
- ⭐⭐⭐⭐ —— **本场唯一 2026 年（9 月）NTRS 新报告**，且是 3MDCP 主线的**力学机理层**：
  v1.198 记的 `20260004625`（3MDCP 达 TRL 6/MRL 6+）是**系统成熟度**，本条是**纤维级断裂传播机理**，
  二者互补 → **3MDCP 主线在本库已形成「材料 → 力学 → 成熟度」完整链**。
- ⚠️ **同报告双 ID**（`20260008239` / `20260006120`，PRESENTATION + ABSTRACT）→ 本场二次归并再次生效。

### 11. ⭐⭐⭐⭐ NTRS · 天王星轨道器 Aerocapture TPS 设计改进（`20240016188` ≡ `20240015716`）

*Improvements to Thermal Protection System Design of Aerocapture Systems for Uranus Orbiters*（PRESENTATION，2025-01-10）

- **国家科学院行星科学与天体生物学十年调查**将**冰巨星（天王星/海王星）**列为最高优先级旗舰任务；
  **UOP（Uranus Orbiter and Probe）** 概念经评估为**最高优先级**；发射窗口自 **2031 年**起，巡航期**至少 12 年**，
  超过**一半质量**需用于入轨机动。
- **Aerocapture（气动捕获）** 利用大气气动力调制轨迹以降低速度、瞄准最终轨道状态 → **显著缩短飞行时间**。
- 关键词含 **C-PICA**、**SLA-561V**（天王星大气成分模型）、**Uranus**。
- ⭐⭐⭐⭐ —— **本场唯一「深空冰巨星」TPS 条目**：C-PICA 从近地/火星走向**天王星大气**，
  材料选型需面对**超低密度氢氦大气 + 极低热流 + 长时间辐射平衡**的极端组合。
- 与 v1.200 记的 `20240016188` 同标题 —— ⚠️ **这是 v1.200 早间场已列的条目**，本场再次命中但**摘要内容更深**，
  说明**同一条目在不同场次的摘要深度不同**（search 层摘要 vs details 层全文）。

### 12. ⭐⭐⭐⭐ 期刊 · PICA 等温转化动力学修正炭化层后退（Research Square 2026-02-23）

`10.21203/rs.3.rs-8928318/v1` — *Implementation of isoconversional pyrolysis kinetics in a finite-element model of charring ablation*

- **核心问题**：**恒参 Arrhenius 模型**（PICA 常用）常能匹配表面温度，却**系统性高估炭化层后退（char recession）**。
- 方法：从**多速率 TGA** 提取**等转化（isoconversion）动力学**（Flynn–Wall–Ozawa），
  以**表列活化能 {E(α)} 与指前因子 {A(α)}** 嵌入 **UMATHT** 用户材料子程序；
  在积分点上推进，并与**导热、热解气焓、辐射/对流换热（含吹气效应）、网格运动**耦合。
- **验证结果**：表面温度平台保持实测 **2250–2500 K** 带内，**同时消除 Arrhenius 过冲**。
- ⭐⭐⭐⭐⭐ —— **本场最具方法论价值的一篇**：直接修正了 **PICA 材料响应模型中被广泛使用数十年的系统性偏差**
  （温度对、后退错）。这是**烧蚀建模的标定级改进**，不是增量改进。
- ⭐⭐⭐⭐ **可复现性**：TGA 多速率 + UMATHT + 网格运动的完整链条公开 → **他人可复现/移植**。

### 13. ⭐⭐⭐⭐⭐ 期刊 · Orion Avcoat 渗透率崩塌与烧蚀剥落（2026-05-28）

`10.5281/zenodo.20420927` — *The Ananas Hypothesis: A Scientific Case for Pineapple-Derived Ablative Composite Materials in Spacecraft Thermal Protection Systems*

- **事实链**：Orion 飞船热盾在 **2022-12 Artemis I 无人任务**中出现**异常烧蚀行为** ——
  改进配方 Avcoat 的炭化材料在**上百个离散位置**发生**释放/剥落（liberalizing）**。
- **NASA 认定的根因**：**渗透率崩塌（permeability collapse）** ——
  跳跃再入（skip reentry）时**封闭炭化层下积聚热解气**，产生**局部压力事件与剥落（spallation）**。
- **2026-04 Artemis II 载人任务**采用**相同热盾构型**，通过**更陡的再入轨迹**（代价是**削减乘员中止选项**）降低风险；
  据报道曾遭**前 NASA 宇航员与热盾专家公开反对**。
- ⭐⭐⭐⭐⭐ —— **本场最有工程分量的行业级发现**：
  - **跳跃再入 × 炭化层封闭 = 局部超压剥落**，这是**热盾材料 + 再入轨迹 + 任务构型三方耦合**问题，
    单靠材料改进无法消除 —— **轨迹必须为材料让路**（代价明确写出：削减中止选项）；
  - 与 v1.199 记的 **Avcoat 渗透率教训**、v1.198 记的 **Hubble 涂层空间暴露后失效**、
    v1.196 记的 **PICA-Flex Strain Isolation Pad** 共同构成 **「渗透率/炭层封闭性」问题族**，
    **本库已把它从单点案例升级为独立问题族**；
  - ⚠️ 标注：本条为 **Zenodo 预印本**，含「Ananas Hypothesis（菠萝基烧蚀复合材料）」这一**非主流假设**，
    **可信度需以「根因描述」与「假设部分」分开评估** —— 前者与 v1.196/199 的独立记录一致，后者尚未验证。
  - ⭐⭐⭐⭐ **建议：把「跳跃再入 × 炭化层封闭 × 渗透率崩塌」列为本库 2027 年重点跟踪条目。**

### 14. ⭐⭐⭐⭐ 期刊 · 中间层航天 TPS：柠檬酸交联细菌纤维素气凝胶（2026-08-12）

`10.26434/chemrxiv.15007375/v1` — *Thermal window matching in a citric acid crosslinked bacterial cellulose aerogel for intermediate-layer spacecraft thermal protection*

- **可复用航天器热盾**需要**中间绝热层**，缓冲外层烧蚀/陶瓷面与底层结构之间的瞬态热。
- **关键矛盾（作者自陈）**：
  - **陶瓷纤维毯**：反复热循环下**失去机械完整性**；
  - **二氧化硅气凝胶**：隔热远优，但**太脆**，无法承受常规搬运与拼板（panelization）。
  - 两类材料**都只在单一性能轴上优化**，而非针对**明确的热工作窗口**优化。
- 方案：**三元细菌纤维素（BC）气凝胶**，柠檬酸交联 + **PVA 增强**，面向**热窗口匹配**而非单点最优。
- ⭐⭐⭐⭐ —— **「热工作窗口（thermal operating window）」是本场最有价值的新提法**：
  它把 TPS 材料选型从「比谁导热低」改为「**是否落在工作窗口内**」——
  脆性/柔性是**随温区变化的属性**，而非固定优劣。
- 与本场第 2 条（薄气凝胶作间隔片）**方向相反但目标一致**：
  第 2 条让气凝胶**变薄变柔**以适配 MLI；本条让气凝胶**变韧**以适配中间层。
  → **「气凝胶柔性化」是 2026 年最清晰的材料主线**（与 v1.199 的 PET/PAR 空心气凝胶、v1.200 的回收 PET 纤维气凝胶同族）。

### 15. ⭐⭐⭐⭐ 期刊 · VKI Plasmatron 低密度单体烧蚀体（MonA）研究（2026-10-05）

`10.13023/ablat.2012.28` — *Methodology for Ablation Investigations in the VKI Plasmatron Facility*

- VKI（冯·卡门流体力学研究所）针对**新一代低密度碳/树脂复合烧蚀体**开展研究，
  在 **1.2 MW 感应加热 Plasmatron** 设施中测试**低密度单体复合烧蚀体（MonA）**。
- 方法学创新：**高速相机 + 短曝光（2 μs）** → **原位**测量 **3D 表面后退**与**剥落**，并首次**演示热解烧蚀体的逸气效应**。
- ⭐⭐⭐⭐ —— **2 μs 曝光是本场最高时间分辨率的测量技术**；
  **逸气（outgassing）效应原位可视化**直接对应第 13 条的「渗透率崩塌 / 热解气积聚」根因 ——
  **测量手段与失效机理在同一研究线上闭合**。
- 与 v1.199 的 **DRACO 软木 P50（1/2 缩比等离子体验证，VKI 参与）** 互证：**VKI 是欧洲 TPS 验证的核心机构**。

### 16. ⭐⭐⭐⭐ 期刊 · Stardust 案例：多孔 TPS 内部气体流动对热导率的影响（JSR 2026）

`10.2514/1.a36307` — *Internal Gas Flow Effects on Porous Thermal Protection System Thermal Conductivity: Stardust Case*

- **Calcarb 与 FiberForm** 等多孔碳纤维预制体用作 TPS 增强体。
- **现行材料响应模型**中，烧蚀材料热导率**仅以温度与压力为函数**列表给定。
- **多孔介质均质化理论**指出：表观热导率**还依赖孔隙内的气体流动状态**（即压力梯度/流动假设）。
- ⭐⭐⭐⭐ —— **直指现行烧蚀材料响应模型的结构性简化**：
  「热导率 = f(T, p) 表格」在**存在内部流动**时不成立。
- 与第 12 条（等转化动力学修正 char recession）同属 **2026 年「PICA/碳酚醛材料响应模型双缺陷修正」**，
  两条独立来源 → **这是本库当前最值得追踪的建模子方向**。

### 17. ⭐⭐⭐⭐ 期刊 · 航天 MLI 毯水汽污染影响（AIAA 2025-09-18）

`10.1117/12.3065462` — *Effect of water vapor on MLI blanket performance in cryogenic systems*

- MLI 毯由多层反射层 + 间隔层组成，通过**辐射、固体导热、（高压下）气体导热**组合实现被动热控。
- MLI 性能受**热寄生（thermal parasitics）**限制：**层间导热短路** 与 **污染物降解绝热性能**。
- **水汽在许多航天系统中普遍存在且持续存在** → 污染是**长期服役中的持续性劣化源**，而非制造缺陷。
- ⭐⭐⭐⭐ —— **本库首次出现「MLI 污染物/水汽」主题**；
  此前 MLI 主线聚焦**机械穿透（钉扣、支撑）**（v1.198）与**缝合**（v1.199 / 本场第 8 条），
  本条补上**化学/污染维度** → **MLI 退化机理三维度齐备：机械 / 工艺 / 化学**。
- 关联 v1.199 的 **MLI 重复性 ±8.4% vs ±16%**（制造方差异）——
  **若水汽污染是部分原因，则「重复性按制造商分别取值」的结论需要增加「污染控制水平」这一维度**。

### 18. ⭐⭐⭐⭐ 期刊 · 气凝胶在航天热防护中的压力与湿度效应（AST 2025-07-06）

`10.1016/j.ast.2025.110602` — *Pressure and humidity effects on water adsorption and thermal conductivity of nanoporous aerogels in spacecraft thermal protection*

- 直接研究**纳米多孔气凝胶在航天热防护中**的水吸附与热导率的**压力/湿度**影响。
- ⭐⭐⭐⭐ —— **与第 17 条（MLI 水汽污染）构成同一物理链条**：
  **气凝胶自身吸水 → 热导率上升**，且这是**长期在轨**的持续过程。
- ⭐⭐⭐ **本场最重要的跨条目串联**：**「水汽」在本场同时命中 MLI 与气凝胶两个核心材料**，
  指向一个本库尚未系统跟踪的子主题：**航天绝热材料的湿气/污染管理**。
- ⭐⭐⭐⭐ **建议：新增独立跟踪条目「航天绝热材料的湿气与污染管理」。**

### 19. ⭐⭐⭐⭐ 期刊 · 纤维绝热热导率贝叶斯识别（Acta Materialia 2026）

`10.1016/j.actamat.2026.122613` ≡ arXiv `2601.03935` — *Bayesian identification of fibrous insulation thermal conductivity towards design of spacecraft thermal protection systems*

- ⭐⭐⭐⭐⭐ **跨渠道交叉印证**：同一工作**同时**出现在 **arXiv export API**（本场 `ax_ax2.xml`）
  与 **Crossref / Acta Materialia**（2026）→ **两渠道独立命中同一论文**，是本场方法论层面的最强验证。
- 内容：用**贝叶斯识别**确定纤维绝热体热导率，用于**航天 TPS 设计**。
- ⭐⭐⭐⭐ —— 「**贝叶斯反演替代经验乘数**」是纤维/MLI 绝热建模的方法论升级，
  与 v1.199 的 **MLI 表观热导率机理模型（`19950070377`）** 属同一方法论方向（机理 + 不确定度），
  但用**贝叶斯框架**处理 → **可直接输出热导率的后验分布，天然服务于「按制造商分别取值」的工程需求**。

### 20. ⭐⭐⭐ 专利 · 高超声速前缘多孔芯热管（HRL Laboratories，`US11535360B1`）

- **前缘热管**：(a) 外壳材料制成，**其中至少一条边曲率半径 < 3 mm**；(b) 带**多孔芯（porous wick）**。
- ⭐⭐⭐ —— **「曲率半径 < 3 mm」是可直接用于设计的硬几何约束**；
  **多孔芯热管 = 被动式热沉**，在**超薄前缘**（几毫米尺度）上比辐射冷却更有效。
- ⭐⭐⭐ **与 v1.199 记的 **Hubble 太阳翼支杆「抖动」→ 镀金属化 Teflon 热盾涂层** 形成对照**：
  同一问题（热致形变/抖动）在本库已有**涂层（被动）**与**热管（主动式被动）**两种解法。

### 21. ⭐⭐⭐ 专利 · 高超声速飞行器防热涂层（俄罗斯 `RU2749171C1`）

- 领域：**火箭与航天器设备**；防热涂层，主要用于**高超声速飞行器整流罩**；
  由**多层（2、4、6 层）抗蚀层**构成。
- ⭐⭐⭐ —— **多层抗蚀结构 + 整流罩场景**：与本场第 6 条（液氢级迎风面辐射屏）
  共同说明 **「迎风面/整流罩」是当前绝热技术的活跃应用位**。

### 22. ⭐⭐⭐ 专利 · Aspen Aerogels 聚酰亚胺气凝胶绝热板（`US11046815B2`）

- 绝热板由**聚酰亚胺基气凝胶**制成，方法与制品同族。
- ⭐⭐⭐ —— 与 v1.199 记的 `US12516156B2`（Aspen 聚酰亚胺气凝胶组合物）、
  本场 `US20240343879A1`（Blueshift 聚合物气凝胶力学+热学改进）、
  `US20240150539A1`（Blueshift 高支化非交联气凝胶）共同构成
  **「商业气凝胶公司在通用材料专利上密集布局，航天专用化靠下游集成」**的连续第 5 场观察。

### 23. ⭐⭐ 专利 · 液氢贮箱多层低温绝热系统（中国 4 件，含北京航天试验技术研究所）

- `CN221222355U`（**北京航天试验技术研究所**，2024-06-25）液氢贮存系统：液氢贮箱 + 一级低温介质贮箱 + 二级低温介质贮箱。
- `CN114923114A`（2022-08-19）多层低温液氢贮箱：外罐体 + **多层绝热层** + 冷屏层 + 内罐体 + 绝热材料。
- `CN114458945A`（2022-05-10）大型液氢全容罐（液气冷却壁）。
- `CN114673925B`（2024-01-23）常压液氢贮罐：外罐 + 金属内罐 + **薄膜内罐** + 冷屏层 + 绝热棉 + 泡沫玻璃砖。
- ⭐⭐⭐ —— **中国侧专利在「液氢贮箱系统集成」上活跃**，而非材料本体 ——
  与 v1.199 记的「材料侧活跃、航天系统侧稀疏」**观察修正（连续第 5 场）**：
  **液氢贮箱集成恰是「航天系统侧」的一个活跃子域**，不应一概而论。

### 24. ⭐⭐ 行业 · SpaceNews：DRACO 软木烧蚀 TPS（2026-11-05，已报道，本场复核）

- `Cork Takes the Heat So DRACO's Data Can Survive` — **Amorim Cork Solutions** 向 ESA **DRACO** 任务提供 **P50 软木基热防护材料**。
- 本场为**复核**（v1.199 晚间场已完整报道），确认 wp-json 通道稳定可用。

---

## 渠道有效性

| 渠道 | 状态 | 备注 |
|------|------|------|
| **proxy 8001** | ✅ **全场可用（连续第 6 场）** | 开场 export.arxiv=200、NTRS=200、PAT=200；**中段未重探**（连续 6 场稳定） |
| **NASA NTRS API** | ✅ **本场最高产出** | 16 组 query **15 组有结果**（1 组 190 B 503 壳）；**121 唯一候选 → 100 从未报道 → 二次归并 90**；详情 **40/40 成功**（1 个 190 B 壳串行重试恢复） |
| **Crossref** | ⚠️ 3/4 | c4 返 **429 / 0 B**；88 唯一 → **严格航天复核后 66** |
| **OpenAlex** | ✅ 4/4 | 97 从未报道 → 与 Crossref 合并去重后 66 |
| **Google Patents xhr** | ✅ **首轮 5/5** | 50 篇 → 49 唯一 → 航天过滤 34 → **23 从未报道**；**中段未撞 503**（较 v1.199 更好） |
| **NASA wp-json** | ✅ 200 | 8 篇，无 TPS 直接相关 |
| **SpaceNews wp-json** | ✅ 200 | 30 posts；DRACO 软木条目可提取 excerpt |
| **arXiv export API** | ⚠️ **1/4 有效** | ax2 = 48.6 KB / 20 entry；ax1/ax3/ax4 = 726–768 B **空 XML**（有效但空）；**池 +3** |
| **CASC** | ⚠️ listing ✅（173 KB） | 6 条相关标题，**无 TPS 内容**；详情页未测（连续第 7 场） |
| **r.jina.ai** | ❌ | 连续多场失效 |
| **ESA 官方站** | ⏸ 停用 | 动态走 SpaceNews + 媒体 |
| **Semantic Scholar** | ⏸ 连续 5 场未测 | **建议本场正式标记停用** |

---

## 质量评估

- **信息完整度**：⭐⭐⭐⭐⭐ —— NTRS 全文摘要 40 条 + 期刊摘要 66 条 + 专利摘要 23 条 + arXiv 摘要 20 条，**四大板块均有完整一手摘要**
- **数据可靠性**：⭐⭐⭐⭐ —— 全部来自 API 一手端点；**唯一需降级评估项** = 第 13 条 Zenodo 预印本（根因描述可信，菠萝假设未验证）
- **工程价值**：⭐⭐⭐⭐⭐ —— **本场产出多个可直接进入设计决策的条目**：气凝胶间隔片工艺、MLI 缝相位 120°、3MDCP 断裂传播机理、PICA 等转化动力学、渗透率崩塌根因、MLI 污染维度
- **可复现性**：**高** —— 全部条目附 DOI / 报告号 / 专利号，可直接检索；第 12 条（TGA→UMATHT）链路完整公开

---

## 改进点

1. **⭐⭐⭐ 历史差集语料必须包含 SKILL.md + 全部 version-history 引用文件**
   - 本场初版差集语料仅取 GitHub `assets/*.md`（110 KB）→ 报出 108 条 NTRS 从未报道；
     加入 **SKILL.md 快照 + version-history-mid10.md** 后（合计 **264 KB**）→ 正确值 **100 条**。
   - **误报 3 条**：`20170008740`（v1.198 已报 MLI 小孔洞）、`20150005738`（v1.198 已报先进刚性烧蚀 TPS）、
     `20250000246`（v1.198 已报 Canopy Aerospace TPS）。
   - **规则**：差集语料 = **assets/ 全部 + SKILL.md + 所有 references/version-history-*.md**，
     不得只取 GitHub assets。**建议固化为脚本自动组装。**

2. **⭐⭐⭐ 差集标题匹配需「去全部非字母数字」而非「保留空格」**
   - 历史文本里 DOI 会被 Markdown 拆散、标题会换行；用「保留空格」的规范化会漏配。
   - 本场改用 `re.sub(r"[^a-z0-9]", "", ...)` 后，`20170008740` 等 3 条被正确识别为已报。
   - **副作用**：规范化后匹配更严格（更少误判为已报），**宁可多报一条候选也不漏报**。

3. **⭐⭐ NTRS search 响应已含 `abstract` 字段**
   - v1.182 曾记「search 结果无 abstract，必须对每条再发 `citations/{id}`」；
     **本场实测 search 响应体已直接携带 `abstract`**（121 条中绝大多数非空）。
   - **新策略**：**先看 search 响应里的 abstract 筛选，详情层只对入选条目抓取** →
     本场详情请求从 100+ 降到 **40**，节省约 60% 请求量，且规避了 v1.200 记录的 36 并发 503 壳。
   - **判活规则更新**：详情层并发 ≤6（v1.200 的 ≤8 同样安全，本场用 6 无 503）。

4. **⭐⭐ 跨渠道交叉印证是强信号，应作为独立质量指标**
   - 本场 `2601.03935`（arXiv）≡ `10.1016/j.actamat.2026.122613`（Acta Materialia），
     两渠道独立命中同一论文 → 既是**去重信号**也是**高置信度信号**。
   - **建议**：在日报中显式标注「跨渠道印证」条目，优先级高于单渠道命中。

5. **⭐⭐ arXiv export API 空 XML 率本场 3/4（75%）**
   - ax1 `all:"aerogel insulation"`、ax3 `all:"multilayer insulation spacecraft"`、
     ax4 `all:"ultra-high temperature ceramic ablation"` 均返 **726–768 B 空 XML**。
   - 这与 v1.200 的 a2 空 XML 同型 → **短语引号写法在 export API 上容易命中空集**。
   - **建议**：export API 改为**先宽后窄**（`all:"thermal protection"` 这类高召回词），
     不要用长精确短语；本场唯一有效的 ax2 正是较宽的 `all:"thermal protection system"`。
   - **池 1640 → 1643**（新增 `1603.04844` FiberForm 渗透率 / `1205.5978` Rosseland 方程 / `2208.06642` 传热形式化）

6. **⭐ arXiv 池判活需按「论文自身摘要」而非 feed 主题词**
   - 3 条新池条目均正确（命中均在自身摘要内），但需警惕 feed 级 boilerplate 造成的假命中。
   - **已验证**：3 条逐一读摘要确认切题。

7. **专利解析结构确认**：`total_num_results` 在 `results` 顶层（**不在** `cluster[0]`），
   `cluster` 可能有多组 → 必须 `for c in cluster: extend(c["result"])`。
   v1.199 记录的「`cluster[0].result[]`」需修正为**遍历所有 cluster**。

8. **Crossref 429 需重试**：c4 返 429/0 B，重试可恢复（v1.200 记 c2 返 0 B 同型）。

9. **Semantic Scholar 连续 5 场未测** → **本场正式标记停用**（S2 search 长期 429，DOI 端点已被 OpenAlex 取代）。

---

## 下一步

1. **建立「水汽/污染对航天绝热材料的影响」独立跟踪子主题**
   —— 本场第 17、18 条同时命中 MLI 与气凝胶；检索式建议：
   `water vapor contamination MLI`、`aerogel moisture adsorption spacecraft`、`contamination thermal control degradation`

2. **建立「PICA/碳酚醛材料响应模型缺陷修正」跟踪线**
   —— 第 12 条（等转化动力学）+ 第 16 条（内部气体流动对热导率）+ 第 13 条（渗透率崩塌）
   三条独立来源指向同一子方向；检索式建议：`isoconversional pyrolysis ablation`、`charring ablation model validation PICA`、`permeability collapse char spallation`

3. **NTRS 下轮 query 建议（换角度法，v1.200 §5 结论继续适用）**：
   `permeability spallation char layer reentry` / `aerogel spacer MLI layer density` /
   `water vapor contamination cryogenic blanket` / `3MDCP fiber yarn mechanics` /
   `gaseous flow porous conductivity ablation model`

4. **补充检索「气凝胶柔性化」主线**（本场第 2、9、14 条集中出现）：
   `flexible aerogel panelization spacecraft` / `aerogel intermediate layer thermal window`

5. **arXiv 降频决定复核** —— v1.200 已定为每 3–4 日 1 次；本场为间隔 1 天的晚间场仍执行了
   （因任务指令要求 arXiv 检索），**产出 3 条池外新 ID（均切题）** →
   **建议维持降频，但保留「池深挖 + 补摘要」而非「追新文」的定位**。

6. **Semantic Scholar 正式停用**，从渠道速查表移除；S2 的位置由 **OpenAlex（4/4）** 承担。

7. **CASC 详情页连续第 7 场未测** —— 本场仅 listing；建议下次**明确测一次**或正式停用，
   避免长期占据预算。

8. **GitHub 推送**：本场使用 `2026-11-08-evening.md` 场次后缀，**不覆盖**任何已有文件
   （早间场 `2026-11-08.md` 本场未创建，晚间场独立命名）。

---

*本记录由 satellite-insulation-research skill v1.201 自动生成。*
*渠道基线专档：[references/channel-baseline-v1.201.md](references/channel-baseline-v1.201.md)*

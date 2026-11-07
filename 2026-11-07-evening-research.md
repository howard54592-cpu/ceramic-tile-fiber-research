# 卫星绝热材料研究 - 2026-11-07（晚间场）

## 检索概要
- **场次**：v1.199 · 2026-11-07 晚间场（早间场 v1.198 已于 `2026-11-07.md`，本场不覆盖）
- **检索渠道**：NASA NTRS API（10 组 query）、Google Patents xhr（5 组）、Crossref（5 组）+ OpenAlex（4 DOI）、
  arXiv export API（3 组）、NASA wp-json、SpaceNews（listing + 详情页）、CASC listing
- **关键词**：`thermal protection system 2026` / `thermal control spacecraft 2026` / `aerogel insulation 2025` /
  `multilayer insulation 2025` / `reentry heat shield 2026` / `insulation blanket cryogenic` /
  `spacecraft radiator heat rejection 2026` / `heat shield material 2026` / `thermal protection composite 2026` /
  `spacecraft insulation 2026`；`aerogel satellite` / `thermal insulation spacecraft` / `multilayer insulation spacecraft` /
  `reusable heat shield tile` / `cryogenic tank insulation spacecraft`
- **耗时**：约 22 分钟
- **网络模式**：proxy 8001 全程可用（连续第 4 场稳定）；7897 仍 refused

## 关键发现

### 1. ⭐⭐⭐⭐⭐ NTRS · PICA-D（莱赛尔纤维基酚醛浸渍碳）国产化替代认证 —— 完整首次报道
- **来源**：NASA NTRS `20220006119`（2022-06-24，CONFERENCE_PAPER，*Qualification of Domestic Lyocell Based Phenolic Impregnated Carbon Ablator (PICA-D) for NASA Missions*）
- **内容**：
  - PICA 是 90 年代末以来 NASA 多任务的行星进入热盾（Stardust、OSIRIS-REx、MSL、Mars 2020），
    **低密度 + 高效烧蚀**，覆盖 Discovery 级到旗舰级。
  - **核心矛盾**：PICA 预制体用的**黏胶（rayon）纤维原料多次出现供应链问题**；
    **每次更换纤维源都需重新认证 PICA** —— 过去 25 年已发生**至少两次**，现在是**第三次**。
  - 本次以**国产莱赛尔（Lyocell）纤维**替代 → **PICA-D**。
  - **PICA 已被基线化**为三个 2026–2028 年发射任务的 TPS：**Dragonfly**、**MSR 样品回收着陆器**、
    **MSR 地球返回舱（Earth Entry System）背罩**。
  - 试验规模：**22 个 PICA-D 坯料**经批次验收试验（LOT），含**热学、力学、代表性环境弧风洞**试验。
  - 结论：**PICA-D 性能与 heritage PICA「非常可比」**，是「**可持续、几乎 drop-in 的替代方案**」。
- **工程价值**：⭐⭐⭐⭐⭐ ——
  （1）这是 v1.198 记的「heritage 材料萎缩 / 供应链风险」的**正面解法案例**，说明该风险在管理上是可解的；
  （2）它与 v1.197 记的外行星 3D 编织供应链风险**构成互证**：烧蚀主线与编织主线**同时**存在原料单一来源风险；
  （3）「至少两次、现在第三次」这一频次统计本身即是**风险量级的一手证据**；
  （4）**drop-in 认证路径**（22 坯料 + 弧风洞）可作为其他材料替换认证的模板。
- **首次报道**：✅ 是（此前日报从未出现 `20220006119`）

### 2. ⭐⭐⭐⭐⭐ NTRS · MLI 缝合概念（Seam）试验 —— 首次报道
- **来源**：NASA NTRS `20170008804`（2019-07-12，GRC-E-DAA-TN44512，PRESENTATION，*Testing Seam Concepts for Advanced Multilayer Insulation*）
- **内容**：
  - MLI 是低温推进剂贮箱的**state-of-the-art 绝热**：多层镀金属膜 + 低导热间隔片。
  - GRC 系统研究了**多种缝合形式引入的热负载**。已测试 **20 层与 50 层**毯。
  - 基线构造：**逐层搭接并缝合（tapped together）**。
  - 对比方案三类：**① 整毯自叠（overlap on itself）② 对接缝（butt joint）③ 错缝对接（staggered butt joint，内层缝相对外层错开）**。
  - **实测热负载**：50 层基线 **0.46 W**，缝合毯退化为 **≈0.47 W**；20 层基线 **0.57 W**。
  - 诚实的测量不确定度声明：**加热器引线与仪表线的热负载需修正**，标定试验正在重做。
- **工程价值**：⭐⭐⭐⭐⭐ ——
  （1）**数值极小但意义大**：50 层毯的缝合退化仅 ≈ **2%**（0.46→0.47 W），
  说明**只要工艺得当，缝合不是 MLI 的主要热漏源** —— 这与 v1.198 记的「钉扣小孔洞」是**显著量级**形成对照
  （钉扣贡献固体导热 + 辐射孔洞，是显式项；缝合是隐性项且可被工艺消解）；
  （2）**「错缝对接」是纯几何手段**（内层缝错开外层缝）→ **零额外质量、零额外零件**的对缝方案，
  对**低轨/高发射质量比**场景价值极高；
  （3）**测量方法论诚实**：作者主动披露引线/仪表热负载修正，说明该领域热测的**系统误差量级接近待测量本身** ——
  与 v1.198 记的「钉扣分析需结合 Fourier 定律」的建模需求互为补充；
  （4）该报告的姊妹篇 `20170008743`（MLI 重复性）见下条，**两篇同批次同单位，构成 2019 年 GRC 低温 MLI 一组完整一手数据**。
- **首次报道**：✅ 是

### 3. ⭐⭐⭐⭐ NTRS · MLI 表观热导率数学模型 —— 首次报道
- **来源**：NASA NTRS `19950070377`（报告号 **LEW-15594**，*Apparent Thermal Conductivity Of Multilayer Insulation*）
- **内容**：建立 MLI 相邻层之间**表观/有效热导率的数学模型**，
  用于分析各传热机理对毯内总热流的贡献，并权衡**层数、层间隙厚度、间隔片类型、重量、总厚度**之间的工程取舍。
- **工程价值**：⭐⭐⭐⭐ ——
  （1）这是**少数把 MLI 从「经验乘数」推向「机理模型」**的一手工作；
  （2）**层数 vs 间隙 vs 间隔片 vs 重量**四维权衡，正是 MLI 布置设计中真正要解的题；
  （3）与本场第 4 条（重复性 ±8.4%）、第 2 条（缝合退化 2%）**构成同一技术链条的三块拼图**：
  **模型（预测）→ 重复性（不确定度）→ 缝合（工艺退化项）**。
  ⭐ 这三块拼合是**本场 MLI 板块的核心贡献**：MLI 的工程可用性，取决于「机理可建模 + 重复性可量化 + 工艺退化可预测」三者同时成立。
- **首次报道**：✅ 是

### 4. ⭐⭐⭐⭐⭐ NTRS · MLI 重复性的**完整版**（含第二批 10 件数据）—— 补齐 v1.198 早间场缺口
- **来源**：NASA NTRS `20170008743`（GRC-E-DAA-TN43917，*Repeatability of Cryogenic Multilayer Insulation*）
- **⚠️ 重要方法论发现**：**`20170008743` 与 v1.198 早间场报道的 `20180000366` 是同一份报告的两个 NTRS 记录**
  （标题、作者单位、试验方案、±8.4% 首批数据完全一致）。
  → **NTRS 存在同报告双 ID 的情况，「从未报道」差集必须做去重，否则会把已报道内容重复计入增量。**
  **本场首次拿到该报告的完整后半段数据**（早间场摘要被截断，未覆盖以下内容）：
  - **首批**（FSU，5 件 GRC 试片 × 25 层）：
    **毯间重复性 ±8.4%**，**同一毯重复安装 ±8.0%**。
  - **第二批**（**Yetispace** 制造 10 件试片，FSU 测试，前 4 次）：
    **重复性 ±16%** —— 显著劣于首批。
  - **统计显著性**：经详细统计分析，数据**具统计显著性**。
- **工程价值**：⭐⭐⭐⭐⭐ ——
  （1）**±8.4% vs ±16% 的对比是本场最重要的新数据**：不同制造商（GRC 供片 vs Yetispace 制造）
    的重复性相差近 **2 倍** → **MLI 重复性不只取决于设计，更取决于制造方**，这对低温贮箱的供应商选择有直接指导意义；
  （2）**修正了 v1.198 早间场结论的适用范围**：早间场记「±8.4% 可直接用于热漏预算」，
    **实际应按制造商分别取值**（±8~16%）→ 早间场结论**偏乐观**，本条予以补正；
  （3）「range 随样本数增大退化为标准差」的统计学论证，与 v1.198 早间场记录一致。
- **首次报道**：⚠️ 部分 —— 早间场已报首批数据；**第二批 ±16% 为本场首次**。

### 5. ⭐⭐⭐⭐ NTRS · VIPER 月球车系统级热真空试验（TVAC）—— 首次报道
- **来源**：NASA NTRS `20250003600`（2025-07-31，POSTER，*Volatiles Investigating Polar Exploration Rover (VIPER) System Integrated Thermal Vacuum Test Planning and Preparation*）
- **内容**：
  - VIPER 将赴**月球南极**钻探挥发物；任务中经历**极端温区**：日间行进时高温，钻探**永久阴影区（PSR）**或**休眠（hibernation）**时低温。
  - 热管理系统构成：**环路热管（loop heat pipe）+ 恒导热热管（CCHP）+ 散热器 + MLI + 热控阀**。
  - 系统级 TVAC 在 **JSC A 舱**执行：走**冷热循环、冷/热热平衡、模拟休眠**；
    **热端用辐射围模拟**、冷端用真空舱模拟 PSR。
  - 试验数据用于**热模型相关性（correlation）与功能验证**。
- **工程价值**：⭐⭐⭐⭐ ——
  （1）**MLI 在此是常规基础件，而非研究项** —— 这是本场唯一「MLI 明确出现在工程系统条目中」的例子（与 v1.198 早间场一致）；
  （2）**「休眠 + 永久阴影」是行星着陆器 TMS 的最恶劣工况组合**，
    对**深空低温载荷**设计有直接参考价值（呼应 v1.198 早间场的「低温链」范式）；
  （3）**JSC A 舱 + 辐射围模拟热端**的试验配置可复用。
- **首次报道**：✅ 是

### 6. ⭐⭐⭐⭐ NTRS · Hubble 太阳翼热盾涂层 —— 35 年空间环境验证案例
- **来源**：NASA NTRS `20250004992`（2025-05-23，PRESENTATION，*NASA Glenn Research Center's Contributions to the Hubble Space Telescope*）
- **内容**：
  - Hubble 1990 年部署后即因**进出阳光的剧烈温度循环**导致太阳翼金属支杆**热胀冷缩而「抖动」**，破坏指向精度。
  - 1993 年 12 月 SA-II 维修任务更换太阳翼，其上采用**镀金属化 Teflon（metallized Teflon）热盾**覆盖支杆。
  - **Glenn 的模拟空间环境测试揭示：原计划的涂层在模拟空间暴露后失效**；
    Glenn 与 **Goddard** 联合重新推荐热盾设计 → 装后**成功消除热致抖动**。
  - 关键词含 **Thermal Shields**、**Multilayer Insulation**、Space Radiation、Degradation。
- **工程价值**：⭐⭐⭐⭐ ——
  （1）**「涂层在模拟空间暴露后失效」是罕见的负面结果一手记录** —— 大多数材料验证报告只报成功，
    **失败案例才是理解失效机理的关键**（对应本 skill 词表里的 `coating degradation` / `atomic oxygen degradation` 簇）；
  （2）**多层 MLI 式镀金属膜结构在 35 年后仍在服役** → 是本主题**少有的长期在轨验证案例**；
  （3）与 v1.196 早间场记的 Avcoat 渗透率教训共同指向：**TPS 涂层必须做「空间暴露后」的验证，而非仅做地面热物性测试**。
- **首次报道**：✅ 是

### 7. ⭐⭐⭐ NTRS · Saturn II 助推器基础 TPS 优化（历史档案）
- **来源**：NASA NTRS `19670045000` / `19670064186`（2019-06-14，CONFERENCE_PAPER / REPRINT，
  *Optimization of base thermal protection system for advanced Saturn II boosters employing strap-on solid propellant motors*）
- **内容**：1960 年代 Saturn II 助推器的**基础 TPS 优化**。关键词：THERMAL RADIATION、CERAMIC HONEYCOMB、
  THERMAL PROTECTION、HEAT TRANSFER、SATURN LAUNCH VEHICLE。
- **工程价值**：⭐⭐⭐ ——
  **CERAMIC HONEYCOMB（陶瓷蜂窝）是今天航天飞机 TPS 的直系祖先**。
  本条为**航天 TPS 谱系的最早期档案件**（NTRS 元数据日期为 2019 是数字化归档日期，实际内容为 1960 年代）。
  价值在于**技术谱系完整性**：现代碳纤维/陶瓷瓦 TPS 的「蜂窝夹层 + 辐射平衡」思路可上溯至此。
- **首次报道**：✅ 是（两条记录为同文异型：CONFERENCE_PAPER 与 REPRINT）

### 8. ⭐⭐⭐⭐ 期刊 · JMST 2026-10-22《Flexible hierarchically structured phase-change composite films integrating superior thermal conductivity and ...》
- **来源**：JMST，DOI `10.1016/j.jmst.2026.10.027`（publication_date 2026-10-22；OpenAlex 无摘要）
- **内容**（依据 OpenAlex 关键词）：**柔性分级结构相变复合薄膜**，同时整合**高热导率**与**优异电绝缘性**。
  关键词：phase change materials、composite films、hierarchy、thermal conductivity、electrical insulation、
  **boron nitride（BN）**、carbon nanotube films、**latent heat storage**、electronics cooling、heat dissipation、
  mechanical robustness、**CPU thermal management**。
- **工程价值**：⭐⭐⭐⭐ ——
  （1）**BN 填料 + CNT 膜 + 分级结构** = 用**高导热填料**解决 PCM 传统「导热率极低 → 充放热慢」的经典瓶颈，
    这是 PCM 相变储热路线近年最重要的技术方向；
  （2）**「高导热 + 电绝缘」双高**是电子散热对导热垫的核心要求（BN 相对 AlN/SiC 的绝缘优势）→ **直接面向航天电子设备散热**；
  （3）本 skill 的相变材料簇（`phase change material` / `latent heat`）在**航天电子热控**方向的应用首次进入本库视野 ——
    与 v1.198 早间场记的 NTRS `20260003053`「PCM 热容原型（Orion 流量/温区）」形成**独立双来源印证**；
  （4）**应用面标注为 CPU/电子散热，非航天** → 需进一步判断航天适用性，但**材料机制本身可迁移**。
- **首次报道**：✅ 是（Crossref 命中 + OpenAlex 补关键词）

### 9. ⭐⭐⭐⭐ 期刊 · Advanced Nanocomposites 2026-07-13《Polyarylate nanofiber-enabled binder-free micro/nano dual-scale hollow nanocomposite aerogels from recycled PET》
- **来源**：DOI `10.1016/j.adna.2026.07.003`（OpenAlex 有完整摘要）
- **内容**：**回收 PET 瓶片 → 同轴熔融中空纺丝 → 空心纤维**，
  再与自制**热致液晶聚芳酸酯（PAR）纳米纤维**经溶液共混、冻干、热压结合，
  形成**无粘结剂（binder-free）PET/PAR 微纳双尺度空心复合气凝胶**。
  - 机理：PAR 的二次热塑性 + PAR/PET 间 π–π 相互作用 → 分级多孔网络 + 强界面结合 + 高效应力传递。
  - **协同调控传热与声传播**：① 增大骨架曲折度 ② **诱导 Knudsen 效应** ③ 多重声散射 + 空腔共振。
  - **最优配比**：PET 15 wt% 时**热导率低至 0.035 W/(m·K)**。
  - 其他关键词：sound absorption、compressive stability、hierarchical porous network。
- **工程价值**：⭐⭐⭐⭐ ——
  （1）**Knudsen 效应被明确列为导热抑制机理** —— 这是本主题**气凝胶类**工作的标准机理，但在
    「**纤维骨架 + 纳米纤维 + 回收原料**」新形态下再次被验证 → **「纤维骨架 + 气凝胶」范式**在本库中
    第三次出现（v1.198 早间场 PPTA/SiO₂ 仿羽毛气凝胶是前两例之一）；
  （2）**0.035 W/(m·K) 已达纤维气凝胶/纳米纤维复合物的第一梯队**，且原料是**回收 PET**（成本与可持续性双优）；
  （3）**声学 + 热学协同** —— 同一材料兼顾隔热与吸声，
    对**航天器舱内噪声与热环境双重约束**的场合（小型卫星/返回舱）是额外价值点；
  （4）**无粘结剂** → 避免粘结剂带来的导热增量与老化问题，是气凝胶工程化的长期正确方向。
- **首次报道**：✅ 是

### 10. ⭐⭐⭐ NTRS · 其他首次报道条目（低优先级但归档）
- `19920024084`（*Cryogenic storage technology readiness for First Lunar Outpost*）——
  含**厚 MLI（4 英寸）1/4 缩比试验箱**、**CEVAT 振动/加速度/温度组合环境试验**、
  **固定泡沫绝热**、零-g 排放系统。⭐⭐⭐（MLI + 泡沫双路线对比，月球前哨冷储）
- `20260010526`（*Surface Habitat Power Demand and Fission Surface Power Mass and Transportation Logistics*，2026-11-06）——
  **本场最新报告**（距今 1 天），月面栖居地功率需求与裂变电源物流。⭐⭐（隔热需求侧推算）
- `20250003971` / `20250003742`（**月尘**在 HLS 乘员舱内的命运 / 月尘表面定量的新型高通量光谱技术）——
  ⭐⭐⭐（**月尘对热控/光学表面的污染**是 TPS 延伸课题，HLS 相关）
- `19670045000`/`19670064186` 同上第 7 条
- `19710017529`（*Thickness measuring and injection device Patent*）、`19790015830`（*Spacecraft Charging Technology, 1978*）——
  ⭐（历史档案，无实质技术内容）

### 11. ⭐⭐⭐⭐ 行业动态 · ESA DRACO 任务选用软木基烧蚀 TPS「Amorim P50」
- **来源**：SpaceNews，2026-11-05，*Cork Takes the Heat So DRACO's Data Can Survive*（**详情页全文已恢复**，262 KB）
- **内容**：
  - **DRACO**（Destructive Reentry Assessment Container Object，ESA 任务，**计划 2027 年发射**）
    将**故意再入**并解体，用于采集卫星再入解体的一手数据，
    服务于 **ESA「Design for Demise」**（让航天器再入时解体更彻底）与 **Zero Debris** 路线。
  - 结构：**40 cm 生存舱（survival capsule）** —— 外面解体，**舱内必须存活足够久**以保存并传输关键科学数据。
  - 生存舱热盾采用 **Amorim P50**（**软木基烧蚀热防护材料**，商业市场现货）。
  - **von Kármán 流体力学研究所（VKI）**负责生存舱的**气动热力学、热防护设计与验证**，
    选中 P50 建立在 **Amorim 与 VKI 约 15 年的气动热力学/TPS 合作**之上。
  - **试验**：**1/2 缩比生存舱在 VKI 设施的等离子体流中暴露**，复现再入气动热环境，
    在进入全尺寸阶段前评估热盾与整体 TPS 设计。
  - **VKI 研究专家 Dr. Bernd Helber 评价**：「P50 是高度绝热、坚固、可预测的烧蚀材料，且** readily available on the commercial market**」。
  - **前身任务**：P50 此前已用于 **QARMAN**（VKI 的 QubeSat 再入气动研究）。
- **工程价值**：⭐⭐⭐⭐ ——
  （1）⭐ **「商业现货 + 15 年合作 + 1/2 缩比等离子体验证」是 TPS 选型的完整工程闭环范式**，
    与 NASA 体系「自研 + 弧风洞筛选」的路径形成鲜明对照 → **两条 TPS 供应体系并行的证据**；
  （2）**软木基烧蚀材料**（cork-based ablative）是本库**全新材料族** ——
    与 phenolic/carbon（碳酚醛）、UHTC、CMC 并列，是**生物基/可持续 TPS** 路线的代表；
  （3）**「商业可得性」被 VKI 研究专家直接作为选型理由说出来**，
    与 v1.197 早间场记的「heritage 材料萎缩 / 供应链风险」形成**直接对照**：
    **对中小型任务，可靠的「现货供应」可能比性能极值更重要**；
  （4）**Design for Demise / Zero Debris** → **再入设计正在成为 TPS 的独立需求维度**（不只是防热，还要可控解体）；
  （5）DRACO 2027 发射 → **近地 TPS 的下一个在轨验证机会**。
- **首次报道**：✅ 是（v1.198 早间场记「SpaceNews 20 条头条无 TPS 相关」，本场为**首条** TPS 直接相关）

### 12. ⭐⭐ 专利 · 新增 2026 年公开 2 篇
- `US12516156B2`（2026-01-06，**Aspen Aerogels**）*Aerogel compositions and manufacturing thereof* ——
  **聚酰亚胺基气凝胶**材料组合物与制备方法，针对物理/化学性能优化。⭐⭐⭐
  （**商业气凝胶龙头 Aspen Aerogels 的专利族持续活跃** → 产业侧投入未减）
- `US12516172B2`（2026-01-06，**Blueshift Materials**）*Macroporous-structured polymer aerogels* ——
  含宏孔的聚合物气凝胶基体。⭐⭐⭐（**从「纳米孔」转向「宏孔」以抗压** —— 气凝胶力学改进的典型路线）
- `KR20250126813A`（2025-08-25）*Cryogenic pumping resistant LH2 storage vessel* ——
  **多层绝热 + 非真空绝热**的抗抽吸液氢贮箱。⭐⭐⭐（韩系专利，LH2 地面储罐思路下沉的旁证）
- `CN109968757B`（2020-07-07，国防科大）低密度抗烧蚀隔热复合材料 —— **三明治结构：短切纤维增强 + 酚醛基体 + 空心微球**。⭐⭐⭐
- 其余首次报道专利多为**非航天**（Cynosure 医美 RF、半导体、CATL 电池隔热垫、船舶 LNG 罐）→ **本库已忽略**。
- **观察修正（连续第 4 场）**：**航天绝热专利主线仍是「烧蚀/TPS 稀疏、MLI-低温-可复用隔热活跃」**；
  但本场新增 **2 篇 2026-01 公开的气凝胶材料专利（Aspen / Blueshift）**，
  说明**「材料侧专利」活跃而「航天系统侧专利」稀疏** —— 商业气凝胶公司在通用材料专利上布局，
  航天专用化需靠**下游集成**（如 v1.198 早间场记的 `US20260110403A1` 低温可复用真空夹套绝热）。

## 渠道有效性

| 渠道 | 状态 | 备注 |
|------|------|------|
| **proxy 8001** | ✅ **全场可用（连续第 4 场）** | 开场 200；中段重探 NTRS 200 / Crossref 200 / Patents 503（配额，正常） |
| 7897 | ❌ refused | 连续第 37 次 |
| **NASA NTRS API** | ✅ **本场最高产出** | 10 组 query 9 组有结果；41 唯一候选 → **14 条从未报道** → 7 条高价值；9 次详情抓取 **9/9 成功**（0 B 重试机制未触发） |
| **NASA wp-json** | ✅ 200 | 18 篇，**无 TPS 直接相关** |
| **SpaceNews** | ✅ **listing + 详情页全文均恢复** | **DRACO 软木 TPS 为本场行业板块唯一高价值条目** |
| **Google Patents xhr** | ✅ 首轮 5/5 | 50 篇；中段 503 配额（首轮集中发完策略有效） |
| **Crossref** | ⚠️ 4/5 | 1 组 0 B；**噪声极高**（电力系统绝缘占多数）→ 需强正则过滤 |
| **OpenAlex** | ✅ 4/4 DOI | `abstract_inverted_index` 补摘要；**无摘要时关键词仍足以支撑判断** |
| **arXiv export API** | ✅ **3/3 组全通（56 entry）** | ⚠️ **切题真新连续第 5 场为 0**（12 个"新"ID 经语义复核**全为误报**：超导/变压器/山火凝胶/红外隐身衣等） |
| **CASC** | ⚠️ listing ✅ / 详情页 ❌ | 连续第 5 场详情页失败；本场未提级 |
| **Semantic Scholar** | ⏸ 未测 | v1.196/v1.197 均 429；本场 arXiv 有产出，未占用时间 |
| **r.jina.ai** | ❌ | 连续多场失效 |
| **ESA 官方站** | ⏸ 停用 | 连续 13 场 404；但 **DRACO 经 SpaceNews 间接获取**（见第 11 条） |
| **Europe PMC** | ❌ 不适用 | 不收录 JMST / JECS |

## 质量评估
- **信息完整度**：⭐⭐⭐⭐ ——
  NTRS 摘要完整（含第二批 ±16% 数据、缝合热负载数值、Batch/LOT 数量）；
  专利有标题 + 摘要片段 + 申请人 + 公开日；期刊侧 Crossref 无摘要（OpenAlex 补足关键词，
  仅 1 篇有完整摘要）→ **期刊板块摘要完整度是本场短板**。
- **数据可靠性**：⭐⭐⭐⭐⭐ ——
  全部关键数值均来自一手 NASA/NTRS 摘要原文（0.46/0.47/0.57 W；±8.4%/±8.0%/±16%；22 坯料；40 cm 胶囊；
  15 年合作；1/2 缩比等离子体试验），**未依赖二手转述**。发现并记录了 NTRS 同报告双 ID（`20170008743`/`20180000366`），
  主动修正了 v1.198 早间场「±8.4% 可直接用于热漏预算」的**偏乐观结论**。
- **工程价值**：⭐⭐⭐⭐ ——
  PICA-D drop-in 认证路径、MLI「模型 + 重复性 + 缝合」三拼图、DRACO 软木 TPS 闭环范式、
  BB（BN+PCM）双高复合膜、回收 PET 空心气凝胶 0.035 W/m·K，均可直接进入设计选型讨论。
- **可复现性**：**高** ——
  所有 URL、query、判活规则、坑位均已记录；NTRS 差集法可原样复跑。

## 改进点

1. **⭐ 必须新增「NTRS 同报告双 ID 去重」步骤** ——
   本场实测 `20170008743` ≡ `20180000366`（同一报告两个 ID）。
   **去重规则**：在「从未报道」差集之后，对**候选 ID 的 (标题规范化 + 报告号 GRC-E-DAA-TNxxxxx) 做二次归并**，
   归并组内只保留一条。**否则 NTRS 差集会把早间场已报内容当作增量重复计入。**
2. **⭐ v1.198 早间场结论需修正**：「MLI 重复性 ±8.4% 可直接用于 MLI 热漏预算」→ **应按制造商区分**
   （GRC 供片 ±8.4% / Yetispace 制造 ±16%），**早间场结论偏乐观**，须在知识库中标注适用范围。
3. **arXiv 切题真新连续第 5 场为 0** → **正式执行 v1.198 的降频决定**：
   - arXiv listing / export API **降为每 3–4 日 1 次**，且**只做池深挖 + 补摘要**，不再追求新文；
   - 本场再次验证：**semantic 复核是必需环节** —— 12 个「池外新 ID」全部为误报（超导、变压器、
     山火凝胶、红外隐身衣、4He 超流）→ **关键词过滤必然过召，必须人工语义复核**。
4. **Crossref 需前置期刊白名单** ——
   本场 86 篇去重候选中，TPS 相关仅 **6 篇**；`Electric Power Systems Research` 一刊即占 13 篇。
   → 建议加 `container-title` 黑名单（电力系统绝缘 / 医学 RF / 半导体）+ 正则强过滤，**并把 Crossref 从「主检索」降为「补充检索」**。
5. **Semantic Scholar 连续 3 场未测** → 本场应补测或**正式标记停用**（避免每场决策成本）。
6. **ESA 渠道虽连续 13 场 404，但 ESA 相关动态经 SpaceNews 可达**（本场 DRACO 即是）→
   **把「ESA 动态」的获取路径从 ESA 官网改为「SpaceNews + 媒体聚合」**，不必强求官网恢复。
7. **本场未做词表更新**（CORE 345 / STRONG 186 保持）。候选假阴性词簇：
   `cork-based ablative` / `PICA-D` / `lyocell` / `phenolic impregnated carbon` / `seam`（MLI 缝合）/
   `apparent thermal conductivity` / `repeatability` / `drag device` 已有 / `Knudsen` / `hollow fiber` /
   `polyarylate` / `BN` / `phase-change composite film` / `latent heat storage` / `thermal vacuum test`（已有）/
   `design for demise` / `Zero Debris` / `survival capsule` / `aeroshell`（已有）。
   ⚠️ 须按 §9.5 八步流程做深挖审计 + 新旧双评分器断言（`newA ⊇ oldA`）才可写回，本场未执行。
8. **池状态**：1640 → **1640（+0）** —— 本场无池深挖新增（arXiv 切题真新为 0）。
   备份：`~/.hermes/tmp_satins/arxiv_papers.json.bak_v199`（3.67 MB）。

## 下一步
1. **NTRS 差集法 + 双 ID 去重** 固化为每场必做流程，并**回溯 v1.197/v1.198 两场的 NTRS 差集**，
   检查是否也存在同报告双 ID 造成的重复计数。
2. **补测 Semantic Scholar**（DOI 端点而非 search 端点），若仍 429 则正式停用并写入渠道基线。
3. **检索 MLI 缝合（seam）后续**：`20170008804` 提到 GRC 还有系列测试，
   可用 `seam multilayer insulation` / `cryogenic insulation blanket test` 补捞更多一手数据。
4. **追踪 PICA-D 后续**：搜索 Lyocell/黏胶替代在 NASA 后续报告中的进展，
   验证是否已真正完成 Dragonfly / MSR EES 的飞行认证。
5. **DRACO 2027 发射跟踪**：作为 2026–2027 唯一的近地再入 TPS 在轨验证机会，
   持续跟踪 VKI/Amorim P50 的试验与飞行结果。
6. **arXiv 池深挖**（下 1 个 arXiv 场次）：针对 1640 条池中 `score>=8` 的条目做语义复核，
   验证「A 类边际价值耗尽」结论是否可翻转。
7. **期刊侧**：补 JMST / JECS / Advanced Nanocomposites 的**卷期直翻**路径
   （v1.198 早间场曾用 Crossref 全归零时成功过），以恢复摘要完整度。

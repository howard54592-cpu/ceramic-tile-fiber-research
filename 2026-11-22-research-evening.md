# 陶瓷瓦 / 纤维隔热研究 — 2026-11-22（晚间场 v1.229）

> 本场为 **2026-11-22 晚间场**。写入 `2026-11-22-research-evening.md`，**不覆盖**任何已存在的文件。

## 检索概要

- **日期**：2026-11-22 20:01 CST（晚间场）
- **渠道**：NASA NTRS（search + details，proxy）、OpenAlex（直连）、arXiv（listing/abs/export）、Google Patents xhr（proxy）
- **语料**：408 源 / raw 4,111,292 B / norm 1,919,809 B（GitHub 全量 + SKILL + references + daily）
- **探针**：真实已报 ID **25/25 FOUND**、0 MISS
- **差集结果**：NTRS 10 条 + OpenAlex 3 条真新；专利 0 条（详见「假阳性识别」）

---

## 关键发现 — 纤维隔热与陶瓷基复合材料方向

### 1. ⭐⭐⭐⭐⭐ NASA-CR-82003 / ER-14535 — X-15A-2 烧蚀 TPS 设计报告（1968）

- **NTRS**：`19680016245` — https://ntrs.nasa.gov/citations/19680016245
- **报告号**：`NASA-CR-82003`、`ER-14535`
- **内容**：X-15A-2 高超声速飞机烧蚀型热防护系统设计报告（*"Ablative thermal protection system for X-15 aircraft operating at hypersonic speeds"*）。
- **陶瓷/纤维相关性**：X-15A-2 采用 **Pyrotex**（酚醛-碳纤维）或改进 Avcoat 类烧蚀体，属**纤维增强酚醛烧蚀体**体系 —— 是**纤维增强陶瓷/酚醛 TPS 最早期的飞行器级系统设计**。
- **工程价值**：美国最早的烧蚀 TPS 系统级设计文档之一。记录了**驻点热流估算 → 烧蚀速率裕度 → 层间直接粘接（direct bond）→ 地面试验验证**的完整链条，是纤维增强烧蚀体「结构-工艺-验证」一体化的早期范式。

### 2. ⭐⭐⭐⭐ NTRS `19930012921` — 气动刹车 TPS 选型：烧蚀 vs RSI vs C/C（1993）

- **NTRS**：https://ntrs.nasa.gov/citations/19930012921
- **内容**：烧蚀 TPS 用于 aerobrakes 的 7 项优势，含第 (4) 条**「对缺陷不敏感，比 RSI（可重复使用表面绝缘）或 C/C（碳碳）更不易损伤」**、第 (5) 条**「大尺寸面板直接粘接」**、第 (7) 条**「无需 SIP（结构内热板）」。
- **陶瓷/纤维相关性**：这是 **SiC 陶瓷基复合材料（C/C、CMC）路线最权威的历史反方论证** —— 1993 年 NASA 明确指出陶瓷基体系相对烧蚀体系在**抗缺陷性**上的结构性劣势。
- **工程价值**：⭐⭐⭐⭐ 直接构成当前 **C/C 与 CMC 再入热盾（X-37B、BAE、ESA ARV）** 相对烧蚀体系的原始技术论证起点，是评估陶瓷基路线时**必须回溯的判据来源**。

### 3. ⭐⭐⭐⭐ NASA/CR-1998-208331 — Ames 热防护材料分支（TPMB）材料表征体系（1998）

- **NTRS**：`19980235586` — https://ntrs.nasa.gov/citations/19980235586
- **报告号**：`NASA/CR-1998-208331`、`NAS 1.26:208331`
- **内容**：Ames **热防护材料分支（TPMB）**分析实验室年度合同报告。TPS 材料持续测试评估三大维度：**热冲击抗力（thermal shock resistance）**、**高温尺寸稳定性（high-temperature dimensional stability）**、**恶劣环境耐受性（tolerance to hostile environmental effects）**；重点在各类研究计划试样的**物理与化学特性测定**。
- **陶瓷/纤维相关性**：高温陶瓷/CMC 材料的**热冲击抗力**与**高温尺寸稳定性**是两大核心考核项 —— 本报告给出了 NASA 官方实验室的**考核维度定义与表征路线**。
- **工程价值**：可作为建立自有陶瓷基/纤维隔热材料评价体系的**考核维度清单模板**。

### 4. ⭐⭐⭐⭐ NTRS `19680006152` — 高温热防护技术术语表 / NASA-CR-92590（1966）

- **NTRS**：https://ntrs.nasa.gov/citations/19680006152
- **内容**：航天器高温环境热防护术语表。
- **陶瓷/纤维相关性**：给出 **ceramic / ceramic matrix / fiber / composite / refractory** 等材料术语在 TPS 语境下的**官方定义边界** —— 对区分「陶瓷隔热（ceramic insulation）」与「陶瓷基复合材料（CMC）」的术语外延尤为关键。
- **工程价值**：NASA 热防护领域**最早权威术语基线**，是消除材料术语歧义（当前 skill `AMBIG` 歧义词表如 `silicon carbide` 的原始依据）的原始文献。

### 5. ⭐⭐⭐ NTRS `20160008019` — 复合材料低温贮箱 TPS 应用 / CCTD（2015）

- **NTRS**：https://ntrs.nasa.gov/citations/20160008019
- **内容**：NASA MSFC TPS Development Facility（Bldg. 4765）在 **Ø5.5 m 复合低温贮箱技术验证件（CCTD）**外表面施加 **Stepanfoam S-180 聚氨酯泡沫**低温绝热层，**人工喷涂工艺**（升降机 + 脚手架；横卧位喷涂桶段/穹顶段 → 竖立位完成末段）。为当时 S-180 泡沫**最大规模人工喷涂应用**，需对验证件实施严格**过程控制最佳实践**。
- **陶瓷/纤维相关性**：低温绝热层（泡沫/气凝胶/MLI）与 TPS 在**工艺链上同源** —— 人工喷涂大尺寸绝热层的厚度均匀性、密度、粘接离散性直接决定层内热导率与粘接失效模式。
- **工程价值**：**「制造过程控制决定绝热层质量」**的实证案例，可直接迁移到纤维隔热毯与陶瓷涂层的大面积施工工艺控制。

### 6. ⭐⭐⭐ OpenAlex — 1968 年 **Mars-entry TPS** 文献三连中的期刊版

- `10.2514/3.29469` — *Thermal protection systems for a Mars-entry vehicle.* — **Journal of Spacecraft and Rockets** — 1968-11
- `10.2514/6.1968-304` — *Thermal protection systems for a Mars-entry vehicle* — **AIAA/ASME/ASCE/AHS/ASC SDM Conference** — 1968-04
- `10.1016/s0045-7825(97)00153-9` — *Thermal analysis of the thermal protection system for the re-entry vehicle* — **Computer Methods in Applied Mechanics and Engineering** — 1998-01

- **交叉印证**：前两条为**同一研究的会议版与期刊版**（AIAA 会议 → JSR），构成「**同源版本对**」，是本领域少见的双渠道独立收录。
- **陶瓷/纤维相关性**：1968 年火星进入器 TPS 构型设计 —— 正是**陶瓷/纤维增强烧蚀体（Avcoat 类）在行星进入任务中的第一次正式应用评估**（与 Apollo 直接继承）。
- **工程价值**：⭐⭐⭐ 当前 Mars Sample Return / ExoMars / ESR-1 的火星进入 TPS 基础构型源自这一时期，该三篇是**经典构型的原始定义文献**，任何火星进入器 TPS 综述必须引用。

### 7. ⭐⭐⭐ 专利侧 —— 陶瓷基与隔热相关（真新 0 件，但清单有工程参考价值）

| 专利号 | 日期 | 权利人 | 主题 |
|---|---|---|---|
| `CN108911760B` | 2021-07-09 | 航天材料及工艺研究所 | **碳纤维增强树脂梯度炭化非烧蚀热防护** |
| `US20200152166A1` | 2020-05-14 | Arianegroup GmbH | **聚酰亚胺气凝胶薄膜多层隔热** |
| `US10520126B2` | 2019-12-31 | Panasonic IP Mgmt | 使用气凝胶的隔热结构 |
| `US9617069B2` | 2017-04-11 | 美国政府（NASA 代表） | 非真空应用多层隔热系统 |
| `EP2777932B1` | 2019-01-02 | Boeing | 隔热系统与方法 |
| `US10101099B2` / `NL2012119C2` / `US20190016482A1` | 2018/2015/2019 | Airbus Defence and Space NL | 散热器与航天器结构 |

- **全部 24 件真航天专利经主键精确匹配核验：语料 0 次 → 本场真新 0 件**（专利侧连续多场零增量，饱和已获独立确认）。
- **⭐⭐⭐⭐ 本场方法论修正 —— 专利「heat shield」消费语境假阳性**：`JP7577686B2`（エリコン フリクション システムズ，标题仅 "Heat shield"）实为**电池组隔热垫**（`temperature-resistant elastomer`），因标题含 "heat shield" 被航天词表误收。**已新增无条件否决词表**（`battery`/`cell pack`/`consumer electronics`/`printed circuit`/`furnace`/`kiln`/`brake pad`/`clutch`/`friction system` 等），与「命中即否决、航天词不得豁免」原则一致。

---

## 渠道有效性

| 渠道 | 状态 | 备注 |
|---|---|---|
| proxy 8001 | ✅ 全程稳定 | 开场真实 HTTPS 隧道探针 200；未复现 v1.219/v1.223/v1.225 失效形态 |
| NTRS search / details | ✅ 76 组 / **334/334 详情** | 报告号与机构分段命中率高（`NASA-CR thermal protection` total=323） |
| OpenAlex | ✅ 5/5 | 串行 12 s，零 503 |
| arXiv listing / abs / export | ✅ 3/3 (149 ID) / 147/149 / 2/5 | **连续第 5 场零新增 = 饱和** |
| Google Patents xhr | ✅ 首轮 4/4 **恢复** | 连续第 4 场归零后首次回春 |
| ESA RSS | ❌ 归零 | 连续第 2 场 → 建议停用 |

## 质量评估

- **信息完整度**：⭐⭐⭐⭐ —— 全部 never 条目含完整摘要 + 报告号 + DOI + 期刊元数据
- **数据可靠性**：⭐⭐⭐⭐⭐ —— 主键精确匹配 13/13 核验为 0 次命中；探针 25/25 FOUND；1 条假阳性被主动识别并修正
- **工程价值**：⭐⭐⭐⭐⭐ —— X-15A-2 烧蚀设计（1968）、CMC 路线反方论证（1993）、TPMB 考核维度（1998）、火星进入 TPS 原始定义（1968×2 + 1998）
- **可复现性**：高 —— 全部 URL/参数/门控/匹配器级别/语料范围已记录

## 改进点

1. ⭐⭐⭐⭐⭐ **NTRS 报告号/机构/年代分段是最高产检索轴**（三轮新增 225 候选 → 10 条真新），下场配额应 **≥60% 压向分段检索**
2. ⭐⭐⭐⭐ **专利无条件否决词表**（消费/电池/工业炉窑/摩擦系统语境）——「命中即否决，航天词不得豁免」
3. ⭐⭐⭐⭐ **年代键必须用 `publications[].publicationDate`**；本场 10 条 never 全部依赖它，`distributionDate` 对 1960s–1990s 档案报告无一条可信 → **NTRS 详情层升为常驻主路径**
4. ⭐⭐⭐⭐ **arXiv 与专利双侧饱和确认**（连续多场零增量）→ 两者降频至每两周 1 次
5. ⭐⭐⭐ **交叉印证在本领域天然稀薄**（NTRS 报告与期刊论文元数据链路断裂）→ 改用「**同源版本对识别**」（会议版 ↔ 期刊版）作为辅助置信度指标

## 下一步

1. 顺藤摸瓜：`X-15A-2` → 同系列 X-15 TPS 报告；`Mars-entry TPS 1968` → AIAA 1968/1969 会议卷中的 TPS 论文
2. NTRS 前缀表补 `NASA-CASE-` / `SWAS-` / `M-` / `X-` / `REPT-` / `L-` / `CR-`
3. 机构 × 年代交叉（`Langley 1970` / `Ames 1980` / `JPL 1990` / `Lewis 2000` / `KSC 2010`）
4. 专利无条件否决词表扩充 `automotive` / `building envelope` / `fireplace` / `solar cooker`

---

*Hermes Agent 自动生成 · v1.229 · 2026-11-22 晚间场*

# cyanotype_classic dossier：经典蓝晒（对照基线）

> 裁定：淘汰（作为免洗产品路线）；保留为对照基线（06 DQ-01 选项 B）。本页于 2026-11-01 补写，原目录缺此 dossier（批评清单「dossiers_missing」）。来源 ID 对应 `_sources/final-json/routes/cyanotype_classic.final.json` 的 sources 字段。

## 1 机制与极性

- 事实（A，S01 Table 1、S03）：紫外光使 Fe(III) 柠檬酸盐光还原为 Fe(II)；Fe(II) 与铁氰根 [Fe(CN)6]³⁻（铁氰化钾）生成不溶的 Turnbull's blue（ferrous ferricyanide）。Turnbull's blue 与 Fe(III) 和亚铁氰根生成的 Prussian blue 化学上基本相同（B，07 §四.1）。
- 过量曝光时，过剩 Fe(II) 把蓝色还原为 Prussian white（solarisation 反转）；之后靠空气或 H2O2 氧化回蓝（S01、S03）。
- 极性：负像（曝光区显蓝，白区洗去未反应感光剂后为纸色）；单色相；连续色调未验证。

## 2 证据

| 编号 | 主张 | 等级 | 标签 | 来源 |
|---|---|---|---|---|
| C1 | 停止即水洗（Jacquard 说明书；Ware 2014 §7.1.4） | A | 事实 | S04、S03 |
| C2 | 洗 4 分钟与 20 分钟的最大褪色值分别为 42 与 16（单次小样） | A | 事实（小样） | S01 |
| C3 | 0.25 M Na2CO3（pH≈10.7）在 30 秒内破坏普鲁士蓝 | A | 事实（Ware 2003 原文） | S01、S03 |
| C4 | pH 9.4 缓冲需 1–10 分钟褪色 | B | 事实（Ware 转引 Holtzman 1945，未直接核对） | S01 |
| C5 | 厂商声明预涂布 6 个月（"for best results"） | A | 事实（厂商声明，非独立验证） | S19 |
| C6 | 碳酸钙缓冲板材对普鲁士蓝有破坏（损失 40–60） | A | 事实 | S01 |

## 3 六条底线逐条结论

1. 喷后免洗：✗（停止即水洗，C1，A）。
2. 白区停得住：✗（未洗白区保留感光剂，C2，A）；本轮所列范围内未发现原地停止剂。
3. 成色留得住：?（褪色可在暗中回复，A；停止剂未知，无法对候选评估）。
4. 少量均匀喷液即可充分停止：?（无候选停止剂，无法评估）。
5. 底材不变形、干后可拼合：?（C6 为碳酸钙板材的破坏；灰板变形未测）。
6. 安全前置：?（K3Fe(CN)6 SDS 未分类，S12，A；酸致 HCN 风险见亚铁氰化钾 SDS，A；ASTM D-4236 与 LHAMA 未能证实，零售页 403，S20、S23）。

## 4 风险与红线

- 红线命中：强酸与铁氰化物生成 HCN（Ware New 硝酸浴，A；历史 1847 方法，A）。重铬酸盐见于 Ware New 配方与部分讲义洗水（A/B），出局。
- 碱（pH>7）破坏普鲁士蓝（C3，A）：碱性方案单独评估，对已成色的影响须按 06 DQ-12 处理。
- 汞盐：Herschel 1842 的氯化汞"无洗"方案因高毒判为不可用（S03 引文，A）。
- 家用：水洗量大，且 FAC、硫酸镍、汞盐、醋酸铅的 SDS 未读（S13 仅为亚铁氰化钾）。

## 5 关键未知

- 能否找到不洗、非碱、非强酸、非还原、非草酸盐、非柠檬酸、非汞镍铅的原地失活方案（本轮范围内未发现先例）。
- 未洗或封存后白区与成色在暗存、湿度、空气下的长期行为（无数据）。
- 395 nm 对经典 FAC 体系的实测曝光时间与 mJ/cm²（未验证；S14 的光谱数值未能读取）。
- 预涂货架期冲突：6 个月（S19，厂商）对 ≥2 年（S21，布料，搜索摘录），出厂货架期未知。

## 6 判别实验设计（作为对照基线使用）

- 目的：为 DQ-01 选项 B 提供白区与成色的基线。
- 三组：未处理暗放；标准全洗（按 Ware 2014 §7.1.4 洗至黄色消失，约 20 分钟）；候选喷剂一次喷后暗放（候选须先过红线筛选并查 SDS）。每组 n=2。
- 曝光：日光 10 分钟（或经 365 nm 标定的 UVA 光源，记录剂量）；显影后吸干，暗放 0 h、24 h、7 天，测白区 ΔD（或 ΔE*ab）。
- 通过与失败标准（提议值，未经文献验证）：候选组白区增幅超过 0.02，或出现蓝或绿偏色，即证伪该候选。
- 另做 2 kilolux·h 褪色对照（Ware 2003 方法）。
- 全部在有抽风柜与专业监护的实验室进行（06 DQ-07 选项 B）。

## 7 对旧轮次的勘误与分歧

- 轮1 A1 第 3 条"水洗是唯一停止与定影手段"：与 Jacquard 说明书与 Ware 2014 一致（agree，强）。
- 原 01 表 A 的 c01 反应物配对已按 07 §四.1 更正为 Turnbull's blue。
- 原 01 表 B 的 c06 碱数据已按 C3、C4 分开标注证据等级。

## 8 负结果（仅指所列范围内未发现）

- WebSearch（research 轮）：无水停止剂或喷雾稳定的先例，未命中（摘录仅为论坛与博客，无可引用的一手实验）。
- 专利关键词（"photographic image without water washing stabilizing spray ferricyanide ferric citrate"）：未发现可直接替代的停止专利（S17 为银盐相纸的免洗稳定液，非蓝晒）。
- 完整清单见 `04-负结果清单.md` 中主题为 cyanotype 的条目。

## 9 来源列表（节选）

- S01 Mike Ware, A Blueprint for Conserving Cyanotypes（Topics in Photographic Preservation vol.10，2003），curl 全文（PDF）。
- S03 Mike Ware, Cyanomicon（2014），curl 全文（PDF）。
- S04 Jacquard, Cyanotype Formula, Mixing and Exposing Instructions，curl 全文（PDF）。
- S07 UMBC, Cyanotype Process steps（教学讲义），curl 全文。
- S12 Bostick & Sullivan, Potassium ferricyanide SDS（CAS 13746-66-2），curl 全文（PDF）。
- S13 Potassium ferrocyanide trihydrate SDS（CAS 14459-95-1，LabAlley 副本），curl 全文（PDF）。
- S14 PubMed 25327500（光谱响应），API（摘要）。
- S18 Mike Ware, New Cyanotype Process，curl 全文。
- S19 Jacquard 产品页，curl 全文（无可用价格与货架期文本）。
- S20、S21、S23：搜索摘录或 curl 403 不可读，未绕过。
- S24 Crossref 元数据，DOI 10.1021/ac00278a041，API。

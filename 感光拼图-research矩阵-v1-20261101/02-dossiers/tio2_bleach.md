# tio2_bleach dossier：TiO2 光催化染料漂白

状态：观察线（降级）· 2026-11-01 · 依据 final.json（c01–c15）、verify.json，并引用专项 deep_f_tio2、deep_uvlamp、safety_other、regulatory。

## 1 机制与极性

- 事实（A，S02）：TiO2 与覆盆子果汁染料在可见激光下发生氧化光漂白，染料被破坏。被照射处变浅，未照射处留色，成「深底浅图」，单色相。
- 推断链：染料结构被破坏，无再生途径，故不可逆（依据摘要「oxidative photobleaching」用语，未见全文）。
- 未验证：电子注入与自由基链、锐钛矿晶型、滤纸底材、染料是否为花青素（来自旧笔记）。
- 对照（事实，A，S08）：Yin 2014 的 TiO2/亚甲蓝为光还原，可逆，不能代表本路线。

## 2 证据

- Ibanez 2011 书目（J Chem Educ 88(8):1116）：A·事实，S01。
- 摘要「可见激光氧化光漂白」：A·事实，S02。
- 锐钛矿吸收边约 387 nm：A·事实，S05。
- Yin 全文：UV 印写，115 °C 加热擦除，无水洗或定影，>20 次写擦，三原色：A·事实，S08。
- Yin 的「至少 3 d 可读」指光印白字，不是未照射背景：A·事实，S08。
- 室内 500 lux 荧光灯 UVA 约 30 mW/m²：A·事实，S09。
- 无 SiO2 的 TiO2 聚合物漆光致泛黄：A·事实，纸基外推未验证，S07。
- 磷酸盐部分抑制 TiO2 光催化，低浓度可升高空穴：A·事实（探针法），deep_f_tio2 f20。
- 磷酸盐作曝光后停止剂：B·推断，证据相互冲突，deep_f_tio2 f22、f34。
- 395 nm（3.14 eV）低于锐钛矿带隙：推断（算式，S05），但染料敏化路径未排除。
- 30 min 日光 UVA 约 5.0–7.2 J/cm²（洛杉矶秋季正午估算）：推断，deep_uvlamp F05。
- TiO2 IARC 2B；欧盟粉末 Carc. 2 分类撤销：B·事实，S06、S13。
- 花青素 pH 变色，欧盟食用 E163：B·事实，S12。
- 旧日光数字（2 min 起漂白，20–25 min 清晰，300 W 灯 5 min）：未验证，S17、S18。

## 3 六条底线

1. 喷后免洗：? 原方案无喷雾；基础曝光无水洗显影（Yin 证实，Ibanez 未证）。若干式 UV 封层算额外步骤，则为名义免洗。
2. 白区停得住：? 理论稳定（推断）。若配方含还原糖或抗坏血酸，白区可能回色或加速降解（deep_f_tio2 f11、f16，聚合物外推）。
3. 成色留得住：? 背景褪色无数据。
4. 少量均匀喷液：? 停止液未设计；磷酸盐效应非线性（f20）。
5. 底材不变形：? 纸与板水基刷涂后变形未测。
6. 安全前置：? 无 ✓。TiO2 粉尘与花青素 SDS 未取到，ASTM D-4236 与 LHAMA 结论未查到。红线未命中。

## 4 风险与红线

- 红线：无铁氰化钾（potassium ferricyanide）、亚铁氰化钾（potassium ferrocyanide）、重铬酸盐，无强酸。碱性停止（K2HPO4 推算 pH 9–10，未测）会改变花青素颜色（B），须实测。
- 氟化钠：H301（ECHA 聚合 97.1%），不进入家用方案（f24）。
- TiO2 粉末：PubChem 聚合 H319、H335、H372（Danger）、H413，H351 通报 12.6%、36.1%（非法定，需厂商 SDS）。IARC 2B；NIOSH 细颗粒 2.4 mg/m³（A）；Prop 65 收录空气中未结合可吸入形态（A）。喷雾停止剂若含 TiO2 颗粒即落入此形态（推断），故停止剂不得含 TiO2。
- K2HPO4：H315（约 41% 通知）、H318（约 10%，Danger）（聚合，B）。
- 亚甲蓝（仅 Yin 型对照）：H302、H318、H412（聚合），不入家用。
- PPE：干粉只在通风处称量，戴 FFP2/N95；护目镜；丁腈手套；UV 防护眼镜，不直视 UV LED；全程湿式浆料化，成人监护。

## 5 关键未知

1. 室内光（以可见为主）下未曝光背景能否数周保持颜色。这决定底线 2–3。
2. 可见光路径：Ibanez 为可见激光驱动，UV 封层不覆盖。395 nm 是否有效取决于染料在 395 nm 的吸收，未查。
3. 干式 UV 封层能否阻断背景反应、不被 TiO2 光氧化，且是否计为额外步骤。
4. Ibanez 日光数字能否归属；30 min 目标需用辐射计实测重建。
5. 磷酸盐的 pH 与浓度窗。SiO2 包覆方向依赖相与载量，不可靠（deep_f_tio2 f19）。

## 6 判别实验

- 目标假设：该配方下背景在室内光 30 d 内稳定，且 K2HPO4 喷雾使白区漂移降低 ≥50%。
- 材料：无酸水彩纸（300 g/m²）与 1.5 mm 灰板，各切 10×10 cm，每组 3 片。浆料：TiO2 粉 2 g（湿式加水称量）、覆盆子果汁浓缩液 5 mL（不调 pH，记录）、HEC 0.5 g、去离子水 20 mL，搅拌 10 min，刷一层，暗处干 24 h。停止液：去离子水；K2HPO4 0.5、5、25 mM，现配并测 pH，不含 TiO2。
- 对照：未处理（不曝光不喷，0 h 基线）；A 避光（只证明暂停）；B 无 TiO2，同曝光；C 曝光不停止；D 曝光后清水喷；E、F、G 曝光后磷酸盐三档。
- 灯：日光组，晴天当地正午前后 1 h，水平放置，30 min，同步用经 365 nm 标定、余弦修正的 UVA 辐射计记录辐照度 E 与剂量。UV 灯：365 nm 窄带 UVA LED 面板（峰值 365–370 nm），工作距离 10 cm，设定 E≈3 mW/cm²，30 min（约 5.4 J/cm²）。395 nm 消费灯（50 W 类）：调距使 E 与 365 nm 组相同，记录距离，30 min。
- 步骤：
  1. 切样编号，遮光，测 0 h 初值（D65 比色仪，每点 3 次平均，ΔE*ab）。
  2. 每片一半用不透光纸遮住，同片得到背景区与白区。
  3. 按组刷涂，暗干 24 h。
  4. 按组曝光，A 组全程避光。
  5. 按组喷停止液，C 不喷；喷距 20 cm，两遍，间隔 1 min，水平放置 30 min。
  6. 测 0 h，记录 pH。
  7. 样片分两批，一批置室内荧光灯（约 500 lux）下，一批置暗处。
  8. 在 24 h、7 d、30 d 重复测量。
- 量化：白区与背景各测 ΔE*ab（相对 0 h）；白区与背景之差为对比度。
- 通过与失败（提议值，未经文献验证）：背景 30 d ΔE*ab ≤2.0；白区 7 d ΔE*ab ≤1.0；停止组白区漂移比 C 组降低 ≥50%，且对比度保留 ≥80%。失败：磷酸盐组背景 ΔE 大于 D 组，淘汰磷酸盐；白区 7 d ΔE >1.0，不进入下一阶段；395 nm 对比度达 365 nm 的 50% 以上，窗后曝光不允许。
- 安全：干粉只在通风处称量；护目镜与手套；UV 灯置于遮光盒内；不用亚甲蓝、氟化物、氨或碳酸钠；废液按当地规定处置；儿童不得接触。
- 预算：材料约 USD 50–150（未验证）；UVA 辐射计与比色仪另计。

## 7 旧轮次勘误与分歧

- 「首轮台架候选 #1」的 Ibanez 日光数字撤回，路线降为观察线（07 勘误 E10）。
- 轮5 G1「无残留感光剂天然通过」与 G3「UV 封层作定影」均不成立（E30、E31）。
- c02「只演示二值图案」有误（Yin 有三原色）；c05 正文「底线 1 ✓」已删除。
- G7 Carc. 2 的日期有分歧：07 勘误记 CJEU 判决日为 2025-08-01；final 据 Normachem 记为失效起算日；safety_other 据 CIRS 记 CJEU 为 2025 年 6 月。本稿不引用具体日期，待 EUR-Lex 与 ECHA 原文核对。
- PubChem TiO2 GHS：final 记 PUG-View 失败，safety_other 记聚合已确认。本稿采用聚合值并标非法定。
- 磷酸盐：final c06 写「淬灭未检索」，但 deep_f_tio2 已检索，本稿采纳其「部分、浓度依赖、推断 B」结论。
- 30 min 依据：旧 4.5–6.3 J/cm² 作废，现为 5.0–7.2 J/cm²（推断）。

## 8 负结果（仅限所列范围）

- Ibanez 全文：pubs.acs.org、doi.org 拒绝访问，未绕过。ResearchGate 图注 HTTP 403。WebSearch「Ibanez 2011 sunlight minutes raspberry anthocyanin TiO2」：未找到日光时长与 300 W 数字。
- 室内 UV 辐照度：PubMed「indoor fluorescent light photocatalytic TiO2 dye degradation visible」0 命中；WebSearch 1 次仅得 ICNIRP 数字。
- 磷酸盐或氟化物作曝光后停止（终点为未曝光区漂白）：PubMed「phosphate or fluoride as post-exposure stop of TiO2 photocatalysis」等多组未发现。暗态停止：PubMed 0 命中。
- TiO2 与染料的背景褪色或加速耐光：deep_f_tio2 的 PubMed 多组检索与 WebSearch 1 次未找到。本稿 c08 无检索式，记为未知，不作结论。
- 专利：Google Patents「photocatalytic bleaching titanium dioxide dye paper」两次返回拦截页，未检索。仅见 UCR US 10,534,254 标题（关键词范围内发现），不写「无专利」。
- 零售：Dharma 站内搜 titanium dioxide，9 个结果无 TiO2 单品（curl，2026-11-01）。Amazon 禁止访问。
- ASTM D-4236 与 LHAMA 对 TiO2、花青素、亚甲蓝：未找到结论，未读 CPSC 页。

## 9 来源

除注明外，access 为 curl 或 API，读取日期 2026-11-01。

- S01 Ibanez 2011 书目，api.crossref.org/works/10.1021/ed1008848，A，API
- S02 ERIC 摘要 EJ941030，eric.ed.gov/?id=EJ941030，A，摘要页
- S03 ResearchGate 图注，researchgate.net/figure/…263945548，未验证，HTTP 403
- S04 2012 同刊日光演示，doi.org/10.1021/ed300048z，A（书目）
- S05 Serpone 2006 摘要，pubmed.ncbi.nlm.nih.gov/17134177，A，API
- S06 Wikipedia Titanium dioxide，en.wikipedia.org/wiki/Titanium_dioxide，B
- S07 Materials 2018 PMC6213899，ncbi.nlm.nih.gov/pmc/articles/PMC6213899，A，全文
- S08 Yin & Xie 2014 Nat Commun，nature.com/articles/ncomms6459，A，全文
- S09 ICNIRP UV 工作者指南，icnirp.org（PDF），A，全文
- S10 Dharma Trading 站内搜索 titanium dioxide，dharmatrading.com/search?q=titanium%20dioxide，A，curl
- S12 Wikipedia Anthocyanin，en.wikipedia.org/wiki/Anthocyanin，B
- S13 Normachem 法规资讯，normachem.com（二手），B
- S14 UC 技术转让 24555，techtransfer.universityofcalifornia.edu/NCD/24555.html，标题可见
- S17 本地旧笔记 F-photobleaching.md，未核原文，2026-10-19
- S18 首单清单 DRAFT（估算价），未验证，2026-10-19
- 专项：deep_f_tio2 f20 引 PMC6471673（A）；deep_uvlamp F05 引 DOI 10.1111/php.13111（A）。

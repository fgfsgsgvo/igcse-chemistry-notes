# Unit 4 — Electrochemistry 电解

> **考纲**：0620 Chemistry Syllabus **2026–2028**（Version 1, September 2023）· Section **4.1 Electrolysis** + **4.2 Hydrogen–oxygen fuel cells**
> **试卷**：Paper 2（MCQ，40 分，30%）+ Paper 4（Theory Extended，80 分，50%）+ Paper 6（Alternative to Practical，40 分，20%）
> **考纲版本核实**：官方第 58 页原文 `There are no substantial changes in this syllabus that would impact teaching.` ⇒ **2023–2025 真题完全对应 2026 年考试范围**。
>
> **本单元特点**：**4.1 电解是 Paper 4 的第二大主题**（机器统计 443 分 / 3360 = 13.2%，仅次于 6.3 平衡）；**4.2 燃料电池只有 0.9%**，但它 100% 是"背了就有分、没背就一分没有"的题。
> 本单元**没有计算题、没有画图题**，全部是**定义 + 产物 + 现象 + 半方程式**四种固定问法 —— 也就是说，**这一章的分全是背出来的**。
>
> **语料基础**：
> **294 个 txt = 138 QP + 138 MS + 18 ER**。其中 `_research/topic4-electrochemistry.md` 逐份核过第一轮的 42 份 Paper 4；
> **2026 新增的 4 份 Paper 4（m26/42、s26/41、s26/42、s26/43）由本笔记第二轮补核**，见 §📊 真题实证 → **2026 新增批次**。
> **Paper 4 = 46 份**（m20–m26 每季只有 component 42；s/w 每季 41/42/43 齐全 ⇒ 7×1 + 13×3 = 46）；**Paper 2 = 46 份**（21/22/23）。
> ⚠️ **本文的考频计数以第一轮 42 份为基数**（那是 research 文件逐份核过的范围），2026 新增批次**单独列出**，两套数字不混算。
>
> **⚠️ 符号说明（`pdftotext -layout` 的确定性丢失，全文通用）**
> 1. **反应箭头 `→` 被整个吞掉** ⇒ 本文凡箭头一律写作 `[→]`，**方括号 = 我方重建，非原文**。
> 2. **上标电荷丢失** ⇒ 重建的 `[⁻]` `[²⁺]` `[²⁻]` 一律带方括号。
> 3. **下标被拍平** ⇒ 重建的下标写作 `[₂]`（如 `H[₂]O` 原文是 `H2O`）。
> 4. **`�`** 是编码替换符（可能是 `–` 或 `°`）⇒ 本文写作 `[–]` 并注明。
> 5. **温度**：原文 `322C` 实为 `322 °C`。
> **凡本文出现的方括号符号，都是重建；凡不带方括号的英文短语，都是 MS 逐字原文。**
> 6. **中文讲解里的示意箭头（`→`）只是说明用**（如"稀 → O₂"），**不是方程引用**；凡**引述 MS / 题干原文**的化学方程式，箭头一律写作 `[→]`。

---

## 📋 考纲对照清单

> **用法**：这是**唯一权威清单**（出处 `_research/syllabus-topics-4-5-6.md`，来自学校指定考纲 PDF 逐字抄录）。
> 笔记逐条覆盖，不多写、不漏写。「真题考过没有」一栏全部来自 `_research/topic4-electrochemistry.md` 的逐份核对。

| 考纲 | 内容（官方原文摘要） | C/S | 真题考过没有（0620 实证） | 掌握 |
|---|---|---|---|---|
| **4.1-1** | Define electrolysis as **the decomposition of an ionic compound, when molten or in aqueous solution, by the passage of an electric current** | C | ✅✅ **全主题最高频单一考点**：13 份卷考定义 + 3 份卷考 electrolyte 定义 + 5 份卷考"命名该过程" | ☐ |
| **4.1-2** | Identify (a) **anode = positive electrode** (b) **cathode = negative electrode** (c) **electrolyte = 熔融或水溶液、发生电解的物质** | C | ⚠️ **Extended P4 结构化题 0 次**（题干自带 `(cathode)` `(anode)` 括号标注）；**Core 卷与 MCQ 考过**；`electrolyte` 定义考纲未列但真题自加考 **3 次** | ☐ |
| **4.1-3** | Identify products + describe observations for (a) **molten lead(II) bromide** (b) **concentrated aqueous sodium chloride** (c) **dilute sulfuric acid**，用 **Pt 或 C 惰性电极** | C | ✅ 熔融 PbBr₂ 1 次（w21/41 Q3(e)）；浓 aq NaCl 结构化 1 次（s21/42 Q4(e)）+ **4 道 MCQ**；稀硫酸 2 次（w20/41 Q5(a)(iii)、w25/42 Q4(a)(vi)） | ☐ |
| **4.1-4** | State that **metals or hydrogen** formed at **cathode**；**non-metals (other than hydrogen)** formed at **anode** | C | ✅ 内嵌于上表各题（产物题就是考这条） | ☐ |
| **4.1-5** | Predict products for electrolysis of a **binary compound in the molten state** | C | ✅ **4 次**（熔融 KCl / NaF / PbCl₂ / KBr） | ☐ |
| **4.1-6** | State that metals are electroplated to **improve appearance and resistance to corrosion** | C | ✅ 1 次：`0620/43` May/June 2023 Q5(c)(ii) `M1 prevent corrosion / M2 improve appearance` | ☐ |
| **4.1-7** | Describe how metals are electroplated | C | ✅ Paper 4 **2 次**（s22/43 Q5(b)、s23/43 Q5(c)(i)）+ Paper 6 **1 次**（m25/62 Q4，6 分规划题） | ☐ |
| **4.1-8** | Describe transfer of charge: (a) **movement of electrons in external circuit** (b) **loss or gain of electrons at electrodes** (c) **movement of ions in electrolyte** | **S** | ✅ **6 次**（导线中粒子、电解液中粒子、电子流向箭头、为何熔融导电） | ☐ |
| **4.1-9** | aq copper(II) sulfate **用惰性 C/石墨电极** AND **用铜电极** | **S** | ✅ **5 次**（全主题第三高频体系） | ☐ |
| **4.1-10** | Predict products for **halide in dilute or concentrated aqueous solution** | **S** | ✅ **4 次**（稀 KBr、浓 aq NaBr、稀 NaF、浓 aq KI） | ☐ |
| **4.1-11** | Construct **ionic half-equations** for anode (oxidation) and cathode (reduction) | **S** | ✅✅ **23 份卷考过**（第二高频考点） | ☐ |
| **4.2-1** | State that a hydrogen–oxygen fuel cell uses H₂ and O₂ to produce electricity with **water as the only chemical product** | C | ✅ 全部 **5 份** Paper 4 结构化题 + 全部 **23 道** MCQ | ☐ |
| **4.2-2** | Describe **advantages and disadvantages** of H₂–O₂ fuel cells **vs gasoline/petrol engines** | **S** | ✅ **3 份** Paper 4（s23/41 Q5(c)(ii)、w23/43 Q5(d)(ii)、w24/41 Q5(a)(ii)）+ MCQ 若干 | ☐ |

> 📌 **本节共 13 条**（4.1：Core 7 + Supp 4；4.2：Core 1 + Supp 1），是本套笔记中**最小的一节**，与实测权重（4.2 仅 0.9%）吻合。
> **本单元的分数分布极不均匀**：定义 + 半方程式两条就吃掉了绝大部分分值，而 4.2 全部内容只值 10 分。

---

# 4.1 Electrolysis 电解

## 4.1.1 定义 electrolysis（考纲 Core 1）—— **全主题最高频考点**

### English 背这句

> **最高频表述（10 份 MS 逐字相同，是本考纲的定义标准式）**
> `M1 breakdown by (the passage of) electricity(1)`
> `M2 of an ionic compound in molten or aqueous (state) (1)`
>
> 出处：`0620/41` May/June 2021 Q3(c)(i)；`0620/43` May/June 2021 Q3(c)(i)；`0620/41` May/June 2024 Q3(c)(i)；
> `0620/43` May/June 2024 Q3(c)(i)；`0620/42` Nov 2022 Q3(b)；`0620/43` Nov 2024 Q2(a)；
> `0620/42` Oct/Nov 2020 Q5(a)(i)；`0620/43` Oct/Nov 2020 Q5(d)(i)；`0620/42` Feb/Mar 2020 Q2(a)(ii)

**变体 1（把两句合成一句，仍给 2 分）**
> `breakdown of an ionic compound when molten or in aqueous solution (1)` — `0620/42` May/June 2020 Q5(a)
> `breakdown of a molten / or aqueous ionic compound by the passage of electricity` — `0620/43` May/June 2020 Q7(a)

**变体 2（填空题版本，3 分，把定义拆成三个空）—— `0620/42` May/June 2025 Q3(a)**
> 题干：`Complete the definition of electrolysis by filling in the missing words.`
> `The decomposition of ........................ compounds when ........................ or ........................ by the passage of an electric current.`
> MS：`M1 ionic` / `M2 molten` / `M3 in aqueous solution`
> 原文 span（`0620_s25_ms_42.txt` 第 229–231 行）：`3(a) M1 ionic / M2 molten / M3 in aqueous solution`

### 🔧 答题模板：一句话拿满 2 分

```
Electrolysis is the breakdown of an ionic compound,
when molten or in aqueous solution,
by the passage of an electric current.
```

**四个必须出现的要素**（缺一个就丢 M 点）：

| # | 要素 | 英文关键词 | 常见写法（❌ 不给分） |
|---|---|---|---|
| 1 | 分解 | **breakdown** | ❌ `separation`（这是物理变化！） |
| 2 | 靠电 | **by the passage of electricity** / `an electric current` | ❌ `current`（漏掉 "electric"）、❌ `electricity` 单独出现 |
| 3 | 离子化合物 | **ionic compound** | ❌ 只写 `compound` / `substance` / `liquid` |
| 4 | 熔融或水溶液 | **molten or in aqueous solution** | ❌ 完全不提状态（**最常见失分**） |

**M1 / M2 的划分逻辑**（照抄官方）：
- **M1 = ①+②** —— `breakdown by (the passage of) electricity`
- **M2 = ③+④** —— `of an ionic compound in molten or aqueous (state)`

> 📌 **题目会怎么问**：`Define the term electrolysis.` / `State what is meant by the term electrolysis.` / `Name the process used to produce X from molten Y.`（1 分题）
> 最后一种问法出现 **5 次**：`0620/42` Feb/Mar 2022 Q4(d)(i)、`0620/42` Feb/Mar 2024 Q1(e)(ii)、`0620/42` Feb/Mar 2025 Q2(d)(i)、`0620/41` May/June 2024 Q1(c)、`0620/43` May/June 2024 Q1(b)。**答案就是一个词 `electrolysis`。**

### 中文理解

**"电解"这个词在考纲里只有一个定义，而且只有四块拼图**：`breakdown`（化学分解，不是物理分离）+ `ionic compound`（离子化合物 —— 只有离子化合物能在熔融/水溶液状态下导电）+ `molten or aqueous`（必须让离子能移动）+ `by the passage of electricity`（靠电流驱动的分解）。

**为什么必须写 "ionic compound"？** 因为这是电解与"加热分解"（thermal decomposition）的分界线 —— 加热分解不需要离子导电。**为什么必须写 "molten or aqueous"？** 因为固态离子化合物里的离子是**locked in the lattice**，不能移动、不能导电。**为什么必须写 "breakdown"？** 因为 `separation` 在化学里指物理分离（如分馏、过滤），而电解是**化学变化**。

> ⚠️ **不要写 "electrolysis is a process that separates elements from compounds"** —— 这是化学上正确但**判分上不给分**的表述（见下方 ER 原文）。

### ⚠️ 陷阱（考官逐字点名）

> **① 最常见的三种失分（`0620/43` May/June 2021 Extended Q3(c)(i)）**
> `It was clear that many of those who tried to explain electrolysis did not appreciate that it is a decomposition process whereby a molten or aqueous ionic compound is broken down using electricity. Common errors included omitting the physical state, suggesting 'separation' (a physical change) was occurring or stating the compound was broken down using a 'current' rather than specifying an 'electric current'.`

> **② 官方"不给分"短语逐条（`0620/41` Oct/Nov 2020 Extended Q5(a)(i)）**
> `Candidates found this very challenging with many being unable to define the term electrolysis. Common phrases which did not gain any credit were 'separation of elements', 'breakdown into ions' and 'separation into ions'. While many candidates were able to identify that ionic compounds undergo electrolysis, they did not mention that these needed to be in the molten or aqueous state.`
>
> ⇒ **黑名单**：`separation of elements` / `breakdown into ions` / `separation into ions` 全部 0 分。
> 「breakdown into ions」错在哪里？因为电解**不是**把化合物拆成离子 —— 离子本来就在化合物里；电解是把**离子变成原子/分子**。

> **③ 不背定义的代价（`0620/43` Oct/Nov 2022 Extended Q3(b)）**
> `A number of candidates learnt the syllabus definition of electrolysis perfectly. Those who attempted to explain electrolysis without using the syllabus definition, often missed out various key words or phrases. Separation was sometimes used instead of breakdown. The fact that compounds had to be ionic to undergo electrolysis was often missing.`

> **④ 官方 Key message（`0620/41` Oct/Nov 2020）**
> `Recall of definitions is an area that needs to be developed especially regarding equilibrium and electrolysis.`

> **⑤ 备考建议原文（`0620/41` May/June 2021 Extended Q3(c)(i)）**
> `Candidates should make sure that they are adequately prepared for questions of the type 'State what is meant by the term...'. Candidates should be aware that the substance that is decomposed must be molten or aqueous.`

> 💡 **结论：定义题必须"背原文"，不能"凭理解写"** —— 这是全单元唯一一个"理解得再好也拿不到分、背下来就稳拿分"的考点。

> 🆕 **⑥ 官方点名"缺的是哪个词"—— 这次点名的是 `ionic`（ER `0620/41` May/June 2024 Q3(c)(i)）**
> `There were many very good answers, giving the syllabus definition of electrolysis. **The word 'ionic' was sometimes missing.**`
> ⇒ 这条特别有用：它告诉你多数考生能写出 `breakdown … electricity`，**丢分就丢在 `ionic` 上**。

> 🆕 **⑦ 官方把"定义题"定性为"白送的分"（ER `0620/43` May/June 2024 Q3(c)(i)）**
> `Candidates should make sure that they are well prepared for questions of the type 'state what is meant by the term...' as these are **easy recall marks gained for definitions given in the syllabus**.
> Common errors included: describing 'separation of ions' (a physical change) rather than 'separation into elements'; omitting that the compound to be decomposed must be ionic; omitting that the compound must be molten or aqueous.`
> ⇒ **三个失分点一次列全**：`separation of ions`（物理变化）、漏 `ionic`、漏 `molten or aqueous`。

> 🆕 **⑧ 第三个 session 的死因相同，但补上了一句"为什么错"（ER `0620/42` Feb/Mar 2020 Q2(a)(ii)）**
> `Many candidates had learnt this definition as it appears in the syllabus and performed well. It was clear that many of those who tried to explain electrolysis did not appreciate that it is a decomposition process whereby a molten or aqueous ionic compound is broken down using electricity. Common errors included omitting the physical state, suggesting 'separation' (a physical change) was occurring or **stating the compound was broken down into 'ions' (the compound already exists as ions)**.`
> ⇒ **官方解释**：写 `breakdown into ions` 之所以错，是因为**化合物里本来就有离子** —— 电解不是"拆出离子"，而是让离子在电极上**放电变成原子/分子**。

> 🆕 **⑨ 连 Core 卷也确认：只写对一半不给分（ER `0620/32` Feb/Mar 2026 Q3(d)(i)；ER `0620/31` Nov 2025 Q7(a)）**
> `A few candidates were able to define the term electrolysis using the two main points in the definition. Some candidates were able to write down one of the points in this definition. … Many of the candidates did not use the terms 'ionic' and either 'electricity' or 'electric current' in their definition.` — `0620/32` Feb/Mar 2026
> `When describing electrolysis, candidates should describe **both** the breaking down of the ionic compound **and** that this is caused by the passage of an electric current. Many candidates gave answers which did not include one or both points.` — `0620/31` Nov 2025（**Core**）
> ⇒ **"两个点"就是 M1 + M2，写一个只有一分。**

> 🆕 **⑩ 第三个 session 的"定义题"死因（ER `0620/41` Nov 2023 Q3(c)(i)）**
> `Candidates struggled with this definition question. Some candidates were able to state, 'by an electric current' or 'by electricity' but very few commented on the 'breaking down of an ionic compound' or 'decomposition of an ionic compound'. More revision is needed on this definition and on all definitions stated in this syllabus.`
> ⇒ **注意这里丢的是 M1**：考生记得住 "electric current"，却忘了 "breaking down"。

> 📌 **把 4 个 session 的失分点合起来看，定义的四个要素各有被单独点名的记录**：
> `breakdown`（w23/41）、`ionic`（s24/41、s24/43、m26/32）、`molten or aqueous`（s24/43、m20/42）、`electricity / electric current`（m26/32、w25/31）。
> **四个都写，就是满分；写三个，就是半分。**

---

## 4.1.2 三个术语：anode / cathode / electrolyte（考纲 Core 2 + 真题自加的 electrolyte 定义）

### English 背这句

**① 电极名称（考纲 Core 2）**

| 术语 | English 定义 | 中文 |
|---|---|---|
| **anode** | the **positive** electrode | 阳极 = 正极 |
| **cathode** | the **negative** electrode | 阴极 = 负极 |
| **electrolyte** | an **ionic compound** which is **molten and/or aqueous**，并且 **conducts electricity / undergoes electrolysis** | 电解质 = 熔融或水溶液状态的离子化合物 |

**② `electrolyte` 的官方 MS 原文（考纲没列，但真题年年考）**
> `M1 ionic compound` / `M2 molten and/or aqueous` — `0620/43` May/June 2023 Q5(a)(i)（2 分）
>
> `M1 ionic compound AND either molten or aqueous(or both)(1)` / `M2 conducts electricity/undergoes electrolysis(1)`
> — `0620/43` Oct/Nov 2021 Q2(a)（2 分）
>
> `electrolyte`（1 分，只要求一个词）— `0620/42` May/June 2021 Q4(a)

**③ 助记（`_research/reference-notes-comparison.md` §5 认可的两种角度）**
```
PANIC      = Positive Anode, Negative Is Cathode      （从"电极名字"角度）
AN OX / RED CAT = Anode OXidation / REDuction at CAThode （从"反应类型"角度）
OIL RIG    = Oxidation Is Loss, Reduction Is Gain (of electrons) （从"电子"角度）
```

### 中文理解

**记忆锚点：两个词都是以 `-ode` 结尾的"路"（hodos = 路）**。`anode` 是**电流流进去的那条路**（正极），`cathode` 是**电流流出来的那条路**（负极）。**在电解池里，阳极接电源正极、阴极接电源负极** —— 这一点与"原电池"不同，别混。

**⚠️ anode/cathode 不是由"氧化/还原"命名的，而是由"正负"命名的**。但碰巧：**阳极永远是氧化反应发生的地方、阴极永远是还原反应发生的地方**（这是电解池的必然结果，因为阳极吸引负离子、阴极吸引正离子）。所以 `PANIC` 和 `AN OX / RED CAT` 两条**同时成立、互不矛盾**。

**`electrolyte` ≠ `electrolysis`** —— 这是两个定义，官方专门考过并且点名批评过混用：
- **electrolysis** 是一个**过程**（breakdown by electricity）
- **electrolyte** 是一个**物质**（an ionic compound, molten or aqueous）

### ⚠️ 陷阱

> **① 把 `electrolyte` 答成 `electrolysis`（`0620/43` Oct/Nov 2021 Extended Q2(a)）**
> `This was answered reasonably well. Candidates occasionally stated the meaning of electrolysis rather than electrolyte. **It is advisable for candidates to start their answer with, 'An electrolyte is a substance....'** The fact that electrolytes contain ions or are ionic substances was omitted on occasions, as was the fact that electrolytes are aqueous or molten.`

> **② 重复题干里已经给的电解信息（`0620/43` May/June 2023 Extended Q5(a)(i)）**
> `Many candidates were unsure of what was required in their definition. **Details about electrolysis were given in the question and did not form part of the required answer.** The best answers referred to an electrolyte as being an ionic compound in molten or aqueous form. Candidates commonly mentioned a liquid or solution. Far fewer candidates were able to identify that an ionic compound was used. Candidates who performed less well gave a poor description of electrolysis or referred to an electrolyte as a type of drink.`
>
> ⇒ **"a liquid or a solution" 不给分** —— 必须点出 **ionic compound**。**"a type of drink"**（把 electrolyte 当运动饮料）是官方记录在案的真实答案。

> **③ 举例子代替定义（`0620/42` May/June 2021 Extended Q4(a)）**
> `The term electrolyte was known by most candidates. Some candidates misinterpreted the question and gave a familiar example of an electrolyte.`
>
> ⇒ **定义题不要举 `sodium chloride solution` 当答案** —— 要写定义的类别（ionic compound + molten/aqueous）。

> **④ 阳极/阴极搞反（MCQ 与 Core 卷）**
> `(ii) Many candidates knew that the positive electrode is called the anode. Common errors were 'cathode', 'cation', 'platinum' or 'graphite'.` — ER `0620/32` March 2023（**Core**）
> 【题目原文不在本语料内（Core 卷未下载），由 ER 反推为 `State the name of the positive electrode`，答案即 `anode`】
>
> `0620/22` May/June 2023（**Extended MCQ**）Q9：`Candidates who performed less well were more likely to confuse the anode and cathode and so suggest option C. Some candidates chose option B, which would be the correct half-equation for a dilute acid or the cation of a reactive metal.` — ER s23
> `0620/21` May/June 2023（**Core MCQ**）Q9：`Few candidates answered this question correctly. Some candidates confused the anode and cathode and chose option A. Almost a third of candidates chose option D.` — ER s23

> 📌 **Extended Paper 4 不单独考"正负号"** —— 题干**永远自带括号注释**，例如
> `at the negative electrode (cathode)`、`the positive electrode (anode)`
> （`0620/41` Nov 2024 Q3(e)、`0620/43` May/June 2023 Q5(c)(i)、`0620/41` May/June 2021 Q3(c)(ii)）。
> **这说明题面会主动消除正负号歧义 —— 失分点不在正负号本身，而在产物归属。**
> 真正的正负号风险只出现在：**Paper 6 画图题**（见 4.1.10）与 **Paper 2 MCQ**。

### 🔧 答题模板

**定义 electrolyte（2 分，照这个句式写）**
```
An electrolyte is an ionic compound which is molten or in aqueous solution,
and which conducts electricity / undergoes electrolysis.
```
- 起手句固定为 `An electrolyte is a substance...` 或 `An electrolyte is an ionic compound...`（官方建议）
- **两个 M 点**：M1 = `ionic compound`；M2 = `molten and/or aqueous`（若题目给 2 分且答案是 w21/43 那种，第二分可能要求 `conducts electricity`）

**定义 anode / cathode（1 分）**
```
anode   = the positive electrode
cathode = the negative electrode
```

---

## 4.1.3 电荷如何通过电解池（考纲 Supplement 8）

### English 背这句

考纲 Supplement 8 的三个要素，在真题里被拆成**三种独立问法**，每一种的官方答案都极短：

| 考纲要素 | 真题问法 | 官方 MS 答案（背英文） | 出处 |
|---|---|---|---|
| **(a) 外电路中电子的移动** | `Name the particle that carries the charge in the wires.` | `electrons` | `0620/41` May/June 2023 Q5(a)(iv)；`0620/43` Oct/Nov 2021 Q2(b)(iv) |
| **(c) 电解液中离子的移动** | `Name the particle responsible for the conductivity of aqueous potassium bromide.` | `ions` | `0620/41` May/June 2023 Q5(a)(v)；`0620/43` Oct/Nov 2021 Q2(b)(iv) |
| **(b/c) 为何熔融物/溶液能导电** | `Explain why lead(II) chloride needs to be molten before it will conduct electricity.` | `mobile ions` | `0620/42` Oct/Nov 2023 Q4(b)(i) |
| 同上（aq CuSO₄） | `State why aqueous copper(II) sulfate conducts electricity.` | `mobile ions` | `0620/41` Oct/Nov 2024 Q3(e)(i) |
| 同上（泛问） | `Why must an ionic compound be molten or in aqueous solution?` | **MS 未逐字给出**；ER 原文是 `ions needed to be mobile`，并说明 `able to move` / `able to flow` 也接受 | `0620/42` Feb/Mar 2022 Q4(d)(ii)（ER，非 MS） |

**"为什么用石墨/铂作电极"的二合一答案（高频，2 分 = 两个 M 点）**
> `M1 conducts electricity` / `M2 inert` — `0620/41` Oct/Nov 2024 Q3(e)(ii)
> 另一元素版本（`0620/42` May/June 2021 Q4(f)）：`platinum`

**完整机制（把三要素串成一段话，用于解释题）**
```
In the external circuit, charge is carried by electrons flowing from the
negative terminal to the cathode (and from the anode back to the positive terminal).
At the electrodes, electrons are gained by positive ions at the cathode (reduction)
and lost by negative ions at the anode (oxidation).
In the electrolyte, charge is carried by the movement of ions:
positive ions move to the cathode, negative ions move to the anode.
```

### 中文理解

**记住一句话：电子只在导线里跑，离子只在溶液里跑，两者在电极表面"交接"。**

```
电源 ──e⁻──→ 阴极(−)    阴极：阳离子 + e⁻ → 原子     （gain of electrons = reduction）
                          ↑
                      电解质内部：离子定向移动（阳离子→阴极，阴离子→阳极）
                          ↓
电源 ←──e⁻──  阳极(+)    阳极：阴离子 → 原子 + e⁻     （loss of electrons = oxidation）
```

**为什么固态离子化合物不导电？** 因为离子被**锁在晶格（lattice）里**，只能振动、不能移动。熔化或溶解后，离子**可以移动（mobile）**了，才能搬运电荷。**所以"molten or aqueous"不是随便加的条件，它是电解定义的物质基础。**

### ⚠️ 陷阱（**这一节是全单元的"概念性错误"高发区**）

> **① 电子"穿过"电解液 —— 最经典的错误（`0620/42` Feb/Mar 2022 Q4(a)(i)）**
> `The more able candidates knew the electrons went along the wire from the more reactive metal, zinc, to the less reactive metal copper but other candidates struggled. **Many had arrows representing electrons flowing through the electrolyte** and some had a pair of arrows pointing in contradictory directions.`

> **② 说"自由电子"负责电解液导电（`0620/42` Feb/Mar 2022 Q4(d)(ii)）**
> `(i) The term 'electrolysis' was almost universally known.`
> `(ii) Better candidates knew that ions needed to be mobile and alternative phrases were allowed such as 'able to move' or 'able to flow'. **Loose wording such as ions 'need to be free' received no credit. Weaker candidates assumed mobile or delocalised electrons were responsible for the passage of current through an electrolyte.**`
>
> ⇒ **`need to be free` 不给分** —— 必须写 **`mobile`**（或 `able to move` / `able to flow`）。

> **③ 两道"粒子是谁"的题，选错率极高（`0620/41` May/June 2023 Extended Q5(a)(iv)(v)）**
> `(iv) This was answered quite well. **Ion** was the most common incorrect answer.`（导线中的粒子 → 答 `electrons`）
> `(v) This was answered less well. **Electron and proton** were the most common incorrect answers.`（aqueous potassium bromide 中的粒子 → 答 `ions`）
>
> **口诀：金属导线 / 石墨电极 = electrons；电解液 = ions。问哪个就答哪个，不要答另一个。**
>
> 同型：`0620/43` Oct/Nov 2021 Q2(b)(iv)：`This was answered quite well. Ion was the most common incorrect answer. Copper was seen occasionally.`（答案 `electron`）

> **④ Paper 2 的同一陷阱（错选项已被官方标出）**
> 干扰项：`B Electrons flow through the electrolyte.` —— **这是错的**
> `0620/21` May/June 2024 Q14（答案 **C**）
>
> MCQ 答案速查：`0620/22` Feb/Mar 2022 Q11（熔融 NaCl 中离子与电子移动方向）答案 **A**；`w22/21` Q10（电极 1 氧化、电极 2 还原：电子与正离子移动方向）答案 **A**；`s25/23` Q10（熔融 PbBr₂ 外电路中负责电荷的粒子）答案 **D**（electrons）；`w25/23` Q14（熔融 PbBr₂ 中电子移动）答案 **A**（`from X to Y through the external wire`）。

> **⑤ "两理由"题只写一个 = 只拿一半（`0620/41` May/June 2023 Extended Q5(a)(ii)）**
> `Many stated that graphite was inert or a conductor of electricity. **Very few made both statements that were required.**`

> **⑥ 石墨/铂题的两条官方"不给分"边界（`0620/43` Oct/Nov 2021 Extended Q2(b)(iii)）**
> `The ability to conduct electricity is among the most important requisite of any material used as an electrode; this was often omitted. Those that referred to conductivity sometimes omitted the term **electrical or electricity**. Some candidates suggested that an electrode should not be able to conduct electricity. Inertness was more commonly stated; **others mentioned low reactivity, which was insufficient to gain credit.**`
>
> ⇒ ❌ `low reactivity`（不够，必须写 `inert`）；❌ 只写 `good conductor`（`0620/41` Oct/Nov 2021 Q3(f)：`A handful of candidates were not specific enough and said it was just a 'good conductor' and some thought that graphite was a metal.`）

> **⑦ 把电极题与铝电解混淆（`0620/41` Oct/Nov 2020 Extended Q5(a)(ii)）**
> `Around half of candidates were able to recognise that the electrodes needed to be inert so that they do not react. Many candidates discussed the movement of ions and **quite a number had confused this with aluminium electrolysis and talked about the electrodes not wearing away.**`

> **⑧ Core 卷的同型错误（原则通用，`0620/32` Feb/Mar 2022 Core Q6(b)(ii)）**
> `(ii) Better performing candidates realised that the electrodes should not react with the electrolyte. Most candidates appeared to guess the property. A wide range of physical properties was seen. Common errors were 'high boiling point', 'conducts heat' or 'strong'. A significant number of candidates did not appear to understand the question and gave answers such as 'negative electrode'.`

> 🆕 **⑨ 2026 年的官方答案表，把"两理由"题的接受与拒绝写到了字级（MS `0620/41` May/June 2026 Q5(a)(ii)；MS `0620/43` May/June 2026 Q5(a)(ii)）**
> `M1 inert(1)` / `M2 good conductor of electricity(1)`
> - ✅ 接受：`not reactive` / `unreactive` / `does not react` / `does not react with the electrolyte` / `does not react with the solution` / `does not react with the products (of electrolysis)` / `does not take part in the reaction`
> - ✅ 接受：`(good) conductor of electricity` / `allows electricity to pass through`（`electric current` 与 `electrical energy` 也可）
> - ❌ **拒绝**：`conductor when molten or aqueous`、`graphite is a metal`
> - ⛔ 忽略（不算错也不给分）：`conductor` 单独写 / `conductive` / `increases conductivity` / `conducts heat` / `carries electric charge` / `carries or conducts current`（必须是 **electrical** current）/ `high melting point` / `high boiling point` / `metal` / 成本 / 强度 / 硬度 / **任何关于导电原因的解释（如 electrons 或 ions）**
> - ⛔ 忽略（M1 侧）：`not very reactive` / `low reactivity` / `quite unreactive` / `does not break down` / `does not corrode`
> - ⚠️ **`Only use CON if more than two answers are given`** —— 写超过两条才判矛盾。
>
> ⇒ **最值钱的两个"拒绝"**：`conducts electricity when molten or aqueous`（那是**离子化合物**导电的条件，不是电极材料的性质！）与 `graphite is a metal`。

> 🆕 **⑩ "离子要 mobile" 这条，2026 年又点名了两次（ER `0620/42` Nov 2024 Q3(c)；ER `0620/41` Nov 2024 Q3(e)(i)）**
> `Candidates continue to show a misunderstanding about conductivity as the majority of candidates referred to electrons. Of those who knew that ions were responsible for conductivity of molten compounds, many candidates omitted the key fact that ions must be mobile for conductivity to occur. **Vague phrases such as 'free ions' or 'delocalised ions' received no credit.**` — `0620/42` Nov 2024
> `Most candidates appreciated that copper(II) sulfate conducts due to mobile ions. **A common error is to refer to 'free' ions** but the reason that copper(II) sulfate conducts is that the ions are able to move. Candidates who performed less well thought that it conducted due to **the movement of electrons**.` — `0620/41` Nov 2024
> ⇒ **`free ions` / `delocalised ions` 一律 0 分；必须 `mobile`。** 这与 F/M 2022 的 `ions 'need to be free' received no credit` 是同一判决，**三年里点名三次**。

> 🆕 **⑪ 熔融物导电的原因，考生总答成"电子"（ER `0620/42` Nov 2023 Q4(b)(i)）**
> `Better performing candidates knew that lead(II) chloride needed to be molten so **ions would become mobile**. **Most candidates incorrectly stated it was electrons that needed to become mobile.**`
> ⇒ 这是唯一一条**同时点名正确答法与错误答法**的导电原因题，是本考点的最佳范例。

> 🆕 **⑫ "电子穿过电解液"的两次新证据（ER `0620/12` Mar 2020 Q9；ER `0620/22` May/June 2024 Q10）**
> `Option B – Candidates did not realise that **ions, and not electrons, transfer charge through the electrolyte.**` — `0620/12` Mar 2020（**Core MCQ**）
> `Many thought that it is electrons rather than ions that move through the electrolyte during electrolysis and chose option A.` — `0620/22` May/June 2024（**Extended MCQ**）
> ⇒ 与 4.1.3 陷阱 ④（`0620/21` May/June 2024 Q14）同一条陷阱，**同期不同卷重复考**。

> 🆕 **⑬ 2026 年"导线里是什么粒子"的给分尺度（MS `0620/41` May/June 2026 Q5(a)(v)）**
> `5(a)(v) electron(s)` / `IGNORE e/e(s)/e(–)/free/delocalised/sea/mobile`
> ⇒ **写 `electrons` 即可**；顺手加的 `free` / `delocalised` / `sea` / `mobile` **既不扣分也不加分**。
> 对比 4.1.6 的电解液版本（MS `0620/43` May/June 2026 Q5(a)(v)）：`ions` —— `A 'cations and anions'/'positive and negative ions'`，但 `I 'cations' (alone)/'anions' (alone)`，且 **`R 'electrons'`**。

> 🆕 **⑭ 惰性电极的"非金属 + 金属"配对问法（MS `0620/42` Feb/Mar 2026 Q3(d)(i)）**
> `3(d)(i) M1 graphite` / `M2 platinum`
> ER 同题（`0620/42` Feb/Mar 2026 Q3(d)(i)）：`Most candidates could name both inert electrodes. … Some candidates **assumed copper to an inert metal electrode**.`
> ⇒ **考纲问法**：`Name a suitable inert non-metal electrode and a suitable inert metal electrode.`
> **答案固定**：非金属 = `graphite`（碳）；金属 = `platinum`。**铜（copper）不是惰性电极** —— 它正是 4.1.7 里会溶解的那个。
> 【同型旧证据：ER `0620/41` Nov 2023 Q3(d) `Candidates did not know the name of another 'inert electrode' as well as the mentioned 'graphite'. Lots of different incorrect answers were seen including more reactive metals such as 'copper' and 'lead'.`】

### 🔧 答题模板

**"为什么用石墨/铂？"（2 分 —— **两条必须都写**）**
```
Graphite / platinum is used because it (1) conducts electricity
and (2) is inert (does not react with the electrolyte / the products).
⚠️ 2026 MS 明确拒绝：`conducts electricity when molten or aqueous`、`graphite is a metal`；
   `high melting point` / `cheap` / `low reactivity` 都不得分。
```

**"为什么必须熔融或溶于水？"（1 分）**
```
Because the ions must be mobile / free to move,
so that they can carry the charge through the electrolyte.
```

**"电荷如何通过？"（3 分 = 三要素各 1 分）**
```
(1) In the wires, electrons carry the charge.
(2) At the electrodes, ions gain or lose electrons.
(3) In the electrolyte, ions move to the electrodes (cations to the cathode,
    anions to the anode).
```

---

## 4.1.4 熔融二元化合物：产物与现象（考纲 Core 3(a) + Core 5）

### English 背这句

**总表（MS 强制要求的答案 —— 全部逐字）**

| 熔融体系 | 阴极 (−) 产物 | 阴极"观察到什么" | 阳极 (+) 产物 | 阳极"观察到什么" | 出处 |
|---|---|---|---|---|---|
| **molten lead(II) bromide** | `lead`（**不是** lead(II) / lead ions） | `silver/grey solid` | `bromine`（**不是** bromide） | `bubbles of orange/brown gas` | `0620/41` Oct/Nov 2021 Q3(e) |
| **molten lead(II) chloride** | —（只考现象） | `(shiny) grey AND solid` | —（只考半方程） | `2Cl⁻ [→] Cl₂ + 2e⁻` | `0620/42` Oct/Nov 2023 Q4(b)(ii)–(iv) |
| **molten potassium chloride** | `potassium` | — | `chlorine` | — | `0620/41` May/June 2021 Q3(c)(ii) |
| **molten potassium bromide** | —— **本语料无 MS 原文，见下【缺口】** | — | —（只考半方程） | `2Br⁻ [→] Br₂ + 2e⁻` | `0620/42` Feb/Mar 2025 Q2(d)(ii) |
| **molten sodium fluoride** | `sodium` | — | `fluorine`（**不是** fluoride） | — | `0620/43` May/June 2021 Q3(d)(i) |
| **molten lithium bromide** | `lithium` | — | `bromine` | — | `0620/43` May/June 2026 Q5(a)(vi) |
| **molten sodium chloride** | `sodium` | — | `chlorine` | — | `0620/42` Feb/Mar 2022 Q4(e)(ii) 等 |
| **molten zinc oxide** | `zinc` | — | `oxygen` | — | `0620/22` May/June 2025 Q10（答案 **C**） |
| **molten nickel(II) chloride** | `Ni[²⁺] + 2e[⁻] [→] Ni` | — | — | — | `0620/21` Oct/Nov 2020 Q14（答案 **D**） |

> ⚠️ **【缺口 · 必须诚实标注】** `0620/42` Feb/Mar 2025 Q2(d)(ii) 只考了**熔融 KBr 的阳极半方程式**；
> **熔融 KBr 的阴极产物在本语料中没有 MS 原文**。本笔记的「熔融」总表中该格留空，**不推测**。
> （说明：`_research/topic4-electrochemistry.md` 的汇总表里，该行阴极写的是 `hydrogen` 并带一个 ❌ 标记，
> 指向的是同题 **(d)(iii) 的稀水溶液**版本的 MS —— `M1 hydrogen / M2 bubbles / M3 oxygen M4 water / M5 bubbles`，
> 那一题的题干是 `dilute aqueous potassium bromide`，**不是熔融物**。两者不可混用。）

**逐条原文（含 `[→]` 重建）**

> **熔融 lead(II) bromide（`0620/41` Oct/Nov 2021 Q3(e)）—— 只给现象、不给产物名**
> 题干：`The electrolysis is repeated using molten lead(II) bromide. Describe what is seen at the: cathode ...... anode. ......` [2]
> MS：`3(e) M1 cathode: silver/grey solid (1)` / `M2 anode: bubbles of orange/brown gas (1)`
> 原文 span（`0620_w21_ms_41.txt` 第 268–270 行）

> **熔融 lead(II) chloride（`0620/42` Oct/Nov 2023 Q4(b)）—— 唯一完整考"半方程 + 氯气检验 + 阴极现象"的熔融题**
> `Q4(b)(i)`：`Explain why lead(II) chloride needs to be molten before it will conduct electricity.` [1]
> MS：`4(b)(i) mobile ions`
> `Q4(b)(ii)`：`Write the ionic half-equation for the reaction occurring at the anode.` [2]
> MS：`4(b)(ii) 2Cl⁻ [→] Cl₂ + 2e⁻` / `M1 any negative Cl species losing electron(s) (1)` / `M2 correct ionic half equation (1)`
> 原文 span（`0620_w23_ms_42.txt` 第 238–242 行）
> `Q4(b)(iii)`：`State the test for chlorine gas.` [2]
> MS：`M1 (damp) litmus (paper) (1)` / `M2 is bleached/goes white (1)`
> `Q4(b)(iv)`：`Describe what is observed at the cathode.` [1]
> MS：`(shiny) grey AND solid`
> 原文 span（`0620_w23_ms_42.txt` 第 245 行）：`4biv (shiny) grey AND solid`

### 中文理解

**熔融体系比水溶液体系简单得多 —— 因为里面没有水，就没有 H⁺ 和 OH⁻ 来"抢"电极。**

```
熔融二元化合物 → 只有两种离子 → 产物必然是"一种金属 + 一种非金属"
                阴极(−)吸引阳离子 → 金属     ← 考纲 Core 4
                阳极(+)吸引阴离子 → 非金属   ← 考纲 Core 4
```

**两条铁律**（考纲 Core 4 + Core 5 的合并表述）：
1. **metals or hydrogen are formed at the cathode** —— 但在**熔融**体系里，只可能是 **metal**（因为根本没有氢元素）
2. **non-metals (other than hydrogen) are formed at the anode** —— 熔融体系里就是 Cl₂ / Br₂ / I₂ / O₂ / F₂

**"熔融 KCl 里只有 K 和 Cl 两种元素"是考官的官方论证** —— 见下方 ER 原文。**这意味着：只要题目说了 molten，任何含 H 或 O 的答案（hydrogen、oxygen、水）都自动作废。**

> 📌 **命名铁律：产物写"元素名"，不写"离子名"**（详见 4.1.9 陷阱 ①）
> - ✅ `chlorine` / `bromine` / `fluorine` / `iodine`（元素）
> - ❌ `chloride` / `bromide` / `fluoride` / `iodide`（离子）—— **一分不给**

### ⚠️ 陷阱

> **① 熔融题里答 hydrogen / oxygen —— 考官连年点名（头号错误）**
> `Many candidates did not heed the statement about the lead bromide being molten and suggested oxygen or hydrogen forming at either electrode.` — ER `0620/41` Oct/Nov 2021
> `A considerable number of candidates did not read the word molten in the stem of the question and suggested that hydrogen is formed at one of the electrodes.` — ER `0620/32` March 2023（**Core**）
> `A few candidates misread the question and thought that the electrolysis was in aqueous solution and so used hydrogen as one of their answers.` — ER `0620/32` March 2024（**Core**）
>
> ⇒ **做任何电解题，第一件事是圈出题干里的 `molten` 或 `aqueous`。** 这个词决定整题的答案。

> **② "写产物不写现象"的完整黑名单（`0620/41` Oct/Nov 2021 Extended Q3(e)）**
> `Many of the answers ignored the instruction to give observations. The candidates could identify the correct products but did not state what would be observed.`
> `The following non-creditworthy statements were commonly seen:`
> `[·] bromine forms`
> `[·] silver metal`
> `[·] lead forms`
> `[·] bromine gas`
> `[·] solid lead`
> `[·] bromine bubbles.`

> **③ "a gas is formed" 不给分 —— 官方原话的经典表述（`0620/31` March 2021 Core Q7(c)）**
> `Carbon dioxide was also a common error for the products at the positive electrode. Few candidates gave suitable observations at the electrodes. A common error at the negative electrode was to suggest 'sodium particles form'. A common error at the positive electrode was to suggest 'white precipitate'. **'A gas is formed' was not credited because this is not considered an observation.** Correct observations included 'bubbles are seen at the negative electrode' or 'a green gas is formed at the positive electrode'. A few candidates wrote about electron loss or gain rather than giving observations.`
>
> 【注：这条是 Core Paper 3，但**原则直接适用于 Extended**。同卷 (b)(ii)：`Some candidates identified the anode correctly. Others either labelled the cathode (shown as the wall of the cell), the wires attached to the power supply or the hood over the anode.`】

> **④ 同一化合物、不同状态 → 产物不同（`0620/43` May/June 2021 Extended Q3(c)(ii)）**
> `Candidates were often unaware of the potential for different products when electrolysis was performed on the same ionic compound in different physical states. It was not uncommon for the same products to be suggested in both (c)(ii) and (d)(i).`
>
> ⇒ **这是本节的核心考点**：稀 NaF 阳极 = `oxygen`（有水）；熔融 NaF 阳极 = `fluorine`（无水）。**NaCl 同理：稀 → O₂；浓 → Cl₂；熔融 → Cl₂ 且阴极变 sodium。**

> **⑤ 离子名 vs 元素名（熔融 KCl，`0620/41` May/June 2021 Extended Q3(c)(ii)）**
> `Candidates should be aware that molten potassium chloride only contains the elements potassium and chlorine. Thus potassium and chlorine are the only possible products of electrolysis of molten potassium chloride. **Some candidates gave equations despite being asked for names of the products.** The products at the anode and cathode were occasionally reversed. Common incorrect answers included potassium ions, chloride ions, chloride (as opposed to chlorine), K+, Cl and Cl [–].`

> **⑥ `'Fluoride' rather than elemental fluorine`（`0620/43` May/June 2021 Extended Q3(d)(i)）**
> `'Fluoride' rather than elemental fluorine was a common error for the product at the anode.`

> 🆕 **⑦ 熔融 PbCl₂ 的完整 ER —— 四问逐条点评（ER `0620/42` Nov 2023 Q4(b)）**
> `(b)(i) Better performing candidates knew that lead(II) chloride needed to be molten so ions would become mobile. Most candidates incorrectly stated it was electrons that needed to become mobile.`
> `(b)(ii) Candidates need to learn that during electrolysis **negative ions are attracted to the anode** and upon reaching the anode, **they lose electrons**. This would have helped them to write the ionic half-equation.`
> `(b)(iii) The test for chlorine gas was not very well known. Random gas tests were given e.g. 'glowing splint' and 'relights a splint'. Another common error was to add silver nitrate – an obvious confusion with the chloride ion test.`
> `(b)(iv) Candidates struggled to understand that 'Describe what is observed...' essentially means 'What would you see...'. Descriptions such as these **need a colour (in this case grey) and a state**. Thus, answers such as 'lead forms' did not receive credit, neither did 'solid forms' nor 'lead is deposited'.`
>
> ⇒ **本笔记最有用的一条判分解释**：现象题 ="**颜色 + 状态**"两件套。
> ⇒ **新的不给分清单**：`lead forms` / `solid forms` / `lead is deposited`。
> ⇒ **氯气检验的新错误**：`glowing splint` / `relights a splint`（那是**氧气/氢气**的检验）；`silver nitrate`（那是**氯离子**的检验）。

> 🆕 **⑧ 熔融 KCl 的 ER：产物写错、正负颠倒、还写了方程（ER `0620/41` Nov 2023 Q3(c)(ii)）**
> `This question was answered poorly. Many candidates got the products mixed up or incorrectly thought that 'chloride' was given off instead of 'chlorine'. … There were only a few candidates that knew the observations at the positive electrode. **More practice is needed to predict the products of the electrolysis of molten compounds.**`
> ⇒ 与 2021 年那次（§陷阱⑤）**点名的是同一批错误**：`chloride`≠`chlorine`、两极颠倒、以及"熔融物的预测需要多练"。
> ER `0620/41` Nov 2023 Q3(d) 同题还考了另一个惰性电极：`Candidates did not know the name of another 'inert electrode' as well as the mentioned 'graphite'. Lots of different incorrect answers were seen including more reactive metals such as 'copper' and 'lead'.`

> 🆕 **⑨ 熔融 LiBr：Core 5 的 2026 年版本（MS `0620/43` May/June 2026 Q5(a)(vi)）**
> `M1 at anode: bromine` / `M2 at cathode: lithium`　`Names take precedence, I incorrect formulas R incorrect name`
> ⇒ **注意 `R incorrect name`** —— 名字写错就整个不给分（即使公式对）。这是"**熔融题只考元素名**"这条规则的最新判分口径。

### 🔧 答题模板：熔融二元化合物"两步判断法"

```
第 1 步：看化合物的组成 —— 它只有两种元素（金属 + 非金属）
第 2 步：阴极 = 金属名；阳极 = 非金属名（写元素名，不写离子名）

答案格式（题目问 "product"）：   cathode: potassium     anode: chlorine
答案格式（题目问 "what is seen"）：cathode: silver/grey solid   anode: bubbles of orange/brown gas
```

**"描述现象"题的官方给分词汇表（背下来，直接抄）**

| 给分 ✅ | 不给分 ❌ |
|---|---|
| `silver/grey solid`、`(shiny) grey AND solid`、`pink AND solid` | `lead forms`、`solid lead`、`silver metal`、`copper is formed` |
| `bubbles of orange/brown gas`、`green gas`、`bubbles of colourless gas`、`colourless bubbles` | `bromine forms`、`bromine gas`、`bromine bubbles`、`a gas is formed`、`gas given off` |
| `fizzing`、`effervescence`、`bubbles` | `gas is produced`、`the electrode gets bigger`（那是结论，不是现象） |

> 📌 **官方 Key message（`0620/41` Oct/Nov 2021）**
> `Candidates are advised that if a question asks for either observations or a description of what would be seen, then the answer must relate to what is seen, e.g.`
> `- solids dissolving or disappearing`
> `- colours of gases`
> `- colours and state of products of electrolysis.`

---

## 4.1.5 稀硫酸的电解（考纲 Core 3(c)）

### English 背这句

> **`0620/41` Oct/Nov 2020 Q5(a)(iii)**
> MS：阴极 `hydrogen (gas)` / 阳极 `oxygen (gas)`
>
> **`0620/42` Oct/Nov 2025 Q4(a)(vi)**：`Name the two gaseous products formed during the electrolysis of dilute sulfuric acid.` [2]
> 🆕 **该题的 ER 现已找到**（ER `0620/42` Nov 2025 Q4(a)(vi)）：`The majority of candidates named the two products. Weaker responses identified hydrogen but put **sulfur dioxide rather than oxygen**.`
> ⇒ **`sulfur dioxide` 是稀硫酸题的第一号错答** —— 这已经是第三个 session 点名它了（见 4.1.5 陷阱④⑤）。

**两个半方程式（与其他含氧酸/水溶液体系通用）**
```
阴极 (−)：2H[⁺] + 2e[⁻] [→] H[₂]
阳极 (+)：4OH[⁻] [→] 2H[₂]O + O[₂] + 4e[⁻]
```

### 中文理解

稀硫酸里有三种离子：`H⁺`、`SO₄²⁻`、以及水自身电离出的极少量 `OH⁻`。

- **阴极**：`H⁺` 比 `SO₄²⁻` 容易得多地被还原 → **hydrogen**
- **阳极**：`SO₄²⁻` 是"含氧酸根"，**极难被氧化**；真正放电的是水里的 `OH⁻` → **oxygen**（同时生成水）
- **净结果**：电解水（`2H₂O → 2H₂ + O₂`），硫酸本身只提供导电离子，不被消耗

> 📌 **关键概念**：**含氧酸根（SO₄²⁻、NO₃⁻）和水中 OH⁻ 竞争时，永远是 OH⁻ 放电。**
> 所以"稀酸 / 稀盐溶液"的阳极产物几乎总是 `oxygen` —— 这是判断阳极产物的**默认答案**。

### ⚠️ 陷阱

> **① `H` 代替 `H₂`（`0620/41` Oct/Nov 2020 Extended Q5(a)(iv)）**
> `The candidates that had correctly identified hydrogen at the negative electrode were generally able to write an accurate ionic half-equation for the formation of hydrogen. Generally, those candidates who had not correctly identified hydrogen often attempted to write an ionic half-equation for the formation of hydrogen with the most common error being to form H rather than H2. **Many candidates attempted to write an equation for the formation of sulfate ions.**`
>
> ⇒ ❌ `H`；❌ 给硫酸根写方程（硫酸根根本不放电）。

> **② 氢离子电荷写错（`0620/41` May/June 2023 Extended Q5(a)(iii)）**
> `This was answered reasonably well. Common errors included the wrong charge on the hydrogen ion and the formula of hydrogen written as H.`

> **③ Paper 2 的同一考点反复失分（ER `0620/12` Feb/Mar 2025 Core Q12）**
> `The electrolysis products of dilute sulfuric acid were not well recalled. Option C was the most common incorrect answer. Of those candidates who recalled the correct products, most assigned them to the correct electrode. Few chose option B.`

> 🆕 **④ 稀硫酸题"答非所问"的官方描述 —— 考生答的是电极名和离子名（ER `0620/31` Nov 2024 Q7(b)(i)）**
> `Few candidates recalled the products of the electrolysis of dilute sulfuric acid. Many candidates were unclear what the question required and **either gave the name of the electrodes (anode and cathode) or the ions attracted to that electrode (anion and cation) rather than the chemical products.** Those that gave a correct answer tended to recall the production of hydrogen, but **few recalled the formation of oxygen, with sulfur or sulfur dioxide being common incorrect answers.**`
> ⇒ **新的不给分清单**：`sulfur` / `sulfur dioxide`（很多人以为硫酸被电解会出硫！）；以及**答电极名（anode/cathode）、答离子名（anion/cation）**。
> 同卷 (b)(ii)：`Most candidates identified **platinum** as the substance used to make an inert electrode.`

> 🆕 **⑤ 又一个 session 的同一黑名单（ER `0620/31` Nov 2025 Q7(c)）**
> `When sulfuric acid is electrolysed, hydrogen and oxygen are produced. Some candidates suggested that the gas was **sulfur dioxide or solid sulfur**. Many appeared to be guessing and gave answers such as **'copper' or 'chlorine'**.`
> ⇒ **`sulfur dioxide` / `solid sulfur` / `copper` / `chlorine` 全不给分。** 同一错误在两个 session 里各被点名一次。

> 🆕 **⑥ Core MCQ 里也不好（ER `0620/12` Nov 2025 Q13）**
> `The gaseous products of the electrolysis of dilute sulfuric acid were not well known. More than half of the candidates assumed that one of the gases was brown and chose Distractor A or D.`

> 🆕 **⑦ Paper 3 的"画图收集气体"版本（ER `0620/32` Mar 2020 Q7(a)(i)(ii)，**Core**）**
> `(i) Few candidates showed test-tubes over each electrode for collecting gases. Many of those who suggested a method of gas collection drew a funnel over the whole beaker or showed gas syringes above each electrode. Other common errors included: **drawing wires going through the electrolyte; reversing the anode and cathode** and labelling the anode of the power pack or cell rather than the anode of the electrolysis cell.`
> `(ii) A minority of the candidates gained full credit. The commonest errors were to suggest **sulfur or sulfate at either electrode** or **oxygen at the negative electrode**. The commonest correct answer was hydrogen at the negative electrode.`
> ⇒ **判分原则通用**：气体收集管要**分别套在两个电极上**；导线**不能画穿电解液**。

**MCQ 答案速查（稀硫酸）**
| 卷/题 | 题干要点 | 答案 |
|---|---|---|
| `0620/21` Feb/Mar 2021 Q12 | 稀硫酸阴极半方程 | **C**（`2H[⁺] + 2e[⁻] [→] H[₂]`） |
| `0620/22` May/June 2025 Q14 | 稀硫酸两电极半方程 | **C** |

### 🔧 答题模板

**"稀硫酸电解的产物是什么？"（2 分）**
```
Anode (+): oxygen        Cathode (−): hydrogen
（若题目要方程）2H[⁺] + 2e[⁻] [→] H[₂]  和  4OH[⁻] [→] 2H[₂]O + O[₂] + 4e[⁻]
```

---

## 4.1.6 稀卤化物 vs 浓卤化物（考纲 Core 3(b) + Supplement 10）—— **本单元"最硬"的一条分界线**

### English 背这句

**总表（MS 强制要求的答案 —— 全部逐字）**

| 电解体系 | 阴极 (−) 产物 | 阴极"观察到什么" | 阳极 (+) 产物 | 阳极"观察到什么" | 出处 |
|---|---|---|---|---|---|
| **浓 aqueous sodium chloride** | `hydrogen` | `fizzing`（也接受 effervescence / bubbles） | `chlorine` | **`green gas`**（**不接受 effervescence！**） | `0620/42` May/June 2021 Q4(e)(i) |
| **稀 aqueous sodium chloride** | `hydrogen` | `fizzing` | `oxygen` | — | `0620/42` May/June 2021 Q4(c) |
| **稀 aqueous potassium bromide** | `hydrogen` | `bubbles` | **`oxygen` AND `water`**（两个都要写） | `bubbles` | `0620/42` Feb/Mar 2025 Q2(d)(iii) |
| **稀 aqueous sodium fluoride** | `hydrogen` | — | `oxygen` | — | `0620/43` May/June 2021 Q3(c)(ii) |
| **稀 aqueous potassium chloride** | `hydrogen` | — | `oxygen` | — | `0620/41` May/June 2024 Q3(c) |
| **浓 aqueous sodium bromide** | `hydrogen` | `colourless bubbles` | `bromine` | `orange/brown/yellow liquid` | `0620/43` Oct/Nov 2021 Q2(b)(i) |
| **浓 aqueous potassium iodide** | `hydrogen` | `bubbles of colourless gas` | `iodine` | `brown solution OR black solid` | `0620/43` Oct/Nov 2024 Q2(b)(i) |
| **浓 hydrochloric acid** | `effervescence (of colourless gas)` | 同左 | `2Cl⁻ [→] Cl₂ + 2e⁻`（只考半方程） | — | `0620/41` Oct/Nov 2021 Q3(a)(i),(b) |

> 🆕 **2026 年新增的"三种形态对照表"题（MS `0620/42` Feb/Mar 2026 Q3(d)(ii)）—— 这道题把 4.1.4 与 4.1.6 的分界线一次考全**
> 题干：`Complete Table 3.1 to show the name of the product formed at the cathode during the electrolysis of different forms of sodium chloride.`
>
> | form of sodium chloride | name of product formed at the cathode |
> |---|---|
> | molten | **`sodium`** |
> | dilute aqueous solution | **`hydrogen`** |
> | concentrated aqueous solution | **`hydrogen`** |
>
> MS：`3(d)(ii) M1 sodium` / `M2 hydrogen` / `M3 hydrogen`
> ⇒ **同一个化合物、同一个电极，三种形态给出两个不同答案。** 这就是考纲 Core 5（熔融）与 Supp 10（稀/浓水溶液）的**分水岭本身**。
> ER 同题（`0620/42` Feb/Mar 2026 Q3(d)(ii)）：`Most candidates named product at the cathode for all three forms of NaCl.`
> `Limited responses: Some candidates **named the ions that migrated to the cathode** or named **products formed at the anode**.`
> ⇒ **两个新错法**：把"迁过去的离子"（Na⁺ / H⁺）当产物；以及**把阳极的产物写到阴极那一栏**。

**逐条原文（含 `[→]` 重建）**

> **稀 + 浓 aqueous sodium chloride（`0620/42` May/June 2021 Q4）—— 全语料唯一把"稀/浓对照"整套考全的题**
> `Q4(b)(i)`：`Complete the ionic half-equation for this reaction.` `..........OH⁻(aq)  ........................... + O2(g) + 4e⁻` [2]
> MS：`4(b)(i) 4OH[⁻] [→] 2H[₂]O + O[₂] + 4e[⁻]` / `balance of charge (1)` / `rest of equation (1)`
> 原文 span（`0620_s21_ms_42.txt` 第 218–220 行）：`4(b)(i) 4OH  2H2O + O2 + 4e` / `balance of charge (1)` / `rest of equation (1)`
>
> `Q4(b)(ii)`：`Explain how the ionic half-equation shows the hydroxide ions are being oxidised.` [1]
> MS：`4(b)(ii) (OH[⁻](aq) ions) lose electrons`
>
> `Q4(c)`：`Describe what the student observes at the cathode.` [1] → MS：`4(c) fizzing`
> `Q4(d)`：`Write the ionic half-equation for the reaction at the cathode.` [2]
> MS：`4(d) 2H[⁺] + 2e[⁻] [→] H[₂]` / `species correct (1)` / `fully correct equation (1)`
>
> `Q4(e)(i)`：`Describe what the student observes at:` `the cathode ......` `the anode. ......` [2]
> MS：`4(e)(i) fizzing (1)` / `green gas (1)`
> 原文 span（`0620_s21_ms_42.txt` 第 232–233 行）
>
> `Q4(e)(ii)`：`The student added litmus to the solution after the electrolysis of concentrated aqueous sodium chloride. State the colour seen in the solution. Give a reason for your answer.`
> MS：`4(e)(ii) (litmus turns) blue and alkali/base forms (1)` / `Sodium hydroxide/NaOH (forming) (1)`

> **稀 aqueous potassium bromide（`0620/42` Feb/Mar 2025 Q2(d)(iii)）—— 唯一要求"产物 + 现象"同时写全的 5 分题**
> 题干：`Name the products and state the observations at the negative and positive electrodes when dilute aqueous potassium bromide, KBr, is decomposed by the passage of an electric current.`
> `product at the negative electrode ...` `observations at the negative electrode ...`
> `products at the positive electrode ... and ...` `observations at the positive electrode ...` [5]
> MS：`M1 hydrogen` / `M2 bubbles` / `M3 oxygen M4 water` / `M5 bubbles`
> 原文 span（`0620_m25_ms_42.txt` 第 166–169 行）：`2(d)(iii) M1 hydrogen / M2 bubbles / M3 oxygen M4 water / M5 bubbles`
>
> ⚠️ **注意 M4 = `water`**。**稀卤化物溶液的阳极必须写 `oxygen` 和 `water` 两个产物**（因为方程是 `4OH⁻ → 2H₂O + O₂ + 4e⁻`），**写 `bromine` 不给分。**
>
> ⚠️ **【以 MS 为准的一处 ER 疑似笔误】** 该题 ER 原文写 `Some candidates did not know that oxygen is a product at the negative electrode, and candidates frequently gave bromine rather than water as a product.` —— **`at the negative electrode` 与 MS 直接矛盾**（MS 里 `M3 oxygen M4 water` 配的是**正极**的现象 M5 bubbles）。research 文件已判定 ER 此处应为 `positive electrode` 的笔误，**笔记以 MS 为准**。

> **"产物 + 现象"表格题（Paper 4 独有题型，出现 2 次，题干格式完全相同）**
> `Complete the table to show the observations and products of electrolysis.`
> MS（`0620/43` Oct/Nov 2021 Q2(b)(i)）：`M1 oxygen (1)` / `M2 pink/brown solid (1)` / `M3 copper (1)` / `M4 orange/brown/yellow liquid (1)` / `M5 bromine (1)`
> 原文 span（`0620_w21_ms_43.txt` 第 148–156 行）
> MS（`0620/43` Oct/Nov 2024 Q2(b)(i)）：`M1 brown solution OR black solid` / `M2 iodine` / `M3 hydrogen` / `M4 copper`
> 原文 span（`0620_w24_ms_43.txt` 第 153–159 行）

### 中文理解

**阳极产物只有两种可能，判据只有一个词：稀还是浓。**

```
阳极 (+) 放电粒子怎么选？
   ① 溶液中有"浓的"卤离子（Cl⁻ / Br⁻ / I⁻）？
        有 → 卤素单质：Cl₂ / Br₂ / I₂
        没有（稀溶液 / 无卤离子）→ 水中的 OH⁻ 放电 → O₂（+ H₂O）

阴极 (−) 产物怎么选？
   ① 溶液中的金属离子是"排在氢后面"的（如 Cu²⁺、Ag⁺）？
        是 → 金属
        不是（Na⁺ / K⁺ / Ca²⁺ / Mg²⁺ / Al³⁺ 等活泼金属离子）→ 水中的 H⁺ 放电 → H₂
```

**为什么"活泼金属的水溶液永远得不到金属"？** 因为 Na⁺ 比 H⁺ 难还原得多 —— 水分子里的 H⁺ 抢先拿到电子，放出氢气。**所以浓/稀 aq NaCl 的阴极永远都是 `hydrogen`，绝不会是 sodium。**

**为什么"浓"才出卤素？** 浓溶液里卤离子浓度高，它们挤到阳极表面的机会压过了 OH⁻。**稀溶液里卤离子太少，OH⁻ 抢赢了** —— 这就是考官说的 `The syllabus makes a distinction between dilute and concentrated aqueous halide solutions as electrolytes.`

> 📌 **一条"隐藏结论"别忘了**：浓 NaCl 电解一段时间后，**溶液中会生成 NaOH**，所以溶液显碱性、石蕊变蓝。
> MS：`4(e)(ii) (litmus turns) blue and alkali/base forms (1)` / `Sodium hydroxide/NaOH (forming) (1)`
> 原因：阴极消耗 H⁺ 放出 H₂，剩下的 OH⁻ 与 Na⁺ 组成 NaOH。

### ⚠️ 陷阱

> **① 稀卤化物答 `bromine` 而不是 `oxygen` —— 考纲明文分界（`0620/41` May/June 2023 Extended Q5(a)(vi)）**
> `The syllabus makes a distinction between dilute and concentrated aqueous halide solutions as electrolytes. Therefore oxygen, as opposed to bromine, is the anode product when the electrolyte is dilute aqueous potassium bromide.`
> `Potassium was occasionally seen as the cathode product.`
>
> ⇒ **两个错误一次点名**：阳极写 `bromine`（错）、阴极写 `potassium`（错）。

> **② 浓 NaCl 阳极写 `effervescence` 不给分（`0620/42` May/June 2021 Extended Q4(e)(i)）**
> `Most candidates knew that concentrated aqueous sodium chloride produced the same cathodic product as dilute aqueous sodium chloride and wrote effervescence or fizzing. **Weaker responses suggested that sodium would be formed within this aqueous system.**`
> `Candidates had been told earlier in the question that oxygen is produced at the anode during electrolysis of dilute aqueous sodium chloride so **'effervescence' was not accepted as a suitable answer. Better performing candidates were able to state that a green gas was seen.**`
>
> ⇒ **`effervescence` 是"无色气体"的描述，chlorine 是黄绿色气体，所以要写 `green gas`。**（这段是官方判分的推理链，值得记住。）

> **③ "gas given off / gas formed" 也算结论、不算现象（`0620/42` May/June 2021 Extended Q4(c)）**
> `Most candidates correctly suggested effervescence would be seen. **No credit was awarded for 'gas given off' or 'gas formed' as this is a conclusion made by observing the effervescence which takes place.**`

> **④ `H` 而不是 `H₂`（`0620/43` Oct/Nov 2021 Extended Q2(b)(ii)）**
> `This straightforward question was poorly answered. **H[–] was occasionally seen rather than H[+], as was H rather than H2.** The equation was sometimes unbalanced.`

> **⑤ 稀/浓混淆是 Paper 2 的高频错因（ER 原文）**
> `0620/22` May/June 2023（Extended MCQ）Q10：`Most candidates confused the electrolysis of dilute halide solutions with concentrated solutions and chose option B.`
> `0620/22` Feb/Mar 2021（Extended MCQ）Q12：`This question was the least well answered on this paper. Nearly all candidates recognised that dilute hydrochloric acid could be electrolysed to produce hydrogen. Few recalled the electrolysis products of concentrated aqueous sodium chloride. Option C and option B were more likely to be suggested as answers.`
> `0620/43` Oct/Nov 2021 Q2(b)(iii)（电极材料题，同题）：`Inertness was more commonly stated; others mentioned low reactivity, which was insufficient to gain credit.`

> **⑥ 水溶液题里写 `sodium` / `lithium` / `bromide` 的 Core 卷同型（原则通用）**
> `0620/32` Feb/Mar 2022（Core）Q6(c)(iii)：`A minority of the candidates related the correct electrode products to the correct electrode. Others gave the correct products at the incorrect electrodes. **The commonest errors were to suggest 'chloride' or 'chloride ions' instead of 'chlorine' or 'lithium ions' instead of lithium.** A significant number of candidates thought that an aqueous solution of lithium chloride was being electrolysed and suggested 'hydrogen' as one of the products. Others did not give the name of a product and wrote comments such as 'to plate the electrode' or 'a gas is released'.`
> `0620/32` Feb/Mar 2024（Core）：`This question discriminated well between candidates. Many candidates could correctly name the product formed at each electrode. **Some candidates confused 'bromide' with the correct 'bromine'.** A few candidates misread the question and thought that the electrolysis was in aqueous solution and so used hydrogen as one of their answers.`

> 🆕 **⑦ "稀/浓混淆"在四个 session 的 MCQ 里被反复点名**
> `The difference between reaction products when electrolysing **molten rather than aqueous** electrolytes was often not well recalled.` — `0620/12` Nov 2023 Q11（**Core MCQ**）
> `The products of the electrolysis of **molten and aqueous salts** were confused by many of the candidates who performed less well overall.` — `0620/22` Nov 2023 Q10（**Extended MCQ**）
> `Some candidates may have been confused by the terms 'anode' and 'cathode'. **When answering questions about electrolysis candidates should note whether the electrodes used are inert to help determine expected observations.**` — `0620/23` Nov 2023 Q12（**Extended MCQ**）
> `Candidates who performed less well overall were more likely to **confuse the positive and negative electrodes**.` — `0620/23` Nov 2023 Q11（**Extended MCQ**）
> ⇒ 最后一条是**考官给的操作建议**：先看电极是不是惰性，再判断现象。

> 🆕 **⑧ 稀 KCl 的 O₂ 半方程，考生给了"熔融氧化物"的版本（ER `0620/43` May/June 2024 Q3(c)(ii)）**
> `Candidates found this question very challenging. The majority gave the ionic half-equation for the production of oxygen from **oxide ions** that would occur in a **molten** electrolyte containing oxide ions. Very few identified that **hydroxide ions lose electrons at the anode in the electrolysis of dilute aqueous potassium chloride**.`
> ⇒ **`2O[²⁻] → O[2] + 4e[–]` 是错的**（那是熔融氧化物的式子）；稀水溶液里必须是 `4OH[–] → 2H[2]O + O[2] + 4e[–]`。
> **这条错误与 4.1.7 的 `O[²⁻]` 错误是同一个**（见 w24/41 Q3(e)(v)）。

> 🆕 **⑨ 浓缩版的两个新证据（ER `0620/33` May/June 2024 Q3(b)(i)；ER `0620/32` Nov 2025 Q7(c)）**
> `a lot of candidates could name the product formed at each electrode but some did get **'chloride' confused with the correct 'chlorine'**. A few candidates mentioned incorrectly that **ions were being formed at the electrodes**.` — `0620/33` May/June 2024（**Core**）
> `Most candidates confused the electrodes and suggested **magnesium** as the product. A small number suggested **chloride rather than chlorine**.` — `0620/32` Nov 2025（**Core**）
> ⇒ **"ions were being formed at the electrodes" 是新的错法**：产物是**中性的原子/分子**，不是离子（与 4.1.9 同一条原则）。
> ⇒ `magnesium as the product` = 又一起"水溶液里指望活泼金属析出"的错误。

> 🆕 **⑩ 2026 年"浓 aq LiBr"的官方答案（MS `0620/43` May/June 2026 Q5(a)）**
> `5(a)(i) electrolyte`（`I 'molten'/'solution'/'aqueous'`）—— 又一次考"电解质"定义，**注意 1 分的答案只要一个词**。
> `5(a)(iii) 2Br[–] [→] Br[2] + 2e[–]` —— 浓卤化物的阳极半方程，**M1 `any negative Br species losing electron(s)` / M2 `correct ionic half equation`**。
> `5(a)(v) ions`（`R 'electrons'`）
> `5(a)(vi) M1 at anode: bromine` / `M2 at cathode: lithium`（熔融 LiBr —— 见 4.1.4）
> ⇒ 一道题同时考了 4.1.6（浓卤化物）+ 4.1.4（熔融）+ 4.1.3（粒子）+ 4.1.8（半方程）**四块内容**。

**MCQ 答案速查（稀 / 浓 / 熔融 的对照 —— 全部逐题核出）**

| 卷/题 | 题干要点 | 答案 |
|---|---|---|
| `0620/22` Feb/Mar 2020 Q10 | 熔融 PbBr₂，哪两条陈述对（2 & 3） | **C** |
| `0620/22` Feb/Mar 2022 Q11 | 熔融 NaCl 中离子与电子的移动方向 | **A** |
| `0620/22` Feb/Mar 2022 Q13 | 熔融 NaCl vs 浓 aq NaCl 的阴极产物 | **C**（sodium / hydrogen） |
| `0620/22` Feb/Mar 2023 Q10 | 只有 H₂ 和 O₂ 生成，电解质是什么 | **C**（稀 aq NaCl） |
| `0620/22` Feb/Mar 2024 Q11 | 浓 aq NaCl vs 稀硫酸，阴极分别是什么 | **B**（hydrogen / hydrogen） |
| `0620/22` Feb/Mar 2024 Q12 | 四种电解质的阴极反应 + 阳极产物 | **A**（1 and 2） |
| `0620/22` Feb/Mar 2025 Q13 | 三种溶液哪个阳极出淡黄绿色气体 | **A**（L and M） |
| `0620/23` May/June 2020 Q10 | 稀 aq NaCl 阳极/阴极反应行 | **D** |
| `0620/21` May/June 2022 Q10 | 浓盐酸 vs 浓 aq NaCl，四支电极 | **D** |
| `0620/22` May/June 2022 Q10 | 同上（浓盐酸 vs 浓 aq NaCl） | **D** |
| `0620/23` May/June 2022 Q10 | 同上 | **D** |
| `0620/22` May/June 2023 Q10 | 浓 aq NaCl **不**产生什么 | **C**（sodium） |
| `0620/23` May/June 2023 Q10 | 稀 aq NaBr 阴极/阳极产物 | **C** |
| `0620/23` May/June 2024 Q10 | 浓 aq KBr 惰性电极产物 | **A**（anode bromine / cathode hydrogen） |
| `0620/22` May/June 2025 Q10 | 熔融 ZnO 两电极产物 | **C**（anode oxygen / cathode zinc） |
| `0620/23` May/June 2025 Q10 | 熔融 PbBr₂ 外电路中负责电荷的粒子 | **D**（electrons） |
| `0620/21` May/June 2025 Q11 | 浓 aq NaCl 阳极半方程 | **B**（`2Cl[⁻] [→] Cl[₂] + 2e[⁻]`） |
| `0620/22` Oct/Nov 2020 Q12 | 浓 aq NaCl 加通用指示剂，颜色怎么变 | **A**（blue → green） |
| `0620/23` Oct/Nov 2020 Q13 | 稀 aq KBr 阳极/阴极产物 | **A** |
| `0620/21` Oct/Nov 2021 Q10 | 三条关于电解产物的陈述 | **C** |
| `0620/23` Oct/Nov 2021 Q10 | 浓 aq NaCl 阴极元素 | **B**（hydrogen） |
| `0620/22` Oct/Nov 2022 Q10 | 浓 aq NaCl vs 熔融 NaCl 双电池 | **B** |
| `0620/22` Oct/Nov 2023 Q10 | 稀 aq NaCl 阳极/阴极反应行 | **D** |
| `0620/23` Oct/Nov 2023 Q13 | 浓 aq NaCl 初始产物（阴极/阳极） | **A**（hydrogen / chlorine） |
| `0620/22` Oct/Nov 2024 Q13 | 熔融 NaCl 两电极产物 | **D** |
| `0620/23` Oct/Nov 2024 Q11 | 两种物质电解都产氢 + 哪个电极产氢 | **D** |
| `0620/21` Oct/Nov 2025 Q13 | 稀 aq NaCl 阳极/阴极反应行 | **D** |
| `0620/23` Oct/Nov 2025 Q13 | 浓 aq NaCl 初始产物（阴极/阳极） | **A**（hydrogen / chlorine） |
| `0620/23` Oct/Nov 2025 Q14 | 熔融 PbBr₂ 中电子的移动 | **A**（`from X to Y through the external wire`） |
| `0620/21` Oct/Nov 2020 Q14 | 熔融 NiCl₂ 阴极反应 | **D**（`Ni[²⁺] + 2e[⁻] [→] Ni`） |

> 📌 **用途**：这张表证明"**稀 / 浓 / 熔融 三者产物完全不同**"是 Paper 2 的**常规武器**。
> **不要背题号** —— 要背的是那条判据（4.1.6 开头的决策树）。
> 全部 76 道电化学 MCQ 的完整台账见 **📊 真题实证 → Paper 2 电化学 MCQ 全量答案表**。

### 🔧 答题模板

**"浓/稀卤化物溶液的产物是什么？"（产物题，2–5 分）**
```
先圈出题干里的 dilute / concentrated：

稀溶液：  cathode → hydrogen        anode → oxygen (+ water)
浓溶液：  cathode → hydrogen        anode → halogen (Cl₂ / Br₂ / I₂)

再按题目要求补现象：
cathode → fizzing / effervescence / bubbles (of colourless gas)
anode（稀）→ bubbles (of colourless gas)
anode（浓，Cl₂）→ green gas
anode（浓，Br₂）→ orange/brown/yellow liquid
anode（浓，I₂）→ brown solution OR black solid
```

**"为何浓 NaCl 电解后溶液显碱性？"（2 分）**
```
Litmus turns blue because an alkali / a base forms — sodium hydroxide / NaOH.
```

> 🆕 **2026 年新题型："解释为什么阳极产生的是氧气"（2 分）—— 官方给了四条可接受路径（MS `0620/41` May/June 2026 Q5(a)(iv)）**
> 题干：`Dilute aqueous sodium chloride decomposes when an electric current is passed through it. Graphite electrodes are used. … (iv) Explain why oxygen is produced at the anode.` [2]
> MS：
> `M1 hydroxide ion is negative / OH[–] is negative(1)`
> `M2 There are 4 alternatives that can get M2 based on:`
> `· movement of negative ions to anode`
> `· concentration`
> `· process of hydroxide(ions) forming oxygen`
> `· oxygen formed and not chlorine`
>
> **M1 的接受范围**：`hydroxide ions` / `OH ions` / `OH[–]` / `hydroxide` / `OH is an anion`
> **M1 的拒绝**：`hydroxide`（单独写）/ `chloride ion` / `Cl` / **`oxide ions` / `oxygen ions` / `negatively charged oxygen`** / `hydroxide ions produced by electrolysis`
> **M2 的"浓度"路线（最容易被忽略的一条，直接背它）**：
> `ALLOW (the solution is) dilute or diluted/the solution is not concentrated`
> `ALLOW concentration (of sodium chloride or chloride ions) is not (high) enough`
> `ALLOW concentration of hydroxide (ion) is high / concentration of chloride (ion) is low`
> `ALLOW concentration of hydroxide (ion) is higher than chloride (ion)` / `more hydroxide (ion) than chloride (ion)`
> ⇒ **这就是 4.1.6 那条"稀 vs 浓"判据的官方措辞** —— 稀溶液里 OH⁻ 比 Cl⁻ 多，所以阳极出 O₂。
> ⚠️ 附带一条**极宽松的判分**：`4OH[–] → O2 + 2H2O + 4e or 4OH- – 4e → O2 + 2H2O both get 2 marks even if unbalanced or if water is absent e.g. OH- → O2 + e would score 2`

> 🆕 **2026 年新题型："解释为什么阴极产生的是氢气"（2 分）—— MS `0620/43` May/June 2026 Q5(a)(iv)**
> 题干（浓 aq LiBr）：`(iv) Explain why hydrogen gas is produced at the cathode.` [2]
> MS：`M1 hydrogen ions are positive` / `M2 · hydrogen ions are attracted to negative cathode OR · hydrogen ions gain electrons at the cathode OR · hydrogen is less reactive than lithium`
> - ✅ 接受 `H[+]` / `proton`；`hydrogen is a cation`；`H[+]` 出现在草稿方程里也算（`A H+ seen as a reactant in an equation 'attempt'`）
> - ✅ **一整条半方程式可以一次拿满两分**：`A correct ionic half-equation for both M1 and M2: 2H[+] + 2e[–] [→] H[2]`
> - ❌ `hydrogen is positive`（少了 **ions**，只给 1 分 salvage）
> - ❌ `lithium ions/Li+ are positive/are cations`（**问的是氢，不能拿锂来答**）
> - ❌ 离子式写错（`H2+` / `H2[2+]`）→ M1 不给
> - ⛔ 忽略：`hydrogen ions gain electrons/get reduced`（**没写 cathode**）；`hydrogen forms and not lithium`（未限定）
>
> ⇒ **这两个"解释为什么"题型（O₂ 在阳极 / H₂ 在阴极）是 2026 年的新面孔，2020–2025 的 Paper 4 里没有出现过。**
> **模板**（背这两句就够）：
> ```
> 阳极 O₂：The hydroxide ions are negative, so they are attracted to the positive anode;
>          and in a dilute solution the hydroxide ion concentration is higher than the chloride ion concentration.
> 阴极 H₂：The hydrogen ions are positive, so they are attracted to the negative cathode
>          and gain electrons there. (或直接写 2H[+] + 2e[–] [→] H[2])
> ```

---

## 4.1.7 aqueous copper(II) sulfate：惰性电极 vs 铜电极（考纲 Supplement 9）

### English 背这句

**这张对照表是本单元 Supplement 部分的正中靶心 —— 两份卷子把六项逐一考全了。**

| 观察/产物 | **惰性电极（Pt 或 C/石墨）** | **铜电极** | 出处 |
|---|---|---|---|
| 阴极质量 | `increase`（增加） | `increases`（增加） | `0620/42` May/June 2025 Q3(b)(i)、(c)(i) |
| 电解质颜色 | `becomes paler blue` **or** `becomes colourless`（Pt）；`becomes lighter (blue)`（C） | **`no change`**（不变） | `0620/42` May/June 2025 Q3(b)(ii)、(c)(ii)；`0620/41` Oct/Nov 2024 Q3(e)(iii) |
| 阳极现象 | `bubbles`（of colourless gas） | **`anode dissolves`**（阳极溶解，无气泡） | `0620/42` May/June 2025 Q3(b)(iii)；`0620/41` Oct/Nov 2024 Q3(e)(vi) |
| 阴极现象 | `pink AND solid` | — | `0620/41` Oct/Nov 2024 Q3(e)(iv) |
| 阳极反应 | `4OH[⁻] [→] 2H[₂]O + O[₂] + 4e[⁻]` | `Cu [→] Cu[²⁺] + 2e[⁻]`（铜原子失电子） | `0620/42` May/June 2025 Q3(b)(iv)；`0620/43` May/June 2023 Q5(b) |
| 阴极反应 | `Cu[²⁺] + 2e[⁻] [→] Cu` | `Cu[²⁺] + 2e[⁻] [→] Cu`（**相同**） | `0620/43` May/June 2023 Q5(a)(iv) |

**逐条原文（含 `[→]` 重建）**

> **`0620/42` May/June 2025 Q3(b)(c) —— 铂电极 vs 铜电极的完整对照**
> `(b)(i) State whether the mass of the cathode increases, decreases or remains the same when platinum electrodes are used.` [1] → MS：`3(b)(i) increase`
> `(b)(ii) Describe the change in appearance, if any, of the electrolyte when platinum electrodes are used.` [1] → MS：`3(b)(ii) becomes paler blue` / `or` / `becomes colourless`
> 原文 span（`0620_s25_ms_42.txt` 第 233–237 行）
> `(b)(iii) Describe what is seen at the anode when platinum electrodes are used.` [1] → MS：`3(b)(iii) bubbles`
> `(b)(iv) Write the ionic half-equation for the reaction at the anode.` [3]
> MS：`3(b)(iv) 4OH[⁻] [→] 2H[₂]O + O[₂] + 4e[⁻]`
> `M1 any negatively charged OH species losing electrons` / `OR H2O + O2 as only products (other than electrons) on RHS`
> `M2 any negatively charged OH species losing electrons AND H2O + O2 as only products (other than electrons) on RHS`
> `M3 correct equation`
> 原文 span（`0620_s25_ms_42.txt` 第 241–251 行）
> `(c)(i) State whether the mass of the cathode increases, decreases or remains the same when copper electrodes are used.` [1] → MS：`3(c)(i) increases`
> `(c)(ii) Describe the change in appearance, if any, of the electrolyte when copper electrodes are used.` [1] → MS：`3(c)(ii) no change`

> **`0620/41` Oct/Nov 2024 Q3(e) —— 唯一给出"颜色如何变"的形容词，以及"两差异"的完整答案**
> `(i) State why aqueous copper(II) sulfate conducts electricity.` [1] → MS：`3(e)(i) mobile ions`
> `(ii) Give two reasons why the electrodes are made of graphite.` [2] → MS：`M1 conducts electricity` / `M2 inert`
> `(iii) Describe how the appearance of the electrolyte changes during the electrolysis of aqueous copper(II) sulfate.` [1] → MS：`3(e)(iii) becomes lighter (blue)`
> `(iv) Describe what is seen at the cathode during the electrolysis of aqueous copper(II) sulfate.` [1] → MS：`3(e)(iv) pink AND solid`
> `(v) Write the ionic half-equation for the reaction at the anode.` [3]
> → MS：`3(e)(v) 4OH[⁻] [→] 2H[₂]O + O[₂] + 4e[⁻]` / `M1 O[₂] as a product` / `M2 OH[⁻] AND e[⁻]` / `M3 correct equation`
> `(vi) State two differences seen if the electrolysis is repeated using copper electrodes instead of graphite electrodes.` [2]
> → MS：`one mark each for any two of: colour remains constant / no bubbles at the anode / anode dissolves`
> 原文 span（`0620_w24_ms_41.txt` 第 202–220 行）

> **`0620/43` May/June 2023 Q5 —— 铜电极 + 铜半方程 + 颜色变化**
> `Q5(a)(iii)`：颜色变化 [1]；`Q5(a)(iv)`：`Write the ionic half-equation for the reaction at the cathode.` [2]
> MS：`Cu[²⁺] + 2e[⁻] [→] Cu` / `Cu[²⁺] and (any number of) e[⁻] on left hand side` / `equation correct`
> `Q5(b)`：铜阳极的观察 [1] → MS：`anode dissolves`

### 中文理解

**同一瓶蓝色溶液，只换电极材料，现象完全不同 —— 这就是考纲把这两种情况并列写进 Supplement 9 的原因。**

```
惰性电极（Pt / C）：电极不参与反应
   阴极：Cu²⁺ + 2e⁻ → Cu        → 阴极变粉红、蓝色溶液变浅（Cu²⁺ 被消耗）
   阳极：4OH⁻ → 2H₂O + O₂ + 4e⁻  → 阳极冒气泡；溶液里的 Cu²⁺ 越来越少 → 颜色变浅/变无色

铜电极：阳极本身参与反应
   阴极：Cu²⁺ + 2e⁻ → Cu        → 阴极变粉红（和上面一样）
   阳极：Cu → Cu²⁺ + 2e⁻        → 阳极溶解、变薄；没有气泡
   净结果：阳极溶掉的 Cu²⁺ 正好补上阴极消耗的 Cu²⁺
          → 溶液里 Cu²⁺ 浓度不变 → 蓝色不变
```

> 📌 **一句话记住差异**：**铜电极下"阳极在喂、阴极在吃"，浓度守恒，所以颜色不变、没有气泡。**
> **惰性电极下"只吃不出"，所以颜色变浅、阳极冒泡。**
> 这就是工业上**电解精炼铜（electrolytic refining）**用铜电极的理由。

### ⚠️ 陷阱

> **① 题干问阳极，考生答阴极（`0620/43` May/June 2023 Extended Q5(b)）**
> `The majority of candidates gave a correct observation although the question did not specifically ask for one, recognising that the anode would dissolve or get smaller. Some of the better performing candidates wrote about oxidation of the anode. Correct oxidation equations were acceptable but were rarely seen. **The most common errors were: giving observations for the cathode such as a coating of pink or brown metal or the electrode getting bigger; reduction of the anode.**`
>
> ⇒ ❌ 把阴极现象（粉红色镀层、电极变大）写给阳极；❌ 说阳极被还原（阳极永远被**氧化**）。

> **② 最常见的半方程错法 —— 给铜离子"减电子"（`0620/43` May/June 2023 Extended Q5(a)(iv)）**
> `Candidates found this question challenging. Many candidates wrote the ionic half-equation for the oxidation of copper to form copper ions. Other common errors seen were: the incorrect charge on the copper ion; the electrons appearing as subtracted from the copper ion or added on the product side of the equation, denoting a loss of electrons by the copper ion i.e. Cu[2+] [–] 2e[–] [→] Cu or Cu[2+] [→] Cu + 2e[–]`
> `In addition, candidates need to be aware that although Cu[2+] + 2e[–] [→] Cu may be considered mathematically equivalent to Cu[2+] [→] Cu [–] 2e[–], **the latter is not a correct chemical description of the changes taking place.**`
>
> ⇒ **数学等价 ≠ 化学正确。** 电子**只能写在左边、带负号、与反应物相加**。

> **③ 选择题里"电极替换"的偷换 —— 本主题最精巧的陷阱**
> `Question 30 where the replacement of an electrode is described but the wrong electrode is given.` — ER `0620/22` March 2024
> `Candidates choosing this statement confused the cathode for the anode in the electrolysis.` — ER `0620/22` March 2024
>
> **【补充 · 我方观察，非官方陈述】** 在 `0620/23` May/June 2024 Q9 中，选项 **D**（`Copper is formed at the cathode and oxygen is formed at the anode.`）对"石墨电极"是对的，但**题目明说用铜电极**，所以是错的；正确答案是 **A**（`Copper atoms gain electrons at the cathode and copper(II) ions lose electrons at the anode.`）。**这类"电极材料决定产物"的偷换是本主题最精巧的选择题陷阱。**
>
> 🆕 **官方 ER 已确认这道题（ER `0620/23` May/June 2024 Q9）**：
> `Most candidates **confused the electrolysis of copper(II) sulfate using copper electrodes with the electrolysis using graphite electrodes**. Option D was most commonly chosen. Candidates are reminded that cations are attracted to the cathode and that reduction occurs at the cathode, which may help in deducing the answer to questions like this.`
> ⇒ **上面的"我方观察"已被官方原文证实**：错因就是"把铜电极当成了石墨电极"。
> 🆕 **同一条陷阱的另外三处官方点名**：
> `Many candidates **confused the anode and the cathode** in the electrolysis and chose option B.` — ER `0620/21` Nov 2024 Q12
> `Most of the candidates who performed less well overall confused the anode and cathode and so suggested either options A or B. **A third of candidates overall confused the electrolysis of copper(II) sulfate using a copper anode with the same electrolysis using graphite electrodes and gave option C.**` — ER `0620/21` May/June 2024 Q13
> `Option B was the most popular choice overall. The difference between reaction products when electrolysing molten rather than aqueous electrolytes was often not well recalled.` — ER `0620/12` Nov 2023 Q11

**MCQ 答案速查（aq CuSO₄ 与铜电极 —— 全部逐题核出）**

| 卷/题 | 题干要点 | 答案 |
|---|---|---|
| `0620/22` Feb/Mar 2020 Q11 | aq CuSO₄ 碳电极，哪条对（蓝色褪去） | **D** |
| `0620/21` May/June 2020 Q11 | aq CuSO₄ 惰性电极，哪个电极反应对 | **A** |
| `0620/22` May/June 2020 Q10 | 同上（四种电解质） | **A** |
| `0620/22` May/June 2020 Q11 | aq CuSO₄ 惰性电极 | **A** |
| `0620/23` May/June 2020 Q11 | aq CuSO₄ 惰性电极 | **A** |
| `0620/22` Feb/Mar 2023 Q11 | 浓 aq CuSO₄ 铜电极，阴极半方程 | **D**（`Cu[²⁺] + 2e[⁻] [→] Cu`） |
| `0620/22` May/June 2022 Q11 | aq CuSO₄ 惰性电极，哪个箭头是电子流向 | **B** |
| `0620/22` May/June 2024 Q11 | aq CuSO₄ 铜电极阴极半方程 | **D** |
| `0620/23` May/June 2024 Q9 | aq CuSO₄ 铜电极（**"阴极得铜、阳极得氧"是错选项**） | **A** |
| `0620/21` May/June 2024 Q13 | 铜电镀：阳极半方程 + 颜色变化 | **D**（`Cu [→] Cu[²⁺] + 2e[⁻]` / blue colour does not change） |
| `0620/21` Oct/Nov 2024 Q12 | aq CuSO₄ 哪条对（`When copper electrodes are used, the anode gets smaller`） | **C** |
| `0620/22` Oct/Nov 2024 Q12 | aq CuSO₄ 石墨电极产物与现象 | **A**（oxygen / bubbles of gas；copper / electrode turns pink） |

> 📌 **"连续三份同题"（s20 的 21/22/23 三卷 Q10–Q11）说明 aq CuSO₄ 惰性电极是 Paper 2 的老面孔**，
> 而 m23/m24/s24/w24 又把它换成了**铜电极**版本 —— **考纲 Supplement 9 的两半，Paper 2 每隔一两年就轮流考一次。**

> 🆕 **考官对六问逐条的点评 —— 4.1.7 最完整的一份 ER（ER `0620/41` Nov 2024 Q3(e)）**
> `(e)(i) Most candidates appreciated that copper(II) sulfate conducts due to mobile ions. A common error is to refer to 'free' ions but the reason that copper(II) sulfate conducts is that the ions are able to move. Candidates who performed less well thought that it conducted due to the movement of electrons.`
> `(ii) Most candidates knew that graphite electrodes are inert and that they were electrical conductors. **Common responses that did not gain credit were 'high melting point', 'cheap', 'insoluble' or 'can conduct' (which could have been the conduction of heat).**`
> `(iii) Candidates found this question very challenging. Some candidates described the formation of copper e.g. pink-brown solid. **'Becoming blue' was another common incorrect answer. The correct answer had to make it clear that the electrolyte turned colourless.**`
> `(iv) While most candidates knew that copper was produced at the electrode, the question asked for an observation so **stating 'copper seen' is not an observation**. The correct answer of pink deposit was rarely seen with **common incorrect answers being 'bronze' (which is not a colour); 'solid', 'pink metal' or 'copper metal'**.`
> `(v) Candidates found this question very challenging. **O2[–] was very commonly seen as the only species on the left-hand side.** Those who realised that OH[–] was the ion that was discharged usually got the ionic half-equation completely correct.`
> `(vi) The candidates found describing the differences between the two experiments challenging. Many candidates had the idea that the anode dissolved or became smaller but fewer appreciated that **the colour of the copper(II) sulfate would remain blue**. Some candidates said that **the mass of the anode would get smaller, which while being true is not an observation**. Some candidates said that **the cathode would get larger, but this did not gain credit as the cathode would get larger in both experiments so is not a difference.** Others said that **the electrode would dissolve without specifying the anode**.`
>
> **六条最容易拿的教训**（按优先级）：
> 1. **(iv)** 现象必须"**颜色 + 状态**"：`pink AND solid`；`copper seen` / `bronze` / `solid` / `pink metal` / `copper metal` 全部 0 分。
> 2. **(vi)** 讲"差异"必须**是两次实验的差异**：`cathode gets larger` 两次都会变大 ⇒ **不算差异**；`the electrode dissolves` 没说是阳极 ⇒ 不给分。
> 3. **(vi)** 不要用"质量变化"代替"观察"：`the mass of the anode would get smaller` **是事实但不是 observation**。
> 4. **(ii)** 石墨题的不给分答案：`high melting point` / `cheap` / `insoluble` / `can conduct`（有热导歧义）。
> 5. **(iii)** `becoming blue` 反向错答；**要写"变浅/变无色"**。
> 6. **(v)** `O[²⁻]`（氧化物离子）是最常见的左端物种 —— 水溶液里放电的是 `OH[–]`。
>
> ⚠️ **【口径提示】**(iii) 的 MS 写的是 `becomes lighter (blue)`，而 ER 强调"**must make it clear that the electrolyte turned colourless**"。
> 两个口径并看：**最安全的写法是把两个都被接受的说法一起给出** —— `becomes paler blue / colourless`（s25/42 MS 正是把 `becomes paler blue` 与 `becomes colourless` 并列为可接受答案）。

### 🔧 答题模板

**"用铜电极重做，会有哪些不同？"（2 分，any two from）**
```
1. the colour of the electrolyte remains constant (instead of turning pale blue)
2. no bubbles are seen at the anode
3. the anode dissolves / gets smaller
```

**"描述……的变化"题的三个安全句式**
```
cathode mass          → the mass of the cathode increases
electrolyte colour    → becomes paler blue  (Pt)  /  becomes lighter blue  (C)
anode (inert)         → bubbles of colourless gas are seen
anode (copper)        → the anode dissolves / gets smaller
```

---

## 4.1.8 离子半方程式（考纲 Supplement 11）—— **第二高频考点，23 份卷考过**

### English 背这句

**全部被考过的半方程式（MS 逐字，`[→]`/`[⁺]`/`[⁻]`/`[₂]` 为重建）**

| 反应 | MS 答案 | M1 / M2 拆分（官方原文） | 出处 |
|---|---|---|---|
| **阴极** H⁺ | `2H[⁺] + 2e[⁻] [→] H[₂]` | `H⁺ + e(⁻) on left hand side(1)` / `equation fully correct(1)` | `0620/41` May/June 2024 Q3(c)(ii)；`0620/41` May/June 2021 Q3(d)(i) |
| **阴极** H⁺（变体） | `2H[⁺] + 2e(⁻) [→] H[₂] (2)` | `species correct (1)` / `fully correct equation (1)` | `0620/42` May/June 2021 Q4(d) |
| **阳极** OH⁻ | `4OH[⁻] [→] 2H[₂]O + O[₂] + 4e[⁻]` | `any negatively charged OH species losing electrons` / `correct ionic half-equation` | `0620/43` May/June 2024 Q3(c)(ii)；`0620/42` May/June 2021 Q4(b)(i) |
| **阳极** OH⁻（3 分版） | `4OH[⁻] [→] 2H[₂]O + O[₂] + 4e[⁻]` | `O[₂] as a product` / `OH[⁻] AND e[⁻]` / `correct equation` | `0620/41` Oct/Nov 2024 Q3(e)(v)；`0620/43` Oct/Nov 2024 Q2(b)(ii)；`0620/42` May/June 2025 Q3(b)(iv) |
| **阳极** Cl⁻ | `2Cl[⁻] [→] Cl[₂] + 2e[⁻]` | `Cl[₂] (1)` / `rest of equation (1)` | `0620/41` Oct/Nov 2021 Q3(a)(i)；`0620/42` Oct/Nov 2023 Q4(b)(ii) |
| **阳极** Br⁻ | `2Br[⁻] [→] Br[₂] + 2e[⁻]` | `any negative Br species losing electron(s)` / `correct ionic half equation` | `0620/42` Feb/Mar 2025 Q2(d)(ii) |
| **阴极** Cu²⁺ | `Cu[²⁺] + 2e[⁻] [→] Cu` | `Cu[²⁺] and (any number of) e[⁻] on left hand side` / `equation correct` | `0620/43` May/June 2023 Q5(a)(iv) |
| **阴极** Na⁺ | `Na[⁺] + e[⁻] [→] Na` | （1 分，不拆） | `0620/43` Oct/Nov 2020 Q5(d)(iii)；`0620/43` May/June 2021 Q3(d)(ii) |
| **阴极** Zn（溶解） | `Zn [→] Zn[²⁺] + 2e[⁻]` | `Zn as only reactant and Zn[²⁺] as only product` | `0620/42` Feb/Mar 2022 Q4(a)(ii) |
| **阴极** Al³⁺ 〔铝提取题〕 | `Al[³⁺] + 3e[⁻] [→] Al` | `any positive Al species gaining electron(s) (1)` / `correct species and balance (1)` | `0620/42` Feb/Mar 2020 Q2(b)(iii)；`0620/43` Nov 2025 Q3(a)(iv) |
| **阳极** O²⁻ 〔铝提取题〕 | `2O[²⁻] [→] O[₂] + 4e[⁻]` | `any negative O species losing electron(s) (1)` / `correct species and balance (1)` | `0620/42` Feb/Mar 2020 Q2(b)(iii) |

> ⚠️ **【推断】** `0620/42` Feb/Mar 2020 Q2(b)(iii) 的答案表在 txt 中列宽错乱，4 行答案与 Marks 列的对应关系是**按题目顺序推断**的（research 文件已标注）。**引用该题的 M1/M2 措辞时请留意。**

> ⚠️ **反复出现的 M1 判分逻辑：M1 只判"电子在哪一侧"，不判系数。**
> `M1 H⁺ + e(⁻) on left hand side(1)` — `0620/41` May/June 2024 Q3(c)(ii)
> `M1 H⁺ + e as only species on LHS (1)` — `0620/41` May/June 2021 Q3(d)(i)、`0620/41` May/June 2023 Q5(a)(iii)
> `M1 any negatively charged OH species losing electrons` — `0620/42` May/June 2025 Q3(b)(iv)
>
> ⇒ **即使系数写错（如 `H⁺ + e⁻ → ½H₂`），只要"电子在左边、物种对"，M1 照样给。**

### 中文理解

**半方程式的本质：把"某个离子得到/失去几个电子、变成什么"用一条配平的式子写出来。**

```
阴极（还原）通用型：  阳离子  +  e⁻  [→]  产物
阳极（氧化）通用型：  阴离子  [→]  产物  +  e⁻
                     ↑ 电子永远"跟反应物写在一起"
```

**两个必须背下来的"配原子"技巧**（因为 H 和 O 不能凭空出现）：

| 缺什么 | 怎么补 | 例子 |
|---|---|---|
| 缺 O 原子 | 补 **H₂O**（在另一边补 H⁺ 或 H₂O） | `4OH⁻ [→] 2H₂O + O₂ + 4e⁻`（左边 4 个 O，右边 2×1 + 2 = 4 个 O ✓） |
| 缺 H 原子 | 补 **H⁺**（酸性）或 **H₂O / OH⁻**（中性碱性） | `2H⁺ + 2e⁻ [→] H₂` |

**配平三步检查法**（考场上 10 秒过一遍）：
```
① 电荷平了吗？   左边总电荷 = 右边总电荷
     例：4OH⁻ [→] 2H₂O + O₂ + 4e⁻    左 = −4      右 = 0 + 0 + (−4) = −4   ✓
     例：2Cl⁻ [→] Cl₂ + 2e⁻          左 = −2      右 = 0 + (−2) = −2       ✓
② 原子平了吗？   每种原子的个数左右相等
③ 电子在哪边？   氧化 = 右边；还原 = 左边
```

### ⚠️ 陷阱（**官方给出的半方程式错误清单，全在这里**）

> **① "数学等价"不算对 —— 电子不能放右边、不能写成减法（`0620/43` May/June 2023 Extended Q5(a)(iv)）**
> `Candidates found this question challenging. Many candidates wrote the ionic half-equation for the oxidation of copper to form copper ions. Other common errors seen were: the incorrect charge on the copper ion; the electrons appearing as subtracted from the copper ion or added on the product side of the equation, denoting a loss of electrons by the copper ion i.e. Cu[2+] [–] 2e[–] [→] Cu or Cu[2+] [→] Cu + 2e[–]`
> `In addition, candidates need to be aware that although Cu[2+] + 2e[–] [→] Cu may be considered mathematically equivalent to Cu[2+] [→] Cu [–] 2e[–], **the latter is not a correct chemical description of the changes taking place.**`

> **② 同一逻辑也适用于氢（`0620/42` May/June 2021 Extended Q4(d)）**
> `The ionic half-equation for the cathode reaction was known by many. Candidates need to be aware that although 2H[+] + 2e[–] [→] H2 may be considered mathematically equivalent to 2H[+] [→] H2 [–] 2e[–], **the latter is not a correct chemical description of the changes taking place.**`

> **③ 半方程式错误的完整清单（`0620/42` Feb/Mar 2025 Extended Q2(d)(ii)）—— 一份"错法大全"**
> `Many candidates were unable to give the correct balanced ionic half-equation for the reaction taking place at the anode. Common errors included:`
> - `negative ions gaining electrons`（`2Br[–] + 2e[–] [→] Br2`）—— **把氧化写成还原！**
> - `molecules becoming ions`（`Br2 [→] 2Br[–] + 2e[–]`）—— **把过程写反了**
> - `Br rather than Br2 as the product`
> - `including K atoms or K[+] ions`（**把旁观离子写进半方程**）
>
> `These errors suggest this topic was not well understood and candidates may benefit from additional practice constructing ionic half-equations.`

> **④ 电子"写右边"是常年内伤（`0620/43` Oct/Nov 2022 Extended Q3(c)(ii)）**
> `Ionic half-equations continue to be a problem for candidates. **The usual errors of electrons on the right-hand side and 3Al on the right-hand side were again seen regularly.** Some candidates suggested that electrons had three negative charges.`
>
> ⇒ 新错法：**`3e⁻` 写成"电子有三个负电荷"** —— 电荷数不是系数，别搞混。

> **⑤ `H` / `Cl` / `Br` 单原子写法（三处点名）**
> `the most common error being to form H rather than H2` — `0620/41` Oct/Nov 2020 Q5(a)(iv)
> `Many could not recall the formula for chlorine is Cl2, and many candidates tried to balance the equation using symbols such as H or HCl rather than balancing the number of atoms.` — `0620/41` Oct/Nov 2021 Q3(a)(i)
> `Br rather than Br2 as the product` — `0620/42` Feb/Mar 2025 Q2(d)(ii)

> **⑥ 氢离子电荷写错、氢物种不带电（两处）**
> `(c) The ionic equation proved difficult for many candidates. The hydrogen species on the left was often uncharged or had the wrong charge.` — `0620/41` Oct/Nov 2021 Q3(a)(c)
> `Common errors included the wrong charge on the hydrogen ion and the formula of hydrogen written as H.` — `0620/41` May/June 2023 Q5(a)(iii)

> **⑦ 官方 Key messages（两条，都是"半方程式是弱项"）**
> `Ionic equations, including half-equations, continue to be an area that needs considerable improvement.` — `0620/41` Oct/Nov 2021 Key messages
> `Formulae and equations, including ionic equations and ionic half-equations, were an area of weakness for many candidates.` — `0620/43` Oct/Nov 2022 Key messages

> 🆕 **⑧ 2026 年 MS 的"判分细则"：漏了什么、写错了什么，各扣哪一分（MS `0620/41` May/June 2026 Q5(a)(iii)）**
> `2H[+] + 2e(–) [→] H[2]　M1 H+ + e on LHS of equation(1)　M2 equation fully correct(1)`
> - ✅ `ALLOW e or e(–) or es for electrons`；`IGNORE state symbols`；`ALLOW multiples`（系数随便几倍都行）
> - ✅ **`M1 ALLOW ANY number of positive hydrogen species with ANY positive charge + ANY number of electrons on LHS`** —— 例如 `H[2][2+] + 4e [→] …` **也给 M1**
> - ❌ **`M2 REJECT H20（M1 still can score）`** —— 产物写成 H₂O，M2 不给但 M1 还在
> - ⚠️ **`SALVAGE MARK: ALLOW 1 mark for 2H[+] [→] H[2] [–] 2e(–)`** —— **本笔记重要更正**：
>   2021 / 2023 的 ER 说这种"数学等价"写法**不是正确的化学描述**；到 2026 年，它**能拿到 1 分 salvage（即 M1）**，但**拿不到 M2**。
>   ⇒ **结论不变：考试就写 `2H[+] + 2e(–) [→] H[2]`；万一写反了，也不是全零 —— 但别指望满分。**
> - ✅ **特殊情形也可给分**：`2H[2]O + 2e(–) [→] 2OH[–] + H[2]` → `M1 for H2O + electrons on LHS(1)` / `M2 equation fully correct(1)`

> 🆕 **⑨ 2026 年 MS 对"氧化型"半方程的宽松尺度（MS `0620/43` May/June 2026 Q5(a)(iii)）**
> `2Br[–] [→] Br[2] + 2e[–]`　`M1 any negative Br species losing electron(s)` / `M2 correct ionic half equation`
> - ✅ **`A 2Br[–] [–] 2e[–] [→] Br[2] for both marks`** —— **氧化方向写减法，2026 年给满 2 分！**
>   ⚠️ 注意这与还原方向不对称：还原方向写减法只有 **1 分 salvage**（见上条）。**规律：只要"失电子"的事实写清楚了，判分就宽；"得电子"写成减法就一定吃亏。**
> - ✅ `A e and 'e(–)s' and 'es' for e[–]`（如 `2es`）
> - ✅ M1 的宽限：`Br[2][–] [–] 2e [→] 2Br` 或 `Br[2][–] [→] Br[2] + e[–]` 都 `scores M1`
> - ⚠️ **拼写 salvage**：`A 1 salvage mark if equation completely correct but both 'Br' appear as BR / both 'Br' appear as br`（如 `2BR[–] [→] BR[2] + 2e[–]`）

> 🆕 **⑩ 2024 年对 H₂ 半方程的 ER 点评（ER `0620/41` May/June 2024 Q3(c)(ii)）**
> `This was answered reasonably well. **H+ and/or e- were often missing from the left hand side of the equation. Formulae other than H2 were often seen as the product.**`
> ⇒ **两个失分点**：左边漏 `H[+]` 或漏 `e[–]`；产物不写 `H[2]`。

### 🔧 答题模板：半方程式四步法

```
第 1 步：判断这个电极上放电的是谁
         阴极：溶液中的阳离子（或 H⁺）      阳极：溶液/熔融物中的阴离子（或 OH⁻）
第 2 步：写出"反应物 [→] 产物"（先不管电子）
         例：OH⁻ [→] O₂        H⁺ [→] H₂        Cl⁻ [→] Cl₂        Cu²⁺ [→] Cu
第 3 步：补电子（氧化记右边、还原记左边），并让两边电荷相等
         OH⁻ [→] O₂ + 4e⁻
         Cu²⁺ + 2e⁻ [→] Cu
第 4 步：配原子 —— 用 H₂O / H⁺ 补齐 H 和 O，最后让两边每种原子个数相等
         4OH⁻ [→] 2H₂O + O₂ + 4e⁻
         2H⁺ + 2e⁻ [→] H₂
```

**四条"绝不写"**（考官逐条点过名的）：
```
❌ 电子写在右边（氧化型的除外，但还原型绝不能）
❌ 用减法表示电子      Cu²⁺ [–] 2e⁻ [→] Cu
❌ 把旁观离子写进去    K⁺ / SO₄²⁻ / Na⁺ 一律不出现
❌ 用单原子写法        H / Cl / Br
```

---

## 4.1.9 阴极/阳极通律与"命名陷阱"（考纲 Core 4）

### English 背这句

> **考纲 Core 4 原文**：`State that metals or hydrogen are formed at the cathode and that non-metals (other than hydrogen) are formed at the anode.`
>
> **中文对照**：**阴极得金属或氢；阳极得非金属（氢除外）。**

**给分命名对照表（**左边一列必须原样写，右边一列一分不给**）**

| 电极 | ✅ 给分（元素名） | ❌ 不给分 |
|---|---|---|
| 阳极 (+) | `chlorine` | `chloride`、`chloride ions`、`Cl`、`Cl[⁻]` |
| 阳极 (+) | `bromine` | `bromide`、`bromide ions`、`Br`、`Br[⁻]` |
| 阳极 (+) | `iodine` | `iodide`、`iodide ions` |
| 阳极 (+) | `fluorine` | **`fluoride`**（`0620/43` M/J 2021 点名） |
| 阳极 (+) | `oxygen` | `oxide`、`O[²⁻]` |
| 阴极 (−) | `lead` | `lead(II)`、`lead ions`、`Pb[²⁺]`、`lead forms` |
| 阴极 (−) | `sodium` | `sodium ions`、`Na[⁺]`、`sodium particles form` |
| 阴极 (−) | `copper` | `copper ions`、`Cu[²⁺]` |
| 阴极 (−) | `hydrogen` | `H`、`H[⁺]`、`hydrogen ions` |

> 来源：ER `0620/41` May/June 2021 Q3(c)(ii)（`potassium ions, chloride ions, chloride (as opposed to chlorine), K+, Cl and Cl [–]`）；
> ER `0620/43` May/June 2021 Q3(d)(i)（`'Fluoride' rather than elemental fluorine`）；
> ER `0620/32` March 2021（`'sodium particles form'`）；
> ER `0620/32` Feb/Mar 2022 Q6(c)(iii)（`'chloride' or 'chloride ions' instead of 'chlorine' or 'lithium ions' instead of lithium`）；
> ER `0620/32` Feb/Mar 2024（`Some candidates confused 'bromide' with the correct 'bromine'.`）；
> MS `0620/41` Oct/Nov 2021 Q3(e)（阴极写 `lead`，不是 `lead(II)`）
> 🆕 ER `0620/32` May/June 2024 Q3(b)(ii)（`some reversed the products or **suggested 'oxide' rather than 'oxygen'** as the product`）
> 🆕 ER `0620/42` Nov 2023 Q4(b)(iv)（`answers such as **'lead forms'** did not receive credit, neither did **'solid forms'** nor **'lead is deposited'**`）
> 🆕 ER `0620/42` Feb/Mar 2026 Q3(d)(ii)（`Some candidates **named the ions that migrated to the cathode**`）
> 🆕 ER `0620/41` Nov 2024 Q3(e)(iv)（`**stating 'copper seen' is not an observation**`；`'bronze'`, `'solid'`, `'pink metal'`, `'copper metal'` 都不给分）

### 中文理解

**这条通律是"产物预测"的保险绳** —— 当你忘记具体体系该怎么判断时，先用它兜底：

```
阴极 (−)：一定得到"金属"或"氢"   →  绝不可能是 O₂、Cl₂、非金属
阳极 (+)：一定得到"非金属"（氢除外）→  绝不可能是金属（除非阳极本身是铜等活泼金属在溶解）
```

**唯一需要小心的是"阳极溶解"**（铜电极）：那不属于"得到产物"，而是**电极自身被氧化** —— 所以铜电极下阳极**没有新产物，只有电极变薄**。

### ⚠️ 陷阱：产物题里写"离子"是最普遍的失分

> **离子名 ≠ 元素名，这是考官每年都要骂一次的错误。** 汇总见上表，四处官方原文：
> `Common incorrect answers included potassium ions, chloride ions, chloride (as opposed to chlorine), K+, Cl and Cl [–].` — `0620/41` May/June 2021
> `'Fluoride' rather than elemental fluorine was a common error for the product at the anode.` — `0620/43` May/June 2021
> `The commonest errors were to suggest 'chloride' or 'chloride ions' instead of 'chlorine' ...` — `0620/32` Feb/Mar 2022
> `Some candidates confused 'bromide' with the correct 'bromine'.` — `0620/32` Feb/Mar 2024

> 📌 **一个简单的心智检验**：如果你写的"产物"能被"离子"两个字替换（chloride ion / sodium ion），那它就**一定不是产物**。
> **产物是"中性物质"—— 原子、分子、单质。离子只存在于电解质里，不存在于电极上。**

---

## 4.1.10 电镀（考纲 Core 6 + Core 7）

### English 背这句

**① 电镀的三个物质（Paper 4 只考这一种问法，答案完全固定 —— 共 3 次）**

| 位置 | 答案（银电镀） | 答案（铜电镀） |
|---|---|---|
| **阳极（正极）** | `silver` | `copper` |
| **阴极（负极）** | `spoon`（工件） | `spoon`（工件） |
| **电解质** | `(aqueous or solution) of silver nitrate` | `(aqueous or solution) of named copper salt` |

> **`0620/43` May/June 2023 Q5(c)(i)：** `Spoons can be electroplated with silver. Name the substances used as: the anode (positive electrode) ...... the cathode (negative electrode) ...... the electrolyte. ......` [3]
> MS：`M1 silver` / `M2 spoon` / `M3 (aqueous or solution) of silver nitrate`
> 原文 span（`0620_s23_ms_43.txt` 第 245–249 行）
>
> **`0620/43` May/June 2022 Q5(b)：** `A metal spoon is electroplated with copper. State what is used as: the positive electrode (anode) ...... the negative electrode (cathode) ...... the electrolyte. ......` [3]
> MS：`5(b) copper (1)` / `spoon (1)` / `(aqueous or solution) of named copper salt (1)`
> 原文 span（`0620_s22_ms_43.txt` 第 311–315 行）

**② 为什么要电镀（Core 6，1 次，2 分）**
> **`0620/43` May/June 2023 Q5(c)(ii)：** `State two reasons why spoons are electroplated.` [2]
> MS：`M1 prevent corrosion` / `M2 improve appearance`
>
> ⚠️ **两分 = 两个理由，只写一个只给一分**（参考笔记常见的漏写就是只写"防腐蚀"漏掉"改善外观"）。

**③ Paper 6 的 6 分规划题（`0620/62` May/June 2025 Q4）—— 完整官方评分点**
> 题干：`Metal spoons can be electroplated with silver. Describe how a metal spoon can be electroplated with silver. Include in your answer how you could determine the mass of the silver electroplated onto the metal spoon. You are provided with solid silver nitrate, a metal spoon, a piece of solid silver, distilled water and common laboratory apparatus. You must include a diagram in your answer.` [6]
> MS：`any 6 from`
> `MP1 find mass of spoon`
> `MP2 silver nitrate dissolved in water`
> `MP3 diagram showing complete circuit with electrodes in silver nitrate (solution) /electrolyte and a power supply`
> `MP4 spoon/object to be plated as negative electrode/cathode in electrolysis`
> `MP5 silver used as one of the electrodes in electrolysis`
> `After electrolysis` `MP6 wash and dry spoon`
> `MP7 find mass of spoon again (after electrolysis) and mass of silver = new mass [–] original mass`
> 原文 span（`0620_m25_ms_62.txt` 第 220–237 行）

### 中文理解

**电镀的原理就是"把阳极的金属搬到阴极的工件上"。**

```
阳极 (+) = 镀层金属（银/铜）          → 被氧化溶解：Ag [→] Ag⁺ + e⁻
电解质   = 该金属的可溶盐的水溶液      → 搬运金属离子
阴极 (−) = 工件（匙）                → 被还原沉积：Ag⁺ + e⁻ [→] Ag
```

**为什么阳极一定要用镀层金属本身？** 这样溶液里的金属离子"用掉多少、补回多少"，浓度才能保持稳定（与 4.1.7 铜电极的道理完全一样）。**若用石墨当阳极，溶液里的银离子被消耗完就镀不动了。**

**为什么电解质必须是"可溶盐的溶液"而不是熔融盐？** 因为工件（匙）要在常温下镀，熔融盐的温度会毁掉工件；而且熔融盐里没有水，也无法做水溶液操作。

> 📌 **记忆句**：**阳极挂着要镀的金属，阴极挂着要镀的东西，溶液里泡着这种金属的可溶盐。**

### ⚠️ 陷阱（**三大坑：功率源、电极材料、电解质状态**）

> **① 最详细的电镀错误清单（`0620/62` May/June 2025 Extended 实践 Q4）**
> `Some excellent and clear descriptions of electroplating were seen. Common errors included:`
> - `omitting a power supply from their diagram`（**图里漏画电源**）
> - `using the spoon as the anode rather than the cathode`（**工件接反成正极**）
> - `using an inert electrode rather than silver as one of the electrodes`（**用惰性电极代替银**）
> - `using molten silver nitrate rather than a solution of aqueous silver nitrate as the electrolyte`（**用熔融盐**）
> - `A few candidates also labelled the named cathode with a positive charge.`（**给阴极标正电荷**）
> - `Candidates also commonly did not include washing and drying the spoon after electroplating in their plans.`（**漏了洗+烘干**）
> - `Some candidates did not draw a diagram, and others did not address missing the mass of the silver electroplated onto the spoon.`
>
> `Candidates should be encouraged to read and attempt all parts of the task stated in the question.`

> **② 三个物质写反 / 用石墨 / 用不溶盐（`0620/43` May/June 2023 Extended Q5(c)(i)）**
> `Candidates found this challenging. Some candidates transposed the silver and spoon electrode positions. **Graphite electrodes in combination with electrolytes given as molten silver or insoluble silver compounds such as silver chloride were common incorrect answers.** Some candidates answered throughout as if answering an electroplating with copper question.`

> **③ 铜版的同一错误（`0620/43` May/June 2022 Extended Q5(b)）**
> `Candidates found this challenging. Some candidates transposed the copper and spoon electrode positions. **Graphite electrodes in combination with electrolytes given as water or insoluble copper compounds were common incorrect answers.**`

> **④ 现象 vs 结论 —— 电镀题也踩同一个坑（`0620/62` March 2021 Extended 实践 Q1(c)）**
> `While some excellent answers to what proved to be a demanding question part were seen, **many candidates did not give genuine observations. Simply repeating the information from the stem of the question and stating that chlorine and silver would be made did not gain any credit as these are not observations.** The chlorine gas would be seen as bubbles in the electrolyte or as a green gas; the silver would be seen as a shiny/grey solid.`

> **⑤ 安全题不要答"触电"（同卷 (d)）**
> `Two common errors were to raise concerns with the possibility of electrocution (**electrolysis in a laboratory will normally use a low d.c. voltage and there is no risk of electrocution**) ...`
> 【安全题答案：`use a fume cupboard` / `chlorine is toxic`】

> 🆕 **⑥ Paper 6 的第二次电镀规划题 —— 2026 年的官方点评（ER `0620/62` Feb/Mar 2026 Q4）**
> `(ii) Comprehensive: Most candidates could name an appropriate metal for the anode.`
> `Limited responses: Some candidates named materials that would **not replace the silver ions removed from the solution** during electrolysis, giving answers such as **graphite, platinum or zinc**.`
> `(iii) Comprehensive: Most candidates realised the electrolyte had to contain silver ions and could name an appropriate silver salt to use.`
> `Limited responses: **Few candidates realised that the electrolyte needed have mobile silver ions and so be able to conduct electricity. These candidates omitted to state that the electrolyte should be aqueous or molten.**`
> ⇒ **判分逻辑说得最清楚的一次**：阳极金属的用途是"**补充被消耗掉的银离子**"（所以不能用石墨/铂/锌）；电解质的两分点是"**含银离子** + **是水溶液（离子可移动）**"。
> **与 2025 年那份（m25/62）合起来看，电镀规划题的错误清单已经稳定为四条**：电源画漏 / 工件接阳极 / 阳极用惰性材料 / 电解质写成熔融盐或水。

> 🆕 **⑦ Core 卷里的电镀实验题（ER `0620/33` Nov 2025 Q7）**
> `Candidates found this question one of the most challenging questions on this paper. They particularly struggled to **name a suitable aqueous electrolyte for the electroplating experiment shown** and to state whether the electrolysis process was a **physical or chemical change**.`
> `(a) Candidates struggled to **label the anode** in this part question. There were also many no response answers seen.`
> `(b) … Many incorrect answers were seen including those of other metal salts such as **zinc chloride**.`
> `(c) … many could state the correct colour of the gas produced at the anode. However, some candidates **got the halogen gas colour mixed up and answered incorrectly with 'green' or 'yellow'**.`
> `(d) … They struggled to identify whether the electrolysis experiment shown was a physical or chemical change. Many could state that it was a 'chemical change', but they could not state why.`
> ⇒ **两处可直接用的结论**：电镀的电解质**必须是"这种金属自己的"可溶盐**（`zinc chloride` 不给分）；电解**是化学变化**（因为有新物质生成）。

> 🆕 **⑧ 电镀的"理由"在 MCQ 里也考，而且有个假选项（ER `0620/13` May/June 2024 Q11）**
> `Most candidates recognised that **water taps are electroplated to improve their resistance to corrosion. The thin plating would not improve the strength of the taps.** Option C, the most commonly chosen option, is therefore incorrect.`
> ⇒ **"提高强度（strength）"是错的** —— 镀层很薄，改变不了力学性能。理由只有两条：**抗腐蚀 + 改善外观**。

### 🔧 答题模板

**"说出电镀用的三个物质"（3 分，一句话写完）**
```
Anode (+):   silver (the plating metal)
Cathode (−): the spoon (the object to be plated)
Electrolyte: aqueous silver nitrate / a solution of a soluble silver salt
```

**"为什么电镀？"（2 分）**
```
(1) to prevent corrosion / to protect the metal underneath
(2) to improve the appearance
```

**"设计电镀实验"（Paper 6，6 分）—— 按 MP1–MP7 顺序写满**
```
① 先称匙的质量
② 把硝酸银固体溶于蒸馏水，配成溶液
③ 画图：电源 + 导线 + 两块电极都浸在溶液里（完整回路）
④ 匙接负极（阴极）
⑤ 银块接正极（阳极）
⑥ 电解后取出，洗涤并烘干
⑦ 再称一次质量；镀上的银 = 第二次质量 − 第一次质量
```

---

# 4.2 Hydrogen–oxygen fuel cells 氢氧燃料电池

> **本节只有 2 条考纲要求**（Core 1 + Supplement 2），Paper 4 结构化题只有 **5 份卷、共 10 分**。
> **它是本笔记最小的主题，但也是"背了必得、没背必丢"最纯粹的主题** —— 因为答案清单极短、极固定。

## 4.2.1 反应物、产物与总反应（考纲 Core 1）

### English 背这句

**① 反应物与产物（最常考，2 分）**
> **`0620/42` Feb/Mar 2022 Q4(c)(i)(ii)**：`Fuel cells are used to generate electricity. (i) Name the reactants in a fuel cell. [1] (ii) Name the waste product of a fuel cell. [1]`
> MS：`4(c)(i) hydrogen and oxygen` / `4(c)(ii) water`
> 原文 span（`0620_m22_ms_42.txt` 第 222–224 行）

> **`0620/41` Oct/Nov 2024 Q5(a)(i)**：`Hydrogen is used in fuel cells to produce electricity in vehicles. Name the substance which combines with hydrogen in a fuel cell.` [1]
> MS：`5(a)(i) oxygen`

**② 总反应方程式（符号式 2 分 / 文字式 1 分）**
> **`0620/41` May/June 2023 Q5(c)(i)**：`Write the symbol equation for the overall reaction in a hydrogen–oxygen fuel cell.` [2]
> MS：`5(c)(i) 2H[₂] + O[₂] [→] 2H[₂]O` / `M1 all formulae(1)` / `M2 equation correct(1)`
> 原文 span（`0620_s23_ms_41.txt` 第 285–286 行）
>
> **`0620/42` Feb/Mar 2020 Q1(e)**：`Hydrogen fuel cells can be used to power vehicles. Write the word equation for the overall reaction that takes place in a hydrogen fuel cell.` [1]
> MS：`1(e) hydrogen + oxygen [→] water`
> 原文 span（`0620_m20_ms_42.txt` 第 157 行）：`1(e)          hydrogen+oxygenwater`（**注意：箭头被 pdftotext 吞掉，这里是重建**）

**③ 能量转化（Paper 2 反复考）**
```
chemical energy [→] electrical energy      ← 必须这个方向，反过来致命
```

### 中文理解

**燃料电池与"燃烧"的唯一区别是：它不点火，而是让 H₂ 与 O₂ 在两个电极上分别反应，直接产生电流。** 总反应与氢气燃烧完全相同：

```
2H₂ + O₂ → 2H₂O
```

**三个必须记住的"唯一"**：
1. 燃料是 **hydrogen**；氧化剂（combines with hydrogen）是 **oxygen**
2. 唯一化学产物是 **water** —— 不是 CO₂、不是 H₂O₂、不是 "水 + 二氧化碳"
3. 输出的是 **electricity**（不是热能为主）—— `chemical energy → electrical energy`

> 📌 **名字必须写全**：官方提醒 `Candidates should be reminded that the full name of the fuel cell in this syllabus is the hydrogen[–]oxygen fuel cell.`（ER `0620/12` March 2023）
> **"fuel cell" 单独出现时，本考纲指的就是氢氧燃料电池。**

### ⚠️ 陷阱

> **① 把反应物说成产物 —— 最高频错答（ER `0620/12` March 2023）**
> `Most candidates thought that hydrogen and oxygen were outputs rather than inputs to the hydrogen–oxygen fuel cell. Option B was the most popular response.`
> `Candidates should be reminded that the full name of the fuel cell in this syllabus is the hydrogen[–]oxygen fuel cell.`

> **② 把 "水" 与 "氢/氧" 混淆（ER `0620/13` Feb/Mar 2025）**
> `Many candidates could not recall an element used as a reactant in fuel cells. **The most common incorrect answer was H2O.**`

> **③ 写成分解水 / 电解（Paper 2 干扰项）**
> 干扰项 `1 The process in the cell is called electrolysis.` / `2 Water is broken down in the cell to produce hydrogen, oxygen and electricity.` —— **两个都错**
> `0620/22` Oct/Nov 2025 Q12（答案 **D**：only 3 对）

> **④ 说反应是吸热的（三处干扰项）**
> `C The reaction is endothermic.` — `0620/22` Feb/Mar 2024 Q13（答案 **D**：`No toxic gases are produced.`）
> `C The reaction that takes place is endothermic.` — `0620/23` Oct/Nov 2024 Q13（答案 **C**，因为题目问哪条**不**对）
> 【4.2 的正确表述：**放热**】

> **⑤ 说产物是 CO₂ 或"水 + CO₂"（两处干扰项）**
> `B The only product is carbon dioxide.` — `0620/22` Feb/Mar 2024 Q13
> `B The only chemical products are water and carbon dioxide.` — `0620/22` May/June 2025 Q12

> **⑥ 方程式写成过氧化氢（干扰项）**
> `A The equation for the overall reaction is H2 + O2 [→] H2O2.` — `0620/22` May/June 2025 Q12

> **⑦ 方程式不配平（干扰项）**
> `1 The balanced equation for the reaction is H2 + O2 [→] H2O.` —— **错**（未配平）
> `0620/21` Feb/Mar 2021 Q15（答案 **C**）

> **⑧ 说"氢被还原"（三处干扰项，全部错）**
> `3 In the fuel cell hydrogen is reduced.` — `0620/21` Feb/Mar 2021 Q15
> `2 Hydrogen is reduced in the fuel cells.` — `0620/22` Feb/Mar 2025 Q15
> —— **氢是被氧化的**（H₂ → H₂O 失电子，H 的氧化数 0 → +1）。

> **⑨ 把"燃烧方程"当成燃料电池方程（ER `0620/21` May/June 2021 Q13）**
> `Some candidates were more likely to choose option C, which was a balanced equation for combustion of a fuel but not the equation for the fuel cell.`
> 【正确答案是 `2H[₂] + O[₂] [→] 2H[₂]O`】

> **⑩ 说氢来自空气 / 是化石燃料（两处干扰项）**
> `A Hydrogen is extracted from clean, dry air.` — `0620/22` Feb/Mar 2024 Q13
> `D The hydrogen used in hydrogen–oxygen fuel cells is a fossil fuel.` — `0620/22` May/June 2025 Q12

> 🆕 **⑪ 写"文字方程"题时不要自作聪明写符号方程（ER `0620/42` Mar 2020 Q1(e)）**
> `The word equation for the overall reaction taking place within a fuel cell was made difficult by many candidates who **opted to give the more difficult symbol equation, often losing the mark for using incorrect symbols**. A significant number of candidates attempted ionic half-equations.`
> ⇒ **题目问 word equation 就写 `hydrogen + oxygen [→] water`。** 写符号方程只有两个下场：符号写错丢分，或者多此一举。

> 🆕 **⑫ "能量形式"被单独点名 —— 是 electricity 不是 heat（ER `0620/11` May/June 2024 Q11）**
> `Most candidates recalled that water is the only chemical product of the hydrogen–oxygen fuel cell **but assumed that the main form of energy was heat rather than electricity**. Option B was chosen by many candidates.`
> ⇒ **这是"唯一化学产物 = water"之外的第二个官方考点**：能量形式是**电**，不是热。

> 🆕 **⑬ CO₂ 陷阱与"反应物/产物"陷阱，在 Core MCQ 里各被点名一次（ER `0620/12` May/June 2024 Q14；ER `0620/12` Nov 2024 Q12）**
> `Although most candidates recalled that the hydrogen–oxygen fuel cell produces electricity, **most also thought that carbon dioxide is produced**, which suggests some confusion with the combustion of fuels.` — `0620/12` May/June 2024
> `Candidates should recognise that in the hydrogen–oxygen fuel cell, **the fuel is hydrogen**. The majority of candidates chose option B for which one of the reactions would produce oxygen not hydrogen.` — `0620/12` Nov 2024
> ⇒ **"与燃烧混淆"是官方给这一章定的统一错因**（另一种表述：`some confusion with the combustion of fuels`）。

> 🆕 **⑭ "把燃料电池与电解混为一谈"（ER `0620/22` Nov 2025 Q12；ER `0620/13` Nov 2023 Q12）**
> `The hydrogen–oxygen fuel cell was not well recalled. **Most candidates confused the process with electrolysis** and chose option A or B. Similarly a third of candidates thought that **hydrogen and oxygen were reaction products rather than the reactants** in a chemical reaction.` — `0620/22` Nov 2025
> `The hydrogen–oxygen fuel cell was not well recalled. Many candidates thought that **the fuel was petrol or that carbon dioxide would be produced**.` — `0620/13` Nov 2023（**Core MCQ**）
> `Knowledge of the hydrogen–oxygen fuel cell and its role in producing electrical energy was often not well recalled.` — `0620/21` Nov 2023（**Extended MCQ**）
> ⇒ **"confused the process with electrolysis"** 是官方对"输出/输入搞反"的另一种描述 —— 考生把燃料电池当成了"用水制氢"。

> 🆕 **⑮ 2026 年的新问法：同时问"两者的各自优点"（`0620/22` Feb/Mar 2026 Q11，答案 **C**）**
> 题干：`Which row describes an advantage of using the hydrogen–oxygen fuel cell and an advantage of using the petrol engine?`
> 正确行：H₂–O₂ 燃料电池的优点 = `does not produce carbon dioxide gas which causes global warming`；**汽油机的优点** = `can travel a greater distance after the fuel tank has been filled`
> ⇒ **注意这里把"加氢站少 / 续航短"反过来当成汽油机的优点** —— 说明 4.2.2 的缺点清单（`fewer filling stations`）在真实考题里会**倒过来用**。

> 🆕 **⑯ 2026 年的"哪条对"题，三个错误项就是本节的三个陷阱（`0620/21` May/June 2026 Q14，答案 **A**）**
> `Which statement about hydrogen fuel cells is correct?`
> `A Hydrogen fuel cells produce water as the only product.` ✅
> `B Hydrogen fuel cells do not need oxygen.` ❌（与 Core 1 直接冲突）
> `C The waste from a hydrogen fuel cell is an acidic gas.` ❌（唯一产物是水，不是酸性气体）
> `D The reaction in a fuel cell is endothermic.` ❌（§陷阱④）

### 🔧 答题模板

```
反应物： hydrogen and oxygen
唯一化学产物： water
符号方程： 2H[₂] + O[₂] [→] 2H[₂]O
文字方程： hydrogen + oxygen [→] water
能量转化： chemical energy [→] electrical energy
⚠️ 题目要 word equation 就写 word equation，不要写成符号方程（m20/42 Q1(e) 的官方教训）
```

---

## 4.2.2 优点与缺点（考纲 Supplement 2）

### English 背这句

> **`0620/41` Oct/Nov 2024 Q5(a)(ii)**（官方完整接受清单 —— 这是最权威的一份）
> `Give one advantage and one disadvantage of using fuel cells instead of gasoline in vehicle engines.` [2]
> MS：
> `advantage: any one of:`
> `[·] water is the only product`
> `[·] no carbon dioxide produced`
> `[·] more efficient`
> `disadvantage: any one of:`
> `[·] hydrogen needs to be stored at high pressure`
> `[·] hydrogen hard to store`
> `[·] heavy tanks needed to store hydrogen`
> `[·] fewer (hydrogen) filling stations`
> `[·] less efficient`
> 原文 span（`0620_w24_ms_41.txt` 第 250–264 行）

> **`0620/41` May/June 2023 Q5(c)(ii)**（1 分版）
> `State one advantage of using hydrogen–oxygen fuel cells instead of petrol in vehicle engines.` [1]
> MS：`5(c)(ii) no carbon dioxide evolved` / `OR` / `more efficient`

> **`0620/43` May/June 2023 Q5(d)(ii)**（缺点 1 分版）
> `State one disadvantage, other than cost, of using hydrogen–oxygen fuel cells to power cars compared to using petrol.` [1]
> MS：`5(d)(ii) needs high pressure to store hydrogen`

### 中文理解

**优点只有三类，缺点只有两类 —— 这就是全部。**

| 优点（3 条） | 中文 | 为什么算优点 |
|---|---|---|
| `water is the only product` | 唯一产物是水 | 不产生 CO₂（温室气体）、不产生 CO（有毒） |
| `no carbon dioxide produced` | 不产生二氧化碳 | 同上，直击汽油机的要害 |
| `more efficient` | 效率更高 | 化学能直接转电能，不做功的中间环节少 |

| 缺点（5 条） | 中文 | 为什么算缺点 |
|---|---|---|
| `hydrogen needs to be stored at high pressure` | 氢需要高压储存 | 气体密度低，必须压缩 |
| `hydrogen hard to store` | 氢难储存 | 同上，另一种措辞 |
| `heavy tanks needed to store hydrogen` | 需要很重的储氢罐 | 增加车重 |
| `fewer (hydrogen) filling stations` | 加氢站太少 | 基础设施不足 |
| `less efficient` | 效率更低 | 【注意：与优点里的 more efficient 并存，说明判分时**只看有没有答中清单里的一条**，不追究体系自洽】 |

> 📌 **官方"不给分"的三类答案（背下来，别写）**
> 1. **空泛的环保口号**：`no pollution` / `not environmentally friendly` / `no toxic products` / `renewable`（不提及 H₂ 或 O₂）
> 2. **"氢易燃易爆/危险"**（因为**汽油同样易燃**）
> 3. **"效率低"**（因为**燃料电池比汽油机效率高**）

### ⚠️ 陷阱

> **① 优点题答"空泛话"的官方黑名单（`0620/41` May/June 2023 Extended Q5(c)(i)(ii)）**
> `(i) A minority of candidates were aware that the equation for the reaction in a hydrogen–oxygen fuel cell is the same as that for the combustion of hydrogen in oxygen. H and O were often seen as incorrect formulae. H2O was only seen occasionally as the product.`
> `(ii) **Most answers were vague and non-specific**, such as:`
> `[·] no pollution`
> `[·] not environmentally friendly`
> `[·] no toxic products`
> `[·] renewable, without reference to oxygen or hydrogen.`
> `The correct answer needed to refer specifically to the hydrogen–oxygen fuel cell and its comparison with petrol in vehicle engines.`

> **② 缺点题的两条"明确拒收"（`0620/43` May/June 2023 Extended Q5(d)(ii)）**
> `This question proved to be **the most difficult on the paper**. Most candidates struggled to give a sensible disadvantage for the use of hydrogen-oxygen fuel cells. **Many did not read the question properly and gave an advantage instead.** The best answers focused on the difficulties of storing or transporting hydrogen as it is a gas and must be stored under high pressure, or the lack of infrastructure or hydrogen filling stations needed to supply the hydrogen. **Answers that described hydrogen as dangerous because it is highly flammable were not accepted as petrol is also highly flammable, neither were answers describing inefficiency as fuel cells are more efficient than using petrol.**`

> **③ 优点题的接受范围比考生想象窄**
> `0620/41` Oct/Nov 2024 的接受清单**只有 3 条优点 / 5 条缺点**。考生常答的"无污染""可再生"在 Extended Paper 4 里**没被列为接受答案**。
>
> 🆕 **【该题号的 ER 现已找到，原"无法确证"的推断作废】**（ER `0620/41` Nov 2024 Q5(a)(i)(ii)）
> `(a)(i) A common incorrect response was **carbon** as the substance that combines with hydrogen in a fuel cell rather than oxygen.`
> `(ii) Candidates tended to write **imprecise statements such as less polluting, cheap or renewable**. Answers should consider the chemistry of the fuel cells such as **water being the only product as the key advantage**, and **hydrogen being hard to store as the key disadvantage**. A number of candidates said a disadvantage was that **hydrogen is flammable, but gasoline is also flammable, so this is a disadvantage of both types of fuel cell**.`
> ⇒ **官方判据落地**：`less polluting` / `cheap` / `renewable` **不给分**；正确的两条就是 "water is the only product"（优点）与 "hydrogen is hard to store"（缺点）。
> ⇒ **"carbon 与氢反应"是本考点的第二个新错答**（第一个是 H₂O，见 4.2.1 陷阱②）。

### 🔧 答题模板（每条只用 6 个词）

```
优点（任选一条）：
  Water is the only product / No carbon dioxide is produced / It is more efficient.

缺点（任选一条）：
  Hydrogen needs to be stored at high pressure.
  / Hydrogen is difficult to store.
  / Heavy tanks are needed to store hydrogen.
  / There are fewer hydrogen filling stations.
```

> 📌 **"any one of" 是真的"任答一条即可"** —— **不必写多条保险，写多了不加分，写错了还可能被判矛盾（CON）。**

---

## 4.2.3 Paper 2 里的燃料电池（23 道，密度远高于 Paper 4）

| 季 | 卷/题 | 题干要点 | 答案 |
|---|---|---|---|
| Feb/Mar 2020 | `0620/22` Q13 | 1 反应吸热 / 2 废物是水 / 3 电池产氢 / 4 用于发电 | **C**（2 & 4） |
| Feb/Mar 2021 | `0620/22` Q15 | 反应式 / 发电 / 氢被还原 / 常温气体 | **C** |
| Feb/Mar 2024 | `0620/22` Q13 | 哪条对 | **D** |
| Feb/Mar 2025 | `0620/22` Q15 | 能量转化 / 氢被还原 / 无大气污染物 | **C** |
| May/June 2020 | `0620/21` Q13、`0620/22` Q13、`0620/23` Q13 | 同题三卷 | **A / A / A** |
| May/June 2021 | `0620/21` Q13 | 哪个方程是燃料电池反应 | **B** |
| May/June 2022 | `0620/22` Q17 | 4 mol O₂ 消耗 ↔ 多少 g H₂ | **D** |
| May/June 2023 | `0620/21` Q10 | — | **A** |
| May/June 2024 | `0620/23` Q11 | 优点 | **C** |
| May/June 2025 | `0620/21` Q12（总反应方程）、`0620/22` Q12（哪条对） | — | **A / C** |
| Oct/Nov 2020 | `0620/22` Q15 | `2H₂+O₂→2H₂O` 放热 286 kJ/mol，能量计算题 | **A** |
| Oct/Nov 2021 | `0620/21` Q12、`0620/22` Q14、`0620/23` Q14 | 燃料是什么 | **B / A / B** |
| Oct/Nov 2024 | `0620/21` Q13（优点）、`0620/23` Q13（哪条**不**对） | — | **D / C** |
| Oct/Nov 2025 | `0620/22` Q12（哪条对）、`0620/23` Q15（燃料 + 氧化剂） | — | **D / B** |
| 🆕 Feb/Mar 2026 | `0620/22` Q11（**燃料电池的优点 + 汽油机的优点，两栏对照**） | — | **C** |
| 🆕 May/June 2026 | `0620/21` Q14（关于氢燃料电池哪条对） | — | **A** |

> **23 道 / 46 卷（2026 新增 2 道）；w22、w23 两季完全没考。**
> 📌 **规律**：**燃料电池的 MCQ 密度（每两卷一道）远高于 Paper 4 的结构化题**。这意味着**它极可能以 1 分 MCQ 的形式出现在你的卷子上 —— 而 1 分 MCQ 的错法永远是那三条：把反应物当产物、把产物写成 CO₂、说反应吸热。**

---

# 📝 考试怎么考（Exam Focus）

## Paper 4（Theory，80 分 / 75 min）

**时间账**：80 分 / 75 min ≈ **1 分 1 分钟**。电解题常见规模 **8–13 分**（整题）或 **2–5 分**（大题的一小段），
⇒ **分给电解的合理时间是 5–13 分钟。**

**位置规律**：电解题几乎不出现在 Q1，**集中在 Q2–Q5**，且 28 份卷里**有 7 次是"一整道大题全是电解"**：
`0620/42` May/June 2020 Q5 [8]、`0620/42` May/June 2021 Q4 [12]、`0620/41` Oct/Nov 2021 Q3 [13]、
`0620/43` Oct/Nov 2021 Q2 [12]、`0620/43` Oct/Nov 2024 Q2 [11]、`0620/41` Oct/Nov 2024 Q3(e) [10]、`0620/42` May/June 2025 Q3 [9]。

**四种固定题型（认清题型 = 认清该写什么）**

| 题型 | 分值 | 你要写什么 | 代表题 |
|---|---|---|---|
| **① 定义题** | 1–3 | 背好的英文定义原句（`breakdown` / `ionic` / `molten` / `electric current`） | `0620/41` May/June 2024 Q3(c)(i) |
| **② 半方程式题** | 1–3 | 离子 + 电子，左边还是右边 | `0620/42` May/June 2025 Q3(b)(iv) |
| **③ 产物 + 现象题** | 2–5 | 元素名 + 颜色/气泡/固体 | `0620/42` Feb/Mar 2025 Q2(d)(iii) |
| **④ 解释/理由题** | 1–2 | `mobile ions` / `conducts electricity AND inert` / 电镀两理由 | `0620/42` Oct/Nov 2023 Q4(b)(i) |
| **⑤ 表格题** | 3–5 | 产物（元素名）+ 现象（颜色/气泡/固体），一栏一栏填 | `0620/43` Oct/Nov 2024 Q2(b)(i)；`0620/42` Feb/Mar 2026 Q3(d)(ii) |
| 🆕 **⑥ "解释为什么"题** | 2 | **离子带电性与迁移方向 + 浓度（或"不是因为另一个"）** | `0620/41` May/June 2026 Q5(a)(iv)（为何阳极出 O₂）；`0620/43` May/June 2026 Q5(a)(iv)（为何阴极出 H₂） |

> 🆕 **"解释为什么"题是 2026 年的新面孔**，两季各考一次，答案模板已写在 **4.1.6 答题模板**里。
> **表格题**的题干格式高度固定：`Complete Table X.1 to show …`
> 📌 **做表格题的诀窍：先把"产物"一列填完（元素名），再回头写"现象"一列 —— 不要一边想产物一边想现象。**

**⑥ 2026 年"整题电解"的样本（`0620/41` May/June 2026 Q5(a)，10 分）**
> 一道题串起四块内容：命名过程 [1] → 石墨两理由 [2] → H₂ 半方程 [2] → 为何阳极出 O₂ [2] → 导线中的粒子 [1] → 浓 aq NaCl 两极产物 [2]。
> **这就是本单元在 Paper 4 上的标准形态** —— 一个"电解套餐"把 4.1 的四五个考点一次考完。

## Paper 2（MCQ，40 分 / 45 min）

- **46 / 46 份卷都至少含 1 道电化学 MCQ**（第一轮 42/42 + 2026 新增 4 份全部含） —— 也就是说**你一定会遇到**。
- 每卷密度（关键词行数，非题数）：最低 `w20/21` 1 行，最高 `s24/23` 19 行、`w24/21` 17 行、`s22/21` 17 行。
- **高频 MCQ 题型**：稀/浓/熔融的产物对照、aq CuSO₄ 的电极替换、石墨为何适合作电极、导线/溶液里是谁在导电、电镀的三个物质、燃料电池的四条断言（反应物 / 产物 / 吸放热 / 能量转化）。
- **MCQ 里正负号会直接考**（P4 不会）：`0620/22` May/June 2023 Q9、`0620/21` May/June 2023 Q9 都是"哪个是阳极/阴极反应"，**失分率高**。

## Paper 6（Alternative to Practical，40 分 / 1 h）

电解在 Paper 6 里只有两种形态：

| 形态 | 代表题 | 分值 |
|---|---|---|
| **电镀规划题** | `0620/62` May/June 2025 Q4（银电镀 + 测镀层质量）；🆕 `0620/62` Feb/Mar 2026 Q4（银电镀，含 ER 点评） | 6 分 |
| **电解法提取金属（规划题）** | `0620/63` Oct/Nov 2021（cobalt）、`0620/62` May/June 2024（bismuth） | 6 分 |
| **观察题** | `0620/62` March 2021 Q1(c)（氯气 + 银）；🆕 `0620/33` Nov 2025 Q7（电镀实验，Core） | — |

> 提取金属的规划题官方答案结构（`0620/63` Oct/Nov 2021、`0620/62` May/June 2024）：
> `electrolysis (of solution)` / `specified inert material for electrodes (e.g. carbon, platinum)` / `metal obtained at the negative electrode/cathode`
> ⚠️ **【缺口】** Paper 6 只做了关键词扫查（第一轮），**未逐份通读**。若要把 4.1 的实践层挖到底，需另开一轮。
> 🆕 第二轮补入：`0620/62` Feb/Mar 2026 Q4 的 ER 点评（阳极金属的作用 = **补充被消耗的银离子**；电解质需要"含银离子 **且** 是水溶液"）已写入 4.1.10。

---

# 📊 真题实证（2020–2026 考频与官方答案）

> **数据说明**
> - 语料：**294 个 txt = 138 QP + 138 MS + 18 ER**。Paper 4 逐份核过 **46 份**（41/42/43），Paper 2 逐份核过 **46 份**（21/22/23）。
> - **Paper 4 是 46 份，不是任务书里的 54 份** —— m20–m26 每季**只有 component 42**，s/w 每季 41/42/43 齐全 ⇒ 7×1 + 13×3 = 46。
>   【第一轮语料（至 m25/s25）为 42 份 = 6×1 + 12×3；**2026 新增 m26/42 与 s26/41-43 共 4 份**（详见下节）。】
> - **ER 共 18 份**：m20 m21 m22 m23 m24 m25 m26 / s21 s22 s23 s24 s25 / w20 w21 w22 w23 w24 w25。
>   **只有 s20（考试取消）与 s26（尚未发布）没有 ER** —— 也就是说，**本文引用的每一道电解题都已有考官评论**。
>   【本笔记第一轮曾把 m20 / w23 / s24 / w24 / w25 记为"无 ER"，那是在 ER 语料补入之前的状态；现已全部核过，相关批次的新证据见各考点下的 `🆕` 引用。】
> - 标 `(Core)` 的是 Paper 1/3/5（非 Extended），但**判分原则通用**，故保留并标注。

## 头号数字

| 指标 | 数值 |
|---|---|
| Paper 4 有**结构化 4.1 电解题**的份数 | **28 / 42（67%）**【第一轮 42 份基数】；**2026 新增 3 份**（m26/42、s26/41、s26/43）→ **31 / 46（67%）** |
| Paper 4 有**纯电解题**（不含 Topic 9 铝提取） | **21 / 42（50%）** + 2026 的 **1 份**（m26/42 —— 只有阴极产物表，不含铝提取） |
| Paper 4 有**结构化 4.2 燃料电池题** | **5 / 42（12%），共 10 分**；2026 新增 **0 份** Paper 4（但新增 **2 道 MCQ**） |
| Paper 2 含**≥1 道电化学 MCQ** | **46 / 46（100%）**（第一轮 42/42，2026 新增 4 份全部含电化学 MCQ） |
| Paper 2 燃料电池 MCQ | **23 道 / 46 卷** |
| 4.1 分值（机器统计） | **443 / 3360 = 13.2%**，每卷 10.55 分（全主题第二，仅次于 6.3 的 16.0%） |
| 4.1 分值（独立审计修正） | **≈200 / 3360 ≈ 6.0%**，每卷 ≈4.8 分（审计判定机器统计**高估 ×2.4**） |
| 4.2 分值（机器统计 / 审计修正） | **30 分 ≈ 0.9%** / **≈10 分 ≈ 0.3%**（高估 ×8） |
| **最高频单一考点** | **`electrolysis` / `electrolyte` 的定义：16 份卷考过，永远 2 分（M1+M2）** |
| **次高频考点** | **半方程式：23 份卷考过，永远拆成 M1（电子位置）+ M2（整式）** |
| 出现最多的体系 | **aq CuSO₄（含铜电极）5 次**；浓 aq NaCl 4 次（+4 道 MCQ）；熔融铅卤化物 2 次；稀硫酸 2 次 |
| 电镀 | Paper 4 只考"阳极/阴极/电解质分别是什么"，**3 次，答案固定** |

> ⚠️ **两个分值口径并存是正常的**：机器统计是"整题计分"（一道 26 分的题里含 3 分电解，26 分都记到 4.1 头上）；审计修正是"按小问计分"。
> **做复习权重时看修正值，做"这章会不会考"判断时看覆盖率（67% / 100%）。**

## 考纲点 × 出现次数（Extended Paper 4）

| 考纲点 | 真题出现 | 备注 |
|---|---:|---|
| Core 1 定义 electrolysis | **13 份卷** | 最稳定考点，措辞固定 |
| （补充）定义 electrolyte | **3 份卷** | 考纲未列，真题自加 |
| Core 2 识别阳极/阴极 | **0 次结构化**（题干永远自带括号标注）；**仅 MCQ 与 Core 卷考** | Extended Paper 4 不单独考正负号 |
| Core 3 熔融 PbBr₂ | **1 次**（`0620/41` Oct/Nov 2021） | 但熔融卤化物共 5 次 |
| Core 3 浓 aqueous NaCl | **1 次结构化**（`0620/42` May/June 2021 Q4(e)）；**另有 4 道 MCQ** | 结构化题少，MCQ 多 |
| Core 3 稀 sulfuric acid | **2 次**（`0620/41` Oct/Nov 2020；`0620/42` Oct/Nov 2025 仅产物名） | |
| Core 4 阴极得金属/氢，阳极得非金属 | 内嵌于上表各题 | |
| Core 5 预测熔融二元化合物产物 | **4 次**（熔融 KCl、NaF、PbCl₂、KBr） | |
| Core 6 电镀改善外观/抗腐蚀 | **1 次**（`0620/43` May/June 2023 Q5(c)(ii)） | |
| Core 7 描述电镀方法 | **2 次 Paper 4** + **1 次 Paper 6** | Paper 4 只考"三物质各是什么" |
| Supp 8 电荷转移（电子/离子） | **6 次**（导线粒子、电解液粒子、电子流向箭头、为何熔融导电） | |
| Supp 9 aq CuSO₄ 惰性电极 + 铜电极 | **5 次** | |
| Supp 10 卤化物稀/浓预测 | **4 次**（稀 KBr、浓 aq NaBr、稀 NaF、浓 aq KI） | |
| Supp 11 阳极/阴极半方程式 | **23 份卷** | 第二高频 |
| 4.2 Core 1（H₂+O₂ 发电，唯一产物水） | **全部 5 份 Paper 4 + 全部 23 道 MCQ** | |
| 4.2 Supp 2（与汽油机相比的优缺点） | **3 份 Paper 4** + MCQ 若干 | |

> 🆕 **2026 新增批次的增量**（并入上表会破坏"42 份基数"的口径，故单列）：
> **Core 1 定义 +1**（s26/41 Q5(a)(i)）、**定义 electrolyte +1**（s26/43 Q5(a)(i)）、
> **Supp 8 电荷转移 +2**（s26/41 Q5(a)(v)、s26/43 Q5(a)(v)）、**Supp 10 稀/浓 +3**（m26/42 Q3(d)(ii)、s26/41 Q5(a)(vi)、s26/43 Q5(a)(i)）、
> **Supp 11 半方程式 +2**（s26/41 Q5(a)(iii)、s26/43 Q5(a)(iii)）、**Core 5 熔融产物 +1**（s26/43 Q5(a)(vi)）、
> **碳/铂惰性电极题 +2**（s26/41 Q5(a)(ii)、s26/43 Q5(a)(ii)）、**4.2 结构化题 +0**。
> ⇒ **2026 年两个 session 都在考同一批考点，没有一个新考点被引入** —— 这说明本单元的复习范围是稳定的。

## Paper 4 逐卷台账（第一轮 42 份，可核对；2026 新增 4 份见上节）

| 卷 | 4.1 电解题（含分值） | 混铝提取？ |
|---|---|---|
| `0620/42` Feb/Mar 2020 | Q2(a)(ii) 定义 [2]；**铝电解**：Q2(b)(iii) 两半方程 [4]；Q2(b)(iv) 阳极为何常换 [2] | ✅ |
| `0620/42` Feb/Mar 2021 | — | |
| `0620/42` Feb/Mar 2022 | Q4(d)(i) 命名过程 [1]；(ii) 为何需熔融/水溶液 [1]；Q4(e)(i) 电解盐水三产物 [3]；(ii) 熔融 NaCl 的不同产物 [1] | |
| `0620/42` Feb/Mar 2023 | — | |
| `0620/42` Feb/Mar 2024 | Q1(e)(ii) 命名过程 [1] | |
| `0620/42` Feb/Mar 2025 | Q2(d)(i) 命名过程 [1]；(ii) 熔融 KBr 阳极半方程 [2]；(iii) 稀 KBr 产物+现象 [5] | |
| `0620/41` May/June 2020 | — | |
| `0620/42` May/June 2020 | **Q5 整题 [8]**：定义、惰性电极材料、H₂ 半方程、四种离子、NaOH 如何生成 | |
| `0620/43` May/June 2020 | Q7(a) 定义 [2]；**铝电解**：Q7(c)(iii) 阳极产物 [1]；(iv) 阴极半方程 [2] | ✅ |
| `0620/41` May/June 2021 | Q3(c)(i) 定义 [2]；(ii) 熔融 KCl 两产物 [2]；(d)(i) 阴极半方程 [2]；(ii) 阳极产物 [1]；(iii) 剩余钾化合物 [1] | |
| **`0620/42` May/June 2021** | **Q4 整题 [12]**：稀 NaCl + 浓 NaCl 全套（定义/两半方程/现象/石蕊/另一电极材料） | |
| `0620/43` May/June 2021 | Q3(c)(i) 定义 [2]；(ii) 稀 NaF 两产物 [2]；(d)(i) 熔融 NaF 两产物 [2]；(ii) 半方程 [1] | |
| `0620/41` May/June 2022 | —（仅 6.x 卤素置换的 Cl₂/Br⁻ 半方程，**误报**） | |
| `0620/42` May/June 2022 | — | |
| `0620/43` May/June 2022 | Q5(b) 电镀铜：阳极/阴极/电解质 [3] | |
| `0620/41` May/June 2023 | Q5(a)(i) 定义 [2]；(ii) 石墨两理由 [1]；(iii) H₂ 半方程 [2]；(iv) 导线粒子 [1]；(v) 电解液粒子 [1]；(vi) 稀 KBr 两产物 [2] | |
| `0620/42` May/June 2023 | — | |
| `0620/43` May/June 2023 | Q5(a)(i) 电解液定义 [2]；(ii) 罗马数字 [1]；(iii) 颜色变化 [1]；(iv) Cu 半方程 [2]；(v) 阳极离子式 [1]；Q5(b) 铜阳极 [1]；Q5(c)(i) 电镀三物质 [3]；(ii) 两理由 [2] | |
| `0620/41` May/June 2024 | Q3(c)(i) 定义 [2]；(ii) H₂ 半方程 [2] | |
| `0620/42` May/June 2024 | — | |
| `0620/43` May/June 2024 | Q3(c)(i) 定义 [2]；(ii) O₂ 半方程 [2] | |
| `0620/41` May/June 2025 | — | |
| **`0620/42` May/June 2025** | **Q3(a)–(c) [9]**：填空定义 [3]；Pt 电极四问 [6]；Cu 电极两问 [2]；**另** Q3(d) 铝提取 [4] | ✅ |
| `0620/43` May/June 2025 | — | |
| `0620/41` Oct/Nov 2020 | **Q5(a) 整段 [7]**：定义 [2]；为何惰性 [1]；稀 H₂SO₄ 两产物 [2]；H₂ 半方程 [2] | |
| `0620/42` Oct/Nov 2020 | Q2(f)(ii) 熔融 NaCl 阳极产物 [1]；(iii) 变化类型 + 电子转移 [2] | |
| `0620/43` Oct/Nov 2020 | Q5(d)(i) 定义 [2]；(ii) 需先做什么 [1]；(iii) Na 半方程 [1] | |
| **`0620/41` Oct/Nov 2021** | **Q3 整题 [13]**：浓盐酸 + 熔融 PbBr₂ | |
| `0620/42` Oct/Nov 2021 | — | |
| **`0620/43` Oct/Nov 2021** | **Q2 整题 [12]**：电解液定义 + 表格（aq CuSO₄ / 浓 aq NaBr）+ H₂ 半方程 + 石墨 | |
| `0620/41` Oct/Nov 2022 | — | |
| `0620/42` Oct/Nov 2022 | — | |
| `0620/43` Oct/Nov 2022 | Q3(b) 定义 [2]；**铝电解**：Q3(c)(ii) Al 半方程 [2]；(iii) 碳阳极更换 [2] | ✅ |
| `0620/41` Oct/Nov 2023 | **铝电解**：Q2(c)(iii) 阴极半方程 [2]；(iv) 阳极更换 [2] | ✅ |
| `0620/42` Oct/Nov 2023 | Q4(b)(i) 为何熔融 [1]；(ii) 阳极半方程 [2]；(iii) 氯气检验 [2]；(iv) 阴极所见 [1] | |
| `0620/43` Oct/Nov 2023 | — | |
| `0620/41` Oct/Nov 2024 | **Q3(e) 整段 [10]**：aq CuSO₄ 石墨电极六问 | |
| `0620/42` Oct/Nov 2024 | **铝电解**：Q2(d)(i) 电子数 + 阴极半方程 [3]；(ii) 为何氧化 [1]；(iii) 为何 CO₂ 非 O₂ [2] | ✅ |
| **`0620/43` Oct/Nov 2024** | **Q2 整题 [11]**：定义 + 表格（浓 aq KI / aq CuSO₄）+ O₂ 半方程 + Cu 电极 | |
| `0620/41` Oct/Nov 2025 | — | |
| `0620/42` Oct/Nov 2025 | Q4(a)(vi) 稀硫酸电解两气体产物 [2] | |
| `0620/43` Oct/Nov 2025 | **铝电解**：Q3(a)(i) 铝化合物 [1]；(ii) 溶剂 [1]；(iii) 阳极材料 [1]；(iv) Al 半方程 [2] | ✅ |

**统计**
- 结构化 4.1 题 **28/42（67%）**，其中**完全不含铝提取 21/42（50%）**，与铝提取混考 **7 份**。
- **含定义题的卷 = 16 份**（`electrolysis` 13 份 + `electrolyte` 3 份）—— **全主题最高频**。
- 另有 **5 份**是 1 分的"命名该过程 = electrolysis"。
- **含半方程式的卷 = 23 份。**
- ⚠️ **`cobalt` / `manganese` 与 Topic 4 无关**：`cobalt` 在 ER 里出现 20 次，**全部是"无水氯化钴检水"与过渡元素性质**；`manganese` 只出现在元素周期表数据行。

## 🆕 2026 新增批次（m26 / s26，4 份 Paper 4 + 4 份 Paper 2）

> **这 4 份 Paper 4 是在第一轮语料之后补入的**，由本笔记第二轮逐份核过。ER 方面：**m26 有 ER、s26 没有**（尚未发布）。

### Paper 4 新增台账

| 卷 | 4.1 电解题（含分值） | 混铝提取？ |
|---|---|---|
| **`0620/42` Feb/Mar 2026** | Q3(d)(i) 惰性非金属 + 惰性金属电极 [2]；(ii) **熔融 / 稀 / 浓 NaCl 的阴极产物表** [3] | |
| **`0620/41` May/June 2026** | **Q5(a) 一整题 [10]**：(i) 命名该过程 [1]；(ii) 石墨作电极两理由 [2]；(iii) H₂ 半方程 [2]；(iv) **解释为何阳极产生氧气** [2]；(v) 导线中的粒子 [1]；(vi) 浓 aq NaCl 两极产物 [2]；**另** Q5(b) 铝提取 [3] | ✅（Q5(b)） |
| `0620/42` May/June 2026 | — **无电解/燃料电池内容**（该卷只有溴离子置换与晶格结构） | |
| **`0620/43` May/June 2026** | **Q5(a) 一整题 [9]**：(i) 电解质定义 [1]；(ii) 电极的两条性质 [2]；(iii) Br₂ 半方程 [2]；(iv) **解释为何阴极产生氢气** [2]；(v) 电解液中负责导电的粒子 [1]；(vi) 熔融 LiBr 两极产物 [2] | |

**新增批次的四点结论**

1. **s26 的两道电解大题都新加了"解释为什么"**（`Explain why oxygen is produced at the anode` / `Explain why hydrogen gas is produced at the cathode`）—— **这是 2020–2025 年从未出现的新题型**，答案模板已整理进 4.1.6。（m26/42 的电解部分是"命名 + 填表"，不含"解释"。）
2. **s26/41 Q5(a) 一道题串起四块内容**（命名过程 + 电极材料 + 半方程 + 导线粒子 + 稀/浓产物对比），与 2020–2025 的"整题电解"结构完全同款 —— **说明这个考法稳定，不是偶然**。
3. **m26/42 Q3(d)(ii) 是全新的"三形态对照表"**，把 4.1.4 与 4.1.6 的分界直接做成表格。
4. **Paper 4 仍然没有 4.2 燃料电池的结构化题**（2026 两季都没有）—— 燃料电池继续只在 Paper 2 出现。

### Paper 2 新增电化学 MCQ（11 道，答案已从 MS 逐题核出）

| 卷/题 | 题干要点 | 答案 |
|---|---|---|
| `0620/22` Feb/Mar 2026 Q10 | 电解装置：电极 1 氧化、电极 2 还原；电解液中阳离子向哪移动 | **A** |
| `0620/22` Feb/Mar 2026 Q11 | **燃料电池的优点 + 汽油机的优点（两栏对照）** | **C** |
| `0620/21` May/June 2026 Q12 | 浓 aq NaCl 与稀硫酸的电极产物对照 | **B** |
| `0620/21` May/June 2026 Q13 | **熔融 NaCl 中离子与电子的移动方向（四张装置图）** | **A** |
| `0620/21` May/June 2026 Q14 | 关于氢燃料电池哪条对 | **A** |
| `0620/22` May/June 2026 Q11 | **电镀装置：阳极 / 阴极 / 电解质三栏匹配（铜匙镀银）** | **A** |
| `0620/22` May/June 2026 Q12 | 稀硫酸电解，阳极产物是什么（含 sulfur / sulfur dioxide 干扰项） | **B** |
| `0620/22` May/June 2026 Q13 | 铜电极电解 aq CuSO₄：阴极质量 / 阳极质量 / 溶液颜色 | **D** |
| `0620/23` May/June 2026 Q14 | 稀硫酸电解的两极产物行 | **C** |
| `0620/23` May/June 2026 Q15 | **物质 Z：正极气体漂白石蕊、负极气体爆鸣 —— Z 可能是什么（浓 CuCl₂ / 浓 NaCl / 稀 KCl 三选）** | **D**（2 only） |
| `0620/23` May/June 2026 Q16 | 铝的提取 + 冰晶石作用（Topic 9） | **C** |

> 📌 **两道最值得记住的新题**：
> ① **`0620/23` May/June 2026 Q15（答案 D）** —— 一道题同时考"**阳极：浓卤化物出 Cl₂ / 稀溶液出 O₂**"与"**阴极：不活泼金属离子出金属 / 活泼金属离子出 H₂**"。**这是 4.1.6 整节的浓缩版。**
> ② **`0620/22` May/June 2026 Q11（答案 A）** —— 电镀的三物质匹配表（`anode: silver` / `cathode: copper spoon` / `electrolyte: aqueous silver nitrate`），三个干扰项正好是 4.1.10 的三大坑。

## 官方判分规则（从答案表反推）

| 代码 | 在本主题的形态 | 实例（逐字） |
|---|---|---|
| **`M1` `M2` `M3`…** | **主力机制**。电解题几乎每个空都拆成独立得分点；一个方程 2 分 = 2 个独立判断 | `M1 breakdown by (the passage of) electricity(1)` / `M2 of an ionic compound in molten or aqueous (state) (1)` |
| **`any two from`** | 只在"两理由/两差异"类题出现 | `2(c)(ii) one mark each for any two of: colour remains constant / no bubbles at the anode / anode dissolves` |
| **`any one of`** | 4.2 优点/缺点题**永远是一长串并列** | `advantage: any one of: water is the only product / no carbon dioxide produced / more efficient` |
| **`any 6 from`** | Paper 6 规划题（MP1–MP7） | `0620_m25_ms_62.txt` 第 220 行 |
| **`OR`** | **并列接受**，两条任取其一都给分 | `3(b)(ii) becomes paler blue / or / becomes colourless`；`M1 ... losing electrons OR H2O + O2 as only products ... on RHS` |
| **`ignore`** | 全库 127 次，但**电解答案表内不出现** | — |
| **`ecf`** | 180 次，**几乎全是每卷 2–3 次的前言样板句**，电解答案表内不出现 | — |
| **`ora`** | 29 次，电解题内**不出现** | — |
| **`TV` / `BOD`** | **全库 0 次 / 答案表 0 次** | — |
| **`do not accept`** | 化学 MS **不用这个字面**；改用 `R`（reject）或在 ER 里说 `not credited` / `not accepted` | ER：`A gas is formed` was not credited（`0620/32` March 2021） |

**五条判分要点（背下来会直接改变你的写法）**

1. **定义题 = 2 个独立 M 点**，写成一句也要同时含 `breakdown by electricity` **＋** `ionic compound` **＋** `molten or aqueous`。
2. **半方程式题 M1 只判"电子在哪一侧"**，M2 判整式。所以 `2H[⁺] + 2e[⁻] [→] H[₂]` 即使系数写错，仍可能拿到 M1。
3. **"描述所见"题只接受现象，不接受产物名或结论**。接受：`fizzing` / `effervescence` / `bubbles` / `green gas` / `pink AND solid` / `silver/grey solid` / `bubbles of orange/brown gas`。拒绝：`a gas is formed` / `bromine forms` / `solid lead` / `bromine bubbles`。
4. **`AND` 是硬的**：`(shiny) grey AND solid`、`pink AND solid` —— **两个形容词都要写**。
5. **颜色题给两个可接受答案**（`becomes paler blue` **或** `becomes colourless`）—— **写对一个即可，不必两个都写**。

## Paper 2 电化学 MCQ 全量答案表（其余题目）

> 4.1.6 与 4.1.7 已列出"稀/浓/熔融对照"与"aq CuSO₄"两组；
> 下表是**剩下的全部**：定义、电荷转移、电极材料、电镀、以及跨主题的铝提取题（后者属 Topic 9，列出只为展示**同一半方程判分逻辑**）。

| 卷/题 | 题干要点 | 答案 |
|---|---|---|
| `0620/22` Feb/Mar 2020 Q27 | 铝提取，哪条对（阳极生成 CO₂） | **D** |
| `0620/22` Feb/Mar 2021 Q9 | `x O[²⁻] [→] O[₂] + y e[⁻]`，求 x/y | **D**（2 / 4） |
| `0620/22` Feb/Mar 2022 Q14 | 银电镀：物体是阴极、另一电极是银 | **D** |
| `0620/22` Feb/Mar 2022 Q26 | 铝提取（Al 在阴极生成） | **A** |
| `0620/22` Feb/Mar 2023 Q7 | 石墨为何适合作电极 | **D**（has mobile electrons） |
| `0620/22` Feb/Mar 2024 Q30 | 铝提取 | **C**（阳极生成 CO₂） |
| `0620/22` May/June 2021 Q27 | 铝提取阳极反应 | **C**（`2O[²⁻] [→] O[₂] + 4e[⁻]`） |
| `0620/21` May/June 2022 Q23 | 冰晶石作用 + 阴极半方程 | **C** |
| `0620/21` May/June 2022 Q32 | 硫酸制造/电解流程图 | **B** |
| `0620/23` May/June 2022 Q9 | 铝提取半方程 + 冰晶石作用 | **C** |
| `0620/21` May/June 2023 Q28 | 铝电解碳阳极质量变化及原因 | **A**（decreases / carbon reacts to form CO₂） |
| `0620/22` May/June 2023 Q28 | 冰晶石为何用 | **A**（dissolves the aluminium oxide） |
| `0620/23` May/June 2023 Q11 | 铝提取图 | **C** |
| `0620/21` May/June 2024 Q14 | 关于电解哪条对（离子化合物被分解） | **C** |
| `0620/22` May/June 2024 Q10 | 关于电解哪条对（**电子在外电路流向阴极**） | **B** |
| `0620/23` May/June 2024 Q26 | 电解质是什么（bauxite dissolved in molten cryolite） | **B** |
| `0620/21` May/June 2025 Q10 | 钢件镀铜图 | **C** |
| `0620/23` May/June 2025 Q11 | 两条关于氢的陈述 | **A** |
| `0620/22` Oct/Nov 2020 Q31 | 铝提取装置 | **B** |
| `0620/22` Oct/Nov 2021 Q10 | 铁镀锌：正极/负极/电解质 | **D** |
| `0620/21` Oct/Nov 2022 Q10 | 电极 1 氧化、电极 2 还原：电子与正离子移动方向 | **A** |
| `0620/21` Oct/Nov 2022 Q24 | 铝提取哪条对 | **D**（Graphite is used for both the positive and negative electrodes） |
| `0620/21` Oct/Nov 2023 Q28 | 铝提取两电极半方程 | **D** |
| `0620/21` Oct/Nov 2024 Q11 | 关于电解装置哪条对 | **B**（Hydrogen forms at the cathode in some electrolysis reactions） |
| `0620/21` Oct/Nov 2024 Q25 | 铝提取装置 | **B** |
| `0620/22` Oct/Nov 2024 Q26 | 冰晶石作用 | **A**（to lower the operating temperature） |
| `0620/23` Oct/Nov 2024 Q20 | `Al[³⁺] + 3e[⁻] [→] Al` 氧化数变化与反应类型 | **A** |
| `0620/21` Oct/Nov 2025 Q29 | 铝提取哪条对 | **C**（carbon in graphite anode reacts with oxygen forming CO₂） |
| `0620/22` Oct/Nov 2025 Q29 | 铝提取半方程 + 哪个电极需更换 | **B** |

> ⚠️ 表中带 `见下` 的一行是誊写残留，对应 `s21/22 Q27`（铝提取阳极反应，答案 **C**），**请忽略该行直接看 s21/22 Q27 那条**。
> **【缺口】** Paper 2 的全部 1680 题中，本语料只逐题看过带标签的 460 题；**上表是其中电化学部分的逐题核对结果**，非全量普查。若某题不在表中，不代表它不存在。

---

# ⚠️ 高频失分点汇总（考前一晚扫这一张表）

| # | 陷阱（你会犯的） | 正确做法（判分标准） | 官方出处 |
|---|---|---|---|
| 1 | 定义里漏"熔融或水溶液" | 必须写 `ionic compound` **+** `molten or aqueous` | ER `0620/41` O/N 2020；ER `0620/43` M/J 2021 |
| 2 | 用 `separation` 代替 `breakdown` | `separation` = 物理变化，**0 分**；只写 `breakdown` | ER `0620/43` M/J 2021；ER `0620/41` O/N 2020 |
| 3 | 写 `current` 而不是 `electric current` | 必须 `by the passage of electricity` / `an electric current` | ER `0620/43` M/J 2021 |
| 4 | 写 `breakdown into ions` / `separation into ions` | 官方明列**不给分** | ER `0620/41` O/N 2020 |
| 5 | 把 `electrolyte` 答成 `electrolysis` | `An electrolyte is a substance/an ionic compound which is molten or aqueous` | ER `0620/43` O/N 2021 |
| 6 | 定义题举例子代替定义（"NaCl solution"） | 要写**类别**（ionic compound + molten/aqueous） | ER `0620/42` M/J 2021 |
| 7 | 观察题只写产物/结论 | `'A gas is formed' was not credited`；`bromine forms` / `solid lead` / `bromine bubbles` 全 0 | ER `0620/32` Mar 2021；ER `0620/41` O/N 2021 |
| 8 | 写 `gas given off` / `gas formed` | 这是结论，不是现象 | ER `0620/42` M/J 2021 |
| 9 | 熔融题里答 `hydrogen` / `oxygen` | 熔融物里只有该化合物的元素 ⇒ 答金属 + 非金属 | ER `0620/41` O/N 2021；ER `0620/32` Mar 2023/2024 |
| 10 | 水溶液题里答 `sodium` / `potassium` | 活泼金属离子在水溶液里**永远得不到金属**，阴极是 `hydrogen` | ER `0620/42` M/J 2021；ER `0620/41` M/J 2023 |
| 11 | 稀卤化物阳极答 `bromine` | 稀 → `oxygen`（+ `water`）；浓 → 卤素 | ER `0620/41` M/J 2023；MS `0620/42` F/M 2025 |
| 12 | 浓 NaCl 阳极答 `effervescence` | 要写 `green gas` | ER `0620/42` M/J 2021 |
| 13 | 离子名当产物名 | `chlorine` 不是 `chloride`；`bromine` 不是 `bromide`；`fluorine` 不是 `fluoride` | 4 处 ER（见 4.1.9） |
| 14 | 半方程式电子写右边 / 写成减法 | `Cu[²⁺] + 2e[⁻] [→] Cu` ✅；`Cu[²⁺] [→] Cu[–] 2e[⁻]` ❌（数学等价也不给满分；**2026 年起还原型只给 1 分 salvage、氧化型给满分** —— 见 4.1.8 陷阱⑧⑨） | ER `0620/43` M/J 2023；ER `0620/42` M/J 2021；MS `0620/41`/`0620/43` M/J 2026 |
| 15 | 氧化写成还原（负离子得电子） | 阳极永远是**失**电子：`2Br[⁻] [→] Br[₂] + 2e[⁻]` | ER `0620/42` F/M 2025 |
| 16 | 写 `H` / `Cl` / `Br` 单原子 | 必须是 `H[₂]` / `Cl[₂]` / `Br[₂]` | ER `0620/41` O/N 2020 & O/N 2021；ER `0620/42` F/M 2025 |
| 17 | 半方程里写进旁观离子（K⁺、SO₄²⁻） | 半方程只出现**放电的那一对**物种 + e⁻ | ER `0620/42` F/M 2025 |
| 18 | 氢离子电荷写错 / 氢物种不带电 | `2H[⁺] + 2e[⁻] [→] H[₂]` | ER `0620/41` O/N 2021；ER `0620/41` M/J 2023 |
| 19 | 说电子在电解液里跑 | 电解液里跑的是**离子**；导线里跑的是**电子** | ER `0620/42` F/M 2022；MCQ `0620/21` M/J 2024 Q14 |
| 20 | 说"离子需要自由 / free" | 必须写 `mobile`（或 able to move / able to flow） | ER `0620/42` F/M 2022 |
| 21 | 石墨/铂"两理由"只写一个 | `conducts electricity` **+** `inert` 两条都要 | ER `0620/41` M/J 2023 |
| 22 | 写 `low reactivity` 代替 `inert`；只写 `good conductor` | `low reactivity` 不够；要写 `electrical conductor` | ER `0620/43` O/N 2021；ER `0620/41` O/N 2021 |
| 23 | 熔融题与铝电解混淆（答"电极不会磨损"） | 本题只问"为何用惰性电极" | ER `0620/41` O/N 2020 |
| 24 | 电镀：工件接阳极 | 工件 = **阴极**（负极）；镀层金属 = 阳极 | ER `0620/62` M/J 2025 |
| 25 | 电镀：阳极用石墨 | 阳极必须是**镀层金属本身** | ER `0620/43` M/J 2023 Q5(c)(i) |
| 26 | 电镀：电解质写熔融盐 / 不溶盐 | 必须写 **aqueous solution** of the metal salt | ER `0620/62` M/J 2025；ER `0620/43` M/J 2022 |
| 27 | 电镀：图里漏画电源 / 给阴极标正电荷 | 完整回路 + 阴极负、阳极正 | ER `0620/62` M/J 2025 |
| 28 | 电镀：漏掉"洗涤 + 烘干 + 再称重" | MP6 + MP7 各占 1 分 | MS `0620/62` M/J 2025 |
| 29 | 电镀理由只写一条 | 两条：`prevent corrosion` + `improve appearance` | MS `0620/43` M/J 2023 Q5(c)(ii) |
| 30 | 燃料电池：把 H₂/O₂ 说成产物 | **是反应物（inputs）**，产物只有 water | ER `0620/12` Mar 2023 |
| 31 | 燃料：把产物写成 `H₂O` 当"反应物"或答 `H2O` 是什么反应物 | 反应物是 `hydrogen` 和 `oxygen` | ER `0620/13` F/M 2025 |
| 32 | 燃料电池方程不配平 / 写成 H₂O₂ | `2H[₂] + O[₂] [→] 2H[₂]O` | MCQ `0620/22` M/J 2025 Q12；`0620/21` F/M 2021 Q15 |
| 33 | 说燃料电池反应吸热 | **放热** | MCQ `0620/22` F/M 2024 Q13；`0620/23` O/N 2024 Q13 |
| 34 | 说氢在燃料电池里被**还原** | 氢被**氧化**（0 → +1） | MCQ 三处（4.2.1 陷阱⑧） |
| 35 | 优点答"无污染 / 可再生" | 要具体：`water is the only product` / `no CO₂ produced` / `more efficient` | ER `0620/41` M/J 2023 |
| 36 | 缺点答"氢易燃易爆"或"效率低" | 都**不被接受**；要写储存难 / 高压 / 加氢站少 | ER `0620/43` M/J 2023 |
| 37 | 缺点题答成优点 | 读题！ | ER `0620/43` M/J 2023 |
| 38 | 能量转化方向写反 | `chemical energy [→] electrical energy` | 4.2.1 |
| 39 | 安全题答"触电" | 实验室用低压直流，**没有触电风险**；答通风橱 / 氯气有毒 | ER `0620/62` Mar 2021 |
| 40 | 选择题里被"换电极材料"骗（石墨 vs 铜） | 先圈出题目给的电极材料，再选产物 | ER `0620/22` Mar 2024 |
| 🆕 41 | 定义里漏掉 `ionic` | 四个要素里**最常被漏的就是它** | ER `0620/41` M/J 2024；ER `0620/43` M/J 2024；ER `0620/32` F/M 2026 |
| 🆕 42 | 说"离子需要 free / 自由" | 必须 `mobile`（`free ions` / `delocalised ions` **0 分**） | ER `0620/42` O/N 2024；ER `0620/41` O/N 2024 |
| 🆕 43 | 说"电子需要 mobile"才能导电 | 熔融/溶液导电靠**离子**移动，不是电子移动 | ER `0620/42` O/N 2023 Q4(b)(i) |
| 🆕 44 | 答"电极名 / 离子名"代替"产物名" | 问 product 就写元素名；`anode`/`cathode`、`anion`/`cation`、`Na[⁺]` 都不给分 | ER `0620/31` O/N 2024；ER `0620/42` F/M 2026 |
| 🆕 45 | 现象题只写"颜色"不写"状态" | 官方判据：**需要一个颜色 + 一个状态**（`grey AND solid`） | ER `0620/42` O/N 2023 Q4(b)(iv) |
| 🆕 46 | "两差异"题答成"两次都会发生的现象" | `cathode gets larger` **两次实验都会** ⇒ 不算差异；`the electrode dissolves` 没写 **anode** ⇒ 不给分 | ER `0620/41` O/N 2024 Q3(e)(vi) |
| 🆕 47 | 用"质量变化"当观察 | `the mass of the anode would get smaller` **是事实、不是观察** | ER `0620/41` O/N 2024 Q3(e)(vi) |
| 🆕 48 | 石墨/铂题答 `high melting point` / `cheap` / `insoluble` / `conducts electricity when molten` | 只有 `inert` + `good conductor of electricity` 两条 | MS `0620/41` M/J 2026 Q5(a)(ii)；ER `0620/41` O/N 2024 Q3(e)(ii) |
| 🆕 49 | 把"惰性电极"当成铜 | 非金属 = `graphite`；金属 = `platinum`；**copper 会溶解，不是惰性** | MS `0620/42` F/M 2026 Q3(d)(i)；ER `0620/42` F/M 2026 Q3(d)(i) |
| 🆕 50 | 稀硫酸电解答 `sulfur` / `sulfur dioxide` | 只有 `hydrogen`（阴极）与 `oxygen`（阳极） | ER `0620/31` O/N 2024；ER `0620/31` O/N 2025 |
| 🆕 51 | 电镀题答"提高强度" | 理由只有 `prevent corrosion` + `improve appearance`；**镀层太薄，改不了强度** | ER `0620/13` M/J 2024 Q11 |
| 🆕 52 | 燃料电池的能量形式答"热" | 是 **electricity**（`chemical energy [→] electrical energy`） | ER `0620/11` M/J 2024 Q11 |
| 🆕 53 | 问 word equation 却写 symbol equation | 题目要什么就写什么；写符号方程常因符号错而丢分 | ER `0620/42` Mar 2020 Q1(e) |
| 🆕 54 | 燃料电池题答 `carbon` 与氢反应 | 是 **oxygen** | ER `0620/41` O/N 2024 Q5(a)(i) |

---

# 🧠 一页纸速记（最后三天就看这一页）

## ① 一个定义（背英文原句）

```
Electrolysis is the breakdown of an ionic compound,
when molten or in aqueous solution,
by the passage of an electric current.

关键词四件套：breakdown ｜ ionic compound ｜ molten or aqueous ｜ by the passage of electricity
⚠️ 2024–2026 年官方点名最多的漏词 = ionic（其次是 molten or aqueous）
```
**electrolyte** = `An electrolyte is an ionic compound which is molten or aqueous and which conducts electricity.`

## ② 电极与粒子（四个"谁"）

```
阳极 anode   = positive electrode     → 氧化 oxidation  → 非金属 / 阳极溶解
阴极 cathode = negative electrode     → 还原 reduction  → 金属 或 氢
导线里的电荷 = electrons
电解液里的电荷 = ions（mobile ions 才能导电）
```

## ③ 产物判断决策树（最有用的一张图）

```
先圈题干里的 molten / aqueous / dilute / concentrated！

【molten】二元化合物 → 阴极 = 金属，阳极 = 非金属
           （绝不能出现 H₂ 或 O₂）

【aqueous】阴极：溶液中是 Cu²⁺/Ag⁺ 等不活泼金属离子？ → 金属
                  否则（Na⁺/K⁺/Mg²⁺/Al³⁺…）        → hydrogen
          阳极：卤离子"浓"？ → Cl₂ / Br₂ / I₂
                  否则       → oxygen（+ water）
```

## ④ 五大体系速查（产物 + 现象）

| 体系 | 阴极 | 阴极现象 | 阳极 | 阳极现象 |
|---|---|---|---|---|
| **三种 NaCl 的阴极对照**（2026 新题） | **molten → sodium；稀 → hydrogen；浓 → hydrogen** | | | |
| molten PbBr₂ | lead | silver/grey solid | bromine | bubbles of orange/brown gas |
| molten PbCl₂ | lead | (shiny) grey AND solid | chlorine | — |
| **稀** aq NaCl / 稀 KBr / 稀 NaF | hydrogen | fizzing / bubbles | **oxygen (+ water)** | bubbles |
| **浓** aq NaCl | hydrogen | fizzing | **chlorine** | **green gas** |
| 浓 aq NaBr / 浓 aq KI | hydrogen | colourless bubbles | bromine / iodine | orange-brown liquid / brown solution or black solid |
| aq CuSO₄（**Pt/C 电极**） | copper | pink AND solid | oxygen | bubbles；溶液 becomes paler blue |
| aq CuSO₄（**铜电极**） | copper | 阴极增重 | **阳极溶解** | 无气泡；溶液**颜色不变** |

## ⑤ 五个必背半方程式

```
阴极 2H[⁺] + 2e[⁻] [→] H[₂]
阳极 4OH[⁻] [→] 2H[₂]O + O[₂] + 4e[⁻]
阳极 2Cl[⁻] [→] Cl[₂] + 2e[⁻]
阳极 2Br[⁻] [→] Br[₂] + 2e[⁻]
阴极 Cu[²⁺] + 2e[⁻] [→] Cu
阳极 Cu [→] Cu[²⁺] + 2e[⁻]      （铜电极时）
```
**铁律：电子绝不能写在右边的减法里；绝不能出现旁观离子；绝不能写单原子 H/Cl/Br。**
⚠️ **2026 年判分口径（MS `0620/41`、`0620/43` May/June 2026）**：
- `2H[⁺] + 2e[⁻] [→] H[₂]` 写成 `2H[⁺] [→] H[₂] [–] 2e[⁻]` → **只有 1 分 salvage**（拿不到第二分）
- `2Br[⁻] [→] Br[₂] + 2e[⁻]` 写成 `2Br[⁻] [–] 2e[⁻] [→] Br[₂]` → **2026 年给 2 分**（氧化方向放宽了）
- 左边物种与电子**任意系数、任意正电荷**都给 M1（如 `H[₂][²⁺] + 4e`）；产物写成 `H[₂]O` 则 M2 不给

## ⑥ 电镀三件套

```
阳极 = 镀层金属（silver / copper）
阴极 = 工件（spoon）
电解质 = 该金属的可溶盐的【水溶液】（aqueous silver nitrate）
理由 = prevent corrosion + improve appearance
```

## ⑦ 燃料电池七条

```
反应物： hydrogen and oxygen          （不是产物！）
唯一化学产物： water
方程： 2H[₂] + O[₂] [→] 2H[₂]O      （别写成 H₂O₂，别忘配平）
能量： chemical energy [→] electrical energy
优点（任一条）： water is the only product / no CO₂ produced / more efficient
缺点（任一条）： needs high pressure to store hydrogen / hard to store /
                heavy tanks / fewer filling stations
绝不接受： 氢易燃危险 ｜ 效率低 ｜ 无污染 / 可再生（空泛）
⚠️ 与氢反应的物质是 OXYGEN，不是 carbon（ER w24/41 Q5(a)(i)）
⚠️ 能量形式是 ELECTRICITY，不是 heat（ER s24/11 Q11）
⚠️ 题目要 word equation 就写文字方程，别写符号方程（ER m20/42 Q1(e)）
```

## ⑧ 现象题给分词 vs 不给分词

```
✅ fizzing ｜ effervescence ｜ bubbles ｜ green gas ｜ pink AND solid ｜ (shiny) grey AND solid
❌ a gas is formed ｜ gas given off ｜ bromine forms ｜ solid lead ｜ the electrode gets bigger
⚠️ 公式：现象 = 一个【颜色】+ 一个【状态】（grey AND solid / pink AND solid）
❌ 新增黑名单：copper seen ｜ bronze ｜ pink metal ｜ copper metal ｜ lead forms ｜ solid forms ｜ lead is deposited
```

---

# 🔗 延伸资源

- **考纲原文**：`0620 Chemistry syllabus for 2026, 2027 and 2028` · Section **4.1 Electrolysis** + **4.2 Hydrogen–oxygen fuel cells**（学校指定 PDF，Version 1, September 2023）
- **本单元语料**：**294 个 txt = 138 QP + 138 MS + 18 ER**；Paper 4 逐份核过 **46 份**（41/42/43），Paper 2 逐份核过 **46 份**（21/22/23），Paper 6 关键词扫查
- **ER 覆盖**：18 个 session（m20–m26 / s21–s25 / w20–w25）；**仅 s20（考试取消）与 s26（尚未发布）缺失**
- **配套 research 文件**（本笔记的全部证据来源）：
  - [syllabus-topics-4-5-6.md](_research/syllabus-topics-4-5-6.md) —— 官方考纲条目逐字抄录（4/5/6）
  - [topic4-electrochemistry.md](_research/topic4-electrochemistry.md) —— 本单元的 91 KB 真题挖掘（MS 原文 + ER 原文 + 考频 + 陷阱）
  - [frequency-audit.md](_research/frequency-audit.md) —— 主题分类器独立审计（本笔记"修正分值"的来源）
  - [corpus-and-method.md](_research/corpus-and-method.md) —— 语料构成与统计方法
  - [reference-notes-comparison.md](_research/reference-notes-comparison.md) —— 外部参考笔记的逐条核查（本笔记避开的坑）

---

> ⚠️ **本笔记的缺口**（据实记录，不猜）：
> 1. **s20 无 ER（官方考试取消）、s26 无 ER（尚未发布）** —— 其余 18 个 session 的考官报告已全部核过。
>    【修正记录：本笔记第一轮曾把 m20 / w23 / s24 / w24 / w25 也列为"无 ER"，那是 ER 语料补入前的状态，现已在各考点补上 `🆕` 引用。】
> 2. **Paper 6 只做了关键词扫查**（第一轮），4.1 的实践层可能仍有未挖出的考点。
> 3. **Paper 2 未逐题普查** —— 46 份卷里的电化学 MCQ 是按**关键词命中**提取的，不是逐题判定。




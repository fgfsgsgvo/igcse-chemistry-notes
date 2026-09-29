# Unit 5 — Chemical energetics 化学能量学

> **考纲**：Cambridge IGCSE Chemistry **0620** · Syllabus **2026–2028** · Section **5.1**
> 本主题**只有一节**，共 **8 条要求**：Core 3 条 + Supplement 5 条。是本套笔记里**最小**的一个单元。
> **试卷**：Paper 2（MCQ，30%）+ Paper 4（Theory，50%）+ Paper 6（实验卷，20%）
> **语料**：**46 份 Paper 4**（m20–m26 七个 session 只提供 /42；s20–s26 与 w20–w25 提供 41/42/43）+ Paper 2 + **18 份 Examiner Report**（2020–2026；**只有 s20「考试取消」与 s26「尚未发布」没有 ER**），全部逐字检索。
> **修订记录**：初版基于 42 份 Paper 4 / 17 份 ER（2020–2025）。**2026-09 语料扩充后**新增 `0620_m26_er.txt` 与 m26/s26 的四份 Paper 4，已并入本笔记：**+2 道键能计算题、+2 道路径图题、+3 条 2026 新评分规则**（详见 5.1.4 与 5.1.6）。

## 本单元的战术定位

| 事实 | 数据 |
|---|---|
| Paper 4 中含 Topic 5 小问的卷数 | **27 / 46（≈59%）** |
| **最高频子话题：用键能计算 ΔH** | **18 / 46（39%）**，合计 **59 分**（3 分 × 13 + 4 分 × 5） |
| 第二高频：reaction pathway diagram | **8 / 46**（7 份要求**画**、1 份要求**读**） |
| ΔH 定义 | 5 / 46（`enthalpy change (of reaction)` 一个词） |
| Ea 定义 | 2 / 46（但 **w23 与 w24 两份 ER 都点名**） |
| exo/endo 由 **ΔH 的符号**判定 | **6 / 46**（m23/42、m25/42、w24/43、w25/43、**m26/42、s26/42**） |
| 出题形态 | **从不单独成题**。永远寄生在别人的大题里（Haber、有机加成、电解），固定 3–4 分一小问 |
| 审计修正后的真实权重 | ≈115 marks / 3360 = **3.4%**（每份 Paper 4 平均约 2.7 分）。分类器原始记录 17.8%，**高估 5 倍**（见 `_research/frequency-audit.md`） |

> **一句话**：这个单元只有三件事值钱 ——
> ① **键能算 ΔH**（几乎每季都有，方法分与答案分分开给，是最容易「错一半还得一半分」或「全丢」的题）；
> ② **reaction pathway diagram**（模板死板到可以机械照做，但考官报告列出了**五类不给分的画法**）；
> ③ **两条短得反直觉的定义**（ΔH / Ea，漏一个词就丢 1 分）。
>
> 本单元**不需要**背任何数值条件、不需要量热法、不需要 Hess 定律（见文末「⛔ 超纲，不用背」）。

---

## ⚠️ 符号与重建说明（全文通用，务必先读）

`pdftotext` 把 PDF 里的 `ΔH`、负号、下标全部吃掉了。来源语料里真题原文印出来的是 `H = �54 kJ / mol` 这种残缺形式（`�` 是 U+FFFD，即丢字处）。

**本笔记沿用了底稿（`_research/topic5-energetics.md`）的重建标记，方括号一律表示「这是我方重建，不是原文」：**

| 本笔记写法 | 含义 | 重建依据 |
|---|---|---|
| `[ΔH]` | 原文是 `ΔH`（或被 pdftotext 吃成一个 `�`） | 上下文 + MS 自身的 `(the value of H is) negative` |
| `[−]` | 原文是**负号** | `exothermic ⇒ ΔH 为负`，且同题 MS 给出正数值（如 m25 的 `+105`、w22 的 `(+) 60`）验证 |
| `[Ea]` | 原文是 `Ea` | 同题 MS 答案 `Ea` |
| `[°C]` | 原文是 `°C` | 上下文 |

化学式里的下标（`CCl4` 应作 CCl₄、`SO2` 应作 SO₂）同样是被压平的结果，不影响内容，引用 MS 时按原样保留。

**2026 语料的额外说明**：`0620_m26_er.txt` 与 2026 各 MS 的行首项目符号在 pdftotext 输出里是 `�`（U+FFFD）。本笔记引用 2026 原文时把行首的 `�` 还原成项目符号 `•`，**其余字符照抄**；同样地，`3H2(g)` 这类写法是压平下标的结果。**引用 2026 ER/MS 时，`•` 是重建、不是原文。**

> **引自 MS 的行内 `�` 有不可还原处**：`0620/43 May/June 2020 Q3(d)` 的 M3 原文是 `energy change =679�864=�AND 185` —— 其中 `AND` **无法还原**，底稿已标注「原文残缺」，本笔记照实标注，请勿当成完整式子背诵。

---

## 📋 考纲对照清单

> 逐条覆盖，不多不少。复习前先勾一遍「掌握」列；「真题考过没有」列的份数按 **46 份 Paper 4** 为分母。

| 考纲 | 内容 | Core/Ext | 真题考过没有 | 掌握 |
|---|---|---|---|---|
| **5.1-1** | State that an **exothermic** reaction **transfers thermal energy to the surroundings** leading to an **increase in the temperature of the surroundings** | **C** | ✅ **约 10 份**（s20/41、w20/41、s21/42、w22/42、w22/43、s24/41、s24/43、s25/41、m20/42、w21/41） | ☐ |
| **5.1-2** | State that an **endothermic** reaction **takes in thermal energy from the surroundings** leading to a **decrease in the temperature of the surroundings** | **C** | ✅ 同上（同一批题的两面） | ☐ |
| **5.1-3** | **Interpret** reaction pathway diagrams showing exothermic and endothermic reactions | **C** | ✅ **读图型 2 份**（w22/42 Q5(e) 命名 A/B 箭头 + 说明放热；w20/41 Q5(b)(iii) 由图说明放热）；**画图型 7 份也含此判断** | ☐ |
| **5.1-4** | State that the transfer of thermal energy during a reaction is called the **enthalpy change, ΔH**. **ΔH is negative for exothermic** and **positive for endothermic** | **S** | ✅✅ **11 份**（定义 5：m23/42、s24/42、w23/42、m25/42、w25/43；**符号判定 6**：m23/42、m25/42、w24/43、w25/43、**m26/42、s26/42**） | ☐ |
| **5.1-5** | Define **activation energy, Ea**, as **the minimum energy that colliding particles must have to react** | **S** | ✅ **2 份**（w23/42 Q5(b)(iv) 拆成 2 分；w24/42 Q3(e)(i)(ii) 定义 + 符号）。⚠️ 2026 两份 Paper 4 只考了「用 Ea 算逆反应」（m26/42），**没有**再考定义 | ☐ |
| **5.1-6** | **Draw and label** reaction pathway diagrams for exothermic and endothermic reactions **using information provided**, to include reactants / products / ΔH / Ea | **S** | ✅ **7 份**（s20/43、w21/42、w22/41、w23/42、w25/41、**m26/42、s26/42**），每次 3–4 分 | ☐ |
| **5.1-7** | State that **bond breaking is endothermic** and **bond making is exothermic**, and **explain the enthalpy change in terms of bond breaking and bond making** | **S** | ✅ **3 份**（w21/42 3 分、s21/42 2 分、w22/43 1 分） | ☐ |
| **5.1-8** | **Calculate the enthalpy change of a reaction using bond energies** | **S** | ✅✅✅ **18 份（39%）**，合计 **59 分** —— 本单元绝对主力（2026 新增：**m26/42 Q4(d) 4 分、s26/42 Q5(c)(iii) 4 分**） | ☐ |

> **编号说明**：考官报告直接引用了考纲编号 **5.1.4**（= 本清单 5.1-4，ΔH 定义）与 **5.1.5**（= 5.1-5，Ea 定义）。这是全库唯一给出**逐字大纲定义**的地方，说明 ER 用的是现行编号。
> 底稿在引用 m23 那段时写了一句「注意它引的是旧编号 5.1.4；现大纲为 5.1 Supplement 第 4 条」—— 两种说法指向**同一条**，不冲突：5.1 内部是 Core 1–3 + Supplement 4–8 的连续编号。

---

# 5.1 Exothermic and endothermic reactions

## 5.1.1 Exothermic / endothermic 的定义（5.1-1 / 5.1-2）

### English 背这句

> An **exothermic** reaction **transfers thermal energy to the surroundings** leading to an **increase in the temperature of the surroundings**.
>
> An **endothermic** reaction **takes in thermal energy from the surroundings** leading to a **decrease in the temperature of the surroundings**.

**官方 mark scheme 收的关键词版（逐字）**
> `exothermic/heat/energy is released/surroundings warm up` — **M1**
> `products have lower energy than reactants/ORA` — **M2**
> `(来源: 0620/41 Oct/Nov 2020 Q5(b)(iii)，2 分)`
> （`ORA` = **or reverse argument**，反向表述同样给分。`surroundings` 是这一空的关键词。）

**⚠️ 用词：考纲写的是 `thermal energy`，不是 `heat`。** 但 MS 收 `heat`。**保守做法：写 `thermal energy`**；要在同一句里塞两个关键词时写 `thermal energy (heat)` 也不违规 —— 但**不要只写 `energy`/`release of energy`**（下一节的陷阱）。

### 中文理解

放热/吸热的判据**不是「反应容器烫不烫」这种描述，而是「能量往哪个方向走」**：

- exothermic：能量从**反应体系**流向**surroundings** → surroundings 温度**上升**；
- endothermic：能量从**surroundings**流向**反应体系** → surroundings 温度**下降**。

注意考纲措辞的重心在于 **surroundings（环境）的温度变化**。所以答题时要同时出现「能量方向」和「surroundings 温度变化」两个要素，缺一个就可能被读成不完整。

### ⚠️ 陷阱

> **Core 卷连年点名的一件事：只说 `release of energy` 不给分，必须说 `thermal` / `heat` / `surroundings`。**
>
> `(ii) Many candidates were able to state the meaning of the term exothermic correctly. The commonest error was to mention 'release of energy' without referring to 'thermal' or 'heat'.`
> `(0620_m22_er.txt，Paper 0620/32（Core）Q8(c)(ii))`
>
> `(e) (i) Most candidates answered this question correctly. However, some candidates did not mention heat or thermal energy in their answers.`
> `(0620_m24_er.txt，Paper 0620/32（Core）Q4(e)(i))`

> **⚠️ 抄定义 ≠ 回答「图怎么说明放热」。** 见 5.1.4 的读图题陷阱 —— 问「这个图怎么说明它是放热」时，答案必须是 `energy of products is lower than energy of reactants`，**不能背放热定义**。

> **⚠️ 手写 `exothermic` 时把 `x` 写清楚。**
> `a number of candidates wrote 'enothermic' – a mixture of the spelling of 'exothermic' and 'endothermic'. This answer could not receive credit; candidates need to ensure that if they are writing 'exothermic' that the 'x' is not ambiguous and written to look like an 'n'`
> `(0620_m20_er.txt，Paper 0620/62 Q2(a)(i)，实验卷但规则通用)`

### 🔧 答题模板

**问「State what is meant by exothermic / endothermic」时，照这个骨架写：**

```
An exothermic reaction transfers thermal energy to the surroundings,
so the temperature of the surroundings increases.
（加一句保险）The products have lower energy than the reactants.
```

```
An endothermic reaction takes in thermal energy from the surroundings,
so the temperature of the surroundings decreases.
```

**问「这个反应是 exothermic 还是 endothermic，为什么」时（可给 2 分）：**
```
exothermic
and
more energy is released (in bond formation) than used/taken in (in bond breaking)
（或：energy released when bonds form is greater than energy absorbed to break bonds）
```
> MS 原文（`0620/42 May/June 2021 Q5(b)(ii)`，2 分）：
> `Answer must reflect answer in 5(b)(i)` / `exothermic` / `and` / `more energy released (in bond formation) than used/taken in (in bond breaking)`
> 第一行 `Answer must reflect answer in 5(b)(i)` 是硬指令：**这一问的 exo/endo 必须与上一问你自己算出的 ΔH 自洽**，算成放热才能判 exothermic。

---

## 5.1.2 Enthalpy change ΔH 与正负号约定（5.1-4）★★★

### English 背这句

> The transfer of thermal energy during a reaction is called the **enthalpy change, ΔH**, of the reaction.
> **ΔH is negative for exothermic reactions** and **positive for endothermic reactions**.

**但 MS 的答案短得反直觉 —— 只要一个词：**

> `enthalpy change (of reaction)`

**官方 mark scheme 原文（5 份全部同一答案，逐字）**

| 出处 | 题目原文 | MS 答案（逐字） |
|---|---|---|
| `0620/42 Feb/March 2023 Q3(b)(i)` | "State what is meant by the symbol **[ΔH]**." | `enthalpy change` |
| `0620/42 May/June 2024 Q3(b)` | "State the meaning of **[ΔH]**." | `enthalpy change (of reaction)` |
| `0620/42 Oct/Nov 2023 Q5(a)` | "State the term used for the transfer of thermal energy during a reaction." | `enthalpy change (of reaction)` |
| `0620/42 Feb/March 2025 Q4(b)` | "State what the symbol **[ΔH]** represents." | `enthalpy change (of reaction)` |
| `0620/43 Oct/Nov 2025 Q3(c)(i)` | "State the meaning of the symbol **[ΔH]**." | `enthalpy change (of reaction)` |

**符号约定（6 份，逐字）**

| 出处 | 题目原文 | MS 答案（逐字） |
|---|---|---|
| `0620/42 Feb/March 2023 Q3(b)(ii)` | "[ΔH] for the forward reaction is `[−]92 kJ/mol`. State why this value shows that the forward reaction is exothermic." | `(the value of) H is negative` |
| `0620/42 Feb/March 2025 Q4(c)` | "State how the value of **[ΔH]** shows that the forward reaction is exothermic." | `(The value of H is) negative` |
| `0620/43 Oct/Nov 2025 Q3(c)(ii)` | "State what can be deduced about the reaction from the negative sign in **[ΔH]** = `[−]850 kJ / mol`." | `(forward) reaction is exothermic` |
| `0620/42 Feb/March 2025 Q4(d)` | "Deduce the value of **[ΔH]** for the reverse reaction. **Include a sign in your answer.**" | `+105 (kJ/mol)` |
| **`0620/42 Feb/March 2026 Q4(a)`** | "State how the information shows that this reaction is reversible and **exothermic**."（`3H2(g) + CO2(g) ⇌ CH3OH(g) + H2O(g)`，译文见下） | `M1 use of reversible arrow/use of [⇌]`<br>`M2 H is negative/H is [−]40 (kJ/mol)` |
| **`0620/42 May/June 2026 Q5(c)(i)`** | "State how the equation shows this reaction is: **exothermic** / reversible." | `M1 H is negative/H is [−]870 (kJ/mol)`<br>`M2 use of reversible arrow/use of [⇌]` |

> **★ 2026 新证据：s26 的 Mark Scheme 新增 `Guidance` 栏，把这一问的「接受 / 忽略 / 拒绝」写死了** —— `0620/42 May/June 2026 Q5(c)(i)`（4 分时代的 MS 没有这个栏目，**2026 年起才有**）：
> ```
> 5(c)(i) M1 H is negative/H is �870(kJ/mol)          2
>         A `Change in ... enthalpy/energy/heat ... is negative'/H < 0
>         I comments about products having less/more E than reactants
>         I �870 without reference to enthalpy change e.g. `cos its �870'
>         I `�'/`cos its negative' alone
>         I Comments about bond breaking/making
>
>         M2 use of reversible arrow/use of [⇌]
>         A any answer that refers to or describes the arrow (in the equation)
>             e.g. A `the arrow' (as a minimum)
>         I `The reversible sign' (alone) but A The (reversible) sign/symbol in
>             middle of equation (as this tells us where to look)
>         I comments describing reversible reactions e.g. reaction goes both ways
> ```
> （`A` = accept 给分，`I` = ignore 忽略不给分，`R` = reject 明确拒绝；2026 年 MS 的新标注体系。）
>
> → **这一栏直接确认了三件事**：
> ① **`H < 0` 也收**（数学不等号写法与 `negative` 等价）；
> ② **`−870` 单独出现不给分**（`cos its −870`、`cos its negative` 都不算），必须**挂到 `enthalpy change`/`energy change`/`heat change` 上**；
> ③ **「产物能量比反应物低」不给分**（`I comments about products having less/more E than reactants`）、**「因为断键/成键」也不给分**（`I Comments about bond breaking/making`）。
>
> ⚠️ 第 ③ 点很反直觉：**同样是「产物能量更低」，在路径图读图题（5.1.4）里是唯一正确答案，在符号判定题里却被 ignore。** 答哪一问、写哪一句，不能混。
>
> → 反向论证同样值得注意：**`the arrow` 三个字就够了**（M2），但 `The reversible sign` 单独写不给分 —— 除非补上 `in the middle of equation`（因为这句话说明你确实指对了位置）。

> **注意 `0620/42 Feb/March 2025 Q4(c)` 的阴险之处**：题目问「**怎么说明**它是放热」，答案**不是「放热」**，而是**「ΔH 是负的」**。这两问的差别被 ER 专门点名（见下）。

### 中文理解

ΔH 是**「反应过程中传递的 thermal energy」的官方名字**。它是一个**带符号的数**，符号本身就是信息：

```
ΔH < 0（带负号）→ 放热（exothermic）→ 能量流出体系 → surroundings 变热
ΔH > 0（带正号）→ 吸热（endothermic）→ 能量流入体系 → surroundings 变冷
```

**为什么 MS 只要 `enthalpy change` 两个词？** 因为这是**定义题（State the meaning of the symbol）**，指令词只要求给出术语本身。考生普遍**过度作答**：写一堆「放热时能量释放……」反而被判不完整或不切题。反过来，考生普遍**答得太模糊** —— ER 四次点名 `energy change`。

### ⚠️ 陷阱

> **陷阱 1：只写 `energy change` 或只写 `enthalpy`。** 这是全 Topic 复现率最高的定义题错法，被 **四份 ER** 独立点名：
>
> `The meaning of H was not well known – vague terms such as 'energy change' were often seen. The relevance of the negative value as an indicator of an exothermic reaction was hardly ever seen.`
> `(0620_m23_er.txt，Paper 0620/42 Q3(b)(i)(ii))`
>
> `Most candidates recognised the symbol and 'enthalpy change' or 'energy change of reaction'. Some candidates needed to be more specific in their response. For example, some candidates gave only 'enthalpy' or 'energy change'. Weaker responses stated 'activation energy'.`
> `(0620_m25_er.txt，Paper 0620/42 Q4(b))`
>
> `Relatively few candidates were familiar with learning objective 5.1.4 of the syllabus which is 'State that the transfer of thermal energy during a reaction is called the enthalpy change, H, ...' and thus the simple answer 'enthalpy change' was not seen too frequently. Others correctly stated 'the transfer of thermal energy during a reaction'. The most common error was 'energy change'.`
> `(0620_s24_er.txt，Paper 0620/42 Q3(b))`
>
> `Many referred to enthalpy but very few spelt the word correctly. Common errors seen were: energy change (alone) or enthalpy (alone).`
> `(0620_w25_er.txt，Paper 0620/43 Q3(c)(i))`
>
> → **`energy change` (alone)、`enthalpy` (alone) 都不够；`activation energy` 是更差的答案。**

> **陷阱 2：问「为什么该值说明放热」时答「放热」。**
> `Weaker candidates gave a description of an exothermic reaction (for example, 'gives out heat') without mentioning the minus sign.`
> `(0620_m25_er.txt，Paper 0620/42 Q4(c))`
> → MS 只认 **`negative` / `minus sign`**。

> **陷阱 3：反向反应的 ΔH —— 符号要翻，数字不能变。**
> `Most candidates knew that H for the reverse reaction would involve a change of sign of the H for the forward reaction. Missing the '+' sign was the most common error, and other candidates changed the magnitude.`
> `(0620_m25_er.txt，Paper 0620/42 Q4(d))`
> → 正反应 `[ΔH] = [−]105 kJ/mol` ⇒ 逆反应 `+105 (kJ/mol)`。**两个错法：漏 `+`；把数字也改了。**

> **陷阱 4：`enthalpy` 拼错不给分。**
> `Many referred to enthalpy but very few spelt the word correctly.`
> `(0620_w25_er.txt，Paper 0620/43 Q3(c)(i))`
> → 与 MS 通用原则 3（拼写须能清晰无歧义地区分）一致。**背的时候连拼写一起背：e-n-t-h-a-l-p-y。**

> **陷阱 5：说 `exothermic side` / `endothermic side`。**
> `Candidates should be aware that there is no such thing as an 'endothermic side' to a reaction; there is, however, an endothermic direction.`
> `(0620_m20_er.txt，Paper 0620/42 节)`
> `Candidates should be aware that there is no such thing as an 'exothermic side' to a reaction; there is, however, an exothermic direction.`
> `(0620_s21_er.txt，Paper 0620/43 Q4(c)(i))`
> `References to exothermic reaction should make it clear that this referred to the forward reaction. Many candidates referred incorrectly to the exothermic side or the endothermic side as opposed to the exothermic reaction or endothermic reaction.`
> `(0620_w24_er.txt，Paper 0620/43 Q4(c)(ii))`
> → **`side` 这个词在任何反应里都不存在**；要写 **`the forward reaction is exothermic`**（必须点明是 forward reaction）。

> **陷阱 6：exo / endo 判断反了 —— 全库复发率第一的概念错误，几乎每份 ER 都要提一次。** Extended 卷实例：
> `Many candidates made no reference to thermicity. 'Exothermic' was the most common wrong answer.`（正解 `endothermic`）`(0620_s24_er.txt，Paper 0620/41 Q4(c))`
> `Many candidates did not understand that if a temperature increase produces an increase in yield of the forward reaction, then that reaction must be endothermic. ... Exothermic was another common incorrect answer.` `(0620_s24_er.txt，Paper 0620/43 Q4(c))`
> `Endothermic was the most common wrong answer.`（正解 `exothermic`）`(0620_w25_er.txt，Paper 0620/43 Q4(a)(iii))` 与 `(0620_w25_er.txt，Paper 0620/43 Q3(c)(ii))`
> `'Endothermic' was the most common incorrect answer.` `(0620_s25_er.txt，Paper 0620/41 Q5(b)(iii))`
> → **拿分推理链**：温度升高 → 正反应产量增大 ⇒ **正反应是 endothermic**；温度升高 → 产量减小 ⇒ **正反应是 exothermic**。只写「平衡移动了」或「速率变快了」**不给分**。

> **陷阱 7：`release of energy` 单独出现（Core 卷反复强调）。** 见 5.1.1 陷阱一栏。Extended 的 MS（`0620/41 Oct/Nov 2020 Q5(b)(iii)`）收的写法是 `exothermic/heat/energy is released/surroundings warm up` —— **把 `surroundings` 一起写上最保险。**

> **陷阱 8（2026 新增）：提到可逆符号却不说它是什么。**
> `(a) ... Limited responses • Some candidates referred to the reversible symbol without saying what that symbol was.`
> `(0620_m26_er.txt，Paper 0620/42 Q4(a)，February/March 2026)`
> → 与 s26 的 MS Guidance 完全一致（`I 'The reversible sign' (alone) but A The (reversible) sign/symbol in middle of equation`）。**写 `the arrow` 或 `the ⇌ symbol` 才给分，写 `the reversible sign` 三个字不给分。**

### 🔧 答题模板 —— ΔH 四连问（考场照抄）

**问 1：State the meaning of the symbol ΔH.**
```
enthalpy change (of reaction)
```
（只想拿这一分，就写这两个词，别加解释。ER 甚至承认照抄大纲整句 `the transfer of thermal energy during a reaction` 也给分。）

**问 2：State how the value of ΔH shows the reaction is exothermic.**
```
(The value of ΔH is) negative
```
（**不是**「放热」！`negative` / `minus sign` 是唯一得分词。）

**问 3：What can be deduced about the reaction from the negative sign in ΔH = [−]850 kJ/mol?**
```
(forward) reaction is exothermic
```

**问 4：Deduce ΔH for the reverse reaction. Include a sign.**
```
+105 (kJ/mol)
```
（数字照抄正反应的，**只翻符号**。）

**问 5（2026 新题型）：State how the equation / the information shows the reaction is exothermic and reversible.**
```
exothermic: the (value of the) enthalpy change is negative     ← 必须挂在 enthalpy change 上
reversible: the arrow (the ⇌ symbol in the middle of the equation)
```
（**不要**答「产物能量比反应物低」，**不要**答「因为断键/成键」，**不要**只写 `−870` 或 `cos its negative` —— 见上方 s26 Guidance 逐字。）

---

## 5.1.3 Activation energy Ea（5.1-5）★★★

### English 背这句

> activation energy, **Ea**, is **the minimum energy that colliding particles must have to react**

**这是考纲 5.1.5 的逐字原文**，也是全库唯一一处 ER 把大纲编号和定义一起抄出来的知识点。

> 出处：`0620_w24_er.txt`，Paper 0620/42 节，`0620/42 Oct/Nov 2024 Q3(e)(i)`：
> ```
> (e) (i)  Section 5.1.5 of the syllabus defines activation energy as `the minimum energy that colliding
>          particles must have to react'. Very few candidates gave this exact definition. Most candidates opted
>          for simplified or incomplete definitions such as `the minimum energy for a reaction to take place'.
>
>      (ii) The symbol for activation energy, Ea, was well known.
> ```

**官方 mark scheme 原文**
> `0620/42 Oct/Nov 2024 Q3(e)(i)` — "Define the term activation energy." → `the minimum energy that colliding particles must have to react`
> `0620/42 Oct/Nov 2024 Q3(e)(ii)` — "Give the symbol for activation energy." → `Ea`

**同一定义在 w23 被拆成 2 分给（逐字）**
> `M1 minimum energy (1)`
> `M2 that colliding particles must have to react (1)`
> `(来源: 0620/42 Oct/Nov 2023 Q5(b)(iv))`

### 中文理解

Ea 的物理图像：**分子的碰撞不是「碰到就反应」**。两个粒子必须带着足够大的**动能**撞在一起，才能越过能垒。这个门槛能量就是 Ea。

**定义的两个独立得分点：**

| 得分点 | 必须出现 | 说明 |
|---|---|---|
| **M1** | `minimum energy` | 少了 `minimum` 就不成立 |
| **M2** | `that **colliding particles** must have to react` | **`colliding particles` 是这条定义的灵魂** |

> 💡 **记忆提示**：Ea 的定义里为什么要有 `colliding particles`？因为反应的发生机制就是**碰撞**。丢了这个主语，定义就变成了「反应发生所需的最低能量」——听起来对，但 CIE 判它**不完整**。

### ⚠️ 陷阱

> **陷阱 1：丢 `colliding particles` —— 被 w23 与 w24 两份 ER 独立点名，是本 Topic 最稳定的得分要求之一。**
>
> `(iv) The definition of activation energy is new to the syllabus. Many candidates wrote 'minimum energy to start a reaction' but only a few attempted to define activation energy in terms of colliding particles reacting.`
> `(0620_w23_er.txt，Paper 0620/42 Q5(b)(iv))`
>
> `Very few candidates gave this exact definition. Most candidates opted for simplified or incomplete definitions such as 'the minimum energy for a reaction to take place'.`
> `(0620_w24_er.txt，Paper 0620/42 Q3(e)(i))`
>
> **以下写法被判「simplified or incomplete」，全部不给 M2：**
> - `the minimum energy for a reaction to take place`
> - `minimum energy to start a reaction`
> - `energy needed to react`

> **陷阱 2：把 Ea 与 overall energy change 搞混。**
> `Some candidates confused the activation energy with the overall energy change of reaction, choosing option A.`
> `(0620_s22_er.txt，Paper 0620/22 Q16，Extended MCQ)`
> → 在同一张路径图上，**Ea 是「反应物线 → hump 顶」的高度**，**ΔH 是「反应物线 → 产物线」的高度**。两者完全不同。

> **陷阱 3：以为升温/降温/改浓度会改变 Ea。** 被四份 ER 点名：
> `Some candidates erroneously stated activation energy is changed.` `(0620_s23_er.txt，Paper 0620/42 Q3(b)(v))`
> `Some candidates erroneously stated activation energy is reduced.` `(0620_m23_er.txt，Paper 0620/42 Q3(b)(v))`
> `Weaker candidates commonly stated incorrectly that decreasing the temperature decreased the activation energy.` `(0620_m25_er.txt，Paper 0620/42 Q5(d)(iii))`
> `they did not recognise that the activation energy of a reaction does not change` `(0620_m23_er.txt，Paper 0620/23 Q14)`
> `Although the majority knew that adding (or removing) a catalyst would change the activation energy, many incorrectly thought that changing the temperature would alter the activation energy.` `(0620_w23_er.txt，Paper 0620/42 Q5(b)(v))`
> → **只有 catalyst 会改变 Ea。温度、浓度、压强、表面积都不改变 Ea** —— 它们改变的是「能量 ≥ Ea 的粒子比例」。

> **陷阱 4：`particles have energy greater than activation energy` —— 少了 proportion 限定词。**
> `Many candidates wrote phrases such as 'particles have energy greater than activation energy' suggesting all particles had energy greater than activation energy.`
> `(0620_m23_er.txt，Paper 0620/42 Q3(b)(v))`
> `However, many candidates wrote phrases such as 'particles have energy lower than activation energy', suggesting all particles had energy lower than activation energy.`
> `(0620_s23_er.txt，Paper 0620/42 Q3(b)(v))`
> → 必须写 **`a greater proportion / percentage / fraction of particles (or collisions)`**。

> **陷阱 5：UV 提供的是 activation energy，不是催化剂、不是「降低 Ea」。**
> `Many other responses were too vague, such as 'to provide energy' or just 'activation energy'. Incorrect responses included 'catalyst' or 'to lower Ea'.`
> `(0620_m24_er.txt，Paper 0620/42 Q5(c)(ii))`
> → 完整答法：`ultraviolet light provides the activation energy for the reaction`（光化学反应的语境）。

> **★ 陷阱 6（2026 新增）：逆反应的 Ea **不是**正反应 Ea 加负号 —— 它更大。**
> ```
> (ii) Comprehensive responses
>      • Many candidates knew that the enthalpy change of the reverse reaction would be the positive
>             value of the forward reaction.
>      Limited responses
>      • Some candidates did not include a sign for each answer and a most assumed the reverse
>            activation would be the negative value of the forward activation energy.
> ```
> `(0620_m26_er.txt，Paper 0620/42 Q4(c)(ii)，February/March 2026)`
> → **考法**：`0620/42 Feb/March 2026 Q4(c)(ii)` 一问两空，各 1 分 —— 给正反应 `Ea = +220 kJ/mol`、`[ΔH] = [−]40 kJ/mol`，求**逆反应**的 ΔH 与 Ea。
>
> **MS 逐字**：
> ```
> 4(c)(ii) M1 +40kJ/mol                                                                   2
>          M2 +260kJ/mol
> ```
>
> **推导（看图即可，不用背公式）**：正反应的 hump 顶点比**反应物**高 220；产物比反应物低 40。所以从**产物**爬到同一个 hump 顶点要 `220 + 40 = 260`。
> ```
> 放热正反应（ΔH < 0）：
>     Ea(逆) = Ea(正) + |ΔH|
>     ΔH(逆) = −ΔH(正)        ← 数字不变，只翻符号
> ```
> → **注意两个空都必须带符号**（`Include a sign with your answer.` 印了两次）。ER 点名「**did not include a sign for each answer**」。
> → **绝不要写 `−220`**：Ea 永远是**正数**（能量门槛），只有 ΔH 才带符号。

### 🔧 答题模板

**问 "Define the term activation energy."（2 分）—— 照抄，不要改写：**
```
the minimum energy that colliding particles must have to react
```
**如果只有 1 分的空，也写全句**（1 分题只取 M1 或 M2，写全句两处都覆盖）。

**问 "Give the symbol for activation energy."**
```
Ea
```

**路径图上标 Ea 的规则**见下一节（必须是从反应物能级到 hump 顶点的**向上单头箭头**）。

---

## 5.1.4 Reaction pathway diagram 反应路径图（5.1-3 / 5.1-6）★★★

> **为什么这一节很值钱**：5 份 Paper 4 要求**画/补全**、1 份要求**读图**。**评分模板高度固定，但考官报告列出的「不给分画法」有五类** —— 这是一个「照做就能满分、临场发挥就丢分」的题。

### 🔧 画图 checklist（机械照做，八步）

```
① 先在左侧画一条水平线 —— 这是 reactants 的能级线。
② 在线上（或紧贴线下方）写【完整化学式】，例如  SF4(g) + 2H2O(g)
   ❌ 写 "reactants" / "reactant" 两个字 —— 不给分
③ 判断方向：
     ΔH 为负 / 题目说 exothermic / 题目说 energy released
        → 产物能级线画在反应物线【下方】
     ΔH 为正 / 题目说 endothermic
        → 产物能级线画在反应物线【上方】
④ 在产物线上写【完整化学式】，例如  SO2(g) + 4HF(g)
   ❌ 写 "product" / "products" 两个字 —— 不给分
⑤ 从反应物线画一条【向上凸起】的 hump（驼峰）——两条斜线或一条曲线都行。
⑥ 从【反应物能级】起，画【单头向上箭头】到【hump 最高点】，标 Ea（题目若指定 A 就标 A）
   ❌ 半途而止 / 只把 hump 顶点标成 "activation energy" —— 不给分
   （2026 起双向箭头/无箭头竖线对 Ea 已放宽 —— 但照旧画单头最安全，见下方 2026 变化表）
⑦ 先画一条水平辅助线从反应物能级向右延长（考官推荐），保证下面这个箭头起点正确
⑧ 从【反应物能级】起，画【单头向下箭头】到【产物能级】，标 ΔH（题目若指定 H 就标 H）
   ❌❌ 双向箭头 / 无箭头的竖线 / 从反应物【斜画】一条直线到产物线 —— 都不给分（2026 仍然严格）
   ✅ 箭头必须正好覆盖「反应物能级 → 产物能级」的整段垂直距离
   ✅ 只画了一个箭头时：**用一个箭头表示 Ea 与 ΔH 是把 M2/M3 都压在一根线上** ——
      必须有【虚线水平能级线】把它分开才两个分都给（s26 Guidance 明文）
```

**自查四问**：① 两条线上都有化学式吗？② Ea 是**向上单头**吗？③ ΔH 是**向下单头**吗？④ 两个箭头都从**反应物能级**出发吗？

### 官方 mark scheme 逐字（7 份画图题 + 1 份读图题）

**① `0620/41 Oct/Nov 2025 Q4(a)` [4]** —— 最完整的一份，**题目本身就把要求列全了**：

> QP 原文：
> `Complete the reaction pathway diagram in Fig. 4.1 for this reaction.`
> `Include in your diagram:`
> `• the position and the formulae of the products`
> `• an arrow, labelled Ea , to show the activation energy`
> `• an arrow, labelled H, to show the enthalpy change of the reaction.`

> MS 逐字：
> `M1 energy level of products below energy level of reactants`
> `M2 label of SO2(g) + 4HF(g) on product line`
> `M3 upward arrow labelled Ea from energy level of reactants to the highest point of the curve`
> `M4 one downward arrow labelled H`
> `AND`
> `energy change starting from energy level of reactants and finishing at energy level of products`

反应：`SF4(g) + 2H2O(g) → SO2(g) + 4HF(g)`，`[ΔH] = [−]54 kJ / mol`（QP 原文印作 `H = �54 kJ / mol`）。

**② `0620/42 Oct/Nov 2023 Q5(b)(iii)` [3]** —— 题目要求：insert the formulae of the reactants and products / draw an arrow, labelled Ea / draw an arrow, labelled [ΔH]：

> `M1 Labels mark`
> `CCl4(g) + 2H2O(g) on reactant line`
> `AND`
> `CO2(g) + 4HCl(g) on product line`
> `M2 Activation E mark`
> `upward arrow labelled Ea from energy level of reactants to top of 'hump'`
> `M3 Energy change mark`
> `one downward arrow labelled H`
> `AND`
> `energy change starting from E level of reactants and finishing at E level of products`

**③ `0620/41 Oct/Nov 2022 Q5(d)(i)` [3]** —— 题目要求：the position of the products / an arrow to show the activation energy, labelled as **A** / an arrow to show the energy change：

> `M1 horizontal line below energy level to right hand side of reactants line and labelled C2H4Br2 (1)`
> `M2 activation energy 'hump' with upward arrow labelled A from the reactants level (1)`
> `M3 one downward arrow starting from the energy level of the reactants and finishing at the energy level of the products (1)`

**④ `0620/42 Oct/Nov 2021 Q4(b)(i)` [3]** —— 题目要求：the product of the reaction / an arrow representing the energy change, labelled **[ΔH]** / an arrow representing the activation energy, labelled **A**：

> `M1 exothermic mark`
> `horizontal line below energy level to R.H.S. of reactants line`
> `and`
> `labelled COCl2(g) (1)`
> `M2 activation E mark`
> `activation energy 'hump' with upward arrow labelled A/activation energy (1)`
> `M3 energy change mark`
> `one downward arrow labelled H`
> `and`
> `energy change starting from E level of reactants and finishing at E level of products (1)`

**⑤ `0620/43 May/June 2020 Q2(e)` [3]** —— 题目：`4NO2 + 2H2O + O2 → 4HNO3`，要求 "Include an arrow that clearly shows the energy change during the reaction."：

> `• horizontal product energy line at lower energy level than reactant`
> `• label of product`
> `• correct direction of vertical arrow – arrow must start level with reactant energy and finish level with product level`
> `and one arrow head ONLY`

> **`one arrow head ONLY` —— 这一句是「双向箭头不给分」的 MS 原文来源（但 2026 年起有变化，见 ⑧）。**

**⑦ `0620/42 Feb/March 2026 Q4(c)(i)` [3]** —— 题目：`3H2(g) + CO2(g) ⇌ CH3OH(g) + H2O(g)`，`[ΔH] = [−]40 kJ / mol`，`Ea = +220 kJ / mol`；"Complete the reaction pathway diagram in Figure 4.1. In your diagram, include: the formulas of the reactants and the products / an arrow, labelled Ea, to show the activation energy of the forward reaction / an arrow, labelled H, to show the enthalpy change of the forward reaction."

> MS 逐字：
> `4(c)(i) M1 labels mark:`
> `       3H2(g) + CO2(g) on reactant line AND CH3OH(g) + H2O(g) on product line`
> `       M2 activation energy mark:`
> `       upward arrow labelled Ea from energy level of reactants to top of 'hump'`
> `       M3 enthalpy change mark:`
> `       one downward arrow labelled H AND energy change starting from E level of reactants and finishing at E level of products`

> ⚠️ 注意 MS 写的是 **`formulas`**（QP 用词），不是 `formulae` —— **2026 年 QP 的动词是 "write the formulas of the reactants and the products"`（s26）**，措辞与旧卷的 "insert the formulae" 不同，但要求一样：**写完整化学式**。

**⑧ ★★★ `0620/42 May/June 2026 Q5(c)(ii)` [3]** —— **本单元最重要的评分标准更新**。`s26` 的 Mark Scheme **新增了 `Guidance` 栏**，把这一问「接受什么 / 忽略什么 / 拒绝什么」逐条写死（旧卷的 MS 没有这一栏）：

> MS 逐字（`Answer` 栏）：
> ```
> 5(c)(ii)   M1 Labels mark                                    3
>            NH3(g) + 3F2(g) on reactant line
>            and
>            NF3(g) + 3HF(g) on product line
>
>            M2 Activation E mark
>            upward arrow labelled Ea from energy level of
>            reactants to top of `hump'
>
>            M3 Energy change mark
>            one downward arrow labelled H
>            and
>            energy change starting from E level of reactants
>            and finishing at E level of products
> ```

> **`Guidance` 栏逐字（★ 这一栏才是新东西）**：
> ```
> M1  I `reactants' and `products' as labels (formulas asked for)
>     A unbalanced stoichiometry
>     A formulas closely above/below lines
>     I state symbols
>
>     For M2 and M3, line must be (near) vertical but A `near misses'
> M2  A label as `activation energy'/`EA'/`E' etc.
>     A double headed arrow for Ea or no arrow heads (i.e. labelled line is OK)
>     A arrows which are outside of the hump and finish (about) equal in E to
>         the top of the hump (i.e. arrow must be (around) correct length)
>
> M3  Arrow must have (only) one arrowhead
>     A For H labels as `H' or `�870' or `�H' or `enthalpy change' I `heat change'
>     R `diagonal' from reactant to products
>     A `near misses' for start and finish of the arrow line
>     A arrowheads mid-line
>     A ECF for arrow not quite being the right length (i.e. penalise poorly
>         drawn arrow once if the correct intention is there)
>
>     If one single line showing both Ea and H is shown with downward arrow at the
>     bottom but correctly split by dotted horizontal energy line, A M2 and M3
>     If one single line showing both Ea and H is shown with downward arrow at the
>     bottom but without dotted horizontal energy line, A M3 as ECF as it is
>     impossible to tell where each line starts.
> ```
> （`A` = accept 给分，`I` = ignore 不给分，`R` = reject 明确拒绝。）

> ### ⚠️ 2026 评分标准的四条变化 —— 老笔记里说的「一律不给分」有几条已经不成立
>
> | 画法 | 旧规则（2020–2025 ER/MS） | **2026 s26 `Guidance` 的实际处理** |
> |---|---|---|
> | **Ea 画成双向箭头** | ❌ 不给分（`Double headed arrows are incorrect`） | ✅ **`A double headed arrow for Ea`（接受！）** |
> | **Ea 画成没有箭头的竖线** | ❌ 不给分 | ✅ **`A ... no arrow heads (i.e. labelled line is OK)`（接受）** |
> | **ΔH 画成双向箭头** | ❌ 不给分 | ❌ **仍然不给分**：`Arrow must have (only) one arrowhead` |
> | **从反应物斜画直线到产物线** | ❌ 不给分 | ❌ **仍然不给分，且明确 `R`（reject）** |
> | **箭头长度不精确** | ❌「did not cover the full energy change」 | ✅ **`A ECF for arrow not quite being the right length`** |
> | **起点/终点有偏差** | — | ✅ **`A 'near misses' for start and finish of the arrow line`** |
> | **两个箭头画成一条线** | — | ✅ **只要有虚线水平辅助线分隔，M2 与 M3 都给** |
>
> **学生的实际结论**：**照旧画「Ea 向上单头、ΔH 向下单头」是最安全的**（两个年份都给分），但要知道 **Ea 那一分在 2026 年对箭头样式宽容得多，ΔH 那一分仍然严格** —— **如果时间不够只能画规范一个，就把 ΔH 画规范。**
>
> 另外新增的两条细则：
> - **M1 接受「化学式写在线上方或下方」（`A formulas closely above/below lines`）与「配平不精确」（`A unbalanced stoichiometry`）**，但**明确 `I 'reactants'/'products'` 两个词**、**`I state symbols`**。
> - **M2 接受多种标签写法**：`activation energy` / `EA` / `E` 都行。
> - **M3 接受多种标签写法**：`H` / `−870` / `ΔH` / `enthalpy change` 都行，但**`heat change` 不给分**（`I`）。

**⑥（变体：读图而非画图）`0620/42 Oct/Nov 2022 Q5(e)` [3]** —— 题目给出已画好的 profile（A 箭头向上、B 箭头向下）：

> `(i) Name the energy change labelled A.` → `activation energy`
> `(ii) Name the energy change labelled B.` → `energy (change) of reaction`
> `(iii) State how the energy profile diagram shows this is an exothermic reaction.` → `energy of products is lower than energy of reactants`

### ⚠️ 陷阱 —— 考官报告点名的五类不给分画法

> **★ 2026 年的最新一段（m26，格式换成了 Comprehensive / Limited responses）** —— `0620_m26_er.txt`，Paper 0620/42 Q4(c)(i)：
> ```
> (c) (i) Comprehensive responses
>             • Some candidates produced carefully labelled reaction pathway diagrams.
>
>      Limited responses
>      • Some candidates used a double headed arrow for the enthalpy change and some candidates
>            drew arrows that were too short or too long.
> ```
> → 2026 年的两条错法：**① [ΔH] 用双向箭头（与 s26 的 `M3 Arrow must have (only) one arrowhead` 一致，仍然扣分）；② 箭头画得太短或太长**（s26 Guidance 对「不太精确」给了 ECF，但**明显错长度仍然扣**）。

> **★ 最重要的一段（2020 年代最具体的路径图错因清单）** —— `0620_w25_er.txt`，Paper 0620/41 Q4(a)：
> ```
> (a)      Overall, many candidates could draw a reaction pathway diagram for an exothermic reaction, with
>          the products at a lower energy level than the reactants. A small number of candidates labelled the
>          product line as `product' rather than HF and SO2 and did not gain credit as the question asked
>          candidates to label the product line with the formulae of the products. Common errors included a
>          double headed arrow for the activation energy, a double headed arrow for H, or both the
>          activation energy and H shown as vertical lines without arrowheads. A small number of
>          candidates drew a diagonal line from the reactants to the product line, which did not gain credit.
> ```
> → **四类必扣分的画法**（第 5 类见下）：① 产品线只写 `product` 而不写化学式；② **Ea 画成双向箭头**；③ **[ΔH] 画成双向箭头**；④ **两个都画成没有箭头的竖线**；⑤ **从反应物斜画一条直线到产物线**。

> **★ 一句话说透箭头方向规则** —— `0620_w23_er.txt`，Paper 0620/42 Q5(b)(iii)：
> ```
> The direction of each arrow is important. Ea should be indicated by an upwardly headed arrow and
> H by a downwardly headed arrow. Double headed arrows are incorrect as they do not indicate the
> endothermic/exothermic nature of the change.
> ```

> **★ 全库最细的一段路径图讲评** —— `0620_w21_er.txt`，Paper 0620/42 Q4(b)(i)：
> ```
> (b) (i) Most candidates struggled with this question. Although many candidates appreciated that the
>            product was at a lower energy level, sometimes the line drawn was not labelled with the product.
>
>      The idea of activation energy was poorly represented with few drawing the traditional `hump'.
>      Candidates should realise that energy increases are represented by upward, single-headed
>      arrows.
>
>      The H arrow had to be a single-headed arrow, going from the energy level of the reactants to the
>      energy level of the products.
>
>      Better responses drew a horizontal construction line from the energy level of the reactants and
>      ensured both the activation energy arrow and the H arrow started from the correct point. Weaker
>      responses frequently contained arrows which did not cover the full energy change they were meant
>      to represent.
> ```
> → 四条硬规矩：① 产品线**必须标化学式**；② Ea 要画 **hump**，用**单头向上箭头**；③ ΔH 箭头**单头、从反应物能级到产物能级**；④ **先画一条水平辅助线**，保证两个箭头起点正确。

> **三条更细的错法** —— `0620_w22_er.txt`，Paper 0620/41 Q5(d)(i)：
> ```
> (d) (i) The majority of candidates drew the horizontal line to the right-hand side and below the reactants
>            line and labelled this C2H4Br2. A few just labelled this line `products'.
>
>      Care should be taken drawing the activation energy arrow from the level of the reactants to the top
>      of the `hump'. Many arrows finished too short of the top of the hump and some candidates simply
>      labelled the top of the `hump' as activation energy.
>
>      Some candidates incorrectly drew a double headed arrow for the energy change as opposed to the
>      downward pointing arrow showing an exothermic reaction.
> ```
> → ① 产品线只写 `products` 不写化学式；② **Ea 箭头没画到 hump 顶点**（半途而止），或**直接把 hump 顶点标成 activation energy**；③ **[ΔH] 画成双向箭头**。

> **标签必须贴线** —— `0620_s22_er.txt`，Paper 0620/32（Core）Q4(d)(ii)：
> `Candidates need to be reminded that the labels must be on or just under the line otherwise they will not gain credit`
> （规则通用：标签写在线上或紧贴线下方，飘在半空不给分。）

> **`0620/41 Oct/Nov 2022` Key messages（Paper 0620/41 节）**
> `• More precision is needed when drawing arrows on an energy profile diagram.`

### ⚠️ 陷阱 —— 读图题（5.1-3）

> **陷阱 1：把向下那个箭头叫 `energy change`。**
> `(i)(ii) These questions asked for the identity of two energy changes. 'Activation energy' was well known as the answer to (i), but many identified the energy change in (ii) as 'energy change' rather than 'energy change of reaction'. Weaker responses stated 'endothermic' and 'exothermic' respectively.`
> `(0620_w22_er.txt，Paper 0620/42 Q5(e))`
> → 向上箭头 = **`activation energy`**；向下箭头 = **`energy (change) of reaction`** —— **不能只写 `energy change`，更不能答 `endothermic`/`exothermic`。**

> **陷阱 2：问「图怎么说明放热」却背了定义 / 完全没提图。**
> `(iii) The question asked candidates to explain how the energy profile diagram shows the reaction was exothermic, but most candidates did not address the question and related the overall energy change to breaking and making of bonds with no reference to the diagram at all.`
> `(同上，0620_w22_er.txt，Paper 0620/42 Q5(e)(iii))`
> → 唯一得分答案：**`energy of products is lower than energy of reactants`**（必须提「产物 vs 反应物能量高低」）。

> **陷阱 3：把同一个点说两遍（不加分）。**
> `Most candidates were able to recognise that the graph was referring to an exothermic reaction but then could not extend this response by explaining that this was because the energy of the products was lower than that of the reactants. Most candidates made the same point twice, i.e. it is exothermic because energy is lost.`
> `(0620_w20_er.txt，Paper 0620/41 Q5(b)(iii))`
> → `exothermic` 与 `energy is lost` 是**同一个得分点**，说两遍仍只得 1 分。必须补上**独立的第二点**：产物能量低于反应物。

### 🔧 答题模板

**读图题三问：**
```
(i)  向上箭头 A → activation energy
(ii) 向下箭头 B → energy (change) of reaction
(iii) 这个图怎么说明是放热？
     energy of products is lower than energy of reactants
```

**给你一个反应式 + ΔH 让你补全图：** 严格执行上面的八步 checklist。**先画辅助线，再画两个箭头。**

**用图 + 数据求逆反应的 ΔH 与 Ea（2026 新题型，`0620/42 Feb/March 2026 Q4(c)(ii)`）：**
```
放热正反应：
  ΔH(逆) = −ΔH(正)                ← 数字不变，只翻符号
  Ea(逆) = Ea(正) + |ΔH|          ← 从产物爬到同一个 hump 顶点
例：Ea(正) = +220、ΔH(正) = [−]40  ⇒  ΔH(逆) = +40、Ea(逆) = +260
★ 两个答案都要带符号；Ea 永远是正数
```

---

## 5.1.5 键断裂 / 键生成解释 exo / endo（5.1-7）★★★

### English 背这句（三句话，一字不改）

```
• bond breaking takes in energy
• bond making releases energy
• the energy change of bond making is greater than bond breaking.
```

**这是考官报告亲手给出的标准答案**（原文见下）。三句缺一不可。

**官方 mark scheme 原文**
> `0620/42 Oct/Nov 2021 Q4(a)` — "Explain why the reaction is exothermic **in terms of the energy changes of bond breaking and bond making**." [3] →
> `M1 E of making bonds > breaking bonds`
> `M2 bond making releases energy`
> `M3 bond breaking requires energy`

**endothermic 一侧的标准措辞**
> `0620/43 Oct/Nov 2022 Q6(a)(ii)` [1] →
> `endothermic AND energy released when bonds form is less than energy absorbed to break bonds`
> `OR`
> `endothermic AND overall energy change has a positive sign`
> → **光写 `endothermic` 不够**，必须把「吸收 > 放出」或「overall energy change 带正号」说出来。

**⚠️ 这一问必须与上一问的计算自洽（判分指令）**
> `0620/42 May/June 2021 Q5(b)(ii)` [2] → 第一行是 `Answer must reflect answer in 5(b)(i)`，然后才是 `exothermic` / `and` / `more energy released (in bond formation) than used/taken in (in bond breaking)`。
> → 前面算成放热，这里才给 exothermic。

### 中文理解

**为什么断键吸热、成键放热？**

- 断键 = 把两个由化学键连着的原子**拉开** → 必须**克服**它们之间的吸引 → **要外界给能量**（吸热，endothermic）。
- 成键 = 两个原子被吸引到一起、落到更低的能量状态 → **多余的能量被释放出来**（放热，exothermic）。

**所以一个反应的总 ΔH = 「断键花的钱」−「成键赚的钱」：**

```
赚 > 花  → 净放热 → exothermic → ΔH 为负
花 > 赚  → 净吸热 → endothermic → ΔH 为正
```

**这一节的常见失败不在理解，而在措辞**：考生想说的和写出来的不是一回事。下面的 ER 引文是这一节的全部价值所在。

### ⚠️ 陷阱

> **★ 考官把标准答案原封不动列出来了（本 Topic 最有用的一段指导）** —— `0620_w21_er.txt`，Paper 0620/42 Q4(a)：
> ```
> (a)      This question asked candidates to explain the exothermic nature of the reaction based upon
>          energy changes of bond breaking and bond making.
>
>          Three simple statements would have sufficed:
>          • bond breaking takes in energy
>          • bond making releases energy
>          • the energy change of bond making is greater than bond breaking.
>
>          Very few candidates gave all three statements and poor phrasing was common.
>
>          A typical answer such as `more energy is released in bond making than breaking' incorrectly
>          suggests bond breaking also releases energy.
>
>          Similarly, `less energy is required to break bonds than make bonds' suggests bond making requires
>          energy.
>
>          Weaker responses ignored the idea of bond breaking/making and thought it was sufficient to write
>          that the process was exothermic because `energy is lost'.
> ```
> → **被读成「错」的两个句式（别省主语，别省 in / required）：**
> - `more energy is released in bond making than breaking` —— 暗示**断键也放能**
> - `less energy is required to break bonds than make bonds` —— 暗示**成键要吸能**
>
> → **最强的三句话，逐字背。**

> **陷阱 1：「成键需要能量」—— 同一个措辞陷阱被三份 ER 独立点名。**
> `Many candidates used incorrect phraseology, which suggested that bond formation required energy. A typical example of this would be, 'energy used to break bonds is less than the energy to used to make bonds' implying, incorrectly, energy was taken in to make bonds.`
> `(0620_s21_er.txt，Paper 0620/42 Q5(b)(ii))`
> `Those candidates who referred to bond breaking and bond forming often made incorrect statements such as 'energy given out when bonds are broken' or 'energy required to form bonds'.`
> `(0620_w22_er.txt，Paper 0620/43 Q6(a)(ii))`
> `Similarly, 'less energy is required to break bonds than make bonds' suggests bond making requires energy.`
> `(0620_w21_er.txt，Paper 0620/42 Q4(a))`
> → **正确措辞只有一个：`bond making releases energy` / `energy released when bonds are formed`。**

> **陷阱 2：说「断键放能」。**
> `energy given out when bonds are broken`（同上，`0620_w22_er.txt`）
> `Some candidates gave option C thinking that bond breaking released energy.`
> `(0620_w20_er.txt，Paper 0620/22 Q14，Extended MCQ)`
> `Weaker candidates were most likely to choose option B, confusing the formation of bonds with an endothermic process.`
> `(0620_w25_er.txt，Paper 0620/23 Q16，Extended MCQ)`

> **陷阱 3：只提断键、或只提成键。**
> `Some candidates referred to bonds being broken, or bonds being formed rather than both.`
> `(0620_w22_er.txt，Paper 0620/43 Q6(a)(ii))`
> → **两件事都要说。**

> **陷阱 4：endothermic 只写「吸热」，不给理由。**
> `Statements, such as 'endothermic because energy is taken in from the surroundings', were often not qualified with a reason.`
> `(同上)`
> → MS 要求的是**键能层面的理由**：`energy released when bonds form is less than energy absorbed to break bonds`（或 overall energy change 带正号）。

### 🔧 答题模板

**问 "Explain why the reaction is exothermic / endothermic in terms of bond breaking and bond making."（3 分）—— 直接默写：**

```
exothermic:
  Bond breaking takes in energy.
  Bond making releases energy.
  The energy change of bond making is greater than bond breaking.

endothermic:
  Bond breaking takes in energy.
  Bond making releases energy.
  The energy released when bonds form is less than the energy absorbed to break bonds.
  （等价写法：the energy change of bond breaking is greater than bond making）
```

> 💡 **一条保命规则**：**断键永远 takes in / requires；成键永远 releases / gives out。** 只要这两个动词配不错，就不会掉进 ER 点名的句式陷阱。

---

## 5.1.6 用键能计算 ΔH（5.1-8）★★★★ 本单元第一大题

> **规模**：**18 / 46 份 Paper 4** 出现（**39%**），合计 **59 分**。**3 分是标准配置**（13 道）；**五道 4 分题全部是「求某个未知键能」型** —— 2026 新加的两道都是 4 分。
> **特点**：**方法分（M1/M2/M3）与答案分分开给**，算错但方法对仍能拿一半 —— 但也因为分步给分，**一步搞反就丢最后 1 分**。反向相减是**被五份 ER 独立点名的本单元第一大失分点**。

### 📐 公式卡

| 项目 | 内容 |
|---|---|
| **核心公式** | `ΔH = (energy needed to break bonds) − (energy released when bonds form)` |
| **英文** | `ΔH = (energy required in breaking bonds) − (energy released when bonds are formed)` |
| **中文** | ΔH = 断键吸收的总能量 − 成键放出的总能量 |
| **永远的顺序** | **先断后成，绝不到过来**（`M1 − M2` 是 MS 逐字给的顺序） |
| **单位** | M1/M2 写 **kJ**；最终答案写 **kJ/mol**（`kJmol−1`）—— 见下方「单位规则」 |
| **符号** | 最终答案必须带符号；负值写 `−`，正值写 `+` |
| **什么时候用** | 题目给一张键能表 + 一个方程式，问 ΔH；或给 ΔH + 部分键能，问某个未知键能 |

### 官方方法词（逐字，各年措辞不同但结构一致）

| 用词 | 出处 |
|---|---|
| `M1 energy needed to break bonds` / `M2 energy released in making bonds` / `M3 energy change M1 − M2` | `0620/41 Oct/Nov 2022 Q5(d)(ii)`、`0620/42 Oct/Nov 2022 Q5(f)` |
| `M1 bond energy in breaking bonds` / `M2 Bond energy of ...` | `0620/42 Feb/March 2022 Q5(c)(ii)`、`0620/42 May/June 2024 Q3(e)`、`0620/42 Feb/March 2025 Q4(f)` |
| `M1 energy required in breaking bonds` / `M2 energy released when bonds are formed` / `M3 enthalpy change, [ΔH]` | `0620/43 May/June 2025 Q6(e)(iii)` |
| `energy needed to break bonds` / `energy released when bond in carbon dioxide form` / `calculate H−Cl bond energy` | `0620/42 Oct/Nov 2023 Q5(c)` |
| `(energy required to break bonds=)...` / `(energy given out when bonds form=)...` / `overall energy change ...` | `0620/42 May/June 2020 Q6(b)(ii)` |
| `bonds broken [...] (1)` / `bonds formed [...] (1)` / `energy change = M1 − M2 = ... (1)` | `0620/42 May/June 2021 Q5(b)(i)` |
| `energy needed to break bonds` / `energy released when bonds formed` / `energy change =...` | `0620/43 May/June 2020 Q3(d)` |

### 🔧 三步模板（变体 A：正着算，3 分 —— 出现频率最高的形态）

```
Step 1  bonds broken（反应物里所有键逐个加起来）        ← M1
Step 2  bonds formed（产物里所有键逐个加起来）           ← M2
Step 3  ΔH = Step 1 − Step 2 = ...                      ← M3（必须带符号）
```

**逐键划掉法（考官在 m22 的 ER 里亲自推荐）**：`Some candidates used the good practice of pencilling out bonds in the structures to ensure every bond was accounted for.` —— **在结构式上把每个键划一笔**，划满即加满。漏键是排第二的失分点。

### 🔧 四步模板（变体 B：给 ΔH，求未知键能，4 分）

```
Step 1  bonds broken（反应物总键能）                     ← M1
Step 2  由 ΔH 反推：bonds formed = Step 1 − ΔH           ← M2  ★最容易错的一步
Step 3  bonds formed − 已知键能 = 未知键的总键能          ← M3
Step 4  总键能 ÷ 该键的个数 = 每一个键的键能              ← M4  ★最容易被忘的一步
```

> **★ 2026 官方原文确认（`0620_s26_ms_42.txt`，Q5(c)(iii) 的 `Guidance` 栏）**：`M2 A ECF for = M1 + 870` —— **MS 亲手写出了「M1 **加** 870」**，这是「ΔH 为负 ⇒ 加 |ΔH|」在评分标准里的直接证据（同一栏还有 `M3 = A ECF for M2 − 810`）。

> **Step 2 的符号处理（本单元第一大失分点，被五份 ER 点名）**：
> ```
> bonds formed = bonds broken − ΔH
> 若 ΔH 为负（放热）→ bonds formed = bonds broken + |ΔH|      ← 是【加】不是【减】
> ```
> 记忆：**放热意味着产物的键比反应物的键「更结实」、总键能更大**（多了 180 / 105 / 130 kJ/mol 那份）。所以**要把 |ΔH| 加上去**。

> **Step 4 单独占 1 分** —— **五道** 4 分题的最后一步都固定给「除以键的个数」：
> `M3/2 = 680/2 = 340`（m22）、`1720/4 = 430`（w23）、`934 ÷ 2 = 467`（w25/41）、**`1230 ÷ 3 = 410`（m26/42）**、**`1680 ÷ 3 = 560`（s26/42）**。
> **看到 4 分的空，就知道最后一定要除。**

### 🔧 变体 C：只算「变化的键」（MS 明确承认的第二种解法）

`0620/43 Oct/Nov 2025 Q4(b)`（C₂H₄ + Cl₂ → CH₂ClCH₂Cl）**原文明说两种方法都给满分**：

> ```
> USUAL METHOD
> M1 2490        M2 2670        M3 -180
>
> ALTERNATIVE METHOD
> M1 850         M2 1030        M3 -180
> ```
> `(来源: 0620/43 Oct/Nov 2025 Q4(b)，MS 逐字照录)`

**两种方法怎么对应：**

| 方法 | M1（断键） | M2（成键） |
|---|---|---|
| **USUAL** | 4×C−H + C=C + Cl−Cl = 4×410 + 610 + 240 = **2490** | 4×C−H + C−C + 2×C−Cl = 4×410 + 350 + 2×340 = **2670** |
| **ALTERNATIVE**（两侧相同的 4×C−H 直接抵消） | C=C + Cl−Cl = 610 + 240 = **850** | C−C + 2×C−Cl = 350 + 680 = **1030** |

> **两式相减结果完全一样**（2490 − 2670 = −180；850 − 1030 = −180），因为两边同时减掉了 4×C−H。
> **判分含义**：**只要化学上自洽，非教科书解法照收**。但**推荐走 USUAL**——M1/M2 的分值更容易在部分错误时保住（考官能看出你在算什么）。

> 同源的还有 `0620/42 May/June 2020 Q6(b)(ii)`（丙烯 + Cl₂）：`(energy required to break bonds=)854` = C=C 612 + Cl−Cl 242（**6 个 C−H 两边抵消**），`(energy given out when bonds form=)1025` = C−C 347 + 2×C−Cl 678。

### 📊 18 道真题全表（MS 逐字，含真题反应）

**A 组 —— 正着算（断键 − 成键），全部 3 分（除注明者）**

| # | 出处 | 反应 / 已知键能 | MS 逐字 | 分 |
|---|---|---|---|---|
| 1 | `0620/42 May/June 2020 Q6(b)(ii)` | C₃H₆ + Cl₂ → C₃H₆Cl₂<br>C−C 347 / C=C 612 / C−H 413 / C−Cl 339 / Cl−Cl 242 | `(energy required to break bonds=)854 (1)`<br>`(energy given out when bonds form=)1025 (1)`<br>`overall energy change 854−1025=[−]171 (1)` | 3 |
| 2 | `0620/43 May/June 2020 Q3(d)` | H₂ + Cl₂ → 2HCl<br>H−H 436 / Cl−Cl 243 / H−Cl 432 | `energy needed to break bonds = 436+243=679`<br>`energy released when bonds formed = 2×432=864`<br>`energy change =679−864=[−]AND 185`（**原文残缺**，`AND` 无法还原） | 3 |
| 3 | `0620/42 May/June 2021 Q5(b)(i)` | N₂ + 3F₂ → 2NF₃<br>N≡N 945 / F−F 160 / N−F 300 | `bonds broken [945 + (3 × 160)] = 1425 (1)`<br>`bonds formed (2 × 3 × 300) = 1800 (1)`<br>`energy change = M1 − M2 = 1425 − 1800 = [−]375 (1)` | 3 |
| 6 | `0620/41 May/June 2022 Q7(e)` | Br₂ + Cl₂ → 2BrCl<br>Br−Br 190 / Cl−Cl 242 / Br−Cl 218 | `432(1)`（= 190+242）<br>`436(1)`（= 2×218）<br>`[−]4(1)` | 3 |
| 7 | `0620/41 Oct/Nov 2022 Q5(d)(ii)` | C₂H₄ + Br₂ → C₂H₄Br₂<br>C−H 410 / C=C 610 / Br−Br 190 / C−C 350 / C−Br 290 | `M1 energy needed to break bonds`<br>`4 × C−H + C=C + Br−Br = 4 × 410 + 610 + 190 = 2440(kJ) (1)`<br>`M2 energy released in making bonds`<br>`4 × C−H + C−C + 2 × C−Br = 4 × 410 + 350 + 2 × 290 = 2570(kJ) (1)`<br>`M3 energy change M1 − M2 = [−]130(kJ/mol) (1)` | 3 |
| 8 | `0620/42 Oct/Nov 2022 Q5(f)` | C₂H₆ + Cl₂ → C₂H₅Cl + HCl<br>C−H 410 / C−C 350 / Cl−Cl 240 / C−Cl 340 / H−Cl 430 | `M1 energy needed to break bonds`<br>`6 × C−H + C−C + Cl−Cl = 6 × 410 + 350 + 240 = 3050(kJ/mol) (1)`<br>`M2 energy released in making bonds`<br>`5 × C−H + C−C + C−Cl + H−Cl = 5 × 410 + 350 + 340 + 430 = 3170(kJ/mol) (1)`<br>`M3 energy change M1 − M2 = [−]120(kJ/mol) (1)` | 3 |
| 9 | `0620/43 Oct/Nov 2022 Q6(a)(i)` | CH₂ClCH₂Cl → CH₂=CHCl + HCl | `M1 2670 (1)`<br>`M2 2610 (1)`<br>`M3 (+) 60 (1)`（→ 下一问据此判 **endothermic**） | 3 |
| 13 | `0620/41 May/June 2025 Q6(d)(ii)` | I₂ + Br₂ → 2IBr<br>I−I 150 / Br−Br 193 / I−Br 175 | `M1 343`<br>`M2 350`<br>`M3 [−]7` | 3 |
| 14 | `0620/43 May/June 2025 Q6(e)(iii)` | I₂ + Cl₂ → 2ICl<br>I−I 150 / Cl−Cl 242 / I−Cl 218<br>（QP 印有 "Your answer should include a sign."） | `M1 energy required in breaking bonds = 150 + 242 = (+) 392`<br>`M2 energy released when bonds are formed = 2 × 218 = (+) 436`<br>`M3 enthalpy change, [ΔH] = 392 − 436 = [−] 44` | 3 |
| 16 | `0620/43 Oct/Nov 2025 Q4(b)` | C₂H₄ + Cl₂ → CH₂ClCH₂Cl<br>C−C 350 / C=C 610 / C−H 410 / Cl−Cl 240 / C−Cl 340<br>（QP 印有 "Your answer should include a sign."） | **两种方法都给分**（见变体 C）：<br>`USUAL METHOD` `M1 2490` `M2 2670` `M3 -180`<br>`ALTERNATIVE METHOD` `M1 850` `M2 1030` `M3 -180` | 3 |

**B 组 —— 给 ΔH，求未知键能**

| # | 出处 | 反应 / 已知 | MS 逐字 | 分 |
|---|---|---|---|---|
| 4 | `0620/42 Oct/Nov 2021 Q4(d)` | Cl₂ + CO → COCl₂<br>QP 给的是**文字**："230kJ of energy is released"（ΔH = [−]230） | `M1 bond energy in making bonds = [(2 × 400) + 745] = 1545 (kJmol−1)`<br>`M2 use of total E change`<br>`[−]230 = [240 + E(CO)] − 1545`<br>`OR [240 + E(CO)] = [−]230 + 1545 = (+1315)`<br>`M3 E(CO) = [[−]230 + 1545] − 240 = 1075 (kJmol−1)` | 3 |
| 5 | `0620/42 Feb/March 2022 Q5(c)(ii)` | C₂H₄ + Cl₂ → C₂H₄Cl₂<br>QP 给 ΔH = `[−]180kJ/mol` | `M1 Bond energy in breaking bonds = [(4 × 410) + 610 + 240] = 2490 (kJ/mol)`<br>`M2 Use of total E change to find bond energy of C2H4Cl2 = M1 + 180 = 2490 + 180 = 2670 (kJ/mol)`<br>`M3 Determination of total C−Cl bond energy = M2 − [(4 × 410) + 350] = 2670 − 1990 = 680 (kJ/mol)`<br>`M4 Determination of each C−Cl bond energy = M3/2 = 680/2 = 340 (kJ/mol)` | **4** |
| 10 | `0620/42 Oct/Nov 2023 Q5(c)` | CCl₄ + 2H₂O → CO₂ + 4HCl<br>QP 给 ΔH = `[−]130 kJ/mol` | `energy needed to break bonds in reactants`<br>`M1 [(4 × 340) + (4 × 460)] = 3200 (kJ/mol) (1)`<br>`energy released when bond in carbon dioxide form`<br>`M2 2 × 805 = 1610 (kJ/mol) (1)`<br>`calculate H−Cl bond energy`<br>`M3 3200 − (1610 + E(4H−Cl)) = [−] 130`<br>`E(4H−Cl) = 3330 − 1610 = 1720 (kJ/mol) (1)`<br>`M4 1720/4 = 430 (kJ/mol) (1)` | **4** |
| 11 | `0620/42 May/June 2024 Q3(e)` | Haber：N₂ + 3H₂ → 2NH₃<br>QP 给 ΔH = `[−]90 kJ/mol`<br>N≡N 945 / H−H 435 | `M1 bond energy in breaking bonds = [945 + (3 × 435)] = (+) 2250(kJ/mol)`<br>`M2 = 2250 + 90 = 2340`<br>`3(f)(i) M3 = 2340/6 = 390` | 3 |
| 12 | `0620/42 Feb/March 2025 Q4(f)` | CO + Cl₂ → COCl₂<br>QP 给 ΔH = `[−]105 kJ/mol`<br>C≡O 1075 / Cl−Cl 240 / C−Cl 340 | `M1 Bond energy in breaking bonds = 1075 + 240 = (+) 1315`<br>`M2 Bond energy of COCl2 = 1315 − ([−]105) = 1420`<br>`M3 C=O = 1420 − 2 × C−Cl = 1420 − (2 × 340) = (+) 740` | 3 |
| 15 | `0620/41 Oct/Nov 2025 Q4(b)` | SF₄ + 2H₂O → SO₂ + 4HF<br>QP 给 ΔH = `[−]54 kJ/mol`<br>S−F 330 / O−H 460 / H−F 570 | `M1 = (4 × S−F) + (4 × O−H) = (4 × 330) + (4 × 460) = 3160`<br>`M2 bond energy of products − 3160 = [−]54`<br>`= 3160 − ([−]54) = 3214`<br>`M3 (2 × S=O) + (4 × H−F) = 3214 therefore 2 × S=O = 3214 − (4 × 570) = 934`<br>`M4 S=O = M3÷2 = 934 ÷ 2 = 467` | **4** |
| **17** | **`0620/42 Feb/March 2026 Q4(d)`** | **3H₂ + CO₂ → CH₃OH + H₂O**（甲醇合成）<br>QP 给 ΔH = `[−]40 kJ/mol`<br>H−H 440 / C=O(CO₂) 805 / O−H 460 / C−O 360（**C−H 待求**） | `M1 bond energy in breaking bonds`<br>`= 3 × 440 + 2 × 805 = 2930 on answer line 1`<br>`M2 = 2 × 460 = 920 on answer line 2`<br>`M3 = determination of total E(C−H)`<br>`2930 − [920 + 360 + 460 + E(3 × C−H)] = [−]40`<br>`E(3 × C−H) = 2930 − (920 + 360 + 460) + 40 = 1230`<br>`OR E(3 × C−H) = 2930 − (1740) + 40 = 1230`<br>`M4 = 1230 ÷ 3 = 410` | **4** |
| **18** | **`0620/42 May/June 2026 Q5(c)(iii)`** | **NH₃ + 3F₂ → NF₃ + 3HF**<br>QP 给 ΔH = `[−]870 kJ/mol`<br>N−H 390 / F−F 150 / N−F 270（**H−F 待求**） | `M1 BE needed in breaking bonds`<br>`= 3 × 390 + 3 × 150 = 1620 on answer line 1`<br>`M2 BE released forming bonds`<br>`= 1620 + 870 = 2490 on answer line 2`<br>`M3 BE energy of 3H−F bonds`<br>`= 2490 − (3 × 270) = 1680`<br>`M4 BE of each H−F bond`<br>`= 1680 ÷ 3 = 560 on answer line 3` | **4** |

### ★★★ 2026 新评分标准：s26 的 `Guidance` 栏（**容差范围原文**）

`0620/42 May/June 2026` 的 MS **首次给键能计算配了 `Guidance` 栏**（旧卷只有 `Answer` + `Marks`）。这一栏把「哪一步可以 ECF、ECF 到什么程度、有效数字要求」全部写死 —— 是**判分规则层面最重要的新证据**：

> `5(c)(iii) M1 BE needed in breaking bonds`　**4**　`Mark each marking point but see M4/M3 comment below`
> ```
> M1  I signs on M1 and M2
>
> M2  A ECF for = M1 + 870
>
> M3  = A ECF for M2 � 810 (even if M3 is a negative value)
>
> M4  = A ECF for M3/3
>     A M4 subsumes M3 if 2490/�2490 seen on line 2
>     A M4 subsumes M3 as an ECF if M4 = (incorrect M2 � 810) � 3
>
>     For M3/M4
>     A M3 for a calculation where �1680 divided by �3 is seen (probably
>         due to algebraic work) and M4 for 560
>     Do not allow M3 for a calculation in which � 1680 is divided by 3 but
>         A M4 ECF if 560 is subsequently seen (i.e. sign has been changed to
>         match the positive nature of bond energy) or � 560 for a correct
>         division
>     But � 560 without calculations does not get M4
>
>     If applying ECF to M4 from incorrect M3
>     A M4 for M3 �3 whether M4 is positive or negative
>     A M4 for negative processed number � �3 to give +ve M4 value as ECF
>     M4 must be to minimum of 2 SF
>     A ECF for any processed number (need not be evaluated) correctly � 3
>     A truncation for ECF and I RE after 3rd SF
>
>     A M4 for M2 � 3 (if no attempt at M3)
> ```
> **`Special case`**
> ```
> If �2490 (if seen in M2) and is used to calculate M3 = �3300 do not
> award M3 but A M4 for �1100 or +1100
> ```
> （`A` = accept 给分，`I` = ignore 忽略，`R` = reject 拒绝，`SF` = significant figures，`RE` = rounding error。）

> **从这一栏能提炼出的四条硬规则：**
> 1. **`I signs on M1 and M2`** —— **M1/M2 必须写正数**（旧的 m25 MS 里 `(+) 2250` 的那个 `(+)` 不是必需的）。M1/M2 带符号会被 ignore。
> 2. **`M2 A ECF for = M1 + 870`** —— **官方亲手确认了符号方向**：ΔH 为负 ⇒ 产物键能 = M1 **+** |ΔH|。这是本笔记从头强调的「是加不是减」在 2026 年的 MS 原文。
> 3. **`M4 must be to minimum of 2 SF`；`A truncation for ECF and I RE after 3rd SF`** —— 最后一步**至少 2 位有效数字**；**截断（truncation）可以，四舍五入误差在第 3 位有效数字之后可以忽略**。这是**本单元唯一一处明写有效数字容差**的地方。
> 4. **`A M4 subsumes M3` / `A M4 for M2 ÷ 3 (if no attempt at M3)`** —— 如果考生**跳步**直接写对最终答案，**M4 可以把 M3 吃掉**（即跳步不扣分）。**「Special case」** 更进一步：错把 M2 的 2490 当成 M3 去算成 3300，**M3 不给但 M4 照给**。
>
> → **实践结论**：**能写全步骤就写全**（M1/M2/M3 各自独立），但**万一跳步、真的把最终答案算对了，M4 仍然拿得到** —— 所以**先确保最终答案写对**。

### 从这 18 份 MS 反推出的六条格式规则

1. **方法分与答案分分开给。** M1 = 断键能总和，M2 = 成键能总和（或由 ΔH 反推的总键能），M3 = 相减结果。**算错但方法对仍得 M1/M2** —— m22 的 ER 明确写了 `Error carried forward marks were able to be awarded to candidates who showed clear working.` **所以永远把两步的和式写出来，不要只给一个最终数。**（2026 的 `Guidance` 栏把 ECF 写到极致：`A M4 for M2 ÷ 3 (if no attempt at M3)`、`A M4 subsumes M3` —— 见上方 ★★★。）
2. **单位**：MS 括号里写 `(kJ/mol)` 或 `(kJmol−1)`，但 QP 的空格本身印的是 `kJ` 或 `kJ / mol`。**M1/M2 常只写 `kJ`，M3 写 `kJ/mol`**（如 w22 那两道：`2440(kJ)` vs `[−]130(kJ/mol)`）。→ **答题时 M1/M2 写 kJ、最终答案写 kJ/mol 最稳。**
3. **「符号」是硬要求。** `0620/43 May/June 2025`、`0620/43 Oct/Nov 2025` 的 QP 直接在空后印 **"Your answer should include a sign."**；`0620/42 Feb/March 2025 Q4(d)` 印 "Include a sign in your answer."。**MS 里所有负值一律带 `[−]`。**
4. **求「未知键能」的题（**5 道 4 分题**：#5 / #10 / #15 / #17 / #18）必须走完四步**，最后那一步（除以 2 / 除以 3 / 除以 4）**单独占 1 分**。忘了除，最多 3/4 分。
5. **一份 MS 给了两种算法并都给分**（#16）：只要化学上自洽，**非教科书解法照收**。
6. **#1 用的是「只算变化的键」路数**（6 个 C−H 两边抵消），与 #16 的 ALTERNATIVE METHOD 同源。

### ⚠️ 陷阱 —— 六大错法（全部有 ER 原文）

> **★ 错法 1：反向相减 / 符号搞反 —— 被五份 ER 独立点名，本单元第一大失分点，没有第二个错误被点名这么多次。**
>
> `In general, candidates were confident in performing the two calculations involving bond energies and the answers 1425kJ and 1800kJ were frequently seen. However, a significant minority did not realise that the net energy change was found by subtracting 1800 from 1425 to give –375kJ/mol. Doing the reverse subtraction to give +375kJ/mol was a common error.`
> `(0620_s21_er.txt，Paper 0620/42 Q5(b)(i))`
>
> `(e) This was answered well. A number of candidates multiplied the correct value of energy required to break the bonds by 2 giving a value of 864. Some gave 4 rather than –4 as the answer.`
> `(0620_s22_er.txt，Paper 0620/41 Q7(e))`
>
> `(ii) This calculation was done very well by the majority of candidates who produced a correct answer of -130 kJ/mol. The most common error was +130 kJ/mol.`
> `(0620_w22_er.txt，Paper 0620/41 Q5(d)(ii))`
>
> `(f) In general, candidates were confident in performing the two calculations involving bond energies, and the answers 3050kJ and 3170kJ were frequently seen. However, a significant minority did not realise that the net energy change was found by subtracting 3170 from 3050 to give -120kJ/mol. Doing the reverse subtraction to give +120kJ/mol was a common error.`
> `(0620_w22_er.txt，Paper 0620/42 Q5(f))`
>
> `(iii) In general, candidates were confident in performing the two calculations involving bond energies and the answers 392kJ and 436kJ were frequently seen. However, a significant number carried out the final subtraction in reverse to give +44kJ/mol.`
> `(0620_s25_er.txt，Paper 0620/43 Q6(e)(iii))`
>
> → **记法**：**ΔH = 断键能 − 成键能，永远是「先断后成」，绝不倒过来。** 三条证据链：反应物里的键必须先断（这些键的键能是「花出去」的），产物里的键生成时把能量「还回来」；花 > 还 = 放热 = 负。
>
> **另一个更快的自查法**：算出的 ΔH **符号必须与题目的热效应一致**。题目说 exothermic 而你算出正数 → 立刻倒过来。

> **★ 错法 2：ΔH 为负时把 |ΔH| 减掉而不是加上（变体 B 的 Step 2）。**
> `In step 2 candidates were expected to realise that if the total energy change was –180kJ/mol then the energy released in formation of product bonds must be 180kJ/mol more than step 1. Frequently many assumed it to be 180kJ/mol less.`
> `(0620_m22_er.txt，Paper 0620/42 Q5(c)(ii))`
> `The most common error was to subtract the magnitude of the enthalpy change (105 kJ/mol) rather than add it for step 2.`
> `(0620_m25_er.txt，Paper 0620/42 Q4(f))`
> `Misreading the question and adding the H value of 130kJ to 1610kJ to give 1740kJ.`（这是另一种错法：把 |ΔH| 加到了**不该加的那一步**上）
> `(0620_w23_er.txt，Paper 0620/42 Q5(c))`
> → **规则**：`bonds formed = bonds broken − ΔH`。ΔH 为负 ⇒ **加** |ΔH|。

> **★ 错法 3：漏数键。**
> `Occasionally the Cl–Cl bond was omitted.`
> `(0620_m22_er.txt，Paper 0620/42 Q5(c)(ii))`
> `• Omitting two O–H bonds and arriving at a value of 2280kJ for the first answer.`（正确值 3200 kJ）
> `(0620_w23_er.txt，Paper 0620/42 Q5(c))`
> `The most common errors were missing out a bond or bonds and carrying out the subtraction the wrong way round.`
> `(0620_w22_er.txt，Paper 0620/43 Q6(a)(i))`
> → 用考官推荐的 **`pencilling out bonds in the structures`**：在结构式上逐键划掉。

> **★ 错法 4：不懂每一步在算什么。**
> `Many candidates also wrote '680' or '680 + x' as the second answer rather than giving the bond energy of COCl2 suggesting they may not understand what they are calculating at each step.`
> `(0620_m25_er.txt，Paper 0620/42 Q4(f))`
> `Many candidates were unable to incorporate the H value of 130kJ correctly into their calculation to find the total H–Cl bond energy.`
> `(0620_w23_er.txt，Paper 0620/42 Q5(c))`
> `Most candidates did not appreciate that the 230kJ/mol of energy released in the reaction must be used in the calculation.`
> `(0620_w21_er.txt，Paper 0620/42 Q4(d))`
> → **每一步都写下它的名字**（`energy needed to break bonds = ...` / `energy released when bonds form = ...` / `energy change = ...`）。**写出名字不仅帮你不迷路，还直接对应 MS 的 M1/M2/M3 给分点。**
>
> **2026 年的同一诊断（m26，新格式）** —— `0620_m26_er.txt`，Paper 0620/42 Q4(d)：
> ```
> (d)  Comprehensive responses
>      • Most candidates were able to calculate the energy needed to break the bonds in the reactants.
>      • Many candidates were able to calculate the energy released when the bonds in water form.
>      • Some candidates were able to use these two calculated figures to determine the bond energy
>             of the C�H bond.
>      • Some candidates who arrived at the correct answer did not work through the calculation steps
>             requested while showing a clear and logical approach.
>
>      Limited responses
>      • Some candidates made progress with the first two bullet pointed steps and then did not fully
>            understand how the bond energy required could be calculated.
>      • Some candidates calculated a negative energy value in the last part which would lead to a
>            negative bond energy value.
> ```
> → **2026 年的典型失分链条**：M1、M2 大多数人都会（`Most` / `Many`）→ **到 M3 就掉队**（`Some`）→ 具体表现为「不知道这个键能要怎么求」，甚至**算出负数键能**。
> → **新出现的错法：键能算出负值。** 键能永远是**正数**；如果你最后一步得到负数，说明你在 M3 那一步减错了对象（要么把产物键能减反了，要么忘了 ΔH 该加不该减）。**当场自查：一个键的键能是负数在物理上不可能。**

> **★ 错法 5：方程式配平不是 1 mol 时按 1 mol 算（MCQ 陷阱）。**
> `This question has an additional challenge because the equation was balanced using two moles of ethyne rather than one. The most common answer was option A where this was not recognised. Most candidates did recognise that the correct value is a negative number with few choosing options C or D.`
> `(2024 年 0620/22 Q15；底稿同时标注 `0620_m24_er.txt` 与 `0620_w24_er.txt`，**具体考季存疑**，但题干特征明确：方程式用了 2 mol ethyne)`
> → **方程式里的系数必须乘进去。** 看到 `2C₂H₂ + ...` 就要把所有键能 ×2。

> **★ 错法 6：最终答案不带符号 / 符号写在中间步骤。**
> `(ii) This was answered very well. Some final answers did not have a sign despite the instruction. Others showed signs on the first two values.`
> `(0620_s25_er.txt，Paper 0620/41 Q6(d)(ii))`
> → **符号只应出现在最终 ΔH 上**：M1/M2 写正数（或按 MS 的 `(+) 2250` 写法），M3 写符号。

> **错法 7（附带）：断键总和被误 ×2。**
> `A number of candidates multiplied the correct value of energy required to break the bonds by 2 giving a value of 864.`
> `(0620_s22_er.txt，Paper 0620/41 Q7(e))`
> （Br₂ + Cl₂ → 2BrCl：断键 190+242=432，被误乘 2 成 864。）
> → **只有「产物里出现 2 个同样的键」时才乘 2**（如 2BrCl 里的 2 × Br−Cl），**反应物侧不要重复乘**。

### 🔧 考场操作顺序（照做）

```
① 抄下方程式，把两侧的键逐个列出来（在草稿上用结构式划键）
② 写 "energy needed to break bonds = <和式> = <数> kJ"     ← M1
③ 写 "energy released when bonds form = <和式> = <数> kJ"   ← M2
④ 写 "ΔH = ② − ③ = <数> kJ/mol"                            ← M3（带符号！）
⑤ 若题目给 ΔH 求未知键能：
     "bond energy of products = ② − ΔH = <数>"                ← M2
     "<未知键总键能> = 上一步 − 已知键能 = <数>"               ← M3
     "<单个键能> = 上一步 ÷ <键的个数> = <数>"                ← M4（4 分题必有）
⑥ 自查：答案符号与题目说的 exo/endo 一致吗？单位写了吗？4 分的题除了吗？
    求出来的键能是【正数】吗（负数说明减错了）？至少 2 位有效数字吗？（s26 Guidance：`M4 must be to minimum of 2 SF`）
```

---

## ⛔ 超纲，不用背（投入产出比为零）

考纲 5.1 **不包含**以下内容。它们在参考书/网上笔记里很常见，但**不会考**：

| 超纲内容 | 说明 |
|---|---|
| **Standard enthalpy change / standard conditions**（101 kPa, 298 K, 1.0 mol/dm³） | 考纲无。考纲只要求「transfer of thermal energy 叫 ΔH」+ 正负号约定 |
| **Hess 定律**、ΔH = ΣH(products) − ΣH(reactants) 的**焓变循环** | 考纲无。5.1-8 只要求**用键能算** ΔH |
| **量热法（calorimetry）**：polystyrene 杯、保温、ΔT 与水质量成反比、测温精度 | 属于 **Paper 6 实验技能（Section 4）**，**不是 5.1**。语料里 0620/6x 只在热学实验里出现 Topic 5 关键词。**不要把量热计算混进 5.1 复习** |
| **Allotropes 选能量更稳定的**（石墨 vs 金刚石）、"exothermic 更 energetically favourable" | 考纲无 |
| **Enthalpy 是 state function** | 考纲无 |
| **Boltzmann 分布曲线** | 考纲 Supplement 只要求 `kinetic energy of particles`（属 6.2 碰撞理论），**未要求画分布曲线** |
| **Haber process 的 ΔH = −92 kJ/mol 具体数值** | 考纲不要求数值（数值只在真题里以「给定信息」出现） |

> 参考笔记（`ref/haoye.txt` 5.1.2 节，1267 字符）把上面大部分内容都写了 —— 这是**「把我学过的都记下来」**的定位，不是本套笔记的定位。**跳过。**

---

# 📝 考试怎么考

## Paper 4（Theory，50%）

- **Topic 5 从不单独成题。** 它永远**寄生在别人的大题里**：
  - **Haber process 题** → 顺势问 ΔH 定义(1) + 键能计算(3–4)
  - **有机加成反应题**（C₂H₄ + Cl₂ / C₂H₄ + Br₂ / 烯烃 + HCl）→ 顺势问键能计算(3) + 路径图(3) + 键与键能解释(1–3)
  - **卤素/卤化氢题**（Br₂ + Cl₂、I₂ + Cl₂）→ 纯键能计算(3)
  - **★ 2026 新模式：可逆反应 / 平衡题**（甲醇合成 `3H₂ + CO₂ ⇌ CH₃OH + H₂O`；`NH₃ + 3F₂ ⇌ NF₃ + 3HF`）→ 顺势问**符号判定(1–2) + 路径图(3) + 逆反应 ΔH 与 Ea(2) + 键能计算(4)**。**这是 Topic 5 与 Topic 6.3 的合并考法，2026 年 m26 与 s26 两份 Paper 4 连续这样出** —— 本单元与「可逆反应」一起复习效率最高。
- **位置**：多见于 **Q3–Q5**。
- **两种固定组合：**

| 组合 | 结构 | 例 |
|---|---|---|
| **A（计算型）** | 键能计算 3 分，或「给 ΔH 求未知键能」4 分 | `0620/42 Feb/March 2025 Q4(f)` |
| **B（定义 + 图 + 计算混合型）** | ΔH 定义(1) + **路径图(3)** + Ea 定义(2) + 催化剂(1) + 键能计算(4) | **`0620/42 Oct/Nov 2023 Q5` = 单题 11 分 Topic 5** |
| **C（2026 新模式：平衡 + 能量）** | 符号判定(2) + 平衡表(4) + **路径图(3) + 逆反应 ΔH/Ea(2) + 键能计算(4)** | **`0620/42 Feb/March 2026 Q4` = 单题 11 分 Topic 5**<br>**`0620/42 May/June 2026 Q5` = 符号判定(2) + 路径图(3) + 键能计算(4) = 9 分** |

- **⭐ 若只做一套真题（老卷），做 `0620/42 Oct/Nov 2023 Q5`** —— 同一题内包齐 ΔH 定义(1) + 路径图(3) + Ea 定义(2) + 催化剂(1) + 键能计算(4) = **11 分**，是该 ER 讲评最长的一道。
- **⭐ 若只做一套真题（最新考纲口径），做 `0620/42 Feb/March 2026 Q4`** —— 符号判定(2) + 平衡表(4) + 路径图(3) + 逆反应 ΔH/Ea(2) + **键能计算 4 分** = **11 分 Topic 5**。**它用的就是 2026 年的新评分格式**（s26 的 `Guidance` 栏要配 s26 的题看）。**做这一套能同时见到 5.1-4 / 5.1-6 / 5.1-8 三条要求的最新考法。**
- **⭐ 第二大：`0620/42 Feb/March 2025 Q4`** —— ΔH 定义(1) + 符号判定(1) + 逆反应 ΔH(1) + 键能计算(3) = **6 分**。
- **⭐ w22 是**唯一**三份 Paper 4 全考的 session**（41/42/43 各有一道键能计算）；**w25 也不遑多让**（41 路径图 4 分 + 键能 4 分，43 ΔH + 符号 + 键能）。**2026 年 s26 也是三份 Paper 4 齐全，但只有 /42 含 Topic 5**（s26/41、s26/43 只考了 6.3 平衡）。
- **三个「提分信号」**：
  - **看到 4 分的空 → 最后一定要除以键的个数**（18 道题里 5 道是 4 分，**全部**是求未知键能型）。
  - **看到空后印着 "Your answer should include a sign." → 那一分就是白送的提醒**（2026 年 m26/42 Q4(c)(ii) 一问里印了**两次**）。
  - **看到题目要求「Use the following steps」/ 分三个答案空 → 这是 4 分题**（`0620/42 Feb/March 2026 Q4(d)` 的三个答案空 = M1 / M2 / M4）。

## Paper 2（MCQ，30%）

- **几乎每年一道 ΔH / Ea 辨析题**（2020–2025 的 42 份 Paper 2 全部含 Topic 5 关键词，合计 227 处；**2026 的 m26/s26 四份 MCQ 卷也每份都有一道** —— 见下方「2026 年的 MCQ」）。
- 被 ER 点名的具体 MCQ：

| 出处 | 内容 |
|---|---|
| `0620/23 June 2021 Q17` | 键焓计算：`This answer has the opposite sign to the correct answer, suggesting that candidates confused the sign of energy changes during bond breaking and bond forming.` |
| `0620/22 March 2022 Q13` | `Candidates often find bond energy calculations challenging. Some candidates appeared to be guessing.` |
| `0620/22 Q16` | `Some candidates confused the activation energy with the overall energy change of reaction, choosing option A.` |
| 2024 年 `0620/22 Q15` | 方程式配平用 **2 mol ethyne**，按 1 mol 算就错（考季存疑，见上） |
| `0620/22 Q14` | `Some candidates gave option C thinking that bond breaking released energy.` |
| `0620/23 Q16` | `Weaker candidates were most likely to choose option B, confusing the formation of bonds with an endothermic process.` |
| `0620/23 Q14` | `they did not recognise that the activation energy of a reaction does not change` |

> ⚠️ **MCQ 无法逐题计数**：Paper 2 的 MS 只给字母网格（如 "10 A 20 B 30 A 40 B"），不含题干。底稿只报告了关键词命中数与被点名的题号，**未做逐题计数**，本笔记不编造「每年几道」。

### ★ 2026 年的 MCQ（新增语料，已核对 MS 答案）

> 2026 年 m26/s26 的四份 Extended MCQ 卷**每份都有一道 Topic 5 题**，且**终于有题干可查**（旧卷只有字母网格）。这是本单元 MCQ 部分第一次有确凿的逐题证据：

| 出处 | 题干 | 答案 | 说明 |
|---|---|---|---|
| **`0620/22 Feb/March 2026 Q12`** | "Which statement describes activation energy?"（A 放能最多 / B 吸能最多 / **C It is the minimum energy colliding particles must have to react** / D 成键所需最低能量） | **C** | **大纲 Ea 定义的逐字版**（= 5.1-5）。**MCQ 把 `colliding particles` 直接写进了正确选项** —— 再次印证这个词不能丢 |
| **`0620/22 Feb/March 2026 Q13`** | 2H₂O₂ → 2H₂O + O₂，O−H 460 / O−O 150 / O=O 496，问 ΔH | **B（−196 kJ/mol）** | 断键 4×460 + 2×150 = 2140；成键 4×460 + 496 = 2336；ΔH = 2140 − 2336 = **−196** |
| **`0620/22 May/June 2026 Q14`** | N₂ + 3F₂ → 2NF₃，N≡N 950 / F−F 150 / N−F 280，问能量变化 | **B（−280 kJ/mol）** | 断键 950 + 3×150 = 1400；成键 6×280 = 1680；ΔH = **−280** |
| **`0620/23 May/June 2026 Q3`** | H−H 436 / Cl−Cl 242 / H−Cl 431，问「能量变化 + 反应类型」 | **B（184 exothermic）** | 断键 678；成键 2×431 = 862；ΔH = **−184**，放热。**干扰项 A 是 `184 endothermic`** —— 正是「反向相减 + 符号错」的 MCQ 版 |
| **`0620/21 May/June 2026 Q15`** | "Which equation represents an endothermic reaction?" | — | 反应类型辨识 |

> **三个可操作的提醒**：
> 1. **2026 的 MCQ 把「反向相减」做成了干扰项**（`184 endothermic` 对 `184 exothermic`）—— 和 Paper 4 的第一大失分点是同一个错误。
> 2. **m26/22 Q13 与 s26/22 Q14 都把键能写成 `+460`、`+150`、`+496`（带正号）** —— 键能表里的数字**全是正数**（键能恒为正），只有 ΔH 才带符号。**别被表里的 `+` 号骗了。**
> 3. **m26/22 Q12 证明 Ea 定义现在直接进 MCQ** —— 背 `the minimum energy that colliding particles must have to react` 是「Paper 2 + Paper 4 双收益」。

## Paper 6（实验卷，20%）

- **Paper 6 不考 5.1 的内容。** 语料里 0620/6x 只在**热学实验**（量热、保温、ΔT 与水质量成反比、测温精度）里出现 Topic 5 关键词，属于**实验技能（Section 4）**。例：`0620/62 May/June 2025 Q2(d)(e)(f)`、`0620/61 June 2023 Q2(c)(g)`、`0620/62 March 2025 Q1(d)(e)`。
- **结论**：复习 Topic 5 时**不要**花时间在量热计算上。

---

# 📊 真题实证

> **数据说明**：Paper 4 的语料现在实为 **46 份**（初版是 42 份）。m20–m26 七个 session **只提供 component 42**；s20–s26、w20–w25 十三个 session 才有 41/42/43 全套（7 + 21 + 18 = 46）。
> **ER 实为 18 份**：m20–m26、s21–s25、w20–w25 —— **只有 s20（考试取消）与 s26（尚未发布）没有 ER**。其中 m20、s24、w23、w24、w25、m26 六份包含本 Topic 最有价值的评语。
> **m 系列样本仍然偏少**（7 份 vs s 系列 21 份、w 系列 18 份），任何按 component 41/42/43 的分布统计在 m 系列上**不可靠**。

## ① 总考频

| 项目 | 数字 |
|---|---|
| Paper 4 中含至少一个 Topic 5 小问 | **27 / 46（≈59%）** |
| 其中最高频子话题 —— **键能计算 ΔH** | **18 / 46（39%）** |
| 键能计算合计分值 | **59 分**（3 分 × 13 + 4 分 × 5） |
| 审计修正后的 Topic 5 真实分值 | ≈115 marks / 3360 ≈ **3.4%**（基于初版 42 份；46 份口径下约 **3.6%**，每份 Paper 4 平均约 2.8 分） |

> ⚠️ 第一个数字（27/46）的构成：25 份来自初版 42 份的全量检索，**+2 份为本轮新核**（`0620/42 Feb/March 2026` Q4、`0620/42 May/June 2026` Q5 含 Topic 5）。同批新核的 `0620/41 May/June 2026` 与 `0620/43 May/June 2026` **不含** Topic 5（只考 6.3 平衡，`endothermic`/`exothermic` 只是给定信息）—— 这正是 `_research/frequency-audit.md` 点名的假阳性模式。

## ② 按子话题

| 子话题 | 出现份数 / 46 | 具体 papers |
|---|---|---|
| **键能计算 ΔH** | **18 份（39%）** | s20/42, s20/43, s21/42, w21/42, m22/42, s22/41, w22/41, w22/42, w22/43, w23/42, s24/42, m25/42, s25/41, s25/43, w25/41, w25/43, **m26/42, s26/42** |
| **路径图（画/补全）** | **7 份** | s20/43, w21/42, w22/41, w23/42, w25/41, **m26/42, s26/42** |
| **路径图（读图，变体）** | 1 份 | w22/42 |
| **ΔH 定义（`enthalpy change`）** | 5 份 | m23/42, s24/42, w23/42, m25/42, w25/43 |
| **exo/endo 由 ΔH 符号判定** | **6 份** | m23/42, m25/42, w24/43, w25/43, **m26/42, s26/42** |
| **逆反应的 ΔH 与 Ea（2026 新题型）** | **1 份** | **m26/42 Q4(c)(ii)** |
| **exo/endo 识别或解释** | ~10 份 | s20/41, w20/41, s21/42, w22/42, w22/43, s24/41, s24/43, s25/41, m20/42, w21/41 |
| **Ea 定义** | 2 份 | w23/42（2 分）, w24/42（1 分 + 1 分符号） |
| **键断/键生成解释 exo/endo** | 3 份 | w21/42（3 分）, s21/42（2 分）, w22/43（1 分） |

## ③ 键能计算的时间分布（最能说明「什么时候该复习」）

| Session | 41 | 42 | 43 |
|---|---|---|---|
| m20 | — | ✗ | — |
| m21 | — | ✗ | — |
| m22 | — | ✓ Q5(c)(ii) | — |
| m23 | — | ✗ | — |
| m24 | — | ✗ | — |
| m25 | — | ✓ Q4(f) | — |
| **m26** | — | **✓ Q4(d)** | — |
| s20 | ✗ | ✓ Q6(b)(ii) | ✓ Q3(d) |
| s21 | ✗ | ✓ Q5(b)(i) | ✗ |
| s22 | ✓ Q7(e) | ✗ | ✗ |
| s23 | ✗ | ✗ | ✗ |
| s24 | ✗ | ✓ Q3(e) | ✗ |
| s25 | ✓ Q6(d)(ii) | ✗ | ✓ Q6(e)(iii) |
| w20 | ✗ | ✗ | ✗ |
| w21 | ✗ | ✓ Q4(d) | ✗ |
| w22 | ✓ Q5(d)(ii) | ✓ Q5(f) | ✓ Q6(a)(i) |
| w23 | ✗ | ✓ Q5(c) | ✗ |
| w24 | ✗ | ✗ | ✗ |
| w25 | ✓ Q4(b) | ✗ | ✓ Q4(b) |
| **s26** | ✗ | **✓ Q5(c)(iii)** | ✗ |

> **趋势**：s20 起几乎每场都有（只有 s23、w24 空）；**w22 是唯一三份 Paper 4 全考的 session**；**m 系列（Feb/March）明显偏少**（7 场里只有 m22、m25、**m26**）。
> **2026 观察**：m26 与 s26 各只有一份 Paper 4 含键能计算，**且两份都是 4 分题**（求未知键能）—— 题型向「4 分 / 多步 / 带 Guidance 栏」收敛。s26 的另两份 Paper 4（41、43）完全没考 Topic 5。

## ④ 分值配置

| 分值 | 题数 | 题型 |
|---|---|---|
| **3 分** | 13 题 | 标准配置：正着算（M1/M2/M3），或给 ΔH 求未知键能但一步到位 |
| **4 分** | **5 题** | **全部是「求某个未知键能」** —— 多出来的 1 分**固定给最后一步除以键的个数** |

> **推论**：`0620/42 Feb/March 2022 Q5(c)(ii)`（**÷2**）、`0620/42 Oct/Nov 2023 Q5(c)`（**÷4**）、`0620/41 Oct/Nov 2025 Q4(b)`（**÷2**）、`0620/42 Feb/March 2026 Q4(d)`（**÷3**）、`0620/42 May/June 2026 Q5(c)(iii)`（**÷3**）。
> **2026 两年的两道都是 ÷3，且都印了三个独立的答案空**（`on answer line 1 / 2 / 3`）—— **三个空 = M1 / M2 / M4**（M3 与 M4 共用一个空）。看到三个空就知道要除。

## ⑤ 判分规则

### 全库通用：Science-Specific Marking Principles（逐字）

> 引自 `0620/41 Oct/Nov 2025` 第 3 页（措辞各年略有出入）：
> ```
> 1 Examiners should consider the context and scientific use of any keywords when awarding marks. Although
>   keywords may be present, marks should not be awarded if the keywords are used incorrectly.
>
> 2 The examiner should not choose between contradictory statements given in the same question part, and
>   credit should not be awarded for any correct statement that is contradicted within the same question
>   part. Wrong science that is irrelevant to the question should be ignored.
>
> 4 The error carried forward (ecf) principle should be applied, where appropriate. If an incorrect answer is
>   subsequently used in a scientifically correct way, the candidate should be awarded these subsequent
>   marking points.
>
> 5 'List rule' guidance
>   For questions that require n responses (e.g. State two reasons ...):
>   • The response should be read as continuous prose, even when numbered answer spaces are provided.
>   • Any response marked ignore in the mark scheme should not count towards n.
>   • Incorrect responses should not be awarded credit but will still count towards n.
>   • Read the entire response to check for any responses that contradict those that would otherwise be
>     credited.
> ```

### ★ 对定义题极关键的一条：术语等价即满分

> 出自 `0620/41 May/June 2024` MS 第 2 页（`0620_s24_ms_41.txt`），逐字：
> ```
> If the candidate uses different terminology to the terminology on the Mark Scheme full credit must be given
> if the meaning is the same.
> ```
> → 这解释了为什么 MS 上写 `enthalpy change (of reaction)`，而 ER 却承认 `energy change of reaction` 也拿分（`0620_m25_er.txt`：`Most candidates recognised the symbol and 'enthalpy change' or 'energy change of reaction'`）。
> **判分看的是含义，不是字面。** 但这**不等于可以乱写** —— ER 同时点名 `enthalpy`、`energy change`、`activation energy` 这三种写法**不够具体**（见 5.1.2 陷阱）。

### Topic 5 里实际出现的判分码

| 码 | 在 Topic 5 的实例 | 含义 |
|---|---|---|
| `M1/M2/M3/M4`（或 `step 1/2/3`） | **18 道键能题全部** | **方法分**，按步给，**互不牵连** |
| `(1)` 逐点 | 路径图题、定义题 | 每个标注点独立 1 分 |
| `AND` | 路径图 M2/M4 的 `AND` | 两个条件**同时满足**才给这 1 分 |
| `OR` | `0620/43 Oct/Nov 2022 Q6(a)(ii)` 的两条并列答案；`0620/42 Oct/Nov 2021 Q4(d)` 的 M2 两种写法 | 择一即可 |
| `ORA`（or reverse argument） | `0620/41 Oct/Nov 2020 Q5(b)(iii)`：`products have lower energy than reactants/ORA` | 反向表述同样给分 |
| `ecf` | `0620/42 Feb/March 2022` 的 ER 说明；通用原则 4 | 前一步算错，后一步方法对仍给分 |
| `any two from` | `0620/41 May/June 2025 Q6(e)(i)` 等 | 多答不倒扣，但按 List rule 处理 |
| **`Answer must reflect answer in 5(b)(i)`** | `0620/42 May/June 2021 Q5(b)(ii)` | **答案必须与前一小问自洽**（前面算出放热，这里才能判 exothermic） |
| **`USUAL METHOD` / `ALTERNATIVE METHOD`** | `0620/43 Oct/Nov 2025 Q4(b)` | **两种解法都满分** |
| **`A` = accept**（2026 新增） | `0620_s26_ms_42.txt` 的 `Guidance` 栏 | **明确给分**（如 `A double headed arrow for Ea`） |
| **`I` = ignore**（2026 新增） | 同上 | **写了不给分也不倒扣**（如 `I signs on M1 and M2`） |
| **`R` = reject**（2026 新增） | 同上 | **明确不给分**（如 `R 'diagonal' from reactant to products`） |
| **`SF` / `RE`**（2026 新增） | 同上 | `SF` = significant figures；`RE` = rounding error（`I RE after 3rd SF`） |

> ⚠️ **2026 起 MS 的写法变了**：`0620_m26_ms_42.txt` 仍是旧的 `Question | Answer | Marks` 三栏，但 **`0620_s26_ms_41/42/43.txt` 变成 `Question | Answer | Marks | Guidance` 四栏**，并且把「接受 / 忽略 / 拒绝」写进 `Guidance`（`A` / `I` / `R` 三个字母）。**这是本单元判分规则层面最大的格式变化** —— 复习时若能找到 2026 的 MS，**先读 Guidance 栏**。

### ★★★ 2026 年新增的 `Guidance` 栏 —— 本单元判分规则的最大更新

`0620_s26_ms_41/42/43.txt` 首次出现 **`Guidance` 第四栏**，逐条写明「接受 / 忽略 / 拒绝」与**容差范围**。本单元受影响的两处（**原文已逐字抄在对应考点**）：

| 考点 | 位置 | 新增的容差 / 接受规则 |
|---|---|---|
| **路径图** `5.1.4` | `0620_s26_ms_42.txt` Q5(c)(ii) | **Ea 接受双向箭头与无箭头竖线**；ΔH **必须只有一个箭头头**；斜线 `R`；箭头长度不精确给 ECF；起点终点 `near misses` 接受；一条线画两个箭头 + 虚线分隔 ⇒ M2/M3 都给 |
| **键能计算** `5.1.6` | `0620_s26_ms_42.txt` Q5(c)(iii) | **M1/M2 的符号被 `I`（不要写符号）**；`M2 A ECF for = M1 + 870`（**官方亲手确认加号方向**）；**M4 至少 2 位有效数字**；截断可以、3 位有效数字后的舍入误差忽略；**跳步 M4 可以吃掉 M3** |

> **一句话**：**旧规则（2020–2025 ER）偏严，新规则（2026 `Guidance`）在「画得不太精确」「跳步」上放宽，但在「ΔH 箭头的单向性」「M1/M2 不带符号」「有效数字」上写得更死。**
> **最稳的应考策略不变**：**照旧画规范图、照旧写全三步、照旧不带多余符号** —— 这样两套规则下都满分。

### ⚠️ 三个「查无实据」的判分码（**不要写进你的复习清单**）

- **`TV`：42 份 Paper 4 MS 中一次都没出现**（全库 `grep` 核实）—— 这个码在 0620 里**不存在**。
- **`BOD`：只在 `0620_s24_ms_41.txt` 出现过一次**，且**不在任何 Topic 5 答案里**，而是在阅卷员批注说明中：
  > `Any response that is worth more than 1 mark must be annotated by tick(s). The number of ticks should be the same as the number of marks awarded. This applies even if other annotations such as BOD or ECF are used.`
  → `BOD` 是**阅卷员批注符号**，不是答案里的判分码。
- **`do not accept`：全库（所有 ms 文件）一次都没出现。** Topic 5 的「不给分」是靠**答案清单本身**实现的（例如定义题只列 `enthalpy change (of reaction)`），不是靠 `do not accept` 标注。

> **实践含义**：**不要指望题目会告诉你「什么不能写」** —— 只有 MS 的答案清单是标准。写「意思相近但用词不是清单里的词」有风险，**背原文最安全**。

## ⑥ 考官报告怎么说 —— 跨年复发率排行

| 排名 | 错误 | 被点名次数 | 出处 |
|---|---|---|---|
| **1** | **反向相减 / ΔH 符号搞反** | **5 次**（s21/42、s22/41、w22/41、w22/42、s25/43） | 见 5.1.6 错法 1 |
| **2** | **exo / endo 判断反了** | 几乎每份 ER；Extended 卷至少 9 处（s24/41、s24/43、w25/43 ×2、s25/41、w25/23、w20/22、s22/22、w24/22） | 见 5.1.2 陷阱 6 |
| **3** | **ΔH 定义只写 `energy change`** | **4 次**（m23、m25、s24、w25） | 见 5.1.2 陷阱 1 |
| **4** | **Ea 定义漏 `colliding particles`** | **2 次**（w23、w24） | 见 5.1.3 陷阱 1 |
| **5** | **「成键需要能量」/「断键放能」的措辞** | 至少 4 处（s21/42、w21/42、w22/43、w20/22） | 见 5.1.5 陷阱 1–2 |
| **6** | **路径图画法不规范（双向箭头 / 无箭头竖线 / 斜线 / 只写 product）** | **5 处**（w21/42、w22/41、w23/42、w25/41、**m26/42**） | 见 5.1.4 陷阱 |
| **7** | **以为升温/降温会改变 Ea** | 4 处（s23/42、m23/42、m25/42、w23/42） | 见 5.1.3 陷阱 3 |
| **8** | **逆反应的 ΔH / Ea 填空（2026 新）**：漏符号、把 Ea 写成 `−220` | 1 处（**m26/42 Q4(c)(ii)**，同段点出两个错法） | 见 5.1.3 陷阱 6 |
| **9** | **键能算出负值（2026 新）** | 1 处（**m26/42 Q4(d)**） | 见 5.1.6 错法 4 |

## ⑦ 无法填补的缺口（如实说明）

1. **Paper 4 现在有 46 份**（初版 42 份）。m20–m26 七个 session 无 41/43。**m 系列样本仍偏少**（7 份 vs s 系列 21 份、w 系列 18 份），m 系列的 component 分布统计**不可靠**。
2. **没有 ER 的两个 session 是 s20（考试取消）与 s26（尚未发布）。** s20 恰好有两道键能计算（`0620/42 Q6(b)(ii)`、`0620/43 Q3(d)`）—— **这两道的考生表现无从得知**。
3. **Paper 2（MCQ）**：2020–2025 的 MS 只给字母网格、不含题干，**无法逐题归因**；但 **2026 的 m26/s26 MCQ 卷有题干可查**，本笔记已补上四道（见「Paper 2 怎么考 → 2026 年的 MCQ」）。**2020–2025 的 MCQ 仍不做逐题计数。**
4. **`0620/43 May/June 2020 Q3(d)` 的 M3 原文残缺**：`energy change =679�864=�AND 185` —— 其中 `AND` 无法还原。
5. **符号重建的固有风险**：所有 `�` 处均为推断，凡标 `[−]` 者依据是「exothermic ⇒ ΔH 为负」这一 MS 自身反复确认的约定。**未经 MS 交叉验证的行内 `�` 无法还原。**
6. **`0620/22` 2024 Q15（ethyne 2 mol）的考季存疑**：底稿在不同段落分别标注为 `0620_m24_er.txt` 与 `0620_w24_er.txt`，本笔记照实标明。

---

# ⚠️ 高频失分点汇总

| # | 陷阱 | 正确做法 | 证据 |
|---|---|---|---|
| 1 | **反向相减**（1425/1800 → 写 +375） | **ΔH = 断键能 − 成键能**，永远先断后成 | s21/42、s22/41、w22/41、w22/42、s25/43 **五次点名** |
| 2 | ΔH 为负时把 \|ΔH\| **减掉** | `bonds formed = bonds broken − ΔH`（ΔH 负 ⇒ **加** \|ΔH\|） | m22/42、m25/42 |
| 3 | 漏数键 | 在结构式上**逐键划掉**（考官推荐） | m22/42（漏 Cl−Cl）、w23/42（漏 2 个 O−H ⇒ 2280 而非 3200）、w22/43 |
| 4 | 忘了**除以键的个数** | 4 分的题必有这一步，单独占 1 分 | m22/42（÷2）、w23/42（÷4）、w25/41（÷2） |
| 5 | 不懂每一步在算什么（写 `680` 或 `680 + x`） | 每步**写下名字**（`energy needed to break bonds = ...`） | m25/42、w23/42 |
| 6 | 忘了用题目给的 ΔH | 题目给的 ΔH 一定进算式 | w21/42 |
| 7 | 方程式配平 ≠ 1 mol 时按 1 mol 算 | 系数乘进所有键能 | 2024 年 0620/22 Q15（2 mol ethyne） |
| 8 | 断键总和被误 ×2 | 只有**产物侧出现 2 个相同键**时才 ×2 | s22/41（864 而非 432） |
| 9 | 最终答案**不带符号** | 符号只出现在**最终 ΔH** 上 | s25/41（两种错法都点名） |
| 10 | 说「成键需要能量」 | **`bond making releases energy`** | s21/42、w21/42、w22/43 |
| 11 | 说「断键放能」 | **`bond breaking takes in energy`** | w22/43、w20/22 |
| 12 | 只提断键、或只提成键 | **两件事都要说** | w22/43 |
| 13 | endothermic 只说「吸热」不给理由 | 必须说「成键放能 < 断键吸能」或「overall energy change 带正号」 | w22/43 |
| 14 | **ΔH 定义只写 `energy change`** | 写 **`enthalpy change (of reaction)`** | m23、m25、s24、w25 **四次点名** |
| 15 | ΔH 定义只写 `enthalpy`（一个词） | 同上，`change` 不能省 | m25、w25 |
| 16 | ΔH 定义答成 `activation energy` | 同上 | m25 |
| 17 | **`enthalpy` 拼错** | e-n-t-h-a-l-p-y | w25/43 |
| 18 | 问「为什么该值说明放热」答「放热」 | 答 **`negative` / `minus sign`** | m25/42 |
| 19 | 逆反应 ΔH 漏 `+` 号，或把数字也改了 | 符号翻，**数字不变** | m25/42（`+105`） |
| 20 | 说 `exothermic side` | **`side` 不存在**；写 `the forward reaction is exothermic` | m20、s21、w24 |
| 21 | **Ea 定义漏 `colliding particles`** | 写全：`the minimum energy that colliding particles must have to react` | w23、w24 **两次点名** |
| 22 | Ea 定义写成 `minimum energy for a reaction to take place` | 同上（属 "simplified or incomplete"） | w24 |
| 23 | 把 Ea 与 overall energy change 搞混 | Ea = 反应物线→hump 顶；ΔH = 反应物线→产物线 | s22/22 |
| 24 | 以为**升温/降温/改浓度**会改变 Ea | **只有 catalyst 改变 Ea** | s23、m23、m25、w23 **四处点名** |
| 25 | `particles have energy greater than Ea`（少限定词） | 写 **`a greater proportion/percentage/fraction of particles`** | m23、s23 |
| 26 | **路径图产物线只写 `product`/`products`** | 必须写**完整化学式**（`SO2(g) + 4HF(g)`） | w21/42、w22/41、w25/41 |
| 27 | **Ea 画成双向箭头**，或没画到 hump 顶点，或只标顶点 | **单头向上箭头**，从反应物能级到**最高点** | w21/42、w22/41、w23/42、w25/41 |
| 28 | **ΔH 画成双向箭头 / 无箭头竖线 / 斜直线** | **单头向下箭头**，从反应物能级到产物能级 | w23/42、w25/41（`one arrow head ONLY` 见 s20/43） |
| 29 | ΔH 箭头**没覆盖全程** | 起点 = 反应物能级，终点 = 产物能级；先画水平辅助线 | w21/42 |
| 30 | 标签**不贴线** | 写在线**上或紧贴线下** | s22 |
| 31 | 读图题把向下箭头叫 `energy change` | 必须写 **`energy (change) of reaction`** | w22/42 |
| 32 | 问「图怎么说明放热」却背定义 / 没提图 | 答 **`energy of products is lower than energy of reactants`** | w22/42 |
| 33 | 把同一个点说两遍（`exothermic` + `because energy is lost`） | 必须补**独立的第二点**：产物能量低于反应物 | w20/41 |
| 34 | exo/endo 判断**反了** | 温度↑→产量↑ ⇒ **正反应 endothermic**；温度↑→产量↓ ⇒ **正反应 exothermic** | s24/41、s24/43、w25/43、s25/41 |
| 35 | 只写 `exothermic`，不写 `the forward reaction is exothermic` | 点明 **forward reaction** | w24/43 |
| 36 | 只说 `release of energy`，不提 `thermal`/`heat`/`surroundings` | 写 **`transfers thermal energy to the surroundings`** | m22/32、m24/32 |
| 37 | 手写 `exothermic` 像 `enothermic` | 把 **`x` 写清楚** | m20/62 |
| 38 | UV 的作用答成 `catalyst` / `to lower Ea` | 正解：**providing the activation energy** | m24/42 |
| 39 | **逆反应的 Ea 写成正反应 Ea 的负值**（`−220`） | **`Ea(逆) = Ea(正) + \|ΔH\|`** = 220 + 40 = **+260**；**Ea 永远是正数** | **m26/42 Q4(c)(ii)** |
| 40 | 逆反应的 ΔH 或 Ea **漏符号**（一问两空，各 1 分） | 两个空**都**带符号（`Include a sign with your answer.` 印了两次） | **m26/42 Q4(c)(ii)** |
| 41 | **求未知键能时算出负数键能** | 键能恒为正；负数 = M3 那步减错了对象 | **m26/42 Q4(d)** |
| 42 | 路径图箭头**画得太短或太长** | 箭头要覆盖「反应物能级 → 目标能级」整段（2026 允许轻微 ECF，明显错长度不给） | **m26/42 Q4(c)(i)**；s26 Guidance |
| 43 | **M1/M2 上写符号**（如 `−2930`） | 2026 明确 `I signs on M1 and M2` —— **符号只出现在最终 ΔH 上** | s26 Guidance |
| 44 | 键能最终答案**只有 1 位有效数字** | **`M4 must be to minimum of 2 SF`**（截断可以） | s26 Guidance |
| 45 | 求反应物/产物化学式时**写 `reactants`/`products`** | 写完整化学式（2026 明确 `I 'reactants' and 'products' as labels`） | s26 Guidance |
| 46 | 符号判定题答**「产物能量比反应物低」或「因为断键/成键」** | 那两句在**符号判定题**里被 `I`（ignore）；只答 `the enthalpy change is negative` | s26 Guidance |
| 47 | 可逆符号答成 `the reversible sign` 三个字 | 写 **`the arrow`** 或 **`the ⇌ symbol in the middle of the equation`** | **m26/42 Q4(a)**；s26 Guidance |

---

# 🧠 一页纸速记

## 必背英文串（5 条，考前默写）

```
① ΔH 的定义        enthalpy change (of reaction)
② Ea 的定义        the minimum energy that colliding particles must have to react
③ 为什么 ΔH 为负    (the value of ΔH is) negative
④ 键断 / 键生成     bond breaking takes in energy
                    bond making releases energy
                    the energy change of bond making is greater than bond breaking
⑤ 图怎么说明放热    energy of products is lower than energy of reactants
```

## 键能计算（三步 + 符号口诀）

```
ΔH = (energy needed to break bonds) − (energy released when bonds form)
             M1                              M2              → M3 = M1 − M2

★ 永远「先断后成」，绝不倒过来（五次 ER 点名）
★ 靠 ΔH 反推产物键能：bonds formed = bonds broken − ΔH
     ΔH 为负 ⇒ 【加】|ΔH|   （m22 / m25 两次点名；2026 官方原文 `A ECF for = M1 + 870`）
★ 4 分的题：最后一定要 ÷ 键的个数（单独 1 分；18 道题里 5 道是 4 分）
★ 符号只写在最终 ΔH 上；题目印 "include a sign" 就是提醒你一分别丢
     （2026 明确：M1/M2 上的符号会被 ignore）
★ 单位：M1/M2 写 kJ，最终写 kJ/mol
★ 求出来的【键能必须是正数】；至少 2 位有效数字（2026：`M4 must be to minimum of 2 SF`）
★ 漏键用「在结构式上逐键划掉」防（考官推荐）
★ 逆反应：ΔH 翻符号、**Ea = Ea(正) + |ΔH|**（2026 新题型）
```

## 路径图画图 checklist（八步）

```
① 反应物水平线（左）
② 线上写【完整化学式】—— 不写 "reactants"
③ exo → 产物线在下方；endo → 产物线在上方
④ 产物线上写【完整化学式】—— 不写 "product"/"products"
⑤ 画 hump（驼峰）
⑥ 反应物能级 → hump 最高点：单头向上箭头，标 Ea   ← 不能双向！
⑦ 从反应物能级画一条水平辅助线
⑧ 反应物能级 → 产物能级：单头向下箭头，标 ΔH     ← 不能双向！不能斜线！必须覆盖全程
```

## 常考反应与答案（复习时随手做一遍）

| 反应 | 断键 (M1) | 成键 (M2) | ΔH |
|---|---|---|---|
| N₂ + 3F₂ → 2NF₃ | 945+3×160 = **1425** | 6×300 = **1800** | **[−]375** |
| C₂H₆ + Cl₂ → C₂H₅Cl + HCl | 6×410+350+240 = **3050** | 5×410+350+340+430 = **3170** | **[−]120** |
| I₂ + Cl₂ → 2ICl | 150+242 = **392** | 2×218 = **436** | **[−]44** |
| Br₂ + Cl₂ → 2BrCl | 190+242 = **432** | 2×218 = **436** | **[−]4** |
| CO + Cl₂ → COCl₂（给 ΔH = [−]105） | 1075+240 = **1315** | **1420** | 求 C=O = **740** |
| CCl₄ + 2H₂O → CO₂ + 4HCl（给 ΔH = [−]130） | 4×340+4×460 = **3200** | 1610 + 4×H−Cl | 求 H−Cl = **430** |
| **3H₂ + CO₂ → CH₃OH + H₂O**（给 ΔH = [−]40）<br>H−H 440 / C=O 805 / O−H 460 / C−O 360 | 3×440+2×805 = **2930** | 2×460 = **920**（水） | 求 C−H = **410** |
| **NH₃ + 3F₂ → NF₃ + 3HF**（给 ΔH = [−]870）<br>N−H 390 / F−F 150 / N−F 270 | 3×390+3×150 = **1620** | **1620 + 870 = 2490** | 求 H−F = **560** |
| **H₂ + Cl₂ → 2HCl**（MCQ）<br>H−H 436 / Cl−Cl 242 / H−Cl 431 | 436+242 = **678** | 2×431 = **862** | **[−]184（exothermic）** |
| **N₂ + 3F₂ → 2NF₃**（MCQ，键能不同！）<br>N≡N 950 / F−F 150 / N−F 280 | 950+3×150 = **1400** | 6×280 = **1680** | **[−]280** |
| **2H₂O₂ → 2H₂O + O₂**（MCQ）<br>O−H 460 / O−O 150 / O=O 496 | 4×460+2×150 = **2140** | 4×460+496 = **2336** | **[−]196** |

## 高频「一句话」判分点

```
只写 energy change            → 0 分（要 enthalpy change (of reaction)）
只写 enthalpy                 → 0 分
Ea 少 colliding particles     → 丢 1 分
问「为什么放热」答「放热」      → 0 分（要 negative）
问「为什么放热」答「产物能量更低」→ 0 分（2026：这句在符号判定题里被 ignore）
产物线只写 product            → 0 分（要化学式）
ΔH 画双向箭头 / 无箭头竖线 / 斜线 → 0 分（2026 仍然严格）
Ea 画双向箭头                 → 2026 起接受（但照旧画单头最安全）
升温 → Ea 改变                → 0 分（只有 catalyst 改 Ea）
逆反应 Ea 写 −220             → 0 分（Ea 永远是正数；要 +260）
未知键能算出负数              → 0 分（键能恒为正）
M1/M2 带符号                  → 被 ignore（符号只写在最终 ΔH）
```

---

# 🔗 延伸资源

- **考纲原文**：`cambridge-igcse-chemistry-0620-syllabus-2026-2028.pdf` · **Section 5.1**（8 条：Core 1–3 + Supplement 4–8）
- **研究底稿**（含全部逐字引用与审计轨迹，正常复习不需要读）：
  - `_research/topic5-energetics.md` —— 本 Topic 的 MS / ER 原文挖掘（初版 16 道键能题全表、路径图模板、陷阱清单）
  - **2026 新增语料**（本笔记第二轮并入，未写进 `_research/` 底稿，引用直接来自原文）：`0620_m26_er.txt`、`0620_m26_ms_42.txt`、`0620_s26_ms_41/42/43.txt`（含 `Guidance` 栏）、`0620_m26/s26_qp_2x`（2026 MCQ 题干）
  - `_research/syllabus-topics-4-5-6.md` —— 考纲条目权威清单
  - `_research/frequency-audit.md` —— 考频分类器审计（本笔记所有「真实权重」数字的来源）
  - `_research/reference-notes-comparison.md` —— 与外部参考笔记的批判比对（超纲项清单的来源）
- **配套文件**：
  - [Unit 4 — Electrochemistry](Unit 4 - Electrochemistry.md)
  - [Unit 6 — Chemical reactions](Unit 6 - Chemical reactions.md)

---

**上一单元**：[Unit 4 — Electrochemistry](Unit 4 - Electrochemistry.md) | **下一单元**：[Unit 6 — Chemical reactions](Unit 6 - Chemical reactions.md) | **索引**：[README](README.md)

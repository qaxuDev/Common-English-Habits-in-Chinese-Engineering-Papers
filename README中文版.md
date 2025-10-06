# 📝 中国工科研究生英文论文中最常见的写作习惯（200+ 篇论文分析）

> 基于 **200 多篇** 中国工科研究生撰写的英文技术论文分析  
> 原作者：**Felicia Brittman** | [原文链接](http://staff.ustc.edu.cn/~jpq/writing/The%20Most%20Common%20Habits.pdf)
> 📘 **中文社区解读**: [Detailed summary & notes (in Chinese)](https://www.cnblogs.com/luohenyueji/p/16990846.html)


本指南总结了中国学生在撰写英文技术论文时**最常出现的语言、语法与格式问题**，旨在帮助作者**自主修改**，减少对母语编辑的依赖，提高论文被国际期刊接受的概率。

---

## 🎯 背景与目的

- 中国多数高校要求硕博生在国际期刊发表至少一篇英文论文。
- 但学生常因“英语差”被拒稿，原因包括：
  - 英语学习偏重听说，缺乏**技术写作训练**；
  - 未在英语国家生活，缺乏语感；
  - 技术写作本身有特殊规范，连母语者也需专门学习。
- 依赖母语编辑成本高，且若编辑**不懂专业**，无法修正术语错误或确保技术含义清晰。

本报告提供**高频错误清单 + 正误对比 + 修改建议**，帮助作者“学会钓鱼”，而非“只给鱼”。

---

## 📌 第一部分：十大关键问题（需优先修正）

### 1. **冠词（a, an, the）缺失或误用**
- **原因**：中文无冠词系统。
- **规则**：单数可数名词前**必须**有冠词或限定词（如 my, this, one）。
- **示例**：
  - ❌ `on surface of blades`  
  - ✅ `on **the** surface of **the** blades`

> 💡 可参考文末【冠词使用流程图】辅助判断。

---

### 2. **句子过长**
- **问题**：受中文影响，将多个想法塞进一句（常超 60 词），逻辑混乱。
- **建议**：
  - 每句聚焦 **1–2 个核心思想**；
  - 参数罗列改用**项目符号或表格**。
- **示例**：
  - ❌ 一句列出齿轮传动等级、间隙、非线性模型等。
  - ✅ 拆分为：
    ```markdown
    - 齿轮传动等级：7 级  
    - 齿轮间隙：0.00012 弧度  
    - 初始间隙值：0
    ```

---

### 3. **主语后置：先写目的/地点/原因**
- **问题**：重点不突出，显得迂回。
- **原则**：**主语/主句放句首**，状语后置。
- **示例**：
  - ❌ `For automobile interiors, this paper studies...`  
  - ✅ `This paper studies... for automobile interiors.`

---

### 4. **习惯以时间/条件状语开头**
- **避免**：`When...`, `If...`, `Based on...` 开头。
- **建议**：先说**结果或图表**。
- **示例**：
  - ❌ `When U is the control parameter, Fig. 8 shows...`  
  - ✅ `Figure 8 shows... when U is the control parameter.`

---

### 5. **“which/that” 指代不清**
- **问题**：读者无法判断 `which` 修饰哪个名词。
- **示例**：
  - ❌ `The bridge has the largest force, which was built in 1978.`（是桥还是力？）
  - ✅ `The bridge, which was built in 1978, has the largest jacking force.`

---

### 6. **“respectively” 误用**
- **正确用法**：仅当**两个有序列表需一一对应**时使用，且放**句末**。
- **常见错误**：
  - ❌ `Equations 2–6 can be respectively linearized...`  
  - ✅ `Equations 2–6 can be linearized..., respectively.`
  - ❌ `Measured using two thermocouples respectively.`（无对应列表）  
  - ✅ `Measured using two thermocouples.`

> ⚠️ 若顺序已明确或无关紧要，**不要用** `respectively`。

---

### 7. **过度使用 “In this paper/study”**
- **建议**：全文**不超过 3 次**。
- **使用场景**：
  - 引言/结论中强调本文工作；
  - 正文中区分“他人工作”与“本文工作”。
- **注意区分**：
  - `In this **study**` → 指**研究行为**；
  - `This **paper** presents...` → 指**论文本身**。

---

### 8. **数字与公式格式错误**
- **句首禁用阿拉伯数字**：
  - ❌ `12 parameters were selected.`  
  - ✅ `Twelve parameters were selected.`
- **一般性描述用英文数字**：
  - ❌ `All 3 studies...`  
  - ✅ `All three studies...`
- **避免在句中插入公式**：
  - ❌ `If SOC > SOClo...`  
  - ✅ `If the SOC is greater than SOClo...`

---

### 9. **格式问题**
| 问题 | 错误 | 正确 |
|------|------|--------|
| **段落** | 无缩进或单句成段 | 缩进或空一行 |
| **图表引用** | `Fig.6`, `Figure6` | `Fig. 6` 或 `Figure 6` |
| **变量** | `C = 5` | *C* = 5（斜体） |
| **大小写** | `The mark...`（句中） | `the mark...` |

> 🔸 全文统一缩写格式（如全用 `Fig.` 或全用 `Figure`）。

---

### 10. **“such as” 与 “etc.” 误用**
- **禁止同时使用**：`such as A, B, and etc.` → ❌
- **`such as` = 非穷尽列举**；**完整列举用冒号**：
  - ❌ `Three characteristics such as X, Y, Z.`  
  - ✅ `Three characteristics: X, Y, and Z.`

---

## 📋 第二部分：其他常见小问题

| 问题 | 避免 | 建议 |
|------|------|------|
| **不可数名词** | `equipments`, `literatures` | `equipment`, `literature` |
| **冗余表达** | `research work`, `simulation results` | `research`, `results` |
| **单复数错误** | `different node` | `different **nodes**` |
| **句首禁用** | `8 samples...`, `Fig. 3 shows...` | `Eight samples...`, `Figure 3 shows...` |
| **中式表达** | `by this way` | `using this method` |
| **句首疑问** | `How to optimize...` | `Determining how to optimize...` |
| **动词错误** | `results are showed as Fig. 2` | `results are **shown** in Fig. 2` |
| **主观语气** | `Obviously, this is novel.` | `This is novel.` |
| **地域词汇** | `in our country`, `abroad` | `in China`, `overseas` |
| **啰嗦连接词** | `that is to say`, `namely` | 直接写清楚 |
| **句尾“too”** | `..., too.` | 删除（正式写作不推荐） |

---

## 📎 附录：冠词使用流程图（简化版）

判断是否使用 `a` / `an` / `the` / **不加**：

```text
是名词吗？
 └─ 可数吗？
     ├─ 单数？
     │   ├─ 特指？ → 用 "the"
     │   └─ 泛指？
     │       ├─ 元音开头？ → "an"
     │       └─ 辅音开头？ → "a"
     └─ 复数？
         ├─ 特指？ → "the"
         └─ 泛指？ → 通常不加冠词（可用 some, these 等限定词）

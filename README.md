# Engineering Paper Reader

面向工程类中英文论文的自适应精读 Skill。给定一篇论文的 PDF、标题、DOI 或链接后，先识别文献功能、研究方法、发表载体和语言，再按需要分析公式、图表、实验、仿真、算法及工程适用性。

## 能做什么

- 区分综述、原创研究、技术报告，并识别实验、理论、仿真、算法或工程案例的组合。
- 用简洁主线解释“问题 → 方法 → 机制 → 证据 → 结论”，按需展开公式或完整流程。
- 核查性能指标的单位、分母和工况，区分作者主张、原文证据、复算与推论。
- 针对中文论文核对术语、双语摘要、公式排版和数值提取。
- 提炼对当前研究可借鉴的设计，并指出需要补做的验证。

## 使用

将本仓库的 `SKILL.md` 与 `references/` 一起放入 Codex 的 skills 目录，保持目录结构。然后提供论文并请求：

> 使用 engineering-paper-reader 精读这篇工程论文。先给一句核心判断和简洁主线图，再解释关键方法、结果、证据边界与对我课题的启发。

技能只依据实际可访问的材料分析。它不自动完成全领域文献检索、全文翻译或实验复现；缺失的内容会标为未确认。

## 结构

- [SKILL.md](SKILL.md)：触发边界、分类、共有流程与输出要求。
- [references/engineering.md](references/engineering.md)：实验、仿真、算法和工程设计的分析要点。
- [references/review.md](references/review.md)：各类综述的证据评价。
- [references/chinese.md](references/chinese.md)：中文与双语处理。
- [references/evidence-and-metrics.md](references/evidence-and-metrics.md)：指标口径与证据边界。

版本：1.0.0。

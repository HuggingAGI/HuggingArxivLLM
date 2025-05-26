# 推理模型偏执：诊断推理模型中的指令覆盖问题

发布时间：2025年05月22日

`LLM理论` `数学教育` `教育测试`

> Reasoning Model is Stubborn: Diagnosing Instruction Overriding in Reasoning Models

# 摘要

> 大型语言模型在处理长篇复杂推理任务时表现出色，但存在明显的依赖性问题——我们将其称为	extit{推理刚性}。即使用户明确指示，这些模型也常常忽视条件，固守旧有的推理路径，从而得出错误结论。这一问题在数学和逻辑谜题等需要严格遵循限制条件的领域尤为突出。为了深入研究这一尚未被充分探索的推理刚性现象，我们推出了一个专家精选的诊断数据集——\dataset{}。该数据集包含对现有数学基准AIME和MATH500的特别修改版本，以及经过重新设计的知名谜题，这些谜题特意要求偏离常规推理策略。通过这一数据集，我们发现了模型在使用根深蒂固的推理模式时出现的重复性污染模式，并将其分类为三种独特类型：(i) 解释过载，(ii) 输入不信任，和 (iii) 部分指令关注。每种类型都会导致模型忽略或扭曲提供的指令。我们公开发布了这一诊断数据集，以支持未来关于缓解语言模型推理刚性的研究。

> Large language models have demonstrated remarkable proficiency in long and complex reasoning tasks. However, they frequently exhibit a problematic reliance on familiar reasoning patterns, a phenomenon we term \textit{reasoning rigidity}. Despite explicit instructions from users, these models often override clearly stated conditions and default to habitual reasoning trajectories, leading to incorrect conclusions. This behavior presents significant challenges, particularly in domains such as mathematics and logic puzzle, where precise adherence to specified constraints is critical. To systematically investigate reasoning rigidity, a behavior largely unexplored in prior work, we introduce a expert-curated diagnostic set, \dataset{}. Our dataset includes specially modified variants of existing mathematical benchmarks, namely AIME and MATH500, as well as well-known puzzles deliberately redesigned to require deviation from familiar reasoning strategies. Using this dataset, we identify recurring contamination patterns that occur when models default to ingrained reasoning. Specifically, we categorize this contamination into three distinctive modes: (i) Interpretation Overload, (ii) Input Distrust, and (iii) Partial Instruction Attention, each causing models to ignore or distort provided instructions. We publicly release our diagnostic set to facilitate future research on mitigating reasoning rigidity in language models.

[Arxiv](https://arxiv.org/abs/2505.17225)
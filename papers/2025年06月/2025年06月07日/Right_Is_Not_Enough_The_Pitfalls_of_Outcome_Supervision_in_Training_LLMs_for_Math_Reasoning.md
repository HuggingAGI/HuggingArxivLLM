# 正确答案不够：训练数学推理LLMs中结果导向监督的误区

发布时间：2025年06月07日

`LLM应用` `评估方法`

> Right Is Not Enough: The Pitfalls of Outcome Supervision in Training LLMs for Math Reasoning

# 摘要

> 基于结果奖励的大语言模型（LLMs）在数学解题方面表现优异，但其成功背后隐藏着一个关键问题：模型往往通过不合理的推理过程得出正确答案，这表明存在奖励滥用现象。我们推出MathOlympiadEval，一个标注精细的新数据集，揭示了LLMs在答案正确性与推理过程正确性之间的显著差距。现有如将LLM作为裁判的自动化方法难以有效识别这些推理漏洞。为解决这一问题，我们提出ParaStepVerifier，一种全新的分步验证方法，能够精准识别推理过程中的错误。实证结果表明，ParaStepVerifier在识别有缺陷解题方案的准确性上显著优于基线方法，尤其在复杂多步问题中表现突出。这为评估和训练具备真正数学推理能力的LLMs提供了更稳健的路径。


> Outcome-rewarded Large Language Models (LLMs) have demonstrated remarkable success in mathematical problem-solving. However, this success often masks a critical issue: models frequently achieve correct answers through fundamentally unsound reasoning processes, a phenomenon indicative of reward hacking. We introduce MathOlympiadEval, a new dataset with fine-grained annotations, which reveals a significant gap between LLMs' answer correctness and their low process correctness. Existing automated methods like LLM-as-a-judge struggle to reliably detect these reasoning flaws. To address this, we propose ParaStepVerifier, a novel methodology for meticulous, step-by-step verification of mathematical solutions. ParaStepVerifier identifies incorrect reasoning steps. Empirical results demonstrate that ParaStepVerifier substantially improves the accuracy of identifying flawed solutions compared to baselines, especially for complex, multi-step problems. This offers a more robust path towards evaluating and training LLMs with genuine mathematical reasoning.

[Arxiv](https://arxiv.org/abs/2506.06877)
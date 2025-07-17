# 基于 LLM 的协作式手术机器人自然语言指令歧义检测

发布时间：2025年07月15日

`LLM应用` `人工智能`

> LLM-based ambiguity detection in natural language instructions for collaborative surgical robots

# 摘要

> 自然语言指令的模糊性在手术等关键领域对人机交互安全构成重大风险。为应对这一挑战，我们提出了一种专门针对协作手术场景的大型语言模型（LLMs）模糊性检测框架。我们的方法采用了一组集成的LLM评估器，每个评估器配置了不同的提示技术，用于识别语言、语境、程序和关键模糊性。其中还包括一个链式思维评估器，系统性地分析指令结构以发现潜在问题。通过符合性预测对各个评估器的评估结果进行综合，该方法基于与标记校准数据集的比较生成非符合性分数。在对Llama 3.2 11B和Gemma 3 12B的评估中，我们发现其在区分模糊与非模糊手术指令的分类准确率超过60%。我们的方法通过提供一种机制，在机器人执行动作前识别潜在模糊指令，从而显著提升了手术中人机协作的安全性和可靠性。

> Ambiguity in natural language instructions poses significant risks in safety-critical human-robot interaction, particularly in domains such as surgery. To address this, we propose a framework that uses Large Language Models (LLMs) for ambiguity detection specifically designed for collaborative surgical scenarios. Our method employs an ensemble of LLM evaluators, each configured with distinct prompting techniques to identify linguistic, contextual, procedural, and critical ambiguities. A chain-of-thought evaluator is included to systematically analyze instruction structure for potential issues. Individual evaluator assessments are synthesized through conformal prediction, which yields non-conformity scores based on comparison to a labeled calibration dataset. Evaluating Llama 3.2 11B and Gemma 3 12B, we observed classification accuracy exceeding 60% in differentiating ambiguous from unambiguous surgical instructions. Our approach improves the safety and reliability of human-robot collaboration in surgery by offering a mechanism to identify potentially ambiguous instructions before robot action.

[Arxiv](https://arxiv.org/abs/2507.11525)
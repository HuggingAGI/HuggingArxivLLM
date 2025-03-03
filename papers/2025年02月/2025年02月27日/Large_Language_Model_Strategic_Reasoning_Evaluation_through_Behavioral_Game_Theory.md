# 通过行为博弈论对大型语言模型进行战略性推理评估

发布时间：2025年02月27日

`LLM应用` `战略决策` `博弈论评估`

> Large Language Model Strategic Reasoning Evaluation through Behavioral Game Theory

# 摘要

> 战略决策涉及互动推理，智能体根据他人的行为调整自己的选择。然而，现有对大型语言模型（LLMs）的评估多集中在纳什均衡（NE）的近似，却忽略了驱动战略选择的机制。为填补这一空白，我们引入了一个基于行为博弈论的评估框架，将推理能力与情境影响区分开来。测试了22个先进的LLMs，发现GPT-o3-mini、GPT-o1和DeepSeek-R1在大多数游戏中表现突出，但模型规模并非唯一决定性能的因素。在提示增强方面，Chain-of-Thought（CoT）提示并非对所有模型都有效，它只对某些级别的模型提高了战略推理能力，而在其他地方则效果有限。此外，我们还研究了编码的人口统计特征对模型的影响，发现某些分配会影响决策模式。例如，GPT-4o在女性特质下的战略推理能力比男性更强，而Gemma为异性恋身份分配了更高的推理水平，与其他性取向相比，这表明了固有的偏见。这些发现强调了制定伦理标准和情境对齐的必要性，以平衡推理提升与公平性。

> Strategic decision-making involves interactive reasoning where agents adapt their choices in response to others, yet existing evaluations of large language models (LLMs) often emphasize Nash Equilibrium (NE) approximation, overlooking the mechanisms driving their strategic choices. To bridge this gap, we introduce an evaluation framework grounded in behavioral game theory, disentangling reasoning capability from contextual effects. Testing 22 state-of-the-art LLMs, we find that GPT-o3-mini, GPT-o1, and DeepSeek-R1 dominate most games yet also demonstrate that the model scale alone does not determine performance. In terms of prompting enhancement, Chain-of-Thought (CoT) prompting is not universally effective, as it increases strategic reasoning only for models at certain levels while providing limited gains elsewhere. Additionally, we investigate the impact of encoded demographic features on the models, observing that certain assignments impact the decision-making pattern. For instance, GPT-4o shows stronger strategic reasoning with female traits than males, while Gemma assigns higher reasoning levels to heterosexual identities compared to other sexual orientations, indicating inherent biases. These findings underscore the need for ethical standards and contextual alignment to balance improved reasoning with fairness.

[Arxiv](https://arxiv.org/abs/2502.20432)
# 缓解性别偏见：培养 LLM 中的探索性思维

发布时间：2025年05月22日

`LLM理论` `伦理学` `社会学`

> Mitigating Gender Bias via Fostering Exploratory Thinking in LLMs

# 摘要

> 大型语言模型（LLMs）常常表现出性别偏见，在不同情境下对男性和女性主体进行不平等对待。为了解决这一问题，我们提出了一种全新的数据生成框架，旨在培养LLMs的探索性思维。我们设计了一种方法，引导模型生成结构相同、道德模糊的情节对，分别以男性和女性为主角，然后提取并比较模型的道德判断。当出现不一致时，模型会被引导生成平衡且性别中立的判断。这些故事-判断对通过直接偏好优化（DPO）用于微调或优化模型。实验结果表明，我们的方法显著降低了性别偏见，同时保留甚至提升了模型的整体能力。我们将发布代码和生成的数据。

> Large Language Models (LLMs) often exhibit gender bias, resulting in unequal treatment of male and female subjects across different contexts. To address this issue, we propose a novel data generation framework that fosters exploratory thinking in LLMs. Our approach prompts models to generate story pairs featuring male and female protagonists in structurally identical, morally ambiguous scenarios, then elicits and compares their moral judgments. When inconsistencies arise, the model is guided to produce balanced, gender-neutral judgments. These story-judgment pairs are used to fine-tune or optimize the models via Direct Preference Optimization (DPO). Experimental results show that our method significantly reduces gender bias while preserving or even enhancing general model capabilities. We will release the code and generated data.

[Arxiv](https://arxiv.org/abs/2505.17217)
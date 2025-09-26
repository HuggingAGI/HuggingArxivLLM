# 让AI解释扎根于经验：面向临床决策支持的反思性认知架构

发布时间：2025年09月25日

`LLM应用` `医疗健康`

> Grounding AI Explanations in Experience: A Reflective Cognitive Architecture for Clinical Decision Support

# 摘要

> 在现代医疗领域，精准的疾病预测需兼顾双重目标：既要保证预测的高准确性，又要提供透明且具有临床价值的解释。然而现有基于机器学习或大型语言模型（LLM）的方法，却常陷入“鱼与熊掌不可兼得”的困境——部分模型虽能输出精准却晦涩的统计结果，另一些则生成流畅却缺乏数据支撑的描述，这两种情况都会同时削弱解释的可信度与预测的准确性。问题的根源在于这些模型与数据的交互停留在表面，无法像人类专家那样形成深入且细致的认知。

我们提出，高准确性与高质量解释并非割裂的目标，而是模型对数据形成深度、直接认知后自然产生的协同效应。为此，我们构建了反思性认知架构（RCA）——一种能协调多个LLM从直接经验中学习的全新框架。RCA的核心在于两大机制：一是迭代规则优化，能从预测错误中不断完善自身逻辑；二是分布感知规则检查，将推理牢牢锚定在数据集的全局统计特性上。通过以预测准确性为反馈信号，RCA驱动模型对数据的理解不断深化，进而构建出稳健的数据内部表征。

我们在1个私有数据集和2个公共数据集上，将RCA与22个基线模型展开对比实验。结果显示，RCA不仅达到了当前最优的准确性和稳健性（相对基线模型提升幅度最高达40%），更重要的是，它凭借这种深度认知，能生成清晰、逻辑严谨、有据可依且客观平衡的解释。这一特性凸显了RCA在构建真正可信的临床决策支持系统上的巨大潜力。代码已开源，地址为\https://github.com/ssssszj/RCA。

> Effective disease prediction in modern healthcare demands the twin goals of high accuracy and transparent, clinically meaningful explanations. Existing machine learning and large language model (LLM) based approaches often struggle to balance these goals. Many models yield accurate but unclear statistical outputs, while others generate fluent but statistically unsupported narratives, often undermining both the validity of the explanation and the predictive accuracy itself. This shortcoming comes from a shallow interaction with the data, preventing the development of a deep, detailed understanding similar to a human expert's. We argue that high accuracy and high-quality explanations are not separate objectives but are mutually reinforcing outcomes of a model that develops a deep, direct understanding of the data. To achieve this, we propose the Reflective Cognitive Architecture (RCA), a novel framework that coordinates multiple LLMs to learn from direct experience. RCA features an iterative rule refinement mechanism that improves its logic from prediction errors and a distribution-aware rules check mechanism that bases its reasoning in the dataset's global statistics. By using predictive accuracy as a signal to drive deeper comprehension, RCA builds a strong internal model of the data. We evaluated RCA on one private and two public datasets against 22 baselines. The results demonstrate that RCA not only achieves state-of-the-art accuracy and robustness with a relative improvement of up to 40\% over the baseline but, more importantly, leverages this deep understanding to excel in generating explanations that are clear, logical, evidence-based, and balanced, highlighting its potential for creating genuinely trustworthy clinical decision support systems. The code is available at \https://github.com/ssssszj/RCA.

[Arxiv](https://arxiv.org/abs/2509.21266)
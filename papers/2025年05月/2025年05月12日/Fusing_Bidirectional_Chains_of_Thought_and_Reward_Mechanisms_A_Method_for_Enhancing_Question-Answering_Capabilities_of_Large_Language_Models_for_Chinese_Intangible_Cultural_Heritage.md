# 融合双向思维链与奖励机制：提升大型语言模型中文非物质文化遗产问答能力的方法

发布时间：2025年05月12日

`LLM应用` `非物质文化遗产` `问答系统`

> Fusing Bidirectional Chains of Thought and Reward Mechanisms A Method for Enhancing Question-Answering Capabilities of Large Language Models for Chinese Intangible Cultural Heritage

# 摘要

> 大型语言模型的快速发展为领域特定模型的开发提供了重要支持。然而，使用非物质文化遗产数据进行微调时，模型不可避免地会面临偏差、知识继承错误和灾难性遗忘等挑战。为此，我们提出了一种结合双向思维链和奖励机制的新型训练方法，该方法基于专门针对非物质文化遗产领域的大型语言模型ICH-Qwen构建。

我们的方法不仅让模型能够进行正向推理，还通过反向提问和反向推理激活模型的潜在知识，从而提高生成答案的准确性。此外，我们在训练过程中引入了一种奖励机制，通过结构和内容的不同加权方案评估来优化模型的决策过程，从而提升模型输出的质量。

实验结果表明，我们的方法在问答任务中的准确率、Bleu-4和Rouge-L分数方面优于0-shot、逐步推理、知识蒸馏和问题增强方法。消融实验进一步证明了双向思维链与奖励机制相结合的有效性。此外，我们在金融、Wikidata和StrategyQA等领域的实验也表明，该方法具有良好的泛化能力，为未来跨领域应用的模型训练提供了一种有价值的思路。

> The rapid development of large language models (LLMs) has provided significant support and opportunities for the advancement of domain-specific LLMs. However, fine-tuning these large models using Intangible Cultural Heritage (ICH) data inevitably faces challenges such as bias, incorrect knowledge inheritance, and catastrophic forgetting. To address these issues, we propose a novel training method that integrates a bidirectional chains of thought and a reward mechanism. This method is built upon ICH-Qwen, a large language model specifically designed for the field of intangible cultural heritage. The proposed method enables the model to not only perform forward reasoning but also enhances the accuracy of the generated answers by utilizing reverse questioning and reverse reasoning to activate the model's latent knowledge. Additionally, a reward mechanism is introduced during training to optimize the decision-making process. This mechanism improves the quality of the model's outputs through structural and content evaluations with different weighting schemes. We conduct comparative experiments on ICH-Qwen, with results demonstrating that our method outperforms 0-shot, step-by-step reasoning, knowledge distillation, and question augmentation methods in terms of accuracy, Bleu-4, and Rouge-L scores on the question-answering task. Furthermore, the paper highlights the effectiveness of combining the bidirectional chains of thought and reward mechanism through ablation experiments. In addition, a series of generalizability experiments are conducted, with results showing that the proposed method yields improvements on various domain-specific datasets and advanced models in areas such as Finance, Wikidata, and StrategyQA. This demonstrates that the method is adaptable to multiple domains and provides a valuable approach for model training in future applications across diverse fields.

[Arxiv](https://arxiv.org/abs/2505.08167)
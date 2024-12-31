# 用于常识性陈述估计的反事实样本构建与训练

发布时间：2024年12月29日

`LLM应用` `语言模型` `常识推理`

> Counterfactual Samples Constructing and Training for Commonsense Statements Estimation

# 摘要

> 合理性估计（PE）在让语言模型客观理解现实世界方面发挥着关键作用。尽管大型语言模型（LLMs）在 PE 任务中展现出出色能力，但因常识知识的复杂，有时会出现细微的常识性错误。它们缺少理想 PE 模型的两个重要特质：a）语言可解释性，即依靠关键词段做决策；b）常识敏感性，能察觉常识中的细微语言变化。为应对这些问题，我们提出一种全新的模型无关方法，名为常识反事实样本生成（CCSG）。通过用 CCSG 训练 PE 模型，促使其关注关键单词，进而增强语言可解释性和常识敏感性。具体来说，CCSG 通过有策略地替换关键词以及在句子中引入低级别随机失活来生成反事实样本。接着将这些反事实样本纳入句子级别的对比训练框架，进一步强化模型的学习过程。在九个不同数据集上的实验结果显示，CCSG 在解决常识推理难题方面成效显著，我们的 CCSG 方法比最先进的方法提升了 3.07%。

> Plausibility Estimation (PE) plays a crucial role for enabling language models to objectively comprehend the real world. While large language models (LLMs) demonstrate remarkable capabilities in PE tasks but sometimes produce trivial commonsense errors due to the complexity of commonsense knowledge. They lack two key traits of an ideal PE model: a) Language-explainable: relying on critical word segments for decisions, and b) Commonsense-sensitive: detecting subtle linguistic variations in commonsense. To address these issues, we propose a novel model-agnostic method, referred to as Commonsense Counterfactual Samples Generating (CCSG). By training PE models with CCSG, we encourage them to focus on critical words, thereby enhancing both their language-explainable and commonsense-sensitive capabilities. Specifically, CCSG generates counterfactual samples by strategically replacing key words and introducing low-level dropout within sentences. These counterfactual samples are then incorporated into a sentence-level contrastive training framework to further enhance the model's learning process. Experimental results across nine diverse datasets demonstrate the effectiveness of CCSG in addressing commonsense reasoning challenges, with our CCSG method showing 3.07% improvement against the SOTA methods.

[Arxiv](https://arxiv.org/abs/2412.20563)
# 利用检索头优化提升大型语言模型的上下文忠实度

发布时间：2025年01月23日

`RAG

理由：该论文主要研究的是在长形式问答（LFQA）场景中，如何通过检索增强的大型语言模型（LLMs）来确保上下文忠实性。论文提出了RHIO框架，该框架通过选择性屏蔽检索头来增强不忠实样本，并将这些样本纳入联合训练，以提高模型的忠实性。此外，论文还推出了GroundBench基准来评估上下文忠实性。这些内容都与检索增强生成（RAG）密切相关，因此将其分类为RAG。` `信息检索` `问答系统`

> Improving Contextual Faithfulness of Large Language Models via Retrieval Heads-Induced Optimization

# 摘要

> 在长形式问答（LFQA）场景中，确保检索增强的大型语言模型（LLMs）的上下文忠实性对于构建可信的信息检索系统至关重要。本研究揭示了LFQA忠实性与检索头（负责检索上下文信息的注意力头）之间的显著关联。基于这一发现，我们提出了RHIO框架，旨在教导LLMs明确区分忠实与不忠实的生成。RHIO通过选择性屏蔽检索头来增强不忠实样本，模拟模型内在错误，并将这些样本纳入联合训练，使模型能够根据控制令牌区分不忠实与忠实输出。此外，控制令牌还用于自我诱导对比输出，通过对比解码放大差异。为评估上下文忠实性，我们还推出了GroundBench，一个基于五个现有LFQA数据集构建的综合基准。实验结果表明，RHIO显著提升了忠实性，甚至超越了GPT-4o。

> Ensuring contextual faithfulness in retrieval-augmented large language models (LLMs) is crucial for building trustworthy information-seeking systems, particularly in long-form question-answering (LFQA) scenarios. In this work, we identify a salient correlation between LFQA faithfulness and retrieval heads, a set of attention heads responsible for retrieving contextual information. Leveraging this insight, we propose RHIO, a framework designed to teach LLMs to explicitly discriminate between faithful and unfaithful generations. RHIO first augments unfaithful samples that simulate realistic model-intrinsic errors by selectively masking retrieval heads. Then, these samples are incorporated into joint training, enabling the model to distinguish unfaithful outputs from faithful ones conditioned on control tokens. Furthermore, these control tokens are leveraged to self-induce contrastive outputs, amplifying their difference through contrastive decoding. Additionally, to facilitate the evaluation of contextual faithfulness, we also introduce GroundBench, a comprehensive benchmark compiled from five existing LFQA datasets. Extensive experimental results on GroundBench demonstrate that RHIO significantly improves faithfulness, even outperforming GPT-4o.

[Arxiv](https://arxiv.org/abs/2501.13573)
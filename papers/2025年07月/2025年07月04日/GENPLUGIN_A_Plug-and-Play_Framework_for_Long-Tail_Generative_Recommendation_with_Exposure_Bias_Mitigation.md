# # GENPLUGIN：支持缓解曝光偏见的长尾生成推荐任务的即插即用框架

发布时间：2025年07月04日

`LLM应用` `推荐系统` `电子商务`

> GENPLUGIN: A Plug-and-Play Framework for Long-Tail Generative Recommendation with Exposure Bias Mitigation

# 摘要

> 生成推荐（GenRec）凭借其LLM集成能力、降低的嵌入成本以及无需对每个候选进行评分的特点，吸引了广泛关注。然而，尽管其性能令人瞩目，本研究揭示了两个关键局限性：生成曝光偏差和长尾项目泛化能力不足，而这些在先前的GenRec研究中被忽视。为了解决这些问题，我们提出了GENPLUGIN，一个插件式框架，采用双编码器与共享解码器架构。在预训练阶段，GENPLUGIN通过对比学习对齐语言与ID视图，使项目表示在两个互补视图中达到和谐统一。此外，GENPLUGIN采用了一种创新的训练策略，即以概率方式将地面真实项目ID令牌替换为语言-语义编码器的预测，从而有效缓解了曝光偏差问题。为了提升长尾生成推荐的效果，我们引入了一种基于检索的数据增强机制。该机制对GENPLUGIN的解码器进行微调，使其能够根据上下文或协同信息利用相关用户，从而在长尾推荐场景中增强项目ID令牌的生成能力。我们将GENPLUGIN集成到多个代表性的GenRec模型中，通过广泛的实验验证，GENPLUGIN在生成项目ID时显著缓解了生成曝光偏差，同时大幅提升了长尾项目推荐的质量。

> Generative recommendation (GenRec) offers LLM integration, reduced embedding costs, and eliminates per-candidate scoring, attracting great attention. Despite its promising performance, this study reveals that it suffers from generation exposure bias and poor long-tail item generalization, two critical limitations overlooked by prior works on GenRec. To address these, we propose GENPLUGIN, a plug-and-play framework featuring a dual-encoder, shared-decoder architecture. During pre-training, it aligns language and ID views via contrastive learning, harmonizing item representations across two complementary views. Besides, GENPLUGIN uses a novel training strategy that probabilistically substitutes ground-truth item ID tokens with predictions from the language-semantics encoder, alleviating exposure bias. To improve long-tail generative recommendation, we propose a retrieval-based data augmentation mechanism. It fine-tunes the decoder of GENPLUGIN to endow GENPLUGIN with the ability to use relevant users w.r.t. contexts or collaborative information to augment the generation of item ID tokens in long-tail recommendation scenarios. We have plugged GENPLUGIN into several representative GenRec models and the extensive experiments demonstrate that GENPLUGIN can notably mitigate generation exposure bias during item ID generation while significantly improving the quality of long-tail item recommendation.

[Arxiv](https://arxiv.org/abs/2507.03568)
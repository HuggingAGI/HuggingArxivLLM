# 教育领域中的一种创新方法：可扩展且自动化的主题控制问题生成

发布时间：2025年01月09日

`LLM应用

**理由：**
这篇论文主要讨论了一种基于预训练模型（T5-small）的自动问题生成方法，并针对教育领域进行了优化。虽然论文中提到了预训练模型的使用，但其核心关注点是如何利用这些模型来生成教育相关的问题，并提升生成问题的主题相关性和有效性。这属于将大型语言模型（LLM）应用于特定领域（教育）的实际应用场景，因此归类为LLM应用。` `问题生成`

> A Novel Approach to Scalable and Automatic Topic-Controlled Question Generation in Education

# 摘要

> 自动问题生成（QG）模型的发展有望通过减轻教师创建教育内容的负担，显著提升教育实践。本文提出了一种新颖的教育问题生成方法，能够精准控制问题的主题焦点。我们提出的主题控制问题生成（T-CQG）方法，显著提升了生成内容在教育应用中的相关性和有效性。该方法基于预训练的T5-small模型进行微调，并采用专为教育需求设计的数据集。研究还深入探讨了预训练策略、量化及数据增强对模型性能的影响。我们特别解决了生成与段落级上下文语义对齐的问题，从而提高了生成问题的主题针对性。此外，我们引入并探索了新的评估方法，用于衡量生成问题的主题相关性。通过严格的离线和人工评估验证，结果表明，所提出的模型能够有效生成高质量、主题集中的问题。这些模型有望通过作为定制问题生成器，减少教师工作量并支持个性化辅导系统。由于其参数规模较小，这些模型不仅提升了处理特定教育主题的能力，还提供了一种可扩展的解决方案，降低了基础设施成本。这种可扩展性使其能够在教育领域广泛应用，而无需依赖像ChatGPT这样的专有大型语言模型。

> The development of Automatic Question Generation (QG) models has the potential to significantly improve educational practices by reducing the teacher workload associated with creating educational content. This paper introduces a novel approach to educational question generation that controls the topical focus of questions. The proposed Topic-Controlled Question Generation (T-CQG) method enhances the relevance and effectiveness of the generated content for educational purposes. Our approach uses fine-tuning on a pre-trained T5-small model, employing specially created datasets tailored to educational needs. The research further explores the impacts of pre-training strategies, quantisation, and data augmentation on the model's performance. We specifically address the challenge of generating semantically aligned questions with paragraph-level contexts, thereby improving the topic specificity of the generated questions. In addition, we introduce and explore novel evaluation methods to assess the topical relatedness of the generated questions. Our results, validated through rigorous offline and human-backed evaluations, demonstrate that the proposed models effectively generate high-quality, topic-focused questions. These models have the potential to reduce teacher workload and support personalised tutoring systems by serving as bespoke question generators. With its relatively small number of parameters, the proposals not only advance the capabilities of question generation models for handling specific educational topics but also offer a scalable solution that reduces infrastructure costs. This scalability makes them feasible for widespread use in education without reliance on proprietary large language models like ChatGPT.

[Arxiv](https://arxiv.org/abs/2501.05220)
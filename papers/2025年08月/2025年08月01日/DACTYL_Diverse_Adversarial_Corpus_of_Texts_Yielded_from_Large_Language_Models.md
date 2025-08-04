# # DACTYL：生成于大型语言模型的多样化对抗文本语料库

发布时间：2025年08月01日

`LLM应用

理由：这篇论文主要关注AI生成文本检测器在实际应用中的性能问题，特别是针对单样本/少量样本生成和特定领域生成文本的检测。研究者引入了新的数据集和训练方法，以改进检测器的泛化能力和健壮性。这属于LLM的应用层面，旨在提升文本检测的实际效果。`

> DACTYL: Diverse Adversarial Corpus of Texts Yielded from Large Language Models

# 摘要

> 现有的AI生成文本检测器在现实场景中表现不佳，尽管在内部测试中取得了成功，这表明它们可能不够健壮。我们严格检查了构建这些检测器的机器学习流程来解决这一问题。目前大多数AI生成文本检测数据集关注于零样本生成，但对少量样本或单样本生成的研究很少，即LLMs被提供人类文本作为示例。为此，我们引入了DACTYL（Diverse Adversarial Corpus of Texts Yielded from Language models）数据集，这是一个专注于单样本/少量样本生成的具有挑战性的AI生成文本检测数据集。我们还包含了来自特定领域继续预训练（CPT）语言模型生成的文本，其中我们使用内存高效的优化方法对所有参数进行了完整训练。许多现有的AI生成文本检测器在我们的数据集上表现不佳，这表明它们可能对单样本/少量样本生成文本和CPT生成文本存在潜在漏洞。我们还使用两种方法训练了我们自己的分类器：标准的二元交叉熵（BCE）优化和一种更近期的方法，深度X风险优化（DXO）。虽然在DACTYL测试集上，BCE训练的分类器略优于DXO分类器，但在分布外（OOD）文本上，后者表现更佳。在我们的模拟部署场景中，使用OOD学生作文数据集进行学生作文检测时，最佳的DXO分类器在最低的假阳性率下，其宏F1分数比最佳的BCE训练分类器高出50.56分。我们的研究结果表明，DXO分类器具有更好的泛化能力，而不会过度拟合测试集。我们的实验结果突显了AI生成文本检测器在多个方面的改进空间。

> Existing AIG (AI-generated) text detectors struggle in real-world settings despite succeeding in internal testing, suggesting that they may not be robust enough. We rigorously examine the machine-learning procedure to build these detectors to address this. Most current AIG text detection datasets focus on zero-shot generations, but little work has been done on few-shot or one-shot generations, where LLMs are given human texts as an example. In response, we introduce the Diverse Adversarial Corpus of Texts Yielded from Language models (DACTYL), a challenging AIG text detection dataset focusing on one-shot/few-shot generations. We also include texts from domain-specific continued-pre-trained (CPT) language models, where we fully train all parameters using a memory-efficient optimization approach. Many existing AIG text detectors struggle significantly on our dataset, indicating a potential vulnerability to one-shot/few-shot and CPT-generated texts. We also train our own classifiers using two approaches: standard binary cross-entropy (BCE) optimization and a more recent approach, deep X-risk optimization (DXO). While BCE-trained classifiers marginally outperform DXO classifiers on the DACTYL test set, the latter excels on out-of-distribution (OOD) texts. In our mock deployment scenario in student essay detection with an OOD student essay dataset, the best DXO classifier outscored the best BCE-trained classifier by 50.56 macro-F1 score points at the lowest false positive rates for both. Our results indicate that DXO classifiers generalize better without overfitting to the test set. Our experiments highlight several areas of improvement for AIG text detectors.

[Arxiv](https://arxiv.org/abs/2508.00619)
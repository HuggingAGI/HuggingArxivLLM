# 如何在不泄露真实答案的情况下发布我的 LLM 基准测试？

发布时间：2025年05月23日

`LLM应用

理由：这篇论文探讨了在发布大型语言模型基准测试时可能带来的污染问题，并提出了一种新的方法来缓解这一问题。这种方法通过引入随机性到基准答案中，从而降低基准的最佳可能准确率，并提供了一种检测数据污染的方法。这属于大型语言模型的应用层面的优化和改进，因此归类为LLM应用。` `基准测试` `数据污染检测`

> How Can I Publish My LLM Benchmark Without Giving the True Answers Away?

# 摘要

> 在互联网上发布大型语言模型（LLM）基准测试可能污染未来LLMs：该基准可能被用于训练或选择模型，无论是有意还是无意。一种常见缓解方法是将基准设为私有，仅让参与者提交模型或预测结果给组织方。然而，此方法仍需依赖单一组织的信任，并可能因重复查询导致测试集过拟合。为解决此问题，我们提出了一种无需完全公开问题正确答案即可发布基准的方法，同时仍能公开评估LLMs。我们的核心思路是通过准备多个逻辑上正确的答案，并在基准中仅包含其中一个作为答案，从而向答案注入随机性。这降低了基准的最佳可能准确率（即贝叶斯准确率）。这不仅有助于保护真实答案不被泄露，还提供了一种检测数据污染的方法。理论上，即使完全有能力的模型也不应超越贝叶斯准确率。如果一个模型在预期中未能超越这一上限却仍超越了，这强烈表明存在数据污染。我们通过实验展示了我们的方法可以在广泛的基准、模型和训练方法上准确检测数据污染。


> Publishing a large language model (LLM) benchmark on the Internet risks contaminating future LLMs: the benchmark may be unintentionally (or intentionally) used to train or select a model. A common mitigation is to keep the benchmark private and let participants submit their models or predictions to the organizers. However, this strategy will require trust in a single organization and still permits test-set overfitting through repeated queries. To overcome this issue, we propose a way to publish benchmarks without completely disclosing the ground-truth answers to the questions, while still maintaining the ability to openly evaluate LLMs. Our main idea is to inject randomness to the answers by preparing several logically correct answers, and only include one of them as the solution in the benchmark. This reduces the best possible accuracy, i.e., Bayes accuracy, of the benchmark. Not only is this helpful to keep us from disclosing the ground truth, but this approach also offers a test for detecting data contamination. In principle, even fully capable models should not surpass the Bayes accuracy. If a model surpasses this ceiling despite this expectation, this is a strong signal of data contamination. We present experimental evidence that our method can detect data contamination accurately on a wide range of benchmarks, models, and training methodologies.

[Arxiv](https://arxiv.org/abs/2505.18102)
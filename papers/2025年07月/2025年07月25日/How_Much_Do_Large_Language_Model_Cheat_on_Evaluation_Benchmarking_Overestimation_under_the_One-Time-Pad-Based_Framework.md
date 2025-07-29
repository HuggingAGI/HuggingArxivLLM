# 大型语言模型在评估中作弊吗？基于一次性密码本框架的过高估计基准测试

发布时间：2025年07月25日

`LLM应用

摘要中讨论了评估大型语言模型时的过高评估问题，并提出了一个新的动态评估框架ArxivRoll，用于更有效地评估LLMs的性能。这属于评估工具和方法的改进，因此归类为LLM应用。` `基准测试`

> How Much Do Large Language Model Cheat on Evaluation? Benchmarking Overestimation under the One-Time-Pad-Based Framework

# 摘要

> 评估大型语言模型（LLMs）时，过高评估问题日益引起关注。由于公开基准测试的污染或模型训练的不平衡，LLMs可能在公开基准测试上获得不真实的评估结果，无论出于有意还是无意，这导致了LLMs之间的不公平比较，并削弱了对其实际能力的评估。现有基准测试试图通过永久保密测试用例、通过人工评估减轻污染，或反复收集和构建新样本来解决这些问题。然而，这些方法未能同时确保可重复性、透明性和高效率。此外，当前LLMs的过高评估程度仍未量化。

为了解决这些问题，我们提出了ArxivRoll，一个受密码学中一次性密码本加密启发的动态评估框架。ArxivRoll包含两个关键组件：\emph{i) SCP（排序、填空与预测）}，一个自动生成私有测试用例的工具，以及\emph{ii) Rugged Scores（RS）}，衡量公开基准测试污染程度和训练偏见的指标。借助SCP，ArxivRoll每半年使用ArXiv上最新的文章构建一个新基准，并用于一次性评估LLM性能。大量实验展示了我们基准测试的高质量，并对当前LLMs进行了系统性评估。源代码可在https://github.com/liangzid/ArxivRoll/获取。

> Overestimation in evaluating large language models (LLMs) has become an increasing concern. Due to the contamination of public benchmarks or imbalanced model training, LLMs may achieve unreal evaluation results on public benchmarks, either intentionally or unintentionally, which leads to unfair comparisons among LLMs and undermines their realistic capability assessments. Existing benchmarks attempt to address these issues by keeping test cases permanently secret, mitigating contamination through human evaluation, or repeatedly collecting and constructing new samples. However, these approaches fail to ensure reproducibility, transparency, and high efficiency simultaneously. Moreover, the extent of overestimation in current LLMs remains unquantified. To address these issues, we propose ArxivRoll, a dynamic evaluation framework inspired by one-time pad encryption in cryptography. ArxivRoll comprises two key components: \emph{i) SCP (Sequencing, Cloze, and Prediction)}, an automated generator for private test cases, and \emph{ii) Rugged Scores (RS)}, metrics that measure the proportion of public benchmark contamination and training bias. Leveraging SCP, ArxivRoll constructs a new benchmark every six months using recent articles from ArXiv and employs them for one-time evaluations of LLM performance. Extensive experiments demonstrate the high quality of our benchmark, and we provide a systematic evaluation of current LLMs. The source code is available at https://github.com/liangzid/ArxivRoll/.

[Arxiv](https://arxiv.org/abs/2507.19219)
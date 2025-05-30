# 第二意见很重要：通过专家模型集成的共识迈向自适应临床AI

发布时间：2025年05月29日

`Agent` `临床决策支持系统`

> Second Opinion Matters: Towards Adaptive Clinical AI via the Consensus of Expert Model Ensemble

# 摘要

> 尽管大型语言模型（LLMs）在临床应用中逐渐普及，但目前的方法仍然高度依赖单一模型架构。为了克服模型过时风险和对单一系统 rigid 依赖，我们提出了一种名为“共识机制”的全新框架。该机制模仿临床分诊和多学科临床决策流程，通过集合专门的医疗专家代理，实现了更优的临床决策能力，同时保持强大的适应性。这种架构使共识机制能够根据内部模型配置，纯粹地针对成本、延迟或性能进行优化。
为了严格评估共识机制，我们采用了三个医学评估基准：MedMCQA、MedQA 和 MedXpertQA Text，以及鉴别诊断数据集 DDX+。在 MedXpertQA 上，共识机制的准确率为 61.0%，显著高于 OpenAI 的 O3（53.5%）和 Google 的 Gemini 2.5 Pro（45.9%）。这种改进在所有基准测试中都保持一致，在 MedQA 上准确率提高了 3.4%，在 MedMCQA 上提高了 9.1%。这些准确率的提升也延伸到了鉴别诊断生成领域，我们的系统在召回率和精确度上表现更优（F1$_\mathrm{consensus}$ = 0.326 vs. F1$_{\mathrm{O3	ext{-}high}}$ = 0.2886），并且在 DDX 的 top-1 准确率上也更高（Top1$_\mathrm{consensus}$ = 52.0% vs. Top1$_{\mathrm{O3	ext{-}high}}$ = 45.2%）。

> Despite the growing clinical adoption of large language models (LLMs), current approaches heavily rely on single model architectures. To overcome risks of obsolescence and rigid dependence on single model systems, we present a novel framework, termed the Consensus Mechanism. Mimicking clinical triage and multidisciplinary clinical decision-making, the Consensus Mechanism implements an ensemble of specialized medical expert agents enabling improved clinical decision making while maintaining robust adaptability. This architecture enables the Consensus Mechanism to be optimized for cost, latency, or performance, purely based on its interior model configuration.
  To rigorously evaluate the Consensus Mechanism, we employed three medical evaluation benchmarks: MedMCQA, MedQA, and MedXpertQA Text, and the differential diagnosis dataset, DDX+. On MedXpertQA, the Consensus Mechanism achieved an accuracy of 61.0% compared to 53.5% and 45.9% for OpenAI's O3 and Google's Gemini 2.5 Pro. Improvement was consistent across benchmarks with an increase in accuracy on MedQA ($Δ\mathrm{Accuracy}_{\mathrm{consensus\text{-}O3}} = 3.4\%$) and MedMCQA ($Δ\mathrm{Accuracy}_{\mathrm{consensus\text{-}O3}} = 9.1\%$). These accuracy gains extended to differential diagnosis generation, where our system demonstrated improved recall and precision (F1$_\mathrm{consensus}$ = 0.326 vs. F1$_{\mathrm{O3\text{-}high}}$ = 0.2886) and a higher top-1 accuracy for DDX (Top1$_\mathrm{consensus}$ = 52.0% vs. Top1$_{\mathrm{O3\text{-}high}}$ = 45.2%).

[Arxiv](https://arxiv.org/abs/2505.23075)
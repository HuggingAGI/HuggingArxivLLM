# 流利却文化疏远：区域训练能否培养文化理解？

发布时间：2025年05月24日

`LLM应用` `文化评估` `多语言模型`

> Fluent but Culturally Distant: Can Regional Training Teach Cultural Understanding?

# 摘要

> 大型语言模型（LLMs）在全球范围内被广泛应用，但它们往往表现出西方文化倾向。为了应对这种文化错位问题，许多国家已经开始开发针对本地社区的“区域”LLMs。然而，目前尚不清楚这些模型是否仅仅能够使用用户的语言，还是也能够反映其文化价值观和实践。

以印度为例，我们对五款印度本地模型和五款全球通用模型进行了评估，主要从两个关键维度进行分析：价值观（通过Inglehart-Welzel图谱和GlobalOpinionQA）和实践（通过CulturalBench和NormAd）。在所有四项任务中，我们发现印度本地模型在与印度文化规范的契合度上并不比全球模型更高。事实上，一个普通的美国人对印度文化价值观的体现要比任何印度本地模型都更贴切。即使采用提示策略，也无法显著提升契合度。

通过消融实验我们发现，区域微调并未提升文化能力，反而可能因阻碍现有知识的调用而损害文化表现。我们将其归因于高质量、未翻译且具有文化背景的预训练和微调数据的稀缺性。

我们的研究将文化评估与多语言基准测试并列为首要要求，并为开发者提供了一种可重复使用的评估方法。我们呼吁加大对具有文化代表性的数据集的投入，以构建和评估真正具有文化主权的LLMs。

> Large language models (LLMs) are used around the world but exhibit Western cultural tendencies. To address this cultural misalignment, many countries have begun developing "regional" LLMs tailored to local communities. Yet it remains unclear whether these models merely speak the language of their users or also reflect their cultural values and practices. Using India as a case study, we evaluate five Indic and five global LLMs along two key dimensions: values (via the Inglehart-Welzel map and GlobalOpinionQA) and practices (via CulturalBench and NormAd). Across all four tasks, we find that Indic models do not align more closely with Indian cultural norms than global models. In fact, an average American person is a better proxy for Indian cultural values than any Indic model. Even prompting strategies fail to meaningfully improve alignment. Ablations show that regional fine-tuning does not enhance cultural competence and may in fact hurt it by impeding recall of existing knowledge. We trace this failure to the scarcity of high-quality, untranslated, and culturally grounded pretraining and fine-tuning data. Our study positions cultural evaluation as a first-class requirement alongside multilingual benchmarks and offers a reusable methodology for developers. We call for deeper investments in culturally representative data to build and evaluate truly sovereign LLMs.

[Arxiv](https://arxiv.org/abs/2505.21548)
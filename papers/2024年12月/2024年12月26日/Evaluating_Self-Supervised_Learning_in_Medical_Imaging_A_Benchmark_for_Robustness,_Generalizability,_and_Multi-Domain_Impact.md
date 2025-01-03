# 医学影像自监督学习评估：鲁棒性、泛化性与多领域影响的基准研究

发布时间：2024年12月26日

`其他

理由：这篇论文主要讨论的是自监督学习（SSL）在医学影像领域的应用和评估，特别是其稳健性和泛化能力。虽然SSL与大型语言模型（LLM）有一定的关联，但论文的核心内容并不直接涉及LLM、Agent、RAG或LLM理论。因此，将其分类为“其他”更为合适。` `医学影像`

> Evaluating Self-Supervised Learning in Medical Imaging: A Benchmark for Robustness, Generalizability, and Multi-Domain Impact

# 摘要

> # 摘要
自监督学习（SSL）在医学影像领域崭露头角，有效应对了医疗环境中标签数据稀缺的长期难题。尽管SSL成果斐然，但现有研究多局限于特定数据集或模态，或仅评估模型性能的单一维度。这种碎片化评估方式带来了严峻挑战，因为医疗场景中的模型不仅需高精度，还需在多样化数据集和复杂条件下展现稳健性与泛化能力。为此，我们对医学领域的SSL方法进行了全面评估，特别聚焦于其稳健性和泛化能力。以MedMNIST数据集为基准，我们在11个医学数据集上测试了8种主流SSL方法。研究深入探讨了模型在域内场景和检测分布外（OOD）样本中的表现，并分析了不同初始化策略、模型架构及多域预训练的影响。通过跨数据集评估和不同标签比例（1%、10%和100%）下的域内性能测试，我们进一步验证了SSL方法的泛化能力，模拟了现实世界中监督有限的情境。希望这一全面基准能为从业者和研究人员在医学应用中应用SSL方法提供有力参考。

> Self-supervised learning (SSL) has emerged as a promising paradigm in medical imaging, addressing the chronic challenge of limited labeled data in healthcare settings. While SSL has shown impressive results, existing studies in the medical domain are often limited in scope, focusing on specific datasets or modalities, or evaluating only isolated aspects of model performance. This fragmented evaluation approach poses a significant challenge, as models deployed in critical medical settings must not only achieve high accuracy but also demonstrate robust performance and generalizability across diverse datasets and varying conditions. To address this gap, we present a comprehensive evaluation of SSL methods within the medical domain, with a particular focus on robustness and generalizability. Using the MedMNIST dataset collection as a standardized benchmark, we evaluate 8 major SSL methods across 11 different medical datasets. Our study provides an in-depth analysis of model performance in both in-domain scenarios and the detection of out-of-distribution (OOD) samples, while exploring the effect of various initialization strategies, model architectures, and multi-domain pre-training. We further assess the generalizability of SSL methods through cross-dataset evaluations and the in-domain performance with varying label proportions (1%, 10%, and 100%) to simulate real-world scenarios with limited supervision. We hope this comprehensive benchmark helps practitioners and researchers make more informed decisions when applying SSL methods to medical applications.

[Arxiv](https://arxiv.org/abs/2412.19124)
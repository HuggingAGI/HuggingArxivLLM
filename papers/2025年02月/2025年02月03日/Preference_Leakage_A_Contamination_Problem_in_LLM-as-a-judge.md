# 偏好泄露：LLM作为评判者时的污染问题

发布时间：2025年02月03日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）在数据标注和评判中的潜在问题，特别是偏好泄漏问题。论文通过定义和实验分析了LLM评判者与数据生成器之间的关系及其对评判结果的影响。这些研究内容属于对LLM内部机制和行为的理论探讨，旨在揭示和解决LLM在应用中的潜在问题，因此应归类为“LLM理论”。` `人工智能` `模型评估`

> Preference Leakage: A Contamination Problem in LLM-as-a-judge

# 摘要

> 大型语言模型（LLMs）作为评判者和基于LLM的数据合成已成为模型开发中的两大基础数据标注方法。尽管它们的结合显著提升了模型训练和评估的效率，但这种新范式可能带来的潜在污染却鲜有人关注。本研究揭示了偏好泄漏问题，即由合成数据生成器与基于LLM的评估者之间的相关性引发的LLM评判污染。我们首先定义了数据生成器LLM与评判者LLM之间的三种常见关系：同一模型、继承关系和同属一个模型家族。通过大量实验，我们实证了评判者对其相关学生模型的偏见，这种偏见源于偏好泄漏在多个LLM基线和基准测试中的影响。进一步分析表明，偏好泄漏是一个普遍且难以检测的问题，相较于之前发现的LLM评判偏见更为隐蔽。这些发现表明，偏好泄漏是LLM评判领域中一个广泛存在且极具挑战性的问题。所有代码和数据已发布在：https://github.com/David-Li0406/Preference-Leakage。

> Large Language Models (LLMs) as judges and LLM-based data synthesis have emerged as two fundamental LLM-driven data annotation methods in model development. While their combination significantly enhances the efficiency of model training and evaluation, little attention has been given to the potential contamination brought by this new model development paradigm. In this work, we expose preference leakage, a contamination problem in LLM-as-a-judge caused by the relatedness between the synthetic data generators and LLM-based evaluators. To study this issue, we first define three common relatednesses between data generator LLM and judge LLM: being the same model, having an inheritance relationship, and belonging to the same model family. Through extensive experiments, we empirically confirm the bias of judges towards their related student models caused by preference leakage across multiple LLM baselines and benchmarks. Further analysis suggests that preference leakage is a pervasive issue that is harder to detect compared to previously identified biases in LLM-as-a-judge scenarios. All of these findings imply that preference leakage is a widespread and challenging problem in the area of LLM-as-a-judge. We release all codes and data at: https://github.com/David-Li0406/Preference-Leakage.

[Arxiv](https://arxiv.org/abs/2502.01534)
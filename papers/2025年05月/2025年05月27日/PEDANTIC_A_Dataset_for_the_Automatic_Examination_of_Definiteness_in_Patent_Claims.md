# PEDANTIC：一个用于专利声明明确性自动检测的数据集

发布时间：2025年05月27日

`LLM应用`

> PEDANTIC: A Dataset for the Automatic Examination of Definiteness in Patent Claims

# 摘要

> 专利的权利要求定义了发明的保护范围。若权利要求表述模糊，专利局将予以驳回。在美国，这被称为 indefiniteness（35 U.S.C § 112(b)），是专利申请被驳回最常见的原因之一。开发自动化的专利明确性审查方法有望提升专利撰写和审查效率，但目前尚未有标注数据集公开发布。

我们推出 PEDANTIC（P_at_e_nt D_efiniteness E_x_amination Corpus），一个包含1.4万条美国专利申请权利要求的新型数据集，这些专利申请涉及自然语言处理（NLP）领域，并标注了明确性不足的原因。我们采用完全自动化的流水线构建 PEDANTIC，该流水线从美国专利商标局（USPTO）检索官方行动文件，并利用大型语言模型（LLMs）提取明确性不足的原因。人工验证研究表明，该流水线能生成高质量标注。为深入分析，我们实施了 LLM-as-Judge 评估，将模型引用的原因与审查员引用的原因进行自由形式推理比较。研究发现，基于 Qwen 2.5 32B 和 72B 的 LLM 代理在明确性预测上难以超越逻辑回归基线，尽管它们通常能正确识别潜在原因。PEDANTIC 为专利 AI 研究者提供了宝贵资源，助力开发先进审查模型。我们将公开发布该数据集和代码。


> Patent claims define the scope of protection for an invention. If there are ambiguities in a claim, it is rejected by the patent office. In the US, this is referred to as indefiniteness (35 U.S.C § 112(b)) and is among the most frequent reasons for patent application rejection. The development of automatic methods for patent definiteness examination has the potential to make patent drafting and examination more efficient, but no annotated dataset has been published to date.
  We introduce PEDANTIC (\underline{P}at\underline{e}nt \underline{D}efiniteness Ex\underline{a}mi\underline{n}a\underline{ti}on \underline{C}orpus), a novel dataset of 14k US patent claims from patent applications relating to Natural Language Processing (NLP), annotated with reasons for indefiniteness. We construct PEDANTIC using a fully automatic pipeline that retrieves office action documents from the USPTO and uses Large Language Models (LLMs) to extract the reasons for indefiniteness. A human validation study confirms the pipeline's accuracy in generating high-quality annotations. To gain insight beyond binary classification metrics, we implement an LLM-as-Judge evaluation that compares the free-form reasoning of every model-cited reason with every examiner-cited reason. We show that LLM agents based on Qwen 2.5 32B and 72B struggle to outperform logistic regression baselines on definiteness prediction, even though they often correctly identify the underlying reasons. PEDANTIC provides a valuable resource for patent AI researchers, enabling the development of advanced examination models. We will publicly release the dataset and code.

[Arxiv](https://arxiv.org/abs/2505.21342)
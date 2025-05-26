# # 案例报告基准
CaseReportBench：面向临床病例报告中密集信息抽取的大型语言模型基准数据集。

发布时间：2025年05月22日

`LLM应用`

> CaseReportBench: An LLM Benchmark Dataset for Dense Information Extraction in Clinical Case Reports

# 摘要

> 罕见病，特别是先天性代谢障碍（IEM），为诊断带来了巨大挑战。病例报告作为关键但尚未被充分计算利用的资源，能够为诊断提供重要信息。临床密集信息抽取指的是将医学信息组织到预定义的结构化类别中。大型语言模型（LLMs）可能能够从病例报告中进行可扩展的信息抽取，但这一任务尚未得到充分评估。

我们引入了CaseReportBench，这是一个专家标注的数据集，专注于从病例报告中提取密集信息，特别是针对IEM。利用该数据集，我们评估了多种模型和提示策略，并引入了新型方法，例如类别特定提示和子标题过滤数据整合。零样本链式推理提示相较于标准零样本提示并无显著优势。类别特定提示能更好地与基准对齐。开源模型Qwen2.5-7B在此任务中优于GPT-4o。

我们的临床医生评估显示，LLMs能够从病例报告中提取具有临床相关性的细节，从而支持罕见病的诊断和管理。我们还指出了改进方向，例如LLMs在识别对鉴别诊断至关重要的阴性发现方面存在局限性。这项研究推动了LLM驱动的临床自然语言处理，并为可扩展的医疗AI应用铺平了道路。

> Rare diseases, including Inborn Errors of Metabolism (IEM), pose significant diagnostic challenges. Case reports serve as key but computationally underutilized resources to inform diagnosis. Clinical dense information extraction refers to organizing medical information into structured predefined categories. Large Language Models (LLMs) may enable scalable information extraction from case reports but are rarely evaluated for this task. We introduce CaseReportBench, an expert-annotated dataset for dense information extraction of case reports, focusing on IEMs. Using this dataset, we assess various models and prompting strategies, introducing novel approaches such as category-specific prompting and subheading-filtered data integration. Zero-shot chain-of-thought prompting offers little advantage over standard zero-shot prompting. Category-specific prompting improves alignment with the benchmark. The open-source model Qwen2.5-7B outperforms GPT-4o for this task. Our clinician evaluations show that LLMs can extract clinically relevant details from case reports, supporting rare disease diagnosis and management. We also highlight areas for improvement, such as LLMs' limitations in recognizing negative findings important for differential diagnosis. This work advances LLM-driven clinical natural language processing and paves the way for scalable medical AI applications.

[Arxiv](https://arxiv.org/abs/2505.17265)
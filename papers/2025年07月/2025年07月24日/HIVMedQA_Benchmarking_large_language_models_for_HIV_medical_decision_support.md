# HIVMedQA：评估大型语言模型在HIV医疗决策支持中的表现

发布时间：2025年07月24日

`LLM应用` `问答系统`

> HIVMedQA: Benchmarking large language models for HIV medical decision support

# 摘要

> 大型语言模型（LLMs）正在成为临床医生日常决策中的得力工具。HIV管理因其复杂性——包括多样化的治疗选择、合并症和依从性挑战——成为一个极具吸引力的用例。然而，将LLMs整合到临床实践中仍面临准确性、潜在危害及临床医生接受度的挑战。尽管AI在HIV护理中展现出潜力，但其应用尚未得到充分探索，关于LLMs的基准研究也较为有限。本研究旨在评估LLMs在HIV管理中的能力，揭示其优缺点。

我们推出了HIVMedQA，这是一个专为评估HIV护理中开放性医疗问题回答能力而设计的基准。该数据集包含经过精心策划、具有临床相关性的问题，这些问题是在感染病医师的参与下开发的。我们对七种通用型和三种医疗专业型LLMs进行了评估，并通过提示工程优化了性能。我们的评估框架结合了词汇相似性和以LLM为裁判的方法，并进行了扩展以更好地反映临床相关性。

我们在多个关键维度上评估了模型性能：问题理解、推理、知识召回、偏见、潜在危害和事实准确性。结果显示，Gemini 2.5 Pro在大多数维度上表现最为出色。值得注意的是，排名前三位的模型中有两个是专有模型。随着问题复杂性的增加，模型性能有所下降。经过医疗微调的模型并不总是优于通用型模型，且模型规模越大并不总是意味着性能更优。推理和理解问题比事实性回忆更具挑战性，同时我们还观察到了近期和现状等认知偏见。

这些发现强调了针对LLMs在临床护理中安全、有效整合进行定向开发和评估的必要性。

> Large language models (LLMs) are emerging as valuable tools to support clinicians in routine decision-making. HIV management is a compelling use case due to its complexity, including diverse treatment options, comorbidities, and adherence challenges. However, integrating LLMs into clinical practice raises concerns about accuracy, potential harm, and clinician acceptance. Despite their promise, AI applications in HIV care remain underexplored, and LLM benchmarking studies are scarce. This study evaluates the current capabilities of LLMs in HIV management, highlighting their strengths and limitations. We introduce HIVMedQA, a benchmark designed to assess open-ended medical question answering in HIV care. The dataset consists of curated, clinically relevant questions developed with input from an infectious disease physician. We evaluated seven general-purpose and three medically specialized LLMs, applying prompt engineering to enhance performance. Our evaluation framework incorporates both lexical similarity and an LLM-as-a-judge approach, extended to better reflect clinical relevance. We assessed performance across key dimensions: question comprehension, reasoning, knowledge recall, bias, potential harm, and factual accuracy. Results show that Gemini 2.5 Pro consistently outperformed other models across most dimensions. Notably, two of the top three models were proprietary. Performance declined as question complexity increased. Medically fine-tuned models did not always outperform general-purpose ones, and larger model size was not a reliable predictor of performance. Reasoning and comprehension were more challenging than factual recall, and cognitive biases such as recency and status quo were observed. These findings underscore the need for targeted development and evaluation to ensure safe, effective LLM integration in clinical care.

[Arxiv](https://arxiv.org/abs/2507.18143)
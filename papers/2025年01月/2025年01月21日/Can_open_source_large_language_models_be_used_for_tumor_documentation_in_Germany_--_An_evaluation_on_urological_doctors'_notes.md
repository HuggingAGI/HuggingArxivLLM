# 开源大语言模型能否胜任德国肿瘤文档记录？——基于泌尿科医生笔记的评估

发布时间：2025年01月21日

`LLM应用

**理由**：这篇论文主要探讨了大型语言模型（LLMs）在肿瘤记录自动化中的应用，具体包括肿瘤诊断识别、ICD-10编码分配及首次诊断日期提取等任务。论文通过评估不同规模和类型的开源LLMs在这些任务中的表现，展示了LLMs在医学领域的应用潜力。因此，这篇论文属于LLM应用类别。` `肿瘤学`

> Can open source large language models be used for tumor documentation in Germany? -- An evaluation on urological doctors' notes

# 摘要

> # 摘要
在德国，肿瘤记录主要依赖人工操作，需从患者病历中提取信息并录入结构化数据库。大型语言模型（LLMs）有望通过提升效率和可靠性来优化这一流程。本次评估测试了11款开源LLMs，模型参数规模从1到700亿不等，针对肿瘤记录中的三大任务：肿瘤诊断识别、ICD-10编码分配及首次诊断日期提取。我们基于匿名泌尿科医生笔记构建了一个注释文本片段数据集，用于评估LLMs的表现。通过不同提示策略，我们探究了少样本提示中示例数量的影响，并测试了LLMs的通用能力。结果显示，Llama 3.1 8B、Mistral 7B和Mistral NeMo 12 B模型表现优异。训练数据较少或参数低于70亿的模型表现欠佳，而更大规模的模型并未带来性能提升。值得注意的是，引入泌尿科以外的医学领域示例也能提升少样本提示的效果，表明LLMs具备处理肿瘤记录任务的能力。开源LLMs在自动化肿瘤记录方面展现出巨大潜力，7到120亿参数的模型在性能与资源效率之间达到了最佳平衡。通过定制微调和精心设计的提示，这些模型有望成为未来临床记录的重要工具。评估代码已开源，数据集也已发布，填补了德语医学NLP领域真实且易获取的基准数据空白。

> Tumor documentation in Germany is largely done manually, requiring reading patient records and entering data into structured databases. Large language models (LLMs) could potentially enhance this process by improving efficiency and reliability. This evaluation tests eleven different open source LLMs with sizes ranging from 1-70 billion model parameters on three basic tasks of the tumor documentation process: identifying tumor diagnoses, assigning ICD-10 codes, and extracting the date of first diagnosis. For evaluating the LLMs on these tasks, a dataset of annotated text snippets based on anonymized doctors' notes from urology was prepared. Different prompting strategies were used to investigate the effect of the number of examples in few-shot prompting and to explore the capabilities of the LLMs in general. The models Llama 3.1 8B, Mistral 7B, and Mistral NeMo 12 B performed comparably well in the tasks. Models with less extensive training data or having fewer than 7 billion parameters showed notably lower performance, while larger models did not display performance gains. Examples from a different medical domain than urology could also improve the outcome in few-shot prompting, which demonstrates the ability of LLMs to handle tasks needed for tumor documentation. Open source LLMs show a strong potential for automating tumor documentation. Models from 7-12 billion parameters could offer an optimal balance between performance and resource efficiency. With tailored fine-tuning and well-designed prompting, these models might become important tools for clinical documentation in the future. The code for the evaluation is available from https://github.com/stefan-m-lenz/UroLlmEval. We also release the dataset as a new valuable resource that addresses the shortage of authentic and easily accessible benchmarks in German-language medical NLP.

[Arxiv](https://arxiv.org/abs/2501.12106)
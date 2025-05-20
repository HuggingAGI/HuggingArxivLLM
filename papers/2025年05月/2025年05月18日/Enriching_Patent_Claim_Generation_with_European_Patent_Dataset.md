# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年05月18日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在专利声明生成中的应用，引入了一个新的欧洲专利数据集（EPD），并展示了如何利用该数据集来提升LLMs在专利撰写任务中的性能。这属于LLM的应用层面，因此分类为LLM应用。` `数据集`

> Enriching Patent Claim Generation with European Patent Dataset

# 摘要

> 撰写专利声明耗时费力，需要专业技能。因此，研究人员一直在探索大型语言模型（LLMs）来协助发明者撰写专利声明。然而，现有研究主要依赖于美国专利商标局（USPTO）的数据集。为了扩大研究范围，涵盖不同司法管辖区、撰写惯例和法律标准，我们引入了EPD，一个欧洲专利数据集。EPD提供了丰富的文本数据和结构化元数据，支持多种与专利相关的任务，包括专利声明生成。该数据集在以下三个关键方面丰富了这一领域：

(1) 司法管辖区多样性：不同专利机构的专利在法律和撰写惯例上存在差异。EPD通过提供欧洲专利的基准，填补了这一关键空白，从而实现了更全面的评估。

(2) 质量提升：EPD提供了高质量的已授权专利，其文本已经最终确定并获得法律批准，而其他数据集则由未经审核或临时的专利申请组成。实验表明，经过EPD微调的LLMs在专利声明质量和跨领域泛化能力上显著优于基于先前数据集训练的模型，甚至优于GPT-4o。

(3) 现实模拟：我们提出EPD的一个困难子集，以更好地反映专利声明生成的现实挑战。结果显示，所有测试的LLMs在这些具有挑战性的样本上表现明显较差，突显了未来研究的必要性。

> Drafting patent claims is time-intensive, costly, and requires professional skill. Therefore, researchers have investigated large language models (LLMs) to assist inventors in writing claims. However, existing work has largely relied on datasets from the United States Patent and Trademark Office (USPTO). To enlarge research scope regarding various jurisdictions, drafting conventions, and legal standards, we introduce EPD, a European patent dataset. EPD presents rich textual data and structured metadata to support multiple patent-related tasks, including claim generation. This dataset enriches the field in three critical aspects: (1) Jurisdictional diversity: Patents from different offices vary in legal and drafting conventions. EPD fills a critical gap by providing a benchmark for European patents to enable more comprehensive evaluation. (2) Quality improvement: EPD offers high-quality granted patents with finalized and legally approved texts, whereas others consist of patent applications that are unexamined or provisional. Experiments show that LLMs fine-tuned on EPD significantly outperform those trained on previous datasets and even GPT-4o in claim quality and cross-domain generalization. (3) Real-world simulation: We propose a difficult subset of EPD to better reflect real-world challenges of claim generation. Results reveal that all tested LLMs perform substantially worse on these challenging samples, which highlights the need for future research.

[Arxiv](https://arxiv.org/abs/2505.12568)
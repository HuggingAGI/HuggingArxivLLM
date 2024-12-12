# : 用于药物专利自动化分析的智能代理

发布时间：2024年10月25日

`Agent` `专利分析`

> : Intelligent Agent for Automated Pharmaceutical Patent Analysis

# 摘要

> 制药专利在生化行业里至关重要，尤其在药物研发领域，为研究人员提供了早期获取独特数据、实验结果及研究见解的途径。伴随机器学习的发展，专利分析已从人工操作转变为自动工具辅助的任务。但目前仍缺少一个能辅助专利分析各方面（从专利阅读到核心化学识别）的统一代理。借助大型语言模型（LLMs）理解需求和遵循指令的能力，我们在该领域推出了首个智能代理——$	exttt{PatentAgent}$，有望推动并可能彻底变革制药研究的局面。$	exttt{PatentAgent}$涵盖三个关键的端到端模块——$	extit{PA-QA}$、$	extit{PA-Img2Mol}$和$	extit{PA-CoreId}$，分别执行（1）专利问答、（2）图像到分子结构的转换以及（3）核心化学结构的识别，满足了制药专利分析中科学家和从业者的核心需求。$	exttt{PatentAgent}$的每个模块在更新算法和$	exttt{PatentAgent}$框架的协同设计下，均展现出显著的有效性。$	extit{PA-Img2Mol}$在 CLEF、JPO、UOB 和 USPTO 等专利基准测试中的表现优于现有方法，准确率提升了 2.46%至 8.37%，而$	extit{PA-CoreId}$在 PatentNetML 基准测试中的准确率提高了 7.15%至 7.62%。我们的代码和数据集将公开可用。

> Pharmaceutical patents play a vital role in biochemical industries, especially in drug discovery, providing researchers with unique early access to data, experimental results, and research insights. With the advancement of machine learning, patent analysis has evolved from manual labor to tasks assisted by automatic tools. However, there still lacks an unified agent that assists every aspect of patent analysis, from patent reading to core chemical identification. Leveraging the capabilities of Large Language Models (LLMs) to understand requests and follow instructions, we introduce the $\textbf{first}$ intelligent agent in this domain, $\texttt{PatentAgent}$, poised to advance and potentially revolutionize the landscape of pharmaceutical research. $\texttt{PatentAgent}$ comprises three key end-to-end modules -- $\textit{PA-QA}$, $\textit{PA-Img2Mol}$, and $\textit{PA-CoreId}$ -- that respectively perform (1) patent question-answering, (2) image-to-molecular-structure conversion, and (3) core chemical structure identification, addressing the essential needs of scientists and practitioners in pharmaceutical patent analysis. Each module of $\texttt{PatentAgent}$ demonstrates significant effectiveness with the updated algorithm and the synergistic design of $\texttt{PatentAgent}$ framework. $\textit{PA-Img2Mol}$ outperforms existing methods across CLEF, JPO, UOB, and USPTO patent benchmarks with an accuracy gain between 2.46% and 8.37% while $\textit{PA-CoreId}$ realizes accuracy improvement ranging from 7.15% to 7.62% on PatentNetML benchmark. Our code and dataset will be publicly available.

[Arxiv](https://arxiv.org/abs/2410.21312)
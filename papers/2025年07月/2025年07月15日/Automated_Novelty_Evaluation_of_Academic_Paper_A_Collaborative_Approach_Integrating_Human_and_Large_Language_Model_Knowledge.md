# 学术论文的自动化新颖性评估：一种结合人类与大型语言模型知识的协作方法

发布时间：2025年07月15日

`LLM应用

论文摘要：新颖性是学术论文同行评审中的关键评价标准。传统评估手段要么依赖专家主观判断，要么通过独特的参考文献组合来衡量，但两者均存在局限：专家知识有限，组合方法效果存疑，且独特的引用未必真正反映新颖性。大型语言模型（LLM）拥有海量知识储备，而人类专家则具备LLM不具备的独特判断力。因此，本研究旨在融合LLM的知识储备与人类专家的判断能力，克服现有新颖性评估的局限。学术论文最常见的新颖性体现在新方法的提出。本文提出了一种结合人类知识与LLM的新颖性评估方法，旨在帮助预训练语言模型（PLMs，如BERT等）预测论文的方法新颖性。具体而言，我们从同行评审报告中提取与论文新颖性相关的句子，并利用LLM对论文的方法部分进行总结，进而用于微调PLMs。此外，我们还设计了一种基于新型稀疏注意力机制的文本引导融合模块，以更高效地整合人类与LLM的知识。通过与大量基线方法的对比实验，我们证明了所提方法在性能上的显著优势。` `学术出版` `研究评估`

> Automated Novelty Evaluation of Academic Paper: A Collaborative Approach Integrating Human and Large Language Model Knowledge

# 摘要

> 新颖性是学术论文同行评审中的关键评价标准。传统评估手段要么依赖专家主观判断，要么通过独特的参考文献组合来衡量，但两者均存在局限：专家知识有限，组合方法效果存疑，且独特的引用未必真正反映新颖性。大型语言模型（LLM）拥有海量知识储备，而人类专家则具备LLM不具备的独特判断力。因此，本研究旨在融合LLM的知识储备与人类专家的判断能力，克服现有新颖性评估的局限。学术论文最常见的新颖性体现在新方法的提出。本文提出了一种结合人类知识与LLM的新颖性评估方法，旨在帮助预训练语言模型（PLMs，如BERT等）预测论文的方法新颖性。具体而言，我们从同行评审报告中提取与论文新颖性相关的句子，并利用LLM对论文的方法部分进行总结，进而用于微调PLMs。此外，我们还设计了一种基于新型稀疏注意力机制的文本引导融合模块，以更高效地整合人类与LLM的知识。通过与大量基线方法的对比实验，我们证明了所提方法在性能上的显著优势。

> Novelty is a crucial criterion in the peer review process for evaluating academic papers. Traditionally, it's judged by experts or measure by unique reference combinations. Both methods have limitations: experts have limited knowledge, and the effectiveness of the combination method is uncertain. Moreover, it's unclear if unique citations truly measure novelty. The large language model (LLM) possesses a wealth of knowledge, while human experts possess judgment abilities that the LLM does not possess. Therefore, our research integrates the knowledge and abilities of LLM and human experts to address the limitations of novelty assessment. The most common novelty in academic papers is the introduction of new methods. In this paper, we propose leveraging human knowledge and LLM to assist pretrained language models (PLMs, e.g. BERT etc.) in predicting the method novelty of papers. Specifically, we extract sentences related to the novelty of the academic paper from peer review reports and use LLM to summarize the methodology section of the academic paper, which are then used to fine-tune PLMs. In addition, we have designed a text-guided fusion module with novel Sparse-Attention to better integrate human and LLM knowledge. We compared the method we proposed with a large number of baselines. Extensive experiments demonstrate that our method achieves superior performance.

[Arxiv](https://arxiv.org/abs/2507.11330)
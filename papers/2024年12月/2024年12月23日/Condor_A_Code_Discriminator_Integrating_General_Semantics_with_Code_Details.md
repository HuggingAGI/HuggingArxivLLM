# Condor：融合通用语义与代码细节的代码判别器。

发布时间：2024年12月23日

`LLM应用` `软件工程` `代码生成`

> Condor: A Code Discriminator Integrating General Semantics with Code Details

# 摘要

> 大型语言模型（LLMs）在软件工程领域展现出了巨大潜力，但面对复杂需求时，生成正确代码仍具挑战。为提升生成代码的可靠性和稳定性，我们引入判别器从多个生成结果中筛选优质输出。当前，判别器主要分为两类：基于执行的判别器和非基于执行的判别器。前者因测试用例获取困难和安全问题而灵活性受限，后者虽更灵活，却难以捕捉代码细节的微小差异。为解决这一问题，本研究提出了Condor方法。首先，我们通过对比学习优化基础模型的代码表示，使其能够更好地反映代码细节的差异。其次，利用代码修改过程中的中间数据，进一步丰富判别器的训练数据，提升其对代码细节的辨别能力。实验结果表明，Condor在CodeNanoFix数据集上的判别性能显著优于其他判别器：Condor（1.3B）将DeepSeek-Coder（1.3B）的F1分数从67%提升到了73%。在判别LLM生成代码时，Condor（1.3B）和Condor（110M）分别将Meta-Llama-3.1-Instruct（70B）在CodeNanoFix数据集上的Pass@1分数从52.64%提升到了62.63%和59.64%。此外，Condor在MBPP和APPS数据集上也表现出强大的泛化能力。例如，在APPS数据集上，Condor（1.3B）将Meta-Llama-3.1-Instruct（70B）的Pass@1分数提升了147.05%。

> LLMs demonstrate significant potential across various software engineering tasks. However, they still face challenges in generating correct code on the first attempt when addressing complex requirements. Introducing a discriminator to select reliable outputs from multiple generated results is an effective way to enhance their reliability and stability. Currently, these discriminators fall into two categories: execution-based discriminators and non-execution-based discriminators. Execution-based discriminators face flexibility challenges due to difficulties in obtaining test cases and security concerns, while non-execution-based discriminators, although more flexible, struggle to capture subtle differences in code details. To maintain flexibility while improving the model's ability to capture fine-grained code details, this paper proposes Condor. We first design contrastive learning to optimize the code representations of the base model, enabling it to reflect differences in code details. Then, we leverage intermediate data from the code modification process to further enrich the discriminator's training data, enhancing its ability to discern code details. Experimental results indicate that on the subtle code difference dataset (i.e., CodeNanoFix), Condor significantly outperforms other discriminators in discriminative performance: Condor (1.3B) improves the discriminative F1 score of DeepSeek-Coder (1.3B) from 67% to 73%. In discriminating LLM-generated outputs, Condor (1.3B) and Condor (110M) raise the Pass@1 score of Meta-Llama-3.1-Instruct (70B) on the CodeNanoFix dataset from 52.64% to 62.63% and 59.64%, respectively. Moreover, Condor demonstrates strong generalization capabilities on the MBPP and APPS datasets. For example, Condor (1.3B) improves the Pass@1 of Meta-Llama-3.1-Instruct (70B) on the APPS dataset by 147.05%.

[Arxiv](https://arxiv.org/abs/2412.17429)
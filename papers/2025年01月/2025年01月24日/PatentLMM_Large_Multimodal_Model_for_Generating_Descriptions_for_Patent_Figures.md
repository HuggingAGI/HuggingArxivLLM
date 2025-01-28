# PatentLMM: 生成专利图描述的大型多模态模型

发布时间：2025年01月24日

`LLM应用

理由：这篇论文主要介绍了一个名为PatentLMM的多模态大型语言模型，该模型专门用于生成专利图描述。虽然论文涉及了多模态视觉编码器和LLaMA模型的微调，但其核心应用场景是利用大型语言模型（LLM）来自动化生成专利图描述。因此，这篇论文应归类为LLM应用。` `知识产权`

> PatentLMM: Large Multimodal Model for Generating Descriptions for Patent Figures

# 摘要

> # 摘要
在专利文件中，撰写全面且准确的技术图纸描述对于知识共享和知识产权保护至关重要。然而，这一任务的自动化长期被研究界忽视。为此，我们推出了PatentDesc-355K，这是一个包含约35.5万张专利图及其详细描述的大规模数据集，数据源自6万多份美国专利文件。此外，我们还提出了PatentLMM——一种专为生成高质量专利图描述而设计的多模态大型语言模型。PatentLMM由两个核心组件构成：(i) PatentMME，一种能够捕捉专利图独特结构的多模态视觉编码器；(ii) PatentLLaMA，一种基于大量专利数据微调的LLaMA模型。实验表明，专门为专利图设计的视觉编码器显著提升了模型性能，生成的描述更加连贯。PatentDesc-355K和PatentLMM为自动化理解专利图奠定了基础，推动了知识共享和专利文件起草的效率。我们已公开相关代码和数据。

> Writing comprehensive and accurate descriptions of technical drawings in patent documents is crucial to effective knowledge sharing and enabling the replication and protection of intellectual property. However, automation of this task has been largely overlooked by the research community. To this end, we introduce PatentDesc-355K, a novel large-scale dataset containing ~355K patent figures along with their brief and detailed textual descriptions extracted from more than 60K US patent documents. In addition, we propose PatentLMM - a novel multimodal large language model specifically tailored to generate high-quality descriptions of patent figures. Our proposed PatentLMM comprises two key components: (i) PatentMME, a specialized multimodal vision encoder that captures the unique structural elements of patent figures, and (ii) PatentLLaMA, a domain-adapted version of LLaMA fine-tuned on a large collection of patents. Extensive experiments demonstrate that training a vision encoder specifically designed for patent figures significantly boosts the performance, generating coherent descriptions compared to fine-tuning similar-sized off-the-shelf multimodal models. PatentDesc-355K and PatentLMM pave the way for automating the understanding of patent figures, enabling efficient knowledge sharing and faster drafting of patent documents. We make the code and data publicly available.

[Arxiv](https://arxiv.org/abs/2501.15074)
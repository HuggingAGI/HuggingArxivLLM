# 预判之眼与质疑之眼：用于大型语言模型输出幻觉检测的预训练不确定性量化模块

发布时间：2025年05月12日

`LLM理论

理由：论文探讨了大型语言模型（LLMs）的幻觉问题，并引入了不确定性量化（UQ）方法来评估模型输出的可靠性。作者设计了预训练的UQ头，作为LLMs的监督辅助模块，以提升模型捕捉不确定性的能力。这些研究属于模型的理论和机制层面，旨在改进模型的可靠性和检测能力，因此归类为LLM理论。` `人工智能`

> A Head to Predict and a Head to Question: Pre-trained Uncertainty Quantification Heads for Hallucination Detection in LLM Outputs

# 摘要

> 大型语言模型（LLMs）容易产生幻觉，即偶尔生成虚假或捏造的信息。这种现象极具挑战性，因为幻觉通常极具说服力，而用户往往缺乏检测工具。不确定性量化（UQ）为评估模型输出的可靠性提供了框架，帮助识别潜在幻觉。本研究引入了预训练的UQ头：LLMs的监督辅助模块，与无监督UQ方法相比，它们显著提升了捕捉不确定性的能力。这些模块的出色表现源于其设计中强大的Transformer架构以及从LLM注意力图中提取的具有信息量的特征。实验结果表明，这些UQ头高度鲁棒，并在声明级别幻觉检测中达到了最先进的性能，适用于域内和域外提示。此外，这些模块在未明确训练的语言上也表现出强大的泛化能力。我们为Mistral、Llama和Gemma 2等流行LLM系列预训练了一系列UQ头，并公开发布了代码和预训练的UQ头。

> Large Language Models (LLMs) have the tendency to hallucinate, i.e., to sporadically generate false or fabricated information. This presents a major challenge, as hallucinations often appear highly convincing and users generally lack the tools to detect them. Uncertainty quantification (UQ) provides a framework for assessing the reliability of model outputs, aiding in the identification of potential hallucinations. In this work, we introduce pre-trained UQ heads: supervised auxiliary modules for LLMs that substantially enhance their ability to capture uncertainty compared to unsupervised UQ methods. Their strong performance stems from the powerful Transformer architecture in their design and informative features derived from LLM attention maps. Experimental evaluation shows that these heads are highly robust and achieve state-of-the-art performance in claim-level hallucination detection across both in-domain and out-of-domain prompts. Moreover, these modules demonstrate strong generalization to languages they were not explicitly trained on. We pre-train a collection of UQ heads for popular LLM series, including Mistral, Llama, and Gemma 2. We publicly release both the code and the pre-trained heads.

[Arxiv](https://arxiv.org/abs/2505.08200)
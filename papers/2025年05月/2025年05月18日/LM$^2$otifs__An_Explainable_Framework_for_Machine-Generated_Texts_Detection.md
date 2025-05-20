# LM²otifs：揭示机器生成文本的可解释性框架

发布时间：2025年05月18日

`LLM应用` `文本生成` `作者身份验证`

> LM$^2$otifs : An Explainable Framework for Machine-Generated Texts Detection

# 摘要

> 大型语言模型在文本生成领域的卓越表现，给作者身份验证带来了重要挑战。尽管已有多种方法用于区分机器生成文本（MGT）与人类生成文本（HGT），但这些方法的可解释性仍有待提升。传统可解释性技术往往难以准确捕捉区分HGT与MGT的复杂词汇关系。为此，我们提出LM$^2$otifs，一种用于MGT检测的新颖可解释性框架。受概率图模型启发，我们为其有效性提供了理论支持。LM$^2$otifs框架结合可解释图神经网络，实现了检测准确性和可解释性的双重目标。该框架的工作流程分为三个主要阶段：首先，基于词汇共现将文本转化为图，以呈现词汇间的依赖关系；其次，通过图神经网络进行预测；最后，运用后验可解释性方法提取可解释的模式，提供从单个词汇到句法结构的多层级解释。在多个基准数据集上的实验结果表明，LM$^2$otifs的表现与现有方法相当。对提取的可解释模式的实证评估证实了其在区分HGT与MGT方面的有效性。此外，定性分析揭示了MGT特有的明显且可辨识的语义特征。

> The impressive ability of large language models to generate natural text across various tasks has led to critical challenges in authorship authentication. Although numerous detection methods have been developed to differentiate between machine-generated texts (MGT) and human-generated texts (HGT), the explainability of these methods remains a significant gap. Traditional explainability techniques often fall short in capturing the complex word relationships that distinguish HGT from MGT. To address this limitation, we present LM$^2$otifs, a novel explainable framework for MGT detection. Inspired by probabilistic graphical models, we provide a theoretical rationale for the effectiveness. LM$^2$otifs utilizes eXplainable Graph Neural Networks to achieve both accurate detection and interpretability. The LM$^2$otifs pipeline operates in three key stages: first, it transforms text into graphs based on word co-occurrence to represent lexical dependencies; second, graph neural networks are used for prediction; and third, a post-hoc explainability method extracts interpretable motifs, offering multi-level explanations from individual words to sentence structures. Extensive experiments on multiple benchmark datasets demonstrate the comparable performance of LM$^2$otifs. The empirical evaluation of the extracted explainable motifs confirms their effectiveness in differentiating HGT and MGT. Furthermore, qualitative analysis reveals distinct and visible linguistic fingerprints characteristic of MGT.

[Arxiv](https://arxiv.org/abs/2505.12507)
# # 摘要  
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年08月04日

`LLM应用

理由：这篇论文主要探讨了如何利用大型语言模型（如ChatGPT）生成伪标签，并结合人工审核来构建医疗领域的阿拉伯语情感分析数据集。研究重点在于模型的应用，特别是在医疗领域的数据标注和模型微调，属于LLM应用的范畴。` `情感分析`

> EHSAN: Leveraging ChatGPT in a Hybrid Framework for Arabic Aspect-Based Sentiment Analysis in Healthcare

# 摘要

> 阿拉伯语患者反馈分析面临两大挑战：方言多样性与方面级情感标签的稀缺性，这些因素限制了自动化评估的进展。为突破这一瓶颈，我们推出了EHSAN——一个创新的数据驱动混合管道，巧妙结合ChatGPT的伪标签与定向人工审核，成功构建了首个专为医疗领域设计的可解释阿拉伯语基于方面情感分析数据集。每条句子均标注了具体方面与情感倾向（正面、负面或中性），形成了一个与医疗主题深度契合的开创性数据集，并为每个标签提供了ChatGPT生成的解释说明，确保标注过程的透明度与可解释性。为了探究标注质量对模型性能的影响，我们精心设计了三个版本的训练数据：全部标签经人工审核的完全监督集、50%标签经人工审核的半监督集，以及仅包含机器生成标签的无监督集。通过在这些数据集上对两个Transformer模型进行微调，我们分别针对方面识别与情感分类进行了深入研究。实验结果令人振奋：我们的阿拉伯语专用模型即使在最小人工干预的情况下也表现优异，仅使用ChatGPT生成标签时性能仅小幅下降。此外，减少方面类别数量显著提升了各类分类指标。这些成果充分证明了我们在医疗领域中结合大型语言模型标注与人类专业知识的有效且可扩展的阿拉伯语基于方面情感分析方法。未来，我们将致力于跨医院的泛化研究、优化提示工程以及开发可解释的数据驱动建模方法。

> Arabic-language patient feedback remains under-analysed because dialect diversity and scarce aspect-level sentiment labels hinder automated assessment. To address this gap, we introduce EHSAN, a data-centric hybrid pipeline that merges ChatGPT pseudo-labelling with targeted human review to build the first explainable Arabic aspect-based sentiment dataset for healthcare. Each sentence is annotated with an aspect and sentiment label (positive, negative, or neutral), forming a pioneering Arabic dataset aligned with healthcare themes, with ChatGPT-generated rationales provided for each label to enhance transparency. To evaluate the impact of annotation quality on model performance, we created three versions of the training data: a fully supervised set with all labels reviewed by humans, a semi-supervised set with 50% human review, and an unsupervised set with only machine-generated labels. We fine-tuned two transformer models on these datasets for both aspect and sentiment classification. Experimental results show that our Arabic-specific model achieved high accuracy even with minimal human supervision, reflecting only a minor performance drop when using ChatGPT-only labels. Reducing the number of aspect classes notably improved classification metrics across the board. These findings demonstrate an effective, scalable approach to Arabic aspect-based sentiment analysis (SA) in healthcare, combining large language model annotation with human expertise to produce a robust and explainable dataset. Future directions include generalisation across hospitals, prompt refinement, and interpretable data-driven modelling.

[Arxiv](https://arxiv.org/abs/2508.02574)
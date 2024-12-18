# 检测文档级别的机器生成的释义内容：模仿人类写作风格并涉及话语特征

发布时间：2024年12月17日

`LLM应用` `内容检测`

> Detecting Document-level Paraphrased Machine Generated Content: Mimicking Human Writing Style and Involving Discourse Features

# 摘要

> 大型语言模型（LLMs）高质量 API 的出现，推动了机器生成内容（MGC）的大量涌现，同时也带来了诸如学术抄袭、错误信息传播等难题。现有的 MGC 检测手段往往只着眼于表层信息，而忽视了隐含及结构特征。这就导致它们容易被表层的句子模式所蒙蔽，尤其是在面对较长文本和经过改写的文本时。
    为应对这些挑战，我们引入了全新的方法和数据集。除了公开可用的 Plagbench 数据集，我们借助 GPT 和话语改写工具 DIPPER，通过对原始版本的拓展，开发出了改写后的长格式问答（paraLFQA）和改写后的写作提示（paraWP）数据集。为解决检测高度相似改写文本的难题，我们提出了 MhBART 模型，这是一种编码器 - 解码器模型，旨在模仿人类写作风格，并融入了新颖的差异评分机制。该模型表现优于强大的分类器基线，能够识别出具有欺骗性的句子模式。为了在文档层面更好地捕捉较长文本的结构，我们提出了 DTransformer 模型，它通过 PDTB 预处理进行话语分析来编码结构特征。与最先进的方法相比，在两个数据集上均取得了显著的性能提升：在 paraLFQA 上绝对提升 15.5％，在 paraWP 上绝对提升 4％，在 M4 上绝对提升 1.5％。

> The availability of high-quality APIs for Large Language Models (LLMs) has facilitated the widespread creation of Machine-Generated Content (MGC), posing challenges such as academic plagiarism and the spread of misinformation. Existing MGC detectors often focus solely on surface-level information, overlooking implicit and structural features. This makes them susceptible to deception by surface-level sentence patterns, particularly for longer texts and in texts that have been subsequently paraphrased.
  To overcome these challenges, we introduce novel methodologies and datasets. Besides the publicly available dataset Plagbench, we developed the paraphrased Long-Form Question and Answer (paraLFQA) and paraphrased Writing Prompts (paraWP) datasets using GPT and DIPPER, a discourse paraphrasing tool, by extending artifacts from their original versions. To address the challenge of detecting highly similar paraphrased texts, we propose MhBART, an encoder-decoder model designed to emulate human writing style while incorporating a novel difference score mechanism. This model outperforms strong classifier baselines and identifies deceptive sentence patterns. To better capture the structure of longer texts at document level, we propose DTransformer, a model that integrates discourse analysis through PDTB preprocessing to encode structural features. It results in substantial performance gains across both datasets -- 15.5\% absolute improvement on paraLFQA, 4\% absolute improvement on paraWP, and 1.5\% absolute improvement on M4 compared to SOTA approaches.

[Arxiv](https://arxiv.org/abs/2412.12679)
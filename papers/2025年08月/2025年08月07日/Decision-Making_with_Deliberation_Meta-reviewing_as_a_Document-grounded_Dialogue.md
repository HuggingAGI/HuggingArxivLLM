# 决策中的深思熟虑：元审阅是一种基于文档的对话

发布时间：2025年08月07日

`Agent` `学术出版` `人工智能`

> Decision-Making with Deliberation: Meta-reviewing as a Document-grounded Dialogue

# 摘要

> # 元审稿  
元审稿是同行评审的最后关键环节，决定论文是否被推荐接收。传统研究将元审稿视为对评审意见的总结，但我们发现它更是一个需要权衡各方观点并结合更广泛背景的决策过程。已有研究表明，对话代理能够有效辅助此类决策场景。基于此，我们探索了开发能够有效协助元审稿人的对话代理所面临的挑战。  
我们首先解决了训练对话代理时的数据不足问题，通过基于大型语言模型（LLMs）的自完善策略生成合成数据，显著提升了对话内容的专业相关性。实验结果表明，这种方法生成的合成数据质量更高，为训练元审稿助手提供了宝贵资源。接着，我们利用这些数据训练专门针对元审稿场景的对话代理，发现其表现优于现有现成的LLM基助手。最后，我们在实际的元审稿场景中应用这些代理，验证了它们能够有效提升元审稿的效率。ootnote{代码和数据：https://github.com/UKPLab/arxiv2025-meta-review-as-dialog}

> Meta-reviewing is a pivotal stage in the peer-review process, serving as the final step in determining whether a paper is recommended for acceptance. Prior research on meta-reviewing has treated this as a summarization problem over review reports. However, complementary to this perspective, meta-reviewing is a decision-making process that requires weighing reviewer arguments and placing them within a broader context. Prior research has demonstrated that decision-makers can be effectively assisted in such scenarios via dialogue agents. In line with this framing, we explore the practical challenges for realizing dialog agents that can effectively assist meta-reviewers. Concretely, we first address the issue of data scarcity for training dialogue agents by generating synthetic data using Large Language Models (LLMs) based on a self-refinement strategy to improve the relevance of these dialogues to expert domains. Our experiments demonstrate that this method produces higher-quality synthetic data and can serve as a valuable resource towards training meta-reviewing assistants. Subsequently, we utilize this data to train dialogue agents tailored for meta-reviewing and find that these agents outperform \emph{off-the-shelf} LLM-based assistants for this task. Finally, we apply our agents in real-world meta-reviewing scenarios and confirm their effectiveness in enhancing the efficiency of meta-reviewing.\footnote{Code and Data: https://github.com/UKPLab/arxiv2025-meta-review-as-dialog

[Arxiv](https://arxiv.org/abs/2508.05283)
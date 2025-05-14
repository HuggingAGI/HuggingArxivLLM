# Re$^2$: 一个支持全流程同行评审与多轮反驳讨论的一致性数据集

发布时间：2025年05月12日

`LLM应用` `学术出版` `人工智能`

> Re$^2$: A Consistency-ensured Dataset for Full-stage Peer Review and Multi-turn Rebuttal Discussions

# 摘要

> 同行评审是AI等科学领域取得进步的关键环节，但投稿量激增给评审系统带来了巨大压力，导致评审人员短缺和评审质量下降。除了研究热度的攀升，这种超负荷现象的另一个关键原因在于低质量稿件的反复提交，这主要是因为缺乏有效的工具供作者在投稿前自我评估其作品。大型语言模型（LLMs）在协助作者和评审方面展现出巨大潜力，但其性能从根本上受限于同行评审数据的质量。然而，现有的同行评审数据集面临三大主要限制：（1）数据多样性不足，（2）由于使用修订版而非初始投稿，导致数据不一致且质量较低，（3）对涉及反驳和评审与作者互动的任务支持不足。为了解决这些挑战，我们引入了最大的一致性保障的同行评审和反驳数据集Re^2，该数据集包含来自24个会议和21个工作坊的19,926份初始投稿、70,668条评论和53,818份反驳，所有数据均来自OpenReview。此外，我们将反驳和讨论阶段构建成一个多轮对话范式，以支持传统的静态评审任务和动态交互式的LLM助手，为作者润色稿件提供更具实用性的指导，同时帮助缓解日益加重的评审负担。我们的数据和代码可在https://anonymous.4open.science/r/ReviewBench_anon/获取。

> Peer review is a critical component of scientific progress in the fields like AI, but the rapid increase in submission volume has strained the reviewing system, which inevitably leads to reviewer shortages and declines review quality. Besides the growing research popularity, another key factor in this overload is the repeated resubmission of substandard manuscripts, largely due to the lack of effective tools for authors to self-evaluate their work before submission. Large Language Models (LLMs) show great promise in assisting both authors and reviewers, and their performance is fundamentally limited by the quality of the peer review data. However, existing peer review datasets face three major limitations: (1) limited data diversity, (2) inconsistent and low-quality data due to the use of revised rather than initial submissions, and (3) insufficient support for tasks involving rebuttal and reviewer-author interactions. To address these challenges, we introduce the largest consistency-ensured peer review and rebuttal dataset named Re^2, which comprises 19,926 initial submissions, 70,668 review comments, and 53,818 rebuttals from 24 conferences and 21 workshops on OpenReview. Moreover, the rebuttal and discussion stage is framed as a multi-turn conversation paradigm to support both traditional static review tasks and dynamic interactive LLM assistants, providing more practical guidance for authors to refine their manuscripts and helping alleviate the growing review burden. Our data and code are available in https://anonymous.4open.science/r/ReviewBench_anon/.

[Arxiv](https://arxiv.org/abs/2505.07920)
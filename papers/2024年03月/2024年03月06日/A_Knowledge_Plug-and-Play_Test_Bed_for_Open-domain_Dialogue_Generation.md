# 我们构建了一个针对开放领域对话生成的“知识即插即用”测试平台，旨在便捷地探究和验证各类知识在对话生成任务中的应用效果。

发布时间：2024年03月06日

`Agent`

> A Knowledge Plug-and-Play Test Bed for Open-domain Dialogue Generation

# 摘要

> 本研究关注的是创建能借助挖掘出的支持性知识与人流畅对话的智能聊天系统，即使在大型语言模型盛行的时代，实时检索最新知识辅助回应生成仍具有重要价值。过往研究表明，单一来源的知识对提升对话质量和响应生成效果有显著作用，然而针对多来源支持知识检索能力的评估数据集却尚未面世。此外，以往的研究通常假设模型在训练和测试阶段接触到的知识来源是相同的，这种不切实际的前提无疑束缚了模型的发展，毕竟在模型训练完成后，还可能涌现出新的知识来源。因此，本文推出了高品质基准——多源版维基巫师（Ms.WoW），其包含经过精心筛选、在话语层面精确对应并按来源分类的多源对话知识，可用于评估和训练多源知识选择及响应生成能力。同时，我们还提出了一个新颖的对话知识即插即用挑战，旨在测试在零样本条件下，已训练好的对话模型如何运用未曾接触过的全新知识来源生成高质量回应。

> Knowledge-based, open-domain dialogue generation aims to build chit-chat systems that talk to humans using mined support knowledge. Many types and sources of knowledge have previously been shown to be useful as support knowledge. Even in the era of large language models, response generation grounded in knowledge retrieved from additional up-to-date sources remains a practically important approach. While prior work using single-source knowledge has shown a clear positive correlation between the performances of knowledge selection and response generation, there are no existing multi-source datasets for evaluating support knowledge retrieval. Further, prior work has assumed that the knowledge sources available at test time are the same as during training. This unrealistic assumption unnecessarily handicaps models, as new knowledge sources can become available after a model is trained. In this paper, we present a high-quality benchmark named multi-source Wizard of Wikipedia (Ms.WoW) for evaluating multi-source dialogue knowledge selection and response generation. Unlike existing datasets, it contains clean support knowledge, grounded at the utterance level and partitioned into multiple knowledge sources. We further propose a new challenge, dialogue knowledge plug-and-play, which aims to test an already trained dialogue model on using new support knowledge from previously unseen sources in a zero-shot fashion.

[Arxiv](https://arxiv.org/abs/2403.03496)
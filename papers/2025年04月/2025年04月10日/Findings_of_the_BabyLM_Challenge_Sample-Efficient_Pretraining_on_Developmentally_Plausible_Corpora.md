# # 研究发现：BabyLM挑战赛发现：在发展合理语料库上的高效样本预训练

发布时间：2025年04月10日

`LLM应用

理由：论文讨论了如何在有限的数据预算下优化语言模型的训练效果，探讨了不同的训练策略和架构选择，属于LLM的应用层面。` `机器学习`

> Findings of the BabyLM Challenge: Sample-Efficient Pretraining on Developmentally Plausible Corpora

# 摘要

> 儿童仅需不到一亿字的输入即可掌握语言，而大型语言模型的数据效率则低得多。它们通常需要多出三个或四个数量级的数据量，即便如此，在许多评估任务中仍无法达到人类的水平。这些对资源的高强度需求限制了研究人员训练新模型的能力，同时也阻碍了将现有模型作为符合认知发展规律的认知模型的可能性。

BabyLM挑战赛是一个集体努力的项目，参与者在固定的数据预算下竞争优化语言模型的训练效果。参赛作品将在针对语法能力、下游任务表现和泛化能力的多项评估任务上进行比较。参与者可以选择参加最多三个赛道，赛道间的数据限制逐步放宽。

从30多份参赛作品中，我们提炼出了如何最佳训练数据高效语言模型的具体建议，以及未来研究应重点关注（或可能不应重点关注）的方向。采用LTG-BERT架构（Samuel等人，2023）的获胜作品在训练数据量仅为万亿级别时就表现优异。其他参赛作品则通过较短的输入序列训练或在预训练教师模型上训练学生模型取得了优异成绩。基于课程的学习方法尽管占据了大量参赛作品，但总体效果不佳，尽管其中一些方法显示出了小幅改进。

> Children can acquire language from less than 100 million words of input. Large language models are far less data-efficient: they typically require 3 or 4 orders of magnitude more data and still do not perform as well as humans on many evaluations. These intensive resource demands limit the ability of researchers to train new models and use existing models as developmentally plausible cognitive models. The BabyLM Challenge is a communal effort in which participants compete to optimize language model training on a fixed data budget. Submissions are compared on various evaluation tasks targeting grammatical ability, downstream task performance, and generalization. Participants can submit to up to three tracks with progressively looser data restrictions. From over 30 submissions, we extract concrete recommendations on how best to train data-efficient language models, and on where future efforts should (and perhaps should not) focus. The winning submissions using the LTG-BERT architecture (Samuel et al., 2023) outperformed models trained on trillions of words. Other submissions achieved strong results through training on shorter input sequences or training a student model on a pretrained teacher. Curriculum learning attempts, which accounted for a large number of submissions, were largely unsuccessful, though some showed modest improvements.

[Arxiv](https://arxiv.org/abs/2504.08165)
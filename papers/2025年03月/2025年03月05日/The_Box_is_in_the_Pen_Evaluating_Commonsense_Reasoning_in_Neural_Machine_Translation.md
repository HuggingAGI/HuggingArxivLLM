# 箱子在笔里：神经机器翻译中的常识推理评估

发布时间：2025年03月05日

`LLM应用` `人工智能`

> The Box is in the Pen: Evaluating Commonsense Reasoning in Neural Machine Translation

# 摘要

> 神经机器翻译是否能产出符合常识的译文？本文提出了一套测试套件，用于评估神经机器翻译的常识推理能力。该测试套件包含三个测试集，涵盖了需要借助常识知识解决的词汇和无上下文/有上下文句法歧义。我们手动创建了1,200个三元组，每个三元组包含一个源句和两个对比译文，涉及7种不同的常识类型。在大规模语料库上预训练的语言模型（如BERT、GPT-2）在本测试套件的目标译文上的常识推理准确率低于72%。我们在该测试套件上进行了大量实验，以评估神经机器翻译中的常识推理，并研究影响该能力的因素。实验和分析表明，神经机器翻译在三种歧义类型的常识推理方面表现不佳，推理准确率为60.1%，推理一致性仅为31%。构建的常识测试套件可在https://github.com/tjunlp-lab/CommonMT获取。

> Does neural machine translation yield translations that are congenial with common sense? In this paper, we present a test suite to evaluate the commonsense reasoning capability of neural machine translation. The test suite consists of three test sets, covering lexical and contextless/contextual syntactic ambiguity that requires commonsense knowledge to resolve. We manually create 1,200 triples, each of which contain a source sentence and two contrastive translations, involving 7 different common sense types. Language models pretrained on large-scale corpora, such as BERT, GPT-2, achieve a commonsense reasoning accuracy of lower than 72% on target translations of this test suite. We conduct extensive experiments on the test suite to evaluate commonsense reasoning in neural machine translation and investigate factors that have impact on this capability. Our experiments and analyses demonstrate that neural machine translation performs poorly on commonsense reasoning of the three ambiguity types in terms of both reasoning accuracy (60.1%) and reasoning consistency (31%). The built commonsense test suite is available at https://github.com/tjunlp-lab/CommonMT.

[Arxiv](https://arxiv.org/abs/2503.03308)
# 大型语言模型的概率无法区分语言的可能与不可能

发布时间：2025年09月18日

`LLM理论` `基础理论`

> Large Language Model probabilities cannot distinguish between possible and impossible language

# 摘要

> 大型语言模型（LLMs）有一项颇具争议的能力测试：辨别“可能语言”与“不可能语言”。尽管有证据显示模型对语法层面“不可能语言”的边界有所感知，但测试材料的合理性让这类证据饱受质疑。本研究借助模型内部表征，直接探究LLMs如何区分“合语法”与“不合语法”。在新构建的基准实验中，我们从4个模型提取概率值，计算最小对惊讶度差异，将合语法句子的概率与四类句子对比：（i）低频合语法句、（ii）不合语法句、（iii）语义异常句、（iv）语用异常句。我们推测，若字符串概率可作为语法边界的“代理”，那么不合语法句在所有语言违规条件中应表现出独特的惊讶度峰值。但结果却显示：不合语法提示并无专属惊讶度特征，反而是语义和语用异常句始终呈现更高的惊讶度。这表明，概率并非模型句法知识内部表征的可靠代理。因此，关于模型能区分可能与不可能语言的说法，需通过其他方法验证。

> A controversial test for Large Language Models concerns the ability to discern possible from impossible language. While some evidence attests to the models' sensitivity to what crosses the limits of grammatically impossible language, this evidence has been contested on the grounds of the soundness of the testing material. We use model-internal representations to tap directly into the way Large Language Models represent the 'grammatical-ungrammatical' distinction. In a novel benchmark, we elicit probabilities from 4 models and compute minimal-pair surprisal differences, juxtaposing probabilities assigned to grammatical sentences to probabilities assigned to (i) lower frequency grammatical sentences, (ii) ungrammatical sentences, (iii) semantically odd sentences, and (iv) pragmatically odd sentences. The prediction is that if string-probabilities can function as proxies for the limits of grammar, the ungrammatical condition will stand out among the conditions that involve linguistic violations, showing a spike in the surprisal rates. Our results do not reveal a unique surprisal signature for ungrammatical prompts, as the semantically and pragmatically odd conditions consistently show higher surprisal. We thus demonstrate that probabilities do not constitute reliable proxies for model-internal representations of syntactic knowledge. Consequently, claims about models being able to distinguish possible from impossible language need verification through a different methodology.

[Arxiv](https://arxiv.org/abs/2509.15114)
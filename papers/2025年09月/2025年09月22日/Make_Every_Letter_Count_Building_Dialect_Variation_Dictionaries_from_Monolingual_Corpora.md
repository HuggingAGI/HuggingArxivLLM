# 让每个字母都发挥作用：基于单语语料库构建方言变体词典

发布时间：2025年09月22日

`LLM应用` `基础理论`

> Make Every Letter Count: Building Dialect Variation Dictionaries from Monolingual Corpora

# 摘要

> 由于缺乏标准拼写系统，方言存在显著的变异。与此同时，大型语言模型（LLMs）处理方言的能力研究仍较为匮乏。为填补这一空白，我们以巴伐利亚方言为案例，通过考察LLMs对不同词性方言术语的识别与翻译表现，探究其词汇层面的方言理解能力。为此，我们提出了DiaLemma——一个仅基于单语数据构建方言变异词典的新型标注框架，并据此编制了包含10万条人工标注的德语-巴伐利亚语词对的基准数据集。我们评估了九款最先进的LLMs对巴伐利亚方言词汇的判断能力：判断其是否为给定德语词元的方言翻译、屈折变体或无关形式。研究结果显示，LLMs在名词和词汇相似的词对上表现最优，而在区分直接翻译与屈折变体时最为吃力。值得注意的是，提供示例用法作为额外上下文虽能提升翻译性能，却会削弱模型识别方言变体的能力。本研究揭示了LLMs在处理方言拼写变异时的局限性，并强调未来需开展针对方言的模型适配研究。

> Dialects exhibit a substantial degree of variation due to the lack of a standard orthography. At the same time, the ability of Large Language Models (LLMs) to process dialects remains largely understudied. To address this gap, we use Bavarian as a case study and investigate the lexical dialect understanding capability of LLMs by examining how well they recognize and translate dialectal terms across different parts-of-speech. To this end, we introduce DiaLemma, a novel annotation framework for creating dialect variation dictionaries from monolingual data only, and use it to compile a ground truth dataset consisting of 100K human-annotated German-Bavarian word pairs. We evaluate how well nine state-of-the-art LLMs can judge Bavarian terms as dialect translations, inflected variants, or unrelated forms of a given German lemma. Our results show that LLMs perform best on nouns and lexically similar word pairs, and struggle most in distinguishing between direct translations and inflected variants. Interestingly, providing additional context in the form of example usages improves the translation performance, but reduces their ability to recognize dialect variants. This study highlights the limitations of LLMs in dealing with orthographic dialect variation and emphasizes the need for future work on adapting LLMs to dialects.

[Arxiv](https://arxiv.org/abs/2509.17855)
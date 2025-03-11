# 长文本生成中的迷失中间现象：合成数据集、评估框架与缓解方法

发布时间：2025年03月09日

`LLM应用` `生成模型`

> Lost-in-the-Middle in Long-Text Generation: Synthetic Dataset, Evaluation Framework, and Mitigation

# 摘要

> 现有长文本生成方法主要关注从短输入生成长文本，却忽视了长输入与长输出任务的巨大潜力。这些任务在实际应用中需求广泛，却长期缺乏基准支持。随着输入长度增加，现有方法难免出现“中间迷失”现象。本文首先推出长输入长输出基准（LongInOutBench），包含合成数据集与全面评估框架，填补了这一空白。我们随后开发了检索增强长文本生成器（RAL-Writer），通过检索并重述重要却被忽视的内容，并借助显式提示，有效缓解了“中间迷失”问题。最后，我们利用LongInOutBench对RAL-Writer与同类基线进行了对比评估，结果充分证明了我们的方法优势。代码已开源：https://github.com/OnlyAR/RAL-Writer。


> Existing long-text generation methods primarily concentrate on producing lengthy texts from short inputs, neglecting the long-input and long-output tasks. Such tasks have numerous practical applications while lacking available benchmarks. Moreover, as the input grows in length, existing methods inevitably encounter the "lost-in-the-middle" phenomenon. In this paper, we first introduce a Long Input and Output Benchmark (LongInOutBench), including a synthetic dataset and a comprehensive evaluation framework, addressing the challenge of the missing benchmark. We then develop the Retrieval-Augmented Long-Text Writer (RAL-Writer), which retrieves and restates important yet overlooked content, mitigating the "lost-in-the-middle" issue by constructing explicit prompts. We finally employ the proposed LongInOutBench to evaluate our RAL-Writer against comparable baselines, and the results demonstrate the effectiveness of our approach. Our code has been released at https://github.com/OnlyAR/RAL-Writer.

[Arxiv](https://arxiv.org/abs/2503.06868)
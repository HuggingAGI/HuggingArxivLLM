# 探索LLMs对社会人口统计学条件改写的鲁棒性

发布时间：2025年01月14日

`LLM理论

**理由**：这篇论文主要探讨了大型语言模型（LLMs）在不同语言变体领域的可靠性问题，并提出了对语言模型推理能力的结构化可靠性测试方法。研究涉及对LLMs在复杂语言场景中的推理能力进行评估，并分析了特定人口统计改写对模型性能的影响。这些内容属于对LLMs的理论研究和性能评估，因此归类为LLM理论。` `社会人口学`

> Exploring Robustness of LLMs to Sociodemographically-Conditioned Paraphrasing

# 摘要

> 大型语言模型（LLMs）在各类NLP任务中表现卓越，但其在不同语言变体领域的可靠性仍存疑虑。尽管已有研究提出了针对局部对抗攻击的鲁棒性评估方法，但我们仍需构建对不同语言风格无偏见的全局鲁棒模型。为此，我们采用更广泛的方法，探索社会人口维度上的多样化变体，对语言模型的推理能力进行结构化可靠性测试。我们扩展了SocialIQA数据集，生成了基于社会人口风格的多组改写集。评估旨在深入探究LLMs在以下两方面的能力：（a）通过设计的提示生成人口统计改写的能力；（b）在复杂现实语言场景中的推理能力。我们还通过困惑度、可解释性及改写集的ATOMIC性能等指标，对这些集上的LLMs进行细粒度可靠性分析。结果表明，特定人口统计的改写显著影响语言模型的性能，语言变体的微妙之处仍是重大挑战。我们将公开代码和数据集，以便复现和未来研究。

> Large Language Models (LLMs) have shown impressive performance in various NLP tasks. However, there are concerns about their reliability in different domains of linguistic variations. Many works have proposed robustness evaluation measures for local adversarial attacks, but we need globally robust models unbiased to different language styles. We take a broader approach to explore a wider range of variations across sociodemographic dimensions to perform structured reliability tests on the reasoning capacity of language models. We extend the SocialIQA dataset to create diverse paraphrased sets conditioned on sociodemographic styles. The assessment aims to provide a deeper understanding of LLMs in (a) their capability of generating demographic paraphrases with engineered prompts and (b) their reasoning capabilities in real-world, complex language scenarios. We also explore measures such as perplexity, explainability, and ATOMIC performance of paraphrases for fine-grained reliability analysis of LLMs on these sets. We find that demographic-specific paraphrasing significantly impacts the performance of language models, indicating that the subtleties of language variations remain a significant challenge. The code and dataset will be made available for reproducibility and future research.

[Arxiv](https://arxiv.org/abs/2501.08276)
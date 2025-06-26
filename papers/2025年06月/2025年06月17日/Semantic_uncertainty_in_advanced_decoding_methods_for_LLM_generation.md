# LLM生成中高级解码方法的语义不确定性

发布时间：2025年06月17日

`LLM应用` `问答系统`

> Semantic uncertainty in advanced decoding methods for LLM generation

# 摘要

> 本研究深入探讨了大型语言模型（LLM）输出在不同解码方法下的语义不确定性，重点关注了推测采样和思维链（CoT）解码等新兴技术。通过在问答、摘要和代码生成任务上的实验，我们揭示了不同解码策略对模型输出多样性和可靠性的双重影响。研究发现，思维链（CoT）解码在语义多样性上表现更优，且预测熵较低，表明结构化探索能够带来更自信且准确的输出。这一结论得到了代码生成任务中Pass@2率显著提升48.8%的支持，尽管其与参考解决方案的对齐度较低。在摘要任务中，推测采样表现尤为出色，不仅ROUGE分数更优，同时保持了适度的语义多样性。我们的研究结果挑战了传统关于语言模型输出中多样性与准确性之间权衡的假设，证明了结构良好的解码方法可以在保持或提升输出质量的同时增加语义探索。这些发现对语言模型在实际应用中的部署具有重要意义，尤其是在需要可靠性和多样化解决方案生成的场景中。

> This study investigates semantic uncertainty in large language model (LLM) outputs across different decoding methods, focusing on emerging techniques like speculative sampling and chain-of-thought (CoT) decoding. Through experiments on question answering, summarization, and code generation tasks, we analyze how different decoding strategies affect both the diversity and reliability of model outputs. Our findings reveal that while CoT decoding demonstrates higher semantic diversity, it maintains lower predictive entropy, suggesting that structured exploration can lead to more confident and accurate outputs. This is evidenced by a 48.8% improvement in code generation Pass@2 rates, despite lower alignment with reference solutions. For summarization tasks, speculative sampling proved particularly effective, achieving superior ROUGE scores while maintaining moderate semantic diversity. Our results challenge conventional assumptions about trade-offs between diversity and accuracy in language model outputs, demonstrating that properly structured decoding methods can increase semantic exploration while maintaining or improving output quality. These findings have significant implications for deploying language models in practical applications where both reliability and diverse solution generation are crucial.

[Arxiv](https://arxiv.org/abs/2506.17296)
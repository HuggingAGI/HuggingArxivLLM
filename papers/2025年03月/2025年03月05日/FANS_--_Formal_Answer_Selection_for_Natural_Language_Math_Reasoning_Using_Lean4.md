# FANS——基于Lean4的自然语言数学推理中的形式化答案选择

发布时间：2025年03月05日

`LLM应用`

> FANS -- Formal Answer Selection for Natural Language Math Reasoning Using Lean4

# 摘要

> 大型语言模型（LLMs）在文本生成、分类和问答等任务中表现出令人惊叹的能力，但其推理能力仍存在诸多争议。自然语言的固有模糊性限制了LLMs的可验证推理能力，导致其答案缺乏连贯性和可信度。针对这一问题，我们提出了一个名为FANS的创新框架：使用Lean4进行自然语言数学推理中的正式答案选择。据我们所知，这是首个利用Lean4提升LLMs自然语言数学推理能力的框架。

具体而言，FANS框架的工作流程如下：首先将自然语言数学问题和LLMs生成的答案转化为Lean4定理陈述，然后利用Lean4证明器进行证明并验证。最后，基于FL结果辅助答案选择。通过为正确答案提供计算机可验证的解决方案，FANS不仅增强了LLMs的数学推理能力，还为答案选择提供了一种超越传统奖励模型的创新方法。

实验结果表明，FANS框架在MATH-500数据集上可将奖励模型增强的LLMs准确率提升最多1.91%，在AMC-23上提升最多8.33%。在数论等Lean4擅长的领域，甚至能选出所有正确答案。定性分析显示，FANS框架使自然语言结果正式地由Lean4证明支持。作为该领域的开创性工作，我们将开源所有模型和数据集，以推动相关研究的进一步发展。

> Large Language Models (LLMs) have displayed astonishing abilities in various tasks, especially in text generation, classification, question answering, etc. However, the reasoning ability of LLMs still faces many debates. The inherent ambiguity of Natural Language (NL) limits LLMs' ability to perform verifiable reasoning, making its answers lack coherence and trustworthy support. To tackle the above problems, we propose a novel framework named FANS: Formal ANswer Selection for Natural Language Math Reasoning Using Lean4. To the best of our knowledge, it is the first framework that utilizes Lean4 to enhance LLMs' NL math reasoning ability. In particular, given an NL math question and LLM-generated answers, FANS first translates it into Lean4 theorem statements. Then it tries to prove it using a Lean4 prover and verify it by Lean4. Finally, it uses the FL result to assist in answer selection. It enhances LLMs' NL math ability in providing a computer-verifiable solution for its correct answer and proposes an alternative method for answer selection beyond the reward model. Extensive experiments indicate the effectiveness of our framework. It can improve the accuracy rate of reward model enhanced LLMs in the MATH-500 dataset by at most 1.91% and AMC-23 by at most 8.33% on strong reward-model baselines. In some particular fields like number theory that Lean4 experts in, we can even select all correct solutions. The qualitative analysis also shows our framework can make NL results formally backed by Lean4 proofs. As a pioneering work in the corresponding field, we will open-source all our models and datasets to further boost the development of the field.

[Arxiv](https://arxiv.org/abs/2503.03238)
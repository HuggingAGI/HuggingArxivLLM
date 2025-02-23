# MM-Verify：借助链式思维验证提升多模态推理能力

发布时间：2025年02月18日

`LLM应用` `多模态` `推理系统`

> MM-Verify: Enhancing Multimodal Reasoning with Chain-of-Thought Verification

# 摘要

> 根据测试时缩放（Test-Time Scaling），结合外部慢思考（External Slow-Thinking）与验证机制已被证明能显著提升大型语言模型（LLMs）的多轮推理能力。然而，在多模态（MM）领域，目前仍缺乏一个强大的MM-Verifier。本文中，我们引入了MM-Verifier和MM-Reasoner，通过更长的推理和更稳健的验证来增强多模态推理能力。首先，我们提出了一种两步式的MM验证数据合成方法，该方法结合了基于模拟的树形搜索与验证，并采用拒绝采样生成高质量的思维链（Chain-of-Thought, COT）数据。随后，我们利用这些数据对验证模型MM-Verifier进行微调。此外，我们还提出了一种更高效的方法来合成MMCOT数据，弥合了文本推理与多模态推理之间的差距。合成的数据被用于对MM-Reasoner进行微调。我们的MM-Verifier在MathCheck、MathVista和MathVerse基准测试中表现优于所有大型模型。此外，MM-Reasoner展现出强大的有效性和可扩展性，其性能随着数据量的增加而提升。最后，将MM-Reasoner与MM-Verifier结合使用时，我们的方法在MathVista上达到了65.3的准确率，超越了GPT-4o（63.8）的表现，采用了12次 rollout，展现出优异的性能。

> According to the Test-Time Scaling, the integration of External Slow-Thinking with the Verify mechanism has been demonstrated to enhance multi-round reasoning in large language models (LLMs). However, in the multimodal (MM) domain, there is still a lack of a strong MM-Verifier. In this paper, we introduce MM-Verifier and MM-Reasoner to enhance multimodal reasoning through longer inference and more robust verification. First, we propose a two-step MM verification data synthesis method, which combines a simulation-based tree search with verification and uses rejection sampling to generate high-quality Chain-of-Thought (COT) data. This data is then used to fine-tune the verification model, MM-Verifier. Additionally, we present a more efficient method for synthesizing MMCOT data, bridging the gap between text-based and multimodal reasoning. The synthesized data is used to fine-tune MM-Reasoner. Our MM-Verifier outperforms all larger models on the MathCheck, MathVista, and MathVerse benchmarks. Moreover, MM-Reasoner demonstrates strong effectiveness and scalability, with performance improving as data size increases. Finally, our approach achieves strong performance when combining MM-Reasoner and MM-Verifier, reaching an accuracy of 65.3 on MathVista, surpassing GPT-4o (63.8) with 12 rollouts.

[Arxiv](https://arxiv.org/abs/2502.13383)
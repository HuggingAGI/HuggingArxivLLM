# PromptCoT 2.0：面向大型语言模型推理的提示合成规模化

发布时间：2025年09月24日

`LLM应用` `基础理论`

> PromptCoT 2.0: Scaling Prompt Synthesis for Large Language Model Reasoning

# 摘要

> 大型语言模型（LLMs）正从对话系统升级为强大的推理工具，能够应对奥林匹克数学、竞赛编程等复杂任务。尽管扩大参数规模和增加测试时计算量带来了进步，但关键瓶颈在于高质量训练题目的匮乏：人工构建的数据集成本高、规模有限，现有合成语料库则常因过于简单或范围狭窄而受限。PromptCoT 1.0曾证明，在提示合成中融入推理过程能提升问题难度。在此基础上，我们提出PromptCoT 2.0——一个可扩展框架，它用期望最大化（EM）循环替代手工设计的启发式规则，通过迭代优化推理过程来指导提示构建。由此生成的题目不仅难度更高，多样性也远超以往语料库。

这些合成提示支持两种训练后模式：（1）自博弈（Self-Play）：无需更强教师模型，强大模型通过可验证反馈实现自主提升；（2）监督微调（SFT）：较弱模型通过学习教师模型提炼的轨迹实现进步。大量实验验证了该方法的有效性：在自博弈场景中，将PromptCoT 2.0应用于Qwen3-30B-A3B-Thinking-2507后，模型在30B参数规模上刷新了最先进水平——AIME 24/25和HMMT 25的得分分别提升4.4、4.8和5.3分，LiveCodeBench v5/v6提升6.1和5.0分，Codeforces则提高35 Elo分。在监督微调中，仅用合成提示训练Qwen2.5-7B-Instruct，其准确率在AIME 24、AIME 25和LiveCodeBench v5上分别达到73.1、65.6和53.4，超越了使用人工数据或混合数据训练的模型。

分析进一步证实，PromptCoT 2.0生成的题目不仅本质难度更高，分布也独具一格。这些结果不仅将提示合成确立为扩展推理能力的新方向，还将PromptCoT 2.0定位为未来开源模型的可扩展基石。相关实现已开源，地址为https://github.com/inclusionAI/PromptCoT。

> Large language models (LLMs) are evolving from conversational systems into strong reasoners for tasks such as Olympiad mathematics and competitive programming. While scaling parameters and test-time computation has driven progress, a key bottleneck is the lack of high-quality training problems: human-curated datasets are costly and limited, while existing synthetic corpora are often too easy or narrow. PromptCoT 1.0 showed that injecting rationales into prompt synthesis increases problem difficulty. Building on this, we present PromptCoT 2.0, a scalable framework that replaces hand-crafted heuristics with an expectation-maximization (EM) loop, where rationales are iteratively refined to guide prompt construction. This produces problems that are both harder and more diverse than prior corpora. The synthetic prompts support two post-training regimes: (1) Self-Play, where strong models improve autonomously via verifiable feedback without stronger teachers; and (2) Supervised Fine-Tuning (SFT), where weaker models learn from teacher-distilled traces. Extensive experiments demonstrate the effectiveness of this approach. In self-play, applying PromptCoT 2.0 to Qwen3-30B-A3B-Thinking-2507 sets new state-of-the-art results at the 30B scale, with +4.4, +4.8, and +5.3 on AIME 24/25 and HMMT 25, +6.1 and +5.0 on LiveCodeBench v5/v6, and +35 Elo on Codeforces. In SFT, training Qwen2.5-7B-Instruct solely on synthetic prompts boosts accuracy to 73.1 (AIME 24), 65.6 (AIME 25), and 53.4 (LiveCodeBench v5), surpassing models trained on human or hybrid data. Analyses further confirm that PromptCoT 2.0 yields fundamentally harder and distributionally distinct problems. These results establish prompt synthesis as a new axis for scaling reasoning and position PromptCoT 2.0 as a scalable foundation for future open-source models. The implementation is available at https://github.com/inclusionAI/PromptCoT.

[Arxiv](https://arxiv.org/abs/2509.19894)
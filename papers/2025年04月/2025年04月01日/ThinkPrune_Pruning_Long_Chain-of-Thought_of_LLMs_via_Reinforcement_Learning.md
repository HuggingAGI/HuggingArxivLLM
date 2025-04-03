# ThinkPrune：利用强化学习精简大型语言模型的长思维链

发布时间：2025年04月01日

`LLM应用` `人工智能` `模型优化`

> ThinkPrune: Pruning Long Chain-of-Thought of LLMs via Reinforcement Learning

# 摘要

> 我们提出了一种名为ThinkPrune的简单而有效的修剪方法，用于优化长思考大型语言模型（LLMs）的思考长度。这些模型常会生成低效且冗余的思考过程。现有的减少思考长度的初步探索主要集中在强制思考过程提前终止，而非让LLMs适应并优化思考过程，因此目前观察到的长度与性能之间的权衡并不理想。为填补这一研究空白，ThinkPrune提供了一个简单解决方案：通过强化学习（RL）持续训练长思考的LLMs，同时设置一个额外的令牌限制，超过此限制后，任何未完成的思考和答案都将被丢弃，并给予零奖励。为了进一步保持模型性能，我们引入了一种迭代长度修剪方法，即进行多轮RL训练，每轮的令牌限制逐渐变得更加严格。我们发现，ThinkPrune实现了显著的性能与长度权衡——在AIME24数据集上，DeepSeek-R1-Distill-Qwen-1.5B的推理长度可以减少一半，同时性能仅下降2%。我们还发现，经过修剪后，LLMs能够跳过不必要的步骤，同时保持核心推理过程的完整性。代码可在https://github.com/UCSB-NLP-Chang/ThinkPrune获取。

> We present ThinkPrune, a simple yet effective method for pruning the thinking length for long-thinking LLMs, which has been found to often produce inefficient and redundant thinking processes. Existing preliminary explorations of reducing thinking length primarily focus on forcing the thinking process to early exit, rather than adapting the LLM to optimize and consolidate the thinking process, and therefore the length-performance tradeoff observed so far is sub-optimal. To fill this gap, ThinkPrune offers a simple solution that continuously trains the long-thinking LLMs via reinforcement learning (RL) with an added token limit, beyond which any unfinished thoughts and answers will be discarded, resulting in a zero reward. To further preserve model performance, we introduce an iterative length pruning approach, where multiple rounds of RL are conducted, each with an increasingly more stringent token limit. We observed that ThinkPrune results in a remarkable performance-length tradeoff -- on the AIME24 dataset, the reasoning length of DeepSeek-R1-Distill-Qwen-1.5B can be reduced by half with only 2% drop in performance. We also observed that after pruning, the LLMs can bypass unnecessary steps while keeping the core reasoning process complete. Code is available at https://github.com/UCSB-NLP-Chang/ThinkPrune.

[Arxiv](https://arxiv.org/abs/2504.01296)
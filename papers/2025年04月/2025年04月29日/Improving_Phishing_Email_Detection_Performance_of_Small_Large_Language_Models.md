# 提升小型大语言模型的钓鱼邮件检测性能

发布时间：2025年04月29日

`LLM应用` `信息安全`

> Improving Phishing Email Detection Performance of Small Large Language Models

# 摘要

> 大型语言模型（LLMs）在自然语言处理（NLP）任务中表现出色，并被用于钓鱼邮件检测研究。然而，当前高性能的LLMs通常需要数十亿甚至数百亿的参数，计算成本高昂。为降低计算成本，我们研究了小型参数LLMs（约30亿参数）在钓鱼邮件检测中的应用，这些模型可在消费级GPU上运行。然而，小型LLMs在钓鱼邮件检测中表现不佳。为此，我们设计了提示工程、解释增强微调和模型集成等方法，显著提升了小型LLMs的钓鱼邮件检测能力。实验结果显示，我们的方法在SpamAssassin数据集上的准确率从基线模型（如Qwen2.5-1.5B-Instruct）的约0.5提升至0.976。

> Large language models(LLMs) have demonstrated remarkable performance on many natural language processing(NLP) tasks and have been employed in phishing email detection research. However, in current studies, well-performing LLMs typically contain billions or even tens of billions of parameters, requiring enormous computational resources. To reduce computational costs, we investigated the effectiveness of small-parameter LLMs for phishing email detection. These LLMs have around 3 billion parameters and can run on consumer-grade GPUs. However, small LLMs often perform poorly in phishing email detection task. To address these issues, we designed a set of methods including Prompt Engineering, Explanation Augmented Fine-tuning, and Model Ensemble to improve phishing email detection capabilities of small LLMs. We validated the effectiveness of our approach through experiments, significantly improving accuracy on the SpamAssassin dataset from around 0.5 for baseline models like Qwen2.5-1.5B-Instruct to 0.976.

[Arxiv](https://arxiv.org/abs/2505.00034)
# 既然我们拥有大型语言模型，那么我们就应该并且能够去探索更具代理性的可解释性。

发布时间：2025年06月13日

`LLM应用` `人工智能` `人机交互`

> Because we have LLMs, we Can and Should Pursue Agentic Interpretability

# 摘要

> 大语言模型时代为可解释性带来了新机遇——agent-like可解释性：这是一种与LLM的多轮对话模式，LLM通过构建并利用用户心智模型主动协助人类理解，反过来也使人类能够更好地构建对LLM的心智模型。这种对话模式是传统`窥探式`可解释性方法未曾使用的能力。拥有一个旨在教学和解释的语言模型，超越仅仅知道如何对话，类似于一位以良好教学为目标的教师，明白自己的成功将由学生的理解程度来衡量。尽管agent-like可解释性可能在互动性上牺牲了完整性，使其不太适合高风险安全场景（可能存在欺骗性模型），但它利用了合作模型来发现可能超越人类的概念，从而改善人类对机器的理解。由于agent-like可解释性具有`人嵌入循环`特性（人类响应是算法不可或缺的一部分），它在评估方面带来了挑战，使得设计和评估变得困难。我们讨论了可能的解决方案和替代目标。随着LLMs在许多任务中接近人类水平，agent-like可解释性的承诺在于帮助人类学习LLMs可能拥有的超越人类的概念，而不是让我们越来越无法理解它们。

> The era of Large Language Models (LLMs) presents a new opportunity for interpretability--agentic interpretability: a multi-turn conversation with an LLM wherein the LLM proactively assists human understanding by developing and leveraging a mental model of the user, which in turn enables humans to develop better mental models of the LLM. Such conversation is a new capability that traditional `inspective' interpretability methods (opening the black-box) do not use. Having a language model that aims to teach and explain--beyond just knowing how to talk--is similar to a teacher whose goal is to teach well, understanding that their success will be measured by the student's comprehension. While agentic interpretability may trade off completeness for interactivity, making it less suitable for high-stakes safety situations with potentially deceptive models, it leverages a cooperative model to discover potentially superhuman concepts that can improve humans' mental model of machines. Agentic interpretability introduces challenges, particularly in evaluation, due to what we call `human-entangled-in-the-loop' nature (humans responses are integral part of the algorithm), making the design and evaluation difficult. We discuss possible solutions and proxy goals. As LLMs approach human parity in many tasks, agentic interpretability's promise is to help humans learn the potentially superhuman concepts of the LLMs, rather than see us fall increasingly far from understanding them.

[Arxiv](https://arxiv.org/abs/2506.12152)
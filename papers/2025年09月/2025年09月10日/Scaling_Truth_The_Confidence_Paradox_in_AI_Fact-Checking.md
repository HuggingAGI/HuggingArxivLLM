# 规模化真相：AI事实核查中的置信悖论

发布时间：2025年09月10日

`LLM应用` `媒体与娱乐`

> Scaling Truth: The Confidence Paradox in AI Fact-Checking

# 摘要

> 虚假信息的泛滥凸显了对可扩展、可靠事实核查解决方案的迫切需求。大型语言模型（LLMs）有望实现事实验证的自动化，但其在全球多语境下的实际效果仍有待验证。我们选取了来自47种语言、经174家专业事实核查机构评估的5000条声明，对九款成熟LLMs展开跨类别系统评估——涵盖开源/闭源、不同规模、多样架构及推理型模型。研究方法重点测试了模型两方面能力：一是对训练数据截止日后新增声明的泛化性能，二是四种模拟公民与专业核查员交互场景的提示策略效果，并以24万余条人类注释作为真实标签。研究发现了一种类似邓宁-克鲁格效应的堪忧现象：小型、易获取的模型虽准确性欠佳，却表现出极高信心；而大型模型虽准确性更高，信心却相对不足。这可能在信息验证中引发系统性偏见，因为资源有限的机构通常依赖小型模型。模型在非英语语言及来自全球南方的声明上的性能差距尤为突出，或将加剧现有的信息不平等。这些研究结果不仅为未来研究奠定了多语言基准，也为旨在保障公平获取可信AI辅助事实核查服务的政策制定提供了实证依据。

> The rise of misinformation underscores the need for scalable and reliable fact-checking solutions. Large language models (LLMs) hold promise in automating fact verification, yet their effectiveness across global contexts remains uncertain. We systematically evaluate nine established LLMs across multiple categories (open/closed-source, multiple sizes, diverse architectures, reasoning-based) using 5,000 claims previously assessed by 174 professional fact-checking organizations across 47 languages. Our methodology tests model generalizability on claims postdating training cutoffs and four prompting strategies mirroring both citizen and professional fact-checker interactions, with over 240,000 human annotations as ground truth. Findings reveal a concerning pattern resembling the Dunning-Kruger effect: smaller, accessible models show high confidence despite lower accuracy, while larger models demonstrate higher accuracy but lower confidence. This risks systemic bias in information verification, as resource-constrained organizations typically use smaller models. Performance gaps are most pronounced for non-English languages and claims originating from the Global South, threatening to widen existing information inequalities. These results establish a multilingual benchmark for future research and provide an evidence base for policy aimed at ensuring equitable access to trustworthy, AI-assisted fact-checking.

[Arxiv](https://arxiv.org/abs/2509.08803)
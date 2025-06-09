# 综述：大型语言模型中的水印技术是否已准备好投入应用？

发布时间：2025年06月05日

`LLM理论` `知识产权` `信息技术`

> SoK: Are Watermarks in LLMs Ready for Deployment?

# 摘要

> 大型语言模型（LLMs）彻底改变了自然语言处理领域，在各种任务中展现出了令人瞩目的能力。然而，部署这些模型也带来了与知识产权侵犯和潜在滥用相关的重大风险，尤其是当对手可以模仿这些模型来窃取服务或生成误导性输出时。我们特别关注模型窃取攻击，因为它们与专有大型语言模型密切相关，并对它们的安全性、收入和道德部署构成了严重威胁。
    尽管出现了各种水印技术来缓解这些风险，但目前尚不清楚社区和行业在开发和部署大型语言模型水印方面取得了多大的进展。为了填补这一空白，我们旨在通过以下方式为大型语言模型中的水印开发一个全面的系统化框架：1）提出大型语言模型水印的详细分类法，2）提出一种新型的知识产权分类器，以探索水印在大型语言模型在受攻击和无攻击环境下的有效性及影响，3）分析现有大型语言模型水印的局限性，4）讨论大型语言模型水印在实际应用中的挑战和未来研究方向。
    通过广泛的实验，我们表明，尽管水印技术的研究成果令人鼓舞，并且领先公司和社区对其在大型语言模型中的部署给予了高度关注，但由于这些技术对大型语言模型及其下游任务的实用性产生了不利影响，它们尚未在实际应用中充分发挥其潜力。我们的研究结果为理解大型语言模型中的水印提供了深刻的见解，并强调了开发实用的水印解决方案以适应大型语言模型部署需求的必要性。

> Large Language Models (LLMs) have transformed natural language processing, demonstrating impressive capabilities across diverse tasks. However, deploying these models introduces critical risks related to intellectual property violations and potential misuse, particularly as adversaries can imitate these models to steal services or generate misleading outputs. We specifically focus on model stealing attacks, as they are highly relevant to proprietary LLMs and pose a serious threat to their security, revenue, and ethical deployment. While various watermarking techniques have emerged to mitigate these risks, it remains unclear how far the community and industry have progressed in developing and deploying watermarks in LLMs.
  To bridge this gap, we aim to develop a comprehensive systematization for watermarks in LLMs by 1) presenting a detailed taxonomy for watermarks in LLMs, 2) proposing a novel intellectual property classifier to explore the effectiveness and impacts of watermarks on LLMs under both attack and attack-free environments, 3) analyzing the limitations of existing watermarks in LLMs, and 4) discussing practical challenges and potential future directions for watermarks in LLMs. Through extensive experiments, we show that despite promising research outcomes and significant attention from leading companies and community to deploy watermarks, these techniques have yet to reach their full potential in real-world applications due to their unfavorable impacts on model utility of LLMs and downstream tasks. Our findings provide an insightful understanding of watermarks in LLMs, highlighting the need for practical watermarks solutions tailored to LLM deployment.

[Arxiv](https://arxiv.org/abs/2506.05594)
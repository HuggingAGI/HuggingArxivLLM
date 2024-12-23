# 从通用到特定：为个性化医疗量身定制大型语言模型

发布时间：2024年12月20日

`LLM应用` `个性化医疗`

> From General to Specific: Tailoring Large Language Models for Personalized Healthcare

# 摘要

> 大型语言模型（LLMs）的迅猛发展改变了众多行业，其中就有医疗保健。然而，以往的医疗LLMs大多聚焦于借助通用医学知识来给出回应，未考虑患者的差异性，在个体层面也缺乏真正的个性化。为应对此问题，我们提出了一种名为个性化医疗语言模型（PMLM）的新方法，它借助推荐系统和强化学习（RL）来探索并优化个性化的LLMs。具体而言，利用自我告知和同伴告知的个性化方式，PMLM捕捉行为和偏好的变化，从而设计出契合个人需求的初始个性化提示。我们还通过RL进一步优化这些初始个性化提示，最终提升LLM指导的精准度。值得注意的是，个性化提示属于硬提示，这赋予了PMLM高适应性和可复用性，使其能够直接利用高质量的专有LLMs。我们使用真实的妇产科数据对PMLM进行评估，实验结果显示PMLM实现了个性化响应，提供了更精细和个性化的服务，为个性化医疗LLMs开辟了一条潜在的道路。

> The rapid development of large language models (LLMs) has transformed many industries, including healthcare. However, previous medical LLMs have largely focused on leveraging general medical knowledge to provide responses, without accounting for patient variability and lacking true personalization at the individual level. To address this, we propose a novel method called personalized medical language model (PMLM), which explores and optimizes personalized LLMs through recommendation systems and reinforcement learning (RL). Specifically, by utilizing self-informed and peer-informed personalization, PMLM captures changes in behaviors and preferences to design initial personalized prompts tailored to individual needs. We further refine these initial personalized prompts through RL, ultimately enhancing the precision of LLM guidance. Notably, the personalized prompt are hard prompt, which grants PMLM high adaptability and reusability, allowing it to directly leverage high-quality proprietary LLMs. We evaluate PMLM using real-world obstetrics and gynecology data, and the experimental results demonstrate that PMLM achieves personalized responses, and it provides more refined and individualized services, offering a potential way for personalized medical LLMs.

[Arxiv](https://arxiv.org/abs/2412.15957)
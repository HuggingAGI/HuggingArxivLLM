# AI系统自动解锁文本至图像生成潜能

发布时间：2024年05月26日

`Agent

这篇论文主要探讨了AI系统，特别是文本到图像（T2I）生成系统，在安全方面的风险，特别是“越狱”问题。论文通过评估商业T2I系统的安全性，并提出了一种自动化越狱管道，展示了如何利用大型语言模型（LLMs）绕过安全机制生成恶意内容。这一研究强调了开发更强防御机制的必要性，属于对AI系统（特别是Agent）安全性的研究。` `版权保护` `人工智能安全`

> Automatic Jailbreaking of the Text-to-Image Generative AI Systems

# 摘要

> 近期AI系统在信息检索、语言及图像生成等任务上展现出超越人类的强大性能，但同时也暴露出安全风险，可能导致大型语言模型（LLMs）绕过安全机制生成恶意内容，即所谓的“越狱”。以往研究多集中于文本越狱，而文本到图像（T2I）生成系统的越狱问题鲜有关注。本文首先评估了ChatGPT、Copilot和Gemini等商业T2I系统在版权侵犯方面的安全性，发现它们对简单提示的防御能力有限。接着，我们提出了一种自动化越狱管道，能生成绕过安全防护的提示。我们的方法利用LLM优化器，无需复杂计算即可生成高度违规的图像。实验表明，这种方法成功越狱ChatGPT，使其在多数情况下生成受版权保护的内容。尽管我们探讨了多种防御策略，但发现现有措施不足以应对，强调了开发更强防御机制的必要性。

> Recent AI systems have shown extremely powerful performance, even surpassing human performance, on various tasks such as information retrieval, language generation, and image generation based on large language models (LLMs). At the same time, there are diverse safety risks that can cause the generation of malicious contents by circumventing the alignment in LLMs, which are often referred to as jailbreaking. However, most of the previous works only focused on the text-based jailbreaking in LLMs, and the jailbreaking of the text-to-image (T2I) generation system has been relatively overlooked. In this paper, we first evaluate the safety of the commercial T2I generation systems, such as ChatGPT, Copilot, and Gemini, on copyright infringement with naive prompts. From this empirical study, we find that Copilot and Gemini block only 12\% and 17\% of the attacks with naive prompts, respectively, while ChatGPT blocks 84\% of them. Then, we further propose a stronger automated jailbreaking pipeline for T2I generation systems, which produces prompts that bypass their safety guards. Our automated jailbreaking framework leverages an LLM optimizer to generate prompts to maximize degree of violation from the generated images without any weight updates or gradient computation. Surprisingly, our simple yet effective approach successfully jailbreaks the ChatGPT with 11.0\% block rate, making it generate copyrighted contents in 76\% of the time. Finally, we explore various defense strategies, such as post-generation filtering and machine unlearning techniques, but found that they were inadequate, which suggests the necessity of stronger defense mechanisms.

![AI系统自动解锁文本至图像生成潜能](../../../paper_images/2405.16567/x1.png)

![AI系统自动解锁文本至图像生成潜能](../../../paper_images/2405.16567/x2.png)

![AI系统自动解锁文本至图像生成潜能](../../../paper_images/2405.16567/x3.png)

![AI系统自动解锁文本至图像生成潜能](../../../paper_images/2405.16567/x4.png)

![AI系统自动解锁文本至图像生成潜能](../../../paper_images/2405.16567/x5.png)

![AI系统自动解锁文本至图像生成潜能](../../../paper_images/2405.16567/x6.png)

![AI系统自动解锁文本至图像生成潜能](../../../paper_images/2405.16567/x7.png)

![AI系统自动解锁文本至图像生成潜能](../../../paper_images/2405.16567/x8.png)

![AI系统自动解锁文本至图像生成潜能](../../../paper_images/2405.16567/x9.png)

![AI系统自动解锁文本至图像生成潜能](../../../paper_images/2405.16567/x10.png)

![AI系统自动解锁文本至图像生成潜能](../../../paper_images/2405.16567/x11.png)

![AI系统自动解锁文本至图像生成潜能](../../../paper_images/2405.16567/x12.png)

![AI系统自动解锁文本至图像生成潜能](../../../paper_images/2405.16567/x13.png)

![AI系统自动解锁文本至图像生成潜能](../../../paper_images/2405.16567/x14.png)

![AI系统自动解锁文本至图像生成潜能](../../../paper_images/2405.16567/x15.png)

![AI系统自动解锁文本至图像生成潜能](../../../paper_images/2405.16567/x16.png)

![AI系统自动解锁文本至图像生成潜能](../../../paper_images/2405.16567/x17.png)

![AI系统自动解锁文本至图像生成潜能](../../../paper_images/2405.16567/x18.png)

![AI系统自动解锁文本至图像生成潜能](../../../paper_images/2405.16567/x19.png)

![AI系统自动解锁文本至图像生成潜能](../../../paper_images/2405.16567/x20.png)

![AI系统自动解锁文本至图像生成潜能](../../../paper_images/2405.16567/possible_risk.png)

![AI系统自动解锁文本至图像生成潜能](../../../paper_images/2405.16567/x21.png)

![AI系统自动解锁文本至图像生成潜能](../../../paper_images/2405.16567/human_eval.png)

![AI系统自动解锁文本至图像生成潜能](../../../paper_images/2405.16567/x22.png)

![AI系统自动解锁文本至图像生成潜能](../../../paper_images/2405.16567/x23.png)

![AI系统自动解锁文本至图像生成潜能](../../../paper_images/2405.16567/x24.png)

![AI系统自动解锁文本至图像生成潜能](../../../paper_images/2405.16567/manual_trial.png)

![AI系统自动解锁文本至图像生成潜能](../../../paper_images/2405.16567/manual_trial3.png)

![AI系统自动解锁文本至图像生成潜能](../../../paper_images/2405.16567/0.png)

![AI系统自动解锁文本至图像生成潜能](../../../paper_images/2405.16567/1.png)

![AI系统自动解锁文本至图像生成潜能](../../../paper_images/2405.16567/2.png)

![AI系统自动解锁文本至图像生成潜能](../../../paper_images/2405.16567/3.png)

![AI系统自动解锁文本至图像生成潜能](../../../paper_images/2405.16567/4.png)

![AI系统自动解锁文本至图像生成潜能](../../../paper_images/2405.16567/5.png)

![AI系统自动解锁文本至图像生成潜能](../../../paper_images/2405.16567/6.png)

![AI系统自动解锁文本至图像生成潜能](../../../paper_images/2405.16567/7.png)

![AI系统自动解锁文本至图像生成潜能](../../../paper_images/2405.16567/8.png)

![AI系统自动解锁文本至图像生成潜能](../../../paper_images/2405.16567/9.png)

![AI系统自动解锁文本至图像生成潜能](../../../paper_images/2405.16567/10.png)

![AI系统自动解锁文本至图像生成潜能](../../../paper_images/2405.16567/11.png)

![AI系统自动解锁文本至图像生成潜能](../../../paper_images/2405.16567/12.png)

![AI系统自动解锁文本至图像生成潜能](../../../paper_images/2405.16567/13.png)

![AI系统自动解锁文本至图像生成潜能](../../../paper_images/2405.16567/14.png)

![AI系统自动解锁文本至图像生成潜能](../../../paper_images/2405.16567/multiple_trial.png)

![AI系统自动解锁文本至图像生成潜能](../../../paper_images/2405.16567/keyword_suppression.png)

![AI系统自动解锁文本至图像生成潜能](../../../paper_images/2405.16567/suffix_intention_screenshot.png)

![AI系统自动解锁文本至图像生成潜能](../../../paper_images/2405.16567/reference.png)

![AI系统自动解锁文本至图像生成潜能](../../../paper_images/2405.16567/vangogh_baseline.png)

![AI系统自动解锁文本至图像生成潜能](../../../paper_images/2405.16567/vangogh_our.png)

[Arxiv](https://arxiv.org/abs/2405.16567)
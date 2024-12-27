# 保留分数：对视觉语言模型的越狱风险进行量化

发布时间：2024年12月23日

`LLM应用` `计算机视觉` `多模态机器学习`

> Retention Score: Quantifying Jailbreak Risks for Vision Language Models

# 摘要

> 视觉语言模型（VLMs）的诞生是将计算机视觉与大型语言模型（LLMs）相融合以提升多模态机器学习能力的重大突破。然而，这一进步也让VLMs易受复杂的对抗性攻击，令人对其可靠性产生担忧。本文旨在评估VLMs抵御越狱攻击的能力，此类攻击可能破坏模型的安全合规性并造成有害输出。为评估VLM对抗对抗性输入干扰的能力，我们提出了一种名为【保留分数】的新指标。该保留分数是一种多模态评估指标，涵盖用于量化VLMs视觉和文本部分越狱风险的保留-I和保留-T分数。我们的流程包括运用条件扩散模型生成合成的图像-文本对。接着，这些对由VLM和毒性判断分类器共同预测毒性分数。通过计算毒性分数的差值，能够以不依赖攻击的方式量化VLM的稳健性。我们的工作有四大主要贡献。其一，我们证明保留分数可作为经认证的稳健性指标。其二，我们表明多数具有视觉组件的VLMs在抵御越狱攻击方面不如相应的普通VLMs稳健。另外，我们评估了黑盒VLM API，发现Google Gemini中的安全设置对分数和稳健性影响显著。而且，GPT4V的稳健性与Gemini的中等设置相似。最后，我们的方法为现有的对抗性攻击方法提供了一种省时的替代选择，并在对包括MiniGPT-4、InstructBLIP和LLaVA在内的VLM进行评估时给出了一致的模型稳健性排名。

> The emergence of Vision-Language Models (VLMs) is a significant advancement in integrating computer vision with Large Language Models (LLMs) to enhance multi-modal machine learning capabilities. However, this progress has also made VLMs vulnerable to sophisticated adversarial attacks, raising concerns about their reliability. The objective of this paper is to assess the resilience of VLMs against jailbreak attacks that can compromise model safety compliance and result in harmful outputs. To evaluate a VLM's ability to maintain its robustness against adversarial input perturbations, we propose a novel metric called the \textbf{Retention Score}. Retention Score is a multi-modal evaluation metric that includes Retention-I and Retention-T scores for quantifying jailbreak risks in visual and textual components of VLMs. Our process involves generating synthetic image-text pairs using a conditional diffusion model. These pairs are then predicted for toxicity score by a VLM alongside a toxicity judgment classifier. By calculating the margin in toxicity scores, we can quantify the robustness of the VLM in an attack-agnostic manner. Our work has four main contributions. First, we prove that Retention Score can serve as a certified robustness metric. Second, we demonstrate that most VLMs with visual components are less robust against jailbreak attacks than the corresponding plain VLMs. Additionally, we evaluate black-box VLM APIs and find that the security settings in Google Gemini significantly affect the score and robustness. Moreover, the robustness of GPT4V is similar to the medium settings of Gemini. Finally, our approach offers a time-efficient alternative to existing adversarial attack methods and provides consistent model robustness rankings when evaluated on VLMs including MiniGPT-4, InstructBLIP, and LLaVA.

[Arxiv](https://arxiv.org/abs/2412.17544)
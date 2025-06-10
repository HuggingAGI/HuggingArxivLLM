# 对抗性改写：一种让AI文本更像人写的通用攻击方法

发布时间：2025年06月08日

`LLM应用` `信息安全` `网络安全`

> Adversarial Paraphrasing: A Universal Attack for Humanizing AI-Generated Text

# 摘要

> 随着大型语言模型（LLMs）能力的不断提升，人们开始担忧其在AI生成剽窃和社交工程中的滥用风险。尽管已有多种AI生成文本检测器被提出以缓解这些风险，但许多检测器仍易受简单的改写等规避技术的攻击。然而，近期的检测器在面对此类基础攻击时展现出更强的鲁棒性。在此，我们提出了一种名为Adversarial Paraphrasing的无训练攻击框架，该框架能够将任何AI生成文本普遍“人性化”，从而更有效地规避检测。我们的方法借助现成的遵循指令的LLM，在AI文本检测器的指导下对AI生成内容进行改写，生成专门优化以绕过检测的对抗样本。通过大量实验，我们发现该攻击方法在多个检测系统中表现优异，既普遍有效又具备高度可转移性。例如，与简单的改写攻击相比——令人意外的是，它在RADAR上将1%假阳性率下的真正阳性率（T@1%F）提高了8.57%，在Fast-DetectGPT上提高了15.03%——由OpenAI-RoBERTa-Large指导的对抗改写将T@1%F在RADAR上降低了64.49%，在Fast-DetectGPT上惊人地降低了98.96%。在包括基于神经网络、水印和零样本方法在内的多种检测器上，我们的攻击在OpenAI-RoBERTa-Large的指导下平均将T@1%F降低了87.88%。此外，我们还分析了文本质量和攻击成功率之间的权衡，发现我们的方法不仅显著降低了检测率，而且文本质量仅略有下降。这一对抗设置凸显了在日益复杂的规避技术背景下，开发更加稳健和 resilient 的检测策略的迫切需求。


> The increasing capabilities of Large Language Models (LLMs) have raised concerns about their misuse in AI-generated plagiarism and social engineering. While various AI-generated text detectors have been proposed to mitigate these risks, many remain vulnerable to simple evasion techniques such as paraphrasing. However, recent detectors have shown greater robustness against such basic attacks. In this work, we introduce Adversarial Paraphrasing, a training-free attack framework that universally humanizes any AI-generated text to evade detection more effectively. Our approach leverages an off-the-shelf instruction-following LLM to paraphrase AI-generated content under the guidance of an AI text detector, producing adversarial examples that are specifically optimized to bypass detection. Extensive experiments show that our attack is both broadly effective and highly transferable across several detection systems. For instance, compared to simple paraphrasing attack--which, ironically, increases the true positive at 1% false positive (T@1%F) by 8.57% on RADAR and 15.03% on Fast-DetectGPT--adversarial paraphrasing, guided by OpenAI-RoBERTa-Large, reduces T@1%F by 64.49% on RADAR and a striking 98.96% on Fast-DetectGPT. Across a diverse set of detectors--including neural network-based, watermark-based, and zero-shot approaches--our attack achieves an average T@1%F reduction of 87.88% under the guidance of OpenAI-RoBERTa-Large. We also analyze the tradeoff between text quality and attack success to find that our method can significantly reduce detection rates, with mostly a slight degradation in text quality. Our adversarial setup highlights the need for more robust and resilient detection strategies in the light of increasingly sophisticated evasion techniques.

[Arxiv](https://arxiv.org/abs/2506.07001)
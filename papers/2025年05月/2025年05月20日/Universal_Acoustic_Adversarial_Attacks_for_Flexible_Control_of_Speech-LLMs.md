# 通用音频对抗攻击：灵活控制语音-LLMs的新方法

发布时间：2025年05月20日

`LLM应用

摘要分析：这篇论文探讨了语音LLMs在对抗攻击中的脆弱性，属于模型应用层面的安全性研究，因此归类为LLM应用。` `语音处理`

> Universal Acoustic Adversarial Attacks for Flexible Control of Speech-LLMs

# 摘要

> 预训练语音编码器与大型语言模型的结合，催生了能够处理广泛语音处理任务的语音LLMs。这些模型虽然功能强大且灵活，但这种灵活性也可能使它们更容易受到对抗攻击。为评估这一问题的严重性，本研究探讨了针对语音LLMs的通用声学对抗攻击。具体而言，我们会在原始输入音频前添加一个固定且通用的对抗音频片段。我们首先研究了两类攻击：一类导致模型无输出，另一类则使模型执行修改后的任务，覆盖原始提示。随后，我们扩展了攻击的特性，使其具有选择性，仅在特定输入属性（如说话人性别或语言）存在时触发。不含目标属性的输入则不受影响，从而实现了对模型输出的精细控制。研究发现，Qwen2-Audio和Granite-Speech存在严重漏洞，提示类似的语音LLMs可能同样易受通用对抗攻击。这凸显了开发更稳健的训练策略和提升模型抗攻击能力的迫切需求。

> The combination of pre-trained speech encoders with large language models has enabled the development of speech LLMs that can handle a wide range of spoken language processing tasks. While these models are powerful and flexible, this very flexibility may make them more vulnerable to adversarial attacks. To examine the extent of this problem, in this work we investigate universal acoustic adversarial attacks on speech LLMs. Here a fixed, universal, adversarial audio segment is prepended to the original input audio. We initially investigate attacks that cause the model to either produce no output or to perform a modified task overriding the original prompt. We then extend the nature of the attack to be selective so that it activates only when specific input attributes, such as a speaker gender or spoken language, are present. Inputs without the targeted attribute should be unaffected, allowing fine-grained control over the model outputs. Our findings reveal critical vulnerabilities in Qwen2-Audio and Granite-Speech and suggest that similar speech LLMs may be susceptible to universal adversarial attacks. This highlights the need for more robust training strategies and improved resistance to adversarial attacks.

[Arxiv](https://arxiv.org/abs/2505.14286)
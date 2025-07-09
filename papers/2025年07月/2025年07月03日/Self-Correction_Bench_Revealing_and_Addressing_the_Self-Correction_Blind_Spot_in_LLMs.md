# # 自我修正基准：揭示与应对 LLMs 的自我修正盲点

发布时间：2025年07月03日

`LLM理论` `人工智能`

> Self-Correction Bench: Revealing and Addressing the Self-Correction Blind Spot in LLMs

# 摘要

> 尽管大型语言模型（LLMs）已经展现出变革性的能力，但它们仍然会出错，并且有时会走上无成效的推理之路。对于一个值得信赖的LLM，特别是自回归LLM，具备自我修正的能力至关重要。虽然LLMs能够识别用户输入中的错误，但它们却存在系统性的“自我修正盲点”——无法纠正自身输出中的相同错误。为了系统性地研究这一现象，我们推出了“自我修正基准框架”（Self-Correction Bench），这是一个通过在三个复杂度水平上进行受控错误注入来测量这一现象的系统性框架。经过对14个模型的测试，我们发现平均盲点率为64.5%。我们的研究发现，这一限制与训练数据的构成密切相关：人类的训练演示大多展示无错误的回应，而不是错误修正序列，这与通过结果反馈学习错误修正的强化学习（RL）训练模型不同。令人惊讶的是，仅仅添加“Wait”这一简单的操作，就可以将盲点减少89.3%，这表明这种自我修正的能力是存在的，只是需要被激活。我们的研究不仅揭示了当前LLMs的一个关键限制，还为提高其可靠性和可信度提供了潜在的解决方案。

> Although large language models (LLMs) have become transformative, they still make mistakes and can explore unproductive reasoning paths. Self-correction is an important capability for a trustworthy LLM, particularly an autoregressive LLM. While LLMs can identify error in user input, they exhibit a systematic 'Self-Correction Blind Spot' - failing to correct identical error in their own outputs. To systematically study this phenomenon, we introduce Self-Correction Bench, a systematic framework to measure this phenomenon through controlled error injection at three complexity levels. Testing 14 models, we find an average 64.5% blind spot rate. We find multiple evidences that this limitation relates to training data composition: human training demonstrations predominantly show error-free responses rather than error-correction sequences, unlike RL-trained models that learn error correction through outcome feedback. Remarkably, simply appending "Wait" reduces blind spots by 89.3%, suggesting that the capability exists but requires activation. Our work highlights a critical limitation in current LLMs and offers potential avenues for improving their reliability and trustworthiness.

[Arxiv](https://arxiv.org/abs/2507.02778)
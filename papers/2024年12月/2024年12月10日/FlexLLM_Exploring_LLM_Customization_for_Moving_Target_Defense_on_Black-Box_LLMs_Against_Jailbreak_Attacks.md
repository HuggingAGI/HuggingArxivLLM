# FlexLLM：探索针对黑盒LLM越狱攻击的移动目标防御中的LLM定制

发布时间：2024年12月10日

`LLM应用` `语言模型` `网络安全`

> FlexLLM: Exploring LLM Customization for Moving Target Defense on Black-Box LLMs Against Jailbreak Attacks

# 摘要

> 在大型语言模型（LLMs）中，防御工作至关重要，因为众多攻击者会利用这些系统，通过操纵提示来生成有害内容，此即所谓的越狱攻击。虽然已提出众多防御策略，但它们往往需要访问模型内部结构或进行额外训练，这对于使用 LLM API（如 OpenAI API 或 Claude API）的服务提供商而言并不现实。本文中，我们提出一种移动目标防御方法，通过改变解码超参数来增强模型抵御各类越狱攻击的能力。我们的方法无需访问模型内部结构，也不会产生额外训练成本。所提出的防御包含两个关键部分：（1）通过识别和调整影响令牌生成概率的解码超参数来优化解码策略；（2）将解码超参数和模型系统提示转变为动态目标，在每次运行期间持续更改。通过不断修改解码策略和提示，该防御能有效减轻现有攻击。我们的结果显示，在将 LLMs 作为黑盒 API 测试的三个模型中，我们的防御针对越狱攻击最为有效。此外，我们的防御具有更低的推理成本，并能保持相当的响应质量，与其他防御方法配合使用时，有望成为一层潜在的防护。

> Defense in large language models (LLMs) is crucial to counter the numerous attackers exploiting these systems to generate harmful content through manipulated prompts, known as jailbreak attacks. Although many defense strategies have been proposed, they often require access to the model's internal structure or need additional training, which is impractical for service providers using LLM APIs, such as OpenAI APIs or Claude APIs. In this paper, we propose a moving target defense approach that alters decoding hyperparameters to enhance model robustness against various jailbreak attacks. Our approach does not require access to the model's internal structure and incurs no additional training costs. The proposed defense includes two key components: (1) optimizing the decoding strategy by identifying and adjusting decoding hyperparameters that influence token generation probabilities, and (2) transforming the decoding hyperparameters and model system prompts into dynamic targets, which are continuously altered during each runtime. By continuously modifying decoding strategies and prompts, the defense effectively mitigates the existing attacks. Our results demonstrate that our defense is the most effective against jailbreak attacks in three of the models tested when using LLMs as black-box APIs. Moreover, our defense offers lower inference costs and maintains comparable response quality, making it a potential layer of protection when used alongside other defense methods.

[Arxiv](https://arxiv.org/abs/2412.07672)
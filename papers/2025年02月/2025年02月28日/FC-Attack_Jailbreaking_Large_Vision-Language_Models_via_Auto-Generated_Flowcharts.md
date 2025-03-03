# FC-Attack：利用自动生成的流程图越狱大型视觉语言模型

发布时间：2025年02月28日

`LLM应用

摘要讨论了大型视觉语言模型（LVLMs）在多模态越狱攻击中的脆弱性，并提出了一种基于自动生成流程图的攻击方法。研究集中在如何利用LLM生成有害内容，属于LLM在实际应用中的安全问题，因此归类为LLM应用。` `人工智能` `网络安全`

> FC-Attack: Jailbreaking Large Vision-Language Models via Auto-Generated Flowcharts

# 摘要

> 大型视觉语言模型（LVLMs）凭借其强大的能力，在实际应用中得到了广泛应用。然而，近期研究揭示了它们在多模态越狱攻击面前的脆弱性，攻击者可以诱导模型生成有害内容，从而引发安全风险。尽管大多数LVLMs已经进行了安全对齐，但最新研究发现，视觉模态仍然容易受到越狱攻击。在我们的研究中，我们发现通过使用包含部分有害信息的流程图，可以诱导LVLMs生成更多有害细节。基于此，我们提出了一种基于自动生成流程图的越狱攻击方法，命名为FC-Attack。

具体而言，FC-Attack首先对预训练的LLM进行微调，基于良性数据集创建一个步骤描述生成器。生成器随后用于生成与恶意查询对应的步骤描述，并将其转换为三种不同形状（垂直、水平和S形）的流程图作为视觉提示。这些流程图随后与良性文本提示结合，对LVLMs执行越狱攻击。

通过Advbench数据集的评估，我们的FC-Attack方法在Gemini-1.5、Llaval-Next、Qwen2-VL和InternVL-2.5等模型上实现了超过90%的攻击成功率，显著优于现有的LVLM越狱方法。此外，我们还探讨了影响攻击性能的因素，包括流程图中的步骤数量和字体样式。评估结果显示，通过改变字体样式，FC-Attack在Claude-3.5上的越狱成功率可以从4%提升至28%。

为了缓解此类攻击，我们探索了多种防御措施，并发现AdaShield能够在很大程度上降低越狱性能，但代价是模型实用性的下降。

> Large Vision-Language Models (LVLMs) have become powerful and widely adopted in some practical applications. However, recent research has revealed their vulnerability to multimodal jailbreak attacks, whereby the model can be induced to generate harmful content, leading to safety risks. Although most LVLMs have undergone safety alignment, recent research shows that the visual modality is still vulnerable to jailbreak attacks. In our work, we discover that by using flowcharts with partially harmful information, LVLMs can be induced to provide additional harmful details. Based on this, we propose a jailbreak attack method based on auto-generated flowcharts, FC-Attack. Specifically, FC-Attack first fine-tunes a pre-trained LLM to create a step-description generator based on benign datasets. The generator is then used to produce step descriptions corresponding to a harmful query, which are transformed into flowcharts in 3 different shapes (vertical, horizontal, and S-shaped) as visual prompts. These flowcharts are then combined with a benign textual prompt to execute a jailbreak attack on LVLMs. Our evaluations using the Advbench dataset show that FC-Attack achieves over 90% attack success rates on Gemini-1.5, Llaval-Next, Qwen2-VL, and InternVL-2.5 models, outperforming existing LVLM jailbreak methods. Additionally, we investigate factors affecting the attack performance, including the number of steps and the font styles in the flowcharts. Our evaluation shows that FC-Attack can improve the jailbreak performance from 4% to 28% in Claude-3.5 by changing the font style. To mitigate the attack, we explore several defenses and find that AdaShield can largely reduce the jailbreak performance but with the cost of utility drop.

[Arxiv](https://arxiv.org/abs/2502.21059)
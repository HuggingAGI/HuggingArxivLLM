# FORCE：基于特征过度依赖修正的可迁移视觉越狱攻击

发布时间：2025年09月25日

`LLM应用` `基础理论`

> FORCE: Transferable Visual Jailbreaking Attacks via Feature Over-Reliance CorrEction

# 摘要

> 新模态的融入虽提升了多模态大型语言模型（MLLMs）的性能，却也带来了新的安全隐患。尤其是简单的视觉越狱攻击，相比复杂的文本攻击手段，能更轻易地操控开源MLLMs。但这类尚不成熟的攻击跨模型迁移能力极差，难以可靠检测闭源MLLMs的漏洞。本研究通过分析这些越狱攻击的损失曲面发现：生成的攻击往往集中在高锐度区域，其攻击效果对迁移时哪怕微小的参数变化都极为敏感。为进一步解释高锐度现象的成因，我们对中间层与频谱域的特征表示展开分析，结果显示攻击存在对局部层特征和语义信息匮乏的频率分量的过度依赖。基于这些发现，我们提出特征过度依赖校正（FORCE）方法：该方法引导攻击探索跨层特征的更广可行区域，并按语义含量重新权衡频率特征的影响。通过去除对层特征和频谱特征的非普适性依赖，我们的方法为视觉越狱攻击找到了平坦化的可行区域，进而提升了跨模型迁移能力。大量实验证明，该方法能有效支持针对闭源MLLMs的视觉红队评估。

> The integration of new modalities enhances the capabilities of multimodal large language models (MLLMs) but also introduces additional vulnerabilities. In particular, simple visual jailbreaking attacks can manipulate open-source MLLMs more readily than sophisticated textual attacks. However, these underdeveloped attacks exhibit extremely limited cross-model transferability, failing to reliably identify vulnerabilities in closed-source MLLMs. In this work, we analyse the loss landscape of these jailbreaking attacks and find that the generated attacks tend to reside in high-sharpness regions, whose effectiveness is highly sensitive to even minor parameter changes during transfer. To further explain the high-sharpness localisations, we analyse their feature representations in both the intermediate layers and the spectral domain, revealing an improper reliance on narrow layer representations and semantically poor frequency components. Building on this, we propose a Feature Over-Reliance CorrEction (FORCE) method, which guides the attack to explore broader feasible regions across layer features and rescales the influence of frequency features according to their semantic content. By eliminating non-generalizable reliance on both layer and spectral features, our method discovers flattened feasible regions for visual jailbreaking attacks, thereby improving cross-model transferability. Extensive experiments demonstrate that our approach effectively facilitates visual red-teaming evaluations against closed-source MLLMs.

[Arxiv](https://arxiv.org/abs/2509.21029)
# Marco-LLM：借助大规模多语言训练来连通语言，达成跨语言增强的效果

发布时间：2024年12月05日

`LLM应用` `机器翻译`

> Marco-LLM: Bridging Languages via Massive Multilingual Training for Cross-Lingual Enhancement

# 摘要

> 大型语言模型（LLMs）近些年来进步显著；然而，其出色表现仍主要局限于世界主要语言，尤其是英语。众多 LLMs 在多语言任务上依旧面临挑战，涉及低资源语言时更是如此。为解决此问题，我们推出了 Marco-LLM：用于跨语言增强 LLMs 的大规模多语言训练。我们为若干低资源语言收集了大量多语言数据，并利用 Qwen2 模型开展了广泛的持续预训练。这番努力造就了名为 Marco-LLM 的多语言 LLMs。通过在包括 MMMLU、AGIEval、Belebele、Flores-200、XCOPA 等在内的各种多语言基准上进行全面评估，Marco-LLM 已展现出相较最先进 LLMs 的显著提升。此外，Marco-LLM 在任意对任意的机器翻译任务中取得了显著进步，彰显了我们多语言 LLMs 的有效性。Marco-LLM 是开创性的多语言 LLMs，不仅要在包括低资源语言在内的多语言任务中表现卓越，还要在英语及其他主要语言中保持强劲性能，缩小高资源和低资源语言能力之间的差距。通过搭建语言桥梁，此项努力表明我们致力于确保 LLMs 在各种语言中准确运行。

> Large Language Models (LLMs) have achieved remarkable progress in recent years; however, their excellent performance is still largely limited to major world languages, primarily English. Many LLMs continue to face challenges with multilingual tasks, especially when it comes to low-resource languages. To address this issue, we introduced Marco-LLM: Massive multilingual training for cross-lingual enhancement LLM. We have collected a substantial amount of multilingual data for several low-resource languages and conducted extensive continual pre-training using the Qwen2 models. This effort has resulted in a multilingual LLM named Marco-LLM. Through comprehensive evaluations on various multilingual benchmarks, including MMMLU, AGIEval, Belebele, Flores-200, XCOPA and many others, Marco-LLM has demonstrated substantial improvements over state-of-the-art LLMs. Furthermore, Marco-LLM achieved substantial enhancements in any-to-any machine translation tasks, showing the effectiveness of our multilingual LLM. Marco-LLM is a pioneering multilingual LLM designed to not only perform exceptionally well in multilingual tasks, including low-resource languages, but also maintain strong performance in English and other major languages, closing the performance gap between high- and low-resource language capabilities. By bridging languages, this effort demonstrates our dedication to ensuring LLMs work accurately across various languages.

[Arxiv](https://arxiv.org/abs/2412.04003)
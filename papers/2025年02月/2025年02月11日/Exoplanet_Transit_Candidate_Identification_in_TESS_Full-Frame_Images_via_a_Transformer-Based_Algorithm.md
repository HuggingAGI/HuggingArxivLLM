# 通过基于Transformer的算法，在TESS全视场图像中识别系外行星凌星候选体

发布时间：2025年02月11日

`LLM应用` `天文学` `天体物理学`

> Exoplanet Transit Candidate Identification in TESS Full-Frame Images via a Transformer-Based Algorithm

# 摘要

> 凌日系外行星巡天卫星（TESS）正在对大量天区进行观测，生成了一个包含海量光变时序数据的数据库。自动化学习方法在识别系外行星凌日信号方面已取得显著成效，但现有方法多集中于候选体的分类和验证，对探索新的候选体搜索技术关注较少。我们提出了一种无需相位折叠或假设凌日信号周期性（如多凌日光变曲线中所观察到的信号）的新方法，直接从光变曲线中识别系外行星凌日信号。为此，我们实现了一种受Transformer启发的新神经网络，直接处理全视场图像（FFI）光变曲线以检测系外行星凌日现象。Transformer最初是为自然语言处理开发的，与之前专注于序列数据的方法相比，最近在捕获长距离依赖方面取得了显著成功。这种能力使我们能够利用多头自注意力机制直接从完整的光变曲线中识别系外行星凌日信号，同时结合背景和质心时序数据，而无需预先假设凌日参数。网络通过学习凌日信号的特征（如深度形状）进行训练，这有助于区分行星凌日与其他变源。我们的模型成功识别了214个新的行星系统候选体，包括122个具有多凌日光变曲线的候选体、88个单凌日以及4个多行星系统，这些候选体来自TESS的1-26号观测区，行星半径大于0.27 $R_{\mathrm{Jupiter}}$，证明了该模型无需依赖信号周期性即可检测凌日现象的能力。

> The Transiting Exoplanet Survey Satellite (TESS) is surveying a large fraction of the sky, generating a vast database of photometric time series data that requires thorough analysis to identify exoplanetary transit signals. Automated learning approaches have been successfully applied to identify transit signals. However, most existing methods focus on the classification and validation of candidates, while few efforts have explored new techniques for the search of candidates. To search for new exoplanet transit candidates, we propose an approach to identify exoplanet transit signals without the need for phase folding or assuming periodicity in the transit signals, such as those observed in multi-transit light curves. To achieve this, we implement a new neural network inspired by Transformers to directly process Full Frame Image (FFI) light curves to detect exoplanet transits. Transformers, originally developed for natural language processing, have recently demonstrated significant success in capturing long-range dependencies compared to previous approaches focused on sequential data. This ability allows us to employ multi-head self-attention to identify exoplanet transit signals directly from the complete light curves, combined with background and centroid time series, without requiring prior transit parameters. The network is trained to learn characteristics of the transit signal, like the dip shape, which helps distinguish planetary transits from other variability sources. Our model successfully identified 214 new planetary system candidates, including 122 multi-transit light curves, 88 single-transit and 4 multi-planet systems from TESS sectors 1-26 with a radius > 0.27 $R_{\mathrm{Jupiter}}$, demonstrating its ability to detect transits regardless of their periodicity.

[Arxiv](https://arxiv.org/abs/2502.07542)
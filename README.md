# Awesome-papers

## FP8 training

| 年份 | 标题 | 简介 |
| -- | -- | -- |
|2022.09|[FP8 FORMATS FOR DEEP LEARNING](https://arxiv.org/pdf/2209.05433)|FP8 的介绍|
|2023.12| [MSAMP](https://arxiv.org/pdf/2310.18313)| benchmark 低精度 optim 与 fp8 weight在语言模型中的影响|
| 2024.05 | [To FP8 and Back Again: Quantifying the Effects of Reducing Precision on LLM Training Stability](https://arxiv.org/html/2405.18710v1) | 对指数和尾数做了详细的消融，指数对稳定性影响很大，尾数相对较小，对FP8 train 评价整体偏负面｜


## llama4 series
| 年份 | 标题 | 简介 |
| -- | -- | -- |
|2023.07|[Scalable-Softmax Is Superior for Attention](https://arxiv.org/pdf/2501.19399)|给softmax加参数，使其更加平滑，加速训练，但效率未做测评，没有FA2、3加持应该不好用|
|2023.11|[Rope](https://arxiv.org/pdf/2104.09864)|相对位置编码，大模型基石|
|2023.11|[The Impact of Positional Encoding on Length Generalization in Transformers](https://arxiv.org/pdf/2305.19466)| NoPE, 提出观点，不加位置编码的情况下，会自动学习成相对位置编码, 直觉上感觉没有rope靠谱|


## 视频相关paper
| 年份 | 标题 | 简介 |
| -- | -- | -- |
|2024.05|[Scaling Rectified Flow Transformers for High-Resolution Image Synthesis](SD3 MMDIT)| wip |

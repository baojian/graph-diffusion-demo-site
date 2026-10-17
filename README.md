# 图与语言的动态扩散

| 演示 | 在线访问 | 离线文件 |
| --- | --- | --- |
| 图上的热扩散 | [打开演示](https://baojian.github.io/graph-diffusion-demo-site/) | `index.html` |
| 扩散语言模型与 Semantic DLM+ | [打开演示](https://baojian.github.io/graph-diffusion-demo-site/language/) | `language/index.html` |

图演示从单节点热源出发，可以切换图结构、调节桥、观察传播与稳定梯度。
语言演示包含逐步去噪、AR 调度与假设成本对照、转移核、语义频率惩罚和论文结果。

每个 HTML 都内嵌全部 CSS、SVG 和 JavaScript，下载后可独立离线打开。
页间导航和论文链接需要联网。语言动画是教学示意；概率实验使用手工小模型，
表格对应论文已报告结果，不是真实大模型推理或速度测试。

本仓库是公开网页的发布副本，通过 GitHub Pages 从 `main` 根目录发布。
论文：[Semantic DLM+](https://arxiv.org/abs/2606.15327v1)。

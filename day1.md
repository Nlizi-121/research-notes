\# Day 1 科研环境启动日



\## 今天完成

\- \[x] Git 配置与 GitHub 首次 push

\- \[x] Miniconda 安装（RTX 3050，4GB 显存）

\- \[x] 创建 `research` 环境（Python 3.11.16）

\- \[x] 安装 PyTorch 2.1.2 + CUDA 12.1

\- \[x] 验证 GPU 可用：`torch.cuda.is\_available() -> True`



\## 环境信息

\- GPU: NVIDIA GeForce RTX 3050 (4GB)

\- CUDA Version: 13.4（驱动）

\- PyTorch: 2.1.2+cu121

\- 工作区路径: D:\\research



\## 我遇到的问题

1\. `git clone` 时连不上 GitHub，通过多次重试和浏览器授权解决了。

2\. `conda create` 报错，因为输入了 `python=3.11.y`（多了空格和字母），修正后解决。

3\. 系统自带 Python 3.14 与 Conda 发生冲突，通过建立独立虚拟环境 `research` 隔离解决。



\## 明天计划

1\. 读一篇联邦学习安全/AI安全综述论文

2\. 找一个带代码的论文项目

3\. 学会用 Agent（Claude/Codex）分析项目结构


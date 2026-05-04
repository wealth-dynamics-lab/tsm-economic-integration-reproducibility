# TSM Economic Integration Degree Framework — Reproducibility Package

**Repository for Chapters 7 & 8** of the paper  
*"Economic Integration Degree: From Dissipative Structures and Two-State Mathematics to Three-Layer Causal Integration in Economic Systems"*

This repository provides full reproducibility for:
- Chapter 7: Constrained Variational Optimization Algorithm
- Chapter 8: Empirical three-layer validation (6 core figures)

**Only author-derived open data and code are included.** Restricted raw data are excluded (see Appendix E).

## Folder Structure
- `code/` — All Python scripts (Fig 8.1–8.6 + algorithm)
- `data/` — Author-curated derived summary data
- `data/raw/` — Place restricted raw files here (not uploaded to GitHub)
- `output/` — Generated 300 dpi figures
- `docs/` — Appendix D & E (Markdown)

## Quick Start (Web Version)
1. Download the files from this repository.
2. Place your derived data files into the `data/` folder.
3. Place restricted raw data (WIOD, full WID, Edelman PDFs, etc.) into `data/raw/` (download from official sources).
4. Run the scripts locally: `python code/fig8_1.py`

## Available Scripts
- `code/algorithm_constraint_variation.py` — Chapter 7 core algorithm
- `code/fig8_1.py` — Figure 8.1: CRJ Distribution and 12.0 Threshold
- `code/fig8_2.py` — Figure 8.2: Wealth Differentiation Trends (2007–2019)
- `code/fig8_3.py` — Figure 8.3: WIOD 2014 Meso-Level Validation
- `code/fig8_4.py` — Figure 8.4: Three-Layer Synchronization Timeline
- `code/fig8_5.py` — Figure 8.5: ρ Proxy & τ Relationship
- `code/fig8_6.py` — Figure 8.6: ρ–CRJ–τ Phase Transition Law

## Data Placement
Put the following files in `data/`:
- 图1数据.csv
- PSID-SCF.xlsx
- psid_wealth_ratios.csv
- wid_crj_trends_2000_2023.csv

## License
MIT License

**Questions?** Open an Issue.

# TSM经济整合度框架 —— 可复现性软件包

**本仓库用于论文第7章和第8章的结果复现**  
论文标题：《经济整合度：从耗散结构和两态数学到经济系统的三层因果整合》

本仓库提供以下内容的**完整可复现材料**：
- 第7章：约束变分优化算法（Constrained Variational Optimization）
- 第8章：三层实证验证（6张核心图表）

**仅包含作者自行整理的可开源数据和代码**。受限原始数据未纳入仓库（详见论文附录E）。

## 仓库文件夹结构
- `code/` —— 全部Python脚本（第7章算法 + 第8章6张图表生成代码）
- `data/` —— 作者自行整理的衍生汇总数据（可安全共享）
- `data/raw/` —— 放置受限原始数据（WIOD、WID完整文件、Edelman报告等），**不会上传到GitHub**
- `output/` —— 生成的300 dpi出版级图表
- `docs/` —— 附录D与附录E的Markdown版本

## 快速开始（网页端用户）
1. 从本仓库下载所有文件。
2. 将作者衍生数据文件放入 `data/` 文件夹。
3. 将受限原始数据（WIOD、完整WID、Edelman报告等）从官方渠道下载后放入 `data/raw/` 文件夹（详见论文附录E）。
4. 在本地运行脚本：
   ```bash
   python code/fig8_1.py

   可用脚本列表

code/algorithm_constraint_variation.py —— 第7章核心算法（约束变分优化）
code/fig8_1.py —— Figure 8.1: CRJ分布与12.0阈值验证
code/fig8_2.py —— Figure 8.2: 2007–2019财富分化趋势
code/fig8_3.py —— Figure 8.3: WIOD 2014中观层验证
code/fig8_4.py —— Figure 8.4: 三层同步时间线
code/fig8_5.py —— Figure 8.5: ρ代理变量构建与τ关系
code/fig8_6.py —— Figure 8.6: ρ–CRJ–τ三元相变律

数据放置要求
请将以下文件放入 data/ 文件夹：

图1数据.csv
PSID-SCF.xlsx
psid_wealth_ratios.csv
wid_crj_trends_2000_2023.csv

环境依赖
安装命令：
Bashpip install -r requirements.txt
许可协议
MIT License（详见 LICENSE 文件）
引用方式
如使用本仓库，请引用论文并链接回本仓库。
问题或建议？ 请在Issues中提出。

最后更新：2026年5月

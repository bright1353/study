# 信用卡欺诈检测：中文源码逐行精读

围绕 [Fraud Detection Handbook](https://fraud-detection-handbook.github.io/fraud-detection-handbook/) 制作的中文学习辅助资料。按原 Notebook 的顺序保留代码，并解释语法、输入输出与关键数据变化。

## 怎么开始

### 在 GitHub 上直接阅读

打开 [客户资料与模拟交易的中文精读 Notebook](精读笔记本/Chapter_3_GettingStarted/SimulatedDataset.精读.ipynb)，按单元格阅读。GitHub 通常可预览 Notebook；文件较大时，建议下载后用下面的网页阅读。

### 下载后离线阅读（推荐）

1. 点击仓库上方绿色 **Code** 按钮，再点击 **Download ZIP**。
2. 解压下载的文件。
3. 双击 **开始精读.html**，用浏览器打开。
4. 先进入“客户资料生成函数”，依次理解 `append → DataFrame → return`。

网页中的目录、原代码、逐行说明、图片和公式均可离线阅读。GitHub 仓库中的 HTML 文件用于下载后阅读，仓库链接本身不等于已经开通阅读网站。

## 每段怎样学

先看“这格解决什么”和“执行前／执行后”，再对照原代码看中文解释。遇到括号、参数或名称不懂，展开该行的“符号与名称”。关键函数的小数据例子用于跟踪变化，原书保存的输出单独标记。

不必一开始运行整本代码。阅读副本中的代码仍然是真实程序，实际执行前应理解它的数据下载、训练和文件保存行为。

## 内容

- 21 份原始 Notebook，687 个代码单元格，8,080 行原代码。
- 6,414 行非空代码有静态逐行解释。
- 218 个代码单元格附算法与数据状态专项补注，包含同源码的明确标注复用。
- 模拟数据、特征工程、基准模型、指标、时间验证、模型选择、不平衡学习与深度学习。

| 文件或目录 | 用途 |
| --- | --- |
| [开始精读.html](开始精读.html) | 下载后用浏览器打开的课程首页 |
| [章节](章节/) | 各本 Notebook 的网页解析 |
| [精读笔记本](精读笔记本/) | 插入中文说明的 `.ipynb` 阅读副本 |
| [原书资源](原书资源/) | 原作者说明、图片和公共函数，供对照 |
| [核对结果.txt](核对结果.txt) | 源码、输出与链接核对范围 |

本资料主要训练 Python、pandas、NumPy、统计和机器学习能力；SQL 仅有可迁移的分析思路，并非完整 SQL 课程。

## 验证与限制

原代码、原执行计数和保存输出均保留并核对。本次制作没有运行原教材或重新训练模型；历史输出不是本次执行结果，手工例子也不是程序实际运行输出。原书包含旧库接口和特定实验假设，已发现的问题在对应解析里标注。

中文逐行层包含静态语法解析和专项教学补注，适合辅助理解，仍应对照原代码核查。真实业务训练数据并非全部公开。

## 来源与许可

原作者：Yann-Aël Le Borgne、Wissam Siblini、Bertrand Lebichot、Gianluca Bontempi。

- [原书网站](https://fraud-detection-handbook.github.io/fraud-detection-handbook/)
- [原书仓库](https://github.com/Fraud-Detection-Handbook/fraud-detection-handbook)
- 原书代码遵循 GPL v3，见 [原书许可全文](LICENSE-原书.txt)。
- 原书文字、图片及本项目新增中文教学改编遵循 [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)。中文补注属于新增改编，并非原作者审定或背书的版本。
- 离线 MathJax 依 Apache-2.0 分发，见 [MathJax 许可](assets/LICENSE-MathJax.txt)。

整理日期：2026-09-30。

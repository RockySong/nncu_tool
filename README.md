# nncu_tool
NN toolkit for MCU，这是一套完整的工具集，用于在NXP Cortex-M核器件上部署深度学习模型，有以下特点：

- 配合我们改进和扩展过的CMSIS-NN库使用
- 模型量化与转换工具
- 测试向量制作工具
- GUI界面
- 附带示例与迷你数据集
- 量化质量测试工具
- 转换后模型的解释器
- MCU测试工程与更新工具
- 详细的用户指南

这里包含分割的压缩包，请把它们统一解到**同一个**目录下(**例如都解压到当前目录**)，哪怕它们内部包含相同的文件夹（内容没有交集）。

| file name          | usage                                                        |
| ------------------ | ------------------------------------------------------------ |
| nncu_datasets#.zip | 包含了多份示例所使用的迷你数据集。因github单个文件不能超过100MB故分割 |
| nncu_examples.7z   | 示例模型，配置文件，以及转换后的NNCU模型                     |
| nncu_main.7z       | 可执行文件与脚本，以及文档。这个文件在版本升级时是变化最快的 |
| nncu_py_env.7z     | Python环境，包含了全部依赖。一般您只需下载一次。             |
| nncu_graphviz.7z   | Graphviz包，用于可视化模型结构。您亦可使用"Netron"软件打开模型文件以观察结构 |

合体的压缩包也可以从以下百度网盘地址下载：
https://pan.baidu.com/s/1eQADEHg8UVhTsZWT_lRRgw

### English version

NN toolkit for MCU，a full set of tools to deploy deep learning models for NXP Cortex-M devices, highlights as below.

- Work with the CMSIS-NN library (with our extensions and improvements)
  Model quantization and conversion
  Test vector utility
  GUI interface
  Examples and mini datasets
  Quantization quality test utility
  Interpreter (Inference engine) for converted model
  MCU test project and updater utility
  Detailed user manual documentation

This repo contains the split parts, extract them all into the **SAME** folder (such as the current folder), even if they have the same folders (contents are not overlapped though):

| file name          | usage                                                        |
| ------------------ | ------------------------------------------------------------ |
| nncu_datasets#.zip | Multiple mini datasets. Split due to the 100MB/file limit of github |
| nncu_examples.7z   | example models, configurations, and converted NNCU models    |
| nncu_main.7z       | Main executables and scripts, this file is the mainly changed one when a new version is updated |
| nncu_py_env.7z     | Python environment with all dependencies, usually you only need to download only once |
| nncu_graphviz.7z   | Graphviz package to visualize model graphs, you can also use "Netron" software to open model files to view their graphs |

The combined  all-in-one package can be downloaded here:
https://pan.baidu.com/s/1eQADEHg8UVhTsZWT_lRRgw

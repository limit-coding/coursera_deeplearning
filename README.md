# Coursera Deep Learning 课程资料仓库

本仓库用于整理与保存 **Deep Learning Specialization（Andrew Ng）** 相关学习内容，包含：

- 各课程（C1~C5）的作业 Notebook
- 对应的公共测试脚本（`public_tests.py` 等）
- 实验所需的工具代码与数据集
- 课程配套的图片、课件素材与模型文件
- 个人学习笔记（`deeplearning-notes/`）

## 仓库内容说明

### 1) 作业与测试（assignment）

`assignment/` 目录按课程与周次组织，例如：

- `C1/W2A1`：Course 1 Week 2 Assignment 1
- `C2/W1A2`：Course 2 Week 1 Assignment 2
- `C4/W2A1`：Course 4 Week 2 Assignment 1

常见文件包括：

- `*.ipynb`：作业 Notebook
- `public_tests.py` / `test_utils.py` / `testCases.py`：测试脚本
- `datasets/`：数据集
- `images/`：课程讲义与说明图片
- `*.h5`：模型或权重文件

### 2) 学习笔记（deeplearning-notes）

`deeplearning-notes/` 目录用于记录个人学习笔记、知识点整理与复习内容。

## 适用课程范围

该仓库对应 Deep Learning Specialization 的主线内容（常见目录为 `C1` 到 `C5`）：

- C1: Neural Networks and Deep Learning
- C2: Improving Deep Neural Networks
- C3: Structuring Machine Learning Projects
- C4: Convolutional Neural Networks
- C5: Sequence Models

## 使用方式（本地）

1. 克隆仓库
2. 使用 Python 环境（建议 `venv`/`conda`）
3. 安装对应作业依赖（若目录内有 `requirements.txt`）
4. 用 Jupyter 打开对应 `*.ipynb` 完成练习

## 说明

- 本仓库主要用于学习与复现课程实验流程。
- 目录中可能包含较大的数据或模型文件（如 `*.h5`），推送到 GitHub 时可能出现大文件告警。
- 请遵守课程平台与学术诚信要求，合理使用作业与答案内容。

# Graph-CAD

<div align="center">

## Learning Hierarchical and Geometry-Aware Graph Representations for Text-to-CAD

[![Project Status](https://img.shields.io/badge/Project%20Page-TODO-6e7781.svg)](#)
[![Paper](https://img.shields.io/badge/Paper-OpenReview-b31b1b.svg)](https://openreview.net/pdf?id=oKMomThD6n)
[![Official Code](https://img.shields.io/badge/Official%20Code-GitHub-1f6feb.svg)](https://github.com/EESJGong/Graph-CAD)
[![Model](https://img.shields.io/badge/Model-ModelScope-ff8c00.svg)](https://modelscope.cn/models/JackeySmile/graph-cad)

**Shengjie Gong, Wenjie Peng, Hongyuan Chen, Gangyu Zhang, Yunqing Hu, Huiyuan Zhang, Shuangping Huang, Tianshui Chen**

[Official Code Repository](https://github.com/EESJGong/Graph-CAD) | [Paper](https://openreview.net/pdf?id=oKMomThD6n) | [Model Weights](https://modelscope.cn/models/JackeySmile/graph-cad)

</div>

---

<div align="center">

### [Go To The Official Graph-CAD Repository](https://github.com/EESJGong/Graph-CAD)

</div>

## Overview

This repository is the laboratory entry point for **Graph-CAD**, a graph-mediated Text-to-CAD framework for long-horizon CAD code generation.  
The actively maintained source code is hosted in the official project repository linked below.

## Jump To The Official Resources

- Official code repository: https://github.com/EESJGong/Graph-CAD
- Paper: https://openreview.net/pdf?id=oKMomThD6n
- Model weights: https://modelscope.cn/models/JackeySmile/graph-cad

## What Is Graph-CAD?

Graph-CAD introduces a hierarchical and geometry-aware intermediate graph for Text-to-CAD generation. Instead of directly decoding natural language into executable Blender `bpy` code, it decomposes the task into three stages:

1. predict a geometry-aware decomposition graph
2. convert the graph into CAD action sequences
3. generate executable Blender code

This design improves geometric fidelity, structural consistency, and geometric constraint satisfaction on complex CAD assemblies.

## Note

- This repository is maintained as the **lab-facing entry page**.
- For the latest code, setup instructions, evaluation scripts, figures, and updates, please visit the official repository:

## Citation

```bibtex
@inproceedings{gonglearning,
  title={Learning Hierarchical and Geometry-Aware Graph Representations for Text-to-CAD},
  author={Gong, Shengjie and Peng, Wenjie and Chen, Hongyuan and Zhang, Gangyu and Hu, Yunqing and Zhang, Huiyuan and Huang, Shuangping and Chen, Tianshui},
  booktitle={The Fourteenth International Conference on Learning Representations}
}
```

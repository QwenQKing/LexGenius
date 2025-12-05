# LexGenius: Evaluating Legal Intelligence in LLMs

<div align="center">

[![arXiv](https://img.shields.io/badge/arXiv-2512.04578-b31b1b.svg)](https://arxiv.org/abs/2512.04578)
[![Homepage](https://img.shields.io/badge/Homepage-LexGenius-0A66C2.svg)](https://github.com/QwenQKing/LexGenius)
[![Dataset](https://img.shields.io/badge/Dataset-HuggingFace-orange.svg)](https://huggingface.co/datasets/QwenQKing/LexGenius)
[![HF Models](https://img.shields.io/badge/HF%20Models-HuggingFace-yellow.svg)](https://huggingface.co/QwenQKing/LexGenius)
[![Email Contact](https://img.shields.io/badge/Contact-wenjinliu23%40outlook.com-red.svg?logo=microsoftoutlook&logoColor=white&style=flat)](mailto:wenjinliu23@outlook.com)

### **LexGenius**: An Expert-Level Benchmark for Large Language Models in Chinese Legal General Intelligence



</div>

---

## Overview

<div align="center">
  <img src="static/images/compare.png" width="60%"/>
</div>

**LexGenius** addresses a fundamental challenge in applying large language models (LLMs) to the legal domain—the absence of a professional, systematic, and trustworthy evaluation framework for legal intelligence. **LexGenius** is an **expert-level benchmarking suite** designed for Chinese legal scenarios, assessing LLMs across diverse legal tasks and capability dimensions to measure their understanding, reasoning, and normative application skills. Through rigorous dataset construction, realistic legal problem design, and human–LLM collaborative validation, **LexGenius** significantly enhances the objectivity, discriminability, and reliability of legal intelligence evaluation, offering actionable insights for model development, optimization, and deployment—without requiring users to build separate assessment systems.


<div align="center">
  <img src="static/images/Framwork.png" width="90%"/>
</div>

By integrating the **three-level structure of seven legal dimensions, eleven tasks, and twenty abilities**, **LexGenius** provides a **structured legal intelligence evaluation framework** that supports systematic capability assessment and cross-model comparative analysis across diverse large-scale LLMs.

## Experimental Results
**Comparison of the 12 SOTA LLMs with human experts on **7 core dimensions** of legal intelligence:**
<div align="center">
  <img src="static/images/7 core dimensions.png" width="50%"/>
</div>

**Performance of 12 LLMs and human experts on **11 legal tasks**, showing a significant gap between LLMs and humans:**
<div align="center">
  <img src="static/images/11 legal tasks.png" width="100%"/>
</div>

**Average ranking and average score ranking of the 12 SOTA LLMs in the **20 legal intelligence abilities**.:**
<div align="center">
  <img src="static/images/20 legal intelligence abilities.png" width="80%"/>
</div>


## BibTex

If you find this work is helpful for your research, please cite:

```bibtex
@misc{liu2025lexgeniusbenchmark,
      title={LexGenius: An Expert-Level Benchmark for Large Language Models in Chinese Legal General Intelligence},
      author={Wenjin Liu and Haoran Luo and Xin Feng and Xiang Ji and Lijuan Zhou and Rui Mao and Jiapu Wang and Shirui Pan and Erik Cambria},
      year={2025},
      eprint={2512.04578},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2512.04578}
}
```

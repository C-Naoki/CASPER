# Discovering Dynamic Causal Space for DAG Structure Learning

Official implementation of [Discovering Dynamic Causal Space for DAG Structure Learning](https://arxiv.org/pdf/2306.02822.pdf).

The paper has been accepted by **KDD 2023** 🔥.
## Introduction
Discovering causal structure from purely observational data (i.e., causal discovery), aiming to identify causal relationships among variables, is a fundamental task in machine learning. The recent invention of differentiable score-based DAG learners is a crucial enabler, which reframes the combinatorial optimization problem into a differentiable optimization with a DAG constraint over directed graph space. Despite their great success, these cutting-edge DAG learners incorporate DAG-ness independent score functions to evaluate the directed graph candidates, lacking in considering graph structure. As a result, measuring the data fitness alone regardless of DAG-ness inevitably leads to discovering suboptimal DAGs and model vulnerabilities. Towards this end, we propose a dynamic causal space for DAG structure learning, coined CASPER, that integrates the graph structure into the score function as a new measure in the causal space to faithfully reflect the causal distance between estimated and ground truth DAG. CASPER revises the learning process as well as enhances the DAG structure learning via adaptive attention to DAG-ness. Grounded by empirical visualization, CASPER, as a space, satisfies a series of desired properties, such as structure awareness and noise robustness. Extensive experiments on both synthetic and real-world datasets clearly validate the superiority of our CASPER over the state-of-the-art causal discovery methods in terms of accuracy and robustness.

<div align="center">
  <img src="files/CASPER.png"/>
</div>

## Citation
If you found this work to be useful in your own research, please consider citing the following:
```
@inproceedings{liu2023discovering,
  author = {Fangfu Liu, Wenchang Ma, An Zhang, Xiang Wang, Yueqi Duan, Tat-Seng Chua},
  title = {Discovering Dynamic Causal Space for DAG Structure Learning},
  booktitle = {KDD},
  publisher = {{ACM}},
  year = {2023}
}
```

## Code
Comming soon.
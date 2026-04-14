<h1 align="center"><strong>ZARA</strong></h1>
<h1 align="center"><strong>
  Training-Free Motion Time-Series Reasoning via Evidence-Grounded LLM Agents
</strong></h1>
<h3 align="center">
  ACL 2026 Main Conference
</h3>
<p align="center">
  <a href='https://zechenli03.github.io/zechen-homepage/' target='_blank'>Zechen Li</a>&emsp;&emsp;
  <a href='https://scholar.google.com/citations?user=haLBEWwAAAAJ&hl=en' target='_blank'>Baiyu Chen</a>&emsp;&emsp;
  <a href='https://scholar.google.com/citations?user=KwhLl7IAAAAJ&hl' target='_blank'>Hao Xue</a>&emsp;&emsp;
  <a href='https://fsalim.github.io' target='_blank'>Flora D. Salim</a>
  <br><br>
  University of New South Wales, Sydney<br/>
  <br><br>
  <a href="https://arxiv.org/abs/2508.04038">
    <img src="https://img.shields.io/badge/arXiv-2508.04038-b31b1b.svg" alt="arXiv">
  </a>
</p>


------
📝 We are currently organizing the code and writing a detailed tutorial to help you build your own ZARA agent for human activity recognition. Stay tuned for updates!


## 🌟 Overview

**ZARA** (Z̲ero-training A̲ctivity R̲easoning A̲gents) is a **training-free, evidence-grounded LLM agent framework** for motion time-series reasoning. It combines **statistically grounded domain knowledge**, **multi-sensor retrieval-augmented evidence**, and **hierarchical multi-agent reasoning** to classify motion sensor data with transparent, human-readable rationales—without fine-tuning or task-specific classifiers.

<div style="text-align: center;">
  <img src="asset/ZARA.png" alt="zara" width=100% >
</div>


### 🔑 Key Features

- **Training-Free HAR Inference**: ZARA performs human activity recognition without task-specific fine-tuning or classifier training, enabling plug-and-play deployment in parameter-frozen settings.
- **Evidence-Grounded Reasoning**: Instead of relying on black-box projections, ZARA grounds LLM decisions in retrieved signal evidence and statistically derived feature priors.
- **Pairwise Knowledge Base**: ZARA builds an activity-pair knowledge base that captures discriminative motion properties as interpretable linguistic priors.
- **Multi-Sensor Retrieval**: Placement-specific retrieval and rank fusion provide class-balanced, query-relevant evidence across heterogeneous wearable sensors.
- **Hierarchical Agentic Workflow**: Specialized agents perform feature selection, evidence pruning, and final decision reasoning to produce concise, evidence-backed rationales.
- **Strong Generalization**: ZARA achieves state-of-the-art performance across 8 HAR benchmarks, with robust transfer across unseen subjects and heterogeneous sensor domains.

## 🌍 Citation

If you find this repository useful for your research, please cite our paper:

```
@article{li2026zara,
  title={ZARA: Training-Free Motion Time-Series Reasoning via Evidence-Grounded LLM Agents},
  author={Zechen Li and Baiyu Chen and Hao Xue and Flora D. Salim},
  journal={arXiv preprint arXiv:2508.04038},
  year={2026},
  url={https://arxiv.org/abs/2508.04038}
}
```

## 📄 License

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/80x15.png" /></a>
<br />
This work is under the <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.


## 📩 Contact

If you have any questions or suggestions, feel free to contact Zechen at `zechen.li(at)unsw(dot)edu(dot)au`.


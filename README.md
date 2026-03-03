# FORLER: Federated Offline Reinforcement Learning with Q-Ensemble and Actor Rectification

[![Paper](https://img.shields.io/badge/Paper-arXiv:2602.02055-B31B1B.svg)](https://arxiv.org/abs/2602.02055)
[![Conference](https://img.shields.io/badge/Accepted_by-ICC-blue.svg)]()
[![Code Status](https://img.shields.io/badge/Code-Coming_Soon-orange.svg)]()

> 🚧 **Code Coming Soon!** 🚧
> 
> The official PyTorch implementation for **FORLER** is currently being cleaned up and prepared for public release. We plan to release the code very soon. 
> 
> ⭐️ **Please star this repository to get notified when the code is available!** ⭐️



## 📖 Abstract

In Internet-of-Things (IoT) systems, federated learning enables parallel policy training without sharing raw data. However, online interactions can be risky and costly, motivating **Offline Federated Reinforcement Learning (FRL)**. Despite its promise, offline FRL often suffers from low-quality, heterogeneous data, leading to local optima and "policy pollution" where suboptimal local policies degrade the aggregated global model.

We present **FORLER**, a novel framework combining:
1. **Server-side Q-Ensemble Aggregation**: Robustly merges device Q-functions to curb policy pollution and offload heavy computation from resource-constrained edge devices without compromising privacy.
2. **Device-side Actor Rectification**: Enriches policy gradients via a zeroth-order search for high-Q actions, guided by a bespoke regularizer.
3. **$\delta$-Periodic Strategy**: Further reduces local computation overhead.

FORLER provides theoretical safe policy improvement guarantees and consistently outperforms strong baselines under varying data quality and heterogeneity.

---

## ⚙️ Installation & Usage (Coming Soon)
Detailed instructions for setting up the environment, downloading datasets, and running the federated training scripts will be provided here once the code is released.

---

## 📝 Citation

If you find our work useful in your research, please consider citing our paper:

```bibtex
@inproceedings{qiao2026forler,
  title={FORLER: Federated Offline Reinforcement Learning with Q-Ensemble and Actor Rectification},
  author={Qiao, Nan and Yue, Sheng},
  booktitle={IEEE International Conference on Communications (ICC)},
  year={2026},
  url={[https://arxiv.org/abs/2602.02055](https://arxiv.org/abs/2602.02055)}
}

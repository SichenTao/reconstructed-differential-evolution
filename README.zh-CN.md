# Reconstructed Differential Evolution（RDE）系列：IEEE CEC 2024 亚军，IEEE CEC 2025 与 IEEE WCCI/CEC 2026 第 1 名（[RDE 论文：arXiv:2404.16280](https://arxiv.org/abs/2404.16280)）

<p align="center">
  <a href="README.md">English</a> |
  <strong>中文</strong> |
  <a href="README.ja.md">日本語</a>
</p>

本仓库是 RDE 系列的入口。RDE 系列是陶思晨及合作者 2024 至 2026 年参加 IEEE CEC / WCCI 数值优化竞赛的差分进化求解器。本仓库最初是 2024 年项目的公开入口；现在代码按年份放在各自的仓库里，各赛道是仓库下的子目录。

## 系列一览

| 年份 | 名称 | 竞赛 | 结果 | 仓库 | 论文 |
| --- | --- | --- | --- | --- | --- |
| 2024 | RDE | IEEE WCCI / CEC 2024 数值优化竞赛，带边界约束的单目标赛道 | 亚军奖 | [RDE](https://github.com/SichenTao/RDE) | [arXiv:2404.16280](https://arxiv.org/abs/2404.16280) |
| 2025 | RDEx | IEEE CEC 2025 数值优化竞赛，四个赛道（SOP、CSOP、MOP、CMOP） | 四个赛道全部第 1 名（U-score） | [RDEx](https://github.com/SichenTao/RDEx) | [SOP](https://arxiv.org/abs/2603.27089), [CSOP](https://arxiv.org/abs/2603.27090), [MOP](https://arxiv.org/abs/2603.27092), [CMOP](https://arxiv.org/abs/2604.03708) |
| 2026 | RDE26 | IEEE WCCI / CEC 2026 数值优化竞赛，四个赛道（SOP、CSOP、MOP、CMOP） | 四个赛道全部第 1 名 | [RDE26](https://github.com/SichenTao/RDE26) | 暂无，见该仓库 |

赛道目录：RDEx：[RDEx_SOP](https://github.com/SichenTao/RDEx/tree/main/RDEx_SOP), [RDEx_CSOP](https://github.com/SichenTao/RDEx/tree/main/RDEx_CSOP), [RDEx_MOP](https://github.com/SichenTao/RDEx/tree/main/RDEx_MOP), [RDEx_CMOP](https://github.com/SichenTao/RDEx/tree/main/RDEx_CMOP)。RDE26：[RDE26_SOP](https://github.com/SichenTao/RDE26/tree/main/RDE26_SOP), [RDE26_CSOP](https://github.com/SichenTao/RDE26/tree/main/RDE26_CSOP), [RDE26_MOP](https://github.com/SichenTao/RDE26/tree/main/RDE26_MOP), [RDE26_CMOP](https://github.com/SichenTao/RDE26/tree/main/RDE26_CMOP)。

每个仓库都有自己的 README（英文、中文、日文）、运行脚本、`LICENSE` 和 `CITATION.cff`；名次和分数写在该年份仓库的 README 里。

## 引用

请使用所用仓库的 “Cite this repository” 按钮；有论文的算法请同时引用其论文。本系列的论文：

```bibtex
@misc{tao2024efficient,
  title = {An Efficient Reconstructed Differential Evolution Variant by Some of the Current State-of-the-art Strategies for Solving Single Objective Bound Constrained Problems},
  author = {Tao, Sichen and Zhao, Ruihan and Wang, Kaiyu and Gao, Shangce},
  year = {2024},
  eprint = {2404.16280},
  archivePrefix = {arXiv},
  primaryClass = {cs.NE},
  doi = {10.48550/arXiv.2404.16280}
}

@misc{tao2026rdexsop,
  title = {RDEx-SOP: Exploitation-Biased Reconstructed Differential Evolution for Fixed-Budget Bound-Constrained Single-Objective Optimization},
  author = {Tao, Sichen and Yang, Yifei and Zhao, Ruihan and Wang, Kaiyu and Liu, Sicheng and Gao, Shangce},
  year = {2026},
  eprint = {2603.27089},
  archivePrefix = {arXiv},
  primaryClass = {cs.NE},
  doi = {10.48550/arXiv.2603.27089}
}

@misc{tao2026rdexcsop,
  title = {RDEx-CSOP: Feasibility-Aware Reconstructed Differential Evolution with Adaptive epsilon-Constraint Ranking},
  author = {Tao, Sichen and Yang, Yifei and Zhao, Ruihan and Wang, Kaiyu and Liu, Sicheng and Gao, Shangce},
  year = {2026},
  eprint = {2603.27090},
  archivePrefix = {arXiv},
  primaryClass = {cs.NE},
  doi = {10.48550/arXiv.2603.27090}
}

@misc{tao2026rdexmop,
  title = {RDEx-MOP: Indicator-Guided Reconstructed Differential Evolution for Fixed-Budget Multiobjective Optimization},
  author = {Tao, Sichen and Yang, Yifei and Zhao, Ruihan and Wang, Kaiyu and Liu, Sicheng and Gao, Shangce},
  year = {2026},
  eprint = {2603.27092},
  archivePrefix = {arXiv},
  primaryClass = {cs.NE},
  doi = {10.48550/arXiv.2603.27092}
}

@misc{tao2026rdexcmop,
  title = {RDEx-CMOP: Feasibility-Aware Indicator-Guided Differential Evolution for Fixed-Budget Constrained Multiobjective Optimization},
  author = {Tao, Sichen and Yang, Yifei and Zhao, Ruihan and Wang, Kaiyu and Liu, Sicheng and Gao, Shangce},
  year = {2026},
  eprint = {2604.03708},
  archivePrefix = {arXiv},
  primaryClass = {cs.NE},
  doi = {10.48550/arXiv.2604.03708}
}
```

## 早先的地址

| 早先的地址 | 现在 |
| --- | --- |
| `IEEE-WCCI-CEC-2024-Competition-RDE` | [RDE](https://github.com/SichenTao/RDE) |
| `IEEE-CEC-2025-Competition-RDEx-Series` | [RDEx](https://github.com/SichenTao/RDEx) |
| `RDE26-SOP` | [RDE26](https://github.com/SichenTao/RDE26)，目录 `RDE26_SOP` |
| `RDE26-CSOP`、`RDE26-MOP`、`RDE26-CMOP`（已归档） | [RDE26](https://github.com/SichenTao/RDE26)，目录 `RDE26_CSOP`、`RDE26_MOP`、`RDE26_CMOP` |

GitHub 会把改名仓库的旧地址跳转到新地址。

## 相关

[RDE-SOR](https://github.com/SichenTao/RDE-SOR) 是另一支团队的另一种算法，2026 年同样参加 BC-MOP 赛道，保留在独立仓库中。

## 许可证

[MIT](LICENSE)。

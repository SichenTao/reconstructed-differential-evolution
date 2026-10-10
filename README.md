# Reconstructed Differential Evolution (RDE) series: Runner-Up at IEEE CEC 2024, Rank 1 at IEEE CEC 2025 and IEEE WCCI/CEC 2026 ([RDE paper: arXiv:2404.16280](https://arxiv.org/abs/2404.16280))

<p align="center">
  <strong>English</strong> |
  <a href="README.zh-CN.md">中文</a> |
  <a href="README.ja.md">日本語</a>
</p>

This repository is the entry point to the RDE series, the differential evolution solvers that Sichen Tao and co-authors entered in the IEEE CEC / WCCI numerical optimization competitions from 2024 to 2026. It started as the public entry of the 2024 project; the code now lives in one repository per year, each with its tracks as sub-directories.

## The series

| Year | Name | Competition | Result | Repository | Paper |
| --- | --- | --- | --- | --- | --- |
| 2024 | RDE | IEEE WCCI / CEC 2024 numerical optimization competition, bound-constrained single-objective track | Runner-Up Award | [RDE](https://github.com/SichenTao/RDE) | [arXiv:2404.16280](https://arxiv.org/abs/2404.16280) |
| 2025 | RDEx | IEEE CEC 2025 numerical optimization competitions, four tracks (SOP, CSOP, MOP, CMOP) | Rank 1 in all four tracks (U-score) | [RDEx](https://github.com/SichenTao/RDEx) | [SOP](https://arxiv.org/abs/2603.27089), [CSOP](https://arxiv.org/abs/2603.27090), [MOP](https://arxiv.org/abs/2603.27092), [CMOP](https://arxiv.org/abs/2604.03708) |
| 2026 | RDE26 | IEEE WCCI / CEC 2026 numerical optimization competition, four tracks (SOP, CSOP, MOP, CMOP) | Rank 1 in all four tracks | [RDE26](https://github.com/SichenTao/RDE26) | none yet; see the repository |

Track directories: RDEx: [RDEx_SOP](https://github.com/SichenTao/RDEx/tree/main/RDEx_SOP), [RDEx_CSOP](https://github.com/SichenTao/RDEx/tree/main/RDEx_CSOP), [RDEx_MOP](https://github.com/SichenTao/RDEx/tree/main/RDEx_MOP), [RDEx_CMOP](https://github.com/SichenTao/RDEx/tree/main/RDEx_CMOP). RDE26: [RDE26_SOP](https://github.com/SichenTao/RDE26/tree/main/RDE26_SOP), [RDE26_CSOP](https://github.com/SichenTao/RDE26/tree/main/RDE26_CSOP), [RDE26_MOP](https://github.com/SichenTao/RDE26/tree/main/RDE26_MOP), [RDE26_CMOP](https://github.com/SichenTao/RDE26/tree/main/RDE26_CMOP).

Each repository has its own README (English, Chinese, Japanese), run scripts, `LICENSE` and `CITATION.cff`; ranks and scores are given in the README of the repository of that year.

## Citation

Use the "Cite this repository" button of the repository you use, and cite the paper of the algorithm where one exists. The papers of the series:

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

## Earlier addresses

| Earlier address | Now |
| --- | --- |
| `IEEE-WCCI-CEC-2024-Competition-RDE` | [RDE](https://github.com/SichenTao/RDE) |
| `IEEE-CEC-2025-Competition-RDEx-Series` | [RDEx](https://github.com/SichenTao/RDEx) |
| `RDE26-SOP` | [RDE26](https://github.com/SichenTao/RDE26), directory `RDE26_SOP` |
| `RDE26-CSOP`, `RDE26-MOP`, `RDE26-CMOP` (archived) | [RDE26](https://github.com/SichenTao/RDE26), directories `RDE26_CSOP`, `RDE26_MOP`, `RDE26_CMOP` |

GitHub redirects the earlier addresses of renamed repositories to the new ones.

## Related

[RDE-SOR](https://github.com/SichenTao/RDE-SOR) is a separate algorithm by a different team, also entered in the BC-MOP track in 2026. It is kept in its own repository.

## License

[MIT](LICENSE).

# Reconstructed Differential Evolution（RDE）シリーズ：IEEE CEC 2024 準優勝、IEEE CEC 2025 と IEEE WCCI/CEC 2026 で第 1 位（[RDE 論文：arXiv:2404.16280](https://arxiv.org/abs/2404.16280)）

<p align="center">
  <a href="README.md">English</a> |
  <a href="README.zh-CN.md">中文</a> |
  <strong>日本語</strong>
</p>

このリポジトリは RDE シリーズの入り口です。RDE シリーズは、陶思晨と共著者が 2024 年から 2026 年に IEEE CEC / WCCI の数値最適化コンペティションへ出場させた差分進化ソルバー群です。もともとは 2024 年のプロジェクトの公開入り口でした。現在のコードは年ごとのリポジトリにあり、各トラックはその下のサブディレクトリです。

## シリーズ一覧

| 年 | 名称 | コンペティション | 結果 | リポジトリ | 論文 |
| --- | --- | --- | --- | --- | --- |
| 2024 | RDE | IEEE WCCI / CEC 2024 数値最適化コンペティション、境界制約付き単一目的トラック | 準優勝賞 | [RDE](https://github.com/SichenTao/RDE) | [arXiv:2404.16280](https://arxiv.org/abs/2404.16280) |
| 2025 | RDEx | IEEE CEC 2025 数値最適化コンペティション、4 トラック（SOP、CSOP、MOP、CMOP） | 4 トラックすべてで第 1 位（U-score） | [RDEx](https://github.com/SichenTao/RDEx) | [SOP](https://arxiv.org/abs/2603.27089), [CSOP](https://arxiv.org/abs/2603.27090), [MOP](https://arxiv.org/abs/2603.27092), [CMOP](https://arxiv.org/abs/2604.03708) |
| 2026 | RDE26 | IEEE WCCI / CEC 2026 数値最適化コンペティション、4 トラック（SOP、CSOP、MOP、CMOP） | 4 トラックすべてで第 1 位 | [RDE26](https://github.com/SichenTao/RDE26) | まだありません（リポジトリを参照） |

トラックのディレクトリ：RDEx：[RDEx_SOP](https://github.com/SichenTao/RDEx/tree/main/RDEx_SOP), [RDEx_CSOP](https://github.com/SichenTao/RDEx/tree/main/RDEx_CSOP), [RDEx_MOP](https://github.com/SichenTao/RDEx/tree/main/RDEx_MOP), [RDEx_CMOP](https://github.com/SichenTao/RDEx/tree/main/RDEx_CMOP)。RDE26：[RDE26_SOP](https://github.com/SichenTao/RDE26/tree/main/RDE26_SOP), [RDE26_CSOP](https://github.com/SichenTao/RDE26/tree/main/RDE26_CSOP), [RDE26_MOP](https://github.com/SichenTao/RDE26/tree/main/RDE26_MOP), [RDE26_CMOP](https://github.com/SichenTao/RDE26/tree/main/RDE26_CMOP)。

各リポジトリには、それぞれの README（英語・中国語・日本語）、実行スクリプト、`LICENSE`、`CITATION.cff` があります。順位とスコアはその年のリポジトリの README に記載しています。

## 引用

使用するリポジトリの「Cite this repository」ボタンを使い、論文があるアルゴリズムはその論文も引用してください。シリーズの論文：

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

## 以前のアドレス

| 以前のアドレス | 現在 |
| --- | --- |
| `IEEE-WCCI-CEC-2024-Competition-RDE` | [RDE](https://github.com/SichenTao/RDE) |
| `IEEE-CEC-2025-Competition-RDEx-Series` | [RDEx](https://github.com/SichenTao/RDEx) |
| `RDE26-SOP` | [RDE26](https://github.com/SichenTao/RDE26)、ディレクトリ `RDE26_SOP` |
| `RDE26-CSOP`、`RDE26-MOP`、`RDE26-CMOP`（アーカイブ済み） | [RDE26](https://github.com/SichenTao/RDE26)、ディレクトリ `RDE26_CSOP`、`RDE26_MOP`、`RDE26_CMOP` |

名前を変更したリポジトリの以前のアドレスは、GitHub が新しいアドレスへ転送します。

## 関連

[RDE-SOR](https://github.com/SichenTao/RDE-SOR) は、別のチームによる別のアルゴリズムで、2026 年に同じく BC-MOP トラックに出場しました。独立したリポジトリで管理しています。

## ライセンス

[MIT](LICENSE)。

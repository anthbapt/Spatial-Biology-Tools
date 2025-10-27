<div align="center">
  <img src="images/kcl_logo.png" width="125px">
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="images/sbf_logo.png" width="210px">
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</div>

<h1 align="center">
 Single Cell Spatial Transcriptomics Tools
</h1>

<div align="center">

  ![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white)
  ![Tools](https://img.shields.io/badge/Tools-150%2B-green)
  ![License](https://img.shields.io/badge/License-MIT-yellow)
  ![Updated](https://img.shields.io/badge/Last%20Updated-October%202025-orange)

</div>

---

<div align="center">

> **Note**: The following tools are Python-based and suitable for working with [**SpatialData**](https://spatialdata.scverse.org/en/stable/tutorials/notebooks/notebooks/examples/intro.html) objects or compatible objects such as [**AnnData**](https://anndata.readthedocs.io/en/stable/index.html) (used in Scanpy and Squidpy).

</div>

---

## Table of Contents

- [Quality Control](#-quality-control)
- [Segmentation](#segmentation)
- [Cell typing](#cell-typing)
- [Cell Deconvolution](#-cell-deconvolution)
- [Domain identification](#domain-identification)
- [Genes imputation](#genes-imputation)
- [Spatially variable genes](#spatially-variable-genes)
- [Cell-cell communications](#cell-cell-communications)
- [Dimension reduction](#dimension-reduction)
- [Multimodal integration](#multimodal-integration)
- [Foundation models](#foundation-models)
- [Other tools](#other-tools)
- [Contributors](#-contributors)

---

## 🔍 Quality Control

Tools for quality control and artifact detection in spatial transcriptomics data.

| Name       | Released | Documentation | Links |
| ---------- | -------  | ------------- | ----- |
| [SpatialQC](https://academic.oup.com/bioinformatics/article/40/8/btae458/7720780)    | 08/2024 | N/A | [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/mgy520/spatialQC)|
| [MerQuaCo](https://elifesciences.org/reviewed-preprints/105149)    | 03/2025 | N/A | [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/AllenInstitute/merquaco) |

---

## 🔬 Segmentation

Tools for cell segmentation and boundary detection in spatial transcriptomics data.

| Name       | Released | Documentation | Links |
| ---------- | -------  | ------------- | ----- |
| [sopa](https://www.nature.com/articles/s41467-024-48981-z)    | 06/2024 | [<img src="https://brand-guidelines.readthedocs.org/_images/logo-dark.png" width="20">](https://www.celltypist.org) | [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://gustaveroussy.github.io/sopa/) |
| [CellSAM](https://www.biorxiv.org/content/10.1101/2023.11.17.567630v5)    | 02/2025 | N/A | [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/vanvalenlab/cellsam) |
| [Segger](https://www.biorxiv.org/content/10.1101/2025.03.14.643160v1)    | 03/2025 | N/A | [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/EliHei2/segger_dev) |
| [BOMS](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0311458)   | 06/2025 | N/A | [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/sciai-lab/boms) |
| [Bering](https://www.nature.com/articles/s41467-025-60898-9)    | 07/2025 |[<img src="https://brand-guidelines.readthedocs.org/_images/logo-dark.png" width="20">](https://bering.readthedocs.io/en/latest/) | [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/jian-shu-lab/Bering) |

---

## 🏷️ Cell typing

Tools for annotating and classifying cell types in spatial data.

| Name       | Released | Documentation | Links |
| ---------- | -------  | ------------- | ----- |
| [TANGRAM](https://www.nature.com/articles/s41592-021-01264-7)    | 10/2021 | [<img src="https://brand-guidelines.readthedocs.org/_images/logo-dark.png" width="20">](https://tangram-sc.readthedocs.io/en/latest/) | [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/broadinstitute/Tangram) |
| [cell2location](https://www.nature.com/articles/s41587-021-01139-4)    | 01/2022 | [<img src="https://brand-guidelines.readthedocs.org/_images/logo-dark.png" width="20">](https://cell2location.readthedocs.io/en/latest/) | [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/BayraktarLab/cell2location/tree/master) |
| [cellTypist](https://www.science.org/doi/10.1126/science.abl5197)    | 05/2022 | [<img src="https://brand-guidelines.readthedocs.org/_images/logo-dark.png" width="20">](https://www.celltypist.org) | [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/Teichlab/celltypist) |
| [CellAnnotator](https://www.nature.com/articles/s41592-024-02235-4)   | 03/2024 | [<img src="https://brand-guidelines.readthedocs.org/_images/logo-dark.png" width="20">](https://cell-annotator.readthedocs.io/en/latest/) | [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/quadbio/cell-annotator?tab=readme-ov-file) |
| [Nico](https://www.nature.com/articles/s41467-024-54973-w)   | 12/2024 | [<img src="https://brand-guidelines.readthedocs.org/_images/logo-dark.png" width="20">](https://nico-sc-sp.readthedocs.io/en/latest/) | [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://pypi.org/project/nico-sc-sp/) |

---

## 🧩 Cell Deconvolution

Tools for deconvolving cell type composition from spatial transcriptomics data.

| Name       | Released | Documentation | Links |
| ---------- | -------  | ------------- | ----- |
| [SpatialcoGCN](https://academic.oup.com/bib/article/25/3/bbae130/7638268)   | 05/2024 | N/A | [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/wwYinYin/SpatialcoGCN)|
| [STdGCN](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-024-03353-0)    | 08/2024 | N/A | [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/luoyuanlab/stdgcn) |
| [SDePER](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-024-03416-2)    | 10/2024 | [<img src="https://brand-guidelines.readthedocs.org/_images/logo-dark.png" width="20">](https://az7jh2.github.io/SDePER/) | [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/az7jh2/SDePER) |
| [CLPLS](https://academic.oup.com/bib/article/26/1/bbaf052/8006047)    | 02/2025 | N/A | [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/LindsayMo/CLPLS_package) |
| [NODE](https://www.nature.com/articles/s42003-025-07625-8)   | 02/2025 | N/A | [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/wzdrgi/NODE) |
| [DECLUST](https://academic.oup.com/nar/article/53/14/gkaf714/8211932)    | 07/2025 | N/A | [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/Qingyueee/DECLUST)|

---

## 🗺️ Domain identification

Tools for identifying and clustering spatial domains and tissue structures.

| Name       | Released | Documentation | Links |
| ---------- | -------  | ------------- | ----- |
| [SpaGCN](https://www.nature.com/articles/s41592-021-01255-8)    | 10/2021 | N/A| [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/jianhuupenn/SpaGCN) |
| [STAGATE](https://www.nature.com/articles/s41467-022-29439-6)    | 04/2022 | [<img src="https://brand-guidelines.readthedocs.org/_images/logo-dark.png" width="20">](https://stagate.readthedocs.io/en/latest/index.html) | [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/zhanglabtools/STAGATE) |
| [CCST](https://www.nature.com/articles/s43588-022-00266-5)    | 06/2022 | N/A  |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/xiaoyeye/CCST)|
| [SpaceFlow](https://www.nature.com/articles/s41467-022-31739-w)    | 07/2022 | N/A  |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">]([https://github.com/JinmiaoChenLab/scTM](https://github.com/hongleir/SpaceFlow))|
| [DeepST](https://academic.oup.com/nar/article/50/22/e131/6761985)   | 12/2022 | N/A | [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/JiangBioLab/DeepST) |
| [GraphST](https://www.nature.com/articles/s41467-023-36796-3)    | 03/2023 | [<img src="https://brand-guidelines.readthedocs.org/_images/logo-dark.png" width="20">](https://deepst-tutorials.readthedocs.io/en/latest/) | [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/JinmiaoChenLab/GraphST) |
| [SPACEL](https://www.nature.com/articles/s41467-023-43220-3)  | 11/2023 | N/A | [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/QuKunLab/SPACEL) |
| [CellCharter](https://www.nature.com/articles/s41588-023-01588-4)    | 12/2023 | [<img src="https://brand-guidelines.readthedocs.org/_images/logo-dark.png" width="20">](https://cellcharter.readthedocs.io/en/latest/) | [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/CSOgroup/cellcharter) |
| [Banksy](https://www.nature.com/articles/s41588-024-01664-3)   | 02/2024 | N/A | [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/prabhakarlab/Banksy_py) |
| [SCGP](https://www.sciencedirect.com/science/article/pii/S266723752400211X?via%3Dihub)    | 08/2024 | N/A  |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://gitlab.com/enable-medicine-public/scgp/-/tree/main?ref_type=heads)|
| [SR-DGN](https://bmcgenomics.biomedcentral.com/articles/10.1186/s12864-024-11072-w)    | 11/2024 | N/A | [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/zhangdaoliang/SR-DGN) |
| [MAEST](https://academic.oup.com/bib/article/doi/10.1093/bib/bbaf086/8058890)    | 03/2025 | N/A | [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/clearlove2333/MAEST) |
| [SpaGT](https://www.sciencedirect.com/science/article/pii/S266723752400211X?via%3Dihub)    | 04/2025 | [<img src="https://brand-guidelines.readthedocs.org/_images/logo-dark.png" width="20">](https://spagt-tutorial.readthedocs.io/en/latest/)  |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/xy428/SpaGT)|

---

## 🧬 Genes imputation

Tools for imputing missing gene expression values in spatial datasets.

| Name       | Released | Documentation | Links |
| ---------- | -------  | ------------- | ----- |
| [SpaOTsc](https://www.nature.com/articles/s41467-020-15968-5)    | 04/2020 | N/A |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/zcang/SpaOTsc) |
| [SpaGE](https://academic.oup.com/nar/article/48/18/e107/5909530?login=true)   | 09/2020 | N/A |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/tabdelaal/SpaGE) |
| [novoSpaRc](https://www.nature.com/articles/s41596-021-00573-7)    | 08/2021 | N/A |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/rajewsky-lab/novosparc) |
| [TANGRAM](https://www.nature.com/articles/s41592-021-01264-7)    | 10/2021 | [<img src="https://brand-guidelines.readthedocs.org/_images/logo-dark.png" width="20">](https://tangram-sc.readthedocs.io/en/latest/) | [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/broadinstitute/Tangram) |
| [stMCDI](https://arxiv.org/abs/2403.10863)    | 03/2024 | N/A | [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/lhc17/stMCDI) |
| [stDiff](https://academic.oup.com/bib/article/25/3/bbae171/7646375)    | 04/2024 | N/A | [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/LiQian-XC/stDiff) |
| [SpotGF](https://www.sciencedirect.com/science/article/abs/pii/S2405471224002692)    | 09/2024 | N/A | [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/YangLabHKUST/SpotGF) |
| [stImpute](https://www.nature.com/articles/s42003-024-06964-2)    | 10/2024 | N/A | [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/Catchxu/stImpute) |
| [stGRL](https://bmcbiol.biomedcentral.com/articles/10.1186/s12915-025-02290-z)    | 01/2025 | N/A | [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/liuhong-jia/stGRL) |

---

## 📊 Spatially variable genes

Tools for identifying genes with spatial expression patterns.

| Name       | Released | Documentation | Links |
| ---------- | -------  | ------------- | ----- |
| [SpatialDE](https://www.nature.com/articles/nmeth.4636)    | 03/2018 | N/A |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/Teichlab/SpatialDE) |
| [Hotspot](https://www.sciencedirect.com/science/article/pii/S2405471221001149)   | 05/2021 |  [<img src="https://brand-guidelines.readthedocs.org/_images/logo-dark.png" width="20">](https://hotspot.readthedocs.io/en/latest/)  | [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">]([https://github.com/prabhakarlab/Banksy_py](https://github.com/yoseflab/hotspot)) |
| [SOMDE](https://academic.oup.com/bioinformatics/article/37/23/4392/6308937)   | 12/2021 | N/A | [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/XuegongLab/somde) |
| [SINFONIA](https://www.mdpi.com/2073-4409/12/4/604)    | 02/2023 |  [<img src="https://brand-guidelines.readthedocs.org/_images/logo-dark.png" width="20">](https://sinfonia-svg.readthedocs.io/en/latest/index.html) |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/BioX-NKU/SINFONIA) |
| [Maxspin](https://www.cell.com/cell-reports-methods/fulltext/S2667-2375(23)00136-4)    | 06/2023 |  N/A |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/dcjones/maxspin) |
| [SC2Spa](https://www.biorxiv.org/content/10.1101/2023.08.22.554277v1)    | 08/2023 |  N/A |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/linbuliao/SC2Spa?tab=readme-ov-file) |

---

## 💬 Cell-cell communications

Tools for analyzing intercellular communication and signaling pathways.

| Name       | Released | Documentation | Links |
| ---------- | -------  | ------------- | ----- |
| [CellphoneDB](https://www.nature.com/articles/s41586-018-0698-6)    | 11/2018 | [<img src="https://brand-guidelines.readthedocs.org/_images/logo-dark.png" width="20">](https://www.cellphonedb.org)  |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/ventolab/CellphoneDB)|
| [NATMI](https://www.nature.com/articles/s41467-020-18873-z)    | 10/2020 | N/A  |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/forrest-lab/NATMI/)|
| [Tensor cell2cell](https://www.nature.com/articles/s41467-022-31369-2)    | 06/2022 | [<img src="https://brand-guidelines.readthedocs.org/_images/logo-dark.png" width="20">](https://earmingol.github.io/cell2cell/)  |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/earmingol/cell2cell?tab=readme-ov-file)|
| [NCEM](https://www.nature.com/articles/s41587-022-01467-z)    | 10/2022 | [<img src="https://brand-guidelines.readthedocs.org/_images/logo-dark.png" width="20">](https://ncem.readthedocs.io/en/latest/)  |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/theislab/ncem)|
| [COMMOT](https://www.nature.com/articles/s41592-022-01728-4)    | 01/2023 | [<img src="https://brand-guidelines.readthedocs.org/_images/logo-dark.png" width="20">](https://commot.readthedocs.io/en/latest/index.html)  |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/zcang/COMMOT)|
| [Holonet](https://academic.oup.com/bib/article/24/6/bbad359/7306826)    | 11/2023 | [<img src="https://brand-guidelines.readthedocs.org/_images/logo-dark.png" width="20">](https://holonet-doc.readthedocs.io/en/latest/)  |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/lhc17/HoloNet)|
| [stLearn](https://www.nature.com/articles/s41467-023-43120-6)    | 11/2023 | [<img src="https://brand-guidelines.readthedocs.org/_images/logo-dark.png" width="20">](https://stlearn.readthedocs.io/en/latest/)  |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/BiomedicalMachineLearning/stLearn)|
| [TWCOM](https://academic.oup.com/bioinformaticsadvances/article/4/1/vbae101/7715000)    | 07/2024 | N/A  |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/jssong-lab/TWCOM)|
| [SpaCCC](https://www.sciopen.com/article/10.26599/BDMA.2024.9020056)    | 07/2024 | N/A  |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/sulab-wmu/SpaCCC)|
| [FlowSig](https://www.nature.com/articles/s41592-024-02380-w)    | 08/2024 | N/A  |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/axelalmet/flowsig)|
| [DeepTalk](https://www.nature.com/articles/s41467-024-51329-2)    | 08/2024 | [<img src="https://brand-guidelines.readthedocs.org/_images/logo-dark.png" width="20">](https://deeptalk.readthedocs.io/en/latest/index.html)  |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/JiangBioLab/DeepTalk) |
| [LIANA+](https://www.nature.com/articles/s41556-024-01469-w)    | 09/2024 | [<img src="https://brand-guidelines.readthedocs.org/_images/logo-dark.png" width="20">](https://liana-py.readthedocs.io/en/latest/index.html)  |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/saezlab/liana-py) |
| [SpaGraphCCI](https://ietresearch.onlinelibrary.wiley.com/doi/full/10.1049/syb2.70000)    | 02/2025 | N/A |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/hxzhard/SpaGraphCCI)|
| [SpaCcLink](https://bmcbiol.biomedcentral.com/articles/10.1186/s12915-025-02141-x)    | 02/2025 | N/A |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/LiangYu-Xidian/SpaCcLink)|
| [scNiche](https://www.nature.com/articles/s41467-025-57029-9)    | 02/2025 | N/A |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/ZJUFanLab/scNiche)|
| [NicheCompass](https://www.nature.com/articles/s41588-025-02120-6)    | 03/2025 | [<img src="https://brand-guidelines.readthedocs.org/_images/logo-dark.png" width="20">](https://nichecompass.readthedocs.io/en/latest/)  |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/Lotfollahi-lab/nichecompass/tree/main)|

---

## 📐 Dimension reduction

Tools for reducing dimensionality while preserving spatial information.

| Name       | Released | Documentation | Links |
| ---------- | -------  | ------------- | ----- |
| [SpatialPCA](https://www.nature.com/articles/s41467-022-34879-1)    | 11/2022 | [<img src="https://brand-guidelines.readthedocs.org/_images/logo-dark.png" width="20">](https://lulushang.org/SpatialPCA_Tutorial/)  |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/shangll123/SpatialPCA?tab=readme-ov-file)|
| [STAMP](https://www.nature.com/articles/s41592-024-02463-8)    | 10/2024 | [<img src="https://brand-guidelines.readthedocs.org/_images/logo-dark.png" width="20">](https://jinmiaochenlab.github.io/scTM/notebooks/stamp/Simulation/)  |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/JinmiaoChenLab/scTM)|
| [GraphPCA](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-024-03429-x)    | 11/2024 | N/A |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/YANG-ERA/GraphPCA)|

---

## 🔗 Multimodal integration

Tools for integrating multiple data modalities and spatial omics datasets.

| Name       | Released | Documentation | Links |
| ---------- | -------  | ------------- | ----- |
| [SpaGCN](https://www.nature.com/articles/s41592-021-01255-8)    | 10/2021 | N/A  |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/jianhuupenn/SpaGCN)|
| [STACI](https://www.nature.com/articles/s41467-022-35233-1)    | 12/2022 | N/A  |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/uhlerlab/STACI)|
| [STAligner](https://www.nature.com/articles/s43588-023-00543-x)    | 10/2023 | [<img src="https://brand-guidelines.readthedocs.org/_images/logo-dark.png" width="20">](https://staligner.readthedocs.io/en/latest/)  |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/zhanglabtools/STAligner)|
| [SpatialScope](https://www.nature.com/articles/s41467-023-43629-w)    | 11/2023 | [<img src="https://brand-guidelines.readthedocs.org/_images/logo-dark.png" width="20">](https://spatialscope-tutorial.readthedocs.io/en/latest/)  |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/YangLabHKUST/SpatialScope)|
| [Starfysh](https://www.nature.com/articles/s41587-024-02173-8#citeas)    | 03/2024 | N/A  |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/azizilab/starfysh)|
| [SpatiaGlue](https://www.nature.com/articles/s41592-024-02316-4)    | 06/2024 | [<img src="https://brand-guidelines.readthedocs.org/_images/logo-dark.png" width="20">](https://spatialglue-tutorials.readthedocs.io/en/latest/)  |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/JinmiaoChenLab/SpatialGlue)|
| [DeepTalk](https://www.nature.com/articles/s41467-024-51329-2)    | 08/2024 | [<img src="https://brand-guidelines.readthedocs.org/_images/logo-dark.png" width="20">](https://deeptalk.readthedocs.io/en/latest/index.html)  |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/JiangBioLab/DeepTalk) |
| [METI](https://www.nature.com/articles/s41467-024-51708-9)    | 08/2024 | N/A |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/Flashiness/METI) |
| [CAST](https://www.nature.com/articles/s41592-024-02410-7)    | 09/2024 | [<img src="https://brand-guidelines.readthedocs.org/_images/logo-dark.png" width="20">](https://cast-tutorial.readthedocs.io/en/latest/)  |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/wanglab-broad/CAST)|
| [STANDS](https://www.nature.com/articles/s41467-024-52445-9)    | 09/2024 | [<img src="https://brand-guidelines.readthedocs.org/_images/logo-dark.png" width="20">](https://catchxu.github.io/STANDS/)  |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/Catchxu/STANDS)|
| [Monae](https://www.nature.com/articles/s41467-024-53355-6)    | 10/2024 | N/A  |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/shapsider/monae)|
| [ISS-Patcher](https://www.nature.com/articles/s41586-024-08189-z)    | 11/2024 | [<img src="https://brand-guidelines.readthedocs.org/_images/logo-dark.png" width="20">](https://iss-patcher.readthedocs.io/en/latest/)  |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/Teichlab/iss_patcher)|
| [MISO](https://www.nature.com/articles/s41592-024-02574-2)    | 01/2025 | N/A  |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/kpcoleman/miso)|
| [INSTINCT](https://www.nature.com/articles/s41467-025-56535-0)    | 02/2025 | [<img src="https://brand-guidelines.readthedocs.org/_images/logo-dark.png" width="20">](N/A)  |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/yyLIU12138/INSTINCT)|

---

## 🤖 Foundation models

Large-scale pre-trained models for spatial transcriptomics analysis.

| Name       | Released | Documentation | Links |
| ---------- | -------  | ------------- | ----- |
| [Nicheformer](https://www.biorxiv.org/content/10.1101/2024.04.15.589472v2)    | 04/2024 | N/A  |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/theislab/nicheformer)|
| [stFormer](https://www.biorxiv.org/content/10.1101/2024.09.27.615337v7)    | 09/2024 | N/A  |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/BioX-NKU/stFormer)|
| [scGPT-spatial](https://www.biorxiv.org/content/10.1101/2025.02.05.636714v1)    | 02/2025 | N/A  |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/bowang-lab/scGPT-spatial/tree/main)|
| [SpatialAgent](https://www.biorxiv.org/content/10.1101/2025.04.03.646459v1)    | 04/2025 | N/A  |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/Genentech/SpatialAgent)|
| [OmiCLIP](https://www.nature.com/articles/s41592-025-02707-1)    | 05/2025 | N/A  |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/mahmoodlab/OMICLIP)|

---

## 🛠️ Other tools

Additional specialized tools for spatial transcriptomics analysis.

| Name       | Released | Purpose  | Documentation | Links |
| ---------- | -------  | -------- | ------------- | ----- |
| [SpaCell](https://academic.oup.com/bioinformatics/article/36/7/2293/5663455?login=false)    | 04/2020 | Predict disease cells | N/A  |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/BiomedicalMachineLearning/SpaCell)|
| [scArches](https://www.nature.com/articles/s41587-021-01001-7)    | 08/2021 | Mapping sc to reference atlas by transfer learning | [<img src="https://brand-guidelines.readthedocs.org/_images/logo-dark.png" width="20">](https://docs.scarches.org/en/latest/)  |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/theislab/scarches)|
| [eggplant](https://www.biorxiv.org/content/10.1101/2021.11.11.468178v1)    | 11/2021 | Common Coordinate Framework | [<img src="https://brand-guidelines.readthedocs.org/_images/logo-dark.png" width="20">](https://spatial-eggplant.readthedocs.io/en/latest/index.html)  |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/almaan/eggplant/tree/master?tab=readme-ov-file)|
| [scvi-tools](https://www.nature.com/articles/s41587-021-01206-w)    | 02/2022 |probabilistic analysis of single cell | [<img src="https://brand-guidelines.readthedocs.org/_images/logo-dark.png" width="20">](https://scvi-tools.org)  |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/scverse/scvi-tools)|
| [PathML](https://aacrjournals.org/mcr/article/20/2/202/678062/Building-Tools-for-Machine-Learning-and-Artificial)    | 02/2022 | computational pathology | [<img src="https://brand-guidelines.readthedocs.org/_images/logo-dark.png" width="20">](https://pathml.org)  |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/Dana-Farber-AIOS/pathml)|
| [CytoCommunity](https://www.nature.com/articles/s41592-023-02124-2)    | 01/2024 | identification of tissue cellular neighborhoods | N/A |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/tanlabcode/CytoCommunity?tab=readme-ov-file)|
| [scCube](https://www.nature.com/articles/s41467-024-49445-0)    | 06/2024 | simulation of spatially transcriptomics data | N/A |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/ZJUFanLab/scCube)|
| [Bento](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-024-03217-7)    | 04/2024 | subcellular analysis | [<img src="https://brand-guidelines.readthedocs.org/_images/logo-dark.png" width="20">](https://bento-tools.readthedocs.io/en/latest/)  |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/YeoLab/bento-tools)|
| [SANTO](https://www.nature.com/articles/s41467-024-50308-x)    | 07/2024 | coarse-to-fine alignment and stitching | N/A  | [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/leihouyeung/SANTO)|
| [SpaGFT](https://www.nature.com/articles/s41467-024-51590-5)    | 08/2024 | Graph Fourier transform for spatial omics | [<img src="https://brand-guidelines.readthedocs.org/_images/logo-dark.png" width="20">](https://spagft.readthedocs.io/en/latest)  |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/OSU-BMBL/SpaGFT)|
| [InSTAnT](https://www.nature.com/articles/s41467-024-49457-w)    | 09/2024 | Intracellular patterns of co-localisation | N/A  |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/bhavaygg/InSTAnT)|
| [MuSpan](https://www.biorxiv.org/content/10.1101/2024.12.06.627195v3)    | 02/2025 | Multiscale analysis | [<img src="https://brand-guidelines.readthedocs.org/_images/logo-dark.png" width="20">](https://www.muspan.co.uk)  |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/joshwillmoore1/MuSpAn-Public)|
| [STIM](https://www.cell.com/cell-systems/fulltext/S2405-4712(25)00097-3)    | 04/2025 | Visualization and alignment framework | N/A  | [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/MahmoodLab/STIM)|
| [Samui](https://www.cambridge.org/core/journals/biological-imaging/article/performant-webbased-interactive-visualization-tool-for-spatiallyresolved-transcriptomics-experiments/B66303984D10B9E5A23D3656CB8537C0)    | 03/2024 | Web-based interactive visualization | N/A  | [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/MicronOxford/samui)|
| [DeepSpot](https://www.medrxiv.org/content/10.1101/2025.02.09.25321567v1)    | 02/2025 | Spatial transcriptomics Prediction from H&E images | N/A  | [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/ratschlab/DeepSpot/tree/main)|
| [MESA](https://www.nature.com/articles/s41588-025-02119-z)    | 04/2025 | ecological inspired spatial analysis | [<img src="https://brand-guidelines.readthedocs.org/_images/logo-dark.png" width="20">](https://mesa-py.readthedocs.io/en/latest/)  |  [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="20">](https://github.com/Feanor007/MESA)|

---

## ✨ Contributors

<div align="center">

| <img src="https://api.dicebear.com/9.x/rings/svg?seed=Anthony%20Baptista" width="100px"> |
|:----------------------------------------------------------------------------------------:|
| **Anthony Baptista**                                                                     |

</div>

---

<div align="center">

**Made with dedication for the spatial biology community**

If you find this resource helpful, please consider starring the repository!

</div>

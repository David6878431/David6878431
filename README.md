<div align="center">

# Hi, I'm yanggguang

**PhD Student · Personal Bioinformatics Projects**

基因组组装 · 泛基因组 · 基因家族分析

[我的项目](#我个人开发的项目) · [Docker 镜像与联系](#docker-镜像与联系)

</div>

---

## 关于我

你好！我是一名**在读博士**，也在持续学习和开发服务于科研分析的生物信息学工具。

**本主页展示的 genomeT2T、pangene 和 pangenefamily，由我个人开发与维护。** 我希望把实际研究中使用的分析脚本，整理成更易配置、复用和追踪结果的工具，让使用者能够看清每一步的输入、参数与输出。

我的开发工作主要包括分析工作流设计与整合、Python 包与命令行封装、统一配置、Docker 环境适配，以及配套 Skill 和使用文档。流程中调用的第三方生信软件、算法和数据库，保留各自作者的归属与引用信息。

## 我个人开发的项目

| 项目 | 解决的问题 | 使用方式 |
| :--- | :--- | :--- |
| **[genomeT2T](https://github.com/David6878431/genomeT2T)** | 整理基因组组装、评估与注释流程，支持 HiFi、ONT、Hi-C 等不同数据分支 | `genomet2t` · Docker · 配套 Skill |
| **[pangene](https://github.com/David6878431/pangene)** | 整合基于组装或短读长的泛基因组分析，包括家族 PAV、候选新序列和图泛基因组等分支 | `pangene-workflows` · Docker · 配套 Skill |
| **[pangenefamily](https://github.com/David6878431/pangenefamily)** | 整理跨样本的基因家族分析，涵盖 HMM 候选筛选、人工确认、PAV、树、Ka/Ks、SV 与表达关联 | `pangenefamily-workflows` · Docker · 配套 Skill |

## 我关注的开发方式

- **把参数写清楚：** 使用统一配置和样本清单，减少写死的物种名称、路径和样本数。
- **把流程拆清楚：** 根据数据选择分析阶段，保留必要的人工检查环节。
- **把运行记录留下来：** 提供配置检查、命令预览、日志和退出状态，便于排查问题。
- **把工具交付完整：** 同时提供脚本、Python 包、Docker 使用说明和配套 Skill。

常用技术：**Python · Bash · Docker · Git**。

## Docker 镜像与联系

使用 Docker 运行上述流程，需要配套的生信软件镜像；镜像文件单独提供，未包含在 GitHub 仓库或 Python 安装包中。

**需要 Docker 镜像，请联系：[1394248709@qq.com](mailto:1394248709@qq.com)。**

欢迎通过各项目的 Issues 反馈问题、报告错误或提出改进建议。项目会随着我的科研需求和使用反馈持续完善。

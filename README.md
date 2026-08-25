# Awesome Topic Models with stars

> A curated list of amazing topic modelling libraries.

## Contents

* [Libraries & Toolkits](#libraries--toolkits)
* [Models](#models)
* [Techniques](#techniques)
* [Research Implementations](#research-implementations)
* [Visualizations](#visualizations)
* [Resources](#resources)
* [Related awesome lists](#related-awesome-lists)

## Libraries & Toolkits

* [scikit-learn](https://github.com/scikit-learn/scikit-learn) ⭐ 67,058 | 🐛 2,128 | 🌐 Python | 📅 2026-08-24 - Python library for machine learning ![GitHub Repo stars](https://img.shields.io/github/stars/scikit-learn/scikit-learn?style=social)
* [gensim](https://github.com/RaRe-Technologies/gensim) ⭐ 16,479 | 🐛 438 | 🌐 Python | 📅 2025-11-01 - Python library for topic modelling ![GitHub Repo stars](https://img.shields.io/github/stars/RaRe-Technologies/gensim?style=social)
* [Mallet](https://github.com/mimno/Mallet) ⭐ 1,028 | 🐛 118 | 🌐 Java | 📅 2026-08-04 - Java-based package for topic modeling ![GitHub Repo stars](https://img.shields.io/github/stars/mimno/mallet?style=social)
* [BIDMach](https://github.com/BIDData/BIDMach) ⭐ 920 | 🐛 67 | 🌐 Scala | 📅 2022-10-04 - CPU and GPU-accelerated machine learning library ![GitHub Repo stars](https://img.shields.io/github/stars/BIDData/BIDMach?style=social)
* [OCTIS](https://github.com/MIND-Lab/OCTIS) ⭐ 804 | 🐛 47 | 🌐 Python | 📅 2026-06-21 - Python package to integrate, optimize and evaluate topic models ![GitHub Repo stars](https://img.shields.io/github/stars/MIND-Lab/OCTIS?style=social)
* [BigARTM](https://github.com/bigartm/bigartm) ⭐ 675 | 🐛 136 | 🌐 C++ | 📅 2026-02-05 - Fast topic modeling platform ![GitHub Repo stars](https://img.shields.io/github/stars/bigartm/bigartm?style=social)
* [tomotopy](https://github.com/bab2min/tomotopy) ⭐ 598 | 🐛 61 | 🌐 C++ | 📅 2026-02-21 - Python extension for Gibbs sampling based *tomoto* which is written in C++ ![GitHub Repo stars](https://img.shields.io/github/stars/bab2min/tomotopy?style=social)
* [stm](https://github.com/bstewart/stm) ⭐ 420 | 🐛 117 | 🌐 R | 📅 2026-01-14 - R package for the Structural Topic Model ![GitHub Repo stars](https://img.shields.io/github/stars/bstewart/stm?style=social)
* [tmtoolkit](https://github.com/WZBSocialScienceCenter/tmtoolkit) ⚠️ Archived -  Python topic modeling toolkit with parallel processing power ![GitHub Repo stars](https://img.shields.io/github/stars/WZBSocialScienceCenter/tmtoolkit?style=social)
* [TopicNet](https://github.com/machine-intelligence-laboratory/TopicNet) ⭐ 143 | 🐛 30 | 🌐 Python | 📅 2024-07-29 - A high-level Python interface for BigARTM library ![GitHub Repo stars](https://img.shields.io/github/stars/machine-intelligence-laboratory/TopicNet?style=social)
* [tomoto](https://github.com/ankane/tomoto) ⭐ 66 | 🐛 2 | 🌐 C++ | 📅 2026-04-09 - Ruby extension for Gibbs sampling based *tomoto* which is written in C++ ![GitHub Repo stars](https://img.shields.io/github/stars/ankane/tomoto?style=social)
* [RMallet](https://github.com/mimno/RMallet) ⭐ 39 | 🐛 4 | 🌐 R | 📅 2022-07-21 -  R package to interface with the Java machine learning tool MALLET ![GitHub Repo stars](https://img.shields.io/github/stars/mimno/RMallet?style=social)
* [TopicModel4J](https://github.com/soberqian/TopicModel4J) ⭐ 29 | 🐛 5 | 🌐 Java | 📅 2023-02-04 - Java-based package for topic modeling ![GitHub Repo stars](https://img.shields.io/github/stars/soberqian/TopicModel4J?style=social)
* [lda++](https://github.com/angeloskath/supervised-lda) ⭐ 23 | 🐛 4 | 🌐 C++ | 📅 2019-03-15 - C++ library for LDA and (fast) supervised LDA (sLDA/fsLDA) using variational inference ![GitHub Repo stars](https://img.shields.io/github/stars/angeloskath/supervised-lda?style=social)
* [R-lda](https://github.com/slycoder/R-lda) ⭐ 16 | 🐛 1 | 🌐 C | 📅 2018-07-26 - R package for topic modelling (LDA, sLDA, corrLDA, etc.) ![GitHub Repo stars](https://img.shields.io/github/stars/slycoder/R-lda?style=social)
* [topicmodels](https://github.com/cran/topicmodels) ⭐ 8 | 🐛 0 | 🌐 C | 📅 2024-08-15 - R package with interface to C code for LDA and CTM ![GitHub Repo stars](https://img.shields.io/github/stars/cran/topicmodels?style=social)

## Models

There are huge differences in performance and scalability as well as the support of advanced features as hyperparameter tuning or evaluation capabilities.

### Truncated Singular Value Decomposition (SVD) / Latent Semantic Analysis (LSA) / Latent Semantic Indexing (LSI)

* [BIDMach](https://github.com/BIDData/BIDMach/blob/master/src/main/scala/BIDMach/models/SVD.scala) ⭐ 920 | 🐛 67 | 🌐 Scala | 📅 2022-10-04 - Scala implementation of a scalable approximate SVD using subspace iteration
* [sparsesvd](https://github.com/RaRe-Technologies/sparsesvd) ⭐ 55 | 🐛 4 | 🌐 C | 📅 2013-08-16 - Python wrapper for SVDlibc
* [SVDlibc](https://github.com/lucasmaystre/svdlibc) ⭐ 53 | 🐛 3 | 🌐 C | 📅 2015-09-01 - C implementation of SVD by Doug Rohde
* [scikit-learn](https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.TruncatedSVD.html) - Python implementation using fast [randomized SVD solver](https://arxiv.org/pdf/0909.4061.pdf) or a “naive” algorithm that uses [ARPACK](https://docs.scipy.org/doc/scipy/reference/generated/scipy.sparse.linalg.svds.html)
* [gensim](https://radimrehurek.com/gensim/models/lsimodel.html) - Python implementation using multi-pass [randomized SVD solver](https://arxiv.org/pdf/0909.4061.pdf) or a [one-pass merge algorithm](https://rdcu.be/cghAi)

### Non-Negative Matrix Factorization (NMF or NNMF)

* [BIDMach](https://github.com/BIDData/BIDMach/blob/master/src/main/scala/BIDMach/models/NMF.scala) ⭐ 920 | 🐛 67 | 🌐 Scala | 📅 2022-10-04 - CPU and GPU-accelerated Scala implementation with L2 loss
* [scikit-learn](https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.NMF.html) - Python implementation using a [coordinate descent](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.214.6398\&rep=rep1\&type=pdf) or a [multiplicative update](https://arxiv.org/pdf/1010.1763.pdf) solver
* [gensim](https://radimrehurek.com/gensim/models/nmf.html) - Python implementation of [online NMF](https://arxiv.org/pdf/1604.02634.pdf)

### Latent Dirichlet Allocation (LDA) [:page\_facing\_up:](https://www.jmlr.org/papers/volume3/blei03a/blei03a.pdf)

* [turicreate](https://github.com/apple/turicreate) ⚠️ Archived - C++ [LDA](https://github.com/apple/turicreate/blob/master/userguide/text/README.md) ⚠️ Archived and [aliasLDA](https://apple.github.io/turicreate/docs/api/generated/turicreate.topic_model.create.html) implementation with export to Apple's Core ML for use in iOS, macOS, watchOS, and tvOS apps
* [Vowpal Wabbit](https://github.com/VowpalWabbit/vowpal_wabbit/wiki/Latent-Dirichlet-Allocation) ⭐ 8,706 | 🐛 2 | 🌐 C++ | 📅 2026-08-18 - C++ implementaion using online variational Bayes inference [:page\_facing\_up:](https://proceedings.neurips.cc/paper/2010/file/71f6278d140af599e06ad9bf1ba03cb0-Paper.pdf)
* [lda](https://github.com/lda-project/lda) ⭐ 1,315 | 🐛 0 | 🌐 Python | 📅 2024-07-29 - Python implementation using collapsed Gibbs sampling which follows scikit-learn interface [:page\_facing\_up:](https://www.pnas.org/content/pnas/101/suppl_1/5228.full.pdf)
* [Mallet](https://github.com/mimno/Mallet/blob/master/src/cc/mallet/topics/ParallelTopicModel.java) ⭐ 1,028 | 🐛 118 | 🌐 Java | 📅 2026-08-04 - Parallelized Java implementation using Gibbs sampling [:page\_facing\_up:](https://www.jmlr.org/papers/volume10/newman09a/newman09a.pdf)[:page\_facing\_up:](https://dl.acm.org/doi/pdf/10.1145/1557019.1557121)
* [gensim-wrapper-Mallet](https://github.com/mimno/Mallet/blob/master/src/cc/mallet/topics/ParallelTopicModel.java) ⭐ 1,028 | 🐛 118 | 🌐 Java | 📅 2026-08-04 - Python wrapper for Mallet's implementation [:page\_facing\_up:](https://www.jmlr.org/papers/volume10/newman09a/newman09a.pdf)[:page\_facing\_up:](https://dl.acm.org/doi/pdf/10.1145/1557019.1557121)
* [MeTA](https://github.com/meta-toolkit/meta) ⭐ 715 | 🐛 56 | 🌐 C++ | 📅 2023-04-17 - C++ implementation of (parallel) collapsed [Gibbs sampling, CVB0 and SCVB](https://meta-toolkit.org/topic-models-tutorial.html)
* [tomotopy](https://github.com/bab2min/tomotopy) ⭐ 598 | 🐛 61 | 🌐 C++ | 📅 2026-02-21 - Python binding for C++ implementation using Gibbs sampling and different [term-weighting](https://www.aclweb.org/anthology/N10-1070.pdf) options [:page\_facing\_up:](https://www.jmlr.org/papers/volume10/newman09a/newman09a.pdf)
* [lda-nodejs](https://github.com/primaryobjects/lda) ⭐ 294 | 🐛 2 | 🌐 JavaScript | 📅 2024-08-20 - Node.js implementation of LDA topic modeling
* [jsLDA](https://github.com/mimno/jsLDA) ⭐ 186 | 🐛 5 | 🌐 JavaScript | 📅 2022-08-01 - JavaScript implementation of LDA topic modeling in the browser
* [lda-purescript](https://github.com/lettier/lda-topic-modeling) ⭐ 108 | 🐛 2 | 🌐 PureScript | 📅 2018-03-02 - PureScript, browser-based implementation of LDA topic modeling
* [TopicModels.jl](https://github.com/slycoder/TopicModels.jl) ⭐ 38 | 🐛 0 | 🌐 Julia | 📅 2020-05-31 - Julia implementation of LDA
* [GibbsSamplingLDA-TopicModel4J](https://github.com/soberqian/TopicModel4J/blob/master/src/main/java/com/topic/model/CVBLDA.java) ⭐ 29 | 🐛 5 | 🌐 Java | 📅 2023-02-04 - Java implementation using collapsed Gibbs sampling [:page\_facing\_up:](https://www.pnas.org/content/pnas/101/suppl_1/5228.full.pdf)
* [CVBLDA-TopicModel4J](https://github.com/soberqian/TopicModel4J/blob/master/src/main/java/com/topic/model/CVBLDA.java) ⭐ 29 | 🐛 5 | 🌐 Java | 📅 2023-02-04 - Java implementation using collapsed variational Bayesian (CVB) inference [:page\_facing\_up:](https://papers.nips.cc/paper/2006/file/532b7cbe070a3579f424988a040752f2-Paper.pdf)
* [PartiallyCollapsedLDA](https://github.com/lejon/PartiallyCollapsedLDA) ⭐ 28 | 🐛 10 | 🌐 Java | 📅 2026-06-30 - Various fast parallelized samplers for LDA, including Partially Collapsed LDA, LightLDA, Partially Collapsed Light LDA and a very efficient Polya-Urn LDA
* [Fugue](https://github.com/PuzaTech/Fugue) ⭐ 5 | 🐛 3 | 🌐 Java | 📅 2026-05-29 - Java implementation of collapsed Gibbs sampling with slice sampling for hyper-parameter optimization
* [topicmodel-lib](https://github.com/hncuong/topicmodel-lib) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2020-06-24 - Cython library for online/streaming LDA (Online VB, Online CVB0, Online CGS, Online OPE, Online FW, Streaming VB, Streaming OPE, Streaming FW, ML-OPE, ML-CGS, ML-FW)
* [scikit-learn](https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.LatentDirichletAllocation.html) - Python implementation using online variational Bayes inference [:page\_facing\_up:](https://proceedings.neurips.cc/paper/2010/file/71f6278d140af599e06ad9bf1ba03cb0-Paper.pdf)
* [lda-gensim](https://radimrehurek.com/gensim/models/ldamodel.html) - Python implementation using online variational inference [:page\_facing\_up:](https://proceedings.neurips.cc/paper/2010/file/71f6278d140af599e06ad9bf1ba03cb0-Paper.pdf)
* [ldamulticore-gensim](https://radimrehurek.com/gensim/models/ldamulticore.html) - Parallelized Python implementation using online variational inference [:page\_facing\_up:](https://proceedings.neurips.cc/paper/2010/file/71f6278d140af599e06ad9bf1ba03cb0-Paper.pdf)

#### Hyperparameter optimization

* [ldatuning](https://github.com/nikita-moor/ldatuning) ⭐ 78 | 🐛 10 | 🌐 R | 📅 2024-05-31 - R package to find optimal number of topics for LDA [:page\_facing\_up:](https://rpubs.com/siri/ldatuning)
* [LDADE](https://github.com/amritbhanu/LDADE-package) ⭐ 6 | 🐛 1 | 🌐 Python | 📅 2021-04-22 - Python tuning tool using differential evolution [:page\_facing\_up:](https://arxiv.org/pdf/1608.08176.pdf)
* [Search-Based-LDA](https://github.com/apanichella/Search-Based-LDA) ⭐ 4 | 🐛 0 | 🌐 R | 📅 2020-09-06 - R scripts using Genetic Algorithms (GA) for hyper-paramenter optimization by Panichella [:page\_facing\_up:](https://doi.org/10.1016/j.infsof.2020.106411)
* [Dodge](https://github.com/amritbhanu/Dodge) ⭐ 2 | 🐛 0 | 🌐 Scilab | 📅 2020-12-24 - Python tuning tool that ignores redundant tunings [:page\_facing\_up:](https://arxiv.org/pdf/1902.01838.pdf)
* [GA-LDA](https://github.com/GESAD-MSR/GA-LDA) ⭐ 0 | 🐛 0 | 🌐 R | 📅 2020-03-13 - R scripts using Genetic Algorithms (GA) for hyper-paramenter optimization, based on Panichella [:page\_facing\_up:](https://doi.org/10.1016/j.infsof.2020.106411)
* [Scalable](https://www.tandfonline.com/doi/suppl/10.1080/10618600.2020.1741378) - Scalable Hyperparameter Selection for LDA [:page\_facing\_up:](https://www.tandfonline.com/doi/full/10.1080/10618600.2020.1741378)

#### Evaluation

* [topic\_interpretability](https://github.com/jhlau/topic_interpretability) ⭐ 180 | 🐛 1 | 🌐 Roff | 📅 2017-04-19 - Computation of the semantic interpretability of topics produced by topic models [:page\_facing\_up:](https://aclanthology.org/E14-1056.pdf)
* [topic-model-diversity](https://github.com/silviatti/topic-model-diversity) ⭐ 51 | 🐛 0 | 🌐 Python | 📅 2021-08-03 - A collection of topic diversity measures for topic modeling [:page\_facing\_up:](https://dl.acm.org/doi/abs/10.1007/978-3-030-80599-9_4)
* [topic-coherence-sensitivity](https://github.com/jhlau/topic-coherence-sensitivity) ⭐ 21 | 🐛 0 | 🌐 Python | 📅 2025-09-10 - Code to compute topic coherence for several topic cardinalities and aggregate scores across them [:page\_facing\_up:](https://aclanthology.org/N16-1057.pdf)

#### CPU-based high performance implementations

* [LDA\*](https://github.com/Angel-ML/angel/blob/master/docs/algo/lda_on_angel_en.md) ⭐ 6,786 | 🐛 139 | 🌐 Java | 📅 2026-07-26 - Tencent's hybrid sampler that uses different samplers for different types of documents in combination with an asymmetric parameter server [:page\_facing\_up:](http://www.vldb.org/pvldb/vol10/p1406-yu.pdf)
* [Familia](https://github.com/baidu/Familia) ⭐ 2,644 | 🐛 28 | 🌐 C++ | 📅 2021-07-01 - A toolkit for industrial topic modeling (LDA, SentenceLDA and Topical Word Embedding) [:warning:](https://github.com/baidu/Familia/issues/111) ⭐ 2,644 | 🐛 28 | 🌐 C++ | 📅 2021-07-01 [:page\_facing\_up:](https://arxiv.org/pdf/1707.09823.pdf)
* [SparseLDA](https://github.com/mimno/Mallet/blob/master/src/cc/mallet/topics/ParallelTopicModel.java) ⭐ 1,028 | 🐛 118 | 🌐 Java | 📅 2026-08-04 - Java algorithm and data structure for evaluating Gibbs sampling distributions used in Mallet [:page\_facing\_up:](https://dl.acm.org/doi/pdf/10.1145/1557019.1557121)
* [lightLDA](https://github.com/microsoft/LightLDA) ⚠️ Archived - C++ implementation using O(1) Metropolis-Hastings sampling [:page\_facing\_up:](https://arxiv.org/pdf/1412.1576.pdf)
* [Yahoo-LDA](https://github.com/sudar/Yahoo_LDA) ⭐ 337 | 🐛 12 | 🌐 C++ | 📅 2011-09-21 - Yahoo!'s topic modelling framework [:page\_facing\_up:](https://dl.acm.org/doi/pdf/10.1145/2124295.2124312)
* [warpLDA](https://github.com/thu-ml/warplda) ⭐ 164 | 🐛 4 | 🌐 C++ | 📅 2019-01-04 - C++ cache efficient LDA implementation which samples each token in O(1) [:page\_facing\_up:](https://arxiv.org/pdf/1510.08628.pdf)
* [dmlc](https://github.com/dmlc/experimental-lda) ⭐ 127 | 🐛 2 | 🌐 C++ | 📅 2016-06-23 - Single-and multi-threaded C++ implementations of [lightLDA](https://arxiv.org/pdf/1412.1576.pdf), [F+LDA](https://arxiv.org/pdf/1412.4986v1.pdf), [AliasLDA](https://dl.acm.org/doi/pdf/10.1145/2623330.2623756), forestLDA and many more
* [PLDA+](https://github.com/openbigdatagroup/plda) ⭐ 83 | 🐛 13 | 🌐 C++ | 📅 2023-06-14 - Google's C++ implementation using data placement and pipeline processing [:page\_facing\_up:](https://dl.acm.org/doi/pdf/10.1145/1961189.1961198)
* [FastLDA](https://github.com/Arnie0426/FastLDA) ⭐ 19 | 🐛 1 | 🌐 C++ | 📅 2019-04-23 - C++ implementation of LDA [:page\_facing\_up:](https://dl.acm.org/doi/pdf/10.1145/1401890.1401960)
* [AliasLDA](https://github.com/polymorpher/aliaslda) ⭐ 10 | 🐛 0 | 🌐 C++ | 📅 2016-04-20 - C++ implemenation using Metropolis-Hastings and *alias* method[:page\_facing\_up:](https://dl.acm.org/doi/pdf/10.1145/2623330.2623756)
* [F+LDA](https://bigdata.oden.utexas.edu/software/nomad) - C++ implementation of F+LDA using an appropriately modified Fenwick tree [:page\_facing\_up:](https://arxiv.org/pdf/1412.4986v1.pdf)

#### GPU-based high performance implementations

* [GS-LDA-BIDMach](https://github.com/BIDData/BIDMach/blob/master/src/main/scala/BIDMach/models/LDAgibbs.scala) ⭐ 920 | 🐛 67 | 🌐 Scala | 📅 2022-10-04 - CPU and GPU-accelerated Scala implementation using Gibbs sampling
* [VB-LDA-BIDMach](https://github.com/BIDData/BIDMach/blob/master/src/main/scala/BIDMach/models/LDA.scala) ⭐ 920 | 🐛 67 | 🌐 Scala | 📅 2022-10-04 - CPU and GPU-accelerated Scala implementation using online variational Bayes inference
* [SaberLDA](https://dl.acm.org/doi/pdf/10.1145/3093336.3037740) - GPU-based system that implements a sparsity-aware algorithm to achieve sublinear time complexity

### Hierarchical Dirichlet Process (HDP) [:page\_facing\_up:](https://papers.nips.cc/paper/2004/file/fb4ab556bc42d6f0ee0f9e24ec4d1af0-Paper.pdf)

* [Mallet](https://github.com/mimno/Mallet) ⭐ 1,028 | 🐛 118 | 🌐 Java | 📅 2026-08-04 - Java-based package for topic modeling using Gibbs sampling
* [tomotopy](https://github.com/bab2min/tomotopy) ⭐ 598 | 🐛 61 | 🌐 C++ | 📅 2026-02-21 - Python extension for C++ implementation using Gibbs sampling [:page\_facing\_up:](https://www.jmlr.org/papers/volume10/newman09a/newman09a.pdf)
* [hca](https://github.com/wbuntine/topic-models) ⭐ 70 | 🐛 3 | 🌐 C | 📅 2016-08-16 - C implementation using Gibbs sampling with/without burstiness modelling
* [TopicModel4J](https://github.com/soberqian/TopicModel4J) ⭐ 29 | 🐛 5 | 🌐 Java | 📅 2023-02-04 - Java implementation using Gibbs sampling based on Chinese restaurant franchise metaphor
* [bnp](https://github.com/chyikwei/bnp) ⭐ 18 | 🐛 1 | 🌐 Python | 📅 2018-09-11 - Cython reimplementation based on *online-hdp* following scikit-learn's API.
* [gensim](https://radimrehurek.com/gensim/models/hdpmodel.html) - Python implementation using online variational inference [:page\_facing\_up:](http://proceedings.mlr.press/v15/wang11a/wang11a.pdf)
* [Scalable HDP](http://www.vldb.org/pvldb/vol11/p826-chen.pdf) - interesting paper

### Hierarchical LDA (hLDA) [:page\_facing\_up:](https://dl.acm.org/doi/10.5555/2981345.2981348)

* [Mallet](https://github.com/mimno/Mallet/blob/master/src/cc/mallet/topics/HierarchicalLDA.java) ⭐ 1,028 | 🐛 118 | 🌐 Java | 📅 2026-08-04 - Java implementation using Gibbs sampling
* [tomotopy](https://github.com/bab2min/tomotopy) ⭐ 598 | 🐛 61 | 🌐 C++ | 📅 2026-02-21 - Python extension for C++ implementation using Gibbs sampling
* [hlda](https://github.com/joewandy/hlda) ⭐ 153 | 🐛 19 | 🌐 Python | 📅 2026-02-11 - Python package based on *Mallet's* Gibbs sampler having a fixed depth on the nCRP tree
* [hLDA](https://github.com/blei-lab/hlda) ⭐ 78 | 🐛 0 | 🌐 JavaScript | 📅 2014-10-05 - C implementation of hierarchical LDA by David Blei

### Dynamic Topic Model (DTM) [:page\_facing\_up:](https://dl.acm.org/doi/pdf/10.1145/1143844.1143859)

* [tomotopy](https://github.com/bab2min/tomotopy) ⭐ 598 | 🐛 61 | 🌐 C++ | 📅 2026-02-21 - Python extension for C++ implementation using Gibbs sampling based on FastDTM
* [DETM](https://github.com/adjidieng/DETM) ⭐ 139 | 🐛 13 | 🌐 Python | 📅 2021-02-02 - Python implementation of the Dynamic Embedded Topic Model [:page\_facing\_up:](https://arxiv.org/pdf/1907.05545.pdf)
* [tca](https://github.com/wbuntine/topic-models/blob/master/HCA/doc/tcaman.pdf) ⭐ 70 | 🐛 3 | 🌐 C | 📅 2016-08-16 - C implementation using Gibbs sampling with/without burstiness modelling [:page\_facing\_up:](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.705.1649\&rep=rep1\&type=pdf)
* [dtm-BigTopicModel](https://github.com/thu-ml/BigTopicModel) ⭐ 23 | 🐛 7 | 🌐 C++ | 📅 2017-03-25 - C++ engine for running large-scale topic models
* [FastDTM](https://github.com/Arnie0426/FastDTM) ⭐ 16 | 🐛 2 | 🌐 C++ | 📅 2017-09-02 - Scalable C++ implementation using Gibbs sampling with Stochastic Gradient Langevin Dynamics (MCMC-based) [:page\_facing\_up:](https://arxiv.org/pdf/1602.06049.pdf)
* [ldaseqmodel-gensim](https://radimrehurek.com/gensim_3.8.3/models/ldaseqmodel.html) - Python implementation using online variational inference [:page\_facing\_up:](https://proceedings.neurips.cc/paper/2010/file/71f6278d140af599e06ad9bf1ba03cb0-Paper.pdf)

### Author-topic Model (ATM) [:page\_facing\_up:](https://arxiv.org/pdf/1207.4169.pdf)

* [TopicModel4J](https://github.com/soberqian/TopicModel4J) ⭐ 29 | 🐛 5 | 🌐 Java | 📅 2023-02-04 - Java implementation
* [Matlab Topic Modeling Toolbox](https://github.com/jonaschn/Matlab-Topic-Modeling-Toolbox) ⚠️ Archived - Matlab and C++ implementation using Gibbs sampling
* [Topic-Model](https://github.com/Ward-nju/Topic-Model) ⭐ 1 | 🐛 1 | 🌐 Python | 📅 2017-10-02 - Simple Python implementation using Gibbs sampling
* [gensim](https://radimrehurek.com/gensim/models/atmodel.html) - Python implementation with online training (constant in memory w\.r.t. the number of documents)

### Labeled Latent Dirichlet Allocation (LLDA, Labeled-LDA, L-LDA) [:page\_facing\_up:](https://www.aclweb.org/anthology/D09-1026.pdf)

* [Mallet](https://github.com/mimno/Mallet/blob/master/src/cc/mallet/topics/LabeledLDA.java) ⭐ 1,028 | 🐛 118 | 🌐 Java | 📅 2026-08-04 - Java implementation using Gibbs sampling [:page\_facing\_up:](http://www.mimno.org/articles/labelsandpatterns)
* [tomotopy](https://github.com/bab2min/tomotopy) ⭐ 598 | 🐛 61 | 🌐 C++ | 📅 2026-02-21 - Python extension for C++ implementation using Gibbs sampling
* [Labeled-LDA-Python](https://github.com/JoeZJH/Labeled-LDA-Python) ⭐ 119 | 🐛 3 | 🌐 Python | 📅 2022-06-22 - Python implementation (easy to use, does not scale)
* [JGibbLabeledLDA](https://github.com/myleott/JGibbLabeledLDA) ⭐ 105 | 🐛 2 | 🌐 Java | 📅 2016-07-18 - Java implementation based on the popular [JGibbLDA](jgibblda.sourceforge.net) package
* [TopicModel4J](https://github.com/soberqian/TopicModel4J) ⭐ 29 | 🐛 5 | 🌐 Java | 📅 2023-02-04 - Java implementation
* [topbox](https://github.com/jonaschn/topbox) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2021-01-20 - Python wrapper for labeled LDA implementation of *Stanford TMT*
* [gensims\_mallet\_wrapper](https://github.com/jonaschn/gensim/tree/labeled-lda) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2021-05-13 - Python wrapper for Mallet using gensim interface
* [STMT](https://nlp.stanford.edu/software/tmt/tmt-0.4/) - Scala implementation by Daniel Ramage

### Partially Labeled Dirichlet Allocation (PLDA) / Dirichlet Process (PLDP) [:page\_facing\_up:](https://www.microsoft.com/en-us/research/wp-content/uploads/2011/08/KDD2011-pldp-final.pdf)

* [tomotopy](https://github.com/bab2min/tomotopy) ⭐ 598 | 🐛 61 | 🌐 C++ | 📅 2026-02-21 - Python extension for C++ implementation using Gibbs sampling
* [TopicModel4J](https://github.com/soberqian/TopicModel4J) ⭐ 29 | 🐛 5 | 🌐 Java | 📅 2023-02-04 - Java implementation using collapsed Gibbs sampling
* [STMT](https://nlp.stanford.edu/software/tmt/tmt-0.4/) - Scala implementation of PLDA & PLDP by Daniel Ramage

### Dirichlet Multinomial Regression (DMR) topic model [:page\_facing\_up:](https://dl.acm.org/doi/10.5555/3023476.3023525)

* [Mallet](https://github.com/mimno/Mallet) ⭐ 1,028 | 🐛 118 | 🌐 Java | 📅 2026-08-04 - Java-based package for topic modeling
* [tomotopy](https://github.com/bab2min/tomotopy) ⭐ 598 | 🐛 61 | 🌐 C++ | 📅 2026-02-21 - Python extension for C++ implementation using Gibbs sampling

### Generalized Dirichlet Multinomial Regression (g-DMR) topic model [:page\_facing\_up:](https://dl.acm.org/doi/10.1007/s11192-020-03508-3)

* [tomotopy](https://github.com/bab2min/tomotopy) ⭐ 598 | 🐛 61 | 🌐 C++ | 📅 2026-02-21 - Python extension for C++ implementation using Gibbs sampling

### Link LDA

* [PTM](https://github.com/yao8839836/PTM) ⭐ 94 | 🐛 2 | 🌐 Java | 📅 2019-11-30 - implemented as benchmark [:page\_facing\_up:](https://ieeexplore.ieee.org/abstract/document/8242679)
* [TopicModel4J](https://github.com/soberqian/TopicModel4J) ⭐ 29 | 🐛 5 | 🌐 Java | 📅 2023-02-04 - Java implementation using collapsed Gibbs sampling

### Correlated Topic Model (CTM) a.k.a. logistic-normal topic models

* [tomotopy](https://github.com/bab2min/tomotopy) ⭐ 598 | 🐛 61 | 🌐 C++ | 📅 2026-02-21 - Python extension for C++ implementation using Gibbs sampling [:page\_facing\_up:](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.149.922)
* [stm](https://github.com/bstewart/stm) ⭐ 420 | 🐛 117 | 🌐 R | 📅 2026-01-14 - R package for the Structural Topic Model (CTM in case of no covariates) [:page\_facing\_up:](https://github.com/bstewart/stm/blob/master/vignettes/stmVignette.pdf?raw=true) ⭐ 420 | 🐛 117 | 🌐 R | 📅 2026-01-14
* [BigTopicModel](https://github.com/thu-ml/BigTopicModel) ⭐ 23 | 🐛 7 | 🌐 C++ | 📅 2017-03-25 - C++ engine for running large-scale DTM [:page\_facing\_up:](https://papers.nips.cc/paper/2013/file/285f89b802bcb2651801455c86d78f2a-Paper.pdf)
* [ctm-c](https://github.com/blei-lab/ctm-c) ⭐ 21 | 🐛 0 | 🌐 C | 📅 2014-10-05 - Original C implementation of the correlated topic model by David Blei [:page\_facing\_up:](https://proceedings.nips.cc/paper/2005/file/9e82757e9a1c12cb710ad680db11f6f1-Paper.pdf)

### Relational Topic Model (RTM)

* [BigTopicModel](https://github.com/thu-ml/BigTopicModel) ⭐ 23 | 🐛 7 | 🌐 C++ | 📅 2017-03-25 - C++ engine for running large-scale topic models
* [R-lda](https://github.com/slycoder/R-lda) ⭐ 16 | 🐛 1 | 🌐 C | 📅 2018-07-26 - R implementation using collapsed Gibbs sampling
* [Constrained-RTM](https://github.com/MIND-Lab/Constrained-RTM) ⭐ 8 | 🐛 2 | 🌐 Java | 📅 2026-05-08 - Java implementation of Contrained RTM [:page\_facing\_up:](https://doi.org/10.1016/j.ins.2019.09.039)

### Supervised LDA (sLDA) [:page\_facing\_up:](https://papers.nips.cc/paper/2007/file/d56b9fc4b0f1be8871f5e1c40c0067e7-Paper.pdf)

* [tomotopy](https://github.com/bab2min/tomotopy) ⭐ 598 | 🐛 61 | 🌐 C++ | 📅 2026-02-21 - Python extension for C++ implementation using Gibbs sampling
* [sLDA](https://github.com/blei-lab/class-slda) ⭐ 65 | 🐛 6 | 🌐 C++ | 📅 2022-01-14 - C++ implementation of supervised topic models with a categorical response
* [slda](https://github.com/Savvysherpa/slda) ⭐ 60 | 🐛 7 | 🌐 Python | 📅 2017-10-09 -  Cython implementation of Gibbs sampling for LDA and various sLDA variants
  * supervised LDA (linear regression)
  * binary logistic supervised LDA (logistic regression)
  * binary logistic hierarchical supervised LDA (trees)
  * generalized relational topic models (graphs)
* [R-lda](https://github.com/slycoder/R-lda) ⭐ 16 | 🐛 1 | 🌐 C | 📅 2018-07-26 - R implementation using collapsed Gibbs sampling
* [YWWTools](https://github.com/ywwbill/YWWTools-v2#slda-supervised-lda) ⭐ 2 | 🐛 0 | 🌐 Java | 📅 2020-09-05 - Java implementation using Gibbs sampling for LDA and various sLDA variants:
  * BS-LDA: Binary SLDA
  * Lex-WSB-BS-LDA: BS-LDA with Lexcial Weights and Weighted Stochastic Block Priors
  * Lex-WSB-Med-LDA: Lex-WSB-BS-LDA with Hinge Loss

### Topic Models for short documents

#### Sentence-LDA / SentenceLDA / Sentence LDA [:page\_facing\_up:](https://dl.acm.org/doi/10.1145/1935826.1935932)

* [Familia](https://github.com/baidu/Familia) ⭐ 2,644 | 🐛 28 | 🌐 C++ | 📅 2021-07-01 - Apply inference on pre-trained SentenceLDA models [:warning:](https://github.com/baidu/Familia/issues/111) ⭐ 2,644 | 🐛 28 | 🌐 C++ | 📅 2021-07-01 [:page\_facing\_up:](https://arxiv.org/pdf/1707.09823.pdf)
* [TopicModel4J](https://github.com/soberqian/TopicModel4J) ⭐ 29 | 🐛 5 | 🌐 Java | 📅 2023-02-04 - Java implementation of Sentence-LDA using collapsed Gibbs sampling

#### Dirichlet Multinomial Mixture Model (DMM) [:page\_facing\_up:](https://link.springer.com/content/pdf/10.1023/A:1007692713085.pdf)

* [jLDADMM](https://github.com/datquocnguyen/jLDADMM) ⭐ 86 | 🐛 0 | 🌐 Java | 📅 2019-04-17 - Java implementation using collapsed Gibbs sampling [:page\_facing\_up:](https://arxiv.org/pdf/1808.03835.pdf)
* [TopicModel4J](https://github.com/soberqian/TopicModel4J) ⭐ 29 | 🐛 5 | 🌐 Java | 📅 2023-02-04 - Java implementation using collapsed Gibbs sampling [:page\_facing\_up:](https://dl.acm.org/doi/10.1145/2623330.2623715)
* [GPyM\_TM](https://github.com/jrmazarura/GPM) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2022-07-13 - Python implementation of DMM and Poisson model

#### Dirichlet Process Multinomial Mixture Model (DPMM)

* [TopicModel4J](https://github.com/soberqian/TopicModel4J) ⭐ 29 | 🐛 5 | 🌐 Java | 📅 2023-02-04 - Java implementation using collapsed Gibbs sampling [:page\_facing\_up:](https://ieeexplore.ieee.org/document/7498276)

#### Pseudo-document-based Topic Model (PTM) [:page\_facing\_up:](https://dl.acm.org/doi/10.1145/2939672.2939880)

* [tomotopy](https://github.com/bab2min/tomotopy) ⭐ 598 | 🐛 61 | 🌐 C++ | 📅 2026-02-21 - Python extension for C++ implementation using Gibbs sampling
* [TopicModel4J](https://github.com/soberqian/TopicModel4J) ⭐ 29 | 🐛 5 | 🌐 Java | 📅 2023-02-04 - Java implementation using collapsed Gibbs sampling

#### Biterm topic model (BTM)

* [BTM](https://github.com/xiaohuiyan/BTM) ⭐ 409 | 🐛 15 | 🌐 C++ | 📅 2019-11-15 - Original C++ implementation using collapsed Gibbs sampling [:page\_facing\_up:](https://raw.githubusercontent.com/xiaohuiyan/xiaohuiyan.github.io/master/paper/BTM-WWW13.pdf)
* [R-BTM](https://github.com/bnosac/BTM) ⭐ 98 | 🐛 4 | 🌐 C++ | 📅 2025-11-26 - R package wrapping the C++ code from BTM
* [BurstyBTM](https://github.com/xiaohuiyan/BurstyBTM) ⭐ 53 | 🐛 2 | 🌐 C++ | 📅 2019-02-23 - Original C++ implementation of the Bursty BTM (BBTM) [:page\_facing\_up:](https://raw.githubusercontent.com/xiaohuiyan/xiaohuiyan.github.io/master/paper/BBTM-AAAI15.pdf)
* [TopicModel4J](https://github.com/soberqian/TopicModel4J) ⭐ 29 | 🐛 5 | 🌐 Java | 📅 2023-02-04 - Java implementation using collapsed Gibbs sampling
* [OnlineBTM]() - Original C++ implementation of online BTM (oBTM) and incremental BTM (iBTM) [:page\_facing\_up](https://raw.githubusercontent.com/xiaohuiyan/xiaohuiyan.github.io/master/paper/BTM-TKDE.pdf)

#### Others

* [shorttext](https://github.com/stephenhky/PyShortTextCategorization) ⭐ 472 | 🐛 2 | 🌐 Python | 📅 2026-08-22 -  Python implementation of various algorithms for Short Text Mining
* [STTM](https://github.com/qiang2100/STTM) ⭐ 161 | 🐛 9 | 🌐 Java | 📅 2020-05-24 - Java implementation and evaluation of DMM, WNTM, PTM, ETM, GPU-DMM, GPU-DPMM, LF-DMM [:page\_facing\_up:](https://arxiv.org/pdf/1904.07695.pdf)
* [SATM](https://github.com/WHUIR/SATM) ⭐ 8 | 🐛 0 | 🌐 Java | 📅 2022-11-04 - Java implementation of Self-Aggregation Topic Model [:page\_facing\_up:](https://dl.acm.org/doi/10.5555/2832415.2832564)

### Miscellaneous topic models

* [Multi-Grain-LDA](https://github.com/bab2min/tomotopy) ⭐ 598 | 🐛 61 | 🌐 C++ | 📅 2026-02-21 - MG-LDA implemented in tomotopy using collapsed Gibbs sampling [:page\_facing\_up:](https://dl.acm.org/doi/10.1145/1367497.1367513)
* [GuidedLDA](https://github.com/vi3k6i5/GuidedLDA) ⭐ 519 | 🐛 57 | 🌐 Python | 📅 2025-04-14 - Python implementation that can be guided by setting some seed words per topic (using Gibbs sampling) [:page\_facing\_up:](https://www.aclweb.org/anthology/E12-1021.pdf)
* [keyATM](https://github.com/keyATM/keyATM) ⭐ 120 | 🐛 1 | 🌐 R | 📅 2026-01-19 - R package for Keyword Assisted Topic Models.
* [ToT](https://github.com/ahmaurya/topics_over_time) ⭐ 117 | 🐛 5 | 🌐 Python | 📅 2020-08-12 - Python implementation of Topics Over Time (A Non-Markov Continuous-Time Model of Topical Trends) [:page\_facing\_up:](https://dl.acm.org/doi/10.1145/1150402.1150450)
* [EnsTop](https://github.com/lmcinnes/enstop) ⭐ 113 | 🐛 7 | 🌐 Python | 📅 2021-09-30 - Python implementation of *ENS*emble *TOP*ic modelling with pLSA
* [seededLDA](https://github.com/koheiw/seededlda) ⭐ 79 | 🐛 13 | 🌐 R | 📅 2026-05-28 - R package that implements seeded-LDA for semi-supervised topic modeling
* [hca](https://github.com/wbuntine/topic-models) ⭐ 70 | 🐛 3 | 🌐 C | 📅 2016-08-16 - C implementation of non-parametric topic models (HDP, HPYP-LDA, etc.) with focus on hyperparameter tuning
* [BayesPA](https://github.com/strin/BayesPA) ⭐ 52 | 🐛 4 | 🌐 Jupyter Notebook | 📅 2016-03-26 - Python interface for streaming implementation of MedLDA, maximum entropy discrimination LDA (max-margin supervised topic model) [:page\_facing\_up:](http://proceedings.mlr.press/v32/shi14.pdf)
* [Dual-Sparse Topic Model](https://github.com/soberqian/TopicModel4J/blob/master/src/main/java/com/topic/model/DualSparseLDA.java) ⭐ 29 | 🐛 5 | 🌐 Java | 📅 2023-02-04 - implemented in TopicModel4J using collapsed variational Bayes inference [:page\_facing\_up:](https://dl.acm.org/doi/10.1145/2566486.2567980)
* [MLTM](https://github.com/hsoleimani/MLTM) ⭐ 26 | 🐛 0 | 🌐 Python | 📅 2017-04-02 - C implementation of multilabel topic model (MLTM) [:page\_facing\_up:](https://www.mitpressjournals.org/doi/pdf/10.1162/NECO_a_00939)
* [lda++](https://github.com/angeloskath/supervised-lda) ⭐ 23 | 🐛 4 | 🌐 C++ | 📅 2019-03-15 - C++ library for LDA and (fast) supervised LDA (sLDA/fsLDA) using variational inference [:page\_facing\_up:](https://dl.acm.org/doi/pdf/10.1145/2964284.2967237) [:page\_facing\_up:](http://www.cs.columbia.edu/~blei/papers/WangBleiFeiFei2009.pdf)
* [BigTopicModel](https://github.com/thu-ml/BigTopicModel) ⭐ 23 | 🐛 7 | 🌐 C++ | 📅 2017-03-25 - C++ engine for running large-scale MedLDA models [:page\_facing\_up:](https://dl.acm.org/doi/10.1145/2487575.2487658)
* [trLDA](https://github.com/lucastheis/trlda/) ⭐ 21 | 🐛 1 | 🌐 C++ | 📅 2015-05-24 - Python implementation of streaming LDA based on trust-regions [:page\_facing\_up:](http://proceedings.mlr.press/v37/theis15.pdf)
* [Logistic LDA](https://github.com/lucastheis/logistic_lda) ⭐ 17 | 🐛 0 | 🌐 Python | 📅 2019-10-17 - Tensorflow implementation of Discriminative Topic Modeling with Logistic LDA [:page\_facing\_up:](https://proceedings.neurips.cc/paper/2019/file/54ebdfbbfe6c31c39aaba9a1ee83860a-Paper.pdf)
* [discLDA](https://github.com/anthonylife/discLDA) ⭐ 3 | 🐛 0 | 🌐 C++ | 📅 2012-12-28 - C++ implementation of discLDA based on GibbsLDA++ [:page\_facing\_up:](https://papers.nips.cc/paper/2008/file/7b13b2203029ed80337f27127a9f1d28-Paper.pdf)
* [ST-LDA](https://github.com/ywwbill/YWWTools-v2#st-lda-single-topic-lda) ⭐ 2 | 🐛 0 | 🌐 Java | 📅 2020-09-05 - ST-LDA: Single Topic LDA [:page\_facing\_up:](https://ywwbill.github.io/files/2016_socinfo_topicDynamic.pdf)
* [MTM](https://github.com/ywwbill/YWWTools-v2#mtm-in-command-line) ⭐ 2 | 🐛 0 | 🌐 Java | 📅 2020-09-05 - Java implementation of Multilingual Topic Model [:page\_facing\_up:](https://www.aclweb.org/anthology/D19-1120.pdf)
* [YWWTools](https://github.com/ywwbill/YWWTools-v2) ⭐ 2 | 🐛 0 | 🌐 Java | 📅 2020-09-05 - Java-based package for various topic models by Weiwei Yang
* [DAPPER](https://github.com/robert-giaquinto/dapper) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2018-11-19 - Python implementation of Dynamic Author Persona (DAP) topic model [:page\_facing\_up:](https://arxiv.org/pdf/1811.01931.pdf)
* [Entropy-Based Topic Modeling](https://github.com/julian-risch/JCDL2018/) ⭐ 1 | 🐛 0 | 🌐 Java | 📅 2020-09-25 - Java implementation of Entropy-Based Topic Modeling on Multiple Domain-Specific Text Collections
* [sequence-models](https://github.com/michaeljpaul/sequence-models) ⭐ 0 | 🐛 0 | 🌐 Java | 📅 2020-08-22 - Java implementation of block HMM and the mixed membership Markov model (M4)
* [sailing-pmls](https://pmls.readthedocs.io/en/latest/med-lda.html) - Parallel LDA and medLDA implementation

### Exotic models

* [PTM](https://github.com/yao8839836/PTM) ⭐ 94 | 🐛 2 | 🌐 Java | 📅 2019-11-30 - Prescription Topic Model for Traditional Chinese Medicine Prescriptions [:page\_facing\_up:](https://ieeexplore.ieee.org/abstract/document/8242679) (interesting benchmark models)
* [KGE-LDA](https://github.com/yao8839836/KGE-LDA) ⭐ 41 | 🐛 4 | 🌐 Java | 📅 2018-08-27 - Knowledge Graph Embedding LDA [:page\_facing\_up:](https://www.aaai.org/ocs/index.php/AAAI/AAAI17/paper/viewFile/14170/14086)
* [LDA-SP](https://github.com/aritter/LDA-SP) ⭐ 16 | 🐛 0 | 🌐 C | 📅 2023-03-10 - A Latent Dirichlet Allocation Method for Selectional Preferences [:page\_facing\_up:](https://www.aclweb.org/anthology/P10-1044.pdf)
* [TEM](https://github.com/jonaschn/TopicExpertiseModel) ⭐ 1 | 🐛 0 | 🌐 Java | 📅 2021-02-19 - Topic Expertise Model [:page\_facing\_up:](https://dl.acm.org/doi/pdf/10.1145/2505515.2505720)
* [LDA+FFT](https://github.com/ai-se/LDA_FFT) ⭐ 1 | 🐛 2 | 🌐 Python | 📅 2018-11-15 - LDA and FFTs (Fast and Frugal Trees) for better comprehensibility [:page\_facing\_up:](https://arxiv.org/pdf/1804.10657.pdf)

### Embedding based Topic Models

* [BERTopic](https://github.com/MaartenGr/BERTopic) ⭐ 7,800 | 🐛 468 | 🌐 Python | 📅 2026-08-22 - BERTopic supports guided, (semi-) supervised, and dynamic topic modeling and visualization [:page\_facing\_up:](https://arxiv.org/pdf/2203.05794.pdf)
* [Top2Vec](https://github.com/ddangelov/Top2Vec) ⭐ 3,102 | 🐛 84 | 🌐 Python | 📅 2024-11-14 - Python implementation that learns jointly embedded topic, document and word vectors [:page\_facing\_up:](https://arxiv.org/pdf/2008.09470.pdf)
* [CTM](https://github.com/MilaNLProc/contextualized-topic-models) ⭐ 1,269 | 🐛 11 | 🌐 Python | 📅 2025-07-24 - CTMs combine contextualized embeddings (e.g., BERT) with topic models
* [Anchored CorEx](https://github.com/gregversteeg/corex_topic) ⭐ 644 | 🐛 13 | 🌐 Python | 📅 2021-03-22 - Hierarchical Topic Modeling with Minimal Domain Knowledge [:page\_facing\_up:](https://arxiv.org/pdf/1611.10277.pdf)
* [ETM](https://github.com/adjidieng/ETM) ⭐ 559 | 🐛 32 | 🌐 Python | 📅 2023-10-03 - Embedded Topic Model [:page\_facing\_up:](https://arxiv.org/pdf/1907.04907.pdf)
* [ProdLDA](https://github.com/akashgit/autoencoding_vi_for_topic_models) ⭐ 256 | 🐛 8 | 🌐 Python | 📅 2021-04-19 - Original TensorFlow implementation of Autoencoding Variational Inference (AEVI) for Topic Models [:page\_facing\_up:](https://arxiv.org/pdf/1703.01488.pdf)
* [LFTM](https://github.com/datquocnguyen/LFTM) ⭐ 179 | 🐛 1 | 🌐 Java | 📅 2017-05-08 - Java implementation of latent feature topic models (improving LDA and DMM with word embeddings) [:page\_facing\_up:](https://www.aclweb.org/anthology/Q15-1022.pdf)
* [pytorch-ProdLDA](https://github.com/hyqneuron/pytorch-avitm) ⭐ 158 | 🐛 5 | 🌐 Python | 📅 2018-07-14 - PyTorch implementation of ProdLDA [:page\_facing\_up:](https://arxiv.org/pdf/1703.01488.pdf)
* [CorEx](https://github.com/gregversteeg/bio_corex) ⭐ 145 | 🐛 16 | 🌐 Python | 📅 2021-10-06 - Recover latent factors with Correlation Explanation (CorEx) [:page\_facing\_up:](https://arxiv.org/pdf/1406.1222.pdf)
* [G-LDA](https://github.com/rajarshd/Gaussian_LDA) ⭐ 143 | 🐛 1 | 🌐 HTML | 📅 2019-12-31 - Java implementation of Gaussian LDA using word embeddings [:page\_facing\_up:](https://www.aclweb.org/anthology/P15-1077.pdf)
* [D-ETM](https://github.com/adjidieng/DETM) ⭐ 139 | 🐛 13 | 🌐 Python | 📅 2021-02-02 - Dynamic Embedded Topic Model [:page\_facing\_up:](https://arxiv.org/pdf/1907.05545.pdf)
* [CatE](https://github.com/yumeng5/CatE) ⭐ 51 | 🐛 3 | 🌐 C | 📅 2021-01-06 -  Discriminative Topic Mining via Category-Name Guided Text Embedding [:page\_facing\_up:](https://arxiv.org/pdf/1908.07162.pdf)
* [Linear CorEx](https://github.com/gregversteeg/LinearCorex) ⭐ 44 | 🐛 2 | 🌐 Python | 📅 2020-11-30 - Latent Factor Models Based on Linear Total CorEx [:page\_facing\_up:](https://arxiv.org/pdf/1706.03353v3.pdf)
* [MetaLDA](https://github.com/ethanhezhao/MetaLDA) ⭐ 7 | 🐛 1 | 🌐 Java | 📅 2019-02-06 - Java implementation using Gibbs sampling that leverages document metadata and word embeddings [:page\_facing\_up:](https://arxiv.org/pdf/1709.06365.pdf)
* [MG-LDA](https://github.com/EliasKB/Multilingual-Gaussian-Latent-Dirichlet-Allocation-MGLDA) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2019-12-28 - Python implementation of (Multi-lingual) Gaussian LDA [:page\_facing\_up:](https://raw.githubusercontent.com/EliasKB/Multilingual-Gaussian-Latent-Dirichlet-Allocation-MGLDA/master/MGLDA.pdf)
* [lda2vec](https://github.com/cemoody/lda2javec) - Mixing dirichlet topic models and word embeddings to make lda2vec [:page\_facing\_up:](https://arxiv.org/pdf/1605.02019.pdf)
* [lda2vec-pytorch](https://github.com/TropjaComplique/lda2vec-pytorch) - PyTorch implementation of lda2vec

## Probabilistic Programming Languages (PPL) (a.k.a. Build your own Topic Model)

* [PyMC3](https://github.com/pymc-devs/pymc3) ⭐ 9,721 | 🐛 481 | 🌐 Python | 📅 2026-08-24 - Python package for Bayesian statistical modeling and probabilistic machine learning, e.g., [LDA](http://docs.pymc.io/notebooks/lda-advi-aevb.html) [:page\_facing\_up:](https://peerj.com/articles/cs-55.pdf)
* [pyro](https://github.com/pyro-ppl/pyro) ⭐ 9,037 | 🐛 284 | 🌐 Python | 📅 2026-08-04 - PPL built on PyTorch, e.g., [prodLDA](http://pyro.ai/examples/prodlda.html) [:page\_facing\_up:](https://www.jmlr.org/papers/volume20/18-403/18-403.pdf)
* [edward](https://github.com/blei-lab/edward) ⭐ 4,843 | 🐛 219 | 🌐 Jupyter Notebook | 📅 2024-03-18 - A PPL built on TensorFlow, e.g., [LDA](http://edwardlib.org/iclr2017?Figure%2011.%20Latent%20Dirichlet%20allocation) [:page\_facing\_up:](https://arxiv.org/pdf/1610.09787.pdf)
* [TFP](https://github.com/tensorflow/probability) ⭐ 4,427 | 🐛 726 | 🌐 Jupyter Notebook | 📅 2026-08-06 - Probabilistic reasoning and statistical analysis in TensorFlow, e.g., [LDA](https://github.com/tensorflow/probability/blob/master/tensorflow_probability/examples/latent_dirichlet_allocation_distributions.py) ⭐ 4,427 | 🐛 726 | 🌐 Jupyter Notebook | 📅 2026-08-06 [:page\_facing\_up:](https://arxiv.org/pdf/2001.11819.pdf)
* [Stan](https://github.com/stan-dev/stan) ⭐ 2,761 | 🐛 155 | 🌐 C++ | 📅 2026-08-25 - Platform for statistical modeling and high-performance statistical computation, e.g., [LDA](https://mc-stan.org/docs/2_26/stan-users-guide/latent-dirichlet-allocation.html) [:page\_facing\_up:](https://files.eric.ed.gov/fulltext/ED590311.pdf)
* [Turing.jl](https://github.com/TuringLang/Turing.jl) ⭐ 2,251 | 🐛 27 | 🌐 Julia | 📅 2026-08-24 -  Julia library for general-purpose probabilistic programming [:page\_facing\_up:](http://proceedings.mlr.press/v84/ge18b/ge18b.pdf)
* [ZhuSuan](https://github.com/thu-ml/zhusuan) ⭐ 2,219 | 🐛 13 | 🌐 Python | 📅 2022-12-17 - A PPL for Bayesian deep learning, generative models, built on Tensorflow, e.g., [LDA](https://zhusuan.readthedocs.io/en/latest/tutorials/lntm.html) [:page\_facing\_up:](https://arxiv.org/pdf/1709.05870.pdf)
* [edward2](https://github.com/google/edward2) ⭐ 712 | 🐛 78 | 🌐 Jupyter Notebook | 📅 2026-07-02 - Simple PPL with core utilities in the NumPy and TensorFlow ecosystem [:page\_facing\_up:](https://arxiv.org/pdf/1811.02091.pdf)

## Research Implementations

* [onlineldavb](https://github.com/blei-lab/onlineldavb) ⭐ 304 | 🐛 4 | 🌐 Python | 📅 2021-05-21 - Python online variational Bayes implementation by Matthew Hoffman [:page\_facing\_up:](https://proceedings.neurips.cc/paper/2010/file/71f6278d140af599e06ad9bf1ba03cb0-Paper.pdf)
* [LDAGibbs](https://github.com/yangliuy/LDAGibbsSampling) ⭐ 233 | 🐛 0 | 🌐 Java | 📅 2020-02-09 - Java implementation of LDA using Gibbs sampling by Liu Yang
* [dtm](https://github.com/blei-lab/dtm) ⭐ 205 | 🐛 8 | 🌐 Shell | 📅 2017-12-12 - C implementation of dynamic topic models by David Blei & Sean Gerrish
* [lda-c](https://github.com/blei-lab/lda-c) ⭐ 167 | 🐛 5 | 🌐 C | 📅 2016-06-09 - C implementation using variational EM by David Blei
* [HDP](https://github.com/blei-lab/hdp) ⭐ 149 | 🐛 6 | 🌐 C++ | 📅 2017-02-21 - C++ implementation of hierarchical Dirichlet processes by Chong Wang
* [ctr](https://github.com/blei-lab/ctr) ⭐ 146 | 🐛 2 | 🌐 C++ | 📅 2015-08-19 - C++ implementation of collaborative topic models by Chong Wang
* [online-hdp](https://github.com/blei-lab/online-hdp) ⭐ 145 | 🐛 4 | 🌐 Python | 📅 2015-03-29 - Python implementation of online hierarchical Dirichlet processes by Chong Wang
* [hLDA](https://github.com/blei-lab/hlda) ⭐ 78 | 🐛 0 | 🌐 JavaScript | 📅 2014-10-05 - C implementation of hierarchical LDA by David Blei
* [sLDA](https://github.com/blei-lab/class-slda) ⭐ 65 | 🐛 6 | 🌐 C++ | 📅 2022-01-14 - C++ implementation of supervised topic models with a categorical response.
* [turbotopics](https://github.com/blei-lab/turbotopics) ⭐ 46 | 🐛 0 | 🌐 Python | 📅 2015-06-16 - Python implementation that finds significant multiword phrases in topics by David Blei
* [ctm-c](https://github.com/blei-lab/ctm-c) ⭐ 21 | 🐛 0 | 🌐 C | 📅 2014-10-05 - C implementation of the correlated topic model by David Blei
* [cvbLDA](https://github.com/davidandrzej/cvbLDA) ⭐ 21 | 🐛 0 | 🌐 C | 📅 2011-11-05 -  Python C extension implementation of collapsed variational Bayesian inference for LDA
* [diln](https://github.com/blei-lab/diln) ⭐ 6 | 🐛 0 | 🌐 C | 📅 2014-10-09 - C implementation of Discrete Infinite Logistic Normal (with HDP option) by John Paisley
* [Matlab Topic Modeling Toolbox](https://github.com/jonaschn/Matlab-Topic-Modeling-Toolbox) ⚠️ Archived - Matlab implementations of LDA, ATM, HMM-LDA, LDA-COL (Collocation) models by Mark Steyvers and Tom Griffiths
* [Stanford Topic Modeling Toolbox](https://nlp.stanford.edu/software/tmt/tmt-0.4/) - Scala implementation of LDA, labeledLDA, PLDA, PLDP by Daniel Ramage and Evan Rosen
* [fast](https://www.ics.uci.edu/~asuncion/software/fast.htm) - A Fast And Scalable Topic-Modeling Toolbox (Fast-LDA, CVB0) by Arthur Asuncion and colleagues [:page\_facing\_up:](https://arxiv.org/pdf/1205.2662.pdf)

## Popular Implementations (but not maintained anymore)

* [Mr.LDA](https://github.com/lintool/Mr.LDA) ⚠️ Archived - Scalable Topic Modeling using Variational Inference in MapReduce [:page\_facing\_up:](https://dl.acm.org/doi/10.1145/2187836.2187955)
* [GibbsLDA++](http://gibbslda.sourceforge.net) - C++ implementation using Gibbs sampling [:page\_facing\_up:](https://dl.acm.org/doi/pdf/10.1145/1367497.1367510)
  [:fork\_and\_knife:](https://github.com/mrquincle/gibbs-lda) ⭐ 34 | 🐛 0 | 🌐 C++ | 📅 2014-03-20
* [Matlab Topic Modeling Toolbox](https://github.com/jonaschn/Matlab-Topic-Modeling-Toolbox) ⚠️ Archived - Matlab implementations of LDA, ATM, HMM-LDA, LDA-COL (Collocation) models by Mark Steyvers and Tom Griffiths
* [Stanford Topic Modeling Toolbox](https://nlp.stanford.edu/software/tmt/tmt-0.4/) - Scala implementation of LDA, labeledLDA, PLDA, PLDP by Daniel Ramage and Evan Rosen
* [JGibbLDA](http://jgibblda.sourceforge.net) - Java implementation using Gibbs sampling

## Learning Implementations (hopefully easy to understand)

* [topic\_models](https://github.com/laserwave/topic_models) ⭐ 99 | 🐛 0 | 🌐 Python | 📅 2016-07-08 - Python implementation of LSA, PLSA and LDA
* [Topic-Model](https://github.com/Ward-nju/Topic-Model) ⭐ 1 | 🐛 1 | 🌐 Python | 📅 2017-10-02 - Python implementation of LDA, Labeled LDA, ATM, Temporal Author-Topic Model using Gibbs sampling

## Visualizations

* [pyLDAvis](https://github.com/bmabey/pyLDAvis) ⭐ 1,851 | 🐛 81 | 🌐 Jupyter Notebook | 📅 2025-12-04 - Python library for interactive topic model visualization
* [LDAvis](https://github.com/cpsievert/LDAvis) ⭐ 570 | 🐛 35 | 🌐 JavaScript | 📅 2024-02-06 - R package for interactive topic model visualization
* [Termite](https://github.com/uwdata/termite-data-server) ⭐ 123 | 🐛 14 | 🌐 Python | 📅 2023-04-06 - Explore topic models using term-topic matrix, group-in-a-box visualization or scatter plot.
* [stminsights](https://github.com/cschwem2er/stminsights) ⭐ 121 | 🐛 2 | 🌐 R | 📅 2024-06-27 - A Shiny Application for Inspecting Structural Topic Models
* [Mallet-GUI](https://github.com/senderle/topic-modeling-tool) ⭐ 115 | 🐛 19 | 🌐 Java | 📅 2021-03-01 - GUI for creating and analyzing topic models produced by MALLET
* [dfr-browser](https://github.com/agoldst/dfr-browser) ⭐ 99 | 🐛 4 | 🌐 JavaScript | 📅 2022-07-11 -  Explore Mallet's topic models of texts in a web browser
* [Topics](https://github.com/DARIAH-DE/Topics) ⭐ 68 | 🐛 3 | 🌐 Python | 📅 2020-09-20 - Python library for topic modeling and visualization
* [TopicsExplorer](https://github.com/DARIAH-DE/TopicsExplorer) ⭐ 67 | 🐛 16 | 🌐 TypeScript | 📅 2026-03-19 - Explore your own text collection with a topic model – without prior knowledge [:page\_facing\_up:](https://dh2018.adho.org/a-graphical-user-interface-for-lda-topic-modeling)
* [TMVE online](https://github.com/ajbc/tmv) ⭐ 52 | 🐛 1 | 🌐 Python | 📅 2015-03-13 - Online Django variant of topic model visualization engine (*TMVE*)
* [TWiC](https://github.com/jarmoza/twic) ⭐ 49 | 🐛 33 | 🌐 JavaScript | 📅 2017-07-13 - Topic Words in Context is a highly-interactive, browser-based visualization for MALLET topic models
* [TMVE](https://github.com/ajbc/tmve-original) ⭐ 45 | 🐛 0 | 🌐 Python | 📅 2015-06-29 - Original topic model visualization engine (LDA trained with *lda-c*) [:page\_facing\_up:](https://www.aaai.org/ocs/index.php/ICWSM/ICWSM12/paper/viewFile/4645/5021)
* [topicApp](https://github.com/wesslen/topicApp) ⭐ 45 | 🐛 2 | 🌐 R | 📅 2025-12-25 - A Simple Shiny App for Topic Modeling
* [dtmvisual](https://github.com/GSukr/dtmvisual) ⭐ 26 | 🐛 1 | 🌐 Python | 📅 2020-05-16 - Python package for visualizing DTM (trained with gensim)
* [scalaLDAvis](https://github.com/iaja/scalaLDAvis) ⭐ 6 | 🐛 0 | 🌐 JavaScript | 📅 2017-07-05 - Scala port of pyLDAvis
* [topicmodel-lib](https://test-dslab.readthedocs.io/en/latest/visualization.html) - Python wrapper for TMVE for visualizing LDA (trained with topicmodel-lib)
* [wordcloud](http://amueller.github.io/word_cloud/) - Python package for visualizing topics via word\_cloud

## Dirichlet hyperparameter optimization techniques

* [Slice sampling](https://people.cs.umass.edu/~cxl/cs691bm/lec08.html)
* [Minka](https://tminka.github.io/papers/dirichlet/minka-dirichlet.pdf)
  * [fastfit](https://github.com/tminka/fastfit) ⭐ 27 | 🐛 0 | 🌐 Matlab | 📅 2017-01-05
  * [dirichlet](https://github.com/ericsuh/dirichlet) ⭐ 117 | 🐛 2 | 🌐 Python | 📅 2025-08-09 Python port of fastfit
  * [lightspeed](https://github.com/tminka/lightspeed) ⭐ 134 | 🐛 1 | 🌐 MATLAB | 📅 2021-06-07
  * [lecture-notes](https://people.cs.umass.edu/~cxl/cs691bm/lec09.html)
* [Newton-Raphson Method](http://jonathan-huang.org/research/dirichlet/dirichlet.pdf)
* [fixed-point iteration](https://people.cs.umass.edu/~wallach/theses/wallach_phd_thesis.pdf) - Wallach's PhD thesis, chapter 2.3

## Resources

* [David Blei](http://www.cs.columbia.edu/~blei/topicmodeling.html) - David Blei's Homepage with introductory materials

## Related awesome lists

* [awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning) ⭐ 74,148 | 🐛 26 | 🌐 Python | 📅 2026-08-24
* [awesome-datascience](https://github.com/academic/awesome-datascience) ⭐ 29,859 | 🐛 8 | 📅 2026-08-22
* [awesome-python-data-science](https://github.com/krzjoa/awesome-python-data-science) ⭐ 3,568 | 🐛 16 | 📅 2026-04-13

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Jonathan Schneider has waived all copyright and
related or neighboring rights to this work.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-25._

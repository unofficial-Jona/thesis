# Assessing aggressive driving behaviour using attention based models

The findings from this project are currently under review for publication at the BNAIC 2023. A link to the paper will be provided as soon as it's available.

Dataset: [METEOR](https://gamma.umd.edu/researchdirections/autonomousdriving/meteor/)

This repository contains the code necessary to replicate the experiments conducted for my Master's thesis. The full text of which can be found in [thesis.pdf](https://github.com/unofficial-Jona/thesis/blob/main/thesis.pdf).

The research presented here builds heavily upon the [OadTR](https://github.com/wangxiang1230/OadTR) and [Colar](https://github.com/VividLe/Online-Action-Detection) models. Both of these demonstrate successful applications of the attention mechanism in the context of online action detection. This research introduces two novel contributions:

1. An integrated model architecture that combines concepts from both the OadTR and Colar models.
2. An explainability approach that leverages prior frame information to generate salient cues.

For replication, please use the provided [YAML file](https://github.com/unofficial-Jona/thesis/blob/main/thesis_conda.yml) to set up the conda environment.

Anyone extending this work is strongly encouraged to train a custom backbone. This was identified as the primary performance bottleneck during this project.

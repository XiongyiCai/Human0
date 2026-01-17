<h1 align="center">In-N-On: Scaling Egocentric Manipulation with in-the-wild and on-task Data</h1>

<p align="center">
<h3 align="center"><a href="https://xiongyicai.github.io/In-N-On/">Website</a> | <a href="https://arxiv.org/abs/2511.15704">arXiv</a> | <a href="https://huggingface.co/datasets/XiongyiC/PHSD">Data</a> | <a href="https://huggingface.co/XiongyiC/Human0">Model</a>
  <div align="center"></div>
</p>

<p align="center">
<img src="./assets/video/grid_video_change.webp" width="80%"/>
</p>

## Introduction

This repository works in a few simple steps.

1. Converts diverse egocentric datasets to human-centric representation.
2. Train a policy that imitaties human behavior.
3. The policy predicts future human movement, which can be retargeted and deployed on actual bimanual egocentric robots.

We support pre-training and post-training on mixed robot and human data.

<p align="center">
<img src="./assets/video/retarget_video_wo_text.webp" width="80%"/>
</p>
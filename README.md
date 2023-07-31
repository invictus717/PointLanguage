<p align="center" width="100%">
<img src="assets\PointLangauge_banner.png"  width="80%" height="80%">
</p>

<div>
<div align="center">
    <a href='https://scholar.google.com/citations?user=KuYlJCIAAAAJ&hl=en' target='_blank'>Yiyuan Zhang<sup>1,2*</sup></a>&emsp;
    <a href='https://kxgong.github.io/' target='_blank'>Kaixiong Gong<sup>1,2*</sup></a>&emsp;
    <a href='https://wlouyang.github.io/' target='_blank'>Wanli Ouyang<sup>2</sup></a>&emsp;
    <a href='http://people.eecs.berkeley.edu/~xyyue/' target='_blank'>Xiangyu Yue<sup>1,†</sup></a>
</div>
<div>

<div align="center">
    <sup>1</sup>
    <a href='http://mmlab.ie.cuhk.edu.hk/' target='_blank'>Multimedia Lab, The Chinese University of Hong Kong</a>&emsp;
    </br>
    <sup>2</sup> <a href='https://github.com/OpenGVLab' target='_blank'>OpenGVLab，Shanghai AI Laboratory 
    </a></br>
    <sup>*</sup> Equal Contribution&emsp;
    <sup>†</sup> Corresponding Author&emsp;
</div>

-----------------

## Point as A Foreign Language, Let Large Language Models (LLMs) Perceive 3D Physical World as Reading Articles!

## 🌟 News
* **2023.7.31:** Github Repository Initialization. The paper will be released very soon.

## Motivation
We propose to utilize pretrained language models for point cloud understanding. Differernt from existing methods leveraging image as intermediate, we found that language models can read point clouds as a foreign language. Benefit from pretraining on the large-scalle corpus, language models performs better in long-tailed and out-of-distibution tasks in 3D vision area. 

###  A Brief Summary

- 💡 **For multimodal research**, our method explores the **underlying representation relationship between different modalities**, specifically, language and 3D point cloud, and demonstrates that models pretrained on natural language can read 3D point clouds.
- 💡 **For 3D vision research**, our method performs **end-to-end point cloud understanding without hand-crafted structure designs**. And it also demonstrates the feasibility of using **natural corpus text as pretraining data for 3D vision**.
- 💡 **For the vision-language area**, our method experimentally validates that **3D point clouds and text can be encoded by the same parameters**. A new promising direction appears for the tasks involving modality alignment between text and point clouds.
- 💡 With outstanding performance across benchmarks including ModelNet-40, S3DIS, and ShapeNetPart, our method demonstrates its effectiveness on both coarse-grained and fine-grained 3D point cloud tasks.


# 🕙 ToDo
- [ ] Support Billion-scale Large Language Models.
- [ ] Large Language Model with More Modalities.
- [ ] Support Outdoor LiDAR Scenes.

# ✉️ Contact
If you are interested in this project, welcome to contribute to our project!

To contact us, you can send an email to `yiyuanzhang.ai@gmail.com` ,`kaixionggong@gmail.com`, or `xyyue@ie.cuhk.edu.hk`!
<br></br>

# License
This project is released under the [Apache 2.0 license](LICENSE).
# Acknowledgement
This code is developed based on an excellent open-sourced project [OpenPoints](https://github.com/guochengqian/openpoints).





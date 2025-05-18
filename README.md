<h1 align="center"><strong>OmniStyle: Filtering High Quality Style Transfer Data at Scale</strong></h1>

<p align="center">
  <a href="https://wangyephd.github.io/">Ye Wang<sup>1</sup></a>,
  Ruiqi Liu<sup>1</sup>,
  Jiang Lin<sup>2</sup>,
  Fei Liu<sup>3</sup>,
  <a href="https://is.nju.edu.cn/yzl_en/main.htm">Zili Yi<sup>2</sup></a>,
  <a href="https://yilinwang.org/">Yilin Wang<sup>4,*</sup></a>,
  <a href="https://ruim-jlu.github.io/#about">Rui Ma<sup>1,5,*</sup></a>
</p>

<p align="center">
  <sup>1</sup>School of Artificial Intelligence, Jilin University &nbsp;&nbsp;
  <sup>2</sup>School of Intelligence Science and Technology, Nanjing University &nbsp;&nbsp;
  <sup>3</sup>ByteDance<br>
  <sup>4</sup>Adobe &nbsp;&nbsp;
  <sup>5</sup>Engineering Research Center of Knowledge-Driven Human-Machine Intelligence, MOE, China<br>
  <sup>*</sup>Corresponding authors
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Project-OmniStyle-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/Paper-arXiv-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Dataset-Open-orange?style=flat-square"/>
  <img src="https://img.shields.io/badge/HuggingFace-Model-yellow?style=flat-square"/>
  <img src="https://img.shields.io/github/stars/your_org/omnistyle?style=social"/>
</p>

---

**OmniStyle** is the first end-to-end style transfer framework based on the Diffusion Transformer (DiT) architecture, achieving high-quality 1K-resolution stylization by leveraging the large-scale, filtered OmniStyle-1M dataset. It supports both instruction- and image-guided stylization, enabling efficient and versatile style transfer across diverse styles. 

**OmniStyle-1M** is the first million-scale paired style transfer dataset, comprising over one million triplets of content, style, and stylized images across 1,000 diverse style categories. It provides strong supervision for learning controllable and generalizable style transfer models. 

**OmniStyle-150K** is a high-quality subset of OmniStyle-1M, specifically filtered to train the OmniStyle model.

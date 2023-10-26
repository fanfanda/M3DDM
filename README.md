# Hierarchical Masked 3D Diffusion Model for Video Outpainting

This is the repository that contains website source code for the paper "Hierarchical Masked 3D Diffusion Model for Video Outpainting". [[Paper](https://arxiv.org/abs/2309.02119)][[Website](https://fanfanda.github.io/M3DDM/)] 

We have made our API public at this [link](https://chuangyi.taobao.com), and merchant users (Currently only support business users) can upload video materials for video outpainting. We have provided a [tutorial](assets/Tutorial.pdf). Due to the practical application in real scenarios, after applying the video outpainting model, we have additionally included a super-resolution model to enhance the filled results after video outpainting. This is different from the pipeline used in the paper. However, in some cases, the super-resolution model may result in a performance decline.
 
![Screenshot](assets/teaser.gif)

## Citation
```bash
@misc{fan2023hierarchical,
      title={Hierarchical Masked 3D Diffusion Model for Video Outpainting}, 
      author={Fanda Fan and Chaoxu Guo and Litong Gong and Biao Wang and Tiezheng Ge and Yuning Jiang and Chunjie Luo and Jianfeng Zhan},
      year={2023},
      eprint={2309.02119},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```

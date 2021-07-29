# **DEEPFILL-V2 DEMONSTRATION**

Colab code for image inpainting. The repository is based out of [DeepFillv2 Pytorch Repo](https://github.com/csqiangwen/DeepFillv2_Pytorch) awesome implementation.
[Original Paper](https://arxiv.org/abs/1806.03589)


```
@article{yu2018generative,
  title={Generative Image Inpainting with Contextual Attention},
  author={Yu, Jiahui and Lin, Zhe and Yang, Jimei and Shen, Xiaohui and Lu, Xin and Huang, Thomas S},
  journal={arXiv preprint arXiv:1801.07892},
  year={2018}
}

@article{yu2018free,
  title={Free-Form Image Inpainting with Gated Convolution},
  author={Yu, Jiahui and Lin, Zhe and Yang, Jimei and Shen, Xiaohui and Lu, Xin and Huang, Thomas S},
  journal={arXiv preprint arXiv:1806.03589},
  year={2018}
}

```

Make sue to change `runtime` in colab to GPU for quick results!

**NOTE**

- The inpainting is being done after resizing the image to 512x512. This can be changed in the RESIZE_TO parameter in the _config.py_ file.
- This repo has not been tested for training. Inference works fine.

Check it out! [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/vrindaprabhu/deepfillv2_colab/blob/main/DeepFillv2_Colab.ipynb)


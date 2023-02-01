---
license: cc-by-nc-sa-4.0
language:
- en
library_name: diffusers
pipeline_tag: text-to-image
tags:
- ' stable-diffusion'
- stable-diffusion-diffusers
---
# Gf_style - 介绍

欢迎使用Gf_style模型 - 这是一个中国华丽古风风格模型，也可以说是一个古风游戏角色模型，具有2.5D的质感。这是一个模型系列，会在未来不断更新模型。

2.0版本已发布：[https://huggingface.co/xiaolxl/Gf_style2](https://huggingface.co/xiaolxl/Gf_style2)

3.0版本已发布：[https://huggingface.co/xiaolxl/Gf_style3](https://huggingface.co/xiaolxl/Gf_style3)

--

Welcome to Gf_style - This is a model of Chinese gorgeous ancient style, which can also be said to be an ancient game character model, with the effect of 2.5D texture. This is a series of models that will be updated in the future.

# install - 安装教程

1. 将XXX.saftensors模型和XXX.yaml放入SD目录 - Put the XXX.safetensors model and XXX.yaml into the SD directory

2. 请记住选择任何VAE文件，否则图形将为灰色 - Remember to select any VAE file, otherwise the drawing will be gray

# How to use - 如何使用

(TIP:人物是竖图炼制，理论上生成竖图效果更好)

如果您想使图片尽可能更好，请尝试以下配置 - If you want to make the picture better as possible, please try the following configuration

- Sampling steps:**30 or 50**

- Sampler:**DDIM** or **(DPM++ 2M Karras, DPM++ SDE Karras)** - These two have different surprises - 这两个有不一样的惊喜

- The size of the picture should be at least **768**, otherwise it will collapse - 图片大小至少768，不然会崩图

- Turn on Hires fix:**R-ESRGAN 4x+ Anime6B** and **Upscale by 2**

- If the face is deformed, try to Open **face repair**

- **key word(Start):**
```
{best quality}, {{masterpiece}}, {highres}, {an extremely delicate and beautiful}, original, extremely detailed wallpaper,
```

- **Negative words:**
```
NSFW, lowres,bad anatomy,bad hands, text, error, missing fingers,extra digit, fewer digits, cropped, worstquality, low quality, normal quality,jpegartifacts,signature, watermark, username,blurry,bad feet
```

# Examples - 例图

(可在文件列表中找到原图，并放入WebUi查看关键词等信息) - (You can find the original image in the file list, and put WebUi to view keywords and other information)

Town building map -- 镇楼图

<img src=https://huggingface.co/xiaolxl/Gf_style/resolve/main/examples/f1.png>

<img src=https://huggingface.co/xiaolxl/Gf_style/resolve/main/examples/f2.png>

Graph generated by keywords in How to use -- How to use中的关键词所生成的图

<img src=https://huggingface.co/xiaolxl/Gf_style/resolve/main/examples/e1.png>

<img src=https://huggingface.co/xiaolxl/Gf_style/resolve/main/examples/e2.png>

<img src=https://huggingface.co/xiaolxl/Gf_style/resolve/main/examples/e3.png>

<img src=https://huggingface.co/xiaolxl/Gf_style/resolve/main/examples/e4.png>

Ending figure -- 收尾图

<img src=https://huggingface.co/xiaolxl/Gf_style/resolve/main/examples/g1.png>

<img src=https://huggingface.co/xiaolxl/Gf_style/resolve/main/examples/g2.png>
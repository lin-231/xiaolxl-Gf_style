---
license: creativeml-openrail-m
language:
- en
library_name: diffusers
pipeline_tag: text-to-image
tags:
- ' stable-diffusion'
- stable-diffusion-diffusers
---
# Gf_style - 介绍

Welcome to Gf_style - This is a model of Chinese gorgeous ancient style, which can also be said to be an ancient game character model, with the effect of 2.5D texture. This is a series of models that will be updated in the future.

--

欢迎使用Gf_style模型 - 这是一个中国华丽古风风格模型，也可以说是一个古风游戏角色模型，具有2.5D的质感。这是一个模型系列，会在未来不断更新模型。

# install - 安装教程

1.Put the XXX.safetensors model and XXX.yaml into the SD directory

2.Remember to select any VAE file, otherwise the drawing will be gray

--

1.将XXX.saftensors模型和XXX.yaml放入SD目录
2.请记住选择任何VAE文件，否则图形将为灰色

# How to use - 如何使用

If you want to make the picture better as possible, please try the following configuration

--

如果您想使图片尽可能更好，请尝试以下配置

Sampling steps:**30 or 50**

Sampler:**DDIM**

**Turn on Hires fix:Latent and Upscale by 2**

**If the face is deformed, try to Open face repair**

**key word(Start):**
```
{best quality}, {{masterpiece}}, {highres}, {an extremely delicate and beautiful}, original, extremely detailed wallpaper,
```

**Negative words:**
```
NSFW, lowres,bad anatomy,bad hands, text, error, missing fingers,extra digit, fewer digits, cropped, worstquality, low quality, normal quality,jpegartifacts,signature, watermark, username,blurry,bad feet
```

# Examples - 例图


---
layout: blog
banana: true
category: AI绘画
title:  Stable Diffusion Ai绘画工具整合包资源 SD网盘分享
date:   2024-03-26 20:06:06
background-image: https://mmbiz.qpic.cn/mmbiz_png/xErpzPePMS4SvCn4qAoTOvoHA8RiaHRVQzLH8JibnAvS3HMg1yKXUybXgZcWCksJic1kM4CG6icqROuwiaWKxt2chTQ/640
tags:
- Stable Diffusion
- Ai绘画
- SD
- 文生图
---
#  背景信息

要说当今绘画圈最大的新秀，那妥妥的就Stable Diffution，V4升级版无需安装，直接解压就能用（在此要感谢秋葉aaaki大佬的分享）比之前推送的更加智能、快速和简单，有多简单呢？这么说吧，之前的版本需要初中生级别现在的V4加强版小学生也能上手。

![Stable Diffution](https://mmbiz.qpic.cn/mmbiz_png/xErpzPePMS4SvCn4qAoTOvoHA8RiaHRVQzLH8JibnAvS3HMg1yKXUybXgZcWCksJic1kM4CG6icqROuwiaWKxt2chTQ/640)

#  Stable Diffusion 是什么？
Stable Diffusion（简称SD）是一种生成式人工智能，于2022年发布，主要用于根据文本描述生成详细图像，也可用于其他任务，如图像的修补、扩展和通过文本提示指导图像到图像的转换。除图像外，您还可以使用该模型创建视频和动画。

这是"AI绘画"第一次能在消费级显卡上运行，任何人都可以下载模型并生成自己的图像。另外，SD高质量的绘图以及强大的自由度(自定义、个性化)受到诸多网友的追捧。Stable Diffusion XL 1.0 (SDXL 1.0) 是Stable Diffusion的一个更为高级和优化的版本，它在模型规模、图像质量、语言理解和模型架构等方面都有显著的改进。

#  Stable Diffusion 能做什么？

首先，大家在入坑SD前，务必要清楚现阶段的SD到底能做什么？能否满足自己的需求？

Stable Diffusion 功能包括文本转图像、图像转图像、图形插图、图像编辑和视频创作。

- 文本转图像生成：最常见和最基础的功能。Stable Diffusion 会根据文本提示生成图像。

- 图像转图像生成使用输入图像和文本提示，您可以根据输入图像创建新图像。典型的案例是使用草图和合适的提示。

- 创作图形、插图和徽标使用一系列提示，可以创建各种风格的插图、图形和徽标。

- 图像编辑和修正可以使用 Stable Diffusion 来编辑和修正照片。例如，可以修复旧照片、移除图片中的对象、更改主体特征以及向图片添加新元素。

- 视频创作使用 GitHub 中的 Deforum 等功能，可以借助 Stable Diffusion 创作短视频片段和动画。另一种应用是为电影添加不同的风格。 还可以通过营造运动印象（例如流水）来为照片制作动画。

#  安装和部署Stable Diffusion

介绍如何安装和部署Stable Diffusion。我使用的是秋葉aaaki的整合包，文章末尾提供180G整合包～

电脑系统：Windows10及以上/macOS Monterey (12.5)。
显卡：RTX3060及以上。
显存：8G及以上。
内存：16G及以上。
磁盘空间：500 SSD及以上

##  步骤一：下载Stable Diffusion整合包后进入文件夹中，解压sd-webui-aki-v4.6
![Stable Diffution](https://mmbiz.qpic.cn/sz_mmbiz_png/562icMQlsX2wmg8aN6dtLle1bq4tX1CiaA2w6vutYGk6KiaOrtngyKUOln5I9y5sB7LWibUZx1pHibzXcib4K0uLDQMg/640)

##  步骤二：双击启动器运行依赖-dotnet-6.0.11，安装所需依赖。
![Stable Diffution](https://mmbiz.qpic.cn/sz_mmbiz_png/562icMQlsX2wmg8aN6dtLle1bq4tX1CiaAor4QTpOAWjic14Tz7gVJN732KVEKqovgMZjtJgKf9CoUS5269xibiafbQ/640)
![Stable Diffution](https://mmbiz.qpic.cn/sz_mmbiz_png/562icMQlsX2wmg8aN6dtLle1bq4tX1CiaASibNsqBNCtOVIoEntP7DkIIARLa5ic02FOwS8cqPqsAPHHia2KPUhg8ng/640)

##  步骤三：最后进入解压好的sd-webui-aki-v4.6文件夹中，下拉找到A绘世启动器并启动。

> 注：第一次启动，需要一些时间部署Python和Git环境，请耐心等待，后面启动就很快了。若未弹出WebUI界面，请将复制链接：http://127.0.0.1:7860 到浏览器中即可。
![Stable Diffution](https://mmbiz.qpic.cn/sz_mmbiz_png/MicSiaicL5eZFyc1lbR32aQ8LFxkMFxJGoakqlRNy7kjxR3BRXkLibICMtqyFRBPN2hzC6Ciaiabc3qV9IeZeSfyZTpQ/640)

若弹出Stable Diffusion WebUI界面，则表示启动成功。
![Stable Diffution](https://mmbiz.qpic.cn/sz_mmbiz_png/MicSiaicL5eZFyc1lbR32aQ8LFxkMFxJGoa5z554icloynV2SnDiaJmSbvAwyQKibSaOUh3qywEkoiaEuQaZ8qrhmXCgw/640)

#  Stable Diffusion 180G 秋葉aaaki整合包+教程

![Stable Diffution](https://mmbiz.qpic.cn/sz_mmbiz_png/562icMQlsX2wmg8aN6dtLle1bq4tX1CiaAb5eJkta1WeQjLc3ONFCllm2WUAC32OkmJmjzJuMGE8KjxWNrZzrP5A/640)
![Stable Diffution](https://mmbiz.qpic.cn/sz_mmbiz_png/562icMQlsX2wmg8aN6dtLle1bq4tX1CiaAvcub1T5aSth2A4p3rzpvHU9HfrBicJuebkU5WS2sZQ90WP4HbfKQXTQ/640)
![Stable Diffution](https://mmbiz.qpic.cn/mmbiz_png/xErpzPePMS4SvCn4qAoTOvoHA8RiaHRVQHQn1OxpHDFnyAicPurGibyEuU8ykje0s7AHqTGsJdIJEH35x1UtZB7lg/640)

打开后的Stable Diffusion Web UI界面。
![Stable Diffution](https://mmbiz.qpic.cn/mmbiz_png/xErpzPePMS4SvCn4qAoTOvoHA8RiaHRVQQukpetOfx7rz6FHe8d2ib91SIufhSNJR440iadAyBcicPkwocQP9mLeng/640)

使用的时候，输入正面提示词和反面提示词（非必须），其他的选项使用默认的就行，然后点击 生成，稍微等待一会，就可以得到生成的图片了。

Stable Diffusion Web UI 界面原本是英文的，我们只需要在其启动器的高级设置中启用云端页面汉化设置，就可以完成Stable Diffusion Web UI 汉化。

关注公众号发送：sdai 获取Stable Diffusion网盘资源下载地址
![8k壁纸社](https://mmbiz.qpic.cn/sz_mmbiz_jpg/562icMQlsX2wmg8aN6dtLle1bq4tX1CiaAmgTNicZY9MJCFsfU7icJzFo6WwibDibqzFFAASeS9yE9iavEiaK3W5LcEkTQ/640)
# Stable Diffusion Lora, Kisara
![](https://img.shields.io/badge/license-Haohanyh%20Computer%20Software%20Products%20Open%20Source%20LICENSE-blue?style=for-the-badge)
![](https://img.shields.io/badge/license-Stable%20Diffusion%20License-blue?style=for-the-badge)

![](https://img.shields.io/github/languages/code-size/Hny0305Lin/SD_Lora_Kisara?style=for-the-badge)
![](https://img.shields.io/github/directory-file-count/Hny0305Lin/SD_Lora_Kisara?style=for-the-badge)
![](https://img.shields.io/github/stars/Hny0305Lin/SD_Lora_Kisara?color=GREEN&label=GITHUB%20STARS&logo=GITHUB&logoColor=green&style=for-the-badge)

😊开始之前，先感谢GitHub的著名项目:`Stable-Diffusion-WebUI`和`sd-webui-additional-networks`开源插件，提供了AI生成的可能性。

😊[Stable-Diffusion-WebUI 点我访问](https://github.com/AUTOMATIC1111/stable-diffusion-webui) | 😊[插件 sd-webui-additional-networks 点我访问](https://github.com/kohya-ss/sd-webui-additional-networks)

注意！本项目会持续开源下去，会存在改进模型的可能，请大家多送点Star谢谢！~反响很好的话我一定会在专升本考试后(可能)更新出更好的模型！~

（2.0，咕咕咕了，事业重要事业重要~~）

## 本项目目前在GitHub外哪里见得到文件和页面呢？
您可以前往海外Huggineface、Civitai网站得到我们的Lora模型文件，当然在GitHub这里也是可以的。

[点我前往huggineface](https://huggingface.co/Hny0305Lin/SD_Lora_Kisara)

[点我前往civitai](https://civitai.com/models/47861?modelVersionId=52456)

由于国内的政策影响，在AI方面还存在很多不确定性，网站平台的审核也的确过于的繁琐了，短期内我不会选择模型投稿至国内社区。敬请谅解。

## 谁是Kisara？我想知道Kisara的具体资料！
可以前往萌娘百科里找到:[点我](https://zh.moegirl.org.cn/zh-hk/%E6%9C%A8%E6%9B%B4)

**木更（キサラ）是跨媒體企劃《Project Engage》之電視動畫作品《契約之吻》中的登場角色，女主角。**

## 那么Lora模型该怎么使用呢？
（在假定您已经安装好了WebUI和插件下，您只需如图所示即可✅）
![如图所示就行啦](https://raw.githubusercontent.com/Hny0305Lin/SD_Lora_Kisara/master/Kisara%20WebUI.png)

如果您还没开始使用WebUI的话，我这里推荐您可以前往这里[国内Bilbili，点我直接打开秋葉aaaki页面](https://space.bilibili.com/12566101/)，获取整合包，即可**直接把Lora插件添加**到`models\Lora`下。

⚠正面Tag里没有Lora的Tag，请记得添加(Markdown写法问题)
| **正面Tag** | **负面Tag** | Steps | **采样方法** | CFG | 种子 | *是否需要面部修复* | 面部修复 | 正常尺寸 | **底模名称 & Hash哈希值** | *是否需要高分辨率修复* | 放大算法 | 高分辨率迭代步数 | 重绘幅度 | 放大倍数 |
|  ----  |  ----  |  ----  |  ----  |  ----  |  ----  |  ----  |  ----  |  ----  |  ----  |  ----  |  ----  |  ----  |  ----  |  ----  |
| 1girl, bangs, black_ribbon, blurry, blurry_background, closed_mouth, collarbone, crying, crying_with_eyes_open, eyebrows_visible_through_hair, hair_between_eyes, hair_ornament, hair_ribbon, hairclip, long_hair, looking_at_viewer, pink_eyes, pink_hair, ribbon, sailor_collar, school_uniform, serafuku, solo, tears, x_hair_ornament | (worst quality:2, low quality:2), (zombie, sketch, interlocked fingers, comic), | 40 | DPM++ SDE Karras | 7 | 3345681139（可不填） | ✅ | GFPGAN | 512x768 | Counterfeit-V2.5 bd83b90a2e | ✅ | R-ESRGAN 4x+ | 10 | 0.3 | 2 |
| masterpiece, best quality, 1girl, bangs, black ribbon, blurry, blurry background, closed mouth, collarbone, eyebrows visible through hair, hair between eyes, hair ornament, hair ribbon, hairclip, long hair, looking at viewer, pink eyes, pink hair, ribbon, sailor collar, school uniform, serafuku, solo, tears, x hair ornament, |  (worst quality, low quality:1.4), (bad anatomy), (bad hands), (bad clothes), (zombie, sketch, interlocked fingers, comic), (missing arms:1.331), (extra legs:1.331), (fused fingers:1.61051), (too many fingers:1.61051), (unclear eyes:1.331), missing fingers, extra digit, (futa:1.1), logo, white letters,missing fingers, extra digit, fewer digits,(mutated hands and fingers:1.5 ), (long body :1.3), bad hands, fused hand, missing hand, disappearing arms, error, missing fingers, missing limb,fused fingers, one hand with more than 5 fingers, one hand with less than 5 fingers, one hand with morethan 5 digit, one hand with less than 5 digit, extra digit, fewer digits, fused digit, missing digit, watermark, text, title, | 40 | DPM++ SDE Karras | 7 | 3875681161（可不填） | ✅ | GFPGAN | 512x768 | Counterfeit-V2.5 bd83b90a2e | ✅ | R-ESRGAN 4x+ | 10 | 0.3 | 2 |

| 本项目将会持续下去直到永远，欢迎大家踊跃添加Tag分享出来送给需要的人!❤ |

## 开源协议？
由于本项目为我第一次公开，并且也是匆匆花钱训练的Lora模型，所以我很希望使用本Lora模型的人，都能遵守我下面填写的开源协议和`中国大陆`在2023年4月11日的通知：**国家互联网信息办公室关于《生成式人工智能服务管理办法（征求意见稿）》公开征求意见**。

### Copyright (c) 2022 Robin Rombach and Patrick Esser and contributors 

Stable-Diffusion-WebUI协议地址:[点我](https://huggingface.co/spaces/CompVis/stable-diffusion-license)

介绍：Stable-Diffusion-WebUI, A browser interface based on Gradio library for Stable Diffusion.

### 版权所有 (C) 2019-FUTURE 浩瀚银河，版权所有。

**永久开源，合法使用即可。**
使用开源协议：Haohanyh Computer Software Products Open Source LICENSE

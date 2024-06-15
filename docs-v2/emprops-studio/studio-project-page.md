---
description: Understanding the many features and nodes within the Studio's Creative Suite
---

# 📔 Studio Project Page

### **Studio Sketchbook Directory**

The Studio Sketchbook Directory is the central hub for organizing and managing all your project sketchbooks. Users can view, create, and manage sketchbooks here, providing an organized workspace for various projects. Each sketchbook can contain multiple pages and project variations.

[![](https://downloads.intercomcdn.com/i/o/1054690564/ef52cec4bcd391b53f4c6fb9/image.png?expires=1716564600\&signature=7463e4d26d0ce917b7662801b05d1214ea6ea6808bac151bdbf5084325e2b5d1)](https://downloads.intercomcdn.com/i/o/1054690564/ef52cec4bcd391b53f4c6fb9/image.png?expires=1716564600\&signature=7463e4d26d0ce917b7662801b05d1214ea6ea6808bac151bdbf5084325e2b5d1)

### Studio Project Page <a href="#h_5dab79fd5f" id="h_5dab79fd5f"></a>

The Studio Sketchbook Viewer allows users to view and interact with the contents of a specific sketchbook. This feature provides a detailed look at each project's pages, variables, and settings, enabling thorough project management and customization.

[![](https://downloads.intercomcdn.com/i/o/1054691982/f022b19b9d9e36be11932fa5/image.png?expires=1716485400\&signature=5f2e6f479df583d2c65d863c90bf105c5754b8491a3492774f4db1f07ac97718)](https://downloads.intercomcdn.com/i/o/1054691982/f022b19b9d9e36be11932fa5/image.png?expires=1716485400\&signature=5f2e6f479df583d2c65d863c90bf105c5754b8491a3492774f4db1f07ac97718)

## Setup <a href="#h_ca1c7608c0" id="h_ca1c7608c0"></a>

#### Set Hashes <a href="#h_c8644a3421" id="h_c8644a3421"></a>

Set Hashes is a feature that allows users to manually control the random seeds for consistent image generation across attempts. While the select-seed tool can control the StableDiffusion seed only, the manual hash affects the StableDiffusion seed, the random variables seed, and the 'pseudorandom' elements within your p5.js code.

[![](https://downloads.intercomcdn.com/i/o/1054692647/e780e6b8f281d3ec8088103a/image.png?expires=1716485400\&signature=59f0a39dc594db2cb88de51b8bbee3d5691e7a2961df59c7e5368d6c7066e939)](https://downloads.intercomcdn.com/i/o/1054692647/e780e6b8f281d3ec8088103a/image.png?expires=1716485400\&signature=59f0a39dc594db2cb88de51b8bbee3d5691e7a2961df59c7e5368d6c7066e939)

### Enable PNG Info <a href="#h_d3ed00079e" id="h_d3ed00079e"></a>

[![](https://downloads.intercomcdn.com/i/o/1054694479/4a16bfeb116ea01feaf7b423/image.png?expires=1716485400\&signature=2b9200d4d884e9ba8e601f06022dea26ff31c8e4a6ca8f338421773b25812497)](https://downloads.intercomcdn.com/i/o/1054694479/4a16bfeb116ea01feaf7b423/image.png?expires=1716485400\&signature=2b9200d4d884e9ba8e601f06022dea26ff31c8e4a6ca8f338421773b25812497)

Enable PNG Info allows users to choose whether a generated image contains the generation information (prompt, settings) within the metadata. This feature provides transparency and insights into the AI's creation parameters and settings. To view the instructions in an image's metadata, either open the image with a notepad app, or use a 3rd-party tool such as the [PNG chunk inspector](https://www.nayuki.io/page/png-file-chunk-inspector).

[PNG chunk inspector](https://www.nayuki.io/page/png-file-chunk-inspector)

### Prompt <a href="#h_b15d93079d" id="h_b15d93079d"></a>

A Prompt is a text description that guides the AI in generating the desired image. Effective prompts are crucial for achieving the intended artistic output.

[![](https://downloads.intercomcdn.com/i/o/1054695168/8b57217e37e8cf415a9f69a9/image.png?expires=1716485400\&signature=58a599255eef1e46919817245404df5da7d42c7dda837cbc4f129f11fbaad1a4)](https://downloads.intercomcdn.com/i/o/1054695168/8b57217e37e8cf415a9f69a9/image.png?expires=1716485400\&signature=58a599255eef1e46919817245404df5da7d42c7dda837cbc4f129f11fbaad1a4)

### Negative Prompt <a href="#h_cd218ddf36" id="h_cd218ddf36"></a>

Likewise, a negative prompt is a text description that guides the AI by telling it what \*not\* to include in the generated image.

[![](https://downloads.intercomcdn.com/i/o/1054696059/702b30b3337752614ca4d088/image.png?expires=1716485400\&signature=770193805c62e00ab972101e79a449e4ae084fc5a8da0dc3c8496b580763614f)](https://downloads.intercomcdn.com/i/o/1054696059/702b30b3337752614ca4d088/image.png?expires=1716485400\&signature=770193805c62e00ab972101e79a449e4ae084fc5a8da0dc3c8496b580763614f)



### **Stable Diffusion Checkpoints**

Pre-trained models that generate new images based on learned knowledge. Training size significantly affects performance.

**Stable Diffusion Models**

* **SD 1.5**: Trained at 512x512 pixels, performs best with small resolutions.
* **SD 2.1**: Trained at 768x768 pixels, ideal around that size.
* **SDXL models**: Trained at 1024x1024 pixels, great for high-resolution and high-quality outputs.

### Sampling Method <a href="#h_7dd71f6a13" id="h_7dd71f6a13"></a>

The Sampling Method is the algorithm used to generate the image, affecting the style and details. Different methods can produce varying artistic effects and levels of detail.&#x20;

### Sampling Steps <a href="#h_724b0bf581" id="h_724b0bf581"></a>

Sampling Steps refer to the number of times the image is refined for higher quality during the generation process. More steps typically result in more detailed and polished images.

### CFG Scale (Prompt Strength) <a href="#h_f4f1a1f962" id="h_f4f1a1f962"></a>

CFG Scale (Prompt Strength) controls how closely the AI adheres to the prompt. A higher value means more adherence to the prompt, resulting in images that closely match the description.

### Width & Height <a href="#h_28c59acb7c" id="h_28c59acb7c"></a>

Width & Height are the dimensions of the generated image. Users can specify these settings to fit their specific project requirements.

### img2img <a href="#h_b6dcecd7e5" id="h_b6dcecd7e5"></a>

The img2img toggle turns on image-to-image generation, which allows the Studio to use an existing image as a starting point. This feature allows for creating derivative artworks based on a source image. There are three img2img options:\
​

*   **Const**

    Select a single constant image from your flatfiles to be used with every generation
*   **Var**

    Select images at random from a gallery of pre-selected images from your flatfiles. To set up an img2img variables group, see "Variables"
*   **p5.js**

    Using p5.js code, create a generative artwork for each image. For more information, see the article on [p5.js](p5.js-guide.md).

### Upscaler <a href="#h_61e756d732" id="h_61e756d732"></a>

The Upscaler enhances the resolution and quality of generated images. This tool is essential for creating high-definition outputs suitable for printing and high-quality displays.\
((((note: add info regarding different upscalers, blending, GFPGAN etc))))

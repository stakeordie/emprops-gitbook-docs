---
description: Understanding the many features and nodes within the Studio's Creative Suite
---

# 📔 Studio Project Page

### **Studio Sketchbook Directory**

The Studio Sketchbook Directory is the central hub for organizing and managing all your project sketchbooks. Users can view, create, and manage sketchbooks here, providing an organized workspace for various projects. Each sketchbook can contain multiple pages and project variations.

![](<../../.gitbook/assets/image (8).png>)

### Studio Project Page <a href="#h_5dab79fd5f" id="h_5dab79fd5f"></a>

The Studio Sketchbook Viewer allows users to view and interact with the contents of a specific sketchbook. This feature provides a detailed look at each project's pages, variables, and settings, enabling thorough project management and customization.

<figure><img src="../../.gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>

## Nodes <a href="#h_ca1c7608c0" id="h_ca1c7608c0"></a>

The Studio functions via a set of nodes which perform diferent functions. We will detail the nodes in the following sections:

## Setup Node <a href="#h_ca1c7608c0" id="h_ca1c7608c0"></a>

<figure><img src="../../.gitbook/assets/image (11).png" alt=""><figcaption><p>Click the - or + buttons to change the number of images generated per batch.</p></figcaption></figure>

#### The Setup node allows you to determine how many image generations you will produce with each press of the Generate button. Typically the generations are randomized with unique hashes, but if you would like to control the output settings within the Studio, you can lock in the randomization with the Set Hashes Manually tool: <a href="#h_c8644a3421" id="h_c8644a3421"></a>

#### Set Hashes Manually: <a href="#h_c8644a3421" id="h_c8644a3421"></a>

Set Hashes is a feature that allows users to manually control the random seeds for consistent image generation across attempts. While the select-seed tool can control the StableDiffusion seed only, the manual hash affects the StableDiffusion seed, the random variables seed, and the 'pseudorandom' elements within your p5.js code.

<figure><img src="../../.gitbook/assets/image (12).png" alt=""><figcaption><p>With Set hashes Manually selected, you can re-run the same processes exactly, resulting in a deterministic output. </p></figcaption></figure>

## Stable Diffusion Node <a href="#h_d3ed00079e" id="h_d3ed00079e"></a>

<figure><img src="../../.gitbook/assets/image (13).png" alt=""><figcaption></figcaption></figure>

### Enable PNG info

Enable PNG Info allows users to choose whether a generated image contains the generation information (prompt, settings) within the metadata. This feature provides transparency and insights into the AI's creation parameters and settings. To view the instructions in an image's metadata, either open the image with a notepad app, or use a 3rd-party tool such as the [PNG chunk inspector](https://www.nayuki.io/page/png-file-chunk-inspector).

### Prompt and Negative Prompt <a href="#h_b15d93079d" id="h_b15d93079d"></a>

A Prompt is a text description that guides the AI in generating the desired image. Effective prompts are crucial for achieving the intended artistic output.

Likewise, a negative prompt is a text description that guides the AI by telling it what \*not\* to include in the generated image.

<figure><img src="../../.gitbook/assets/image (14).png" alt=""><figcaption><p>A Prompt describing a fashionable scene with a {{Texture}} variable, while the negative prompt ensures the image is not cut off or oversaturated.</p></figcaption></figure>

The **Enhance AI** function allows you to run your prompt through a Large Language Model like ChatGPT in order to improve the prompt's level of detail. You can also add Enhance instructions to your prompt, usually by adding them in parenthesis at the very beginning of your prompt, such as _(When Enhancing this prompt, please rewrite it as an acrostic poem that spells out "AIART")_

### **Stable Diffusion Checkpoints**

<figure><img src="../../.gitbook/assets/image (15).png" alt=""><figcaption></figcaption></figure>

Pre-trained models that generate new images based on learned knowledge. Training size significantly affects performance.

**Stable Diffusion Models**

* **SD 1.5**: Trained at 512x512 pixels, performs best with small resolutions.
* **SD 2.1**: Trained at 768x768 pixels, ideal around that size.
* **SDXL models**: Trained at 1024x1024 pixels, great for high-resolution and high-quality outputs.

### Sampling Method <a href="#h_7dd71f6a13" id="h_7dd71f6a13"></a>

<figure><img src="../../.gitbook/assets/image (16).png" alt=""><figcaption></figcaption></figure>

The Sampling Method is the algorithm used to generate the image, affecting the style and details. Different methods can produce varying artistic effects and levels of detail.&#x20;

### Sampling Steps <a href="#h_724b0bf581" id="h_724b0bf581"></a>

Sampling Steps refer to the number of times the image is refined for higher quality during the generation process. More steps typically result in more detailed and polished images.

### CFG Scale (Prompt Strength) <a href="#h_f4f1a1f962" id="h_f4f1a1f962"></a>

CFG Scale (Prompt Strength) controls how closely the AI adheres to the prompt. A higher value means more adherence to the prompt, resulting in images that closely match the description.

### Width & Height <a href="#h_28c59acb7c" id="h_28c59acb7c"></a>

Width & Height are the dimensions of the generated image. Users can specify these settings to fit their specific project requirements.

### img2img <a href="#h_b6dcecd7e5" id="h_b6dcecd7e5"></a>

<figure><img src="../../.gitbook/assets/image (17).png" alt=""><figcaption></figcaption></figure>

The img2img toggle turns on image-to-image generation, which allows the Studio to use an existing image as a starting point. This feature allows for creating derivative artworks based on a source image. There are three img2img options:\
​

*   **Const**

    Select a single constant image from your flatfiles to be used with every generation
*   **Var**

    Select images at random from a gallery of pre-selected images from your flatfiles. To set up an img2img variables group, see "Variables"
*   **p5.js**

    Using p5.js code, create a generative artwork for each image. For more information, see the article on [p5.js](p5.js-guide.md).

### Refiner

The Refiner tool allows model switching during generation. With the current SDXL\_Refiner model, setting Refiner to 0.75 in a 40-step generation means the first 30 steps use your selected checkpoint, and the final 10 steps use SDXL\_Refiner. \
note: the Refiner was designed with XL models in mind. Using the refiner with any non-SDXL-based model will result in some very strange looking artifacts.

### Upscaler Node <a href="#h_61e756d732" id="h_61e756d732"></a>

<figure><img src="../../.gitbook/assets/image (18).png" alt=""><figcaption></figcaption></figure>

The Upscaler enhances the resolution and quality of generated images. This tool is essential for creating high-definition outputs suitable for printing and high-quality displays. You can blend multiple upscalers and/or make use of tools to improve faces such as GFPGAN and Codeformer

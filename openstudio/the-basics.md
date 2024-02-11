# The Basics

#### Profile Setup

We highly recommend, nay we insist, that you setup your profile so that everyone can see who is publishing what. Here’s an explainer to make it dead simple.\
\


### Getting Comfortable

#### Prompt Field

This is where you write prompts.

It’s the same as any prompt field you are used to, but it has a superpower, it accepts template prompts with variables. I will go over that more and in detail later

Negative Prompt

This is where you type in words that represent things you don’t want to see

Model

Currently, we offer four models: SD 1.5, SD 2.1, SDXL 0.9 (beta), and SDXL 1.0. We will be adding new models over time, and will make announcements when we do.

Number of Generations

The Number of Generations determines how many images will be generated when you hit the ‘Generate’ button. The more images, the longer the load time.

Sampling Method

\<aside> 💡 To learn more, check out the guide by stable-diffusion-art: [https://stable-diffusion-art.com/samplers/](https://stable-diffusion-art.com/samplers/)

\</aside>

CFG Scale

\<aside> 💡 In Stable Diffusion, CFG stands for Classifier Free Guidance scale. CFG is **the setting that controls how closely Stable Diffusion should follow your text prompt**.

\</aside>

Width

* Determines how many pixels wide your image will be (pre-upscale)

Height

* Determines how many pixels wide your image will be (pre-upscale)

Generate

* Press Generate to run the image generation algorithm!

Features

Upscaler

* Upscale the image using the custom EmProps upscaling recipe. Images take longer to generate with this turned on.

Preserve Last Generation

* Keep the same OpenStudio variation hash, stablediffusion hash, and P5.js seed settings when re-running your prompt.

img2img

Fixed

* Select an image from your FlatFiles to be used for every image generated.

Variable

* Randomly chooses an image from a user-selected group of image variables (see [Variables](https://www.notion.so/Variables-891b88334d444e80b267317e2f12ecd4?pvs=21))

p5.js

* Generates an image using p5.js and sends it to the img2img. Each image generated gets a unique p5.js output.

Denoising Strength

* The Denoising Strength parameter determines the extent to which the image will be altered during the img2img process. A value of 0 results in the raw, unmodified image being displayed, while a value of 1 produces an image that is almost entirely dissimilar to the original.

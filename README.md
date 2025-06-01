

## Introduction
We are thrilled to release **Qwen-Image**, a 20B MMDiT image foundation model that achieves significant advances in **complex text rendering** and **precise image editing**. Experiments show strong general capabilities in both image generation and editing, with exceptional performance in text rendering, especially for Chinese.


![](https://qianwen-res.oss-cn-beijing.aliyuncs.com/Qwen-Image/bench.png#center)

## News
- 2026.02.10: We are launching Qwen-Image-2.0, a next-generation foundational image generation model. The key highlights of Qwen-Image-2.0 include:

    * **Professional Typography Rendering** – Supports 1k-token instructions for direct generation of professional infographics, including PPTs, posters, comics, and more.
    * **Stronger Semantic Adherence** – Native 2K resolution support for finely detailed realistic scenes, including people, nature, and architecture.
    * **Improved Text Rendering** – Integrated understanding and generation capabilities, unifying image generation and editing in a single mode
    * **Lighter Model Architecture**  – Smaller model size with faster inference speed.
Check our [Blog](https://qwen.ai/blog?id=qwen-image-2.0) for more details! Also give it a try at [Qwen Chat](https://chat.qwen.ai/?inputFeature=t2i).
- 2025.12.31: We released Qwen-Image-2512 weights! Check at [Huggingface](https://huggingface.co/Qwen/Qwen-Image-2512) and [ModelScope](https://modelscope.cn/models/Qwen/Qwen-Image-2512)!
- 2025.12.31: We released Qwen-Image-2512! Check our [Blog](https://qwen.ai/blog?id=qwen-image-2512) for more details!
    🚀 Our December upgrade to Qwen-Image, just in time for the New Year.

    ✨ What’s new:
    • More realistic humans — dramatically reduced “AI look,” richer facial & age details
    • Finer natural textures — sharper landscapes, water, fur, and materials
    • Stronger text rendering — better layout, higher accuracy in text–image composition

    🏆 Tested in 10,000+ blind rounds on AI Arena, Qwen-Image-2512 ranks as the strongest open-source image model, while staying competitive with closed-source systems.
    ![](https://qianwen-res.oss-cn-beijing.aliyuncs.com/Qwen-Image/image2512/arena.png#center)
- 2025.12.31: [Qwen-Image-Lightning](https://github.com/ModelTC/Qwen-Image-Lightning), developed by [Lightx2v](https://github.com/ModelTC/LightX2V), provides [Day 0 acceleration support for Qwen-Image-2512](https://huggingface.co/lightx2v/Qwen-Image-2512-Lightning).
- 2025.12.31:vLLM-Omni supports high performance Qwen-Image-2512 inference from Day-0, with long sequence parallelism, cache acceleration and fast kernels, please check [here](https://github.com/vllm-project/vllm-omni/tree/main/examples/offline_inference/text_to_image) for details.
- 2025.12.23: We released Qwen-Image-Edit-2511 weights! Check at [Huggingface](https://huggingface.co/Qwen/Qwen-Image-Edit-2511) and [ModelScope](https://modelscope.cn/models/Qwen/Qwen-Image-Edit-2511)!
- 2025.12.23: We released Qwen-Image-Edit-2511! Check our [Blog](https://qwen.ai/blog?id=qwen-image-edit-2511) for more details!
- 2025.12.23: **[LightX2V](https://github.com/ModelTC/LightX2V/)** delivers Day 0 acceleration for Qwen-Image-Edit-2511, with native support for a wide range of hardware, including **NVIDIA, Hygon, Metax, Ascend, and Cambricon**. By combining **[diffusion distillation](https://github.com/ModelTC/Qwen-Image-Lightning)** with cutting-edge inference optimizations, LightX2V achieves a **25x reduction in DiT NFEs** and **an order-of-magnitude 42.55x overall speedup**, enabling real-time image editing across diverse AI accelerators.
- 2025.12.23: **vLLM-Omni** supports high performance `Qwen-Image-Edit-2511`, `Qwen-Image-Layered` inference from Day-0, with long sequence parallelism, cache acceleration and fast kernels, please check [here](https://github.com/vllm-project/vllm-omni/tree/main/examples/offline_inference/image_to_image) for details.

- 2025.12.23: **SGLang-Diffusion** provides day-0 support for Qwen-Image models. To play with `Qwen-Image-Edit-2511` in SGlang, please check community supports section for details.

- 2025.12.19: We released Qwen-Image-Layered weights! Check at [Huggingface](https://huggingface.co/Qwen/Qwen-Image-Layered) and [ModelScope](https://modelscope.cn/models/Qwen/Qwen-Image-Layered)!
- 2025.12.19: We released Qwen-Image-Layered! Check our [Blog](https://qwenlm.github.io/blog/qwen-image-layered) for more details!
- 2025.12.18: We released our [Research Paper](https://arxiv.org/abs/2512.15603) on Arxiv!
- 2025.11.11: **[T2I-CoreBench](https://t2i-corebench.github.io/)** offers a comprehensive and complex evaluation of T2I models in real-world scenarios. On this benchmark, Qwen-Image achieves state-of-the-art performance under real-world complexities in both composition and reasoning T2I tasks, surpassing other open-source models and showing comparable results to closed-source ones.
- 2025.11.07: LeMiCa is a diffusion model inference acceleration solution developed by China Unicom Data Science and Artificial Intelligence Research Institute. By leveraging cache-based techniques and global denoising path optimization, LeMiCa provides efficient inference support for Qwen-Image, achieving nearly 3x lossless acceleration while maintaining visual consistency and quality. For more details, please visit the homepage: [https://unicomai.github.io/LeMiCa/](https://unicomai.github.io/LeMiCa/)

- 2025.09.22: This September, we are pleased to introduce Qwen-Image-Edit-2509, the monthly iteration of Qwen-Image-Edit. To experience the latest model, please visit [Qwen Chat](https://qwen.ai)  and select the "Image Editing" feature. Compared with Qwen-Image-Edit released in August, the main improvements of Qwen-Image-Edit-2509 include:

- 2025.08.19: We have observed performance misalignments of Qwen-Image-Edit. To ensure optimal results, please update to the latest diffusers commit. Improvements are expected, especially in identity preservation and instruction following.
- 2025.08.18: We’re excited to announce the open-sourcing of Qwen-Image-Edit! 🎉 Try it out in your local environment with the quick start guide below, or head over to [Qwen Chat](https://chat.qwen.ai/) or [Huggingface Demo](https://huggingface.co/spaces/Qwen/Qwen-Image-Edit) to experience the online demo right away! If you enjoy our work, please show your support by giving our repository a star. Your encouragement means a lot to us!
- 2025.08.09: Qwen-Image now supports a variety of LoRA models, such as MajicBeauty LoRA, enabling the generation of highly realistic beauty images. Check out the available weights on [ModelScope](https://modelscope.cn/models/merjic/majicbeauty-qwen1/summary).
![](https://qianwen-res.oss-cn-beijing.aliyuncs.com/Qwen-Image/magicbeauty.png#center)
    
- 2025.08.05: Qwen-Image is now natively supported in ComfyUI, see [Qwen-Image in ComfyUI: New Era of Text Generation in Images!](https://blog.comfy.org/p/qwen-image-in-comfyui-new-era-of)
- 2025.08.05: Qwen-Image is now on Qwen Chat. Click [Qwen Chat](https://chat.qwen.ai/) and choose "Image Generation".
- 2025.08.05: We released our [Technical Report](https://arxiv.org/abs/2508.02324) on Arxiv!
- 2025.08.04: We released Qwen-Image weights! Check at [Huggingface](https://huggingface.co/Qwen/Qwen-Image) and [ModelScope](https://modelscope.cn/models/Qwen/Qwen-Image)!
- 2025.08.04: We released Qwen-Image! Check our [Blog](https://qwenlm.github.io/blog/qwen-image) for more details!

> [!NOTE]
> Due to heavy traffic, if you'd like to experience our demo online, we also recommend visiting DashScope, WaveSpeed, and LibLib. Please find the links below in the community support.




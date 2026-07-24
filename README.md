# Amuse
Amuse is the flagship demo application for the [TensorStack SDK](https://github.com/saddam213/TensorStack), showcasing high-performance local AI image, video, audio and text generation through a modern, extensible .NET architecture.

<div align="center">
   <h1><a href="https://github.com/saddam213/AmuseAI/releases/download/v3.6.1/Amuse_v3.6.1.exe">Download Amuse v3.6.1</a></h1>
</div>

## Features
* Automatic installation of an isolated, Python environment.
* Safetensors, GGUF, and ONNX support.
* Video Editor for generated or local content.
* Image/Video Upscale for static and moving media.
* Feature Extraction from images and video.
* Video Interpolation for frame rates and slow-motion.
* Image Inpaint to remove objects or fill areas.
* Advanced Image Editing with selection and masking tools.
* Voice Generation (Supertonic).
* Speech Recognition (Whisper).
* Media Gallery for organization and management.
* Lora/ControlNet Support for output control.

---

## Image Pipelines
- Z-Image
- Qwen
- FLUX.1
- FLUX.2
- Chroma
- Kandinsky5
- StableDiffusion-XL
- StableDiffusion-3
- Ernie Image
- Anima
- JoyAI Image
- PRX-Pixel
- Krea2
- GLM Image
- Ideogram4

## Video Pipelines
- LTX
- LTX-2
- Wan 2.2
- CogVideoX
- Kandinsky5
- SkyReels-V2
- Helios
- Motif
- AnyFlow

## Audio Pipelines
- ACE-Step XL
- Whisper
- Supertonic v3
- LongCat Audio

## Text Pipelines
- Qwen3

---

## GPU Support
Amuse utilizes `NVIDIA CUDA 13.0` for local hardware acceleration.

### Nvidia GPU Support
Amuse leverages `CUDA 13.0`, providing native support for the latest generation of hardware.<br /> While legacy architectures (Pascal/Maxwell) are technically supported, an RTX-enabled card is strongly recommended to utilize Tensor Cores for efficient generation speeds.
<table>
  <thead>
    <tr>
      <th>Architecture</th>
      <th>Platform Support</th>
      <th>GPU Models</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><b>Blackwell</b> (SM_100)</td>
      <td>Windows 10, 11, Server 22</td>
      <td>GeForce RTX 5090, 5080, 5070 Ti, 5070; RTX PRO Blackwell series</td>
    </tr>
    <tr>
      <td><b>Ada Lovelace</b> (SM_89)</td>
      <td>Windows 10, 11, Server 22</td>
      <td>GeForce RTX 4090, 4080, 4070 Ti/Super, 4070, 4060 Ti, 4060; RTX 6000/5000/4000 Ada</td>
    </tr>
    <tr>
      <td><b>Ampere</b> (SM_86)</td>
      <td>Windows 10, 11, Server 22</td>
      <td>GeForce RTX 3090 Ti, 3090, 3080 Ti, 3080, 3070 Ti, 3070, 3060 Ti, 3060; RTX A-series (A6000, etc.)</td>
    </tr>
    <tr>
      <td><b>Turing</b> (SM_75)</td>
      <td>Windows 10, 11, Server 22</td>
      <td>GeForce RTX 2080 Ti, 2080 Super, 2070, 2060; GTX 1660 Ti, 1660 Super, 1650</td>
    </tr>
  </tbody>
</table>

> Note: Minimum Driver (NVIDIA): `Version 580.65` or later is required for `CUDA 13.0` compatibility.

---

### AMD GPU Support
AMD GPU's are currently not supported<br />
For `AMD` devices I recommend `ComfyUI` or `AMD Lemonade Server`, these will have full support for AMD.

ComfyUI:
[https://comfy.org/](https://comfy.org/)

Lemonade Server:
[https://lemonade-server.ai/](https://lemonade-server.ai/)

---

### Intel GPU Support
Intel GPU's are currently not supported<br />
For `Intel` devices I recommend `ComfyUI` or `Intel AI Playground`, these will have full support for Intel.

ComfyUI:
[https://comfy.org/](https://comfy.org/)

Intel AI Playground:
[https://www.intel.com/content/www/us/en/products/docs/discrete-gpus/arc/software/ai-playground.html](https://www.intel.com/content/www/us/en/products/docs/discrete-gpus/arc/software/ai-playground.html)

---


<div align="center">
   <h1><a href="https://github.com/saddam213/AmuseAI/releases/download/v3.6.1/Amuse_v3.6.1.exe">Download Amuse v3.6.1</a></h1>
</div>


### External Dependencies
- `PdfPig` https://github.com/UglyToad/PdfPig
- `Markdig` https://github.com/xoofx/markdig
- `Serilog` https://github.com/serilog/serilog
- `ColorCode` https://github.com/CommunityToolkit/ColorCode-Universal
- `TensorStack` https://github.com/saddam213/TensorStack
- `HtmlAgilityPack` https://github.com/zzzprojects/html-agility-pack

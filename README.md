# ComfyUI Tools Roadmap 🎮

<p align="center">
  <img src="ComfyUI.png" alt="ComfyUI" style="display:block; margin:auto; width:650px;" />
</p>

Here we will track the latest development tools for ComfyUI, including Image, Mesh, Texture, 3D Model, Animation, Video, Avatar, Audio, Music and more!🔥

## Table of Contents

* [ComfyUI](#comfyui)
* [Image](#image)
* [Mesh](#mesh)
* [Texture](#texture)
* [3D Model](#model)
* [Animation](#animation)
* [Video](#video)
* [Avatar](#avatar)
* [Audio](#audio)
* [Music](#music)
* [ComfyUI Workflow](#workflow)


## Project List

### <span id="comfyui">ComfyUI</span>

| ComfyUI                                                                                      | Description                                                                                                                                                                                    |   Source   |   Paper   |
| :------------------------------------------------------------------------------------------ | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :-----------: | :-------: |
| [Comflowyspace](https://github.com/6174/comflowyspace)                                         | Comflowyspace is an open-source AI image and video generation tool committed to providing a better, interactive experience than the standard SDWebUI and ComfyUI.  | [Comflowyspace](https://github.com/6174/comflowyspace)         |         |
| [ComfyUI](https://github.com/comfyanonymous/ComfyUI)                                           | The most powerful and modular stable diffusion GUI and backend.                                                         | [ComfyUI](https://github.com/comfyanonymous/ComfyUI)              |         |
| [ComfyUI Browser](https://github.com/talesofai/comfyui-browser)                                | An image/video/workflow browser and manager for ComfyUI.                                                                | [ComfyUI Browser](https://github.com/talesofai/comfyui-browser)              |         |
| [Comfy.ICU](https://github.com/pagebrain/comfyicu)                                           | ComfyICU - Run ComfyUI workflows in the Cloud.                                                                            | [Comfy.ICU](https://github.com/pagebrain/comfyicu)              |         |
| [ComfyUI-Custom-Scripts](https://github.com/pythongosssss/ComfyUI-Custom-Scripts)              | Enhancements & experiments for ComfyUI, mostly focusing on UI features.                                                 | [ComfyUI-Custom-Scripts](https://github.com/pythongosssss/ComfyUI-Custom-Scripts)       |         |
| [ComfyUI Manager](https://github.com/ltdrdata/ComfyUI-Manager)                                 | ComfyUI-Manager is an extension designed to enhance the usability of ComfyUI.                                           | [ComfyUI Manager](https://github.com/ltdrdata/ComfyUI-Manager)    |         |
| [ComfyUI_TensorRT](https://github.com/comfyanonymous/ComfyUI_TensorRT)                         | This node enables the best performance on NVIDIA RTX™ Graphics Cards  (GPUs) for Stable Diffusion by leveraging NVIDIA TensorRT.           | [ComfyUI_TensorRT](https://github.com/comfyanonymous/ComfyUI_TensorRT)    |         |

<p style="text-align: right;"><a href="#table-of-contents">^ Back to Contents ^</a></p>


### <span id="image">Image</span>

| ComfyUI                                                                                      | Description                                                                                                                                                                                    |   Source   |   Paper   |
| :------------------------------------------------------------------------------------------ | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :-----------: | :-------: |
| [ComfyUI-AnyText](https://github.com/zmwv823/ComfyUI-AnyText)                 | AnyText: Multilingual Visual Text Generation And Editing.                                | [AnyText](https://github.com/tyxsspa/AnyText)               |[arXiv](https://arxiv.org/abs/2311.03054)  |
| [comfyui_controlnet_aux](https://github.com/Fannovel16/comfyui_controlnet_aux)                 | ComfyUI's ControlNet Auxiliary Preprocessors.                                                                                                                                    |          |          |
| [ComfyUI_ExtraModels](https://github.com/city96/ComfyUI_ExtraModels)                 | Support for miscellaneous image models. Currently supports: DiT, PixArt, T5 and a few custom VAEs.                                | [Hunyuan-DiT](https://github.com/Tencent/HunyuanDiT)               |[arXiv](https://arxiv.org/abs/2403.08857)  |
| [ComfyUI-Flowty-LDSR](https://github.com/flowtyone/ComfyUI-Flowty-LDSR)                        | This is a custom node that lets you take advantage of Latent Diffusion Super Resolution (LDSR) models inside ComfyUI.                                                         |          |         |
| [ComfyUI-IC-Light](https://github.com/kijai/ComfyUI-IC-Light)                | ComfyUI native implementation of IC-Light.                                                                    | [IC-Light](https://github.com/lllyasviel/IC-Light)     |  |
| [ComfyUI-InstanceDiffusion](https://github.com/logtd/ComfyUI-InstanceDiffusion)                | Instance-level Control for Image Generation.                                                                    | [InstanceDiffusion](https://github.com/frank-xwang/InstanceDiffusion)     |[arXiv](https://arxiv.org/abs/2402.03290)  |
| [ComfyUI InstantID](https://github.com/ZHO-ZHO-ZHO/ComfyUI-InstantID)                          | Zero-shot Identity-Preserving Generation in Seconds.                                                                    | [InstantID](https://github.com/InstantID/InstantID)               |[arXiv](https://arxiv.org/abs/2401.07519)  |
| [ComfyUI IPAdapter plus](https://github.com/cubiq/ComfyUI_IPAdapter_plus)                      | The IPAdapter are very powerful models for image-to-image conditioning.                                                 | [IP-Adapter](https://github.com/tencent-ailab/IP-Adapter/)        |[arXiv](https://arxiv.org/abs/2308.06721)  |
| [ComfyUI-layerdiffuse](https://github.com/huchenlei/ComfyUI-layerdiffuse)                      | Transparent Image Layer Diffusion using Latent Transparency.                                                            | [LayerDiffuse](https://github.com/layerdiffusion/LayerDiffuse)    |         |
| [ComfyUI-Marigold](https://github.com/kijai/ComfyUI-Marigold)                                  | Marigold depth estimation in ComfyUI.                                                                                   | [Marigold](https://github.com/prs-eth/Marigold)                   |[arXiv](https://arxiv.org/abs/2312.02145)  |
| [ComfyUI-MimicBrush](https://github.com/AIFSH/ComfyUI-MimicBrush)                              | Zero-shot Image Editing with Reference Imitation.                                                                       | [MimicBrush](https://github.com/ali-vilab/MimicBrush)             |[arXiv](https://arxiv.org/abs/2406.07547)  |
| [ComfyUI_omost](https://github.com/huchenlei/ComfyUI_omost)                        | Omost is a project to convert LLM's coding capability to image generation (or more accurately, image composing) capability.                                               | [Omost](https://github.com/lllyasviel/Omost)           |   |
| [ComfyUI OOTDiffusion](https://github.com/AuroBit/ComfyUI-OOTDiffusion)                        | Outfitting Fusion based Latent Diffusion for Controllable Virtual Try-on.                                               | [OOTDiffusion](https://github.com/levihsu/OOTDiffusion)           |[arXiv](https://arxiv.org/abs/2403.01779)  |
| [ComfyUI PhotoMaker Plus](https://github.com/shiimizu/ComfyUI-PhotoMaker-Plus)                 | Customizing Realistic Human Photos via Stacked ID Embedding.                                                            | [PhotoMaker](https://github.com/TencentARC/PhotoMaker)            |[arXiv](https://arxiv.org/abs/2312.04461)  |
| [ComfyUI Segment Anything](https://github.com/storyicon/comfyui_segment_anything)              | Based on GroundingDino and SAM, use semantic strings to segment any element in an image.                                | [Segment Anything Model (SAM)](https://github.com/facebookresearch/segment-anything)         |[arXiv](https://arxiv.org/abs/2304.02643)  |
| [ComfyUI StableZero123](https://github.com/deroberon/StableZero123-comfyui)                    | A Single Image to Consistent Multi-view Diffusion Base Model.                                                           | [Zero123++](https://github.com/SUDO-AI-3D/zero123plus)            |[arXiv](https://arxiv.org/abs/2310.15110)  |
| [ComfyUI_UltimateSDUpscale](https://github.com/ssitu/ComfyUI_UltimateSDUpscale)                | ComfyUI nodes for the Ultimate Stable Diffusion Upscale script by Coyote-A.                                             | [Ultimate SD Upscale](https://github.com/Coyote-A/ultimate-upscale-for-automatic1111)            |         |
| [PuLID ComfyUI](https://github.com/cubiq/PuLID_ComfyUI)                                        | Pure and Lightning ID Customization via Contrastive Alignment.                                                          | [PuLID](https://github.com/ToTheBeginning/PuLID)                  |[arXiv](https://arxiv.org/abs/2404.16022)  |

<p style="text-align: right;"><a href="#table-of-contents">^ Back to Contents ^</a></p>


### <span id="mesh">Mesh</span>

| ComfyUI                                                                                      | Description                                                                                                                                                                                    |   Source   |   Paper   |
| :------------------------------------------------------------------------------------------ | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :-----------: | :-------: |
| [ComfyUI InstantMesh](https://github.com/jtydhr88/ComfyUI-InstantMesh)                         | Efficient 3D Mesh Generation from a Single Image with Sparse-view Large Reconstruction Models.                      | [InstantMesh](https://github.com/TencentARC/InstantMesh)          |[arXiv](https://arxiv.org/abs/2404.07191)  |

<p style="text-align: right;"><a href="#table-of-contents">^ Back to Contents ^</a></p>


### <span id="texture">Texture</span>

| ComfyUI                                                                                      | Description                                                                                                                                                                                    |   Source   |   Paper   |
| :------------------------------------------------------------------------------------------ | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :-----------: | :-------: |
| [Comfy Textures](https://github.com/AlexanderDzhoganov/ComfyTextures)                          | Unreal Engine ⚔️ ComfyUI - Automatic texturing using generative diffusion models.                                                                                                          |          |          |

<p style="text-align: right;"><a href="#table-of-contents">^ Back to Contents ^</a></p>


### <span id="model">3D Model</span>

| ComfyUI                                                                                      | Description                                                                                                                                                                                    |   Source   |   Paper   |
| :------------------------------------------------------------------------------------------ | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :-----------: | :-------: |
| [ComfyUI-Flowty-TripoSR](https://github.com/flowtyone/ComfyUI-Flowty-TripoSR)                  | TripoSR custom node for comfyui.                                                                                        | [TripoSR](https://github.com/VAST-AI-Research/TripoSR)            |[arXiv](https://arxiv.org/abs/2403.02151)  |
| [ComfyUI-Tripo](https://github.com/VAST-AI-Research/ComfyUI-Tripo)                             | This extension integrates Tripo into ComfyUI, allowing users to generate 3D models from text prompts or images directly within the ComfyUI interface.        | [TripoSR](https://github.com/VAST-AI-Research/TripoSR)            |[arXiv](https://arxiv.org/abs/2403.02151)  |


<p style="text-align: right;"><a href="#table-of-contents">^ Back to Contents ^</a></p>


### <span id="animation">Animation</span>

| ComfyUI                                                                                      | Description                                                                                                                                                                                    |   Source   |   Paper   |
| :------------------------------------------------------------------------------------------ | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :-----------: | :-------: |
| [ComfyUI-ADMotionDirector](https://github.com/kijai/ComfyUI-ADMotionDirector)                  | ComfyUI nodes for training AnimateDiff motion loras.                                                                    | [AnimateDiff MotionDirector](https://github.com/ExponentialML/AnimateDiff-MotionDirector)              |          |
| [ComfyUI-AnimateDiff-Evolved](https://github.com/Kosinkadink/ComfyUI-AnimateDiff-Evolved)      | Animate Your Personalized Text-to-Image Diffusion Models without Specific Tuning.                                       | [AnimateDiff](https://github.com/guoyww/AnimateDiff)              |[arXiv](https://arxiv.org/abs/2307.04725)  |
| [ComfyUI-AnimateDiff-Evolved](https://github.com/Kosinkadink/ComfyUI-AnimateDiff-Evolved)      | AnimateDiff-Lightning is a lightning-fast text-to-video generation model.                                               | [AnimateDiff-Lightning](https://huggingface.co/ByteDance/AnimateDiff-Lightning)              |[arXiv](https://arxiv.org/abs/2403.12706)  |
| [Comfyui-AnimateLCM](https://github.com/dezi-ai/ComfyUI-AnimateLCM)                            | Accelerating the Animation of Personalized Diffusion Models and Adapters with Decoupled Consistency Learning.         | [AnimateLCM](https://github.com/G-U-N/AnimateLCM)                 |[arXiv](https://arxiv.org/abs/2402.00769)  |
| [ComfyUI-DynamiCrafter](https://github.com/chaojie/ComfyUI-DynamiCrafter)                      |  Animating Open-domain Images with Video Diffusion Priors.                                                              | [DynamiCrafter](https://github.com/Doubiiu/DynamiCrafter)         |[arXiv](https://arxiv.org/abs/2310.12190)  |
| [ComfyUI-MagicAnimate](https://github.com/thecooltechguy/ComfyUI-MagicAnimate)                 | Easily use Magic Animate within ComfyUI!                                                                                                                                         |          |          |
| [ComfyUI-ToonCrafter](https://github.com/AIGODLIKE/ComfyUI-ToonCrafter)                        |  Generative Cartoon Interpolation.                                                                                      | [ToonCrafter](https://github.com/ToonCrafter/ToonCrafter)         |          |

<p style="text-align: right;"><a href="#table-of-contents">^ Back to Contents ^</a></p>


### <span id="video">Video</span>

| ComfyUI                                                                                      | Description                                                                                                                                                                                    |   Source   |   Paper   |
| :------------------------------------------------------------------------------------------ | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :-----------: | :-------: |
| [ComfyUI-DragNUWA](https://github.com/chaojie/ComfyUI-DragNUWA)                                | DragNUWA enables users to manipulate backgrounds or objects within images directly, and the model seamlessly translates these actions into camera movements or object motions, generating the corresponding video.  | [DragNUWA](https://github.com/ProjectNUWA/DragNUWA)   |      |
| [ComfyUI-SVD](https://github.com/kijai/ComfyUI-SVD)                                            | Experimental use of stable-video-diffusion in ComfyUI.                                                                                                                           |          |         |
| [ComfyUI-VideoHelperSuite](https://github.com/Kosinkadink/ComfyUI-VideoHelperSuite)            | Nodes related to video workflows.                                                                                                                                                |          |         |

<p style="text-align: right;"><a href="#table-of-contents">^ Back to Contents ^</a></p>


### <span id="avatar">Avatar</span>

| ComfyUI                                                                                      | Description                                                                                                                                                                                    |   Source   |   Paper   |
| :------------------------------------------------------------------------------------------ | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :-----------: | :-------: |
| [avatar-graph-comfyui](https://github.com/avatechai/avatar-graph-comfyui)                      | A custom nodes module for creating real-time interactive avatars powered by blender bpy mesh api + Avatech Shape Flow runtime.                                                |          |         |
| [ComfyUI-AniPortrait](https://github.com/chaojie/ComfyUI-AniPortrait)                          | Audio-Driven Synthesis of Photorealistic Portrait Animations.                                                               | [AniPortrait](https://github.com/Zejun-Yang/AniPortrait)      |[arXiv](https://arxiv.org/abs/2403.17694)  |
| [ComfyUI-IP_LAP](https://github.com/AIFSH/ComfyUI-IP_LAP)                                      | The comfyui custom node of IP_LAP to make audio driven videos!                                                              | [IP_LAP](https://github.com/Weizhi-Zhong/IP_LAP)              |[arXiv](https://arxiv.org/abs/2305.08293)  |
| [Comfyui-MusePose](https://github.com/TMElyralab/Comfyui-MusePose)                             |  MusePose: a Pose-Driven Image-to-Video Framework for Virtual Human Generation.                                             | [MusePose](https://github.com/TMElyralab/MusePose)            |          |
| [ComfyUI-MuseTalk](https://github.com/chaojie/ComfyUI-MuseTalk)                                | Real-Time High Quality Lip Synchorization with Latent Space Inpainting!                                                     | [MuseTalk](https://github.com/TMElyralab/MuseTalk)            |         |
| [ComfyUI-MuseV](https://github.com/chaojie/ComfyUI-MuseV)                                      | Infinite-length and High Fidelity Virtual Human Video Generation with Visual Conditioned Parallel Denoising!               | [MuseV](https://github.com/TMElyralab/MuseV)                  |         |
| [ComfyUI-V-Express](https://github.com/tiankuan93/ComfyUI-V-Express)                         | Conditional Dropout for Progressive Training of Portrait Video Generation.             | [V-Express](https://github.com/tencent-ailab/V-Express)              |[arXiv](https://arxiv.org/abs/2406.02511)  |
| [ComfyUI_wav2lip](https://github.com/ShmuelRonen/ComfyUI_wav2lip)                              | A custom node for ComfyUI that allows you to perform lip-syncing on videos using the Wav2Lip model. It takes an input video and an audio file and generates a lip-synced output video.             | [Wav2Lip](https://github.com/Rudrabha/Wav2Lip)              |[arXiv](https://arxiv.org/abs/2008.10010)  |

<p style="text-align: right;"><a href="#table-of-contents">^ Back to Contents ^</a></p>


### <span id="audio">Audio</span>

| ComfyUI                                                                                      | Description                                                                                                                                                                                    |   Source   |   Paper   |
| :------------------------------------------------------------------------------------------ | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :-----------: | :-------: |
| [ComfyUI-AudioScheduler](https://github.com/a1lazydog/ComfyUI-AudioScheduler)                  | AudioScheduler project contains a collection of audio processing nodes.                                                                                                          |          |          |
| [ComfyUI-ChatTTS](https://github.com/AIFSH/ComfyUI-ChatTTS)                                    | ChatTTS is a generative speech model for daily dialogue.                                                                | [ChatTTS](https://github.com/2noise/ChatTTS)              |          |
| [ComfyUI-GPT_SoVITS](https://github.com/AIFSH/ComfyUI-GPT_SoVITS)                              | A Powerful Few-shot Voice Conversion and Text-to-Speech WebUI.                                                          | [GPT-SoVITS](https://github.com/RVC-Boss/GPT-SoVITS)              |          |
| [ComfyUI_ParlerTTS](https://github.com/smthemex/ComfyUI_ParlerTTS)                              | Parler-TTS is a lightweight text-to-speech (TTS) model that can generate high-quality, natural sounding speech in the style of a given speaker (gender, pitch, speaking style, etc).    | [Parler-TTS](https://github.com/huggingface/parler-tts)             |          |
| [ComfyUI-StableAudioSampler](https://github.com/lks-ai/ComfyUI-StableAudioSampler)              | The New Stable Diffusion Audio Sampler 1.0 In a ComfyUI Node. Make some beats!                                               |         |          |
| [ComfyUI-UVR5](https://github.com/AIFSH/ComfyUI-UVR5)                                          | The comfyui custom node for UVR5 to separate vocals and background music.                                               | [UVR5](https://github.com/Anjok07/ultimatevocalremovergui)        |          |

<p style="text-align: right;"><a href="#table-of-contents">^ Back to Contents ^</a></p>

 
### <span id="music">Music</span>

| ComfyUI                                                                                      | Description                                                                                                                                                                                    |   Source   |   Paper   |
| :------------------------------------------------------------------------------------------ | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :-----------: | :-------: |
| [ComfyUI-SunoAI](https://github.com/GentlemanHu/ComfyUI-SunoAI)                                 | ComfyUI Node wrapper of SunoAI API.                                                                                                                                             |          |          |

<p style="text-align: right;"><a href="#table-of-contents">^ Back to Contents ^</a></p>


### <span id="workflow">ComfyUI Workflow</span>

| ComfyUI                                                                                      | Description                                                                                                                                                                                    |   Source   |   Paper   |
| :------------------------------------------------------------------------------------------ | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :-----------: | :-------: |

<p style="text-align: right;"><a href="#table-of-contents">^ Back to Contents ^</a></p>


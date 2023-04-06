# Awesome-Foundation-Models
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A foundation model is a large-scale pretrained model (e.g., BERT, DALL-E, GPT-3) that can be adapted to a wide range of downstream applications. This term was [first popularized](https://crfm.stanford.edu) by the Stanford Institute for Human-Centered Artificial Intelligence. This repository maintains a curated list of foundation models for vision and language tasks. Research papers without code are not included.


## Papers

### Survey

* [2023.03] [A Comprehensive Survey on Pretrained Foundation Models: A History from BERT to ChatGPT](https://arxiv.org/pdf/2302.09419.pdf)
* [2022.07] [On the Opportunities and Risks of Foundation Models](https://arxiv.org/pdf/2108.07258.pdf) (This survey first popularizes the concept of foundation model; from Standford)

### 2023

* [Segment Anything](https://github.com/facebookresearch/segment-anything) (the first foundation model for image segmentation; from Meta)
* [Toward Building General Foundation Models for Language, Vision, and Vision-Language Understanding Tasks](https://arxiv.org/pdf/2301.05065.pdf) (from ByteDance)
* [EVA-CLIP: Improved Training Techniques for CLIP at Scale](https://arxiv.org/pdf/2303.15389.pdf) (from BAAI and HUST)
* [EVA-02: A Visual Representation for Neon Genesis](https://arxiv.org/pdf/2303.11331.pdf) (from BAAI and HUST)
* [EVA-01: Exploring the Limits of Masked Visual Representation Learning at Scale](https://arxiv.org/pdf/2211.07636.pdf) (CVPR, from BAAI and HUST)
* [LLaMA: Open and Efficient Foundation Language Models](https://arxiv.org/pdf/2302.13971v1.pdf) (A collection of foundation language models ranging from 7B to 65B parameters; from Meta)
* [The effectiveness of MAE pre-pretraining for billion-scale pretraining](https://arxiv.org/pdf/2303.13496.pdf) (from Meta)
* [BloombergGPT: A Large Language Model for Finance](https://arxiv.org/pdf/2303.17564.pdf) (50 billion parameters; from Bloomberg)
* [BLOOM: A 176B-Parameter Open-Access Multilingual Language Model](https://arxiv.org/pdf/2211.05100v3.pdf) (this work was coordinated by BigScience whose goal is to democratize LLMs.)
* [FLIP: Scaling Language-Image Pre-training via Masking](https://arxiv.org/abs/2212.00794) (from Meta)
* [BLIP-2: Bootstrapping Language-Image Pre-training with Frozen Image Encoders and Large Language Models](https://arxiv.org/pdf/2301.12597.pdf) (from Saleforce Research)
* [GPT-4 Technical Report](https://arxiv.org/pdf/2303.08774.pdf) (from OpenAI)
* [Visual ChatGPT: Talking, Drawing and Editing with Visual Foundation Models](https://arxiv.org/pdf/2303.04671.pdf) (from Microsoft Research Asia)
* [UNINEXT: Universal Instance Perception as Object Discovery and Retrieval](https://arxiv.org/pdf/2303.06674.pdf) (a unified model for 10 instance perception tasks; CVPR, from ByteDance)
* [InternVideo: General Video Foundation Models via Generative and Discriminative Learning](https://arxiv.org/pdf/2212.03191.pdf) (from Shanghai AI Lab)
* [InternImage: Exploring Large-Scale Vision Foundation Models with Deformable Convolutions](https://arxiv.org/pdf/2211.05778.pdf) (CVPR, from Shanghai AI Lab)
* [BridgeTower: Building Bridges Between Encoders in Vision-Language Representation Learning](https://arxiv.org/pdf/2206.08657.pdf) (from Harbin Institute of Technology and Microsoft Research Asia)

### 2022
<!-- * [Unified Vision and Language Prompt Learning](https://arxiv.org/pdf/2210.07225.pdf) (No code yet; from Nanyang Technological University and Apple) -->
* [BEVT: BERT Pretraining of Video Transformers](https://arxiv.org/pdf/2112.01529.pdf) (CVPR, from Shanghai Key Lab of Intelligent Information Processing)
* [Foundation Transformers](https://arxiv.org/pdf/2210.06423.pdf) (from Microsoft)
* [A Generalist Agent](https://openreview.net/pdf?id=1ikK0kHjvj) (known as Gato, a multi-modal, multi-task, multi-embodiment generalist agent; from DeepMind)
* [FIBER: Coarse-to-Fine Vision-Language Pre-training with Fusion in the Backbone](https://arxiv.org/pdf/2206.07643.pdf) (from Microsoft, UCLA, and New York University)
* [Flamingo: a Visual Language Model for Few-Shot Learning](https://arxiv.org/pdf/2204.14198.pdf) (from DeepMind)
* [Point-E: A System for Generating 3D Point Clouds from Complex Prompts](https://arxiv.org/pdf/2212.08751.pdf) (efficient 3D object generation using a text-to-image diffusion model; from OpenAI)
* [Image Segmentation Using Text and Image Prompts](https://arxiv.org/pdf/2112.10003.pdf) (CVPR, from University of Göttingen)
* [Unifying Flow, Stereo and Depth Estimation](https://arxiv.org/pdf/2211.05783.pdf) (A unified model for three motion and 3D perception tasks; from ETH Zurich)
* [PaLI: A Jointly-Scaled Multilingual Language-Image Model](https://arxiv.org/pdf/2209.06794.pdf) (from Google)
* [SLIP: Self-supervision meets Language-Image Pre-training](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136860514.pdf) (ECCV, from UC Berkeley and Meta)
* [GLIP: Grounded Language-Image Pre-training](https://openaccess.thecvf.com/content/CVPR2022/papers/Li_Grounded_Language-Image_Pre-Training_CVPR_2022_paper.pdf) (CVPR, from UCLA and Microsoft)
* [BLIP: Bootstrapping Language-Image Pre-training for Unified Vision-Language Understanding and Generation](https://proceedings.mlr.press/v162/li22n/li22n.pdf) (from Salesforce Research)
* [NUWA-Infinity: Autoregressive over Autoregressive Generation for Infinite Visual Synthesis](https://arxiv.org/pdf/2207.09814.pdf) (from Microsoft)
* [PaLM: Scaling Language Modeling with Pathways](https://arxiv.org/pdf/2204.02311.pdf) (from Google)
* [CoCa: Contrastive Captioners are Image-Text Foundation Models](https://arxiv.org/abs/2205.01917) (from Google)
* [Parti: Scaling Autoregressive Models for Content-Rich Text-to-Image Generation](https://openreview.net/pdf?id=AFDcYJKhND) (from Google)
* [Imagen: Photorealistic Text-to-Image Diffusion Models with Deep Language Understanding](https://proceedings.neurips.cc/paper_files/paper/2022/file/ec795aeadae0b7d230fa35cbaf04c041-Paper-Conference.pdf) (from Google)
* [Stable Diffusion: High-Resolution Image Synthesis with Latent Diffusion Models](https://openaccess.thecvf.com/content/CVPR2022/papers/Rombach_High-Resolution_Image_Synthesis_With_Latent_Diffusion_Models_CVPR_2022_paper.pdf) (CVPR, from Stability and Runway)
* [Beyond the Imitation Game: Quantifying and extrapolating the capabilities of language models](https://arxiv.org/pdf/2206.04615.pdf) (BIG-Bench: a 204-task extremely difficult and diverse benchmark for LLMs, 444 authors from 132 institutions)
* [CRIS: CLIP-Driven Referring Image Segmentation](https://arxiv.org/pdf/2111.15174.pdf) (from University of Sydney and OPPO)
* [Masked Autoencoders As Spatiotemporal Learners](https://arxiv.org/pdf/2205.09113.pdf) (extension of MAE to videos; NeurIPS, from Meta)
* [Masked Autoencoders Are Scalable Vision Learners](https://openaccess.thecvf.com/content/CVPR2022/papers/He_Masked_Autoencoders_Are_Scalable_Vision_Learners_CVPR_2022_paper.pdf) (known as MAE; CVPR, from FAIR)
* [InstructGPT: Training language models to follow instructions with human feedback](https://arxiv.org/pdf/2203.02155.pdf) (trained with humans in the loop; from OpenAI)
* [DALL-E2: Hierarchical Text-Conditional Image Generation with CLIP Latents](https://cdn.openai.com/papers/dall-e-2.pdf) (from OpenAI)
* [Robust and Efficient Medical Imaging with Self-Supervision](https://arxiv.org/pdf/2205.09723.pdf) (from Google, Georgia Tech, and Northwestern University)
* [Video Swin Transformer](https://openaccess.thecvf.com/content/CVPR2022/papers/Liu_Video_Swin_Transformer_CVPR_2022_paper.pdf) (CVPR, from Microsoft Research Asia)
* [FLAVA: A Foundational Language And Vision Alignment Model](https://openaccess.thecvf.com/content/CVPR2022/papers/Singh_FLAVA_A_Foundational_Language_and_Vision_Alignment_Model_CVPR_2022_paper.pdf) (CVPR, from Facebook AI Research)
* [Towards artificial general intelligence via a multimodal foundation model](https://www.nature.com/articles/s41467-022-30761-2) (Nature Communication, from Renmin University of China)
* [FILIP: Fine-Grained Interactive Language-Image Pre-Training](https://openreview.net/pdf?id=cpDhcsEDC2) (ICLR, from Huawei and HKUST)
* [SimVLM: Simple Visual Language Model Pretraining with Weak Supervision](https://openreview.net/forum?id=GUrhfTuf_3) (ICLR, from CMU and Google)
* [GLIDE: Towards Photorealistic Image Generation and Editing with Text-Guided Diffusion Models](https://arxiv.org/pdf/2112.10741.pdf) (from OpenAI)

### 2021

* [Unifying Vision-and-Language Tasks via Text Generation](http://proceedings.mlr.press/v139/cho21a/cho21a.pdf) (from UNC-Chapel Hill)
* [ALIGN: Scaling Up Visual and Vision-Language Representation Learning With Noisy Text Supervision](http://proceedings.mlr.press/v139/jia21b/jia21b.pdf) (PMLR, from Google)
* [UniT: Multimodal Multitask Learning with a Unified Transformer](https://openaccess.thecvf.com/content/ICCV2021/papers/Hu_UniT_Multimodal_Multitask_Learning_With_a_Unified_Transformer_ICCV_2021_paper.pdf) (ICCV, from FAIR)
* [WenLan: Bridging Vision and Language by Large-Scale Multi-Modal Pre-Training](https://arxiv.org/pdf/2103.06561.pdf) (This paper presents the first large-scale Chinese multimodal pre-training model called BriVL; from Renmin University of China)
* [Codex: Evaluating Large Language Models Trained on Code](https://arxiv.org/pdf/2107.03374.pdf) (a GPT language model finetuned on public code from GitHub, from OpenAI and Anthropic AI)
* [Florence: A New Foundation Model for Computer Vision](https://arxiv.org/pdf/2111.11432.pdf) (from Microsoft)
* [DALL-E: Zero-Shot Text-to-Image Generation](https://arxiv.org/pdf/2102.12092.pdf) (from OpenAI)
* [CLIP: Learning Transferable Visual Models From Natural Language Supervision](https://arxiv.org/pdf/2103.00020.pdf) (from OpenAI)
* [Multimodal Few-Shot Learning with Frozen Language Models](https://proceedings.neurips.cc/paper/2021/file/01b7575c38dac42f3cfb7d500438b875-Paper.pdf) (NeurIPS, from DeepMind)
* [Swin Transformer: Hierarchical Vision Transformer using Shifted Windows](https://openaccess.thecvf.com/content/ICCV2021/papers/Liu_Swin_Transformer_Hierarchical_Vision_Transformer_Using_Shifted_Windows_ICCV_2021_paper.pdf) (ICCV, from Microsoft Research Asia)
* [An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale](https://arxiv.org/pdf/2010.11929.pdf) (The first Vision Transfomer with pure self-attention blocks; ICLR, from Google)

### 2020

* [GPT-3: Language Models are Few-Shot Learners](https://arxiv.org/pdf/2005.14165.pdf) (175B parameters; permits in-context learning compared with GPT-2; from OpenAI)
* [UNITER: UNiversal Image-TExt Representation Learning](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123750103.pdf) (from Microsoft)
* [T5: Exploring the Limits of Transfer Learning with a Unified Text-to-Text Transformer](https://dl.acm.org/doi/pdf/10.5555/3455716.3455856) (from Google)

### 2019

* [GPT-2: Language Models are Unsupervised Multitask Learners](https://d4mucfpksywv.cloudfront.net/better-language-models/language-models.pdf) (1.5B parameters; from OpenAI)
* [LXMERT: Learning Cross-Modality Encoder Representations from Transformers](https://arxiv.org/pdf/1908.07490.pdf) (EMNLP, from UNC-Chapel Hill)
* [BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://arxiv.org/pdf/1810.04805.pdf) (from Google AI Language)

### 2018

* [GPT: Improving Language Understanding by Generative Pre-Training](https://www.cs.ubc.ca/~amuham01/LING530/papers/radford2018improving.pdf) (from OpenAI)


### 2017

* [Attention Is All You Need](https://proceedings.neurips.cc/paper_files/paper/2017/file/3f5ee243547dee91fbd053c1c4a845aa-Paper.pdf) (NeurIPS, from Google and UoT)


## Related Topics

### Training Efficiency

* [Green AI](https://dl.acm.org/doi/pdf/10.1145/3381831) (introduces the concept of Red AI vs Green AI)
* [The Lottery Ticket Hypothesis: Finding Sparse, Trainable Neural Networks](https://arxiv.org/pdf/1803.03635.pdf) (the lottery ticket hypothesis, from MIT)

* Other Challenges and Opportunities: Trust, reliability, safe use, interpretability, self-improvement, adaptation, augmentation, specilization, understanding/predicting capability.

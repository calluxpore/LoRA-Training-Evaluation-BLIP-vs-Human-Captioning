# LoRA-Training-Evaluation-BLIP-vs-Human-Captioning

## Overview
"LoRA Training Evaluation: BLIP vs Human Captioning" is a research project by Sam, a graduate student of Digital Futures at OCAD University, CA. This project explores training Lora models within the stable diffusion framework to generate images from text descriptions. The focus is on understanding how the captions used before training impact the model's performance and ability to accurately reproduce results.

## Objectives
- Investigate the impact of captioning methods (BLIP vs human) on LoRA training for Stable Diffusion models
- Evaluate trained models' performance through systematic testing with various prompts and captions
- Document the entire process comprehensively to ensure reproducibility of results

## Research Approach
The project follows a comparative approach, training two LoRA models using different captioning methods:
- BLIP (Bootstrapping Language-Image Pre-training) captioning
- Human captioning

The models are trained on a focused dataset of 11 images and evaluated based on several parameters, including caption tokens, training duration, prompt tokens, performance speed, and reproducibility.

## Key Findings
- BLIP captioning provides an advantage over human captioning in terms of the effort-to-impact ratio
- The BLIP captioned model achieved high reproducibility and required less effort in dataset preparation and training
- Human captioning required significantly more effort in writing captions and longer training time, with medium to low overall impact

## Recommendations for Future Work
- Explore methods to mitigate potential biases in human-written captions
- Conduct experiments with larger datasets to assess scalability and robustness of findings
- Develop and adhere to structured protocols to enhance efficiency and reproducibility of the training process
- Engage participants with diverse backgrounds and experience levels in AI prompting for more holistic evaluation

## Tools and Technologies
- RunPod Secure Server with 1 RTX 3090 (24 GB VRAM) and 300 GB Pod Volume for training
- RunPod Secure Server with 1 RTX 4090 (62GB VRAM) and 500 GB Pod Volume for evaluation
- Kohya SS implementation of LoRA for model training

## Links
- [Github Repository](https://github.com/calluxpore/LoRA-Training-Evaluation-BLIP-vs-Human-Captioning)
- [BLIP Captions](https://github.com/calluxpore/LoRA-Training-Evaluation-BLIP-vs-Human-Captioning/tree/main/Blip%20Captions)
- [Human Captions](https://github.com/calluxpore/LoRA-Training-Evaluation-BLIP-vs-Human-Captioning/tree/main/Human%20Captions)
- [BLIP Captioned LoRA Models]()
- [Human Captioned LoRA Models]()
- [Workflow Video - BLIP Captions](https://vimeo.com/929730071)
- [Workflow Video - Human Captions](https://vimeo.com/929730440)

## Acknowledgements
Special thanks to Professor Alexis Morris and Professor Fidelia Lam of the Faculty of Arts & Science at OCAD University for their guidance and support throughout the exploration and development of this project.

## References
Hu, Edward J., Yelong Shen, Phillip Wallis, Zeyuan Allen-Zhu, Yuanzhi Li, Shean Wang, Lu Wang, and Weizhu Chen. 2021. “LoRA: Low-Rank Adaptation of Large Language Models.” arXiv. https://doi.org/10.48550/arXiv.2106.09685.

Invoke, dir. 2024. Creating Embeddings and Concept Models with Invoke Training - Textual Inversion & LoRAs. https://www.youtube.com/watch?v=OZIz2vvtlM4.

Li, Junnan, Dongxu Li, Caiming Xiong, and Steven Hoi. 2022. “BLIP: Bootstrapping Language-Image Pre-Training for Unified Vision-Language Understanding and Generation.” arXiv. https://doi.org/10.48550/arXiv.2201.12086.


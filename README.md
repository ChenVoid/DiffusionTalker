# DiffusionTalker: Personalization and Acceleration for Speech-Driven 3D Face Diffuser

Official code release for  [DiffusionTalker: Personalization and Acceleration for Speech-Driven 3D Face Diffuser](https://arxiv.org/abs/2311.16565)

<p align='center'>
  <b>
    <a href="https://arxiv.org/abs/2311.16565">Paper</a>
    | 
    <a href="https://chenvoid.github.io/DiffusionTalker/">Project Page</a>
    |
    <a href="https://github.com/ChenVoid/DiffusionTalker">Code</a> 
  </b>
</p> 
  <p align='center'>  
    <img src='image/pipeline.png' width='1000'/>
  </p>


**Abstract**: Speech-driven 3D facial animation has been an attractive task in both academia and industry. Traditional methods mostly focus on learning a deterministic mapping from speech to animation. Recent approaches start to consider the non-deterministic fact of speech-driven 3D face animation and employ the diffusion model for the task. However, personalizing facial animation and accelerating animation generation are still two major limitations of existing diffusion-based methods. To address the above limitations, we propose DiffusionTalker, a diffusion-based method that utilizes contrastive learning to personalize 3D facial animation and knowledge distillation to accelerate 3D animation generation. Specifically, to enable personalization, we introduce a learnable talking identity to aggregate knowledge in audio sequences. The proposed identity embeddings extract customized facial cues across different people in a contrastive learning manner. During inference, users can obtain personalized facial animation based on input audio, reflecting a specific talking style. With a trained diffusion model with hundreds of steps, we distill it into a lightweight model with 8 steps for acceleration. Extensive experiments are conducted to demonstrate that our method outperforms state-of-the-art methods. The code will be released.


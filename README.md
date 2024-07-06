## Generative AI Animation Project
# Overview
This project aims to create short animated videos from textual prompts using generative AI techniques. The system generates an initial image based on the prompt, and then passes it to a Stable Video Diffusion model to create a small animated video. Background music is also generated using MusicGen based on the same prompt and combined with the animation to produce the final output.
# Features
1. Prompt-based Image Generation: Generates an initial image from a given prompt.
2. Stable Video Diffusion: Converts the initial image into an animated video.
3. Background Music Generation: Creates background music using MusicGen based on the prompt.
4. Parameter Tuning: Supports various tuning parameters to customize the animation:
   - Frame rates
   - Rotation
   - Zoom
   - Translation
   - 2D or 3D mode
   - Noise sampler
   - Steps
   - Scale
   - Batch size
# Evaluation
1. User Reviews: Gather feedback from users to assess the quality and appeal of the animations. User reviews provide valuable insights into the effectiveness of the generated content.
2. CLIP Score: Use the CLIP (Contrastive Language-Image Pre-Training) model to evaluate the alignment between the generated animation and the input prompt. A CLIP score above 35 is considered indicative of high-quality content. Our model has achieved a CLIP score of 36.9583, demonstrating its effectiveness.
# Model Used 
- Text to Image Model - Anime-mix
- Text to Video - Stable Video Diffusion Model
- Text to Music - MusicGen
# Contribution
1. Akshit Singhal
2. Raghav Mangla
3. Aditya Kumar

# Big Models, Small Tweaks: Exploring the LoRA Way of Fine-Tuning
## Exploring-LoRA
The Idea Behind Parameter Efficient Fine-Tuning and Analyzing LoRA through its Implementation on an MLP

Research paper reference: <br>
**LoRA: Low-Rank Adaptation of Large Language Models** <br>
*Edward J. Hu\*, Yelong Shen\*, Phillip Wallis, Zeyuan Allen-Zhu, Yuanzhi Li, Shean Wang, Lu Wang, Weizhu Chen* <br>
Paper: https://arxiv.org/abs/2106.09685 <br>
Video explainer: https://www.youtube.com/watch?v=DhRoTONcyZE <br>

Blog reference:
1. **Exploring LoRA — Part 1: The Idea Behind Parameter Efficient Fine-Tuning and LoRA**: https://medium.com/inspiredbrilliance/exploring-lora-part-1-the-idea-behind-parameter-efficient-fine-tuning-and-lora-ec469d176c26 “The What and Why of Adapter based Parameter Efficient Fine Tuning: Understanding Its Purpose and Significance”
2. **Exploring LoRA - Part 2: Analyzing LoRA through its Implementation on an MLP**: https://medium.com/inspiredbrilliance/exploring-lora-part-2-analyzing-lora-through-its-implementation-on-an-mlp-fbc386036f6f “The How of Parameter-Efficient Fine-Tuning with LoRA: Exploring the Inner Workings”
3. **Intrinsic Dimension Part 1: How Learning in Large Models Is Driven by a Few Parameters and Its Impact on Fine-Tuning**: (https://medium.com/inspiredbrilliance/intrinsic-dimension-part-1-why-large-models-can-be-fine-tuned-with-fewer-parameters-d15702d2943e)
"Understanding the Intrinsic Dimension (ID) of a Model and Why Networks Stay so Large Despite a very Tiny ID."
4. **Intrinsic Dimension Part 2: Measuring the True Complexity of a Model via Random Subspace Training**:
https://medium.com/inspiredbrilliance/intrinsic-dimension-part-2-measuring-the-true-complexity-of-a-model-via-random-subspace-training-bdf4ef27430c
"Instead of tweaking all weights, we project into a compact subspace and optimize just a few directions that matter."

<div align="center">

# AnimationBench: Are Video Models Good at Character-Centric Animation?

**Leyi Wu\*, Pengjun Fang\*, Kai Sun\*, Yazhou Xing, Yinwei Wu, Songsong Wang, Ziqi Huang, Dan Zhou, Yingqing He, Ying-Cong Chen, Qifeng Chen**

**The Hong Kong University of Science and Technology, The Hong Kong University of Science and Technology (Guangzhou), Nanyang Technological University, New AI Labs, Pearl Studio**

<p>
  <a href="https://animationbench.github.io/"><strong>Project Page</strong></a> |
  <a href="https://arxiv.org/abs/2604.15299"><strong>Paper</strong></a>
</p>

</div>

AnimationBench is a benchmark for evaluating image-to-video models on character-centric animation. Unlike realism-oriented video benchmarks, AnimationBench focuses on what matters most in animation: stylized character appearance, expressive motion, animation principles, and long-range character consistency.

The benchmark organizes evaluation into three major pillars: **Disney's 12 Principles of Animation**, **IP / Character Preservation**, and **Broader Generative Video Quality**. It provides a more informative way to compare modern video generation models with respect to animation-specific behavior and is designed to better reflect human preferences in character-centric animation scenarios.

https://github.com/user-attachments/assets/ccc9a865-c9e6-4543-9842-bc3c24b2e07d

## Overview

- A dedicated benchmark for **character-centric animation** evaluation.
- Covers **19 evaluation dimensions** across animation principles, character preservation, and broader video quality.
- Includes a diverse benchmark suite with **customized prompts, curated character assets, and animation-style test cases**.
- Supports both **standardized evaluation** and **flexible diagnostic analysis**.
- Shows strong alignment with **human preference** while exposing quality gaps that realism-focused benchmarks often miss.
<img width="1346" height="745" alt="image" src="https://github.com/user-attachments/assets/0f0b144b-3406-4e40-86ad-3c438261a495" />

## What AnimationBench Evaluates

AnimationBench goes beyond generic video quality metrics and focuses on animation-specific properties that are central to character performance:

- **Animation Principles**: e.g., squash and stretch, anticipation, slow in and slow out, arcs, secondary action, appeal, exaggeration, and related motion cues.
- **IP / Character Preservation**: whether a generated character remains on-model in appearance, behavior, personality, and style.
- **Broader Quality Dimensions**: semantic consistency, motion rationality, camera motion consistency, and other general video quality factors.

## Evaluation Results
<img width="1344" height="518" alt="image" src="https://github.com/user-attachments/assets/8daf790d-213f-4fcd-ab9c-c230cbd92a5c" />

We report results following our top-down hierarchy: 
- **IP Preservation**
- **Animation Principles** 
- **Broader Quality Dimensions**.

**Abbrev.**: **Antic.** = Anticipation; **FTOA** = Follow Through and Overlapping Action; **SI/SO** = Slow In and Slow Out; **S&S** = Squash and Stretch; **DC** = Distinctive Content; **SD** = Solid Drawing; **DD** = Dynamic Degree; **SE** = Semantic Extension; **Sem.** = Semantic Consistency; **MR** = Motion Rationality; **CMC** = Camera Motion Consistency.

<img width="1344" alt="image" src="https://github.com/user-attachments/assets/a3dbc245-cbd2-46aa-a5c4-2a26cda3138c" />

## Human Alignment Results
<img width="2187" height="658" alt="combined_plot" src="https://github.com/user-attachments/assets/3543b137-1a26-4f0e-98e6-daeab18e49cb" />

## Main Findings

- AnimationBench reveals clear differences among modern video models on character-centric animation tasks.
- Current models are relatively strong on basic semantic alignment and camera motion consistency while fine-grained character behavior, expressive motion, and long-term IP preservation remain challenging.
- The benchmark provides a more discriminative view of animation quality than realism-oriented evaluation settings.


## Citation

If you find AnimationBench useful in your research, please consider citing:

```bibtex
@misc{wu2026animationbenchvideomodelsgood,
      title={AnimationBench: Are Video Models Good at Character-Centric Animation?}, 
      author={Leyi Wu and Pengjun Fang and Kai Sun and Yazhou Xing and Yinwei Wu and Songsong Wang and Ziqi Huang and Dan Zhou and Yingqing He and Ying-Cong Chen and Qifeng Chen},
      year={2026},
      eprint={2604.15299},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2604.15299}, 
}
```

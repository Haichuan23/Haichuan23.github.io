---
permalink: /
title: "Haichuan Wang"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


I am a third year PhD student at Harvard University, where I am fortunate to be advised by Professor Milind Tambe. My research lies at the intersection of strategic decision making and generative AI. Specifically, my interests are:

<div class="research-directions" style="margin: 1.25em 0;">
  <details style="border: 0; background: transparent; padding: 0.25em 0; margin-bottom: 0.85em;">
    <summary style="cursor: pointer; font-weight: 600;">When alignment is possible: Align strategic agents.</summary>
    <p style="margin: 0.85em 0 0;">How can we design incentives that align a strategic agent's behavior with our goals? I study how game theory can inform reward design and the alignment of generative AI systems.</p>
  </details>
  <details style="border: 0; background: transparent; padding: 0.25em 0; margin-bottom: 0.85em;">
    <summary style="cursor: pointer; font-weight: 600;">When alignment is uncertain: Detect and correct misalignment.</summary>
    <p style="margin: 0.85em 0 0;">How can we determine whether an agent's behavior is aligned with our goals? I am interested in auditing AI systems to identify misalignment and using those findings to guide corrective interventions.</p>
  </details>
  <details style="border: 0; background: transparent; padding: 0.25em 0; margin-bottom: 0.85em;">
    <summary style="cursor: pointer; font-family: 'Courier New', Courier, monospace; font-size: 0.95em; font-weight: 400; line-height: 1.5;">When alignment is infeasible: Learn to best respond.</summary>
    <p style="margin: 0.85em 0 0;">Responding effectively to other agents requires understanding their strategies, which can be complex, high-dimensional, and multimodal. I use diffusion and flow-based models to represent these strategies and support better decision making.</p>
    <details style="border: 0; background: transparent; padding: 0; margin: 1em 0 0 1.25em;">
      <summary style="cursor: pointer; font-size: 1em; font-weight: 600;">When other players’ behavior data are available: Learn their strategies and best respond.</summary>
      <p style="margin: 0.85em 0 0;">When data on other players’ behavior are available, we can learn their strategies directly using a machine learning model, reducing reliance on unrealistic behavioral assumptions. Prior approaches often lack uncertainty quantification or impose restrictive parametric assumptions. Diffusion and flow-based models offer a flexible alternative: they capture complex, high-dimensional distributions and adapt to new strategic settings through conditional modeling. In the ranger–poacher game, we use these models to predict where poachers are likely to go in a national park and help rangers design patrol routes. Our results demonstrate that generative models can serve as effective behavioral models and inform decision making for societal benefit.</p>
    </details>
  </details>
</div>

{% comment %}

1. Applying tools from **machine intelligence**—namely, probabilistic models—to understand human behavior.
2. Applying tools traditionally used to study **human intelligence**—namely, game theory—to understand machine behavior.

---
## (1) Modeling Human Behavior with Generative Models

Traditional game theory assumes that agents act rationally or follow bounded rationality models. However, such assumptions greatly simplify the high-dimensional and complex nature of human decision-making, leading to limited predictive power in practice. In many settings, human strategies are naturally represented as distributions. With the advent of modern probabilistic models such as **diffusion models**, we can instead learn fully data-driven representations of human behavior. A natural follow-up question is: **what can we build on top of this new paradigm of behavioral modeling?**

### Exemplary Projects

- **Learning human behavior under data scarcity and observational bias** *(IAAI 2025)*  
  *Generative AI Against Poaching: Latent Composite Flow Matching for Wildlife Conservation*

- **Playing against learned adversary strategies via robust optimization** *(UAI 2025)*  
  *Robust Optimization with Diffusion Models for Green Security*

- **Transferring strategic knowledge across similar players** *(NeurIPS 2025)*  
  *Composite Flow Matching for RL with Shifted-Dynamics Data*
  
---
## (2) Understanding AI Systems through Game Theory

Post-trained AI systems are goal-oriented, and in this sense can be understood as rational decision-makers. This perspective unlocks tools from **game theory** for understanding complex AI systems. For example, the reward model in alignment is essentially an incentive mechanism and one may ask what's the optimal such mechanism. I hope this perspective can offer new insights into questions that are central to the **design and alignment of next-generation AI systems**.

### Exemplary Project
- **Design better incentive mechanism for alignment** *(ICML 2026)*  
  *Reward Shaping for Inference-Time Alignment: A Stackelberg Game Perspective*
    
---

Previously, I graduated Summa Cum Laude from the University of Chicago, where I obtained a triple major in Computer Science (Honors), Economics (Honors), and Mathematics. During my undergraduate years, I was fortunate to work with Professor Haifeng Xu on game theory, and with Professor Anthony Zhang and Dr. Gordon Liao on Decentralized Finance.

Last updated: Jan 2026

CV
======

You can access my CV in the following link: [CV](https://www.dropbox.com/scl/fi/fjmtpxk3fxauk5xg9e9x4/Haichuan_CV_Sept2025.pdf?rlkey=bczxk277ycpx0ltgjdzbpvq1e&st=4q2c9rgk&dl=0)


{% endcomment %}

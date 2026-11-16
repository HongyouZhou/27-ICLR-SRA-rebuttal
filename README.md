# Supplementary material

Anonymous supplementary material for an ICLR 2027 submission.

## Figures

- `figures/human_study.png` (also as PDF): the four-question human study. Four participants each rated all 200 pairs, 40 per comparison. Each column is one comparison, each row one question, and each bar gives the case-weighted share of judgments preferring SRA (win 1, tie 0.5, loss 0), so 50 means no preference.
- `figures/kappa_tradeoff.png` (also as PDF): SRA and Euler-weighted ReFL on Z-Image-Turbo at five values of the reward strength κ each (Euler-weighted ReFL at 0.1, 0.2, 0.3, 0.45 and 0.6, SRA at 0.1, 0.2, 0.3, 0.4 and 0.6). Each row is one prompt-based metric (CLIP-S, PickScore, ImageReward), each column one reward-related metric (DINO-D, DINOv3, Quality-S), and the number beside each point is κ. Means over the twenty validation cases, one training run per configuration.
- `figures/kappa_tradeoff_klein.png` (also as PDF): the same figure on FLUX.2-klein-4B, with five values of κ for each method (Euler-weighted ReFL at 0.1, 0.2, 0.3, 0.45 and 0.6, SRA at 0.1, 0.2, 0.3, 0.4 and 0.6).

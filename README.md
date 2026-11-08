# Near-Zero Forgetting Is Not Enough: Out-of-Distribution Robustness in Continual Learning of Pretrained VLAs

> **Code and Paper Coming Soon**
>
> Thank you for visiting from CoRL 2026 *Learn@Deploy* workshop! The official paper and complete codebase will be uploaded here soon.

**Authors:** Adrià Ruiz, Bartłomiej Twardowski, Tinne Tuytelaars, Sergi Masip *(KU Leuven / Computer Vision Center, UAB)*

## Overview

Recent work shows pretrained Vision-Language-Action (VLA) models exhibit near-zero forgetting in continual learning with experience replay. However, we show that this robustness does not extend to out-of-distribution (OOD) data. 

Evaluating $\pi_0$ across the LIBERO and LIBERO-Plus benchmarks, we find:
* **Severe OOD Forgetting:** Despite in-domain stability, OOD performance on previous tasks quickly collapses.
* **Shared Bottleneck:** OOD degradation follows a shared representational pattern across different domain shifts.
* **Representational Drift:** Drift concentrates heavily in the multimodal and action-expert layers. OOD features retain task-relevant information but become misaligned with the in-domain readout.

## Citation

If you found our poster or upcoming paper useful, please consider citing it:

```bibtex
@inproceedings{ruiz2026nearzero,
  title     = {Near-Zero Forgetting Is Not Enough: Out-of-Distribution Robustness in Continual Learning of Pretrained {VLA}s},
  author    = {Ruiz, Adri{\`a} and Twardowski, Bart{\l}omiej and Tuytelaars, Tinne and Masip, Sergi},
  booktitle = {CoRL 2026 Workshop on Robot Learning at Deployment (Learn@Deploy)},
  year      = {2026}
}

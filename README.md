# When Validation Stops Learning: Auditing Update Admission for Continual Embodied Agents

Qinzhen Ma, Ruihai Wu

arXiv preprint, 2026

**Project page:** https://when-validation-stops-learning.pages.dev · [arXiv:2609.10873](https://arxiv.org/abs/2609.10873) · [Paper PDF](assets/paper.pdf)

> An update gate should be audited for the learning it blocks as well as the errors it stops: fresh paired checks admit 31.6% of a common update stream where a range-based confidence gate admits none.

## Abstract

Independent evaluation can reject harmful policy updates yet also prevent useful continual learning. We argue that update admission must be assessed through both error control and retained learning opportunities at a stated interaction budget. We identify a concrete failure: a range-based confidence gate cannot certify unchanged old-task behavior within otherwise substantial budgets. A standard paired-binomial construction reduces this burden when outcome disagreements are rare. We also specify certified historical-reference promotion and a round-level missed-opportunity metric. In a constructed one-step pushing diagnostic with 32 seeds, fresh paired checks admit 31.6% of a common update stream at 2,000 episodes per stage, versus zero for the range-based gate; unconditional replay nevertheless learns better in closed-loop runs. A separate learned-dynamics stress test distinguishes model bias from feedback-selection error. The contribution is an admission-audit protocol with analytical and synthetic evidence; physical-robot and VLA validation remain open.

## Code

Code release: to be added to this repository.

## Project page

The site is plain static HTML (`index.html`, `style.css`, `assets/`) deployed with Cloudflare Pages
from this repository: no build command, output directory `/`.

## Citation

```bibtex
@article{ma2026when,
  title  = {When Validation Stops Learning: Auditing Update Admission for Continual Embodied Agents},
  author = {Qinzhen Ma and Ruihai Wu},
  journal = {arXiv preprint arXiv:2609.10873},
  year   = {2026}
}
```

---
title: Common traps to avoid when building AI systems
description: Assessing common AI/ML mistakes that lead to unintended side effects.
author: Mike Nolan
categories: privacy-ethics
tags: ["design"]
downloadBtn: "true"

---

_Assessing common mistakes that lead to unintended side effects_.
Information summarized from [_Fairness and Abstraction in Sociotechnical Systems_](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3265913), a paper published at the 2019 ACM Conference on Fairness, Accountability, and Transparency.


## Framing Trap

_Failure to model the entire system over which a social criterion, such as fairness, will be enforced_.

For this trap, we will want to look at our outcome variables.
Are these variables a proxy of the actual outcome you wish to achieve?
What evidence of existing negative bias currently exists with regards to these variables?


## Portability Trap

_Failure to understand how repurposing algorithmic solutions designed for one social context may be misleading, inaccurate, or otherwise do harm when applied to a different context_.

Here, you will want to be fully understanding of the context in which this model is being built for and the context in which you will be using it.
There should be clear documentation distributed across the entire team focusing on this.
What stakeholders do you expect to have an impact on where this technology will be used.
Are they informed?


## Formalism Trap

_Failure to account for the full meaning of social concepts such as fairness, which can be procedural, contextual, and contestable, and cannot be resolved through mathematical formalisms_.

How does your chosen outcome continue to implement and solve existing procedural "catches" in order to ensure the decision making process is fair?
What method of recourse are available for those who are unfairly judged?


## Ripple Effect Trap

_Failure to understand how the insertion of technology into an existing social system changes the behaviors and embedded values of the pre-existing system_.

How do you think the introduction of this recommendation system will affect your users?
What changes in behavior do you intend to change?
Can you think of any possible changes in behavior that you don't intend as a result of your software?


## Solutionism Trap

_Failure to recognize the possibility that the best solution to a problem may not involve technology_.

Will this technology elevate social values which can be quantified?
Will it devalue those which cannot?
What values might take a back seat if this technology is implemented?


## Attributions

Thanks to the publishers of the [original paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3265913):

* **Andrew D. Selbst**
  (UCLA School of Law)
* **Danah Boyd**
  (Data & Society Research Institute; Microsoft Research)
* **Sorelle Friedler**
  (Haverford College)
* **Suresh Venkatasubramanian**
  (University of Utah)
* **Janet Vertesi**
  (Princeton University)

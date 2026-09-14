# Attestra — User stories

**Product:** [PRODUCT.md](./PRODUCT.md)


### Model owner and product manager (first line)

- As a model owner, I want to see the exact evidence still outstanding for my clearance and who owes it, so that I can plan a launch date instead of waiting for legal to come back to me.
- As a model owner, I want the platform to tell me at design time which of the three lawful bases my intended decision can plausibly rest on, so that I do not build a fully automated flow that has to be rebuilt with a human in the loop.
- As a product manager, I want to know before I change a decision's population or thresholds whether the change invalidates the existing clearance, so that a routine release does not put the enterprise outside its lawful basis.
- As a model owner, I want low-risk systems to clear through self-attestation against a standard control set, so that second-line challenge is spent on the systems that warrant it.

### Second-line reviewer and model validator

- As a second-line reviewer, I want a queue ordered by risk tier and clearance expiry rather than by submission date, so that my scarce challenge capacity lands on the highest-exposure systems first.
- As a model validator, I want to record a challenge finding that blocks clearance until it is resolved or formally accepted, so that my objection cannot be quietly closed by the business unit that raised the submission.
- As a second-line reviewer, I want to see every case where a fairness claim rests on inferred rather than observed protected attributes, so that I can judge how much weight the claim can actually bear.
- As a second-line reviewer, I want to be blocked from approving a system inside my own reporting line, so that the independence of my review is a property of the system rather than of my discretion.

### Data Protection Officer and privacy counsel

- As a DPO, I want a single register of every solely-automated decision the enterprise makes, its lawful basis, and its safeguard status, so that I can answer a supervisory authority in days rather than commissioning a discovery exercise.
- As privacy counsel, I want special-category data used for bias testing held in a purpose-limited enclave with its own retention clock, so that proving non-discrimination does not itself create a new compliance exposure.
- As a DPO, I want to record where an explanation obligation exists and what the individual actually receives, so that transparency is evidenced by the artefact rather than by the policy.

### Named human overseer and operations lead

- As a named overseer, I want intervention and contestation cases delivered with the decision inputs, the model's reasoning and my authority to overturn stated plainly, so that my review is meaningful rather than a rubber stamp.
- As an operations lead, I want an alert when a contestation queue breaches its published response commitment, so that a rights failure is handled as an operational incident rather than surfacing later as a complaint.
- As a named overseer, I want to decline an oversight nomination when I lack the competence or the capacity for it, so that accountability is not assigned to me by default. *(exception path)*

### Board risk committee and internal audit

- As a board risk committee member, I want the portfolio shown as cleared, conditionally cleared, blocked and expired, with the value at stake behind each state split by growth channel, so that I can decide whether to fund faster assurance or accept slower deployment.
- As an internal auditor, I want to reconstruct any past clearance exactly as it stood on a given date, including the evidence, the challenge findings and the named approver, so that a decision made two years ago is still defensible today. *(governance / admin story)*
- As a board risk committee member, I want every live risk acceptance listed with its named owner and expiry, so that exceptions age visibly instead of becoming permanent policy.

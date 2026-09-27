# Task 07: The Ethics of Synthetic Representation

## Project Overview

This repository contains the two required phases of **Research Task 7: The Ethics of Synthetic Representation**.

Task 7 builds directly on my Task 6 synthetic-media experiment. In Task 6, I converted a verified sports-analysis narrative into synthetic audio using ElevenLabs and a synthetic-avatar video using HeyGen. The media was clearly labeled as synthetic, used a stock/synthetic avatar, and did not impersonate a real person.

Task 7 moves from building synthetic media to governing it:

- **Phase A** analyzes the ethical implications of the capability I exercised in Task 6.
- **Phase B** converts that analysis into an operational synthetic-media policy for a specific organizational setting.
- **Policy Limitations** stress-tests the policy and identifies residual risks it cannot eliminate.

No new synthetic-media artifact is created for this task.

## Organizational Context

The Phase B policy is written for a **University Athletics Communications Office**.

I chose this setting because it connects directly to my Task 6 artifact, which presented an analysis of Syracuse women's lacrosse data. An athletics communications office is a realistic environment in which synthetic narration, accessibility content, multilingual communication, generic presenters, recruiting media, athlete features, and public announcements could all be considered.

The same setting also creates clear risks: fabricated statements by coaches or athletes, false injury or disciplinary announcements, unauthorized voice or likeness cloning, misleading recruiting communication, and synthetic content that loses its disclosure after reposting.

The policy is intentionally written as a **generic university athletics policy**, not as an official policy of Syracuse University.

## Repository Map

| File | Purpose |
|---|---|
| `PHASE_A_ETHICAL_ANALYSIS.md` | Ethical analysis grounded in the Task 6 artifact, including the truth, consent, context, and scale axes and a mitigation survey |
| `PHASE_B_SYNTHETIC_MEDIA_POLICY.md` | Operational governance policy for a University Athletics Communications Office |
| `POLICY_LIMITATIONS.md` | Stress test of the policy, including residual risk and failure modes |
| `TASK6_REFERENCE.md` | Reference to the Task 6 repository and the specific Task 6 experiences used in this analysis |
| `README.md` | Project description, context, repository map, and reflection |

## Task 6 Reference

Task 6 repository:

https://github.com/rvsspavankumar/Task_06_Deep_Fake

Task 6 used:

- ElevenLabs synthetic audio;
- a HeyGen stock/synthetic avatar;
- a truthful Task 5 sports-analysis narrative;
- explicit synthetic-media disclosure;
- a visible HeyGen watermark;
- a macOS screen recording because the free HeyGen tier did not allow direct download.

The Task 6 artifact is **referenced rather than re-uploaded** in this repository.

## Brief Reflection

The most surprising lesson from Task 6 was not that synthetic media could be made. It was how quickly a factual script could acquire the tone and appearance of a human presentation, even though no human speaker actually delivered it.

A second lesson came from the free-tier workflow. Because HeyGen did not allow direct download, I preserved the generated video by screen recording it. The watermark remained visible in my recording, which was useful for provenance, but the process also demonstrated how easily media can leave the environment in which it was generated and become a new file. That experience made the **context** and **provenance** questions in Task 7 much more concrete.

My main conclusion is that disclosure, provenance, detection, and policy are all useful, but none is sufficient alone. Responsible use requires several layers at once: narrow permitted uses, explicit prohibitions, documented consent, persistent disclosure, human review, provenance records, and a willingness to refuse projects whose risk cannot be reduced enough.

## Scope Note

This project reasons primarily from my own Task 6 experience and from invented hypotheticals, rather than cataloguing real-world deepfake incidents. The scenarios in Phase A are fictional and are used to test ethical boundaries.

## Status

- Phase A ethical analysis: complete
- Phase B governance policy: complete
- Policy limitations / stress test: complete
- Task 6 reference: complete

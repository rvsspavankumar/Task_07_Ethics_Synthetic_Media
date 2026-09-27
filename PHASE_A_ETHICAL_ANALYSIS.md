# Phase A: Ethical Analysis

## 1. Starting Point: What I Actually Built

My Task 6 artifact began with a relatively low-risk use case. The source material was a sports-analysis narrative derived from my Task 5 work on the 2025 Syracuse women's lacrosse season. The script stated that Syracuse's offensive outcome gap was larger than its defensive outcome gap and explained that the result was an observational recommendation rather than a causal guarantee.

I converted that verified script into synthetic media in two forms:

1. a synthetic voice generated with ElevenLabs; and
2. a synthetic talking-avatar video generated with HeyGen.

The avatar was a stock/synthetic presenter rather than an impersonation of a real person. The repository clearly labeled the media as synthetic, and the HeyGen watermark remained visible in the screen-recorded video.

On the surface, this was a responsible use: truthful content, no stolen identity, explicit disclosure, and an academic purpose. That is exactly why it is a useful ethical starting point. The underlying capability is much broader than the harmless use I selected.

## 2. Returning to the Artifact with Fresh Eyes

When I was creating the Task 6 artifact, my attention was mostly technical: generate the voice, create the avatar video, preserve the result, document the tool limitations, and make sure the artifact was visibly labeled.

Looking back at it as an ethics problem changes what stands out.

The first issue is **borrowed human authority**. The synthetic presenter gives a statistical argument a face, voice, pacing, and apparent confidence. A viewer can react to those cues before thinking about who actually performed the analysis, who is responsible for the claims, or whether there is a human speaker who can be questioned.

The second issue is **separation between message and speaker**. In a normal recorded presentation, the person on screen is usually accountable for what is being said. In a synthetic presentation, the apparent speaker may have no relationship to the claim at all. Even when the content is true, synthetic representation makes it easier to detach communication from the individual who would normally carry responsibility for it.

The third issue is **portability**. My HeyGen free-tier workflow did not allow a direct download, so I preserved the generated video by making a macOS screen recording. The HeyGen watermark remained visible in my copy, which helped preserve provenance. At the same time, the experience showed how easily media can leave the original generation environment and become a new file with a different technical history. A future editor could crop, re-encode, caption, or repost that copy.

The fourth issue is **ease of repetition**. Once the script and workflow exist, making another synthetic presentation is not conceptually difficult. The ethical question therefore cannot be limited to whether one artifact is harmless. Governance has to anticipate repeated and scaled use.

I would create a similar artifact again for clearly disclosed research, education, accessibility, or generic presentation purposes. I would not use the same workflow to make a real person appear to say something they did not say, to publish sensitive claims in synthetic form, or to create content whose disclosure is likely to disappear while the human-like presentation remains.

---

## 3. Reasoning Across the Ethical Axes

The following scenarios are fictional. Each changes one major feature of my Task 6 use case while keeping the underlying synthetic-media capability similar.

### Axis 1: Truth

#### Hypothetical

A university athletics communications employee uses the same type of synthetic presenter I used in Task 6. The video is professionally formatted and appears to be an athletics update. Instead of presenting verified statistics, the script falsely states that a starting player has been suspended for violating team rules.

The employee includes accurate team colors, schedule information, and other true details around the false claim. The video is posted briefly, copied by viewers, and redistributed before the department removes it.

#### Ethical Change

The delivery mechanism is almost identical to my Task 6 artifact. The decisive ethical change is that the content is false.

Synthetic presentation can make false information easier to package in a credible form because viewers are not only processing text. They are receiving voice, facial expression, timing, confidence, and visual framing. Those cues can create the appearance of an official communication even though the statement was fabricated.

The harm is not limited to whether viewers eventually learn that the claim was false. The player may suffer reputational damage, teammates and family may react, and later corrections may circulate less widely than the original clip.

The ethical lesson is that **truthfulness must be a production requirement, not merely a preference**. High-risk factual claims should require source verification and human approval before synthetic media is generated or released. Disclosure that a clip is AI-generated does not make false content acceptable.

### Axis 2: Consent

#### Hypothetical

A university athletics office wants to publish an accurate ticket-sales announcement while the head coach is traveling. An employee has enough old interview audio to create a convincing clone of the coach's voice. The script is completely truthful and contains nothing controversial.

The employee reasons that the coach would probably approve of the message and uses the cloned voice without asking. The file is labeled as AI-generated.

#### Ethical Change

Here the content remains true, but the identity boundary changes.

A person's voice or likeness is not simply another communication format. It is part of how that person expresses agency, reputation, and accountability. Using it without consent makes the individual appear to participate in a communication they never chose to make.

Disclosure reduces deception toward the audience, but it does not solve the consent problem for the person being represented.

Employment should not be treated as blanket permission to synthesize a person's identity. Consent should specify the purpose, duration, channels, and type of synthetic representation. It should also be revocable for future uses.

This axis is where synthetic media can move from a generic tool into impersonation. My Task 6 use of a stock/synthetic avatar avoided this boundary. That design choice should become a governance rule: **use generic synthetic presenters by default; use real identities only under documented, purpose-specific consent**.

### Axis 3: Context

#### Hypothetical

An athletics office publishes a clearly labeled AI-generated weekly sports recap using a synthetic avatar. The opening frame says "AI-generated synthetic media," the caption repeats the disclosure, and the original platform shows a watermark.

A viewer screen-records only the middle 20 seconds. The opening disclosure is gone. Another user crops the watermark and reposts the clip with the caption, "Official statement from the athletics department."

The spoken content itself has not changed.

#### Ethical Change

The ethical risk changes because the **context carrying the disclosure has been separated from the content carrying the persuasive human-like presentation**.

This scenario is especially relevant to my Task 6 workflow. I already created a screen-recorded derivative of the hosted HeyGen video. In my case, the watermark remained visible. That was a positive provenance outcome, but it also demonstrated how easily a new copy can be created outside the original platform.

This means disclosure cannot depend on a single title card, caption, metadata field, or platform label. A responsible workflow should use redundant disclosure: visible labeling in the media itself, written disclosure in the post, provenance metadata where available, and internal records linking the public file to its generation history.

Even then, disclosure can be stripped. Governance therefore has to assume that some downstream copies will lose context and ask whether the underlying media would become materially deceptive if that happened. If the answer is yes and the harm would be serious, the organization should consider refusing the project.

### Axis 4: Scale

#### Hypothetical

A university athletics office develops a system that can automatically generate personalized synthetic-avatar videos for prospective students, donors, alumni, recruits, and fans. Instead of producing one weekly recap, the office can create thousands of videos per month.

Each video can vary a person's name, sport, donation history, recruiting interest, location, and preferred language.

#### Ethical Change

Scale changes the governance problem even if each individual video appears low risk.

First, human review becomes difficult. A mistake in a template or data source can be reproduced thousands of times before anyone notices.

Second, personalization can increase persuasive force. A synthetic presenter addressing a viewer by name may feel more like a human interaction even when no human reviewed or delivered the message.

Third, scale changes accountability. It becomes unclear whether responsibility belongs to the person who wrote the template, the engineer who built the workflow, the data owner, the communications office, or the platform generating the media.

Fourth, incident response becomes harder. Retracting one video is manageable. Identifying and correcting thousands of generated variations is not.

The ethical lesson is that **permission to create one synthetic artifact should not automatically imply permission to automate the same artifact at scale**. High-volume or personalized generation should trigger a separate review threshold, stronger logging, sampling, testing, and a defined shutdown mechanism.

---

## 4. Mitigation Landscape

No single mitigation resolves the ethical problems above. Each provides useful protection while failing in predictable ways.

| Mitigation | What it promises | Where it breaks | Lesson from Task 6 |
|---|---|---|---|
| Disclosure labels | Tell viewers that media is synthetic | Labels can be ignored, cropped, removed, or separated from excerpts | Task 6 used disclosure in filenames/documentation and preserved the HeyGen watermark, but downstream editing could change that |
| Visible watermarking | Keeps a synthetic indicator inside the media | Can be cropped, blurred, covered, or excluded from an excerpt | The HeyGen watermark survived my screen recording, which was useful but not a guarantee for every transformation |
| Provenance / content credentials | Preserve information about media origin, tools, edits, or signing history | Metadata may be absent, unsupported, stripped, or unavailable after screen recording and re-encoding | My derivative screen recording had a new technical history, showing why provenance should not depend on one metadata layer |
| Automated detection | Attempts to classify media as synthetic using forensic signals | False positives, false negatives, model updates, compression, and generator advances reduce reliability | Task 6 did not use an independent automated detector, so I cannot claim detector performance from my own experiment |
| Legal / regulatory rules | Create duties or penalties for harmful synthetic-media uses | Jurisdiction, definitions, enforcement speed, and cross-platform distribution can limit effectiveness | Law is a backstop; an organization still needs operational rules before a violation becomes a legal case |
| Platform policy | Allows platforms to label, reduce, or remove deceptive synthetic content | Enforcement varies; content can move between services; reposts may escape the original platform's controls | My HeyGen-hosted output could be copied into a local screen recording, demonstrating cross-environment movement |
| Professional / organizational norms | Set stricter internal expectations for acceptable use | Depend on staff awareness, incentives, enforcement, and good-faith compliance | This is the layer the Phase B policy addresses directly |
| Human review | Adds accountable judgment before publication | Reviewers can miss issues, become overloaded, or approve ambiguous cases inconsistently | Review is necessary but should be combined with narrow permitted uses and refusal rules |

### Disclosure

Disclosure is necessary because audiences should not have to infer whether a human-looking or human-sounding presentation is synthetic. However, disclosure is fragile. A caption may not travel with a downloaded video. An opening title may be cut from an excerpt. A watermark may not remain after editing.

Therefore, disclosure should be **redundant and persistent**, but organizations must still assume that some viewers will encounter a copy without the original context.

### Provenance and Content Credentials

Provenance systems can help document where media came from and whether supported tools recorded parts of its history. Their strongest value is evidentiary: they help establish a chain of custody for responsible organizations.

They do not establish truth. A perfectly signed synthetic video can still contain a false script, and a genuine recording can be published without provenance metadata.

My Task 6 screen-recording workflow also showed a practical boundary: once a hosted video becomes a screen recording, the derivative file has a new creation path. That makes internal logging and retained originals important alongside technical credentials.

### Detection

Detection can be useful as one signal, particularly when provenance is missing. However, a detector result should not be treated as proof.

My Task 6 submission relied on provenance evidence rather than an independent deepfake detector: the hosted HeyGen link, visible watermark, synthetic filenames, disclosure, and process documentation. Because I did not run a separate detector, the responsible conclusion is limited: I learned more about **provenance visibility** than detector accuracy.

An organizational policy should therefore avoid requiring a detector to make a final authenticity decision by itself.

### Legal and Regulatory Regimes

The legal landscape generally addresses synthetic media through several kinds of rules: disclosure obligations, restrictions around sensitive or election-adjacent uses, protections against non-consensual synthetic imagery, fraud and impersonation rules, and obligations placed on platforms or distributors.

For an organization, legal compliance should be treated as the minimum boundary rather than the complete ethical standard. A use can be unwise or harmful before it clearly violates a law.

### Platform Policy

Platforms can provide labels, upload restrictions, reporting mechanisms, removal processes, and synthetic-media rules. These controls matter most at the point of distribution.

Their weakness is portability. Content can be downloaded, screen-recorded, reposted, compressed, or moved to a different service. Organizational governance should therefore remain effective even when platform protections disappear.

### Professional and Organizational Norms

Professional norms are the most immediate layer of control for the setting chosen in Phase B. A university athletics office can decide that some technically possible uses will simply not be produced.

This layer can be stronger than disclosure alone because it controls the decision **before** generation. It can say that certain sensitive categories—such as synthetic disciplinary announcements or unauthorized athlete impersonation—are prohibited even if the media would be labeled.

---

## 5. Accountability

The ethical burden should be shared, but not evenly distributed.

The **producer** has the strongest initial responsibility because they choose the script, identity, tool, disclosure, and release context.

The **organization** has responsibility for setting boundaries, creating review systems, maintaining consent records, training staff, and responding to incidents.

The **platform** has responsibility for the distribution environment, including available provenance, labeling, reporting, and enforcement mechanisms.

The **audience** can exercise skepticism, but governance should not shift the main burden onto viewers. A viewer cannot reasonably investigate every clip before reacting to it.

Regulators provide an external boundary, but internal governance should operate before a harmful use reaches the point where legal enforcement is necessary.

---

## 6. Bridge to Phase B

The four axes point toward specific governance requirements:

- the **truth axis** requires verification and approval for factual claims;
- the **consent axis** requires documented, purpose-specific permission for real identities;
- the **context axis** requires redundant disclosure and retained provenance records;
- the **scale axis** requires a separate review threshold for automated, personalized, or high-volume production.

The mitigation survey also shows why the policy cannot rely on one technical solution. The Phase B policy therefore combines narrow permitted uses, explicit prohibitions, consent, disclosure, provenance records, human review, incident response, and refusal.

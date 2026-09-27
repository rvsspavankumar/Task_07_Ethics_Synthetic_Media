# Task 6 Reference

## Repository

Task 6 — Constructing and Evaluating Synthetic Media:

https://github.com/rvsspavankumar/Task_06_Deep_Fake

This Task 7 repository references Task 6 rather than re-uploading its synthetic media.

## Task 6 Source Narrative

The Task 6 script was based on the Task 5 analysis of the 2025 Syracuse women's lacrosse season.

Key points in the script included:

- Syracuse averaged 15.70 goals in wins and 8.67 in losses.
- The offensive outcome gap was approximately 44.80%.
- The defensive outcome gap was approximately 29.63%.
- Offense was the recommended team-level priority under the defined rule.
- Emma Ward had the highest Offensive Impact Score.
- Emma Muchnick had the highest overall Game Changer Score.
- The script explicitly stated that the recommendation was observational, not causal.

## Synthetic Media Approaches Used

### Approach 1 — ElevenLabs audio

Task 6 generated a synthetic narration using:

- ElevenLabs;
- the voice "Alexandra - Conversational and Natural";
- the Task 5 coaching-analysis script.

The retained MP3 was approximately 62 seconds long.

### Approach 2 — HeyGen avatar video

Task 6 generated a talking-avatar presentation using:

- HeyGen;
- a stock/synthetic avatar;
- the same Task 5 analytical narrative.

The free HeyGen account allowed generation and viewing but did not allow direct download. The output was therefore preserved using a macOS screen recording.

## Provenance Experience

The screen-recorded HeyGen artifact retained a visible HeyGen watermark.

Task 6 did not run an independent automated deepfake detector. Instead, its provenance check documented:

- the hosted HeyGen URL;
- visible HeyGen watermark;
- synthetic labeling in filenames;
- repository disclosure;
- process documentation;
- local media metadata.

This matters for Task 7 because it demonstrates both the value and fragility of provenance.

The watermark survived the screen-recording workflow used in Task 6, but screen recording also produced a new media file outside the original hosting environment. That experience directly informs the Task 7 analysis of context loss, re-encoding, reposting, and chain-of-custody.

## Key Task 6 Lessons Used in Task 7

1. **Truthful content can still gain artificial human authority.**  
   The script was factually grounded, but the generated voice and face gave the analysis the form of a human-delivered presentation.

2. **Generic synthetic identities reduce consent risk.**  
   Task 6 did not require impersonating a real person.

3. **Disclosure matters, but it is not permanent.**  
   Task 6 intentionally labeled artifacts as synthetic.

4. **Watermarking is useful but bounded.**  
   The HeyGen watermark remained visible in the retained screen recording.

5. **Media can leave the generator's original environment easily.**  
   Screen recording created a derivative copy when direct download was unavailable.

6. **Provenance and detection are different.**  
   Task 6 documented provenance but did not establish how an independent detector would classify the artifact.

7. **Consumer tools make repetition easy.**  
   Once the script and workflow were established, generating additional synthetic communication would require much less conceptual effort.

## Task 6 Files Most Relevant to This Analysis

Within the Task 6 repository:

- `README.md`
- `PROCESS_LOG.md`
- `EVALUATION.md`
- `DETECTION_RESULTS.md`
- `scripts/source_script.md`

These files form the experiential basis for the Phase A analysis in Task 7.

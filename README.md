# Task 06: Constructing and Evaluating Synthetic Media

> **Synthetic Media Disclosure:** The audio and video artifacts contained in this repository were created using AI-based synthetic media tools for research and educational purposes. They should not be interpreted as authentic human recordings.

## Project Overview

This project explores how a written analytical narrative can be transformed into synthetic media using currently available AI tools.

The goal was not simply to create realistic AI-generated content, but to examine the process of creating it, identify noticeable failure modes, compare different generation approaches, and investigate how synthetic content can be detected or identified through provenance mechanisms.

The experiment focuses on characteristics such as:

* Prosody and speech rhythm
* Pronunciation
* Emotional expression
* Cadence and pauses
* Lip synchronization
* Facial movement
* Blinking and gaze
* Overall realism
* Synthetic-media detection and provenance

## Source Script

The experiment uses a short analytical narrative discussing synthetic media and the differences between AI-generated and authentic human communication.

The complete script can be found in:

`source_script.md`

The same underlying narrative was used across the experiments so that differences between the generated outputs could be compared more consistently.

## Approach 1: AI-Generated Audio

For the first approach, I used ElevenLabs Text to Speech to convert the written narrative into synthetic speech.

I generated multiple versions of the same script and compared their pacing, pronunciation, emphasis, and overall naturalness.

### Process

1. The source script was entered into ElevenLabs Text to Speech.
2. A synthetic voice was selected.
3. The first version of the audio was generated.
4. The output was reviewed for pacing, pronunciation, and naturalness.
5. A second generation was created to compare the results.
6. The preferred output was downloaded and saved as a synthetic artifact.

The final audio artifact is stored as:

`artifacts/approach_A_SYNTHETIC_audio.mp3`

A screenshot showing the generation process is available in:

`screenshots/elevenlabs_generations.png`

### Observations

The generated speech was clear and generally convincing. Shorter sentences sounded particularly natural.

Some weaknesses became more noticeable during longer sentences. These included slightly unnatural pauses, inconsistent emphasis, and a lack of the subtle breathing and hesitation patterns normally present in human speech.

Repeated listening also made the consistency of the synthetic voice more noticeable.

## Approach 2: Synthetic Avatar Video

The second approach uses the same narrative/audio with a synthetic or generic avatar to investigate how adding a visual component affects perceived realism.

The final artifact is stored as:

`artifacts/approach_B_SYNTHETIC_video.mp4`

The video is evaluated for:

* Lip synchronization
* Facial expressions
* Blinking
* Eye movement and gaze
* Head movement
* Emotional alignment
* Temporal consistency

## Comparison

The audio-only approach produced convincing speech with relatively little effort.

Adding a visual avatar introduced additional opportunities for synthetic-media artifacts to become visible. Even when the underlying audio sounded natural, facial movement, gaze, blinking, and lip synchronization provided additional signals that could make the output appear artificial.

This suggests that increasing the number of generated modalities does not automatically increase overall realism.

## Detection and Provenance

The generated artifacts were also considered from a synthetic-media detection and provenance perspective.

The goal of this portion of the experiment is to determine whether automated tools or embedded provenance information can identify the content as synthetic.

Results from these checks are documented in:

`detection_results.md`

Detection confidence should not be interpreted as definitive proof of authenticity or manipulation. Detection systems attempt to classify media based on characteristics of the content, while provenance systems attempt to preserve information about where media originated and how it was modified.

## Key Failure Modes

Several important synthetic-media failure modes were considered during the experiment.

### Prosody

AI-generated speech can pronounce individual words correctly while placing emphasis on unusual parts of a sentence.

### Cadence

Synthetic speech can sometimes sound unusually consistent compared with natural human speech.

### Emotional Register

The generated voice may communicate the words correctly without reproducing all of the emotional variation expected from a human speaker.

### Lip-Sync Drift

In synthetic video, mouth movements may occasionally fail to perfectly match the corresponding speech.

### Blinking and Gaze

Synthetic avatars may display unusually repetitive blinking or maintain eye contact more consistently than a human speaker.

### Temporal Stability

Small inconsistencies in facial movement, lighting, or other visual elements may become noticeable when synthetic video is viewed repeatedly.

## What I Learned

One of the most interesting observations from this experiment was the difference between first impressions and careful inspection.

A synthetic artifact can appear convincing during a short interaction. However, repeated listening or viewing makes subtle patterns easier to recognize.

For audio, these patterns include pacing, breathing, emphasis, and emotional variation.

For video, additional signals such as lip synchronization, blinking, gaze, and facial expressions become important.

The experiment demonstrates that evaluating synthetic media requires more than simply asking whether something "looks real" or "sounds real."

## Reproducing the Experiment

To reproduce the audio portion of this project:

1. Open an AI text-to-speech platform such as ElevenLabs.
2. Copy the narrative from `source_script.md`.
3. Select a generic synthetic voice.
4. Generate the first version.
5. Listen for problems with pronunciation, pacing, emphasis, and pauses.
6. Modify punctuation or sentence structure if necessary.
7. Generate another version.
8. Compare the generations.
9. Export the preferred version.
10. Clearly label the exported file as synthetic.

For the video experiment, the generated audio can be paired with a generic synthetic avatar using an AI avatar/video-generation platform.

## Repository Structure

```text
Task_06_Deep_Fake/
│
├── README.md
├── source_script.md
├── process_log.md
├── evaluation.md
├── detection_results.md
│
├── artifacts/
│   ├── approach_A_SYNTHETIC_audio.mp3
│   └── approach_B_SYNTHETIC_video.mp4
│
└── screenshots/
    └── elevenlabs_generations.png
```

## Ethical Considerations

No real identifiable person's likeness should be used without consent.

This project uses synthetic media strictly for educational and research purposes. All generated artifacts are clearly identified as synthetic so that viewers are not misled about their origin.

## Conclusion

This experiment demonstrates how accessible synthetic-media generation has become while also showing that convincing output is not necessarily indistinguishable from authentic media.

Synthetic audio can achieve a high level of clarity and short-form realism, but careful listening can reveal weaknesses in prosody, cadence, breathing, and emotional expression.

Synthetic video introduces additional challenges because audio must be coordinated with facial movement, lip synchronization, blinking, gaze, and expression.

Overall, the experiment highlights the importance of critical evaluation, transparent labeling, and provenance when working with synthetic media.

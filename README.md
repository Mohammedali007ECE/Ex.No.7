# EXP 7 – Exploration of Prompting Techniques for Audio Generation

**Date:** 28-08-2026
**Register No.:** 212223060161

## Aim

To explore and analyze different prompting techniques for AI-based audio generation and understand how prompt structure, context, musical parameters, and descriptive details influence the quality and characteristics of generated music, speech, and sound effects.

## AI Tools Required

1. **Google MusicLM / other AI music generation model** – For text-to-music generation.
2. **AI Text-to-Speech Tool** – For speech and voice generation.
3. **AI Sound-Effect Generator** – For generating environmental and cinematic sound effects.
4. **Web Browser** – For accessing the selected AI audio-generation platform.

## Introduction

AI-based audio generation uses machine-learning models to synthesize music, speech, and sound effects from textual or multimodal inputs. The quality of the generated audio depends significantly on the prompt provided to the model.

Prompt engineering allows the user to control parameters such as:

* Genre
* Mood
* Tempo/BPM
* Instrumentation
* Duration
* Vocal characteristics
* Environment
* Audio intensity
* Rhythm
* Production style

In this experiment, prompts are progressively improved from **naive prompts** to **refined and advanced prompts** to study their effect on generated audio.

## Procedure

### 1. Understanding AI Audio Generation

First, familiarize yourself with an AI-based audio-generation system capable of producing music, speech, or sound effects from natural-language prompts.

The general workflow is:

**Text Prompt → AI Audio Model → Audio Generation → Listening → Evaluation → Prompt Refinement**

### 2. Naive Prompt

A simple prompt contains minimal information.

**Prompt:**

> "Generate relaxing background music."

**Expected Output:**

A basic relaxing musical track with unspecified instruments, tempo, duration, and structure.

**Observation:**
The output may be relevant to the word *relaxing*, but the musical characteristics may vary considerably.

---

### 3. Refined Prompt

Additional musical parameters are introduced.

**Prompt:**

> "Generate a 3-minute ambient music track with soft piano, light acoustic guitar, and smooth electronic elements. Use a slow tempo of approximately 60 BPM to create a calm and soothing atmosphere suitable for background relaxation."

**Expected Output:**

A slower ambient track containing piano, acoustic guitar, and electronic textures with a calm mood.

**Observation:**
The output becomes more predictable because the prompt specifies instrumentation, tempo, duration, and intended use.

---

### 4. Advanced Prompt – Music Generation

**Prompt:**

> "Create a 3-minute instrumental ambient track for focused studying. Use soft piano chords, subtle acoustic guitar, warm synthesizer pads, minimal percussion, and a tempo of approximately 65 BPM. Maintain a peaceful, non-distracting mood with gradual transitions, moderate reverb, and a clean stereo mix. Avoid vocals and sudden changes in volume."

**Expected Output:**

An instrumental study track with controlled instrumentation, moderate tempo, smooth transitions, and minimal distractions.

**Observation:**
Adding purpose, instrumentation, tempo, structure, and negative constraints provides greater control over the generated audio.

---

## 5. Speech Generation Prompt

AI audio generation can also be used for synthetic speech.

**Prompt:**

> "Generate a clear and professional English announcement for a college technical symposium. Use a confident, friendly, and moderately paced voice. Maintain clear pronunciation and short pauses between sentences. The speech should sound suitable for a public-address system."

**Expected Output:**

A professional announcement with clear pronunciation, appropriate pacing, and a formal tone.

---

## 6. Sound-Effect Generation

**Prompt:**

> "Generate a 15-second realistic laboratory ambience containing low-level electronic equipment hum, cooling fans, occasional keyboard typing, and subtle background room noise. Keep the environment natural and avoid music or human speech."

**Expected Output:**

A realistic technical-laboratory ambient sound.

**Observation:**
Environmental details and unwanted-sound constraints help produce a more specific soundscape.

---

## 7. Cinematic Sound-Effect Prompt

**Prompt:**

> "Generate a 10-second cinematic futuristic laboratory sound effect. Start with a low electronic hum, gradually introduce digital beeps and mechanical movements, and finish with a short high-tech activation sound. Use a dark futuristic atmosphere without music or speech."

**Expected Output:**

A futuristic electronic soundscape containing mechanical and digital elements.

---

## 8. Interactive Prompting

Interactive prompting involves generating an initial audio output and then modifying it through additional instructions.

### Initial Prompt

> "Generate calm instrumental background music for studying."

### Modification Prompt

> "Make the music slightly slower, reduce the percussion, increase the presence of soft piano, and make the background atmosphere more spacious."

### Further Refinement

> "Remove any distracting rhythmic elements and maintain a consistent low-energy atmosphere suitable for concentration."

**Observation:**
Iterative prompting allows the generated audio to be gradually refined according to the desired characteristics.

## Prompt Comparison

| Prompt Type | Details Provided                             | Expected Control | Output Specificity |
| ----------- | -------------------------------------------- | ---------------- | ------------------ |
| Naive       | Very low                                     | Low              | Low                |
| Basic       | Mood + purpose                               | Moderate         | Moderate           |
| Refined     | Genre + instruments + BPM + duration         | High             | High               |
| Advanced    | Musical + structural + technical constraints | Very High        | Very High          |
| Iterative   | Previous output + modifications              | Very High        | High               |

## Observations and Insights

1. **Mood:** Words such as *calm, energetic, dark,* and *peaceful* influence the overall emotional character.
2. **Tempo:** Specifying BPM provides better control over rhythmic speed.
3. **Instrumentation:** Naming instruments helps guide the generated timbre and arrangement.
4. **Duration:** Specifying duration helps define the required output length.
5. **Context:** Describing the intended application improves relevance.
6. **Negative Constraints:** Instructions such as *no vocals* or *avoid sudden volume changes* reduce unwanted elements.
7. **Iterative Prompting:** Repeated refinement improves the output according to user requirements.
8. **Detailed Prompts:** More structured prompts generally provide more predictable and targeted outputs.

## Optimization Report

The following prompt structure was found to be effective:

**[Audio Type] + [Purpose] + [Genre/Style] + [Mood] + [Instruments/Sounds] + [Tempo] + [Duration] + [Structure] + [Constraints]**

### Optimized Example

> "Create a 3-minute instrumental ambient study track with soft piano, warm synthesizer pads, subtle acoustic guitar, and minimal percussion. Use approximately 65 BPM, smooth transitions, low dynamic variation, and a peaceful atmosphere. Keep the arrangement simple and non-distracting. No vocals, no sudden transitions, and no prominent bass."

This prompt provides the AI model with sufficient semantic and musical information to generate a targeted audio output.

## Deliverables

1. Collection of naive, basic, refined, and advanced audio-generation prompts.
2. Generated samples for music, speech, and sound effects.
3. Observations comparing the generated outputs.
4. Prompt optimization report.
5. Comparison of different prompting strategies.

## Result

Different prompting techniques were successfully explored for AI-based audio generation. Naive, refined, advanced, and iterative prompts were tested for music, speech, and sound-effect generation. The experiment demonstrated that adding specific information such as **mood, genre, instruments, BPM, duration, context, structure, and constraints** can improve the relevance and controllability of generated audio.

## Conclusion

The experiment demonstrated the effectiveness of prompt engineering in AI-based audio generation. Simple prompts produce broad results, whereas detailed prompts provide greater control over musical and acoustic characteristics. Iterative prompting further improves the output by allowing modifications based on the generated audio. Thus, effective prompt design is an important technique for generating customized music, speech, and sound effects using AI models.

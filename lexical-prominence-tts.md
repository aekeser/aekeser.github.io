---
layout: default
title: Lexical Prominence and TTS
permalink: /lexical-prominence-tts/
---

# Acoustic Implementation of Lexical Prominence in Human and Synthetic Speech

## A Cross-Linguistic Comparison of English and Turkish

This project examines how contemporary multilingual text-to-speech (TTS) systems reproduce the acoustic realization of lexical prominence in American English and Turkish.

I compare Human and synthetic productions across several acoustic dimensions, including fundamental frequency (F0), intensity, and the first two vowel formants (F1 and F2). The project is designed to evaluate synthetic speech not only in terms of perceptual naturalness, but also in terms of how closely it reproduces linguistically meaningful patterns of phonetic implementation.

The study includes 32 Human speakers, 16 synthetic voice conditions from four multilingual TTS systems, and 120 trisyllabic lexical items across English and Turkish.

## Main Findings

The current analyses show that Human–TTS correspondence is strongly dependent on the acoustic dimension being examined.

F0 and intensity show comparatively selective differences across language and lexical-category conditions, whereas F1 and F2 show broader and more systematic Human–TTS differences across both languages. At the same time, recognizable vowel-space organization is preserved in both Human and synthetic speech.

These findings suggest that preserving broad linguistic organization does not necessarily entail reproducing Human phonetic implementation across all acoustic dimensions.

## Main Figures

### F0

![Model-estimated F0 differences between Human and TTS speech](https://raw.githubusercontent.com/aekeser/english-turkish-lexical-prominence-tts/main/figures/main/Figure_MODEL_01_F0_emmeans.png)

### Intensity

![Model-estimated intensity differences between Human and TTS speech](https://raw.githubusercontent.com/aekeser/english-turkish-lexical-prominence-tts/main/figures/main/Figure_MODEL_02_intensity_emmeans.png)

### Human–TTS Vowel Spaces

![Human and TTS vowel-space comparison](https://raw.githubusercontent.com/aekeser/english-turkish-lexical-prominence-tts/main/figures/main/Figure_DESC_03_Human_TTS_vowel_space.png)

## Interactive 3D Visualizations

The project also includes interactive three-dimensional visualizations of the acoustic data. These are organized by language and voice-sex category.

### English — Female

- [3D vowel space](https://aekeser.github.io/lexical-prominence-tts/interactive/english_female/Figure_3D_01_EN_Female_vowel_space.html)
- [F1–F2–Intensity visualization](https://aekeser.github.io/lexical-prominence-tts/interactive/english_female/Figure_3D_05_EN_Female_F1F2_Intensity.html)

### English — Male

- [3D vowel space](https://aekeser.github.io/lexical-prominence-tts/interactive/english_male/Figure_3D_02_EN_Male_vowel_space.html)
- [F1–F2–Intensity visualization](https://aekeser.github.io/lexical-prominence-tts/interactive/english_male/Figure_3D_06_EN_Male_F1F2_Intensity.html)

### Turkish — Female

- [3D vowel space](https://aekeser.github.io/lexical-prominence-tts/interactive/turkish_female/Figure_3D_03_TR_Female_vowel_space.html)
- [F1–F2–Intensity visualization](https://aekeser.github.io/lexical-prominence-tts/interactive/turkish_female/Figure_3D_07_TR_Female_F1F2_Intensity.html)

### Turkish — Male

- [3D vowel space](https://aekeser.github.io/lexical-prominence-tts/interactive/turkish_male/Figure_3D_04_TR_Male_vowel_space.html)
- [F1–F2–Intensity visualization](https://aekeser.github.io/lexical-prominence-tts/interactive/turkish_male/Figure_3D_08_TR_Male_F1F2_Intensity.html)

## Exploratory Multidimensional Visualization

An exploratory principal component analysis is also available:

- [Exploratory acoustic PCA](https://aekeser.github.io/lexical-prominence-tts/interactive/exploratory/Figure_3D_09_exploratory_acoustic_PCA.html)

The interactive figures are descriptive and exploratory. They should not be interpreted as independent inferential tests or as direct representations of articulatory tongue position.

## Public Research Repository

The public project repository contains:

- finalized stimulus metadata;
- derived descriptive and inferential results;
- main and supplementary figures;
- interactive 3D visualizations;
- analysis scripts;
- sensitivity analyses; and
- methodological documentation.

[View the project repository on GitHub](https://github.com/aekeser/english-turkish-lexical-prominence-tts)

## Acoustic Processing

Acoustic localization and measurement were conducted using **Savlaq**, an automated acoustic-analysis pipeline developed for controlled speech research.

[View Savlaq on GitHub](https://github.com/aekeser/Savlaq)

## Data Availability

Raw Human recordings, participant-level metadata, and other potentially identifying research materials are not publicly distributed.

The public repository contains non-sensitive stimulus metadata, derived results, figures, analysis code, and documentation suitable for open research dissemination.
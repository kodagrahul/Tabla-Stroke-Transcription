# Weakly Supervised Tabla Stroke Transcription via an Adaptive Dynamic Rhythmic Language Model (ADRM)

This repository accompanies the paper:

**_Weakly Supervised Tabla Stroke Transcription via an Adaptive Dynamic Rhythmic Language Model (ADRM)_**

It provides dataset documentation and supporting materials for **weakly supervised Tabla Stroke Transcription (TST)** using symbolic stroke sequence annotations without onset-level timing information.

---

## Overview

This repository focuses on **sequence-level transcription of tabla solo performances** under weak supervision. In contrast to existing datasets that rely on isolated strokes or precise onset annotations, this work addresses transcription from **continuous performances annotated only with symbolic stroke sequences**.

The proposed framework integrates:
- CTC-based acoustic modeling  
- Adaptive Dynamic Rhythmic Language Modeling (ADRM)  
- Rhythm-aware lattice rescoring  

The main contribution is the **Tabla Improvised Dataset (TID)**, curated specifically for weakly supervised learning in Indian percussion music.

---

## Task

### Tabla Stroke Transcription (TST)

- Automatic transcription of tabla strokes from solo performances  
- Learning from symbolic stroke sequences only  
- No onset-level or frame-level alignment  
- Designed for sequence-level and rhythm-aware modeling  

---

## Dataset: Tabla Improvised Dataset (TID)

The **Tabla Improvised Dataset (TID)** consists of continuous tabla solo performances recorded in a controlled environment to minimize background noise.

### Recording Characteristics

- Stereo audio recordings  
- Sampling rate: 44.1 kHz  
- Fixed tabla tuning at A♯ (466.16 Hz)  
- Tempo range: 110–240 BPM (madhya and drut laya)  

### Dataset Statistics

- Total duration: ~133 minutes  
- Number of recordings: 23  
- Recording style: Improvised tabla solos  
- Annotation type: Symbolic stroke sequences (weak labels)  

---

## Tala Coverage

The dataset covers six commonly used Hindustani tala-s:

- Dadra  
- Ektal  
- Jhaptal  
- Kehrva  
- Rupak  
- Teental  

---

## Stroke (Bol) Vocabulary

The dataset includes **30 distinct tabla stroke classes**, covering both **basic articulations** and **compound strokes** involving simultaneous *dayan* and *bayan* gestures.

### Complete Bol List
dha, dhada, dhage, dhi, dhin,
gadi, gana, ge, ghene,
ka, kat, kata, katta,
kita, kitataka, kra,
na, nana,
ta, taka, tati, te, tete,
ti, tin,
tira, tirakita, tirekita,
traka, tu, tuna

## Download "Tabla_Improvised_Dataset_TID"

[Download Tabla Improvised Dataset (TID)]([https://iitk-my.sharepoint.com/:u:/g/personal/rkodag_iitk_ac_in/IQBtPnqqQ3NHTaiacwkkxGLdAaWM_X4xEvZ4RP0aAQLCrms?e=uzVt8V])

---

The dataset contains **performance-recorded audio samples of improvised tabla solo performances**. Tabla is a prominent North Indian percussion instrument widely used in Hindustani classical music and is characterized by rich timbral variations and complex rhythmic structures.

```text
Tabla_Improvised_Dataset_TID/
│
├── Audio/                 # Continuous tabla solo recordings (.wav)
│
├── Annotations/           # Symbolic stroke sequence labels (.txt)
│
└── README.md              # Additional details about the dataset
```

*The codes will be uploaded soon.




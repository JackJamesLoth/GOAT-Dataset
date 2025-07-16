<div align="center">
  
# GOAT: A Large Dataset of Paired Guitar Audio Recordings and Tablatures

<!-- [![Paper](http://img.shields.io/badge/paper-arxiv.1001.2234-B31B1B.svg)](https://www.nature.com/articles/nature14539) -->
[![Conference](http://img.shields.io/badge/ISMIR-2025-4b44ce.svg)](https://ismir2025.ismir.net/)

</div>

## Description

This repository contains helper code and audio examples from the GOAT dataset. If you would like access to this dataset, please request access on the [Zenodo](https://zenodo.org/records/15690894) page.

## Abstract
In recent years, the guitar has received increased attention from the music information retrieval (MIR) community driven by the challenges posed by its diverse playing techniques and sonic characteristics. Mainly fueled by deep learning approaches, progress has been limited by the scarcity and limited annotations of datasets. To address this, we present the Guitar On Audio and Tablatures (GOAT) dataset,  comprising 5.9 hours of unique high-quality direct input audio recordings of electric guitars from a variety of different guitars and players. We also present an effective data augmentation strategy using guitar amplifiers which delivers near-unlimited tonal variety, of which we provide a starting 29.5 hours of audio. Each recording is annotated using guitar tablatures, a guitar-specific symbolic format supporting string and fret numbers, as well as numerous playing techniques. For this we utilise both the Guitar Pro format, a software for tablature playback and editing, and a text-like token encoding. Furthermore, we present competitive results using GOAT for MIDI transcription and preliminary results for a novel approach to automatic guitar tablature transcription. We hope that GOAT opens up the possibilities to train novel models on a wide variety of guitar-related MIR tasks, from synthesis to transcription to playing technique detection.

## Examples
Please refer to the `audio-examples` directory. This directory also contains the corresponding MIDI and tablatures for the example audio.

## Citation
If you would like to cite this work, please use the following citation:
```
@inproceedings{loth_goat_2025,
  author = {Loth, Jackson and Sarmento, Pedro and Sarkar, Saurjya and Guo, Zixun and Barthet, Mathieu and Sandler, Mark},
  booktitle = {Proceedings of the 26nd International Society for Music Information Retrieval Conference},
  title = {{GOAT: A Large Dataset of Paired Guitar Audio Recordings and Tablatures}},
  year = {2025}
}
```

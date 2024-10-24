# ☕ ELAICHI [WIP]
ELAICHI: Enhancing Low-resource TTS by Addressing Infrequent and  Low-frequency Character Bigrams

## Abstract
Recent advancements in Text-to-Speech (TTS) technology have led to natural-sounding speech for English, primarily due to the availability of large-scale, high-quality web data. However, many other languages lack access to such resources, relying instead on limited studioquality data. This scarcity results in synthesized speech that often suffers from intelligibility issues, particularly with low-frequency character bigrams. In this paper, we propose three solutions to address this challenge. First, we leverage high-quality data from linguistically or geographically related languages to improve TTS for the target language. Second, we utilize low-quality Automatic Speech Recognition (ASR) data recorded in non-studio environments, which is refined using denoising and speech enhancement models. Third, we apply knowledge distillation from large-scale models using synthetic data to generate more robust outputs. Our experiments with Hindi demonstrate significant reductions in intelligibility issues, as validated by human evaluators. We propose this methodology as a viable alternative for languages with limited access to high-quality data, enabling them to collectively benefit from shared resources.

## Getting Started
We use the VITS model as implemented by [jaywalnut/vits](https://github.com/jaywalnut310/vits), with an extended vocabulary to accommodate Indian scripts and additional emotion embeddings. Note that all models released in this work have been trained with a neutral emotion label.

## Model Checkpoints
All model checkpoints are public and available [here](https://huggingface.co/collections/ai4bharat/elaichi-671a1cb837b351a28d1c5a8b)

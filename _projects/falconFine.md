---
layout: page
title: Falcon 40B
description: Finetuning Falcon 40B on a subset of the Open Assistant dataset.
img: assets/img/finetuneLLM.jpg
importance: 1
category:
related_publications: False
---

This is one of my initial experiments in finetuning open-source LLMs with data. I used `Falcon40BTrain` to finetune Falcon 40B on a subset of the [Open Assistant dataset](https://github.com/LAION-AI/Open-Assistant). The finetuning process requires at least 40GB of GPU RAM, as the model is loaded in 4-bit using `bitsandbytes`. To upload the adapters to your HuggingFace repo, connect your HuggingFace account by providing your access token. The `Falcon40BTest` component demonstrates how to merge your adapters with the base model and use it for inferencing. Remember to disconnect the kernel after training to free up GPU RAM space for testing.

Check out the project on GitHub [here.](https://github.com/sai-samarth/Falcon40BFinetune)

---
# For reference on model card metadata, see the spec: https://github.com/huggingface/hub-docs/blob/main/modelcard.md?plain=1
# Doc / guide: https://huggingface.co/docs/hub/model-cards
{}
---

# SDXL-Turbo Model Card

<!-- Provide a quick summary of what the model is/does. -->
![row01](output_tile.jpg)
SDXL-Turbo is a fast generative text-to-image model that can synthesize photorealistic images from a text prompt in a single network evaluation.

## Model Details

### Model Description
TODO: ADD DETAILED MODEL DESCRIPTION.



- **Developed by:** Stability AI
- **Funded by:** Stability AI
- **Model type:** Generative text-to-image model
- **Finetuned from model:** [SDXL 1.0 Base](https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0)

### Model Sources

For research purposes, we recommend our `generative-models` Github repository (https://github.com/Stability-AI/generative-models), 
which implements the most popular diffusion frameworks (both training and inference).

- **Repository:** https://github.com/Stability-AI/generative-models
- **Paper:** TODO


## Evaluation
![comparison](comparison.png)
The chart above evaluates user preference for SDXL-Turbo over TODO.
SDXL-Turbo is preferred by human voters in terms of image quality and prompt following. 
For details on the user study, we refer to the [research paper](TODO)

## Uses

### Direct Use

The model is intended for research purposes only. Possible research areas and tasks include

- Research on generative models.
- Research on real-time applications of generative models.
- Research on the impact of real-time generative models.
- Safe deployment of models which have the potential to generate harmful content.
- Probing and understanding the limitations and biases of generative models.
- Generation of artworks and use in design and other artistic processes.
- Applications in educational or creative tools.

Excluded uses are described below.

### Out-of-Scope Use

The model was not trained to be factual or true representations of people or events, 
and therefore using the model to generate such content is out-of-scope for the abilities of this model.
The model should not be used in any way that violates Stability AI's [Acceptable Use Policy](https://stability.ai/use-policy).

## Limitations and Bias

### Limitations
- The generated images are of a fixed resolution (512x512 pix), and the model does not achieve perfect photorealism.
- The model cannot render legible text.
- Faces and people in general may not be generated properly.
- The autoencoding part of the model is lossy.


### Recommendations

The model is intended for research purposes only.

## How to Get Started with the Model

Check out https://github.com/Stability-AI/generative-models




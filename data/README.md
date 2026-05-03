# Dataset

This folder contains all potato leaf image data used for the vision-language model fine-tuning, organised following the raw → processed pipeline.

Images are collected from both controlled/uniform and uncontrolled background conditions.

## Data Sources

- EYEDOL/PlantVillage dataset - images with extended captions 
- Irish Potato Leaf Imagery dataset - 20,000K images from each class healthy, early blight and late blight

## Annotation Format

Images are paired with:
- Disease class labels added with subfolder creation and manual filtering of a subset of images
- Symptom descriptions developed with the support of Generative AI tools (Chat-GPT 5.2)

## Structuring for VLM Applciable Chat-templates
- Question-answer pairs for conversational training developed with Chain-of-Thought reasoning and Question-Answer Pool generation
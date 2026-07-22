# Fashion Trend Segmentation

POC de segmentation vestimentaire via l'API serverless Hugging Face
(modèle `sayeed99/segformer_b3_clothes`).

Projet 2 du parcours AI Engineer — OpenClassrooms.

## Objectif
Évaluer si le modèle SegFormer B3 permet d'identifier les pièces
vestimentaires sur des photos d'influenceurs, et chiffrer le coût
d'un usage à 500 000 images / 30 jours.

## Installation
```bash
uv sync
cp .env.example .env   # renseigner HF_TOKEN
```

## Structure
- `huggingface_api_cloth_seg.ipynb` — notebook principal
- `top_influenceurs_2024/IMG` — images de test
- `top_influenceurs_2024/Mask` — masques annotés de référence

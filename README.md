**Environments**

- Docker image: nvcr.io/nvidia/pytorch:20.12-py3

```bash
einops==0.5.0
timm==0.5.4
wandb==0.12.17
omegaconf
imgaug==0.4.0
```

**Example**

```bash
python main.py configs=configs.yaml DATASET.target=bottle
```

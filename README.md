# Viz: Various state-of-the-art frontier Text-to-Image tools compared
### Source: Individual websites or HuggingFace
### Date: 17-Aug-2024

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Figma Embed</title>
</head>
<body>

<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://www.figma.com/embed?embed_host=share&url=https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Fboard%2F31ubjGVmluozgcJJnTdrO1%2FText-to-Image-Tools-Comparision-17Aug2024%3Ft%3DsPVN8w2tpFbN9FP7-1" allowfullscreen></iframe>

</body>
</html>



# Viz: GPU Pricing compared
### Source: Individual websites
#### Date: 17-Aug-2024
[View GPU Pricing Comparison](https://olabs-ai.github.io/genai-observations/gpu_pricing.html)


# Viz: Various current and planned semiconductor plants in India
### Source: Individual websites
### Date: 17-Aug-2024
[View Semiconductor Plants in India](https://olabs-ai.github.io/genai-observations/semiconductor_companies_india2.html)

# Table: Various GPUs with their configs
### Source: Claude 3.5 Sonnet
### Date: 10-Sep-2024
| Name | Manufacturer | RAM Size | Performance (TFLOPs FP32) | Release Date | Architecture | Cores/Units | Cluster Config | Total Accelerator Size | Additional Info | Source URLs |
|------|--------------|----------|---------------------------|---------------|---------------|-------------|----------------|------------------------|-----------------|-------------|
| A100 (40GB) | NVIDIA | 40 GB | 19.5 | Q2 2020 | Ampere | 6912 CUDA cores | DGX A100 (8 GPUs) | 320 GB | 156 TFLOPs per system | https://www.nvidia.com/en-us/data-center/a100/ https://www.nvidia.com/en-us/data-center/dgx-a100/ |
| A100 (80GB) | NVIDIA | 80 GB | 39 | Q4 2020 | Ampere | 6912 CUDA cores | DGX A100 (8 GPUs) | 640 GB | 312 TFLOPs per system | https://www.nvidia.com/en-us/data-center/a100/ https://www.nvidia.com/en-us/data-center/dgx-a100/ |
| H100 | NVIDIA | 80 GB | 60 | Q3 2022 | Hopper | 16896 CUDA cores | DGX H100 (8 GPUs) | 640 GB | 480 TFLOPs per system | https://www.nvidia.com/en-us/data-center/h100/ https://www.nvidia.com/en-us/data-center/dgx-h100/ |
| MI250X | AMD | 128 GB | 47.9 | Q4 2021 | CDNA 2 | 14080 stream processors | 8-way config | 1024 GB | 383.2 TFLOPs per system | https://www.amd.com/en/products/server-accelerators/instinct-mi250x |
| MI300X | AMD | 192 GB | ~123 | Q4 2023 | CDNA 3 | 14080 stream processors | 8-way config | 1536 GB | ~984 TFLOPs per system | https://www.amd.com/en/products/server-accelerators/instinct-mi300 |
| GH200 | NVIDIA | 96 GB | ~60 | Q2 2023 | Hopper | 16896 CUDA cores | Up to 256 nodes | 24,576 GB | ~15,360 TFLOPs (256 nodes) | https://nvidianews.nvidia.com/news/nvidia-announces-gh200-grace-hopper-superchip |
| TPU v4 | Google | 32 GB HBM | ~137.5 (estimated from bfloat16) | Q2 2021 | TPU v4 | 4096 ALUs | TPU v4 pod (4096 chips) | 131,072 GB | 563,200 TFLOPs per pod | https://cloud.google.com/tpu/docs/system-architecture-tpu-vm https://cloud.google.com/blog/products/ai-machine-learning/google-cloud-launches-new-tpu-vms-for-artificial-intelligence-workloads |
| TPU v5e | Google | N/A | N/A | Q3 2023 | TPU v5 | N/A | TPU v5e pod (4096 chips) | N/A | N/A | https://cloud.google.com/blog/products/ai-machine-learning/announcing-cloud-tpu-v5e-and-a3-gpus |
| Gaudi2 | Habana (Intel) | 96 GB | ~350 (estimated from bfloat16) | Q2 2022 | Gaudi2 | 24 Tensor Processor Cores | 8-card server | 768 GB | ~2,800 TFLOPs per server | https://habana.ai/products/gaudi2/ |
| Trainium | AWS | Up to 512 GB | ~500 (estimated from FP16) | Q4 2022 | AWS Trainium | N/A | Trn1.32xlarge (16 chips) | Up to 8,192 GB | ~8,000 TFLOPs per instance | https://aws.amazon.com/machine-learning/trainium/ |
| Groq TSP | Groq | N/A | ~62.5 (estimated from FP16) | Q3 2021 | LPU | N/A | GroqRack (32 chips) | N/A | ~2,000 TFLOPs per rack | https://groq.com/technology/ |
| Cerebras CS-2 | Cerebras | 40 GB eSRAM | ~175 (rough estimate) | Q4 2020 | WSE-2 | 850,000 cores | Single wafer-scale chip | 40 GB | Unique wafer-scale design | https://www.cerebras.net/product-system/ |
| Graphcore IPU-M2000 | Graphcore | 900 MB In-Processor | ~62.5 (estimated from FP16) | Q3 2020 | Colossus Mk2 | 1472 IPU-Cores | IPU-POD64 (16 M2000s) | 57.6 GB | 1,000 TFLOPs per POD64 | https://www.graphcore.ai/products/ipu-m2000 https://www.graphcore.ai/products/bow-pod |
| RTX 4090 | NVIDIA | 24 GB | 82.6 | Q4 2022 | Ada Lovelace | 16384 CUDA cores | N/A (consumer GPU) | 24 GB | Consumer flagship | https://www.nvidia.com/en-us/geforce/graphics-cards/40-series/rtx-4090/ |
| RTX 3090 Ti | NVIDIA | 24 GB | 40 | Q1 2022 | Ampere | 10752 CUDA cores | N/A (consumer GPU) | 24 GB | Previous gen flagship | https://www.nvidia.com/en-us/geforce/graphics-cards/30-series/rtx-3090-3090ti/ |
| RX 7900 XTX | AMD | 24 GB | 61 | Q4 2022 | RDNA 3 | 6144 stream processors | N/A (consumer GPU) | 24 GB | AMD consumer flagship | https://www.amd.com/en/products/graphics/amd-radeon-rx-7900xtx |
| Arc A770 | Intel | 16 GB | 19.6 | Q4 2022 | Alchemist | 512 Xe cores | N/A (consumer GPU) | 16 GB | Intel's top consumer GPU | https://www.intel.com/content/www/us/en/products/sku/227957/intel-arc-a770-graphics-16gb/specifications.html |

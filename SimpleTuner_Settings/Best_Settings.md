# SimpleTuner Best Settings

Based on a Reddit discussion, the following settings are recommended for SimpleTuner when using a 4090 GPU for Flux-based training:

## config.env settings:
- LEARNING_RATE=1e-4
- TRAIN_BATCH_SIZE=6
- GRADIENT_ACCUMULATION_STEPS=1
- VAE_BATCH_SIZE=2

## multidatabackend.json configuration:
- Resolution: 512x512
- Crop Style: Random
- Data Caching: Enabled

These settings are tailored for specific use cases and hardware configurations, such as the NVIDIA 4090 GPU. Adjustments may be needed based on different hardware or project requirements.

This project explores techniques for deploying large neural network models (SLMs) on resource-constrained edge devices like Microsoft's Phi-2. The focus is on improving the efficiency of SLMs through quantization and fine-tuning while maintaining accuracy.

Key Techniques:

Quantization: Reducing the bit-width of weights and activations in the SLM to lower memory footprint and computational cost. This project likely explores methods like Quantized Linear Operations Rounding Accumulation (QLORA) for achieving this.
Gradient Low-Rank Projection: Compressing gradients during the fine-tuning process to reduce communication overhead and improve training efficiency on edge devices.
Project Goal:

The overall objective is to enable efficient execution of SLMs on edge devices by:

Reducing model size through quantization.
Optimizing the training process for resource-limited environments using gradient compression techniques.
Benefits:

Enables deployment of powerful SLMs on edge devices with limited resources.
Reduces power consumption and latency for on-device inference.
Potential Applications:

Real-time image/speech recognition on mobile devices.
Low-power intelligent sensors in Internet-of-Things (IoT) applications.

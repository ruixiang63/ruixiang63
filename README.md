### Hi, I'm Ruixiang 👋 

I am Senior DevTech Engineer at NVIDIA.

### 🚀 Recent Open Source Contributions

#### [llama.cpp](https://github.com/ggml-org/llama.cpp)
 - [**#23869**](https://github.com/ggml-org/llama.cpp/pull/23869) — Speed-bench: standardized speculative decoding performance evaluation benchmark
 - [**#18039**](https://github.com/ggml-org/llama.cpp/pull/18039) — **Eagle3** speculative decoding: **1.2–3.28× speedup** across many model families
 - [**#22105**](https://github.com/ggml-org/llama.cpp/pull/22105) — **DFlash** speculative decoding: **up to 8× speedup** on Qwen3 models
 - [**#24536**](https://github.com/ggml-org/llama.cpp/pull/24536) - Add speculative decoding metrics for better observability and parameters tuning
 - [**#24655**](https://github.com/ggml-org/llama.cpp/pull/24655) - Support GPU-backend sampling to improve Eagle3 performance
 
#### [HuggingFace Transformers](https://github.com/huggingface/transformers)
 -  [**#45665**](https://github.com/huggingface/transformers/pull/45665) — Performance fix: eliminated implicit H2D copies in Gated DeltaNet

#### [Unsloth](https://github.com/unslothai/unsloth)
 - This NVIDIA-Unsloth [**blog**](https://unsloth.ai/blog/nvidia-collab) explains the following optimizations in detail.
 - [**#534**](https://github.com/unslothai/unsloth-zoo/pull/534) — Double-buffered checkpoint reload via CUDA streams + events, +8.4% on 8B, +6.7% on 14B fine-tuning speedup
 - [**#4173**](https://github.com/unslothai/unsloth/pull/4173) — Packed-sequence metadata caching, +14.3% fine-tuning speedup on Qwen3-14B QLoRA SFT
 - [**#535**](https://github.com/unslothai/unsloth-zoo/pull/535) — GPT-OSS MoE expert routing optimization, ~10-15% fine-tuning speedup on GPT-OSS models

### ✍️  Technical Writing — NVIDIA Developer Blog
Model Quantization Series:
1. [**Concepts, Methods, and Why It Matters**](https://developer.nvidia.com/blog/model-quantization-concepts-methods-and-why-it-matters/)
2. [**Post-Training Quantization Using NVIDIA Model Optimizer**](https://developer.nvidia.com/blog/model-quantization-post-training-quantization-using-nvidia-model-optimizer/)
3. [**Turn FP8 Checkpoints into High-Performance Inference Engines with NVIDIA TensorRT**](https://developer.nvidia.com/blog/model-quantization-turn-fp8-checkpoints-into-high-performance-inference-engines-with-nvidia-tensorrt/)
<!--
**ruixiang63/ruixiang63** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

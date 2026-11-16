# Aarush Agarwal

I'm a **6× hackathon winner** studying **Artificial Intelligence at Carnegie Mellon University** (SCS, class of 2027), focused on **ML systems, GPU performance, and adaptive models**. My work spans search relevance at Shopify, Mixture-of-Experts research at CMU, and C++/CUDA systems for graph construction and inference.

[Website](https://www.aarushagarwal.dev) · [Resume](https://www.aarushagarwal.dev/documents/Resume%20-%20Aarush%20Agarwal.pdf) · [LinkedIn](https://www.linkedin.com/in/aarush-agarwal-2751a61b1/) · [Email](mailto:aarusha@andrew.cmu.edu)

## What I'm working on

- **Shopify · ML Engineer Intern, Search Relevance** — Training and compressing query-rewriting models, improving search ranking, and optimizing GPU serving. Built a merchant-aware training objective that improved Shopify's Merchant Plus relevance metric by **10%**. Pruned and distilled **Qwen3.5-0.8B to 400M parameters** while maintaining production term F1, then optimized inference kernels to reduce benchmark latency by **~20%** versus Shopify's existing internal query-optimization engines.
- **CMU Language Technologies Institute · ML Researcher** — Researching adaptive multimodal **Mixture-of-Experts** architectures with Chenyan Xiong, including capacity expansion for out-of-distribution data and autonomous model-adaptation experiments.
- **Open-source ML systems** — Proposed fixes for FP8 GEMM benchmark cache/timing issues in [SGLang #50551](https://github.com/sgl-project/sglang/pull/50551) and Gated DeltaNet workspace sizing under CUDA MPS in [FlashInfer #9499](https://github.com/flashinfer-ai/flashinfer/pull/9499). Both are open pull requests.

Previously, I worked on **buyer-fraud ML at Shopify**, reducing training iteration time by **70%** and co-filing a patent on a Neo4j-based multi-agent execution system.

## Selected work

### [FastGraph](https://www.aarushagarwal.dev/projects/FastGraph) · Exact GPU nearest-neighbor search

First author of the FastGraph paper. Developed PCA-subspace pruning and rewrote selected C++/CUDA kernels, building on Jan Kieseler's original implementation. The evaluated system achieved **41× speedup over exact FAISS-GPU** on an HGCAL-derived workload: **5M points, 8 dimensions, 40 neighbors, A100 80 GB**.

[Code](https://github.com/AgarwalAarush/FastGraphCompute) · [Paper](https://github.com/AgarwalAarush/fastgraph-paper/blob/869f9d41277c75000f51e968ac5abe655a20b9d7/Paper.pdf) · [Benchmarks & approach](https://www.aarushagarwal.dev/projects/FastGraph)

### [AutoReflex](https://www.aarushagarwal.dev/projects/AutoReflex) · Vision meets real-time control

**3rd place, Hackberry Pi.** Connected **100 FPS** vision on a Jetson Orin Nano to a Raspberry Pi **1 kHz PID** control loop over UDP, with approximately **30 ms** camera-to-actuation latency.

[Code](https://github.com/beeler-devs/HackberryPi) · [Demo & architecture](https://www.aarushagarwal.dev/projects/AutoReflex)

### [Haven](https://www.aarushagarwal.dev/projects/Haven) · Multi-agent hospital intelligence

**CalHacks 12.0: YC & Fetch.AI track wins and Best Startup.** Built backend agent infrastructure, an OpenCV/FastICA rPPG heart-rate pipeline, and real-time voice intake with LiveKit and Groq.

[Code](https://github.com/scrappydevs/haven) · [Demo & architecture](https://www.aarushagarwal.dev/projects/Haven)

More builds: [Mimir — AI tutoring](https://www.aarushagarwal.dev/projects/Mimir) · [Medicly — physical therapy feedback](https://www.aarushagarwal.dev/projects/Medicly) · [Yumi — group dining agents](https://www.aarushagarwal.dev/projects/Yumi)

## Tools & interests

**Python · C++ · CUDA · PyTorch**  
Model compression and distillation · GPU inference · Mixture-of-Experts · Search ranking · Geometric deep learning

# Jisha Rajala

Computer Science student focused on machine learning from first principles, with research interests in reasoning capabilities, mathematical logic, and transformer interpretability.

My approach combines building architectures from scratch to understand the fundamentals with leveraging state-of-the-art models to push reasoning boundaries.

## Core Projects

### LLM Attention Kernels From Scratch
**C++, ARM NEON SIMD, Flash Attention, Memory Optimization**

Complete attention kernel suite implemented from scratch with zero dependencies. Features Flash Attention with online softmax, custom SIMD vectorization, sliding-window KV cache with INT8 quantization, and production-grade memory optimization patterns.

- Engineered Flash Attention with 2D tiling achieving O(N) memory complexity
- Built hybrid attention pipeline with forward-looking eviction and sink tokens
- Implemented ARM NEON vectorization and custom thread pool parallelization
- Designed type-safe quantization system reducing memory footprint by 50%

### Nano-Reason: Inference-Time Scaling Engine
**Python, PyTorch, MCTS, LLM Evaluation**

System 2 reasoning framework enabling small language models to solve complex mathematical problems through test-time compute scaling.

- Implemented Monte Carlo Tree Search with Upper Confidence Bound for reasoning path exploration
- Designed verifier mechanism using reward functions to prune incorrect logic
- Demonstrated emergent reasoning capabilities on problems baseline models failed zero-shot
- Built upon Qwen2.5-Math-1.5B-Instruct to study reasoning in sub-2B parameter models

### GPT-2 From Scratch
**Python, PyTorch, Deep Learning**

Ground-up implementation of GPT-2 architecture (124M parameters) to master transformer engineering.

- Implemented Causal Self-Attention, Multi-Head Attention, and MLP blocks manually
- Built custom training loops and data pipelines without high-level abstractions
- Integrated RoPE and RMSNorm achieving 15% faster convergence vs standard LayerNorm
- Achieved sub-1.5 perplexity on TinyShakespeare within 500 training steps

## Systems Engineering

Strong ML engineering requires understanding the underlying infrastructure. Built low-level systems to master the foundation:

**Protocol Implementations**: HTTP server with raw socket handling, BitTorrent client with peer-to-peer protocols, Redis-like in-memory server
**Neural Network Foundations**: Micrograd backpropagation engine, loss surface analysis, gradient mechanics exploration

## Research Interests

- **Reasoning Priors**: Inducing stronger logic and Chain-of-Thought in smaller parameter spaces
- **Transformer Interpretability**: Understanding attention mechanisms and reasoning capabilities
- **Neuro-AI Alignment**: Exploring biologically plausible learning paradigms beyond backpropagation
- **Embodied AI**: Applying reasoning models to physical control systems

## Contact

**LinkedIn**: [linkedin.com/in/jisha-rajala](https://www.linkedin.com/in/jisha-rajala/)
**Email**: jisharajala@gmail.com

Actively seeking collaboration opportunities in reasoning-centric ML and robotics research.

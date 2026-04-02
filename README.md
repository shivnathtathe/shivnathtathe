<h1 align="center">Shivnath Tathe</h1>
<h3 align="center">Independent AI Researcher | 4-bit Neural Networks | Training LLMs from Scratch</h3>
<p align="center">
  <a href="https://arxiv.org/abs/2603.13931">arXiv</a> •
  <a href="https://zenodo.org/records/15272894">Zenodo</a> •
  <a href="https://scholar.google.com/citations?user=8E2rsVoAAAAJ">Google Scholar</a> •
  <a href="https://linkedin.com/in/shivnath-tathe-919985233">LinkedIn</a> •
  <a href="https://huggingface.co/shivnathtathe">HuggingFace</a>
</p>

---

### About

I'm Shivnath Tathe, a Software Engineer at ISG eSolutions and an independent AI researcher from India. I work on training neural networks at extremely low precision, proving that 4-bit quantized models can match full-precision accuracy without expensive GPUs.

My first paper on arXiv demonstrates training a convolutional network from scratch at true 4-bit precision on a standard CPU, achieving 92.34% on CIFAR-10 with 8x memory compression. I'm currently building T4NT, a 1.5B parameter multilingual Indian language model trained from scratch on 10 languages using 4-bit quantization-aware training with tanh soft clipping.

I believe powerful AI should not require powerful hardware.

---

### Publications

| Paper | Venue | Links | Year |
|------|------|------|------|
| LACE: Loss-Adaptive Capacity Expansion for Continual Learning | arXiv (cs.LG) | [Paper](https://arxiv.org/abs/2603.13931) | 2026 |
| True 4-Bit Quantized Convolutional Neural Network Training on CPU: Achieving Full-Precision Parity | arXiv (cs.LG) | [Paper](https://arxiv.org/abs/2603.13931) · [Code](https://github.com/shivnathtathe/true-4bit-training) | 2026 |
| Autonomous Tool-Creation in AI Agents: A Conceptual Framework for Self-Evolving Systems | Zenodo | [Paper](https://zenodo.org/records/15272894) · [Code](https://github.com/shivnathtathe/AgentForge) | 2025 |

---

### Research

**4-bit Quantization-Aware Training**
- Trained VGG-style networks at true 4-bit precision from scratch using symmetric quantization + straight-through estimators
- 92.34% on CIFAR-10 (0.16% gap from full-precision) with 8x memory compression
- Validated on CIFAR-100 (70.94%) and on mobile (OnePlus 9R, 83.16% in 6 epochs)
- No specialized GPU kernels. Standard PyTorch on CPU.

**T4NT-1.5B** *(in progress)*
- Multilingual Indian LLM trained from scratch on 10 languages
- Architecture: RMSNorm + RoPE + SwiGLU + 4-bit QAT + Tanh Soft Clipping
- Custom SentencePiece tokenizer (65K vocab) covering Devanagari, Bengali, Tamil, Telugu, Kannada, Malayalam, Gurmukhi scripts
- Training on Kaggle TPU v5e-8

---

### Projects

| Project | Description |
|---------|-------------|
| [true-4bit-training](https://github.com/shivnathtathe/true-4bit-training) | 4-bit QAT with tanh soft clipping — arXiv published |
| [DevShakti Offline RAG](https://github.com/shivnathtathe/DevShakti-APK) | React Native + GGUF, fully offline on-device LLM chatbot |
| [AgentForge](https://github.com/shivnathtathe/AgentForge) | LangChain/CrewAI agents that build their own tools |

---

### Tech

    Research : PyTorch, Quantization, QAT, STE, LoRA, PEFT
    Models   : llama.cpp, GGUF, HuggingFace Transformers
    Frontend : React Native, Angular, Electron
    Backend  : FastAPI, Node.js
    Infra    : Kaggle TPU, Google Colab, Linux

---

### Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=shivnathtathe&show_icons=true&theme=dark&hide_border=true" alt="GitHub Stats" />
</p>
<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=shivnathtathe&theme=dark&hide_border=true" alt="Streak Stats" />
</p>

---

<p align="center">
  <a href="https://arxiv.org/abs/2603.13931">arXiv:2603.13931</a> · 
  <a href="https://doi.org/10.5281/zenodo.15272894">DOI:10.5281/zenodo.15272894</a>
</p>

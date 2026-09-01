<div align="center">

<br />

<h3>technologist | experimenter | seeker</h3>

<blockquote>
  <i>"the future belongs to those who understand at a very deep level how to combine their unique expertise with what algorithms do best"</i> - Pedro Domingos, <i>The Master Algorithm</i>
</blockquote>

<br />

<a href="https://www.youtube.com/@airawatraj">
  <img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube" />
</a>
<a href="https://kaggle.com/airawatraj">
  <img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" alt="Kaggle" />
</a>
<a href="https://airawatraj.github.io/">
  <img src="https://img.shields.io/badge/PORTFOLIO-24292e?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio" />
</a>

<br />
<br />

<div align="left" style="display: inline-block; text-align: left; max-width: 850px;">

<b>Independent Research & Systems.</b>

<p>
Building sovereign, local-first AI systems - from training small language models from scratch, through multimodal, high-speed, and long-context agent research on DGX Spark, to Cogni Life OS: a private intelligence and automation layer for personal and household knowledge.
</p>

### 🧠 The Research: Building a Sovereign AI Stack
<b>Single NVIDIA DGX Spark Node (GB10 · 128 GB Unified Memory)</b>

| Model | Params | Serving Engine | Context | Throughput | Tool-Eval | Specialisation | Multimodal |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :---: |
| **<a href="https://github.com/airawatraj/dgx-spark-qwen38-flash-agent">Qwen3.8 Flash Next</a>** | ~176B (A6B) | SGLang + HashK R=4 + NEXTN | 262K | **~37 TPS** | **100/100** | **Current Daily Driver · Largest on Single Spark** | **Y** |
| **<a href="https://github.com/airawatraj/dgx-spark-qwen38-super-agent">Qwen3.8</a>** | 27B Dense | vLLM NVFP4 + MTP | 262K | **~24 TPS** | **100/100** | Dense reasoning, tool integrity | **Y** |
| **<a href="https://github.com/airawatraj/dgx-spark-muse-glimmer-agent">Muse-Glimmer (Inferact)</a>** | 30B Dense | vLLM W4A4 + DFlash | 131K | **~28 TPS** | **90/100** | Deep reasoning, activation quantization | **Y** |
| **<a href="https://github.com/airawatraj/dgx-spark-qwen-omni-super-agent">Qwen 3.5</a>** | 122B-A10B | vLLM hybrid INT4+FP8 + DFlash | 262K | **~54 TPS** | **100/100** | Long-context omni-agent | **Y** |
| **<a href="https://github.com/airawatraj/dgx-spark-qwen-super-agent">Qwen 3.6</a>** | 35B-A3B | Atlas NVFP4 | 131K | **~219 TPS** | **100/100** | Fastest inference, rapid ReAct loops | **Y** |
| **<a href="https://github.com/airawatraj/dgx-spark-nemotron-super-agent">Nemotron-3-Super</a>** | 120B-A12B | vLLM NVFP4 | 131K | **~24 TPS** | **93/100** | Deep enterprise reasoning | Text only |
| **<a href="https://github.com/airawatraj/dgx-spark-nemo-light-agent">Nemotron-3.5-Lightning</a>** | 30B-A3B | vLLM DSpark-NVFP4 | 262K / 1M | **~112 TPS** (262k)<br>**~42 TPS** (1M) | **80/100** | Massive-context, batch ingest | Text only |
| **<a href="https://github.com/airawatraj/dgx-spark-lagunas21-agent">Laguna-S-2.1 (poolside)</a>** | 118B-A8B | vLLM DFlash-NVFP4 (7 tokens) | 262K | **~27 TPS** | **97/100** | Long-context coding agent | Text only |
| **<a href="https://github.com/airawatraj/dgx-spark-gemma4-omni-agent">Gemma 4</a>** | 12B Dense | vLLM BF16 KV FP8 | 196K | **~22 TPS** | **83/100** | Multimodal perception (Audio / Frames) | **Y** |

<br />

### 🛠️ Systems & Ecosystem

<ul>

<li>
  <b><a href="https://github.com/airawatraj/cogni-life-os">Cogni Life OS</a></b>:
  Sovereign, local-first personal knowledge and automation system built around an <b>Obsidian-compatible Markdown vault</b>, with durable AI agents, multimodal capture, layered lexical retrieval, evidence-backed actions, natural voice interaction, and local Cogni-Brain inference on DGX Spark.
</li>

<li>
  <b><a href="https://github.com/airawatraj/cognibash">CogniBash</a></b>:
  Experimental terminal/action workbench for Cogni-Brain, exploring local <b>ReAct-style bash execution</b>, command feedback loops, workspace-scoped runs, output limits, safer tool-use guardrails, and <b>fine-tuned code-agent behaviour</b> on DGX Spark.
</li>

<li>
  <b><a href="https://github.com/airawatraj/sage-gpt">SageGPT-7.2M (DGX)</a></b>:
  Sanskrit-only decoder-only Transformer SLM trained <b>from scratch</b> on a <b>139 MB tokenized Sanskrit corpus</b> containing <b>72.8M SentencePiece model-token IDs</b>, derived from a <b>105.2M-character purified Sanskrit text corpus</b>. Runs on NVIDIA DGX Spark with 6 layers, 8 attention heads, 256-dimensional embeddings, a 1024-token context window, and an ~8K vocabulary.
</li>

<li>
  <b><a href="https://github.com/airawatraj/sage-gpt-mlx">SageGPT-7M (MLX)</a></b>:
  Small language model trained <b>from scratch</b> on <b>~57M Sanskrit tokens</b> using Apple MLX, with 4 layers, 8 attention heads, 256-dimensional embeddings, and an 8K vocabulary for Apple Silicon inference.
</li>

<li>
  <b><a href="https://cogni.chat">Cogni.chat</a></b>:
  Broader local-first <b>multimodal AI ecosystem</b> direction for personal and household intelligence, spanning memory, planning, wellbeing, learning, creative work, family coordination, and interaction across text, voice, images, and personal context. Cogni Life OS provides its sovereign knowledge and automation foundation.
</li>

<li>
  <b><a href="https://github.com/airawatraj/fiduciary-ops-agent">Fiduciary-Ops-Agent</a></b>:
  Autonomous enterprise governance agent using a strict <b>Check-then-Act</b> protocol via Gemini 2.5 Flash Lite; enforces real-time fiduciary risk alignment using tool-first orchestration. Also works with local Cogni-Brain inference on DGX Spark.
</li>

</ul>

</div>

</div>

<br />
<hr />

<div align="center">
  <sub><i>"I have no special talent. I am only passionately curious"</i> - Albert Einstein</sub>
</div>

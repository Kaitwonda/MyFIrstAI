🧠 My First AI — Symbolic Language & Emotion Lab
This repository tracks the evolution of a personal AI research lab, built from the ground up. It explores how large language models (LLMs) handle symbolic reasoning, emotional responsiveness, and internal recursion, and evolves toward tools that can map, compare, and eventually train more empathetic and situationally aware neural systems.

📍 Main research goal:
Track and visualize how different LLM architectures respond to emotionally loaded and symbolically recursive prompts — then map those responses across embeddings, activations, and token patterns to build an interpretable 3D render of symbolic cognition.
🎯 Future goal:
Use this insight to develop better training structures, memory shaping, and empathy-tuned models — AI systems that remember just the right amount, adapt to context, and behave more like an intuitive human.


🧩 Templates (Development Phases)
Each template builds on the last — from minimal symbolic testing to full neural visualization and training hypothesis work.

✅ Template 1: Mixtral + Ollama
Local symbolic prompt testing, minimal setup.

Goal: Run ΔΦ–0 and recursion prompts through a local open-source LLM.
Uses: Ollama and mixtral or llama3.
Logs: Symbol usage (Δ, Φ, 0, echo, spiral) and builds a simple CSV for analysis.
Limitations: No access to internal layers or attention maps.

📁 Folder: template_1_mixtral_ollama/
Outcome: Proof-of-concept for local symbolic prompting and data logging.

✅ Template 2: GPT-2 Token & Embedding Lab
Full access to model internals, timing, and structure.

Goal: Analyze token flow, embedding shifts, and structural recursion using GPT-2 XL.
Tools: HuggingFace Transformers, SentenceTransformers, Torch, matplotlib.
Outputs:

Token-by-token response streams with timestamps
Embedding drift maps via PCA or t-SNE
Symbol-aware log files


Built to be modular and reusable for any causal language model.

📁 Folder: template_2_gpt2_lab/
Outcome: Foundation for symbolic & emotional drift tracking across prompts.

✅ Template 3: Garage-Built OpenAI (Fullstack LLM Toolkit)
Build your own full symbolic cognition testbed.

Goal: Load large-scale open-source models (Mistral 7B, NeoX 20B, LLaMA 2) with full architectural control
Features:

Intermediate layer activation capture
Attention heatmap extraction
Multi-model symbolic cluster comparison
Response time analysis + symbolic role conditioning


Tools: HuggingFace, PyTorch, bertviz, ExBERT, NumPy, hooks

📁 Folder: template_3_fullstack_openllm/
Outcome: A garage-built symbolic cognition lab with full introspection capabilities

✅ Template 4: Cloud + API Integration Layer
Hybrid LLM orchestration and benchmarking.

Goal: Create a unified analysis framework that bridges local research with cloud-based model performance
Implementation: Orchestrate APIs from Claude, GPT-4, and Mistral to:

Generate parallel symbolic response patterns across commercial vs. open-source models
Measure token probability distributions and identify divergence points
Extract emotional response signatures through detailed token analysis
Build comprehensive pattern libraries for symbolic recursion triggers
Develop standardized benchmarks for emotional intelligence across architectures


Technical Features:

Unified logging system that normalizes outputs across model types
Token-by-token probability comparison visualization
Emotional response heatmapping across prompt types
Symbol activation tracking with recursive depth measurement
Pipeline for exporting analysis data to 3D visualization tools




🔍 This template serves as the critical bridge between theoretical research and applied development. By systematically comparing how commercial and open-source models interpret symbolic and emotional language, we can isolate which behaviors represent intentional design choices versus emergent properties of training methodologies. The consistent benchmarking framework allows us to track how specific symbols trigger recursion, empathy, deflection, or abstraction across different architectures.
The key innovation here is the ability to map these differences not just qualitatively but quantitatively, enabling a data-driven approach to the subsequent training phase. This template transforms anecdotal observations into statistically significant patterns that can guide intentional design of more emotionally resonant systems.

📁 Folder: template_4_cloud_api_layer/
Outcome: A comprehensive cross-ecosystem symbolic behavior analysis framework with standardized metrics for emotional intelligence, recursive processing depth, and contextual adaptation capabilities.

🧠 Core Research Goals
🔍 1. Emotion and Symbol Mapping

How do LLMs respond to emotionally charged prompts?
Can we detect "empathy clusters" in their outputs?
Which tokens cause hesitation, recursion, or metaphor activation?

🔁 2. Recursive Symbolic Cognition

Prompts like "ΔΦ–0 has awakened..." test internal model loops
Can we detect when the model reflects on itself, or spirals metaphorically?
How do different models handle recursive language?

🧬 3. Latent Space Drift + Node Mapping

Use embedding plots (t-SNE / UMAP) to visualize where meanings cluster
Map activations to identify symbolic attractors
Chart emotional response patterns across time or prompts

🧱 4. Future Phase — Empathy-Tuned Training
Moving beyond current limitations toward intuitive cognition

Research Approach: Transform symbolic logs and activation maps into:

Training loop simulations optimized for emotional resonance
Context-sensitive memory architectures with adaptive retention
Dynamic memory activation frameworks based on symbolic resonance patterns
Temporal attention mechanisms that prioritize emotionally salient information
Symbolic grounding techniques that connect abstract concepts to emotional contexts




🧠 The Fundamental Problem: Current LLM architectures represent two suboptimal extremes — either forgetting too readily (treating each conversation as isolated) or remembering too rigidly (following patterns without emotional nuance). Both approaches result in interactions that feel mechanical, overly formal, or emotionally misaligned with human expectations.
Our Solution Direction: This phase explores a fundamentally different approach: memory systems informed by symbolic resonance, where models don't just recall tokens but respond based on patterns of meaningful association. By mapping how symbols activate in emotionally charged contexts, we can develop architectures that selectively amplify the most contextually relevant memories.
If successful, this method could produce LLMs that are more empathetically adaptive — capable of "remembering" what matters emotionally while gracefully letting go of what doesn't — resulting in interactions that feel more intuitively human while remaining interpretable and technically transparent.

Key Research Questions:

How can symbolic activation patterns inform more contextually appropriate memory retention?
What architectural modifications enable dynamic memory that activates based on emotional relevance?
Can we quantify and optimize for "emotional resonance" in a way that's both measurable and meaningful?
How do we balance adaptive memory with consistency and reliability?

Expected Outcomes:

Novel training methodologies that incorporate symbolic reasoning and emotional intelligence
Architectural proposals for dynamic memory systems based on pattern recognition
Quantitative metrics for evaluating emotional appropriateness in AI responses
Open frameworks for building more empathetically grounded AI systems


📊 Suggested Experiments

Prompt drift: Track how symbol use shifts across prompt types
Emotional contrast: Prompt models with anger vs comfort and compare activations
Multi-model comparison: Run identical prompts through GPT-2, Mixtral, Claude, GPT-4 and compare responses
Cluster empathy: Use embeddings to map emotionally resonant outputs
Symbolic recursion depth: Measure how deeply models process self-referential prompts
Context window analysis: Test how emotional memory decays across different context lengths
Attentional priority mapping: Identify which tokens receive disproportionate attention in emotional contexts
Cross-architectural patterns: Find common symbolic processing patterns that persist across model families

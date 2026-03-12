# Hey, I'm German

Software engineer based in New York, building things with TypeScript, React, and AI.

Currently in the Fractal Residency program — here's what I've been shipping:

## Projects

### [Context Arena](https://context-arena.vercel.app/) · [GitHub](https://github.com/TheGermanAZ/context-arena)
A research platform that benchmarks what LLMs forget when context windows fill up. Tests 21 memory compression strategies across 8 stress-test scenarios, discovering a novel "Quantity-Pinning Buffer" approach that achieves 96.8% retention and 88% accuracy.

### [Pocket Empires](https://claude-game-ruby.vercel.app/)
A Civilization-lite 4X strategy game built with PixiJS. Features 5 victory conditions (exploration, territorial, scientific, religious, score), a 9-tech research tree across 3 tiers, 3 AI opponent personalities, culture-based territory pressure, full diplomacy with trade routes and alliances, 3 foundable religions with spreading mechanics, and procedurally generated maps — all on a clean engine/scene architecture where game logic is fully decoupled from rendering.

### [Finetune Personas](https://github.com/TheGermanAZ/finetune-personas)
An end-to-end LLM fine-tuning pipeline that generates synthetic persona training data with Claude, fine-tunes Qwen3-1.7B using LoRA on Apple Silicon via MLX, and exports to GGUF for local inference. Trained a Yoda persona model on 100 synthetic examples in 600 iterations.

### [Corporate Clash](https://corporate-clash-production.up.railway.app/) · [GitHub](https://github.com/TheGermanAZ/corporate-clash)
A multiplayer real-time strategy game where players build corporate offices, hire employees, and attack rivals. Features dynamic economic systems, random disaster events (tariffs, return-to-office mandates, intern deletes the database), and RISK-style combat via Server-Sent Events.

### [Yoda Evals](https://github.com/TheGermanAZ/yoda-evals)
A multi-method evaluation framework that benchmarks fine-tuned vs. baseline models across 20 test cases. Combines heuristic scoring, LLM-judge absolute scoring (Claude 3.5 Sonnet), and randomized A/B comparative evaluation with bias mitigation — then synthesizes all three into a unified analysis.

### [Train Shakespeare Model](https://github.com/TheGermanAZ/train-shakespeare-model)
A character-level GPT built from scratch in PyTorch — 10.8M parameter transformer trained on Shakespeare's complete works. Implements multi-head self-attention, positional embeddings, and autoregressive generation across 6 transformer blocks, with Apple Silicon MPS acceleration.

### [Manifest Journal](https://github.com/TheGermanAZ/manifest-journal)
A daily journaling web app that coaches users toward their dream life by analyzing their writing with AI. Built on TanStack Start with a Convex backend and Claude integration.

### [Chatbot](https://github.com/TheGermanAZ/chatbot)
A full-stack AI chat app with Claude-powered streaming responses, recursive document analysis (RLLM), and multi-provider auth. Built with React 19, Express 5, and Supabase.

### [LocalLLM](https://github.com/TheGermanAZ/localllm)
A benchmarking tool that compares LLM inference performance across three deployment strategies: local (LM Studio), managed cloud (Groq), and self-hosted (Modal + vLLM on A10G GPUs). Measures tokens/second and calculates speedup ratios using a standardized prompt via LiteLLM.

### [Tic Tac Toe](https://github.com/TheGermanAZ/tic-tac-toe-german)
Multiplayer tic-tac-toe with ELO ratings, 5 AI difficulty levels via minimax, WebSocket real-time gameplay, and OpenTelemetry observability instrumentation.

## Stack

`TypeScript` `React` `Bun` `Vite` `PixiJS` `TanStack` `Tailwind` `Supabase` `Convex` `Claude API` `Python` `PyTorch` `MLX` `Modal` `vLLM`

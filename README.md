## Mapping Spoken Language to Deterministic Execution Vectors: A Robust NLP Approach to Real-Time Voice User Interfaces

While prior work in Voice User Interfaces (VUIs) heavily relies on rigid keyword matching or generalized LLM API calls, such approaches suffer from high latency and low tolerance for live acoustic transcription errors. This paper introduces a novel, low-latency end-to-end framework that maps unstructured, live-transcribed speech directly into deterministic macro execution sequences.

The core novelty lies in our application-specific orchestration: we couple a live OpenAI Whisper stream with a domain-optimized MacBERT architecture. By leveraging MacBERT's inherent masked-language correction capabilities, our system uniquely bridges the gap between colloquial speech imperfections and frame-perfect application control within the nes-py environment. This constitutes a novel application of robust NLP architectures for real-time, zero-shot software execution mapping.

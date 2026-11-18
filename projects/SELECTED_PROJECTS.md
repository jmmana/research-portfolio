# Selected projects

## BoneAgeTW2

**Repository:** https://github.com/jmmana/BoneAgeTW2

**Context:** Master's research in Artificial Intelligence, Universidad de La Salle.

**Problem:** connecting image-based skeletal maturation assessment with structured, bone-level outputs using the Tanner–Whitehouse 2 framework.

**Documented approach:** a YOLOv8 localization stage, an EfficientNet-B3 maturation classifier and a scoring/reporting layer. The project also documents fallback behavior when trained weights are unavailable.

**Current evidence:** public code and architectural documentation. This overview does not certify the completion of training or clinical validation.

**Evaluation priorities:** distinguish original data, annotated subsets and test cases; separate pseudo-labels from expert reference labels; prevent patient leakage across splits; report the detector, stage classifier and final age estimate separately; identify prior-based outputs explicitly.

## enterprise-rag

**Repository:** https://github.com/jmmana/enterprise-rag

**Problem:** grounding answers in a controlled document collection.

**Documented approach:** local retrieval and generation with LlamaIndex and Ollama, accompanied by an evaluation setup.

**Research relevance:** retrieval quality, grounded answers, abstention and evaluation design. Results from a small collection should be interpreted at the scale of that collection.

## llm-serving-benchmark

**Repository:** https://github.com/jmmana/llm-serving-benchmark

**Problem:** understanding the difference between sequential model calls and a serving engine under a specified workload.

**Current evidence:** the repository documents a Transformers baseline and a vLLM path with hardware/dependency limitations. It does not support claiming an executed head-to-head comparison where a path could not run.

**Research relevance:** controlled workloads, throughput/latency measurement and transparent reporting of execution limits.

## Additional research directions

I also work on natural-language-to-SQL and quantitative prioritization of automation opportunities. Public research artifacts and bibliographic records will be added when a shareable implementation, contribution statement and verified publication record are available.

### what is fine tuning

* Process of adapting a pretrained language model to perform specific tasks
* It involves training the parameters of a pre-existing LLM on domain-specific data
* `**Catastrophic forgetting**` - LLM forgets the previous knowledge while learning from new dataset, this usually happens during fine-tuning of all or some parameters of the LLM.

### Important tuning parameters to consider

* Batch size
* Epochs
* Iteration
* Learning rate

### Types of fine Tuning

- **In-context fine-tuning**
  - Partial fine-tuning
    - BitFit
    - Diff Pruning
    - LT-SFT
- **Retrieval-augmented generation (RAG)**

## Parametric fine-tuning
- **Parametric efficient fine-tuning (PEFT)**
  - Additive fine-tuning
    - Prompt tuning
    - P-tuning
    - Prefix tuning
- **Full fine-tuning**
- **Reparameterized fine-tuning**
  - LoRA
  - QLoRA
  - KronA


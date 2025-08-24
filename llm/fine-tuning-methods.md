### what is fine tuning

* Process of adapting a pretrained language model to perform specific tasks
* It involves training the parameters of a pre-existing LLM on domain-specific data
* **`Catastrophic forgetting`** - LLM forgets the previous knowledge while learning from new dataset, this usually happens during fine-tuning of all or some parameters of the LLM.

### Important tuning parameters to consider

* Batch size
* Epochs
* Iteration
* Learning rate

### Types of fine Tuning

### Non-parametric fine-tuning
It is the type that works by passing the task-specific data as a context without training any parameters of the model

- **In-context fine-tuning**
  - Partial fine-tuning
    - BitFit
    - Diff Pruning
    - LT-SFT
- **Retrieval-augmented generation (RAG)**

## Parametric fine-tuning
It is the type that works by fine-tuning the model’s parameters on task-specific datasets. It can be the training of all the parameters of the model or training only a few parameters by freezing the rest of the parameters of the model.

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

* **`Freezing`** refers to keeping certain parameters of the model unchanged during fine-tuning, allowing them to retain their pre-trained knowledge without being updated or modified.

This document explains every column used in the metadata corpus in simple, clear language. Each field was chosen to capture the essential technical characteristics of modern Large Language Models (LLMs).

1. Model

The official name of the model (e.g., BERT, RoBERTa, GPT-3).
Used to uniquely identify each system.

2. Year

The year the model was released or publicly documented.
Helps build an accurate timeline of LLM progress.

3. Architecture_Family

The structural design of the model.
Includes:

Encoder-only (e.g., BERT) — best at understanding text

Decoder-only (e.g., GPT) — best at generating text

Encoder–decoder (e.g., T5) — best at translation and sequence tasks

This field shows how model design impacts capability.

4. Parameters

The total number of learned weights inside the model (e.g., 110M, 7B, 175B).
Represents the model’s capacity and memory footprint.

5. Pretrained_Data_Scale

The amount of data used during training (e.g., tokens, documents, TB of text).
Larger datasets usually lead to stronger generalization.

6. Modality

The type of input the model accepts, such as:

Text

Text + Vision

Text + Audio

Multimodal

Used to classify which senses the model can operate in.

7. Reported_Compute

The total compute used to train the model (often expressed in FLOPs).
This reflects training cost, sustainability, and hardware demands.

8. Weight_Size_Bytes

The size of the final trained model on disk (MB/GB).
Shows storage requirements and deployment constraints.

9. Training_Duration

How long the model was trained (e.g., days, weeks).
Gives insight into compute efficiency and resource planning.

10. Hardware_Specs

Key details about the hardware used during training, such as:

GPU/TPU type

number of accelerators

cluster configuration

Relevant for reproducibility and compute benchmarking.

11. Context_Learning

Indicates whether the model supports:

zero-shot

few-shot

in-context learning

Helps categorize emergent reasoning behaviour.

12. Citation

The main source(s) used for the model entry (e.g., official paper, report).
Ensures traceability and academic correctness.
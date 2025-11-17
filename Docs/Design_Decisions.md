This document outlines the key choices made during the construction of the metadata corpus, taxonomy, and analytical framework. Each decision was selected to maximize clarity, reproducibility, and usefulness for future research.

1. Model Selection

Only models with popularity and publicly available, verifiable technical details were included. Priority was given to models with official research papers, documented parameter counts, and confirmed release timelines. This ensured consistency across entries and eliminated speculative data.

2. Core Attributes Included

The metadata table focused on attributes that directly influence model capability and resource requirements:

year of release

architecture family

parameter count

training data scale

modality

compute estimates

hardware notes

context-learning ability

These fields were chosen because they represent the most stable, comparable indicators across LLM generations.

3. Taxonomy Structure

Models were grouped using three classification angles:

Architecture type (encoder-only, decoder-only, encoder–decoder)

Parameter scale (small, medium, large, XL)

Modality (text-only, multimodal)

This structure was selected because it reflects how modern LLMs fundamentally differ in design and application.

4. Source Priority Rules

When model values conflicted across sources, the following hierarchy was applied:

peer-reviewed conference/journal papers

original arXiv preprints

official developer blogs or technical reports

secondary analyses

This ensured reliability while preserving transparency.

5. Exclusions

Models lacking sufficient technical disclosure were excluded to avoid introducing noise. Experimental, unreproducible, or proprietary-only models were also omitted.

6. Reproducibility Standard

All decisions were intentionally made to allow another researcher to recreate the dataset, taxonomy, and timeline using the same public sources. The goal was to keep the workflow simple, transparent, and technically defensible.
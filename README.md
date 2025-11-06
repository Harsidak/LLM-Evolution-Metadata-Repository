This repository contains the metadata corpus, taxonomy files, and scripts used in the research paper:
“From Transformer to GPT-5: Advancements, Limitations, and Future Directions in Large Language Model Design.”

It provides reproducible data and code supporting the systematic analysis of Large Language Models (LLMs) from 2017 to 2025, covering architectural evolution, scaling trends, and taxonomy mapping.

📁 data/
 ┣ 📄 metadata.csv                → Core dataset of model attributes
 
 ┣ 📄 taxonomy.csv                → Architecture-family mapping
 ┗ 📄 raw_records.csv             → Initial extracted records

📁 scripts/
 ┣ 📄 extract_metadata.py         → Script for metadata cleaning
 ┣ 📄 compute_trends.py           → Generates parameter-growth plots
 ┗ 📄 taxonomy_builder.py         → Rule-based taxonomy construction

📁 figures/
 ┣ 📊 timeline_fullwidth.svg      → Historical timeline figure
 ┗ 📈 params_vs_year.png          → Parameter scaling plot

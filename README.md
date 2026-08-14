# Awesome Turkish Datasets 🇹🇷

A curated catalog of datasets for Turkish across language, speech, vision, and multimodal AI.

Links in **Description** lead to a dataset's canonical source — an official dataset card, repository, catalog record, or project page. **Download** points at the data itself where a direct location is known.

**Size** is the stored data volume; **Scale** is the published count of rows, samples, sentences, hours, or images. For multilingual datasets the Turkish portion is reported whenever it could be isolated: a scale written as `601,734 total; 14,327 Turkish` means only the second figure is Turkish. A size marked *(all languages)* covers every language in that repository, not Turkish alone, and a size marked `~ … (GitHub repo)` is repository size including version history.

**A dash (—) means the value could not be verified from an authoritative source.** No cell in this catalog is estimated, inferred, or filled in because it looked plausible. See [METHODOLOGY.md](METHODOLOGY.md).

Catalog last reviewed: August 2026.

**20 datasets** — 20 text/NLP.

## Text, NLP & LLM

| Released | Dataset | Description | Download | Size | Scale | Task | License | Access |
|---|---|---|---|---:|---:|---|---|---|
| 2026-07-10 | Conversation Prompt Injection | [Prompt-injection attacks in Turkish conversations (dataset card)](https://huggingface.co/datasets/3nesdeniz/turkish-conversation-prompt-injection) | [Files](https://huggingface.co/datasets/3nesdeniz/turkish-conversation-prompt-injection/tree/main) | 44.1 KB | 750 rows | LLM Safety Classification | CC BY 4.0 | Open |
| 2026-05 | Bilge-Turkish-CoT-50K | [Chain-of-thought reasoning examples, 50K samples (dataset card)](https://huggingface.co/datasets/bugrabilge/Bilge-Turkish-CoT-50K) | [Files](https://huggingface.co/datasets/bugrabilge/Bilge-Turkish-CoT-50K/tree/main) | 815.2 MB | 50K examples | Question Answering; Reasoning; Text Generation | Gemma Terms of Use | Open |
| 2026-01 | FineTranslations | [Machine-translated parallel text, 500+ languages (dataset card)](https://huggingface.co/datasets/HuggingFaceFW/finetranslations) | [Files](https://huggingface.co/datasets/HuggingFaceFW/finetranslations/tree/main) | 406 GB | 58,171,145 Turkish rows | Machine Translation / Cross-lingual | ODC Attribution | Open |
| 2025-10 | Global PIQA Non-Parallel | [Hand-built commonsense reasoning benchmark, 100+ languages (dataset card)](https://huggingface.co/datasets/mrlbenchmarks/global-piqa-nonparallel) | [Files](https://huggingface.co/datasets/mrlbenchmarks/global-piqa-nonparallel/tree/main) | 136 KB | 100 Turkish rows | Benchmarking | CC BY-SA 4.0 | Open |
| 2025 | SentiTurca | [Movie, e-commerce and hate-speech reviews (dataset card)](https://huggingface.co/datasets/turkish-nlp-suite/SentiTurca) | [Files](https://huggingface.co/datasets/turkish-nlp-suite/SentiTurca/tree/main) | 70.4 MB | 234,345 labeled rows across e-commerce, movie, and hate-speech subsets | Sentiment Analysis; Hate Speech Classification | CC BY-SA 4.0 | Open |
| 2025 | TrGLUE | [Single-sentence and sentence-pair classification benchmark (dataset card)](https://huggingface.co/datasets/turkish-nlp-suite/TrGLUE) | [Files](https://huggingface.co/datasets/turkish-nlp-suite/TrGLUE/tree/main) | 181 MB | 813,313 rows across 8 Turkish language-understanding tasks | Turkish Language Understanding Benchmark | CC BY-SA 4.0 | Open |
| 2025 | HPLT2.0 | [Web-crawled multilingual text corpus (project page)](https://hplt-project.org/datasets/v2.0) | — | 21 TB deduplicated / 15 TB cleaned (all languages, v2.0) | 116.57 million Turkish documents, 51.67 billion Turkish words (cleaned; per HPLT paper arXiv:2503.10267) | Language Modeling | CC0 | Open |
| 2024-12 | FineWeb 2 | [Web pretraining data across 1000+ languages (dataset card)](https://huggingface.co/datasets/HuggingFaceFW/fineweb-2) | [Files](https://huggingface.co/datasets/HuggingFaceFW/fineweb-2/tree/main) | 125.5 GB (Turkish subset) | 95,129,129 Turkish documents; 41,933,799,420 Turkish words | Language Resource / Modeling | ODC Attribution | Open |
| 2024-11 | MedTurkQuAD | [Medical-domain question-answering pairs, Turkish (dataset card)](https://huggingface.co/datasets/incidelen/MedTurkQuAD) | [Files](https://huggingface.co/datasets/incidelen/MedTurkQuAD/tree/main) | 3.3 MB | 618 medical articles; 875 paragraphs; 8,200 QA pairs | Question Answering | CC BY-NC-ND 4.0 | Open |
| 2024-07 | InstructTurca | [Synthetic instructions from code, poems, medical texts (dataset card)](https://huggingface.co/datasets/turkish-nlp-suite/InstrucTurca) | [Files](https://huggingface.co/datasets/turkish-nlp-suite/InstrucTurca/tree/main) | 13.1 GB | ~2.58M examples | Instruction Tuning | CC BY-SA 4.0 | Open |
| 2024 | BellaTurca | [Turkish pretraining corpus collection (dataset card)](https://huggingface.co/datasets/turkish-nlp-suite/BellaTurca) | [Files](https://huggingface.co/datasets/turkish-nlp-suite/BellaTurca/tree/main) | 246.5 GB | 105,157,983 documents; 30.89 billion words across 5 subsets | Language Modeling | CC BY-SA 4.0 | Open |
| 2024 | Global-MMLU (Turkish) | [Multilingual knowledge benchmark, 42 languages (dataset card)](https://huggingface.co/datasets/CohereLabs/Global-MMLU) | [Files](https://huggingface.co/datasets/CohereLabs/Global-MMLU/tree/main) | 4.2 MB (Turkish subset) | Approximately 14.3k Turkish MMLU items; 42 languages overall | Multitask Knowledge Evaluation | Apache-2.0 | Open |
| 2022 | MASSIVE (Turkish) | [Intent and slot annotations across 51 languages (dataset card)](https://huggingface.co/datasets/AmazonScience/massive) | [Files](https://huggingface.co/datasets/AmazonScience/massive/tree/main) | 40.3 MB (Turkish subset) | 16,521 Turkish utterances: 11,514 train, 2,033 validation, 2,974 test; 60 intents and 55 slots | Intent Classification; Slot Filling | CC BY 4.0 | Open |
| 2020 | KeNet | [Turkish WordNet lexical database (repository)](https://github.com/StarlangSoftware/TurkishWordNet) | [Files](https://github.com/StarlangSoftware/TurkishWordNet/raw/master/src/main/resources/turkish_wordnet.xml) | ~ 379.5 MB (GitHub repo) | 77,330 synsets; 109,049 synset members; 80,956 distinct members | Lexical Semantics; Word Sense Processing | GPL-3.0 | Open |
| 2020 | MKQA (Turkish) | [Open-domain QA pairs across 26 languages (repository)](https://github.com/apple/ml-mkqa) | — | ~ 12.4 MB (GitHub repo) | 10,000 human-translated Turkish questions; 260,000 aligned question-answer examples across 26 languages | Open-Domain Question Answering | CC BY-SA 3.0 (dataset); Apache-2.0 (code) | Open |
| 2020 | MLSUM (Turkish) | [Multilingual text summarization corpus (repository)](https://github.com/ThomasScialom/MLSUM) | — | ~ 38 KB (GitHub repo) | 273,617 Turkish article-summary pairs: 249,277 train, 11,565 validation, 12,775 test | Summarization | Non-commercial research use; source copyrights retained | Open |
| 2020 | WikiLingua (Turkish) | [Abstractive summaries extracted from WikiHow (repository)](https://github.com/esdurmus/Wikilingua) | — | ~ 44 KB (GitHub repo) | 4,503 Turkish article-summary pairs; approximately 770k pairs across 18 languages | Summarization | CC BY-NC-SA 3.0 | Open |
| 2020 | XCOPA (Turkish) | [Multilingual causal commonsense reasoning tasks (repository)](https://github.com/cambridgeltl/xcopa) | [Files](https://huggingface.co/datasets/cambridgeltl/xcopa) | 185.3 MB (all languages) | 600 Turkish items: 100 validation and 500 test | Causal Commonsense Reasoning | CC BY 4.0 | Open |
| 2018 | TrMor2018 | [Morphological analysis data for Turkish (repository)](https://github.com/ai-ku/TrMor2018) | [Files](https://github.com/ai-ku/TrMor2018/tree/master/TrMor2018) | ~ 27.2 MB (GitHub repo) | 390 documents; 34,673 sentences; 460,669 morphologically analyzed tokens | Morphological Analysis; Disambiguation | MIT (repository); analyzer/FST permission caveat | Open |
| 2017-02 | turkish_ner | [Wikipedia sentences with NER and category tags (dataset card)](https://huggingface.co/datasets/erayyildiz/turkish_ner) | [Files](https://huggingface.co/datasets/erayyildiz/turkish_ner/tree/main) | 204.4 MB | 532,629 annotated examples | Named Entity Recognition | CC BY 4.0 | Open |

## Notes on the data

- **Release dates.** For datasets whose canonical source is a Hugging Face repository, the date is when the dataset was published there. An older original release may exist for corpora that were uploaded to Hugging Face later.
- **Turkish subsets.** A multilingual dataset is listed only when its Turkish portion can be identified — a dedicated Turkish split, config, or a reported Turkish count. Turkish-specific scale is preferred over the multilingual total wherever it could be established.
- **Licenses.** A license is recorded only when it applies to the dataset itself. Repository licenses covering shared documentation rather than data were not copied into this table.
- **Access.** `Open` means the data is publicly downloadable, `Gated` requires accepting terms or requesting access, and `Paid` means the distributor charges a fee.

## Contributing

Corrections are welcome, especially missing values and better canonical sources. The one rule is that every value must be traceable to an authoritative source — a blank cell is preferred over a plausible guess.

## License

The catalog text in this repository is available under CC BY 4.0. Each dataset carries its own license, listed above.

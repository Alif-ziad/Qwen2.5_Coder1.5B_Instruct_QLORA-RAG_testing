# Qwen2.5-Coder-1.5B-Instruct — QLoRA + RAG Testing

Evaluation-artifact repository for code-repair experiments using a QLoRA-tuned **Qwen2.5-Coder-1.5B-Instruct** model with retrieval-augmented generation.

## Published outputs

- `rag_full_results.csv` — completed evaluation results
- `rag_checkpoint.csv` — checkpoint/resume output from the run

The repository commit history records the RAG evaluation reaching **2,510 / 2,510** test samples.

## Purpose

This repository preserves experiment outputs rather than providing a standalone inference application. Use the CSV files for evaluation/audit work and the related training repository for adapter artifacts.

## Related training artifacts

[Qwen2.5_1.5B](https://github.com/Alif-ziad/Qwen2.5_1.5B)

## Reproducibility note

Any performance numbers reported from this repository should be calculated from the final CSV under the same evaluation protocol; intermediate checkpoint files should not be treated as separate final experiments.

## Author

MD Alif Ziad Sarkar — CSE, American International University-Bangladesh (AIUB)

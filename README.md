# t2v-splitter-bench

Reproducible inference and benchmark wrapper for Text2Video splitter experiments.

## Scope
- Clean inference examples
- Comparative benchmark runs for article figures/tables
- Reuse validated parts from historical repos with explicit provenance

## Historical sources
- Rotation_T2I_to_T2V (main technical base)
- Rotation_train_Text2Image_2_task_Tex2Video (historical research stage)
- MIPT_magistratura/Text2Video_project (early research + article context)

## Structure
- `src/` inference + reusable core modules
- `tests/` benchmark/regression scenarios
- `configs/` run profiles (quick/paper/ablation)
- `examples/` minimal runnable scenarios
- `docs/` migration, reproducibility, history
- `.control/` Oracle/Architect/Researcher workflow integration

## Artifact policy
Large models/datasets/videos/logs are not committed to git.
Use DVC/ClearML/external storage references.

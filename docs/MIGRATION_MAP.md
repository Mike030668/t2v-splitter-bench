# Migration Map

## Source of truth for reusable code
- Rotation_T2I_to_T2V: inference/test pipeline components

## Historical reference only
- Rotation_train_Text2Image_2_task_Tex2Video
- MIPT_magistratura/Text2Video_project

## Migration rules
1. Copy only runnable, minimal, testable components.
2. Keep provenance note for each migrated module.
3. Replace notebook-only flows with scripts/CLI where possible.
4. Do not migrate heavy artifacts into git.

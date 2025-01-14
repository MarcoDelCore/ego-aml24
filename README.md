# From Egocentric Videos to Textual Answers: A Two-Stage Pipeline for NLQ-Based Video QA

This repository contains the implementation and experiments for deriving textual responses to natural language queries in egocentric videos. The project focuses on evaluating models trained on the Ego4D Natural Language Queries (NLQ) benchmark and extends the task by generating textual answers using a two-step pipeline.

## Repository Structure

- **VSLNet/**: Original implementation of the VSLNet model for the NLQ task.
- **VSLNet_b/**: Modified version of VSLNet with separate encoders for video and text, designed to better capture their distinct characteristics.
- **VSLBase/**: Adaptation of VSLNet resulting in the VSLBase model.
- - **clip/**: Folder containing the 50 extracted video clips (in `.mp4` format) used in the final evaluation step.
- **ego_aml24.ipynb**: Colab notebook containing the complete code, including training, evaluation, and textual answer generation.
- **ground_truth.json**: Manually annotated ground truth file with queries and expected textual answers for the final evaluation step.

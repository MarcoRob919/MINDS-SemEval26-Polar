# MINDS-SemEval26-Polar
The official repository for the challenge POLAR @ SemEval-2026 Task 9 carried out by the MINDS team.

## About the repository
This repository contains the code and notebooks for the SemEval-2026 Task 9: "Detecting Multilingual, Multicultural and Multievent Online Polarization". The project investigates effective modeling strategies for online polarization analysis in a multilingual setting. We compared multiple approaches for each subtask by implementing and evaluating different model architectures, in order to assess their effectiveness under the same experimental setting.

## Project Structure

```text
├── Dataset/
│   ├── subtask-1/
│   │   ├── original/      # original data from the challenge
│   │   ├── translated/    # translated data for the architecture 2
│   ├── subtask-2/
│   │   ├── original/      # original data from the challenge
│   │   ├── translated/    # translated data for the architecture 2 and 3
├── Subtask-1/
│   ├── Architecture-1/    # XLM-RoBERTa_Base + XLM-RoBERTa_Large_LoRA_subtask1
│   ├── Architecture-2/    # MarianTranslate + DeBERTa_Base_subtask1
├── Subtask-2/
│   ├── Architecture-1/    # Two-Model-Cascade-Pipeline_subtask2
│   ├── Architecture-2/    # DeBERTa_Base_subtask2
│   ├── Architecture-3/    # LLaMa_q4bit
```

The file ‘XLM-RoBERTa_Base’ contains the training and evaluation of the model for both tasks. <br>
The file ‘MarianTranslate’ is used for Architecture-2 and Architecture-3. <br>
The file ‘LLaMa_q4bit’ contains the training and evaluation of the model for both tasks.

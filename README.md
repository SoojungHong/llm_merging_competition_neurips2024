# NeurIPS challenge :  llm_merging_competition_neurips2024
LLM Merging Competition: Building LLMs Efficiently through Merging

## Competition page 
https://llm-merging.github.io/index

## Starter kit 
https://github.com/llm-merging/LLM-Merging

## Background of the competition
specialized fine-tuned models can be rapidly merged to combine capabilities and generalize to new skills.

## Challenges description
- a list of expert models that have already been trained on a task-specific dataset. 
- All of these models will be publicly available on the Hugging Face Model Hub
- The goal of this competition is to re-use the provided models to create a generalist model that can perform well on a wide variety of skills
- skills are like reasoning, coding, maths, chat, and tool use. 
- a set of validation datasets to measure the time and space efficiency of the merging method. 
- validation datasets are not meant to benchmark the performance of the merging method.
- two sets of hidden tasks that will be used to evaluate the submissions from participants
- hidden test tasks : (1) a set of leaderboard ranking test tasks, and (2) a set of final ranking test tasks.

## Submission 
https://docs.google.com/forms/d/17TPg7N02o8qvw1czx55Zbh_5Kp7-YStUIOhQDJYc23g/viewform?edit_requested=true

## Rules (some of important ones)
- Submissions must take less than 1 hours to merge/fine-tune and evaluate on a single Nvidia A6000 (48 GB) or equivalent resource.
- Allowed Models
- Participants in the LLM-Merging competition are allowed to use any publicly available model weights that can be downloaded and fullfils the conditions.
- Specifically, the model should satisfy the following criteria:
- The model is publicly available on Hugging Face
- The model is uploaded before May 31st 2024
- The model’s parameter size is not larger than 8 billion This flexibility aims to encourage creativity and innovation in model merging techniques.
- To help participants get - started, we have provided a list of recommended models. (recommended models are in the competition page)

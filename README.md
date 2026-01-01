# Unsloth Fine Tuning Experiments
My experiments using Unsloth to fine tune LLMs. The goals are to learn the process and build intuition.

<br>

## Experiments

- Exp1 - Set up Kaggle Unsloth workflow<br>
https://github.com/vbookshelf/Unsloth-Fine-Tuning-Experiments/tree/main/Exp1%20-%20Set%20up%20Kaggle%20Unsloth%20workflow

- Exp2 - Set up Runpod Unsloth workflow<br>
https://github.com/vbookshelf/Unsloth-Fine-Tuning-Experiments/tree/main/Exp2%20-%20Set%20up%20Runpod%20Unsloth%20workflow


<br>

## Notes
- Fine tuning can be used to condition how the model responds to a given system message e.g. concise instead of verbose response, stop ending all responses with a question etc. This use-case requires less data (15 examples). The same system message that's used during fine tuning is also used during inference.
- Fine tuning can be used to get the model to respond in a specific way without using a system message. No system message is used during fine tuning and during inference. This requires around 500 data examples.


<br>

## Resources

- How to Fine-tune LLMs with Unsloth: Complete Guide<br>
Pookie<br>
https://www.youtube.com/watch?v=Lt7KrFMcCis

- Kaggle Notebook - Afrik-Stories - Gemma-2-9b fine-tuned - Afrikaans<br>
https://www.kaggle.com/code/vbookshelf/afrik-stories-gemma-2-9b-fine-tuned-afrikaans

- Unsloth Github Notebooks<br>
(Includes both Colab and Kaggle example notebooks)<br>
https://github.com/unslothai/notebooks/?tab=readme-ov-file

- Unsloth Notebooks (Website)<br>
https://unsloth.ai/docs/get-started/unsloth-notebooks




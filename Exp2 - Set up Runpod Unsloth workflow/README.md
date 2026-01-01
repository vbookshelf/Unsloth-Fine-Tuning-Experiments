## Notes
- To ensure there are no dependency errors, please select this Template when setting up the instance on Runpod:
  Fine-tuning Notebook by Trelis - Cu12.1 Py2.2.0<br>
  
- Be sure to edit the Template to allocate enough memory to save your fine tuned model.
- I did not use the Unsloth docker image that's available on Runpod. When using the Unsloth docker image I found that the fine tuned model could not be converted to gguf format using Unsloth - the code failed because of dependency issues.
- For this experiment I used the A40 GPU (48GB VRAM)

## Notes
- I loaded the gguf model created in Exp2 into my local Ollama setup. It runs fine.
- This is how I loaded the model into Ollama:<br>
1- Download the gguf file and Modelfile created on Runpod in exp2<br>
  2- cd into the folder containing the files<br>
  3- Type this command in the terminal (Mac): ollama create marisol-q4-k-m -f Modelfile<br>
  marisol-q4-k-m is the name I used. You can use any name.<br>
  4- The model will now appear in your list of local Ollama models and can be selected for inference. You'll need to use the system message that was used during fine tuning.

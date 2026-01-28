# tool-planning-fine-tuning


### pre-processing.ipynb
Contains the script to pre-process the data - 
1. Extract <plan> and <explain>. Drop rows where this cannot be extracted.
2. Convert into messages format for the fine-tuning

### fine-tuning-peft.ipynb
1. LoRA Script for finetuning on the pre-processed data

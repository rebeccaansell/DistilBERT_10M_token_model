# DistilBERT Model for BabyLM Challenge

The training for the model takes place in distilBERT.ipynb
- This notebook is configured for CUDA 12.4 support 
- Data can be downloaded from here: https://osf.io/ad7qg/
    - The data the model is trained on is in the text_data\train_10m folder
    - With more compute it can be trained on the text_data\train_100m folder
- Libraries needed: torch, torchvision, torchaudio, datasets, transformers, accelerate

An example of how to load the model is in loading_model.ipynb 


1. Download data
2. Install libraries
3. Run distilBERT.ipynb
4. Run loading_model.ipynb
5. For evaluation benchmarking -> go to final_model_for_eval

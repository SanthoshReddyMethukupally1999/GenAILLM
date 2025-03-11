Image__captioning using BLIP and Gradio
The image.py is a python file used for image captioning. the model used for image classification is BLIP. BLiP stands for Bootstrapped Language Image preloading.It is used for visual-language learning.
BLIP is primarily based on Vision Transformers (ViTs) and Large Language Models (LLMs). 
It uses a dual-stream encoder-decoder architecture, where:
Vision Encoder: A pre-trained Vision Transformer (ViT) extracts image features.
Text Encoder & Decoder: A Transformer-based LLM processes text input and generates captions.
It combines visual embeddings with language embeddings to improve contextual captioning and reasoning over images. 
Gradio is used for the user interface.

# Finetuning-TrOCR
📝 Handwritten Text Recognition using TrOCR
This project uses Microsoft's TrOCR model to recognize handwritten text from images.

📦 Features
Converts labeled image-text data into a Hugging Face Dataset

Preprocesses images and text using TrOCRProcessor

Trains the VisionEncoderDecoderModel on custom handwritten notes

Supports saving/loading finetuned models

Runs seamlessly on Kaggle or local setups

🚀 Quick Steps
Prepare data: A label.txt file with image_name<TAB>text and image folder

Convert to Dataset: Load data into a Hugging Face Dataset from Pandas

Preprocess: Use TrOCRProcessor to prepare pixel values and tokenized labels

Train: Use DataLoader and train the model with PyTorch

Save & Load: Save the best model with .save_pretrained() and reload later

🤖 Social Media Detector — ML Backup
Social Media Detector Backup is a dedicated machine learning repository containing trained models, model checkpoints, configuration files, and supporting resources used by the Social Media Detector application. The repository serves as a backup and reference source for managing different model formats required during development, testing, conversion, and application integration.

📁 Repository Contents
The repository may contain different types of machine learning and supporting files:
* .onnx – ONNX models for cross-platform inference and deployment.
* .safetensors – Safely stored model weights.
* .pt – PyTorch model/checkpoint files.
* .pth – PyTorch trained model weights/checkpoints.
* .bin – Binary model or supporting weight files.
* .json – Model configuration and metadata files.
* .txt – Supporting text, labels, vocabulary, or configuration files.
* .py – Python scripts used for model processing, testing, or conversion.

🎯 Purpose
This repository is intended to keep the Social Media Detector’s machine learning assets organized and backed up separately from the Android application. 
It can be used as a reference when preparing models for ONNX Runtime, Android integration, testing, or future model conversion.

🔄 Model Workflow
Training / Model Development
          ↓
    Model Checkpoint
          ↓
   Model Processing
          ↓
   Model Conversion
          ↓
     ONNX Model
          ↓
   Android Integration
          ↓
Social Media Detection

🧩 Model Integration
The trained model can be prepared and converted into a deployment-friendly format such as ONNX, which can then be integrated into the Android application for local machine-learning inference.

Python / PyTorch
       ↓
Model Weights
       ↓
Model Conversion
       ↓
    .onnx
       ↓
ONNX Runtime
       ↓
Android App
       ↓
Text Classification

⚠️ Note
This repository is primarily intended as a model backup and development resource. Individual files may serve different purposes depending on the model version, training stage, or conversion workflow.

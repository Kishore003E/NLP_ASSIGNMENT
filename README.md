# Medical Diagnosis with Attention Mechanism

This project leverages a Transformer-based NLP model (BERT) to identify critical symptoms in medical reports using attention scores. The attention heatmap helps visualize which terms the model focuses on, aiding in disease diagnosis.

## 🚀 Features
- ✅ Utilizes BERT for extracting attention weights  
- ✅ Visualizes attention heatmaps with seaborn  
- ✅ Analyzes how attention shifts with different medical symptoms  

## 🛠️ How It Works
1. **Input Medical Notes**: The model takes medical text as input.  
2. **BERT-based Attention Extraction**: Extracts attention scores from the final layer.  
3. **Attention Heatmap Visualization**: Highlights critical symptoms using seaborn heatmaps.  

## 📋 Sample Medical Notes Analyzed
- 🟢 Persistent cough, high fever, and difficulty breathing.  
- 🟡 Mild headache and occasional dizziness without fever or cough.  
- 🔴 Unexplained weight loss and night sweats.  

## 📦 Dependencies
- PyTorch  
- Transformers (Hugging Face)  
- Seaborn  
- Matplotlib  


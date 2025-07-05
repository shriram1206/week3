# E-Waste Classification System 🔄

A production-ready deep learning system for automated electronic waste classification using ensemble models and advanced computer vision techniques.

## 🚀 Quick Start

1. **Open**: `e_waste_classification_final_submission.ipynb`
2. **Run all cells** to train models and setup the system
3. **Launch interface**: Gradio web interface starts automatically
4. **Test**: Upload e-waste images for instant classification

## 🎯 Key Features

### 🤖 Advanced AI Models
- **Ensemble Learning**: 3 different architectures (EfficientNetV2B0, B1, ResNet152V2)
- **Hyperparameter Optimization**: Automated tuning with Optuna
- **Advanced Augmentation**: 7-layer image augmentation pipeline
- **Label Smoothing**: Improved generalization

### 📊 Professional Evaluation
- **Comprehensive Metrics**: Accuracy, F1-score, ROC curves
- **Model Interpretability**: Grad-CAM and LIME analysis
- **Interactive Visualizations**: Plotly-based dashboards
- **Cross-Validation**: Robust model validation

### 🌐 Production Deployment
- **Web Interface**: Ready-to-use Gradio application
- **API Ready**: Production-grade endpoints
- **Real-time Classification**: Instant results
- **Model Versioning**: Timestamped saves

## 📋 E-Waste Categories
10 types of electronic waste including smartphones, laptops, batteries, cables, circuit boards, and more.

## 🔧 Technical Specs
- **Input**: 224×224 pixels
- **Models**: Keras SavedModel format
- **Classes**: 10 e-waste categories
- **Framework**: TensorFlow/Keras + Gradio

## 📈 Performance
- **High Accuracy**: Ensemble approach for improved performance
- **Fast Inference**: Optimized for real-time classification
- **Interpretable**: Explainable AI features included

## 🛠️ Usage
```python
# Launch web interface
production_interface.launch()
# Access at: http://localhost:7860

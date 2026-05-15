# 🔍 Electronic Components ML

Modelo de Machine Learning para reconocer componentes electrónicos automáticamente a partir de imágenes, usando Transfer Learning con EfficientNetB0 y TensorFlow.

## 📸 Demo

![Matriz de confusión](matriz_confusion.png)
![Muestra del dataset](muestra_dataset.png)

## 🎯 Componentes detectados
| Componente | Precisión |
|------------|-----------|
| LED | 84% |
| Transistor | 71% |
| Diodo | 64% |
| Resistencia | 60% |
| Capacitor | 58% |

**Precisión global: 65%** con solo ~787 imágenes y sin GPU.

## 🛠️ Tecnologías
- Python 3.13
- TensorFlow 2.21
- EfficientNetB0 Transfer Learning
- OpenCV 4.13
- Gradio
- JupyterLab
- scikit-learn

## 🚀 Cómo ejecutarlo

### 1. Clonar el repositorio

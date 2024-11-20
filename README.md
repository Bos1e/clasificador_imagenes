
# Clasificador de Imágenes Básico - CIFAR-10

Este proyecto implementa un clasificador de imágenes utilizando el dataset CIFAR-10, con una arquitectura básica de redes neuronales convolucionales (CNN). Es ideal para aprender los fundamentos del procesamiento de imágenes y la clasificación utilizando **TensorFlow/Keras**.

---

## 📋 Requisitos

Antes de comenzar, asegúrate de tener instalados los siguientes paquetes:

- **Python 3.7+**
- **TensorFlow**
- **Numpy**
- **Matplotlib**

Para instalar las dependencias, utiliza:
```bash
pip install tensorflow numpy matplotlib
```

---

## 🚀 Cómo Usar el Proyecto

### **1. Entrenamiento del Modelo**
Ejecuta el archivo `train.py` para entrenar el modelo. Este código:
- Carga el dataset CIFAR-10.
- Entrena una red neuronal convolucional.
- Guarda el modelo entrenado como `cifar10_classifier.h5`.

```bash
python src/train.py
```

### **2. Predicciones**
Para realizar predicciones, ejecuta el archivo `predict.py`. Esto permite:
- Cargar el modelo entrenado.
- Realizar predicciones en imágenes del dataset o personalizadas.

```bash
python src/predict.py
```

### **3. Prueba en Google Colab**
Puedes ejecutar el proyecto directamente en Google Colab habilitando una GPU. Simplemente sube los archivos del proyecto al entorno de Colab y ajusta los pasos para entrenar o probar el modelo.

---

## 📂 Estructura del Proyecto

```plaintext
image_classifier/
├── README.md             # Descripción del proyecto
├── requirements.txt      # Dependencias necesarias
├── models/               # Modelos entrenados
├── notebooks/            # Experimentos opcionales
├── src/
│   ├── train.py          # Entrenamiento del modelo
│   ├── predict.py        # Predicciones con el modelo
│   ├── model.py          # Definición del modelo
│   └── utils.py          # Funciones auxiliares (opcional)
└── app.py                # Interfaz opcional con Streamlit
```

---

## 🎨 Visualizaciones

Durante el entrenamiento, el modelo genera gráficos para evaluar la precisión y la pérdida:

![Ejemplo de Gráfica](https://via.placeholder.com/800x400?text=Gráfica+de+Entrenamiento)

También puedes realizar predicciones en imágenes aleatorias del dataset:

**Ejemplo:**
![Imagen Predicción](https://via.placeholder.com/200?text=Imagen+Predicción)

---

## 🛠 Mejoras Futuras

1. **Transfer Learning:** Usa modelos preentrenados para mejorar la precisión.
2. **Interfaz Gráfica:** Agrega una interfaz visual con **Streamlit** para cargar imágenes personalizadas.
3. **Aumentación de Datos:** Implementa técnicas de data augmentation para mejorar la generalización.

---

## 💻 Contribuciones

¡Las contribuciones son bienvenidas! Si deseas mejorar el proyecto:
1. Realiza un fork del repositorio.
2. Crea una rama con tu mejora.
3. Haz un pull request.

---

## 📜 Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo `LICENSE` para más detalles.

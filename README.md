# Cusco-project
# 🧠 Asistente con Ollama – Interfaz de Chat Multimodal

Este proyecto proporciona una interfaz interactiva construida con [Streamlit](https://streamlit.io) que se conecta con el modelo LLM de **Ollama**. El asistente puede recibir entradas de texto, leer documentos PDF e interpretar imágenes para ofrecer respuestas contextuales y útiles.

---

## 🚀 Características principales

- ✅ **Chat en lenguaje natural** con modelo de lenguaje vía Ollama
- 📎 **Carga de archivos PDF o imágenes** como contexto adicional (JPG, PNG)
- 💬 **Historial de mensajes** y copia rápida de respuestas
- 🎨 **Diseño moderno y responsivo**
- 🌙 **Modo centrado o ancho** intercambiable
- 🧠 **Respuestas enriquecidas** con Markdown (listas, código, etc.)
- 📋 **Botón de copiar respuesta al portapapeles**
- 🖥️ Listo para ejecutar en [Streamlit Cloud](https://streamlit.io/cloud)

---

## 🛠️ Estructura del proyecto

asistente-ollama/
│
├── app.py ← archivo principal de la app Streamlit
├── requirements.txt ← dependencias para ejecutarla
├── README.md ← documentación del proyecto
└── chat/
├── init.py
├── ollama_api.py ← manejo de llamadas a Ollama
├── extractors.py ← OCR y lectura de PDF o imágenes
├── state.py ← manejo de sesión
└── utils.py ← utilidades (copiado, estilos, etc.)

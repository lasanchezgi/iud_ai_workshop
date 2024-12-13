# Chatbot de Preguntas y Respuestas sobre la Constitución Política de Colombia

Este repositorio contiene un proyecto para la creación de un chatbot capaz de responder preguntas sobre la Constitución Política de Colombia. Utilizando las capacidades de **LangChain**, **ChromaDB** y **OpenAI**, el sistema permite realizar consultas precisas y obtener respuestas basadas en la Constitución.

## 🔧 **Instalación**

### **Requisitos previos**

- Python 3.8 o superior
- Acceso a la API de OpenAI
- Paquetes de Python necesarios:

```bash
pip install langchain chromadb tiktoken openai
```

### **Configuración**

1. Clona este repositorio:

```bash
git clone https://github.com/lasanchezgi/iud_ai_workshop
cd tu-repositorio
```

2. Configura tus claves de API de OpenAI:

```bash
export OPENAI_API_KEY="tu_clave_api"
```

3. Asegúrate de tener el archivo de la Constitución Política de Colombia en el directorio de entrada de documentos.

---

## 📌 **Estructura del Proyecto**

- **data/**: Carpeta que contiene el archivo de la Constitución Política de Colombia.
- **notebooks/**: Contiene el notebook con todos los pasos para la generación del chatbot.
- **vectorstore/**: Carpeta donde se almacenan los embeddings generados por ChromaDB.

---

## 📊 **Tecnologías Utilizadas**

- **LangChain**: Marco para construir aplicaciones de IA basadas en modelos de lenguaje.
- **ChromaDB**: Base de datos de vectores para almacenar los embeddings de los documentos.
- **OpenAI**: Proveedor de la API para generar respuestas a partir de un modelo LLM (GPT).
- **tiktoken**: Herramienta para contar y manipular tokens de texto.

---

## ✨ **Mejoras Futuras**

- **Mejorar la Precisión**: Ajustar el proceso de división de documentos para obtener un mejor balance entre contexto y fragmentación.
- **Interfaz Gráfica**: Crear una interfaz de usuario para facilitar la interacción con el chatbot.
- **Soporte Multilingüe**: Adaptar el sistema para responder en múltiples idiomas.

---

Si tienes alguna pregunta o necesitas ayuda, no dudes en abrir un issue o contactar al mantenedor del repositorio.

¡Disfruta explorando la Constitución Política de Colombia con esta poderosa herramienta de consulta! 🌐
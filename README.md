title: Segmentacion
emoji: 🏢
colorFrom: blue
colorTo: red
sdk: gradio
sdk_version: 6.14.0
python_version: '3.13'
app_file: app.py
pinned: false
license: unknown
---
readme_content = """# Chatbot Comercial Segmentado con RAG 🚀

Este proyecto es una aplicación de **Generación Aumentada por Recuperación (RAG)** diseñada para ofrecer atención al cliente personalizada y segmentada mediante el procesamiento de contenido web en tiempo real.

## 📋 Descripción del Proyecto
Este sistema permite a las organizaciones automatizar la atención al cliente utilizando su propia base de conocimientos alojada en la web. La aplicación descarga contenido HTML de URLs específicas, lo procesa y utiliza una base de datos vectorial para recuperar información relevante ante las consultas de los usuarios. La característica distintiva es su capacidad de **segmentación**, clasificando las respuestas según el público objetivo (ej. Pymes, Empresas, Empleados) mediante modelos de clasificación zero-shot.

## 🛠️ Tecnologías Utilizadas
* **Lenguaje:** Python.
* **Framework de IA:** LangChain (comunidad y Google GenAI).
* **Procesamiento de Texto:** BeautifulSoup4 (Scraping) y RecursiveCharacterTextSplitter.
* **Base de Datos Vectorial:** FAISS (faiss-cpu).
* **Modelos de Embeddings:** `models/gemini-embedding-001`.
* **Interfaz:** Gradio.

## 🤖 Modelos y APIs
* **LLM Principal:** Google Gemini (soporta `gemini-1.5-flash` y versiones recientes).
* **Clasificador Zero-Shot:** `facebook/bart-large-mnli` para segmentar las respuestas según el público objetivo.
* **APIs:** Google Generative AI SDK.

## 🖥️ Interfaz Gráfica
Desarrollada con **Gradio**, la interfaz permite:
* Configurar la API Key de Gemini y la temperatura del modelo.
* Definir dinámicamente la lista de URLs a descargar para el contexto.
* Visualizar un historial de chat y una respuesta en "Formato Ejecutivo" que incluye los segmentos detectados y su nivel de confianza.

## ⚙️ Instrucción de Instalación y Ejecución Local

### Requisitos Previos
Tener instalado Python 3.9+ y una API Key de Google Gemini.

### Pasos
1. **Clonar el repositorio:**
   ```bash
   git clone [https://github.com/jeansdelgado/pagesegmentacion.git](https://github.com/jeansdelgado/pagesegmentacion.git)
   cd pagesegmentacion

Instalar dependencias:
pip install -r requirements.txt

Ejecutar la aplicación:
python app.py
La aplicación se abrirá en tu navegador en http://127.0.0.1:7860.

Enlaces del Proyecto
Link al repositorio: GitHub Repo
https://github.com/jeansdelgado/pagesegmentacion/tree/main
Link a la app desplegada: Hugging Face Spaces
https://huggingface.co/spaces/JeansDr/Segmentacion



Python
readme_content = """

# Chatbot Comercial Segmentado con RAG 🚀

Este proyecto es una aplicación de **Generación Aumentada por Recuperación (RAG)** diseñada para ofrecer atención al cliente personalizada y segmentada mediante el procesamiento de contenido web en tiempo real.

## 📋 Descripción del Proyecto
Este sistema permite a las organizaciones automatizar la atención al cliente utilizando su propia base de conocimientos alojada en la web. La aplicación descarga contenido HTML de URLs específicas, lo procesa y utiliza una base de datos vectorial para recuperar información relevante ante las consultas de los usuarios. La característica distintiva es su capacidad de **segmentación**, clasificando las respuestas según el público objetivo (ej. Pymes, Empresas, Empleados) mediante modelos de clasificación zero-shot.

## 🛠️ Tecnologías Utilizadas
* **Lenguaje:** Python.
* **Framework de IA:** LangChain (comunidad y Google GenAI).
* **Procesamiento de Texto:** BeautifulSoup4 (Scraping) y RecursiveCharacterTextSplitter.
* **Base de Datos Vectorial:** FAISS (faiss-cpu).
* **Modelos de Embeddings:** `models/gemini-embedding-001`.
* **Interfaz:** Gradio.

## 🤖 Modelos y APIs
* **LLM Principal:** Google Gemini (soporta `gemini-1.5-flash` y versiones recientes).
* **Clasificador Zero-Shot:** `facebook/bart-large-mnli` para segmentar las respuestas según el público objetivo.
* **APIs:** Google Generative AI SDK.

## 🖥️ Interfaz Gráfica
Desarrollada con **Gradio**, la interfaz permite:
* Configurar la API Key de Gemini y la temperatura del modelo.
* Definir dinámicamente la lista de URLs a descargar para el contexto.
* Visualizar un historial de chat y una respuesta en "Formato Ejecutivo" que incluye los segmentos detectados y su nivel de confianza.

## ⚙️ Instrucción de Instalación y Ejecución Local

### Requisitos Previos
Tener instalado Python 3.9+ y una API Key de Google Gemini.

### Pasos
1. **Clonar el repositorio:**
   ```bash
   git clone [https://github.com/jeansdelgado/pagesegmentacion.git](https://github.com/jeansdelgado/pagesegmentacion.git)
   cd pagesegmentacion
Instalar dependencias:

Bash
pip install -r requirements.txt
Ejecutar la aplicación:

Bash
python app.py
La aplicación se abrirá en tu navegador en http://127.0.0.1:7860.

🔗 Enlaces del Proyecto
Link al repositorio: GitHub Repo

Link a la app desplegada: Hugging Face Spaces

📸 Captura de pantallas
(Nota: Las imágenes deben estar presentes en el repositorio en las rutas indicadas o subidas localmente).

Interfaz principal: ![Screenshot 1]
<img width="975" height="445" alt="image" src="https://github.com/user-attachments/assets/38bf5109-4b4b-4027-b007-c790c59bfffa" />
Respuesta segmentada: ![Screenshot 2]
<img width="975" height="459" alt="image" src="https://github.com/user-attachments/assets/f9908c86-af6e-4697-b3aa-df4c8a1d155d" />


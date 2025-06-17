# VStar – Procesamiento de Texto en Imágenes con Modelos Multimodales

Este repositorio contiene el desarrollo del proyecto **VStar**, realizado en el marco del curso **Aplicaciones de Data Science**. VStar es un modelo diseñado para **entender y responder preguntas basadas en texto contenido en imágenes**, combinando visión por computadora y procesamiento de lenguaje natural.

## 🧠 Objetivo

Desarrollar una solución capaz de interpretar imágenes que contienen texto (como señales, capturas de pantalla, documentos escaneados, etc.) y generar respuestas inteligentes a preguntas relacionadas con ese contenido textual.

## 🔍 Descripción General

El sistema se basa en modelos multimodales como **Qwen2-VL** y herramientas como `transformers`, `torch`, y `torchrl` para procesar tanto la imagen como el texto relacionado. El flujo general incluye:

- Carga y preprocesamiento de imágenes.
- Extracción y codificación de texto visual.
- Generación de respuestas mediante modelos generativos de lenguaje.

## 📦 Requisitos

Instala todas las dependencias con:

```bash
pip install -r requirements.txt

# 🧪 Sesión 1 – Fundamentos de Python para Ciencias Biológicas

**Fecha:** 22/08/2025  
**Docentes:** Dra. Carol Moraga e Ing. Felipe Gómez

Este módulo práctico introduce los fundamentos de programación en Python con ejemplos del ámbito biológico (FASTA, GC%, k-mers). Está pensado para ejecutarse en **Google Colab** (cero instalación) o de manera **local** si lo prefieres.

## 🎯 Objetivos de aprendizaje
- Comprender la lógica y el pensamiento computacional aplicado a datos biológicos.
- Manejar la sintaxis básica de Python: variables, tipos, estructuras de datos, control de flujo y funciones.
- Leer archivos FASTA simples, calcular **GC%** y contar **k-mers**.
- Configurar el entorno en **Google Colab** y/o instalación local.

## 📂 Estructura del repositorio
```
.
├── README.md
├── data
│   └── ejemplo.fasta
├── notebooks
│   └── example.ipynb
└── slides
    └── Session_1_Fundamentos_Python_Biologia.pptx
```

## 🚀 Empezar en Google Colab
Haz clic en el badge para abrir el notebook en Colab (ajusta la URL a tu repo si es necesario):

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/<TU_USUARIO>/<TU_REPO>/blob/main/notebooks/example.ipynb)

> En Colab, sube `data/ejemplo.fasta` si el notebook lo solicita o monta tu Drive.

## 💻 Instalación local (opcional)
1. Instala **Python 3.10+**.  
2. Crea y activa un entorno:
   ```bash
   python -m venv .venv
   # Linux/Mac
   source .venv/bin/activate
   # Windows PowerShell
   .venv\Scripts\Activate.ps1
   ```
3. (Opcional) Instala dependencias mínimas:
   ```bash
   pip install -U pip
   # Para la sesión 1 no se requiere Biopython, pero si deseas usarlo:
   # pip install biopython
   ```
4. Abre Jupyter:
   ```bash
   pip install notebook
   jupyter notebook
   ```

## 🧵 Contenidos de la sesión
- **Lógica y pensamiento computacional:** descomposición de problemas, patrones y abstracción.
- **Sintaxis básica:** tipos (`int`, `float`, `str`, `bool`), listas, diccionarios, tuplas; `if/for/while`; funciones.
- **Práctica con datos biológicos:**
  - Lectura de un archivo `FASTA` sencillo (sin librerías externas).
  - Cálculo de **GC%** por secuencia y global.
  - Conteo de **k-mers** y ranking de los más frecuentes.
  - Mini-evaluaciones con `assert` para validar tus funciones.

## ✅ Evaluación formativa
El notebook incluye celdas de prueba con `assert` para verificar que tus funciones producen los resultados esperados. Intenta pasar todas las pruebas.

## 🧷 Datos
- `data/ejemplo.fasta`: contiene pocas secuencias de ejemplo. Puedes reemplazarlo por tus secuencias.

---

> Si encuentras errores o deseas proponer mejoras, abre un **issue** o un **pull request**. ¡Gracias!

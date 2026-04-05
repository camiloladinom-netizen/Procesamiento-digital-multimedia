# EIE 401: Procesamiento Digital Multimedia (PUCV 2026-1)
# Camilo Andres Ladino Morales

## 📚 Descripción del Curso
Asignatura electiva de 7° semestre de Ingeniería Eléctrica en la Pontificia Universidad Católica de Valparaíso (PUCV). Impartida por el **Prof. Jorge Hernán Cárdenas** (PhD(c) Ingeniería Eléctrica).

**Créditos**: 4 (162 horas pedagógicas)  
**Requisitos**: EIE 409 (Programación 2), EIE 310 (Análisis y Procesamiento de Señales)  
**Objetivos principales**:
- Utilizar fundamentos teóricos del procesamiento digital de señales multimedia
- Identificar e implementar algoritmos para audio, imágenes y video
- Modelar y simular sistemas multimedia
- Elaborar informes técnicos [file:7][file:8]

## 📂 Contenido del Repositorio
Este repositorio contiene:
- **Transcripciones de clases** (sampling, Nyquist, ruido gaussiano, DFT 1D/2D)
- **Diapositivas y syllabus** del curso
- **Proyecto 1: LIGO-VIRGO** (procesamiento de ondas gravitacionales)
- **Códigos de ejemplo** (Python para DFT 2D, visualizaciones)
- **Notebooks Jupyter** para talleres y simulaciones

### Estructura de carpetas sugerida:
```
EIE401-MULTIMEDIA/
├── docs/              # Diapositivas, syllabus, proyecto PDF
├── notebooks/         # Talleres semanales (sampling, DFT, audio)
├── proyecto1/         # LIGO-VIRGO: datos, notebook, reporte IEEE
├── examples/          # Scripts de ejemplo (transfEspacial, ruido)
└── README.md          # Este archivo
```

## 🛠️ Tecnologías y Herramientas
- **Python 3.x** con NumPy, SciPy, Matplotlib
- **Jupyter Notebooks** para simulaciones
- **Git/GitHub** para control de versiones y entregas
- **Repositorio oficial del profesor**: https://github.com/Jorgecardenas1/EIE401MULTIMEDIA

## 📋 Actividades y Evaluación
- **Talleres de simulación** (25%): Cada 3 semanas en Jupyter Notebook
- **Ayudantías** (5%): Revisión semanal de conceptos
- **Proyectos integradores** (60%): Proyecto 1 (LIGO-VIRGO), Proyecto 2
- **Lectura investigativa** (10%): Presentación de papers (10+5 min)

**Calendario clave**:
- Semana 8: Entrega Proyecto 1
- Semana 15: Entrega Proyecto 2
- Todas las entregas vía GitHub + Aula Virtual [file:8]

## 🎯 Proyecto 1: LIGO-VIRGO
Procesar datos ruidosos de ondas gravitacionales (GW150914 u otros):
1. Descargar datos de https://gwosc.org/eventapi/html/GWTC/
2. Aplicar filtrado, denoising y extracción de *chirp*
3. Generar reporte IEEE (≤2 páginas)
4. Entrega: Notebook + PDF en GitHub [file:5]

## 📖 Referencias Principales
1. Vaseghi, *Multimedia Signal Processing* (Wiley, 2007)
2. Sayood, *Introduction to Data Compression* (Morgan Kaufmann, 2012)
3. Abbott et al., "LIGO-Virgo detector noise" (CQG, 2020) [file:5]

## 🚀 Instrucciones para Clonar y Ejecutar
```bash
git clone https://github.com/[tu-usuario]/EIE401-MULTIMEDIA.git
cd EIE401-MULTIMEDIA
pip install -r requirements.txt  # numpy scipy matplotlib jupyter
jupyter notebook
```

**requirements.txt** (crear si no existe):
```
numpy
scipy
matplotlib
jupyter
```

---

*Repositorio privado para organización personal del curso EIE401. Actualizado abril 2026.*

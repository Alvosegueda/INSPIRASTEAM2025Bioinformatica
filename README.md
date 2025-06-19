# INSPIRASTEAM2025Bioinformatica
# Bioinformática en acción: Epidemiología Genómica de Enfermedades Infecciosas  
**Syllabus & Recursos del Workshop**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](#licencia)

---

## Índice
1. [Descripción general](#descripción-general)
2. [Datos del workshop](#datos-del-workshop)
3. [Objetivos del curso](#objetivos-del-curso)
4. [Agenda y actividades](#agenda-y-actividades)
5. [Software necesario](#software-necesario)
6. [Requisitos previos](#requisitos-previos)
7. [Instalación y puesta a punto](#instalación-y-puesta-a-punto)
8. [Estructura del repositorio](#estructura-del-repositorio)
9. [Cómo citar este repositorio](#cómo-citar-este-repositorio)
10. [Contribuciones](#contribuciones)
11. [Licencia](#licencia)
12. [Contacto](#contacto)

---

## Descripción general
Este repositorio acompaña al workshop **“Bioinformática en acción: Epidemiología Genómica de Enfermedades Infecciosas”**.  
A lo largo de tres días, los participantes aprenderán a:

* Analizar secuencias genómicas de patógenos.
* Construir e interpretar árboles filogenéticos.
* Evaluar la diversidad genética y las variantes.
* Aplicar la vigilancia genómica para apoyar decisiones de salud pública.

Todo el contenido teórico, guías prácticas, datasets de ejemplo y scripts de apoyo estarán disponibles aquí.

---

## Datos del workshop
| Ítem | Detalle |
| ---- | ------- |
| **Lugar** | El Salvador |
| **Fechas** | 16 – 18 julio, 2025 |
| **Horario** | 9:45 – 11:00 a. m. |
| **Instructor** | **Wilber Alexander Alvarado Osegueda** |
| **Email** | alvosegueda@gmail.com |
| **Bio** | Molecular epidemiologist & bioinformatician focused on viral pathogens and genomic surveillance. |

---

## Objetivos del curso
Al finalizar el workshop, los participantes serán capaces de:

1. Utilizar herramientas bioinformáticas para analizar datos genómicos de patógenos infecciosos.  
2. Interpretar árboles filogenéticos para entender la evolución y diseminación de patógenos.  
3. Aplicar el análisis de variantes genómicas en estudios epidemiológicos.  
4. Emplear plataformas de vigilancia genómica para monitorear la propagación de enfermedades infecciosas.

---

## Agenda y actividades

| Día | Tema principal | Sesiones (45 min × 2) | Meta diaria |
| --- | -------------- | --------------------- | ----------- |
| **Día 1** | Introducción a la Bioinformática y Epidemiología Genómica | 1. Herramientas y recursos bioinformáticos (NCBI, GISAID, BLAST)  <br>2. Uso de datos genómicos en epidemiología (caso COVID-19) | Conocer las herramientas básicas y su relevancia en la vigilancia de patógenos. |
| **Día 2** | Análisis filogenético y diversidad genética | 1. Métodos de construcción de árboles (ML, NJ)  <br>2. Diversidad genómica y variantes (caso SARS-CoV-2) | Construir e interpretar árboles; comprender la evolución de patógenos. |
| **Día 3** | Vigilancia genómica y aplicaciones prácticas | 1. Plataformas de vigilancia (Nextstrain, GISAID)  <br>2. Discusión de proyectos y aplicaciones a brotes hipotéticos | Usar vigilancia en tiempo real para apoyar decisiones de salud pública. |

---

## Software necesario
| Herramienta | Tipo | Enlace / Instalación rápida |
|-------------|------|-----------------------------|
| **NCBI BLAST** | Online | <https://blast.ncbi.nlm.nih.gov/> |
| **GISAID** | Online (registro gratuito) | <https://gisaid.org/> |
| **MAFFT** | CLI / GUI | `conda install -c bioconda mafft` |
| **IQ-TREE** | CLI / GUI | `conda install -c bioconda iqtree` |
| **Nextstrain** | Online  | <https://nextstrain.org/> |

---

## Requisitos previos
* Conocimientos básicos de biología molecular o disciplinas afines.  
* Familiaridad mínima con la línea de comandos (Unix/Linux o Windows WSL).  
* Laptop con **≥ 8 GB RAM** y **5 GB** de espacio libre.  
* **Conda** (o **Mamba**) para gestionar entornos.

---

## Instalación y puesta a punto
```bash
# 1. Clona este repositorio
git clone https://github.com/tu-usuario/bioinfo-epi-genómica.git
cd bioinfo-epi-genómica

# 2. Crea un entorno conda
conda env create -f environment.yml
conda activate bioepi2025

# 3. Verifica las versiones
mafft --version
iqtree -h

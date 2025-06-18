# Scraping-de-titulares-de-noticias-de-El-Pais

Este mini-proyecto es una práctica guiada para aprender **web scraping** en Python usando `requests`, `BeautifulSoup` y `pandas`.

El objetivo es extraer los 10 primeros titulares de la portada del diario [El País](https://elpais.com/), guardarlos en un archivo CSV y visualizarlos desde Google Colab.

## 🔧 Tecnologías utilizadas

- Python 3
- Google Colab
- requests
- BeautifulSoup
- pandas
- csv

## 📌 Pasos principales

1. Acceder al HTML de la página de El País.
2. Extraer los titulares desde etiquetas `<h2>`.
3. Guardar los primeros 10 titulares en un archivo `CSV`.
4. Mostrar y descargar el archivo desde Colab.

## 📁 Archivos generados

- `titulares_elpais.csv`: contiene los 10 titulares extraídos.

## 🚀 Cómo ejecutarlo

1. Abre el notebook en Google Colab.
2. Ejecuta todas las celdas.
3. Visualiza los titulares.
4. Descarga el archivo CSV con un clic.

## 🧠 Aprendizajes clave

- Uso de selectores CSS con BeautifulSoup.
- Limpieza de texto con Python.
- Exportación de datos a CSV.
- Uso de Google Colab para prototipado rápido.

---

### 💡 Nota

La estructura de las webs puede cambiar con el tiempo. Si el scraping deja de funcionar, revisa el HTML con F12 (Inspeccionar) y ajusta los selectores.

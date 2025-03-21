# 🖹 OCR con Google Colab + OpenAI  

🔍 Extrae texto y tablas de PDFs e imágenes usando OCR con Tesseract y Tabula. Además, puede mejorar la estructura del texto usando OpenAI.  

---

## 🚀 **¿Qué hace esta herramienta?**  
✅ **Soporte para PDF e imágenes** (JPG, PNG)  
✅ **OCR con Tesseract** para extraer texto  
✅ **Tabula** para extraer tablas de PDFs  
✅ **Salida en Word (`.docx`)** para texto y en **Excel (`.xlsx`)** para tablas  
✅ **Carpeta organizada:** archivos subidos y procesados en directorios separados  
✅ **Eliminación automática** de archivos después de la descarga  
✅ **Integración con OpenAI** (opcional) para mejorar la estructura del texto  

---

## 📌 **Abrir en Google Colab**  
Haz clic en el botón para abrir y ejecutar el notebook en Google Colab:  

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CENFARG/ocr2text2table/blob/main/OCR_simple_con_IA.ipynb?usp=copy)

---

## 📥 **¿Cómo usarlo?**  
1️⃣ **Sube un archivo** PDF o imagen (JPG, PNG)  
2️⃣ **El notebook extrae:**  
   - Texto con **OCR (Tesseract)**  
   - Tablas con **Tabula**  
3️⃣ **Descarga los resultados:**  
   - **Texto** en Word (`.docx`)  
   - **Tablas** en Excel (`.xlsx`)  
4️⃣ **Los archivos temporales se eliminan automáticamente**  

📌 **Nota:** Si usas OpenAI para mejorar el texto, debes configurar tu API Key en el notebook antes de ejecutar.  

---

## 🔧 **Dependencias utilizadas**  
Este notebook usa las siguientes bibliotecas:  

- `pytesseract` → OCR con Tesseract  
- `pdf2image` → Convierte PDF a imágenes  
- `opencv-python` → Preprocesamiento de imágenes  
- `pandas` → Manejo de datos  
- `tabula-py` → Extrae tablas de PDFs  
- `python-docx` → Guarda texto en Word  
- `xlsxwriter` → Guarda tablas en Excel  
- `markdownify` → Convierte HTML a Markdown  
- `openai` → (Opcional) Mejora de texto con IA  

Estas dependencias se instalan automáticamente en Google Colab, ¡así que no te preocupes! 🚀  

---

## 📜 **Licencia**  
Este notebook está bajo la licencia **MIT**, por lo que puedes usarlo y modificarlo libremente.  

---

## 📬 **Contacto**  
Si tienes dudas o sugerencias, puedes escribirme:  
📧 **Email:** [cenf.arg@gmail.com](mailto:cenf.arg@gmail.com)  
🐦 **Web:** [@CENF WEB](https://www.cenfarg.com)

---
✨ ¡Gracias por usar esta herramienta! 🚀  

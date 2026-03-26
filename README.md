🔍 Digital Forensics Lab – Kali Linux
🔍 Laboratorio de Forense Digital – Kali Linux
👨‍💻 Author / Autor
Carlos Pinto
Esteban Saldaña

---

📌 Description / Descripción

EN:
This project is a hands-on digital forensics lab using Kali Linux. It includes password cracking, steganography analysis, and metadata investigation to simulate real-world cybersecurity scenarios.

ES:
Este proyecto corresponde a un laboratorio práctico de forense digital utilizando Kali Linux. Incluye técnicas de cracking de contraseñas, análisis de esteganografía e investigación de metadatos, simulando escenarios reales de ciberseguridad.

---

## 🛠️ Tools Used/Herramientas utilizadas

* John the Ripper
* fcrackzip
* Steghide
* Stegcracker
* Exiftool
* Binwalk
* Strings

---

## 🔐 1. Password Cracking/Crackeo de archivos protegidos

Se realizó la recuperación de contraseñas utilizando ataques de diccionario con `rockyou.txt`.
Password-protected files were analyzed and successfully cracked using dictionary attacks with the `rockyou.txt`.

### 📦 ZIP

* Tool/Herramienta: fcrackzip
* Result/Resultado: contraseña recuperada ✔️

### 📄 PDF

* Tool/Herramienta: pdf2john + john
* Result/Resultado: acceso al contenido protegido ✔️

---

## 🕵️ 2. Steganography Analysis/Esteganografía

Hidden data was discovered inside an image using steganography techniques.
Se identificó y extrajo información oculta dentro de una imagen.

* Password Found/Contraseña encontrada: `slipknot`
* Extracted file/Archivo extraído: `tumismo`
* Hidden Message/Mensaje oculto:

> "Se tu mismo. Todos los demas ya estan ocupados."

---

## 🧬 3. File Analysis/Análisis forense

* El archivo analizado correspondía a una imagen JPEG válida
* No se detectaron datos incrustados con binwalk
* Se confirmó el uso de esteganografía

---

## 📍 4. Metadata/Metadatos

* 📅 Date/Fecha: 03-12-2012
* 📱 Device/Dispositivo: iPhone 4S
* 📍 Location/Ubicación: Copán, Honduras

---

## 🧠 Conclusión

Este laboratorio demuestra cómo técnicas como la esteganografía y el uso de contraseñas débiles pueden comprometer la seguridad de la información. Además, resalta la importancia del análisis de metadatos en investigaciones forenses.

---

## 📸 Evidence/Evidencias

![Crack ZIP](evidencias/01_zip_crack.png)
![Crack PDF](evidencias/02_pdf_crack.png)
![Stegcracker](evidencias/03_stegcracker.png)
![Steghide](evidencias/04_steghide.png)
![Strings](evidencias/05_strings.png)
![Exiftool](evidencias/06_exiftool.png)

---

## 🚀 Skills Demonstrated/Habilidades demostradas

* Análisis forense digital
* Uso de Kali Linux
* Cracking de contraseñas
* Esteganografía
* Interpretación de metadatos

* Digital Forensics / Forense Digital
* Password Cracking
* Steganography Analysis
* Metadata Analysis (EXIF)
* Kali Linux Tooling

---

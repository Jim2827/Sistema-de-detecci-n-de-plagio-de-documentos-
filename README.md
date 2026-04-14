Sistema de Detección de Plagio de Documentos
Este es un sistema de Backend desarrollado en Python para la auditoría y validación de originalidad en documentos. A diferencia de scripts básicos, esta versión implementa una interfaz gráfica de usuario para la selección de archivos, lo que facilita su uso en entornos administrativos y profesionales.

Funciones Principales
Interfaz Intuitiva: Implementación de explorador de archivos mediante tkinter para una selección de documentos sin errores.
Soporte Multiformato: Extracción de texto de archivos .txt, .pdf, .docx (Word) y .xlsx (Excel).
Limpieza de Datos Avanzada: Uso de la librería unidecode para normalizar el texto, eliminando acentos, caracteres especiales y puntuación para garantizar una comparación precisa.
Análisis de Similitud: Algoritmo basado en conjuntos de palabras únicas que calcula el porcentaje de coincidencia entre dos fuentes de datos.
Generación de Informes: Creación automática de reportes técnicos en .txt y actualización de un historial centralizado de comparaciones.

Stack Tecnológico
Lenguaje: Python 3.x
Librerías de Procesamiento: PyPDF2: Para la manipulación de flujos de datos en PDF.
python-docx: Para la extracción de estructuras de texto en Word.
openpyxl: Para la lectura de celdas y hojas de cálculo en Excel.
unidecode: Para la normalización lingüística.
Interfaz: Tkinter (filedialog)

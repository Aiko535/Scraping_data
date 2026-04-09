# 🕷️ Scraping de Resultados UNMSM 2026-II

## 📌 ¿Qué hace el proyecto?

Este proyecto realiza web scraping de los resultados del examen de admisión 2026-II de la Universidad Nacional Mayor de San Marcos (UNMSM).

El script accede automáticamente a la página oficial, obtiene los enlaces de todas las carreras y extrae la información completa de los postulantes, incluyendo:

- Código
- Apellidos y nombres
- Escuela profesional
- Puntaje
- Mérito
- Observación

Debido a que la página utiliza DataTables (paginación con JavaScript), el script navega por todas las páginas de resultados para obtener la información completa.

---

## ⚙️ ¿Cómo instalar las dependencias?

Primero, asegúrate de tener Python instalado.

Luego, en la terminal de Visual Studio Code ejecuta:

```bash
python -m pip install selenium pandas openpyxl webdriver-manager beautifulsoup4
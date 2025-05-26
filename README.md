---

## 📘 `README.md`

```markdown
# 🌡️ CattleClimate

Visualizador interactivo de datos meteorológicos para calcular y analizar variables relevantes al estrés térmico en ganado vacuno. Desarrollado con [Streamlit](https://streamlit.io/) y pensado para investigadores, estudiantes y técnicos del semillero AGRISOS BIOCLIMÁTICA.

![Streamlit](https://img.shields.io/badge/Built%20with-Streamlit-red?style=for-the-badge&logo=streamlit)
![Python](https://img.shields.io/badge/Python-3.13-blue?style=for-the-badge&logo=python)

---

## 📂 Estructura del proyecto

```

- `app.py` – Aplicación principal en Streamlit.
- `datos/`
  - `hidrometeorologicos/` – Archivos .data
  - `radiacion/` – (opcional)
  - `Glosario_Variables.xlsx`
  - `CNE_IDEAM.xlsx`
- `README.md`
- `requirements.txt`
- `.gitignore`````

---

## 🚀 ¿Cómo ejecutar la aplicación?

1. Clona el repositorio:

```bash
git clone https://github.com/justorfc/CattleClimate.git
cd CattleClimate
````

2. Crea un entorno virtual (opcional pero recomendado):

```bash
python -m venv .venv
source .venv/bin/activate  # o .venv\Scripts\activate en Windows
```

3. Instala las dependencias:

```bash
pip install -r requirements.txt
```

4. Ejecuta la aplicación:

```bash
streamlit run app.py
```

5. Abre en tu navegador: `http://localhost:8501`

---

## 📊 Funcionalidades principales

* Visualización de archivos `.data` con fechas y valores meteorológicos.
* Validación automática del formato de datos.
* Rango de fechas seleccionable.
* Estadísticas básicas (mínimo, máximo, promedio).
* Promedios mensuales y anuales con gráficos.
* Descarga de datos filtrados en formato CSV.

---

## 🧑‍💻 Créditos

Desarrollado por el profesor Justo Fuentes y el semillero AGRISOS BIOCLIMÁTICA, en colaboración con el profesor Quelbis Quintero (Universidad de Sucre).

---

## 📝 Licencia

Este proyecto es de uso educativo y puede ser reutilizado y modificado citando la fuente.

```

---

```

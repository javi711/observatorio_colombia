# Observatorio Nacional de Colombia

Plataforma de inteligencia territorial, econometría y simulación de políticas públicas para los 32 departamentos y Bogotá D.C.

Todas las cifras se consultan en vivo a las APIs oficiales (datos.gov.co / Socrata, Banco de la República y, como respaldo nacional, Banco Mundial). Si una fuente falla, el observatorio lo informa y no sustituye datos con cifras simuladas.

## Secciones

- 📌 Presentación y monitor de salud de las APIs
- 📊 Tablero general con KPI, ranking, distribución y evolución
- 🔬 Radiografía y microdatos con exportación a CSV y Excel
- 🗺️ Mapa coroplético, correlaciones y clústeres K-Means
- 📈 Series y pronóstico con SARIMA, ETS y OLS
- 🎛️ Simulador de políticas con regresiones de panel
- 📄 Generador de informes en HTML
- 🤖 Asistente de ayuda

## Archivos del repositorio

- `app.py` es la aplicación
- `requirements.txt` lista las librerías que se instalan
- `.streamlit/config.toml` define el tema oscuro de la página

## Publicación en Streamlit Community Cloud

1. Suba estos archivos a un repositorio público de GitHub.
2. Entre a https://share.streamlit.io con su cuenta de GitHub.
3. Elija **Create app**, seleccione el repositorio, la rama `main` y el archivo `app.py`.
4. Pulse **Deploy**.

## Ejecución local

```bash
pip install -r requirements.txt
streamlit run app.py
```

## Autores

Francisco Lagos, Nathaly Viteri y Camilo Linares. Programa de Economía, Facultad de Ciencias Económicas y Administrativas, Universidad de Nariño. Seminario de Investigación Regional, docente Julio Riascos. San Juan de Pasto, 2026.

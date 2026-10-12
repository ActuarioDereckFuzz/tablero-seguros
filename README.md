# 📊 Tablero de Cartera — Diplomado ML Seguros

Aplicación **Streamlit** para análisis de cartera y cotización de primas en seguros de auto.  
Carga datos desde **SQLite** (reconstruido desde Parquet si no existe) y permite visualizar KPIs, ratios de rentabilidad y cotizar primas de forma empirica y con modelos GLM.

## 🚀 Cómo correrlo en local

1. Clona este repositorio:
   ```bash
    git clone https://github.com/ActuarioDereckFuzz/tablero-seguros.git
   ```
2. Instala dependencias:
   ```bash
   pip install -r requirements.txt
   ```
3. Ejecuta la aplicación:
   ```bash
   streamlit run app_streamlit.py
   ```
4. Abre el navegador en la URL que Streamlit te indique (por defecto http://localhost:8501).

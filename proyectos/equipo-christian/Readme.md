# Dashboard de Apagones en Puerto Rico 🔌

Un dashboard interactivo que visualiza y analiza datos históricos de apagones eléctricos en Puerto Rico desde 2021. El proyecto utiliza Streamlit para crear una interfaz web interactiva que permite explorar patrones de apagones por localización y tiempo.

Lo puedes accesar en https://energyhackathon-9ccofqkuvniq666atvhwfm.streamlit.app/

![Dashboard Preview](demo.gif)

## 🌟 Características

- **Mapa de Calor Interactivo**: Visualización geográfica de la frecuencia de apagones
- **Análisis por Localización**: Búsqueda y estadísticas detalladas por área
- **Tendencias Temporales**: Análisis de patrones a lo largo del tiempo
- **Filtros Dinámicos**: Por municipio, fecha y localización

## 🛠️ Tecnologías Utilizadas

- Python 3.x
- Streamlit (interfaz web)
- Folium (mapas interactivos)
- Pandas (análisis de datos)
- Plotly (visualizaciones)

## ⚙️ Instalación

1. Clonar el repositorio:
```bash
git clone https://github.com/PREnergyHack/Caguas_2024.git
cd Caguas_2024/proyectos/equipo-christian
```

2. Crear un entorno virtual:
```bash
# En Windows
python -m venv venv
venv\Scripts\activate

# En macOS/Linux
python3 -m venv venv
source venv/bin/activate
```

3. Instalar dependencias:
```bash
pip install -r requirements.txt
```

O instalar manualmente:
```bash
pip install streamlit pandas folium plotly streamlit-folium
```

## 🚀 Uso

1. Activar el entorno virtual:
```bash
source venv/bin/activate  # En macOS/Linux
venv\Scripts\activate     # En Windows
```

2. Ejecutar el dashboard:
```bash
streamlit run main.py
```

## 📊 Datos

Los datos provienen de varias fuentes:
- LUMA Energy (datos de apagones)
- Datos normalizados por Urbital LLC

## 📁 Estructura del Proyecto

```
proyecto/
├── script     
|   |__ filterByMunicipio # Script para filtrar csv por pueblo
├── src/                  # Directorio de datos
│   └── caguas_outages.csv
│   └── main.py           # Aplicación principal de Streamlit
│   └── requirements.txt  # Dependencias del proyecto
└── README.md
```



## 👥 Autores

- Christian Nogueras Rosado - [@Kiri_23](https://github.com/Kiri23)
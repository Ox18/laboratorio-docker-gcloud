# Instalar dependencias

pip install streamlit pandas numpy matplotlib

# Construir imagen 2

docker build -t mi-streamlit-app .


# Correr contenedor

docker run -p 3005:8080 mi-streamlit-app

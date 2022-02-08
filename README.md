# Preparar entorno virtual 
  
      py -3 -m venv .venv .venv\scripts\activate

# Crear archivo de dependencias.

     echo.> requirements.txt
     wsl touch requirements.txt

# Instalar dependencias.

    pip install -r requirements.txt

# Instalar ejecutar migraciones.

    py manage.py makemigrations
    py manage.py migrate


# Ejecutar Servidor Web.

    python manage.py runserver


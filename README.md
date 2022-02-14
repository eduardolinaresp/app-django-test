# Preparar entorno virtual 
  
      python -m venv .venv 
	  
	  .venv\scripts\activate
	  
	  Nota: En powershell permitir ejecutar script con Set-ExecutionPolicy Unrestricted

      python3 -m venv .venv
     
      python3 -m venv .venv\scripts\activate


# Crear archivo de dependencias.

     echo.> requirements.txt
     wsl touch requirements.txt

# Instalar dependencias.

    pip install -r requirements.txt

# Crear una aplicacion.

    django-admin startproject mysite

# Instalar ejecutar migraciones.

    python manage.py makemigrations
    python manage.py migrate


# Crear un usuario administrador.
	
	python manage.py createsuperuser

# Ejecutar Servidor Web.

    python manage.py runserver
	


	
	


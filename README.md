# Preparar entorno virtual 
  
      python -m venv .venv 
	  
	  .venv\scripts\activate
	  
	  Nota: En powershell permitir ejecutar script con Set-ExecutionPolicy Unrestricted

      python3 -m venv .venv
     
      python3 -m venv .venv\scripts\activate


# Crear archivo de dependencias.

     pip freeze > requirements.txt  # Python3
     echo.> requirements.txt
     wsl touch requirements.txt

# Instalar dependencias.

    pip install -r requirements.txt

# Crear una aplicacion.

    django-admin startproject mysite

# Instalar ejecutar migraciones.

    python3 manage.py makemigrations
    python3 manage.py migrate


# Crear un usuario administrador.
	
	python3 manage.py createsuperuser

# Ejecutar Servidor Web.

       python3 manage.py runserver
	


	
	


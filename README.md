# Preparar entorno virtual 
  
## Windows Powershell.

      python -m venv .venv 
	  
	  .venv\scripts\activate
	  
	  Nota: En powershell permitir ejecutar script con Set-ExecutionPolicy Unrestricted
	  
## Linux Shell.

      python3 -m venv venv
     
      source venv/bin/activate


# Crear archivo de dependencias.

     pip freeze > requirements.txt  # Python3
     echo.> requirements.txt
     wsl touch requirements.txt

# Instalar dependencias.

    pip install -r requirements.txt

# Crear una aplicación.

    django-admin startproject mysite

# Instalar ejecutar migraciones.

    python3 manage.py makemigrations
    python3 manage.py migrate


# Crear un usuario administrador.
	
	python3 manage.py createsuperuser

# Ejecutar Servidor Web local.

	python3 manage.py runserver
	
# Ejecutar sub-rutinas desde shell.
	
       python3 -c 'from elinares import *; list_ordenes()'

# Ejecutar test desde shell.

      python3 manage.py test animals
      
# Ejecutar django shell.   

     python3 manage.py shell


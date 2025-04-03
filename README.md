Version  3.12.9

Guía Rápida: Configuración del Entorno y Uso de Git

1. Crear un entorno virtual
```
python -m venv .venv
```
	
2. Activarlo
- Windows (CMD):
  ```
  .venv\Scripts\activate
  ```
- PowerShell:
  ```
  .venv\Scripts\Activate.ps1
  ```
- Linux/Mac/Git Bash:
  ```
  source .venv/bin/activate

  ```
3. Instalar una librería (ejemplo requests) y guardar dependencias
```
pip install requests  
pip freeze > requirements.txt
```

4. Inicializar Git y preparar archivos
```
git init  
git add .  
git commit -m "Proyecto inicial"
```

5. Subirlo a GitHub
```
git remote add origin https://github.com/tu-usuario/tu-repo.git  
git push -u origin main
```

6. Ejecutar el código
```
python main.py
```

7. Copiar y compartir el enlace del repositorio en GitHub.
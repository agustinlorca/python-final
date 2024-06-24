# Clase 24/06
1. Abrir la terminal de Git Bash o terminal en Linux, debe ser como administrador en Window
2. Creamos una carpeta o directorio: 
```sh
mkdir python-final
```
3. Entramos en ella: 
```sh
cd python-final
```
4. Iniciamos el repositorio:
```sh
git init
```
5. Creamos un archivo:
```sh
touch finales.py
```
6. Abrimos VSC:
```sh
code .
```
7. En terminal ingresamos el comando para saber la versión de Python que tenemos instalada:
```sh
python -V
```
ó
```sh
python3 -V
```
8. Creamos el entorno virtual en Python:
```sh
python3 -m venv venv #Creamos el entorno virtual
```
9. Activamos el entorno virtual:
```sh
source venv/bin/activate #Activamos el entorno virtual en Linux
```
```sh
venv/scripts/activate #En windows
```

10. Hacemos actualización del pip de Python
```sh
python3 -m pip install --upgrade pip #Actualizamos el pip
```
11. Investigar ¿Qué es el pip y porque lo actualizamos?

# Funciones Principales de Pip:
- Instalar Paquetes: Permite instalar paquetes desde el Python Package Index (PyPI) y otras fuentes.
```sh
pip install nombre_paquete
```
- Actualizar Paquetes: Permite actualizar paquetes instalados a sus versiones más recientes.
```sh
pip install --upgrade nombre_paquete
```
- Desinstalar Paquetes: Permite desinstalar paquetes que ya no se necesitan.
```sh
pip uninstall nombre_paquete
```
- Listar Paquetes Instalados: Muestra una lista de todos los paquetes instalados.
```sh
pip list
```
- Mostrar Información de un Paquete: Proporciona detalles sobre un paquete específico
```sh
pip show nombre_paquete
```
# Razones para Actualizar Pip:
1. Nuevas Funcionalidades: Las nuevas versiones de pip pueden incluir características adicionales que mejoran su funcionalidad y facilidad de uso.
2. Corrección de Errores: Las actualizaciones suelen corregir errores y fallos presentes en versiones anteriores, mejorando la estabilidad y fiabilidad de la herramienta.
3. Mejoras de Seguridad: Las versiones más recientes pueden incluir parches de seguridad que protegen contra vulnerabilidades descubiertas en versiones anteriores.
4. Compatibilidad: Mantener pip actualizado asegura que es compatible con las últimas versiones de Python y de los paquetes disponibles en PyPI.
5. Mejor Rendimiento: Las actualizaciones pueden mejorar el rendimiento de pip, haciendo que las operaciones de instalación, actualización y desinstalación sean más rápidas y eficientes.

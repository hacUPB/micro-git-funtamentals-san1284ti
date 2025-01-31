
# Cómo crear un repositorio local con comandos de Git.

<img src="../images/i1.png" alt="Texto alternativo" width="200" height="200">

Para crear un repositorio local con Git, hay que seguir estos pasos:

1. **Inicia un directorio vacío:**
   Si ya tienes un proyecto en una carpeta, navega a esa carpeta en la consola con el comando `cd`:
   ```bash
   cd ruta/del/directorio
   ```

   Si aún no tienes un directorio, crea uno con `mkdir` y navega hacia él:
   ```bash
   mkdir mi-proyecto
   cd mi-proyecto
   ```

2. **Inicializa el repositorio de Git:**
   Dentro del directorio donde quieras crear el repositorio, usa el siguiente comando:
   ```bash
   git init
   ```

   Esto crea un repositorio local de Git, se genera una subcarpeta llamada `.git` que contiene todos los archivos de configuración del repositorio.

3. **Agrega archivos al repositorio:**
   Si ya tienes archivos en el directorio que deseas versionar, usa el siguiente comando para agregar todos los archivos al repositorio:
   ```bash
   git add .
   ```

   Si solo deseas agregar archivos específicos, puedes hacerlo indicando el nombre del archivo:
   ```bash
   git add archivo.txt
   ```

4. **Haz el primer commit:**
   Después de agregar los archivos, realiza el primer commit con el siguiente comando:
   ```bash
   git commit -m "Primer commit"
   ```

   Esto guarda los archivos en el repositorio con el mensaje "Primer commit".



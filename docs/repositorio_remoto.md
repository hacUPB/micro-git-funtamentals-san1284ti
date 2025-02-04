# Cómo crear un repositorio remoto con comandos de Git.
<img src="../images/i2.png" alt="Texto alternativo" width="200" height="150">

1. **Conecta a un repositorio remoto:**
   Si deseas vincular tu repositorio local a uno remoto (como GitHub, GitLab, etc.), usa el siguiente comando:
   ```bash
   git remote add origin https://url-del-repositorio-remoto.git
   ```

2. **Empuja los cambios al repositorio remoto:**
   Si tienes un repositorio remoto configurado y quieres subir tus cambios, usa:
   ```bash
   git push -u origin master
   ```

   Esto sube tus commits al repositorio remoto y los vincula para futuros `push` sin necesidad de especificar la rama.
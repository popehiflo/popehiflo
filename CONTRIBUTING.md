# Guía de Contribución

¡Gracias por tu interés en contribuir!

## Flujo de Trabajo

1.  **Configura tu entorno:**
    - Asegúrate de tener `nvm` instalado.
    - Ejecuta `nvm use` en la raíz del proyecto para usar la versión de Node.js correcta.
    - Instala las dependencias con `npm install`.

2.  **Inicia el servidor de desarrollo:**
    - Ejecuta `npm run dev`.

3.  **Crea una nueva rama:**
    - Usa un nombre descriptivo siguiendo la convención: `feat/nombre-feature` o `fix/nombre-bug`.
    - Ejemplo: `git checkout -b feat/formulario-contacto`.

4.  **Realiza tus cambios:**
    - Escribe tu código y asegúrate de que todo funciona como se espera.

5.  **Formatea y valida tu código:**
    - Antes de hacer commit, ejecuta `npm run format` y `npm run lint:fix` para asegurar que el código sigue las guías de estilo y no tiene errores.

6.  **Haz commit de tus cambios:**
    - Usa la convención de [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/).
    - Ejemplo: `git commit -m "feat: agrega validación de email en formulario de contacto"`.

7.  **Sube tus cambios y crea un Pull Request:**
    - Sube tu rama al repositorio (`git push origin feat/formulario-contacto`).
    - Abre un Pull Request en GitHub hacia la rama principal de desarrollo (`dev`).

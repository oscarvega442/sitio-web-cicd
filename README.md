
# Sitio web con CI/CD


Este repositorio contiene un sitio web sencillo en **HTML** cuyo propósito es demostrar un flujo de **CI/CD**.  
Cada cambio en `main` dispara un workflow que **despliega automáticamente** el sitio en **GitHub Pages**.

## ¿Cómo está configurado el workflow?
- **Evento**: `push` a `main` o ejecución manual (`workflow_dispatch`).
- **Build**: se empaqueta el contenido del repo como artifact para Pages.
- **Deploy**: se usa `actions/deploy-pages@v4` para publicar el sitio.

## ¿Qué problema resuelve la automatización?
Evita subir archivos manualmente y asegura un despliegue **consistente y repetible**.  
Cada actualización pasa por el mismo proceso automatizado, reduciendo errores y ahorrando tiempo.

## Sitio WEB
Sitio deplegado: https://oscarvega442.github.io/sitio-web-cicd/

## Enlaces útiles
- GitHub Actions (docs): https://docs.github.com/en/actions  
- Acción oficial para Pages: https://github.com/actions/deploy-pages


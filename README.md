# Política de privacidad de IdeaForge

Responsable: Juan Manuel O'Hara, desarrollador independiente.
Contacto público autorizado: juanmohara@gmail.com.

La página está preparada para revisión y publicación. No se publicó ni se creó un repositorio remoto. Su contenido describe la implementación revisada de IdeaForge; antes de publicar, confirmar que coincide con las prácticas reales de soporte, conservación y distribución. No sustituye una revisión legal de las obligaciones de cada mercado.

## Publicar sin servidor propio

1. En GitHub, crear un repositorio **público separado**, por ejemplo `ideaforge-privacy`. No cambiar la visibilidad del repositorio de la app.
2. Subir únicamente `index.html` y `.nojekyll` de esta carpeta a la raíz de ese repositorio.
3. En Settings > Pages, seleccionar Deploy from a branch, rama `main`, carpeta `/ (root)` y guardar.
4. Esperar al despliegue. Copiar la URL que muestra GitHub Pages y verificar que abre sin iniciar sesión, también desde un teléfono.
5. Pegar esa URL en el campo Privacy Policy URL / URL de la política de privacidad de App Store Connect y guardar los cambios de metadatos.
6. La app ya incluye el mismo documento sin conexión. Cuando exista la URL pública se puede agregar también un enlace web; no se ha configurado una URL supuesta.

No se necesita dominio propio. La URL final depende de la cuenta y del nombre del repositorio: debe copiarse del despliegue real.

## Mantener las dos copias

La fuente del documento es `IdeaForge/Resources/PrivacyPolicy.html` dentro del proyecto de la app. Después de editarla, actualizar `privacy-site/index.html` con una copia exacta, revisar la fecha y desplegar la nueva página. Incluir el documento actualizado en la siguiente versión de la app.

## Revisiones pendientes

- Verificar esta política con las prácticas reales y los países donde se distribuirá.
- Declarar en App Store Connect los datos conforme a sus definiciones: el contenido local/iCloud, los correos de soporte y los diagnósticos no deben confundirse automáticamente con seguimiento publicitario.
- Resolver por separado el flujo de eliminación de datos y revocación de acceso. La política no afirma que exista un botón de eliminación de cuenta que todavía no está implementado.
- No se han redactado términos de servicio ni publicado el correo fuera de estos archivos.

Referencias: [Apple, revisión y privacidad](https://developer.apple.com/app-store/review/guidelines/#privacy); [GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages); [datos técnicos de visitantes](https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages).

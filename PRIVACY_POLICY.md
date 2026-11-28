# Política de Privacidad — WoW AdonnES
*Última actualización: 28 de noviembre de 2026*

**WoW AdonnES** es una aplicación de escritorio independiente, de código abierto y sin ánimo de lucro, diseñada para la traducción y gestión comunitaria de complementos (addons) del videojuego World of Warcraft al español.

El compromiso con la privacidad de los usuarios es absoluto. A continuación se detalla cómo se gestiona la información y las conexiones de red:

---

### 1. Recopilación de Datos Personales
* **Cero datos personales:** WoW AdonnES **NO** recopila, almacena, comparte ni vende ningún tipo de dato personal identificable (nombre, dirección, correo electrónico, dirección IP, información de pago ni identificadores de hardware).
* **Sin cuentas ni registros:** La aplicación no requiere inicio de sesión, creación de cuentas de usuario ni contraseñas.

---

### 2. Almacenamiento Local
* Todo el almacenamiento se realiza de forma estrictamente local en el equipo del usuario (archivo `config.json` en el directorio de la aplicación).
* Se almacenan exclusivamente las preferencias elegidas por el usuario:
  - La ruta local de la carpeta `Interface\AddOns`.
  - La versión seleccionada del juego (Forever, Classic, Retail, Cataclysm).
  - El modelo de traducción preferido.
* Ninguno de estos datos se envía a servidores externos propios ni de terceros con fines de rastreo o telemetría.

---

### 3. Conexiones de Red y Servicios de Terceros
La aplicación realiza peticiones de red directas únicamente para cumplir sus funciones esenciales solicitadas por el usuario:
1. **GitHub (`api.github.com` / `raw.githubusercontent.com`):** Consulta el archivo `version.json` para verificar si existen actualizaciones de la aplicación y descargar los paquetes oficiales de actualización.
2. **CurseForge Core API (`api.curseforge.com`):** Consulta la base de datos pública de CurseForge para buscar addons, comprobar versiones más recientes y descargar los complementos seleccionados por el usuario.
3. **Google Generative AI (Gemini API):** Envía fragmentos de texto en inglés (descripciones y frases de addons) para obtener su traducción contextual al español. **Nunca** se envían datos personales, cuentas, correos ni datos del sistema a través de esta API.

---

### 4. Seguridad de los Archivos del Juego
* La aplicación no modifica, no parchea y no interactúa en memoria con el cliente ejecutable del juego (`WoW.exe`).
* Solo lee y escribe archivos de texto plano (`.toc` y `.lua`) en el directorio público y permitido de complementos (`Interface\AddOns`).
* Antes de modificar cualquier archivo, genera automáticamente una copia de seguridad local (`.bak`) que el usuario puede restaurar en cualquier momento con un solo clic.

---

### 5. Descargo de Responsabilidad (Aviso Legal)
World of Warcraft y Blizzard Entertainment son marcas comerciales o marcas registradas de Blizzard Entertainment, Inc. en EE. UU. y/u otros países. WoW AdonnES es un proyecto independiente desarrollado por y para la comunidad, y no está afiliado, respaldado, asociado ni patrocinado por Blizzard Entertainment ni por CurseForge/Overwolf.

---

### 6. Contacto y Soporte
Para cualquier consulta, reporte de error o solicitud sobre el proyecto y su código, puedes ponerte en contacto a través del repositorio oficial en GitHub:  
👉 **[https://github.com/tutosyoutu/WoW-AdonnES-App/issues](https://github.com/tutosyoutu/WoW-AdonnES-App/issues)**

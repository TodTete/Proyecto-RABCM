# 📄 SADDO / Sistema de Administración de Documentos

Plataforma universitaria para la **gestión y organización de memorandos**, optimizando la administración interna mediante herramientas tecnológicas modernas.

---

📂 **Estructura del proyecto**

```
SADDO/
├─ App/
│  ├─ Controllers/
│  ├─ Models/
│  ├─ Config/
│  └─ Middleware/
├─ public/
│  ├─ images/
│  │  └─ logo.ico
├─ Views/
│  ├─ home.php
│  ├─ courses.php
│  └─ ...
├─ index.php
├─ composer.json
└─ README.md
```

---

🚀 **Instalación**
Clona el repositorio:

```bash
git clone https://github.com/TodTete/Proyecto-FRABCM.git
cd Proyecto-FRABCM
```

Configura el entorno:

1. Instala dependencias con Composer:

   ```bash
   composer install
   ```
2. Configura la base de datos MySQL en `App/Config/`.
3. Levanta el proyecto en **XAMPP/Apache**.
4. Accede desde el navegador:

   ```
   http://localhost/pproject/ublic
   ```

✅ Listo, ya podrás comenzar a usar SADDO.

🧪 **Cómo probar la PWA en local y desde el celular**

1. **Levanta un servidor local** sin depender de XAMPP (opcional, pero práctico para pruebas rápidas):
   ```bash
   php -S 0.0.0.0:8000 -t public
   ```
   Esto expone la aplicación en `http://localhost:8000` y la deja accesible desde otros dispositivos en la misma red.
2. **Abre la app en tu navegador de escritorio** visitando `http://localhost:8000` (o la ruta que utilices con XAMPP). Verás la invitación para instalar la aplicación cuando el service worker se haya registrado correctamente.
3. **Prueba la instalación como app de escritorio**: en Chrome o Edge selecciona el icono de "Instalar app" en la barra de direcciones y sigue los pasos.
4. **Accede desde tu celular** conectado a la misma red Wi-Fi que tu equipo. Usa la IP local de tu computadora (ej. `http://192.168.0.10:8000`). Si usas XAMPP, asegúrate de permitir conexiones en el firewall y apunta a `http://<tu-ip-local>/public`.
5. **Instala la PWA en Android/iOS**: abre la URL en Chrome (Android) o Safari (iOS). En Android el navegador mostrará un banner "Instalar aplicación" o el menú ⋮ → "Agregar a la pantalla principal". En iOS usa el botón de compartir → "Agregar a pantalla de inicio".
6. **Prueba el modo offline**: una vez instalada y con la aplicación abierta al menos una vez, activa el modo avión. Deberías ver el contenido en caché y, en caso de navegar a una página no disponible, se mostrará `offline.html` como respaldo.

> 💡 Consejo: para depurar el service worker abre las DevTools del navegador (F12) → pestaña "Application" → sección "Service Workers" y utiliza el botón "Update" o "Unregister" para forzar recargas.

---


✨ **Características**

* Registro y consulta eficiente de documentos
* Clasificación por áreas, fechas y responsables
* Control de acceso según rol de usuario
* Generación de reportes administrativos
* Interfaz web moderna e intuitiva

---

📖 **Uso**

1. Ingresa al sistema con tu usuario y contraseña.
2. Registra o consulta documentos según tu rol.
3. Filtra por área, fecha o responsable.
4. Descarga reportes administrativos listos para presentar.

---

🛠️ **Desarrollo futuro**

* Integración con firma electrónica institucional
* Notificaciones automáticas por correo o app móvil
* Buscador avanzado con filtros personalizados
* Panel de métricas y analítica de documentos
* Internacionalización (multi-idioma)
* Mejoras continuas para la experiencia PWA (notificaciones push, sincronización en segundo plano)

---

👤 **Autor**
Desarrollado por **@TodTete** / Ricardo Vallejo Sanchez para la Universidad Tecnológica de Tecamachalco, sin fines lucrativos

🔗 Repositorio oficial: [SADDO en GitHub](https://github.com/TodTete/Proyecto-FRABCM/)

---

📜 **Licencia**
Este proyecto está bajo la licencia MIT. Consulta el archivo **LICENSE** para más información.

---

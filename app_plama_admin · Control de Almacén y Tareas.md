PLAMA

# app_plama_admin

Control de Almacén, Herramientas e Itinerario

Sincronización local + pestañas activa

En turno: **0**

Pendientes: **0**

Completados: **0**

Buscar en Directorio de Empleados

🔍

Escribe palabras en cualquier orden (ej. "tovar neicer"). Presiona **Enter** para agregar el primer resultado.

Registrar empleado nuevo (fuera del directorio)

Listado Diario Activo

🔎

## ☁️ Sincronización entre dispositivos

1. En **console.firebase.google.com** crea un proyecto y una base **Realtime Database**.
2. En la pestaña **Reglas** permite lectura y escritura (`".read": true, ".write": true`) y publica.
3. En Configuración del proyecto → tu app web, copia el bloque `firebaseConfig` y pégalo aquí.
4. Usa **Copiar enlace de conexión** y ábrelo en los demás dispositivos: se conectan solos.
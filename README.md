# Actividad 4 - Entorno de equipo

## Información del Proyecto
* **Equipo:** Raúl, Eduardo, Alejandro y Sergio[cite: 1].
* **Módulo:** 5052 Diseño, Gestión, Producción y Publicación (DGPP)[cite: 1].

<img width="432" height="116" alt="image" src="https://github.com/user-attachments/assets/5119ee51-b529-4991-b4e6-79c95406e5c1" />

---

## Organización y Metodología de Trabajo
Para la gestión del proyecto hemos configurado un entorno de trabajo colaborativo siguiendo estos pasos[cite: 1]:

1. **Repositorio:** Creamos el repositorio con la plantilla de archivo README y el `.gitignore` correspondiente a nuestro motor de desarrollo, invitando a los miembros del equipo como colaboradores[cite: 1].
2. **Tablero de Tareas:** Configuramos un tablero en GitHub Projects con tres columnas (`Por hacer`, `En curso` y `Hecho`), distribuyendo las tareas iniciales de producción del juego[cite: 1].
3. **Flujo de Trabajo:** Trabajamos mediante commits y ramas de trabajo, registrando los avances y actualizando el estado de las tarjetas en el tablero[cite: 1].

---

## Configuración del Aviso Automático (Webhook)
Primero creamos el repositorio en GitHub con el nombre de nuestro juego, añadiendo el README y el archivo .gitignore correspondiente[cite: 1]. Después, invitamos a los demás integrantes del equipo como colaboradores y organizamos el tablero de tareas con las columnas de estado y las tarjetas del proyecto[cite: 1]. En Discord preparamos un canal de texto para los avisos y generamos un webhook copiando su enlace[cite: 1]. Luego fuimos a los ajustes del repositorio en GitHub, añadimos el webhook pegando la URL con «/github» al final y lo configuramos en formato application/json para el evento de push[cite: 1]. Finalmente, hicimos un commit en el repositorio y comprobamos que la notificación se enviaba automáticamente al canal del equipo[cite: 1].

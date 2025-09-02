# Funcionalidades
"El proyecto de chats esta inspirado en base al UI de WhatsApp y acomplado a la comunidad de la UAN"

La siguientes es una lista de las funcionalidades disponibles para el usuario de la aplicación:

1. # Pantalla de inicio/Login

Como recomendacion y buena practica el proyecto estara haciendo HASH a cada uno de las contrase;as que sean ignresadas en base al proyecto se realizara la decicion de cual es el mejor escenario para el HASH

Campos Usuario Campos: Usuario (@uan.edu.co) y Contraseña.

Función: Autenticación con credenciales institucionales (solo correos UAN). con el fin de que la app solo sea usada por miembros de la UAN 

Acción primaria: Done / Ingresar. Estado de carga mientras se 

Mensajería de error (propuesta): Usuario vacío / formato inválido / dominio no permitido; Credenciales incorrectas / cuenta bloqueada.

Casos de uso/flujo: válido → token de sesión → redirige a Chats;  Error → muestra feedback inline y permite reintentar; Persistir sesión hasta logout.

UI: Diseño minimalista, con input fields y botón de acceso.

2. # Pantalla de chats

Pantalla donde se mostrara una vista previa de gran parte de las funcionalidades y de como se estima que se vea cada una de las pantallas. 

Lista de conversaciones recientes con nombre, vista previa del último mensaje y hora/fecha.

Funciones principales:

Ver y abrir chats individuales, donde se observara informacion minima sobre le contacto o usuario. 

Acceder a chats archivados, donde se podran identificar chats donde no se desean vizualizar previamente en la pantalla de inicio. 

Crear nuevo chat (icono “+” o “ArchiveMore”). donde se identificaran diferentes acciones para tener un mayor uso de los contactos

UI: Inspirado en WhatsApp, con estilo limpio y organizado.

3. # Pantalla de chat invidual 

Cada uno de los chats se le dara su propia privacidad. 

Elementos:

Mensajes de texto enviados y recibidos, adicionalmente a eso se realizara un lectura de chats donde cada uno de los chats se leera apenas el usuario entre al chat privado. 

Archivos multimedia (imágenes, documentos, audio).

Funciones:

Enviar y recibir mensajes.

Compartir imágenes, audios, videos y documentos.

Marcar mensajes destacados.

UI: Burbuja de chat clásica.

4. # Perfil de usuario
Datos visibles:  Foto de perfil. Nombre y correo institucional cada uno de los usuarios podran ver info solo de los correos que pertenezcan a la UAN

Funciones:

Editar contacto. donde se podra realizar el cambio de nombre. Editar contacto : Name / Correo. Acciones Guardar / Cancelar; Eliminar contacto disponible desde la ficha.

Eliminar contacto.

Guardar información.

5. # Estados 

Elementos:

Publicar texto o multimedia como estado temporal. cada uno de los estados se usaran con la idea de que sean estados informativos, con fines de que todos los estudiantes tengan la informacion de la Universidad al dia sobre todo sobre los coodinadores y personas que manejen informacion relevante sobre la univeridad.

Ver estados de otros contactos.

Opciones de privacidad (quién puede ver mis estados).

Funciones:

Crear, editar y eliminar estados.

Gestionar visibilidad.

6. # Ajustes

Cuenta → Información personal, seguridad, privacidad.

Chats → Fondos, historial, copia de seguridad.

Notificaciones → Activar/desactivar alertas, sonidos, vibración, grupos.

Almacenamiento y datos → Control de consumo en Wi-Fi/datos móviles para fotos, videos, documentos y audios.

Ayuda → Soporte, preguntas frecuentes.

UI: Lista de opciones con iconos y submenús, clara y simple.

7. # Reglas De las funcionalidades 

Reglas funcionales clave (acceptance criteria)

- Login

Dado usuario @uan.edu.co y contraseña válida → entra a Chats.

Dado dominio no @uan.edu.co → error “Usa tu correo institucional”. 

- Lista de chats

Dado tap en conversación → abre Chat con histórico y fecha de corte visible (Fri, Jul 26). 

Dado “Archivados” → ver lista de archivados. 

- Chat

Dado envío de imagen → aparece miniatura + nombre archivo + tamaño (p.ej., png 2.8 MB). 

Dado “Buscar en el chat” → resalta coincidencias y permite saltar entre resultados. 

- Contacto/Perfil

Dado “Editar contacto” → formulario con Name y Correo, Guardar/Cancelar. 

Dado edición de Mi perfil → actualizar Nombre/Info/Avatar visibles en chats. 

- Estados

Dado “Agregar a mi estado” → publicar; Privacidad Estados define audiencia. 

- Notificaciones

Dado toggle “Mostrar notificaciones” OFF → silenciar todas; ON → seguir reglas de “mensajes” y “grupos”. 

- Almacenamiento y datos

Dado Wi-Fi ON → autodescarga según switches por tipo (Audio/Docs/Fotos/Videos).



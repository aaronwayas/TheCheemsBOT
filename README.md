# Bot de Moderación de Discord/ Bot casual

Este es un bot de moderación o casual de Discord que se ha creado utilizando discord.py, una biblioteca de Python para interactuar con la API de Discord.

## Comandos de Moderación

El bot tiene los siguientes comandos de moderación:

- `!ban`: Banea a un usuario del servidor. Requiere permisos de `ban_members`.
- `!unban`: Desbanea a un usuario del servidor. Requiere permisos de `ban_members`.
- `!kick`: Expulsa a un usuario del servidor. Requiere permisos de `kick_members`.
- `!mute`: Mutea a un usuario del servidor. Requiere permisos de `manage_roles`.
- `!unmute`: Desmutea a un usuario del servidor. Requiere permisos de `manage_roles`.
- `!clear`: Elimina mensajes en masa en un canal. Requiere el rol con administrador en permisos.

## Código del Bot

El código del bot se encuentra en el archivo `TheCheems` . Utiliza la biblioteca `discord.py` y se ha implementado con una serie de comandos y eventos para interactuar con Discord.

## Requisitos

El bot utiliza la librería `discord.py`, por lo que necesitarás instalarla para poder ejecutar el bot. Puedes instalarla utilizando el siguiente comando: `pip install discord.py`

Por favor, asegúrate de reemplazar `token = ""` con tu propio token de Discord antes de ejecutar el bot. También puedes personalizar los comandos y el mensaje de ayuda según tus necesidades.





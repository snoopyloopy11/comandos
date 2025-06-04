# Comandos disponibles solo para streamer y moderadores. 🎮  

### ▶️ `#star`  
- Enciende el bot para que empiece a procesar la información de Kukoro.  

### ℹ️ `#info`  
- Muestra información de la mazmorra:  
  - Jugadores registrados con `!kukoro`.  
  - Jugadores en misión con `!getinfo`.  
  - Total de enemigos registrados.  
  - Apartado de "faltantes" si alguien no usó `!getinfo`.  

### 📋 `#all`  
- Muestra todos los `!getinfo` (agrupados por enemigo).  

### 🔄 `#get`  
- Actualiza el `!getinfo` de todos los jugadores en partida (ideal para cambios de habilidades).  
  - *Nota:* No incluye jugadores no registrados a tiempo (requiere actualización manual).  

### 🔄 `#rst`  
- Reinicia toda la información registrada.  

### 🎯 `#ENEMIGO` (ej. `#lobo`, `#limo`, `#murciélago`, `#sombra`, etc.)  
- Muestra los jugadores que enfrentarán a dicho enemigo (ignora acentos).  

### 👾 `#enemigos` / `#mobs`  
- Agrupa a los jugadores por enemigo *sin* mostrar su `!getinfo`.  

### ❓ `#extra`  
- Jugadores sin enemigo asignado (Ya no es necesario, pero lo dejo por si HeyNau actualiza nuevos enemigos).  

### 🏷️ Comandos `#bestia` / `#maldito` / `#humanoide` / `#desconocido`  
- Agrupa enemigos por categoría/especie.  

### 🏃 `#agiles` y 🛡️ `#resistentes`  
- Jugadores que pueden luchar contra enemigos más ágiles o resistentes que ellos.  

### ⚠️ `#riesgo`  
- Muestra jugadores que ponen en riesgo la mazmorra.  

### 💀 `#kami`  
- Jugadores que matarán a su enemigo al morir.  

### 📊 `#b agiles` y `#b resistentes`  
- Lista todos los enemigos ágiles/resistentes de Kukoro.  

### 📌 `#b [enemigo]` (ej. `#b lobo`, `#b lizardo`)  
- Muestra estadísticas del enemigo. Ejemplo:  
   `#b lizardo`   > → 🦎 **Lizardo Lancero [Bestia]** ★ 🛡️6% ➤ 💥24% ➤ ⚡12% ★  

### ❌ `#f @jugador`  
- Elimina a un jugador (muerto) de las listas `#info` y `#ENEMIGOS`.  

### 🏁 `#fin`  
- El bot finaliza su chamba. 😆  

### 🔐 Comandos adicionales para autorizar a no-mods:  
- `#add @Xpersona` → Añade permisos.  
- `#remove @Xpersona` → Revoca permisos.  
- `#users` → Lista de usuarios autorizados.  

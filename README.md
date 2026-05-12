#### ⚡ Setup de Inicialización Automática
Haz clic en el desplegable para visualizar los comandos de configuración del entorno:

<summary><b>📂 COMANDOS DE INSTALACIÓN (TERMUX/VPS)</b></summary>
<br>

> [!TIP]
> **1. Sincronización de dependencias globales**
> ```bash
> pkg update && pkg upgrade -y && \ 
> pkg install git nodejs-lts ffmpeg imagemagick -y
> ```
> 
> **2. Clonación y despliegue del núcleo**
> ```
> git clone https://github.com/cristianborgesfernandez-hub/Diablo-MD
cd Diablo-MD
> ```
> 
> **3. Inyección de módulos y arranque**
> ```
> npm install && npm start
> ```  
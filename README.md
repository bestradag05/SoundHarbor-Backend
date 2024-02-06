# SoundHarbor-Backend

¡Bienvenido al repositorio del backend de SoundHarbor! Aquí encontrarás los pasos necesarios para instalar y ejecutar el proyecto en tu entorno local.

## Pasos de instalación

1. **Clonar el proyecto:**

   ```bash
   git clone https://github.com/bestradag05/SoundHarbor-Backend

2. **Ingresar a la carpeta del proyecto:**

   ```bash
   cd SoundHarbor-Backend

3. **Instalar dependencias:**

   ```bash
   npm install

4. **Opcional: Instalar nodemon para facilitar la ejecución del servidor:**

   ```bash
   npm install -g nodemon
   ```
   puedes ejecutar utilizando nodemos o utilizando node.

5. **Crear archivo .env:**

      Variables de la base de datos:  
            DB_HOST= # host de la bd   
            DB_USER= # usuario de la bd   
            DB_PASSWORD= # password de la bd   
            DB_DATABASE= # nombre de la base de datos   

Configuración de Mailtrap:  
      EMAIL_USER= # user de mailtrap   
      EMAIL_PASS= # password de mailtrap   
      EMAIL_HOST= # host de mailtrap   
      EMAIL_PORT= # puerto de mailtrap   

URL del frontend:  
      FRONTEND_URL= # ruta de tu frontend

6. **Ejecutar el servidor en modo desarrollo:**

```bash
npm run dev
```
¡Listo! Ahora tu servidor de SoundHarbor está en funcionamiento en tu entorno local. Si tienes alguna pregunta o problema, no dudes en abrir un problema en el repositorio. ¡Disfruta desarrollando con SoundHarbor!

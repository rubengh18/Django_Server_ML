# Django_Server_ML

Claro, aquí tienes las instrucciones para configurar un entorno virtual, instalar las dependencias desde `requirements.txt` y ejecutar el servidor de desarrollo de Django en Windows, suponiendo que ya tienes Python instalado:

1. **Configuración del entorno virtual y preparación del proyecto:**

   1. Abre tu terminal (puedes usar PowerShell o el Símbolo del sistema de Windows).
   2. Navega hasta tu proyecto con el comando `cd mi_proyecto`. Por ejemplo:

      ```bash
      cd mi_proyecto
      ```

   3. Crea un entorno virtual llamado `env`:

      ```bash
      python -m venv env
      ```

   4. Activa el entorno virtual:

      ```bash
      .\env\Scripts\activate
      ```

2. **Instalación de dependencias desde `requirements.txt`:**

   1. Asegúrate de que tu archivo `requirements.txt` esté ubicado en el directorio `mi_proyecto`.
   2. Instala las dependencias usando `pip`:

      ```bash
      pip install -r requirements.txt
      ```

3. **Iniciar el servidor de desarrollo de Django:**

   1. Una vez instaladas las dependencias, ejecuta el servidor de desarrollo de Django:

      ```bash
      python manage.py runserver
      ```

   2. Esto iniciará el servidor de desarrollo, y podrás acceder a tu proyecto desde un navegador en `http://localhost:8000/`.

Siguiendo estos pasos, estarás configurando un entorno virtual, instalando las dependencias necesarias y ejecutando tu proyecto Django en un entorno controlado y aislado en Windows.
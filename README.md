<img width="1880" height="1078" alt="image" src="https://github.com/user-attachments/assets/fcfe4fce-f9d6-4096-b445-2675678165f1" />


He utilizado docker compose up --build


Nginx se coloca delante de Flask/Gunicorn porque actúa como proxy inverso, recibiendo las peticiones del cliente y enviándolas a la aplicación Flask dentro de la red interna. Esto mejora la seguridad, evita exponer Flask directamente, y optimiza el rendimiento al manejar mejor las conexiones y servir archivos estáticos de forma más eficiente.

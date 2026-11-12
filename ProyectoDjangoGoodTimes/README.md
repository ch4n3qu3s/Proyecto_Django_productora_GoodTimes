# Productora GoodTimes - eventos

Proyecto Django con eventos, Clientes, Cotizacion y recursos.

## Instalación

1. Clonar el repositorio:

   ```bash
   git clone https://github.com/ch4n3qu3s/Proyecto_Django_productora_GoodTimes
   cd Proyecto_Django_productora_GoodTimes
   ```

2. Instalar las dependencias y activar el entorno:

   ```bash
   pipenv install -r requirements.txt
   pipenv shell
   ```

3. Copiar `.env.example` como `.env` y agregar una SECRET_KEY:

   ```bash
   copy .env.example .env
   ```

4. Aplicar las migraciones y crear un superusuario:

   ```bash
   py manage.py migrate
   py manage.py createsuperuser
   ```

5. Iniciar el servidor:

   ```bash
   py manage.py runserver
   ```
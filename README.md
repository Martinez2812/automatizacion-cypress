# automatizacion-cypress
automatizacion-smoketestbanco
# Automatización de Pruebas con Cypress

Este repositorio contiene pruebas automatizadas utilizando Cypress para la aplicación web Zero Bank.

## Configuración

1. Clona este repositorio en tu máquina local:


git clone https://github.com/martinez2812/automatizacion-cypress.git


2. Instala las dependencias:


npm install


3. Asegúrate de tener la aplicación web Zero Bank disponible en `http://zero.webappsecurity.com`.

## Ejecución de Pruebas

Para ejecutar las pruebas, utiliza el siguiente comando:


npm run test


## Descripción de las Pruebas

### 1. Validar página de inicio

- Verifica que la imagen del banco esté visible.
- Comprueba que el título "Online Banking" esté presente.

### 2. Prueba E2E - Transferencia de fondos

- Inicia sesión con las credenciales proporcionadas.
- Navega a la sección de transferencias.
- Selecciona cuentas de origen y destino.
- Ingresa una cantidad y una descripción.
- Envía la transacción y verifica que se haya realizado correctamente.

### 3. Prueba de validación de actualización del gráfico

- Inicia sesión nuevamente.
- Accede a la sección de mapas de dinero.
- Haz clic en el elemento del gráfico para validar su actualización.



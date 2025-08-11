# Escáner de Red - Proyecto de Redes

## Descripción

Esta aplicación permite escanear un rango de direcciones IP dentro de una red para identificar qué dispositivos están activos.

Utiliza comandos `ping` para comprobar la conectividad y realiza consultas DNS para obtener el nombre de cada equipo cuando es posible.

Cuenta con una interfaz gráfica simple y amigable desarrollada en Java Swing, donde se ingresan las IPs de inicio y fin del rango, y se muestran los resultados en una tabla junto con una barra de progreso.

## Funcionalidades

- Validación de direcciones IP ingresadas
- Escaneo secuencial de IPs mediante ping
- Resolución del nombre del host (DNS)
- Visualización de resultados con:
  - Dirección IP
  - Nombre del equipo
  - Estado (Conectado / No responde)
  - Tiempo de respuesta en milisegundos
- Barra de progreso del escaneo
- Botón para limpiar resultados y campos

## Tecnologías utilizadas

- Lenguaje: Java
- Interfaz gráfica: Swing
- Uso de comandos del sistema operativo (ping) para comprobar conectividad
- Resolución DNS con la clase InetAddress

## Cómo usar

1. Clonar o descargar el repositorio.
2. Compilar el archivo `NetworkScanner.java`:
3. Ejecutar la aplicación:
4. Ingresar el rango de IPs a escanear.
5. Presionar "Escanear" para iniciar.
6. Los resultados se mostrarán en la tabla con el progreso visible.
7. Presionar "Limpiar" para borrar resultados y campos.

## Nota

El programa utiliza comandos ping nativos del sistema operativo, por lo que debe ejecutarse con permisos normales y en un entorno compatible con ping.


# FPGA UART Contador Ascendente/Descendente

Este proyecto implementa un contador ascendente/descendente controlado por UART en una FPGA. El sistema permite enviar comandos a través de una interfaz UART para controlar el comportamiento del contador.

## Estructura del Proyecto

- **Receptor UART (`uart_rx`)**: Recibe datos UART y detecta el bit de inicio.
- **Controlador UART (`uart_controller`)**: Maneja la lógica de control basada en los datos recibidos.
- **Contador Ascendente/Descendente (`contador_asc_desc`)**: Realiza el conteo ascendente o descendente según la señal de control.
- **Nivel Superior (`top_level`)**: Integra los módulos anteriores y agrega un VIO para monitorear y controlar las señales.


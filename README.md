# Aplicación Cliente-Servidor con Java y Sockets TCP/IP

## Descripción
Este proyecto implementa una aplicación distribuida basada en el protocolo TCP/IP utilizando Java. Consiste en una arquitectura cliente-servidor en la que el cliente envía datos al servidor, el servidor los procesa y responde con un resultado.

El caso de uso implementado es el cálculo del **Índice de Masa Corporal (IMC)**, donde el cliente proporciona el peso y la altura, y el servidor devuelve el IMC calculado junto con un mensaje interpretativo.

## Características
- Comunicación basada en **Sockets TCP/IP**.
- Implementación de **hilos** para manejar múltiples clientes simultáneamente.
- Cálculo del IMC en el servidor y respuesta al cliente.

## Requisitos
- **Java JDK 8 o superior**
- **NetBeans 12.3** (opcional, puedes usar otro IDE)

## Instalación y Ejecución
### 1. Clonar el repositorio
```sh
git clone https://github.com/tuusuario/tu-repositorio.git
cd tu-repositorio
```

### 2. Compilar y ejecutar el servidor
```sh
javac ServidorTCP.java
java ServidorTCP
```

### 3. Compilar y ejecutar el cliente
```sh
javac ClienteTCP.java
java ClienteTCP
```

## Uso
1. **Ejecutar el servidor** antes que los clientes.
2. **Ejecutar uno o más clientes** y proporcionar el peso y la altura.
3. El servidor calculará el IMC y enviará la respuesta al cliente.
4. El cliente mostrará el IMC calculado y su interpretación.

### Ejemplo de interacción
```
Ingrese su peso (kg): 70
Ingrese su altura (m): 1.75
IMC: 22.86
Estado: Peso normal
```

## Estructura del Proyecto
```
📂 tu-repositorio
 ┣ 📜 ServidorTCP.java
 ┣ 📜 ClienteTCP.java
 ┣ 📜 README.md
```

## Contribución
1. Haz un fork del proyecto.
2. Crea una nueva rama (`git checkout -b feature-nueva-funcionalidad`).
3. Realiza tus cambios y haz commit (`git commit -m 'Agrega nueva funcionalidad'`).
4. Haz push a la rama (`git push origin feature-nueva-funcionalidad`).
5. Abre un Pull Request.

## Licencia
Este proyecto se distribuye bajo la licencia MIT. ¡Siéntete libre de usarlo y modificarlo!

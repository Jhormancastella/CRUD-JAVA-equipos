
# 🎯 Desafío: CRUD-JAVA-equipos ⚽

## 📌 Descripción

Este proyecto implementa un sistema **CRUD** para gestionar equipos de fútbol utilizando **Java**, **Jackson** y archivos **JSON** para la persistencia de datos. El objetivo es permitir al usuario crear, listar, actualizar y eliminar equipos de fútbol, junto con sus jugadores.

---

## 🛠️ Tareas

1. **Usa Jackson** para manejar la serialización y deserialización de datos en formato JSON.
2. **Implementa un CRUD** para gestionar equipos de fútbol y sus jugadores.
3. **Persiste los datos** en un archivo JSON (`equipos.json`) para garantizar la persistencia entre ejecuciones.
4. **Crea un menú interactivo** que permita al usuario realizar operaciones CRUD.

---

## 🚀 Estructura del Proyecto

### 📂 Clases Principales

1. **Modelos:**
   - `Equipo`: Define los atributos y métodos para representar un equipo de fútbol.
   - `Jugador`: Define los atributos y métodos para representar a un jugador de fútbol.

2. **Servicio:**
   - `EquipoService`: Implementa la lógica del CRUD utilizando un `HashMap` y persistencia en JSON.

3. **Cliente:**
   - `Main`: Proporciona un menú interactivo para que el usuario gestione los equipos de fútbol.

4. **Archivo de Datos:**
   - `equipos.json`: Almacena los datos de los equipos y jugadores en formato JSON.

---

## 🚀 Instalación y Configuración

### 📋 Requisitos Previos

- **Java Development Kit (JDK) 17 o superior**
- **Maven** (para gestionar las dependencias)
- **Git instalado en tu sistema**

### 📥 Clonar Repositorio

```bash
git clone https://github.com/Jhormancastella/CRUD-JAVA-equipos.git
```

### 🛠️ Compilar y Ejecutar

1. Abre una terminal en la carpeta del proyecto.

```bash
mvn clean install
```

3.Ejecuta el programa:

```bash
mvn exec:java -Dexec.mainClass="com.crud.Main"
```

---

## 🛠️ Uso

1. **Menú Principal:**
   - El programa mostrará un menú interactivo con las siguientes opciones:
     - **Crear un equipo**: Ingresa los datos del equipo y sus jugadores.
     - **Listar equipos**: Muestra todos los equipos registrados.
     - **Actualizar un equipo**: Modifica los datos de un equipo existente.
     - **Eliminar un equipo**: Elimina un equipo por su ID.
     - **Salir**: Termina la ejecución del programa.

2. **Persistencia de Datos:**
   - Los datos se guardan automáticamente en el archivo `equipos.json` después de cada operación.

---

## 📋 Ejemplo de Ejecución

```plaintext
GESTIÓN DE EQUIPOS DE FÚTBOL
1. Agregar equipo
2. Listar equipos
3. Actualizar equipo
4. Eliminar equipo
5. Salir
Selecciona una opción: 1

Nombre del equipo: Equipo A
Ciudad que representa: Ciudad A
Fecha de fundación: 2000-01-01
Presidente del equipo: Presidente A
¿Cuántos jugadores deseas agregar? 2

Número de dorsal: 10
Nombre del jugador: Jugador A
Ciudad del jugador: Ciudad A
Edad del jugador: 25

Número de dorsal: 7
Nombre del jugador: Jugador B
Ciudad del jugador: Ciudad B
Edad del jugador: 28

✅ Equipo creado con ID: 1
```

---

## 📋 Características

- **Soporte para múltiples equipos**: Cada equipo puede tener una lista de jugadores asociados.
- **Persistencia en JSON**: Los datos se almacenan en un archivo JSON (`equipos.json`) para mantener la información entre ejecuciones.
- **Interfaz interactiva**: Un menú sencillo permite al usuario realizar operaciones CRUD sin complicaciones.
- **Uso de Jackson**: La biblioteca Jackson se utiliza para la serialización y deserialización de datos JSON.

---

## 🚨 Estado del Ejercicio

- **Culminado.**

---

## 👤 Autor

- **Jhorman Jesús Castellanos Morales**

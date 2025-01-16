
# Consultas MongoDB - Restaurantes en NYC

📄 **Descripción**
Este proyecto se centra en la creación y ejecución de consultas MongoDB para una colección de restaurantes en la ciudad de Nueva York. El objetivo es analizar y manipular los datos de manera eficiente utilizando comandos de MongoDB. La colección incluye campos como `restaurant_id`, `name`, `borough`, `cuisine`, `address` y `grades`.

---

💻 **Tecnologías Utilizadas**
- MongoDB
- JSON para la representación de datos

---

📋 **Requisitos**
- MongoDB instalado y en ejecución
- Terminal o MongoDB Compass para ejecutar las consultas

---

🛠️ **Instalación**
1. Clona el repositorio:
   ```bash
   git clone <URL_DEL_REPOSITORIO>
   ```
2. Importa el conjunto de datos en tu instancia de MongoDB:
   ```bash
   mongoimport --db restaurants --collection restaurants --file restaurantes.json
   ```
3. Abre `restaurantes_queries.json` para ejemplos de consultas y ejecútalas en MongoDB.

---

📁 **Estructura del Proyecto**
- `restaurantes.json`: Archivo JSON con el conjunto de datos de los restaurantes en NYC.
- `restaurantes_queries.json`: Archivo JSON con las consultas MongoDB documentadas para análisis y manipulación.

---

📚 **Documentación**
Para más detalles sobre la sintaxis de consultas y operaciones de MongoDB, consulta la [Documentación Oficial de MongoDB](https://www.mongodb.com/docs/).

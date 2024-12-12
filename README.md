# AdminSQLete3: Gestión y Análisis de Datos Inmobiliarios

## 📋 Descripción
AdminSQLete3 es un proyecto desarrollado en Jupyter Notebook diseñado para analizar y gestionar datos en este ejemplo datos inmobiliarios almacenados en una base de datos SQLite. Este proyecto proporciona herramientas prácticas para consultar, actualizar y visualizar datos de propiedades, lo que facilita la toma de decisiones basadas en datos.

### Características principales:
Este repositorio ofrece una guía practiaca para:
- Conexión interactiva a una base de datos SQLite para explorar y actualizar datos.

---

## 🛠️ Requisitos del Entorno

### Librerías necesarias:
El notebook utiliza las siguientes librerías de Python:
- **`pandas`**: Manipulación y análisis de datos estructurados.
- **`numpy`**: Operaciones matemáticas y estadísticas.
- **`matplotlib`**: Generación de gráficos y visualizaciones.
- **`sqlite3`**: Interacción con bases de datos SQLite.

### Configuración del entorno Python

#### 1. Instalar Python
Descarga e instala Python (versión 3.7 o superior) desde la [página oficial de Python](https://www.python.org/downloads/).

#### 2. Crear un entorno virtual
Se recomienda usar un entorno virtual para gestionar las dependencias del proyecto:
```bash
# Crear un entorno virtual
python -m venv env

# Activar el entorno virtual
source env/bin/activate   # En Windows: .\env\Scripts\activate
```

#### 3. Instalar dependencias
Una vez que el entorno esté activado, instala las librerías necesarias:
```bash
pip install pandas numpy matplotlib
```

Para verificar que todo esté instalado correctamente:
```bash
pip list
```

---

## 🚀 Cómo Ejecutar

### 1. Clonar el Repositorio
```bash
git clone https://github.com/JavierVaronBueno/AdminSQLete3.git
cd AdminSQLete3
```

### 2. Configurar la Base de Datos
Asegúrate de que el archivo de base de datos SQLite (`db.sqlite3`) esté ubicado en la ruta correcta. Actualiza en el notebook la ruta, en el ejemplo es:
```plaintext
../../chat-Interface/db.sqlite3
```

### 3. Ejecutar el Notebook
1. Inicia el servidor de Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Abre el archivo `adminSQLete3_main.ipynb` en el navegador.
3. Sigue las instrucciones dentro del notebook, ejecutando las celdas en orden para:
   - Conectar y explorar la base de datos.
   - Realizar consultas y análisis.
   - Actualizar registros según sea necesario.
   - Visualizar resultados.

---

## 📂 Estructura del Código

El notebook está organizado en las siguientes secciones:

1. **Configuración de la Base de Datos**:
   - Incluye la clase `DatabaseViewer`, que proporciona métodos para conectarse, realizar consultas personalizadas y ejecutar actualizaciones SQL en la base de datos.

2. **Consultas de Datos**:
   - Ejemplos prácticos de cómo listar tablas y explorar datos, incluyendo estructuras y métricas clave.

3. **Análisis y Visualización de Datos**:
   - Cálculos como el precio promedio por metro cuadrado y agrupaciones por número de habitaciones.
   - Gráficos generados con `matplotlib` para mostrar tendencias en los precios y tamaños de propiedades.

4. **Actualizaciones en la Base de Datos**:
   - Incluye ejemplos de actualizaciones de registros utilizando comandos SQL (`UPDATE`).
   - Muestra cómo verificar los cambios realizados en la base de datos.

5. **Resultados y Exportación**:
   - Salidas tabulares y gráficas listas para ser exportadas o utilizadas en informes.

---

## 🎯 Resultados Esperados

### Salidas Generadas
El notebook genera los siguientes tipos de resultados:
- **Tablas resumen**:
  - Promedio de precios, tamaño y costo por metro cuadrado de propiedades.
  - Datos agrupados por ubicación y número de habitaciones.

### Ejemplo de Salida Tabular:
| Número de Habitaciones | Cantidad de Propiedades | Precio Promedio | Tamaño Promedio (m²) | Precio por m² |
|-------------------------|-------------------------|-----------------|-----------------------|---------------|
| 1                      | 6                       | 265,000         | 158.8                 | 1,965.67      |

### Ejemplo de Gráfico:
- Un gráfico de barras que compara el precio promedio por número de habitaciones.

---

## 📝 Licencia

Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo `LICENSE` para más información.



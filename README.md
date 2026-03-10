# 🤖 Inteligencia Artificial - Repositorio de Trabajos Prácticos

Bienvenido/a al repositorio oficial para la cátedra de **Inteligencia Artificial**. Este espacio está diseñado para centralizar los recursos, datasets y notebooks utilizados a lo largo del cursado.

**Integrantes:**
* **Irina Lauritto**
* **Agustín Grioni**

---

## 📂 Estructura del Proyecto

Para garantizar que los notebooks sean ejecutables y no pierdan sus dependencias, el repositorio se organiza de la siguiente manera:

* **`1_datos/`**: Contiene los conjuntos de datos (archivos `.csv`, `.json`, etc.) requeridos para los análisis.
* **`Notebooks/`**: Archivos `.ipynb` con el desarrollo de las actividades, organizados por unidad o trabajo práctico.
* **`Scripts/`**: (Opcional) Funciones auxiliares en Python.

---

## 🚀 Guía de Uso en Google Colab

Debido a la naturaleza volátil de las sesiones de Google Colab, hemos implementado una solución para que cualquier persona que abra los notebooks pueda ejecutarlos sin errores de "archivo no encontrado":

### 1. Carga de Datos Automática
En la primera celda de cada notebook, se incluye un comando para clonar este repositorio. Esto permite que el entorno de Colab tenga acceso inmediato a la carpeta `1_datos/`.

```python
# Ejecutar esta celda para descargar los archivos necesarios
!git clone [https://github.com/](https://github.com/)[TU_USUARIO_GITHUB]/[NOMBRE_REPOSIROTIO].git
%cd [NOMBRE_REPOSIROTIO]

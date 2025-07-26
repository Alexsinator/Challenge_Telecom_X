# Analisis sobre cancelaciones de Clientes - TelecomX

Este repositorio contiene un análisis exploratorio sobre los factores que influyen en los clientes 
en la cancelación de servicios por parte de los clientes de la empresa TelecomX.
Se analizaron datos proporcionados en la base para identificar oportunidades de mejora
que ayuden a reducir la cancelación de clientes.

---

## Contenido

TelecomX_Data.json: Base de Datos utilizados para el análisis.
TelecomX_LATAM.ipynb: Notebook de análisis con codigo Python (Hecho en Colab).
TelecomX_diccionario.md: Diccionario de datos.

##Limpieza y Tratamiento de datos

- Se eliminaron filas vacias y valores nulos.
- Se reemplazaron binarios por "Si" y "No", para facilitar el análisis
- Se clasificaron variables continuas

### 1. Adulto Mayor vs Cancelación  
Explora si los adultos mayores tienen mayor probabilidad de cancelar el servicio.  
📄 `adulto_mayor_vs_cancelacion.jpg`

### 2. Forma de Pago  
Analiza qué métodos de pago se asocian con mayor retención.  
📄 `formas_de_pago.jpg`

### 3. Género vs Cancelación  
Compara la tasa de cancelación entre hombres y mujeres.  
📄 `genero_vs_cancelacion.jpg`

### 4. Permanencia vs Tipo de Contrato  
Agrupa a los clientes por su rango de permanencia y tipo de contrato.  
📄 `permanencia_vs_contrato.jpg`

### 5. Servicios Contratados  
Visualiza la relación entre cancelación:

### 6. Tiempo de Permanencia  
Distribución general del tiempo con el servicio contratado.  

### 7. Tipo de Contrato  
Comparativa de cancelaciones por tipo de contrato.  


### 8. Tipo de Contrato vs Cancelación  
Tiempo promedio de permanencia según el tipo de contrato.  

---

## 🔍 Conclusiones Clave

- Los **contratos mensuales** tienen una mayor tasa de cancelación.
- Los pagos **domiciliados a tarjeta de crédito** muestran menor churn.
- Los **adultos mayores** cancelan con más frecuencia.
- No hay gran diferencia entre géneros, aunque las mujeres cancelan ligeramente más.

---

## ✅ Recomendaciones

1. Promover contratos de largo plazo al momento de la contratación.
2. Incentivar el pago domiciliado con descuentos o promociones.
3. Reconocer la permanencia de clientes con cupones o beneficios al cumplir un año.
4. Implementar campañas de fidelización enfocadas en segmentos vulnerables al churn.

## 💡 Autor

Alejandro Alanis  
📫 Contacto: [ale.x.israel@hotmail.com]

---

## 📎 Licencia

Este proyecto es solo con fines educativos. Proporcionado por Alura LATAM.

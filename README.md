# Algoritmo de Curvas Elípticas con Versión Cuántica de Shor

Este repositorio contiene tres **notebooks** que desarrollan y comparan la implementación del algoritmo de curvas elípticas bajo diferentes enfoques: clásico, cuántico y un modelo híbrido. El objetivo es mostrar cómo puede modificarse el algoritmo de Shor para trabajar sobre curvas elípticas, y explorar su comportamiento en cada escenario.

---

## 📂 Contenido del repositorio

1. **`Curvas elípticas clásicas.ipynb`**  
   Implementación clásica del algoritmo de curvas elípticas.  
   - Operaciones sobre puntos en una curva elíptica definida sobre un cuerpo finito.  
   - Multiplicación escalar, orden de puntos y verificación de propiedades.  
   - Generación de ejemplos paso a paso con cálculos manuales y programáticos.  

2. **`Algoritmo Cuántico.ipynb`**  
   Versión cuántica adaptada del **algoritmo de Shor** para curvas elípticas.  
   - Construcción del circuito cuántico.  
   - Codificación de la multiplicación escalar reversible.  
   - Uso de la Transformada de Fourier Cuántica (QFT) para estimar órdenes de puntos.  
   - Tablas de salidas que muestran cómo las amplitudes se cancelan y permanecen solo los múltiplos del orden.  

3. **`Curvas elípticas Híbrido.ipynb`**  
   Enfoque **híbrido** que combina cálculos clásicos y cuánticos.  
   - Preprocesamiento clásico de los puntos en la curva.  
   - Ejecución de subrutinas cuánticas (estimación de orden).  
   - Post-procesamiento clásico (uso de fracciones continuas, gcd, etc.).  

---

## ⚙️ Requisitos de instalación

Antes de ejecutar los notebooks, instala las dependencias necesarias:

```bash
pip install -r requirements.txt

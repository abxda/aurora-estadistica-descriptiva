# ☕ Estadística Descriptiva con Python — Aurora Coffee

Cuadernos interactivos de **Estadística Descriptiva** (clave ICD-013) de la **Universidad Aurora**,
nivel licenciatura. Todo el curso gira en torno a un caso único —la cadena de cafeterías
**Aurora Coffee**— y avanza en tres movimientos acumulativos: **describir → estimar → decidir**.

Los cuadernos están listos para ejecutarse en **Google Colab** sin instalar ni descargar nada:
los datos se generan dentro del propio cuaderno.

## 🚀 Abre los cuadernos en Colab

| Cuaderno | Contenido | Abrir |
| --- | --- | --- |
| **Práctica 1** — Estadística Descriptiva | Población y muestra · tipos de variable · tablas de frecuencia · gráficos · media/mediana/moda · dispersión · cuartiles y boxplot | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/abxda/aurora-estadistica-descriptiva/blob/main/Practica_1_Estadistica_Descriptiva_Aurora.ipynb) |
| **Práctica 2** — De la muestra a la decisión | Distribución de muestreo · error estándar · Teorema Central del Límite · intervalos de confianza · pruebas de hipótesis (Z y t) · errores tipo I y II | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/abxda/aurora-estadistica-descriptiva/blob/main/Practica_2_Inferencia_y_Pruebas_Aurora.ipynb) |

> Si tu usuario o repositorio difieren, ajusta `abxda/aurora-estadistica-descriptiva` en los
> enlaces de arriba.

## ▶️ Cómo usarlos

1. Haz clic en **Open in Colab** del cuaderno que quieras.
2. Ejecuta las celdas **en orden**, de arriba hacia abajo (botón ▶ o `Shift + Enter`).
3. Empieza siempre por el **Paso 0**, que carga las librerías y genera los datos.
4. Lee las celdas de texto: cada concepto se explica antes de ejecutarlo y se interpreta después.

No hay que instalar nada. Los cuadernos usan solo librerías estándar de ciencia de datos
(`numpy`, `pandas`, `matplotlib`, `scipy`), ya preinstaladas en Colab.

## 🧭 El hilo: Aurora Coffee

Una sola cadena de cafeterías genera todos los datos del curso (peso de las bolsas de café,
propinas, satisfacción, sucursal, método de pago). La misma pregunta escala a lo largo de las
tres sesiones:

1. **Describir** (Sesión 1) — resumir lo que tenemos: ¿cómo son nuestros datos?
2. **Estimar** (Sesión 2) — saltar de la muestra a la población con intervalos de confianza:
  ¿cuánto pesan *en realidad* todas las bolsas?
3. **Decidir** (Sesión 3) — juzgar una afirmación con una prueba de hipótesis:
  la empresa dice que sus bolsas pesan 500 g… ¿la evidencia lo respalda?

## 📚 Contenido por cuaderno

**Práctica 1 — Estadística Descriptiva**

- Población vs. muestra · parámetro vs. estadístico
- Tipos de variable (cualitativa/cuantitativa, nominal/ordinal, discreta/continua)
- Tablas de frecuencia (absoluta, relativa, acumulada)
- Visualización: barras, pastel, pictograma
- Tendencia central: media, mediana, moda (y el efecto de los valores atípicos)
- Dispersión: rango, varianza, desviación estándar
- Posición y forma: cuartiles, percentiles y diagrama de caja (boxplot)

**Práctica 2 — Inferencia y Pruebas de Hipótesis**

- Distribución de muestreo y error estándar
- Teorema Central del Límite (con simulación)
- Estimadores e intervalos de confianza para la media y la proporción
- Qué significa realmente "95% de confianza" (simulación de cobertura)
- Pruebas de hipótesis: H₀/H₁, estadístico de prueba, p-valor, nivel de significancia
- Errores tipo I y II · pruebas de una y dos colas · los 5 pasos
- Estadístico Z vs. t de Student · conexión intervalo ↔ prueba

## 🗂️ Estructura del repositorio

```
Practica_1_Estadistica_Descriptiva_Aurora.ipynb   # cuaderno Sesión 1
Practica_2_Inferencia_y_Pruebas_Aurora.ipynb      # cuaderno Sesiones 2-3
README.md
```

## ⚙️ Ejecución local (opcional)

Si prefieres correrlos fuera de Colab:

```bash
pip install numpy pandas matplotlib scipy notebook
jupyter notebook
```

## ✍️ Autor

**Dr. Abel Alejandro Coronado Iruegas** — Universidad Aurora.
Material docente para la asignatura Estadística Descriptiva (ICD-013).

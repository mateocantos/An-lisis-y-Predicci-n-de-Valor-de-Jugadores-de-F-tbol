# ⚽ Análisis y Predicción de Valor de Jugadores de Fútbol
### Autor: Mateo Cantos

Este proyecto de `data science` tiene como objetivo analizar los factores que influyen en el valor de mercado de los jugadores de fútbol de las cinco ligas más importantes de Europa. A través de un análisis exploratorio y la construcción de un modelo predictivo, se busca ofrecer `insights` valiosos para que un club de fútbol pueda tomar decisiones más informadas en el mercado de transferencias.

---

### ❓ Preguntas Clave del Análisis

El proyecto se centró en responder las siguientes preguntas de negocio:
1.  **Distribución de Jugadores:** ¿Cómo se distribuyen los jugadores por posición?
2.  **Valor por Posición:** ¿Cuál es la posición de ataque más valiosa en el mercado?
3.  **Edad y Precio:** ¿Cómo influye la edad de un jugador en su precio de mercado?
4.  **Liga y Precio:** ¿El precio de un jugador está influenciado por la liga en la que juega?
5.  **Agentes y Precio:** ¿Los representantes influyen en el valor de un jugador?

---

### 📊 Análisis Exploratorio de Datos (EDA)

Durante el análisis, se obtuvieron los siguientes hallazgos clave:
- Los jugadores entre **20 y 25 años** tienen el valor de mercado más alto.
- La **Premier League (EPL)** tiene el precio promedio de jugadores más elevado.
- La posición de **ataque** es, en promedio, la más valiosa.
- Se observó una correlación entre el **agente** y el precio del jugador, aunque no es el factor más determinante.

---

### 🤖 Modelo Predictivo (Machine Learning)

Se construyó un modelo de `Random Forest Regressor` para predecir el precio de un jugador basándose en sus características.

- **Variables (Features) Usadas:** Edad, altura, posición, y liga.
- **Resultados del Modelo:**
    - **R² Score:** 0.35 (El modelo explica el 35% de la variabilidad en el precio).
    - **MAE:** 6.56 M€ (El error promedio de la predicción es de 6.56 millones de euros).

El modelo demuestra que, incluso con un conjunto de datos limitado, es posible predecir el valor de un jugador con una precisión notable, lo que lo convierte en una herramienta útil para la toma de decisiones.

---

### 🛠️ Herramientas y Tecnologías

- **Lenguaje:** Python
- **Librerías:** Pandas, Matplotlib, Seaborn, Scikit-learn
- **Entorno:** Jupyter Notebook / Google Colab

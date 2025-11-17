# 🎰📊 Ruleta-Analyzer: Simulador y Analizador de Ruleta en Rust

**Ruleta-Analyzer** es una herramienta de consola (CLI) de alto rendimiento desarrollada en **Rust** para simular millones de giros de ruleta (formato americano: 0, 00, 1-36) y analizar la distribución estadística de los números resultantes.

Este proyecto es ideal para estudiar patrones de frecuencia, probar la aleatoriedad de los generadores de números pseudoaleatorios o simplemente explorar cómo se comporta la ley de los grandes números en un contexto de juego de azar.

## ⚡ Características Principales

* **Alto Rendimiento:** Construido en Rust para una velocidad de ejecución excepcional y un uso eficiente de la memoria, crucial para simular millones de iteraciones.
* **Simulación de Ruleta:** Genera números aleatorios que incluyen el formato americano (00), cubriendo 38 posibles resultados (0, 00, 1 a 36).
* **Análisis de Frecuencia:** Identifica y muestra el número que ha aparecido con **MENOR frecuencia** en la simulación.
* **Contador de Iteraciones:** El número de simulaciones está preestablecido en **10,000,000** (diez millones), pero puede ser fácilmente ajustado en el código fuente (`src/main.rs`).
* **Estudio de Aleatoriedad:** Útil para pruebas de uniformidad y distribución estadística en grandes muestras.

## 🛠️ Tecnologías Utilizadas

* **Rust:** El lenguaje de programación principal, elegido por su seguridad de memoria y rendimiento.
* **Crates:** Utiliza el sistema de módulos estándar de Rust (`rand` para la generación de números aleatorios).
* **CLI (Command Line Interface):** Herramienta de ejecución directa en la terminal.

## 🚀 Cómo Empezar

Necesitas tener **Rust y Cargo** (el gestor de paquetes de Rust) instalados en tu sistema.

### 1. Clonar el repositorio

```bash
git clone [https://github.com/santiagourdaneta/Ruleta-Analyzer.git](https://github.com/santiagourdaneta/Ruleta-Analyzer.git)
cd Ruleta-Analyzer

2. Compilar y Ejecutar
Usa cargo run para compilar y ejecutar el proyecto en un solo paso. La ejecución es rápida debido a la naturaleza de Rust.

cargo run --release # Usar --release para la máxima optimización de velocidad

El programa te mostrará el resultado del análisis estadístico directamente en la consola.

3. Modificar la Simulación
Para cambiar el número de simulaciones (actualmente 10 millones), edita la constante de iteraciones en el archivo principal (src/main.rs) y vuelve a compilar (cargo run).

🤝 Contribuciones
Si deseas mejorar el análisis (ej. añadir media, desviación estándar, identificar el número más frecuente), ¡las Pull Requests son bienvenidas!

👥 Autor
Santiago Urdaneta

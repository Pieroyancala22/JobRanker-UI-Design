# 🎯 JobRanker - Dashboard de Reclutamiento Inteligente

Este repositorio contiene el caso de estudio y la documentación del diseño UX/UI para **JobRanker**, una plataforma web responsive orientada a la gestión y análisis automatizado de currículums.

---

## 🔗 Enlaces del Proyecto
* **[Ver Prototipo Interactivo en Figma](PEGA_AQUÍ_EL_ENLACE_DE_TU_PROTOTIPO_DE_FIGMA)**
* **[Ver Archivo de Diseño en Figma](PEGA_AQUÍ_EL_ENLACE_DE_TU_ARCHIVO_DE_FIGMA)**

---

## 📋 Documentación de Requerimientos

### Historias de Usuario (User Stories)
* **HU01 - Dashboard Visual:** Como Reclutador, quiero visualizar gráficos interactivos del porcentaje de coincidencia de los candidatos para tomar decisiones de contratación más rápidas.
* **HU02 - Experiencia Mobile:** Como Reclutador, necesito revisar el estado de las postulaciones desde mi dispositivo móvil con una interfaz adaptada y legible.

### Wireframes (Estructura Inicial)
![Wireframe de Baja Fidelidad](img/wireframe.png)

---

## 🎨 Buenas Prácticas Aplicadas en Figma

### 1. Auto-layout Avanzado
Toda la interfaz fue construida utilizando contenedores flexibles (Auto-layout). Esto garantiza que las tarjetas de candidatos, tablas de datos y menús de navegación se adapten de forma exacta al contenido sin romper la estructura visual.

### 2. Sistema de Componentes y Variantes
Se diseñó un sistema de diseño atómico escalable:
* **Botones:** Variantes para estados Default, Hover, Focused y Disabled.
* **Candidate Cards:** Componentes reutilizables con propiedades de texto e instancias configurables.

### 3. Diseño Totalmente Responsive
Se crearon layouts específicos para dos resoluciones críticas que validan el comportamiento responsivo utilizando *Constraints* y *Auto-layout wrap*:
* **Desktop:** Pantalla completa de 1440px optimizada para monitores de oficina.
* **Mobile:** Versión compacta de 390px adaptando barras de navegación en menús hamburguesa y apilando las tarjetas de candidatos verticalmente.

---

## 📸 Capturas del Diseño Final

| Versión Desktop | Versión Mobile |
| :---: | :---: |
| ![Desktop Version](img/desktop.png) | ![Mobile Version](img/mobile.png) |

---
*Diseñado por Piero Yancala - 2026*

# 🧮 Calculadora de Nota de Acceso a la Universidad (Comunitat Valenciana)

Esta herramienta permite calcular **la Nota de Acceso a la Universidad (NAU)** y la **Nota de Admisión Total (NAT)** para el sistema educativo de la **Comunitat Valenciana**, de acuerdo con el modelo oficial que combina la media de Bachillerato, la nota de la fase general de la EBAU y las materias voluntarias ponderadas.

---

## 🌐 Acceso en línea

👉 **Usa la calculadora directamente aquí:**  
[https://herrprofesor.github.io/index-card.html](https://herrprofesor.github.io/index-card.html)

*(Funciona totalmente en el navegador, no guarda datos y no requiere inicio de sesión.)*

---

## 🧩 Cómo funciona

### 🏫 1.º y 2.º de Bachillerato
- Introduce las notas de las materias de cada curso.  
- En los campos con varias opciones (como “Inglés / Francés” o “Biología / Dibujo Técnico / Tecnología”) selecciona la materia correspondiente.  
- Puedes escribir los nombres de las **optativas** libremente.  
- La **media de cada curso** y la **media global de Bachillerato** se calculan automáticamente.

### 🎓 Fase general de la EBAU
- Introduce tus calificaciones en Castellano, Valenciano, Idioma, Historia/Filosofía y Matemáticas.  
- La aplicación calcula la **media de la fase general** (EBAU) automáticamente.

### 💪 Fase voluntaria
- Puedes añadir hasta **dos materias voluntarias**.  
- Indica el nombre de cada materia, su nota y su ponderación (**0.1 o 0.2**, por defecto 0.2).  
- Se mostrará la contribución ponderada de cada una (“Voluntaria 1” y “Voluntaria 2”).

---

## 🧾 Cálculos mostrados

El sistema presenta los siguientes resultados:

| Cálculo | Descripción |
|----------|-------------|
| **Media Bachillerato** | Promedio de todas las materias de 1.º y 2.º. |
| **Media Fase General** | Promedio de las materias comunes de la EBAU. |
| **Nota de acceso (NAU)** | `0.6 × Bachillerato + 0.4 × Fase General` |
| **Voluntaria 1 / Voluntaria 2** | Ponderaciones de las materias optativas de la fase voluntaria. |
| **Nota total (NAT)** | `NAU + (Pond1 × Vol1) + (Pond2 × Vol2)` |

Todos los resultados se muestran con **tres decimales**.

---

## 🧹 Botones de limpieza

- Cada columna (1.º, 2.º y EBAU) incluye un botón para **limpiar solo esa sección**.  
- El botón **“Limpiar todo”** reinicia completamente el formulario.  

---

## ⚙️ Detalles técnicos

- Aplicación desarrollada en **HTML + CSS + JavaScript puro** (sin dependencias externas).  
- Cálculos realizados de forma **local en el navegador**.  
- Diseño **responsive** con tarjetas y sombreado suave.  
- Compatible con los principales navegadores (Chrome, Firefox, Edge, Safari).

---

## 📄 Créditos

Desarrollado para uso educativo y orientación académica.  
Proyecto mantenido por **herrprofesor**.

---

### 🔗 Enlace directo
➡️ [Abrir calculadora ahora](https://herrprofesor.github.io/index-card.html)

# 🧮 Calculadora de Nota de Acceso a la Universidad (Comunitat Valenciana)

Esta herramienta permite calcular fácilmente la **nota media de Bachillerato** y la **nota de acceso a la universidad (EBAU / PAU)** según el sistema de la **Comunitat Valenciana**.  
Funciona completamente **en el navegador**, sin necesidad de registro ni almacenamiento de datos personales.

🌐 Puedes usar la calculadora online aquí:  
👉 **https://herrprofesor.github.io/calculadora-bachillerato-cv/**

---

## 🧭 Funcionamiento general

La aplicación calcula dos valores principales:

1. **Media de Bachillerato**  
   - Calculada como la media aritmética de todas las materias de 1.º y 2.º de Bachillerato.  
   - Permite elegir idioma (Inglés o Francés) y otras asignaturas con varias opciones.  
   - Las optativas pueden nombrarse libremente.

2. **Nota de acceso a la universidad (fase general + voluntaria)**  
   Fórmula oficial:
Nota acceso = 0,6 × Bachillerato + 0,4 × Fase General + (Pond1 × Examen1) + (Pond2 × Examen2)
donde:
- **Pond1 / Pond2**: ponderaciones (0.1 o 0.2) elegidas según la titulación universitaria.
- **Examen1 / Examen2**: materias de la fase voluntaria (nombre y nota editables).

---

## 📘 Instrucciones de uso

1. Abre la página o el archivo `index.html` en tu navegador.
2. Rellena las notas (entre 0 y 10) de:
- **1.º de Bachillerato**
- **2.º de Bachillerato**
- **Fase general de la EBAU**
- (Opcional) **Fase voluntaria**
3. Pulsa **Calcular**.
4. Se mostrarán:
- Media de Bachillerato  
- Media EBAU (fase general)  
- Nota de acceso (sin ponderaciones)  
- Aportaciones ponderadas de las materias voluntarias  
- Nota total final (con ponderaciones)

El botón **Limpiar** borra todos los valores introducidos.

---

## 🧮 Ejemplo de cálculo

| Concepto | Valor | Peso | Resultado |
|-----------|--------|------|------------|
| Media de Bachillerato | 8,25 | 0,6 | 4,95 |
| Media EBAU (fase general) | 7,50 | 0,4 | 3,00 |
| Fase voluntaria (Biología, 0.2, nota 7) | – | – | +1,4 |
| **Nota final total** | – | – | **9,35** |

---

## ⚙️ Características técnicas

- Desarrollado en **HTML + CSS + JavaScript puro**.  
- No usa bases de datos ni cookies.  
- Todo el cálculo ocurre **localmente en el navegador del usuario**.  
- Los resultados se muestran con **tres decimales**.  
- Compatible con ordenadores, tablets y móviles.


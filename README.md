# 🎓 SQL University Stats

Este proyecto es una entrega final del curso de SQL, donde se analiza un dataset académico y profesional de estudiantes para obtener insights sobre su rendimiento, carrera y satisfacción laboral.

---

## 📁 Contenido del repositorio

- `script_students.sql` → Creación de vistas y funciones.
- `script_SegundaEntrega.sql` → Stored Procedures y Triggers.
- `Der_student_modificado.png` → Diagrama Entidad-Relación del modelo.
- `education_career_success.csv` → Dataset base.
- `Entrega Final_SQL_Salas.pdf` → Informe final del proyecto.

---

## 🛠 Funcionalidades SQL implementadas

### 📊 **Vistas (Views)**
- `student_full_profile`: perfil completo del estudiante.
- `university_salary_stats`: salarios promedio por universidad.
- `field_career_success`: satisfacción y promoción por carrera.
- `satisfaction_salary`: relación entre salario y satisfacción.

### 🧮 **Funciones (Functions)**
- `career_satisfaction(fieldId)`: satisfacción media por carrera.
- `avg_to_promote(fieldId)`: años promedio hasta promoción.
- `salary_by_age(minAge, maxAge)`: salario promedio por rango etario.

### 🌀 **Stored Procedures**
- `Get_Field_Statistics(fieldName)`: estadísticas generales o por carrera.
- `sp_life_career_balance()`: balance vida-trabajo vs. satisfacción.

### 🚨 **Triggers**
- `after_student_insert`: log de inserciones.
- `after_student_update`: log detallado de actualizaciones en la tabla `student`.

---

## 📦 Cómo clonar este repositorio

```bash
git clone https://github.com/eliz-ana/sql-university-stats.git

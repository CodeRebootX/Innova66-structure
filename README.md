# Innova66

**Innova66** es una aplicación de gestión técnica y administrativa diseñada para optimizar la operativa diaria de **Indasor 66 S.L.**, empresa especializada en instalaciones eléctricas. Este sistema fue desarrollado como parte del **Trabajo Fin de Grado**, abordando necesidades reales de control laboral, inventario, trazabilidad técnica y documentación.

> 🧪 Este repositorio contiene la **estructura del proyecto** y su **documentación oficial**. El código fuente se mantiene privado por acuerdo de uso.

---

## 🚀 ¿Qué resuelve Innova66?

-  Registro digital de jornadas laborales, con trazabilidad y protección de datos.
-  Gestión centralizada de actividades técnicas y materiales utilizados.
-  Generación de **albaranes automáticos**, agrupados por proyecto, cliente y fecha, con posibilidad de valoración y exportación a PDF.
-  Inventario dinámico con actualización en tiempo real y alertas por stock bajo.
-  Sistema de gestión de eventos críticos: mantenimientos, inspecciones y revisiones técnicas, con avisos anticipados.

> ✅ Validado con datos reales en colaboración directa con la empresa Indasor 66 S.L.

---

## 🧰 Tecnologías utilizadas

| Capa       | Tecnología        |
|------------|-------------------|
| Frontend   | Flutter            |
| Backend    | Java + Spring Boot |
| Base de datos | MySQL         |
| Seguridad  | BCrypt        |
| PDF Generator | OpenPDF       |
| Otros      | Provider (Flutter), REST API, Hibernate |

---

## 🧱 Estructura del proyecto

### 📦 Backend (`/backend`)

```bash
api/                      # Controladores REST
config/                   # Configuración de seguridad, CORS, etc.
models/                   # Entidades JPA y DTOs (agrupados en request/response)
repository/               # Interfaces JPA
services/                 # Lógica de negocio
Innova66Application.java  # Punto de entrada de Spring Boot
```

### 📱 Frontend (/frontend/lib)

```bash
data/
  models/                 # Modelos de datos
  repositories/           # Acceso abstracto a servicios
  services/               # Llamadas a la API
providers/                # Gestión de estado (Provider)
screens/
  admin/                  # Vistas para administradores
  tecnico/                # Vistas para técnicos
  shared/                 # Pantallas compartidas
widgets/
  admin/                  # Componentes reutilizables (admin)
  tecnico/                # Componentes reutilizables (técnico)
main.dart                 # Punto de entrada Flutter
```

---

## 📄 Documentación complementaria
[📎 Presentación TFG (PDF)](docs/Presentacion_INNOVA66.pdf)

[📘 Memoria del proyecto](docs/Memoria_TFG_INNOVA66.pdf)

---

## 🛡️ Estado del código
Este repositorio no contiene el código fuente completo,en cumplimiento de un acuerdo de uso con la empresa colaboradora.  
La estructura del backend y frontend se publica con fines académicos y demostrativos.  

---

## 👨‍💻 Autor
**Rolando Tomalo Aguilar**  
📍 IES ÍTACA – TFG DAM 2025  
🔗 [linkedin.com/in/rolando-tomalo](https://www.linkedin.com/in/rolando-tomalo)

## ⚡ Sobre mí
Durante este proyecto he asumido todos los roles del desarrollo de software: análisis, diseño de base de datos, implementación backend y frontend, pruebas, documentación y presentación.  
He trabajado con estándares reales, aplicado buenas prácticas de arquitectura y validado el sistema en una empresa activa.

> 🧩 Mi mayor aprendizaje: combinar la tecnología con las necesidades reales de un negocio para crear soluciones funcionales y escalables.

---

## ⚖️ Licencia
El uso, modificación o distribución de este software está restringido.  
Consulta la memoria del proyecto para más información sobre la licencia de uso personalizada.

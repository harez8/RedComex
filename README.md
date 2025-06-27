# RedComex
El proyecto RedComex consiste en el desarrollo de una aplicación web integral orientada a facilitar la visualización y gestión de datos relacionados con el emprendimiento y la innovación, con un enfoque específico en los sectores económicos de las PYMEs colombianas que buscan exportar sus productos o servicios a mercados internacionales.
---
## Funcionalidades Principales

### Gestión de Usuarios
- Registro y autenticación de usuarios.
- Asignación de roles: `PYME` o `ADMIN`.
- Actualización de datos de perfil.
---

### Módulo de Empresas
- Registro de empresas asociadas a usuarios.
- Modificación y eliminación de información empresarial.
- Asociación de múltiples productos por empresa.
---

### Módulo de Productos
- Registro de productos para exportación.
- Edición y eliminación de productos.
- Asignación de precio base.
---      

### Módulo de Exportaciones
- Registro de exportaciones con país destino y fecha.
- Cálculo automático del arancel mediante APIs o scraping.
- Registro de cantidad exportada y cálculo del:
    - **Costo final**
      - **Volumen exportado en USD**
---

### Automatización de Aranceles
- Obtención de tasas arancelarias actualizadas desde fuentes externas.
- Registro del valor arancelario al momento de exportar para mantener trazabilidad histórica.
---   
### Estadísticas e Informes
- Generación de estadísticas por empresa, producto y país.
- Cálculo de promedios, totales exportados y tendencias.
- Visualización de indicadores clave (KPI) para la toma de decisiones.

---   

### Panel Administrativo- Gestión de usuarios y roles.
- Monitoreo del sistema.
- Carga o modificación de aranceles manuales en caso de falla en la automatización.
    
---

## Tecnologías utilizadas
- **Backend:** Java + Spring Boot
- **Frontend:** Angular
- **Base de datos:** PostgreSQL / MySQL
- **Automatización arancelaria:** Consumo de APIs / Web Scraping (puede incluir Python o servicios externos)
---
## Contribuciones
Este proyecto fue desarrollado con fines académicos y sociales, para promover la innovación y el comercio exterior de las PYMEs en Colombia.

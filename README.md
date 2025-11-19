├── README.md
# Sistema de Pedidos para Cafetería Universitaria (SPCU)

## 📌 Descripción del Caso
Sistema web diseñado para optimizar el servicio de alimentos en la universidad. Permite pedidos anticipados, gestión de inventario y punto de venta, mejorando la experiencia de la comunidad universitaria.

## 🎯 Objetivos
- Agilizar el proceso de pedidos en cafetería.
- Mejorar la gestión de inventario.
- Ofrecer una experiencia eficiente y moderna.

## 📋 Requerimientos
- Funcionales: Registro de usuarios, pedidos en línea, gestión de menú.
- No funcionales: Seguridad, disponibilidad, escalabilidad.

## 🧪 Tabla de Pruebas

| Caso | Entrada | Resultado Esperado | Validación |
|------|--------|---------------------|------------|
| 1    | Pedido válido | Confirmación de pedido | ✅ |
| 2    | Usuario no registrado | Error de autenticación | ✅ |
| 3    | Menú vacío | Mensaje de "no disponible" | ✅ |

## (Tipo de Mantenimiento Propuesto):
*Perfectivo*: Se busca mejorar la experiencia del usuario y optimizar tiempos de respuesta, reduciendo pasos en el proceso de pedido.

## Reflexión sobre el Control de Versiones
El uso de Git y GitHub permite mantener un historial claro de cambios, facilita la colaboración y asegura trazabilidad en la documentación técnica. Markdown mejora la presentación y legibilidad de los archivos.
├── requerimientos/
│   ├── DRS_v1.docx
**Documento de Requerimientos del Sistema (Versión 1)**  
- **Funcionales**:  
  - Registro de usuarios.  
  - Gestión de menú de la cafetería.  
  - Realización de pedidos en línea.  
  - Confirmación de pedidos.  
- **No funcionales**:  
  - Seguridad en el acceso.  
  - Disponibilidad 24/7.  
  - Escalabilidad para más usuarios.  
│   └── DRS_v2.docx
**Documento de Requerimientos del Sistema (Versión 2)**  
- **Funcionales**:  
  - Registro y autenticación de usuarios con roles (cliente, administrador).  
  - Gestión avanzada de inventario.  
  - Notificaciones en tiempo real de pedidos.  
  - Reportes de ventas.  
- **No funcionales**:  
  - Mayor seguridad con cifrado de datos.  
  - Interfaz responsiva para móviles.  
  - Optimización de tiempos de respuesta.  
├── pruebas/
│   └── PlanPruebas.docx
**Plan de Pruebas del Sistema SPCU**

| Caso | Entrada | Resultado Esperado | Validación |
|------|---------|---------------------|------------|
| 1    | Usuario válido inicia sesión | Acceso al sistema | ✅ |
| 2    | Usuario no registrado | Mensaje de error | ✅ |
| 3    | Pedido con menú disponible | Confirmación de pedido | ✅ |
| 4    | Pedido con menú vacío | Mensaje de “no disponible” | ✅ |

├── mantenimiento/
│   └── Propuesta_Mantenimiento.md
# Propuesta de Mantenimiento

Se propone aplicar **mantenimiento perfectivo** al sistema SPCU.  
Este tipo de mantenimiento busca mejorar la experiencia del usuario y optimizar el rendimiento del sistema.

## Justificación
- Reducir pasos en el proceso de pedido.  
- Mejorar la interfaz gráfica para que sea más intuitiva.  
- Optimizar tiempos de respuesta en las consultas y pedidos.  
- Ampliar funcionalidades según la retroalimentación de los usuarios.  
- Garantizar que el sistema se mantenga competitivo y actualizado frente a nuevas necesidades.

## Conclusión
El mantenimiento perfectivo permitirá que el sistema SPCU evolucione de acuerdo con las expectativas de la comunidad universitaria, asegurando mayor eficiencia y satisfacción en el servicio.
├── investigacion/
│   └── Uso_de_Markdown.md
# ¿Qué es Markdown?
Markdown es un lenguaje de marcado ligero que permite escribir texto con formato utilizando una sintaxis sencilla. Es ampliamente usado en proyectos de software por su compatibilidad con plataformas como GitHub
├── evidencias/
    ├── historial_commits.png
    ├── versionado_docs.png
    └── estructura_repo.png
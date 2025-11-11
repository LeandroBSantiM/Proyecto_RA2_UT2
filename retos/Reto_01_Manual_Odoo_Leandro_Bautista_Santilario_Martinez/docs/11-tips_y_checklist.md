![Logo_de_Odoo](../assets/img/00-portada/odoo_logo.png)

# 11 — Tips & Checklist

Adoptar buenas prácticas desde el inicio es fundamental para mantenerlo todo en orden

## Tips

### Activa 2FA y define roles desde el día 1
Es muy recomendable activar la **autenticación en dos pasos (2FA)** para proteger el acceso a tu cuenta, especialmente porque Odoo gestiona información sensible.  
Puedes vincularlo con aplicaciones como **Google Authenticator**.  

Además, define **roles y niveles de acceso** por módulo (Ventas, Contabilidad, etc.). Es importante determinar si un usuario puede:
- Ver solo sus propios documentos.
- Ver todos los documentos de la empresa.
- O actuar como **Administrador** con control total.

---

### Usa etiquetas
El uso de **etiquetas** desde el principio permite **segmentar contactos o tareas** de forma eficiente y facilita el filtrado de grandes volúmenes de datos  

### Haz copias de seguridad antes de desinstalar apps
Desinstalar módulos puede ser peligroso si contienen datos importantes
Odoo advierte que esta acción puede eliminar información o generar errores

## Checklist de Configuración Inicial

Esta lista resume los pasos esenciales que deberían completarse tras la configuración inicial o la prueba gratuita:

- [x] **Base de datos de prueba activada**  
  La base de datos debe activarse por correo electrónico después del registro
  Si no se confirma, se eliminará automáticamente en unas 3 horas

- [x] **Aplicaciones iniciales instaladas**  
  Selecciona las apps necesarias (máximo 10 durante la prueba gratuita)

- [x] **2FA y notificaciones configuradas**  
  Activa la autenticación en dos pasos desde la sección de seguridad.

- [x] **Integración con Gmail y Calendar (si aplica)**  
  Configura las credenciales obtenidas desde **Google Cloud Console (GCP)** en los ajustes de autenticación OAuth de Odoo

- [x] **Contactos importados y etiquetados**  
  Importa tu lista de contactos mediante el archivo CSV de Odoo

  Crea etiquetas personalizadas para una futura segmentación más sencilla

- [x] **Proyectos y tareas configurados**  
  Define la estructura de proyectos con etapas

- [x] **Documentos y firma electrónica probados**  
  Sube archivos al módulo de Documentos y realiza una prueba de Firma digital

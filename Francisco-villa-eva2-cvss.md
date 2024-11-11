# Evaluación de Seguridad Informática

## Cuestionario sobre Conceptos de Seguridad

### 1. Define vulnerabilidad, amenaza y riesgo en el contexto de la seguridad informática

**Vulnerabilidad**  

* Es una debilidad o fallo en un sistema de información que puede comprometer la seguridad.  
* Esta debilidad puede ser explotada por amenazas para causar daño al sistema.

**Amenaza**  

* Es cualquier evento potencial que puede afectar negativamente a un sistema.  
* Puede ser algo intencional o accidental, y de origen humano o natural.

**Riesgo**  

* Es la probabilidad de que una amenaza explote una vulnerabilidad.  
* El riesgo se mide considerando tanto el impacto potencial como la probabilidad de que ocurra.

### 2. ¿Qué es CVE y cuál es su propósito?

CVE (Common Vulnerabilities and Exposures) es un sistema que asigna identificadores únicos a vulnerabilidades de seguridad conocidas públicamente. Su propósito es estandarizar la forma en que se identifican y se refieren las vulnerabilidades en diferentes sistemas y plataformas.

### 3. Menciona tres ventajas del uso de CVE

* Facilita la comunicación e identificación uniforme de vulnerabilidades entre organizaciones.
* Permite el seguimiento histórico y documentación de vulnerabilidades conocidas.
* Mejora la interoperabilidad entre herramientas y bases de datos de seguridad.

### 4. ¿Qué es CVSS y para qué se utiliza?

CVSS (Common Vulnerability Scoring System) es un sistema estándar para evaluar la gravedad de las vulnerabilidades de seguridad. Se utiliza para asignar puntuaciones numéricas basadas en varias características de la vulnerabilidad, lo que ayuda a priorizar y gestionar las vulnerabilidades según su nivel de severidad.

### 5. Describe los tres grupos métricos del CVSS

1. **Métricas Base**  
   * Evalúan las características fundamentales de una vulnerabilidad.  
   * Incluyen el impacto y la explotabilidad de la vulnerabilidad.

2. **Métricas Temporales**  
   * Reflejan características que pueden cambiar con el tiempo.  
   * Consideran factores como la disponibilidad de exploits y parches.

3. **Métricas Ambientales**  
   * Tienen en cuenta el entorno específico del usuario.  
   * Incluyen modificadores según el contexto en el que se implementa el sistema.

### 6. Explica el concepto de "componentes con vulnerabilidades conocidas" (OWASP A9:2017)

Este concepto hace referencia al riesgo de utilizar componentes de software (como bibliotecas, frameworks o módulos) que ya tienen vulnerabilidades conocidas y documentadas. Sucede cuando las organizaciones no mantienen un inventario actualizado de sus componentes o no actualizan/parchean regularmente sus sistemas.

### 7. ¿Qué es la encriptación y cuál es su objetivo?

La encriptación es el proceso de convertir información legible en un formato codificado e ilegible, utilizando algoritmos matemáticos. Su objetivo es proteger la confidencialidad de los datos, asegurando que solo las partes autorizadas, que posean la clave correcta, puedan acceder a la información original.

### 8. ¿Qué significan las siglas SOAP, WS y XML?

* **SOAP:** Simple Object Access Protocol  
* **WS:** Web Services  
* **XML:** eXtensible Markup Language

### 9. ¿Qué es hardening y cómo se relaciona con la seguridad de sistemas?

El hardening es el proceso de asegurar un sistema reduciendo sus vulnerabilidades y superficies de ataque. Se relaciona con la seguridad de los sistemas al:

* Fortalecer la configuración de seguridad predeterminada.  
* Eliminar servicios y aplicaciones innecesarias.  
* Implementar controles de seguridad más estrictos.

### 10. Describe tres acciones comunes de hardening

1. **Gestión de usuarios y permisos**  
   * Implementar políticas de contraseñas fuertes.  
   * Eliminar cuentas innecesarias.  
   * Aplicar el principio de mínimo privilegio.

2. **Configuración de servicios**  
   * Deshabilitar servicios no esenciales.  
   * Cerrar puertos no utilizados.  
   * Actualizar y parchear regularmente los sistemas.

3. **Fortalecimiento del sistema**  
   * Implementar cifrado de datos.  
   * Configurar firewalls y políticas de seguridad.  
   * Mantener registros de auditoría.

### 11. ¿Qué es un CAPTCHA y cuál es su función?

CAPTCHA (Completely Automated Public Turing test to tell Computers and Humans Apart) es una prueba diseñada para diferenciar entre usuarios humanos y programas automatizados (bots). Su función principal es prevenir el acceso automatizado a sistemas y proteger contra ataques automatizados como spam o ataques de fuerza bruta.

### 12. ¿Qué se entiende por "autenticación robusta centralizada"?

La autenticación robusta centralizada es un sistema que:

* Proporciona un punto único de autenticación para múltiples sistemas y aplicaciones.  
* Implementa múltiples factores de autenticación (algo que sabes, tienes y eres).  
* Gestiona de manera centralizada las políticas de seguridad y acceso.  
* Facilita la administración y auditoría de accesos a los sistemas.

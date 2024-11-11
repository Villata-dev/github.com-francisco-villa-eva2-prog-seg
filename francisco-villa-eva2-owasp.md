# Evaluación OWASP

## Cuestionario sobre OWASP y Seguridad de Software

### 1. ¿Qué es OWASP y cuál es su principal objetivo?

OWASP (Open Web Application Security Project) es una organización sin fines de lucro que trabaja para mejorar la seguridad del software. Su principal objetivo es hacer que la seguridad de las aplicaciones sea más visible, para que las organizaciones puedan tomar decisiones más informadas sobre los riesgos. Lo logran creando recursos gratuitos, herramientas, documentación y comunidades que ayudan a las empresas a desarrollar, comprar y mantener aplicaciones más seguras.

### 2. ¿Qué es el OWASP Top 10 y por qué es importante para los desarrolladores?

El OWASP Top 10 es un documento estándar que presenta los riesgos más críticos para la seguridad de las aplicaciones web. Está basado en un consenso amplio entre expertos y sirve como una guía de concientización para los desarrolladores. Es importante para los desarrolladores porque:

* Ofrece una guía práctica sobre las vulnerabilidades más comunes
* Ayuda a priorizar los esfuerzos de seguridad
* Es un buen punto de partida para empezar a implementar seguridad en el desarrollo de aplicaciones
* Se actualiza regularmente para reflejar nuevas amenazas emergentes

### 3. Describe brevemente dos de las vulnerabilidades del OWASP Top 10 2017

**Inyección (A1:2017):**

La inyección ocurre cuando los datos no confiables se envían a un intérprete, como parte de un comando o consulta. Los atacantes pueden aprovechar esto para ejecutar comandos maliciosos o acceder a datos sin autorización.

**Exposición de Datos Sensibles (A3:2017):**

Cuando una aplicación no protege adecuadamente los datos sensibles (como información personal, financiera o credenciales), los atacantes pueden robar o modificar estos datos para cometer fraudes o incluso robar identidades.

### 4. ¿Qué es OWASP ASVS y cuáles son sus niveles de verificación?

OWASP ASVS (Application Security Verification Standard) es un conjunto de requisitos para verificar la seguridad de una aplicación. Está dividido en tres niveles de verificación:

1. **Nivel 1**: Para aplicaciones con baja garantía de seguridad
2. **Nivel 2**: Para aplicaciones que manejan datos sensibles
3. **Nivel 3**: Para aplicaciones críticas que requieren el nivel más alto de confianza

### 5. ¿Cuál es la diferencia entre los niveles 1 y 3 de OWASP ASVS?

**Nivel 1:**

Este nivel proporciona una protección básica contra las vulnerabilidades de seguridad comunes. Es el nivel más fácil de implementar.

**Nivel 3:**

Este nivel es mucho más exhaustivo, y requiere un análisis profundo de la arquitectura, la codificación y las pruebas de seguridad. Se aplica a aplicaciones críticas, como las del sector financiero o de salud, donde la seguridad es una prioridad máxima.

### 6. ¿Qué es el modelado de amenazas y cuáles son sus beneficios?

El modelado de amenazas es un proceso que se utiliza para identificar posibles amenazas y vulnerabilidades en un sistema. Sus beneficios incluyen:

* Ayuda a identificar problemas de seguridad desde las primeras etapas
* Permite tener una visión más clara de cómo los atacantes pueden explotar las vulnerabilidades
* Facilita la priorización de los esfuerzos de seguridad
* Ayuda a reducir los costos al abordar los problemas en etapas tempranas del desarrollo

### 7. Nombra dos metodologías de modelado de amenazas

1. **STRIDE:**
   Desarrollada por Microsoft, esta metodología ayuda a identificar las amenazas de suplantación, manipulación, repudio, revelación de información, denegación de servicio y elevación de privilegios.

2. **PASTA:**
   PASTA (Process for Attack Simulation and Threat Analysis) es una metodología centrada en el riesgo, diseñada para simular ataques y analizar las amenazas de manera más detallada.

### 8. ¿Qué es el SDL y cómo ayuda a la seguridad del software?

SDL (Security Development Lifecycle) es un conjunto de prácticas de seguridad que se integran en cada fase del desarrollo de software. Ayuda a mejorar la seguridad del software al:

* Integrar medidas de seguridad desde el principio del desarrollo
* Ofrecer prácticas específicas para cada fase del ciclo de vida del software
* Reducir la cantidad y gravedad de las vulnerabilidades
* Establecer requisitos de seguridad claros y alcanzables

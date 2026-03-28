# **🛡️ Laravel Security Agent \- Realtime Auditor**

**Security Agent** es una interfaz de auditoría técnica diseñada para desarrolladores Senior y Auditores de Sistemas que buscan validar la integridad de aplicaciones Laravel en tiempo real. Utiliza modelos de lenguaje avanzados (LLMs) para detectar vulnerabilidades, fallos de arquitectura y desviaciones de los principios SOLID.

## **🚀 Propósito del Proyecto**

Este proyecto nace de la necesidad de automatizar la **auditoría preventiva** en entornos de desarrollo gubernamentales y de alta seguridad. Su objetivo no es reemplazar al programador, sino actuar como un "Pair Programmer" especializado en ciberseguridad.

### **Capacidades Principales:**

* **Análisis Estático (SAST):** Detección de patrones inseguros antes de la ejecución.  
* **Auditoría de Inyección:** Identificación de consultas SQL crudas o mal sanitizadas.  
* **Validación Arquitectónica:** Verifica el cumplimiento de *Thin Controllers* y *Fat Models*.  
* **Cumplimiento OWASP:** Basado en los estándares internacionales de seguridad web.

## **🛠️ Stack Tecnológico**

* **Frontend:** HTML5, Tailwind CSS (Layout ultra-responsivo y minimalista).  
* **Engine:** JavaScript (ES6+) con integración de la API de Google Generative AI.  
* **Estándares:** Diseñado específicamente para ecosistemas **Laravel 11+**.

## **📖 Instrucciones de Uso**

1. **Obtener API Key:** Consigue tu clave gratuita en [Google AI Studio](https://aistudio.google.com/).  
2. **Configuración:**  
   * Abre el archivo security\_agent\_auditor.html.  
   * Pega tu API Key en el campo superior.  
   * Selecciona el modelo deseado (Gemini 3 Flash recomendado por velocidad).  
3. **Auditoría:** Pega fragmentos de controladores, modelos o rutas de Laravel y el Agente generará un informe detallado en la terminal interactiva.

## **⚖️ Directrices de Desarrollo (Philosophy)**

El agente está programado para hacer cumplir las siguientes reglas de oro:

* **Clean & Thin:** Controladores sin lógica de negocio.  
* **Eloquent First:** Prioridad total al ORM sobre SQL plano.  
* **Seguridad Defensiva:** Validación obligatoria mediante FormRequests.  
* **SOLID:** Una sola responsabilidad por clase.

## **👤 Autor**

**Omar Figueroa**

*Desarrollador Senior Full-Stack | Especialista en Arquitectura Laravel*

"El código limpio no es un lujo, es una medida de seguridad."

## **📄 Licencia**

Este proyecto es de código abierto bajo la licencia MIT. Siéntete libre de usarlo, mejorarlo y compartirlo para fortalecer la comunidad de seguridad en Laravel.
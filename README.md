# Simulador de Redes 🚀  
**Proyecto Final** - Sistemas Operativos y Redes | Universidad Nacional de General Sarmiento (UNGS)

---

## 📋 Descripción del Proyecto  

El proyecto tiene como objetivo **diseñar e implementar una red completa** para la empresa **Skynet**, con sedes distribuidas en las provincias de:  
- **Buenos Aires**  
- **Córdoba**  
- **La Rioja**  

La solución de red garantiza la **conectividad** entre todas las sedes, departamentos y hosts, siguiendo las mejores prácticas del modelo **OSI**. Además, se configura un servidor **DNS** para asegurar el acceso al sitio web oficial de la empresa dentro del simulador:  

👉 **[http://www.skynet.com.ar](http://www.skynet.com.ar)**  

---

## 🌐 Arquitectura de Red  

### 🛠️ Tecnologías Utilizadas  
- **Modelo OSI**: Referencia para la configuración de cada capa.  
- **Protocolos Implementados**:  
  - TCP/IP  
  - DNS  
  - HTTP  
  - ICMP (para diagnóstico mediante *ping*).  
- **Hardware Virtualizado**:  
  - Hosts (PCs)  
  - Switches  
  - Routers  
  - Servidor DNS y Web  

### 🏢 Distribución de la Red  
La red se organiza en **subredes** según departamentos y sedes, optimizando el uso de direcciones IP para asegurar:  
- **Escalabilidad**: Capacidad de expansión futura.  
- **Eficiencia**: Reducción del tráfico innecesario mediante segmentación.  
- **Confiabilidad**: Comunicación entre todos los nodos y acceso al servidor central.

---

## 🚀 Funcionamiento  

### 🔗 Comandos Básicos de Verificación  

1. **Verificar Conectividad entre Hosts**:  
   - Desde cualquier host:  
     ```bash
     click en host -> Desktop -> Command Prompt
     ping <ip-destino>
     ```  
     Ejemplo: `ping 172.18.8.1`  

2. **Acceder al Sitio Web de la Empresa**:  
   - Desde cualquier host:  
     ```bash
     click en host -> Desktop -> Web Browser
     http://www.skynet.com.ar
     ```  

   Esto mostrará la página alojada en el servidor web de la sede central (Buenos Aires).

---

## 📊 Características Principales  

- **Segmentación** de red por subredes y departamentos.  
- **Servidor DNS** para resolución de nombres de dominio.  
- **Servidor Web** accesible desde todas las sedes.  
- **Ruteo** entre sedes utilizando **RIP v2**.  
- Configuración **escalable** para posibles expansiones futuras.  

---

## 🧩 Estructura del Proyecto  

El proyecto incluye los siguientes archivos:  
- **simulador_redes.pkt**: Archivo de simulación para Cisco Packet Tracer.  
- **documentacion.pdf**: Informe detallado con el diseño de la red, justificación técnica y pruebas realizadas.  
- **README.md**: Este archivo, con instrucciones y descripción general.

---

## 📦 Instalación y Ejecución
 - Requisitos Previos:

 - Cisco Packet Tracer (versión 8.2.2 o compatible).
 - Pasos para Cargar el Proyecto:

 - Abre Cisco Packet Tracer.
 - Carga el archivo simulador_redes.pkt.
 - Realiza las pruebas de conectividad y navegación web según lo indicado.

 ---

 ## Gracias por leer ☻
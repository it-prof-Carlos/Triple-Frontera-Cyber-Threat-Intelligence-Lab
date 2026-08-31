# Triple Frontera Cyber-Threat Intelligence Lab

**Autor:** Carlos Gallardo  
**Fecha:** Agosto 2026  
**Estado:**  En Desarrollo  
**Contexto:** Proyecto Integrador - Ingeniería en Inteligencia Artificial

---

## Resumen Ejecutivo

El **Triple Frontera Cyber-Threat Intelligence Lab** es un proyecto integral que aplica técnicas avanzadas de **Inteligencia Artificial**, **OSINT** y **análisis de riesgos geopolíticos** para la detección, análisis y mitigación de amenazas cibernéticas en la región de la Triple Frontera (Argentina - Brasil - Paraguay), con foco en tres verticales críticas:

1. **Empresas de Tecnología** (centros de datos, comunicaciones satelitales)
2. **Plantas de Extracción de Minerales Críticos** (litio, cobre, tierras raras)
3. **Infraestructura Turística de Alto Nivel** (Hotel Hilton Garden Inn Salta)

**Contexto de Amenaza (2025-2026):**

- **Argentina creó el Centro Nacional de Ciberseguridad** en enero de 2026, con el objetivo de proteger infraestructuras críticas y gestionar amenazas.
- **El gobierno dio 180 días a los organismos públicos** para reforzar su ciberseguridad, fortaleciendo la resiliencia de las infraestructuras críticas.
- **La Triple Frontera es un punto crítico** para el financiamiento de grupos terroristas y el crimen organizado transnacional.
- **Argentina se ha alineado con EE.UU.** en la alianza "Pax Silica" para asegurar cadenas de suministro de minerales críticos e inteligencia artificial.
- **El Hilton Garden Inn Salta** (primer hotel de la cadena en la provincia) se inaugurará a fines de 2026, con 10.500 m² y 350 plazas.

**Valor del Proyecto:**  
Este laboratorio demuestra la capacidad de integrar **inteligencia criminal**, **análisis geopolítico**, **ciberseguridad GRC** e **Inteligencia Artificial** para proteger infraestructuras críticas en zonas de alta complejidad. 

---

##  Objetivos del Proyecto

1. **Recolectar y analizar inteligencia de amenazas** específica de la Triple Frontera.
2. **Mapear TTPs** a MITRE ATT&CK Framework (versión ICS para entornos industriales).
3. **Desarrollar reglas personalizadas** para Wazuh SIEM (adaptadas a entornos OT/ICS).
4. **Aplicar IA** (Isolation Forest, XGBoost) para la detección de patrones de crimen organizado y ataques cibernéticos.
5. **Generar reportes ejecutivos** siguiendo estándares OWASP WSTG y NIST.

---

##  Arquitectura y Tecnologías

┌─────────────────────────────────────────────────────────────────────────────┐
│ TRIPLE FRONTERA CYBER-THREAT INTELLIGENCE LAB │
├─────────────────────────────────────────────────────────────────────────────┤
│ │
│ [OSINT] → [Threat Intel] → [SIEM/Wazuh] → [IA/ML] → [Dashboard/Report] │
│ │
│ • Fuentes • MITRE • Wazuh • Python • Streamlit │
│ OSINT ATT&CK Manager Scikit-learn Plotly │
│ • Telegram • TTPs • Wazuh • Isolation • SHAP │
│ • Foros • IoCs Indexer Forest │
│ • Deep Web • Grupos • Wazuh • XGBoost │
│ • Noticias APT Dashboard │
│ │
└─────────────────────────────────────────────────────────────────────────────┘


| Componente | Tecnología | Propósito |
|------------|------------|-----------|
| **OSINT** | Python, Telegram API, Scrapy | Recolección de inteligencia de fuentes abiertas |
| **Threat Intelligence** | MITRE ATT&CK (ICS/Enterprise) | Mapeo y clasificación de TTPs |
| **SIEM/XDR** | Wazuh 4.14.3 | Detección y monitoreo en tiempo real |
| **IA/ML** | Isolation Forest, XGBoost | Detección de anomalías y patrones |
| **Dashboard** | Streamlit, Plotly | Visualización interactiva |
| **Reportes** | Markdown, PDF, OWASP WSTG | Documentación ejecutiva |

---

## Instalación y Ejecución

### Requisitos
- Python 3.9+
- pip

### Instalación

``bash
git clone https://github.com/it-prof-Carlos/triple-frontera-cyber-threat-lab.git
cd triple-frontera-cyber-threat-lab
pip install -r requirements.txt

Ejecutar el Dashboard

streamlit run app.py

Referencias Oficiales
Centro Nacional de Ciberseguridad - Argentina

MITRE ATT&CK for ICS Matrix

Wazuh - SIEM/XDR Open Source

OWASP WSTG - Reporting

Argentina - Minerales Críticos y Pax Silica

Contacto

LinkedIn: linkedin.com/in/carlos-gallardo-746059194

GitHub: github.com/it-prof-Carlos

Email: gallardocarlositpro@gmail.com

"No se trata de predecir el futuro, sino de prepararse para él."

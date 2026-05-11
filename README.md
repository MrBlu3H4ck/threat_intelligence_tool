# threat_intelligence_tool
# Threat Intelligence CLI Tool

Herramienta en Python para **enriquecer direcciones IP** usando múltiples fuentes de Threat Intelligence:

- VirusTotal
- AbuseIPDB
- IPinfo

El output es en formato **key=value**, pensado para ser copiado fácilmente en tickets, logs o herramientas de análisis.

---

## 🚀 Funcionalidades

- Validación de IP (IPv4 / IPv6)
- Integración con múltiples APIs
- Manejo de errores (timeouts, SSL, etc.)
- Output simple y copiable
- Uso por CLI

---

## 📦 Requisitos

- Python 3.10 o superior
- API Keys de:
  - VirusTotal
  - AbuseIPDB
  - IPinfo

---

## 🔧 Instalación

1. Clonar el repositorio
2. Crear ambiente virtual: python -m venv venv
3. Activar el ambiente: venv\Scripts\activate
4. Instalar los requerimientos para el funcionamiento: pip install -r requirements.txt
5. Crear el .env para las Keys de las apis:
   
"""
VT_API_KEY=tu_api_key_virustotal
ABUSE_API_KEY=tu_api_key_abuseipdb
IP_INFO_API_KEY=tu_token_ipinfo
"""

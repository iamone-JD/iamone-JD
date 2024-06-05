# Hello, I'm Jose 👋

I am an IT enthusiast with a deep interest in technology and a dedication to solving complex problems.

## Objective

My journey as a web developer has led me to find a passion for cybersecurity, and I am now eager to transition into this field, specifically aiming to join a Security Operations Center (SOC) as a Tier 1 Analyst or as a Pentester.

## Skills

| Skill                                         | Associated Project         |
|-----------------------------------------------|----------------------------|
| SIEM Implementation and Log Analysis          | <a href="https://google.com">Detection Lab</a>|
| Network Traffic Monitoring and Attack Detection | <a href="https://google.com">Detection Lab</a>|
| Security Automation with Shuffle SOAR         | SOC Automation Lab|
| Incident Response Planning and Execution      | SOC Automation Lab|
| Case Management with TheHive                  | SOC Automation Lab|
| Scripting and Automation for Threat Mitigation | SOC Automation Lab|

## Tools
### Network
<div>
    <img src="https://img.shields.io/badge/-Wireshark-1679A7?&style=for-the-badge&logo=Wireshark&logoColor=white" />
    <img src="https://img.shields.io/badge/-Nmap-4D4D4D?&style=for-the-badge" />
    <img src="https://img.shields.io/badge/-Traceroute-4D4D4D?&style=for-the-badge" />
</div>

### Endpoint
<div>
    <img src="https://img.shields.io/badge/-Microsoft_Defender_for_Endpoint-00A4EF?&style=for-the-badge&logo=Microsoft&logoColor=white" />
    <img src="https://img.shields.io/badge/-Kaspersky_Endpoint_Security-00A4EF?&style=for-the-badge&logo=Kaspersky" />
</div>

### SIEM
<div>
    <img src="https://img.shields.io/badge/-Elastic-005571?&style=for-the-badge&logo=Elastic&logoColor=white" />
</div>

### SOC
<div>
    <img src="https://img.shields.io/badge/-Wazuh-005571?&style=for-the-badge" />
    <img src="https://img.shields.io/badge/-Shuffle-005571?&style=for-the-badge" />
    <img src="https://img.shields.io/badge/-TheHive-005571?&style=for-the-badge" />
</div>

## Certifications
<div>
<img src="https://img.shields.io/badge/-Cisco CCNA-000080?&style=for-the-badge&logo=Cisco&logoColor=white" />
</div>

## Projects
- Detection Lab
- SOC Automation Project
- SIEM configuration and management

- # Scripting and Automation for Threat Mitigation

Este proyecto contiene un script en Python para la automatización de tareas relacionadas con la mitigación de amenazas. El script realiza un escaneo de puertos abiertos en una dirección IP, verifica vulnerabilidades comunes en esos puertos y genera un informe con los resultados.

## Requisitos

- Python 3.x
- nmap (debe estar instalado y en el PATH)
- Bibliotecas de Python: `python-nmap` y `requests`

## Instalación

### Paso 1: Instalar `nmap`

#### Windows

1. Descarga el instalador de `nmap` desde [nmap.org](https://nmap.org/download.html).
2. Ejecuta el instalador y sigue las instrucciones para instalar `nmap`.
3. Asegúrate de que la ruta de instalación de `nmap` esté en el PATH del sistema. Puedes agregarla manualmente si es necesario.

#### macOS

1. Si tienes `Homebrew` instalado, puedes instalar `nmap` con el siguiente comando:

    ```sh
    brew install nmap
    ```

2. Si no tienes `Homebrew`, puedes descargar el instalador desde [nmap.org](https://nmap.org/download.html) y seguir las instrucciones.

#### Linux

1. En distribuciones basadas en Debian/Ubuntu, puedes instalar `nmap` con el siguiente comando:

    ```sh
    sudo apt-get install nmap
    ```

2. En distribuciones basadas en Red Hat/Fedora, usa el siguiente comando:

    ```
    sudo yum install nmap
    ```

### Paso 2: Instalar las bibliotecas de Python

Ejecuta el siguiente comando para instalar las bibliotecas requeridas:

```
pip install python-nmap requests

```
## Uso

### Paso 1: Clonar el repositorio

Clona este repositorio en tu máquina local:

```sh
git clone https://github.com/wh0arew3/-Scripting-and-Automation-for-Threat-Mitigation-
cd tu_repositorio
```

### Paso 2: Instalar las bibliotecas de Python

Ejecuta el siguiente comando para instalar las bibliotecas requeridas:

```sh
pip install python-nmap requests
```

### Paso 3: Ejecutar el script

Ejecuta el script desde la línea de comandos (cmd en Windows o terminal en macOS/Linux):

```sh
python threat_mitigation.py
```

### Paso 4: Ingresar la dirección IP

Cuando se te solicite, ingresa la dirección IP que deseas escanear:

```plaintext
Ingresa la dirección IP a escanear:
```

### Paso 5: Ver los resultados

El script escaneará los puertos abiertos en la dirección IP especificada, verificará vulnerabilidades comunes y generará un informe en formato JSON llamado `report.json`.

## Ejemplo de salida

```plaintext
Ingresa la dirección IP a escanear: 192.168.1.1
Escaneando puertos abiertos en 192.168.1.1...
Puertos abiertos encontrados: [22, 80, 443]
Escaneo y verificación de vulnerabilidades completado.
Informe generado: report.json
```

## Informe

El informe generado (`report.json`) contendrá información como la siguiente:

```json
{
    "timestamp": "2024-06-05T12:34:56.789012",
    "ip_address": "192.168.1.1",
    "open_ports": [22, 80, 443],
    "vulnerabilities": {
        "22": "SSH potencialmente vulnerable a ataques de diccionario",
        "80": "HTTP podría tener vulnerabilidades XSS",
        "443": "HTTPS podría tener configuraciones débiles de SSL/TLS"
    }
}
```


# 🪟 Windows Server Security Lab

Laboratorio práctico de **administración y seguridad en Windows Server 2022**, creado como parte de mi portafolio de ciberseguridad.

> **Estado:** En desarrollo y documentación continua.

## 🎯 Objetivo

Implementar y documentar un entorno de Windows Server donde pueda practicar administración, servicios de red, acceso remoto y controles básicos de seguridad, dejando evidencia clara de cada configuración realizada.

## 🧰 Tecnologías y herramientas

- Windows Server 2022
- VirtualBox
- PowerShell
- DHCP
- IIS
- Remote Desktop Protocol (RDP)
- Windows Defender Firewall
- Herramientas administrativas de Windows Server

## 🧪 Prácticas realizadas

- Creación y administración de usuarios y grupos
- Configuración de direccionamiento IP
- Instalación y configuración del servicio DHCP
- Definición de rangos y exclusiones DHCP
- Instalación y publicación de un sitio web con IIS
- Configuración y pruebas de acceso remoto mediante RDP
- Revisión de conectividad y servicios
- Administración básica y resolución de errores del servidor

## 🔐 Enfoque de seguridad

Durante el laboratorio se aplican buenas prácticas como:

- Uso de cuentas separadas según función
- Restricción del acceso remoto
- Revisión de reglas de firewall
- Validación de servicios y puertos necesarios
- Documentación de cambios
- No publicación de contraseñas, credenciales ni datos sensibles

## 🗂️ Estructura del repositorio

```text
windows-server-security-lab/
│
├── README.md
├── capturas/
│   └── README.md
├── docs/
│   └── README.md
└── scripts/
    └── README.md
```

## 📸 Evidencias

Las capturas del laboratorio se irán organizando en la carpeta [capturas](./capturas/).

Cada evidencia tendrá una breve explicación de:

1. Qué se configuró.
2. Por qué se realizó.
3. Qué resultado se obtuvo.
4. Qué problema apareció, si lo hubo.
5. Cómo se solucionó.

## 📄 Documentación

Los informes, procedimientos y explicaciones técnicas se organizarán en [docs](./docs/).

## 💻 Scripts

Los comandos y scripts de PowerShell utilizados para automatizar o verificar configuraciones se organizarán en [scripts](./scripts/).

## 🧠 Aprendizajes

Este laboratorio me permite reforzar conocimientos de administración de servidores, redes, control de acceso, servicios de infraestructura y documentación técnica orientada a ciberseguridad.

## 🚧 Próximos pasos

- Documentar evidencias con capturas limpias y explicadas
- Profundizar en Active Directory y políticas de grupo
- Revisar eventos y registros de seguridad
- Practicar hardening básico de Windows Server
- Automatizar tareas con PowerShell

## ⚠️ Privacidad y uso responsable

Toda la información publicada en este repositorio corresponde a un entorno de laboratorio. Las capturas y documentos deben ocultar contraseñas, correos personales, claves, tokens, IP públicas y cualquier otra información sensible.

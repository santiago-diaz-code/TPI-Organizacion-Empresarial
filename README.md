# Automatización del Proceso de Solicitud de Vacaciones mediante Chatbot

Este proyecto consiste en un simulador de chatbot interactivo por consola desarrollado en **Python** para la materia Organización Empresarial de la UTN. El objetivo principal es automatizar la gestión de licencias del personal de la empresa **Soluciones Tech S.A.** (empresa ficticia), reemplazando el flujo tradicional por correo electrónico.

## Características Principales
- **Máquina de Estados Finitos:** Controla el flujo lógico de la conversación garantizando que se respeten todos los pasos del proceso de negocio.
- **Robustez y Control de Errores:** Validación en tiempo real de números de legajo, tipos de datos enteros para los días y formato estandarizado de fechas (DD/MM/AAAA).
- **Persistencia en Archivos Planos:** Uso de archivos CSV ('empleados.csv' y 'solicitudes.csv') como repositorios transaccionales estables.

## Requisitos e Instalación:
Para ejecutar el simulador localmente, solo necesitas tener instalado Python 3.x.

1. Clonar el repositorio:
```bash
git clone https://github.com/santiago-diaz-code/TPI-Organizacion-Empresarial.git
```

2. Asegurarse de tener los archivos empleados.csv y solicitudes.csv en el mismo directorio que el script principal.

3. Ejecutar el programa:
```bash
python main.py
```
## Alumnos
- Luis Santiago Díaz
- Cristian Detter

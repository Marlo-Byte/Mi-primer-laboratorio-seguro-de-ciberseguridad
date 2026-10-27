Reporte: Hardening inicial de Windows 11 Home
Herramienta: Oracle VirtualBox
Sistema operativo: Windows 11 Home

1. Creación de la máquina virtual
Se creó una máquina virtual en VirtualBox para instalar Windows 11 Home.

Importancia: Permite trabajar en un entorno aislado para realizar pruebas de seguridad.

2. Configuración de red NAT
Se configuró la red en modo NAT antes de iniciar la máquina virtual.

Importancia: Permite el acceso a Internet y reduce la exposición directa de la máquina virtual a conexiones entrantes externas.

3. Creación de usuario estándar
Se creó un usuario con permisos limitados en Windows 11 Home.

Importancia: Reduce el riesgo de cambios no autorizados y limita las acciones que pueden realizarse sin permisos administrativos.

4. Actualización del sistema
Se ejecutó Windows Update para instalar las actualizaciones disponibles.

Importancia: Las actualizaciones corrigen vulnerabilidades y mejoran la seguridad del sistema operativo.

5. Creación del snapshot
Con la máquina virtual apagada, se creó una instantánea llamada Hardening Inicial.

Importancia: Permite recuperar el estado guardado de la máquina virtual si surgen problemas durante futuras configuraciones.

Conclusión
Se realizaron las configuraciones iniciales de seguridad en Windows 11 Home, incluyendo la red NAT, un usuario estándar, las actualizaciones del sistema y un snapshot de referencia. Estas medidas ayudan a reducir riesgos y facilitan la recuperación ante posibles errores.
# Indice
<!--toc:start-->
- [UF1465 - Computadoras para base de datos](#uf1465-computadoras-para-base-de-datos)
  - [Estructura y Componentes de una Computadora](#estructura-y-componentes-de-una-computadora)
  - [Funciones y Objetivos de los Sistemas Operativos](#funciones-y-objetivos-de-los-sistemas-operativos)
  - [Sistemas de Archivos](#sistemas-de-archivos)
  - [Multiproceso y Multiusuario](#multiproceso-y-multiusuario)
  - [Particionamiento Lógico y Núcleos Virtuales](#particionamiento-lógico-y-núcleos-virtuales)
  - [Configuración y Ajuste de Sistemas](#configuración-y-ajuste-de-sistemas)
- [UF1466 - Sistemas de Almacenamiento](#uf1466-sistemas-de-almacenamiento)
  - [Introducción a los sistemas de almacenamiento](#introducción-a-los-sistemas-de-almacenamiento)
  - [Dispositivos de almacenamiento](#dispositivos-de-almacenamiento)
  - [Sistemas de almacenamiento en red](#sistemas-de-almacenamiento-en-red)
  - [Gestión del almacenamiento](#gestión-del-almacenamiento)
  - [Rendimiento y optimización](#rendimiento-y-optimización)
  - [Seguridad y respaldo](#seguridad-y-respaldo)
  - [Tendencias actuales](#tendencias-actuales)
- [UF1467 - Aplicaciones microinformáticas e Internet para consulta y generación de documentación](#uf1467-aplicaciones-microinformáticas-e-internet-para-consulta-y-generación-de-documentación)
  - [Herramientas Ofimáticas](#herramientas-ofimáticas)
  - [Internet y Servicios Web](#internet-y-servicios-web)
  - [Documentación Técnica](#documentación-técnica)
- [Glosario de Términos Técnicos](#glosario-de-términos-técnicos)
- [Enlaces a Recursos Adicionales](#enlaces-a-recursos-adicionales)
<!--toc:end-->
# UF1465 - Computadoras para base de datos
## Estructura y Componentes de una Computadora
- **Procesadores**: Funcionamiento de la CPU, componentes clave como la Unidad de Control, Unidad Logica Aritmetica, memoria caché y reloj.
- **Memorias**: Tipos de memoria (RAM, ROM, VRAM, SRAM, DRAM, memoria flash).
- **Interfaces de E/S**: Comunicación entre la CPU y dispositivos periféricos, evolución de las interfaces (USB, HDMI, etc.).
- **Discos**: Sistemas de almacenamiento y comparativa de procesadores.
- Ejercicios Practicos
  - Identificar componentes de una CPU.
  - Comparar diferentes tipos de memoria.
  - Configurar interfaces de E/S.

## Funciones y Objetivos de los Sistemas Operativos
- **SO como Interfaz**: Interfaz gráfica (GUI), línea de comandos (CLI) y interfaces naturales (NUI).
- **SO como Administrador de Recursos**: Gestión de CPU, memoria, dispositivos de E/S y seguridad.
- Ejercicios Practicos
  - Crear scripts en CLI (Command Prompt y Bash).
  - Configurar permisos de usuario en Windows y Linux.

## Sistemas de Archivos
- **Archivos y Directorios**: Operaciones básicas, rutas absolutas y relativas, metadatos.
- **Implementación**: Sistemas de archivos de disco (NTFS, ext4, HFS+) y flash (FAT32, exFAT).
- Ejercicios Practicos
  - Crear y gestionar archivos y directorios.
  - Comparar sistemas de archivos NTFS y ext4.

## Multiproceso y Multiusuario
- **Introducción**: Concepto de multiprocesamiento y su evolución.
- **Hardware de Multiprocesador**: Arquitecturas UMA, NUMA y COMA.
- **Tipos de SO para Multiprocesador**: Multiprocesamiento simétrico (SMP) y asimétrico.
- **Multicomputadoras**: Características y aplicaciones.
- **Organización de Usuarios**: Gestión de cuentas, permisos y seguridad.
- Ejercicios Practicos
  - Configurar un entorno de multiprocesamiento.
  - Gestionar usuarios y grupos en Windows y Linux.

## Particionamiento Lógico y Núcleos Virtuales
- **Virtualización**: Concepto, historia y aplicaciones en la nube.
- **Contenedores**: Docker y su uso en entornos Linux y Windows.
- Ejercicios Practicos
  - Instalar y configurar una máquina virtual con VirtualBox.
  - Ejecutar contenedores Docker en Windows.

## Configuración y Ajuste de Sistemas
- **Rendimiento**: Métricas de rendimiento y optimización.
- **Resolución de Problemas**: Soluciones para situaciones de alto consumo.
- **Procesos de Servicios**: Gestión de servicios de red, impresión, actualización y seguridad.
- **Planes de Pruebas**: Elaboración de planes de pruebas para sistemas operativos.
- Ejercicios Practicos
  - Monitorear el rendimiento del sistema con herramientas como CPU-Z.
  - Elaborar un plan de pruebas para un sistema operativo.


# UF1466 - Sistemas de Almacenamiento

## Introducción a los sistemas de almacenamiento
- **Jerarquía de datos**: Desde bits hasta bases de datos.
- **Tipos de almacenamiento**: Local (discos duros, USB), en red (NAS), en la nube (Google Drive, Dropbox).
- **Evolución**: Desde tarjetas perforadas hasta el almacenamiento en la nube.
- Ejercicios Prácticos
  - **Particionado y formateo en Linux**:

## Dispositivos de almacenamiento
- **HDD**: Discos duros tradicionales, económicos pero más lentos.
- **SSD**: Unidades de estado sólido, más rápidas pero más caras.
- **RAID**: Sistemas de redundancia para mejorar la fiabilidad y el rendimiento.
- **Cintas magnéticas**: Aún utilizadas para almacenamiento a largo plazo y copias de seguridad.
- Ejercicios Prácticos
  -  **Configuración de RAID**:

## Sistemas de almacenamiento en red
- **NAS**: Almacenamiento conectado a la red, ideal para compartir archivos.
- **SAN**: Red de alta velocidad dedicada al almacenamiento, usada en entornos empresariales.
- **NAS vs SAN**: NAS es más simple y económico, SAN ofrece mayor rendimiento y escalabilidad.

## Gestión del almacenamiento
- **Particionado y formateo**: Organización del espacio en discos.
- **Sistemas de archivos**: FAT, NTFS, ext4, etc.
- **Gestión de volúmenes lógicos**: Flexibilidad en la administración de discos.

## Rendimiento y optimización
- **Técnicas de optimización**: Desfragmentación, compresión, deduplicación, caché SSD.
- **Monitorización**: Herramientas como CrystalDiskInfo, Disk Speedtest, iostat.
- Ejercicios Prácticos
  - **Monitorización de rendimiento**

## Seguridad y respaldo
- **Copias de seguridad**: Estrategias 3-2-1, tipos de copias (completas, incrementales, diferenciales).
- **Recuperación ante desastres**: Planes de recuperación (RTO, RPO), replicación en la nube.
- Ejercicios Prácticos
  - **Copia de seguridad en la nube**

##  Tendencias actuales
- **Almacenamiento definido por software (SDS)**: Separación del software de almacenamiento del hardware.
- **Hiperconvergencia**: Integración de computación, almacenamiento y redes en un solo sistema.
- **Servicios en la nube**: AWS, Google Cloud, Azure.

# UF1467 - Aplicaciones microinformáticas e Internet para consulta y generación de documentación

## Herramientas Ofimáticas
- Esta unidad cubre las herramientas esenciales para la creación y gestión de documentos, hojas de cálculo y presentaciones. Se exploran tanto aplicaciones de escritorio como soluciones en la nube, destacando sus ventajas y desventajas. También se introducen herramientas de comunicación como Discord y Slack.
- Ejercicios Practicos
  - Crear un documento en Word/Writer con formato estándar.
  - Diseñar una hoja de cálculo en Excel/Calc con fórmulas básicas.
  - Crear una presentación en PowerPoint/Impress con animaciones.
  - Comparar las ventajas de Google Workspace vs. Microsoft 365 Online.

## Internet y Servicios Web
- En esta unidad se estudian los fundamentos de Internet, incluyendo navegadores, protocolos de red (DNS, HTTP/HTTPS, FTP, SSH) y servicios como correo electrónico y transferencia de archivos. También se aborda el software libre y los sistemas de control de versiones.
- Ejercicios Practicos
  - Configurar una cuenta de correo electrónico y enviar un mensaje con adjuntos.
  - Usar FTP para transferir archivos entre dos equipos.
  - Explorar un repositorio de software libre y descargar una aplicación.
  - Configurar un sistema de control de versiones básico con Git.

## Documentación Técnica
- Esta unidad se centra en la creación de documentación técnica, utilizando formatos estándar y herramientas colaborativas como los wikis. También se introduce el uso de sistemas de control de versiones como Git y GitHub.
- Ejercicios Practicos
  - Crear un documento técnico utilizando un formato estándar (PDF, Markdown).
  - Colaborar en un wiki para editar y mejorar un artículo.
  - Subir un proyecto a GitHub y documentar los pasos en un archivo README.

# Glosario de Términos Técnicos
- **CPU**: Unidad Central de Procesamiento, el "cerebro" de la computadora.
- **RAM**: Memoria de Acceso Aleatorio, memoria volátil utilizada para almacenar datos temporalmente.
- **BIOS**: Sistema Básico de Entrada/Salida, firmware que inicializa el hardware durante el arranque.
- **Virtualización**: Técnica que permite ejecutar múltiples sistemas operativos en un mismo hardware.
- **Docker**: Plataforma de contenedores que permite ejecutar aplicaciones en entornos aislados.
- **E/S**: Sistema de Entrada y Salida.
- **Bit**: Unidad más pequeña de información, puede ser 0 o 1.
- **Byte**: 8 bits, representa un carácter ASCII.
- **RAID**: Redundant Array of Independent Disks, sistema de almacenamiento que combina múltiples discos para mejorar el rendimiento y la redundancia.
- **NAS**: Network Attached Storage, dispositivo de almacenamiento conectado a una red.
- **SAN**: Storage Area Network, red dedicada de alta velocidad para almacenamiento.
- **SDS**: Almacenamiento definido por software, separa el software de almacenamiento del hardware.
- **RTO**: Objetivo de Tiempo de Recuperación, tiempo máximo para restaurar operaciones tras un desastre.
- **RPO**: Objetivo de Punto de Recuperación, cantidad máxima de datos que se pueden perder tras un desastre.
- **DNS (Sistema de Nombres de Dominio)**: Sistema que traduce nombres de dominio a direcciones IP.
- **HTTP/HTTPS**: Protocolos de transferencia de hipertexto, con HTTPS siendo la versión segura.
- **FTP (Protocolo de Transferencia de Archivos)**: Protocolo para transferir archivos entre sistemas.
- **SSH (Secure Shell)**: Protocolo para acceder y administrar servidores de forma segura.
- **SMTP (Protocolo Simple de Transferencia de Correo)**: Protocolo para enviar correos electrónicos.
- **VPN (Red Privada Virtual)**: Tecnología que permite una conexión segura y privada a través de Internet.
- **CDN (Content Delivery Network)**: Red de servidores que distribuye contenido web de manera eficiente.
- **Git**: Sistema de control de versiones para gestionar cambios en el código fuente.

# Enlaces a Recursos Adicionales
- **Webgrafía**:
  - [Plantillas de documentación técnica](https://clickup.com/es-ES/blog/106488/plantillas-de-documentacion-tecnica)
  - [Git Documentation](https://git-scm.com/doc)
  - [Markdown Guide](https://www.markdownguide.org/)
  - [W3C](https://www.w3.org/)
  - [ICANN](https://www.icann.org/)
  - [Cloudflare CDN](https://www.cloudflare.com/es-es/learning/cdn/what-is-a-cdn/)
  - [GitHub](https://github.com/)
  - [Ley de Moore](https://es.wikipedia.org/wiki/Ley_de_Moore)
  - [Virtualización](https://openwebinars.net/blog/virtualizacion-que-es-para-que-sirve-y-ventajas/)
  - [Docker](https://www.docker.com/)
    - [![Docker](https://img.youtube.com/vi/CV_Uf3Dq-EU/maxresdefault.jpg)](https://www.youtube.com/watch?v=CV_Uf3Dq-EU)
  - [CPU-Z](https://www.cpuid.com/softwares/cpu-z.html)
  - **Evolución del almacenamiento**: [Enlace](https://www.revistacloudcomputing.com/wp-content/smush-webp/2013/08/evolucion-almacenamiento.jpg.webp)
  - **Tipos de SSD**: [Enlace](https://www.pccomponentes.com/guia-de-tipos-de-discos-ssd-cuales-hay-y-como-elegir-el-mejor-segun-el-caso-de-uso)
  - **RAID 5**: [Enlace](https://www.ionos.es/digitalguide/servidores/seguridad/raid-5/)
  - **Cintas magnéticas**: [Enlace](https://computerhoy.20minutos.es/noticias/tecnologia/almacenamiento-cinta-magnetica-aumento-2021-ransomware-1052073)
  - **AWS Training**: [Enlace](https://explore.skillbuilder.aws/learn/courses/10455/fundamentos-de-la-nube-de-aws-para-profesionales-espanol-de-espana-aws-cloud-practitioner-essentials-spanish-from-spain)
- Herramientas:
   - [LibreOffice](https://es.libreoffice.org)
   - [OpenOffice](https://www.openoffice.org/es/)
   - [Microsoft 365](https://www.microsoft.com/es-es/microsoft-365)
   - [Google Workspace](https://workspace.google.com/intl/es/)
- **Bibliografía**: 
  - "Computadores para bases de datos" por María de la Cruz Béjar Heredia.


# Proyectos Bochan - Entrega Final

Bienvenidos a la documentación oficial de los proyectos. A continuación se presentan las demostraciones en vídeo del trabajo realizado.

---


## Explicación breve Boochan 1 y su proceso

### Objetivo del Proyecto
Diseñar, desplegar y securizar un servidor web y de archivos en Linux, evolucionando de una arquitectura tradicional de puertos abiertos a una infraestructura profesional "Zero Trust" de alta disponibilidad, totalmente blindada contra ataques externos.

### Resumen Ejecutivo (Para la Portada)
El proyecto Bochan 1 documenta la creación y el bastionado (hardening) de un servidor Ubuntu Server a través de cuatro ejes fundamentales:

Infraestructura Base: Despliegue inicial de un servidor web de alto rendimiento (Nginx) y un entorno enjaulado y cifrado para la transferencia de archivos (ProFTPD / SFTP).

Evolución Zero Trust: Supresión de la exposición de puertos públicos (cierre de Port Forwarding) migrando la conectividad a túneles cifrados de Cloudflare. Esto oculta la IP real del servidor e implementa validación de identidad (OTP y Browser Rendering) para la administración remota.

Criptografía y Hardening: Implementación de defensa reactiva (Fail2Ban), autenticación asimétrica sin contraseñas (Llaves RSA para SSH) y automatización de certificados SSL/TLS (Let's Encrypt) con políticas HSTS, logrando la máxima calificación de seguridad (A+) en auditorías externas.

Resiliencia (Disaster Recovery): Particionado de hardware virtual secundario e implementación de una política de copias de seguridad incrementales, automatizadas y cifradas mediante BorgBackup y Crontab.

###  Demostración Proyecto Integrador (Bochan 1)
*Proyecto realizado por Héctor, Iker y Jorge.*

**Playlist YouTube:** https://www.youtube.com/playlist?list=PLU7Qnmepg_8-CQi_cG02l16OHLwAT3g8K

**Vídeos locales:** `videos/Boochan 1/`
| # | Vídeo | Archivo |
|---|---|---|
| 1 | Fase 9 - Auditorías de Seguridad y Pentesting | `01 - fase 9 Auditorías de Seguridad y Pentesting...mp4` |
| 2 | Fase 8 - Ampliación de Disco | `02 - fase 8 Ampliación de Disco...mp4` |
| 3 | Fase 7 - Plan de Respaldo | `03 - FAse 7 Plan de Respaldo...mp4` |
| 4 | Fase 6 - Hardening y Blindaje | `04 - fase 6 Hardening y Blindaje...mp4` |
| 5 | Fase 4b - Cloudflare Tunnel | `05 - Fase 4b Cloudflare Tunnel...mp4` |
| 6 | Fase 3 - Configuración Nginx y ProFTPD | `06 - fase 3 Configuración Nginx y ProFTPD...mp4` |
| 7 | Fase 2 - Instalación OpenSSH, XFCE4 y AnyDesk | `07 - Fase 2 boochan v1 Instalación...mp4` |
| 8 | Fase 1 - Instalación Ubuntu Server 24.04 | `08 - Fase 1 boochan v1 Introduccion...mp4` |
| 9 | Bonus: De VirtualBox a SSH | `09 - 0 distraccion De VirtualBox a SSH...mp4` |

---

## Explicacion breve Boochan 2 y su proceso

  #### Objetivo del Proyecto
Diseñar e implementar una infraestructura corporativa híbrida y segura en la nube, centralizando la gestión de identidades, el control de acceso y el almacenamiento en red para simular un entorno empresarial real.

  #### Resumen Ejecutivo (Para la Portada)
El proyecto Boochan 2 detalla el despliegue técnico de un servidor en Microsoft Azure (Ubuntu IaaS) configurado sobre cuatro pilares fundamentales:

Identidad y Dominio: Creación de un Controlador de Dominio (Samba AD DC) para la gestión centralizada de usuarios, grupos y permisos (NSS & RFC2307).

Conectividad Segura: Establecimiento de un túnel VPN cifrado (WireGuard) para conectar clientes locales de forma segura a la nube privada virtual.

Almacenamiento Avanzado: Implementación de discos virtuales con cuotas y aplicación de seguridad granular a nivel de kernel mediante listas de control de acceso (ACLs) y ABE (Access Based Enumeration), garantizando la invisibilidad de recursos no autorizados.

Monitorización: Automatización del procesamiento de logs del servidor para la extracción y registro de eventos críticos.

  ###  Demostración Boochan 2
*Proyecto realizado por Iker y Jorge.*

**Playlist YouTube:** https://www.youtube.com/playlist?list=PLU7Qnmepg_8_94ZFcMpZDa0VXZ-DgVjHv

**Vídeos locales:** `videos/Boochan 2/`
| # | Vídeo | Archivo |
|---|---|---|
| 1 | Tu propio dominio en Azure | `01 - Boochan v2 - Tu propio dominio en Azure...mp4` |
| 2 | Fase 8 - Conexión de Equipos Windows | `02 - 💻 Fase 8 El Aterrizaje del Cliente...mp4` |
| 3 | Fase 7 - Seguridad Granular (ABE) | `03 - 🕵️ Fase 7 El Sistema de Cortinas...mp4` |
| 4 | Fase 6 - Discos y Cuotas | `04 - 💾 Fase 6 Las Bóvedas de Datos...mp4` |
| 5 | Fases 4 y 5 - Dominio e Identidades | `05 - 👑👥Fases 4 y 5 El Corazón de la Infraestructura...mp4` |
| 6 | Fase 3 - Túnel WireGuard | `06 - 🔒 Fase 3 El Túnel Secreto...mp4` |
| 7 | Fase 2 - Purga y Preparación | `07 - 🧹 Fase 2 Terreno Limpio...mp4` |
| 8 | Fase 1 - Introducción y Firewall Azure | `08 - 🏗️ Fase 1 El Plano Maestro...mp4` |
| 9 | Bonus: Tu dominio en Azure (Prod. Optics) | `09 - Tu propio dominio en Azure...mp4` |


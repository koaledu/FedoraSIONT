# FedoraSIONT

Repositorio de infraestructura para el semillero de investigación SIONT (UDI).

## Migración a Contenedores
Tras un fallo de *hardware* en el equipo original, hemos migrado de una
instalación monolítica (XAMPP) a una arquitectura basada en **contenedores**
(Podman/Docker).

El servidor físico utiliza **Bluefin** (Fedora 44), un sistema inmutable
diseñado para ejecutar servicios aislados. Esta política nos permite:
- **Mantener el sistema limpio:** No instalamos paquetes en el sistema *host*.
- **Garantizar resiliencia:** Infraestructura como código, reconstruible ante
fallos de *hardware*.

## Estado
Estamos transicionando los servicios a contenedores. Este repositorio almacenará
únicamente las configuraciones necesarias para su despliegue.

Actualmente, la utilidad a largo plazo de este repositorio es incierta, ya que
las configuraciones necesarias en el servidor son, de momento, nulas.

# Cisco Catalyst SD-WAN — Guía Metodológica de Implementación
Guía metodológica de implementación Cisco Catalyst SD-WAN con automatización Python y validación en Cisco DevNet Sandbox.

**Proyecto Capstone | Ingeniería en Conectividad y Redes**

Proyecto de diseño, implementación y validación de una infraestructura Cisco Catalyst SD-WAN multisede, utilizando Cisco DevNet Sandbox 20.18 y automatización mediante Python.

## Objetivo

Desarrollar una metodología reproducible para implementar Cisco Catalyst SD-WAN, incorporando conectividad redundante, políticas de selección inteligente de rutas, calidad de servicio y monitoreo automatizado.

## Arquitectura del laboratorio

- **4 sedes:** Santiago, Parral, Arica y Magallanes.
- **2 transportes WAN:** MPLS y Business Internet.
- **Plano de control:** SD-WAN Manager, Controller y Validator.
- **Seguridad:** túneles IPsec entre dispositivos WAN Edge.
- **Políticas:** Application-Aware Routing (AAR), SLA y QoS.
- **Automatización:** Python y API REST de Cisco SD-WAN Manager y CML.

## Validación experimental

El proyecto contempla monitoreo de 24 sesiones BFD dirigidas, pruebas de interrupción física de MPLS, degradación controlada del SLA, recuperación de conectividad y generación automática de evidencias en CSV, JSON y Excel.

## Documentación

La guía metodológica presenta los procedimientos de implementación, configuración, validación y recuperación del laboratorio.

**Entorno de validación:** Cisco DevNet Sandbox — Catalyst SD-WAN 20.18.

*Proyecto académico desarrollado con fines educativos y de investigación aplicada.*

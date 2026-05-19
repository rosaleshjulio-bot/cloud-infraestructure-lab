# cloud-infraestructure-lab
Laboratorio de diseño AWS con subredes publicas y privadas
# Diseño de Arquitectura de Red Segura en la Nube

## 📝 Descripción del Proyecto
Este proyecto simula el diseño de una infraestructura de red corporativa utilizando conceptos de AWS. El objetivo es garantizar la alta disponibilidad y la seguridad de los datos aislando los servidores de base de datos de la red pública.

## 🗺️ Diagrama de la Red
(Acá vas a pegar una foto del diagrama que podés hacer gratis en herramientas como Draw.io o Lucidchart)

## 🛠️ Conceptos Aplicados
* **VPC (Virtual Private Cloud):** Segmentación de la red con un bloque CIDR 10.0.0.0/16.
* **Subredes Públicas:** Para los balanceadores de carga y servidores orientados al cliente (10.0.1.0/24).
* **Subredes Privadas:** Para proteger las bases de datos (10.0.2.0/24).
* **Tablas de Enrutamiento:** Configuración de rutas hacia el Internet Gateway para la subred pública.
* **Seguridad:** Implementación de Security Groups (Stateful) para permitir solo el tráfico necesario (Puertos 80, 443 y 22).

## 🚀 Conclusiones del Laboratorio
Con esta estructura se logra mitigar el riesgo de accesos no autorizados directos a la base de datos, cumpliendo con las mejores prácticas de la industria (Well-Architected Framework).

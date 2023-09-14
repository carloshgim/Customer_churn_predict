# Pronóstico de Cancelación de Clientes en Interconnect

## Descripción

Este proyecto de Data Science tiene como objetivo desarrollar un modelo de pronóstico de la tasa de cancelación de clientes para el operador de telecomunicaciones Interconnect. El propósito principal es identificar a los usuarios que planean abandonar el servicio y ofrecerles códigos promocionales y opciones de planes especiales para retenerlos.

El equipo de marketing de Interconnect ha recopilado una variedad de datos personales de los clientes, incluyendo información sobre sus planes y contratos. Estos datos se utilizarán para entrenar el modelo de pronóstico y mejorar la retención de clientes.

## Servicios de Interconnect

Interconnect ofrece principalmente dos tipos de servicios:

1. **Comunicación por teléfono fijo:** Los teléfonos pueden estar conectados a varias líneas simultáneamente.
2. **Internet:** La red puede configurarse a través de una línea telefónica (DSL, *línea de abonado digital*) o mediante un cable de fibra óptica.

Además de estos servicios principales, la empresa también ofrece otros servicios, como:

- **Seguridad en Internet:** software antivirus (*ProtecciónDeDispositivo*) y un bloqueador de sitios web maliciosos (*SeguridadEnLínea*).
- **Soporte técnico (*SoporteTécnico*).**
- **Almacenamiento de archivos en la nube y backup de datos (*BackupOnline*).**
- **Streaming de TV (*StreamingTV*) y directorio de películas (*StreamingPelículas*).**

Los clientes pueden elegir entre un pago mensual o firmar un contrato de 1 o 2 años. Se aceptan varios métodos de pago y se emite una factura electrónica después de cada transacción.

## Descripción de los Datos

Los datos utilizados en este proyecto se han obtenido de diferentes fuentes y se encuentran almacenados en los siguientes archivos:

- `contract.csv`: Contiene información sobre los contratos.
- `personal.csv`: Incluye datos personales de los clientes.
- `internet.csv`: Proporciona información sobre los servicios de Internet.
- `phone.csv`: Contiene información sobre los servicios telefónicos.

En cada archivo, la columna `customerID` (ID de cliente) contiene un código único asignado a cada cliente. Es importante destacar que la información del contrato es válida a partir del 1 de febrero de 2020.

---

# Customer Churn Forecasting at Interconnect

## Description

This Data Science project aims to develop a customer churn prediction model for the telecommunications operator Interconnect. The primary purpose is to identify users planning to leave the service and offer them promotional codes and special plan options to retain them.

Interconnect's marketing team has collected a variety of customer personal data, including information about their plans and contracts. This data will be used to train the forecasting model and enhance customer retention.

## Interconnect Services

Interconnect primarily offers two types of services:

1. **Fixed-line Communication:** Phones can be connected to multiple lines simultaneously.
2. **Internet:** The network can be set up through a telephone line (DSL, Digital Subscriber Line) or via fiber optic cable.

In addition to these core services, the company also provides other services, such as:

- **Internet Security:** Device antivirus software (*DeviceProtection*) and a malicious website blocker (*OnlineSecurity*).
- **Technical Support (*TechnicalSupport*).**
- **Cloud file storage and data backup (*OnlineBackup*).**
- **TV Streaming (*StreamingTV*) and movie directory (*StreamingMovies*).**

Customers can choose between monthly payment or signing a 1- or 2-year contract. Various payment methods are accepted, and an electronic invoice is issued after each transaction.

## Data Description

The data used in this project has been sourced from different channels and is stored in the following files:

- `contract.csv`: Contains contract information.
- `personal.csv`: Includes customer personal data.
- `internet.csv`: Provides information about Internet services.
- `phone.csv`: Contains information about phone services.

In each file, the `customerID` column contains a unique code assigned to each customer. It's important to note that contract information is valid from February 1, 2020.

---

Este README proporciona una visión general del proyecto y su contexto. Para obtener información detallada sobre el proceso de análisis, modelado y resultados, consulte los archivos y documentos específicos en este repositorio.


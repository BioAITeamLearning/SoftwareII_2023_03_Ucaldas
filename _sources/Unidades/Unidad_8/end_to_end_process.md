---
file: end-to-end
---

# Proceso end-to-end de ejemplo

## Escenario: **Plataforma de Reservas para un Restaurante**


## 🌐🍔👨‍🍳 Necesidad de Negocio: 

La compañía **"DeliciousMeals"** necesita una plataforma que permita a los clientes realizar reservas en línea para mejorar la experiencia del cliente y optimizar la gestión de las reservas.

## 📘 Proceso de elicitación de requerimientos

### De la necesidad de negocio a los requerimientos...


### 📌  Requerimientos funcionales:

* **RF1:** Los clientes deben poder ver la disponibilidad de mesas.
* **RF2:** Los clientes deben poder reservar una mesa para una fecha y hora específicas.
* **RF3:** Los empleados deben poder ver y gestionar las reservas.

### 📌  Requerimientos NO funcionales:

* **RNF1:** La plataforma debe ser accesible desde cualquier dispositivo.
* **RNF2:** Tiempo de respuesta del sistema inferior a 2 segundos.

### 🎯 Veamos como quedan los requerimientos.


<img src="../../_static/images/RFEE.png" />


## ✍️🎒  Historias de usuario

### 🧠 Recordemos el formato: 

**Como** [rol] **quiero** [funcionalidad] **para** [beneficio]

### 📌  Historias de usuario:

<img src="../../_static/images/HUEE.png" />

## Pasemos ahora a los casos de uso...

## 📌  Casos de uso:

1. 📍 Autenticación de usuarios.
2. 👀 Visualizar disponibilidad.
3. ✅ Realizar una reserva.
4. 🍽️ Gestionar reservas.
5. ❌ Cancelar reserva.
6. 📆 Actualizar disponibilidad.

### 👥 Actores del sistema:

* Cliente
* Empleado

### Veamos como queda el diagrama de casos de uso...

<img src="../../_static/images/DCUEE.png" />


### Debemos realizar el uso de Include y extend...

<img src="../../_static/images/DCUEE2.png" />

## 📌  Especificación de casos de uso:

### 📌  Caso de uso 1: Autenticación de usuarios.

<img src="../../_static/images/ECUEE1.png" />

### 📌  Caso de uso 2: Visualizar disponibilidad.

<img src="../../_static/images/ECUEE2.png" />

### 📌  Caso de uso 3: Realizar una reserva.

<img src="../../_static/images/ECUEE3.png" />

### 📌  Caso de uso 4: Gestionar reservas.

<img src="../../_static/images/ECUEE4.png" />

### 📌  Caso de uso 5: Cancelar reserva.

<img src="../../_static/images/ECUEE5.png" />

### 📌  Caso de uso 6: Actualizar disponibilidad.

<img src="../../_static/images/ECUEE6.png" />

::::{card-carousel} 1

:::{card}
:margin: 3
:class-body: text-center
:class-header: bg-light text-center
:link: https://github.com/BioAITeamLearning/SoftwareII_2023_03_Ucaldas/raw/main/Unidades/Unidad_8/end2_end.xlsx
**💬 Documento de apoyo*
^^^
```{image} https://mailmeteor.com/logos/assets/PNG/Google_Sheets_Logo_512px.png
:height: 100
```

Documento cuadros end-to-end
+++
Explore this book {fas}`arrow-right`
:::
::::
---
title: Tipos de procesos de Software
---


## Tipos de procesos de software

<img src="https://cms.rootstack.com/sites/default/files/inline-images/equipos2_23.JPG"/>


Algunos de los tipos de procesos de software son:

* Modelos lineales
* Modelos en espiral
* El proceso unificado
* Creación de prototipos
* Entrega continua

Cada uno de estos sirve dependiendo del tipo de producto o desarrollo que queramos realizar, las necesidades, tiempos y stakeholders con los que se cuente.

---

### 🛣️ Modelos lineales

**En este modelo la siguiente fases no puede empezar sin que termine la fase anterior.**

No hay retroalimentación continua por parte del cliente final, no está involucrado **completamente** en todo el desarrollo.

Consume muchos recursos cuando **NO** se hace una buena planeación.

Dentro de los modelos lineales tenemos:

::::{dropdown} Cascada (Waterfall)

```{image} ../../images/U3_14.png
```

* Solo se involucra el cliente en el arranque del proyecto y en la última etapa de verificación (cuando el sistema está completamente desplegado).

* **No permite ejecutar fases en paralelo.**

::::


::::{dropdown} V-Model

```{image} ../../images/U3_15.png
```

* Es una mejora al de cascada.
* Se tiene en cuenta un proceso más riguroso de calidad, de acuerdo a los documentos y fases iniciales del proyecto (requerimientos, diseños)
* El cliente solo ve el desarrollo hasta la última etapa.
* En este el cliente se involucra al cliente al principio y al final, y se debe tener una buena cantidad de información inicial y un buen proceso de requerimientos para entender la idea del cliente.

::::

::::{dropdown} Modelo Diente de sierra

```{image} ../../images/U3_16.png
```

* Involucra de forma más activa al cliente en el desarrollo del proyecto.
* No deja de ser un modelo lineal, pero cuenta con verificación por parte del cliente en cada una de las fases, lo que permite corregir errores y evidenciar avances durante el proyecto

::::

---

### 🌀 Modelos en espiral

Es un proceso iterativo, que realiza las fases por etapas de **4** pasos
se tiene en cuenta mucho la calidad del proceso. y se analiza antes de la implementación los posibles riesgos de esa fase.

<img src="../../images/U3_17.png" />

Este proceso divide la espiral en 4 sectores. Cada cuadrante contiene un tipo de proceso iterativo diferente

EL proceso en **Espiral** permite retroalimentación constante por parte del cliente.

```{warning}
 Se da la posibilidad de regresar a las etapas anteriores, lo que implica un tiempo de desarrollo más largo e indefinido.
```

<img src="../../images/U3_18.png" />

#### Fases del modelo en espiral

<img src="../../images/U3_19.png" />

::::{grid} 1 1 2 2
:class-container: text-center
:gutter: 3

:::{grid-item-card}
:class-header: bg-light

**Fase 1 🌀**
^^^

Determinar los objetivos, alternativas y restricciones del proyecto

*Es lo primero que se realiza.*
:::

:::{grid-item-card}
:class-header: bg-light

**Fase 2 🌀**
^^^

Identificar y resolver los riesgos en el proyecto

*Un grupo debe identificar y resolver los riesgos, normalmente estos deben ser grupos con gran experiencia. Se debe tener un prototipo antes de comenzar a desarrollar y probar.*
:::
:::{grid-item-card}
:class-header: bg-light

**Fase 3 🌀**
^^^

Desarrollar y probar.

*Se realiza el desarrollo y las pruebas que se determinen en los objetivos.*


:::
:::{grid-item-card}
:class-header: bg-light

**Fase 4 🌀**
^^^

Planear la próxima iteración

*Planear lo que se debe realizar en la próxima iteración*
:::

::::

#### ✅ Ventajas del modelo en espiral

* El análisis del riesgo se hace de forma explícita y clara.
* Une los mejores elementos de los anteriores modelos.
* Reduce riesgos del proyecto.
* Incorpora objetivos de calidad.


Este permite hacer ajustes en el plan de trabajo pero requiere consumo alto de recursos y tiempo, en parte porque los riesgos los debe realizar una persona con mucha experiencia.

---

### 🚀 El proceso unificado


<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/f5/Fases_y_Flujos_de_trabajo_en_PUR.svg/400px-Fases_y_Flujos_de_trabajo_en_PUR.svg.png" />

En este se trabaja en fases básicas que tienen unas cuantas iteraciones que se repiten hasta que el producto final se entrega y se considera completa.

Este proceso NO **se centra** en cada uno de los requerimientos del documento de requerimientos sino en los **diagramas** y la **arquitectura**, lo que permite poder hacer las tareas en paralelo junto con otras. Es efectivo cuando se trabaja con arquitecturas orientada a microservicios.

**No** solo es un proceso iterativo sino que también es paralelo.

**Es  muy bueno para proyectos largos**



#### Etapas del proceso unificado


::::{dropdown} Fase de Inicio

```{image} ../../images/U3_20.png
```

La única fase del proceso unificado en la que no se hace iteración es en la fase de inicio o inception

* Se define la arquitectura del sistema.
* Se hace los casos de uso del sistema
  
**Se definen los riesgos y el enfoque del proyecto**

En las otras fases si se desarrolla ciclicamente  y se pueden desarrollar todas las demás etapas en paralelo (hasta cierto punto)

::::

::::{dropdown} Fase de Elaboración

```{image} ../../images/U3_21.png
```

Es la primera que se hace cíclicamente, en esta se generan los diseños y diferentes tipos de  prototipos del desarrollo que se estableció en la fase anterior.

Se generan: 

* Diagramas de casos de uso
* Diagramas de clases
  
Para finalizar esta etapa, se entrega un plan para el desarrollo de la fase siguiente.

::::


::::{dropdown} Fase de Construcción

```{image} ../../images/U3_22.png
```

**Es en esta etapa donde el proyecto cobra vida**

- En esta fase se aplican todo lo que se planea durante la primer etapa   e integra todo lo que se aprende en la etapa de elaboración 

- Recordar que acá todo puede ocurrir en paralelo

- Acá empieza la implementación a ocurrir iterativamente.

::::

::::{dropdown} Fase de Transición

```{image} ../../images/U3_23.png
```

**Ya se encuentra terminada una versión madura para ser publicada con el usuario Final**

- El producto se encuentra en producción.
- Se empieza a hacer la transición del producto de los desarrolladores al cliente y los usuarios finales del producto mediante algunas pruebas y ajustes de errores.
- una vez se termina esta etapa se puede tomar la decisión de volver a otra etapa si se requieren mayores cambios

::::

### Creación de prototipos

<img src="https://ux247.com/wp-content/uploads/2018/07/new-benefits-of-prototyping-ip-1024x600.png" />

Este se aplica a los modelos iterativos, enfocado principalmente en espiral y proceso unificado

Son importantes porque el cliente interviene en las diferentes etapas y por medio de prototipos puede validar el desarrollo del producto y el cumplimiento de los requerimientos.

<img src="../../images/U3_24.png" />


::::{grid} 1 1 2 3
:class-container: text-center
:gutter: 3

:::{grid-item-card}
:class-header: bg-light

**Ilustrativo 📄**
^^^

Es el más básico en el que solo se entregan en un papel algunos bosquejos, o diapositivas. Se aplican para ilustrar una idea de manera rápida y sujeta a muchos cambios, poco fiable pero ahorrando dinero en plasmar la idea de lo que se quiere lograr con el cliente sin gastar de más en tiempo y/o recurso
:::

:::{grid-item-card}
:class-header: bg-light

**Exploratorio 🔍**
^^^

En este se requiere un poco más de tiempo, se programa un poco más, se mira no solo como se verá el sistema sino sus interacciones y aspectos a tener en cuenta o posibles dificultades, como una prueba de concepto. Buscar si hay algo ya desarrollado o que me pueda servir.

:::
:::{grid-item-card}
:class-header: bg-light

**Desechable 🗑️**
^^^

El desechable es en el que se tiene una versión poco funcional, luego se realiza algo más funcional usando la primera y se bota la anterior y así sucesivamente hasta que se logra un prototipo que cumpla con los alcances del proyecto o de la fase.
:::

:::{grid-item-card}
:class-header: bg-light

**Incremental 🪜**
^^^

En este se realizan por fases las entregas, cada entrega es un producto completamente funcional y se van priorizando en el orden de la imágen. vamos de lo que se debe hacer hasta lo que se puede hacer. Agregar nuevas características a lo largo del tiempo

:::

:::{grid-item-card}
:class-header: bg-light

**Evolutivo 🏃🏽‍♂️🦍**
^^^

En este se empieza con todas las características en una forma base, pero todas al tiempo y luego estas van evolucionando conforme pasa el tiempo. va de algo rústico a más elaborado.

:::


::::

### ♻️ Entrega continua 

<img src="https://miro.medium.com/v2/resize:fit:612/1*t6AoYmibARPlaJejcrrZEg.png" />

Es una estrategia para caracterizar la forma en la que se integran las entregas y los avances incrementales que se van presentando sin traumatismos y evitando que existan errores en la integración de los productos o versiones del software

permite entregar continuamente avances del proyecto y que cada vez que se haga una entrega, se compile, integre, pruebe y se despliegue
se deben tener varias ramas en el proyecto.

<img src="../../images/U3_25.png" />
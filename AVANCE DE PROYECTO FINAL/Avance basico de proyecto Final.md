---

# 📘 **APF 1 – VERSIÓN FINAL MEJORADA**

## **Transformación Digital Logística – Mueblería J & M**

---

## **Introducción**

El presente proyecto tiene como finalidad analizar el funcionamiento actual de la empresa Mueblería J & M, un negocio local ubicado en la ciudad de Arequipa dedicado a la comercialización de muebles para el hogar. Actualmente, la empresa desarrolla sus actividades mediante una tienda física y el uso de redes sociales como principal canal de comunicación con sus clientes, lo cual le permite operar de manera continua, pero con limitaciones en la gestión interna.

Uno de los principales aspectos críticos identificados es la falta de organización en la logística del negocio, específicamente en el registro de pedidos, el control de inventario y la planificación de entregas. Estas actividades se realizan de manera manual, lo que genera desorden en la información, retrasos en la atención y posibles errores que afectan tanto la eficiencia operativa como la satisfacción del cliente.

En un entorno donde incluso los pequeños negocios están adoptando herramientas digitales, la ausencia de un sistema de gestión representa una desventaja competitiva. Por ello, el presente proyecto se enfoca en analizar el proceso logístico actual del negocio, identificando sus principales problemas, causas y consecuencias.

A partir de este diagnóstico, se plantea una propuesta de transformación digital enfocada en la mejora de la logística interna mediante el uso de herramientas tecnológicas accesibles y de bajo costo. La solución propuesta no busca ser altamente compleja, sino adecuada al tamaño del negocio, permitiendo mejorar la organización, reducir errores y optimizar la gestión de pedidos y entregas. Finalmente, se desarrollará un prototipo funcional que represente esta solución.

---

# **1. Información general del caso de estudio**

## **1.1 Empresa elegida**

**Nombre:** Mueblería J & M

**Descripción general:**
Mueblería J & M es un negocio local dedicado a la venta de muebles para el hogar, ofreciendo productos como salas, camas, roperos y comedores. Su modelo de negocio se basa principalmente en la atención presencial en tienda física, complementada con la promoción y comunicación a través de redes sociales como Facebook y WhatsApp.

El negocio gestiona sus operaciones internas de manera manual, incluyendo el registro de pedidos, control de productos y coordinación de entregas. Este enfoque, aunque funcional en etapas iniciales, presenta limitaciones conforme aumenta el volumen de ventas.

**Rubro:** Comercio minorista de muebles

---

## **1.2 Contexto actual**

**Situación actual:**
Actualmente, la empresa atiende consultas de clientes mediante redes sociales y de manera presencial. El proceso de venta inicia cuando el cliente solicita información, la cual es proporcionada manualmente por el vendedor. Sin embargo, no existe un sistema estructurado para registrar pedidos ni controlar el inventario.

Esto genera problemas como pérdida de información, duplicidad de pedidos y dificultad para verificar la disponibilidad de productos en tiempo real. Además, la coordinación de entregas se realiza de forma informal, lo que puede ocasionar retrasos y desorganización.

**Segmentos de clientes:**

* Familias que buscan equipar su hogar
* Clientes locales de Arequipa
* Personas que adquieren muebles por primera vez

**Canales de atención:**

* Tienda física
* WhatsApp
* Facebook

---

# **2. Diagnóstico del proceso actual**

## **2.1 Proceso logístico actual (As-Is)**

El proceso logístico actual inicia con la solicitud del cliente y continúa con el registro manual del pedido por parte del vendedor. Luego, se verifica el stock consultando al área de almacén, lo cual no es inmediato. Posteriormente, se coordina la entrega del producto.

Este proceso presenta falta de integración, ya que no existe un sistema centralizado que conecte todas las etapas, generando dependencia de la comunicación verbal o mensajes.

---

### 🔹 Diagrama de carriles (DESCRITO PARA EXCALIDRAW)

**Carriles:**

* Cliente
* Vendedor
* Almacén
* Repartidor

**Flujo detallado:**

Cliente → Consulta producto
Vendedor → Responde información
Cliente → Solicita compra
Vendedor → Registra pedido manual
Almacén → Verifica stock
Vendedor → Confirma disponibilidad
Cliente → Realiza pago
Repartidor → Coordina entrega
Cliente → Recibe producto

---

### 🔹 Flujo principal

Inicio → Pedido → Registro manual → Verificación stock →
¿Hay stock? → (No: espera / Sí: entrega) → Fin

---

## **2.2 Actores del proceso**

Los actores principales son el cliente, quien inicia la compra; el vendedor, encargado de la gestión del pedido; el personal de almacén, responsable del control de productos; y el repartidor, encargado de la entrega final.

---

## **2.3 Personas involucradas (MEJORADO)**

El cliente busca rapidez, claridad y cumplimiento en la entrega. El vendedor requiere herramientas que le permitan organizar pedidos sin errores. El encargado de almacén necesita visibilidad clara del inventario para evitar inconsistencias. El repartidor requiere información precisa sobre entregas para cumplir con los tiempos establecidos.

---

## **2.4 Problemas, causas e impacto (MEJORADO)**

* **Falta de registro digital:** causa errores y pérdida de pedidos → impacto: desorganización
* **Control manual de inventario:** genera información desactualizada → impacto: ventas fallidas
* **Coordinación informal de entregas:** causa retrasos → impacto: insatisfacción del cliente
* **Dependencia del vendedor:** limita escalabilidad → impacto: baja eficiencia

---

## **2.5 Nivel de madurez digital (MEJORADO)**

La empresa presenta un nivel de madurez digital bajo, debido a la ausencia de sistemas de gestión integrados, la dependencia de procesos manuales y la falta de automatización en la logística. Aunque utiliza redes sociales, estas no forman parte de un sistema estructurado, lo que limita su capacidad operativa y de crecimiento.

---

# **3. Propuesta de transformación digital**

## **3.1 Innovaciones propuestas (JUSTIFICADAS)**

* Sistema de registro de pedidos → evita pérdida de información
* Control digital de inventario → mejora precisión de stock
* Lista de entregas organizada → reduce retrasos
* Historial de pedidos → mejora seguimiento

---

## **3.2 Propuesta de valor (MEJORADO)**

* **Cliente:** reducción de tiempos de entrega y mayor confiabilidad
* **Vendedor:** menor carga manual y reducción de errores
* **Almacén:** control actualizado del inventario
* **Empresa:** mejora en eficiencia y organización

---

## **3.3 Transformación digital**

Se propone implementar un sistema logístico básico que integre pedidos, inventario y entregas en una sola plataforma accesible para el negocio.

---

## **3.4 Tecnologías (JUSTIFICADAS)**

* HTML/CSS/JS → interfaz simple y accesible
* SQLite → bajo costo y facilidad de uso
* Sistema web → accesible desde cualquier dispositivo
* WhatsApp → mantener canal actual integrado

---

# **4. Alcance del proyecto**

El proyecto contempla el desarrollo de un prototipo funcional que permita gestionar pedidos, inventario y entregas de manera integrada. Este sistema permitirá centralizar la información, mejorar la comunicación interna y reducir errores.

No incluirá pagos en línea ni automatización avanzada, enfocándose en una solución realista y aplicable a un negocio pequeño.

---

# **Referencias**

* Material del curso
* Casos de digitalización en PYMES

---

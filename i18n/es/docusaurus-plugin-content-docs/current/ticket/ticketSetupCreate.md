---
sidebar_position: 0
---

# Configurar sistema de tickers

Este subcomando te permitirá configurar el sistema de tickets. Este sistema es un poco complejo, por lo que se explicará por partes.

## Uso

`/configurar-tickets crear <canal> <categoría> <rol> <everyone> <descripción> <botón> {transcripciones}`

![ticket setup Command](img/ticketSetupCommandCreate.png)

## Explicación

Configurar este sistema puede ser un poco confuso al principio. Esta guía te permitirá entender cada parámetro y su funcionalidad.

### Parámetros requeridos

* **canal**: Este es el canal en el que el bot enviará el mensaje inicial, que servirá como punto de entrada al sistema. Este NO es el canal donde se crearán los tickets.
* **categorpía**: Dentro de la categoría especificada se crearán los canales de tickets. Se recomienda tener una categoría vacía para evitar conflictos con otros canales.
* **rol**: El rol especificado aquí tendrá permisos para ver, acceder y realizar acciones dentro del ticket. Se recomienda establecer un rol de soporte o un rol de administrador (ten en cuenta que los miembros con permisos de administrador ignorarán esta restricción).
* **everyone**: Para garantizar compatibilidad, rendimiento y minimizar posibles errores, debes enviar el rol "everyone" aquí. De esta manera, el bot podrá almacenarlo en caché y realizar acciones más rápido.
* **descripción**: Establecerá el texto de descripción para el mensaje que se enviará en el canal especificado. Puede ser una descripción para informar a los usuarios sobre cuándo abrir un ticket u otro mensaje similar.
* **botón**: El texto del botón para abrir un ticket. Se recomienda mantenerlo corto o agregar un emoji.

### Parámetros opcionales

:::info

Como administrador, eres responsable de informar a los usuarios de que sus mensajes se almacenarán como una transcripción.

:::
* **transcripciones**: Configurar este parámetro hará que el bot envíe una transcripción en un archivo .html al canal establecido aquí.
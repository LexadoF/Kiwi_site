---
sidebar_position: 2
---

# Remover advertencias

Este es el subcomando para eliminar una advertencia, te permite quitar una advertencia de un usuario. Para esto necesitarás el id de la advertencia.

:::note

Los ids de las advertencias se calculan dinámicamente, por lo que debes revisar utilizando el comando de revisión antes de eliminar una advertencia.

:::

## Uso

`/advertencias eliminar <usuario> <id>`

![warns add Command](img/warnsRemoveCommand.png)

## Explanation

Este comando tiene 2 parámetros obligatorios: el usuario y el id.

### Parámetros obligatorios

* usuario: Este puede ser cualquier usuario en el servidor que tenga advertencias.
* id: Este es el id específico de la advertencia que deseas eliminar. Debido a que la lista asigna ids dinámicos, si un usuario, por ejemplo, tiene 3 advertencias y eliminas la número 2, la advertencia número 3 se convierte en la número 2. Por esta razón, asegúrate de revisar las advertencias con el comando revisar antes de remover alguna.
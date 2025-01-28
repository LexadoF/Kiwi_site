---
sidebar_position: 0
---

# Agregar rol

Este es el subcomando agregar role, te permite asignar un rol al usuario especificado. Para esto, el bot debe tener su propio rol por encima del rol que deseas asignar.

## Uso

`/roles añadir <usuario> <rol>`

![roles add Command](img/rolesAddCommand.png)

## Explicación

Este comando tiene 2 parámetros obligatorios: el usuario al que se le asignará el rol y el rol que se asignará.

### Parámetros obligatorios

* usuario: Este puede ser cualquier usuario en el servidor que no tenga el rol (no tendrá ningún efecto si el usuario ya tiene el rol).
* rol: Este rol debe estar por debajo del rol del bot, de lo contrario, el bot no tendrá permiso para asignarlo y se mostrará un error.
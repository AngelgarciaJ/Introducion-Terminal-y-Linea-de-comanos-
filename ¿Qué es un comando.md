# 驴Qu茅 es un comando?

Un comando puede ser cuatro cosas:

1. Un programa ejecutable.
2. Un comando de utilidad de la `shell`.
3. Una funci贸n de `shell`.
4. Un alias.

<aside>
馃挕 El comando `type` es un comando que nos permite analizar la naturaleza de otros comandos.

</aside>

Para crear alias en la terminal podemos hacer uso de la palabra reservada `alias`, este nos crea un alias temporal para la sesi贸n actual en la que estamos trabajando; hacerlo persistente se ver谩 en una siguiente secci贸n.

```bash
alias l="ls -lh"
```

### Comandos de esta clase

**Comando**

help {comando}

man {comando}

info {comando}

whatis {comando}

**Acci贸n**

Muestra informaci贸n sobre c贸mo usar un comando (BASH).

Muestra el manual del comando indicado.

Muestra el manual del comando indicado.

Muestra una descripci贸n corta del comando indicado.
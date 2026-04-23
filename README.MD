# Guía Rápida de Comandos Cisco (Packet Tracer)

Esta guía detalla los comandos básicos para la configuración de routers y switches en Cisco Packet Tracer, organizados por sus respectivos modos de operación.

---

### 1. Modo Usuario
**Prompt:** `Router>`
* `enable`: Activa el modo **Privilegiado** (Administrador).

### 2. Modo Privilegiado (Administrador)
**Prompt:** `Router#`
* `configure terminal`: Accede al modo de **Configuración Global**.
* `copy running-config startup-config`: Guarda la configuración actual en la memoria persistente (NVRAM).

### 3. Modo de Configuración Global
**Prompt:** `Router(config)#`
* `interface [nombre]`: Selecciona una interfaz específica para configurar (ej: `interface FastEthernet0/0`).
* `end`: Sale directamente al modo Privilegiado.

### 4. Modo de Configuración de Interfaz
**Prompt:** `Router(config-if)#`
* `ip address [direccion_ip] [mascara]`: Asigna una dirección IP a la interfaz.
* `no shutdown`: Enciende (habilita) la interfaz seleccionada.
* `exit`: Regresa al modo de Configuración Global.

---

### Resumen de Navegación
| Comando | Acción |
| :--- | :--- |
| `exit` | Retrocede un nivel en la jerarquía de menús. |
| `end` | Vuelve directamente al modo Privilegiado (`#`). |
| `wr` | Abreviatura común de `write` (equivalente a guardar cambios). |
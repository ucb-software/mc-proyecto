# Proyecto BOT de Ingeniería de Software.

## Intoriducción

Este documento específica el porqué es necesario tener un BOT para **Control de vacaciones en una empresa**

## Problemática

La empresa MONSTER INC. cuenta con 50 empleados y no tiene un sistema de Recursos Humanos, entonces los empleados a la hora de solicitar permisos o dias de vacación, desconocen:

 1. Cuántos días de vacaciones les queda.
 2. El histórico de los permisos solicitados.
 3. El histórico de las vacaciones solicitadas.
 4. Pedir un permiso vía bot y que se quede registrado si fue aprobado o no por el Gerente de RRHH.
 5. Perir dias de vacación via BOT y ver si fue aprobado o no.

Como Gerente de RRHH, tengo los siguientes problemas:
 1. Registro en un excel los permisos, y dias de vacación solicitados.
 2. Por la cantidad de empleados a veces se omiten registros.
 3. Quisiera una notificación un día antes de que un empleado salga de vacaciones.
 4. Quiero una notificación cuando un empleado solicite permiso o dias de vacación, para el caso de permisos quiero una justificación y si corresponde imagenes (baja medica).

## Valor el valor que el proyecto va a dar a la empresa.

Un control automatizado de permisos y vacaciones permitirá:

 - Tangible (Siempre se traduce en dinero)
   - Evita el fraude por un control manual.
 - Intangible (no se traducen en dinero)
   - Los empleados estaran mas felices al tener un control de sus permisos y vacaciones.

## Ejemplo de funcionamiento del BOT

### Menu de Empleado

```
Emp: Hola
Bot: Hola selecciona una opción:
1. Ver permisos solicitados
2. Ver vacaciones solicitadas este año
3. Solicitar permiso
4. Solicitar vacación
5. Cancelar permiso.
6. Cancelar vacación.
```

Si selecciona la opción 1:

```
Bot: Usted pidio los siguientes permisos este año
1. 01/Ene/2022  8:30 a 14:00  Visita al medico
2. 10/Ene/2022  9:00 a 15:00  Emergencia Familiar

Desea:
1. Ver otro año
2. Volver
```


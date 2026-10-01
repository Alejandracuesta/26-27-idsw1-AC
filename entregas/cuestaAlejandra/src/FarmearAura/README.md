# EXPLIACION:

## FARMEAR AURA:

### GLOSARIO:
- Persona: individuo que puede farmear aura.
- Aura: cantidad acumulada que representa el nivel de aura de una persona.
- Accion: actividad que puede generar aura.
- Evento: situacion en la que puede realizarse una accion.
- RegistroAura: registro de una ganancia de aura producida por una accion.

##SUPUESTOS:
1. Una persona tiene una determinada cantidad de aura.
2. Las acciones pueden proporcionar una cantidad de aura.
3. La cantidad obtenida depende de la accion y su dificultad.
4. El aura se puede acumular.
5. No todas las acciones tienen por que generar aura.
6. Una accion puede realizarse dentro de un evento, aunque tambien puede realizarse fuera de uno.

### ¿POR QUE?

He incluido RegistroAura para poder conservar el historial de como se consigue el aura. De esta manera no solamente se conoce el aura actual de una persona, sino tambien las acciones que han provocado sus aumentos.
No hemos creado una clase Aura, porque considero que el aura no necesita existir como objeto independiente. En este modelo nos interesa principalmente la cantidad de aura que tiene una persona.

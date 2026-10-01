# EXPLICACION:

## SOMBRA:

### GLOSARIO:
- Objeto: elemento que bloquea la luz.
- Sombra: zona donde llega menos luz debido a un objeto.
- FuenteLuz: elemento que emite luz.
- Superficie: lugar sobre el que se proyecta la sombra.

### SUPUESTOS:
1. Para que exista una sombra debe haber una fuente de luz.
2. Debe existir un objeto que bloquee parte de esa luz.
3. La sombra se proyecta sobre una superficie.
4. Una fuente de luz puede producir sombras de varios objetos.
5. La posicion y tamanio de la sombra dependen de la posicion de la fuente de luz y del objeto.
6. No distinguimos entre sombra total y penumbra.

### ¿POR QUE?:
He creado Sombra como una clase porque no queria representar solamente si un objeto tiene sombra o no. Una sombra tiene caracteristicas propias, como su longitud, posicion y direccion.
Tambien he creado FuenteLuz y Superficie, ya que la sombra depende de estos elementos. El mismo objeto puede producir una sombra diferente si cambia la posicion de la fuente de luz.

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

## SIMPATIA:

###GLOSARIO:
- Persona: individuo que interactua con otras personas.
- Interaccion: situacion en la que dos o mas personas se relacionan.
- Comportamiento: accion o actitud mostrada durante una interaccion.
- Contexto: situacion en la que ocurre una interaccion.
- Valoracion: opinion de una persona sobre la simpatia de otra.

### SUPUESTOS:
1. Una persona puede ser considerada simpatica de forma diferente por distintas personas.
2. La simpatia depende del comportamiento y del contexto.
3. Una interaccion puede tener varios comportamientos asociados.
4. Una persona puede valorar a otra despues de una interaccion.
5. No existe un valor absoluto de simpatia.

### ¿POR QUE?

No he puesto simplemente un atributo simpatico dentro de Persona, porque obligaria a considerar que una persona es simplemente simpatica o no simpatica.
En cambio, he decidido representar la simpatia mediante comportamientos e interacciones, junto con las valoraciones de otras personas.
Tambien he creado Contexto, porque una persona puede comportarse de manera diferente dependiendo de la situacion. Por ejemplo, puede comportarse de una forma con sus amigos y de otra en el trabajo.
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
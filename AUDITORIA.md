#	Problema detectado	Categoría	Evidencia	¿Por qué es un problema?
1	Falta de meta viewport	Responsive	Línea 7 (comentada)	El formulario no es responsivo y se ve diminuto en dispositivos móviles.
2	Ausencia de etiquetas (<label>)	Accesibilidad	Inputs generales	Los placeholders desaparecen al escribir; los lectores de pantalla no identifican el campo.
3	Contraste de texto insuficiente	Accesibilidad	Clase .low-contrast	El texto gris claro sobre blanco no cumple con los estándares mínimos de legibilidad.
4	Tipos de input inadecuados	Validación	Fecha y Teléfono	Usar type="text" impide el uso de calendarios nativos y teclados numéricos en móviles.
5	Botones con colores idénticos	UX	Botón Cancelar	El botón de cancelar tiene el mismo color que el de guardar, causando confusión visual.
6	Instrucciones absurdas	Contenido	Ayuda de contraseña	Pedir "jeroglíficos" es una barrera imposible que impide completar el registro.
7	Acción destructiva peligrosa	UX	Botón Borrar todo	Su ubicación junto a "Guardar" y su color llamativo invitan a perder todos los datos por error.
8	Solicitud de datos excesiva	UX	Religión / Estado civil	Pide información privada y sensible que no es necesaria para un registro estándar.
9	Requisito de extensión irreal	Contenido	Textarea 500 palabras	Obligar a escribir un ensayo para registrarse garantiza que el usuario abandone el sitio.
10	Falta de feedback de errores	Validación	Nota al pie (.tiny-note)	Indicar que "no se mostrarán detalles" en caso de error deja al usuario bloqueado y sin guía.
11	Layout desorganizado	Jerarquía Visual	Sección de dirección	Campos amontonados sin estructura de rejilla (grid) que dificultan la lectura rápida.
12	Lenguaje hostil	Contenido	Banner superior	Amenazar al usuario con rechazar su solicitud sin explicación crea una pésima experiencia emocional.


Evidencia en movil que evidencia el punto 1:
127.0.0.1_5500_index.html(Samsung Galaxy S20 Ultra).png

Evidencia en Escritorio: 
127.0.0.1_5500_index.html.png

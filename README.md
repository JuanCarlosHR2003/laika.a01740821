# Laika

Administration system for homeless animal adoptions.

Created for the Laika Organization in Culiacán Sinaloa as a social service project.

# Stack

- JavaScript
- Node
- MongoDB
- EJS

# Run Locally

Make sure to have Node and Mongodb installed on your computer

```bash
npm install
npm run dev
```

# ToDo

## Pedro

### Complicado

- [x] Search Filters
- [x] Pagination/Infinite Scroll
- [x] Calendar View (como Reminders)
- [x] Protected Routes to Edit and Delete (Prompt)
- [x] Zip Codes JSON data using JS
- [ ] Pedir contraseña para editar y para poder acceder a ver los datos (dos veces)
- [ ] Filtro calendario desde una fecha hasta otra fecha
- [ ] Busqueda para buscar los que NO tengan un evento
- [ ] Agregar campo de otro y descripcion en eventos
- [ ] Agregar nota médica, text_area grande en eventos
- [ ] Adopcion agregar edad de adopcion
- [ ] Adopciones apartado para notas grande al final
- [ ] Adopciones editar
- [ ] Laika juntar ambas paginas en un dominio
- [ ] Migrar de Wix a Laika.org

### Sencillo

- [x] Asterisco para los forms opcionales
- [x] Arreglar editar animal
- [x] Crear animal: (opcionales) Alias, Señas Particulares y Fotos
- [x] Crear animal: añadir color de animal (Blanco, Negro, Café y Otro) (obligatorio)
- [x] Crear animal: meses y años, guardar la fecha de nacimiento estimada (obligatorio)
- [x] Crear campo para PetcoID (opcional) (numero entero)
- [x] Crear rescate: (opcionales) Codigo Postal, Colonia y Calle, Rescatista. (quitar) Notas
- [x] En la cita agregar campo para descripción (obligatoria)
- [x] Adopciones (opcionales) Regreso, Calle
- [x] Adopción quitar calle y solo imprimir en la tabla municipio y colonia
- [x] Dropdowns for knowing which vaccines the animal has
- [x] Add references
- [ ] Cambiar tipo a especie
- [ ] Parcino, Siamés, atigrado (agg colores)
- [ ] Sexo (agg otro)
- [ ] Cambiar Adoptado Por (Cuidado por) y Adopciones por (Hogar)
- [ ] Laika vs Cuidadano en Otro Rescate
- [ ] Telefono en adopciones agregar (obligatorio), perfil de redes o correo (opcional)
- [x] Orden de fotos dejar asi
- [x] Mandar pdf de las screen de la pagina (con los menús)
- [ ] Deployment (set server hour to gmt-6)

## (Juan, Rogelio, Ozner y JC)

- [ ] Crear pdf con datos para imprimir (animal, eventos, rescate, hogares(censurados), citas), que sean opcionales
- [ ] Logo de Laika al Final de cada página
- [ ] Rediseñar los colores de la página. Solo un diseño #6ea6a5 verde aqua y #8a1b70 Rosa-Morado
- [ ] Error handling (try/catch) y mensajes de error (Si ponen " " muchos espacios vacíos, debe marcar error también). Tal vez con mongoose validators (?) o npm zod (?) o función trim (?)
- [ ] Tablas con headers centrados
- [ ] Pasar los datos de la base antigua a la nueva manualmente
- [ ] Betatesting con Eva

# Authors

- Pedro Moreno
- Juan Hernández
- Rogelio Lizárraga
- Juan Bernal
- Ozner

(Credits to Rey Vega and Agustín Quintanar)

# References

[1st version of the app](https://github.com/ReyVega/Laika_WebPage)

[Neighborhoods data](https://www.correosdemexico.gob.mx/SSLServicios/ConsultaCP/CodigoPostal_Exportar.aspx)

[Municipalities data](https://cuentame.inegi.org.mx/monografias/informacion/sin/territorio/div_municipal.aspx?tema=me&e=25)

[Default images](https://www.freepik.es/fotos/perro-mestizo)

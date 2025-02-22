# Propuesta TP DSW

## Grupo
### Integrantes
* 50955 - Scarpecci, Tomás Agustín
* 51434 - Vuelta, Tomás Manuel
* 50462 - Aquilante, Jazmín

### Repositorios
* [frontend app](https://github.com/tomasscarpecci/frontend-app)
* [backend app](https://github.com/tomasscarpecci/backend-app)

## Tema
### Descripción
Nuestro Software se basa en una aplicación que funciona como un portal de noticias. Los usuarios podrán ingresar a la plataforma de forma gratuita. En la app se podrán visualizar noticias de diferentes editoriales asociadas a la plataforma y así poder tener diferentes puntos de vista sobre un mismo hecho. Lo innovador es que se podrán leer noticias completas de varios diarios (nacionales e internacionales) registrándose en un solo sitio, sin tener que hacerlo en la pagina de cada editorial.

### Modelo
[Draw.io](https://drive.google.com/file/d/1LGKbmAMBDoTjJfaFTT9kgwQqup--Kbi8/view?usp=sharing) 

## Alcance Funcional 
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Categoria<br>2. CRUD Usuario<br>3. CRUD Editorial<br>4. CRUD Noticia<br>|
|CRUD dependiente|1. CRUD Noticia {depende de} CRUD Categoria<br>2. CRUD Noticia {depende de} CRUD Editorial<br>|
|Listado<br>+<br>detalle| 1. Listado de noticias, muestra título, fecha y editorial => detalle CRUD Noticia y CRUD Editorial<br> 2. Listado de usuarios, muestra nombre, usuario, mail, edad ⇒ detalle CRUD Usuario<br>|
|CUU/Epic|1. Mostrar una noticia.<br>2. Eliminar una editorial y por consiguiente todas sus noticias.|

## WorkSpace
[Notion](https://www.notion.so/Workspace-Desarrollo-de-SW-73c2ff5055bc4f3ea4d0dc12968b0895?pvs=4)

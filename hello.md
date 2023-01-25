# Curso de Markdown

## Títulos

# H1 Título
## H2 Título
### H3 Título
#### H4 Título
##### H5 Título
###### H6 Título

## Texto

Texto en *italica*

Texto en **negrita**

Texto ~~tachado~~

Texto subíndice Sub~indice~

Texto superíndice  2^10^

## Listas desordenadas

* Item 1
  * Item anidado
    * Item anidado 2
* Item 2

## Listas ordenadas

1. Item 1
2. Item 2
   1. Item anidado

## Generar enlaces

[Mangas](https://inmanga.com "Leer mangas online")

## Crear una cita

> Esto es una cita
> Otra linea de la cita

## Crear una linea horizontal

---

___

## Citar codigo

`console.log("Hola mundo")`

Multiples lineas de codigo

### Javascript
```javascript
const persona = {
  nombre: "Pipo",
  edad: 20,
  profesion: "Desarrollador web",
  musicaRock: true,
  mostrarInformacion: function () {
    console.log(
      `El nombre es ${this.nombre} y su edad es ${this.edad} y su profesion es ${this.profesion}`
    );
  },
};
persona.mostrarInformacion()
```
### Html
```html
<h1 class="lowerCamelCase" id="usar-kebab-case">Hola mundo</h1>
```
### Css
```css

*, *::before, *::after {
  box-sizing: border-box;
}
* {
  margin: 0;
}
html, body {
  height: 100%;
}
body {
  line-height: 1.5;
  -webkit-font-smoothing: antialiased;
}
img, picture, video, canvas, svg {
  display: block;
  max-width: 100%;
}
input, button, textarea, select {
  font: inherit;
}
p, h1, h2, h3, h4, h5, h6 {
  overflow-wrap: break-word;
}
```

## Tablas

| Nombre | Apellido | Edad | Profesion         |
| ------ | -------- | ---- | ----------------- |
| Pipo   | Pipote   | 20   | Desarrollador web |
| Juan   | Perez    | 30   | Desarrollador web |

## Imágenes

### Usando url
![Visual Studio Code Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Visual_Studio_Code_1.35_icon.svg/1200px-Visual_Studio_Code_1.35_icon.svg.png "Visual Studio Code Logo")

### Usando ruta relativa
![Visual Studio Code Logo](./assets/img/vslogo.png "Visual Studio Code Logo")

## Tareas

- [x] Tarea 1
- [ ] Tarea 2
- [ ] Tarea 3

## Emojis
### :smile: :+1: :100: :fire: :rocket: :muscle: :metal: :heart: :alien: :zap: :tada:

## Hacer menciones a usuarios

@PipoPipote

## Hacer menciones a equipos

@github/developers
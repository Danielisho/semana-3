### Asignaciones | Semana 3 | Clases 1,2,3 y 4

##### <u>CLASE 1</u>
<details>
<summary>
Calentamiento
</summary>
Terminar los juegos de Flexbox Froggy y CSS Grid Garden!

* [Flexbox Froggy](https://flexboxfroggy.com/#es)
* [CSS Grid Garden](https://cssgridgarden.com/#es)
* </details>

<details>
<summary>
Ejercicio Layout
</summary>
1. Crear su propio layout de cards que muestre las entradas de su blog usando el layout visto en clase.

No lo hagas literal, asegúrate de tener un cambio diferencial.
</details>


---

##### <u>CLASE 2</u>

<details>
<summary>
Calentamiento
</summary>
Agregar la siguiente etiqueta meta a tu HTML de la hoja de vida:
`<meta name='viewport' content='width=device-width, initial-scale=1.0,
maximum-scale=1.0' />`

1. Abrir la hoja de vida en el navegador (Usando npx vite dev ).
2. Abrir el inspector haciendo clic derecho > Inspeccionar en el navegador.
3. Hacer clic en la vista responsive (El icono del smartphone).
4. Constratar los cambios en vista responsive con y sin la etiqueta meta.

**¿Qué diferencias viste?**
</details>

<!-- -->

<details>
<summary>
Mobile First Responsive
</summary>
1. Crear una versión Mobile First Responsive de su hoja de vida (CV).
2. Hacer commit de dichos cambios, o multiples commits.

<cite>No haremos fork ni un pull request por ahora.</cite>

**Solución:**

Ver archivo `index.html`
</details>

---

##### <u>CLASE 3</u>
<details>
<summary>
Ejercicio con Vite
</summary>

1. Ejecutar `npm init -y` en la raíz del proyecto de la hoja de vida.

2. Agregar vite como dependencia `npm install vite`

3. Agregar en el `package.json` los scripts de vite:

```javascript
{
  "scripts": {
	"dev": "vite",
	"build": "vite build",
	"preview": "vite preview"
	}
}
```


</details>

<!-- -->

<details>
<summary>
Añade tu primer archivo de JavaScript
</summary>

1.- Agrega un tag de `<script type="module" src="/main.mjs"> </script>`
2. Escribe en el siguiente código:

```javascript
// main.mjs
function handleSubmit(event) {
event.preventDefault(); //
console.log("Hola mundo");
}
const $form =
document.querySelector("form");
$form.addEventListener("submit",
handleSubmit);
```
3.- Haz submit del formulario y revisa la consola (clic derecho inspecionar > consola)

**Solución:**

Ver archivo `index.html`
</details>
---

##### <u>CLASE 4</u>
<details>
<summary>
Ejercicio Framework
</summary>

1.- Hacer fork del repositorio de la semana-3 `https://github.com/undefinedacademy/semana-3`
2. Subir la maquetación de la portada de blog usando Flexbox y CSS Grid a la carpeta `students-blog`.
3. Subir la maquetación mobile first responsive de la hoja de vida a la carpeta `student-scv`.
4. Elegir entre **Bootstrap** o **TailwindCSS** y maquetar el formulario de contacto con dicha tecnología en la carpeta `student-forms`.

**Estructura del PR**
```
.
├── student-cvs/
│ └── glrodasz-0666/
│ ├── index.html
│ ├── form.html
│ ├── styles.css
│ └── main.mjs
├── student-blogs/
│ └── glrodasz-0666/
│ ├── index.html
│ └── styles.css
└── student-forms/
└── glrodasz-0666/
├── src
└── package.json
```
**nota:** 
¡Si usas ambos, crea las carpetas dentro de `student-forms : bootstrap|tailwind` !
</details>

---

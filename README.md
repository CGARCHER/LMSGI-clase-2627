# LMSGI · Ejercicios y ejemplos de clase · 2026–2027

Repositorio de **Lenguajes de Marcas y Sistemas de Gestión de Información** con los ejercicios y ejemplos que realizamos en clase durante el curso 2026–2027.

Sirve para repasar las explicaciones, consultar el código y continuar las prácticas. Los ejemplos se van construyendo y revisando en el aula: pueden mostrar pasos intermedios y aspectos pendientes de mejorar.

## Contenido

Actualmente trabajamos HTML:

- Estructura de un documento, encabezados y párrafos.
- Imágenes y rutas relativas.
- Enlaces a apartados de una página.
- Listas, tablas y formularios.

Iremos incorporando nuevos ejemplos conforme avance el curso.

## Organización

```text
html/
└── ejemplo1/
    ├── index.html          # Ejemplo con los módulos de DAW
    ├── images/            # Imágenes del ejemplo
    └── otras/
        └── pagina1.html   # Imagen enlazada desde una subcarpeta
```

## Cómo trabajar con los ejemplos

1. Descarga el repositorio desde **Code → Download ZIP** y descomprímelo, o clónalo:

   ```bash
   git clone https://github.com/CGARCHER/LMSGI-clase-2627.git
   ```

2. Abre la carpeta del repositorio en Visual Studio Code.
3. Abre el HTML que quieras estudiar, por ejemplo `html/ejemplo1/index.html`.
4. Visualízalo en el navegador. Puedes utilizar **Live Preview** para trabajar con un servidor local.
5. Modifica el código, guarda y comprueba el resultado. Conserva la estructura de carpetas para que funcionen las rutas.

Los ejemplos actuales no necesitan instalar dependencias. Los formularios permiten practicar el marcado y los controles; este repositorio no incluye un servidor que procese o guarde sus datos.

## Apuntes y herramientas de consulta

- [Apuntes de la asignatura](https://marcas.cgarcher.dev/).
- [Unidad 2 · HTML](https://marcas.cgarcher.dev/docs/unidades/02/).
- [MDN Web Docs en español](https://developer.mozilla.org/es/): documentación y ejemplos.
- [HTML y CSS de mclibre](https://www.mclibre.org/consultar/htmlcss/): explicaciones y ejercicios.
- [Validador HTML del W3C](https://validator.w3.org/nu/#textarea): pega el documento completo para comprobar errores y advertencias.

Al repasar, intenta explicar qué hace cada etiqueta y por qué se utiliza. Comprueba el código en el navegador y en el validador; que una página se vea bien no significa que su HTML sea correcto.

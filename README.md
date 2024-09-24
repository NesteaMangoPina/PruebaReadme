# PruebaReadme
Prueba de clase

## 1. ¿Qué es Markdown y para qué se utiliza?

Markdown es un lenguaje de marcas que permite convertir texto plano en HTML sin la necesidad de utilizar etiquetas complejas. Fue creado en 2004 con el propósito de crear un formato fácil de escribir y leer, que pudiera ser convertido fácilmente en HTML.

Markdown se desarrolló en un contexto en el que los creadores de contenido necesitaban una forma rápida y sencilla de formatear texto sin tener que lidiar con el código detallado de HTML. Su simplicidad permite que sea utilizado en una variedad de plataformas y aplicaciones, como blogs, foros, y sistemas de control de versiones como GitHub.

## 2. Comparación entre Markdown y HTML

### Características principales de Markdown:
- **Simplicidad**: El lenguaje es fácil de leer y escribir sin experiencia técnica.
- **Portabilidad**: Es agnóstico de la plataforma y puede ser convertido a diferentes formatos (HTML, PDF, etc.).
- **Legibilidad**: Un archivo escrito en Markdown es legible sin necesidad de ser procesado por un navegador o software.

### Ventajas de Markdown sobre HTML:
- **Más sencillo de aprender y usar**: No requiere etiquetas complicadas.
- **Más limpio**: El texto escrito en Markdown es más legible y menos propenso a errores de sintaxis.
- **Menos tiempo para escribir**: Ideal para escritura rápida o documentación técnica.

### Inconvenientes de Markdown frente a HTML:
- **Limitaciones**: Markdown tiene menos capacidad para formateos complejos en comparación con HTML.
- **Dependencia en conversiones**: Necesita ser convertido a HTML o PDF para ser publicado en la web.

## 3. Aplicaciones y Plataformas que utilizan Markdown

Markdown se utiliza en una variedad de plataformas debido a su simplicidad y funcionalidad. Ejemplos incluyen:
- **GitHub**: Para archivos README y la documentación de proyectos.
- **Jekyll**: Un generador de sitios estáticos que utiliza Markdown para el contenido de las páginas.
- **Notion**: Herramienta de productividad que soporta Markdown para la creación de notas y documentación.
- **Slack**: Aunque no usa Markdown directamente, permite un subconjunto de funcionalidades para formatear texto.

Estas plataformas han adoptado Markdown por su simplicidad, fácil conversión a HTML y por la legibilidad del texto plano.

## 4. Ejemplos de Formato en Markdown

### Párrafos:
Este es un párrafo de texto. Es un espacio de linea

### Encabezados:
Para crear un encabezado solo hay que poner # delante del encabezado contra mas pongas mas pequeño sera siendo 1 solo el mas grande
# Encabezado 1
## Encabezado 2
### Encabezado 3

### Enlaces:
``[Texto del enlace](URL)`` Habria que poner esto para un enlace

[Google](https://www.google.com/)

### Imagenes:

Para una imagen hay que poner esto ``![Texto alternativo de la imagen](https://ejemplo.com/imagen.jpg)``

![Texto alternativo de la imagen](https://media.istockphoto.com/id/636379014/es/foto/manos-la-formaci%C3%B3n-de-una-forma-de-coraz%C3%B3n-con-silueta-al-atardecer.jpg?s=612x612&w=0&k=20&c=R2BE-RgICBnTUjmxB8K9U0wTkNoCKZRi-Jjge8o_OgE=
)

### Negrita:

Seria el texto entre **    **holaaa**

### Bloques o lineas de codigo:

```python
def suma(a, b):
    return a + b
```


### Listas:

Para crear una lista no ordenada, se utiliza un guion -, asterisco * o signo más + seguido de un espacio y el texto.

- Manzana
- Naranja
- Plátano

Para crear una lista ordenada, se usan números seguidos de un punto 1. y un espacio.

1. Primer paso
2. Segundo paso
3. Tercer paso

Puedes anidar listas (listas dentro de listas) utilizando indentación (4 espacios o una tabulación).
1. Frutas
   - Manzana
   - Naranja
2. Verduras
   - Zanahoria
   - Brócoli


### Tablas:

Las tablas en Markdown se crean utilizando | para separar las columnas, y guiones - para crear la fila del encabezado.

| Columna 1   | Columna 2   |
|-------------|-------------|
| Dato 1      | Dato 2      |
| Dato 3      | Dato 4      |

### Enlace a otro documento:
``[Texto del enlace](ruta/del/documento.md)``
[Texto del enlace](ruta/del/documento.md)

# Arafel CSS

Arafel CSS es un micro-framework CSS ligero y moderno que te permite crear interfaces de usuario atractivas y responsivas rápidamente, sin la complejidad de frameworks más grandes.

## Instalación

### Opción 1: Descarga directa
Descarga el archivo `arafel-css.zip` e incluye el archivo CSS en tu HTML:

```html
<link rel="stylesheet" href="css/arafel.min.css" />
```

### Opción 2: Usar CDN (Próximamente)
Una vez que subas este repositorio a GitHub, podrás usar un CDN como jsDelivr:
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/tu-usuario/Arafel-CSS/dist/arafel.min.css" />
```

## Guía de Uso Rápido

Arafel CSS incluye clases de utilidad para estructurar tu página y componentes hermosos listos para usar.

### Sistema de Anchos (Responsivo)
Usa las clases `.ancho-X` para definir el tamaño de tus elementos (del 1 al 100).
Arafel incluye variantes responsivas que se activan según el tamaño de la pantalla: `.ancho-sm-*` (> 576px), `.ancho-md-*` (> 768px), y `.ancho-lg-*` (> 992px).

```html
<!-- Ocupa el 100% en móvil y el 50% en pantallas medianas o más -->
<div class="ancho-100 ancho-md-50">Contenedor Responsivo</div>
```

### Botones Modernos
Botones con efectos hover y estados activos. Colores disponibles: rojo, verde, azul, negro, gris, amarillo, naranja, marino.

```html
<!-- Botón con fondo -->
<button class="button azul-con-fondo">Aceptar</button>

<!-- Botón hueco (Outline) -->
<button class="button rojo-sin-fondo">Cancelar</button>
```

### Campos de Texto
Campos de formulario con una suave transición y efecto de brillo al enfocar.

```html
<input type="text" class="input" placeholder="Escribe algo aquí...">
```

### Encabezado (Header)
Un header fijo con efecto Glassmorphism (cristal opaco) y sombra. Se recomienda añadir un contenedor con `.espacio` justo después para empujar el contenido hacia abajo y evitar que quede escondido bajo el encabezado.

```html
<header class="header">
  <h1 class="texto-blanco negritas">Mi Proyecto</h1>
</header>
<div class="espacio"></div>
```

### Loaders / Indicadores de Carga
El framework también incluye varios indicadores de carga en puro CSS con nombres en español. Por ejemplo:

```html
<!-- Anillo doble -->
<div class="lds-anillo-doble"></div>

<!-- Corazón latiendo -->
<div class="lds-corazon"><div></div></div>

<!-- Girador tipo reloj -->
<div class="lds-girador"><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div></div>
```

## Licencia
MIT License - Creado para facilitar el desarrollo web rápido y moderno.

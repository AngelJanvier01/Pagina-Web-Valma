---
name: VALMA
description: Sistema visual para soluciones de salud con alcance nacional
colors:
  navy: "#0a3747"
  teal: "#007f77"
  teal-bright: "#00a598"
  lime: "#bcef70"
  paper: "#f5f8f4"
  mint: "#e3f2eb"
  white: "#ffffff"
  line: "#d6e6e1"
typography:
  display:
    fontFamily: "Manrope, sans-serif"
    fontSize: "clamp(3rem, 4.5vw, 4.6rem)"
    fontWeight: 700
    lineHeight: 1.02
    letterSpacing: "-0.04em"
  headline:
    fontFamily: "Manrope, sans-serif"
    fontSize: "clamp(2.1rem, 3.6vw, 3.5rem)"
    fontWeight: 700
    lineHeight: 1.08
    letterSpacing: "-0.04em"
  body:
    fontFamily: "DM Sans, sans-serif"
    lineHeight: 1.6
rounded:
  control: "5px"
  field: "8px"
spacing:
  section: "98px"
  section-mobile: "64px"
components:
  button-primary:
    backgroundColor: "{colors.navy}"
    textColor: "{colors.white}"
    rounded: "{rounded.control}"
    height: "46px"
  button-accent:
    backgroundColor: "{colors.teal}"
    textColor: "{colors.white}"
    rounded: "{rounded.control}"
    padding: "15px 22px"
    height: "56px"
---

# Design System: VALMA

## Overview

**Creative North Star: "Cobertura en movimiento"**

Una identidad editorial para el sector salud que combina claridad institucional con una sensación contemporánea de cercanía y alcance. Los contrastes generosos, la tipografía expresiva y las imágenes de la portada dan protagonismo a la información útil.

La misma gramática visual acompaña la navegación, los servicios, los formularios y las páginas de soporte. Las interacciones son evidentes y respetan la preferencia de movimiento reducido.

**Key Characteristics:**
- Jerarquía editorial audaz y legible.
- Superficies luminosas y espacios generosos.
- Retícula clara que se adapta a pantallas pequeñas.
- Verde azulado y lima como acentos sobre azul marino.

## Colors

El azul marino ancla la identidad; el verde azulado guía acciones, el lima aporta pequeños acentos y el papel claro mantiene una base luminosa. El menta distingue secciones y el blanco presenta contenido y controles. Los bordes suaves separan superficies sin imponer peso visual.

## Typography

**Display Font:** Manrope, con alternativa sans-serif.  
**Body Font:** DM Sans, con alternativa sans-serif.

Los títulos utilizan una escala expresiva y espaciado compacto; el cuerpo mantiene una lectura cómoda. El encabezado principal alcanza `clamp(3rem, 4.5vw, 4.6rem)` y los títulos de sección `clamp(2.1rem, 3.6vw, 3.5rem)` en escritorio.

## Layout

La portada combina dos columnas y una imagen a sangre; las secciones usan una retícula y espaciado amplio. El contenido principal alcanza 1240 px, mientras la portada usa una alineación propia. Las secciones tienen 98 px de separación vertical, reducida a 64 px en móvil. A 700 px o menos, la portada y las vacantes se apilan, y la banda de servicios pasa a dos columnas.

## Elevation & Depth

Las superficies son mayormente planas. El contraste de fondos, los bordes y los cambios de escala organizan la página; las tarjetas de la identidad nueva no utilizan sombras.

## Shapes

Los controles y tarjetas comparten esquinas contenidas de 5 px; los campos conservan 8 px. Las listas de servicios usan líneas superiores y carecen de borde envolvente, lo que refuerza su carácter editorial.

## Components

### Buttons

Los botones principales usan azul marino con texto blanco, al menos 46 px de altura y esquinas de 5 px. La acción principal de la portada usa verde azulado y una altura mínima de 56 px. El foco visible usa un contorno de 3 px con separación de 3 px.

### Cards / Containers

Las tarjetas se presentan sobre blanco con borde tenue y sin sombra. En servicios se transforman en elementos abiertos con una línea superior verde y separación amplia.

### Inputs / Fields

Los campos tienen fondo blanco, borde tenue, esquinas de 8 px y tipografía heredada. El foco visible usa el mismo contorno que las acciones.

### Navigation

La navegación usa texto de peso fuerte sobre blanco y destaca el contacto con un botón oscuro. En pantallas pequeñas se reorganiza y mantiene accesibles los enlaces.

## Do's and Don'ts

### Do:
- **Do** mantener una jerarquía tipográfica clara y espacio suficiente entre contenidos.
- **Do** adaptar la retícula a dispositivos pequeños y preservar la legibilidad de los controles.
- **Do** utilizar el color de acento para señalar acciones y puntos de interés.

### Don't:
- **Don't** presentar afirmaciones comerciales sin respaldo como hechos verificados.
- **Don't** permitir que los recursos decorativos compitan con la navegación o el contenido.

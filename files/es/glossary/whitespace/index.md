---
title: Espacio en blanco
slug: Glossary/Whitespace
tags:
  - Glosario
  - Gramática léxica
  - espacioenblanco
translation_of: Glossary/Whitespace
original_slug: Glossary/Espacio_en_blanco
---
El **espacio en blanco** es un conjunto de {{Glossary("Caracter", "caracteres")}} que se utiliza para mostrar espacios horizontales o verticales entre otros caracteres. A menudo se utilizan para separar fragmentos en {{Glossary("HTML")}}, {{Glossary("CSS")}}, {{Glossary("JavaScript")}} y otros lenguajes informáticos.Los caracteres de espacio en blanco y su uso varía de un lenguaje a otro.

## En HTML

La [_HTML Living Standard_](https://html.spec.whatwg.org/) especifica 5 caracteres ASCII como espacio en blanco: `U+0009` TAB, `U+000A` LF, `U+000C` FF, `U+000D` CR y `U+0020` ESPACIO. En forma de texto, se tratan como caracteres de espacio normal y los espacios en blanco secuenciales se contraen como un solo espacio en muchos casos (este comportamiento se puede cambiar mediante la propiedad CSS {{cssxref("white-space")}}. También se utilizan como separadores del nombre de un elemento y sus parámetros, nombres de clases, etc.

## En JavaScript

La [especificación del lenguaje ECMAScript® 2015](https://www.ecma-international.org/ecma-262/6.0/#sec-white-space) establece varios puntos de código Unicode como espacio en blanco: `U+0009` CARACTERES de TABULACIÓN \<TAB>, `U+000B` TABULACIÓN DE LÍNEA \<VT>, `U+000C` FORM FEED \<FF>, `U+0020` ESPACIO \<SP>, `U+00A0` ESPACIO SIN ROTURA \<NBSP>, `U+FEFF` ANCHO CERO NO -BREAK SPACE \<ZWNBSP> y otra categoría “Zs” Cualquier otro punto de código Unicode “Separador, espacio” \<USP>. Estos caracteres suelen ser innecesarios para la funcionalidad del código.

1.  Especificaciones

    1.  [Espacio en blanco ASCII](https://infra.spec.whatwg.org/#ascii-whitespace)
    2.  [Especificación del lenguaje ECMAScript® 2015](https://www.ecma-international.org/ecma-262/6.0/#sec-white-space)

2.  Referencias

    1.  [Cómo se manejan los espacios en blanco mediante HTML, CSS y el DOM](/es/docs/Web/API/Document_Object_Model/Whitespace)
    2.  {{cssxref("white-space")}}

3.  Artículos de Wikipedia

    1.  {{interwiki("wikipedia", "El caracter de espacio en blanco")}}

4.  [Glosario](/es/docs/Glossary)

    1.  {{Glossary("Character", "Caracter")}}

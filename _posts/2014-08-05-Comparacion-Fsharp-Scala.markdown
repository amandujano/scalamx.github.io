---
layout: post
author: "amandujano"
title:  "Comparando Scala y F#"
date:   2014-08-05 00:14:55
categories: scalamx redaccion
---

Continuando con la serie de posts para el blog, voy a establecer una breve comparación entre Scala y F#.
Debido a que mis conocimientos son limitados en cuanto a la programacion funcional, ofrezco una compararación de ambos lenguajes a nivel básico, tomando como base características funcionales destacadas. Comenzaré con una explicación sencilla de los dos lenguajes y posteriormente haré una tabla comparativa de los dos lenguajes funcionales.

Lenguajes funcionales
---------------------
En programación funcional, los programas son ejecutados evaluando expresiones, mientras en los programas de programacion imperativa son compuestos de sentencias que cambian el estado global y manipulan variables cuando son ejecutados. Los programas funcionales son más parecidos a funciones matemáticas, ellos siempre mapean las mismas salidas a las mismas entradas sin cambiar los valores de  las variables de entrada ellos mismos y ademas estos pueden ser encadenados entre otros programas funcionales mediante entradas y salidas (Composicion funcional).

Scala
---------------------
Se compila en el bytecode de Java y se ejecuta en la parte superior de la máquina virtual de Java (JVM).

Mientras que Scala es un lenguaje funcional, tambien incorpora todos los elementos de los lenguajes imperativos y orientados a objetos lo cual le permite la introducción de características de programación funcional a una comunidad más amplia de programadores.

Siendo un desarrollo Open Source, esta disponible para todos los sistemas operativos que soportan Java, los plugins de desarrollo de Java y sus archivos de definición de sintaxis están disponibles para los más populares editores e IDEs de desarrollo, incluyendo Netbeans, Eclipse e IntelliJ.  

http://www.developer.com/lang/other/article.php/3890906/Scala-vs-F-Round-2-Application-Programming-Features.htm

F#
---------------------
Es un lenguaje de proposito general desarrollado por Microsoft que corre como parte del Common Language Runtime (CLR) de .NET. También esta basado en otro ortodoxo lenguaje funcional ([OCAML][ocalm]).

Microsoft introdujo F# en la plataforma .Net, aparte de otras razones, para incrementar el interes en la programación funcional y la oportunidad de hacer computación de alto rendimiento y paralelismo.

Apesar de su sintaxis que es distintivamente funcional, F# es de hecho un lenguaje híbrido que engloba estilos funcional, imperativo y orientado a objetos.
Sus caracteristicas orientadas a objetos e imperativas son presentadas mayormente para compatibilidad con la plataforma .Net.

- F# vs. Scala: First Order Functions (Funciones de Primer Orden)
- F# vs. Scala: Lazy Evaluation (Evaluacion Perezosa)
- F# vs. Scala: Lambda Expressions and Currying (Expresiones Lambda y Currying)
- F# vs. Scala: Lambda Expressions (Expresiones Lambda)
- F# vs. Scala: Pattern Matching (Relacion de Patrones)
- F# vs. Scala: List Comprehensions (Listas Comprensivas)
- F# vs. Scala: Multiple Inheritance via Mixins (Herencia Multiple via Mixins)


http://www.developer.com/lang/other/article.php/3883051/Scala-vs-F-Comparing-Functional-Programming-Features.htm

--------------------------------------------------------------------------------------------------------------------------------------------------------------------



http://www.infoq.com/articles/scala-java-myths-facts
http://www.genbetadev.com/formacion/lista-por-comprension
http://www.genbetadev.com/tag/scala
http://timkellogg.me/blog/2013/06/22/comparing-scala-to-fsharp/
http://es.slideshare.net/pt114/haskell-vs-f-vs-scala

https://skillsmatter.com/explore?q=scala

[scala]:    http://scala-lang.org/
[ocalm]:	http://es.wikipedia.org/wiki/Ocaml

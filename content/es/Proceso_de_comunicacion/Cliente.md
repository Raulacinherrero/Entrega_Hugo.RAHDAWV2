---
title: "Cliente"
date: 2022-10-24T16:06:18+01:00
draft: false
weight: 1
---

Cada vez que saltes entre páginas, dependiendo a parámetros que hayas dado, o información contenida en la base de datos, PHP podrá construir una versión diferente de la misma página. Quieres que la misma página responda a eventos que tu realizas mientras estás en ella, que se comporte como un programa de propósito general. Es JavaScript, todo los navegadores lo entienden. Con Javascript puedes manejar todos los eventos y hacer que tu página web actúe de una forma dinámica.

Te permite manipular directamente los elementos HTML y modificar su estado, forma, color, posición y diversas propiedades. El código Javascript, va embebido dentro de HTML. Por supuesto, si generaste tu página con PHP, este te permite a su vez generar código JavaScript, que es algo que el navegador entiende junto con HTML. Al final, en tiempo de ejecución, el usuario interactúa directamente solo con el código escrito en JavaScript.

Con estas 3 herramientas, podemos lograr crear una página web realmente poderosa. Bueno digamos que toma un tiempo entender el «orden de ejecución» de una página web. Si notas, la comunicación con la base de datos del servidor...esta en PHP. Se ejecuta en el servidor que contiene la BD y solo mediante código PHP, y todo eso se hace antes de cargar la página en tu navegador.

Es decir JavaScript es todo lo bonito y dinámico que quieras, pero no puede comunicarse con la base de datos. Si yo le pido a mi web ciertos datos de mi base de datos, usando JavaScript, este no puede dármelos. De esa manera, no puedo actualizar dinámicamente los elementos de mi web, al menos mediante la Base de Datos. Una opción, sería que llamara una nueva página, de acuerdo a esos parámetros, y se haría todo el proceso de nuevo, empezando por crear la nueva página con PHP en base a la consulta.

Cada que yo solicite algo a la base de datos, Javascript mandaría llamar una nueva página que mediante PHP hace el trabajo.
Todos los assets quedan localmente. Ustedes hagan lo que tengan q hacer para que aparezcan.



Some email clients, like outlook, strip out <style> tag from emails, so it's best to have your CSS written inline within your markup.

Esta testeado en muchos clientes con inline styles e imagenes random de algun servidor online, con Mailosaur y Litmus,

Les dejo las imagenes originales importadas localmente desde los assets y la hoja css con todos los estilos (no esta linkeada);
 aparte les dejo la hoja CSS con los mismos estilos ordenados como lo pidieron

 Por su puesto, si importan correctamente las imagenes originales se visualizarán perfectamente

 Respecto a la fuente, hice una investigacion muy profunda. Las web fonts, como es el caso de Inter, solo funcionan en clientes de Apple. 
 Lo que hice fue implementar Inter, y en los casos que Inter no sea reconocida, se aplique Arial como la fallback font. 
 Por qué Arial? de todas las "safe fonts" (fuentes que funcionan siempre en todas las maquinas) es la que más se parece a Inter, siendo casi identica. 

 Arial bold no la tienen todas las maquinas


 Teniendo en cuenta el modo oscuro, puse a proposito fondo blanco porque no se solicitó compatibilidad con modo oscuro, y la maqueta es blanca en todo momento.


 Las media queries son lo unico que puse en el style tag. Porque inline es la forma mas segura de estilizar para email.


 Las imagenes las subi a un PRIVATE IMAGE STORAGE


 Puse fallbacks en todo lo posible
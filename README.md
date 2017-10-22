# CLASE PRACTICA
## Replicar el siguiente ejercicio
![Pagina a raplicar](assets/images/img-nuestras-coders.png "titulo")

### HTML
Lo primero a realizar es la maquetación HTML que tendra como elemento padre a SECTION quien tendra en su interior un H1(titulo principal "Nuestras Coders") un DIV(que sera la pequeña barra negra ubicada debajo del h1) y una LIST(que tendra las inmagenes de cada coder).

```
		
		//<section>
        <h1>Nuestras Coders</h1>
        <div class="box"></div>
        <ul>
            <li id="dary"><a href="#">Dary Reinaga</a></li>
            <li id="diana"><a href="#">Diana Torero</a></li>
            <li id="lucero"><a href="#">Lucero Gómez</a></li>
            <li id="marilyn"><a href="#">Marilyn Villano</a></li>
            <li id="milagros"><a href="#">Milagros Ponce</a></li>
            <li id="yenai"><a href="#">Yenai Delgado</a></li>
        </ul>
    </section>
		
```
### CSS
Mediante el selector universal le damos la tipografia adecuada al HTML, al DIV que hace las veces de bloque decorativo se le da el width y height adecuados para su buena visualizacion.
Con respecto al contenedor SECTION se le aplica clear, margin auto y un width adecuado para que los elementos que posteriormente flotaran respeten ese margen.
A las etiquetas LI se les ha contenido una imagen tipo sprite, la cual posteriormente sera configurada una por una para que muestre lo adecuado y las cuales a su vez estaran con float left.

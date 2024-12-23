--- 
   <h1> Ecco come ho cambiato lo stile del mio sito:</h1>
---
    /* Importa il font Poppins */
        @import url('https://fonts.googleapis.com/css2?
        family=Poppins:wght@400;600&display=swap');


    /* Applica il font Poppins all'intero sito e perrsonalizzazione del cursore*/
        body {
            font-family: 'Poppins', sans-serif;
            cursor: url('images/cursore.png') 16 16, auto;
        }

    /* Personalizzazione del cursore all'hover e all'active */

        a:hover,
        a:active,
        a span:hover,
        a span:active{
            cursor: url('images/cursore_click.png'), auto; /* Stesso cursore per hover e click */
        }


    /* Nascondi <h1> solo nella pagina About */
        body.page-about h1 {
            display: none;
        }


    /* Imposta il colore di sfondo dell'header e della navbar */
        .md-header {
            background-color: #da3d8e;  /* Rosa */
        }


    /* Personalizza i link della navbar */
        .md-nav .md-nav__link {
            color: white;
            text-decoration: none;
            position: relative;
            display: inline-block;
            overflow: hidden;
        }

    /* Aggiunta di stile ai link della navbar */
        .md-tabs{
            background-color: #5a78ba;
        }

        .md-tabs__item--active a{
            font-weight: bold;
        }

        a.md-nav__link span{
            color: #da3d8e;
        }

        a.md-nav__link span:hover{
            color: #5a78ba;
        }
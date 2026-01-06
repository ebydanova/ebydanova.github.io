---
title: Práctica
layout: default
filename: practica
--- 
<html>
  <head>
    <style>
      .grid {
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        gap: 16px;
      }
    </style>
  </head>
  <body>
    <h2>La ruleta de la sort</h2>
    
    <p>Ja ha acabat el primer trimestre del curs escolar 2025-26. Per a moltes famílies ha sigut un canvi d'etapa perquè els seus nens han començat infantil, primaria o ESO, o bé perquè han canviat del centre educatiu. Alguns, però, no han aconseguit plaça a l'escola que volien i han acabat en una altra, no sempre del seu gust. Aquest any en tota Catalunya 91,5% dels alumnes que es van inscriure a I3 <strong>han tingut sort</strong> i van rebre assignació a un centre triat en la primera opció - bé per tenir germans al mateix centre, bé per reunir altres puntuacions altes o bé per guanyar el sorteig de places. Tot i això, 11% de les places es van quedar vacants i ratio per grup de mitjana es va quedar en 18 alumnes per classe, per sota dels límits objectiu. Evidentment, alguns centres son més sol·licitats que altres.</p>

    <p><strong>Aquesta situació, ¿és la mateixa entre comarques?</strong></p>  
  
    <p>Així van anar les preinscripcions d'aquest curs per a 1r d'educació infantil (I3):</p>

    <div class="grid">
      <div style="min-height:360px" id="datawrapper-vis-a7vM3"><script type="text/javascript" defer src="https://datawrapper.dwcdn.net/a7vM3/embed.js" charset="utf-8" data-target="#datawrapper-vis-a7vM3"></script><noscript><img src="https://datawrapper.dwcdn.net/a7vM3/full.png" alt="Assignats en 1a petició (Choropleth map)" /></noscript></div>
      <div style="min-height:360px" id="datawrapper-vis-D2mVd"><script type="text/javascript" defer src="https://datawrapper.dwcdn.net/D2mVd/embed.js" charset="utf-8" data-target="#datawrapper-vis-D2mVd"></script><noscript><img src="https://datawrapper.dwcdn.net/D2mVd/full.png" alt="Places vacants (Choropleth map)" /></noscript></div>
      <div style="min-height:360px" id="datawrapper-vis-Gzsk5"><script type="text/javascript" defer src="https://datawrapper.dwcdn.net/Gzsk5/embed.js" charset="utf-8" data-target="#datawrapper-vis-Gzsk5"></script><noscript><img src="https://datawrapper.dwcdn.net/Gzsk5/full.png" alt="Ratios per grup (Choropleth map)" /></noscript></div>
    </div>

    <p></p>

    <small>Source 1: <a target="_blank" href="https://analisi.transparenciacatalunya.cat/Educaci-/Estad-stica-de-l-assignaci-de-places-en-el-proc-s-/99md-r3rq/about_data">Portal de dades obertes de la Generalitat de Catalunya. <i>"Estadística de l’assignació de places en el procés de la Preinscripció en els ensenyaments obligatoris i Infantil segon cicle"</i></a>, accessed 19/11/2025.</small>
    <br><small>Source 2: <a target="_blank" href="https://www.idescat.cat/dades/obertes/censph">Institut d’Estadística de Catalunya. <i>"Cens de població i habitatges"</i></a>, accessed 31/12/2025.</small>
    <br><small>Preprocessed with RStudio (view <a target="_blank" href="https://github.com/ebydanova/ebydanova.github.io/new/main/viz/pr/inscription_data_preprocessing.md">source code</a>) and visualized with <a target="_blank" href="https://www.datawrapper.de/">Datawrapper</a> and <a target="_blank" href="https://public.tableau.com/app/discover">Tableau</a> by Elena Bydanova Puchkova.</small>
    <br><small>Download transformed data: <a target="_blank" href="https://github.com/ebydanova/ebydanova.github.io/blob/main/viz/pr/preinscripcions_preprocessed.zip">file 1</a>, <a target="_blank" href="https://github.com/ebydanova/ebydanova.github.io/blob/main/viz/pr/preinscripcions_cens.csv">file 2</a></small>
  
  </body>
</html>

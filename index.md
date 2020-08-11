---
layout: page
title: Seja Bem-Vindo!
permalink: /
---

### SEJA BEM VINDO A VICTOR3D PÁGINA PESSOAL! Estamos com muitas novidades... APROVEITE!

#### Caro visitante, nós dedicamos mais de 90% do nosso tempo na internet em nosso site, tudo para que você possa ficar informado e atualizado de tudo da internet e do mundo, em troca nós pedimos um voto para que outras pessoas vejam nosso trabalho.

<iframe width="560" height="315" src="https://www.youtube.com/embed/OIyAHzMk1N4" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Músicas Nacionais

[![Barão Vermelho - Álbum (1996)](/musicas/capas/baraovermelho-1996-album.jpg){:style="height: 150px; float: left; margin-right: 7px; margin-top: 7px;"}](/musicas/baraovermelho-1996-album.html)
[![Kid Abelha - Greatest Hits (1990)](/musicas/capas/kidabelha-1990-greatesthits.jpg){:style="height: 150px; float: left; margin-right: 7px; margin-top: 7px;"}](/musicas/kidabelha-1990-greatesthits.html)
[![Legião Urbana - Mais do Mesmo (1998)](/musicas/capas/legiaourbana-1998-maisdomesmo.jpg){:style="height: 150px; float: left; margin-right: 7px; margin-top: 7px;"}](/musicas/legiaourbana-1998-maisdomesmo.html)
[![Virgulóides - Virgulóides? (1997)](/musicas/capas/virguloides-1997-virguloides.jpg){:style="height: 150px; float: none; margin-right: 7px; margin-top: 7px;"}](/musicas/virguloides-1997-virguloides.html)

<div class="posts">
  {% for post in site.posts limit:1 %}
    <article class="post">

      <h3>{{ post.title }}</h3>

      <div class="entry">
        {{ post.excerpt }}
      </div>

      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Leia mais</a>
    </article>
  {% endfor %}
</div>

### Novelas

[![Os Imigrantes](/novelas/img/os_imigrantes_escada.jpg){:style="height: 150px; float: left; margin-right: 7px; margin-top: 7px;"}](/novelas/os_imigrantes.html)
[![Irmãos Coragem](/novelas/img/irmaos_coragem_tarcisio_e_claudio.jpg){:style="height: 150px; float: left; margin-right: 7px; margin-top: 7px;"}](/novelas/irmaos_coragem.html)
[![O Bem Amado](/novelas/img/o_bem_amado_p_gracindo.jpg){:style="height: 150px; float: left; margin-right: 7px; margin-top: 7px;"}](/novelas/o_bem_amado.html)
[![Gabriela](/novelas/img/gabriela_tema.jpg){:style="height: 150px; float: left; margin-right: 7px; margin-top: 7px;"}](/novelas/gabriela.html)
[![Escalada](/novelas/img/escalada_tarcisio_e.jpg){:style="height: 150px; float: left; margin-right: 7px; margin-top: 7px;"}](/novelas/escalada.html)
[![Saramandaia](/novelas/img/saramandaia_elenco.jpg){:style="height: 150px; float: left; margin-right: 7px; margin-top: 7px;"}](/novelas/saramandaia.html)
[![O Casarão](/novelas/img/o_casarao_r_sorrah_festa.jpg){:style="height: 150px; float: left; margin-right: 7px; margin-top: 7px;"}](/novelas/o_casarao.html)
[![Escrava Isaura](/novelas/img/escrava_isaura_lucelia_e_beatriz_lyra.jpg){:style="height: 150px; float: left; margin-right: 7px; margin-top: 7px;"}](/novelas/escrava_isaura.html)
[![Dancin'Days](/novelas/img/dancin_days_sonia_danca.jpg){:style="height: 150px; float: left; margin-right: 7px; margin-top: 7px;"}](/novelas/dancin_days.html)
[![Roque Santeiro](/novelas/img/roque_santeiro_l_duarte_r.jpg){:style="height: 150px; float: left; margin-right: 7px; margin-top: 7px;"}](/novelas/roque_santeiro.html)
[![Que Rei Sou Eu?](/novelas/img/que_rei_sou_eu_edson_e_giulia_gam.jpg){:style="height: 150px; float: left; margin-right: 7px; margin-top: 7px;"}](/novelas/que_rei_sou_eu.html)
[![Mulheres de Areia](/novelas/img/mulheres_de_areia_glorias_pires.jpg){:style="height: 150px; float: left; margin-right: 7px; margin-top: 7px;"}](/novelas/mulheres_de_areia2.html)
[![A Próxima Vítima](/novelas/img/a_proxima_vitima_logo.jpg){:style="height: 150px; float: left; margin-right: 7px; margin-top: 7px;"}](/novelas/a_proxima_vitima.html)
[![O Rei do Gado](/novelas/img/o_rei_do_gado_foto_antiga.jpg){:style="height: 150px; float: left; margin-right: 7px; margin-top: 7px;"}](/novelas/o_rei_do_gado.html)
[![Pantanal](/novelas/img/pantanal_caruso_castro_e_alves.jpg){:style="height: 150px; float: left; margin-right: 7px; margin-top: 7px;"}](/novelas/pantanal.html)
[![Éramos Seis](/novelas/img/eramos_seis.jpg){:style="height: 150px; float: left; margin-right: 7px; margin-top: 7px;"}](/novelas/eramos_seis.html)
[![Redenção](/novelas/img/redencao_couco_e.jpg){:style="height: 150px; float: none; margin-right: 7px; margin-top: 7px;"}](/novelas/redencao.html)

<div class="posts">
  {% for post in site.posts offset:5 limit:1 %}
    <article class="post">

      <h3>{{ post.title }}</h3>

      <div class="entry">
        {{ post.excerpt }}
      </div>

      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Leia mais</a>
    </article>
  {% endfor %}
</div>

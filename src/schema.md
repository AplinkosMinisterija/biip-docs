```mermaid
flowchart-elk

aaa["👤 AAA darbuotojas"]
aad["👤 AAD darbuotojas"]
am["👤 AM darbuotojas"]
vstt["👤 VSTT darbuotojas"]
visuomene["👤 Visuomenė"]
tiekejas["👤 Duomenų gavėjas"]
gavejas["👤 Duomenų tiekėjas"]

subgraph "Biologinės įvairovės informacinė sistema"
subgraph admin["BĮIS vidinis portalas"]
  biip_admin_web["Administravimo aplinka: vidinė dalis"]
end

subgraph web["BĮIS išorinis portalas"]
  all_web["Įžuvinimų sistema: vidinė dalis
  Verslinė žvejyba: vidinė dalis
  Medžioklės informacinė sistema: vidinė dalis
  Medžioklės žurnalas: Android ir iOS programėlė
  Nelaisvėje laikomų laukinių gyvūnų informacinė sistema: vidinė dalis
  Upių, ežerų ir tvenkinių kadastras (UETK): vidinė dalis
  Rūšių stebėjimo informacinė sistema: vidinė dalis"]
end

subgraph public["BĮIS viešasis portalas"]
  all_public["Verslinės žvejybos ir įžuvinimo modulis: vieša dalis
  Žuvų išteklių mokslinių tyrimų duomenys
  Medžioklės informacinė sistema: vieša dalis
  Nelaisvėje laikomų laukinių gyvūnų informacinė sistema: vieša dalis
  Rūšių stebėjimo informacinė sistema (INVA): vieša dalis
  Rūšių stebėjimo informacinė sistema (SRIS): vieša dalis
  Upių, ežerų ir tvenkinių kadastras (UETK): vieša dalis
  BĮIS svetainė
  Ekosisteminės paslaugos
  Gamtotvarka
  Genetiškai modifikuotų organizmų duomenų bazė
  Želdynai"]
end

subgraph api["BĮIS moduliai"]
  all_api["Administravimo aplinka: API
  Autentifikavimo ir naudotojų valdymo modulis: API
  Įžuvinimų sistema: API
  Verslinė žvejyba: API
  Medžioklės informacinė sistema: API
  Nelaisvėje laikomų laukinių gyvūnų informacinė sistema: API
  Rūšių stebėjimo informacinė sistema: API
  Upių, ežerų ir tvenkinių kadastras (UETK): API
  Žemėlapių naršyklė: vidinė dalis
  Žemėlapių naršyklė: QGIS
  BĮIS įrankiai: API"]
end

postgresql[("PostgreSQL")]
mariadb[("MariaDB")]
redis[("Redis")]
s3[("S3")]
qgis["QGIS serveris"]
vt["Vector Tiles"]
end

subgraph remote["IS, registrai ir kadastrai"]
    viisp["VIISP"]
%%    alis["ALIS"]
%%    adresu_registras["Adresų registras"]
%%    sris_kadastras["Saugomų teritorijų kadastras"]
%%    misku_kadastras["Miškų valstybės kadastras"]
%%    geoportalas["Geoportalas"]
%%    nekilnojamo_kadastras["Nekilnojamo turto kadastras"]
%%    uetk["UETK"]
end

am --> qgis
am --> admin

vstt --> qgis
vstt --> admin

visuomene --> public

aad --> admin
aaa --> admin

tiekejas --> web
gavejas --> web

api --> postgresql
public --> mariadb
api --> redis
api --> s3
api --> qgis
api --> vt
api --> remote

qgis --> postgresql

web --> api
public --> api
admin --> api
```

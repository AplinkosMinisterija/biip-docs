# Žuvų įveisimo informacinė sistema
Žuvų įveisimo informacinė sistema skirta rinkti, kaupti, analizuoti ir saugoti žuvų įveisimo duomenis. 

**Tikslas** – supaprastinti ir efektyvinti žuvų įveisimo procesą Lietuvoje.

**Auditorija** - ši informacinė sistema yra skirta asmenims, kurie privalo žuvinti Lietuvos vandens telkinius įstatymo nustatyta tvarka. 

**Kaupiami duomenys** - žuvinimo registracijos ir įžuvinimo fakto duomenys (įžuvinamų žuvų rūšys bei kiekiai), žuvų įveisimo naudotojai.

## Sistemą sudarančios aplinkos

- WordPress sistema - skirta administratoriams valdantiems svetainės turinį ir atvaizdavimą. Adresas išoriniams naudotojams: [zuvys.biip.lt](https://zuvys.biip.lt)
- Aplinka skirta sistemos administratoriams. Adresas administratoriams: [admin.biip.lt](https://admin.biip.lt), modulis Žuvinimas, bei Naudotojų valdymas (administruoti sistemos administratoriams bei naudotojams)

**Aplikacijos dizaino failai** - [Žuvų įveisimo aplikacija XD Formatu](design/zuvinimas_admin.xd), [Vidiniai naudotojai](design/vidiniai_naudotojai.xd)

### Autentifikuoto naudotojo funkcijos

- Teikia pranešimą apie planuojamą žuvų įveisimą;
- Pildo vykdomo žuvų įveisimo faktą;
- Administruoja narius.

### Aplinkos apsaugos gyvosios gamtos skyriaus vadovas

- Peržiūri žuvų įveisimo duomenis;
- Skiria atsakingą AAD pareigūną, kuris vyksta į žuvų įveisimo vietą;

### Autentifikuoto administratoriaus funkcijos

- Peržiūri žuvų įveisimo duomenis;
- Administruoja klasifikatorius (žuvų rūšys, žuvų amžius, vandes telkiniai, bendri nustatymai);
- Administruoja naudotojus.

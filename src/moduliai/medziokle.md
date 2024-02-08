# Medžioklės informacinė sistema
Medžioklės informacinė sistema skirta rinkti, kaupti, analizuoti ir saugoti sumedžiotų gyvūnų informaciją bei prašymus skirti medžiojamųjų gyvūnų sumedžiojimo limitus.

**Tikslas** - Užtikrinti efektyvų medžiotojų veiklą ir tikslius duomenis apie medžioklės rezultatus bei prašymus dėl sumedžiojimo limitų. Sistema siekiama skatinti atsakingą medžioklę.

**Auditorija** -  ši informacinė sistema skirta medžiotojams ir medžiotojų asociacijoms.

**Kaupiami duomenys** - medžioklių plotų ir jų naudotojų duomenys, limituojamų gyvūnų duomenys, sumedžiotų gyvūnų duomenys, medžioklių duomenys, medžiotojų duomenys.

## Sistemą sudarančios aplinkos

- WordPress sistema - skirta administratoriams valdantiems svetainės turinį ir atvaizdavimą. Adresas išoriniams naudotojams: [medziokle.biip.lt](https://medziokle.biip.lt)
- Aplinka skirta sistemos administratoriams. Adresas administratoriams: [admin.biip.lt](https://admin.biip.lt), modulis Medžioklė, bei Naudotojų valdymas (administruoti sistemos administratoriams bei naudotojams)
- Mobili aplikacija - skirta medžiotojams planuoti savo medžiokles, bei pildyti informaciją apie sumedžiotus gyvūnus, pildyti prašymą medžiojamų gyvūnų sumedžiojimo limitų suteikimui. [Google play](https://play.google.com/store/apps/details?id=com.mobile_medziotojas&pli=1), [App store](https://apps.apple.com/us/app/med%C5%BEiokl%C4%97s-%C5%BEurnalas/id1637595597)
- WEb aplikacija - skirta medžiotojamas planuoti, bei peržiūrėti informaciją apie sumedžiotus gyvūnus, pildyti prašymą medžiojamų gyvūnų sumedžiojimo limitų suteikimui. [medziokle.biip.lt/app](https://medziokle.biip.lt/app)

**Aplikacijos dizaino failai** - [Medžioklės web aplikacija XD Formatu](design/Medziokle%20-%20Admin.xd), [Medžioklės administratoriaus aplinka](design/Medziokle%20-%20WEB%20APP.xd), [Vidiniai naudotojai](design/Vidiniai%20naudotojai.xd)

### Neautentifikuoto naudotojo funkcijos

- Teikia informaciją apie didžiųjų plėšrūnų (vilkų, lūšių ir rudųjų lokių) bei stumbrų buvimą laisvėje Lietuvos Respublikos teritorijoje;
- Teikia pranešimą dėl medžiojamų laukinių gyvūnų padarytos žalos.

### Autentifikuoto naudotojo funkcijos mobilioje aplikacijoje

- Planuoja medžiokles;
- Registruoja sumedžiotus gyvūnus, pateikia daugiau inofrmacijos jei buvo sumedžiotas vilkas;
- Peržiūri sumedžiotų gyvūnų statistiką bei pildo prašymus skirti medžiojamųjų gyvūnų sumedžiojimo limitus;
- Vykdo medžiojamųjų gyvūnų apskaitą pagal pėdsakus sniege; 
- Administruoja narius.


### Autentifikuoto naudotojo funkcijos web aplikacijoje

- Planuoja medžiokles;
- Peržiūri sumedžiotų gyvūnų statistiką bei pildo prašymus skirti medžiojamųjų gyvūnų sumedžiojimo limitus;
- Administruoja narius.

### Autentifikuoto administratoriaus funkcijos

- Peržiūri šios  dienos vykstančias medžiokles;
- Administruoja medžioklės plotų vienetų informaciją;
- Administruoja medžioklės plotų naudotojus;
- Administruoja medžiotojų informaciją;
- Peržiūri sumedžiotų gyvūnų informaciją;
- Peržiūri ir tvirtina limitų prašymus;
- Administruoja klasifikatorius (gyvūnų rūšys, medžiojimo terminai, naudojimosi taisyklės);
- Administruoja detalios duomenų peržiūros leidimus.

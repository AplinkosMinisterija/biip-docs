# Invazinių rūšių informacinė sistema

Informacinė sistema skirta rinkti, kaupti ir dalintis informacija apie Lietuvoje aptinkamas invazines rūšis. Sistema suteikia galimybę vartotojams susipažinti su Lietuvoje ir Europos Sąjungoje įtrauktomis invazinėmis rūšimis, kurios turi būti naikinamos. Prisijungę asmenys ir identifikavę save per elektroninius valdžios vartus gali pateikti anketas apie pastebėtas invazines rūšis.

**Tikslas** – suteikti galimybę asmenims teikti informaciją apie pastebėtas invazines rūšis, suteikti galimybę gauti išrašą apie tam tikroje teritorijoje esančias invazines rūšis, suteikti galimybę susipažinti su invazinėmis rūšimis, kurios įtrauktos į Lietuvos arba Europos sąjungos sąrašus, ir būdais kaip jas naikinti.

**Auditorija** - ši sistema skirta visiems Lietuvos gyventojams, valstybės institucijoms, kurios rengia planus ir priemones invazinių rūšių naikinimui. Pagrindinė auditorija yra valstybinės institucijos, kurios gavusios išrašą galės planuotis kur ir kaip naikinti invazines rūšis.

**Kaupiami duomenys** - invazinių rūšių duomenys ir jų stebėjimo anketos, augaviečių bei radaviečių duomenys, naudotojų duomenys.

## Sistemą sudarančios aplinkos

- WordPress sistema - skirta administratoriams valdantiems svetainės turinį ir atvaizdavimą. Adresas išoriniams naudotojams: [inva.biip.lt](https://inva.biip.lt)
- Aplinka skirta autentifikuotiems asmenims pateikti bei gauti informaciją apie invazines rūšis. Taip pat aplinka skirta invazinių rūšių tikrintojams. Tiesioginis adresas: [rusys.biip.lt](https://rusys.biip.lt)
- Aplinka skirta sistemos administratoriams. Adresas administratoriams: [admin.biip.lt](https://admin.biip.lt), modulis Rūšių stebėjimas, bei Naudotojų valdymas(administruoti rūšių sistemos administratoriams bei naudotojams)

**Aplikacijos dizaino failai** - [Saugomų/Invazinių rūšių informacinė sistema XD formatu](../design/rusiu_stebejimas.xd), [Vidiniai naudotojai](../design/vidiniai_naudotojai.xd)

**Duomenų bazės struktūra** - [Duomenų bazės struktūra](../docs/rusiu_duomenu_bazes_struktura.pdf)


### Autentifikuoto naudotojo funkcijos
- Teikia anketą apie invazinę rūšį;
- Teikia prašymą gauti duomenis apie invazines rūšis;
- Teikia prašymą gauti prieigą žemėlapyje matyti ir saugomų rūšių radavietes;
- Teikia prašymą tapti invazinių rūšių tikrintoju;
- Peržiūri invazines rūšis žemėlapyje;
- Redaguoja savo profilio kontaktinę informaciją;
- Administruoja savo įmonės darbuotojus bei jų kontaktinę informaciją;
- Redaguoja savo įmonės kontaktinę informaciją.

### Autentifikuoto eksperto tikrintojo funkcijos
- Teikia anketą apie invazinę rūšį;
- Tikrina ir tvirtina kitų pateiktas anketas bei priskiria jau prie esančių radaviečių, jei yra tų rūšių ekspertas;
- Peržiūri visas invazinių rūšių radavietes;
- Teikia prašymą gauti išrašą apie invazines rūšis;
- Teikia prašymą norint tapti ekspertu naujoms invazinėms rūšims;
- Peržiūri rūšių klasifikatorių bei administruoja leidžiamą informaciją.

### Autentifikuoto administratoriaus funkcijos
- Stebėjimo anketoms priskiria/perskiria tikrintoją ekspertą;
- Tvirtina/atmeta gautus prašymus;
- Administruoja sistemos naudotojus;
- Administruoja klasifikatorius: rūšių, klasių, tipų, sąrašų, eunis buveinių, šaltinių.

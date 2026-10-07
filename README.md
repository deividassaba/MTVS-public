# MTVS-public

**Mokyklos tvarkaraščių valdymo sistema (MTVS)**

MTVS – tai mokyklos tvarkaraščių kūrimo, valdymo ir generavimo sistema, skirta supaprastinti mokyklos tvarkaraščių sudarymo procesą ir pakeisti dalį senesnių, rankiniu būdu atliekamų darbo procesų.

Šis viešas repozitoriumas skirtas **MTVS leidžiamoms diegimo versijoms ir naudotojo dokumentacijai**.

### Diegimas

1. Atsisiųskite naujausią `MTVS-Setup.exe` failą.
2. Paleiskite diegimo programą.
3. Vadovaukitės diegimo programos nurodymais.
4. Įdiegę programą paleiskite MTVS iš „Start“ meniu arba darbalaukio nuorodos.

> Jei „Windows“ pateikia saugos įspėjimą, patikrinkite, ar diegimo failas buvo atsisiųstas iš oficialios šio projekto GitHub saugyklos.

## Dokumentacija

Naudotojams ir sistemos administravimui skirta dokumentacija pateikiama atskirame faile:

**[MTVS dokumentacija](./MTVS-dokumentacija.pdf)**

Dokumentacijoje pateikiama informacija apie:

- sistemos paskirtį ir pagrindines funkcijas;
- programos diegimą ir paleidimą;
- pradinių duomenų importavimą;
- mokytojų, klasių, kabinetų ir kitų duomenų valdymą;
- tvarkaraščio apribojimų nustatymą;
- tvarkaraščio kūrimą ir generavimą;
- sugeneruoto tvarkaraščio peržiūrą ir eksportavimą;
- kitus pagrindinius sistemos naudojimo aspektus.

## Apie projektą

MTVS kuriama kaip mokyklos tvarkaraščių valdymo sistemos demonstracinė versija.

Pagrindinis sistemos naudotojas – **pavaduotojas ugdymui**, atsakingas už mokyklos tvarkaraščių sudarymą ir valdymą.

Sistema skirta naudoti **Windows** operacinėje sistemoje.

### Pagrindinės technologijos

- C#
- .NET 10
- WPF
- Entity Framework Core
- SQLite
- MVVM architektūros principai

### Pagrindinės funkcijos

- Mokyklos duomenų valdymas
- Duomenų importavimas iš CSV ir Excel failų
- Tvarkaraščių apribojimų kūrimas ir valdymas
- Tvarkaraščio generavimas
- Skirtingų generavimo algoritmų naudojimas
- Sugeneruoto tvarkaraščio tikrinimas pagal nustatytus apribojimus
- Tvarkaraščio eksportavimas
- HTML tvarkaraščio generavimas

## Repozitoriumai

Šis repozitoriumas skirtas tik viešai platinamai MTVS informacijai, diegimo failams ir dokumentacijai.

Programos kūrimo kodas laikomas atskirame repozitoriume.

## Sistemos reikalavimai

- Windows 10 arba naujesnė Windows versija
- x64 procesorius
- Pakankamai laisvos vietos programai ir jos duomenims

## Licencija

Projekto naudojimo ir platinimo sąlygos nurodytos repozitoriume pateikiamoje licencijoje.

## Autorius

**Deividas Sabaliauskas**

MTVS sukurta kaip praktinis projektas, skirtas mokyklos tvarkaraščių sudarymo ir valdymo procesui tobulinti.

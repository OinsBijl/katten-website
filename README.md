# index
# katten-website
een website voor katten

Titel en opmaak
html
Kopiëren
Bewerken
<head> ... </head>
Zet de titel van de pagina.

Linkt naar een stijlblad (style.css) voor kleuren en opmaak.

Hoofdtitel van de site
html
Kopiëren
Bewerken
<header>
  <h1>Enzo's Katten Winkel</h1>
</header>
Laat bovenaan de pagina een grote titel zien.

Menu (navigatie)
html
Kopiëren
Bewerken
<nav>
  <a href="index.html">Home</a>
  <a href="sub1.html">Menukaart</a>
  <a href="sub2.html">Kattenrassen</a>
  <a href="sub3.html">Contact</a>
</nav>
Hiermee kun je klikken naar andere pagina’s.

Welkomsttekst + afbeelding
html
Kopiëren
Bewerken
<p>Hallo, ik ben Enzo...</p>
<img src="ckat.png">
Tekst die uitlegt wat de site doet.

Een plaatje van een kat.

Informatie in 3 vakken
html
Kopiëren
Bewerken
<main>
  <div>Populaire katten</div>
  <div>Openings tijden</div>
  <div>Contact info</div>
</main>
Een lijst met kattenrassen.

De dagen dat de winkel open is.

Manieren om contact op te nemen.

Extra sluiting
html
Kopiëren
Bewerken
<section>
  <h3>Extra Sluitingsdag(en)</h3>
  <p>Geen zin</p>
</section>
Grappig bedoeld: de winkel is gesloten tot het jaar 3000.

Onderaan de pagina
html
Kopiëren
Bewerken
<footer>
  <p>&copy; 2025 Enzo's Katten Winkel</p>
</footer>
Laat copyright zien.

# sub1

Begin van de pagina
html
Kopiëren
Bewerken
<html lang="nl">
De website is in het Nederlands.

Informatie over de pagina (in <head>)
html
Kopiëren
Bewerken
<head>
  <title>Enzo's katten winkel</title>
  <link rel="stylesheet" href="style.css">
  <meta ...>
</head>
Titel van de pagina (bovenin je browser).

Stijlblad voor kleuren/opmaak.

Extra info over de site (auteur, zoekwoorden, omschrijving).

Bovenaan de pagina
html
Kopiëren
Bewerken
<header>
  <h1>Menukaart</h1>
</header>
Laat groot zien: "Menukaart".

Menu om te klikken
html
Kopiëren
Bewerken
<nav>
  <a href="index.html">Home</a>
  <a href="sub1.html"><b><u>Menukaart</u></b></a>
  <a href="sub2.html">Kattenrassen</a>
  <a href="sub3.html">Contact</a>
</nav>
Navigatieknoppen naar andere pagina’s.

Menukaart is vetgedrukt en onderstreept (actieve pagina).

De zichtbare inhoud
html
Kopiëren
Bewerken
<body>
  <div id="wrapper">
    <h2>Binnenkort beschikbaar</h2>
    <p>Deze pagina is verwacht af te zijn in het jaar 3000</p>
  </div>
</body>
Laat zien dat de menukaartpagina nog niet af is.

Gekke opmerking: pas klaar in het jaar 3000.

# sub2

Pagina-info bovenaan
html
Kopiëren
Bewerken
<html lang="nl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Enzo's Katten Winkel</title>
  <link rel="stylesheet" href="style.css">
</head>
De pagina is in het Nederlands.

Titel: Enzo's Katten Winkel (dit zie je in het tabblad).

Laadt een stijlblad voor de opmaak (style.css).

De kop van de pagina
html
Kopiëren
Bewerken
<header>
  <h1>Kattenrassen</h1>
</header>
Grote titel bovenaan: Kattenrassen.

Navigatie (menu)
html
Kopiëren
Bewerken
<nav>
  <a href="index.html">Home</a>
  <a href="sub1.html">Menukaart</a>
  <a href="sub2.html"><b><u>Kattenrassen</u></b></a>
  <a href="sub3.html">Contact</a>
</nav>
Klikmenu naar andere pagina’s.

“Kattenrassen” is vet en onderstreept (actieve pagina).

Hoofdinhoud van de pagina
html
Kopiëren
Bewerken
<main>
  <div id="wrapper">
    <h2>Onze Populaire Kattenrassen</h2>
    <ul> ... </ul>
    <p>Wil je een ras die hier niet staat? Laat het ons weten!</p>
  </div>
</main>
Titel: Onze Populaire Kattenrassen

Lijst van kattenrassen met korte uitleg:

Europese korthaar

Maine Coon

Brits korthaar

Siberische kat

Chinese naaktkat

Tekst onderaan: “Ken je een ander ras? Laat het weten!”

Voettekst (onderaan)
html
Kopiëren
Bewerken
<footer>
  <p>&copy; 2025 Enzo's Katten Winkel</p>
</footer>
Tekst met jaartal en naam van de winkel.

# sub3

Pagina-instellingen
html
Kopiëren
Bewerken
<html lang="nl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Enzo's Katten Winkel</title>
  <link rel="stylesheet" href="style.css">
</head>
De website is in het Nederlands.

Titel: Enzo's Katten Winkel (staat in je browser-tab).

Laadt een stijlbestand (CSS) voor kleuren en opmaak.

Titel bovenaan de pagina
html
Kopiëren
Bewerken
<header>
  <h1>Contact</h1>
</header>
Grote titel: Contact

Menu (navigatiebalk)
html
Kopiëren
Bewerken
<nav>
  <a href="index.html">Home</a>
  <a href="sub1.html">Menukaart</a>
  <a href="sub2.html">Kattenrassen</a>
  <a href="sub3.html"><b><u>Contact</u></b></a>
</nav>
Menu met links naar andere pagina's.

Contact is vet en onderstreept → je zit nu op die pagina.

Inhoud van de pagina
html
Kopiëren
Bewerken
<main>
  <div id="wrapper">
    <h2>Stuur ons een bericht!</h2>
    <p>Heb je vragen of suggesties? Neem contact met ons op via een van de onderstaande manieren.</p>
    <ul>
      <li><a href="https://www.instagram.com/">Instagram</a></li>
      <li><a href="https://nl-nl.facebook.com/">Facebook</a></li>
      <li><a href="https://mail.google.com/">Email</a></li>
      <li>Telefoon: 06-12345678</li>
    </ul>
  </div>
</main>
Titel: Stuur ons een bericht!

Korte uitleg over contact opnemen.

Lijstje met:

Link naar Instagram

Link naar Facebook

Link naar E-mail

Telefoonnummer

Onderkant (footer)
html
Kopiëren
Bewerken
<footer>
  <p>&copy; 2025 Enzo's Katten Winkel</p>
</footer>
Copyright

Jaar: 2025

Naam van de winkel

# style
Achtergrond van de pagina
css
Kopiëren
Bewerken
body {
   background-image: url('ak.png');
}
De achtergrond van de pagina krijgt een afbeelding: ak.png.

Standaard instellingen voor alles
css
Kopiëren
Bewerken
* {
  box-sizing: border-box;
}
Zorgt ervoor dat padding en borders netjes binnen elk element blijven. Handig voor opmaak.

Algemene stijlen voor de pagina
css
Kopiëren
Bewerken
body {
  font-family: Arial, sans-serif;
  margin: 20px;
  background-color: #fffabe;
  color: #333;
}
Lettertype: Arial

Tekstkleur: donkergrijs

Achtergrondkleur: lichtgeel

Ruimte rondom de pagina: 20px

Opmerking: Er zijn twee body-regels in de code. De laatste telt — dus background-image wordt overschreven door background-color: #fffabe.

Header (bovenste balk)
css
Kopiëren
Bewerken
header {
  background-color: #0368ff; /* blauw */
  color: white;
  padding: 20px;
  text-align: center;
}
Blauwe achtergrond

Witte tekst

Tekst staat in het midden

Ruimte rondom de tekst

Titel in de header
css
Kopiëren
Bewerken
header h1 {
  margin: 0;
}
Geen extra ruimte boven/onder de koptekst

Hoofdinhoud (main)
css
Kopiëren
Bewerken
main {
  margin-top: 20px;
  padding: 20px;
}
Ruimte bovenaan en binnenin het hoofdgedeelte

Container
css
Kopiëren
Bewerken
.container {
  display: flex;
  justify-content: space-between;
  margin: 20px 0;
}
Zet elementen naast elkaar (met flexbox)

Verdeling met ruimte ertussen

Navigatiebalk
css
Kopiëren
Bewerken
nav {
  text-align: center;
  margin-top: 10px;
  margin-bottom: 20px;
}

nav a {
  margin: 0 10px;
  text-decoration: none;
  color: #000;
  font-weight: bold;
}

nav a:hover {
  text-decoration: underline;
}
Menu staat in het midden

Links krijgen ruimte ertussen en zijn vetgedrukt

Als je met je muis over een link gaat: onderstreept

Lijstjes & formulieren
css
Kopiëren
Bewerken
ul {
  padding-left: 20px;
}

label {
  display: block;
  margin-top: 10px;
}

input, textarea {
  width: 100%;
  padding: 6px;
  margin-top: 4px;
  font-size: 1rem;
}
Lijstjes krijgen inspringing

Formulieren zijn netjes uitgelijnd en volledige breedte

Knoppen
css
Kopiëren
Bewerken
button {
  margin-top: 15px;
  background-color: #0368ff;
  color: white;
  border: none;
  padding: 10px 15px;
  cursor: pointer;
  font-size: 1rem;
}

button:hover {
  background-color: #0051c9;
}
Blauwe knop, witte tekst

Geen rand

Als je erover zweeft: donkerblauw

Wrapper (centrale inhoud)
css
Kopiëren
Bewerken
#wrapper {
  width: 1200px;
  margin: auto;
}
Inhoud staat in het midden van de pagina

Maximale breedte: 1200px

Samenvatting:
Deze CSS regelt:

Achtergrond, kleuren, lettertype

Opmaak van header, navigatie, knoppen, formulieren

Flexibele indeling met .container

Centrale layout met #wrapper

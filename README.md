> _Fork_ deze deeltaak en ga aan de slag. De instructie vind je in: [docs/INSTRUCTIONS.md](docs/INSTRUCTIONS.md)


# All human WCAG Audit 

## Inhoudsopgave
* Beschrijving
* Kenmerken
* Conclusie
* Licentie

## Beschrijving

Het is belangrijk dat een website goed accessible is. Ik heb de website van het Mediacollege Amsterdam getest. Dit is mijn oude school. Ik wilde deze graag onderzoeken om te kijken of er op opleidingen goed gekeken wordt naar of hun website goed toegankelijk is.
<br><img width="1392" alt="Schermafbeelding 2022-11-02 om 08 42 27" src="https://user-images.githubusercontent.com/112861144/199451703-4ee0816a-e495-4f00-9b4f-133ba2bb8bd2.png">
<br>Op deze website heb ik een handmatige test gedaan, en een lighthouse test. Uit deze lighthouse test is gebleken dat deze website een accessibility heeft van 77. Dit kan zeker nog beter.
<br><img width="1439" alt="Schermafbeelding 2022-10-24 om 09 56 53" src="https://user-images.githubusercontent.com/112861144/199451816-9d048f69-df0e-4c9e-af0a-f76f0300fd3a.png">

## Kenmerken

De lighthouse test kijkt onder andere naar de kleurcontrasten en of de HTML goed is geschreven. Bij de handmatige tests wordt er vooral gekeken naar of de website goed te bedienen is met het het toetsenbord en een screenreader.

## Conclusie

De website mag de user-scalable="no" in het -element niet gebruiken omdat het tekstschalen en zoomen uitschakelt, wat essentieel is voor gebruikers met een slecht gezichtsvermogen. Dit is op te lossen door de parameter user-scalable="no" uit het content-attribuut van het element te verwijderen. Zo maak je zoomen mogelijk. Dit zorgt ervoor dat de variabele voor de maximale schaal niet kleiner is dan 2. Het contrast tussen de voor-en achtergrond is te laag. De kleuren moeten dus worden aangepast om meer contrast te krijgen. De links hebben geen goede naam die de link omschrijft. Links moeten een tekst of beschrijving bevatten in het alt-label attribuut. Dit moet vanwege toegankelijkheidsredenen (vereist voor screenreaders). Er moet dus een alt-label komen met een duidelijke beschrijving van waar de link naartoe verwijst. Op de manier hoe de headings nu zijn neergezet wordt navigeren op een webpagina verwarrender gemaakt voor gebruikers. Koppen moeten in een geldige logische volgorde staan, wat betekent dat h1 tot en met h6 element-tags in een opeenvolgend aflopende volgorde moeten staan. Hierdoor kun je makkelijker navigeren. Om dit probleem op te lossen moeten de headings dus op een geldige logische volgorde staan.

## Licentie

![GNU GPL V3](https://www.gnu.org/graphics/gplv3-127x51.png)

This work is licensed under [GNU GPLv3](./LICENSE).

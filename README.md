# Eindopdracht Javascript Advanced: Filmzoeker 

[Screenshots van Filmzoeker](#screenshots)

## Introductie

Je gaat een een filmzoeker maken!

In dit project ga je een overzicht maken van verschillende films. Over de database hoef je je (nog) geen zorgen te maken! Die hebben wij voor je gemaakt.

Er zitten een aantal films in de database die de gebruiker moet kunnen filteren dmv een aantal filterbuttons. De film naar keuze kan de gebruiker dan vervolgens vinden op IMDB. 

## Requirements

Aan deze eisen moet jouw project voldoen:


1. Als gebruiker wil ik een lijst kunnen zien van de beschikbare films **met de poster van de film**.
    * Check de data: elke film in de database heeft een link naar de juiste poster.
2. Als gebruiker wil ik bovenaan de pagina kunnen klikken op 5 verschillende filters in de vorm van radio-buttons. De filter functionaliteit wordt hieronder verder toegelicht.
3. Als gebruiker kan ik maar 1 filter tegelijk gebruiken.
    * Als ik een ander filter aanklik gaat het andere filter dus weer uit. (Hence de **radiobutton** (1 antwoord mogelijk), in tegenstelling tot een checkbox (meerdere antwoorden mogelijk).
4. Categorie 1: Als gebruiker wil ik kunnen filteren op de categorie **nieuwste films**: van de laatste jaren, dat betekent 2014 of nieuwer.
5. Categorie 2: Als gebruiker wil ik kunnen filters op films met **"Avengers"** in de titel.
6. Categorie 3: Als gebruiker wil ik kunnen filteren op films met **"X-Men"** in de titel.
7. Categorie 4: Als gebruiker wil ik kunnen filteren op films met **"Princess"** in de titel.
8. Categorie 5: Als gebruiker wil ik kunnen filteren op films met **"Batman"** in de titel.
    * Gebruik arraymethods voor je filters
    * Check of een gedeelte van een string in een andere string aanwezig is met de .includes() method.
    *  De laatste 4 filters lijken heel veel op elkaar. Heb je daar meerdere functies voor nodig? Kan het ook in 1?
9. Als gebruiker kan ik op de poster van de film klikken, waardoor ik naar de juiste IMDB pagina wordt gebracht.
     * IMDB werkt met een `id` per film/serie in de URL. Deze ids vind je ook weer terug in onze filmdatabase. Zie bijvoorbeeld: https://www.imdb.com/title/tt0944947/ Pas de URL van IMDB aan en plak het juiste ID erachter.

## Bonus Requirements 

1. Als gebruiker kan ik in een inputfield de titel van een film invullen, wanneer ik op enter druk worden de films gefilterd op de titel die ik heb ingevuld.

**Focus je eerst op de functionaliteiten en JavaScript, voordat je gaat beginnen met stylen.**

## Screenshots:

### Filmzoeker
![Eindopdracht Filmzoeker](./screenshot-eindopdracht-filmzoeker.png)

### Filmzoeker filter
![Eindopdracht Filmzoeker Filter](./screenshot-eindopdracht-filmzoeker-filter.png)

### Filmzoeker zoeken
![Eindopdracht Filmzoeker Zoeken](./screenshot-eindopdracht-filmzoeker-zoeken.png)
### Filmzoeker responsive
![Eindopdracht Filmzoeker responsive](./screenshot-eindopdracht-filmzoeker-responsive.png)


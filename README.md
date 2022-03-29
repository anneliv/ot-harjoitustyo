**Viikko 1.**
[Viikon materiaali](https://ohjelmistotekniikka-hy.github.io/java/viikko1)
 - [komentorivi.txt](https://github.com/anneliv/ot-harjoitustyo/blob/main/laskarit/viikko1/komentorivi.txt)
 - [gitlog.txt](https://github.com/anneliv/ot-harjoitustyo/blob/main/laskarit/viikko1/gitlog.txt)

# Alustava määrittelydokumentti
päivitys hankaluuksia, korjaan formaatin myöhemmin

## Sovelluksen tarkoitus 
-Niin sanottu klikkeri-peli: rekisteröinyt käyttäjä klikkaa nappulaa niin kauan kuin jaksaa. Paras tulos tallennetaan käyttäjän profiiliin. 
## Käyttäjä 
Alustavasti yksi käyttäjärooli eli normaalikäyttäjä. 
## Suunnitellut toiminnallisuudet 
- käyttäjätunnuksen luominen (pituus väh. 3, yksilöllisyys tarkistetaan) 
- sisäänkirjautuminen (järjestelmä tarkistaa käyttäjätunnuksen olemassa olon) 
- sovellus ilmoittaa, jos käyttäjätunnusta ei löydy 
- sisäänkirjautumisen jälkeen käyttäjä voi... 
  - pelata eli klikata nappulaa 
  - nähdä oman parhaan tuloksen 
  - nähdä TOP 3 ranking listan 
 - pelaaminen: 
   - Pelaaja klikkaa nappulaa niin kauan kuin jaksaa. Pelaajan kasvava tulos näkyy samaan aikaan. 
   - Mahdollinen aikaraja: jos pelaaja ei klikkaa nappulaa 5 sekuntiin, pelikierros loppuu. 
   - Alustavasti erillinen lopeta-nappi, joka lopettaa pelikierroksen. Jos sovellus suljetaan ennen, tulosta ei tallenneta. 
   - Pelikierroksen lopussa: jos tulos on käyttäjän paras, se tallentuu käyttäjän profiiliin. 
   - Jos tulos on parempi kuin ranking listalla, se sijoitetaan listalle ja syrjäyttää listan huonoimman tuloksen. 
## Mahdollisia lisäyksiä 
- kirjautuessa vaadittava käyttäjä salasana 
- kuva nappulaan ja ääniefekti klikkaukseen 
- käyttäjäprofiiliin käyttäjän klikkausten kokonaismäärä, käytetty aika 

 
